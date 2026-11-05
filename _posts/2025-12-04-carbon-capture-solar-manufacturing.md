---
layout: post
title: Can carbon capture help make solar panels net-zero?
date: 2025-12-04 09:00:00-0700
description: Solar power is central to decarbonization, yet making solar panels still depends on carbon-intensive inputs. Here is where carbon capture and utilization could help, and where it falls short.
tags: solar-pv carbon-capture life-cycle-assessment
categories: research
thumbnail: assets/img/ccu-pv-module-layers.png
toc:
  sidebar: left
---

Solar photovoltaics (PV) is one of the most important tools we have for cutting carbon emissions. The Intergovernmental Panel on Climate Change (IPCC) projects that warming will substantially exceed 1.5 °C without deep cuts in CO₂ emissions [1], and it identifies solar PV as the mitigation option with the greatest potential [2].

But there is a paradox. A solar panel produces clean electricity for decades, yet the factories that make it still run largely on fossil energy. In this post, I look at where the carbon in a crystalline-silicon (c-Si) solar module comes from, and ask whether **carbon capture and utilization (CCU)** could help close the gap.

## The carbon cost of making solar panels

Crystalline-silicon modules account for more than 90% of the global market [3]. Over their full life cycle, they emit roughly 28–100 g CO₂-equivalent per kilowatt-hour of electricity generated [4], far less than fossil power. Most of those emissions, however, are released up front, during manufacturing.

According to the International Energy Agency (IEA), global PV manufacturing released about 51.9 million tonnes of CO₂ in 2021 [5, 6]. The main reason is location: manufacturing is concentrated in regions with coal-heavy grids (Figure 1), and coal supplies more than 60% of the electricity used to make solar panels worldwide [6].

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/ccu-pv-manufacturing-map.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Figure 1: Where crystalline-silicon PV components are manufactured. Source: Wikoff et al. (2022) [2].</div>

The scale matters. The U.S. Department of Energy's _Solar Futures Study_ explores manufacturing 1 terawatt (TW) of new PV capacity by 2035 [7]. Studies estimate that producing the modules alone for 1 TW could consume 2–14% of the remaining global carbon budget for limiting warming to 1.5 °C, depending on the energy mix and process efficiency. That estimate excludes racking, inverters, and other balance-of-system components, so the true burden is higher.

Cleaner grid electricity helps, but it is not a complete fix. Several of the most carbon-intensive steps rely on high-temperature heat, chemical reactions, or fossil-derived raw materials. This is where CCU comes in.

## What is carbon capture and utilization?

CCU captures CO₂ from industrial sources and converts it into fuels, chemicals, and materials. In PV manufacturing, that could mean:

- **CO₂-derived ethylene, methanol, formic acid, or carbon monoxide** as feedstocks for encapsulants and backsheets
- **Synthetic methane or methanol** in place of natural gas in high-temperature glass and wafer furnaces
- **Industrial symbiosis**, where PV factories are co-located with cement or ammonia plants to exchange waste heat and captured CO₂

Done well, this could support a circular economy in which renewable energy technologies are built from carbon-neutral or even carbon-negative materials.

## What is inside a solar module?

To find the carbon hotspots, it helps to know what a module is made of (Figure 2).

- **Glass:** a 3–4 mm sheet of tempered glass protects the module while letting light through.
- **Encapsulant:** a transparent polymer layer, usually ethylene-vinyl acetate (EVA) or polyolefin elastomer (POE), bonds the glass to the cells and keeps moisture out.
- **Solar cells:** wafers of crystalline silicon about 160–180 micrometers thick, refined to 99.9999% purity and wired in strings of 60 to 144 cells.
- **Backsheet:** a multilayer polymer film, typically polyethylene terephthalate (PET) or a fluoropolymer, that insulates the rear of the module and blocks moisture.
- **Frame:** aluminum or steel, which accounts for 15–25% of the module's weight [11].
- **Junction box:** houses the electrical connections and bypass diodes.

