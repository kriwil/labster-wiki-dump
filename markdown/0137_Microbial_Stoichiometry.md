In the microbial aspect, stoichiometry defines the quantitative
relationship between substrates and product of microbial processes,
including biomass formation.

### Mass Balance

**Black box modeling**\
![Black box model for yeast](/wiki/black box.png "fig:Black box model for yeast")
In the black box
model, the input and output of the system are analyzed instead of the
processes inside the system itself. All the chemical reactions that
occur within the cells are neglected, and the whole fermentation process
is viewed as one single reaction, where substrates are converted to
biomass and products.\
![](/wiki/Stoichiometric_equation.jpg "fig:Stoichiometric_equation.jpg")\
In general, only the most important substrates and products are
regarded. For example, for yeast cells, the general stoichiometric
equation would be as follows:\
![](/wiki/GenStoichiometric_equation.jpg "fig:GenStoichiometric_equation.jpg")\
The coefficient in front of every compound is the yield coefficients.
That is the ratio between the change in compound j and the change
compound i.\
![](/wiki/Yield.jpg "fig:Yield.jpg")\
In exponential growth, there is a linear relationship between substrate
consumption and product formation. The yield coefficient will thereby be
constant, which can be calculated as the slope in a plot of the product
versus substrate.\
![In general fermentation, substrate is consumed and biomass and a product are formed. Plotting biomass over substrate shows a linear curve, with Y~sx~ as the slope.](/wiki/Yield_calculation.jpg "fig:In general fermentation, substrate is consumed and biomass and a product are formed. Plotting biomass over substrate shows a linear curve, with Ysx as the slope.")\

**Carbon balance and cmol**\
For carbon balance (or any elemental balance in the fermentation for
that matter), the general stoichiometric equation is used. All the
compounds that contain carbon are taken into account:\
![](/wiki/Massbalance.jpg "fig:Massbalance.jpg")\
Because only the elemental contribution of biomass and not the specific
molecular formula is known, the units are changed to cmol. Relative to
cmol, the general composition in the microorganism is
CH~1.8~O~0.5~N~0.2~. When converting to cmol, the molecule and the
molecular weight are normalized to the carbon content. For example,
glucose(C~6~H~12~O~6~) having the molecular weight of 180 g/mol in cmol
is CH~2~O, and it has the molecular weight of 30 g/cmol (simply the
original molecular weight divided by the number of carbon atoms). The
yields coeffcients can be converted from g/g to cmol/cmol.\
![](/wiki/ConvertCmol.jpg "fig:ConvertCmol.jpg")\
After converting the units to cmol, the carbon balance is as follows:\
![](/wiki/CarbonBalance.jpg "fig:CarbonBalance.jpg")\
The carbon balance is a good method of controlling the fermented
microorganisms. If the carbon balance does not close, there is a lot of
unaccounted carbon, which means unknown byproducts are being produced.

**Molecular weights**\
The following elemental molecular weights are usefull when calculating
the molecular weights of the organic substances:\
Mw (Hydrogen) = 1 g/mol\
Mw (Carbon) = 12 g/mol\
Mw (Nitrogen) = 14 g/mol\
Mw (Oxygen) = 16 g/mol\

### Productivity

The simplest term for productivity is the volumetric productivity,
called q, and it is the amount of product formed per time per volume.\
![](/wiki/vol_product.jpg "fig:vol_product.jpg")\
If one wants to compare the production rate of two different
microorganisms, one would have to consider that the growth rate of the
two organisms could be different. The specific productivity, called r,
is the amount of product formed per time per g DW. It can be calculated
as follows:\
![](/wiki/spe_product.jpg "fig:spe_product.jpg")\
The specific productivity is both dependent on the yield (how much
product is produced in relation to biomass) and how fast the cells are
growing(how much biomass is generated) It is related to the volumetric
productivity with the concentration of biomass.\
![](/wiki/qp=rp.jpg "fig:qp=rp.jpg")\
The volumetric production is dependent of the biomass concentration. In
batch fermentation the biomass concentration is growing, and so the
productivity is not constant. If one want to make an estimate over the
overall volumetric productivity it is calculated as the maximum product
concentration, divided by the time to reach that concentration.

Often, there is a tradeoff in productivity and yield. Better yield makes
the process cheaper (less substrate is needed to form same amount of
product), but higher productivity means faster production and thereby
smaller production facilities. As a rule of thumb, yield is most
important for low-value products (e.g., bulk chemicals) and productivity
is most important for high-value products (e.g., pharmaceuticals)

**Abbreviation**\
<var>x</var>: concentration of biomass produced\
DW: dry weight, a measurement of biomass\
*Y*: yield factor\
S~R~: initial substrate concentration\
s: residual substrate concentration\
*p*: concentration of product\
*q*~*p*~: specific rate of product formation (mg product g^-1^ biomass h
^-1^)\
Y~*xp*~: yield of product in terms of biomass (g product g^-1^ biomass)

[⇐ Previous (Microbial Growth)](/wiki/Microbial_Growth "wikilink") / [Next
(Excelguide) ⇒](/wiki/Fermentation_excel "wikilink");\
 [⇐ Theory overview](/wiki/Fermentation_Case "wikilink")

