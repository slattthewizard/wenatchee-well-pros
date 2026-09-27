---
meta_title: "Pump Curve Explained: Finding Your Pump's Operating Point"
meta_description: "Pump curve explained in plain terms: read the chart, work out total dynamic head, and find where your well pump actually operates."
primary_keyword: "pump curve explained"
secondary_keywords: "well pump curve, total dynamic head, submersible pump curve, pump operating point, TDH calculation"
---

# Pump Curve Explained: How Your Well Pump Actually Performs

Every submersible pump ships with a chart nobody hands you when you buy a house. It is called a pump curve, and it is the single most useful piece of paper for understanding why your water pressure behaves the way it does. Once you can read one, a lot of things that seemed random, weak pressure on the second floor, a pump that short cycles, a system that never quite hits the numbers on the box, start making sense.

This is a plain-English walkthrough: what the curve shows, how to work out the number you need to read it (total dynamic head, or TDH), and how to tell whether your well and your pump are actually a good match.

## What a Pump Curve Shows You

A pump curve is a simple line graph. Flow, in gallons per minute (GPM), runs along the bottom. Head, in feet, runs up the side. The line itself slopes down from left to right: the harder a centrifugal pump has to lift and push water, the less of it comes out the top. Push more flow through the same pump and the head it can produce drops. Ask for more head and the flow drops instead. That relationship is built into how a submersible pump works. There is no getting around it with a different brand or a fancier motor.

Manufacturers publish a separate curve for every model and every horsepower and stage count within that model. Some now put selection software online, such as Xylem's [Goulds Water Technology selection and sizing tools](https://www.xylem.com/en-us/brand/goulds-water-technology/selection--sizing-tools/), which size submersible and jet pumps against your conditions instead of leaving you to dig through a paper catalog. If you still have the old pump's tag or the invoice from the last install, that model number is the fastest way to find the right curve.

The point on that curve where your system actually runs is called the operating point, or duty point. It is not a fixed spot the manufacturer picks for you. It is wherever your pump's curve crosses your system's own head requirement at your system's flow rate. That crossing point is what this whole article is really about.

## Total Dynamic Head: The Number Behind Every Curve

You cannot use a pump curve at all until you know your total dynamic head, the total resistance your pump has to overcome to deliver water at the pressure you want. TDH has three parts, and all three add together in feet:

| Component | What it represents | Where the number comes from |
|---|---|---|
| Lift (elevation head) | Vertical distance from the water level in the well while it's pumping up to the pressure tank | Well report or a water level check, plus drawdown while running |
| Friction loss | Resistance from the drop pipe, fittings, and the line running to the house | Pipe diameter, length, and your flow rate |
| Pressure head | The pressure your system needs to hold, converted to feet (1 psi equals about 2.31 feet of head) | Your pressure switch's cut-out setting |

Add those three and you have TDH. That is the head number you carry over to the vertical axis of the curve. Get any one of the three wrong and the whole exercise is off.

