# VID-001 Source-Method Review

**Work package:** WP-002  
**Review date:** 2026-09-20  
**Video:** VID-001 — *Why Data Centers Can't Just Plug Into the Grid*

## Review decision

The evidence base is strong enough to draft the final narration **if the video explains “connection” as a chain of physical, planning, operational, and contractual constraints rather than as a single queue**.

The most important correction from reading the full Berkeley Lab `Speed to Power` report is terminological:

- **connection** is the broad problem of obtaining electric service for a large load;
- **interconnection** is the narrower study/process for attaching that load to transmission or distribution.

A data center can therefore face a bottleneck even when the problem is not simply “there is no power plant” or “it is stuck in an interconnection queue.”

## Primary sources reviewed

### 1. Lawrence Berkeley National Laboratory — Speed to Power

Full report:
https://eta-publications.lbl.gov/sites/default/files/2026-06/lbnl_large_loads_speed_to_power_final_1.pdf

Publication page:
https://emp.lbl.gov/publications/speed-power-solutions-accelerating

The June 2026 report is a document/literature review aimed primarily at regulators. It identifies **41 potential solutions** grouped into five broad functions:

1. load forecasting;
2. interconnection;
3. utility procurement;
4. markets and operations;
5. cost allocation and ratemaking.

The report explicitly says:
- the list is not exhaustive;
- the solutions are not recommendations or a roadmap;
- some are region-specific;
- some are mutually exclusive;
- permitting and generator-interconnection reform are largely outside its scope.

**Editorial consequence:** the video may describe the categories of bottlenecks. It may not present Berkeley Lab's 41 ideas as proven fixes or a nationally applicable prescription.

### 2. Portland General Electric — current large-load study process

https://portlandgeneral.com/builders-new-construction/large-load-study

PGE currently requires a Large Load Study for requests of **1 MW or greater**. Its process may include:
- pre-feasibility;
- feasibility;
- system-impact study;
- facilities study.

PGE says the studies depend on load size, location, system capacity and complexity. Its published estimated study timelines range from days for pre-feasibility to months for later phases; cluster studies can take longer.

PGE also states that completing the studies does **not** guarantee that the full requested load can be delivered on the requested timeline. Constraints can include available transmission, project timelines, long-lead items and available flexibility.

### Version-change warning

Berkeley Lab's June report reproduces an earlier PGE process in which the cluster-study threshold is described differently from the current PGE webpage. This is useful evidence that procedures themselves can change.

**Editorial consequence:** if PGE appears in narration, date the example and avoid presenting its threshold or timeline as a permanent national standard.

### 3. American Transmission Company — direct load-interconnection guide

ATC customer/interconnection page:
https://www.atcllc.com/customer-engagement/

Direct guide surfaced in the review:
https://www.atcllc.com/wp-content/uploads/Load-Interconnection-Guide_Rev-13_final_022124.pdf

ATC's guide provides a useful bounded illustration of why a connection can take far longer than a study alone. It states that its planning/Best Value Planning work can typically take roughly **6–18 months**, while construction after the appropriate project documentation can vary with required work:
- around 18–30 months for certain short transmission-line extensions;
- 30–48 months for longer line extensions;
- 48–60 months for projects involving items such as transmission power transformers, gas-insulated substations, underground transmission, long-lead equipment, major system reinforcements or certain state approvals.

These are **ATC process ranges**, not national data-center wait-time statistics.

**Narration decision:** this is the strongest bounded timeline example if the final script needs to explain how a “study” can become a multi-year physical project.

### 4. Berkeley Lab — Electricity Rate Designs for Large Loads, 2026 Update

Publication:
https://eta.lbl.gov/publications/electricity-rate-designs-large-0

Technical brief:
https://eta-publications.lbl.gov/sites/default/files/2026-08/rate_designs_large_loads_2026.08.10.pdf

The authors analyzed **55 large-load tariffs/frameworks**, primarily from Halcyon's tracker and supplemented with independent research.

