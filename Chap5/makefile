summary5.pdf: summary5.dvi
	dvipdfmx -p a4 summary5.dvi

summary5.dvi: summary5.tex fig8_2.eps fig8_3.eps fig8_4.eps
	platex summary5.tex

fig8_2.eps: fig8_2.svgz
	inkscape -z -f fig8_2.svgz -E fig8_2.eps
fig8_3.eps: fig8_3.svgz
	inkscape -z -f fig8_3.svgz -E fig8_3.eps
fig8_4.eps: fig8_4.svgz
	inkscape -z -f fig8_4.svgz -E fig8_4.eps
