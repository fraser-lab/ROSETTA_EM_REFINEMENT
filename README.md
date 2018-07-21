# ROSETTA_EM_REFINEMENT
Scripts for EM Refinement in Rosetta

launch_rosetta_local.py - defines an area for intensive sampling (in script, probably should move to arguments)
launch_rosetta_global.py - is essentially the tutorial commands for a global refinement

Thanks to Gabe Lander and Mark Herzik (esp for density weighting) and Ray Wang (for other advice)

# Dealing with Lys acetylation
(adapted from https://www.rosettacommons.org/demos/latest/public/patched_residue_types_in_centroid-fullatom_protocols/README)

move lys_acetylated.txt to database/chemical/residue_type_sets/centroid/patches/lys_acetylated.txt

add the line:
patches/lys_acetylated.txt
into
database/chemical/residue_type_sets/centroid/patches.txt

Edit Residue Name from ALY to LYS

# Other notes:
make sure chains are A not 1A
remove Mg and GTP (there are tutorials for dealing with this on DiMaio website)

-ignore_unrecognized_res flag has been removed from rosetta_scripts command
