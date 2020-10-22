all: prb7.pdf ans7.pdf

prb7.pdf: prb7.dvi
	dvipdfmx -p a4 prb7.dvi 
prb7.dvi: prb7.tex fig2.eps
	platex prb7.tex 
ans7.pdf: ans7.dvi
	dvipdfmx -p a4 ans7.dvi 
ans7.dvi: ans7.tex fig1ans.eps fig2ans.eps
	platex ans7.tex 

fig2.eps: fig2.svgz
	inkscape -z -f fig2.svgz -E fig2.eps
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
fig2ans.eps: fig2ans.svgz
	inkscape -z -f fig2ans.svgz -E fig2ans.eps
