---
meta_title: "Pump Saver: Dry Run Protection for Well Pumps"
meta_description: "A pump saver shuts a well pump off before it runs dry. How dry run protection works, who actually needs one, and what reset behavior to expect."
primary_keyword: "pump saver"
secondary_keywords: "pumptec, well pump dry run protection, low water cutoff well pump, dry run protection well pump, low yield well pump"
---

# Pump Saver Devices: How Dry Run Protection Keeps a Well Pump From Burning Out

A well pump is built to move water, not air. When the water level in the well drops below the pump intake, the pump keeps spinning but there's nothing left to move, and nothing left to cool the motor or lubricate its bearings. That's what a pump saver is for: a small control device that watches the pump's electrical load and cuts power before a dry-run condition turns into a burned-out motor.

If you searched for "pump saver" or "pumptec," you're probably standing at a pump that already tripped something, or you've read about a neighbor's well running low in a dry summer and want to get ahead of it. Either way, this is a straightforward piece of equipment once you understand what it's actually watching for.

## What a Pump Saver Actually Protects Against

Groundwater science calls the problem a "cone of depression." Pumping a well draws down the water level around the intake, and in a low-yielding aquifer that drawdown reaches deeper and faster than it does in a productive one, according to the [USGS Water Science School](https://www.usgs.gov/water-science-school/science/groundwater-wells). When the water level falls below the pump, the pump starts pumping air. USGS puts a rough figure of 5 gallons per minute (GPM) on what's considered an adequate domestic supply, which is a useful benchmark: a well that recovers well under that during peak use is the kind of well where dry-running becomes a real, recurring risk rather than a once-a-decade fluke.

A submersible pump's motor uses the water flowing past it for cooling. A jet pump depends on a steady column of water to stay primed. Either way, running dry, especially over and over, is what kills pumps early. A pump saver's whole job is to notice the moment the pump loses its load and shut it down before that happens, then give it a reasonable chance to try again once water has had time to recover.

If your well has been running low, read [Is Your Well Running Dry? Warning Signs and Options](/blog/well-running-dry/) first. A pump saver is a protection device, not a fix for a well that genuinely can't keep up with demand.

## How Dry Run Protection Actually Works

There are two different mechanisms sold under this idea, and they're not the same thing.

**Underload (current) sensing.** This is what devices like Franklin Electric's Pumptec and Pumptec-Plus do. The unit sits between the power supply and the pump and continuously watches the motor's electrical load. According to [Franklin Electric's own Pumptec product page](https://www.franklinwater.com/products/drives-starters-and-protection/protective-devices/pumptec-single-phase-pump-protection/), the device "interrupts power to the motor whenever the load drops quickly or below a preset level," which is exactly what happens when a pump starts moving air instead of water: a motor turning against water resistance draws more current than one spinning free. The same class of device also catches a few other failure modes: a waterlogged pressure tank that makes the pump short-cycle, and abnormal line voltage that can damage the motor on its own.

**Low-pressure cutoff.** A different approach, more mechanical, ties a switch to the system's pressure rather than the pump's electrical draw. If pressure falls below a set point and stays there, meaning the tank isn't refilling because the pump isn't delivering, the switch cuts power. This is closer in spirit to your normal pressure switch, just set to catch a failure the regular cut-in/cut-out points would miss. If you haven't looked at how a standard pressure switch is set, [How to Adjust a Well Pump Pressure Switch](/blog/well-pump-pressure-switch-adjustment/) covers that separately, don't confuse the two adjustments.

Both approaches solve the same underlying problem from different angles. Underload sensing reacts faster and catches more failure modes; a pressure-based cutoff is simpler and cheaper but slower to respond and blind to anything that doesn't show up as a pressure drop.

## Who Actually Needs One

Not every well needs dry-run protection. A well with strong, consistent yield and a pump that's never tripped anything doesn't gain much from adding one. It earns its keep on wells where the water level and pump demand are close enough that a bad week can push them past each other. That can describe properties in the foothills and orchard country here, where wells can be deep and yield varies well to well even on the same road.

Situations where a pump saver is genuinely worth the conversation:

1. **The well has a known low or marginal yield**, especially anything documented near or under that rough 5 GPM benchmark for a household well.
2. **It's late summer**, when water levels typically sit at their lowest. In April 2026 Ecology declared drought in every watershed in the state, citing low snowpack and multiple years of precipitation deficits. The [Washington Department of Ecology's drought page](https://ecology.wa.gov/water-shorelines/water-supply/water-availability/statewide-conditions/drought-response) tracks statewide conditions and drought declarations year to year; check it before assuming this summer looks like last summer.
3. **The property runs heavy seasonal demand** on top of the house, like orchard or garden irrigation pulling from the same well.
4. **The pump has already shut off on its motor overload, or the taps have spat air,** without an obvious wiring or electrical cause. That's often the well, not the equipment, telling you something.
5. **It's a cabin or seasonal property** where nobody's watching the pressure gauge day to day and a dry-running pump could burn for hours before anyone notices.

If any of those describe your situation, a [well yield test](/blog/well-yield-test/) is the honest next step before you spend money on protection equipment: it tells you what your well can actually deliver, rather than guessing from a bad week.

## Pumptec, PumpSaver, and the Other Names You'll See

Search around and you'll run into several brand names for essentially the same idea: Franklin Electric's Pumptec and Pumptec-Plus, and devices marketed under the PumpSaver name from other manufacturers. We're not a dealer for any of these and don't carry a preferred brand; the table below is just an orientation to what's out there, based on how each maker describes its own product.

| Device type | What it senses | Typical HP range | Wiring |
|---|---|---|---|
| Underload relay (Pumptec-style) | Motor current/load | 1/3 to 5 HP, depending on model | 2-wire and 3-wire single-phase |
| QD-style plug-in relay | Motor current/load | 1/3 to 1 HP | Designed for specific 3-wire control boxes |
| Low-pressure cutoff switch | System pressure | Limited by the switch's contact rating | Usually a pressure switch with a built-in cutoff, fitted in place of the standard switch |

None of these are a substitute for a working pressure switch, a sized-right pressure tank, or a control box that's matched to your motor. They sit alongside that equipment and add one more layer that shuts things down before a dry-run condition becomes a burned motor.

## What Reset and Restart Behavior Looks Like

This is the part people get surprised by. When a pump saver trips, it doesn't necessarily mean anything is broken. Most of these devices are built to try again on their own: after tripping, they wait through a delay period to give the water level time to recover, then attempt a restart. If the well has recovered, the pump runs and the device resets itself with no one touching anything. If it hasn't, the device trips again and waits again.

Some devices instead require a manual reset, a button or lever you have to press before the pump will run again, specifically so a well that's genuinely out of water doesn't cycle itself into the ground unattended. Which behavior you have depends on the specific device and how it's set up, so check the documentation for your unit rather than assuming.

A pump saver tripping once on a hot, dry afternoon during irrigation season isn't an emergency. A pump saver tripping every few minutes, day after day, is the well telling you the demand on it has outrun what it can deliver right now, and that's worth a call rather than repeated manual resets.

## What a Pump Saver Won't Fix

A pump saver protects the motor. It doesn't add water to the well, and it doesn't change how much your household can draw from it. If your well's real problem is that peak demand, showers, laundry, irrigation, all landing in the same couple of hours, outstrips what the aquifer can recharge, dry-run protection just means the pump shuts off cleanly instead of burning out. You'll still be short on water at the tap. [Penn State Extension's guide to low-yielding wells](https://extension.psu.edu/using-low-yielding-wells) walks through this peak-demand problem in more detail, including why a bigger pressure tank alone adds little storage and where a low-water cut-off switch fits.

That's a separate conversation from protection equipment: spreading out heavy water use, adding storage ahead of the pressure tank, or in some cases looking at whether the well itself can be improved. None of that is what a pump saver does, and it's worth knowing the difference before you buy one expecting it to solve a supply problem instead of a protection problem.

## Installing or Troubleshooting a Pump Saver: When to Call a Pro

These devices wire into the same circuit as your pressure switch and control box, which usually means working on the pump's 240-volt circuit. Before anyone touches wiring, the breaker gets shut off and verified dead with a meter, not just switched off and trusted. If the work means opening a control box or pulling a pump from a deep well to check the drop cable, that's a job for a professional, not a weekend project.

On cost, adding a pump saver isn't a line on our price list, so we quote it once we've seen the system. A service call to diagnose a nuisance trip, meaning the device is tripping but the well itself tests fine, runs $150 to $250, applied toward the repair if you have us do the work. For a fuller breakdown of what different well and pump jobs run, see [our well pump cost guide](/well-pump-cost/).

If you're getting repeated trips and you're not sure whether it's the well, the pump, or the device itself, call **[(509) 300-5151](tel:+15093005151)**. We answer 24/7 and cover Chelan, Douglas and Grant counties. If you'd rather start with a look at the whole system before committing to anything, [get a free estimate](/#contact) and we'll walk through what's actually happening at the pressure tank and control box, covered in more detail in [Well Pump Control Box: How It Works and Common Failures](/blog/well-pump-control-box-troubleshooting/).

If the pump saver keeps tripping and a service call confirms the well itself is short on water, that's a different job than a control box swap, and it's worth having someone who's actually pulled the pump look at the whole system rather than just resetting the device and hoping. [Well pump repair](/well-pump-repair-wenatchee/) covers that kind of full diagnostic visit, not just the relay.

## Frequently Asked Questions

### What's the difference between a pump saver and a normal pressure switch?

A pressure switch turns the pump on and off at set pressure points during normal operation, cut-in and cut-out. A pump saver is a separate layer that watches for an abnormal condition, either the pump's motor load dropping (dry-run) or pressure staying low longer than it should, and cuts power to protect the motor. They do different jobs and one doesn't replace the other. A well can have a perfectly good pressure switch and still benefit from dry-run protection if the water level is marginal.

### Will a pump saver fix a well that keeps running low?

No. It protects the pump motor from damage when the well runs low, but it doesn't add water to the well or change what the aquifer can deliver. If your well genuinely can't keep up with peak demand, the pump saver will just mean it shuts off cleanly instead of burning out, and you'll still be short on water at the tap. A [well yield test](/blog/well-yield-test/) tells you what the well can actually deliver, which is the real starting point for a supply problem.

### How do I know if my pump saver tripped, or something else killed power to the pump?

Check the breaker first: if it's tripped, that's a separate issue from the pump saver, which is a different device downstream of the panel. If the breaker is fine and the pump still isn't running, look at the device itself, many show a tripped indicator or require a manual reset button. If you're not sure what you're looking at or the pump won't restart after the water's had time to recover, a service call ($150 to $250, applied to the repair) will sort out which piece actually failed.

### Can I add a pump saver to an existing well system, or does it need a new pump?

In most cases it wires into your existing setup between the power supply and the pump, alongside your current pressure switch and control box. It doesn't require replacing the pump. Compatibility depends on your pump's horsepower and whether your system is 2-wire or 3-wire, which is worth confirming before buying one. Because the work involves the 240-volt circuit feeding the pump, we'd recommend having it installed rather than wiring it in yourself unless you're comfortable working inside a de-energized, meter-verified panel.
