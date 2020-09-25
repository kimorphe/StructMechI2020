summary4.pdf:	summary4.dvi
	dvipdfmx -p a4 summary4.dvi
summary4.dvi:	summary4.tex fig7_0.eps fig7_1.eps fig7_2.eps fig7_3.eps fig7_4.eps fig7_5.eps fig8_1.eps 
	platex summary4.tex

fig7_0.eps: fig7_0.svgz
	inkscape -z -f fig7_0.svgz -E fig7_0.eps
fig7_1.eps: fig7_1.svgz
	inkscape -z -f fig7_1.svgz -E fig7_1.eps
fig7_2.eps: fig7_2.svgz
	inkscape -z -f fig7_2.svgz -E fig7_2.eps
fig7_3.eps: fig7_3.svgz
	inkscape -z -f fig7_3.svgz -E fig7_3.eps
fig7_4.eps: fig7_4.svgz
	inkscape -z -f fig7_4.svgz -E fig7_4.eps
fig7_5.eps: fig7_5.svgz
	inkscape -z -f fig7_5.svgz -E fig7_5.eps
fig8_1.eps: fig8_1.svgz
	inkscape -z -f fig8_1.svgz -E fig8_1.eps
