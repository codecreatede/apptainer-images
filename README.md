apptainer-cpat

- apptainer images for the cpat
- to build the image
 
```
apptainer build cpat.sif apptainer.def
```
- to inspect the image
```
apptainer inspect cpat.sif
```
- to run the apptainer image 
```
apptainer exec cpat.sif cpat 
```
- to run on the computing cluster with the singularity installed
```
module load singularity
```

Gaurav Sablok
