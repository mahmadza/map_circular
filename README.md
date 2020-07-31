# map_circular
a short reads mapper to circular genome

Problem statement:
There is no (at the time of project conception) good and publicly available short reads mapper to circular genome.
The standard practice has been to cut the genome to be linear, and map the reads there.
This could be a problem, as paired-end reads that span the cut position will not be mapped properly, or even mapped at all.
