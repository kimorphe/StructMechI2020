summary7.pdf: summary7.dvi
	dvipdfmx -p a4 summary7.dvi

summary7.dvi: summary7.tex fig10_1.eps fig10_1_1.eps fig10_2.eps fig10_2_1.eps fig10_2_2.eps fig10_3.eps fig10_3_1.eps fig10_4.eps
	platex summary7.tex

fig10_1.eps: fig10_1.svgz
	inkscape -z -f fig10_1.svgz -E fig10_1.eps
fig10_1_1.eps: fig10_1_1.svgz
	inkscape -z -f fig10_1_1.svgz -E fig10_1_1.eps
fig10_2.eps: fig10_2.svgz
	inkscape -z -f fig10_2.svgz -E fig10_2.eps
fig10_2_1.eps: fig10_2_1.svgz
	inkscape -z -f fig10_2_1.svgz -E fig10_2_1.eps
fig10_2_2.eps: fig10_2_2.svgz
	inkscape -z -f fig10_2_2.svgz -E fig10_2_2.eps
fig10_3.eps: fig10_3.svgz
	inkscape -z -f fig10_3.svgz -E fig10_3.eps
fig10_3_1.eps: fig10_3_1.svgz
	inkscape -z -f fig10_3_1.svgz -E fig10_3_1.eps
fig10_4.eps: fig10_4.svgz
	inkscape -z -f fig10_4.svgz -E fig10_4.eps
