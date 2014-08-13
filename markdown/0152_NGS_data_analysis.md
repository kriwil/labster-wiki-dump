Now that we have sequenced the DNA sample, we need to analyze the data
outcome. The raw image data (pictures of the fluorescence-labeled
nucleotides) are very large; they can be up to 1 TB (tera bytes)! The
sequencing machine is able to do some data processing to reduce the file
size. The data analysis process for Next Generation Sequencing can be
divided into 3 steps:

-   **Primary analysis**

![]( IlluminaData.jpg)

Primary analysis includes all the steps required to call or identify
each base. Besides identifying the bases, the sequencing machine will
also assign a quality score for each of the bases. The most common
outcome is stored as a FASTQ file (see image), containing the sequence
identifiers, the assigned nucleotides (A, G, T or C) also called "reads"
and the associated Phred quality score. When a nucleotide is assigned to
N, it implies that the machine cannot determine the exact nucleotide.
The Phred quality score refers to the probability of incorrect base
calling. The primary analysis is typically performed in the sequencing
machine automatically after each run.

-   **Secondary analysis**

Secondary analysis is performed after the primary analysis. When you
want to sequence several samples together in 1 run (for example, from
different patients or different experiments) you can assign a specific
tag to each of them. Tag or also known as barcode is a short DNA
sequence that is added to the adapter to differentiate reads from each
sample. This tag will also be sequenced and by identifying each the
specific adapter sequence for each samples, you will be able to separate
them from each other. This is also called *multiplexing* and has a great
advantage of lowering the sequence cost and getting larger sample. The
first step to do before performing the secondary analysis is to trim out
the tag and adapters because these sequences do not have a biological
meaning.

The main aim of secondary analysis is to assemble all those short DNA
sequences (also called as reads) so that we can interpret the sequence
data. Before this reassembly, the “raw” reads from the machine are often
assessed and filtered for quality to produce the best results, removing
reads that have low Phred quality scores. When the reassembly is
performed from scratch without any reference genome, it is referred to
as *de novo assembly*. In contrast, when there is a reference genome
available, the process is much simpler because we can simply *align* all
the reads to the reference genome.

Normally we would have several reads mapping the same area of the
genome; this is often referred to as "read depth". The read depth
measures how many time that area is covered with different reads, for
example, a read depth of 10 implies that there are 10 reads mapping on
top of each other in the same genomic area.

-   **Tertiary analysis**

Tertiary analysis is where we are trying to understand and make sense of
the sequencing result. It includes variant calling, and the actual
analysis (for example SNP profiling, genome-wide association study,
finding chromosomal aberrations, and others)

Variant calling is the process of accurately determining the variations
(or differences) between a sample and the reference genome. These may be
in the form of single nucleotide variants, smaller insertions or
deletions (called indels), or larger structural variants of
categorizations such as transversions, trans-locations, and copy number
variants.

There are specific variations that are characteristic of [ancient DNA
sample](ancient DNA sample "wikilink"), for example the C \> T at the 5'
end and G \> A at the 3' end. Using these characteristics, we can
identify the ancient DNA and separate them from contaminating modern
DNA.

After identifying variations that are present in the sample, we can then
analyze and try to understand the biological impact of these variations,
for example, by performing SNP analysis. The difference in 1 nucleotide
can result in differential gene expression that gives rise to a specific
phenotype; you can read some of these SNP examples in [ancient Greenland
SNP](ancient Greenland SNP "wikilink").

[⇐ Theory overview](NGS_Case "wikilink")

