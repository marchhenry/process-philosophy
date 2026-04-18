# Becoming — A Process Philosophy Simulation

A browser-based simulation of Whitehead's process philosophy, built as a single self-contained HTML file. No dependencies, no build step.

**[Live demo](https://marchhenry.github.io/process-philosophy/)**

---

## What it is

In *Process and Reality*, Whitehead argues that reality is not made of stable substances but of *actual occasions* — discrete events that arise, reach completion, and perish. Every occasion comes into existence by *prehending* others: grasping and integrating what it receives into a novel synthesis (*concrescence*). When that integration succeeds, something higher emerges. When it fails, the occasion perishes — but even failure seeds what comes next.

This simulation renders that ontology directly. Each circle is an actual occasion. Encounter is the only mechanism of change. The world has no fixed substances — only events producing events.

## Stages

Entities evolve through seven stages, visible as color and size:

| Stage | Color | Description |
|---|---|---|
| Nascent | Yellow | New occasion, not yet shaped by encounter |
| Mature 1–3 | Orange → Red | Growing concrescence through repeated encounter |
| Ascended 1–3 | Lilac → Deep purple (glowing) | Full concrescence achieved |

## Collision rules

Every collision is an **event**. Its outcome depends on the angle of approach:

- **Joyful event** (glancing collision) — successful concrescence. Both occasions perish and a new one emerges at the next stage, inheriting their averaged trajectory.
- **Sad event** (near-frontal collision) — failed integration. Both perish and scatter nascent offspring.

At the apex, Ascended-3 entities cannot advance further. Any encounter — joyful or sad — ends them and releases a burst of new nascent occasions into the world.

## Controls

| Parameter | Effect |
|---|---|
| Nascent entities | Number of occasions spawned on reset |
| Sad angle | Angular threshold between joyful and sad collisions |
| Speed | Velocity of all entities |
| Mature offspring | Nascents produced by a sad mature collision |
| Ascended offspring | Nascents produced by a sad ascended collision, or any a3 encounter |

The live graph at the bottom of the panel tracks total population, nascent, mature, and ascended counts over time.

## Usage

Open `index.html` in any modern browser. No installation required.

## License

MIT
