# sequence_alignment
## Multiple Sequence Alignment


Ebola virus is the causative agent of Ebola hemorrhagic fever (EHF), a disease affecting humans and other primates. The disease is characterized by high death rates (as high as 90%) and is highly contagious.
I obtained RNA genomes for the ebola project.
&nbsp;

![aaa](https://github.com/programweb/sequence_alignment/assets/12736699/a46513ab-39db-42d4-a5a1-3c9623c82c5d)
&nbsp;


We can see the downloaded file contains 249 full length genomes. 
First, just align the first ten full ebola sequences against one another
(Why? Comparing multiple genomes can be used to assess the quality of genome assemblies. Inconsistencies or gaps in the alignments can highlight potential issues with the assembly and guide further improvements.).
Second, find the IDs of the first ten sequences.
Using these accession numbers, we can extract the sequences that correspond to these IDs.
&nbsp;

![bbb](https://github.com/programweb/sequence_alignment/assets/12736699/f1e1fa01-2fde-4892-802e-a19947e68694)
&nbsp;

I perform a **multiple sequence alignment** with the mafft tool.  MAFFT is a multiple sequence alignment program for *nix operating systems.  It offers a range of multiple alignment methods: L-INS-i (accurate; for alignment of <∼200 sequences), FFT-NS-2 (fast; for alignment of <∼30,000 sequences), etc.
&nbsp;

![ccc](https://github.com/programweb/sequence_alignment/assets/12736699/5829affe-8049-4476-8a45-c7b6e6b5380d)
&nbsp;

I can view the alignment with the head/tail BASH commands which display a visual alignment of all sequences.
One can see that one difference between the genomes is how complete the assemblies are at their edges.
The term "edges" indicates the parts of the genomes that are at the beginning or end of the sequence, often where the sequencing data may be less reliable or less well-assembled.
The * character indicates a consensus.
&nbsp;

![ddd](https://github.com/programweb/sequence_alignment/assets/12736699/500cd37b-84b1-492e-9fcc-1acb6efb0cdd)
&nbsp;

One can perform multiple sequence alignments on 10% of the genomes
&nbsp;

![eee](https://github.com/programweb/sequence_alignment/assets/12736699/0112f891-e0a0-4a0f-b196-6111b079bc64)
&nbsp;

![fff](https://github.com/programweb/sequence_alignment/assets/12736699/200ba457-6db0-4115-9587-19865fdc898c)
