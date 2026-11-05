---
layout: post
title: "Solar or carbon capture: where should the next climate dollar go?"
date: 2026-11-04 12:00:00-0700
description: Comparing the cost of cutting a ton of CO₂ with solar power versus carbon capture and storage, and why carbon capture still matters for the jobs only it can do.
tags: energy climate policy
categories: research
thumbnail: assets/img/solar-ccs-learning-curve.png
toc:
  sidebar: left
---

Two technologies sit at the center of almost every decarbonization plan: utility-scale solar power, and carbon capture and storage (CCS), which traps CO₂ at industrial smokestacks before it reaches the atmosphere. The IPCC lists both among the options with the largest potential to cut emissions this decade (IPCC, 2022). The International Energy Agency's _Net Zero by 2050_ roadmap treats them as complementary pillars: solar becomes the largest source of electricity, while CCS handles residual emissions from cement, steel, and other heavy industry (IEA, 2021).

Officially, then, the question is not which technology to choose, but how quickly to scale both. I think that framing deserves a closer look, because climate money is finite.

## Every dollar has an opportunity cost

Global clean energy investment reached a record \\$1.8 trillion in 2023 (IEA, 2023). That sounds enormous, but it is well short of the roughly \\$4.5 trillion per year the IEA says will be needed by the early 2030s to keep 1.5 °C within reach (IEA, 2021). When investment falls this far short of need, every allocation decision carries a real opportunity cost. A dollar spent on CCS is a dollar not spent on solar or grid upgrades, and vice versa.

Research on energy transition pathways reinforces this. Way et al. (2022) found that pathways built on fast-improving technologies like solar and wind have much lower total system costs than pathways that lean on a broader mix including CCS, because that broader mix carries cost uncertainties that compound over time.

So the question I want to ask is simple: **for every dollar spent, which technology prevents or removes more CO₂?**

My argument has two parts. First, CCS is over-prioritized relative to solar for cutting bulk emissions from electricity, and that imbalance has more to do with politics than with engineering. Second, CCS is under-invested in the narrower set of jobs that solar simply cannot do. The answer is not to pick one technology over the other. It is to stop asking CCS to compete with solar where it consistently loses, and to focus it where nothing else works.

## How to compare them: the cost per ton of CO₂

To compare technologies that work in completely different ways, I use the **levelized cost of carbon abatement (LCCA)**: the lifetime cost of a project divided by the tons of CO₂ it avoids or removes.

$$
\text{LCCA} \ (\$/\text{ton}) = \frac{\text{Total project cost} \ (\$)}{\text{Tons of CO}_2 \text{ avoided or removed}}
$$

Lower is better. A technology with an LCCA of \\$40 per ton delivers twice the climate benefit per dollar of one at \\$80 per ton.

The three technologies do different jobs, so it is worth being precise about where they actually compete.

|                    | Utility-scale solar                                                  | Point-source CCS                                                           | Direct air capture                                    |
| ------------------ | -------------------------------------------------------------------- | -------------------------------------------------------------------------- | ----------------------------------------------------- |
| **What it does**   | Replaces fossil electricity, preventing emissions before they happen | Captures CO₂ at factory or power plant chimneys                            | Pulls CO₂ out of the open air: true removal           |
| **Where it works** | Grid electricity only                                                | Cement, steel, chemicals, and gas power; competes with solar only in power | Reversing overshoot and offsetting residual emissions |
| **Typical cost**   | About \\$33–82 per ton CO₂ (see below)                               | \\$100–300 per ton CO₂                                                     | \\$300–1,000 per ton CO₂ (Fasihi et al., 2019)        |

<div class="caption">Table 1: The three technology categories compared in this post.</div>

The head-to-head comparison between solar and CCS applies only to electricity generation, the one place where both are doing the same job. Everywhere else, the comparison is about opportunity cost: given a fixed pot of money, which investment cuts the most CO₂?

Two caveats are worth stating up front. First, solar's cost per ton depends on what it replaces. Displacing coal avoids about 900 kg of CO₂ per megawatt-hour; displacing gas avoids closer to 400 kg. I use the 2023 U.S. grid average of about 367 kg per MWh (EIA, 2023), which sits near the gas end of the range and makes my solar estimates conservative. Second, cost per ton is not the whole story. It leaves out speed of deployment, political feasibility, co-benefits such as jobs and cleaner air, and risks such as CCS's dependence on suitable geology and long-term storage integrity.

