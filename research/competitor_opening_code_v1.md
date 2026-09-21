# Competitor Opening Structure Coding v1

**Work package:** WP-001  
**Date:** 2026-09-20  
**Purpose:** examine a small balanced subset of long-form videos for observable opening structure. This is not a retention study because competitor retention data are unavailable.

## Coding rules

Record only what was actually available from a direct transcript, creator-hosted transcript, or clearly identified public transcript/episode source.

Do **not**:
- infer private retention from public views;
- infer that an opening caused a video's performance;
- invent exact words when only a summary is available;
- treat a thumbnail as coded unless it was independently inspected.

## Coded examples

### Practical Engineering — Stopping the Unstoppable

**Video:** https://www.youtube.com/watch?v=-17mPnFxi30  
**Published:** 2026-09-01  
**Duration:** ~15:46  
**Public-performance context:** substantially higher public view total than several adjacent uploads in the retrieved snapshot.

**Opening structure observed from creator-hosted transcript:**
1. concrete real-world failure: a 2016 Hoboken train crash;
2. closely related 2017 crash;
3. immediate human consequences;
4. apparent cause: operators fell asleep;
5. reframing: the end of a rail line is a special engineering problem;
6. misconception correction: ordinary static bumping posts were not designed to stop a fully powered passenger train;
7. promise: explain/model how this problem is engineered.

**Pattern label:** case first → surprise/reframe → hidden mechanism.

Creator-hosted transcript:
https://practical.engineering/blog/2026/9/1/stopping-the-unstoppable

### Practical Engineering — Bridge Demolition Is Complicated

**Video:** https://www.youtube.com/watch?v=7oi4yMr8Rjk  
**Published:** 2026-06-16  
**Duration:** ~17:56  
**Public-performance context:** lower public view total than *Stopping the Unstoppable* in the retrieved snapshot.

**Opening structure observed from creator-hosted transcript:**
1. introduces replacement I-74 bridges and the fact that old bridges remain;
2. establishes why removal is required;
3. invokes the intuitive “just smash/blow it up” idea;
4. reverses that intuition: demolition can be more complicated than designing a new structure;
5. promises a case study and later visual payoff.

**Pattern label:** project context → intuitive misconception → contradiction → mechanism.

Creator-hosted transcript:
https://practical.engineering/blog/2026/6/16/how-to-demolish-a-bridge

### Wendover Productions — Why Texas Wins

**Video:** https://www.youtube.com/watch?v=dzmoALgtB1Q  
**Published:** 2026-08-04

**Opening structure observed from public episode transcript:**
1. narrative scene: Dutch football fans walking through Houston;
2. emphasizes shade, canals, transit, and walkability;
3. reveal: this is Houston, a place stereotyped as car-oriented/unwalkable;
4. broadens into Texas's growth and the video's larger explanation.

The macro thesis becomes clear only after the narrative setup.

**Pattern label:** scene → expectation violation → thesis.

Public transcript source:
https://podscan.fm/podcasts/wendover-productions/episodes/why-texas-wins

### Asianometry — Has the Solid State Transformer’s Time Finally Come?

**Video:** https://www.youtube.com/watch?v=Oytqz3zuB7w  
**Published:** 2026-08-24  
**Duration:** ~20:34

**Opening structure observed from public episode text:**
1. asks how to replace technology that has been battle-tested for more than a century;
2. introduces the solid-state-transformer challenger;
3. notes that the technology has repeatedly appeared “almost ready” for decades;
4. asks whether AI data centers could finally create the use case that changes that.

**Pattern label:** durable incumbent → long-hyped challenger → repeated failure to break through → new catalyst question.

Public episode source:
https://www.listennotes.com/podcasts/asianometry/has-the-solid-state-uaicJTEPm_2/

### Asianometry — True 3D DRAM

**Video:** https://www.youtube.com/watch?v=byWZoKCdePo  
**Published:** 2026-07-26  
**Duration:** ~20:49

**Opening structure observed from public transcript/summary source:**
1. states the technical problem: conventional DRAM scaling has slowed;
2. points to stacking as one of the remaining density paths;
3. invokes 3D NAND as a successful analogy;
4. asks whether the same idea can work for DRAM;
5. immediately introduces the constraint: stacking DRAM cells is not straightforward.

**Pattern label:** technical bottleneck → successful analogy → question → constraint.

Public transcript/summary source:
https://tuberizer.com/share/asianometry/true-3d-dram/byWZoKCdePo

### Engineering with Rosie — Why is China Dominating Ultra High Voltage DC?

**Video:** https://www.youtube.com/watch?v=1CVlbBYl5OU  
**Published:** 2024-05-30  
**Duration:** 11:03

**Opening structure observed from public transcript:**
1. vivid geographic thought experiment: could afternoon solar power in Perth serve Sydney later in the day?;
2. introduces ultra-high-voltage DC as the long-distance transmission mechanism;
3. establishes that China leads deployment;
4. asks why countries such as the U.S. and Australia have not adopted it at similar scale.

**Pattern label:** intuitive hypothetical → technology reveal → global comparison → why-question.

Public transcript source:
https://lilys.ai/notes/399226

### Engineering with Rosie — Australia’s Solar Boom Is Breaking the Grid - Or Is It?

**Video:** https://www.youtube.com/watch?v=qavFbOpt4jA  
**Published:** 2025-11-08  
**Duration:** 14:38

**Opening structure from public video metadata/timestamps:**
- starts from Australia's unusually high solar penetration;
- frames intuitive system questions around evening demand, midday price pressure, and the retirement of traditional synchronous generation;
- moves into batteries and grid-forming inverters.

**Pattern label:** success creates new problem → intuitive system questions → technical solutions.

Because a full verified transcript was not retrieved in this pass, no exact wording is recorded.

## Cross-example observations

The coded openings repeatedly do one or more of the following before heavy technical detail:
- start with a concrete event or vivid hypothetical;
- expose a contradiction or mismatch with intuition;
- make the viewer understand the problem before naming the technical machinery;
- state or imply a specific explanatory promise.

The examples differ substantially in pacing. Some reach the mechanism almost immediately; others use a longer narrative reveal. Public views alone cannot determine which pacing caused more retention.

## VID-001 implication

The current VID-001 opening should preserve this order:

1. **Concrete project:** land, building plan, computers.
2. **Simple question:** “Where do you plug it in?”
3. **Contradiction:** a visible nearby power line is not the same as a usable high-capacity connection.
4. **Mechanism promise:** follow the path from generation/grid infrastructure to the site's actual service.
5. **Scale evidence later:** introduce global/U.S. electricity projections only after the physical problem is understood.

This is an editorial hypothesis supported by descriptive competitor observations and the project's source ledger. It is not a claim of proven retention optimization.

## Thumbnail coding status

Systematic thumbnail coding remains **not independently verified in this pass**. No thumbnail findings are used as causal evidence.

The existing VID-001 thumbnail hypothesis remains a design hypothesis because it visually depicts the title's promised mechanism:
- data-center building
- grid/substation
- visible connection gap
- optional text: **WAITING FOR POWER**

A future design-review task can compare actual thumbnail screenshots if needed.