For a well specifically, this is not the same as sizing a surface pump moving water across flat ground. The lift has to be measured from the water level in the well while the pump is running, not from the ground surface and not from where the pump happens to sit. [WSU's irrigation program notes this directly in its pump horsepower guidance](https://irrigation.wsu.edu/Content/Calculators/General/Required-Water-Pump-HP.php): the depth to the water surface while pumping has to be added to the pressure required at the surface before you can size anything. Skip that step and every other number downstream is wrong.

## Finding Your Lift: Static Level, Pumping Level, and Seasonal Drawdown

Static water level is where the water sits when nothing has been running. Pumping level is where it drops to once the pump has been running a while, because pulling water out of the aquifer around the casing lowers the level near the well. [USGS describes this as a cone of depression](https://www.usgs.gov/water-science-school/science/groundwater-wells): pumping lowers the water level in and around the well, and how far that cone spreads depends on the aquifer and how hard the well is pumped. The difference between static and pumping level is drawdown, and it is drawdown you need for TDH, not the static number off your well report.

In orchard country and the foothills around Wenatchee, Cashmere, and Leavenworth, that pumping level is not necessarily fixed year round. Water levels in many wells run lower late in a hot, dry summer than they do in spring. A curve calculation done with a spring water level can undersell how much lift the pump is actually fighting in August. If your pressure sags every summer and comes back every winter, a falling pumping level is one likely reason, not necessarily a failing pump. Our guide to [testing well yield with a flow test](/blog/well-yield-test/) covers how to measure this properly instead of guessing from the pressure gauge.

## Friction Loss and Pressure Head: The Two Numbers People Skip

Friction loss is easy to ignore because it does not show up anywhere on the well report. It comes from the pipe itself: diameter, length, material, and how fast water is moving through it. A drop pipe that is a size too small for the flow you are asking of it, or an old galvanized run with decades of scale inside it, adds real head that a curve chart cannot know about unless you account for it. This matters more the longer the horizontal run from wellhead to house, and it matters more at higher flow rates, since friction loss climbs faster than flow does.

Pressure head is more straightforward. Your pressure switch's cut-out setting, the higher of the two numbers on a setting like 40/60, is what the pump has to be able to produce at the top of its work, and it has to be converted to feet before you add it to lift and friction. That conversion is the 1 psi to 2.31 feet relationship in the table above. If that cut-out setting has been changed recently, your pressure head number changed too, even if nobody thought to redo the TDH math.

Add lift, friction loss, and pressure head together and you have a TDH in feet. Pair that with the GPM you actually need, which is a separate question tied to fixture count and peak household demand and covered in our guide to [well pump sizing](/blog/well-pump-sizing/), and you have the two coordinates you need to read a curve.

## Reading the Chart: Where Your Well and Your Pump Actually Meet

Once you have TDH and GPM, find your TDH on the vertical axis, follow it across, and see where it crosses the pump's curve. That intersection tells you the flow that pump will actually deliver at your head, which can be quite different from the nominal GPM in the pump's model name.

A well-matched system runs somewhere toward the middle of the curve's published range, not jammed against either end. Say your TDH is 220 feet and the curve for a given model shows it delivering 8 GPM at that head, comfortably inside its published range. That is a workable match. If the same well needed 220 feet of head and the curve you were looking at only reached 180 feet before running out, that pump cannot do the job at all, no matter how much horsepower is on the label.

There is a supply side to this too. Your well itself has a limit, in GPM it can sustain, and casing diameter narrows the field of pumps that fit before you even open a curve chart. Penn State Extension's guidance for people about to drill a well lays out rough casing-to-capacity pairings, a [4-inch casing takes pumps rated at less than 20 GPM](https://extension.psu.edu/before-you-drill-a-well), a 6-inch casing roughly 20 to 100 GPM, and an 8-inch casing more again. If your well is on the small end, no curve is going to get you flow it was never built to deliver.

## When the Operating Point Is Wrong

A pump with far more head than your system needs runs out toward the right end of its curve: high flow, low head. It pushes more water than the house is asking for, which can fill a small tank almost as soon as it starts, shut off, then start again a minute later, and on a low-yield well it can pull the water level down faster than the aquifer refills it. Our piece on [why wells short cycle](/blog/well-pump-short-cycling/) walks through the tank and switch side of that problem, but a pump sitting well off its intended operating point is one of the causes that gets missed.

A pump without enough head for your well runs toward the left end of its curve, close to the maximum head it can make, and you get the opposite complaint: a trickle of flow, weak pressure everywhere, and long run times, even though the pump sounds like it is working hard. Very low flow also means less water moving past the motor to carry heat away. Run far outside its intended range for long enough, at either end, a pump tends not to last as long as one running where it was designed to run. Our guide to [how long well pumps actually last](/blog/how-long-do-well-pumps-last/) has more on what shortens that lifespan.

Either way, the fix is rarely "buy a bigger pump." It is usually matching the pump to the TDH and GPM you actually have, which sometimes means a smaller pump, not a larger one. If your existing pump has never run right and you suspect it was never sized to your well in the first place, that is worth a proper look before you spend more money chasing the symptom. A service call to check this over runs $150 - $250, and that fee applies to the repair if you hire us for the work, or call **[(509) 300-5151](tel:+15093005151)** and we can talk through what your numbers look like.

## A Note on Variable Speed Systems

Constant-pressure and variable-speed setups change this picture a little, because the pump's speed, and therefore its curve, shifts with demand instead of staying fixed. Our article on [variable-speed well pumps](/blog/variable-speed-well-pump/) covers how that works and whether the added cost is worth it for a given household. Even on a variable-speed system, though, the pump still has an outer curve it cannot exceed, and TDH still has to fit inside it. Variable speed widens the usable range. It does not remove the need to know your numbers.

It is also worth remembering that not every well pump is a submersible. Shallow jet pumps have their own curves and their own limits, most notably suction lift, and the two types are not interchangeable just because both move water. Our comparison of [submersible and jet pumps](/blog/submersible-vs-jet-pump/) covers where each one actually fits.

## Checking Your Own System Safely

There is a limited amount you can check yourself before this becomes a job for someone with a curve chart and a flow test kit in hand.

1. Find your pump's model number, on a tag or label left at the wellhead, control box, or pressure tank, or on the invoice from the last install.
2. Watch the pressure gauge and note the reading at the moment the pump shuts off. That is your cut-out pressure.
3. Check whether your household's peak demand has changed, more fixtures, an added hose bib, irrigation added, since the pump was sized.
4. If pressure has dropped seasonally, ask whether your well's pumping level has been retested recently.
5. Do not open the well seal, pull wire, or work inside the control box or panel to chase this further. Shut off the breaker and verify it is dead with a meter before touching any wiring, and leave anything past that point, especially pulling a pump from a deep well, to someone equipped for it.

If those checks point toward a mismatch rather than a switch or tank problem, that is where we come in. We serve Chelan, Douglas, and Grant counties, the phone is answered 24/7, and estimates are free: [get a free estimate](/#contact) and we will walk the numbers with you before anything gets pulled. If a full pump swap does turn out to be the answer, our [well pump cost guide](/well-pump-cost/) has the ranges by pump type, or see our [replacement service page](/well-pump-replacement-wenatchee/) for what the job itself involves.

## Frequently Asked Questions

### Do I need to know my pump curve to just fix low water pressure?

Not always. Low pressure can just as easily come from a faulty pressure switch, a waterlogged tank, or a partly clogged filter, none of which need a curve chart to diagnose. The curve becomes useful once the simple causes are ruled out, or when you are choosing a replacement pump and want to know it will actually perform at your well's real head, not just the number printed on the box.

### What GPM and head numbers count as "normal" for a house on a well?

There is no single normal number. It depends on your well's depth, your pumping water level, your pipe run, and your pressure switch setting, all of which vary well to well even on the same street. What matters is whether your specific TDH and GPM land in the middle of your specific pump's curve, not whether they match a number from a neighbor's system or a generic online chart.

### Can I just buy a bigger pump if mine seems weak?

Usually not the right first move. A pump sized above what your well and plumbing actually need tends to short cycle and can outrun a well's sustainable yield, pulling the water level down faster than the aquifer can keep up. Matching TDH and GPM correctly almost always produces a better result than sizing up, and sometimes the fix is a smaller pump, a different tank size, or a pressure switch adjustment rather than more horsepower.

### Does a pump curve change over the life of the pump?

The published curve for a given model does not change, but where your system operates on it can, mainly because your TDH changes. A drop in your well's pumping water level over a dry summer, pipe scaling that raises friction loss over the years, or a pressure switch that gets bumped up over time all shift your operating point even though the pump itself is unchanged. That is why a system that ran fine for years can start acting up without the pump having failed yet.