## Solar's learning curve

The cost of utility-scale solar electricity has fallen faster and further than almost any energy technology in history. In 2010, the global benchmark levelized cost of electricity (LCOE) was about \\$350 per MWh. By 2024, it had dropped below \\$30 per MWh in the most competitive markets, a decline of more than 90% in 14 years (Lazard, 2024).

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/solar-ccs-learning-curve.png" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">Figure 1: Utility-scale solar LCOE and global installed capacity, 2010–2024. Data from Lazard (2024), IRENA (2023), and IEA (2024).</div>

This is not luck. It is a textbook example of **Wright's Law**: every time cumulative production doubles, the cost per unit falls by a predictable percentage, typically 15–25% for solar (Kavlak et al., 2018). Global solar capacity has grown from about 40 gigawatts in 2010 to more than 1,700 gigawatts in 2024 (IEA, 2024), and each doubling has delivered another round of cost cuts.

The important point is not just that solar is cheap today. It is that solar keeps getting cheaper, and every project built now makes the next one cheaper still. For anyone allocating climate finance, the trajectory matters as much as the current price. A technology at \\$30 per MWh that is projected to reach \\$20 within a decade is a very different bet from one that costs \\$150 per ton today and shows no sign of improving.

## Carbon capture's track record

CCS has been deployed at commercial scale at only a handful of sites, and the flagship projects most often cited as proof of concept tell a more cautious story.

| Project          | Location                 | Design capture | What happened                                                                                                                                                         |
| ---------------- | ------------------------ | -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Boundary Dam** | Saskatchewan, Canada     | ~1 Mt CO₂/yr   | Early operation captured well below design because of repeated capture-unit problems; total cost about C\\$1.5 billion against an initial estimate of C\\$1.3 billion |
| **Petra Nova**   | Texas, USA               | ~1.4 Mt CO₂/yr | Captured about 3.9 million short tons over three years, then shut in 2020 when oil and power prices collapsed; restarted in 2023                                      |
| **Gorgon**       | Barrow Island, Australia | ~4 Mt CO₂/yr   | Injected about 30% of reservoir CO₂ over its first five years against a required 80%; Chevron bought offsets to cover the shortfall                                   |

<div class="caption">Table 2: Performance of three flagship CCS projects. Sources: MIT Carbon Capture & Sequestration Technologies Program; Manuilova et al. (2014); POWER Magazine (2023); Boiling Cold (2021); LNG Prime (2021).</div>

**Boundary Dam**, which opened in 2014 as the world's first commercial post-combustion CCS unit on a coal plant, was designed to capture about one million tonnes of CO₂ a year. Early on, repeated mechanical problems in the capture unit kept it running far below that (Manuilova et al., 2014).

**Petra Nova**, a retrofit on a coal plant near Houston, started in 2017 and sold its captured CO₂ for enhanced oil recovery. When oil and power prices collapsed in 2020, it was mothballed. It restarted in 2023, but the episode showed how tightly its business model was tied to fossil fuel prices rather than to climate value (Jenkins, 2015; POWER Magazine, 2023).

**Gorgon**, Chevron's liquefied natural gas project in Western Australia, was meant to be the world's largest demonstration of geological storage. Its state approval required it to inject at least 80% of the CO₂ stripped from its gas over a rolling five-year period. Delays in preparing injection wells, subsurface complications, and equipment problems meant it injected only about 30% over its first five years, while the LNG plant kept operating. Chevron ultimately bought carbon offsets to cover the shortfall (Boiling Cold, 2021; LNG Prime, 2021), which undercuts the idea that CCS delivers reliable, verifiable reductions at scale.

Taken together, these projects share a pattern: they are expensive to build, hard to run reliably, dependent on site-specific geology, and exposed to commodity prices that have nothing to do with their climate purpose.

## Why carbon capture has no learning curve

CCS has not followed Wright's Law, and the reason is not simply that it is too new or under-funded. It comes from what CCS physically is (Rubin et al., 2015).

