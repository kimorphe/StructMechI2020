all: prb3.pdf ans3.pdf

prb3.pdf: prb3.dvi
	dvipdfmx -p a4 prb3.dvi

ans3.pdf: ans3.dvi
	dvipdfmx -p a4 ans3.dvi

prb3.dvi: prb3.tex fig1.eps
	platex prb3.tex
ans3.dvi: ans3.tex fig1ans.eps fig2ans.eps
	platex ans3.tex


fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
fig2ans.eps: fig2ans.svgz
	inkscape -z -f fig2ans.svgz -E fig2ans.eps
