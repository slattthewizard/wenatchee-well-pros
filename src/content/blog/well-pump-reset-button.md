---
title: "Well Pump Reset Button: What It Resets and When to Stop"
navTitle: "Well Pump Reset Button: What"
metaTitle: "Well Pump Reset Button: What It Resets, When to Stop"
metaDescription: "There is no single well pump reset button. Here is what each reset point actually does, how to use it safely, and when a repeat trip means call for help."
primaryKeyword: "well pump reset button"
secondaryKeywords: "well pump not turning on, well pump won't turn on, well pump overheating, well pump reset, control box overload reset"
publishedDate: "2026-10-02"
tag: "Well Care"
subtitle: "Someone hands you a flashlight and says \"did you try the reset button?\" and you head out to the pump house or the pressure tank not entirely sure what you're looking for."
canonical: "https://wenatcheewellpros.com/blog/well-pump-reset-button/"
faq:
  - question: "Is it safe to keep resetting my well pump myself?"
    answer: "Resetting it once, when you know what caused the trip, is fine. Resetting it repeatedly without knowing why is where it gets risky, both for the pump and for you if the trip involves a live pressure switch or control box. Each of those carries line voltage inside, so any hands on work means the breaker off and verified dead with a meter first. If the same reset keeps happening, that's the system telling you something upstream needs attention, not a switch that needs to be held longer."
  - question: "What's the difference between a pressure switch reset and a breaker reset?"
    answer: "The pressure switch's low pressure cutoff, where it exists, is a mechanical lever on the side of the switch that trips when tank pressure falls too far. A breaker trip is an entirely separate protection at the electrical panel, sized to the circuit rather than the pressure system, and it trips on overcurrent or a short, not low pressure. If your breaker is tripping, that points toward a wiring or motor issue rather than a pressure problem, and it's worth reading through what a tripping breaker usually means before you keep flipping it back on."
  - question: "Why does my well pump keep overheating in summer?"
    answer: "Summer adds a few things at once: static water levels tend to fall as irrigation season draws the aquifer down, which can leave a submersible motor with less water moving past it for cooling, and heavy irrigation demand asks more of the pump for longer stretches. A motor that was fine with light spring use can start tripping on hot, high demand days for reasons that have little to do with the motor itself failing. An amp draw check is the way to tell whether it's the motor working too hard or just needing less duty cycle."
  - question: "Can I bypass the dry run protection so the pump stops shutting off?"
    answer: "No. That device tripping means the pump was about to run, or was running, without enough water around it, which is exactly the condition that burns out a submersible motor for good. Bypassing it removes the one thing standing between a temporarily low well and a pump that needs full replacement instead of a service call. If it's tripping often enough to be a nuisance, the well's yield is the thing to look at, not the protection device."
---
Someone hands you a flashlight and says "did you try the reset button?" and you head out to the pump house or the pressure tank not entirely sure what you're looking for. There isn't one reset button on a well system. There are three separate parts that can each stop your pump on purpose, for different reasons, and pushing or holding the wrong one, or forcing the right one over and over, can turn a five minute fix into a dead motor.

Here's what each "reset" is, how to use it safely, and when a pattern of trips means stop resetting.

## There Are Three Different Things People Call "the Reset"

Depending on your setup, the thing that shut your pump off is one of these:

1. **The pressure switch's low pressure cutoff lever.** A spring loaded lever on the side of some pressure switches that locks the switch off when pressure falls too far.
2. **The control box overload.** On many three wire submersible systems, mostly the larger motors, a thermal or current sensing device in the control box that opens the circuit when the motor draws too much current for too long.
3. **A dry run or low water cutoff device.** A separate add on device, often called something like a pump saver, wired to shut the motor down fast when it senses the pump is spinning without enough water moving through it.

Two wire submersible pumps carry their overload protection inside the motor itself, so there's no external box to check on those systems, and smaller three wire motors often have built-in protection too, with a control box that has no overload reset. Jet pumps and shallow well setups have no separate control box; their overload is built into the motor, and some jet pump motors have their own reset button on the motor housing.

| Reset point | Where it lives | What trips it | How you clear it |
|---|---|---|---|
| Pressure switch low pressure cutoff | Side of the pressure switch, near the tank tee | Pressure fell too far and didn't recover (empty tank, line break, pump not delivering) | Hold the lever toward Start until pressure builds back above the cutoff, then release |
| Control box overload | Inside the control box, often near the pump house or wellhead | Motor drew too much current, too long, and got too hot | Some boxes need a manual reset button pressed after cooling; others reset on their own once cool, per the manufacturer |
| Dry run / low water cutoff device | Wired inline with the control box or pressure switch circuit | Motor load dropped the way it does when the pump is pumping air, not water | Wait for the well to recover, then the device clears itself or needs a manual reset depending on model |
## The Pressure Switch's Low Pressure Cutoff Lever

