---
meta_title: "Well Pump Capacitor: What It Does and How to Test It"
meta_description: "A well pump capacitor stores the extra push a motor needs to start turning. See how to spot a bad one, test it safely, and what replacement runs."
primary_keyword: "well pump capacitor"
secondary_keywords: "well pump start capacitor, how to test well pump capacitor, well pump relay, run capacitor, start capacitor"
---

# Well Pump Capacitor: What Every Homeowner Should Know

A well pump capacitor is a small, drum-shaped part that does an outsized job: it gives a single-phase pump motor the extra electrical push it needs to start turning. Most homes run on single-phase power, and a single-phase motor cannot create a rotating magnetic field on its own from a dead stop. The capacitor briefly shifts the current so the motor has something to grab onto. When that part fails, the symptom is usually loud and immediate: a hum, a click, and no water.

This guide walks through what the capacitor actually does, how it differs from the relay it works with, what failure looks like, and how to test one safely if you decide to open the control box yourself. It also covers what a straight capacitor swap runs versus a full control box replacement, using the same price ranges we quote on every job.

## What a Capacitor Actually Does in a Well Pump Circuit

Single-phase AC motors, the kind almost every residential well pump uses, need a jolt in a specific direction to start spinning. Left alone, the magnetic field in a single-phase motor just pulses back and forth instead of rotating. A capacitor, wired into a second set of windings, delays the current enough to create that rotation. Once the rotor is spinning on its own, it does not need the same help.

That is why a capacitor is rated in microfarads (µF, the unit of capacitance, or how much charge the part can hold) and in volts. A start capacitor for a fractional-horsepower well pump is typically a high-µF part built for brief, repeated duty, not continuous running. Larger, longer-running submersible systems sometimes add a second, lower-µF run capacitor that stays connected the whole time the motor runs, smoothing current and improving running efficiency. Franklin Electric's own control box literature describes this split directly: its standard boxes use capacitor start only, while its CRC (capacitor run) boxes add "a run capacitor for smoother motor operation" on top of the start capacitor ([Franklin Water control box specifications](https://www.franklinwater.com/products/submersible-motors-and-control-boxes/submersible-motor-control-boxes/motor-control-boxes/)).

## Start Capacitor vs. Run Capacitor: Different Jobs, Different Failure Habits

The two parts sound similar but fail differently:

| Component | When it works | Typical failure symptom |
|---|---|---|
| Start capacitor | Only during the first second or two of startup | Pump hums but never turns over |
| Run capacitor (if present) | Continuously, the whole time the motor runs | Weak running torque, motor runs hot, higher hum |
| Relay (potential relay or solid-state) | Switches the start capacitor out once the motor is near full speed | Chattering, clicking repeatedly, or start capacitor failing again soon after replacement |

A start capacitor that has weakened often still lets the motor limp to speed some of the time, so the problem can look intermittent before it becomes constant. A bad relay, by contrast, tends to keep cooking start capacitors, because it fails to take the capacitor out of the circuit once the motor is running. If a freshly replaced start capacitor fails again within weeks, the relay is the more likely culprit, not bad luck with parts.

## Where the Capacitor and Relay Actually Live

On a submersible pump, the capacitor, relay, and any overload protection sit in a control box, usually mounted in the pump house or basement near the pressure tank, not down in the well. That box is the accessible part of the whole starting circuit. We cover what else is inside it, and how the pieces interact, in our guide to [well pump control box troubleshooting](/blog/well-pump-control-box-troubleshooting/), so this article stays focused on the capacitor and relay specifically.

Not every well pump has a separate, external relay to look at. Two-wire submersible motors build the starting components inside the motor housing itself, down in the well, with no accessible relay in a box. Three-wire motors run the starting circuit through that external control box instead, which is why a three-wire system is generally easier to diagnose and service at the surface. If you are not sure which one you have, our [two-wire vs. three-wire well pump](/blog/two-wire-vs-three-wire-well-pump/) guide explains how to tell from the wiring and the pump's data plate.

