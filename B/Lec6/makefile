all: prb6.pdf ans6.pdf

prb6.pdf: prb6.dvi
	dvipdfmx -p a4 prb6.dvi 
prb6.dvi: prb6.tex fig1.eps fig2.eps 
	platex prb6.tex 

ans6.pdf: ans6.dvi
	dvipdfmx -p a4 ans6.dvi 
ans6.dvi: ans6.tex fig1ans.eps fig2ans.eps fig3ans.eps fig4ans.eps
	platex ans6.tex 

fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig2.eps: fig2.svgz
	inkscape -z -f fig2.svgz -E fig2.eps
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
fig2ans.eps: fig2ans.svgz
	inkscape -z -f fig2ans.svgz -E fig2ans.eps
fig3ans.eps: fig3ans.svgz
	inkscape -z -f fig3ans.svgz -E fig3ans.eps
fig4ans.eps: fig4ans.svgz
	inkscape -z -f fig4ans.svgz -E fig4ans.eps