Some pressure switches, not all of them, include a low pressure cutoff feature: a lever on the side that is spring loaded toward the off position. If your tank pressure drops far enough, from a burst line, a tank that's run dry, or a pump that just isn't delivering, the switch locks itself off rather than letting the motor keep trying against no pressure. To clear it, you hold the lever toward Start and hold it there until pressure in the line climbs back above the cutoff point, then let go. If the switch doesn't have this lever at all, there's no reset on the switch, and the cause is somewhere else: a failed switch, a tripped breaker, or a pump problem. Those are repairs, not resets.

The lever sits on the outside of the switch, and you work it with the cover on and the power on. Never take the cover off to reach anything while the circuit is live. Before you open a pressure switch for any reason, shut off the breaker that feeds the pump at the panel and verify it's dead with a meter. The terminals inside carry full line voltage.

Holding the lever once, when you know exactly why pressure dropped (you just refilled a tank, or you fixed a line break upstream) is reasonable. Holding it again ten minutes later because it tripped right back is not a fix, it's a sign the well isn't holding pressure the way it should. For the switch itself, see our guide to [common well pressure switch problems](/blog/pressure-switch-problems/).

## The Control Box Overload Reset

Three wire submersible pumps run through a control box that sits between the wellhead wiring and the panel, and on larger motors that box carries the motor's overload protection. When the motor pulls more current than it should, for longer than it should, the overload opens the circuit to keep the windings from cooking. Depending on the box, that protection either resets itself automatically once the motor has cooled, or it needs someone to press an external reset button on the box after it's had time to cool down. Franklin Electric's own control box literature describes boxes built with [external access to the overload reset](https://www.franklinwater.com/products/submersible-motors-and-control-boxes/submersible-motor-control-boxes/motor-control-boxes/) for exactly this reason.

An overload that trips once, on a hot day, under a heavy load, and then runs fine isn't necessarily telling you anything is wrong. An overload that trips repeatedly usually traces back to one of a short list: a failing start or run capacitor, corrosion or a bad splice in the wiring between the box and the wellhead, a motor that's genuinely wearing out, or a pump that's binding, for example with sand or sediment dragging on the impellers. Our [control box troubleshooting guide](/blog/well-pump-control-box-troubleshooting/) walks through the box itself. If you want to know which of those it actually is rather than guessing, [amp draw testing](/blog/well-pump-amp-draw-testing/) is the way a technician confirms it instead of swapping parts one at a time.

## Dry Run and Low Water Cutoff Devices

