## _Ride the Supercoiling_: Evolution of Supercoiling-Mediated Gene Regulatory Networks through Genomic Inversions

Evolution is often considered an unpredictable process, as genetic mutations happen at random.
But the fixation of mutations is not completely arbitrary, as mutations need to pass the sieve of natural selection to be retained.
In particular, the beneficial or deleterious character of a mutation can depend on the genetic background in which it happens, an effect called epistasis.
In this work, I study a particular kind of epistatic interactions in bacteria:  the interplay between mutations in the mechanisms regulating DNA supercoiling -- the level of over- or under- winding of DNA -- and genomic rearrangements.

I present _EvoTSC_, a mathematical and computational model of DNA supercoiling tailored to study the mutual interaction between gene transcription and DNA supercoiling (the _transcription-supercoiling coupling_ or TSC), and integrated into a full-fledged evolutionary simulation.
I first validate the model by showing that evolution can leverage this coupling to evolve gene regulatory networks that are able to tune gene expression levels in response to environmental perturbations, by changing only the relative positions of the genes through genomic inversions.
I then show that, in _EvoTSC_ as well as in the evolutionary simulation platform _Aevol_, introducing supercoiling mutations does not seem to speed up evolution, indicating that the evolutionary relevance of epistatic interactions might be not as important as initially thought.
Using _EvoTSC_, I additionally show that the TSC can lead some genes to be activated by an excess of positive supercoiling, providing a plausible mechanism to explain the similar behavior observed in many bacterial genes.
Finally, I characterize the structure of these supercoiling-mediated gene regulatory networks, showing that they cannot be reduced to local pairwise interactions.
Interaction with many neighboring genes can indeed be needed to regulate gene expression through supercoiling, providing a possible explanation to the evolutionary conservation of gene syntenies.
