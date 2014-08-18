![DNApolymerase kræver en primer for at kunne påbegynde kopieringen af DNA. En primer er en kort nukleotidsekvens (18-25 bp) som binder sig til den komplementære single-stranded DNA streng.|center](https://s3-us-west-2.amazonaws.com/labster/wiki/media/Polymerase dk.jpg "DNApolymerase kræver en primer for at kunne påbegynde kopieringen af DNA. En primer er en kort nukleotidsekvens (18-25 bp) som binder sig til den komplementære single-stranded DNA streng.|center")

Primers er korte DNA fragmenter, der bruges til at starte PCR reaktionen
ved at diagere DNA-polymerasen hen til det sted der skal kopieres.
Primers er normalt 18-25 nuklotider lange, og de binder(anneal) sig til
den komplementære sekvens på den enkelt-strengede DNA(template DNA) Når
en primer har bundet sig til sekvensen, kan DNA-polymerasen binde sig
til 3’ enden på primeren, og påbegynde kopieringen af template strengen.

### Primer design

Hvis man får udleveret et stykke DNA i stil med den nedenstående
sekvens, og ønsker at designe en primer det får kopieret hele sekvensen
i en PCR reaktion. Så skal primeren placeres i begge ender af sekvensen,
som det kan ses i fed på sekvensen nedenunder.

`5'-'''TTACGAGCTATGGGCTATGAACGACTCTA'''TATTCGATTCGATTCG'''TAGCTTTAGGTGTTCAATACGTCACGTA'''-3'`

`3'-'''AATGCTCGATACCCGATACTTGCTGAGAT'''ATAAGCTAAGCTAAGC'''ATCGAAATCCACAAGTTATGCAGTGCAT'''-5'`

DNA-polymerase kan kun tilføje nukleotider til 3’ enden af DNA-strengen.
Man er derfor nød til at sikre sig at primerne vender den rigtige vej,
da de fungere som start punkt for ens DNA-polymerase, så det er
sekvensen imellem primerne der bliver kopieret og ikke det væk fra dem.
Da DNA er antiparallet, skal primerne binde til forskellige strenge som
vist nedenfor.

:   
    :   `3' - primer - 5'`

`5'-'''TTACGAGCTATGGGCTATGAACGACTCTA'''ATTCGATTCGATTCG'''TAGCT<span style="text-decoration: underline;">TTAGGTGTTCAATACGTCAC</span>GTA'''-3'`

`3'-'''AAT<span style="text-decoration: underline;">GCTCGATACCCGATACTTGC</span>TGAGAT'''TAAGCTAAGCTAAGC'''ATCGAAATCCACAAGTTATGCAGTGCAT'''-5'`

:   
    :   `5' - primer - 3'`

Vi har nu fundet stedet hvor primerne skal binde til, og mangler kun at
bestemme sekvensen. Man kan ud fra DNA sekvensen se hvilke nukleotider
som primeren skal binde(anneal) sig til, og derfor skal primeren være
komplementær til den streng den skal binde sig til. Primers er normal
imellem 18 og 25 basepar lange, her bruger vi en på 20. Den venstre
primer (primer 1) kaldes normal for forward (fv) primer, og den højre
reverse (rv) primer.

:   
    :   `(reverse primer) 3'-AATCCACAAGTTATGCAGTG-5'`

`5'-'''TTACGAGCTATGGGCTATGAACGACTCTA'''ATTCGATTCGATTCG'''TAGCT<span style="text-decoration: underline;">TTAGGTGTTCAATACGTCAC</span>GTA'''-3'`

`3'-'''AAT<span style="text-decoration: underline;">GCTCGATACCCGATACTTGC</span>TGAGAT'''TAAGCTAAGCTAAGC'''ATCGAAATCCACAAGTTATGCAGTGCAT'''-5'`

:   `5'-CGAGCTATGGGCTATGAACG-3' (forward primer)`

I virkeligheden ville der være en del flere faktorer at tage i
betragtning når man designer sin primer. Man vil f.eks. undgå dimer
formation hvor ens primere binder sig til hinanden i stedet for ens DNA
streng. Yderligere vil primernes smelte temperatur påvirke stabiliteten
af primer/template bindingen. Heldigvis er der udviklet en del
programmet som forholder sig til mange af disse faktorer under
udviklingen af nye primere, man skal bare vælge sin sekvensen og lade
programmet klare resten.

### Længden af PCR productet er bestemt af primerne

![Længden af et PCR produkt bliver bestemt ud fra placering af primerne. I den her figur følger vi en enkelt streng og observere hvordan den bliver, korter og kortere indtil den ønskede længde er opnået.](https://s3-us-west-2.amazonaws.com/labster/wiki/media/Pcrlength dk.jpg "Længden af et PCR produkt bliver bestemt ud fra placering af primerne. I den her figur følger vi en enkelt streng og observere hvordan den bliver, korter og kortere indtil den ønskede længde er opnået.")

I en PCR reaktion er primerne valgt således at de ind grænser det område
man ønsker kopieret. Dermed kommer de også til at bestemme længden af
PCR-produktet og bliver en del af det endelige produkt. Figuren til
højre viser hvordan en enkelt-strenget sekvens bliver forkortet ned til
den ønskede længde, via flere runder med sekvens specifikke primere.

[⇐ Forrige (PCR (Polymerase chain reaction))](/wiki/PCR "wikilink") / [ Næste (DNA polymerase) ⇒](/wiki/DNA_polymerase "wikilink")\
[⇐ Teori oversigt ](/wiki/CSI_Casen "wikilink")

