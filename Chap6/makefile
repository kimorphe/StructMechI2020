summary6.pdf: summary6.dvi
	dvipdfmx -p a4 summary6.dvi

summary6.dvi: summary6.tex fig9_0.eps fig9_1.eps fig9_2.eps fig9_3.eps fig9_4.eps fig9_5.eps fig9_6.eps
	platex summary6.tex

fig9_0.eps: fig9_0.svgz
	inkscape -z -f fig9_0.svgz -E fig9_0.eps
fig9_1.eps: fig9_1.svgz
	inkscape -z -f fig9_1.svgz -E fig9_1.eps
fig9_2.eps: fig9_2.svgz
	inkscape -z -f fig9_2.svgz -E fig9_2.eps
fig9_3.eps: fig9_3.svgz
	inkscape -z -f fig9_3.svgz -E fig9_3.eps
fig9_4.eps: fig9_4.svgz
	inkscape -z -f fig9_4.svgz -E fig9_4.eps
fig9_5.eps: fig9_5.svgz
	inkscape -z -f fig9_5.svgz -E fig9_5.eps
fig9_6.eps: fig9_6.svgz
	inkscape -z -f fig9_6.svgz -E fig9_6.eps