Some systems, especially on wells with a known low yield history, have a dedicated add on device wired into the circuit whose whole job is watching the motor's load and shutting it off fast if that load drops the way it does when the pump is spinning in air instead of moving water. Franklin Electric's own page for its Pumptec line describes a device that monitors "motor load and power line conditions" and cuts power when load drops below a set point, specifically to guard against [dry well conditions and waterlogged tanks](https://www.franklinwater.com/products/drives-starters-and-protection/protective-devices/pumptec-single-phase-pump-protection/).

If this is what tripped, the device didn't malfunction. It did exactly what it's there for: it caught the well falling behind before the pump ran dry and burned up trying to move water that wasn't there. In orchard country, static water levels move with the season. A well that had plenty of margin in April can start pumping down further than usual by August, when everyone's irrigating and the water table has dropped for the summer. If your well is doing this and hasn't before, that's worth reading up on in our [well running dry](/blog/well-running-dry/) guide rather than just clearing the device and moving on.

Resetting one of these devices usually means waiting for the well to recover and letting the device clear on its own, or pressing a manual reset at the unit, depending on the model. Don't wire around it or defeat it to stop the nuisance of it tripping. It's the cheapest insurance you have against a dry running motor, and a dry run failure on a submersible almost always costs more than the inconvenience it's protecting you from. If the well has been dropping for weeks and this device keeps catching it, that's worth a look before it turns into a pump replacement instead of a well problem, and you can [get a free estimate](/#contact) on what's going on.

## Well Pump Overheating: Why the Motor Trips in the First Place

"Overheating" isn't really its own failure, it's what happens when a motor works harder than it should, or cools worse than it should, or both. On the working harder side: a failing capacitor makes the motor labor to start and run, low voltage from a long or undersized wire run makes it draw more current for the same output, and worn bearings or sand binding the impellers add drag, all of which make the motor pull harder than its rating.

On the cooling side, a submersible motor depends on water moving past its shell to carry heat away. A motor set below the point where water enters the well, or sitting in casing much wider than the motor, may not get the cooling flow it was designed around, even though electrically everything looks fine; installers fit a flow sleeve for that. A partly closed valve or a clogged line cuts the flow too, which is why a throttled pump can run hot even though it isn't drawing extra current. This is part of why pump placement and casing diameter matter at install, not just horsepower.

Guessing at which of these it is and swapping parts one at a time gets expensive fast. An amp draw reading, checked against the motor's rated draw, tells a technician in minutes whether the motor itself is the problem or something upstream of it is making the motor work too hard. If it comes back to a capacitor or the control box itself, replacement typically runs $200 to $450 installed; a [full breakdown of what different well pump repairs cost](/well-pump-cost/) is on our cost guide.

## Well Pump Won't Turn On Even After You Reset It

You found the switch, the box, or the low water device, cleared it the right way, and the pump still isn't running. A few things are worth checking before you assume the reset didn't work: is the breaker itself tripped, separately from anything at the pump house; is there a GFCI or disconnect switch somewhere in the circuit that's open; and, on a three wire system, is there a second reset on the control box that also needs clearing. If those all check out and it's still silent, the reset probably wasn't the real problem. A dead capacitor, a pressure switch whose contacts no longer close, or a pump that's actually reached the end of its life all look the same from the pump house: nothing happens when you flip it back on.

Our [well pump not working](/blog/well-pump-not-working/) guide walks through that checklist in more depth, and if it's specifically the breaker that keeps tripping rather than anything inside the pump house, [well pump tripping breaker](/blog/well-pump-tripping-breaker/) covers that side of it directly. If you'd rather have someone confirm it than keep working through the list yourself, call **[(509) 300-5151](tel:+15093005151)** and we'll talk through what you're seeing.

## When Repeated Trips Mean Stop, Not Reset

A single trip you can explain is normal wear on a system doing its job. A pattern is a different conversation. Stop resetting and get it looked at when:

1. It trips again within minutes of you clearing it, more than once.
2. You genuinely don't know why it tripped the first time.
3. The breaker at the panel is tripping, not just a switch or a box inside the pump house.
4. You notice a burnt smell anywhere near the panel, the control box, or the pressure tank tee.
5. The well itself has felt different lately: weaker flow, water that sputters before it steadies, or a longer wait before pressure comes back up.

Private well owners carry the maintenance load themselves; there's no utility checking your system the way there is on municipal water, and the [EPA notes that private wells aren't regulated by EPA](https://www.epa.gov/privatewells/protect-your-private-well), so the upkeep falls to you. The CDC's guidance for well owners is similarly direct: get your [well checked for mechanical problems every year](https://www.cdc.gov/drinking-water/safety/), not just when something has already stopped working. A reset switch or an overload tripping repeatedly is that mechanical problem showing up early, while it's still a service call instead of a full pump job.

A diagnostic visit runs $150 to $250, applied to the repair if you hire us for it, and we answer calls 24/7 across Chelan, Douglas and Grant counties. If you'd rather start with a number before deciding anything, you can also [get a free estimate](/#contact), or read more about what a [well pump repair visit](/well-pump-repair-wenatchee/) actually covers.
## Frequently Asked Questions

### Is it safe to keep resetting my well pump myself?

Resetting it once, when you know what caused the trip, is fine. Resetting it repeatedly without knowing why is where it gets risky, both for the pump and for you if the trip involves a live pressure switch or control box. Each of those carries line voltage inside, so any hands on work means the breaker off and verified dead with a meter first. If the same reset keeps happening, that's the system telling you something upstream needs attention, not a switch that needs to be held longer.

### What's the difference between a pressure switch reset and a breaker reset?

The pressure switch's low pressure cutoff, where it exists, is a mechanical lever on the side of the switch that trips when tank pressure falls too far. A breaker trip is an entirely separate protection at the electrical panel, sized to the circuit rather than the pressure system, and it trips on overcurrent or a short, not low pressure. If your breaker is tripping, that points toward a wiring or motor issue rather than a pressure problem, and it's worth reading through what a [tripping breaker](/blog/well-pump-tripping-breaker/) usually means before you keep flipping it back on.

### Why does my well pump keep overheating in summer?

Summer adds a few things at once: static water levels tend to fall as irrigation season draws the aquifer down, which can leave a submersible motor with less water moving past it for cooling, and heavy irrigation demand asks more of the pump for longer stretches. A motor that was fine with light spring use can start tripping on hot, high demand days for reasons that have little to do with the motor itself failing. An amp draw check is the way to tell whether it's the motor working too hard or just needing less duty cycle.

### Can I bypass the dry run protection so the pump stops shutting off?

No. That device tripping means the pump was about to run, or was running, without enough water around it, which is exactly the condition that burns out a submersible motor for good. Bypassing it removes the one thing standing between a temporarily low well and a pump that needs full replacement instead of a service call. If it's tripping often enough to be a nuisance, the well's yield is the thing to look at, not the protection device.
