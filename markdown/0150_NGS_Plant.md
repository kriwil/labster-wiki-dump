![Workflow of Next Generation Sequencing using Illumina platform.]( IlluminaNGSflow.png "Workflow of Next Generation Sequencing using Illumina platform.")

### Next Generation Sequencing

Next Generation Sequencing is an advanced sequencing technology that
sequences millions of short DNA molecules at the same time. The
technology is also called massive parallel sequencing.

There are many different Next Generation Sequencing platforms: each of
them utilizes a different technique. In this case, we will focus on the
reversible dye termination technology employed by Illumina. First, the
DNA is fragmented and the two short DNA molecules, called adapters, are
ligated to each end of each sequence (see Figure 2). These adapters
function as primer-docking sites for the PCR and attach to flow cells.

DNA molecules capped with adapters are first attached to a slide (called
the flow cell) and are then amplified by the polymerase enzyme creating
local clonal DNA colonies. These DNA colonies are also referred to as
DNA clusters. Each of the clusters contains exactly the same DNA
sequence, hence the term clonal DNA colonies. Similar to the First
Generation Sequencing technique, the nucleotides are individually
labeled with a fluorescence dye. After the addition of one nucleotide,
the elongation stops and a picture is taken. Thereafter, the blocker,
sitting at the 3' terminus, is chemically removed from the DNA allowing
the next cycle of nucleotide addition to occur.

\
Once the DNA is extracted, it needs to be processed in preparation for
sequencing. The different sample preparation steps are outlined below:

-   Fragmentation
-   End-repair
-   A-tailing
-   Adapter ligation
-   PCR amplification
-   Followed by Cluster generation and the actual Sequencing process.

The reads are assembled by comparing their sequence to a reference
sequence. Overlaps of reads allow for the reconstruction of the original
DNA fragments.

Parallel sequencing produces millions of reads per run. This is
exponentially larger than the reads that are produced by First
Generation Sequencing. Next Generation Sequencing is a very powerful
technique that can be used for many different applications, such as SNP
profiling, gene expression analysis and the detection of genetic
aberrations (e.g. mutations or chromosomal rearrangements).\
For this case we want to identify protein-coding sequences; therefore we
can exclude all of the RNA species other than mRNAs. Relevant sequences
contain a start codon, followed by several hundred codons, and then a
stop codon.

[ ⇐ cDNA](/wiki/cDNA "wikilink")/ [ BLAST ⇒](/wiki/BLAST "wikilink")\
[⇐ Theory overview](/wiki/PlantLab "wikilink")

