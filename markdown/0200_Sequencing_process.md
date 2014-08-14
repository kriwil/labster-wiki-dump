![**Figure 1.** Sequencing by synthesis. After the polymerase has
attached to the primer, nucleotides labeled with fluorophore will be
added at the 3' end of the primer. The nucleotides are modified with a
3' capped that allows only 1 nucleotide addition at a time. The
fluorescence signal emitted by the fluorophore is detected and the 3'
capped is cleaved allowing the next sequencing cycle to
begin.]( Sbs.jpg "Figure 1. Sequencing by synthesis. After the polymerase has attached to the primer, nucleotides labeled with fluorophore will be added at the 3' end of the primer. The nucleotides are modified with a 3' capped that allows only 1 nucleotide addition at a time. The fluorescence signal emitted by the fluorophore is detected and the 3' capped is cleaved allowing the next sequencing cycle to begin.")

Now that we have a flow cell filled with a lot of DNA, we are ready to
begin the sequencing process. There are several different ways of
performing Next Generation Sequencing depending on the platform that
they are using. As written previously, in this case we are using
Illumina platform *sequencing by synthesis*. This implies that the
sequencing data is obtained by synthesizing each base pair. Let us go
through the process in detail.

-   **Polymerase attachment**

Once we have the cluster of clonal DNA attaching on the flow cell,
sequencing reagents are then pumped into the flow cell. They enter from
1 side of the flow cell and exit on the other side. T4 DNA polymerase
are flushed in and attach to the short DNA molecule bound to the flow
cell (acting as the sequencing primer).

-   **Nucleotides tagged with fluorophore**

All the 4 nucleotides are tagged with specific fluorophore. As you can
see in Figure 1, Thymine is tagged with a
<span style="color:#32CD32">green</span> fluorophore, Cytosine with a
<span style="color:#40E0D0">blue</span> fluorophore, Guanine with a
<span style="color:#FF0000">red</span> fluorophore, and Adenine with an
<span style="color:#FF8C00">orange</span> fluorophore. These nucleotides
are also modified; they have a 3' capped that allows only addition of 1
nucleotide at a time. Therfore, after 1 nucleotide has been added to the
3' end of the primer, no more nucleotides can attach. The remaining
nucleotides that are freely floating are then washed away from the
system.

![**Figure 2.** An overlay image, each color dot represents a clonally
amplified DNA cluster. The color codes for the 4 different nucleotides,
Thymine, Cytosine, Guanine, and
Adenine.]( Sequenceimage.png "Figure 2. An overlay image, each color dot represents a clonally amplified DNA cluster. The color codes for the 4 different nucleotides, Thymine, Cytosine, Guanine, and Adenine.")

-   **Detection**

Because of all the nucleotides are individually labeled with a specific
fluorophore, we can identify the nucleotide by observing at the
fluorescence signal that they emit. For example, in Figure 1, we can
observe that 1 nucleotide tagged with a
<span style="color:#32CD32">green</span> fluorophore is added at the 3'
end of the primer. By a chemical reaction,the
<span style="color:#32CD32">green</span> fluorescence is emitted and can
be recorded by taking a picture. Because we know that Thymine is tagged
with the green fluorophore, we can identify the base as Thymine. Four
pictures are taken at the end of each cycle, recording each of the
possible colors. After taking all 4 pictures, the system will overlay
all 4 images; therefore we can easily identify the base identity of each
cluster (see Figure 2).

-   **Cleavage and remove**

After the picture has been taken the 3' capped of the nucleotide is
cleaved so that the next sequencing cycle can begin. The cleaved 3'
capped is then removed from the system. This marks the end of a
sequencing cycle and the new cycle can begin by flushing new rounds of
nucleotides and repeating the steps again.

\
\
\
\
\
\
\
==Single- vs. paired-end sequencing== ![**Figure 3.** Paired-end
sequencing implies that the sequencing is performed from both
directions. The DNA needs to be flipped by running another round of
cluster
generation.]( PESeq.jpg "fig:Figure 3. Paired-end sequencing implies that the sequencing is performed from both directions. The DNA needs to be flipped by running another round of cluster generation.")

-   **Single-end sequencing**

As the name suggests, single-end sequencing is when the sequencing
process is performed only from a single direction. As we have discussed
earlier in [Cluster generation](/wiki/Cluster_generation "wikilink") after
bridge PCR amplification, we have 2 types of DNA molecules that are
complementary to each other, and we washed away 1 of them. We then
sequence the remaining DNA that have the same direction. If we only
sequence these DNA (all having the same direction), it is called by
single-end sequencing.

-   **Paired-end sequencing**

In paired-end sequencing, the DNA is being sequenced from both
directions (see Figure 3). The process is identical to the single-end
sequencing, but after the end of the sequencing process, we continue by
running another round of cluster generation and removing the strands
with the direction that we have sequenced previously (the DNA having
<span style="color:#1E90FF">blue adapters</span>). Therefore, we are
left with only DNA having <span style="color:#DA70D6">purple
adapters</span>. This DNA has the complementary sequence of the first
DNA.

When using paired-end sequencing, we can detect structural variants in
the genome with higher confidence because we have higher sequence
coverage and increased specificity when aligning back to the genome
compared with single-end sequencing, which involves only 1 end of the
DNA fragment. When sequencing long DNA fragments, it is preferred to use
paired-end sequencing. It is also better to use paired-end sequencing
when we wants to study deletion, mutations, or chromosomal
rearrangements.

[⇐ Theory overview](/wiki/NGS_Case "wikilink")