## Signs a Capacitor or Relay Is Starting to Fail

Watch for these patterns:

- The pump hums for a second or two, then goes silent, with no water at the tap. This is the classic start-capacitor symptom, covered in more depth in [well pump humming but not running](/blog/well-pump-humming-not-running/).
- The motor starts, but slowly, or only on the second or third try.
- The breaker trips right at startup, not while running. A motor drawing full locked-rotor current with no starting boost pulls more amps than a healthy start does; our [well pump tripping breaker](/blog/well-pump-tripping-breaker/) article walks through the other causes worth ruling out too.
- You hear a rapid clicking or chattering from the control box during a start attempt. That points to the relay, not the capacitor.
- The capacitor's case is visibly bulged, cracked, or leaking a waxy residue inside the control box. A capacitor that looks like this gets replaced regardless of what a meter says.
- The control box feels warm to the touch or smells faintly burnt after a normal cycle.

None of these symptoms confirm a capacitor problem on their own. They narrow the search to the starting circuit rather than the pump, the wiring, or the pressure switch.

## Before You Open the Control Box: Safety Comes First

This is the step people skip, and it is the one that matters most. Turning off the breaker at the panel makes the wiring dead, but it does not automatically discharge a capacitor that is already carrying a charge. A capacitor stores its own electrical energy independent of the incoming power, and that stored energy does not disappear just because the circuit feeding it is off.

