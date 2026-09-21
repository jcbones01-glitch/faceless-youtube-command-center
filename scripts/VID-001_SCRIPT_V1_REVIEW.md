# VID-001 Script V1 — Review Version

**Working title:** Why Data Centers Can't Just Plug Into the Grid  
**Status:** factual-review draft  
**Important:** bracketed claim IDs refer to research/VID-001_SOURCE_LEDGER.md and are not narration.

---

## OPEN — THE GIANT OUTLET THAT DOESN'T EXIST

Imagine a company has picked a site for a new data center. The land is ready. The building has been designed. The computers are coming.

And just beyond the property, there are power lines.

So the last step sounds almost ridiculous:

**Where do you plug it in?**

This project is fictional, but the problem is real.

At the scale of a major new electrical load, a nearby line is not the same thing as a usable connection. The power system still has to determine whether it can serve that load reliably, what equipment or network upgrades are required, and how the project fits alongside everything already using the grid. [C05][C06][C08][C16]

There is no giant wall socket waiting for a data center.

And that simple fact explains one of the strangest bottlenecks in the AI boom.

---

## 1 — WHY THIS QUESTION IS GETTING BIGGER

The International Energy Agency estimates that data centers worldwide used about 485 terawatt-hours of electricity in 2025. Its 2026 outlook projects roughly 950 terawatt-hours in 2030 — close to double. Electricity use from AI-focused data centers is projected to grow even faster, roughly tripling over that period. [C01][C02]

Those are projections, not destiny. The IEA itself says near-term growth is being constrained by things such as grid connections, planning and regulatory systems, energy-equipment supply chains, chips and financing. [C03]

In the United States, Berkeley Lab's 2026 update gives a 2030 reference case of 649 terawatt-hours, with compounded uncertainty scenarios ranging from 521 to 843. That range is a set of modeled uncertainty scenarios — not a statistical confidence interval. [C04]

So the question is not only whether the world can generate more electricity.

It is whether electricity can actually reach the right sites, at the required scale, under conditions the grid can reliably support.

---

## 2 — WHAT “CONNECTED” REALLY MEANS

Electricity reaches customers through a system: generation, high-voltage transmission, substations and transformers, and then distribution or direct high-voltage service to large customers. Operators also have to keep supply and demand balanced as the system changes moment by moment. [C16]

Berkeley Lab makes an important distinction.

It uses **interconnection** for the narrower process of studying and attaching a load to the transmission or distribution system.

But it uses **connection** more broadly: everything required for that large customer to actually receive electric service. [C05]

That broader problem can be broken into six questions.

Is the requested load real enough to plan around?

What will it do to the local transmission and distribution system?

What new equipment has to be built?

Is there enough reliable generation and network capacity to serve it?

Can the system operate reliably with the way that load behaves?

And who bears the cost if the project arrives late, grows more slowly than expected, or never reaches the demand it originally requested? [C06][C12][C13]

That is a much bigger problem than finding the nearest power line.

---

## 3 — FIRST, THE GRID HAS TO STUDY THE REQUEST

Consider Portland General Electric in Oregon.

PGE's current process says that new or expanded loads of one megawatt or more go through its Large Load Study process. Depending on the project, that can include pre-feasibility, feasibility, a system-impact study and a facilities study. [C11]

The names matter because each phase answers a different question.

A system-impact study asks what the proposed load would do to the safety and reliability of the existing network.

A facilities study goes one step further: if upgrades are required, what equipment, engineering, procurement and construction work will be needed?

And PGE explicitly warns that even completing the studies does not guarantee that the full requested demand can be delivered on the customer's requested timeline. Available transmission, project schedules, long-lead equipment and load flexibility can all matter. [C11]

So even before construction starts, “Can I get power here?” has become an engineering and planning problem.

---

## 4 — THEN THE STUDY CAN TURN INTO A CONSTRUCTION PROJECT

This is where the phrase “waiting for power” can become misleading.

Sometimes the wait is not for electricity to exist.

It is for the physical path to the site to be made capable of carrying it.