A solar panel is a **manufactured product**. It is made in a factory under controlled conditions, and every process improvement and materials advance carries forward into the next panel off the line.

A CCS facility is an **engineering project**. It is designed for a specific source of CO₂ at a specific geological site, with capture chemistry tailored to that source's flue gas. The compressors, absorption columns, pipelines, and injection wells cannot be standardized and copied the way solar panels can. Rubin et al. (2015), in the most comprehensive review of CCS learning rates, found that while some components get cheaper, total system costs show no consistent downward trend, because site-specific integration costs dominate. In effect, every CCS project is a first-of-its-kind project in its own setting.

## Running the numbers

To convert solar's electricity cost into a cost per ton of CO₂, I divide the LCOE by the emissions intensity of the grid it displaces:

$$
\text{LCCA} \ (\$/\text{t CO}_2) = \frac{\text{LCOE} \ (\$/\text{MWh})}{\text{Grid emissions intensity} \ (\text{t CO}_2/\text{MWh})}
$$

| Scenario                 | Grid intensity | Solar LCOE                   | Solar cost per ton    |
| ------------------------ | -------------- | ---------------------------- | --------------------- |
| S1: U.S. grid, today     | 0.367 t/MWh    | \\$30/MWh (Lazard, 2024)     | **about \\$82/t CO₂** |
| S2: U.S. grid, projected | 0.367 t/MWh    | \\$20/MWh (Way et al., 2022) | **about \\$55/t CO₂** |
| S3: Coal-heavy grid      | 0.9 t/MWh      | \\$30/MWh (Lazard, 2024)     | **about \\$33/t CO₂** |

<div class="caption">Table 3: Solar's cost of carbon abatement under three grid scenarios.</div>

For CCS, the best case in the peer-reviewed literature is about \\$100 per ton, at high-concentration sources such as natural gas processing or fertilizer production where the CO₂ stream is already fairly pure (Bui et al., 2018). For capture at coal or gas power plants, the application that competes directly with solar, the realistic range is \\$150–300 per ton (Rubin et al., 2015; Global CCS Institute, 2023).

| Comparison                                  | Solar   | CCS      | CCS costs this much more |
| ------------------------------------------- | ------- | -------- | ------------------------ |
| Best-case CCS vs. solar today (U.S. grid)   | \\$82/t | \\$100/t | **1.2×**                 |
| Best-case CCS vs. projected solar (U.S.)    | \\$55/t | \\$100/t | **1.8×**                 |
| Typical CCS (low) vs. solar today (U.S.)    | \\$82/t | \\$150/t | **1.8×**                 |
| Typical CCS (low) vs. solar on a coal grid  | \\$33/t | \\$150/t | **4.5×**                 |
| Typical CCS (high) vs. solar on a coal grid | \\$33/t | \\$300/t | **9.1×**                 |

<div class="caption">Table 4: How much more CCS costs per ton of CO₂ than solar across scenarios.</div>

Even under the most optimistic assumptions for CCS, solar cuts a ton of CO₂ more cheaply. In the least favorable comparison, CCS costs about nine times as much. And because solar is still on its learning curve, the gap is more likely to widen than to close.

## Why carbon capture keeps getting funded

If CCS costs so much more, why does it attract so much public money? In my view, the answer has less to do with technical merit than with who benefits. CCS spending flows mainly to fossil fuel producers, pipeline operators, and oilfield service companies; solar spending flows to manufacturers, installers, and electricity customers (McLaren & Markusson, 2020; Stephens, 2014).

| Who benefits                | Why they favor CCS                                                         | How they benefit                                        |
| --------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------- |
| **Fossil fuel producers**   | CCS offers a climate rationale for continued extraction                    | Preserves the value of reserves and infrastructure      |
| **Pipeline operators**      | CO₂ pipelines use the same skills and capital as gas pipelines             | A new revenue stream without stranded-asset risk        |
| **Enhanced oil recovery**   | Injected CO₂ pushes more oil out of mature fields                          | Two revenue streams: the 45Q tax credit and extra oil   |
| **Engineering contractors** | Bespoke, site-specific design commands higher margins than commodity solar | Long-term contracts and proprietary technology licenses |

