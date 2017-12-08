The file 'sense_clusters-21.senses' contains a sense clustering of WordNet senses
(we adopted WordNet 2.1). The clustering is created automatically with the aid 
of a methodology described in (Navigli, 2006). Senses in the same cluster appear
on the same line.

Sense clusters for words in the test set of the Semeval English coarse-grained 
all-words task were manually validated by an expert lexicographer. Sense clusters
for all other words have not been validated, but can be still be used for improving
the quality of disambiguation systems. For obvious reasons, monosemous words 
are not reported in the file 'sense_clusters-21.senses'. Words missing in the file 
could not be mapped according to the adopted automated procedure.

A final note on the quality of automatic clusters: due to the unavailability of a full
mapping of WordNet senses from 2.0 to 2.1 and the difficulty in converting the resources
used for building the clustering, some information went lost during the 
mapping process described in (Navigli, 2006). As a result, the quality of the 
automatic clustering might be slightly lower than expected (of course, this does not affect 
the manually validated sense clusters). 

Enjoy the task!
Roberto Navigli and Ken Litkowski

References

Navigli R. 2006. Meaningful Clustering of Senses Helps Boost Word Sense 
   Disambiguation Performance. Proc. of COLING-ACL 2006, Sydney, Australia, 
   July 17-21, 2006, pp. 105-112.