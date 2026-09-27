---
meta_title: "Well Pump Soft Start: What It Does and Who Needs One"
meta_description: "A well pump soft start smooths the current surge a motor draws at startup. Who actually benefits, how 2-wire and 3-wire pumps differ, and what to check first."
primary_keyword: "well pump soft start"
secondary_keywords: "reduced voltage starter well pump, submersible pump inrush current, soft starter for well pump, generator for well pump, VFD vs soft start"
---

# Well Pump Soft Start: What It Does and Who Actually Needs One

Somebody mentioned a soft start to you. Maybe an electrician suggested one while sizing a generator, maybe you read about it chasing a flicker in your lights every time the pump kicks on, maybe you are wiring up a solar or battery system and the word kept coming up. It is a real device with a specific, narrow job. It isn't a universal upgrade, and whether it does anything useful for your well depends heavily on what kind of pump you have and what is actually straining right now.

## What Inrush Current Actually Means

Every electric motor pulls far more current the instant it starts than it does once it is running. That first burst is called inrush current, and at its peak it matches the motor's locked rotor amps, the current it would draw if the rotor couldn't turn at all. North Dakota State University Extension puts a rough number on it for common equipment: [electric motors draw about four times the power to start as they do to run](https://www.ag.ndsu.edu/news/newsreleases/2022/december/safely-use-standby-generators-for-emergency-power), and a typical home running a water pump along with a few other loads can hit roughly 5,000 watts of starting demand against 2,000 watts of continuous draw.

Franklin Electric's submersible motor manual describes the same moment from the motor's side, writing about its three-phase motors: at a full-voltage start the motor goes from zero to full speed in half a second or less, the current jumps to locked rotor amps and then drops to running amps, and that can dim lights and cause momentary voltage dips on other equipment. That instant, brief spike, not the pump's normal running draw, is what a soft start is built to soften.

## What a Soft Start Actually Does

A soft start, sometimes called a reduced voltage starter or RVS, ramps voltage up to the motor over a few seconds instead of slamming it to full voltage all at once. Current and starting torque ramp up along with it. In the three-phase chapter of [Franklin Electric's submersible motor application manual](https://fele.widen.net/content/mrbmponfcz/pdf/M1311_60Hz_AIM_Manual.pdf), the reasons given for using one include a power company that requires limiting voltage drop on the line, a desire to cut the mechanical stress a hard start puts on shafts, couplings and discharge piping, and slowing the sudden rush of water at start-up so it doesn't create a jolt of upthrust or [water hammer](/blog/water-hammer-well-system/) in the plumbing. None of that changes how the pump runs once it is up to speed. It only changes the first few seconds.

## Who Actually Benefits From One

A soft start earns its keep in a handful of specific situations, not as a blanket upgrade for every well. Read this list alongside the next section, because on most household pumps the motor's wiring type decides whether a soft start is an option at all.

- **Generator users.** A generator has to be sized for the pump's starting surge, not its running load, which is why a pump that runs fine on 240 volts from the grid can stall or trip a generator that looks big enough on paper. Our [guide to sizing a generator for a well pump](/blog/generator-for-well-pump/) covers that math in more detail.
- **Solar and off-grid inverter systems.** Batteries and inverters generally tolerate a steady load far better than a hard current spike. A gentler start is easier on the whole off-grid setup, which we cover in our [piece on solar well pumps for off-grid property](/blog/solar-well-pump-off-grid/).
- **Long wire runs to a remote well.** A long cable already drops some voltage the moment the motor demands its starting current, which blunts the surge somewhat but also steals starting torque from the motor. Our [guide to well pump wire size and voltage drop](/blog/well-pump-wire-size-voltage-drop/) explains that trade-off.
- **Weak or shared rural lines.** If your lights dim across the house every time the pump kicks on and neighbors on the same transformer notice it too, a soft start is one of the tools that addresses the complaint, alongside simply checking that the wire and breaker are sized correctly for the run.

If you are not sure which of these actually describes your situation, call **[(509) 300-5151](tel:+15093005151)** and walk us through it. We answer 24/7 across Chelan, Douglas and Grant counties, and we can help you work out whether a soft start is even on the table for your setup.

## Two-Wire vs Three-Wire Motors: Why the Wiring Type Changes the Answer

This is where a soft start question usually runs into a wall, and it comes down to where a pump's starting hardware physically lives. Our [two-wire vs three-wire guide](/blog/two-wire-vs-three-wire-well-pump/) covers the wiring differences in full, so we won't re-teach that here, but the short version matters for this topic specifically.

A 2-wire motor has its starting switch built into the motor itself, down in the well. There is no control box at the surface at all. A 3-wire motor keeps its starting capacitor and relay in a control box at the surface instead.

Here is what the manufacturer literature actually supports. [Franklin Electric's AIM manual](https://fele.widen.net/content/mrbmponfcz/pdf/M1311_60Hz_AIM_Manual.pdf) covers reduced voltage starters, autotransformer starters and solid-state soft starters in its three-phase motor chapter, for the three-lead and six-lead motors more common on bigger acreage and irrigation wells. It gives no add-on soft starter for its single-phase household motors. For 3-wire motors it says the motor and control box are two pieces of one assembly that must match in horsepower and voltage, and that running the motor with an incorrect box can cause motor failure and void the warranty. And its drive section says Franklin's single-phase submersible motors can only be run on a drive through the appropriate Franklin constant pressure controller.

So on a single-phase 3-wire pump, the manufacturer-supported route to a gentler start is a constant-pressure drive, not a box spliced into the existing control box. Franklin's [MonoDrive units are built to convert a 1/2 to 2 hp single-phase 3-wire system](https://www.franklinwater.com/products/drives-starters-and-protection/variable-frequency-drives/subdrivemonodrive-nema-4-variable-frequency-drive/) to constant pressure by replacing the control box and pressure switch, and soft start is one of the listed features. On a 2-wire pump, Franklin's own [SubDrive/MonoDrive FAQ](https://www.franklinwater.com/support/faqs/faqs/subdrivemonodrive/) is blunt: two-wire motors do not have soft start ability. Other manufacturers' motors and drives have their own rules, so the motor's nameplate and the drive maker's compatibility list decide it, not a general answer.

Any of this work happens with the breaker off and verified dead with a meter first. Opening a control box on a live circuit, or pulling a submersible pump out of a deep well to inspect it, isn't a do-it-yourself step. That is a call for a licensed electrician or a well tech.

## Soft Start vs a Correctly Sized Generator

The generator section of that same Franklin manual makes a point that surprises a lot of people looking into this: using a generator sized to the motor's minimum rating already acts as a soft start on its own, and no additional voltage reduction is allowed. The manual is equally direct about the flip side of that: never combine a reduced voltage starter with a minimum-sized generator. Both a soft starter and an undersized generator drop the voltage reaching the motor, and stacking the two can starve the motor of enough voltage to start at all, which risks real motor damage.

In practice, that means the first question to answer is not "should I add a soft start," it is "is my generator sized correctly for this pump's starting demand in the first place." [Get a free estimate](/#contact) and we will look at your pump's nameplate before you buy or size a generator, so you are not solving the same problem twice, once with the generator and again with a soft-start device that was never needed.

## Soft Start vs a Variable-Speed (VFD) System

These two get confused because both smooth out a hard start, but they solve different problems. A soft start only manages the first few seconds. Once the motor is up to speed, it runs exactly like it would without one, at one fixed speed, until the pressure switch cuts it off. A variable-frequency drive continuously adjusts the motor's speed the entire time it runs, which is how a constant-pressure system holds one pressure at every fixture instead of cycling between cut-in and cut-out. Our [breakdown of variable-speed well pump systems](/blog/variable-speed-well-pump/) covers whether that upgrade is worth it on its own terms. If your actual complaint is pressure that swings up and down while a shower is running, that is a VFD question, not a soft-start question. On a single-phase 3-wire pump the two overlap in practice: as covered above, the manufacturer-supported way to get a soft start there is a constant-pressure drive, which ramps the motor up gently every time it starts.

## What Adding One Involves, What It Costs, and When It Is Worth It

Getting a softer start isn't a standalone weekend project on most systems. Whatever the route, it has to be matched to your motor's wiring type, horsepower and voltage, and it has to be something the motor manufacturer approves, because a mismatched control box or drive can cost you the motor and its warranty. On a 2-wire pump, the realistic fixes are usually on the power side: generator size and wire size. Two cost realities worth knowing going in:

1. A service call and diagnosis to check your pump's nameplate, wiring type and what is actually causing the symptom you are chasing runs $150 - $250, and that fee applies toward the repair if you hire us to do the work.
2. If your capacitor or control box is already due for replacement on its own, that job runs $200 - $450 installed, separate from any soft-start decision. Our [well pump cost guide](/well-pump-cost/) breaks down pricing on the rest of a well system if you want the fuller picture.

Before you spend money on a device, work through this list.

| Question | Why it matters |
|---|---|
| Is your pump 2-wire or 3-wire? | Franklin says its 2-wire motors have no soft start ability; a 3-wire motor may get one through a matched drive |
| What is actually straining: a generator, an inverter, a long wire run, or lights dimming on a shared line? | A soft start fixes some of these and does nothing for others |
| Is your control box or capacitor already near the end of its life? | Replacing it may be the more useful fix, with or without a soft start |
| Are you chasing a hard start, or swinging water pressure? | Swinging pressure is a variable-speed question, not a soft-start question |
| Has anyone confirmed the device is rated for your motor's horsepower and voltage? | An unmatched device is a warranty and reliability risk |

If the answers point toward a real benefit, [get a free estimate](/#contact) and we will look at your control box, your wiring and your power source together, rather than pricing one part of the system in isolation.

## Frequently Asked Questions

### Does a soft start work with a 2-wire well pump?

Generally no. A 2-wire motor's starting switch is built into the motor itself, and Franklin Electric states plainly that its two-wire motors do not have soft start ability, in the FAQ for its own constant-pressure drives. For a 2-wire pump, the realistic path to an easier start is making sure your power source, generator or wiring, is correctly sized for the motor in the first place. If someone offers you an add-on device for a 2-wire pump, ask them to show you the motor maker's approval for it before anything gets installed.

### Will a soft start let me use a smaller generator?

Somewhat, but be careful how you combine the two. Manufacturer guidance is direct that a generator correctly sized to your motor's minimum rating already acts like a soft start on its own. It also warns against pairing a reduced voltage starter with a minimum-sized generator, since both drop voltage to the motor and stacking them can leave it without enough voltage to start safely. Size the generator to the pump's real starting demand first, then decide if a separate device still adds value.

### Is a soft start the same thing as a VFD or constant-pressure system?

No. A soft start only smooths the first few seconds of a start. Once the motor reaches speed, it runs exactly as it would without one, at a single fixed speed, until the pressure switch shuts it off. A variable-frequency drive continuously varies the motor's speed the whole time it runs, which is what lets a constant-pressure system hold steady pressure at every fixture instead of cycling. If your real complaint is pressure that rises and falls during use, that points to a VFD conversation, not a soft start.

### How do I know if my well actually needs one?

Look for a specific symptom rather than adding one on principle. Lights that dim across the house every time the pump starts, a generator or inverter that stalls or faults right at pump start-up, or a power company that has flagged voltage sag on your line are all real signals. A control box or capacitor that is already failing is worth fixing on its own regardless. If none of those apply and your pump simply starts and runs normally, a soft start is solving a problem you don't have yet.
