# VID-001 Source and Claim Ledger

**Video:** VID-001 — Why Data Centers Can't Just Plug Into the Grid  
**Source review date:** 2026-09-20  
**WP-002 status:** full connection/rate-design review completed

“Verified” means the cited source supports the bounded statement. It does not mean every underlying model was independently replicated.

| ID | Source-grounded statement | Evidence and limits |
|---|---|---|
| C01 | IEA's April 2026 outlook puts global data-center electricity use at 485 TWh in 2025 and projects about 950 TWh in 2030. | IEA, *Key Questions on Energy and AI*. All data centers; 2030 is a projection. https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary |
| C02 | The same IEA outlook projects AI-focused data-center electricity consumption to roughly triple from 2025 to 2030. | Same source. Do not label the total-data-center series “AI electricity.” |
| C03 | Grid connections, planning/approval systems, energy-equipment supply chains, advanced chips and financing are among the bottlenecks constraining near-term data-center expansion. | IEA April 2026 report/release. Do not convert this into a universal connection wait time. https://www.iea.org/news/data-centre-electricity-use-surged-in-2025-even-with-tightening-bottlenecks-driving-a-scramble-for-solutions |
| C04 | Berkeley Lab's U.S. 2025 Update gives a 2030 Reference Case of 649 TWh and Compounded Uncertainty scenarios of 521–843 TWh, corresponding to 11.8% reference and 9.5–15.3% scenario share of U.S. electricity. | Official LBNL/DOE metadata. Bottom-up model uses planned IT shipments, modeled device electricity use, cooling simulations and facility information. The range is scenario/uncertainty analysis, not a statistical confidence interval. https://eta.lbl.gov/publications/united-states-data-center-energy-2025 |
| C05 | Berkeley Lab uses “connection” for the broader problem of receiving electric service and “interconnection” for the narrower interconnection process. | *Speed to Power*, June 2026, Executive Summary footnote. This distinction should govern the script. https://eta-publications.lbl.gov/sites/default/files/2026-06/lbnl_large_loads_speed_to_power_final_1.pdf |
| C06 | Large-load connection challenges span forecasting, process coordination, interconnection uncertainty, capacity adequacy, operational impacts, and cost-shifting/stranded-cost risks. | *Speed to Power*, §§2.1–2.2. The report identifies 41 potential solutions across five broad functional areas. |
| C07 | Berkeley Lab's 41 solutions are illustrative potential opportunities, not recommendations or a universal roadmap; some are regional or mutually exclusive. | *Speed to Power*, Executive Summary and §2.2. |
| C08 | Load interconnection studies typically include impact and facilities studies; their timelines vary with load size, configuration complexity and location. | *Speed to Power*, §4.2.1. |
| C09 | End-to-end connection can require construction of interconnection facilities and network upgrades after studies/service agreements; construction can be costly and time-consuming. | *Speed to Power*, §§2.3 and 4.2.5. |
| C10 | ATC provides a bounded example in which planning can take about 6–18 months and construction ranges from roughly 18–60 months depending on required transmission work and approvals. | American Transmission Company Load Interconnection Guide. This is one utility/transmission-provider example, not a U.S. average and not data-center-specific. https://www.atcllc.com/customer-engagement/ |
| C11 | PGE currently studies new/expanded loads at 1 MW or greater and says completing required studies does not guarantee the full requested load on the requested timeline. | Current PGE Large Load Study Process. Its procedures/timelines are utility-specific and can change. https://portlandgeneral.com/builders-new-construction/large-load-study |
| C12 | Large-load tariffs/service agreements are used to manage operational and financial risks, including underutilized/stranded investment risk. | Berkeley Lab, *Electricity Rate Designs for Large Loads: 2026 Update*. Sample covers 55 tariffs/frameworks, not every U.S. utility. https://eta-publications.lbl.gov/sites/default/files/2026-08/rate_designs_large_loads_2026.08.10.pdf |
| C13 | In Berkeley Lab's tariff sample, mechanisms include minimum contract terms, minimum billing demand/bills, collateral and direct assignment of certain costs. | Same source. Do not claim every utility uses all mechanisms. |
| C14 | Flexibility options for AI data centers include computational shifting, facility/infrastructure adjustments, storage and onsite generation. | Granderson et al., *The Bridge*, May 2026. Applicability depends on workloads and facility/market arrangements. https://eta.lbl.gov/publications/integrating-ai-data-centers-power |
| C15 | Data-center demand flexibility does not eliminate the long-term need for bulk generation and grid infrastructure. | Same source. Avoid “AI can just turn off” framing. |
| C16 | Grid delivery uses transmission, substations/transformers and distribution, while operators continually balance electricity supply and demand. | U.S. EIA, *Delivery to consumers*. https://www.eia.gov/energyexplained/electricity/delivery-to-consumers.php |
| C17 | Electricity storage has separate power and energy ratings and must be charged. | U.S. EIA, *Energy storage for electricity generation*. Historical capacity totals on that page should not be presented as 2026 current totals. https://www.eia.gov/energyexplained/electricity/energy-storage-for-electricity-generation.php |

## Editorial safeguards

- Use **connection** for the broad service problem and **interconnection** for the narrower process.
- Keep global IEA figures separate from U.S. Berkeley Lab figures.
- Do not average unrelated forecasts.
- A scenario/uncertainty range is not automatically a statistical confidence interval.
- Do not substitute generator-interconnection queue statistics for large-load connection evidence.
- Separate MW (power) from MWh/TWh (energy).
- Avoid universal “energy per AI prompt” claims.
- Do not state a universal data-center connection wait time.
- Any timeline must name/date the utility/provider whose process it describes.
- The ATC ranges are a bounded example, not an average.
- PGE's current process differs in details from the version reproduced in Berkeley Lab's June report; procedures can change.
- Flexibility is conditional and cannot be assumed for every workload.
- Berkeley Lab's 41 solutions are not a list of universally recommended fixes.
- The previously supplied DOE $1.9 billion announcement remains excluded because it was not verified in the launch packet.

## Narrative-use decision

If the script needs one concrete wait-time illustration, use **ATC** as the named bounded example. Keep PGE as supporting evidence for the multi-stage study process and the fact that a completed study does not guarantee the requested demand/timeline.

Full reasoning:
`research/VID-001_SOURCE_METHOD_REVIEW.md`
