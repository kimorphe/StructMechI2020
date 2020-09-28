all: prb5.pdf ans5.pdf

prb5.pdf: prb5.dvi
	dvipdfmx -p a4 prb5.dvi

ans5.pdf: ans5.dvi
	dvipdfmx -p a4 ans5.dvi

prb5.dvi: prb5.tex fig1.eps fig2.eps 
	platex prb5.tex
ans5.dvi: ans5.tex fig1ans.eps fig2_2ans.eps fig3ans.eps
	platex ans5.tex

fig1.eps:fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig2.eps:fig2.svgz
	inkscape -z -f fig2.svgz -E fig2.eps
fig1ans.eps:fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
fig2_2ans.eps:fig2_2ans.svgz
	inkscape -z -f fig2_2ans.svgz -E fig2_2ans.eps
fig3ans.eps:fig3ans.svgz
	inkscape -z -f fig3ans.svgz -E fig3ans.eps
