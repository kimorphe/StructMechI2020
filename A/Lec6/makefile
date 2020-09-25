all: prb6.pdf ans6.pdf

prb6.pdf: prb6.dvi
	dvipdfmx -p a4 prb6.dvi 
prb6.dvi: prb6.tex fig1.eps
	platex prb6.tex 
ans6.pdf: ans6.dvi
	dvipdfmx -p a4 ans6.dvi 
ans6.dvi: ans6.tex fig1.eps
	platex ans6.tex 

fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
