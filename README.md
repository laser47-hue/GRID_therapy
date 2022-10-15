# GRID_therapy
Development Of GRID Therapy Capabilities On The XRAD Pre-clinical Radiotherapy System

# Project Abstract 

GRID therapy, a form of spatially fractionated radiation therapy (SFRT) strays from the
conventional approach of uniformly irradiating a tumour by intentionally producing a het-
erogeneous dose distribution within the target volume. This area of research is attracting
growing attention because it has proven to be an effective alternative to conventional
radiation therapy in specific clinical and preclinical settings. To date, preclinical research
on this topic has mostly focused on the production and dosimetric evaluation of various
grid collimators without implementation into a treatment planning system. This work
describes the approach to producing and implementing various grid collimators into the
XRAD preclinical radiotherapy system. The grids were manufactured by casting a low
melting point alloy, Cerrobend into a silicone mould. The silicone was moulded around a
3d printed replica of each grid which allowed diverging holes of various radii and spacing
to be investigated. A Monte Carlo simulation on an equivalent 3d model was performed
for each manufactured grid. By incorporating these simulations into the XRAD treat-
ment planning system, the dose distribution in complex geometries such as small animal
patients can be analysed. The incorporation of the grid collimators into a treatment
planning system can significantly improve the practicality of these grids. This work pro-
vides the potential for further research into the biological implications of grid therapy,
facilitated by accurate complex dose distributions. Our method could also be applied in
a clinical setting.

# Prerequisites
See https://github.com/nrc-cnrc/EGSnrc to download the EGSnrc package

A few Code Modifications of the EGSnrc package is needed for the input files provided to work.
1.  The density correction files provided have to be placed in the folder $HEN_HOUSE/pegs4/density_corrections/compounds/  ie. cp density_files/* $HEN_HOUSE/pegs4/density_corrections/compounds/. from within this github folder
2.  The max_stack size has to be increased to 7000000 in the array_sizes.h file in the application you will be using (eg. tutor7pp)


# .egsinp files
The collimator files are designed to be used in the tutor7pp package of the C++ AdvancedApplication app in egsnrc package. The collimators are described in further detail in the .egsinp files

### 10 mm at isocentre XRAD collimator

![10mm_col](https://user-images.githubusercontent.com/63790873/195986300-210e76a5-4fc6-4c50-b10c-92a13f80ca4e.png)


### GRID XRAD collimator

![GRID](https://user-images.githubusercontent.com/63790873/195986321-f94cdcc5-620c-4ca3-a560-a46fea51eff7.png)



# Film Results
To see film results see the paper doi: _________________

# Support 
Please contact me via github for any inquiries

# Contributing
You can contribute to this work. 