<div class="row mt-3">
  <div class="col-sm-8 mt-3 mt-md-0 mx-auto">
    {% include figure.liquid loading="eager" path="assets/img/ccu-pv-module-layers.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Figure 2: The layers of a crystalline-silicon PV module. Source: Aryan et al. (2018) [12].</div>

## Four carbon hotspots

### 1. Silicon

Silicon is the single largest hotspot, responsible for about 76% of manufacturing emissions [2]. Producing 1 kg of silicon emits roughly 109–113 kg of CO₂, with the trichlorosilane reduction step alone contributing about 59% [13]. Alternative metallurgical routes are not much better, at about 70 kg CO₂ per kg [14].

The cause is electricity. Purifying silicon requires temperatures of 1,500–2,000 °C, and most production takes place in China, where coal supplies more than 75% of power (Figure 3) [6].

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/ccu-pv-polysilicon-electricity.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Figure 3: Polysilicon electricity consumption by region and electricity price, 2021. Source: IEA [6], as reproduced in [15].</div>

For U.S. manufacturing, this is both a challenge and an opportunity. The DOE Solar Energy Technologies Office has set a goal of less than 1 kg CO₂ per kg of silicon [16]. Reaching it will depend mainly on clean electricity and process efficiency, with CCU playing a role only for unavoidable process emissions.

### 2. Solar glass

Glass makes up 65–75% of a module's mass [11]. Melting it requires furnace temperatures of 1,400–1,600 °C, held continuously, and emissions range from about 0.68 to 1.2 kg CO₂ per kg of glass depending on the energy source [15]. At 10–15 kg of glass per square meter of module [17], that adds up to 7–18 kg of CO₂ per square meter.

Because the demand is for high-temperature heat, glass is a strong candidate for CCU: synthetic methane or methanol made from captured CO₂ and green hydrogen could replace natural gas in the furnace.

### 3. Aluminum and steel frames

Producing a ton of aluminum requires 13.5 MWh of thermal energy, equivalent to 11.2 tonnes of CO₂ [18], compared with 4.5 MWh and 1.8 tonnes for steel [9]. Today's aluminum frames emit about 87 kg CO₂ each, or 173,500 tonnes per gigawatt of solar capacity [19].

CCU here is already moving beyond theory. An industry consortium aims to halve direct CO₂ emissions from primary aluminum by 2030, using carbon capture to collect and reuse smelter emissions [21]. Captured CO₂ could also feed synthetic fuels, polymer feedstocks, or carbonated building materials [20].

### 4. Encapsulants and backsheets

Encapsulants and backsheets are a small share of a module's mass but an underexamined source of emissions. They are made from petrochemical feedstocks through multi-step, energy-intensive synthesis. EVA, for example, is built from ethylene and vinyl acetate derived from fossil hydrocarbons.

That petrochemical origin makes polymers a natural fit for CCU. Electrochemical CO₂ reduction can produce ethylene directly from captured CO₂ and renewable electricity [22], and early techno-economic studies suggest that CO₂-derived ethylene could replace fossil monomers in polymer production [23–26].

## How much could CCU cut? A back-of-the-envelope estimate

To put numbers on this, I built a simple estimate for a typical 400-watt module.

### Baseline

Life cycle assessments report cradle-to-gate emissions of about 400–800 kg CO₂-eq per kilowatt-peak (kWp) for c-Si modules [27]. Using a central value of 600 kg CO₂-eq/kWp:

$$
E_{\text{baseline}} = 600 \ \tfrac{\text{kg CO}_2\text{-eq}}{\text{kWp}} \times 0.4 \ \text{kWp} = 240 \ \text{kg CO}_2\text{-eq per module}
$$

I then split this total across the module's materials, assuming a 22 kg module [28] and representative carbon intensities of 110 kg CO₂-eq/kg for silicon, 1 kg CO₂-eq/kg for glass, and 15 kg CO₂-eq/kg for aluminum. The remainder is attributed to the polymer subsystem.

| Material         | Share of mass | Mass (kg) | Baseline emissions (kg CO₂-eq) |
| ---------------- | ------------- | --------- | ------------------------------ |
| Glass            | 75%           | 16.5      | 16.5                           |
| Polymers and EVA | 12%           | 2.64      | 127.8                          |
| Aluminum frame   | 9%            | 1.98      | 29.7                           |
| Silicon cells    | 3%            | 0.66      | 66.0                           |
| **Total**        |               |           | **240**                        |

<div class="caption">Table 1: Material composition [28] and estimated embodied emissions of a 400 W c-Si module.</div>

The polymer figure implies an effective intensity of about 48 kg CO₂-eq per kg of polymer. That number should be read as covering polymer production plus any residual process emissions not captured by the simple silicon, glass, and aluminum accounting, rather than as a precise value for EVA or backsheet resins alone. Even so, the takeaway is striking: polymers are only 12% of the module's mass but, in this simplified balance, account for more than half of its embodied carbon.

### A CCU scenario

Next, I applied an optimistic but plausible set of reductions:

- **Glass:** 50% lower, by replacing part of the natural gas with CO₂-based synthetic fuels or by electrifying furnaces
- **Aluminum:** 40% lower, through more recycled content and CCU in primary production
- **Polymers:** 50% lower, by partly replacing fossil ethylene and other monomers with CO₂-based feedstocks and cleaner energy
- **Silicon:** unchanged, since it benefits mainly from cleaner grids and process efficiency rather than CCU

| Material  | Baseline (kg CO₂-eq) | With CCU (kg CO₂-eq) |
| --------- | -------------------- | -------------------- |
| Glass     | 16.5                 | 8.3                  |
| Polymers  | 127.8                | 63.9                 |
| Aluminum  | 29.7                 | 17.8                 |
| Silicon   | 66.0                 | 66.0                 |
| **Total** | **240**              | **156**              |

<div class="caption">Table 2: Embodied emissions per module before and after the CCU scenario.</div>

That is a reduction of about **84 kg CO₂-eq per module, or 35%**, lowering the intensity from 600 to about 390 kg CO₂-eq/kWp. Roughly three-quarters of the savings come from the polymer subsystem, with metals and glass contributing the rest.

### Scaling to 1 terawatt

At 400 W per module, 1 TW of capacity is 2.5 billion modules:

$$
E_{\text{1 TW, baseline}} = 600 \ \tfrac{\text{kg CO}_2\text{-eq}}{\text{kWp}} \times 10^{9} \ \text{kWp} = 600 \ \text{Mt CO}_2\text{-eq}
$$

$$
E_{\text{1 TW, CCU}} \approx 390 \ \tfrac{\text{kg CO}_2\text{-eq}}{\text{kWp}} \times 10^{9} \ \text{kWp} \approx 390 \ \text{Mt CO}_2\text{-eq}
$$

Even with CCU limited to glass, aluminum, and polymers, manufacturing 1 TW of PV could avoid on the order of **210 million tonnes of CO₂-eq**.

## The catch: technical and economic barriers

These numbers are encouraging, but several obstacles stand in the way.

**Technical barriers**

- **Dilute CO₂ streams.** Flue gases from aluminum smelting and glass melting often contain less than 2% CO₂, which makes capture energy-intensive and expensive. Amine and solid-sorbent systems perform poorly at these concentrations [29, 30].
- **Immature conversion technology.** Electrochemical routes from CO₂ to ethylene remain largely at laboratory or pilot scale [31, 32].
- **Furnace retrofits.** Switching glass furnaces to synthetic fuels means retrofitting burners and maintaining stable combustion above 1,400 °C.
- **Clean energy dependence.** Without abundant low-carbon electricity and hydrogen, CCU pathways may not deliver net emission reductions at all [32].

**Economic barriers**

- Capturing CO₂ from dilute sources is costly [30], and concentrated sources are often far from manufacturing clusters.
- CO₂-derived ethylene currently costs significantly more than fossil ethylene from steam cracking, even under optimistic renewable electricity prices [33, 34].
- Retrofitting aluminum smelters for CCU is expensive, and smelters' need for constant power exposes them to volatile electricity prices [35].
- Synthetic fuels for glass furnaces remain more expensive than natural gas, mainly because green hydrogen is costly.

## The bottom line

CCU is not a silver bullet for decarbonizing solar manufacturing, but it is a useful tool for the parts of the supply chain that clean electricity alone cannot fix: polymer feedstocks, high-temperature glass melting, and metal processing. In my simple estimate, targeted CCU could cut a module's embodied emissions by about a third and avoid roughly 210 million tonnes of CO₂-eq across 1 TW of production.

Making that happen will depend on more efficient processes, cheaper renewable energy and hydrogen, larger-scale CCU technologies, and supportive policies such as tax credits, carbon pricing, and incentives for industrial co-location. As U.S. solar manufacturing grows, building CCU into the right parts of the supply chain could help deliver solar panels that are low-carbon, or even net-zero, from the start.

---

## References

1. IPCC (2021). [Climate Change 2021: The Physical Science Basis](https://www.ipcc.ch/report/ar6/wg1/chapter/summary-for-policymakers/). Contribution of Working Group I to the Sixth Assessment Report.
2. Wikoff, H. M., Reese, S. B., & Reese, M. O. (2022). [Embodied energy and carbon from the manufacture of cadmium telluride and silicon photovoltaics](https://doi.org/10.1016/j.joule.2022.06.006). _Joule_, 6(7), 1710–1725.
3. Mints, P. (2020). _Photovoltaic Manufacturer Capacity, Shipments, Price & Revenues 2019/2020_. SPV Market Research.
4. Life cycle greenhouse gas emissions from solar photovoltaics (2012). _Journal of Industrial Ecology_, 16, S122.
5. Jackman, J. [What's the carbon footprint of solar panels?](https://www.sunsave.energy/solar-panels-advice/solar-energy/carbon-footprint) Sunsave.
6. IEA (2022). [Solar PV Global Supply Chains](https://www.iea.org/reports/solar-pv-global-supply-chains). Paris.
7. Ardani, K., et al. (2021). _Solar Futures Study_. U.S. Department of Energy, Office of Scientific and Technical Information.
8. Margolis, N. (1997). _Energy and Environmental Profile of the Aluminum Industry_. Energetics, Inc.
9. Margolis, N., & Sousa, L. (1997). [Energy and environmental profile of the U.S. iron and steel industry](https://www.osti.gov/biblio/20001922).
10. Pellegrino, J. L. (2002). _Energy and Environmental Profile of the U.S. Glass Industry_. Energetics, Inc.
11. Stolz, P., Frischknecht, R., Wambach, K., & Sinha, P. (2018). _Life Cycle Assessment of Current Photovoltaic Module Recycling_.
12. Aryan, V., Font-Brucart, M., & Maga, D. (2018). [A comparative life cycle assessment of end-of-life treatment pathways for photovoltaic backsheets](https://doi.org/10.1002/pip.3003). _Progress in Photovoltaics_, 26(7), 443–459.
13. Yang, S., et al. (2023). [Coupling the digital twin technology and life cycle assessment: Carbon dioxide emissions from polysilicon production](https://doi.org/10.1016/j.spc.2023.08.004). _Sustainable Production and Consumption_, 41.
14. Yang, S., et al. (2023). [Research on carbon emission of solar grade polysilicon produced by metallurgical route using digital simulation technology](https://doi.org/10.1007/s12633-023-02532-1). _Silicon_, 15, 6567–6578.
15. Colum, C. P. [Solar panels are three times more carbon-intensive than IPCC claims](https://environmentalprogress.org/big-news/2023/7/3/solar-panels-are-more-carbon-intensive-than-experts-will-admit). Environmental Progress.
16. Weaver, J. F. (2024). [$20 million federal initiative targets low-emission silicon and thin film research](https://pv-magazine-usa.com/2024/05/09/20-million-federal-initiative-targets-low-emission-silicon-and-thin-film-research/). _pv magazine USA_.
17. Webb, J., & Hamilton, J. (2011). Physical properties of glass and the requirements for photovoltaic modules. _Photovoltaic Module Reliability Workshop_, Golden, CO.
18. Wang, J. (2022). _The Environmental Footprint of Semi-Fabricated Aluminum Products in North America_. The Aluminum Association.
19. Origami Solar (2024). [Environmental Impact Report](https://origamisolar.com/environmental-impact-report/).
20. Dardor, D., et al. (2025). [Decarbonizing the aluminium industry: A comprehensive review of pathways and process integration perspectives](https://doi.org/10.1016/j.esr.2025.101853). _Energy Strategy Reviews_, 61.
21. Fives Group. [First CO₂ capture solutions for the aluminium industry](https://www.fivesgroup.com/newspress/detail-view/first-co2-capture-solutions-for-the-aluminium-industry).
22. Berkelaar, L., et al. (2022). [Electrochemical conversion of carbon dioxide to ethylene: Plant design, evaluation and prospects for the future](https://doi.org/10.1016/j.cherd.2022.03.034). _Chemical Engineering Research and Design_, 182.
23. Pappijn, C. A. R., Ruitenbeek, M., Reyniers, M.-F., & Van Geem, K. M. (2020). [Challenges and opportunities of carbon capture and utilization: Electrochemical conversion of CO₂ to ethylene](https://doi.org/10.3389/fenrg.2020.557466). _Frontiers in Energy Research_, 8.
24. Mufarrij, F., et al. (2023). [Development and lifecycle assessment of various low- and high-density polyethylene production processes based on CO₂ capture and utilization](https://doi.org/10.1016/j.jclepro.2023.137624). _Journal of Cleaner Production_, 414.
25. Zhou, W., et al. (2025). [Advances in CO₂ electroreduction to ethylene over Cu-based catalysts in membrane electrode assembly](https://doi.org/10.26599/NR.2025.94907613). _Nano Research_, 18(9).
26. Damayanti, D., et al. (2023). [CO₂ utilization applied on converting of polyethylene terephthalate feedstock materials](https://doi.org/10.1016/j.clet.2023.100697). _Cleaner Engineering and Technology_, 17, 100697.
27. Reichel, C., et al. (2022). CO₂ emissions of silicon photovoltaic modules: Impact of module design and production location. _8th World Conference on Photovoltaic Energy Conversion_, Milan.
28. Yuan, L., Nain, P., Kothari, M., & Anctil, A. (2024). [Material intensity and carbon footprint of crystalline silicon module assembly over time](https://doi.org/10.1016/j.solener.2024.112336). _Solar Energy_, 269.
29. Raganati, F., Miccio, F., & Ammendola, P. (2021). [Adsorption of carbon dioxide for post-combustion capture: A review](https://doi.org/10.1021/acs.energyfuels.1c01618). _Energy & Fuels_, 35(16), 12845–12868.
30. Wang, X., & Song, C. (2020). [Carbon capture from flue gas and the atmosphere: A perspective](https://doi.org/10.3389/fenrg.2020.560849). _Frontiers in Energy Research_, 8.
31. Ramdin, M., et al. (2021). [Electroreduction of CO₂/CO to C₂ products: Process modeling, downstream separation, system integration, and economic analysis](https://doi.org/10.1021/acs.iecr.1c03592). _Industrial & Engineering Chemistry Research_, 60(49), 17862–17880.
32. Vega, L. F., Bahamon, D., & Alkhatib, I. I. I. (2024). [Perspectives on advancing sustainable CO₂ conversion processes: Trinomial technology, environment, and economy](https://doi.org/10.1021/acssuschemeng.3c07133). _ACS Sustainable Chemistry & Engineering_, 12(14), 5357–5382.
33. Barecka, M. H., Ager, J. W., & Lapkin, A. A. (2021). Economically viable CO₂ electroreduction embedded within ethylene oxide manufacturing. _Energy & Environmental Science_, 14(3), 1530–1543.
34. IEAGHG (2023). [Techno-economic assessment of electrochemical CO₂ conversion technologies](https://publications.ieaghg.org/technicalreports/2023-03%20Techno-Economic%20Assessment%20of%20Electrochemical%20CO2%20Conversion%20Technologies.pdf). IEAGHG Technical Report.
35. Lassagne, O., Gosselin, L., Désilets, M., & Iliuta, M. C. (2013). [Techno-economic study of CO₂ capture for aluminum primary production for different electrolytic cell ventilation rates](https://doi.org/10.1016/j.cej.2013.06.038). _Chemical Engineering Journal_, 230, 338–350.
