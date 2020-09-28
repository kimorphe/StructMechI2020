all: prb4.pdf ans4.pdf

prb4.pdf: prb4.dvi
	dvipdfmx -p a4 prb4.dvi

ans4.pdf: ans4.dvi
	dvipdfmx -p a4 ans4.dvi

prb4.dvi: prb4.tex fig1.eps
	platex prb4.tex
ans4.dvi: ans4.tex fig1ans.eps 
#fig2ans.eps
	platex ans4.tex


fig1.eps:fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig1ans.eps:fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
#fig2ans.eps:fig2ans.svgz
#	inkscape -z -f fig2ans.svgz -E fig2ans.eps
