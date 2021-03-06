![**Figure 1.** Flow cell showing high density of short DNA strand attached to the surface.](https://s3-us-west-2.amazonaws.com/labster/wiki/media/FlowCell.jpg "Figure 1. Flow cell showing high density of short DNA strand attached to the surface.")

After completing the NGS sample preparation, the DNA needs to be
anchored to a plate surface where it will again be amplified and then
sequenced. This plate surface is also called flow cell (see Figure 1).
There are short DNA molecules attached to the surface of the flow cell,
as you can observe from the image there are many of these short DNA
molecules creating a very high density area. There are basically 2
different short DNA molecules attaching to the flow cell surface, shown
as <span style="color:#008000">green</span> and
<span style="color:#FFD700">yellow</span> poles. Each of these short DNA
molecules bind specifically to 1 type of adapter because their sequences
are complimentary. One adapter will bind to the
<span style="color:#008000">green molecule</span> whereas the other
adapter will bind to the <span style="color:#FFD700">yellow
molecule</span>.

Cluster generation steps
------------------------

After the DNA molecules are bound to the flow cell, 2 steps will occur.
Note that the different coloring in Figure 1 and Figure 2 are
irrelevant, they merely are to show that there are two different short
DNA molecules attaching to the flow cell.

-   **Bridge PCR**

The DNA molecule that is bound to the short DNA molecule (shown as the
<span style="color:#1E90FF">blue molecule</span>) will bend over and
bind to the other molecule (shown as the
<span style="color:#DA70D6">purple molecule</span>) creating a "bridge"
(see Figure 2). A primer will then attached to the
<span style="color:#DA70D6">purple molecule</span> and amplify the DNA,
creating 2 DNA molecules that are complimentary to each other. The
bridge is then released, and each of the DNA molecule is now only bound
to 1 short DNA molecule. The process is repeated numerous times
generating a cluster, and in this cluster we can find both the DNAs, the
DNA molecules that are bound to the <span style="color:#1E90FF">blue
molecule</span> and the DNA molecule that are bound to the
<span style="color:#DA70D6">purple molecule</span>. Approximately 4,000
DNA molecules are found in each cluster after bridge PCR amplification,
but half of them are washed away leaving only 2,000 DNA molecules per
cluster.

-   **Flush**

At the moment we have 2 complementary DNA strands attaching to the flow
cell surface. But we only want to sequence 1 of them (for example, only
DNA that are bound to the <span style="color:#1E90FF">blue
molecule</span>). We will flush the other DNA molecules that are bound
to the <span style="color:#DA70D6">purple molecule</span>; therefore,
now we will have only DNA molecules that were synthesized with the same
orientation. Now, in each cluster, we find only DNA that is bound to the
<span style="color:#1E90FF">blue molecule</span>, and they are identical
because they were clonally amplified. At the end of the cluster
generation step, we can expect having approximately 200 millions of
clonally amplified DNA cluster in 1 flow cell. This is a lot of DNA that
is ready to be sequenced!

![**Figure 2.** Cluster generation showing bridge PCR and amplification.](https://s3-us-west-2.amazonaws.com/labster/wiki/media/ClusterGeneration.jpg "Figure 2. Cluster generation showing bridge PCR and amplification.")

[⇐ Theory overview](/wiki/NGS_Case "wikilink")

