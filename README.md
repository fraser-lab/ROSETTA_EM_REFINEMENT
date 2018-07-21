# ROSETTA_EM_REFINEMENT
Scripts for EM Refinement in Rosetta


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
