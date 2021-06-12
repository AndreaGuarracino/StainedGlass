## configuration info 
```
sample: small
fasta: test/small.fasta
### Additional options 
# Size of the windows used in alignment
window: 5000 
# The number of batches to split alignment jobs across
nbatch: 100 
# The number of alignment threads per batch
alnthreads: 4 
# Setting for the minimap2 -f parameter
mm_f: 10000 
# Path for a temp dir to be used by pipeline
tempdir: temp 
```