<div class="caption">Table 5: Main beneficiaries of CCS investment. Sources: McLaren & Markusson (2020); Stephens (2014).</div>

Enhanced oil recovery deserves particular attention. When captured CO₂ is injected into an aging oil field to push out more crude, it can qualify for the same U.S. federal tax credit (known as 45Q) as permanent storage, even though some of the CO₂ resurfaces with the oil and has to be recaptured. The result is a public program that subsidizes oil production while counting as climate investment (Núñez-López & Moskal, 2019).

CCS also plays a strategic role. By offering a credible-sounding path to "clean" fossil fuels, it lets producers argue that coal plants, gas fields, and oil infrastructure need not be retired quickly. Green (2018) examines how norms against fossil fuels emerge and are resisted, and CCS fits that pattern: the climate result is slower decarbonization, while the financial result is preserved asset values.

## Where carbon capture is essential

None of this means CCS should be abandoned. It is over-funded as a tool for cutting bulk electricity emissions, but under-developed for the jobs only it can do.

**Heavy industry.** In cement, steel, and chemicals, CO₂ comes from the chemistry itself, not just from the energy used. Solar cannot remove it.

| Sector        | Why solar cannot substitute                                                                                                      | Role of CCS                                                                                     | Share of global CO₂ |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------- |
| **Cement**    | CO₂ is released when limestone is heated and breaks down, not just from burning fuel                                             | Capturing process CO₂ at the kiln is currently the only large-scale option                      | ~8%                 |
| **Steel**     | Primary steelmaking uses carbon as a chemical reducing agent; green hydrogen routes are emerging but not yet at commercial scale | Capture at blast furnaces can cut emissions until hydrogen-based steel becomes cost-competitive | ~7%                 |
| **Chemicals** | Many processes need carbon feedstocks or release CO₂ as a by-product regardless of energy source                                 | Capture at ammonia, ethylene, and methanol plants is already cost-competitive in some markets   | ~4%                 |

<div class="caption">Table 6: Industrial sectors where CCS complements rather than competes with solar.</div>

Together, these sectors account for roughly a fifth of global emissions. Here, CCS complements renewable energy rather than competing with it (Davis et al., 2018).

**Carbon removal.** The IPCC now treats overshooting 1.5 °C as the likely outcome, and every pathway back below that threshold requires physically pulling CO₂ out of the atmosphere (IPCC, 2022). Solar cannot do that. The geological storage infrastructure and regulations needed for large-scale removal take decades to build, so that work needs to start now (Minx et al., 2018).

## The bottom line

Solar has crossed a threshold. At under \\$30 per MWh in competitive markets and still falling, it cuts CO₂ far more cheaply than CCS, and its advantage is growing. CCS, by contrast, has shown no consistent learning curve, its flagship projects have fallen short, and, in my view, its public support in the United States reflects the influence of fossil fuel interests more than climate cost-effectiveness.

But CCS still has an essential role. Cement, steel, and chemicals release CO₂ that electricity cannot eliminate, and reversing temperature overshoot will require removing CO₂ from the air. For those jobs, CCS investment is not just justified but necessary.

The policy implication is clear. Public climate funding, especially the 45Q tax credit, should be redirected so that it supports CCS where there is no alternative: industrial capture and the storage infrastructure needed for future carbon removal. It should stop subsidizing CCS as a large-scale emissions fix in power generation, where solar does the job better and more cheaply.

The broader lesson is about method. Climate investment decisions made without a careful comparison of costs will be shaped by whoever has the most power to shape them. A better starting point is the question at the center of this post: what does each technology deliver for the climate, per dollar spent?

---

## References

