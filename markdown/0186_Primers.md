![A primer is required in order for DNA polymerase to copy DNA. A primer
is a short (18-25) stretch of nucleotides that anneals to complementary
single stranded template
DNA.|center]( polyprimer.png "A primer is required in order for DNA polymerase to copy DNA. A primer is a short (18-25) stretch of nucleotides that anneals to complementary single stranded template DNA.|center")

Primers are short fragments of DNA used to start DNA copying by the
enzyme DNA polymerase in a PCR reaction. They are typically 18-25
nucleotides in length and will bind (anneal) to a complementary region
of a single-stranded DNA, called the template strand. When a primer is
bound, the polymerase can also bind to the DNA at the 3' end of the
primer. After binding to the 3' end of the primer, DNA polymerase will
copy the DNA template strand.

\

### Primer design

If we are given a DNA piece, as shown below, and wanted to design
primers that would amplify this entire region in a PCR reaction, we
would have to place the primers at each end of the sequence. The primer
regions are shown in bold in the sequence below:

`5'-'''TTACGAGCTATGGGCTATGAACGACTCTA'''TATTCGATTCGATTCG'''TAGCTTTAGGTGTTCAATACGTCACGTA'''-3'`

`3'-'''AATGCTCGATACCCGATACTTGCTGAGAT'''ATAAGCTAAGCTAAGC'''ATCGAAATCCACAAGTTATGCAGTGCAT'''-5'`

The DNA polymerase can only add nucleotides to the 3' end of a DNA
strand. Because the primers are the "starting points" of a the new DNA
strands made by the polymerase, we have to ensure that the 3' ends of
our primers point in the right direction, so that the sequence *between*
the two primers is copied, and not the sequence *away* from the primers.
Because DNA strands are antiparallel, the primers must bind to different
strands. This is shown below.

:   
    :   `3' - primer - 5'`

`5'-'''TTACGAGCTATGGGCTATGAACGACTCTA'''ATTCGATTCGATTCG'''TAGCT<span style="text-decoration: underline;">TTAGGTGTTCAATACGTCAC</span>GTA'''-3'`

`3'-'''AAT<span style="text-decoration: underline;">GCTCGATACCCGATACTTGC</span>TGAGAT'''TAAGCTAAGCTAAGC'''ATCGAAATCCACAAGTTATGCAGTGCAT'''-5'`

:   
    :   `5' - primer - 3'`

We have now located the placement of the primers, and only need to
determine the sequence. We can observe the sequence that the primers
will need to anneal (bind) to, and therefore the primer sequences must
be complementary to the strands they bind to. Primers are typically
18-25 bases long. Here we will design 20 base primers. The left primer
(primer 1) is normally termed the forward (fv) primer, and the right is
the reverse (rv) primer.

:   
    :   `(reverse primer) 3'-AATCCACAAGTTATGCAGTG-5'`

`5'-'''TTACGAGCTATGGGCTATGAACGACTCTA'''ATTCGATTCGATTCG'''TAGCT<span style="text-decoration: underline;">TTAGGTGTTCAATACGTCAC</span>GTA'''-3'`

`3'-'''AAT<span style="text-decoration: underline;">GCTCGATACCCGATACTTGC</span>TGAGAT'''TAAGCTAAGCTAAGC'''ATCGAAATCCACAAGTTATGCAGTGCAT'''-5'`

:   `5'-CGAGCTATGGGCTATGAACG-3' (forward primer)`

In reality, there are more factors to consider when designing primers.
For example, we want to avoid dimer formation, which implies that the
primers bind to themselves instead of the single-stranded DNA.
Futhermore, the melting temperature of the primers determines the
stability of the template DNA/primer duplex. Luckily, many programs have
been developed, which take these parameters into consideration and
design your primers when given an input sequence (the sequence you want
to amplify).

### Length of the PCR product is determined by the primers

![The length of a PCR product is determined by the placement of the
primers. In this figure, we follow a single strand, and observe how the
primer placement shortens the fragment length through multiple rounds of
replication (three rounds are required to get the first double-stranded
fragment where both strands are the length of the
primers)]( pcrlength.jpg "The length of a PCR product is determined by the placement of the primers. In this figure, we follow a single strand, and observe how the primer placement shortens the fragment length through multiple rounds of replication (three rounds are required to get the first double-stranded fragment where both strands are the length of the primers)")

In a PCR reaction, the primers are chosen such that they frame the
desired sequence. This also determines the length of the resulting
fragment, and the primers are included in the final PCR product. The
figure to the right shows how a single strand is shortened to the
desired PCR product length through several rounds of replication
directed by the site specific primers.

[← Previous (PCR)](PCR (Polymerase Chain Reaction) "wikilink") / [Next
(DNA Polymerase) →](DNA Polymerase "wikilink")

[← Theory Overview](CSI Case "wikilink")

