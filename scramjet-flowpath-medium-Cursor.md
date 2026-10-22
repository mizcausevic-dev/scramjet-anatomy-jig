# How to read a scramjet flowpath in 34 seconds

**Subtitle:** A Mach 6 anatomy plate, what the colors are doing, and the claims the drawing refuses to make.

A scramjet is an air-breathing engine that keeps the core flow supersonic while it burns. There is no compressor. The vehicle's own shape slows and squeezes the air, fuel has to mix in a very short duct, and the nozzle is often just the afterbody. That is the whole machine. The hard part is seeing the order.

I drew that order as a 34-second side elevation: [Scramjet Flowpath Anatomy Jig](https://mizcausevic-dev.github.io/scramjet-anatomy-jig/). It runs 1,020 frames at 30 fps. Same frame number, same picture. It is a schematic of a Mach 6 underbody flowpath, not a test record, not a CFD solution, and not a drawing of a specific flight vehicle.

If you only have the length of the film, use it in this order: shell, shock train, injection, ignition, nozzle forces. That is also the order the air meets the hardware.

## What you are looking at

Nose left, exhaust right. Orthographic side elevation, so nothing is posed in perspective to look fast. The belly of the wedge is the compression ramp, the ceiling of the isolator, and the expansion ramp. The cowl is the lower jaw. It ends before the ramp does. After that edge, the underside of the plume is a shear layer, not a wall.

The shell is ceramic matrix composite, `#121316`, lifted off along the surface normals. The casing you see in section is titanium, `#2E333D`. Three accents are reserved and they do not get reused for decoration:

- Mach violet, `#7209B7`, is an oblique shock.
- Shock yellow, `#FFD000`, is the compression core and the injected fuel.
- Plasma, `#F72585`, is autoignition.

Bone-colored arrows are force on the vehicle. Colored arrows are velocity. If those two families look the same, the plate has failed, because thrust and flow point in different directions.

NASA's public X-43A page is the right historical anchor for why this layout exists, and it is not a caption for this drawing. The page, read on October 22, 2026, describes 12-foot unpiloted vehicles, gaseous hydrogen fuel, and a forebody that compresses the incoming air. It records Mach 6.8 on March 27, 2004, and Mach 9.6 on November 16, 2004. Source: [X-43A Hyper-X, NASA](https://www.nasa.gov/reference/x-43a/). The plate here is a teaching elevation in that family of airframe-integrated engines. It is not the X-43A, and it does not carry that vehicle's measured pressures, temperatures, or thrust.

A separate page, [Scramjet Flowpath](https://mizcausevic-dev.github.io/scramjet-flowpath-explainer/), uses a different brief, a different palette, and a cavity-flameholding stage. Do not merge the two figures. They are not two views of one data set.

## Why the five shots are in this order

The film is cut to the gas path, not to a highlight reel.

| Time | Frames | What changes |
| --- | --- | --- |
| 0.0–5.0 s | 0–150 | Thermal panels leave on their surface normals. The near-side shell comes off and the duct is visible. |
| 5.0–10.0 s | 151–300 | Color schlieren in the inlet. The forebody shock meets the cowl lip. Reflections stay downstream of that lip. |
| 10.0–17.0 s | 301–510 | Macro on three injection pylons. Fuel enters the crossflow. The middle pylon trails a counter-rotating vortex pair. |
| 17.0–25.0 s | 511–750 | Tracking shot down the divergent combustor. The wake lights. The core keeps moving downstream. |
| 25.0–34.0 s | 751–1020 | Pull-out through the single-expansion ramp. Velocity, wall taps, ramp pressure, and the forward force on the vehicle. |

A player that scrubs is the point. Pause on a frame and the label has to survive without the motion.

## The shell is the cut, not the subject

The first five seconds are an exploded view. Ceramic panels translate on the local surface normal: up off the leeward skin, down off the windward ramp and the cowl. A near-side closeout, the wall you would be looking through, parks below the engine so the section can be read for the rest of the film.

That move is geometry, not a maintenance procedure. Nothing here is a torque, a gap, or a material allowables table. The hatch on the titanium is the drafting convention for a cut metal edge. It is not a claim about grain, weld, or heat treat.

If the panels stayed on, you would be looking at a silhouette. The silhouette cannot show an isolator.

## A started inlet is a shock train that stays put

After the shell is open, the inlet shot is a color-schlieren plate. Horizontal banding is the knife-edge look. Violet lines are the shocks.

One line runs from the nose to the cowl lip. That is shock-on-lip, drawn as the design-point picture: the forebody oblique shock meets the lip instead of passing under it or being swallowed early. The angles are composed so the line hits the lip and the compressed layer between shock and ramp stays visible. They are not a method-of-characteristics solution, and the plate says so.

From the lip, a reflected train bounces between the belly and the cowl and fades before the pylons. The first reflection stays downstream of the lip. That is the entire point of the isolator in one sentence: the duct between inlet and combustor is there to hold the pressure rise of the combustor so the shock system is not pushed out the front.

If that system is expelled forward of the lip, the inlet unstarts. Capture collapses. The engine does not "run rough." It stops being an inlet. The film does not animate an unstart. It shows the contained case, and the caption says the inlet remains started. Treat that as the subject of the drawing, not as a prediction for a vehicle at off-design Mach or angle of attack.

## Fuel has to mix while it is still moving faster than sound

The third shot pushes in on three pylons hanging from the belly into the duct. Yellow leaves the orifices, bends downstream, and breaks into a short spray. On the middle pylon, two ribbons of opposite sense trail the upper jet. That pair is the counter-rotating vortex pair a transverse jet sheds in a supersonic crossflow. It is drawn as the mixing structure, not as a turbulence simulation.

Why struts, in this schematic: a scramjet duct is short in time. The air is not waiting in a flame tube. You put fuel where the air already is, and you use the vortex pair because a plain jet in a fast crossflow will otherwise hug a wall and leave a cold core. The plate shows one clean pair on the center pylon so the macro can be read. It does not show every injector a real engine would carry, and it does not name a fuel. "Gaseous" is the state the shot is drawn in. It is not a specification for hydrogen, a hydrocarbon, or an igniter species.

The manifold above the pylons is a feed line in section. It is there so the jets are not magic dots. It has no pressure, no valve schedule, and no part number.

## Ignition is a picture of a wake, not a stopwatch

From 17 seconds, plasma fills the divergent duct from the strut wakes and runs aft as the camera tracks. The core arrows stay pointed downstream. There is no flashback drawn upstream of the pylons. The label is "no flashback," which is the scramjet claim in ordinary words: heat release happens in flow that has not been slowed below sonic speed in the core.

The shot list I was given asked for a sub-millisecond residence window. I did not print a time. Residence time is a length divided by a speed, after you have decided which streamline and which static state you mean. This elevation does not resolve length as a scale, and it does not resolve speed as a number. A clock on the plate would have been a costume.

What the plate does show is the sequence people actually argue about: compression heating, fuel in the crossflow, a wake that anchors the reaction, and a core that keeps moving. Autoignition here means "the mixture lights from the temperature the shocks and the deceleration have already bought," not "this geometry will light at Mach 6 in flight." A real engine may still carry an igniter. NASA's X-43A flight reporting describes a hydrogen engine that used a separate ignition source. That fact is about that vehicle. It is another reason this schematic does not stamp "autoignition guaranteed" on the duct.

The wall-pressure trace in the last shot is a shape: lower at the inlet, higher through the duct, lower again on the ramp. The axis says "schematic shape." There is no unit, because a unit would be a lie.

## On the ramp, velocity and force point apart

A single-expansion-ramp nozzle, a SERN, has one expansion wall. The other side ends. NASA/TP-1999-209138, Deere and Asbury, May 1999, describes the installation directly: the underside of the afterbody can be the external ramp, and the lower cowl can be short, which is a weight and skin-friction trade against a nozzle that closes on both sides. That report is about a translating-throat SERN experiment, not about this drawing. I use it for the definition. [NASA/TP-1999-209138](https://www.cs.odu.edu/~mln/ltrs-pdfs/NASA-99-tp209138.pdf).

A 2013 Acta Astronautica paper's introduction states that SERNs were used on the planar engines of NASP and X-43. That is that paper's claim, cited here as a claim, not re-certified from flight hardware in this project. [Design exploration for a single expansion ramp nozzle (SERN) using data mining](https://www.sciencedirect.com/science/article/abs/pii/S0094576512003736).

On this plate the ramp is the belly, continuing aft after the cowl stops. Colored arrows in the plume follow the gas, downstream, to the right. Bone arrows along the ramp point up and forward, into the structure. The summed arrow at the nose points forward, which is left. Exhaust momentum and the force on the vehicle are opposite answers to two different questions. A figure that draws both of them to the right has taught the wrong machine.

The taps are stations on the wall. They are not a pressure survey. The plot under them is the same schematic shape, inlet to ramp, so a paused frame still shows where the rise and the drop sit.

## What I will not let the plate say

This is the list I held while drawing, and it is the list to hold while reading.

- No thrust in newtons, no specific impulse, no pressure recovery, no "net positive" as a measured result. The forward arrow is a direction.
- No station Mach numbers past the scenario label `M∞ = 6`. The scenario is the flight condition the shot list fixed. It is not a pitot reading.
- No residence time.
- No claim that the shock angles would start this inlet at Mach 6, or at any other Mach.
- No X-43A outline, no NASA mark, no material allowables, no "flight-proven."
- The schlieren bands are a graphic for density gradient. They are not a wind-tunnel negative.

If a later version adds a number, the number needs a source, a unit, and a sentence about what was held constant. Until then the honest plate is the one with the unit left off.

## How the page is built

One HTML file draws the plate. Fonts are Space Grotesk and JetBrains Mono, both SIL Open Font License, stored in the repository so the page does not call a third party at runtime. There is no build step and no application server. GitHub Pages serves the `gh-pages` branch.

The clock is frame-locked. A requestAnimationFrame loop accumulates time and steps the simulation at 30 fps. Particles and vortex phase are functions of the frame number and a fixed hash, so scrubbing backward does not require a second physics history. The camera is a small set of keys, eased, then multiplied by a fit scale so a phone-width window still contains the wedge. `prefers-reduced-motion` parks on the nozzle plate until someone presses play.

Query `?f=230&pause=1` is the review URL. Space plays and pauses. Arrows step a frame. Shift-arrow steps a second.

I did not put a form on it. A film does not need a name, an email, or a cookie. I did not put an analytics tag on it either.

The source is [mizcausevic-dev/scramjet-anatomy-jig](https://github.com/mizcausevic-dev/scramjet-anatomy-jig).

## Who it is for

Use it if you have to explain a scramjet to someone who can read a section and will be misled by a cutaway that mixes force with velocity. That includes propulsion students, people writing about hypersonic flight who need a visual that will not invent a thrust number, and engineers who want a shared picture before they open a real inlet deck.

Do not use it to size an engine, to choose a fuel, to claim an inlet is started, or to brief a flight-safety case. The sibling explainer linked above is also not that document. Neither page is a certified reference.

The same player can hold a ramjet, a rocket nozzle, or a turbine stage. The rule that travels is the rule on this one: the last shot has to show force on the machine and velocity of the gas as two different arrows, and any number you did not compute stays off the plate.

## A note on the search

People looking for "scramjet explained," "what is an isolator," "shock-on-lip," or "single expansion ramp nozzle" usually get either a textbook chapter or a vehicle gallery. This piece is a third thing: a frame-locked plate with the reading instructions written beside it. The plate will not rank on the strength of this sentence. It is useful if the five shots, the color rule, and the refusal list save you from treating a schematic as a test.

Play it once at full length. Then park on the nozzle frame and check which arrows point downstream and which arrows point forward. If you can answer that without the caption, the drawing did its job.
