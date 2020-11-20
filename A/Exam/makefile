all: exam.pdf ans.pdf

exam.pdf: exam.dvi
	dvipdfmx -p a4 exam.dvi 
exam.dvi: exam.tex fig1.eps fig2.eps
	platex exam.tex 
ans.pdf: ans.dvi
	dvipdfmx -p a4 ans.dvi 
ans.dvi: ans.tex fig1ans.eps fig2ans.eps
	platex ans.tex 

fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
fig1ans.eps: fig1ans.svgz
	inkscape -z -f fig1ans.svgz -E fig1ans.eps
fig2.eps: fig2.svgz
	inkscape -z -f fig2.svgz -E fig2.eps
fig2ans.eps: fig2ans.svgz
	inkscape -z -f fig2ans.svgz -E fig2ans.eps
