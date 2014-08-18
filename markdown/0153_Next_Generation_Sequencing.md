DNA sequencing is a method to identify each base that makes up the DNA
strand.

### First Generation Sequencing

![**Figure 1.** Chain-termination method. The labeled DNA molecules are separated according to their size. Each of the molecule has a modified nucleotide (ddNTP) that is labeled with a fluorescence dye. The different fluorescence color indicates a specific base,i.e., <span style="color:#00ff00">A</span>, <span style="color:#ffd700">G</span>, <span style="color:#ff0000">T</span> or <span style="color:#0000ff">C</span>.]( Sangersequencing.png "Figure 1. Chain-termination method. The labeled DNA molecules are separated according to their size. Each of the molecule has a modified nucleotide (ddNTP) that is labeled with a fluorescence dye. The different fluorescence color indicates a specific base,i.e., A, G, T or C.")

The first generation sequencing refers to the *chain-termination method*
that was developed by Fredrick Sanger and co-workers in 1977 (see Figure
1). The DNA molecule is amplified with a modified nucleotide allowing
only 1 addition of base per cycle. The DNA is then amplified with
varying length, 1 strand having 1 base pair longer than the previous
molecule. These molecules are then separated in a capillary
electrophoresis. Each of the bases is labeled with fluorescence dye. By
reading the different color signal, we will be able to identify the
bases, i.e., A, G, T or C.

### Next Generation Sequencing

Next Generation Sequencing is an advance sequencing technology where
many short DNA molecules are sequenced at the same time. The technology
is also called massively parallel sequencing. These short DNA molecules
are then assembled by comparing their sequence to a reference sequence,
thereby revealing the complete DNA sequence that can be very long (as
long as our genome!).

There are many different platforms of Next Generation Sequencing, each
of them utilize a different technique in achieving DNA sequencing. In
this case, we will focus on the *reversible dye termination technology*
employed by Illumina. In this method the DNA is first fragmented into
smaller sizes and 2 short DNA molecules called "Adapters" are ligated to
each end of the sample (see Figure 2). These adapters will function as
primer-docking site to amplify the DNA during PCR and to bind to the
flow cell. Before analyzing the data, we remove the adapters because
they are not a biological sequence.

DNA molecules capped with adapters and primers are first attached on a
slide (called the flow cell) and amplified with the polymerase enzyme
creating local clonal DNA colonies. These DNA colonies are also referred
to as *DNA clusters*. Each of the cluster contains exactly the same DNA
sequence, hence the term clonal DNA colonies. Similar to the First
Generation Sequencing technique, the nucleotides are individually
labeled with a fluorescence dye. After the addition of 1 nucleotide, the
elongation stops and a picture is taken. Following which, the blocker
sitting at the 3' terminal is then chemically removed from the DNA
allowing the next cycle of nucleotide addition to proceed.

Once the DNA is extracted, it needs to be processed in preparation for
sequencing. The different sample preparation steps are outlined below:

-   [Fragmentation](/wiki/Fragmentation "wikilink")
-   [End-repair](/wiki/End-repair "wikilink")
-   [A-tailing](/wiki/A-tailing "wikilink")
-   [Adapter ligation](/wiki/Adapter_ligation "wikilink")
-   [PCR amplification](/wiki/PCR_amplification "wikilink")

Followed by [Cluster generation](/wiki/Cluster_generation "wikilink") and the
actual [Sequencing process](/wiki/Sequencing_process "wikilink").

![**Figure 2.** Workflow of Next Generation Sequencing using Illumina
platform.]( IlluminaNGSflow.png "fig:Figure 2. Workflow of Next Generation Sequencing using Illumina platform.")
The parallel sequencing produces millions and billions of reads per run.
This is exponentially larger than the reads that are produced by First
Generation Sequencing. Next Generation Sequencing is a very powerful
technique that can be used for many different applications, such as SNP
profiling, gene expression analysis, detecting genetic aberrations such
as mutation or chromosomal rearrangements.

### How to extract the DNA?

DNA can be extracted from any cell. First, we need to disrupt the cell
(also known as cell lysis). This can be achieved by using chemical and
physical methods, grinding or sonicating the cell. Once the cell is
disrupted, we need to remove the membrane lipids by adding surfactants
or detergents, digest the protein using protease and remove the RNA by
using RNase. Following which, we can precipitate the DNA (for example,
using ethanol) and isolate the DNA from all other materials present in a
cell. There are several methods that can be chosen to extract the DNA,
the most popular method is by using phenol and chloroform. However, new
methods that are easier and safer have been developed, for example,
using column separation.

Please note that extracting DNA from a bone sample can be quite tricky
as compared to blood samples or tissue samples. There are many
commercial kits available for extracting specific sample including for
bone samples.

### Magnetic beads

During the NGS sample preparation, the DNA needs to be purified from
other materials several times. There are various methods that can be
used to achieve this. For example, using column separation (similar to
the DNA extraction method) or using magnetic beads, such as in this
case. The magnetic beads will bind selectively to the DNA molecules when
placed under the magnetic rack, and all the beads will be separated from
the solution. We can then pipette the solution, containing all the
unwanted materials (such as the end-repair mix, A-tailing mix, and
other) and wash the beads using 80% ethanol. After several rounds of
washing, we can elute the DNA molecules from the magnetic beads and
transfer them to a new tube.

[Next (Fragmentation) ⇒](/wiki/Fragmentation "wikilink")

[⇐ Theory overview](/wiki/NGS_Case "wikilink")

