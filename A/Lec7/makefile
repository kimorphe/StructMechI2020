all: prb7.pdf ans7.pdf

prb7.pdf: prb7.dvi
	dvipdfmx -p a4 prb7.dvi 
prb7.dvi: prb7.tex fig1.eps
	platex prb7.tex 
ans7.pdf: ans7.dvi
	dvipdfmx -p a4 ans7.dvi 
ans7.dvi: ans7.tex fig1ans.eps
	platex ans7.tex 

fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
