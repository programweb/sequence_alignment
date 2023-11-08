# sequence_alignment
## Multiple Sequence Alignment


Ebola virus is the causative agent of Ebola hemorrhagic fever (EHF), a disease affecting humans and other primates. The disease is characterized by high death rates (as high as 90%) and is highly contagious.
I obtained RNA genomes for the ebola project.
&nbsp;

![alignment_001](https://github.com/programweb/sequence_alignment/assets/12736699/02ed8196-3927-4a0e-9056-d37cf6eaa646)
&nbsp;


We can see the downloaded file contains 249 full length genomes. 
First, just align the first ten full ebola sequences against one another
(Why? Comparing multiple genomes can be used to assess the quality of genome assemblies. Inconsistencies or gaps in the alignments can highlight potential issues with the assembly and guide further improvements.).
Second, find the IDs of the first ten sequences.
Using these accession numbers, we can extract the sequences that correspond to these IDs.
&nbsp;

![alignment_002](https://github.com/programweb/sequence_alignment/assets/12736699/2ec9c64f-ea22-46a0-b713-7bd0416a115e)
&nbsp;

I perform a **multiple sequence alignment** with the mafft tool.  MAFFT is a multiple sequence alignment program for *nix operating systems.  It offers a range of multiple alignment methods: L-INS-i (accurate; for alignment of <∼200 sequences), FFT-NS-2 (fast; for alignment of <∼30,000 sequences), etc.
&nbsp;

![alignment_003](https://github.com/programweb/sequence_alignment/assets/12736699/4449f531-b387-421f-bad8-e7ad07f80dff)
&nbsp;

I can view the alignment with the head/tail BASH commands which display a visual alignment of all sequences.
One can see that one difference between the genomes is how complete the assemblies are at their edges.
The term "edges" indicates the parts of the genomes that are at the beginning or end of the sequence, often where the sequencing data may be less reliable or less well-assembled.
The * character indicates a consensus.
&nbsp;

![alignment_004](https://github.com/programweb/sequence_alignment/assets/12736699/532029ae-aabd-4322-88f2-8554fc9685c0)
&nbsp;

One can perform multiple sequence alignments on 10% of the genomes
&nbsp;

![alignment_005](https://github.com/programweb/sequence_alignment/assets/12736699/b6d4a11a-5084-40d4-85c3-86a9f6e8b7fc)
&nbsp;

![alignment_006](https://github.com/programweb/sequence_alignment/assets/12736699/a75330cd-84b8-43c9-bd42-e3036f0b970c)
