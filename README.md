# ANYstructure #
ANYstructure is the ultimate steel structure design tool for plate fields and cylinders! 
Weight optimization for all structures with machine learning capabilities. 
Calculations are based on DNV standards and rules
### What's new in 4.10 ###
* Corrected minor bug on membrane stresses for unstiffened cylinder.
### What's new in 4.9.1 ###
* Corrected bug in loading old save files
* Corrected error on buckling flat plate calculation
### What's new in 4.8 ###
* Reporting table on cylinders.
* Color coding on come cylinder properties.
* Corrected error on additional hoop stress input for cylinders.
### What's new in 4.7 ###
* Corrected error on girder caluculation for cylinder buckling.
* Added 1.10 load factor option for cylinder buckling.
* Better compability with linux.
* Python 3.11 based.
### What's new in 4.4 ###
* Backup and restore feature added.
### What's new in 4.3 ###
* General stability.
* User friendliness.
### What's new in 4.2 ###
* Bug fixing.
* Ukraininan theme.
### What's new in 4.0 ###
* Cylinder design and optimization!
* Flat plate prescriptive buckling improved. Girder calculation added.
* Updated GUI with color themes.
### What's new in 3.3 ###
* Extremely efficient Machine Learning version of PULS called ML-CL. Implemented for all optimizer options.
* Calculation of Center of Gravity and Center of Buoyancy.
* Reporting of weights and COG.
* Lots of bug fixes.

------------------------------------------------------------------------

## The following is calculated: ##
* Minimum plate thickness (DNV-OS-C101)
* Minimum section modulus of stiffener/plate (DNVGL-OS-C101)
* Minimum shear area (DNVGL-OS-C101)
* Buckling (DNVGL-RP-C201)or PULS (licenced DNV software)
* Buckling strength of shells DNV-RP-C202
* PULS buckling (DNV license needed)
* Machine learning buckling, PULS based
* Fatigue for plate/stiffener connection (DNVGL-RP-C203)

Compartments (tank pressures) are created automatically.

Pressures on external hull (or any other generic location) is defined by specifying equations.

You can optimize cylinders, single plate/stiffener field or multiple. Geometry of double bottom can be optimized.
