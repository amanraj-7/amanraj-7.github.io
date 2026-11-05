---
layout: post
title: The hidden cost of clean energy, and how to cut it
date: 2026-04-20 09:00:00-0700
description: Rare earth metals power wind turbines, electric vehicles, and electronics, but mining them leaves a heavy environmental footprint. Here is where that footprint comes from and how cleaner extraction and recycling could shrink it.
tags: energy materials circular-economy
categories: research
thumbnail: assets/img/ree-lanthanides.jpg
toc:
  sidebar: left
---

Wind turbines, electric vehicles, smartphones, and defense systems all depend on a small group of metals most people never think about: the **rare earth elements (REEs)**. As demand for clean energy grows, so does demand for these metals, and so does the environmental damage from producing them.

This post is adapted from my term project for CEE 516 at Arizona State University. It covers what rare earths are, why the world depends on them, what mining them does to land, water, and communities, and what we can do to reduce that damage.

## What are rare earth metals?

Rare earths are a group of 17 metallic elements: the 15 lanthanides, plus scandium and yttrium. They are usually split into two groups:

- **Light rare earths**, such as lanthanum, cerium, and neodymium, are relatively abundant and are used in magnets and catalysts.
- **Heavy rare earths**, such as dysprosium, terbium, and europium, are scarcer and are critical for high-performance magnets.

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/ree-lanthanides.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Samples of lanthanide elements. Image credit: Wikipedia (Wikimedia Commons).</div>

For the energy transition, a handful matter most: neodymium, dysprosium, and terbium for permanent magnets, lanthanum for batteries, and cerium for catalysts.

## Why the world needs them

Rare earths show up across modern technology, from electric motors and wind turbine generators to catalytic converters, displays, and guidance systems.

