all: prb5.pdf ans5.pdf

prb5.pdf: prb5.dvi
	dvipdfmx -p a4 prb5.dvi

ans5.pdf: ans5.dvi
	dvipdfmx -p a4 ans5.dvi

prb5.dvi: prb5.tex 
	platex prb5.tex
ans5.dvi: ans5.tex fig1ans.eps
	platex ans5.tex

fig1ans.eps:fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
