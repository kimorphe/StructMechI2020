all: prb2.pdf ans2.pdf

prb2.pdf: prb2.dvi
	dvipdfmx -p a4 prb2.dvi
prb2.dvi: prb2.tex fig1.eps
	platex prb2.tex
fig1.eps: fig1.svgz 
	inkscape -z -f fig1.svgz -E fig1.eps


ans2.pdf: ans2.dvi
	dvipdfmx -p a4 ans2.dvi
ans2.dvi: ans2.tex fig1ans.eps
	platex ans2.tex
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps

