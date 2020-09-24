all: prb1.pdf ans1.pdf

prb1.pdf: prb1.dvi
	dvipdfmx -p a4 prb1.dvi
ans1.pdf: ans1.dvi
	dvipdfmx -p a4 ans1.dvi

prb1.dvi: prb1.tex fig1.eps fig2.eps
	platex  prb1.tex
fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig2.eps: fig2.svgz
	inkscape -z -f fig2.svgz -E fig2.eps

ans1.dvi: ans1.tex fig1ans.eps fig2ans.eps
	platex  ans1.tex
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
fig2ans.eps: fig2ans.svgz
	inkscape -z -f fig2ans.svgz -E fig2ans.eps