<div class="row mt-3">
  <div class="col-sm-10 mt-3 mt-md-0 mx-auto">
    {% include figure.liquid loading="eager" path="assets/img/ree-applications.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Rare earth elements and their applications. Image credit: U.S. Department of Energy, National Energy Technology Laboratory.</div>

Two numbers capture the scale of the challenge:

- The IEA projects that demand for rare earths could grow about **seven-fold by 2040** as clean energy expands.
- A direct-drive wind turbine uses roughly **175 kg of neodymium per megawatt** of capacity in its permanent magnets (Sherwood et al., 2022).

## A short history of rare earth production

Global rare earth supply has passed through three eras (Weng et al., 2013).

<div class="row mt-3">
  <div class="col-sm-10 mt-3 mt-md-0 mx-auto">
    {% include figure.liquid loading="eager" path="assets/img/ree-production-history.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Global rare earth oxide production by country over time. Image credit: Weng, Jowitt, Mudd, and Haque (2013), <em>Applied Earth Science</em>.</div>

**The monazite placer era (late 1800s to 1964).** The first large-scale production came from monazite-bearing beach sands in Brazil, India, and the southeastern United States, which supplied light rare earths until the 1960s.

**The Mountain Pass era (1960s to 1990s).** The Mountain Pass deposit in California's Mojave Desert was discovered in 1949 by prospectors searching for uranium, and mining began in the early 1950s. In the 1960s, europium from Mountain Pass made the red phosphors in color televisions possible, creating the first real mass market for rare earths. For the next three decades, Mountain Pass was the world's dominant producer.

**The Chinese era (2000s to today).** By the late 1990s, U.S. producers struggled to compete with lower-cost Chinese supply, and Mountain Pass closed in 2002 after a series of toxic wastewater spills. By 2010, China controlled about 95% of global production.

## How rare earths are produced

Conventional production is a long chain of energy- and chemical-intensive steps (Zapp et al., 2022):

1. **Mining:** ore is extracted, often from open pits.
2. **Beneficiation:** the ore is crushed, wet ground, and separated from other minerals by flotation.
3. **Cracking:** the concentrate is treated with acids or alkalis to convert rare earths into soluble salts.
4. **Separation:** dozens of solvent-extraction stages separate the chemically similar elements from each other.
5. **Refining:** individual oxides are reduced to metal, for example by molten salt electrolysis for neodymium and praseodymium.

A different route applies to **ion-adsorption clays** in southern China, weathered, clay-rich soils where rare earths are loosely bound. These are mined by pumping leaching solutions directly into the ground.

## The environmental costs

### Land degradation

Open-pit mining strips away vegetation and topsoil. It can change soil composition, eliminate soil microorganisms, displace wildlife, trigger landslides and erosion, and send sediment-laden runoff into streams.

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/ree-mountain-pass.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">The Mountain Pass mine in California, about 53 miles southwest of Las Vegas. Image credit: Wikipedia (Wikimedia Commons).</div>

### Radioactive waste

Rare earths often occur alongside thorium and uranium (Zapp et al., 2022). Processing produces radioactive tailings that are often stored in unlined ponds, where they can contaminate groundwater. Around China's Bayan Obo mine, the largest rare earth mine in the world, nearby villages have reported elevated rates of cancer and respiratory illness (Xiang, 2016).

### Water and soil pollution

Acid mine drainage and processing reagents such as ammonium sulfate can leach heavy metals into soil and water. By one estimate, every ton of rare earths produced generates about **2,000 tons of mine tailings, including 1 to 1.4 tons of radioactive waste** (Filho, 2016).

### Energy and carbon intensity

Refining rare earths takes a great deal of energy, especially for the heavier and harder-to-separate elements.

| Rare earth oxide                             | Primary energy (MJ/kg) |
| -------------------------------------------- | ---------------------- |
| Lanthanum                                    | 177                    |
| Cerium                                       | 157                    |
| Praseodymium                                 | 798                    |
| Neodymium                                    | 743                    |
| Samarium, europium, gadolinium (mixed oxide) | 1,074                  |

<div class="caption">Table 1: Primary energy needed to produce selected rare earth oxides. Source: Haque et al. (2014).</div>

For comparison, producing aluminum, itself considered an energy-intensive metal, takes roughly 65–75 MJ per kg. Neodymium oxide needs about ten times as much.

<div class="row mt-3">
  <div class="col-sm-9 mt-3 mt-md-0 mx-auto">
    {% include figure.liquid loading="eager" path="assets/img/ree-co2-intensity.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Greenhouse gas emissions per kg of rare earth oxide, by process input. Image credit: Haque, Hughes, Lim, and Vernon (2014), <em>Resources</em>, CC BY 4.0.</div>

The same pattern holds for emissions: the heavier oxides carry several times the carbon footprint of lanthanum and cerium, driven largely by chemical inputs and waste disposal.

## Strategy 1: Cleaner extraction

The first lever is to change how rare earths are mined and processed at the source.

- **Ionic liquid extraction.** Ionic liquids are salts that are liquid at room temperature. They can selectively extract rare earths with lower energy input and near-zero volatility, cutting the emissions associated with conventional organic solvents. So far, this has been demonstrated mainly at laboratory scale (Tunsu et al., 2015).
- **Bioleaching.** Microorganisms such as _Gluconobacter oxydans_ produce organic acids that dissolve rare earths from low-grade ores, reducing the use of harsh chemical reagents and the risk of acid mine drainage (Brisson et al., 2016).
- **Dry tailings and radioactive isolation.** Storing filtered, dewatered tailings instead of using wet ponds reduces the risk of groundwater contamination. Thorium-bearing waste can also be converted into stable solid forms that resist leaching.
- **Alternative deposits.** Ion-adsorption clays and deep-sea muds tend to contain less radioactive material than hard-rock ores, though seabed mining raises serious ecological concerns of its own (Zhang et al., 2013).

## Strategy 2: Recycling and the circular economy

The biggest untapped opportunity is recycling. Less than **1% of rare earths** are currently recycled (Binnemans et al., 2013), even though discarded electronics are a rich source. Permanent magnets contain around 30% rare earths by weight, a concentration that rivals or exceeds primary ores.

Several pathways are promising:

- **Urban mining from e-waste:** recovering rare earths from hard drives, electric motors, and lamp phosphors in end-of-life electronics.
- **Hydrometallurgical recovery from magnets:** acid dissolution followed by solvent extraction or selective precipitation can recover more than 95% of the neodymium and dysprosium in magnet production scrap.
- **Direct reuse and remanufacturing:** used neodymium-iron-boron magnets can be demagnetized and re-sintered, preserving their crystal structure and avoiding full chemical reprocessing, with large energy savings (Walton & Williams, 2011).
- **Policy support:** the EU Critical Raw Materials Act (2024) sets a goal for recycling to supply 25% of the EU's annual consumption of strategic raw materials by 2030. Design-for-disassembly requirements can make rare earths much easier to recover at end of life.

## Key takeaways

1. **Rare earths are indispensable to clean energy**, but mining them causes serious land, water, and radioactive contamination.
2. **Cleaner extraction**, through ionic liquids, bioleaching, and dry tailings management, can substantially reduce the burden at the source.
3. **Recycling rates below 1% are the biggest untapped opportunity.** Urban mining and direct magnet reuse are approaching commercialization.
4. **Substitution, supply diversification, and policy grounded in life cycle assessment** are essential for long-term supply resilience and lower environmental impact.

---

## References

- Binnemans, K., Jones, P. T., Blanpain, B., Van Gerven, T., Yang, Y., Walton, A., & Buchert, M. (2013). [Recycling of rare earths: A critical review](https://doi.org/10.1016/j.jclepro.2012.12.037). _Journal of Cleaner Production_, 51, 1–22.
- Brisson, V. L., et al. (2016). Bioleaching of rare earth elements from monazite sand. _Biotechnology and Bioengineering_, 113(2), 339–348.
- European Union (2024). [Critical Raw Materials Act](https://single-market-economy.ec.europa.eu/sectors/raw-materials/areas-specific-interest/critical-raw-materials/critical-raw-materials-act_en).
- Filho, W. L. (2016).
- Haque, N., Hughes, A., Lim, S., & Vernon, C. (2014). [Rare earth elements: Overview of mining, mineralogy, uses, sustainability and environmental impact](https://doi.org/10.3390/resources3040614). _Resources_, 3(4), 614–635.
- IEA (2021). [The Role of Critical Minerals in Clean Energy Transitions](https://www.iea.org/reports/the-role-of-critical-minerals-in-clean-energy-transitions).
- National Energy Technology Laboratory. Rare earth elements and their applications.
- Sherwood, J., et al. (2022). Via the Environmental and Energy Study Institute.
- Tunsu, C., Petranikova, M., Gergorić, M., Ekberg, C., & Retegan, T. (2015). Reclaiming rare earth elements from end-of-life products: A review of the perspectives for urban mining using hydrometallurgical unit operations. _Hydrometallurgy_, 156, 239–258.
- Walton, A., & Williams, A. (2011).
- Weng, Z., Jowitt, S. M., Mudd, G. M., & Haque, N. (2013). Assessing rare earth element mineral deposit types and links to environmental impacts. _Applied Earth Science_, 122(2), 83–96.
- Xiang (2016).
- Zaimes, G. G., Hubler, B. J., Wang, S., & Khanna, V. (2015). Environmental life cycle perspective on rare earth oxide production. _ACS Sustainable Chemistry & Engineering_, 3(2), 237–244.
- Zapp, P., Schreiber, A., Marx, J., & Kuckshinrichs, W. (2022). Environmental impacts of rare earth production. _MRS Bulletin_, 47, 267–275.
- Zhang et al. (2013).