- Boiling Cold (2021, July 16). [Time's up on Gorgon's five years of carbon storage failure](https://www.boilingcold.com.au/times-up-on-gorgons-five-years-of-carbon-storage-failure/).
- Bui, M., et al. (2018). [Carbon capture and storage (CCS): The way forward](https://doi.org/10.1039/C7EE02342A). _Energy & Environmental Science_, 11(5), 1062–1176.
- Davis, S. J., et al. (2018). [Net-zero emissions energy systems](https://doi.org/10.1126/science.aas9793). _Science_, 360(6396), eaas9793.
- Fasihi, M., Efimova, O., & Breyer, C. (2019). [Techno-economic assessment of CO₂ direct air capture plants](https://doi.org/10.1016/j.jclepro.2019.03.086). _Journal of Cleaner Production_, 224, 957–980.
- Global CCS Institute (2023). _Global Status of CCS 2023_.
- Green, F. (2018). [Anti-fossil fuel norms](https://doi.org/10.1007/s10584-017-2134-6). _Climatic Change_, 150, 103–116.
- IEA (2021). [Net Zero by 2050: A Roadmap for the Global Energy Sector](https://www.iea.org/reports/net-zero-by-2050).
- IEA (2023). [World Energy Investment 2023](https://www.iea.org/reports/world-energy-investment-2023).
- IEA (2024). [Renewables 2024: Analysis and Forecast to 2030](https://www.iea.org/reports/renewables-2024).
- IPCC (2022). [Climate Change 2022: Mitigation of Climate Change](https://doi.org/10.1017/9781009157926). Contribution of Working Group III to the Sixth Assessment Report.
- IRENA (2023). [Renewable Power Generation Costs in 2022](https://www.irena.org/Publications/2023/Aug/Renewable-Power-Generation-Costs-in-2022).
- Jenkins, J. (2015). _Financing Mega-Scale Energy Projects: A Case Study of the Petra Nova Carbon Capture Project_. Paulson Institute.
- Kavlak, G., McNerney, J., & Trancik, J. E. (2018). [Evaluating the causes of cost reduction in photovoltaic modules](https://doi.org/10.1016/j.enpol.2018.08.015). _Energy Policy_, 123, 700–710.
- Lazard (2024). _Levelized Cost of Energy Analysis, Version 17_.
- LNG Prime (2021). [Chevron says to offset Gorgon CCS shortfall](https://lngprime.com/lng-terminals/chevron-says-to-offset-gorgon-ccs-shortfall/33579/).
- Manuilova, A., et al. (2014). Life cycle assessment of post-combustion CO₂ capture and CO₂-enhanced oil recovery based on the Boundary Dam Integrated Carbon Capture and Storage Demonstration Project in Saskatchewan. _Energy Procedia_, 63, 7398–7407.
- McLaren, D., & Markusson, N. (2020). [The co-evolution of technological promises, modelling, policies and climate change targets](https://doi.org/10.1038/s41558-020-0740-1). _Nature Climate Change_, 10, 392–397.
- Minx, J. C., et al. (2018). [Negative emissions, Part 1: Research landscape and synthesis](https://doi.org/10.1088/1748-9326/aabf9b). _Environmental Research Letters_, 13, 063001.
- MIT Carbon Capture & Sequestration Technologies Program. [Boundary Dam fact sheet](https://sequestration.mit.edu/tools/projects/boundary_dam.html).
- Núñez-López, V., & Moskal, E. (2019). [Potential of CO₂-EOR for near-term decarbonization](https://doi.org/10.3389/fclim.2019.00005). _Frontiers in Climate_, 1, 5.
- POWER Magazine (2023, September 13). [Petra Nova, pioneering power plant carbon capture unit, is up and running again, says JX Nippon](https://www.powermag.com/petra-nova-pioneering-power-plant-carbon-capture-unit-is-up-and-running-again-says-jx-nippon/).
- Rubin, E. S., Azevedo, I. M. L., Jaramillo, P., & Yeh, S. (2015). [A review of learning rates for electricity supply technologies](https://doi.org/10.1016/j.enpol.2015.06.011). _Energy Policy_, 86, 198–218.
- Stephens, J. C. (2014). [Time to stop investing in carbon capture and storage and reduce government subsidies of fossil-fuels](https://doi.org/10.1002/wcc.266). _WIREs Climate Change_, 5(2), 169–173.
- U.S. Energy Information Administration (2023). [How much carbon dioxide is produced per kilowatthour of U.S. electricity generation?](https://www.eia.gov/tools/faqs/faq.php?id=74&t=11)
- Way, R., Ives, M. C., Mealy, P., & Farmer, J. D. (2022). [Empirically grounded technology forecasts and the energy transition](https://doi.org/10.1016/j.joule.2022.08.009). _Joule_, 6(9), 2057–2082.
