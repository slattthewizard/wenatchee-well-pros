---
meta_title: "How to Wire a Pressure Switch on a Well Pump"
meta_description: "How to wire a pressure switch on a well pump: line and load terminals, grounding, and the safety steps to take before you touch a single wire."
primary_keyword: "how to wire a pressure switch"
secondary_keywords: "well pump wiring, well pump wire colors, pressure switch terminals, 240 volt well pump wiring, two wire versus three wire pump"
---

# How to Wire a Pressure Switch on a Well Pump System

If you're standing at the pressure tank with the old switch cracked open, wondering which screw goes where, you're in the right place. Wiring a pressure switch is not a complicated job on paper: a couple of hot wires in, a couple out, a ground screw. What makes it worth doing carefully is that every terminal on that switch can carry 240 volts, and the switch itself has no way to tell you that. It just sits there and switches. This guide walks through how the wiring actually works, what line and load mean on the switch body, and the safety steps that matter more than the wiring diagram.

## What the Pressure Switch Actually Does

A pressure switch is a mechanical valve for electricity. Inside the housing, a diaphragm or piston reacts to water pressure in the tank and pipe. When pressure drops to a set point, called the cut in pressure, the diaphragm pushes a set of contacts closed and sends power to the pump. When pressure climbs back up to the cut out pressure, the contacts spring open and the pump stops. Penn State Extension describes a typical cycle this way: the pump runs until tank pressure reaches around 40 psi, then the switch shuts it off, and the pump restarts once pressure falls to around 20 psi as water is used from the tank ([Penn State Extension, Using Low-Yielding Wells](https://extension.psu.edu/using-low-yielding-wells)). The actual numbers on your system might be different (20/40, 30/50, or 40/60 are all common factory settings), and adjusting them is a separate job from wiring the switch. If you need to change the settings rather than replace the switch, see our guide to [adjusting a pressure switch](/blog/well-pump-pressure-switch-adjustment/) instead.

The wiring question only comes up when you're installing a new switch, replacing a failed one, or troubleshooting why the pump won't start or won't stop. All three of those start the same way: with the power off.

## Before You Touch a Wire: Kill the Breaker and Verify It's Dead

This is the part worth slowing down for. A pressure switch is usually fed by a dedicated 240 volt, double pole breaker, and both legs are hot. (Some smaller jet pumps run on 120 volts; the safety steps are the same.) Shutting off the switch's own lever, if it has one, does nothing for the wiring inside the box. Only the breaker does that.

1. Find the breaker that feeds the pump circuit. It's often labeled "well pump" or "pump," but on an older or previously modified panel, it may not be labeled at all.
2. Switch that breaker off.
3. Open the pressure switch cover and, using a multimeter (a non-contact tester is a handy first check, not proof), check for voltage between the two line terminals, between the two load terminals, and between each terminal and ground. All readings should be zero before you go further. Check the meter on a known live circuit before and after, so a dead meter can't fool you.
4. If you get any reading at all, stop. You have the wrong breaker, a mislabeled panel, or a second feed you don't know about yet.
5. If your property has a secondary disconnect near the well or the pump house, confirm that one too before assuming the circuit is dead.

That verification step is not optional caution. It's the professional standard: OSHA's workplace rules for work on electrical equipment require a qualified person to use test equipment to confirm circuit elements are actually de-energized before work begins, not just switched off at a breaker that might be misidentified ([OSHA 1910.333](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.333)). A university extension safety sheet aimed at farms and rural properties puts the everyday version of the same rule plainly: shut off power at the breaker before troubleshooting, and never touch a panel, wiring, or a pump with wet hands ([University of Wisconsin-Madison Extension, Electrical Safety Around Irrigation and Well Pumps](https://safety.cals.wisc.edu/wp-content/uploads/sites/325/2026/01/Electrical-safety-around-irrigation-well-pumps.pdf)). Pump houses and pressure tank closets are damp places. Treat that as part of the hazard, not background noise.

If the panel is old, poorly labeled, or you're genuinely not sure which breaker feeds the pump, that's a reasonable point to stop and call **[(509) 300-5151](tel:+15093005151)** rather than guess your way through a live panel.

## Where the Switch Sits and What's Already Connected to It

The pressure switch mounts on or near the pressure tank, usually threaded into a tee fitting alongside the pressure gauge and drain valve. Two sets of wires come to it: one set from the breaker (the power source) and one set going onward to the pump circuit. On a shallow well jet pump or a two-wire submersible, that second set often runs straight to the pump. On a three-wire submersible, it runs to a control box first, and the control box then feeds the pump. The switch itself doesn't change based on which setup you have. What changes is what's on the other end of the load wires.

## Line and Load: How Power Actually Flows Through the Switch

Most residential pressure switches have two pairs of screw terminals plus a ground screw. The naming convention is line and load, and it matters for how the circuit behaves, even though both pairs can look identical at a glance.

| Terminal | What connects there | What it does |
|---|---|---|
| Line (typically the outer pair) | The two hot conductors coming from the breaker | Brings incoming 240 volt power into the switch |
| Load (typically the inner pair) | The wires continuing to the pump, or to the control box on a three-wire system | Only carries power out to the motor circuit when the switch's internal contacts are closed |
| Ground screw | The bare or green equipment grounding conductor | Gives fault current a path back to the panel instead of through a person |

When the diaphragm senses low pressure, it closes the contacts and bridges line to load, sending power through to the pump or control box. When pressure is satisfied, the contacts open and the load side goes dead, at least until the switch calls for the pump again. That's why the terminals matter for more than just getting the pump running: if line and load get swapped, the switch may still work, but the terminals marked load, the ones the next person expects to be dead when the switch is open, stay energized instead. That's one more reason to test every terminal, not just the ones you expect to be live. It's an easy mistake to make because the terminal pairs are rarely marked as clearly as they should be, so check the wiring diagram printed inside the switch cover rather than assuming.

## Grounding the Switch and Why It Matters

The ground screw is usually a green screw on the switch body, and it should carry the same bare or green equipment grounding conductor that runs with the rest of the circuit back to the panel. Its job is simple: if a hot wire ever contacts the metal housing or a stray part of the switch, the ground gives that fault current a low-resistance path home, which trips the breaker instead of leaving the housing energized. Skipping the ground connection because it's inconvenient, or because the old wiring didn't have one, removes that protection entirely. Near a wet pressure tank closet or an outdoor pump house, that's exactly the kind of shortcut the safety guidance above warns against.

## Two-Wire and Three-Wire Systems Wire Differently

The wiring downstream of the switch depends on what kind of pump you have. A two-wire submersible pump has its start components built into the motor itself, so the load side of the pressure switch typically runs straight to the pump's two power leads and ground, with no separate box in between. A three-wire pump keeps its starting capacitor and relay in a control box mounted above ground, so the switch's load side feeds the control box, and the control box then feeds the pump downhole. If you open the pressure switch expecting two wires headed to the pump and instead find wires headed to a metal box on the wall, that's your three-wire system, and the control box is part of the circuit you're working on, not a separate issue. We cover the mechanical difference between the two setups, including how to tell which one you have, in [two-wire versus three-wire well pumps](/blog/two-wire-vs-three-wire-well-pump/), and what actually fails inside a control box in our [control box troubleshooting guide](/blog/well-pump-control-box-troubleshooting/).

If you're not sure which setup is behind your wall, don't guess and start disconnecting things. Have us confirm it first: [get a free estimate](/#contact) before anyone touches a wire.

## Wire Colors, Gauge, and Why a Universal Chart Is Risky

Homeowners searching for "well pump wire colors" are usually hoping for one chart that applies to every pump. It doesn't exist. Wire color conventions for submersible motors are set by the motor manufacturer, not by a single national standard, and they vary between brands and sometimes between models from the same brand. Franklin Electric, one of the larger submersible motor manufacturers, documents the exact wire count, color, and connection points for its own motors in its own installation and maintenance manual rather than relying on a generic chart ([Franklin Electric, Submersible Motors Application, Installation, and Maintenance Manual](https://fele.widen.net/content/mrbmponfcz/pdf/M1311_60Hz_AIM_Manual.pdf?u=bt7ctv)). The practical takeaway: check the tag on the motor, the paperwork that came with the pump, or the splice you're replacing, rather than trusting a color chart pulled from a different brand's pump.

Wire gauge matters just as much as color, especially on a deep well where the drop cable run is long. Undersized wire causes voltage drop severe enough to shorten motor life or keep a pump from starting reliably, and it's a separate calculation from the switch wiring itself. We walk through that sizing question in [well pump wire size and voltage drop](/blog/well-pump-wire-size-voltage-drop/).

## Mistakes That Turn a Simple Swap Into a Bigger Repair

A pressure switch swap is one of the more affordable repairs on a well system, typically $150 to $350 installed depending on access and switch type. A handful of wiring mistakes are what turn that small job into something bigger.

- **Undersized or damaged wire reused from the old switch.** If the old wire is nicked, corroded at the terminal, or simply too small for the load, reusing it under a new switch just carries the same problem forward, and a damaged or loose conductor can overheat at the terminal. If the breaker starts tripping after a repair, see [well pump tripping breaker](/blog/well-pump-tripping-breaker/) for the likely causes.
- **A floating or skipped ground wire.** It's tempting to tuck an unused ground wire out of the way rather than land it on the screw. Don't. It has one job and it only does that job if it's actually connected.
- **Wires forced under a terminal screw with strands hanging out.** A loose strand touching the housing, or touching the neighboring terminal, is how a switch that wired up fine on day one starts arcing or nuisance-tripping weeks later.
- **Reusing brittle or corroded wire nuts in a damp box.** Pressure tank closets and pump houses see condensation and temperature swings. Connectors rated for that environment, tightened properly, matter more here than in a dry basement panel.
- **Forgetting to reset the pressure settings after the swap.** A new switch usually ships at a factory setting that may not match your old one. If your tank was set up for 30/50 and the new switch is preset differently, the tank's air precharge (normally set about 2 psi below cut-in) no longer matches, which shrinks the usable drawdown and can make the pump short cycle until the switch or precharge is adjusted. That's a quick fix and not a wiring problem.

Anything that involves opening a control box, working inside a crowded panel, or pulling a pump out of a deep well to check a connection at the wellhead is a good place to stop and call **[(509) 300-5151](tel:+15093005151)** instead of working it out on the fly. Our [well pump repair](/well-pump-repair-wenatchee/) service across Chelan, Douglas, and Grant counties covers exactly this kind of call, and a full breakdown of what different well repairs run is in our [pricing guide](/well-pump-cost/).

## Frequently Asked Questions

### Can I wire a pressure switch myself?

If you're comfortable killing the breaker, verifying it's dead with a meter, and matching wires to clearly marked line and load terminals, the wiring itself is within reach for a handy homeowner. Where people get into trouble is skipping the verification step, working in a crowded or poorly labeled panel, or misreading which wires go where on a three-wire system with a control box involved. If any of that is unclear once the cover is off, stop and call rather than guess. A service call and diagnosis runs $150 to $250, applied toward the repair if you hire us to finish it.

### What happens if I wire the line and load backward on a pressure switch?

In many cases the switch will still open and close and the pump will still run, because the internal contacts don't care which side is labeled line and which is labeled load. The real risk shows up later: if someone opens that switch expecting the load side to be dead whenever the contacts are open, and line and load were swapped, they can find voltage where they didn't expect it. Wire it to match the diagram printed inside the switch cover, not just to whatever gets the pump running.

### Why does my well pump wiring need a control box?

A control box is only needed for three-wire submersible pumps. Those motors don't have a starting capacitor and relay built in, so those components live in a box mounted above ground, usually near the pressure tank or breaker panel, where they're easy to service. Two-wire pumps have that starting hardware built into the motor itself and don't use a separate box. Neither design is wrong; they're just different approaches to the same job, and which one you have depends on the pump that's already installed, not on how you wire the switch.

### Are well pump wire colors the same on every pump?

No. Wire color coding for submersible pump motors is set by each manufacturer, and it can differ from brand to brand and even between models from the same maker. There's no single national color standard for pump motor leads the way the electrical code sets colors for the neutral and ground in household wiring. Before connecting or splicing wires on an unfamiliar pump, check the tag on the motor or the installation paperwork that came with it rather than assuming a color you learned on a different job applies here.