OSHA's standard practices for electrical work address this directly: capacitors must be discharged, and high-capacitance elements short-circuited and grounded, whenever the stored energy could endanger someone, and anyone handling that discharge is to treat the capacitor as though it were still energized ([OSHA 1910.333, electrical work practices](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.333)). Virginia Tech's electrical safety program explains why this matters in plain terms: a capacitor "may store hazardous energy even after the equipment has been de-energized," and that residual charge is capable of a real shock on its own ([Virginia Tech EHS, capacitor safety](https://ehs.vt.edu/programs/occupational-safety/electrical-safety-in-research-operations/capacitors.html)).

For a homeowner willing to go this far, the safe sequence is:

1. Shut off the breaker feeding the pump circuit at the panel. Do not rely on the pressure switch or a wall switch alone.
2. Verify the circuit is dead at the control box terminals with a meter, not by assumption.
3. Discharge the capacitor deliberately, with an insulated tool built for the job, before touching its leads. A bare screwdriver across the terminals is not a safe substitute.
4. Only then disconnect a lead and test.

If any of that sequence is unfamiliar, or you do not have the right tool on hand, that is the point to stop. Call **[(509) 300-5151](tel:+15093005151)** and we will walk through it or come do it; we answer 24/7, and a capacitor swap is a routine part of a normal service call. The same goes if the capacitor turns out to be the least of the problem: a failing submersible motor means pulling the pump out of the well itself, and on the deeper wells common in the foothills around Cashmere and Leavenworth, that is not a job to improvise.

## How to Test a Well Pump Capacitor

Once the circuit is confirmed dead and the capacitor discharged, testing it is straightforward with the right tool:

1. Read the capacitor's printed rating: microfarads (µF) and voltage. Write it down before you disconnect anything.
2. Disconnect at least one lead so the capacitor is isolated from the rest of the circuit. A capacitance reading taken while still wired in will be unreliable.
3. Set a multimeter to its capacitance (µF) function. Not every multimeter has one; if yours does not, a dedicated capacitor tester works the same way.
4. Touch the leads to the capacitor's terminals and read the result.
5. Compare the reading to the printed rating and the tolerance range printed on the case itself (it varies by part, so read your capacitor rather than assume a number). A reading well outside that range, or a reading of zero, means the capacitor is done.
6. Replace it if the case shows any bulging, cracking, or leaking residue, even if the meter reading still looks close to spec. Physical damage outruns the number.

A capacitor that tests within range but the symptom keeps recurring is worth a second look at the relay before you assume the part is fine. A capacitor can also fail intermittently under the load of an actual start in a way a static bench test on a mild day does not always catch.

## What Capacitor and Control Box Work Actually Costs

A capacitor or control box replacement runs **$200 to $450** installed. Where a job lands in that range depends on what needs replacing: swapping just the capacitor is on the lower end, while a full control box, where the relay, terminals, and wiring have also aged out together, runs higher. A standalone diagnostic visit is **$150 to $250**, applied toward the repair if you have us do the work. An after-hours call adds an emergency premium of $150 to $300. For the fuller breakdown across pumps, tanks, and wiring, see our [well pump cost guide](/well-pump-cost/).

If you would rather have someone confirm what you are looking at before you buy a part, [get a free estimate](/#contact) and we will tell you straight whether it is the capacitor, the relay, or something upstream of the control box entirely.

## When the Capacitor Tests Fine but the Pump Still Will Not Start

A capacitor that checks out does not mean the starting circuit is clear. Corroded or loose terminals inside the control box can starve the capacitor of a clean connection without ever showing up as a bad reading on the bench. A pump saver or low-water cutoff switch upstream can also cut power before the motor gets a fair shot at starting, which looks identical to a dead capacitor from the tap. And a winding fault inside the motor itself, down in the well, can produce the same hum-and-stop symptom a bad capacitor does, with no fix possible at the control box at all.

Seasonal load plays a role too. Through a hot, dry stretch when a well is cycling far more often to keep up with household and orchard irrigation demand, every extra start asks more of a capacitor that is already marginal. That doesn't change the diagnosis, but it helps explain why a capacitor that seemed fine in spring can fail in late summer without warning.

If you have been through the checklist above and still cannot pin down whether it is the capacitor, the relay, or something else in the starting circuit, [our well pump repair service](/well-pump-repair-wenatchee/) covers exactly this kind of diagnosis across Chelan, Douglas, and Grant counties. A short visit with the right meters usually settles it faster than swapping parts one at a time.

## Frequently Asked Questions

### Can I test a well pump capacitor myself?

Yes, if you are comfortable with basic electrical safety and have a meter with a capacitance setting. The work is done with the power off; anything inside a live panel is a job for a pro. The steps are: kill the breaker, verify dead with a meter, discharge the capacitor with an insulated tool (never assume it is safe just because the power is off), then read it with a multimeter's capacitance function and compare to the printed rating. If any part of that sequence feels unfamiliar, or you lack the right tool, it is a reasonable point to call in help rather than guess.

### How much does it cost to replace a well pump capacitor?

A capacitor or control box replacement runs $200 to $450 installed, depending on whether it is just the capacitor or the whole box, including the relay and terminals. A standalone diagnostic visit runs $150 to $250 and applies toward the repair if you move forward with it. These figures come from our own current pricing, not a national average. An after-hours call adds an emergency premium of $150 to $300.

### What is the difference between a well pump capacitor and a well pump relay?

The capacitor stores and releases the electrical charge that helps a single-phase motor start turning. The relay is the switch that takes the start capacitor out of the circuit once the motor reaches near-running speed, so it is not left connected longer than it needs to be. A bad capacitor usually shows up as humming with no start. A bad relay often shows up as chattering, or as a freshly replaced start capacitor failing again within weeks because the relay never disconnected it properly.

### How do I know if it is the capacitor or the control box?

If a bulging, cracked, or leaking capacitor is the only visible problem and the rest of the box looks clean, replacing just the capacitor usually solves it. If the terminals show corrosion, the relay is chattering, or more than one component looks aged, replacing the whole control box at once is often the more reliable fix, since the parts inside age together. A diagnostic visit settles this faster than guessing, particularly if the symptom has come and gone more than once.