Common mechanisms include:
- minimum demand thresholds;
- minimum contract durations;
- demand charges;
- minimum billing demand/minimum bills;
- collateral;
- direct assignment of certain costs.

The sample is not every U.S. tariff. The report categorizes how common elements are in its reviewed sample and how adoption has changed.

**Editorial consequence:** the video can explain *why* utilities may require long contracts, minimum payments or collateral: large-load service can trigger infrastructure/resource commitments that become stranded if a project is delayed, smaller than expected or abandoned. Do not claim all utilities impose the same terms and do not predict a viewer's household bill from this report.

### 5. Berkeley Lab — U.S. Data Center Energy Usage Report: 2025 Update

Publication page:
https://eta.lbl.gov/publications/united-states-data-center-energy-2025

DOE/OSTI record:
https://www.osti.gov/biblio/3374245

The report's public metadata describes a **bottom-up** model using planned IT-equipment shipments, modeled per-device electricity use, cooling simulations and information on facility types/locations.

Key 2030 U.S. outputs:
- Reference Case: **649 TWh**;
- Compounded Uncertainty scenarios: **521–843 TWh**;
- Reference Case share of U.S. electricity: **11.8%**;
- scenario share: **9.5%–15.3%**.

The scenario range is produced through sensitivity/uncertainty assumptions. It must **not** be described as a statistical confidence interval.

The full report PDF was not reliably retrievable through the research interface in this pass, so the script should rely only on the methods/results exposed in the official LBNL/DOE records unless the full PDF is reviewed separately.

### 6. IEA — Key Questions on Energy and AI

https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary

The April 2026 IEA outlook estimates global data-center electricity consumption at **485 TWh in 2025** and projects about **950 TWh in 2030**, roughly doubling. It projects electricity consumption from AI-focused data centers to grow faster, roughly tripling over the period.

The IEA explicitly links near-term expansion constraints to grid connections, planning/regulatory systems, energy-equipment supply chains, chips and capital.

**Editorial consequence:** use IEA data to establish scale after the viewer understands the physical connection problem. Do not call the total-data-center series “AI electricity.”

### 7. Berkeley Lab — Integrating AI Data Centers with the Power Grid

https://eta.lbl.gov/publications/integrating-ai-data-centers-power

The May 2026 article describes four broad flexibility mechanisms:
- computational load shifting;
- flexible facility/infrastructure operation;
- storage;
- onsite generation.

The article also says demand flexibility is **not a substitute for the long-term need for bulk generation**.

**Editorial consequence:** present flexibility as conditional and workload/site-specific, not as “AI can simply shut off whenever the grid is busy.”

---

## What the full source review says the bottleneck actually is

A large load connection can fail, slow down or become expensive at several distinct layers.

### Layer 1 — Is the request itself credible?

Utilities and planners can receive speculative, duplicated or uncertain project requests. Forecasting errors can lead to overbuilding or underbuilding.

### Layer 2 — What does the local grid experience if the load appears?

Impact studies examine whether transmission/distribution facilities can serve the requested load while meeting reliability requirements.

### Layer 3 — What must physically be built or upgraded?

A facilities study identifies equipment and network upgrades. Even after studies and agreements, substations, transformers, lines and other facilities may need to be designed, procured and constructed.

### Layer 4 — Is enough supply/capacity available reliably?

A connection is not just copper reaching the property. Generation, transmission and distribution capacity must be adequate under the applicable service arrangement.

### Layer 5 — Can the system operate reliably with the load?

Large loads can have operational characteristics that affect reserves, ramping, power quality and other reliability needs. Flexibility can help in some cases.

### Layer 6 — Who pays if the project changes?

A utility may invest based on a customer's expected demand. If the project is delayed, scales more slowly, uses less than expected, never opens or closes early, some investment can become underused or stranded. Tariffs, contracts and collateral are tools used to allocate that risk.

This six-layer structure is a **video explanatory framework created for VID-001**. It is not a direct Berkeley Lab taxonomy. It is derived from the report's functional areas and should be labeled as our simplification.

