DNA sequencing is a method to identify each base that makes up the DNA
strand.

First Generation Sequencing
---------------------------

![**Figure 1.** Chain-termination method. The labelled DNA molecules are separated according their size. Each molecule has a modified nucleotide (ddNTP) that is labeled with a fluorescence dye. The different fluorescence color indicates a specific base: <span style="color:#00ff00">A</span>, <span style="color:#ffd700">G</span>, <span style="color:#ff0000">T</span> or <span style="color:#0000ff">C</span>.]( Sangersequencing.png "Figure 1. Chain-termination method. The labelled DNA molecules are separated according their size. Each molecule has a modified nucleotide (ddNTP) that is labeled with a fluorescence dye. The different fluorescence color indicates a specific base: A, G, T or C.")

First-generation sequencing refers to the chain-termination method that
was developed by Fredrick Sanger and co-workers in 1977 (Figure 1). The
DNA molecule is amplified with a modified nucleotide, allowing only one
addition of base per cycle. DNA is then amplified with varying length:
one strand having one base pair longer than the previous molecule. These
molecules are then separated in a capillary. Each base is labeled with a
fluorescence dye. By reading the different color signal, we will be able
to identify the base (A, G, T, or C).

Next Generation Sequencing
--------------------------

Next-generation sequencing is an advanced sequencing technology where
many short DNA molecules are sequenced at the same time. The technology
is also called massively parallel sequencing. These short DNA molecules
are then assembled by comparing their sequence to a reference sequence,
thereby revealing the complete DNA sequence that can be very long (as
long as our genome!).

There are many different platforms of next-generation sequencing, and
each of them utilize a different technique in achieving DNA sequencing.
In this case, we will focus on the *reversible dye termination
technology* employed by Illumina. In this method, DNA is first
fragmented into a smaller size, and two short DNA molecules called
"Adapters" are ligated to each end of the sample (Figure 2). These
adapters will function as a primer-docking site to amplify DNA during
PCR and to bind to the flow cell. Before analyzing the data, we remove
the adapters because they are not a biological sequence.

DNA molecules capped with adapters and primers are first attached on a
slide (called the flow cell) and amplified with polymerase enzyme
creating local clonal DNA colonies. These DNA colonies are also referred
to as *DNA clusters*. Each cluster contains exactly the same DNA
sequence; therefore the term clonal DNA colonies. Similar to the
first-generation Sequencing technique, the nucleotides are individually
labeled with a fluorescence dye. After the addition of one nucleotide,
the elongation stops and a picture is taken. Following this, the blocker
sitting on the 3' terminal is then chemically removed from DNA, allowing
the next cycle of nucleotide addition to proceed.

![**Figure 2.** Workflow of next-generation sequencing using Illumina platform.]( Illumina.jpg "fig:Figure 2. Workflow of next-generation sequencing using Illumina platform.")\
\
\
\
\
\
\
The parallel sequencing produces millions and billions of reads per run.
This is exponentially larger than the reads produced by first-generation
sequencing. Next-generation sequencing is a very powerful technique that
can be used for many different applications, such as SNP profiling, gene
expression analysis, and detecting genetic aberrations such as mutation
or chromosomal re-arrangements. Once DNA is extracted, it needs to be
processed in preparation for sequencing.

The different sample preparation steps are outlined below:

-   Fragmentation
-   End-repair
-   A-tailing
-   Adapter ligation
-   PCR amplification

This is followed by cluster generation and the actual sequencing
process.

DNA mutation
------------

There are several classifications for DNA mutations; you can find out
more about the mutation information from the way it is written. For
example:

-   345G\>T means that there is one nucleotide substitution from guanine
    to thymine on the position 345.
-   345delGT means that there is deletion of two nucleotides (guanine
    and thymine) starting from position 345.
-   345dupA means that there is a duplication in position 345, resulting
    in two adenine residues.
-   345insTA means that there are two nucleotides inserted (thymine and
    adenine) starting from position 345.

[⇐ Previous (Protein Truncation
Test)](/wiki/Protein_Truncation_Test "wikilink")

[⇐ Theory overview](/wiki/Medical_Genetics_case "wikilink")

