summary2.pdf: summary2.dvi
	dvipdfmx -p a4 summary2.dvi
summary2.dvi: summary2.tex Qth_example.eps ex5_Torque.eps ex6_Mohr.eps fig3_1.eps fig3_2.eps fig3_3.eps fig3_4.eps fig3_5.eps fig4-1.eps fig4-2.eps fig4_1.eps fig4_2.eps fig4_3.eps fig5_1.eps fig5_2.eps
	platex summary2.tex

fig3_1.eps: fig3_1.svgz
	inkscape -z -f fig3_1.svgz -E fig3_1.eps
fig3_2.eps: fig3_2.svgz
	inkscape -z -f fig3_2.svgz -E fig3_2.eps
fig3_3.eps: fig3_3.svgz
	inkscape -z -f fig3_3.svgz -E fig3_3.eps
fig3_4.eps: fig3_4.svgz
	inkscape -z -f fig3_4.svgz -E fig3_4.eps
fig3_5.eps: fig3_5.svgz
	inkscape -z -f fig3_5.svgz -E fig3_5.eps
fig4_1.eps: fig4_1.svgz
	inkscape -z -f fig4_1.svgz -E fig4_1.eps
fig4-1.eps: fig4-1.svgz
	inkscape -z -f fig4-1.svgz -E fig4-1.eps
fig4_2.eps: fig4_2.svgz
	inkscape -z -f fig4_2.svgz -E fig4_2.eps
fig4-2.eps: fig4-2.svgz
	inkscape -z -f fig4-2.svgz -E fig4-2.eps
fig4_3.eps: fig4_3.svgz
	inkscape -z -f fig4_3.svgz -E fig4_3.eps
fig5_1.eps: fig5_1.svgz
	inkscape -z -f fig5_1.svgz -E fig5_1.eps
fig5_2.eps: fig5_2.svgz
	inkscape -z -f fig5_2.svgz -E fig5_2.eps
Qth_example.eps: Qth_example.svgz
	inkscape -z -f Qth_example.svgz -E Qth_example.eps
ex5_Torque.eps: ex5_Torque.svgz
	inkscape -z -f ex5_Torque.svgz -E ex5_Torque.eps
ex6_Mohr.eps: ex6_Mohr.svgz
	inkscape -z -f ex6_Mohr.svgz -E ex6_Mohr.eps