Berkeley Lab notes that after a service agreement, a large customer may still need the facilities that physically connect it to the grid, plus transmission or distribution upgrades required to serve the load reliably. Those projects can be expensive and time-consuming. [C09]

One transmission company shows how wide that gap can become.

American Transmission Company — ATC — says in its own load-interconnection guide that its planning work can typically take roughly six to eighteen months. After the project reaches construction, certain transmission-line extensions can take roughly eighteen to thirty months. More complex projects involving longer lines, transmission transformers, gas-insulated substations, underground transmission, major reinforcements or certain regulatory approvals can fall into ranges as long as forty-eight to sixty months. [C10]

That is one provider's process, not a national average and not a universal data-center wait time.

But it illustrates the mechanism.

A study can discover that the “plug” you need is actually a substation upgrade, a transformer, a new line, or a larger transmission project.

And those are physical things that have to be engineered, procured, approved and built.

---

## 5 — WHY NOT JUST BUILD EVERYTHING IN ADVANCE?

Because the grid has another problem: uncertainty.

Imagine our fictional data center asks for a very large amount of capacity. The utility plans around that request, orders equipment and builds infrastructure.

Then the project is delayed.

Or it opens at a fraction of the expected load.

Or its technology changes and it needs less electricity than forecast.

Or the project never opens at all.

The infrastructure does not disappear when the forecast changes.

Berkeley Lab identifies this as part of the cost-shifting and stranded-cost problem around large loads. [C06][C12]

That is why the connection can involve economics and contracts as well as engineering.

In a 2026 review of 55 large-load tariffs and related frameworks, Berkeley Lab found mechanisms such as minimum contract terms, minimum billing requirements, collateral and direct assignment of some costs. They are different ways of answering the same basic question:

**If the grid makes a major investment for one customer, who takes the risk that the customer does not use it as expected?** [C12][C13]

Not every utility uses the same rules. But the existence of these rules tells us something important: getting power to a data center is also a commitment problem.

---

## 6 — CAN THE DATA CENTER BEND INSTEAD OF THE GRID?

Sometimes.

Researchers at Berkeley Lab describe several ways data centers can provide flexibility: shifting some computing tasks in time or location, adjusting facility systems, using energy storage, or operating onsite generation. [C14]

That can matter because a customer that can reduce or reshape its demand under certain conditions may be easier to integrate than a customer that requires its full requested power every second of the year.

But “data centers are flexible” is not a magic answer.

Different computing workloads have different timing and reliability requirements. The facility, contracts, market rules and onsite equipment all matter. And Berkeley Lab explicitly notes that demand flexibility does not replace the long-term need for bulk power generation. [C14][C15]

Batteries have the same limitation.

A battery has a **power** rating — how quickly it can deliver electricity — and an **energy** rating — how much it can deliver over time. It also has to be charged in the first place. [C17]

So a battery may help with peaks, short interruptions or flexible-service arrangements. It does not create a permanent new supply of electricity.

---

## 7 — RETURN TO THE “PLUG”

Now go back to our imaginary data center.

The power line next door was never the real question.

The real questions were hidden behind it.

Can the requested load be planned with confidence?

Can the existing network handle it?

What upgrades are required?

How long will those upgrades take to build?

Is enough reliable capacity available?

Can the load operate flexibly when useful?

And what commitments protect everyone if the project changes?

That is why a data center can be physically close to the grid and still be far away from usable power. [C05][C06][C08][C09][C12]

And it is why “just build more power plants” is only part of the answer.

More generation can matter. But a power plant does not eliminate the need for transmission, substations, transformers, studies, construction, operations and agreements that turn electricity somewhere on the system into reliable service at one specific site. [C09][C15][C16]

So the next time you hear about a giant new data center, ask three questions:

**Where will its electricity come from?**

**What has to be built to get that electricity to the site?**

**And what happens when its demand changes?**

Those three questions reveal the physical system hiding underneath the cloud.

And one of the hardest pieces of that system may be something that looks almost boring from the outside:

a transformer.

That is where we can go next.