---

## Timeline finding: studies versus end-to-end construction

The sources support an important distinction:

- Within the formal interconnection process, studies can be a major time-consuming component.
- Across the **end-to-end connection**, physical network construction can take substantially longer.

Berkeley Lab notes that study duration varies with load size, configuration and location, and separately notes that network-upgrade/interconnection-facility construction is often the longest end-to-end step.

This resolves an apparent tension in the report and is useful for the script: **finishing the paperwork/study does not mean the site can be energized immediately.**

---

## Bounded narrative example selected

### ATC large-load connection timeline

If the final script needs one concrete timeline example, use ATC and label it clearly:

> One U.S. transmission utility's own guide illustrates the difference between planning and construction: planning can take roughly 6–18 months, while more complex transmission construction can extend into multi-year ranges.

Then explain one or two examples from the guide rather than giving a generic national wait time.

Do **not** say:
- “data centers take 5 years to connect”;
- “the average wait is X years”;
- “every utility follows ATC's process.”

ATC is an illustration, not a national statistic.

---

## Claims safe for final narration

### Safe with normal qualification

- A nearby power line does not guarantee that a large new load can receive the amount of reliable service it wants on its preferred schedule.
- Large-load connection involves more than one engineering study.
- Utilities may need to examine transmission/distribution impacts and identify network upgrades.
- Physical construction can outlast study timelines.
- Large-load growth creates forecasting and financial risks as well as engineering constraints.
- Utilities use contracts/tariffs to manage risks that arise if a large load arrives late, scales differently or leaves.
- Some data-center loads can provide flexibility, but the available flexibility depends on workloads, facility systems and commercial arrangements.
- Global and U.S. data-center electricity consumption are projected to rise substantially, with material uncertainty.

### Safe only as a dated, named example

- PGE's current study thresholds and study timelines.
- ATC's planning/construction ranges.
- Specific tariff terms for a named utility.
- Any queue size or local capacity figure.

### Not safe / exclude

- A universal U.S. data-center connection wait time.
- Generator-interconnection queue statistics presented as data-center load queues.
- “The grid has no electricity” as the generic explanation.
- “Batteries solve the problem” without power/energy-duration and recharge caveats.
- “AI workloads can always pause.”
- Claims that Berkeley Lab's 41 solution ideas are proven or recommended everywhere.
- Claims that 521–843 TWh is a 95% confidence interval.
- Claims that all data-center demand is AI demand.
- Claims about a specific household-rate impact without local causal evidence.
- Invented transformer delivery times or construction durations.
- The previously unverified DOE $1.9 billion announcement.

---

## Visual implications

### Original diagram

Create an original progressive diagram:

```
GENERATION / SUPPLY
        ↓
TRANSMISSION
        ↓
SUBSTATION / TRANSFORMERS
        ↓
DISTRIBUTION OR DIRECT HIGH-VOLTAGE SERVICE
        ↓
DATA-CENTER SITE
```

Overlay six questions as the story progresses:
1. Is the requested load credible?
2. What does it do to the system?
3. What needs to be built?
4. Is reliable capacity available?
5. How flexible/operationally compatible is it?
6. Who bears the investment risk?

This diagram is our synthesis and should not reproduce Berkeley figures.

### Forecast chart

If used, create an original two-bar/simple line graphic and clearly label:
- geography;
- all data centers versus AI-focused data centers;
- observed/estimated year versus projected year;
- source and date.

Do not combine IEA global numbers and Berkeley U.S. numbers into one implied continuous series.

---

## WP-002 conclusion

The source base is adequate for final script drafting.

The strongest story is **not** “AI uses a lot of electricity, therefore grids are overwhelmed.” It is:

> A data center can be close to electricity infrastructure and still lack a usable high-capacity service path, because reliable service is the outcome of planning, studies, equipment, construction, available capacity, operating rules and financial commitments all lining up.

That is the explanatory promise the final narration should deliver.
