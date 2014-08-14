Ligation, which is a process that covalently joins the phosphate
backbone of double-stranded DNA, is carried out by an enzyme called DNA
ligase. DNA ligase, commonly used in biotechnology labs, was isolated
from phage T4 or from *E.coli*. They both catalyze ligation reactions in
a similar way, but they differ in cofactor requirements. The *E.coli*
enzyme requires NAD^+^ while the T4 enzyme requires ATP. These cofactors
are provided in buffer.

Ligation reaction
-----------------

The ligation reaction generally consist of two steps:

-   DNA ends collision.\
    This collision occurs by chance and the occurrence rate is lower in
    low temperature. The low temperature stabilizes the hydrogen bonding
    between the complementary nucleotides. The DNA ligase reaches an
    optimum optimum activity at 25^o^. A general rule is that the lower
    the incubation temperature, the longer the incubation time.
-   Enzymatic reaction.\
     DNA ligase catalyzes the joining between 3'-hydroxyl to
    5'-phosphate.

![Ligation reaction. The AMP nucleotide is transferred to the
5'-phosphate. Then the AMP-phosphate bond is attacked by 3'-OH forming a
covalent bond while releasing
AMP.](ligase.png "Ligation reaction. The AMP nucleotide is transferred to the 5'-phosphate. Then the AMP-phosphate bond is attacked by 3'-OH forming a covalent bond while releasing AMP.")

The efficiency of a ligation reaction can be increased by optimizing the
insert:vector ratio. A ratio of 3:1 is a good initial parameter. The
concentration of DNA vector and insert can be measured using
spectrophotometer such as [Nanodrop](DNA_Isolation "wikilink"). The
formula required to calculate amount of gene of interest (insert) to be
added in the ligation reaction is:\
![](ligation formula.png "fig:ligation formula.png")

**Example of ligation reaction optimization calculation:**\
**Data**\
Result from spectophometer measurement are:

-   DNA vector concentration: 30 ng/μL
-   Insert concentration: 15 ng/μL

We also have the data about vector and insert length which are 4000 bp
and 1000 bp respectively. Optimum ratio is 3:1. We will use 60 ng of DNA
vector.\

**Calculation**\
\*(ng vector x kb size of insert)/ kb size of vector x insert/vector =
ng of insert

-   (60ng x 1 kb) / 4 kb x 3/1 = 45 ng of insert

  ---------------------------------------------------------------------------------------
  Reaction component                   Reaction concentration   Volume
                                                                
  ------------------------------------ ------------------------ -------------------------
  10x Ligation Buffer, T4 DNA Ligase   1X                       20 μL/ 10x = 2μL
                                                                

  DNA vector                           60ng                     60ng/30ng/μL= 2μL
                                                                

  Insert                               45ng                     45ng/10ng/μL= 4.5μL
                                                                

  Water                                                         20 -(2+2+4.5+1)= 10.5μL
                                                                

  T4 DNA Ligase                        1 unit                   1 μL
                                                                

  Total                                                         20 μL
                                                                
  ---------------------------------------------------------------------------------------

  : Table 1. Ligation reaction

Plasmid vector
--------------

![ Expression vector contains multiple cloning sites, a selectable
marker, an origin of replication, an operator and a strong
promoter.](Expression vector.jpg "fig: Expression vector contains multiple cloning sites, a selectable marker, an origin of replication, an operator and a strong promoter.")
Plasmid are extra-chromosomal molecules of DNA, mostly double-stranded,
covalently closed, and circular molecule. It varies in size from 1 kb to
more than 200 kb. Not all plasmids are a vector. A DNA molecule such as
plasmid needs to have features to be able to act as a vector for gene
cloning. Generally there is two types of vectors based on their
application: cloning vector and expression vector. Both vectors have the
main feature that a vector should possess: a selectable marker gene, an
origin of replication, and multiple cloning sites. But the expression
vectors have an additional feature that is a strong promoter because it
is used to express foreign protein encoded in the gene of interest.
Expression vectors may contain an operator as a gene expression
regulator. Operator is a segment of DNA to which a transcription factor
binds. Cloning vectors are mainly used to carry and multiply the gene of
interest.

A selectable marker is used to ensure that host vector retains the
particular plasmid. An origin of replication gives the plasmid ability
to multiply within the cell independent of the main host chromosome.

Plasmid Assembly
----------------

In principle, plasmid assembly involves these following steps:\
\*Closed circular vector plasmid and gene of interest fragment are
cleaved with one or more restriction enzymes.

-   Gene of interest is ligated to the linearized vector plasmid.
-   The resulting plasmid is transformed into an appropriate host.

![ Different restriction enzymes can generate compatible
overhangs]( compatible overhang.png "fig: Different restriction enzymes can generate compatible overhangs")
Higher success rate in plasmid assembly is achieved when using DNA
fragment with 5' or 3' sticky/overhang ends compared with assembling
plasmid with blunt end DNA fragments. DNA ligase joins two DNA fragment
with compatible overhang. A DNA fragment with a particular overhang can
be ligated not only to the fragment that cut with same restriction
enzyme, but also to any fragment with compatible ends generated by other
restriction enzymes.

Confirmation of plasmid assembly can be determined by performing DNA
sequencing. It is important to confirm that the insert have been
successfully ligated into plasmid vector with the correct conformation
and reading frame. Frame shift can cause nonsense or misense mutation
that lead to the expression of nonfunctional protein.

[⇐ Previous (Restriction enzyme)](Restriction enzyme "wikilink") / [Next
(Transformation) ⇒](Transformation "wikilink")\
[⇐ Theory overview](Molecular Cloning "wikilink")

