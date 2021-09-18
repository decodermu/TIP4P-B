# TIP4P-B
new balanced solvent model for both IDPs and folded proteins
## parameter files
Suppose $AMBERHOME is the amber installation path   
Then put file "leaprc.water.tip4pb" into directory "$AMBERHOME/dat/leap/cmd/";   
put file "frcmod.tip4pb" into directory "$AMBERHOME/dat/leap/parm/";   
put file "tip4pb.off" into directory "$AMBERHOME/dat/leap/lib";  
## tleap.in usage
see "tleap_example.in" for how to use TIP4P-B for MD simulation
