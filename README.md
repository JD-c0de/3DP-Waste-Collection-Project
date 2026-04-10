# 3D Printing Waste Collection Project

This repository will provide some guidance on how to set up your own 3D printing waste collection points.
Our main focus will be on waste produced by FDM 3D printing (although you could potentially expand it to other types of 3D printing).


## Table of Contents
1. [What is this waste?](#what-is-this-waste)
2. [What could be done?](#what-could-be-done)
    1. [Ecological perspective](#ecological-perspective)
        1. [Prevention/Reduction](#preventionreduction)
        2. [Re-Use](#re-use)
        3. [Recycling](#recycling)
        4. [Recovery](#recovery)
        5. [Disposal](#disposal)
    2. [Socio-economical perspective](#socio-economical-perspective)
    3. [Technological perspective](#technological-perspective)
    4. [Philosophical perspective](#philosophical-perspective)
        1. [Rebound effect](#rebound-effect)
        2. [Long-term](#long-term)
        3. [Responsibility](#responsibility)
3. [What are the current barriers?](#what-are-the-current-barriers)
4. [Who creates this waste?](#who-creates-this-waste)
5. [Sources](#sources)

The text below gives more information on the waste problem itself. If you just want to know how a collection point could be set up, go [here](Collection-Points.md#collection-points).

## What is this waste?

The waste of 3D printing can be caused by a lot of things:
- Failed prints
- Supports
- Filament change waste
- End of Life prints
- Wrong design
- ...

A survey was conducted in 2019 in the UK about the filament consumption of makers. For those interested, [here is the article.](https://www.filamentive.com/how-much-plastic-waste-does-3d-printing-really-generate)

In the article, there is a table which displays the filament consumption of a user per week (and converted per year) split into 3 usage categories: Casual, Frequent and Heavy.  

| User level | Amount of material used per week | Median Value | Pro rata, per year (converted to kg) |
|------------|----------------------------------|--------------|--------------------------------------|
| Casual     | 40-70 g                          | 55 g         | 2.9 kg                               |
| Frequent   | 135-200 g                        | 167 g        | 8.7 kg                               |
| Heavy      | 320-1345 g                       | 832 g        | 43 kg                                |

Further in the article, they stated that around 33% of filament consumption is waste. This means that for a Frequent user the waste would be 2.871 kg per year.

Currently, this waste is not being recycled by default. That's why this project exists; to make recycling of 3D printing waste more accessible.

## What could be done?

We will now look at the problem from 4 different perspectives and offer some potential solutions.

### Ecological perspective
If we have a look at the waste hierarchy pyramid, we can see that recycling is not the first option that we must consider.
We have:
- Prevention/Reduction
- (Re-Use)
- Recycling
- Recovery
- Disposal

![Waste Hierarchy Pyramid](https://environment.ec.europa.eu/sites/default/files/styles/oe_theme_medium_2x_no_crop/public/2021-01/SC656%20waste_hierachy%20FINAL.jpg?itok=sr1Ra9oC)

(NOTE: We do not talk much about the transport pollution that sending waste to recycling facilities has, because this goes beyond our scope. Just keep in mind that this is also something to consider.)

Let's have a look at each of the layers.

#### Prevention/Reduction

This is the step that will have the biggest impact and is thus very important. We have more detailed tips and tricks on how to reduce 3D printing waste [here](Waste-reduction-tips.md#waste-reduction-tips).

#### Re-Use

This step is a bit harder to achieve with 3D prints because most prints are application specific parts which cannot be reused directly.

#### Recycling

This is the step where the project comes in.
To be able to recycle the waste, we need to collect it first. This can be done through collection points. More about the collection points can be found [here](Collection-Points.md#collection-points).

After the collection, there can be different things done to recycle the waste:
- Create your own filament (using a dedicated filament making machine)
- Send it to processing/recycling facilities
    - Re-melting the waste into new filament
    - Degradation of the material (if bio-degradable, like PLA)
- Use the materials in other sectors (ex. use for construction plates, use in art, ...)
- Use the material for injection molding

#### Recovery

Here is the question: "Can we harvest energy from this waste?".
This could be possible with waste-to-energy plants that burn waste to ash and use the produced heat to generate energy. The toxic fumes and residues are getting filtered and are the only things that remain, which means that the waste pile has been reduced in volume too. It is important to note that this method of energy recovery is not only applicable for 3D printing waste, but for all waste in general.
![waste-to-energy plant](https://www.eia.gov/energyexplained/biomass/images/wastetoenergy.png)

#### Disposal

This is the last step and the most wasteful. The garbage gets collected in landfills or gets burned without energy recovery. This is what currently happens if the 3D printing waste is not being recycled.

### Socio-economical perspective

There are some socio-economical advantages on recycling this waste.

There could be potential cost savings if you are a school or company and consume a lot of filament. If you decide to only recycle your own filament and create your own from it, you could save some extra material cost.

Organizing a collection point makes recycling more accessible to a broader public. It could give people more incentive to collect their failed prints and other 3D printing waste to deposit it rather than throwing it away immediately.

### Technological perspective

One could design a (semi) automated way of sorting the material types at the collection points by various properties. The most noticeable properties to differentiate are the density and glass transition temperature. Here is a table with some of the common 3D printing materials and their properties. (Densities are also separately listed for Bambulab filaments).

| Type | Bambulab Density | Density           | Glass transition temperature |
|------|------------------|-------------------|------------------------------|
| PLA  | 1.24 g/cm³       | 1,210–1,430 g/cm³ | 60–65 °C                     |
| PETG | 1.28 g/cm³       | 1.27 g/cm³        | 80–85 °C                     |
| ABS  | 1.05 g/cm³       | 0.9–1.53 g/cm³    | 105 °C                       |
| ASA  | 1.05 g/cm³       | 1.06 g/cm³        | 100 °C                       |
Sources: (3D Printer Filament \| Bambu Lab US Store, z.d.),(Wikipedia, The Free Encyclopedia, z.d.), (KAD 3D Info,3D Printing services in Australia),(All About Material Density, Specific Mass, z.d.)


For the density based sorting system, there could be a bath of a fluid with a density in between the 2 unknown materials (like Glycerol with a density of 1.261g/cm³ sits between PLA and PETG). One of the 2 materials would float, while the other would sink in the fluid.

The sorting system based on the glass transition temperature is a bit harder since you need a temperature controlled environment and the samples must be tested individually, which is labor intensive.

Another technological advancement could be made in the design of a DIY filament maker. Currently, there are a few on the market, but diversity and more research into this could lead to cheaper devices and better quality recycled filaments.

Another link with technology is that 3D printing is mainly used in sectors that design new technologies. So it is important that the collection points should be organized at places where this public would be (such as engineering campuses, companies, technical schools, ...).

### Philosophical perspective

There are a few philosophical questions that could be asked  about this project.

#### Rebound effect
Could organizing more recycling collection points create a rebound effect?

This means that people will be more likely to 3D print more and be more wasteful because they know it will be recycled. This effect is also visible in other technological advancements like the uprising of energy efficient lamps.

#### Long-term
Can this project be sustained on the long term?

Since 3D printing is gaining more popularity each year, you could say that organizing these collection points can be a long term solution.

#### Responsibility
Who is responsible for the waste?

One could argue that it is the responsibility of the designer of the print to reduce the waste or manage it. It could also be the manufacturers of the filaments themselves or maybe the waste management facilities? The point is, everyone can point to each other, but if we all start contributing a little, we can move further instead of playing "the blame game".

## What are the current barriers?

There are a lot of barriers that prevent such recycling of 3D printing waste. [Here](https://doi.org/10.1016/j.jclepro.2019.118313) is a paper that gives a nice summary of what they could be.

This table originates from that paper (Note that this table has been paraphrased and reformed):

| Nr. | Barrier | Description |
| :--- | :--- | :--- |
| 1 | Diameter sensitivity of FFF | FFF printers require high precision (±0.05mm). Inconsistent recycled filament causes jams or poor print quality. |
| 2 | Avoiding recycled filament | Users often avoid recycled options due to concerns over mechanical consistency, high prices, or negative perceptions. |
| 3 | Focus on 3D print capabilities | As a nascent technology, the industry prioritizes new applications over waste management and recycling extruder development. |
| 4 | External contamination | Dust, grease, and moisture (especially in PLA) degrade the mechanical properties and printability of the final filament. |
| 5 | Varying types of thermoplastics | Different chemical compositions and additives between suppliers make effective separation and recycling difficult. |
| 6 | Limited desktop extruder capacity | Most consumer-grade extruders are designed for virgin pellets rather than processing irregular plastic waste. |
| 7 | Quality degradation | Heating and contamination break polymer chains. Virgin material is often required to restore the filament's integrity. |
| 8 | Start-up instability | Initial extrusion phases often fall below standards due to unstable heating zones or environmental factors like drafts. |
| 9 | Process complexity | Extrusion is a sensitive process requiring precise temperature control and specific cooling/spooling setups. |
| 10 | Lack of mono-streams | Most makerspaces lack large, homogeneous waste streams, often mixing different plastic types in a single bin. |
| 11 | High cost of recycled filament | The labor and processing involved often make recycled filament more expensive to produce than virgin material. |
| 12 | ROI uncertainty | High production costs and unpredictable quality make it difficult to guarantee a return on investment for recycling. |
| 13 | High consumer quality demands | Users expect high aesthetic standards; recycled filaments may have surface finishes that do not meet these expectations. |
| 14 | Linear economy mindset | Current economic systems favor raw material extraction, and short-term financial focus rejects circular initiatives. |
| 15 | Lack of awareness | Since 3DP is already a niche market, recycling within that sector remains a "niche within a niche" with low visibility. |
| 16 | Sustainability mindset dependency | Local recycling is often not financially viable for low-end polymers, making it dependent on eco-conscious decision-makers. |
| 17 | Lack of resources | Many organizations lack the time, physical space, budget, or staff required to manage local recycling operations. |
| 18 | Lack of standardization | There are no standardized regional procedures to ensure the quality and efficiency of collection and recycling hubs. |
| 19 | Labor-intensive preparation | The need to clean, dry, shred, and blend waste makes the preparation process extremely time- and space-consuming. |
| 20 | Safety and health regulations | Meeting industrial safety standards (e.g., managing toxic ABS fumes) is difficult and poorly regulated at a local level. |
| 21 | IP and trade secrets | Patents on extruders and closed-source printer systems hinder innovation and the use of locally recycled materials. |
| 22 | Lack of polymer categories | The absence of clear standards for 3DP polymers leads to uncontrolled growth and difficulty in identifying material properties. |

Source: (Peeters et al., 2019)

## Who creates this waste?

The people who produce this waste are mainly:
- The maker community (Individuals)
- School/Universities
- Public libraries/Fab labs
- Companies
- ...


## Sources

- 3D printer Filament | Bambu Lab US Store. (z.d.). https://eu.store.bambulab.com/collections/bambu-lab-3d-printer-filament
- All about material density, specific mass. (z.d.). https://kg-m3.com/
- Biomass explained. (n.d.). Eia. Retrieved March 24, 2026, from https://www.eia.gov/energyexplained/biomass/waste-to-energy-in-depth.php
- How Much Plastic Waste does 3D Printing Really Generate? (2023, February 14). Filamentive. Retrieved March 24, 2026, from https://www.filamentive.com/how-much-plastic-waste-does-3d-printing-really-generate/
- Israr, A. (2025b, oktober 29). 3D Printing Materials Guide | PLA, PETG, ABS, Resin & More | KAD 3D. KAD 3D. https://kad3d.com.au/3d-printing-materials-guide/
- Peeters, B., Kiratli, N., & Semeijn, J. (2019). A barrier analysis for distributed recycling of 3D printing waste: Taking the maker movement perspective. Journal of Cleaner Production, 241, Article 118313. https://doi.org/10.1016/j.jclepro.2019.118313
- Sandhu, K. (Ed.). (2022). Sustainability for 3D Printing (1st ed. 2022.). Springer International Publishing. https://doi.org/10.1007/978-3-030-75235-4
- Waste Framework Directive. (n.d.). Environment. Retrieved March 24, 2026, from https://environment.ec.europa.eu/topics/waste-and-recycling/waste-framework-directive_en
- Wikipedia, the free encyclopedia. (z.d.-b). https://www.wikipedia.org/
