##Work log
####22 July 2015 
**HA:** Ran tblastn of Chlamy PSR1 file (see Makefile for commands). Created ipynb to analyze the output of the blast. At 1e-10 cutoff there were 112 hits to the MMETSP db. Looking over the list it is almost all green lineage. No diatoms/dinos/red lineage at all. However: it did hit to one strain of Ehux and one strain of Alexandrium.  We should look at these hits more closely and directly queery the Ehux genome. 



###To do:###
- Create a phylogeny of all hits to MMETSP and NCBI nr/nt. 
- Run blast at a lower cutoff (1e-5)
- MAST search to identify all the hits to the motifs in the Micro genome.  Can we do this same search for different organisms? E.g. can we put in a different set of sequences with the motif search output from Mpu? 



