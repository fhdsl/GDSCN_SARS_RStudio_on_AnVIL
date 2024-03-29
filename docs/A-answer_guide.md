# (APPENDIX) Appendix {-}

# Answer Guide

This page contains the answers to the reflection questions asked in the student guide. If you discover a mistake or have a suggestion for additional or alternate reflection questions, please contact us through our [Discourse Channel](https://help.anvilproject.org/) or [submit an issue on our GitHub repository](https://github.com/fhdsl/GDSCN_SARS_Phylogeny_on_AnVIL/).


1. What is some information saved in a .fasta object that RStudio tells us that we don't get from a .phyDat object?

_The .fasta object also tells us at least some of the names of the samples in the fasta file, as well as the average base composition of all the sequences and how big the fasta file is._

2. How many omicron sequences are there in the second file (loaded into the object `spike.omicron`)?

_There are four omicron sequences in the second file._

3. Do you think there is more variability in the omicron sequences than in other variants (alpha, beta, delta, and gamma)? Why or why not?

_While adding the omicron sequences to the fasta file increases the number of site patterns in the sequences, this doesn't necessarily mean the omicron sequences have more variability among each other than the other sequences. The omicron sequences may just be very different from the other variants._

4. Which variant(s) is the most distantly related to the original Wuhan reference sequence?

_All the variants other than the alpha variant share the same most recent common ancestor with the original Wuhan reference sequence, thus they are all equally distant relatives of the Wuhan reference sequence._

5. Which variant shares the most recent common ancestor with the omicron variants? What does this mean for determining where the omicron variant came from?

_The beta variant shares the most recent common ancestor with the omicron variants. This suggests that the omicron variant probably evolved from an ancestor of the beta branch._

6. what is the branch length distance between the beta variant and the alpha variant?

_The branch length distance between the beta variant and the alpha variant is 13._

7. What is the longest branch length in the tree? What does this mean for the number of mutations (compared to the Wuhan reference sequence) seen in that variant versus the others?

_The longest branch length is 12, leading to the gamma variant. The gamma variant has a greater number of mutations compared to the Wuhan reference sequence than the others._

8. Did adding the omicron samples change the branch length distances between the original five samples? What is the branch length distance between the alpha and beta variants now?

_Adding the omicron samples did not really change the branch lengths between the original five sequences. The distance between the alpha and beta variants is still 13._

9. What is the length of the branch connecting the omicron group to the rest of the tree?

_The length of the branch connecting the omicron variants to the rest of the tree is 15._

10. The covid vaccines were originally designed based on the Wuhan reference sequence of the spike protein. The immune system learns to recognize the spike protein from the vaccine and can identify and destroy any invading Covid-19 viruses. Using what you have learned about the phylogenetic tree of SARS-CoV-2 variants, can you explain why these initial vaccines were less effective at protecting against the omicron variants than they were against the delta variant?

_The distance between any of the omicron variants and the Wuhan reference variant is much larger than the distance between the delta variant and the Wuhan reference sequence. This tells us the omicron spike protein sequence has mutated more in the omicron variants, so the spike protein probably doesn't look as much like the spike protein the vaccines train the immune system to recognize (compared to the delta variant spike proteins)._

11. Based on the information from the phydat files for the spike protein dataset and the membrane protein dataset, is there the same amount of variation in each protein-coding region?

_No, there is much less variation in the membrane protein-coding region than in the spike protein-coding region._

12. Do you think the spike protein dataset or the membrane protein dataset contains a greater number of phylogenetically-informative sites? 

_The spike protein dataset contains a greater number of phylogenetically-informative sites._

13. Is the tree built from the membrane protein data the same as the tree built from the spike protein data?

_The tree built from the membrance protein data looks very different from the tree built from the spike protein data. The relationships are much less resolved._

14. Why is a greater number of phylogenetically-informative sites better for tree building?

_A greater number of phylogenetically-informative sites results in more resolution among the taxa in the tree._
