summary1.pdf:	summary1.dvi
	dvipdfmx -p a4 summary1.dvi

summary1.dvi: summary1.tex ploads.eps bar1d.eps axial_force.eps ex1_disp.eps ex2_strain.eps ex3_force.eps ex3_force2.eps ex4_ODE.eps
	platex summary1.tex

ploads.eps:	ploads.svgz
	inkscape  -z -f ploads.svgz -E ploads.eps
bar1d.eps:	ploads.svgz
	inkscape  -z -f bar1d.svgz -E bar1d.eps
axial_force.eps:	axial_force.svgz
	inkscape  -z -f axial_force.svgz -E axial_force.eps
ex1_disp.eps:	ex1_disp.svgz
	inkscape  -z -f ex1_disp.svgz -E ex1_disp.eps
ex2_strain.eps:	ex2_strain.svgz
	inkscape  -z -f ex2_strain.svgz -E ex2_strain.eps
ex3_force.eps:	ex3_force.svgz
	inkscape  -z -f ex3_force.svgz -E ex3_force.eps
ex3_force2.eps:	ex3_force2.svgz
	inkscape  -z -f ex3_force2.svgz -E ex3_force2.eps
ex4_ODE.eps:	ex4_ODE.svgz
	inkscape  -z -f ex4_ODE.svgz -E ex4_ODE.eps
