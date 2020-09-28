summary8.pdf: summary8.dvi
	dvipdfmx -p a4 summary8.dvi

summary8.dvi: summary8.tex fig10_1.eps fig10_2.eps fig10_3.eps fig11_1.eps fig11_2.eps fig11_3.eps fig11_4.eps
	platex summary8.tex

fig10_1.eps: fig10_1.svgz
	inkscape -z -f fig10_1.svgz -E fig10_1.eps
fig10_2.eps: fig10_2.svgz
	inkscape -z -f fig10_2.svgz -E fig10_2.eps
fig10_3.eps: fig10_3.svgz
	inkscape -z -f fig10_3.svgz -E fig10_3.eps

fig11_1.eps: fig11_1.svgz
	inkscape -z -f fig11_1.svgz -E fig11_1.eps
fig11_2.eps: fig11_2.svgz
	inkscape -z -f fig11_2.svgz -E fig11_2.eps
fig11_3.eps: fig11_3.svgz
	inkscape -z -f fig11_3.svgz -E fig11_3.eps
fig11_4.eps: fig11_4.svgz
	inkscape -z -f fig11_4.svgz -E fig11_4.eps
