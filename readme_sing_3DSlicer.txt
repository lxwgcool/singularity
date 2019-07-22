1: How to create a singularity container (sandbox)
$sudo singularity build --sandbox ./3DSlicer.ssb ../singularity_3DSlicer.recipe

2: How to run 3DSlicer with singularity container
$singularity exec ./3DSlicer.ssb/ /home/software/3DSlicer/Slicer-4.10.2-linux-amd64/Slicer

3: The version of Singularity i used in this testing case
v 2.5.2-dist (Ubuntu)
v 3.1 (Redhat)




