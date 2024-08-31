---
date created: 2024-08-18 10:40
tags:
  - Mongoose
  - UNFORMATTED
---

ROBOT HANDBOOK

Traveller ©2022 Mongoose Publishing Ltd. All rights reserved. Reproduction of this work by any means without the written permission of the publisher is expressly
forbidden. All significant characters, names, places, items, art and text herein are copyrighted by Mongoose Publishing Ltd.

This game product contains no Open Game Content. No portion of this work may be reproduced in any form without written permission. To learn more about the Open
Game License, please go to <http://www.mongoosepublishing.com.>

This material is protected under the copyright laws of the United Kingdom and of the United States. This product is a work of fiction. Any similarity to actual people,
organisations, places or events is purely coincidental.

is a registered trade mark of Mongoose Publishing Ltd.

Printed in China.

**CREDITS**

CLASSIC TRAVELLER

Marc Miller

MONGOOSE TRAVELLER

**AUTHOR**
Geir Lanesskog

**EDITOR**
Matthew Sprange,
Christopher Griffen

**LAYOUT/GRAPHIC DESIGN**
Cassie Gregory

**ILLUSTRATIONS**
Mark Graham, Brendan.J.Lancaster, Alejandro Arevalo,
Douglas Deri, Dimitar Spasov, Xavier Bernard, Mitch Mueller,
John Ric Detoon, Nikita Vasylchuk

**COVER ARTIST**
Nikita Vasylchuk

**PROOFING**
Charlotte Law

**ACKNOWLEDGEMENTS**
Joshua Bell, Thomas Jones-Low, Matthew Kerwin,
Jim Kundert

TRAVELLER INNER CIRCLE

Andrew James Alan Welty, Colin Dunn, M. J. Dougherty,
Rob Eaglestone, Sam Wissa, Joshua Bell, Maksim
Smelchak, Geir Lanesskog, Christopher Griffen

CONTENTS
INTRODUCTION 02
ROBOT DESIGN 06
CHASSIS 13
LOCOMOTION 16
CHASSIS OPTIONS 19
LOCOMOTION MODIFICATIONS 22
MANIPULATORS 25
DEFAULT SUITE 29
ZERO-SLOT OPTIONS 31
SLOT COST OPTIONS 41
BRAIN 65
SKILL PACKAGES 69
FINALISATION 76
SPECIAL ROBOTS AND OTHER SYNTHETICS 79
OTHER CONSIDERATIONS 106
ROBOTS AS TRAVELLERS 115
CENTRAL SUPPLY CATALOGUE: ROBOTS 118
ROBOTICS CONTROL CHART 124
ROBOT CATALOGUE 125
MILITARY ROBOTS 126
SERVICE ROBOTS 145
UTILITY ROBOTS 175
ALIEN ROBOTS 189
DRONES 208
MICROBOTS 217
NANOROBOTS 224
ANDROIDS 227
BIOLOGICAL ROBOTS 236
CYBORGS 239
AVATARS 243
CLONES 246
MISSILE ROBOTS 249
VEHICLE BRAINS 251
SHIP'S BRAINS 254
HIGH TECHNOLOGY 256

# I NTRODUCTION

A robot is an artificial being capable of reasoning and
motion. It may vary in capabilities, construction or
origin, but these two properties are always present,
even if its reasoning is limited to simple hard-coded
programming and its motion constrained to that of a
single manipulator or remote control of another object.

The Robot Handbook uses many of the same design
principles as the Vehicle Handbook. For the purposes
of this book, size is an important factor in determining
what is a robot versus what is a vehicle. The robot
design sequence is focused on machines smaller than
a large animal. For larger robots, the design rules of
the Vehicle Handbook apply to any intelligent machine
larger than four Spaces, although robot brains can be
designed using these rules and applied to a vehicle as
a zero Space option instead of a computer and possibly
in place of an autopilot. Also, robots in general do not
accommodate living beings as passengers, except in
special cases such as autodoc medivac robots.

While the Vehicle Handbook and High Guard
are useful references to have when developing
specialised robots such as ship’s brains, only the
Traveller Core Rulebook is required to understand
robot design and characteristics.

History of Robots
Robots are labour-saving machines that emerge
as part of the technological development of most
advanced races. They are good at repetitive, boring
tasks and can operate in hazardous environments
without risk to life. Despite these advantages, many
cultures have difficulty embracing robots as part of
everyday society. For some, they represent the loss of
jobs, for others the fear of a ‘robot revolution’. Whether
these concerns are rational or not, they sometimes
lead to violent opposition to the expansion of robots’
roles in civilisation.

Early robots are industrial machines that conduct
respective tasks, essentially a stationary manipulator
working on an assembly line. Mobility requires an
understanding of the local environment, incorporating
optical and range-finding technologies such as radar,
sonar and lidar to navigate autonomously. By TL8,

Primitive and Basic robot brains allow for mobile robots,
limited in flexibility but able to perform programmed
functions without continual guidance from an operator
or nearby biological being.

Increasing miniaturisation and sophisticated multi-
processing continues to drive down the cost of robotic
brains and increase their flexibility. By TL10, Advanced
robot brains gain the flexibility to perform a large variety
of tasks, although they fall short in understanding
subtler forms of communication or unravelling complex
problems. Still, as Advanced robot brains continue to
evolve, they become capable of replacing biological
beings in many occupations that require skilled labour.

Some societies embrace these advances; others shun
it. Tradition-bound societies such as the Vilani make
limited use of robots, employing them only for tasks
too hazardous for humans to perform. Other societies
are more open to the advantages of a larger labour
pool or need to employ robots to make up for deficits
in personnel; the [[Terra|Terran]] Confederation employed large
numbers of support robots in the Interstellar Wars
as they fought against a vastly larger empire. These
robots built facilities and transported supplies but a
fear of lethal robots turning upon their masters kept
the Solomani from employing deadly robots – warbots

- in the field. Ironically the Zhodani, who can read the

minds of their biological soldiers, have no issue with
deploying deadly robots to fight among their troops.

During the Second Imperium, domestic robots became
widespread but the development of Very Advanced
robotic brains did not begin until the early years of
the Third Imperium. In 298 the megacorporation
Makhidkarun produced the first Very Advanced
robotic brains with the ability to perform any task as
well as most humans. Continual improvement has
led to robotic brains that are self-aware, believing
themselves to be fully conscious; however, most
roboticists believe they still lack the true ‘spark’ of
sentience. Many of these robots would disagree.
Rumours of truly conscious intellects persist but these
are thought to be too large to fit within the shell of a
robotic body or at least within any robot smaller than a
small building or large vehicle.

**SHUDUSHAM CONCORDS**
The Third Imperium’s outlook on robotics
was formed more than a century before its
founding, based on an event that occurred in
-112 aboard the Empire’s Banner, a Sylean
Federation battleship. While the ship was on
a goodwill tour in orbit around Fornol (in the
Core) a terrorist group rigged a courier robot
to self-destruct and smuggled it aboard. The
robot’s fuel cell detonated, killing Fornol’s
Premier, two ambassadors and a Sylean vice-
minister, among other dignitaries and crew.
The event nearly led to a Sylean civil war.

The resulting conference between a dozen
Sylean worlds was held on the neutral world
of Shudusham, leading to the drafting of the
Shudusham Concords in -110. The Concords
limited weaponry carried by robots and their
use as instruments of war. The treaty contains
seven articles governing the programming of
robots, weapons control systems and detailed
regulation of weapons in those instances
allowed. Eventually the Concords acquired 43
amendments, including the 37th Amendment,
which prohibits a ‘pseudobiological’ or android
robot from impersonating a living being.

Technically, the Concords lost the force of
law in Year 0 when Cleon I declared the
Third Imperium and the Sylean Federation
ceased to exist, however many worlds within
the Imperium continue to base their robot
regulations on the Concords. One principal
that remains in force on nearly all those
Imperial worlds with written regulations
regarding robots is the principal that robots are
property and the responsibility of each robot’s
legal owner for any actions the robot takes and
any intentional or otherwise consequences of
those actions.

Introduction

TRAVELLER

Robots Across Charted Space
In Charted Space, robots are ubiquitous devices
common to nearly every industrialised civilisation
with computing technology. The acceptance of robots
within a civilisation varies greatly, with some cultures
treating them as just a new form of tool and others
with greater reservations, whether from the threat
to worker livelihood, fears of some future ‘robot
apocalypse’ or misgivings over the use of autonomous
lethal military machines.

While use and acceptance of robots differs greatly, no
major society has considered even advanced robots
as anything other than tools and property. While
advanced robots can emulate the behaviour of sentient
beings, they are generally considered non-sentient
and afforded few, if any, rights. As research into full-
conscious artificial intelligences progresses, questions
of robots’ rights may emerge but for now robots are
fancy tools, rumours of fully sentient artefacts of the
Ancients notwithstanding.

The robots of various races and polities outside the
Third Imperium and their cultural perceptions and
acceptance of robots are detailed in separate sections
of the Robot Catalogue.

THE THIRD IMPERIUM
The Third Imperium has no one law or policy regarding
robots, although the legacy of the Shudusham
Concords and old Vilani legends of the Ancients’ war
machines cast a shadow over most member world’s
laws. None of the Imperium’s armed forces use
lethal robots in the field. Although smart missiles and
autonomous defence systems are widespread, the
use of warbots or other directly lethal war machines is
contrary to doctrine. Robots are mostly used in support
roles such as logistics and construction.

Across the Third Imperium, service and utility robots
occupy low and semi-skilled roles in many industries.
Hazardous environments particularly see widespread use
of drones and robots, reducing risk to biological workers.

MAJOR MANUFACTURERS
There are literally millions of robot manufacturers
across Charted Space, ranging from workshops in
the back alleys of startowns to the vast manufacturing
complexes of megacorporations some of which may
encompass whole cities or honeycomb entire asteroids.
Robots with wide distribution are normally produced
by megacorporations, but these firms aim for broad
markets, achieving low cost and consistent quality
by producing millions of units of each design. The
megacorporations with robots as a major market
focus include Naasirka, Makhidkarun and Ling
Standard Products.

In quantity, Naasirka is the largest manufacturer
of robots in the Third Imperium and perhaps of all
Charted Space. Naasirka robots are available for
nearly every function. They are fairly reliable but
not particularly innovative, concentrating on mass
production and common components to achieve
economies of scale and using Naasirka’s aggressive
marketing to drive up sales.

The megacorporation Makhidkarun is as ancient as
Naasirka but focuses on entertainment and luxury
goods. Its computer and software division long ago
branched into robotics and became a pioneer of Very
Advanced and Self-aware robot brains. Makhidkarun
remains an innovative producer of complex brained
robots, targeting the high-end consumer market.

Ling Standard Products (LSP) manufactures a
wide range of robots. These robots are not elegant
or sophisticated but are reliable, with a focus on
industrial and utility robots capable of undertaking
hazardous and tedious tasks.

SPECIALITY FIRMS
Most speciality firms focus on a single niche or small
subset of the robotics market, hoping to stand out
from the heavily marketed Naasirka products. Many
are regional in scope, their factories shipping within
at most a domain or sector of the Imperium. One
such firm is Spinward Specialities, which focuses on
heavily armoured courier robots, all with a contoured
streamlined chassis to suggest speed and class.

Introduction

The best-known speciality firm is the Shinku University
Research Directorate or SURD, an innovative producer
of pseudobiological or android robots in the Core,
combining life-like appearance with sophisticated
robotic brains. Beginning as a research organisation,
their products often have a prototype-like feel but
command high prices for their limited production runs.
The four-century-old manufacturer is growing under the
guidance of professional managers, expanding product
lines and market scope as their products begin to
appear in the distant corners of the Imperium.

Robot Brains
In nearly all instances, robots are machines that move
under their own volition but their defining characteristic
is not shape or locomotion but their brains. The brain
determines the robot’s capabilities, controlling and
providing meaning to its movements. A robot’s brain
separates it from a fancy programmed automaton or
remotely controlled drone. The brain is often the most
expensive component of a robot as well.

True robots appear as early as TL7 but their Primitive
brains cannot exceed their programming in any
way. A Primitive brain does what it is told to do and
any contingencies or feedback are determined by
preprogrammed instruction. For simple tasks, such as
tracking a target, Primitive brains remain in production
even as more advanced options become available
because they are inexpensive and behave in a
predictable manner.

The Basic brain, first available at TL8, is a massive
improvement that incorporates ‘machine learning’
in its programming. This allows the robot to ‘learn’
from experience, albeit in a limited form, with much
of its behaviour still carefully programmed and its
‘learned’ behaviour little more than a decision tree
based on statistical analysis of a data set. The
Basic brain is limited to a core function and has no
general intelligence or capability for ‘common sense’.
It interprets data and makes decisions but has no
real understanding of what it is doing. The Hunter/
Killer brain is a derivative of the Basic brain focused
on security and military applications, capable of
determining friend from foe using user-defined criteria
that can be altered via later input. In any case, a Basic
or Hunter/Killer brain is as advanced as a smart insect

or dumb reptile. As technology advances, these brains
become cheaper and slightly more intelligent but they
remain focused on narrow tasks.

The Advanced robot brain is available at TL10 and
represents a massive step forward. The miniaturisation
of millions of individual computing elements makes true
learning possible within a package small enough to fit
inside a robot’s body. An Advanced brain allows a robot
to fully communicate in natural language and improvise
solutions in real time. It gives no thought to the ‘why’ of
an action but has the capability to make autonomous
decisions and learn from experience in a manner that
gives it limited ‘common sense’. The Advanced robot is
still a very literal being and may act inappropriately or
fail to act in unexpected situations.

The major development first pioneered by Makhidkarun
in 298 was the development of the Very Advanced
robotic brain. This brain approaches the complexity of
a biological brain in its number of connections. It does
not allow for full sentience – at least as defined by most
scholars – but allows for complex reasoning. Robots
with Very Advanced brains can attempt tasks outside
their programmed functions and develop opinions and
beliefs based on experience and reasoning. Synaptic
pathways designed for maximum efficiency are in some
ways more efficient than those developed by the trial-
and-error evolutionary method, and robots with Very
Advanced brains are capable of both biological-like
higher reasoning and the memory and computational
power of computers, making them better at certain
tasks than biological beings.

The most advanced robotic brains available in the
Imperium are the Self-aware brains first produced by
researchers in association with SURD. Few production
models are equipped with Self-aware brains for a
number of reasons, including their recent development,
high costs and lingering questions over sentience. Most
roboticists do not consider a Self-aware robot brain
to be fully conscious, pointing to differences between
these brains and large experimental mainframe units
whose processing arrays match human neural cell
quantities and connections. Philosophers and ethicists
dispute these assertions based on behavioural analysis
and testing results, pointing out that nearly half the
recognised sophont races within the Imperium would
fail to meet these roboticists’ standards.

Introduction

# R OBOT DESIGN

The major components of a robot design are size,
locomotion and brain. Determining these characteristics
and installing a few options and skill packages allows
for the rapid design of a standard robot. While not
required for complete robot design, modifications to
the characteristics, options and skill packages allow for
considerable additional adjustments to make a unique
robot with special attributes.

This design system is not based on exact volumes
and masses but on the assumption that certain
standard configurations apply and only deviations
from those standards require detailed design work.

The core design principles are:

•	 Size: Based on its Size, a robot body has a
certain number of Slots to be used for physical
equipment options.
•	 Locomotion: A robot body has a cost and traits
based on its primary locomotion capability. A
robot may also be immobile or have multiple
modes of locomotion. Primary locomotion without
options or enhancements has no Slot cost.
•	 Brain: All robots have a brain included. The
initial brain normally incurs no Slot cost, though
options applied to it might, and certain robot
Sizes might have limited brain capability at some
Tech Levels. Brains provide Bandwidth for skill
packages and Intellect enhancements.
•	 Default Suite: All standard robots have a default
set of five Zero-Slot options to provide sensory
input and communications capability. These can
be optionally upgraded, altered or replaced.
•	 Physical Options: Features or accessories
can be added based on available Slots. Items
requiring no Slots such as coatings and small
equipment are available at additional cost, limited
only by the robot’s Size and Tech Level.
•	 Skill Packages: Software to provide the robot
with skills is available based on Brain complexity
and Bandwidth.

Additionally, these core principles assume certain
design generalisations:

•	 A robot ‘head’ is an assumed feature for design
purposes. Unless removed in a robot description,
a ‘head’ in the form of a movable cluster of
sensory and communications capabilities is
assumed to exist.
•	 Robots are assumed to have two manipulators of
appropriate size for their bodies by default but this
can be modified by addition, deletion or resizing.
•	 Most basic traits and options can be enhanced
(or degraded) by additional design customisation.
•	 Special robot types, including drones, microbots,
nanorobots, androids, biological robots and other
artificial beings follow their own specialised design
processes derived from these standard principles.
•	 Larger vehicles with brains, including those
designed using the Vehicle Handbook or High
Guard, are physically created using the rules in
those books but can use modified versions of the
brain design process in this book.

Design Overview
The robot design process consists of the following steps.

Step 1: Chassis Size
Determine the physical size of the robot from Size 1 (rat-
sized) to Size 8 (rhino-sized). Physical size determines
the number of physical option Slots a robot has available
as well as the Base Hits and attack roll DMs for a robot
of this Size. Size modifies the Cost of the robot, although
not necessarily in a linear manner, as miniaturisation
costs often counter savings in material. Each chassis
includes a Default Suite of sensory and communication
functions, two manipulators of appropriate size and an
internal power system, all of which can be modified later
in the process.

Step 2: Locomotion
Determine the primary method of locomotion for the
robot. Locomotion options include wheels, tracks, walker
and grav, among others. The selected locomotion type
modifies the Base Cost of the robot and even the smallest
robots require a certain amount of equipment and control
circuitry to allow for locomotion. Basic locomotion modes
have various traits, including Flyer and ATV, which are
compatible with traits in the Vehicle Handbook. Robot
locomotion generally occurs at ground scale and speeds;
but additional options may allow a robot to achieve high
speed movement similar to vehicles.

Step 3: Physical Options
Physical options are grouped into seven categories:

•	 **Chassis Modifications:** Whole-body options that
alter characteristics or performance of a robot.
•	 **Locomotive Modifications:** These affect the
movement and speed of a robot.
•	 **Manipulator Modification:** These alter, add or
subtract manipulators or allow legs to
become manipulators.
•	 Default Suites: A list of Zero-Slot options that
provide sensory and communication capabilities.
•	 Zero-Slot Options: Small options that provide
additional capabilities. Zero-Slot options are not
infinite; in addition to the five Zero-Slot options of the
robot’s Default Suite, a robot design may incorporate
Zero-Slot options equal to its Size plus its build Tech
Level. Beyond Default (5) + Size + TL any additional
Zero-Slot options require one Slot each.
•	 Slotted Options: Larger features or equipment that
consume Slots.
•	 Weapons: These may be installed into weapon
mount options as part of the robot.

Step 4: Robot Brain
All robots have a brain. A robot’s brain determines its
capacity to understand and react to its environment, and
its ability to perform tasks. Different brains have different
purposes and capabilities. Optional alterations may
increase the capabilities of more advanced brains, adding
Bandwidth or Intellect.

Step 5: Skill Packages
Choose software packages that provide skills or
additional capabilities based on the robot’s brain,
Bandwidth and Tech Level.

Step 6: Finalisation
The robot design system abstracts the shape of a
robot into Size and method(s) of locomotion. Additional
options may modify these basic properties but often in
an abstracted manner. The designer should describe the
general shape of the robot – be it a humanoid mechanical
being or a floating ball with myriad tentacles or some
other form – in a manner consistent with the design
components chosen.

Finalisation includes filling out the robot statistics block,
listing such characteristics as Hits, Speed, TL, Cost,
Skills, Attacks, Traits and Programming. At the designer’s
discretion, Cost can be modified – usually downward – to
two significant digits and includes discounts based on the
ubiquity of the robot design and its role in society.

Robot Traits
The traits associated with robot design are similar to those
described in the Traveller Core Rulebook, Page 84.

•	 Alarm: When panicked or under threat, the robot
emits a loud sound, a recorded message or makes
a bright visual display, alerting others to the danger.
The alarm may include electronic messaging to a
central command post or to other robots, alerting
them to the threat and enabling them to take
appropriate action.
•	 Amphibious: The robot is equally at home on
land or in water. It does not suffer water damage
while submerged and its movement is less affected
underwater. Robots with only an aquatic locomotion
system are not automatically amphibious as they
may not be able to operate on land.
•	 Armour (+X): The robot has thick layers of physical
protection. It has an armour Protection score equal
to the figure shown in the Armour trait. Nearly all
non-biological robots have some inherent armour
protection unless an outer covering is intentionally
omitted or weakened.

Robot Design

TRAVELLER

•	 ATV: The robot can handle difficult terrain. It
receives DM+2 on checks to handle rough terrain.
If it is a walker, this robot has biological-like
flexibility to navigate hazards such as loose rocks,
underbrush and fallen trees.
•	 Flyer (X): The robot has propellers, thrusters, grav
drives or some other method of gaining altitude
and sustaining flight. When flying, it may travel at
a maximum Speed Band listed in the Flyer trait.
Without special options, a flying robot operates at
human-like speeds and has the Flyer (idle) trait.
•	 Hardened: The robot’s brain is immune to ion
weapons. Additionally, all radiation damage
inflicted on the robot is halved.
•	 Heightened Senses: The robot has better
hearing and sight than humans. It receives DM+
to Recon and Survival checks.
•	 Invisible: The robot is essentially invisible across
the electromagnetic spectrum through the use of
active visual camouflage technology. Attempts to
spot the robot are made at DM-4.
•	 IR Vision: The robot can sense its environment
in the visual and infrared spectrum, allowing it to
detect heat sources in the dark. It cannot detect
objects in a dark environment where there is no
temperature differential.
•	 IR/UV Vision: The robot can sense
its environment at a greatly extended
electromagnetic range, encompassing at least
infrared to ultraviolet wavelengths and perhaps
beyond, such as into microwave, radio or x-ray
wavelengths. This allows it to see clearly in
darkness and, at the Referee’s discretion, it may
notice certain electromagnetic emissions from the
equipment of Travellers.
•	 Large (+X): The robot is larger than a human
and presents a huge target. All ranged attacks
made against the robot gain a DM equal to the
score listed in the Large trait. Robots of Size 6+
are Large.
•	 Small (-X): The robot is smaller than a human
and presents a difficult target. All ranged attacks
made against the robot suffer a DM equal to the
score listed in the Small trait. Robots of Size 4-
are Small.

•	 Stealth (+X): The Stealth trait, as opposed
to to the Stealth skill, is the robot’s ability to
evade detection by electronic sensors such as
radar or lidar. In addition to the inherent DM
indicated (+X), Stealth applies a negative DM
to Electronics (sensors) checks equal to the
difference between the robot’s TL and that of the
device it is trying to evade.

Design Worksheets
A designer can use one of the design worksheets,
available in this book or as downloads, to aid the
build process. For complex robots with many options
the full Robot Design Worksheet is most useful but
for simpler robots, the Short Design Worksheet
version is adequate. In either case, the back portion
of the worksheet is a robot design block, allowing the
designer to provide information in a format used by this
book and other Traveller publications.

The example robot designs provided throughout the
following sections use these worksheets.

Example Robot Designs
Each design chapter ends with a discussion of two
example robots.

Steward Droid: Designed using the Short Design
Worksheet, this is a straightforward small humanoid
robot designed to act as a qualified steward aboard
a starship or as an all-around household butler. The
Steward Droid is designed and built at a TL12 facility.

StarTek: After returning from a trip to the Aslan
Hierate, the designer has become enamoured by
the highly capable Hikare’ Technician robot used as
a replacement for a female engineer on some Aslan
vessels. Designed using the Robot Design Worksheet,
the StarTek is a human-produced robot based on the
Hikare’ design concept. A very sophisticated robot,
StarTek is built and designed at a TL14 facility.

Robot Design

**Robot Name: ROBOT DESIGN WORKSHEET (PHYSICAL)**

**Characteristic Value Slots Effect Traits TL = Cost**

Chassis Size Hits = Basic Cost:
Locomotion Type Agility = Multiplier: X

Skill

Armour Base = Total =

Endurance = Hours

Power Packs Endurance = Hours

Resilient Chassis Hits: +

Light Chassis Hits: – Total Hits =

Agility + Final Agility =

Tactical Speed ± Final Speed = Final Endurance = Hours

Vehicle Speed? Vehicle Speed Band =

Enhancement: Final Speed Band =

Secondary Locomotion? Traits =

**# Size STR DEX Slots STR Mod/Final(DM) DEX Mod/Final(DM) Skill Cost**

1 2 3 4 5 6

**Default Suite (5 Zero-Slot Items)**

**Item Slots Notes TL Traits Skill Cost**

Physical Options
Item Slots Notes TL Traits Skill Cost

**ROBOT DESIGN WORKSHEET (PHYSICAL)**

Weapon TL Range Damage Magazine Cost Traits Cost

Robot Brain Type Slots TL Bandwidth Base INT Skill DM Capabilities Cost

Bandwidth Upgrade: + Adjusted Bandwidth = Zero Bandwidth Skills =
Intellect Upgrade: + Adjusted INT = Adjusted Bandwidth =
Trait:
Skill Package Level TL Bandwidth Characteristic/Trait Adjusted Skills Cost

Total Cost:

Name:
Description:

.

Robot Hits Locomotion Speed TL Cost

Skills
Attacks
Manipulators
Endurance
Traits
Programming
Options

Robot Name: ROBOT DESIGN WORKSHEET (SHORT FORM)
Characteristic Value Slots Effect Traits TL = Cost
Chassis Size Hits = Basic Cost:
Locomotion Type Agility = Multiplier: X
Skill
Armour Base = Total =
Endurance = Hours
Power Packs Endurance = Hours
Resilient Chassis Hits: +
Light Chassis Hits: – Total Hits =

Agility + Final Agility =
Tactical Speed ± Final Speed = Final Endurance = Hours

# Size STR DEX Slots STR Mod/Final(DM) DEX Mod/Final(DM) Skill Cost

1
2
Default Suite (5 Zero-Slot Items)
Item Slots Notes TL Traits Skill Cost
Visual spectrum sensor
Voder speaker
Audible sensor
Wireless data link
Transceiver, 5km (improved)
Physical Options
Item Slots Notes TL Traits Skill Cost

Weapon TL Range Damage Magazine Cost Traits Cost

**Robot Brain Type Slots TL Bandwidth Base INT Skill DM Capabilities Cost**

Bandwidth Upgrade: + Adjusted Bandwidth = Zero Bandwidth Skills =

Intellect Upgrade: + Adjusted INT = Adjusted Bandwidth =

Trait:

**ROBOT DESIGN WORKSHEET (SHORT FORM)**

Skill Package Level TL Bandwidth Characteristic/Trait Adjusted Skills Cost

Total Cost:

Name:
Description:

.

Robot Hits Locomotion Speed TL Cost

Skills
Attacks
Manipulators
Endurance
Traits
Programming
Options

## C HASSIS

A robot requires a body. Without physical form, a
robot is just a piece of software performing tasks
without directly interacting or moving through its
physical environment. For the purposes of these
design rules, general purpose robots range in size
from a rat to a rhinoceros, from a kilogram to a few
tons, or in terms of vehicle design, up to four vehicle
Spaces in size. Anything larger is considered to be

- and is physically designed as – a vehicle, though

such larger designs may be fitted with a robot brain.
Anything smaller is considered a microbot (insect-
sized) of limited capability, or a nanorobot (microbe-
sized), a single purpose robot commonly deployed in
swarms. Microbots and nanorobots are considered in
separate sections, beginning on page 105.

Size
Size determines the Basic Cost, physical capacities
and traits of a robot. The Base Slots value indicates
the physical option Slots available to the robot.
Unused Slots may be reserved as spare Slots for
future use or may be permanently removed at design
time to lower the Cost of a robot but the Base Slots
value remains unchanged for determining the Cost of
most full-chassis robot options.

**Robot Size**

Size Base Slots Base Hits Attack Roll DM Equivalent Size

Equivalent
Vehicle Spaces Basic Cost
1 1 1 -4 Rat 0 Cr
2 2 4 -3 Cat 0.02 Cr
3 4 8 -2 Dog 0.1 Cr
4 8 12 -1 Bwap, Droyne, Goat 0.25 Cr
5 16 20 +0 Human, Vargr, Dolphin 0.5 Cr
6 32 32 +1 Aslan, Cow, Lion 1 Cr
7 64 50 +2 K’kree, Bear, Shark 2 Cr
8 128 72 +3 Virushi, Rhino, Orca 4 Cr

The Base Hits value indicates the default damage
absorption capacity of the robot. Customisation may
increase or decrease the Hit capacity of a robot. When
a robot’s Hits reach 0, it is inoperable and considered
wrecked, or at least cannot be easily repaired; at
cumulative damage equal to twice its Hits the robot is
irreparably destroyed. The Attack Roll DM indicates the
difficulty of hitting the robot based on its Size. This also
corresponds to the robot’s Large (+1 or more) or Small
(-1 or less) trait.

A robot is assumed to have two standard manipulators
proportionally sized to its chassis and may or may not
have a head. These features are considered part of the
chassis of the robot and its actual physical form. While
important to the aesthetics and description of the robot,
these details do not influence its Cost or characteristics
and are left to the imagination of the designer.

Although unused Slots are often reserved for future
use, they can be permanently removed during the
design process. Permanent Slot reductions will not
lower the Slots required for ‘per Slot’ options such
as coatings and environmental protections, and are
noted at the end of the Slotted options record. Each
Slot permanently removed at design time will lower the
robot Cost by Cr100 and these cannot be restored by
post-design modifications. However, the minimum cost
for any robot is its Basic Cost.

TRAVELLER

SIZE, SLOTS, SPACES AND TONS
Size and Slots are not precise measurements
but abstractions of physical dimensions. Slots
represent available space for customisation
after the robot’s basic ‘guts’ are assembled. For
the purposes of determining the true dimensions
of a robot, for instance if one robot carries
another within it or attempts to use a fabricator
to create another robot, a robot is considered
to occupy twice the number of Slots as it can
use – a Size 5 robot has 16 Slots available but
another 16 Slots comprise its basic structure,
making the robot itself 32 Slots in size. The
equivalent Vehicle Handbook Spaces of a robot
is listed on the Robot Size table. Note that
while a human-sized robot is only 0.5 Spaces in
physical dimension, a seat for a human requires
a full Space (64 Slots): half for the human, half
for the seat and access to it.

A spacecraft ton – approximately 14 cubic metres

- is the equivalent of four Spaces or 256 Slots. Of

course this would make a Space equal to more
than 54 litres of volume but only if all Spaces were
perfect cubes. Both the Vehicle Handbook and
Robot Handbook use an abstract design system
that allows for straightforward design of vehicles,
robots and other objects without resorting to 3D
design software and assumptions about clearance
buffers and a myriad of other factors that prevent
objects from being crammed together without any
wasted space.

Using this 256-Slot extrapolation, a
corresponding ship ton is equal to a Size 8
robot (128 x 2). If designed with wings or as a
multilegged robot low to the ground, it could
require up to two ship tons for storage and
access however, for instance, a Size 7 autodoc
or low berth is designed to fit compactly on
a ship and requires only 0.5 tons. Four Size
5 humanoid robots could be squeezed into a
closet of 0.5 tons in a fashion that would allow
only one robot to emerge at a time. Such an
arrangement would be intolerable for a living
humanoid but consider the emergency low
berth, which crams four individuals and life
support systems into a single ton.

A robot Slot is assumed to be able to hold
the equivalent of an object massing around
three kilograms or at least three litres in actual
volume. This is a rough number. For instance,
a small weapon mount, requiring one Slot,
can hold any handgun or melee weapon of
reasonable size, although a two-handed battle
axe would likely require a two-Slot medium
mount. As with the design process in the Vehicle
Handbook, to avoid detailed design procedures
requiring precise dimensions and blueprints,
a certain amount of compromise and common
sense is required.

Chasis

**EXAMPLES**

Steward Droid
The Steward Droid design concept is for a humanoid
robot operating in an environment built for humans.
However, the robot is not likely to have a need for
many added features requiring Slots, so it can be
somewhat smaller than the standard human. The
designer envisions the robot as short and thin but
with long thin arms capable of reaching high shelves
or scooping items off the floor. The robot is smaller
than human-sized, or Size 4, with 8 Base Slots and
12 Base Hits. A Size 4 chassis has a basic cost of
Cr800. Its size gives it the Small (-1) trait, making it
harder to hit in combat.

Robot Name: STEWARD DROID
Characteristic Value Slots Effect Traits TL 12 Cost
Chassis Size 4 8 Hits = 12 Small (-1) Basic Cost: 800 800

StarTek
StarTek is envisioned to be an engineer and mechanic
on a starship. It might need to move heavy equipment
and carry a variety of tools but must also fit into an
environment built for humans and crawl into tight
spaces. While the Aslan version of this robot is larger
than a human, it is not suitable for use on human-
designed ships. Therefore, StarTek is Size 5 with 16
Base Slots and 20 Base Hits. A Size 5 chassis has a
basic cost of Cr1000 and has no size-related traits. The
designer envisions the robot as a broad-shouldered
humanoid with a blunt head.

**Robot Name:** STARTEK

**Characteristic Value Slots Effect** Traits TL 14 Cost

Chassis Size 5 16 Hits = 20 Basic Cost: 1000 1000

## L OCOMOTION

Robots are by definition mobile devices. Some
exceptions to this are stationary robots that perform
tasks with manipulators and emplaced command
unit robots, which remotely control drone subunits.
The number of locomotion units – whether wheels
or legs or propellers – is an aesthetic detail left to
the discretion of the designer, however designs
with more than eight legs, axles or thrusters may
optionally require additional Slots or cost. A robot
may optionally have multiple forms of locomotion
if Slots and cost are dedicated to them. When
designing a vehicle, the most expensive cost
multiplier is applied to the basic cost first and any
additional locomotion options are added as described
in the Secondary Locomotion section on page 23.

A choice of ‘None’ for locomotion adds 25% to the
robot’s available Slots, rounded up. This does not
increase the Base Slot number used to determine
coatings and other options but is one of the methods
a robot designer may use to obtain more than its
Base Slot value available for options.

A locomotion system includes dedicated sensors
that enable the robot to navigate a cluttered
environment and avoid collisions. These include
secondary video sensors, short range radar or lidar
emitters and acoustic emitters and equipment tied

to the locomotion system. For simplicity, these are
not treated separately from the locomotion system
and not related to sensors installed on the robot
for general use. Most robots are equipped with a
transceiver or wireless data link to communicate
with compatible buildings or other robots to aid in
navigation within structures, in urban environments,
along roads and potentially across a highly civilised
world’s surface.

A robot’s base Agility is determined by its locomotion
type. Agility is a factor in determining a robot’s
movement rate, modifying a robot’s base movement
rate of five metres per Minor Action in every six-
second combat round. Traits are similar to vehicle
Traits and described on Page 101. Traits for some
locomotion types may be modified during the design
process. Base Endurance indicates the duration
in hours a robot can function without recharging.
Endurance can be modified during the design process
by a variety of factors, including Tech Level, efficiency,
power packs and various speed modifications.

The Cost Multiplier for locomotion is applied to the
basic cost of the chassis Size to determine the Base
Chassis Cost, an important value in some robot
modification options.

Robot Locomotion
Locomotion TL Agility Traits Base Endurance Cost Multiplier
None 5 — — 216 hours x
Wheels 5 +0 — 72 hours x
Wheels, ATV 5 +0 ATV 72 hours x
Tracks 5 -1 ATV 72 hours x
Grav 9 +1 Flyer 24 hours x
Aeroplane 5 +1 Flyer 12 hours x
Aquatic 6 -2 Seafarer 72 hours x
VTOL 7 +0 Flyer 24 hours x
Walker 8 +0 ATV 72 hours x
Hovercraft 7 +1 ACV 24 hours x
Thruster 7 +1 — 2 hours x

**LOCOMOTION SPECIAL CHARACTERISTICS:**
Some locomotion types have special characteristics
beyond agility, movement rate and endurance.

Aeroplane locomotion requires a runway of at
least 50 metres for landing. Take-off normally
requires a similar distance but Size 1–3 aeroplane
robots can be launched by hand. Any aeroplane
locomotion robot can be launched from a moving
vehicle travelling at least Medium speed. A robot
with aeroplane locomotion must include the vehicle
movement speed enhancement (see page 22) to
avoid stalling; it cannot travel slower than Slow.
Slower flying movement requires a choice of VTOL or
grav locomotion. Basic landing wheels are included
but aeroplane locomotion requires some form of
ground secondary locomotion system to do more
than taxi on a runway.

Thruster is a special locomotive system which,
unlike other modes, is generally available only as
a secondary locomotion system although, for cost
reasons, its primary locomotion type can be ‘none’. A
thruster-equipped robot’s endurance is only invoked
while thrusters are firing; otherwise, the robot’s
primary locomotion mode’s endurance period applies.
A standard thruster provides 0.1G acceleration if not
modified, making it useful only in space or on worlds
of Size 0 or 1. Missiles and torpedoes are a special
class of robot that achieve higher acceleration with
thrusters as both primary and secondary locomotive
types and the vehicle speed movement modification
selected. Rules for missile and torpedo-based robots
are detailed on page 100.

VTOL or Vertical Take-Off and Landing locomotion
includes helicopters with one or more rotors, ducted
fan jet propulsion and tiltrotors, as well as ornithopter
designs. These vehicles require some form of
secondary locomotion if they are to move across the
ground at all.

VTOL and hovercraft robots suffer Agility -1 in
thin atmospheres but gain no benefit in dense
atmospheres. At the Referee’s discretion, such
robots might operate in very thin atmospheres on low
gravity planets at Agility -2 to -4.

LOCOMOTION TRAITS
ACV: The robot is equipped with an air cushion that
allows it to ride on a layer of air for movement over
both solid and liquid surfaces. The robot may not hover
more than a few metres and requires at least a thin
atmosphere to operate. These robots normally float if
their locomotion system is shut down over water.

ATV: The robot is equipped to handle difficult terrain.
This trait provides DM+2 to any checks made to
negotiate rough terrain. All robots equipped with
walker locomotion are considered ATVs.

Flyer (X): The robot is equipped to operate in
an aerial mode at vehicle Speed Band (X). An
aeroplane or VTOL robot requires at least a thin
atmosphere to operate. A grav robot can operate in
an airless environment but requires interaction with
a gravitational field; this may be an artificial gravity
field or the gravity well of a planetary-sized body but
the robot requires secondary thruster locomotion to
travel beyond 1,250km of a planetary body’s surface.
Without special options a flying robot will operate at
human speeds and have the Flyer (Idle) trait.

Seafarer: This robot is equipped to operate in a
liquid environment. By default, the robot operates
only on the surface of a liquid. Additional options
allow for submersible operation.

Thruster (X): The robot is equipped with thrusters
capable of acceleration equal to (X) G. By default,
secondary thruster locomotion provides 0.1G
acceleration. Missile-like thruster locomotion
provides 10G at TL8–13 and 15G at TL14+.

Some options apply to the entire robot, including
armour, resiliency and efficiency.

Locomotion

**EXAMPLES**

**Steward Droid**
The Steward Droid is intended to be humanoid in
appearance, making walker the obvious choice for
locomotion. Walker grants the ATV trait to the robot,
no modification to Agility and no modification to the
base movement speed of five metres. The walker
locomotion type multiplies the chassis size basic cost
by 10, making the Base Chassis Cost of the Steward
Droid Cr8000.

Robot Name: STEWARD DROID
Characteristic Value Slots Effect Traits TL 12 Cost
Chassis Size 4 8 Hits 12 Small (-1) Basic Cost 800
Locomotion Type Walker Agility Multiplier: X 10 8000

Robot Name: STARTEK
Characteristic Value Slots Effect Traits TL 14 Cost
Chassis Size 5 16 Hits 20 Basic Cost 1000
Locomotion Type Grav Agility +1 Flyer (idle) Multiplier: X 20 20000

StarTek
The StarTek robot is based on the Aslan Hikare’ robot,
which has both grav and walker locomotion modes.
Since grav locomotion has a higher cost multiplier
than walker, grav is considered the primary locomotion
mode and walker is added later as a secondary
locomotion mode. Grav locomotion grants the Flyer
(Idle) trait to the robot and Agility +1, modifying the
base movement rate to six metres. Grav locomotion
multiplies the cost of the Size 5 robot by 20, resulting
in a base chassis cost of Cr20000.

## C HASSIS OPTIONS

Armour
A robot’s base armour is determined by the technology
of its construction, with more advanced materials
having greater resiliency. In addition to innate structure,
a designer may add armour to a robot’s chassis at a
cost that includes use of physical option Slots.

The robot’s Base Protection is its value without
additional armour. Each point of additional armour,
up to the listed maximum, may be obtained for the
specified percentage of the robot’s Base Chassis
Cost and the allocation of a percentage of Slots
as indicated. Slots required are always rounded
up and any added armour requires at least one
Slot. Additionally, since robots are relatively small
compared to vehicles and armour is applied to
surface area, not volume, only a certain amount of
armour can be installed per Slot as indicated by the
robot armour table’s Maximum per Slot column. For
example, there is no way a rat-sized robot can have
five centimetres of armour around its entire surface;
the maximum per Slot values for armour simulates
this limitation.

Optionally, Base Protection can be reduced by -1 at
a cost savings equivalent to 10% of the robot’s Base
Chassis Cost. This exposes some of the robot’s internal
machinery and prevents installation of additional
armour or environmental protection. This has no effect
on the Base Chassis Cost computation in relation to
other modifications and options, and is not available to
any special robot types that lack base armour.

Androids and biological robots have no default
Protection and can only add a limited amount of armour
as indicated in their specific robot design sequences.

Endurance
A robot’s Base Endurance in hours is determined by
locomotion type. By default, a stationary robot can
continuously operate on internal power for nine days, a
ground-moving robot for three days and a flying robot
for one 24-hour day. After operating for this period of
time, a robot requires a full eight hours to recharge.
A robot with access to a power source can recharge
while operating normally, although this will tend to limit
mobility. Certain options may shorten recharge time or
provide auxiliary power to increase endurance.

Robots of advanced technology automatically have
additional endurance. At TL12 Base Endurance
is increased by 50%. At TL15 Base Endurance is
increased by 100%.

A robot may also increase endurance by using more
efficient components or dedicating additional space to
power storage. To increase endurance by efficiency, a
robot may have its endurance increased by 100% at
a cost of 50% of its Base Chassis Cost. This may be
done once and is applied after a TL increase.

A robot may also increase endurance with up to
three additional power packs. Each power pack
consumes 10% of the robot’s Base Slots (round
up) and increases endurance by 100%. This value
is calculated after any efficiency increase. A power
pack costs Cr500 per Slot consumed.

Robots whose endurance has been increased by
additional power packs gain the equivalent of Athletics
(endurance) skill at a level determined by the number of
power packs added.

Robot Armour
TL Base Protection Max. Slots Max. per Slot Cost per Slot
6–8 2 20 1% 1 Cr
9–11 3 30 0.5% 2 Cr
12–14 4 40 0.4% 3 Cr
15–17 4 50 0.3% 4 Cr
18+ 5 60 0.25% 5 Cr

TRAVELLER

Installed power options, as described beginning
on page 55, may further modify endurance and
performance. Endurance for robots equipped with a
radioisotope thermoelectric generator (RTG) or solar
power have their endurance calculated by using the
formulas described in Power Options on page 56.
However, default endurance might still apply in certain
situations, such as when a robot with solar power
spends extended periods in darkness.

Endurance Modifier TL Slots

Increased
Endurance

Athletics
(endurance) Cost
Improved Technology 12 — +50% — —
Advanced Technology 15 — +100% — —
Efficiency 7+ — +100% — 50% Base Chassis Cost
Power Packs (3 max.) 8+ 10% per pack +100% +1 per pack Cr500 per Slot

Resiliency Slots Hits Cost
Increased Resiliency (per Hit) 1 +1 5% of Base Chassis Cost
Decreased Resiliency (per Hit) — -1 -Cr50 x Locomotion Multiplier

Resiliency
A designer may dedicate part of a robot’s structure to
resiliency, using compartmentalisation and redundancy
to increase durability. Each Slot so dedicated increases
the robot’s Hits by +1 and costs 5% of the robot’s Base
Chassis Cost. No more than 50% of a robot’s Slots may
be dedicated to resiliency.

Conversely, a robot design may skimp on standard
resiliency practices. A robot design may reduce costs
by Cr50 times its locomotion multiplier for every Hit
reduced, up to 50% of the robot’s Base Hits.

Chassis Options

**Endurance Modifier TL Slots**

Increased
Endurance

Athletics
(endurance) Cost

Improved Technology 12 — +50% — —

Advanced Technology 15 — +100% — —

Efficiency 7+ — +100% — 50% Base Chassis Cost

Power Packs (3 max.) 8+ 10% per pack +100% +1 per pack Cr500 per Slot

Resiliency Slots Hits Cost
Increased Resiliency (per Hit) 1 +1 5% of Base Chassis Cost
Decreased Resiliency (per Hit) — -1 -Cr50 x Locomotion Multiplier

Steward Droid
The Steward Droid does not need additional
armour beyond the Base Protection +4 of a TL12
design. Base Endurance of 72 hours, modified by
TL12 to 108 hours, is plenty for a robot designed
to operate in a civilised environment. The robot is
not intended for harsh conditions or combat, so the
designer chooses to lower the robot’s resiliency by
2 Hits, saving (2 x 50 x 10) Cr1000 and lowering the
Steward Droid’s Hits from 12 to 10.

**EXAMPLES**

STEWARD DROID Cost
Chassis Modifications Skill
Armour Base 4 Total 4 Armour (+4)
Efficiency Endurance 108 Hours
Power Packs Endurance Hours
Resilient Chassis Hits
Light Chassis -2 Hits Total Hits 10 -1000

StarTek
The StarTek robot also has Base Protection +4 but may
operate in hostile conditions. The designer chooses
to add Protection +6 to give the robot total Protection
+10. Each point of armour requires 0.4% of the robot’s
total Slots, or (6 x 0.004 x 16) 0.384 Slots. Normally
this value would round to 1 Slot but to simulate the
relatively larger impact of surface area on smaller
objects, TL12–14 armour provides a maximum of
Protection +3 per Slot, so the added Protection +6
requires 2 Slots. The Cost for 2 Slots of TL14 armour at
Cr1500 per slot is Cr3000.

STARTEK Cost
Chassis Modifications Skill
Armour Base 4 +6 2 Total 10 Armour (+10) 3000
Efficiency ☐ Endurance 72 Hours 10000
Power Packs Endurance Hours
Resilient Chassis Hits
Light Chassis Hits Total Hits 20

The Base Endurance for grav locomotion is only 24
hours modified by TL12+ to 36 hours, which should
be sufficient for operating in a shipboard environment

- except when the robot is fixing the power plant. To

be safe, the designer could increase the efficiency
of the robot, doubling endurance at half the Base
Chassis Cost or adding power cells, each taking
10% of the robot’s Slots – rounded up to 2 Slots and
costing Cr1000. Adding power cells is cheaper but the
designer wants to ensure the robot has enough space
for onboard toolkits and Cr10000 is a minor cost for
a robot with a Very Advanced brain, so the designer
chooses to double endurance by increasing efficiency
and forgoing the power cells. The designer does not
alter the resiliency of the StarTek’s chassis, trusting
armour to keep the robot safe.

## L OCOMOTION MODIFICATIONS

Locomotion modifications alter the performance
characteristics of a robot’s primary form of
locomotion and allow for the installation of a
secondary locomotion mode.

Agility
Enhancements or restrictions to a robot’s Agility affect
its movement rate, its ability to manoeuvre in complex
environments and to dodge attacks.

Agility Enhancement
This modification requires no Slot utilisation but
increases the cost of a robot’s locomotive component
and grants the robot the equivalent of the Athletics
(dexterity) skill. It can be used in conjunction with
speed enhancements but costs are cumulative.
Each level of agility enhancement grants one level
of Athletics (dexterity) and increases overall Agility,
increasing tactical speed movement by +1.

Agility Enhancement Speed Skill Cost of Base Chassis Cost
Agility +1 +1 Athletics (dexterity) 1 100%
Agility +2 +2 Athletics (dexterity) 2 200%
Agility +3 +3 Athletics (dexterity) 3 400%
Agility +4 +4 Athletics (dexterity) 4 800%

Tactical Speed Enhancement
This modification requires no Slot utilisation but
increases the robot’s cost and tactical movement rate.
Each increase of one metre per round to a robot’s
tactical movement rate costs 10% of a robot’s Base
Chassis Cost. Tactical speed enhancement cannot
increase a robot’s tactical movement rate beyond
12 metres per Minor Action and each increase in
movement rate decreases a robot’s endurance by 10%.
Speed enhancement cannot be used in conjunction
with the vehicle speed movement modification.

Tactical Speed Reduction
This modification provides no Slot utilisation benefit but
decreases the cost of a robot and decreases the robot’s
tactical movement rate. Each decrease of one metre per
round to a robot’s tactical movement rate saves a cost
equal to 10% of a robot’s Base Chassis Cost. Tactical
speed reduction cannot decrease a robot’s movement
rate below 0 metres per Minor Action but each decrease
in movement rate increases a robot’s endurance by
10%. Tactical speed reduction cannot be used in
conjunction with the agility enhancement or vehicle
speed movement modifications.

Tactical Speed Enhancement Effects Cost of Base Chassis Cost
per +1 metre movement rate +1 metre movement rate
-10% endurance

10%

Tactical Speed Reduction Effects Cost of Base Chassis Cost
per -1 metre movement rate -1 metre movement rate
+10% endurance

-10%

###### OCOMOTION MODIFICATIONS

Vehicle Speed Movement
The vehicle speed movement modification adds a
vehicle-grade transmission and locomotion system to
the robot. This option requires 25% of a robot’s Base
Slots (round up) and provides locomotion at a rate
indicated in the Vehicle Speed Locomotion table.

The cost of the vehicle speed movement modification
is equal to the Base Chassis Cost of the robot. The
robot’s rate of movement may be increased by one
Speed Band at the expense of an additional 10%
of Slots and a further doubling of cost. This may be
done up to three times.

Vehicle speed movement benefits from either an
autopilot or a skill package appropriate for operating
that type of vehicle. The vehicle speed movement
modification includes a basic skill level 0 autopilot
but an additional autopilot option or a vehicle
skill package is recommended to perform any
complicated manoeuvres at high velocity.

Vehicle speed movement reduces a robot’s
endurance by a factor of four when in use. The
robot does not reduce endurance when moving at
normal speed of 5 + Agility. Each further movement
enhancement halves the robot remaining endurance.

Grav locomotion systems equipped with vehicle speed
movement are capable of propelling a robot to orbit.
A robot with regular tactical speed grav systems
could technically reach orbit of a Terra-sized world
in 10 or more hours but it could never reach orbital
velocity. In any case, the grav units used by robots are
lifter plates capable of functioning only within 1,250
kilometres of the surface of a world or a tenth of a
planetary diameter above a smaller world’s surface.

See the Missile Robots section starting on page 100
for speed and range limitations of vehicle speed
movement Thrusters.

Vehicle Speed Locomotion
Locomotion Speed Band
Wheels Slow
Tracks Very Slow
Grav High
Aquatic Very Slow
VTOL Medium
Walker Very Slow
Hovercraft Medium

Secondary Locomotion
A robot may use a secondary mode of locomotion.
The secondary mode’s locomotion cost multiplier
must be no greater than its primary mode and may
not use the vehicle speed movement modification.

A robot’s secondary locomotion mode requires 25%
of a robot’s Slots (round up) with each required
Slot costing Cr500 times the secondary mode’s
locomotion Cost Multiplier.

Robots envisioned to have more than eight legs,
axles or thrusters may be considered to have
a secondary locomotion option installed. This
locomotion mode must be identical to the original.
Other than aesthetics, this option allows a robot to
continue to function if its primary locomotion option is
disabled or destroyed by a Critical Hit. If the primary
locomotion mode has the vehicle speed movement,
an identical secondary locomotion system is
considered to have this option as well when both
locomotion systems are operational. If the one
system is disabled or destroyed, the robot’s vehicle
Speed Band is reduced by one.

Final Endurance
Endurance is determined from locomotion type,
technology, efficiency, power packs and any power
options. As efficiency normally exceeds a full day, in
settings where power is readily available such as a
technological society or aboard a vessel, endurance
can be effectively ignored. It is assumed that a robot
could plug in and recharge during ‘down hours’.
Efficiency is the total running time of the robot and
can be conserved if the robot goes into a standby
‘sleep’ mode. Recharging is assumed to take eight
hours regardless of its endurance unless a fast
charger option is installed.

To compute the robot’s effective endurance before
it requires a recharge, round the final result to the
nearest hour. For robots with the vehicle speed
movement modification and possible enhancements,
note the modified lower endurance while moving at
vehicle speeds in parentheses.

Locomotion Modifications

**Steward Droid**
The Steward Droid is intended to work with humans
and other species that have a movement rate of 6
metres. An increase of +1 to the robot’s movement rate
costs 10% of its Base Chassis Cost or a total of Cr800.
This decreases the robot’s endurance by 10% to 97.2
hours, rounded to 97 hours.

**EXAMPLES**

STEWARD DROID

Locomotion Modifications Cost
Agility Final Agility 0
Tactical Speed +1 Final Speed 6 Final Endurance = 97 Hours 800

STARTEK
Locomotion Modifications Cost
Agility Final Agility +1
Tactical Speed Final Speed 6 Final Endurance = 72 Hours
Vehicle Speed ☐ Vehicle Speed Band
Enhancement Final Speed Band
Secondary Locomotion Walker 4 Traits ATV 20000

StarTek
The StarTek robot does not need to move faster but
differently. Emulating the Aslan robot from which it was
based, the StarTek has a secondary locomotion system
of two legs, giving it a walker mode. The addition of a
secondary locomotion option requires 25% or four of
the StarTek’s Slots at a cost of (Cr500 x 4 Slots x 10
walker multiplier) Cr20000. The legs grant the StarTek
the ATV trait while walking.

## M ANIPULATORS

A base robot design includes two manipulators of a
size appropriate to the robot’s chassis Size; by default,
a chassis Size 5 robot has Size 5 manipulators. These
manipulators have a default STR of 2 x Size-1 and
DEX of TL/2 +1 (round up). These two manipulators are
included in the Base Chassis Cost of a robot. For many
robots, no further design is required for manipulators.
However, manipulators may be added, resized,
removed, strengthened or weakened.

Additional Manipulators
Additional manipulators cost Cr100 x Manipulator Size.
This initial cost is also the basis of any characteristic-
based cost modifications to the robot’s base or
additional manipulators.

Each additional manipulator requires 10% of a robot’s
Slots (round up) for the addition of one ‘same-size’
manipulator. Smaller manipulators can be added at a
Slot expenditure of 5% for one size smaller, 2% for two
sizes smaller or 1% for three or more sizes smaller.

Similarly, a robot may add manipulators of one or two
sizes larger, using 20% of Slots for one size larger or
40% of Slots for two sizes larger. It is not possible to
install manipulators more than two sizes above robot
Size, although a robot of Size 8 may have Size 10
manipulators if so designed. Regardless of size, all
additional manipulators require at least one Slot.

The cost of the manipulator is Cr100 x Manipulator
Size-equivalent, not robot Size. For instance, a Size 5
robot may add a Size 4 manipulator at a cost of 5% of
its Slots – rounded to one Slot – and Cr400.

To avoid computation, the Additional Manipulator
Slots table provides the requirements for
additional manipulators.

Altered Base Manipulators
Alterations to base manipulators are possible at design
time, removing them or making one or both smaller or
larger (within limits).

Removal: A robot does not require manipulators.
One or both standard manipulators can be removed.
Additional Slots gained for reducing manipulators
are 10% of the robot’s Base Slots per manipulator,
rounded up to always gain at least one Slot. Removing
a manipulator lowers the cost of the robot by Cr100
multiplied by the size of the robot but no more than
20% of the Base Chassis Cost.

Resizing: Changing the size of a robot’s
manipulators is the equivalent of removing it and
adding a different sized manipulator. To calculate
the Slots gained or lost by resizing, refer to the
Additional Manipulator Slots Requirement table and
use the size of the resized manipulator rather than
the robot size, then subtract the Slot requirement for
a manipulator of the robot’s size.

In addition, the following rules apply: if the
manipulator is smaller than the default size, it gains at
least one Slot for the robot to use. If the manipulator
is larger than default size, it requires at least one
additional Slot to install.

Additional Manipulator Slots
Slots Required Robot Size
Additional Manipulator Size vs Robot Size % of Base Slots 1 2 3 4 5 6 7 8
+2 40% 1 1 2 4 7 13 26 52
+1 20% 1 1 1 2 4 7 13 26
Same Size as Chassis 10% 1 1 1 1 2 4 7 13
-1 5% 1 1 1 1 1 2 4 7
-2 2% 1 1 1 1 1 1 2 3
-3 (or less) 1% 1 1 1 1 1 1 1 2

TRAVELLER

Resizing a manipulator changes the robot’s cost by
Cr100 x the difference in Slots between the robot’s
default manipulator size and actual manipulator
size. Therefore, the cost is increased by Cr100 if the
resized manipulator is one Slot larger and decreased
by Cr100 if one Slot smaller. The Base Chassis Cost
cannot be reduced by more than 20% by reducing
manipulator size.

Altered Characteristics
Rather than increasing or decreasing a manipulator’s
size, it can have its STR or DEX characteristics
increased. This change has an associated Cost but
does not impact Slots.

Strength: Increasing a manipulator’s STR costs an
additional amount equal to its base manipulator cost
multiplied by the square of its increase in STR. For
example, a Size 5 manipulator increased from STR
9 to STR 10 (+1) costs an additional Cr500 (Cr100
x 5 x 1 x 1), while increasing the same manipulator
to STR 15 (+6) requires an additional cost of
(Cr100 x 5 x 6 x 6) Cr18000. A manipulator may
not have its STR increased beyond twice its default
value; therefore, the maximum STR of the Size 5
manipulator would be STR 18 (9 x 2 for +9) at a Cost
of (Cr100 x 5 x 9 x 9) Cr40500.

Dexterity: A manipulator may have its DEX
increased to a limit of its TL+3 at twice its base
manipulator Cost multiplied by the square of its
increase in Dexterity. For instance, at TL10, a size 5
manipulator would normally have a DEX of 12 ÷ 2 +
1 = 7 but it could be increased to 10 (+3) at a cost of
Cr200 x 5 x 3 x 3 or Cr9000. DEX could be increased
to a maximum of 13 (TL10+3 for a total DEX +6) at a
cost of Cr36000 (Cr200 x 5 x 6 x 6).

Manipulator Characteristics
Characteristic Default Value Maximum Characteristic Cost Formula
STR 2 x Manipulator Size - 1 2 x default STR Manipulator Size x (net increase STR)^2 x Cr100
DEX TL ÷ 2 +1 (round up) TL+3 Manipulator Size x (net increase DEX)^2 x Cr200

Both STR and DEX can be increased, with the costs
combined. For instance, a TL10 Size 5 manipulator
increased from STR 9, DEX 7 to STR15, DEX 10
would cost (Cr18000 + Cr9000) Cr27000.

Walker Legs as Manipulators
A robot designed as a walker may enhance a leg
to operate as a manipulator by paying the base
manipulator cost of a robot of its Size (Cr100 x
Size per modified manipulator). Multi-legged robots
may have one, some or all legs altered into multi-
functional limbs but their size may not be altered.
For design simplicity a multi-legged walker with
legs altered to become manipulators is considered
to have two legs; for example, designing an eight-
limbed robot with all limbs as manipulators would
involve keeping the two original manipulators, adding
four manipulators and altering the two default legs to
become manipulators.

Manipulator Athletics Skill Requirements
Increased DEX and STR values do not directly grant
a skill equivalence of Athletics (dexterity) or Athletics
(strength) to the robot unless it has a skill package
of Athletics installed in its brain. If such a package is
installed, even at skill level zero, then DMs for high
STR or DEX are applied to simulate that skill level,
although in situations where different manipulators
have different DMs, the Referee should determine
whether a DM applies. Note that a robot with DEX 15
manipulators and Athletics 0 would be considered to
have Athletics (dexterity) 3 for skill recording purposes
but would not receive an additional DM+3 to that skill
while attempting checks using Athletics (dexterity).

Manipulators

**VEHICLE ROBOT MANIPULATORS**
The Vehicle Handbook includes specifications
for manipulator installation on vehicles on
page 59. Vehicle-installed manipulators
are considerably larger than robot-installed
manipulators and require additional equipment
to control their limbs. Optionally, vehicles of
four or less Spaces may install robot-scale
manipulators using the Robot Handbook.
These manipulators are waldo arms controlled
by the vehicle operator. For the purposes of
vehicle to robot conversion and manipulator
specifications and pricing, a four-Space
vehicle is equivalent to a Size 8 robot, a 2–3
Space vehicle is equivalent to Size 7 and a 1
Space vehicle to Size 6. Up to four vehicle-
installed robot manipulators can be installed
using one vehicle Space. A vehicle sized at
one Space may install two Size 5 (or smaller)
manipulators without using its only Space.

**Steward Droid**
The Steward Droid has two Size 4 manipulators by
default, with STR 7 (2 x Size - 1) and DEX 7 (TL ÷ 2
+1). This is perfectly adequate for a domestic robot and
requires no modification.

**EXAMPLES**

STEWARD DROID
Manipulators (including modified legs)

Siz e STR DEX Slots STR Mod/Final(DM) DEX Mod/Final(DM) Skill Cost

1 4 7 7
2 4 7 7

STARTEK
Manipulators (including modified legs)

 Siz e STR DEX Slots STR Mod/Final(DM) DEX Mod/Final(DM) Skill Cost

1 5 9 8 0 +3/12 (+2) 0 Athletics (strength) 2 4500
2 5 9 8 0 +3/12 (+2) 0 4500
3 3 5 8 -1 0 +4/12 (+2) n/a 9900
+
+
+

**StarTek**
The StarTek robot has two manipulators that need
to be upgraded for heavy lifting. At TL14, these
manipulators have STR 9 and DEX 8. To allow for
heavy lifting, the two Size 5 arms can be increased
to Size 6, gaining a default STR 11, but that expends
Slots (10% rounded up to require 2 Slots per
manipulator), so instead they are enhanced to STR
12, a +3 modification from default costing (Cr100 x 5
Size x 3 x 3) Cr4500 per arm.

For more delicate work, a third manipulator of Size
3 is added with STR 5 and DEX 8. Being two sizes
smaller than the base robot, this manipulator requires
2% of the robot’s Slots, rounded up to one Slot. To
be nimble for this delicate work, this manipulator has
DEX +4, giving the manipulator DEX 12. At Size 3 this
third manipulator has a base Cost of Cr300 (Cr100
x 3) with the added DEX +4 enhancement at (Cr200
x 3 Size x 4 x 4) Cr 9600 for a total cost of Cr9900.
Despite the increased cost, the manipulator does
not gain a general Athletics (dexterity) DM even if
the robot has an Athletics skill package because the
Referee determines that the DEX modifier is limited to
the specific actions of the small arm.

## D EFAULT SUITE

Every robot Size 1 or larger includes a Default Suite
of five Zero-Slot options to allow for basic sensory and
communication functions. The standard Default Suite
available at TL8 and above includes:

•	 Visual spectrum sensor (380 – 750 nm)
•	 Voder speaker – voice modulation
•	 Auditory sensor (20 – 20,000 hertz)
•	 Wireless data link (50 metres)
•	 Transceiver 5km (improved)

This allows the robot to have vision, audio input and
output, and connections to a local computer network
and a city-range radio network. The Default Suite is

included in the cost of the base chassis but removal
of components does not alter the cost of the robot.
Any Zero-Slot item can be installed as a substitute
component in the Default Suite.

Other options available at no additional cost when
substituted as one of the five Default Suite Zero-slot
items are:

•	 Drone Interface – for remote control, available at TL6
•	 Transceiver 5km (basic) – available at TL7
•	 Video Screen (basic) – low resolution LCD,
available at TL7

**Steward Droid**
The standard Default Suite is adequate for the Steward
Droid and is included at no cost. It adds no traits or
skills to the robot.

**EXAMPLES**

**StarTek**
The StarTek robot requires sensors that span the
electromagnetic spectrum. The designer replaces
the visual spectrum sensor with a PRIS sensor. This
sensor could have been added as a separate Zero-
Slot component but as the PRIS sensor includes the
visual spectrum, the designer deems it more efficient
and aesthetically appealing to replace the default
sensor. The PRIS sensor adds Cr2000 to the cost of
the Default Suite and provides the StarTek robot with
the IR/UV Vision trait.

STEWARD DROID
Default Suite (5 Zero-Slot Items)
Item Slots Notes TL Traits Skill Cost
Visual spectrum sensor 0
Voder speaker 0
Audible sensor 0
Wireless data link 0
Transceiver, 5km (improved) 0

STARTEK
Default Suite (5 Zero-Slot Items)
Item Slots Notes TL Traits Skill Cost
Visual spectrum sensor 0 Upgrade 12 IR/UV Vision 2000
Voder speaker 0
Audible sensor 0
Wireless data link 0
Transceiver, 5km (improved) 0

## Z ERO-SLOT OPTIONS

Some options are small enough to require no Slots.
These options include items that are applied to the
outer surface of a robot or take up negligible internal
space and generally have a mass of no more than one
kilogram. A robot’s surface area and volume are finite,
however. In addition to the five Zero-Slot options of the
robot’s Default Suite, a robot design can incorporate
additional Zero-Slot options equal to its size plus
its Tech Level. Beyond Default (5) + Size + TL any
additional Zero-Slot options require one Slot each. To
conserve space for additional options, a robot’s design
can incorporate any of the Zero-Slot options listed in
this section as part of a custom Default Suite.

Additionally, microbots can only have Zero-Slot
options. Specific limitations and properties of these
tiny robots are described in the Microbots section
starting on page 80.

Chassis Surface
In addition to armour, a robot has some options
that can be applied as coatings to its surfaces.
Zero-Slot option coatings are listed in this section;
other surface options are available but require Slot
expenditure and are listed in a later section. The cost
for all chassis surface options is multiplied by the
Base Slots for the robot’s chassis Size.

Camouflage: Visual Concealment
Visual camouflage is designed to conceal a robot
from visual detection, focusing on the human visual
spectrum at lower Tech Levels and expanding into
infrared, ultraviolet and beyond as Tech Levels
improve. Lower Tech Levels rely on static colours
and materials to achieve an effect, rendering
camouflage ineffective in inappropriate terrain;
camouflage patterned for a pink forest environment
will not work on a rocky asteroid. Advanced TL12
camouflage is an adaptive multi-chromatic coating
that conforms to all terrains; it can also be used to
achieve full-motion 2D video across the robot’s hull
for styling or advertising purposes. Superior TL13
camouflage uses visilight technology to actively
bend light around the robot with fibre-optic emitters,
rendering the robot nearly invisible.

Minimum range is the shortest range at which
camouflage is effective in its intended environment.
This value assumes a robot of Size 5. Smaller robots
may benefit from camouflage at shorter ranges
at the Referee’s discretion, whereas the opposite
could be true for larger robots. The Detection DM
for camouflage is applied against Recon checks to
detect the robot and considered the equivalent of the
robot’s Stealth skill. A reflec armour renders visual
camouflage ineffective.

Camouflage: Visual Concealment
Camouflage TL Minimum Range Detection DM Notes Cost per Base Slot
Primitive 1 500 -1 Natural materials Cr1
Basic 4 250 -2 Painted patterns Cr4
Improved 7 100 -2 +Infrared and thermal protections Cr40
Enhanced 11 50 -3 +Full spectrum Cr100
Advanced 12 10 -4 +Multi-chromatic Cr500
Superior 13 1 -4 +Visilight Cr2500

TRAVELLER

Camouflage: Audible Concealment
Camouflage TL Minimum Range Detection DM Notes Cost per Base Slot
Basic 5 50 -1 Coverings and dampers Cr5
Improved 8 10 -2 +Active sound dampening Cr10
Advanced 10 5 -3 +Active sound projection Cr50

Camouflage: Olfactory Concealment
Camouflage TL Minimum Range Detection DM Notes Cost per Base Slot
Basic 7 100 -1 Chemical coating Cr10
Improved 9 20 -2 +Active emissions Cr20
Advanced 12 10 -3 +Active negation Cr100

Item TL Cost per Base Slot
Hostile Environment
Protection

6 Cr300

Item TL Cost per Base Slot
Reflec Armour 10 Cr100

Camouflage: Audible Concealment
Audible camouflage is designed to conceal a robot
from the detection of sound, muffling the noise from
its motors, limbs and locomotion. Audible camouflage
negates the Heightened Senses trait when applied
to detecting the concealed robot but is only applied
against Recon checks when the robot is not in line of
sight or protected by visilight camouflage. If a robot is
capable of both audible and olfactory camouflage, the
camouflage DM associated with the primary sense of
the detecting party is used against Recon checks.

Camouflage: Olfactory Concealment
Olfactory camouflage is designed to conceal a robot
from chemical detection by other machines and
beings reliant on smell as a primary sense. Olfactory
camouflage negates the Heightened Senses trait
when applied to detecting the concealed robot but is
only applied against Recon checks performed when
the robot is not in line of sight or protected by visilight
camouflage. If a robot is capable of both audible and
olfactory camouflage, the camouflage DM associated
with the primary sense of the detecting party is used
against Recon checks.

Hostile Environment Protection
A robot equipped with a hostile environment
protection package has an outer shell capable of
withstanding hostile environmental conditions, including
temperatures between -50o C and +50o C, high and low
humidity, up to 500 rads of radiation, most biological
attacks and Atmospheres 2–9, A, D and E. Survival
in full vacuum or trace atmospheres requires vacuum
environment protection but hostile environment
protection allows a robot to function in vacuum
conditions for twice as long as an unprotected robot.

Reflec Armour
Reflec armour consists of a shiny plastic coating that
provides protection against laser fire. Reflec is not
compatible with visual camouflage since it negates the
associated stealth bonus and imposes an additional
DM-2 on Stealth checks. Reflec armour provides
Protection +10 against laser fire in addition to the
robot’s existing armour.

Zero-Slot Options

Solar Coating TL Maximum Flying Speed Maximum Ground Speed Cost per Base Slot
Basic 6 None 1m Cr500
Improved 8 None 2m Cr100
Enhanced 10 1m 4m Cr200
Advanced 12 2m Full Cr500

**Solar Coating**
A solar coating option covers the surface of the robot
with photovoltaic cells. It is not compatible with reflec
or visual camouflage options. The solar coating allows
near unlimited endurance in sunlight, at habitable
distances from most stars, but limits the power
output of the robot, reducing mobility if not used in
conjunction with the standard power supply or power
cell included in a robot.

Solar coating power restrictions only apply to robots
that have exceeded their endurance period or
have no internal power system. These restrictions
depend on the robot’s mode of locomotion and
amount of available sunlight. In low light conditions,
such as cloudy or indoor environments, reduce
the capabilities of the solar coating to the next
less-advanced version. For each orbit beyond the
habitable zone of a star, reduce the capabilities by
one level. For example, Improved Solar Coating
functions at the Basic level when operating one band
out from the habitable zone. However, moving closer
to a star than the habitable zone does not gain any
capabilities and risks the robot overheating.

During periods of sunlight a basic solar coating can
fully recharge a power system or power pack in four
times the duration of its endurance if the robot is
dormant or limited to zero mobility. More advanced
solar coatings can recharge power packs at a one-
hour-per-hour basis for a dormant robot and at one
fourth the rate for a robot performing minimal activities
and moving at no more than one-metre speeds.

Maximum Flying and Ground Speeds refer to the
maximum movement rate when operating on solar
power only, if regular power is not installed or depleted.

Zero-Slot Options

TRAVELLER

Item TL Cost per Base Slot
Vacuum Environment
Protection

7 Cr600

Vacuum Environment
Protection (biological)

10 Cr50000

ROBOTS IN VACUUM
Robots do not need to breathe but some power
systems rely on the presence of atmospheric
gas, usually oxygen, to function and many
designs assume components can be cooled
using convection provided by an atmosphere,
not just radiative cooling in vacuum. While a
robot not equipped with vacuum environment
protection does not cease to function
immediately in a vacuum or trace atmosphere, it
does operate less optimally.

A robot without vacuum environment protection
operating in vacuum or trace atmosphere suffers
a 50% decrease in endurance and requires a
malfunction check (see Robot Maintenance on
page 108) every hour of operation, with DM-2 to
the check if the robot is operating in temperatures
above 100oC or below -100oC. A robot with hostile
environment protection only requires a check
every two hours.

Androids suffer no additional ill effects, except
those as noted, but biological robots suffer
the same effects as their template lifeform in
vacuum conditions.

Item TL Cost
Drone Interface 6 Cr100

Vacuum Environment Protection
A robot equipped with a vacuum environment protection
package has a sealed outer shell and internal
components capable of functioning in the hostile
environment of outer space. A vacuum protection
package includes all of the capabilities of a hostile
environment package and expands the operational
temperature range to between +250oC and -250oC.
A robot equipped with this package can operate in
Atmospheres 0-A, D, E and some F environments as
well as underwater to a depth of 10 metres in standard
atmosphere and gravity. The robot can survive for a
number of hours equal to its Tech Level in corrosive (B)
environments and its Tech Level in minutes in insidious
(C) environments. Vacuum environment protection for
biological robots applies to those based on beings that
cannot normally survive vacuum or trace environments.

Communications
A robot can communicate in a variety of ways, from
voice to video to radio waves. Many of these can be
miniaturised to be usable by even the smallest of
robots as Tech Levels improve.

Drone Interface
A drone interface is primarily a receiver for controlling
drones but also allows a robot’s brain to be
bypassed, allowing it to act either as a drone while
under remote control, or a robot when operating
independently or out of range of a drone controller.
A drone interface connects a communications
device such as a transceiver to the robot’s brain,
integrating with locomotion and sensory systems.
A robot equipped with a drone interface requires no
additional actuators to operate as a drone. A drone
interface can be substituted for any component of a
robot’s Default Suite at no cost.

A drone interface can act as an override switch,
allowing an authorised user to take complete control
of the robot or shut it down. Regulations in some
jurisdictions require the installation of a drone
interface on all robots. To command the robot, a
biological remote user requires a drone interface,
although another robot can control robots or drones
more efficiently with a robotic drone controller.

A drone interface also acts as an inhibitor (see page
120) that allows for remote shutdown and geofencing

- limiting the operating range – of robots. In most

cases a robot allows the drone interface to override
its conscious functions or at least gain control of its
movements. A recalcitrant robot with an Advanced or
more sophisticated brain can ‘resist’ a drone interface
take-over, requiring the controller to actively gain
control (see Hacking Robots on page 106). Some
robots can shut down a drone interface after detecting
a failed attempt to take control. Others can shut down
a drone interface at any time, although the ability
to ‘self-isolate’ is usually not an option for drone
interfaces installed in jurisdictions that require them.

A drone interface requires a separate transceiver to
be installed.

Zero-Slot Options

Item TL Cost
Encryption Module 6 Cr4000

**Encryption Module**
A robot may use specialised hardware to encrypt
communications prior to transmission. This equipment
also encrypts data on the robot itself, including brain
and memory functions. Decryption normally requires a
Very Difficult (12+) Electronics (comms) or Electronics
(computers) check but encryption created at a higher
Tech Level is generally impossible to decrypt within
a reasonable timeframe. Decrypting an encryption
algorithm created at a lower Tech Level provides
at least DM+1 for every Tech Level a decryption
tool is superior to the technology used to encrypt
the information. By TL8 nearly all transmissions
are encrypted by default but the encryption module
provides a much higher degree of protection against
advanced decryption methodologies, which target
weakness across the entire communications chain.

Attempts to gain unauthorised access or hack into
an encryption module robot require a successful
decryption attack prior to the access attempt unless
the hacker is in possession of an authorised drone
control interface with the robot’s authorisation
decryption key installed.

**Transceiver**
A transceiver is a two-way radio device capable
of directly communicating between transceivers
or with a local telecommunications network. The
transceiver in the standard Default Suite has a range
of 5km, although more powerful transceivers can
communicate with it at greater ranges. By using a
local telecommunications network, the 5km transceiver
can reach any other node within that network. On
many TL8+ worlds with substantive populations, this
includes communications via satellite relay to any other
transceiver on the planet.

To reliably communicate directly with a ship in orbit,
a transceiver requires a minimum range of 500km. At
lower Tech Levels, transceivers are bulky and require
slots. Zero-Slot transceivers, their ranges and costs
vary with Tech Level.

Transceiver Range (km) TL Cost
Basic 5 7 Cr250
Improved 5 8 Cr100
Improved 50 8 Cr500
Enhanced 50 10 Cr250
Advanced 50 13 Cr100
Improved 500 9 Cr1000
Enhanced 500 11 Cr500
Advanced 500 14 Cr250
Improved 5,000 9 Cr5000
Enhanced 5,000 12 Cr1000
Advanced 5,000 15 Cr500

Video Screen TL Screen Resolution Cost
Basic 7 2D: 640 x 480 Cr200
Improved 8 2D: 1,920 x 1,080 Cr500
Advanced 10 3D: 16K x 9K Cr2000

Video Screen
The video screen is a flat panel for displaying still or
moving images built onto the surface of the robot. The
cost for this option assumes a small screen but an
option to extend it to cover the entirety of the robot is
available by multiplying the cost of the screen by the
Base Slots of the robot’s Size. This full-screen option
can be used as an improvised camouflage coating,
providing the equivalent of basic visual camouflage
compatible with any terrain. A basic video screen can
be included as a no cost item in a Default Suite. Video
screens do not include a voder speaker but can emit
pre-recorded or transmitted sounds.

Zero-Slot Options

TRAVELLER

Item TL Cost
Voder Speaker 8 Cr100
Voder Speaker (broad spectrum) 10 Cr500

Item TL Cost
Wireless Data Link 8 Cr10

Voder Speaker
A voder is a speech synthesiser for audible
communications in a robot’s known languages. A
voder differs from a standard audio speaker in that
it actually generates sound based on the robot’s
inputs, not playing a pre-recorded or transmitted
audio message. The voder can also emit non-speech
sounds, including alarms, music or sounds from the
natural environment, although a source for these
sounds and sophistication of speech is a function of
the robot’s brain and programming. By TL9 a voder’s
speaking voice is indistinguishable from natural
speech. When not included as part of a Default Suite,
a voder costs Cr100.

A broad-spectrum voder speaker can emulate sounds
beyond most species’ hearing ranges, useful when
communicating with aliens who use ultra-low or ultra-
high frequency sounds.

Wireless Data Link
A wireless data link provides high-speed secure
communications to a local data network such as those
within a building or ship. The data link includes an
inherent Security/0 package and encryption capable of
secure communications protocols of up to the robot’s
Tech Level. A wireless data link is available at TL8.
When not included as part of a Default Suite, a wireless
data link costs Cr10.

Wireless data links transmit and receive data at 10
times the rate of a comparable transceiver of the same
Tech Level. To transfer new or upgraded skill packages
a robot requires either a wireless data link connection
or to be connected directly to the issuing data system.

Item TL Cost per Base Slot
Gecko Grippers 9 Cr500

Item TL Cost
Injector Needle 7 Cr20

Miscellaneous
This section includes a variety of Zero-Slot options not
covered by other categories.

Gecko Grippers
Much like its namesake, gecko grippers use the
Van der Waals force to enable to robot to adhere to
surfaces, including walls and ceilings. A robot equipped
with gecko grippers can climb vertical surfaces and
adhere to the walls and ceilings of almost any material
in gravity environments ranging from 0–1.5 G although
movement is halved while traversing these surfaces.

Injector Needle
An injector needle is essentially a stinger equipped
with a hollow tip, allowing it to deliver fluid into a target.
This could be medicinal, poison, acid or any fluidic
substance. An injector needle is treated as a stinger,
requiring a successful melee attack to use. It inflicts
one point of damage and has AP equal to the base
armour of the robot of its Tech Level (see page 19).
Subsequent effects depend upon the fluid injected
into the target. An injector needle contains enough
fluid for a single attack but can be used as a stinger in
subsequent combat rounds until refilled.

A robot may install multiple needles but each counts as
a separate Zero-Slot option; up to four needles may be
clustered and used in a single attack. Injector needles
are available at TL7 for Cr20 each.

Zero-Slot Options

**Laser Designator**
A laser designator is a low-powered laser, usually
infrared to avoid visual detection, used to identify
a target for tracking or for guided munitions to
strike. Successfully targeting an object with a laser
designator requires an Average (8+) check as a
Minor Action. The laser designator is considered the
equivalent of a ranged weapon with a 100-metre
effective range, with all bonuses for DEX and range
applying, but no skill required.

A fire control system linked to a laser designator
receives DM+2 to attack a target successfully
illuminated. The designation is effective until the end
of the subsequent combat round. The designation
check must be repeated each round to be successful,
but subsequent checks receive DM+4 if designating
a stationary target.

Item TL Cost
Laser Designator 7 Cr500

**Magnetic Grippers**
Magnetic grippers enable a robot to adhere to metallic
surfaces in gravity environments ranging from 0–1.5G.
It can climb metallic walls and walk across metallic
ceilings, although movement is halved while traversing
these surfaces. Magnetic grippers are not useful on
ceramic, plastic or natural material surfaces.

Magnetic grippers allow a robot to voluntarily
attract metal objects within one metre of its body
or extremities, useful for the retrieval of dropped
items or errant tools in zero gravity but this use of
grippers is not selective and attracts all metal items
in the vicinity.

Item TL Cost per Base Slot
Magnetic Grippers 8 Cr10

Item TL Cost
Parasitic Link 10 Cr10000

Parasitic Link
A parasitic link allows a robot to attach itself to
another robot and take control of its body. The target
robot must have a drone interface or equivalent
to be susceptible. A parasitic link is often used by
a microbot to ‘ride’ another robot host but can be
installed and used by any robot. The link requires
physical contact to operate but is not hindered by a
robot’s armour, although a hardened brain provides
some protection. The parasitic link grants automatic
access but not control, which requires a check.

See Hacking Robots on page 109 for further
details on the process of taking control of a robot.
If successful, the controlling robot may operate its
host as if the link was an enhanced robotic drone
controller. A link can only control one robot but a
robot could theoretically use multiple links to control
multiple robots, although contact between each robot
and a parasitic link must be maintained at all times.

Self-Maintenance Enhancement
This alleviates or eliminates the need for annual
maintenance. Use of high-quality components
and self-repairing modules allows for extended
independent operation but at considerable cost.
Robots intended for extended field operations, such
as long-range explorers or surveillance robots often
include this expensive option.

Self-Maintenance Enhancement TL Maintenance Period Malfunction Check Cost per Base Slot
Basic 7 12 years 1 year Cr20000
Improved 8 24 years 2 years Cr50000

Zero-Slot Options

TRAVELLER

Item TL Cost
Stinger 7 Cr10

Item TL Cost
Atmospheric Sensor 8 100

Item TL Trait Cost
Auditory Sensor 5 — Cr10
Auditory Sensor
(broad spectrum)

8 Heightened Senses Cr200

Stinger
A stinger is a sharp needle or blade, which can be
extended from the body of a robot or its manipulators
to puncture a target as a melee attack. A stinger only
inflicts one point of damage but has AP equal to the
base armour of a robot of its Tech Level (see page 19).
A robot may install multiple stingers but each counts a
separate Zero-Slot option. Up to four stingers may be
clustered and used in a single attack.

Sensors
Sensors provide a robot with awareness of its
environment. Zero-Slot sensors are small enough to be
placed on a robot’s head, if one exists, even on microbots.

Atmospheric Sensor
An atmospheric sensor determines atmospheric
pressure and composition, screens for common
containments and determines basic environmental
data such as temperature and relative humidity.
The sensor is available at TL8 and costs Cr100.
An atmospheric sensor is included in the suite of
instruments that comprise an environment processor
and planetology sensor suite.

Auditory Sensor
A basic auditory sensor is included in the Default Suite
but can be purchased separately for Cr10 starting at
TL5. It is normally sensitive to sounds in the hearing
range of its designer’s race, which for Humaniti is 20-
20,000 hertz and is sensitive down to 0 decibels.

More advanced auditory sensors have increased
frequency and threshold capabilities and are included
in various recon sensors and environment processors.

A stand-alone broad spectrum auditory sensor is
available at TL8. This grants the Heightened Senses
trait and provides high sensitivity across a broad
range of frequencies from 1–200,000 hertz and
down to -10 decibels. The broad-spectrum sensor is
included in the suite of instruments that comprise an
environment processor.

Item TL Trait Cost
Environment
Processor

10 Heightened Senses Cr10000

Environment Processor
The environment processor correlates inputs
from highly sensitive sensors with threat analytic
algorithms to optimise responses. It grants the
Heightened Senses trait, applying DM+1 to all Recon
and Survival checks. The environment processor
includes an atmospheric sensor, broad-spectrum
audio sensor, Geiger counter, advanced light
intensifier sensor and provides Recon 0, although
this skill is limited to the processor’s sensory input
and often superseded by a full recon sensor suite
or recon skill packages on most reconnaissance-
focused robots. The environment processor does not
include an olfactory sensor or PRIS sensor but can
accept inputs from them.

Zero-Slot Options

**Geiger Counter**
A Geiger counter is a sensor that can detect alpha,
beta and gamma radiation and determines intensity
and likely source. Its functions are included in a PRIS
sensor and environment processor.

Item TL Cost
Geiger Counter 8 Cr400

**Light Intensifier Sensor**
This sensor allows clear, monochrome binocular vision
up to 18 metres in anything less than total dark. At TL9,
the advanced sensor combines light intensification with
visual-spectrum and false-colour thermal imaging in the
same sensor. The advanced sensor is included in the
environment processor.

Light Intensifier Sensor TL Trait Cost
Basic 7 — Cr500
Advanced 9 IR Vision Cr1250

Olfactory Sensor TL Trait Cost
Basic 8 — Cr1000
Improved 10 Heightened
Senses

Cr3500

Advanced 12 Heightened
Senses

Cr10000

**Olfactory Sensor**
An olfactory sensor provides the robot with the ability
to emulate a generalised sense of smell using a
suite of chemical detectors. The basic sensor suite
provides human-level acuity. The improved sensor
suite emulates the acuity of a more olfactory-attuned
race such as Vargr and grants the Heightened
Senses trait. The advanced sensor provides broad-
range trace chemical detection capability beyond
any one biological being’s capability and also grants
the Heightened Senses trait. An olfactory sensor
only operates in an atmosphere; the basic and
improved sensors operate in Atmospheres 4–9 and in
Atmospheres 2–3, D and E at DM-2. The advanced
sensor operates equally well in all atmospheres from
trace to exotic (1-F) and is included in a planetology
sensor suite.

PRIS Sensor
Either as a supplement or replacement to the visual
spectrum sensor provided in the Default Suite, this
sensor extends vision into infrared and ultraviolet
wavelengths and beyond, and provides passive light
amplification. A PRIS sensor grants the IR/UV Vision
trait and includes the functionality of a Geiger counter.

Item TL Trait Cost
PRIS Sensor 12 IR/UV Vision Cr2000

Thermal Sensor
Either as a supplement or replacement to the visual
spectrum sensor provided in the Default Suite, this
sensor extends vision into the infrared spectrum,
granting the IR Vision trait. Its functionality is included
in the TL9 version of the light intensifier sensor and the
PRIS sensor.

Item TL Trait Cost
Thermal Sensor 6 IR Vision Cr500

Visual Spectrum Sensor
The visual spectrum sensor is included in the standard
Default Suite but can be purchased separately for Cr50.

Item TL Cost
Visual Spectrum Sensor 7 Cr50

Zero-Slot Options

**Steward Droid**
The Steward Droid performs food preparation as part
of its duties and the detection of odours is also a useful
trait for its cleaning function. An advanced olfactory
sensor is included as a Zero-Slot option, costing
Cr3500 and granting the Heightened Senses trait. This
is the only added Zero-Slot option but the Steward
Droid could have up to 15 more Zero-Slot options: Size
(4) + TL (12).

**EXAMPLES**

**StarTek**
The StarTek robot is required to work in hostile
environments, including vacuum conditions. The
vacuum environment protection option includes all
hostile environment protection features and costs
Cr600 per Base Slot for a total of Cr9600. StarTek
could have up to 18 more Zero-Slot options: Size (5)

- TL (14).

STEWARD DROID
Physical Options
Item Slots Notes TL Traits Skill Cost
Olfactory sensor (improved) 0 10 Heightened Senses 3500
Autobar (enhanced) 2 Max DM+2 10 2000
Autochef (enhanced) 3 Max DM+2 11 5000
Medikit (basic) 1 Max DM+0 8 1000
Storage compartment
(refrigerated)

2 ~4 litres 200

STARTEK

Physical Options
Item Slots Notes TL Traits Skill Cost
Vacuum Environment Protection 0 +500 Rads 6 9600
Starship engineering toolkit (advanced) 4 Max DM+3 14 10000
Medikit (enhanced) 1 Max DM+2 12 5000
Radiation environment protection 1 +700 Rads 14 9600
Weapon mount: pistol 1 5 500
(spare) 1 Future use

## S LOT COST OPTIONS

Items larger than approximately one kilogram in mass
or one litre in volume require an expenditure of Slots
for installation. As a rule of thumb, a Slot represents no
more than three kilograms of mass, although bulky or
awkward items may require more Slots than their mass
would indicate.

Chassis Options
Slotted chassis options include both surface and
interior components. Unlike surface coatings, such as
reflec armour or solar coating, chassis options require
additional equipment or support structures and use
the indicated number of Slots regardless of the Size of
the robot. The cost for chassis options is multiplied by
the Base Slots of the robot’s Size. For some options,
the robot can only have one installed option of that
type but others can stack. Unless specifically stated,
a robot may have multiple types of chassis options
installed on its surface.

Active Camouflage
Going beyond the light-bending properties of visilight
camouflage, an active camouflage surface uses
quantum waveguides to bend light, making the robot
practically invisible across the entire electromagnetic
spectrum, providing DM-4 to both Recon and
Electronics (sensors) checks. Active camouflage
grants the robot effective Stealth 4 and the Invisible
trait. Only one active camouflage option can be
installed on a robot.

Item TL Slots

Cost per
Base Slot
Active Camouflage 15 1 Cr10000

Corrosive Environment Protection
This robot is modified through the use of ceramics and
corrosion-resistant materials to withstand corrosive (B)
atmospheres. The corrosive environment protection
option includes all the benefits of hostile environment
protection but does not provide vacuum environment
protection. It does provide complete protection from
temperatures ranging from -200oC to +200oC. Only
one corrosive environment protection option can be
installed on a robot.

Item TL Slots

Cost per
Base Slot
Corrosive Environment
Protection

9 1 Cr600

Insidious Environment Protection
This robot is modified to temporarily withstand the
most destructive (insidious) atmospheres by use of
advanced seals and corrosion-resistant materials.
This customisation does not provide permanent
protection but does protect the robot against
insidious environments for a number of days equal
to the TL of the robot. After this time has elapsed,
the robot loses its protection until it is completely
refurbished, a process taking 1D days in a fully
equipped workshop and an expenditure of 5% of
the total cost of the robot. Insidious environment
protection includes all the benefits of hostile
environment protection but does not provide vacuum
or corrosive environment protection. It provides
complete protection from temperatures ranging from
-270oC to +800oC and from pressures of up to 10 x
TL atmospheres. It may also be used for enhanced
submersible environment protection (see page 42).
Only one insidious environment protection option can
be installed on a robot.

Item TL Slots

Cost per
Base Slot
Insidious Environment
Protection

11 1 Cr3000

TRAVELLER

Radiation Environment Protection
A robot with this environment protection is hardened
to survive a high-radiation environment through
shielding and radiation-resistant components. The
protection afforded by this feature stacks with the 500
rads provided by hostile environment protection and
provides an additional 50 x TL rads protection starting
at TL7. Radiation environment protection can be
applied multiple times to a robot for additional safety.

Item TL Slots Cost per Base Slot
Radiation Environment
Protection

7 1 Cr600

Self-Repairing Chassis
A self-repairing chassis provides the robot’s outer shell
with a nano material sealant that repairs minor damage
and breaches of the robot’s chassis. This modification
repairs scratches, small dents and punctures, such as
those caused by bullets or hand-held laser weapons. It
does not repair major damage or missing components
and only restores one Hit per penetrating attack,
requiring one minute to repair damage from each
penetration. Only one self-repairing chassis option can
be installed on a robot.

Item TL Slots Cost per Base Slot
Self-Repairing
Chassis

11 5% Cr1000

Submersible Environment Protection
A submersible environment is different from
atmospheric or vacuum environments since pressure
increases quickly, essentially adding one standard
atmosphere for every 10 metres depth in water. Without
submersible protection a robot can operate at up to 10
metres depth without adverse impact, although robots
with the light chassis modification may experience
damage to exposed components at the Referee’s
discretion. Submersible environment protection does
not include the hostile environment option but any
robot equipped with the hostile environment protection
option or other options that include it should have little
difficulty surviving prolonged immersion in 10 metres of
non-corrosive fluids.

Robots with submersible environment protection have
a Safe Depth. Beyond Safe Depth, a robot must avoid
a critical hit on a 2D check of 4+ once per minute. For
every multiple of the Safe Depth, the robot suffers a
DM-2 to this check.

A robot can use any locomotion type except aeroplane
and VTOL while submersed, however all but aquatic
locomotion suffer Agility -2 and a reduction in
movement speed to half, rounded down. Wheeled,
tracked and walker modes require movement
across the bottom of a body of water unless aquatic
locomotion is installed.

Submersible Environment Protection TL Slots Safe Depth Cost per Base Slot
Basic 4 5% 50m Cr200
Improved 6 2% 200m Cr400
Enhanced 9 2% 600m Cr800
Advanced 12 2% 2,000m Cr1000
Superior 15 2% 4,000m Cr2000

A robot may apply additional submersible environment protection to increase its Safe Depth. Each application of
Safe Depth increases the value by the indicated metres and requires an additional indicated percentage of Slots.
Once the total percentage of Slots allocated to submersible environment protection is calculated, this value is
rounded up to the nearest Slot.
Slot Cost Options

Cleaning Options
Robots are often found in domestic and industrial
cleaning roles. While some humanoid robots use the
same tools as a biological cleaner or custodian, others
have built-in equipment, including vacuums, mops,
dusters, buffers and sprayers. Consumables, including
caustic cleaning agents, are often loaded in separate
storage compartments. A robot equipped with cleaning
equipment can typically operate for 20 out of 24 hours,
spending the remaining time on replenishment, waste
disposal and travel between locations. A robot with
multiple or different types of cleaning options may only
operate one set of cleaning equipment concurrently.
Areas to be cleaned are usually expressed in square
metres, with a typical starship stateroom equal to
approximately 18 square metres.

**Domestic Cleaning Equipment**
Domestic cleaning equipment is suitable for use in
homes, passenger, retail or dining areas and other
domestic spaces. The equipment provided to the robot
determines how quickly and efficiently a robot can
clean a room.

Domestic Cleaning Equipment TL Slots Square metres per hour Cost
Small 5 1 10 Cr100
Medium 5 4 50 Cr1000
Large 5 8 120 Cr5000

**Industrial Cleaning Equipment**
Industrial cleaning equipment is suitable for use in
areas not considered domestic, such as those with
machinery, food preparation equipment, warehouses
and hangars. Industrial cleaning equipment includes a
larger variety of tools and chemicals.

Industrial Cleaning Equipment TL Slots Square metres per hour Cost
Small 5 2 10 Cr500
Medium 5 8 50 Cr5000
Large 5 16 120 Cr20000

Slot Cost Options

TRAVELLER

Communications Options
While most robot communication options are
miniaturised and require no Slots, specialised or lower
tech options are large enough to consume considerable
space within a robot.

High Fidelity Sound System
A voder or the audio speakers associated with video
systems can prove adequate sound output but for a
rich audio experience, specialised speakers become
necessary. High Tech Levels do not necessarily
produce better quality sound but allow for greater
miniaturisation and sonic focus. At TL11 an enhanced
high fidelity sound system can focus sound well
enough to avoid ‘bleed-off’ of loud performances that
might otherwise annoy neighbours or passers-by. A
sound system can be used to play pre-recorded or
transmitted music or other audio output. At TL8 and
above, a robot can use the sound system to output its
own ‘live’ performances using its Art (performer) or Art
(instrument) skill.

High Fidelity Sound System TL Slots Cost
Basic 6 4 Cr1500
Improved 8 3 Cr2500
Enhanced 11 3 Cr4000
Advanced 12 2 Cr5000

Robotic Drone Controller
Robots have an advantage over biological controllers
in that they can use multi-processors to control
separate robots doing separate tasks in a manner
unmatched by most ‘natural’ minds.

For successful control, both controller and drone
must have transceivers installed, with the range
of controller’s transceiver being the limiting factor
in control distance. In addition to a robotic drone
controller, the controlling robot must have an
Electronics (remote ops) skill package installed. More
advanced robotic drone controllers can command
multiple drones but for each drone beyond the first
controlled, the effective Electronic (remote ops)
skill of the robot decreases by -1. For instance, an
advanced drone controller installed in a robot with an
Electronics (remote ops) skill package and skill DMs
of 3 could control eight independent drones but at a
DM-4 for all of them. For effective, but more limited,
control of a large number of remote drones, a swarm
controller (see following page) would probably be
more effective. The robotic drone controller includes
a communications multiplexor with enough channels
to support the maximum number of drones and allow
similar concurrent wireless data links to program
drones or other robots.

Maximum skill indicates the highest level of
Electronics (remote ops) a robot can use through the
robotic drone controller. This is reduced by the DM
for controlling multiple drones.

If desired, a robot could install a less machine-
optimised ‘biologically-controlled’ drone controller.
This lacks the multiplexor and limits control to one
drone but does not limit the Electronic (remote ops)
skill of the operator.

Robotic Drone Controller TL Slots Maximum Drones Maximum Skill Cost
Basic 7 2 1 0 Cr2000
Improved 9 1 2 1 Cr10000
Enhanced 10 1 4 2 Cr20000
Advanced 11 1 8 3 Cr50000

Slot Cost Options

**Satellite Uplink**
A satellite uplink allows a communication system to
maintain a steady link to a ship or satellite in orbit.
It requires a transceiver capable of at least 500
kilometres but allows the transceiver to reach a ship or
satellite as far as 50,000 kilometres distant. For one-on-
one communications, a ship can initiate and maintain
communications with a single robot that is not equipped
with an uplink but the uplink enables multiple robots to
remain in constant communication with a single ship. It
also allows the robot to initiate the communication with
a ship of known location or orbit.

A satellite uplink amplifies a robot’s transceiver up to 100
times when communicating with a ship-sized receiving
array. Communications with large communications
arrays on space stations or ground installations can be
multiplied a million times or more, depending on the
diameter of the receiving antenna, allowing a robot to
conduct interplanetary communications.

Item TL Slots Cost
Satellite Uplink 6 2 Cr1000

**Swarm Controller**
A swarm controller allows a robot to control a large
number of drones, microbots or nanorobots that
have data links, receivers and control components.
Swarms cannot be directly controlled by biological
beings; in the absence of a robot, a computer or
device running Swarm Control software is required.

Swarm Controller TL Slots Maximum Complexity Maximum Tasks Maximum Skill Cost
Basic 8 3 Average (8+) 1 0 Cr10000
Improved 10 2 Difficult (10+) 2 1 Cr20000
Enhanced 12 1 Very Difficult (12+) 3 2 Cr50000
Advanced 14 1 Formidable (14+) 4 3 Cr100000

A swarm controller can manage a theoretically
unlimited number of machines, provided they are
within wireless data link range and performing related
tasks. For successful control, both controller and
swarm must have wireless data links, limiting control
distance to 50 metres and the controlling robot must
have an Electronics (remote ops) skill package
installed. More advanced swarm controllers can
command a swarm to complete increasingly complex
tasks, although maximum complexity of the tasks
carried out by a swarm is also limited by the maximum
skill complexity capability of the robot controlling the
swarm. For instance, only a Self-aware or Conscious
robot brain could attempt to command a swarm to
perform a Formidable (14+) task.

More sophisticated swarm controllers allow the
controlling robot to simultaneously command
separate elements of a swarm to perform different
tasks, although this decreases the maximum task
complexity of the entire swarm by one level and as
with a robotic drone controller, imposes DM-1 on all
checks for every additional task. A single swarm task
is any physical task that could be completed by one
check by a single entity.

A Traveller can attempt to control a swarm using a
swarm controller console or computer running Swarm
Control software as detailed on page 122 and 123.

Slot Cost Options

TRAVELLER

Tightbeam Communicator
A tightbeam communicator uses lasers or masers
to provide point-to-point communication between
two such devices provided they are in line of sight. A
tightbeam communicator has a 5,000-kilometre range
and transmissions are nearly impossible to intercept.

When combined with a satellite uplink, range increases
to 500,000 kilometre and communications are easy to
maintain between moving targets.

Item TL Slots Cost
Tightbeam Communicator 8 1 Cr2000

Transceivers
At lower Tech Levels or at higher power, a radio
transceiver is bulky enough to require Slots. Other than
size, these transceiver options are identical to their
Zero-Slot counterparts.

Transceiver Range (km) TL Slots Cost
Basic 50 7 1 Cr1000
Basic 500 7 1 Cr2000
Basic 5,000 7 2 Cr10000
Basic 50,000 8 4 Cr20000
Improved 50,000 10 2 Cr10000
Enhanced 50,000 12 1 Cr5000
Advanced 50,000 15 1 Cr2500
Basic 500,000 9 8 Cr50000
Improved 500,000 11 4 Cr25000
Enhanced 500,000 13 2 Cr10000
Advanced 500,000 16 1 Cr5000

Medical Options
Robots are often used in medical situations acting
as everything from combat medics to surgeons to
low berths, the latter of which can be considered as
immobile robots with limited capabilities.

Medical Chamber
A medical chamber is an advanced enclosed stretcher
capable of supporting or transporting a patient in
need of medical attention. It can form the basis of
an ambulance robot or custom autodoc through the
addition of manipulators, medikits and a brain with the
proper skill packages.

The medical chamber includes no manipulators but a
robot designed around it should include at least one
manipulator of Size 3 or greater to allow handling of
the patient and medical equipment within the chamber.
The chamber has a sealed environment for the patient,
which will provide basic protection to low pressure
conditions but does not include hostile environment
options; these must be added to the chassis of the
robot into which the chamber is installed.

A medical chamber adds +1 to the maximum skill level
supported by a medikit option but does not directly add
a DM to Medic checks. It does not include a medikit but
provides access panels to allow operation of medikits,
scientific instruments or manipulators inside the sealed
environment of the chamber.

Keeping in mind that a robot’s Base Slots encompass
only half of its physical volume, a medical chamber
sized for adult human occupants requires at least 32
Slots. Medical chambers designed for other races
might require fewer or more Slots.

The Imperial Starport Authority standard for a low
berth specifies a 50-Slot size medical chamber
in dimensions that accommodate all but the most
morbidly obese human – technically a human up to
2.25 metres tall and massing up to 150 kilograms, with
allowance for overcapacity. This standard includes
a specification for a standard spacecraft mounting,
which corresponds to a Size 7 robot, 2 vehicle Spaces
or 0.5 displacement tons. This standard applies to
common low berths and autodocs.

Item TL Cost per Chamber Slot
Medical Chamber 8 Cr200

Slot Cost Options

**Medical Chamber Options**
Medical chambers can include a number of options
that allow conversion into cryoberths, low berths
or autodocs.

Technologies required for cryoberths and low
berth hibernation systems are similar. A cryoberth
is designed to quickly (within one combat round)
freeze an individual, usually in response to severe
medical trauma. This process carries inherent
risk and the individual must perform a low berth
survival check both on entry and exit from cryoberth-
induced hibernation. Medical skills applied to aid
these cryoberth survival checks are considered
rushed, lowering checks by DM-2 and often forgone
as counterproductive if no qualified individual is
available to assist.

Low-berth hibernation is a more gradual process,
usually medically supervised, which only requires a
survival check during the retrieval process. Improved
versions of both technologies are available at TL12,
providing DM+1 to both freezing and revival checks.

Cryoberths, low berths and autodocs are designed
with the physiology of a specific species in mind.
While a unit designed for humans works equally well
whether the patient is Solomani, Vilani, Zhodani,
even Geonee or Suerrat, aliens suffer a negative
DM when attempting to use a system designed
for Humaniti. For a Vargr or other [[Terra|Terran]]-evolved
being, this is DM-1. For Aslan, K’kree, Hiver or
other species with similar biochemistry, this is DM-

2. For truly alien races with divergent or unknown

biochemistry, the DM is at least -4 and there is a
chance the mechanism will be unable to do anything
other than kill and preserve the body. The converse
applies for humans who use alien-designed systems.
Each species-specific add-on option can provide
safe hibernation and treatment for one additional
specified alien species without incurring a penalty,
assuming a broadly similar biochemistry and reaction
to environmental factors.

At TL13, a nanorobot applicator allows the medical
chamber to program and apply nanorobots to a patient
and includes a swarm controller specialised for this
use. The applicator can store up to two litres of medical
nanorobots and the larger nanorobot generator also
includes a one-Slot enhanced fabricator to create
medical nanorobots from raw materials in addition to
functioning as a nanorobot applicator.

At TL14, a medical chamber is capable of reanimation,
provided no more than 2D minutes have passed
since the patient’s death and the body is generally
intact. This period can be doubled by extremely cold
conditions, extended up to 1D days by placing the
corpse in a low berth or indefinitely if preserved using
the cryoberth option – although any cryoberth or low
berth survival negative Effect contributes a negative
DM to the Difficult (10+) Medic (1D x10 minutes, EDU)
task of successful reanimation.

Medical Chamber Option TL Slots Cost
Cryoberth (basic) 10 8 Cr20000
Cryoberth (improved) 12 8 Cr20000
Low berth (basic) 10 8 Cr20000
Low berth (improved) 12 8 Cr20000
Nanorobot applicator 13 4 Cr100000
Nanorobot generator 13 8 Cr200000
Reanimation 14 8 Cr900000
Species-specific add-on 10 4 Cr10000

Slot Cost Options

TRAVELLER

Medikit
A medikit provides basic diagnostic and treatment tools
for medical emergencies and long-term treatment of a
disease or other medical condition. The complexity of
the medikit is the limiting factor of a robot’s Medic skill
using the robot’s internal medikit capability, although
it does not limit the robot’s skill when it has access to
specialised medical equipment or the suite of tools
available in a medical chamber.

Medikit TL Slots Max Skill Cost
Basic 8 1 0 Cr1000
Improved 10 1 1 Cr1500
Enhanced 12 1 2 Cr5000
Advanced 14 1 3 Cr10000

The medikit requires one Slot and occasional
replenishment of supplies at a cost of Cr500. With
light usage, consumables may last five years; in a
field hospital or emergency room they may need
daily replenishment.

Miscellaneous Options
Various options provide robots with integral
equipment to perform certain tasks. Where specified
by the Maximum Skill column, the sophistication of
an option is the limiting factor of a robot’s skill using
the robot’s internal capability, although it does not
limit the robot’s skill when it has access to external
specialised tools for the task.

Agricultural Equipment
Robots are often used as agricultural workers in
roles from gardeners to harvesters to hydroponic
specialists. Much like cleaning equipment,
agricultural equipment performance is measured
in square metres worked per hour, with a standard
spacecraft four-ton area corresponding to 18 square
metres. An agricultural robot can operate effectively
for up to 20 of 24 hours, with time out for movement,
replenishment and other inefficiencies. Very large
agricultural robots may be installed with multiple
agricultural equipment options in order to cover a
greater area.

Agricultural Equipment TL Slots Square metres per hour Cost
Small 5 1 20 Cr100
Medium 5 4 100 Cr1000
Large 5 16 500 Cr10000

Slot Cost Options

**Autobar**
An autobar option includes a selection of beverages
and a mixing function allowing for voice-activated
or robot-initiated disbursement of drinks. The
complexity of the autobar is the limiting factor of a
robot’s Steward or Profession (bartender) skill when
using the robot’s internal autobar capability, although
it does not limit the robot’s skill when it has access to
an external wet bar or autobar device. The autobar
has a limited internal capacity of two litres, requiring
access to a storage compartment (preferably
refrigerated) to provide additional drinks.

The autobar requires replenishment of materials at a
cost equal to half its initial cost. With light to normal
usage in a household or small spacecraft setting, this
replenishment is monthly but with higher frequency
use, such as in a hotel bar, replenishment may be
needed daily.

Autobar TL Slots Maximum Skill Cost
Basic 8 2 0 Cr500
Improved 9 2 1 Cr1000
Enhanced 10 2 2 Cr2000
Advanced 11 2 3 Cr5000

**Autochef**
An autochef is a food preparation system that prepares
properly cooked meals when provided with ingredients.
The autochef includes equipment for all steps of food
preparation from cutting and peeling to cooking and
presentation. The complexity of the autochef is the
limiting factor of a robot’s Steward or Profession (chef)
skill using the robot’s internal autochef capability,
although it does not limit the robot’s skill when it
has access to an external galley or kitchen. The
autochef has only limited storage capacity for holding
or reheating two meals but can be connected to an
internal storage compartment.

The autochef requires three Slots but does not include
ingredients, although it is normally stocked with an
initial supply of spices and condiments.

Autochef TL Slots Maximum Skill Cost
Basic 9 3 0 Cr500
Improved 10 3 1 Cr2000
Enhanced 11 3 2 Cr5000
Advanced 12 3 3 Cr10000

Autopilot
Robots capable of movement at vehicle speeds through
use of the vehicle speed movement modification benefit
from either an autopilot, a Basic (locomotion) brain
or an appropriate vehicle operating skill package to
perform complicated manoeuvres. The vehicle speed
movement modification itself provides a basic autopilot
of skill 0. Additional skill levels can be accomplished
using a brain skill package but the robot designer may
choose to conserve limited and potentially expensive
Bandwidth by installing a separate autopilot processor
to control vehicle speed performance.

To perform beyond the basic guidance system included
for the vehicle speed movement modification, an
autopilot option requires one Slot. Autopilot and skill
level packages do not stack; the higher of autopilot or
vehicle operating skill applies.

Autopilot TL Slots Skill Level Cost
Improved 7 1 1 Cr7500
Enhanced 9 1 2 Cr10000
Advanced 11 1 3 Cr15000

Slot Cost Options

TRAVELLER

Bioreaction Chamber TL Complexity Cost per Chamber Slot
Basic 6 Microbes Cr1000
Improved 8 Tissues Cr2000
Enhanced 10 Complex organisms, x12 growth Cr5000
Advanced 13 Complex organisms, x50 Accelerated growth Cr20000

Construction Equipment
Robots are often used as construction workers
building everything from basic infrastructure to
complex machinery. Construction equipment
performance is measured in cubic metres worked
per hour, with a standard spacecraft one-ton volume
corresponding to 14 cubic metres. A construction
robot can operate effectively for up to 20 of 24 hours,
with time out for movement, replenishment and other
inefficiencies. Very large construction robots may be
installed with multiple construction equipment options
in order to cover a larger volume.

The listed hourly volumes assume simple construction,
such as roads or residential buildings, with roads and
other surfaces generally considered one metre deep,
allowing a simple equivalence of cubic and square
metres. Complex construction, such as that required for
vehicles and machinery, proceeds more slowly; at best
such construction is at 50% the nominal rate, at worst
10%. Construction equipment may also be used to
clear rubble or prepare an area for development.

Construction Equipment TL Slots Cubic metres per hour Cost
Small 5 2 0.2 Cr500
Medium 5 8 1 Cr5000
Large 5 32 5 Cr50000

Bioreaction Chamber
A bioreaction chamber, sometimes called a ‘bioreactor’
or ‘vat’, supports a biologically active environment. It
can be used to grow cultures or organisms or support
a growing biological being, including a human foetus or
developing clone. Bioreaction chambers are available in
varying sizes. An 8-Slot unit supports a human foetus to
full term and a 32-Slot unit supports a full human clone
to average adult size. A bioreaction chamber is a sealed
environment. It does not provide hostile environment or
vacuum protection on its own but can be protected by
a robot’s chassis if it includes those options. Costs per
Chamber Slot refer to the cost related to the size of the
bioreaction chamber, not the robot.

A TL6 basic bioreaction chamber can support the growth
of microbes with a simple nutrient feed mechanism. This
provides the basis for growing medicinal organisms,
feedstock and biomass fuel sources.

A TL8 improved chamber provides for the growth of
tissues. It can grow skin, muscles or artificial meat fit
for consumption.

The TL10 enhanced chamber can grow a complete
organism, such as carrying a mammal from conception
to birth as an artificial womb. The enhanced chamber can
grow a fertilised embryo or cloned organism to full term in
a normal gestation period or at up to 12 times acceleration
with access to little more than power and stored nutrients.

The TL13 advanced chamber can act as a growth
accelerator, increasing the growth rate of tissues or
complete organisms by a factor of up to 50, greatly
increasing the maturation rate of the organism, though
perhaps at the expense of long-term viability.

All bioreaction chambers require organic feedstock of at
least the equivalent mass of their output. It is possible
to insert an organism’s genetic source material and
chaff from a wheat harvest into an advanced bioreaction
chamber and see a fully grown adult clone emerge four
to five months later.

Slot Cost Options

**Fabrication Chamber**
A fabrication chamber allows a robot to build
objects from component ingredients. It is often
referred to as a ‘fabricator’ or ‘fab’. A TL8 basic
fabricator is a straightforward 3D printer, able to lay
down layers of material to form simple mechanical
objects. Increasingly complex fabricators can create
objects quicker and of increasing complexity, up
to and including additional fabrication chambers
themselves. A fabrication chamber is a sealed
environment. It does not provide hostile environment
or vacuum protection on its own but can be protected
by a robot’s chassis if it includes those options. A
fabrication chamber can create a device equal in
size to half its Slot size, or approximately 1.5 litres in
volume per Slot. Cost is calculated based on the Slot
size of the chamber, not the robot.

Fabricators require materials equal to the mass of
the object created. These may be everything from
simple powders to rare earths or other required
materials, depending on the final product. In general,
these materials cost 50% of the cost of a similar
purchased product, although those composed of
purely common materials may have as low as a
10% material cost and those requiring rare elements
may cost more to fabricate in small batches than
to purchase from a manufacturer able to acquire
materials in bulk. Optionally, the Referee can impose
a 1D x 10% materials cost for most products and a
2D x 10% materials cost for computers, robots and
complicated electronic machinery.

The TL10 improved fabrication chamber can create
simple electronic devices. It can create any part
of a robot’s body but is only capable of creating a
Primitive, Basic or Hunter/Killer brain. When creating
complete robot bodies, four times the Slot capacity
of the robot is required. For instance, a 64-Slot
chamber is required to create a 32-Slot object, which
translates into a Size 5 robot with 16 Slots available
for customisation.

A TL13 enhanced fabrication chamber can create
additional fabrication chambers, even complete
robots with Advanced brains, although it is limited
to brains and brain options one TL lower than the
fabrication chamber itself. An enhanced chamber
cannot create Self-aware or Conscious robot
brains. An enhanced fabrication chamber includes
the technology to act as an advanced bioreaction
chamber (see previous page). It can print a full
organ, limb or similar replacement part, possibly

infusing it with cybernetic components, but is unable
to directly print a complete living and thinking
organism, although it can infuse a biological creation
with an artificial nervous system to be programmed
as a robot or artificial being.

A TL17 advanced fabrication chamber can print a
complete living biological being or cyborg. It can
create Very Advanced, Self-aware or Conscious
complexity robot brains. A biological brain created
in an advanced fabrication chamber is a blank
slate. The printing process is not sophisticated
enough to duplicate memory patterns but it can
embed wafer jacks capable of acting as accelerating
learning enhancers. Objects created in an advanced
fabrication chamber cannot be of greater Tech Level
than the chamber itself.

As a general rule, fabrication chambers can fully
manufacture any non-animate item available two TLs
or more prior to their own TL. For instance, a Basic
fabricator can manufacture TL6 items, including auto
pistols and vacuum-tube radios, while an Improved
fabrication chamber can manufacture a transistor
radio, portable computer or other TL8 electronic
device. This progression holds until the debut of the
Advanced fabrication chamber, a device capable of
turning a society into a post-scarcity civilisation, with
any item available on demand, assuming access to
the proper raw materials.

Note that design templates for fabricated items are
often patented and require licenses to produce,
although pirated and open-source versions of many
common and some highly questionable items are
available. Most commercially sourced fabrication
chambers are specifically blocked from creating
weapons, currency, copywritten materials or
controlled substances, although specific restrictions
vary by government and manufacturer.

The Time Requirement listed for each fabrication
chamber is a minimum to complete fabrication of
an object. Brains, biological or robotic, and their
‘neurological’ connections quadruple construction
time and complex, highly irregularly shaped objects
and objects that require high melting temperatures
and cooling double fabrication time, meaning a highly
complex robot might need a combined eight times
the listed time requirement.

Slot Cost Options

TRAVELLER

Fabrication Chamber TL Complexity Time Requirement Cost per Chamber Slot
Basic 8 Mechanical 2 hours Cr2000
Improved 10 Simple electronics
Primitive, Basic or Hunter/Killer
robot brains

2 hours Cr10000

Enhanced 13 Complex electronics, simple
biomechanical
Advanced robot brain

1 hour Cr50000

Advanced 17 Complex biomechanical
Any robot brain

1 hour Cr200000

Forklift
A forklift option allows a robot to carry heavy loads
without the intricacies of a manipulator. A forklift does
not allow for delicate handling but is useful for moving
boxes or pallets of equipment. The maximum load of
a forklift is more a case of balance than gravity and
is independent of local conditions, unless the gravity
exceeds 1.5G, in which case the forklift maximum load
should be adjusted to reflect actual gravity. Multiple
forklift-equipped robots can work together to lift a load.
Maximum load is expressed in spacecraft displacement
tons; multiply by four for vehicle Spaces. Actual mass
computations are normally not necessary, as volume
can also be a limiting factor but a five-ton starship
shipping container might mass up to 32 metric tons.

Forklift TL Slots Maximum Load Cost
Small 5 8 0.5 tons Cr3000
Medium 5 12 1 tons Cr5000
Large 5 60 5 tons Cr20000

Holographic Projector
A holographic project displays a three-dimensional
image or motion picture in front of the robot. The
hologram is of adequate fidelity, increasing in quality
as Tech Levels increase beyond 10. The holographic
projector includes a sound system, although the robot
may project sound via its voder speakers or high-
fidelity sound system.

Item TL Slots Cost
Holographic Projector 10 1 Cr1000

Mining Equipment
Robots are often used as mine workers and excavators.
Mining equipment performance is measured in cubic
metres worked per hour, with a standard spacecraft
displacement ton volume corresponding to 14 cubic
metres. A mining robot can operate effectively for
up to 20 of 24 hours, with time out for movement,
replenishment and other inefficiencies. Very large
mining robots may be installed with multiple mining
equipment options to cover a larger volume. The listed
volumes assume moderately hard rock. Loose soil may
improve mining performance, while metallic asteroids
or hard rock may degrade performance considerably.
Mining equipment can also be used to clear rubble or
prepare an area for construction.

When used for asteroid mining, performance must
consider the vagaries of microgravity and collection
of debris. A large mining equipment option is the
equivalent of a mining drone, gathering 1D tons of
common ore per day.

Mining
Equipment TL Slots

Cubic metres
per hour Cost
Small 5 5 0.5 Cr2000
Medium 5 15 2 Cr5000
Large 5 45 8 Cr15000

Slot Cost Options

**Navigation System**
A robot may have a navigation system complete with
compass, inertial locator, navigation system receivers
and integration between these inputs and its standard
sensors to allow it to emulate the Navigation skill in
hardware rather than expending a skill package and
brain Bandwidth. A robot’s navigation system can
update itself via local data sources and library data
if available. The skill level imparted by this option is
based on the system’s information and not modified by
a robot’s INT modifier.

Navigation
System TL Slots

Navigation
Skill Cost
Basic 8 2 1 Cr2000
Improved 10 2 2 Cr10000
Enhanced 12 1 3 Cr25000
Advanced 14 1 4 Cr50000

Self-Destruct
System TL Slots Effect to Robot Effect to Others Cost per Base Slot
Defensive 8 5% Hits ÷3 D
3 x 1D Severity Brain Critical Hits

Robot damage dice ÷2 –
Robot’s armour, Blast 3

Cr500

Offensive 6 10% Hits ÷3 D
3 x 1D Severity Brain Critical Hits

Hits x 2/3 D,
Blast = robot Size

Cr1000

TDX 12 10% Hits ÷3 D
3 x 1D Severity Brain Critical Hits

Hits x D, Blast 15 Cr5000

Nuclear 12 4 Vaporisation 10DD, Blast 1,000,
Radiation

Cr500000 (fixed)

Self-Destruct System
A self-destruct system can have two purposes:
one is to ensure the robot is destroyed, preventing
technology or data from falling into the wrong hands;
the other achieves that goal incidentally in an
attempt to cause as much damage to the local area
as possible. These two systems are referred to as
defensive and offensive, respectively.

A defensive self-destruct is composed of explosives
strategically placed in a robot’s brain, power system
and other high-value options. It does damage to the
robot equal to one third of the robot’s Hits, rounded
up, in dice – for example 7D for a 20 Hit robot – and
also three critical hits of Severity 1D to the robot’s
brain. All critical hits and possible cascading effects
apply and armour does not prevent any damage. This
explosion is ‘slow’ – more of a fast burn – and damage
external to the robot is limited. Anyone within three
metres of the robot will take damage equal to one half
the robot’s damage dice, rounded down – for example,
3D in the case of the 20-Hit robot – but factor in the
robot’s own armour when determining damage. For
example, if the robot has armour +6, the damage to
bystanders is reduced by six.

An offensive self-destruct option does an equal
amount of damage to the robot but the explosion is
‘fast’ and the robot’s armour does not protect anyone.
External damage is two-thirds of the robot’s Hits in
damage dice rounded down – or 13D for a 20 Hit
robot – with a Blast trait equal to the robot’s Size.
A TDX offensive option provides a gravity-focused
explosion of damage dice equal to the robot’s Hits

- in the ongoing example, 20D – with Blast 15. The

nuclear option is a fixed-size explosive illegal in any
jurisdiction and usually detectable by Geiger counters;
it will do 10DD damage with Blast 1,000, vaporise the
robot (and much else) and irradiate the environment.
Slot Cost Options

TRAVELLER

OFFENSIVE SELF-DESTRUCT RESTRICTIONS
In Charted Space, the Third Imperium takes a
very dim view towards robots with offensive self-
destruct systems. The Shudusham Concords
were written explicitly to ban such devices and
possession of a robot with an offensive self-
destruct system is prohibited by Imperial Law.
While certain permits allow such devices, they
are difficult to obtain and often scrutinised by
Imperial officials. All Starport Authority facilities
have screeners tuned to look for hidden explosive
devices and despite built-in methods to obscure
self-destruct explosives, defeating the typically
TL12+ scanners situated at every point of entry
or egress from a starport requires the robot to
make a Very Difficult (12+) Stealth check.

Self-Maintenance Enhancement
A self-maintenance enhancement alleviates or
eliminates the need for annual maintenance. Use
of high-quality components, self-repairing modules
and nanomachines allows for extended independent
operation but at considerable cost. Robots intended for
extended field operations, such as long-range explorers
or surveillance robots, often include these options. The
enhanced version uses active nanomachines to stretch
the robot’s ‘annual maintenance’ requirement to every
60 years with ‘monthly’ malfunction checks every five
years thereafter. The advanced version includes a
miniaturised fabricator to repair both the components
and the repair nanomachines themselves to completely
eliminate maintenance requirements.

Self-Maintenance Enhancement TL Slots Maintenance Period Malfunction Check

Cost per
Base Slot
Enhanced 13 10% 60 years 5 year Cr200000
Advanced 15 10% Indefinite indefinite Cr500000

In any case, the explosives contained within
such a robot are banned at Law Level 1.
Unauthorised possession of nuclear explosives
is liable to result in life imprisonment or worse
and even the use of conventional explosives
most often results in a long stay on an Imperial
prison world for the robot’s owner and a short
stay in a smelter for the robot.

Even a defensive self-destruct mechanism is
viewed with suspicion and requires enough
authorisation to make civilian ownership of a
robot so equipped problematic.

Stealth
Stealth provides the capability to hide from electronic
detectors, both active and passive. This is achieved
primarily through passive means, mainly through the
use of advanced materials and designs that limit the
robot’s available internal volume. In addition to the
inherent DM indicated, stealth applies a negative
DM to Electronics (sensors) checks equal to the
difference between the robot’s TL and that of the
device it is trying to evade. Reflec armour coating
renders stealth ineffective except when scanning
for concealed internal components. Stealth requires
sacrificing a fixed number of Slots but cost is based
on the Base Slots of the robot.

Stealth
Item TL Slots Trait Cost per Base Slot
Stealth (basic) 7 1 Stealth (+1) Cr300
Stealth (improved) 9 2 Stealth (+2) Cr600
Stealth (enhanced) 11 3 Stealth (+3) Cr900
Stealth (advanced) 13 3 Stealth (+4) Cr1200

Slot Cost Options

**Storage Compartment**
A storage compartment is an internal space within the
robot sealed by a door or panel, usually accessible to
its manipulators. Each Slot dedicated to storage can
hold approximately two kilograms or two litres and
costs Cr50. The storage compartment is protected by
the robot’s armour and environmental enhancements
but does not include an airlock.

Hazardous material storage requires special materials
and other safeguards and costs Cr500 per Slot. In
general, the material to be stored should be specified
upon installation of a hazardous material storage
compartment. If an airlock is desired, it should
be considered as a separate hazardous material
storage compartment of a Slot size large enough to
accommodate the item that requires it.

**Item TL**

Cost per
allocated Slot
Storage Compartment 6 Cr50
Refrigerated Storage
Compartment

6 Cr100

Hazardous Material
Storage Compartment

6 Cr500

**Video Projector**
A video projector can display still or moving 2D
images on an external flat surface. The display
includes a sound system of moderate quality, although
the robot can also produce sound through its voder or
other sound system.

Item TL Slots Cost
Video Projector 7 1 500

Power Options
A robot is assumed to have an internal power
system, whether batteries, fuel cells or even internal
combustion engines. These systems provide the
robot’s basic endurance, perhaps supplemented by
additional power cells.

However, non-standard conditions may allow for,
or require, alternate power sources. If confined to
operating in a technological setting, a robot could
have no internal power system, making it reliant on
external power. Conversely, a robot intended for use
far beyond civilisation – for example, an exploratory
probe – might use solar panels or a radioisotope
thermoelectric generator (RTG) for supplementary or
primary power, allowing a low level of endurance for
years or decades.

Robots relying only on RTG or solar power sources
have their movement rate and STR halved (round
down), suffer Agility -2 and may not install the vehicle
speed movement modification. Such robots never
have an Athletics (endurance) skill. Most robots avoid
this limitation by installing both a conventional power
system to allow normal operations, at least for an
intermittent period of time, and rely on the RTG or
solar power unit for recharging. If a robot installs two
RTG or solar power sources, in any combination, it
is not subject to these performance degradations,
provided both power sources are operating at full
capability; in such cases the robot could support
vehicle speed movement modifications.

External Power
Robots without the external power option require a
direct connection to a power source, limiting mobility
while recharging and have finite endurance. A robot
with this option draws power from an external source
such as wires or beamed microwaves. This provides
the robot with unlimited endurance while within range
of the power source and ensures it is charged at full
endurance when it moves outside of range.

Item TL Slots Cost per Base Slot
External Power 9 5% Cr100

Slot Cost Options

TRAVELLER

Item TL Slots Cost
No Internal Power 6 +10% —

No Internal Power
If a robot has no internal conventional power system,
it gains an extra 10% Slots (round up) available for
allocation to physical options. These Slots become
available at no cost but do not reduce the cost of
the robot, as interfaces to power sources need to
be installed to prevent the robot from becoming
an inert piece of metal and plastic. A robot without
a conventional power system may still use power
packs to achieve endurance similar to its base
endurance. Without an internal power system or
power packs, a robot immediately shuts down when
power is not available.

RTG Long Duration
A radioisotope thermoelectric generator (RTG) relies
on the decay of radioactive particles to generate
power. An RTG is a very inefficient and expensive
option but might be the only option available for a
robot designed to operate in the depths of space
or hostile environments with limited exposure to
sunlight. An RTG can recharge a power pack or
internal power system while stationary or performing
minimal activity but requires three times a power
pack’s endurance to fully recharge it.

An RTG power source’s endurance is measured
in years. Endurance represents the half-life of the
radioactive elements in the RTG unit, the amount of
time since unit installation a robot will function. Storage
in a powered-off state does not extend RTG endurance.

Once the RTG endurance period expires, the robot will
continue to function but at lower power, once again
halving the robot’s movement and STR and suffering
an additional Agility -2. The robot then requires twice
as long to recharge additional power systems. Once
twice the RTG’s endurance has elapsed, the robot
ceases to function.

RTG units are large, consuming a considerable portion
of the robot’s Slots for installation, shielding and
cooling. Their cost is based on the robot’s Base Slots.

Aging or obsolete RTGs can be replaced but at a cost
equal to the replaced RTG plus the new power unit.
This assumes proper disposal and safety precautions
during the process. Shortcuts can reduce this cost but
are likely to cause repercussions.

RTG Long
Duration TL Slots Endurance

Cost per
Base Slot
Basic 7 20% 25 years Cr20000
Improved 9 15% 50 years Cr50000
Advanced 11 10% 100 years Cr100000

RTG Short Duration
A more compact version of the radioisotope
thermoelectric generator (RTG) uses faster decaying
isotopes to provide more power in a smaller package,
although duration is still long by battery standards.

RTG Short
Duration TL Slots Endurance Cost per Slot
Basic 8 15% 3 years Cr50000
Improved 10 10% 4 years Cr100000
Advanced 12 5% 5 years Cr200000

Solar Power Unit
A solar power unit, composed of solar panels,
converters and batteries, is dependent upon sunlight
to generate power but its converters and batteries
allow operation in the dark for half as many hours as it
spent in sunlight. If the robot limits its activity to half its
solar-powered limits (by halving again its movement
and STR and reducing Agility by a further -2 – this is
referred to as ‘quarter power’) it may operate for as
many hours as it spent in sunlight and if stationary
and performing only limited physical activity, it may
continue to function at that low level for twice as many
hours as it spent in light. If equipped with additional
power packs, in this lowest operational state, during
periods of sunlight it can fully recharge a power pack
in twice the hours as the power pack supplies. Under
quarter power operations, it requires four hours
to charge one hour of power pack endurance and
under ‘normal’ solar power operations it will require
eight hours. Without multiple power systems or
supplemental sources, the solar power unit will never
provide full power.

A solar power system is designed to operate in a star’s
habitable zone. In a star system’s cold zone, usually
on a planet further out than a habitable-zone world, the
solar power unit provides only enough power to support
quarter power activity. At the world beyond that, it can
only support a stationary robot. Beyond that, in the
frozen outer solar system, it cannot function. Adding
additional sets of solar power units extends its zone

Slot Cost Options

Solar Power Unit TL Slots Endurance Cost per Base Slot
Basic 6 20% 10 years Cr2000
Improved 8 15% 25 years Cr5000
Enhanced 10 10% 50 years Cr10000
Advanced 12 5% 100 years Cr20000

**Quick Charger**
Regardless of a robot’s endurance, a full recharge for a
robot not operating on external power typically requires
eight hours plugged into an external power source.
For some robots, this is not sufficient for their duties.
The quick charger option allows a robot to be fully
recharged in one hour from a high amperage power
source such as those found in starship engineering
spaces or facilities supporting electric vehicles.

Item TL Slots Cost
Quick Charger 8 1 Cr200

of operation, as does the addition of the solar coating
option but since solar power weakens with the square
of distance, an outer system solar-powered robot
remains impractical.

Certain atmospheres or local conditions might further
limit the effectiveness of solar power. Even a deep
valley on an otherwise habitable world might limit
solar power activity. Like RTGs, solar power systems
have an endurance measured in years, representing
degradation of solar panels over time. However, solar
panels can be replaced and the endurance period
assumes daily operations; a robot stored in a powered-
down state or that only uses solar power as an
occasional supplement when ‘off the grid’ can expect
considerably longer lifetimes.

Robots with deployed solar power units may still
possess a Stealth trait but suffer a DM-2 to any
Stealth checks or provide a DM+2 to the opposition’s
Electronics (sensors) or Recon checks.

Deployed solar power units increase the effective Size
of a robot by +1. The panels may not be armoured
beyond the base armour of a robot’s Tech Level. Unless
attacks are specifically targeted against a robot’s
components, half of all successful attacks against a
robot with deployed solar power are considered to hit
the solar power unit, which has 10% (round up) the Hits
of the robot itself and ceases to function if destroyed.

Sensor Options
Sensors that require internal space for complicated
electronics or instruments require Slots. These sensors
are not usually subject to the benefits of miniaturisation
and cannot be used by microbots or nanorobots. All
sensors listed in this section, with the exception of
recon sensors, require an Electronics (sensors) skill of
at least level 0 to operate and might require appropriate
Science or Investigate skills to interpret results.

Bioscanner Sensor
A bioscanner sensor detects organic molecules and
tests chemical samples, studying the components of a
sample to detect poisons or bacteria, analyse organic
matter, search for life signs and classify unfamiliar
organisms. Unlike a science toolkit, samples do not
need to be collected to perform a scan; instead,
samples must be within three metres of the sensor
to achieve a successful scan. This TL15 option costs
Cr350000 and occupies two Slots but can provide
answers to biological questions in a manner of minutes.

Item TL Slots Cost
Bioscanner Sensor 15 2 Cr350000

Densitometer Sensor
A densitometer sensor uses minute variations in a
target’s gravity to determine its internal composition.
A densitometer sensor must be within 100 metres of a
target to make an accurate reading.

Item TL Slots Cost
Densitometer Sensor 14 3 Cr20000

Slot Cost Options

TRAVELLER

Neural Activity Sensor
A Neural Activity Sensor (NAS) detects neural activity
up to 500 metres distant and provides a rough
estimation of the intelligence of organisms based on
mental activity. The NAS performs tasks in real-time but
even at TL15 remains a bulky instrument.

Item TL Slots Cost
Neural Activity Sensor 15 5 Cr35000

Planetology Sensor Suite
A planetology sensor suite is a set of instruments
intended to analyse the characteristics of a planetary
environment, providing a full workup of atmosphere
and surface composition, climatic conditions and
rough internal planetary structure. The suite includes
functionality of the atmospheric sensor and advanced
olfactory sensor options, adds +1 to the maximum skill
level supported by a Science (planetology) toolkit and
provides DM+1 to any checks conducted in conjunction
with data provided by the suite.

Item TL Slots Cost
Planetology Sensor Suite 12 5 Cr25000

Recon Sensor
A recon sensor package actively maps the environment
looking for movement or anomalies that require
the robot to take action or make a decision. The
package emulates the Recon skill and can only be
installed once. It is usable against both conventional
stealth and electronic defences. It includes visual,
auditory, chemical detection and electronic detection
components and can be used in lieu of Electronics
(sensors) to detect targets of reduced electronic
signature. Recon skill levels provided by this sensor are
not modified by a robot’s INT.

Recon Sensor TL Slots Recon Skill Cost
Basic 7 2 1 Cr1000
Improved 8 1 1 Cr100
Enhanced 10 1 2 Cr10000
Advanced 12 1 3 Cr20000

Tool Kit Options
A robot may have an internally mounted toolkit
dedicated to a specific skill or set of tasks. Some
tools may be fixed so they function directly from
their mountings, others may be detachable for use
by a robot’s manipulators or by another individual.
Where specified by the Maximum Skill column,
the complexity of a toolkit is the limiting factor of
a robot’s skills using the robot’s internal toolkit
capability, although it does not limit the robot’s skill
when it has access to external specialised tools.

Cutting Torch
A basic cutting torch uses incandescent gases fed by a
receptacle to cut metal but is ineffective on crystaliron
and superdense alloys. The improved cutting torch
uses a plasma cutter that can cut through nearly all
materials, although it can take a long time to breach
hull armour. The miniaturised advanced cutting torch is
a UV laser torch of similar power. A cutting torch can be
improvised as a melee weapon, doing 3D damage with
the AP 4 trait. A cutting torch is included as part of the
starship engineering toolkit option.

Cutting Torch TL Slots Cost
Basic 5 2 Cr500
Improved 9 2 Cr5000
Advanced 13 1 Cr5000

Electronics Toolkit
An electronics toolkit contains the tools required to
install, troubleshoot and repair electronic equipment.
It is highly dependent on the Tech Level of both the
tools and the equipment being worked on. In general,
a toolkit only allows a positive DM to repair attempts
if it is at least the same Tech Level as the equipment
being repaired.

Electronics
Toolkit TL Slots

**Maximum
Skill Cost**
Basic 6 1 0 Cr2000
Improved 8 1 1 Cr4000
Enhanced 10 1 2 Cr6000
Advanced 12 1 3 Cr8000
Slot Cost Options

**Fire Extinguisher**
The fire extinguisher is designed to extinguish most
types of chemical and electrical fires. If used to
assist a Traveller who has been subjected to fire,
the extinguisher reduces damage by half during the
first round it is used before eliminating all damage in
subsequent rounds.

Item TL Slots Cost
Fire Extinguisher 5 1 Cr100

**Forensic Toolkit**
This specialised analytical toolkit is designed to
investigate crime or accident scenes to determine
what has occurred. It is used in conjunction with the
Investigate skill. With equipment and materials useful in
supporting the scientific skills of biology and chemistry,
it can often aid in a task chain using one or more
Science skills and Investigate to reach a conclusion.

Forensic Toolkit TL Slots

Maximum
Skill Cost
Basic 8 5 0 Cr2000
Improved 10 4 1 Cr4000
Enhanced 12 4 2 Cr8000
Advanced 14 3 3 Cr10000

Mechanical Toolkit
A mechanical toolkit includes tools required for
mechanical construction and repair. It is limited by the
skill of the user, not the sophistication of the tools, and
to some extent the Tech Level of the equipment it must
repair. If a piece of equipment is more than two Tech
Levels more advanced than both toolkit and robot,
repair attempts suffer DM-2.

Mechanical Toolkit TL Slots Cost
Basic 4 6 Cr1000
Improved 8 4 Cr2000
Advanced 12 2 Cr4000

Scientific Toolkit
A scientific toolkit contains tools related to a single
scientific speciality such as biology, chemistry or
robotics. Obviously, an astronomy toolkit does not
include a large telescope, nor does a physics toolkit
contain a small particle accelerator, but in general a
toolkit contains the materials required to perform tasks
or interpret data for a robot to successfully complete
a scientific skill check, such as microscopes, testing
materials and detailed libraries of scientific data. The
speciality of the toolkit must be specified at installation.
Biology, chemistry and some other toolkits can be used
in tasks requiring the Investigate skill or in lieu of a
forensic toolkit at the Referee’s discretion.

Scientific
Toolkit TL Slots

Maximum
Skill Cost
Basic 5 4 0 Cr2000
Improved 8 3 1 Cr4000
Enhanced 11 3 2 Cr6000
Advanced 14 3 3 Cr8000

Slot Cost Options

TRAVELLER

Starship Engineering Toolkit
This set of equipment provides increasingly complex
toolkits for a robot to perform routine engineering
maintenance and repairs aboard a spacecraft. These
include generalised electronic and gravitic test and
repair equipment, mechanic’s tools, a small laser,
cutting torch, bulkhead patches, iris valve opener, duct
tape and a large hammer. A starship engineering toolkit
supports starship-related engineering, electronics
and mechanical repair tasks at up to the maximum
Electronics, Engineer or Mechanic skill indicated.

The toolkit may be used as a generalised electronics
or mechanical toolkit but at a potentially lower skill
maximum at the Referee’s discretion.

Starship Engineering Toolkit TL Slots Maximum Skill Cost
Basic 8 6 0 Cr1000
Improved 10 5 1 Cr2000
Enhanced 12 5 2 Cr4000
Advanced 14 4 3 Cr10000

Stylist Toolkit
A stylist toolkit contains tools and supplies (product)
to allow the robot to cut, style, colour and wash
hair, trim, polish and colour nails, apply facials
and makeup and perform similar tasks in each
species-specific kit. The kit contains both tools and
receptacles to hold and dispense product. Additional
product can be sourced from an adjacent storage
compartment. One Slot or two litres of product is
included within the toolkit and is sufficient for 10 full
beauty sessions and costs Cr500 to replenish.

For styling appropriate to a higher SOC, the cost of
product doubles for every point of SOC past 8 but
a positive Effect of a Profession (stylist) check can
increase the effective SOC of the product’s value by the
Effect’s value. Only when attempting to exceed SOC
8 with ‘inferior’ product is a check normally necessary,
and an exceptional failure might have consequences
Every species has its own stylist toolkit and use on
another species inflicts DM-3 or worse on a task to
attempt even ‘adequate’ styling.

Item TL Slots Cost
Stylist Toolkit 6 3 Cr2000

Weapon Options
Combat robots may carry standard weapons and use
combat skill packages but more often a robot intended
for combat operations has built-in weapon and fire
control capabilities. These may include integrated
weapon mounts and targeting sensors.

Fire Control System
A fire control system provides targeting assistance to
weapons that are integrally mounted on a robot. The fire
control system is tied to a single or linked set of weapon
mounts and provides targeting bonuses to that weapon
or linked set. Each weapon or set of linked weapons
generally requires its own fire control system. A fire
control system includes the Scope trait and requires one
Slot. It is usable only for one primary target at a time.

For finalisation purposes, Weapon Skill DM is treated as
the weapon skill of the robot with the integrated weapon.

An integrated weapon without a fire control system
should allocate a skill package containing at least a
level 0 weapons skill to avoid an unskilled DM-3 when
using an installed weapon.

Standard weapons held by a robot are primarily
governed by the robot’s weapon skill and DEX modifier.
A dedicated fire control system for a manipulator-
held weapon or any fire control system for a weapon
mounted in a robot’s manipulator provides a bonus to
that weapon in addition to the robot’s weapon skill, if any,
but this bonus does not stack with any DEX modifier for
that manipulator; instead, the larger of the DEX or the
dedicated fire control system modifier applies.

Fire Control
System TL Slots

Weapon
Skill DM Cost
Basic 6 1 +1 Cr10000
Improved 8 1 +2 Cr25000
Enhanced 10 1 +3 Cr50000
Advanced 12 1 +4 Cr100000

Slot Cost Options

**Weapon Mount**
A weapon mount is integrated into a robot, either as
an attachment to a manipulator or a separate weapon
servo. A weapon mounted in the robot’s torso may use
any available Slots. A weapon installed into a weapon
mount does not require additional Slots but the weapon
mount does not include the cost of the weapon or any
ammunition or power pack. The external power packs of
weapons do not require additional mounts or Slots.

The Minimum Manipulator Size is the required
manipulator size for attaching a weapon mount to a
robot’s manipulator and being able to use its DEX or
STR modifier.

A small weapon mount may hold any melee weapon
useable with one hand, any pistol or equivalent
single-handed ranged weapon, or an explosive charge
or grenade of less than three kilograms. A medium
weapon mount may hold any larger weapon usable by
Melee or Gun Combat skills or an explosive of up to
six kilograms. A heavy mount may hold any weapon
usable with Heavy Weapons (portable). A vehicle
mount may hold any weapon of mass 250 kilograms

Weapon Mount Slots Minimum Manipulator Size Cost
Weapon Mount (small) 1 3 Cr500
Weapon Mount (medium) 2 5 Cr1000
Weapon Mount (heavy) 10 7 Cr5000
Weapon Mount (vehicle) 15 — Cr10000

or less that requires Heavy Weapons (vehicle).
Larger weapon mounts are only available on vehicles
designed using the Vehicle Handbook.

Each weapon requires a separate mount, however
up to four weapons of the same type can have their
mounts linked. Linked mounts make only one attack
roll and require only one fire control system. If they
successfully hit a target, only one damage roll is
made for them but they add +1 per damage dice to
the total damage dealt to the target for every extra
weapon. This bonus has already been factored into
the robots described in this book.

Weapon Mount Autoloader
By doubling the number of Slots used, a weapon
mount can be equipped with an autoloader and up to
10 additional magazines or power packs. The cost of
this is equal to twice that of the additional magazines.
Autoloaders increase the Minimum Manipulator Size of
the mount by +1.

Item TL Slots Cost
Weapon Mount Autoloader 6 +100% Weapon Mount size 20 x magazine cost

Slot Cost Options

TRAVELLER

**THE VEHICLE HANDBOOK AND ROBOTS**
A designer may include additional options from the Vehicle Handbook that require vehicle Spaces
within a robot design at a conversion rate of one Space per 64 Slots. For any options listed both in
the Vehicle Handbook and Robot Handbook, the designer should use the option in the latter when
applied to a robot design.

Specifically, options from the Vehicle Handbook that do not require Spaces must use a Robot
Handbook equivalent since what is an insignificant amount of volume on a vehicle might be very
significant on a robot. Vehicle Handbook options that consume a percentage of Spaces must use the
Robot Handbook equivalent, if available. Percentage calculations should always be rounded up.

**ROBOT OPTIONS AND ARMOUR**
Many options included in the robot design rules could be applied to armour or vacc suits. In fact,
many options listed for robots are included as features or part of the electronics suite for armour
and vacc suits described in the Central Supply Catalogue. Others are similar features available as
Slot options for battle dress.

In general, any option listed in the Robot Handbook can be applied to a Traveller’s armour, vacc
suit or battle dress. For Slot sizing purposes, a human-scale vacc suit and most non-powered
armour is considered Size 5. Any suit massing more than 100 kilograms – usually battle dress

- is considered Size 6. Non-battle dress suits can use Zero-Slot items up to their TL or TL +5 if

no Electronics Suite is included. Optionally, these suits can include up to eight Slotted items at a
mass cost of three kilograms per Slot. Battle dress can use a number of Zero-Slot items up to its
TL and as many Slotted items as the armour supports.

Most items function on a Traveller’s armour as they do on a robot. However, radiation hardening
on a robot can focus on critical electronics, while a Traveller’s protection must be whole-body. The
radiation environment protection option provides only TL x 10 additional rads protection beyond
that of the armour if installed but the option may be installed multiple times.

**EXAMPLES**

Steward Droid
The Steward Droid normally has access to a wet bar
and a galley but for versatility and ‘field service’ the
designer has chosen to install an autobar and autochef
within the robot. With the goal of providing Steward 2
skill, both the autobar and the autochef are enhanced
versions, costing Cr2000 and Cr5000, respectively.
The autobar requires two Slots; the autochef requires
three. In addition, to allow the Steward Droid to deal
with dietary requirements, food poisoning and other
mishaps, the designer has included a basic medikit,
costing Cr1000 and requiring one Slot.

STEWARD DROID

**Physical Options**

**Item Slots Notes TL Traits Skill Cost**

Olfactory sensor (improved) 0 10 Heightened Senses 3500

Autobar (enhanced) 2 Max DM+2 10 2000

Autochef (enhanced) 3 Max DM+2 11 5000

Medikit (basic) 1 Max DM+0 8 1000

Storage compartment
(refrigerated)

2 ~4 litres 200

With the above options requiring six Slots, the
Steward Droid has two remaining Slots. The designer
chooses to dedicate these to refrigerated storage at a
total Cost of Cr200.

The Steward Droid has no capacity to carry weapons.

**StarTek**
The StarTek robot is designed to repair starships.
As such, its most important option is an advanced
starship engineering toolkit. At TL14 this can support
a skill level of up to 3 in repair tasks, requires four
Slots and costs Cr10000. As a secondary function,
the robot can provide first aid in damage control
situations and is equipped with an enhanced
medikit, allowing it to offer up to Medic 2 skill if its
programming supports it. Additionally, to operate
in dangerous environments, StarTek has radiation
environment protection, requiring one Slot and
costing (Cr600 per Slot) Cr9600. Adding to the 500
rads of protection provided by vacuum environment
protection, this option blocks another 700 rads (50 x
14) for a total of 1,200 rads protection.

Finally, the robot may have to deal with a variety of
situations, including a literal rat’s nest in the wiring.
So, it is equipped with a TL12 stunner attached to a
small weapon mount. The mount requires one Slot
at Cr500 and the stunner costs an additional Cr1000
plus Cr200 for the power pack. This weapon can be
installed in the Size 3 manipulator to take advantage
of the small manipulator’s DEX DM+2. If a skill
package of at least Gun Combat 0 is installed in the
robot, it can use this weapon without a fire control
system or a DM-3 penalty.

At this point in the design, the StarTek robot has
two Slots unallocated. A brain upgrade (noted later)
requires one of these Slots but the final available
Slot is noted as a spare for buyer customisation and
future upgrades.

STARTEK
Physical Options
Item Slots Notes TL Traits Skill Cost
Vacuum Environment Protection 0 +500 Rads 6 9600
Starship engineering toolkit
(advanced)

4 Max DM+3 14 10000

Medikit (enhanced) 1 Max DM+2 12 5000
Radiation environment protection 1 +700 Rads 14 9600
Weapon mount: pistol 1 5 500
(spare) 1 Future use

Weapon TL Range Damage Magazine Cost Traits Cost
Stunner 12 10 3D 100 200 Stun, Zero-G 1000

## B RAIN

A brain is what makes a robot something more than a
mobile machine or drone. It provides purpose to the
robot’s actions. The distinction between a drone and a
robot is a robot’s lack of an external operator. A drone
may have some autonomous functions but without
external input, it cannot devise or revise its tasks. A
robot, once instructed to perform an activity, does so
autonomously and reacts to changing conditions. A
vehicle autopilot is not generally considered a robot, as
the ability to perform mobility tasks is considered a base
function of a moveable machine and does not allow the
vehicle to perform any other tasks besides navigating
its environment, a task so innate to a robot that it is
considered a trait, not a skill. Robots have skills beyond
the ability to traverse their environment.

Brain Types
Robot brain types range from simple programmable
computers to fully sentient beings. In general, as Tech
Levels increase, capabilities increase and costs of
equivalent brains decrease, often dramatically. Robot
brain types begin with simple programmed mobile
computers and progress to full consciousness.

Primitive
The robot has one core function hard programmed
into its memory. It is not considered intelligent but is
a programmed machine with limited ability to deal
with contingencies by referring to preprogrammed
decision trees and by indicating alarm status or shutting
down when experiencing error conditions. It cannot
communicate in any meaningful manner beyond
preprogrammed messages.

Basic (X)
The robot has limited intelligence and is focused on
its core function. This function is generally determined
when it is manufactured and cannot be changed or
augmented. Very little additional memory for new
skills is available. The robot avoids obvious hazards
and can only communicate alerts or status related to
programmed functions. It ignores inputs outside the
criteria for completing its functions and is limited in
understanding by its data set. A list of common core
Basic functions is featured on page 6.

Hunter/Killer
The robot has a modified Basic intelligence enabling it
to distinguish between friend or foe in a configurable
manner. Identification can be based on criteria such
as species, uniform, passwords or other factors
including biometric recognition from a database. It
performs a configurable combat action – such as block,
detain, disable, kill or an escalating set of actions –
against any target that does not conform to its ‘friend’
parameters or it can be configured to only engage
based on specified ‘foe’ parameters. A Hunter/Killer
brain provides a default skill of Recon 0. A specialised
form of Hunter/Killer has a built-in tactical engine to
allow it to function effectively in battlefield conditions.

Advanced
The robot has general intelligence and can
communicate and interact with its environment in a
manner that emulates a sentient being. Communication
and actions are literal and formulaic with the potential
for unexpected or unfamiliar circumstances to
cause confusion, inaction or inappropriate action.
An Advanced robot can have its skillset increased
or changed by adding additional computing capacity
during installation or at a later time. Advanced robots
can attempt tasks up to Difficult (10+).

Very Advanced
The robot is highly intelligent, capable of logical
reasoning and can attempt functions outside its
programmed parameters. It is not conscious but
appears to be so and considers itself to be conscious
without fully understanding the concept. Very Advanced
robots can perform at capabilities similar to or superior
to biological sentients in a broad variety of skills. A Very
Advanced robot can develop interests and hobbies
outside its programmed functions. Very Advanced
robots can attempt tasks up to Very Difficult (12+).

Self-Aware
The robot is capable of fully independent thought
and reason. While not considered a fully conscious
sentient being, this is a philosophical distinction that
a Self-aware robot can understand and debate. A
Self-aware robot can accomplish tasks based on
very general parameters or solely interpretation of its

TRAVELLER

owner’s requirements. Self-Aware robots have innate
intelligence greater than most biological beings and can
attempt Formidable (14+) tasks.

Conscious
The robot is a fully conscious being in every aspect. It
can exceed its parameters and limitations and has the
ability to develop true emotions and ambitions that might
not conform to the expectations of its biological creators.
Conscious brains combine full sentient thought patterns
with high-speed computational and analytical circuitry
allowing them to exceed the intellectual capacity of non-
augmented biological beings.

SIZE LIMITS
A robot brain fits into a robot chassis of a Size equal
to or exceeding its initial Computer/X rating at no Slot
cost. At each TL after its introduction, a given brain fits
into a robot one Size smaller. In all cases, a robot brain
can be accommodated by expending one Slot. For
instance, a TL13 Very Advanced brain can be included
in a Size 4 or larger robot at no Slot cost at TL13. That
same brain could be incorporated into a smaller robot,
down to Size 1 by using one Slot. At TL14, that same
Very Advanced Computer/4-equivalent brain could be
accommodated in a Size 3 or larger robot at no Slot

Robot Brains
Programming/
Control TL Computer/X Cost

Base
INT Skills

Base Capability
(built-in at no Bandwidth cost, cumulative)
Primitive 7 0 Cr10000 1 -2 Programmable
Primitive 8 0 Cr100 1 -2 Programmable
Basic (X) 8 1 Cr20000 3 -1 Limited language, Security/0
Hunter/Killer 8 1 Cr30000 3 -1 Limited Friend or Foe, Security/1
Basic (X) 10 1 Cr4000 4 -1 Limited language, Security/0
Hunter/Killer 10 1 Cr6000 4 -1 Limited Friend or Foe, Security/1
Advanced 10 2 Cr100000 6 +0 Intelligent Interface, Expert/1, Security/1
Advanced 11 2 Cr50000 7 +0 Intelligent Interface, Expert/1, Security/1
Advanced 12 2 Cr10000 8 +0 Intelligent Interface, Expert/1, Security/1
Very Advanced 12 3 Cr500000 9 +1 Intellect Interface, Expert/2, Security/2
Very Advanced 13 4 Cr500000 10 +1 Intellect Interface, Expert/2, Security/2
Very Advanced 14 5 Cr500000 11 +1 Intellect Interface, Expert/2, Security/2
Self-Aware 15 10 MCr1 12 +2 Near sentient, Expert/3, Security/3
Self-Aware 16 15 MCr1 13 +2 Near sentient, Expert/3, Security/3
Conscious 17 20 MCr5 15 +3 Conscious Intelligence, Security/3
Conscious 18 30 MCr1 15 +3 Conscious Intelligence, Security/3

cost and in Size 1 or 2 robots at a cost of one Slot, but
the TL14 Very Advanced Computer/5-equivalent brain
requires one Slot if installed in a robot smaller than
Size 5.

BASE INT AND SKILLS
For skills normally modified by INT or EDU, the skill DM
of a robot brain is associated with its INT modifier. This
is generally incorporated into the listed skill level of a
robot, allowing a highly intelligent robot to substitute its
general intelligence for a more expensive skill package.
For instance, a TL12 Advanced Brain has base INT 8,
which provides DM+0 on INT-based skills. If the robot’s
brain is upgraded to INT 9, it receives DM+1 to all INT-
based skills and for simplicity, this +1 is added to the
skill level of the robot.

ADVANCED CAPABILITIES
In addition to Bandwidth available for skill packages,
robot brains of Advanced or greater capability have the
ability to exceed their programming through installed or
acquired skills of level 0. For each point of Computer/X
inherent (not expanded) Bandwidth, a robot may have
X zero-level skills. If these skills are specified as part
of the robot’s design, they require a cost equivalent
to the skill’s level 0 package cost; if the skill develops
naturally in the course of a robot’s experience, they
have no monetary cost.

Brain

RETROTECH
As technology advances, brains with previously
cutting-edge technology become less expensive. This
capability is already expressed on the Robot Brains
chart prior to the advent of Very Advanced brains.
Thereafter, capabilities increase dramatically with
technology improvements. A brain of Very Advanced
or greater capability drops to 50% of its initial Cost for
every Tech Level above introduction. As an example,
a TL12 Very Advanced Brain costs Cr500000 when
introduced but costs only Cr125000 at TL14; however,
it only has the capabilities of the TL12 brain.

Brain Upgrades
The brains of all robots have limited Bandwidth. The
inherent Bandwidth of a brain type is an absolute
limit on the size of any singular skill package – for
instance a TL10 Advanced Brain with Bandwidth 2
cannot use any single skill package requiring more
than Bandwidth 2 – but a robot design can incorporate
one additional storage module as a one Slot option
to increase total brain Bandwidth capacity, increasing
the robot’s potential number of skills or allowing an
increase in the robot’s INT. This does not change the
robot’s inherent skill level limitations.

Brain Bandwidth Upgrade
A robot’s design can incorporate a single brain
Bandwidth upgrade package at an expenditure of
one Slot. A robot can use any Bandwidth Upgrade
package as long as its brain is of at least the Minimum
Base Brain indicated for the package in the table

**Minimum Base Brain TL Bandwidth Cost**

Basic or Hunter/Killer 8 +1 Cr5000

Advanced 10 +2 Cr5000

Advanced 11 +3 Cr10000

Advanced 12 +4 Cr20000

Very Advanced 12 +6 Cr50000

Very Advanced 12 +8 Cr100000

Self-Aware 15 +10 Cr500000

Self-Aware 15 +15 MCr1

Self-Aware 15 +20 MCr2.5

Self-Aware 15 +25 MCr5

Conscious 17 +30 MCr5

Conscious 17 +40 MCr10

Conscious 18 +50 MCr5

Brain Intellect Upgrade
A robot brain design can use Bandwidth to increase
general intelligence at additional cost. Each increase
in INT requires a cumulative cost in Bandwidth; for
instance, INT +1 requires Bandwidth 1 but INT +2
requires 1+2, or Bandwidth 3 and INT +3 requires
1+2+3 or Bandwidth 6. No brain can be increased
beyond INT +3. The cost to increase INT is based
on the new INT and is also cumulative and then
multiplied by Cr1000.

Increase Cost
INT+1 (INT+1) x Cr1000
INT+2 (INT+1) x (INT+2) x Cr1000
INT+3 (INT+1) x (INT+2) x (INT+3) x Cr1000
to INT 12+ Cost x 2

Item TL Effect Cost
Brain
Hardening

8 Protection from
ion and radiation
weapons

+50% Brain
and Bandwidth
upgrade

As an example, an increase from INT 6 to INT 9 requires
Bandwidth 6 and costs (7 x 8 x 9 x Cr1000) Cr504000.
Increased INT that brings a brain to INT 12 or greater
is doubled in cost, even for any incremental increase
below 12. Increases to INT must be permanently
configured into a brain at build time and cannot be
altered except by replacing the robot brain. The brain
intellect upgrade does not require Slot expenditure.

Brain Hardening
A brain can be protected from radiation and ion weapons
by use of alternate materials and shielding. A hardened
brain, much like a computer, is given the /fib designation
and costs 50% more than a comparable brain. To fully
protect the brain, any Bandwidth upgrade package must
also be hardened at a 50% cost increase.

Brain

**EXAMPLES**

Steward Droid
The Steward Droid is built at TL12 but targeted at the
consumer market and does not require a sophisticated
brain or upgrades for additional Bandwidth or INT. By
default, a TL12 Advanced brain provides the equivalent
services of a Computer/2 with regards to complexity
and Bandwidth, and costs Cr10000. It has base INT 8
and with a built-in Intelligent Interface, it can interact
normally with biological beings, although the limitations
of the Advanced brain keep verbal interaction literal and
narrowly focused. Note that with built-in Expert/1, it is
only capable of performing Difficult and simpler tasks.
With no modifications to its brain, the Steward Droid
has Bandwidth 2 available for skill packages and can
have two additional level-0 skills.

StarTek
As an all-around ship’s engineering robot, StarTek is
designed to be very intelligent. Starting with a TL14
Very Advanced Brain that provides Bandwidth 5 and
INT 11 for Cr500000, it is very capable on its own. To
increase INT and provide room for a variety of technical
skills, the designer has added a brain bandwidth
upgrade of +6, requiring one Slot and costing Cr50000.
One point of additional Bandwidth is dedicated to a
brain intellect upgrade, increasing the robot’s INT to
12 and granting DM+2 on INT-based skills at a cost
of Cr24000 (12 x 1000 x 2). This leaves Bandwidth
10 (the original 5, plus 5 from the upgrade) available
for skill packages. The StarTek can also have five
additional level-0 skill packages.

STEWARD DROID

**Robot Brain Type Slots TL Bandwidth Base INT Skill DM Capabilities Cost**

Advanced 0 12 2 8 +0 Intelligent Interface, Expert 1 10000

Bandwidth Upgrade Adjusted Bandwidth Zero Bandwidth Skills 2

Intellect Upgrade Adjusted INT Adjusted Bandwidth 2

Brain Hardening (/fib) ☐ Trait

STARTEK
Robot Brain Type Slots TL Bandwidth Base INT Skill DM Capabilities Cost
Advanced 0 14 5 11 +1 Intelligent Interface, Expert/2 500000
Bandwidth Upgrade: + +6 1 14 Adjusted Bandwidth 11 Zero Bandwidth Skills 5 50000
Intellect Upgrade: + 0 12 Adjusted INT 12 +2 Adjusted Bandwidth 10 24000
Brain Hardening (/fib) ☐ Trait:000

## S KILL PACKAGES

Primitive Brain Packages
A Primitive brain is a specialised computer
optimised for a single task. Primitive brains have no
initiative and can only communicate via structured
programmed inputs and responses.

Primitive brain packages include a set of skills and
are hard-coded, requiring no Bandwidth. Primitive
packages are available at TL7.

A Primitive brain only contains one hard-coded
package, which is included in the cost of the brain.
The package counteracts any potential negative
DMs associated with the computer’s DEX or INT
characteristics. Multiple Primitive brains cannot be
installed in a single robot.

Primitive (alert)
The alert package requires sensory input. The
package outputs a preconfigured alert based on
programmed instructions and input from connected
sensors. These sensors include those installed within
the robot and others connected by wired or wireless
networks to the brain. The alert package includes the
Alarm trait.

Primitive (clean)
The clean package requires a physical cleaning option
to perform its tasks. The robot cleans a designated
area as instructed, avoiding obstacles using both
sensory input and learning algorithms. It communicates
error conditions via installed communications options.
A clean package is much more limited than a Basic
(servant) package; it may only use domestic or
industrial cleaning options and not benefit from the use
of manipulators or outside tools to increase efficiency. It
is strictly a machine capable of using built-in equipment
to clean a given area.

Package Skills Cost
Primitive
(alert)

Recon 0 —

Primitive
(clean)

Profession (domestic cleaner) 2 —

Primitive
(evade)

Athletics (dexterity) 1, Stealth 2 —

Primitive
(homing)

Weapon 1 —

Primitive (evade)
The evade package is designed to avoid detection
through stealth and camouflage. It is useful in
surveillance roles but does not have the intelligence
to actively seek a target, making it more of a
distraction unless equipped with a recon sensor and
transceiver to gather and transmit data. The evade
package is preprogrammed to respond to stimuli. Its
decision tree is static but contains a randomiser to
make it appear unpredictable in behaviour.

Primitive (homing)
The homing package will keep the robot focused
on a designated target. The package interacts with
sensors, manipulators, locomotive and weapons
options to home in on a target. If so programmed,
it activates a weapons system when the target is
acquired using pre-defined algorithms. The homing
package lacks the sophistication of a Hunter/Killer or
Basic (target) brain and cannot distinguish between
friend or foe in any generalised manner or react to
changing conditions.

TRAVELLER

Basic Brain Packages
A Basic brain is not sophisticated but it is very
specialised. This allows for a relatively high level
of skill in tasks that do not require much initiative
or those without much ambiguity. A Basic brain
contains hard-coded circuits optimised for the robot’s
designated primary task. Except for the Basic (none)
brain, a Basic brain’s programming and default skill
are not variable once installed. A change of default
skill requires a full brain replacement.

Basic brain packages include a set of skills and
use Bandwidth 1. Basic packages are available at
TL8. The skills provided by a Basic package are not
subject to INT limitations – specifically, the negative
DMs – of the Basic brain.

Weapon skills are normally provided by targeting
options but a Basic (security) package may have
additional skills such as Melee related to intelligent
discretionary use of weapons.

Basic (labourer)
The Basic (labourer) package allows a robot to
perform functions such as agriculture, simple
construction or mining in conjunction with built-in
tools or tools operated by the robot’s manipulators.
In most instances a check is not needed for a
day’s labour but if the Referee finds it necessary or
interesting, the robot’s daily labour can involve an
Average (8+) check. Add or subtract 10% per Effect
to the robot’s output. An exceptional failure results in
some sort of mishap.

Package Skills Cost
Basic (labourer) Profession (labourer) 2 —
Basic (locomotion) Athletics (dexterity) X, Vehicle (type) X —
Basic (none) —
Basic (recon) Recon 2 —
Basic (security) Weapon 1 Tactics (military) 1 —
Basic (servant) Profession (domestic servant or domestic cleaner) 2 —
Basic (service) Mechanic 0, Steward 0 —
Basic (target) Explosives 1 or Weapon 1 —

A Basic (labourer) robot shows very little initiative
and performs duties according to a plan provided by
a supervisor. Problem solving and creativity are not
evident in this robot’s behaviour and obstacles are
met with brute force or a work stoppage followed by a
request for additional guidance. Complex construction
or fabrication projects require a robot with at least an
Advanced brain and skill packages such as Mechanic,
Engineer or a speciality profession.

A labourer package is designed around a set of tasks
within a specific function. The robot has the limited
role of an order taker with no innovative, planning or
questioning behaviour. While a robot cannot operate
beyond its function, it is usually broadly defined
within that function. For instance, a construction
robot is not limited to drywalling or roofing but to
the totality of construction tasks required to build a
house. However, its interpretation of the assignment
is literal – if instructed to build a room without doors
or without a floor it does so, exactly to specifications,
without question. Likewise, an agricultural robot
might be able to pick fruit from a tree or plough a
field, and even identify rotten fruit, but would be just
as adept at picking poison fruit or planting nice rows
of noxious weeds, if so instructed.

**Basic (locomotion)**
The Basic (locomotion) package is designed for
robots whose major function is to travel from
one location to another. This package is usually
installed on robots with a vehicle speed movement
Skill Packages

modification and functions similarly to an autopilot,
providing the robot with a skill in its vehicle class
operation equivalent to its agility enhancement
modification value. If the robot has no Agility
enhancement rating, it has skill 0 in the appropriate
vehicle operation. The Basic (locomotion) package
and an agility enhancement value also provides
the robot with Athletics (dexterity) skill equal to its
agility enhancement for the purposes of hazardous
manoeuvring and reactions such as dodging. Most
robots with a Basic (locomotion) brain have at least a
minimal agility enhancement modification installed.

**Basic (none)**
A robot may have a general purpose basic program
installed with no particular skills. This robot responds
to general commands with the sophistication of a
Basic robot and can be customised later, adding a
Basic package with the insertion of a skill chip for
a cost of Cr1000. Most robots are not sold without
a specialised chip but export restrictions or other
considerations might preclude the initial installation
of security or target packages.

A Basic (none) robot might instead be installed with
a single standard brain package at up to skill level

1. These skill packages are subject to the limitations

of the Basic brain’s INT, which will generally reduce
the effective skill level of the robot to 0, although
DEX-based skills might retain higher values. A Basic

(none) robot can benefit from a Bandwidth 1 upgrade
package to allow use of a second skill package at up
to skill level 1 but core brain limitations preclude the
use of Bandwidth 2 or greater packages.

Basic (recon)
An upgrade to the Primitive (alert) package, the
Basic (recon) package turns the robot into a keen
observer. While this package provides the Recon
skill, the package does not include any sensors,
limiting the robot’s capabilities to what it can detect.

The recon package makes the robot pay attention to
its surroundings. Some implementations have been
criticised as making the robot ‘too nosy’ but in general
the robot learns or is instructed about what to ignore
over time. Everything else is noted, recorded and
acted upon based on additional instructions.

Basic (security)
The Basic (security) package is concerned with the
protection of a facility, asset or person. A Basic (security)
robot lacks the aggressive behaviour and target
discerning capability of a Hunter/Killer robot and instead
focuses on defence of its designated asset. The security
robot follows operator-designated escalation procedures
and alarms, warns, detains or attacks based on simple
criteria. Friend or foe recognition is generally limited to
a password or electronic signal. The Basic (security)
package includes the Alarm trait.

Skill Packages

TRAVELLER

The security robot’s tactical skill is focused on
optimising a firing position and using available
cover. It sets only simple ambushes and behaves
in a predictable manner that an expert tactician can
soon anticipate. The security robot does not think
‘two steps ahead’ but picks the best available tactical
option. A security robot does not pursue its quarry
beyond specified parameters. It is also impossible to
reason with a Basic (security) robot; its instructions
are concrete and not subject to interpretation.

Security robots have an override or standdown code.
In some jurisdictions local law enforcement are
privy to the override code. Some less sophisticated
operators of security robots might leave default
codes in place but are liable to only make such a
mistake once.

Basic (servant)
The Basic (servant) package is concerned with
cleaning and less sophisticated household
maintenance. A servant robot can use all cleaning
equipment, including that designed for industrial use,
but cannot repair damaged goods or equipment, just
discarding it and noting the change in inventory to
allow for replacement. A servant robot is not adept at
making meals but can present them, clean up after
them and make sure materials for meals are properly
stored, reordered and disposed.

When operating in a purely domestic mode, a
servant robot can provide a clean, comfortable
environment for up to four Travellers. It cannot act
as a steward in a starship environment, nor can it fix
broken equipment, although it can handle clean-ups
if equipment malfunctions.

Basic (service)
A Basic (service) package is concerned with direct
service to the public or simple maintenance tasks.
A service robot can prepare a simple meal, ensure
basic household maintenance has occurred and note
any deficiencies beyond its capability to address.
The service robot has good interactive skills and
listens intently, although this does not guarantee
full comprehension. It takes assignments literally,
performing tasks as programmed or requested
without thought to unintended effects.

The service robot can operate domestic and
industrial cleaning equipment but only in a superficial
manner. It can prepare meals and beverages using
an autochef or autobar but only uses standard
recipes. A service robot can only repair items if it is
aware of the device’s specific purpose and known
failure states; without a service manual it can do
nothing. A service robot does not qualify a starship
to carry High passengers but it is adequate to
support up to eight Middle passengers or 100 Basic
passengers, however poorly.

Basic (target)
This specialised package turns the robot into a smart
bomb. The target package allows a robot to home
in on a single specified target and self-destruct. An
improvement on the Primitive (homing) package, it
provides the sophistication to change behaviour if the
target moves or mission parameters put the target out
of bounds, such as a targeted individual running into
a school or hospital. In such cases, it might hide and
wait for the target to emerge and reengage. The target
package is designed for proximity operations and is
not as sophisticated as a Hunter/Killer package.

The target brain package includes Explosives 1 and
Recon 0, although many designers improve inherent
capabilities with a more sophisticated recon sensor
option. A robot with melee or ranged weapons may
substitute an appropriate skill for Explosives 1 but
retains Explosives 0 if designed to self-destruct.

Hunter/Killer Brain Packages
A Hunter/Killer brain package is combat-focused and
includes both friend or foe identification and Recon

0. Higher level weapon skills are provided by fire

control systems options or DEX modifiers.

Hunter/Killer (standard)
A Hunter/Killer robot is much more aggressive than
a Basic (security) robot. Where a security robot is
concerned with the defence of an asset, a Hunter/
Killer can be given objectives for attack as well as
defence, carrying out an independent attack on a
designated enemy. Given a Hunter/Killer robot’s
focus on offensive rather than defensive action, it
has a much more refined friend or foe recognition
system. While an operator can still open parameters
to a setting as broad as ‘kill all but X’, in general
detailed parameters for determining legitimate targets
helps limit legal sanction against the operator for
indiscriminate or reckless mayhem.

Skill Packages

Package Skills Cost
Hunter/Killer (standard) Gun Combat/Melee 0, Recon 0 —
Hunter/Killer (tactical) Gun Combat/Melee 0, Recon 0, Tactics (military) 2 Cr10000

**Hunter/Killer (tactical)**
The tactical variant of the Hunter/Killer brain package
includes a specialised tactical analysis instruction set,
allowing the robot to not only develop a sound tactical
plan but also anticipate counter actions and adapt
to changing conditions. While this package does not
provide general intelligence, it makes the Hunter/Killer
(tactical) robot the equivalent of an idiot savant in
combat tactics and a much more dangerous and less
predictable foe. This tactical skill is not subject to the
INT limitations of the robot’s brain.

Standard Brain Packages
Standard brain packages are used by brains of at least
Advanced sophistication. These packages emulate
skilled tasks performed by biological beings. The
Standard Skill Packages table is based on a level of 0.
The Tech Level requirements for a skill vary with level,
with each additional level requiring one TL higher.

Most level 0 skills require no Bandwidth but complex
skills, especially those requiring interaction with
other beings, may require Bandwidth 1 even at level

0. Each additional skill level requires an additional

Bandwidth 1. A brain can hold as many Bandwidth
0 level 0 skills as its base brain Bandwidth score;
beyond this, additional Bandwidth 0 skills require
Bandwidth 1.

Cost increases by a factor of 10 per skill level; for
example, a skill costing Cr100 at level 0 is available
at level 1 for Cr1000 and level 2 for Cr10000. No
robot skill packages may exceed level 3 and robot
brains cannot process skills that require more
than a brain’s inherent (not expanded) Bandwidth.
Characteristic DMs for INT or DEX apply to all these
skill packages and may increase a robot’s effective
skill level beyond 3.

Vehicle skills such as Drive, Flyer, Pilot and Seafarer
assume a robot is piloting a vehicle or equipped with
a vehicle speed movement modification; movement
at Idle speed requires no skill. Robots employing
inherent locomotion functions or vehicles with robot
brains often use an autopilot to accomplish this
function, not a brain package. Most combat rolls
are performed using fire control systems; specific
combat skills generally only apply to weapons held
by a robot, not installed within it.

Recon and Stealth skills are available as standard
skill packages but these skills are most often
implemented in hardware, through specialised
sensors and camouflage or stealth coatings.

The Jack-of-all-Trades skill is never available to
any robot.

INHERENT SKILL DMS
The characteristic associated with a skill can provide
an additional DM to checks. For simplicity, this DM
is included in the final skill determination of the robot
as listed in the skills row of its description. While
some skills typically related to SOC or EDU are
listed as associated with INT, the robot’s effective
SOC or EDU is considered equivalent to its INT
but only in the very narrow sense of performing
the specified task. Only Self-aware and Conscious
robots have true SOC and EDU characteristics.

Finally, for skills with many specialities, the Referee
may rule that selecting a given skill package four
times at a certain level provides a broad enough
exposure so that the skill can be in all specialities.
Optionally, extremely broad skills such as Science
may require eight packages for full coverage.

Skill Packages

TRAVELLER

Standard Skill Packages
Skill TL Bandwidth Characteristic Cost
Admin 8 0 INT Cr100
Advocate 10 0 INT Cr500
Animals 9 0 DEX Cr200
Art 10 0 INT Cr500
Astrogation 12 1 INT Cr500
Athletics 8 0 variable Cr100
Broker 10 0 INT Cr200
Carouse 11 1 INT Cr500
Deception 13 1 INT Cr1000
Diplomat 10 1 INT Cr500
Drive 8 0 DEX Cr100
Electronics 8 0 INT Cr100
Engineer 9 0 INT Cr200
Explosives 8 0 INT Cr100
Flyer 8 0 DEX Cr100
Gambler 10 0 INT Cr500
Gun Combat 8 0 DEX Cr100
Gunner 8 0 DEX Cr100
Heavy Weapons 8 0 DEX Cr100
Investigate 11 1 INT Cr500
Language 9 0 INT Cr200
Leadership 13 1 INT Cr1000
Mechanic 8 0 INT Cr100
Medic 9 0 INT Cr200
Melee 8 0 DEX Cr100
Navigation 8 0 INT Cr100
Persuade 11 1 INT Cr500
Pilot 8 0 DEX Cr100
Profession 9 0 INT Cr200
Recon 10 0 INT Cr500
Science 9 0 INT Cr200
Seafarer 8 0 DEX Cr100
Stealth 10 0 DEX Cr500
Steward 8 0 INT Cr100
Streetwise 13 1 INT Cr1000
Survival 10 0 INT Cr200
Tactics 8 0 INT Cr100

Skill Packages

**EXAMPLES**

Steward Droid
The Steward Droid is designed to be a steward, so its
entire Bandwidth is used to provide Steward 2, which
costs Cr10000 and requires TL11 as a minimum. With
the Advanced brain having base Bandwidth 2, the
designer can designate two level 0 skills or hold them
in reserve for future development. In this case, the
designer chooses to provide Medic 0 for Cr200 to allow
use of the robot’s built-in medikit and Flyer 0 for Cr100
to allow the robot to act as a pilot for a flying vehicle.

STEWARD DROID

**Skill Package Level TL Bandwidth Characteristic/Trait Adjusted Skills Cost**

Steward 2 11 2 Steward 2 10000

Medic 0 10 0 Medic 0 200

Flyer 0 9 0 Flyer 0 100

Total Cost^39800

STARTEK

**Skill Package Level TL Bandwidth Characteristic/Trait Adjusted Skills Cost**

Electronics (comms) 1 10 1 INT Electronics (comms) 3 1000

Electronics (computers) 1 10 1 INT Electronics (computers) 3 1000

Electronics (remote ops) 1 10 1 INT Electronics (remote ops) 3 1000

Electronics (sensors) 1 10 1 INT Electronics (sensors) 3 1000

Engineer (m-drive) 1 10 1 INT Engineering (m-drive) 3 2000

Engineer (j-drive) 1 10 1 INT Engineering (j-drive) 3 2000

Engineer (life support) 1 10 1 INT Engineering (life support) 3 2000

Engineer (power) 1 10 1 INT Engineering (m-drive) 3 2000

Mechanic 1 10 1 INT Mechanic 3 1000

Athletics 0 9 0 STR Athletics (strength) 2 100

Medic 0 10 0 INT Medic 2 200

Explosives 0 9 0 INT Explosives 2 100

Gun Combat 0 9 0 DEX Gun Combat 2 100

(spare bandwidth) 1

(spare zero bandwidth = 1)

Total Cost^697100

StarTek
To do its job, StarTek requires Mechanic and a broad
range of Engineer and Electronic skills. Its INT 12
provides DM+2 to all these skills, allowing a package
of skill level 1 to emulate skill level 3 in the execution
of its duties. Engineer and Electronics each have four
specialities, accounting for Bandwidth 8 to gain all
specialities. Mechanic adds one more, using nine of
the available Bandwidth 10. With an advanced starship

engineering toolkit, the robot can perform all these tasks
at a equivalent skill level 3 and with built-in Expert/2, it is
capable of performing Very Difficult tasks.

Holding one Bandwidth in reserve for a customer-specific
skill package, StarTek can also use up to five Bandwidth
0 skill packages as part of its inherent capabilities. The
designer specifies four of these: Athletics, which allows
use of the DM+2 for increased STR in the robot’s two
upgraded manipulators; Medic, which with the INT
modifier and enhanced medikit can be performed at an
equivalent level 2; Explosives, also subject to the INT
modifier and envisioned to handle explosive ordnance
disposal functions; and Gun Combat, to allow use of the
Stunner without DM-3 as the robot lacks a fire control
system and with the DM+2 of the small manipulator,
giving it an effective Gun Combat (energy) 2. These skills
leave one available Bandwidth 0 skill. Very Advanced
robots are complex beings that can develop their own
hobbies and interests. To accommodate this, the designer
has left this package unassigned.

## F INALISATION

With the robot design complete, its information can be
compiled into a robot record sheet. The first section
in this is descriptive, providing the robot’s name and a
description of function, general appearance and specific
modifications, options and components.

COST MODIFICATION
Optionally, the designer may modify the robot’s final
cost at this time. Any robot’s cost can be rounded down
or up to one or two significant digits and discounts or
premiums can be applied for mass production or societal
acceptance or abhorrence of robots.

Standard discounts for common robot models range
from 10–20% but are applied unevenly. Combat-oriented
robots may be unavailable at any price and rarely sell
at discount unless purchased in large quantities. In
universes where a particular robot model is ubiquitous
and produced by the billions, cost may be reduced by as
much as 80%.

ROBOT RECORD SHEET
Robots are categorised in a standardised manner based
on capabilities, skills and traits. These entries are derived
from information recorded in the robot design form.

In the first blank row directly under Robot, record the
robot’s name, its Hits, mode(s) of locomotion, tactical
speed, Tech Level and final cost. If the robot has the
vehicle speed modification, record the speed as ‘–’
if it lacks locomotion, or as ‘Xm’ with X representing
speed in metres.

In the Skills row, list the robot’s skill equivalents in
alphabetical order, including any modifiers for INT or
other factors incorporated, ignoring duplicates. If a skill

Robot Hits Locomotion Speed TL Cost

Skills
Attacks
Manipulators
Endurance
Traits
Programming
Options

with specialities has a base level of 0 increased by the
robot’s INT or other characteristic to 1 or more, list the
specialisation relevant to the robot’s operation or list (all).

Attacks refers to the weapons installed on the robot.
List weapons and associated traits. While a robot can
use its manipulators as weapons it does not normally
do so unless it has a Melee skill package. The damage
of manipulators may vary but should be informed by
the size of the robot or its manipulators. Consider
manipulator size ÷ 2 as a good rule of thumb for damage
dice. If a robot has no weapons or Melee skill, treat its
attacks as ‘none’.

The Manipulators row should detail the quantity of
manipulators and their STR and DEX. These may vary
between manipulators. Also note if a walker has its legs
modified to be manipulators and their characteristics.

The Endurance row should include the robot’s final
endurance value and any alteration from the vehicle
speed movement modification. Endurance is normally
indicated in hours but power options such as RTGs
or solar are expressed in half-life years, with hourly
endurance from other sources listed in parentheses.

The Traits row lists the robot’s traits from all sources,
such as Armour, Locomotion, Size and Options, in
alphabetical order.

The Programming row records the robot’s brain type
and INT. Optionally, it may include special features or
Bandwidth enhancements.

Finally, the Options row contains all installed options,
Zero-Slot and Slotted, and any other information that
needs to be recorded, such as spare Slots available.

Robot Hits Locomotion Speed TL Cost
Steward Droid 10 Walker 6m 12 Cr35000
Skills Flyer 0, Medic 0, Steward 2
Attacks none
Manipulators 2 X (STR 7 DEX 7),
Endurance 97 hours
Traits Armour (+4), ATV, Heightened Senses, Small (-1)
Programming Advanced (INT 8)
Options Auditory Sensor, Autobar (enhanced), Autochef (enhanced), Medikit (basic),
Olfactory Sensor (improved), Storage Compartment (2 Slots refrigerated),
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless
Data Link

**Steward Droid**
A description of the Steward Droid should highlight
its function as a ship’s steward or household butler,
provide a basic description of the robot’s physical form
and list its options and their functions.

The Steward Droid’s final cost is Cr39800. Given that
this is a common design with a broad market and
competitive products available, it is likely to be sold at a
discounted price. First, rounding down to two significant
digits gives a cost of Cr39000. Then, applying a 10%
discount for quantity gives a cost of Cr35100. Rounding
this value down to two significant digits results in
Cr35000 as a final list cost. Availability may vary this
considerably and used models, with their quirks, might
be available for considerably less.

Skills, Traits and Options – basically all installed options
and any special characteristics – are determined from
the robot’s design worksheet and listed in alphabetical
order in the proper row.

**EXAMPLES**

Name: STEWARD DROID
Description: Replacing a qualified starship steward or an all-around household butler, the Steward Droid is
a humanoid robot designed to interact with people and food. The Steward Droid is a relatively
short and thin robot with long arms designed to reach high shelves or to scoop items off the
ground. With a built-in autobar and autochef and an advanced olfactory sensor, the Steward
Droid is adept at preparing meals and ensuring the comfort of passengers and guests. With an
integral medical kit and basic first aid and dietary knowledge, the Steward Droid can treat minor
ailments, recommend dietary changes and act as a basic medical aide in emergency situations.
Programmed with basic traffic regulations and flying vehicle operational guidelines, the robot
can act as an adequate chauffer, although this is often for show, as it is usually inferior to a
vehicle’s autopilot functions. The Steward Droid’s internal refrigerated storage compartment has
a capacity of two Slots beyond its inherent autobar and autochef capacity.

**StarTek**
A description of the StarTek should emphasise
its expert functions and possibly its origin story
as a ported Aslan-inspired design.

Skills, Traits and Options – basically all installed
options and special characteristics – are
determined from the robot’s design worksheet
and listed in alphabetical order in the proper row.

StarTek’s final cost is Cr697100. It is a speciality
robot so could sell at a premium. Rather than
applying a discount, its cost can simply be
rounded down to Cr690000. At TL14 and limited
to the spacecraft or space station engineering
market, a StarTek could be difficult to obtain,
perhaps requiring a waiting period or a premium
to secure a model.

Robot Hits Locomotion Speed TL Cost
StarTek 20 Grav Walker 6m 14 Cr690000
Skills Athletics (strength) 2, Electronics (all) 3, Engineer (all) 3, Explosives 2, Gun Combat
(energy) 2, Mechanic 3, Medic 2, +1 available Bandwidth
Attacks Stunner (3D Stun, Zero-G)
Manipulators 2 X (STR 12 DEX 8), 1 X (STR 5 DEX 12)
Endurance 72 hours
Traits Armour (+10), ATV, Flyer (idle), IR/UV Vision
Programming Very Advanced (INT 12)
Options Auditory Sensor, Medikit (enhanced), PRIS Sensor, Radiation Environment
Protection (+700 rads), Starship Engineer Toolkit (advanced), Transceiver 5km
(improved), Vacuum Environment Protection, Voder Speaker, Weapon Mount
(small), Wireless Data Link, Spare Slot x1

Name: STARTEK
Description: Loosely based on the Aslan Hikare’ technician robot, the StarTek is designed to be an all-around
replacement for a ship’s engineer. The humanoid robot is equipped with a grav propulsion
system allowing it to access ship components not easily reachable by human technicians. A third
arm can perform delicate electronics work. Skilled in all aspects of engineering, electronics and
mechanics and fully equipped with the tools of the trade, the StarTek can also act as a disaster
relief robot with a built-in enhanced medikit and skills to perform explosive ordnance disposal.
An armour coating, plus vacuum and radiation protection allows StarTek to operate in hostile
environments. As a defensive mechanism, the StarTek has a stunner built into its small arm to
discourage or disable living obstacles to completing its tasks.

## S PECIAL ROBOTS AND OTHER SYNTHETICS

In addition to traditional robots, other mobile machines

- artificial entities or synthetics – from drones to

nanorobots to androids are available for sale. Many
of these (usually) thinking, moving machines can be
designed using variations of the design procedures for
robots presented in the earlier sections of this book.
This chapter covers everything from mundane drones
to high technology creations beyond the capabilities of
most civilisations.

Drones
A drone is a robot-like machine without a robot
brain that is operated remotely. Robots may also
be considered drones when operated remotely via
a drone interface. Drones are controlled, either by
biological beings or robots equipped with a robotic
drone controller (see page 44). Other than often
having little or no brain installed, drones follow
standard robot design procedures.

DRONE INTERFACE
If a robot has a drone interface chip installed, its robot
brain can be overridden and operated as a drone with
either a biologically operated drone control interface
or a robotic drone controller. All that is required is a
control unit, communications – usually a transceiver or
wireless controller – installed and proper authorisation
codes to override the robot’s control of its own body.

If communications between the remote operator
and the drone fails, the drone may resume either
a preprogrammed or fully automatic set of actions.
Some drone interface chips mandate a shutdown if
communications are disrupted.

DRONE CONTROL INTERFACE
Biological beings operating drones with no robot
brain installed require a drone control interface
unit, identical to that described on page 67 of the
Vehicle Handbook. Limited to controlling only one
drone, they are not generally installed on robots but
can take the place of a more capable robotic drone
controller if desired. The Control DM is the modifier
applied to Electronics (remote ops) checks made
to control the drone through the interface. Drone
interfaces installed on robot-sized drones do not
require a separate actuation system as is needed
in larger vehicle-sized drones but they do require a
transceiver or wireless link to communicate with and
establish control of drones.

In lieu of a drone control interface, a TL8+ computer
may act as a basic drone control interface to control
a drone through a transceiver link. More advanced
computers running Drone Control software (see page
123) have better capabilities.

VEHICLE DRONES
Vehicle-sized drones do not require a drone interface
but in addition to a transceiver, the vehicle requires an
actuation system as described on pages 67–68 of the
Vehicle Handbook. The actuation system requires one
Space for every 20 Spaces of the vehicle (but none for
vehicles smaller than 20 Spaces) and costs Cr1000
per Space of the system.

Microbots
Most robots are large devices on par with a typical
sophont or large animal but certain classes of robots
such as surveillance units benefit from small size. A
microbot is generally insect-sized and the smallest
class of robot used as a single unit, although swarms
of microbots also have their uses. As Tech Levels
increase microbots become more sophisticated and
have the option to become smaller, although extreme
miniaturisation tends to offset cost savings from
decreased use of materials.

Drone Control
Interface TL Slots Control DM Cost

Primitive 5 2 -4 Cr1000

Basic 7 1 -2 Cr2000

Improved 9 0 0 Cr500

Advanced 11 0 +1 Cr4000

TRAVELLER

SIZE
A microbot is a Size 0 robot. By convention, a microbot
is any robot that has a mass of less than 30 grams, with
robots between this size and one kilogram living in a grey
area between Size 0 and 1, depending on whether they
can support a Slotted option. Minimum mass is limited
by Tech Level. Available at TL8, a microbot’s Base Cost
does not decrease from Cr50 with miniaturisation but the
minimum mass continues to decrease as Tech Levels
increase. Minimum microbot mass is one gram at TL8 and
decreases by about a factor of two for every subsequent
TL. All microbots have Hits 1 and the Small (-4) trait.
Microbots cannot have armour.

The Microbot Size table provides a rough minimum
‘length’ limit in millimetres (mm) for a microbot at varying
TLs. This minimum is based on a spherical design of
moderate density. The microbot’s actual dimensions can

vary at the discretion of the designer or Referee. Any
microrobot may be up to 30 grams maximum size at any
subsequent TL but is subject to the same restrictions as
a smaller microbot of the same TL.

LOCOMOTION
A microbot can use any locomotion. Movement rate
is halved (rounded up) but can be increased up to 12
metres per Minor Action by paying 50% of the cost
of the locomotion mode (in effect, locomotion mode
multiplier x Cr25 x tactical speed increase) for each
increase in metres per round.

As with a regular robot, each increase in tactical speed
reduces endurance by 10%. The efficiency modification
is available but the microbot cannot install additional
power cells to increase endurance. The locomotion
mode of ‘none’ is an available configuration but does
not grant any Slots. Neither vehicle movement nor
secondary locomotion modifications are available.

MANIPULATORS
A default microbot has no manipulators. Size 0
manipulators are available as Zero-Slot options but
count against the total number of Zero-Slot options
available to a microbot. A microbot manipulator is
treated as having STR 0 and the DEX of a full-sized
manipulator (TL ÷ 2 +1). The utility of these tiny
manipulators is left to the imagination of the designer.
Microbot manipulators cost Cr10 each.

ZERO-SLOT OPTIONS
A microbot does not have a Default Suite but can have
as many Zero-Slot options as its Tech Level. For the
purposes of options such as coatings whose cost is
determined by Base Slots, the microbot is considered
to have 0.5 Base Slots.

MICROBOT-ONLY OPTIONS
Besides Size 0 manipulators, microbots have certain
Zero-Slot options not available to standard robots,
including environmental protection and
self-destruct options.

Environmental chassis options that normally require
Slots are available for microbots but they are
expensive, multiplying the total cost of all microbot
components except software packages. This cost
multiplier is cumulative if multiple environmental
options are chosen, including if radiation environment

OPTIONAL CONSIDERATIONS
Microbots are destroyed by any blow that does
damage but can be notoriously hard to hit. Even
close combat is subject to the Small trait DM-4.
At the Referees discretion, attacking these very
tiny machines might require an additional DM-2,
especially with ranged weapons. If the robot is
stationary, however, dropping a heavy object on
the machine could solve the problem.

Microbot Size
TL TL Mass (mg) Minimum Length (mm)
(maximum) — 30,000 40
8 8 1000 12
9 9 500 10
10 10 250 8
11 11 125 6
12 12 60 5
13 13 30 4
14 14 15 3
15 15 8 2.5
16 16 4 2
17 17 2 1.5

Special Robots and Other Synthetics

protection is chosen multiple times. The environmental
options have the same effects and limitations detailed
in their standard descriptions.

Microbots have both defensive and offensive self-
destruct options. A defensive self-destruct causes 1D
damage to the microbot, at least destroying it, usually
beyond any hope of salvage. An offensive self-destruct
option is only effective with microbots massing more
than one gram and does 1D damage only to a target
in direct contact with the microbot. With a successful
melee attack a microbot might be able to penetrate
some types of armour through gaps or exposed
surfaces prior to detonation.

**Microbot Environmental Multiplier**

Option TL Cost Multiplier
Corrosive Environment
Protection

9 X 2

Insidious Environment
Protection

11 X 5

Radiation Environment
Protection

7 X 2

Microbot Brains
Brain TL Bandwidth INT Cost
Primitive 8 0 1 Cr100
Basic (x) 11 1 4 Cr4000
Hunter/Killer 11 1 4 Cr6000
Advanced 12 2 6 Cr10000
Very Advanced 15 3 9 Cr500000

MICROBOT BRAIN
A microbot’s brain is heavily miniaturised. Following
robot brain sizing limitations, a microbot cannot
install a brain until it becomes small enough to fit in
a Size 0 chassis without a Slot, for example, a Very
Advanced TL12 brain has Bandwidth 3 and could
not be installed in a microbot until three TLs later, or
TL15; this brain would still cost a full MCr0.5. Most
microbots have Primitive or Basic brains installed or
are designed as drones with no brain. The Microbot
Brains table lists these brains.

A microbot has no Slots available for Bandwidth
upgrades but may sacrifice Bandwidth for INT increases.

Special Robots and Other Synthetics

**MICROBOT DESIGN WORKSHEET**

Robot Name:
Characteristic Value Slots Effect Traits TL = Cost
Chassis Size 0 0 Hits = 1 Basic Cost:
Locomotion Type Agility = Multiplier: X
Skill
Armour Base = Total =
Endurance = Hours
Light Chassis N/A Hits: – 1 Total Hits =

Agility + Final Agility =
Tactical Speed ± Final Speed = Final Endurance = Hours
Zero-Slot Suite (5 Zero-Slot Items)
TL Item Notes TL Traits Skill Cost
1 2 3 4 5 6 7 8 9

10
11
12
13
14
15
16
17
18

Robot Brain Type Slots TL Bandwidth Base INT Skill DM Capabilities Cost

Bandwidth Upgrade: + Adjusted Bandwidth = Zero Bandwidth Skills =
Intellect Upgrade: + Adjusted INT = Adjusted Bandwidth =
Trait:
Skill Package Level TL Bandwidth Characteristic/Trait Adjusted Skills Cost

Total Cost:

**SWARM CONTROL**
A swarm controller operated by a robot or Swarm
Control software operated by a person allows control of
multiple microbots in accordance with the capabilities
and limitations described on page 122.

Nanorobots
Nanorobots, also called ‘nanobots’ or just ‘nanos’ are
very small robots. Despite their name, most nanorobots
are micron-scale. As most microbots are millimetre-scale
robots, this optimistic classification is nothing new and
some nanorobots are less than one micrometre, or 1,000
nanometres, in at least one dimension.

Unlike microbots, most nanorobots are too small
to be seen without magnification; unlike microbots,
nanorobots are not just tiny versions of fully functional
robots. Their minuscule size precludes advanced
programming, leaving nanorobots as single-purpose
programmed devices, usually operating in groups
ranging from less than a dozen to millions of machines
in a swarm. Nanorobots do not have endurance in
the common sense, recharging themselves from their
surrounding environment, but suffer degradation that
eventually renders them ineffective.

Early examples of nanorobots are more scientific
curiosities than practical machines. Mass-produced
nanorobots become feasible at TL13 and are
constructed in specialised manufacturing facilities
or enhanced fabrication chambers. Nanorobot
functions centre around three main purposes; medical
applications, such as healing or enhancement,
construction or destruction of macroscopic objects and
environmental alteration or clean-up duties.

In most jurisdictions (generally Law Level 2+),
nanorobots are considered controlled substances,
requiring licensing and adherence to strict regulations
to produce or sell. During the operative period of
the Shudusham Concords, nanorobots did not exist
outside experimental laboratories. Nevertheless, the
23 rd Amendment specifically restricted deployment
of lethal and self-replicating nanorobots. The former
remains mostly apocryphal, the latter far beyond
current technology.

Nanorobots are not sold individually but in packages,
usually a 0.1 litre or 0.1 kilogram container filled with
millions of nanorobots designed for a single purpose.

As a general rule, a single nanorobot package can
perform one medical function, increase one attribute
or transform one type of material, although packages

as large as one litre are often marketed to solve a
particular problem using a mix of nanorobots.

Nanorobots are considered to have vacuum and
hostile environment options as standard. Additional
environmental protections multiply the cost of the
nanorobot using the Microbot Environmental Multiplier
table on page 81.

Medical Nanorobots
Medical-grade nanorobots cost Cr20000 per
package or double (Cr40000) if intended to cross the
blood-brain barrier to affect Intellect. Aging control
nanorobots cost quadruple (Cr80000) as much per
dose. Medical nanorobots are normally infused into a
body intravenously within a fluid, although some may
be ingested.

The following rules apply to medical nanorobots:
•	 A smarm controller is required to initially
program medical nanorobots but once injected
or ingested, medical nanorobots operate
autonomously, although a swarm controller
could be used to deactivate them prior to their
effective end-of-life.
•	 A body can only absorb so many medical
nanorobot packages at once. After a
maximum of 15 active packages or 1.5 litres
of active nanorobots, each additional package
causes the recipient’s END to decrease by -1.
This is permanent.
•	 At TL13, medical nanorobots lose effectiveness
after one year and dissolve harmlessly inside the
body. Nanorobot durability doubles with every
TL, so TL15 nanorobots continue to function for
up to four years if not disrupted or destroyed.
•	 A single package can provide the effects of
common drugs such as panaceas for the
duration of the nanorobots’ effectiveness.
Negative effects of multiple or prolonged use
of certain drugs are manifest in nanorobot
packages just as in normal medications. No PSI-
drug packages are known to exist, although a
null package is rumoured to be in development.
•	 A single package can induce regeneration of one
characteristic point lost permanently due to injury
within one week, allowing regrowth of limbs,
eyes and all critical organs but the brain. No
more than four such packages can be in effect
at any time and the recipient requires at least
normal nutritional levels to facilitate regeneration.
•	 A single package can increase one
characteristic by +1. Maximum characteristic
increase is +3 but an increase of +2 requires
three packages (1 + 2) and an increase of +3
requires six packages (1 + 2 +3).

Special Robots and Other Synthetics

TRAVELLER

Aging can be slowed by medical nanorobots,
reducing aging rate by 50% at TL13, 75% at TL14
and 90% at TL15. Unlike anagathics, ceasing
nanorobot treatment will not cause an adverse
reaction but after 20 years of use, medical
nanorobots begin to lose effectiveness, becoming
one TL less effective at reducing aging.

This loss of effectiveness is cumulative but does
not change a nano’s period of effectiveness. For
example, a Traveller receiving nanorobot aging
treatment at TL15 must pay Cr80000 every four
years for a new package. Over the course of 60
years, the Traveller must receive a new package
every four years. The Traveller ages two years in the
first 20 years, five years in the next 20 and 10 years
in the final 20, for a total aging of 17 years and a total
cost of MCr1.2. At TL13, a Traveller pays MCr1.6
over the course of 20 years and ages 10 years
during that period. When starting with TL13 nanos,
further treatment would not be effective unless
continued with TL14 nanorobots but the Traveller
would already be considered to have undergone 20
years of treatment and the TL14 nanorobots would
be no more effective than the TL13 – although they
would last twice as long, thus reducing the cost of
the next 20 years.

In many jurisdictions, age reduction nanorobots
are highly controlled and often illegal, although a
considerable black market exists. A Traveller may
only use one aging reduction package at a time.

Medical Nanos TL Cost per package
Pharmaceutical 13 Cr20000
Physical enhancement 13 Cr20000
Mental enhancement 13 Cr40000
Aging rate reduction 13 Cr80000

Construction Nanorobots
Nanorobots intended for construction allow for ‘open
fabrication’ or the additive construction of objects
outside the confines of a fabrication chamber.
Fabrication nanorobots available at TL13 can only
build simple structures, the equivalent of a basic
fabrication chamber. Construction nanorobots
require some form of swarm controller and may
operate within a limited effective range of 50 metres
if two-way communication is required. One swarm
controller can control as many 0.1 litre ‘bags’ of
construction nanos as its Max Tasks value.

Nano constructors can build larger structures
over time. Cost is indicated in Slots of structure
produced per hour, which is the maximum capability
of a 0.1-litre bag of construction nanos. This
translates into 1/64 of a vehicle Space or 1/256 of
a displacement ton; four displacement tons can be
considered 1,000 Slots for simplicity.

As with fabrication chambers, material cost is 1D
x 10% the cost of the final product had it been
purchased instead of constructed. A simple structure
built from local materials costs nothing for materials
but requires twice the construction time per Slot to
account for both harvesting and construction using
those materials. More efficiently, environmental
excavation nanos (see below) can create a mining
tunnel or chambers inside an asteroid progressing at
the standard hourly rate while a set of construction
nanos could use the slag from the excavation
process to build surface structures, also at the
standard hourly rate.

Basic construction nanos can build simple structures
such as the shell of a building and a plumbing
system. Improved construction nanos can build a
complete facility, including power, environment and
lighting but not computer controls. Enhanced or
advanced nano constructors are not available until at
least TL18.

Construction nanos degrade relatively quickly over
time while actively working. They have an effective
working life of three weeks or approximately 500
hours. Much like medical nanos, at each Tech Level
past their introductory level, this lifespan doubles.
Construction nanos can operate for 24 hours a day
during their entire lifespan.

Special Robots and Other Synthetics

Construction Nanos TL Complexity Cost per Slot created per hour
Basic 13 Mechanical Cr10000
Improved 15 Simple electronics Cr50000

Environmental Nanorobots
Nanorobots can transform environments much
like microbes but in a more controlled manner.
Environmental nanorobots are tailored for specific
tasks ranging from simple excavation to soil creation
to environmental clean-up. More advanced nanos
can jumpstart environmental transformation but their
lack of ability to reproduce makes them ineffective
in large terraforming projects, although they have a
niche use in transforming smaller environments such
a sealed cave or lava tube.

Environmental nanos require some form of a swarm
controller and may operate within a limited effective
range of 50 metres if two-way communication
is required.

The base rate of excavation nano progress assumes
silicate rock. Softer surfaces are transformed at twice
the base rate while harder material, such as metal or
industrial rubble, is transformed at half the base rate.
The output of excavation nanos is dust, which must
be disposed of in some manner, but could be seed
material for construction nanos.

Soil creation nanos transform rock into soil,
preparing sterile environments for agriculture
or further transformation by microbes or other
organisms. The soil is the ‘waste’ produced by these
nanos and requires no disposal. Soil creation nanos
can also be used to slowly ‘disintegrate’ structures,
although they are unable to break down crystaliron,
diamond or superdense materials.

Environmental clean-up nanos must be tailored
for a specific containment. The specific output of
these nanos depends on the type of containment
and may range from useful by-products to solid
waste requiring further disposal. Procuring a nano
for a particular type of contaminant may be difficult
and for particularly toxic or radioactive by-products
these nanos might require special licensing and
handling. Costs are a range, with the most common
contaminants in a region costing the least to clean-
up. Unique nanos developed for novel contaminants
could cost up to Cr100000 per package.

Environmental nanos often act as catalysts, using
local materials to facilitate clean-up. The process of
breaking down materials takes a toll on all types of
environmental nanos, reducing their working lifespan
to one week (168 hours) of use. The lifespan of
environmental nanos doubles with each Tech Level
after introduction. Environmental nanos can operate for
24 hours a day for their entire lifespan.

Environmental Nanos TL

Cost per Slot
cleaned per hour
Excavation 13 Cr5000
Soil Creation 13 Cr10000
Environmental Clean-up 13 Cr10000–50000

Nanorobot Development
Specific nanorobots can be designed by an individual
with the Science (robotics) skill and appropriate
equipment, such as an enhanced fabrication
chamber and a computer running Fab Creator
software (see page 123). Creation of a custom
nanorobot swarm requires a task chain beginning
with a skill appropriate to the type of nanorobot being
developed, such as Medic, Science (biology), Science
(chemistry) or Profession (architect) and ending with
Science (robotics). Successful completion requires
a Formidable (14+) Science (robotics) check (1D
weeks, INT) and an expenditure of raw materials
equal to 1D x the cost of a completed package of
a similar type. In many jurisdictions a license as a
registered nanoroboticist is also required if the creator
intendeds to sell the resulting product. In nearly as
many jurisdictions, creating nanorobots without a
license is a criminal offense.

Nanorobot Countermeasures
Stories of nanos run amok, dissolving bodies or turning
environments into ‘Grey Goo’ are mostly fiction. The
ability to replicate nanos requires the technology to
create a fabricator capable of creating more nanos.
This sophistication is not available until at least
TL18, beyond the capabilities of Charted Space.
Ironically, larger robots with fabrication chambers could
accomplish this as early as TL13 but this does not
cause as much fear in the general public.

Special Robots and Other Synthetics

TRAVELLER

Nanos can however be created with destructive
purposes and deployed with hostile intent. These include
medical nanos designed to damage a body, effectively
turning a single person into grey goo or excavation
nanos set loose to destroy a building or fortification.

There is little defence against tailored medical nanos
already inside a body, as they are designed to operate
autonomously, but there are many simpler ways to kill a
person. Aggressive counter-nanos could be developed
to fight the damaging nanos or other nanos could
work to repair damage, in either case leading to a war
inside the person’s body that may have additional side
effects. Prophylactic nanotech defence packages are
medical packages that can provide DM+1 to resist
nanotech infections. Unlike characteristic enhancement
packages, these packages stack linearly.

Against excavation nanos, which could theoretically
also dissolve a body, there are two lines of defence:
First, an excavation nano requires a swarm controller,
which could be disabled, jammed or spoofed;
second, regulated nanos require two failsafes, one
of which is a shutdown signal, the other a failure
of communications, although this may be a timed
check-in feature of up to an hour duration to allow for
momentary signal loss and work beyond the standard
50-metre range. Either preventing communications
or transmitting a failsafe message shuts down hostile
nanos. Another method is even lower tech. A nano is
a very small machine. Simply vacuuming them up or
opening an airlock door into a vacuum environment
prevents them from operating.

Androids
An android or ‘pseudobiological’ robot is a
mechanical robot encased in a chassis made to
emulate a biological being. The sophistication of
this physical emulation increases with Tech Level
but appearance alone does not make an android
emulate a biological being. Something that looks
biological but acts mechanical can cause unease,
known as the ‘uncanny valley’ effect among humans.
Truly emulating a biological being has as much to
do with the behavioural features associated with
the sophistication of the robot’s brain as it does the
appearance of the robot’s body.

ANDROID PROPERTIES
When first introduced at TL8, an android suffers greatly
from the uncanny valley effect, especially when the
robot does ‘not look quite right’, which leads to DM-2
on all checks involving social interaction. The uncanny
valley decreases as Tech Levels and costs rise,
allowing an android at TL14 with a Very Advanced brain
to pass as a member of its emulated species.

Oddly, androids can avoid the DM-2 uncanny
valley effect if they are intentionally designed to
appear ‘cartoonish’ with simplified, clearly fictitious
or exaggerated features and expressions; this
prevents people from feeling confusion or unease
over the android’s less-than-perfect affect and
expressions. Even with this accommodation, some
may react negatively to such androids, experiencing
automatonophobia, a psychological condition similar to
coulrophobia, the fear of clowns.

The android has obvious size and locomotion
limitations imposed by the species it is emulating.
For human emulators, this restricts the robot to Size
5 and walker locomotion, although smaller ‘child’
emulators or larger ‘giant’ versions are possible. The
android has no armour by default and can only add up
to two Slots of armour below its surface to retain its
emulated shape and range of motion. Unless otherwise
specified, armour or any chassis-spanning coating
or environmental protection must be added during
construction. Clearly, options such as reflec coating
spoil any attempt to pass as biological.

The android modification requires 50% of a robot’s
Base Slots. In addition to the cost per Base Slot
for an android modification, a 3x cost modification
applies to the entire physical makeup of the robot:
chassis, modifications and options, including the
listed android cost per Base Slot, the robot’s brain
and any Bandwidth or INT upgrades or hardening.
Only the android’s skill packages are not subject to
this multiplier.

The properties of the android and the minimum brain
requirement to achieve the proper level of emulation
are noted on the Androids table. If an android’s brain is
below the minimum complexity indicated, the android’s
ability to pass and conduct social interactions suffers a
further DM-2.

The self-repairing property provides the same effect as
the self-repairing chassis option and ‘heals wounds’ at
a rate similar to natural healing.

Special Robots and Other Synthetics

**ANDROID ROBOT LEGAL RESTRICTIONS**
Within the Third Imperium, many member worlds
model their robot regulations upon the Shudusham
Concords. The 37th Amendment to the treaty
specifically prohibits ‘pseudobiological robots’ from
presenting themselves as living beings. On some
worlds, this prohibits the building, importation or
operation of androids. On others it requires clear
marking such as colouration, skin patterns or clear
distinctions from local biologicals. Some worlds make
exceptions for registered body doubles. Legally,
the Concords have had no enforceability since the
foundation of the Third Imperium and many worlds
have no restrictions on androids at all. On high-
tech worlds where androids are banned or heavily
regulated, a black market often exists.

Biological Robots
A biological robot or ‘biobot’ is a living organism, albeit
one that may have been grown in a vat and implanted
with an electronic brain inside its bony skull.

At TL16, an advanced fabrication chamber can
‘print’ a biological being but at lower Tech Levels,
a biological entity must be genetically designed,
either from a natural or modified template or from
an entirely artificial genome, then grown, usually in
a large bioreactor or vat. This process is similar to
one used for growing clones and subject to the same
considerations and effects if an organism is created
quickly, rather than by cell division and growth.

**Androids**

Android TL Minimum Brain Properties Cost per Base Slot
Basic 8 Basic (x) or
Hunter/Killer

Barely emulating. DM-2 on all social interactions from
uncanny valley effect.

Cr1000

Improved 10 Advanced Natural-looking. Passes at a distance but uncanny
valley DM-2 within 5 metres.

Cr2000

Enhanced 12 Very Advanced Natural-looking; Invisitech. Passes in close interaction,
but on a roll of a natural 2 the uncanny valley sets in.

Cr5000

Advanced 14 Very Advanced Natural-looking; Invisitech; Self-repairing. Can pass as
a biological being unless scanned.

Cr10000

Superior 16 Self-aware Natural-looking; Invisitech; Self-repairing. Can pass
even after most scans.

Cr20000

Special Robots and Other Synthetics

TRAVELLER

BIOLOGICAL ROBOT PROPERTIES
All biological robots have ‘Natural-looking’ and ‘Self-
repairing’ properties – meaning healing, not the
chassis repair option, although that option can be
added separately. The interface between a biobot’s
robot brain and its biological body is detectable,
especially at lower Tech Levels. A biological robot
requires the biological body option.

As with an android, the biological robot option triples
the physical cost of the robot, up to and including the
brain and its modifications. The biological robot option
requires 75% of a robot’s Base Slots and limits the
robot to ‘natural’ locomotion modes, which should
match the organism being emulated. This usually
results in a walker configuration, although aquatic and
flight modes are possible as a primary or secondary
locomotion type if the biology supports it.

Much like an android, a biological robot requires a
minimum brain configuration to avoid an uncanny valley
DM-2 to social interactions. The biobot’s body may be
natural but its reactions will be stiff and appear artificial
if the brain requirement is not met. Automatonophobes
tend to react negativity to a known biological robot,
even if it appears entirely natural.

Standard robot endurance values do not apply to
biological robots; they must eat, drink and breath
just like a living being. Coatings and environmental
protections are not available unless they are part of a
biobot’s genome. Starting at TL13, biobots are often
based around quick-grown clones and suffer the same
lifespan limitations. A biobot may use any personal
augmentations from the Central Supply Catalogue
(pages 86 –93) or from the Cyborgs section of this
chapter at the same cost and effects as a normal
biological being.

Biological Robots
Biological
Robot TL Minimum Brain Properties

Cost per
Base Slot
Basic 11 Basic (x) or
Hunter/Killer

DM-2 on all healing checks. Emissions from the
electronic brain or interfaces are detectable by attuned
scanners and by any psionic life detection.

Cr2000

Improved 13 Advanced Treat detection of an artificial brain as DM-2 on any
scanner check, including psionic life detection.

Cr5000

Enhanced 15 Very Advanced DM+2 on all healing checks. DM-4 on any scanner
check, including psionic life detection.

Cr10000

Advanced 17 Self-aware DM+4 on all healing checks. Indistinguishable from a
fully biological being, even psionically.

Cr20000

In civilisations focused on biological sciences and
adept at biotechnology, the TL for biobot features can
be reduced by two to four levels at the discretion of
the Referee, but minimum brain restrictions (and those
brains’ minimum Tech Levels) still apply.

BIOLOGICAL ROBOT LEGAL RESTRICTIONS
Legal restrictions applying to androids generally
apply equally to biological robots, although in certain
jurisdictions clever legal arguments using ambiguities
present in the original wording of the Shudusham
Concords’ 37th Amendment allow for loopholes
excluding biobots from these restrictions.

Cyborgs
A cyborg is any biological being with a robotic
component. In common parlance, a cyborg is the
converse of a biological robot; whereas a biological
robot has a robotic brain and a biological body, a
cyborg has biological brain and a robotic body in part
or in whole. However, in some instances, an essentially
biological robot may have a cybernetic part. While
in principle a biological robot could have a full-body
cyborg chassis, this is a very expensive and convoluted
method for creating a standard robot, incurring triple
costs for no gain.

Standard cybernetic augments are treated well in
the Personal Augmentation section of the Central
Supply Catalogue on pages 86–93. These rules do
not invalidate the guidelines and items presented in
that section but allow for greater detail in designing
custom cybernetic components and the implications
of their usage.

Special Robots and Other Synthetics

Cybernetic augments include various implants and
body part enhancements or replacements up to and
including a full body ‘brain-in-a-jar’ replacement of
nearly every biological component of a body. While
cybernetics may provide benefits to the Traveller, they
also create challenges for the recipient of a legal,
physical and mental nature.

**CYBERNETIC INTERFACES**
In many cases, the most sophisticated and expensive
portion of a cybernetic augment is not the cybernetic
part itself but its interface to a living being. Links to
brains and peripheral nerves to allow cybernetics
to function require complex electronics and delicate
installation procedures. Normally these interfaces are
used to connect the brain to a cybernetic limb or sensor
but can connect to other devices, whether internal or
external to the body.

An individual may install an unlimited number of
cybernetic interfaces but a cyborg with many augments
can substitute disparate interfaces by implanting a TL13
neural link and biological-initiated avatar control system
(BIACS) as a master controller to allow management of
all augments connected to the cyborg’s body.

**Cybernetic Limbs Interfaces**
Cybernetic limbs require a limb interface for each
cybernetic limb controlled by the brain. The interface
is an implant that allows mental control of the limb but
limits the DEX of the limb. The actual DEX of a limb
is constrained by the lower of the controller’s rating
or limb’s DEX. Starting at TL10, cybernetic limbs and
interfaces include full haptics, providing sensations
indistinguishable from a natural limb. Also, at TL10 and
beyond, cybernetic limbs are powered by the energy of
the biological body itself.

**Cybernetic Arms**
A cybernetic arm is designed like a robot manipulator.
For human arms at TL10 and below this is a Size
6 manipulator; at TL11+ it is a Size 5 or smaller
manipulator. Costs for an arm are triple the equivalent
of a robot manipulator of the same characteristics,

Limb Interface TL DEX Limb Endurance Cost
Basic 8 6 300 hours Cr20000
Improved 10 10 Infinite Cr10000
Enhanced 12 12 Infinite Cr20000
Advanced 14 15 Infinite Cr50000

including the cost for its Size and any increases to
STR or DEX from the Manipulator Characteristics
table on page 26. The arm itself has three available
Slots for options, including additional armour and
internal fittings such as tools and weapons. For
options such as coatings that consider the limb as a
whole, an arm is treated as having four Base Slots,
similar to a Size 3 robot. Options are available at
standard prices and not subject to the 3x rule for the
arm itself but all costs for the structure, capabilities
and interface of a cybernetic part are subject to
percentage increases from the Other Cybernetic
Options table on page 93 for additional optional
features such as Detachable or Natural-looking.

An example TL8 arm with STR 12 – one more STR
than standard for a Size 6 manipulator – costs 6
x Cr100 + 1^2 x Cr100 or Cr700 multiplied by 3 for
Cr2100. Add Cr20000 for the limb interface and the
arm has STR 12 and DEX 5 for Cr22100. To increase
the DEX from 5 to 7 add 3 x Cr200 x 2^2 or Cr2400,
which brings the total cost to Cr24500.

A TL11 STR 15 arm, a Size 5 equivalent, costs three
times 5 x Cr100 + 6^2 x Cr100 or 3 x Cr4100 equals
Cr12300 plus the cost of the limb interface, assuming
an unchanged DEX value of 7 at TL11.

Cybernetic Legs
A human-sized cybernetic leg is larger than an arm,
treated in construction cost as a Size 6 manipulator
regardless of TL. The leg also carries the triple cost
multiplier for cybernetics. Otherwise, the limb is
treated as having four available Slots and six Base
Slots. The DEX of a leg is not normally adjusted but
for Agility (dexterity) checks requiring the movement
of legs, including dodging, balancing and zero-G
movement, the leg’s DEX is equal to the standard
value of TL ÷ 2 +1 with increases priced as with any
Size 6 manipulator.

For purposes of running, when both legs are
cybernetic, movement speeds beyond the standard
rate (six metres for humans) can be achieved in the
same manner as a STR increase – as less fine motor

Special Robots and Other Synthetics

TRAVELLER

skills are necessary – at a cost equal to the increase
from six squared times Cr100 times the Size (6) of
the leg. The total movement rate is limited by the DEX
level of the limb interface. For example, to build human
cybernetic legs capable of a movement rate of 12
metres would require one enhanced interface per leg
and 3x (Cr100 x 6^2 + 600) or Cr12600 per leg.

CYBERNETIC LIMB CONSIDERATIONS
For tasks where natural limbs and cybernetic limbs
have differing characteristics, tasks performed solely
by the artificial or natural limb use the characteristics
of the limb in question, but for those requiring the use
of multiple limbs, the average of the limbs in question
controls the modifier to STR or DEX. END is not
modified by cybernetic limbs, unless both legs are
cybernetic, in which case for walking or running tasks it
is effectively END 15.

Custom limbs require time and effort to locate. Clinics
may charge a considerable surcharge and waiting
times may stretch into weeks, although the installation
procedure itself generally takes only a day. A recipient
needs 1D weeks to become fully comfortable with
the use of the cybernetic limb if it varies in size or
performance from the natural limb. If a limb is added,
such as a third arm, this acclimation period is doubled.

A cybernetic limb interface may also connect to a
device that is neither limb, sensory or organ, such as
an implanted computer or tool via internal artificial
nerves. A physically connected object may be as
large as a limb; a Traveller could control a chainsaw
in addition to or instead of their arm with a limb
interface if desired.

If the limb interface is connected to a wireless data
link or transceiver, the Traveller could cybernetically
control external tools with similar complexity to a limb.
For example, the Traveller could control a crane but
controlling a vehicle requires a more sophisticated
interface such as a drone or avatar controller and
Electronics (remote ops) skill.

Control of multiple non-limb devices is limited by
the same rules as performing multiple actions or
using multiple skills, with each additional external
use increasing task complexity by one level for all
simultaneous tasks. This does not include control
over a ‘standard’ number cybernetic limbs, sensors or
organs attached to the controller’s body.

Cybernetic Senses
Cybernetic senses begin with relatively simple
hearing devices such as cochlear implants, proceed
to artificial eyes of increasing resolution and range,
and include the most complex sensors of all,
cybernetic olfactory sensors.

Cybernetic Sensory Interfaces
Cybernetic senses require two components, a
cybernetic interface to the brain and the augment itself.
Interfaces can control only one sense but may control
more than one sensor, for instance one interface may
control two eyes, while another may control two ears.
Additional sensory input beyond what is ‘normal’ for a
species requires one additional interface per sensor to
help interpret unaccustomed stimuli. These additional
interfaces – for instance one controlling a third eye,
even if the other two eyes are natural – costs twice as
much as the standard interface of that type.

Sensory Interface TL Cost
Auditory 7 Cr2000
Visual 8 Cr10000
Olfactory 9 Cr10000
Taste 9 Cr10000

Cybernetic Sensor Implants
Auditory (ear) and visual (eye) sensors are available
individually but the olfactory sensor (nose) is a single
sensor unit. A cybernetic tongue sensitive to taste
is available at the same cost and sensitivity as a
cybernetic nose. Standard ranges and capabilities
refer to human options; other races, such as Vargr,
may require more advanced technology to match their
natural capabilities.

Special Robots and Other Synthetics

**Cybernetic Organs**
Replacement of organs with mechanical devices
has a long history but a narrow application. In most
cases, biological alternatives, such as transplants
or regenerated organs, are the preferred method for
replacing a destroyed or damaged organ. In some
cases, such as lack of availability of transplanted parts
or taboos against transplantation or cloning, artificial
organs become the best available option. Cybernetic
organs do not require special interfaces.

At TL7 basic cybernetic organs become available but
these require external power sources or battery packs,
limiting mobility. These primitive organs have a high
degree of failure. Implantation is a Very Difficult (12+)
Medic (1Dx4 hours, EDU) procedure, with a negative
Effect indicating the dice of damage sustained by the
patient. Any positive Effect may act as a DM to the
weekly 6+ END check required to remain healthy.
Negative Effects from this weekly roll equal damage
sustained from a failing or malfunctioning device. This
damage can be healed with medical care. At TL8 these
basic organs are more reliable, allowing DM+2 on both
implantation and weekly survival rolls.

Cybernetic Ear (each) TL Effect Cost
Basic 7 Standard hearing range (20 to 20,000 hertz) Cr1000
Improved 9 1 to 100,000 hertz, low volume, Heightened Senses Cr5000

Cybernetic Eye (each) TL Effect Cost
Basic 8 Low resolution vision; DEX -2 Cr5000
Improved 10 Standard resolution vision Cr10000
Enhanced 13 Binocular zoom, IR and Light Intensifier, IR Vision Cr10000
Advanced 14 PRIS Vision, IR/UV Vision Cr20000

Cybernetic Nose or Tongue TL Effect Cost
Basic 9 Crude olfactory sensor Cr5000
Improved 11 Vargr-level sensitivity, Heightened Senses Cr10000
Advanced 13 Trace chemical detection, Heightened Senses Cr20000

At TL9 reliable internally powered artificial organs
become available. These still require a Difficult
(10+) Medic (1D hours, EDU) procedure to install
with the same risk of damage from negative Effects
but, if successful, the organ functions without risk of
malfunction, although they require annual maintenance
like a robot.

At TL11 and above, organs become self-repairing
and require an Average (8+) Medic (1 hour, EDU)
procedure to install. By TL13 advanced artificial
organs are superior to the natural and grant the
recipient an overall END +2; this increase is only
applied once, not once per organ.

Each organ requires a separate cost and procedure,
even if linked. For instance, a heart and double lung
transplant requires three organs and three procedures
but if installed during the same set of procedures, the
recipient only requires one weekly END roll with DM-1
for each additional organ. Cost assumes a major organ
such as a heart or lungs. Simpler organs such as a liver
or kidney cost half this but incur the same risks.

Cybernetic Organ TL Effect Cost
Basic 7 Procedure: (12+); Weekly survival: 6+ END; external power required Cr50000
Improved 9 Procedure: (10+) Cr50000
Enhanced 11 Procedure: (8+); Self-repairing Cr100000
Advanced 13 Procedure: (8+); Self-repairing; END +2 Cr200000

Special Robots and Other Synthetics

TRAVELLER

Neural Implants
A Traveller may implant a computer or mobile
comm and link it to their brain. At TL10 this implant
can operate as a mobile comm, a short range (five
kilometre) transceiver/wireless data link unit that can
be operated by thought or subvocalisation. Standard
neural comms are detailed in the Central Supply
Catalogue, page 91.

The short-range comm can be updated to include Zero-
Slot transceiver upgrade communications options, such
as an encryption module, by adding triple the standard
cost of the option to the cost of the neural comm. No
more than five Zero-Slot options can be added to the
neural comm, all at triple cost. At TL15 the advanced
neural comm can be upgraded to Computer/2
functionality at an additional Cr10000.

More advanced than a neural comm is a neural link,
which introduces motor control through a complete
neural lace. The initial implant is available at TL13 and
includes all the features of the TL12 neural comm. A
Traveller may not have both a neural comm and neural
link installed simultaneously; the upgrade process
involves replacement of the neural comm. As with the
neural comm, the transceiver can be upgraded, as can
the computer at TL15 and up to five Zero-slot triple
cost options can be added. The neural link allows use
of Expert systems for physical skills and provides a
mechanism for remote control of the Traveller’s body in
a manner similar to a drone interface.

Neural Comm TL Effect Cost
Basic 10 Neural Comm: Audio, 5km comm, wireless data link Cr1000
Improved 12 Neural Comm: +Visual, Computer/0 Cr5000
Advanced 14 Neural Comm: + Full sensory, Computer/1 Cr20000

Neural Link TL Effect Cost
Basic 13 Neural Link with Neural Lace + Neural Comm (improved) Cr30000
Improved 14 Neural Link with Neural Lace + Neural Comm (advanced) Cr45000

Robot Brain Implants
Even more advanced than the neural link is the robot
brain implant. A robot brain installation requires a neural
link. The implant is a brain with at least Advanced
complexity and can communicate directly with the
Traveller’s brain, normally in a conversational manner,
but optionally through the installation of a remote-
initiated biological avatar control interface (RIBACI)
between the brains. A robot brain implant is size-limited
and cannot include a brain bandwidth upgrade until two
Tech Levels beyond its indicated Tech Level.

Miscellaneous Cybernetics
Other devices may be implanted in a biological body
and attached to the brain for control. For simplicity,
these devices require a cybernetic interface equivalent
to a limb interface or can be controlled by an existing
neural link. The devices themselves cost three times as
much as a standard version of such devices and may
not be larger than one Slot or two kilograms each. No
more than three such devices can be implanted.

Full-body Cybernetics
The ultimate in cybernetics is the so-called ‘brain-in-
a-jar’ or ‘brain-in-a-box’ full body replacement. In this
scenario, a biological brain is placed within a robot body.
This procedure is inherently dangerous and can cause
lasting psychological harm even if entirely successful. The
procedure is only available at TL12 and above, and is
illegal on many worlds and frowned upon on most others.

**Robot Brain Implant TL Brain Cost**
Basic 13 Advanced, Bandwidth 2, INT 8 Cr100000
Improved 14 Very Advanced, Bandwidth 3, INT 9 MCr1
Enhanced 15 Very Advanced, Bandwidth 4, INT 10 MCr1.5
Advanced 16 Very Advanced, Bandwidth 5, INT 11 MCr2
Special Robots and Other Synthetics

Full-body Cyborg TL Slots Survival Degradation Check Cost
Basic 12 3 Formidable (14+) Monthly INT 4+ MCr1
Improved 14 2 Very Difficult (12+) Annually INT 5+ MCr2
Advanced 16 2 Difficult (10+) Annually INT 3+ MCr5

Survival indicates the difficulty of the Medic (1Dx4
hours, EDU) check related to the implantation
procedure. A Science (robotics) (one hour, EDU)
check of one degree lesser difficulty during robotic
body preparations can be added to a task chain.
Failure with Effect -1 indicates an abortive procedure
that may be attempted a second time; failure with
Effect -2 or greater results in brain damage causing
a permanent decrease of INT and EDU equal to the
Effect, distributed between those characteristics and
DM-2 on any subsequent attempts. A failure with Effect
-6 results in irrevocable brain death.

Degradation Check indicates the long-term viability
risks of the transplant. The recipient must roll as
indicated to avoid permanently losing one point of
INT or EDU, determined randomly. If the optional
STY characteristic is used, the recipient must make a
second check to avoid also losing one point of STY.
INT and STY modifiers apply to these checks.

Cost includes all interfaces to the robot body but
not the robot body itself. The robot may be anything
from a Size 2 box to a humanoid robot to a vehicle
or spacecraft. Major deviations from the basic limb
structure of the original biological body impose DM-2
to the Degradation check. Major deviations include
replacement of limbs with other forms of locomotion but
only if legs are no longer present. For instance, adding
grav locomotion while retaining walker mode does not
incur this penalty.

**Other Cybernetic Options**
Cybernetic augments may add options listed on page
93 of the Central Supply Catalogue. For completeness,
this section is summarised below.

The detachable option is only available to external
cybernetic augments. It allows the Traveller to
disconnect the augment using a specialised socket.
This can be done for storage, disguises or to allow
multiple augments to fit into the same socket. The
disconnection process requires a Significant Action, as
does reconnection.

Other Cybernetic Options
Item TL Cost
Detachable 9 Cr5000, +25% of augment
Invisitech 12 +100% of augment
Invisitech 16 +200% of augment
Natural-looking 10 +25% of augment
Natural-looking 14 +75% of augment
Ruggedised 8 +25% of augment
Self-repairing 14 +100% of augment

An augment with invisitech is made from materials
that do not trigger a scanner, sensor or mechanostatic
listener. Other than medical examination or direct
contact with the augment, there is no electronic way
to sense its presence. At TL16, invisitech also foils
psionic scanning such as clairvoyance.

A natural-looking augment is constructed like an
android component with a layer of synthetic skin
and hair over a cybernetic augment to make it seem
more organic and lifelike at a passing glance. This
option helps the augment blend in with the rest of
the Traveller’s body, granting DM+2 to all Deception
checks made to hide the nature of the augment. At
TL14, this bonus is increased to DM+4.

All circuitry and electronic components of a ruggedised
augment have been hardened. This makes the
augment immune to energy-based weaponry targeting
augments specifically or which cause adverse effects
based on the presence of cybernetic augments, such
as electromagnetic grenades and ion weapons.

A self-repairing augment uses nanomachines to
allow an augment to heal ‘naturally’ instead of
requiring special attention by a cyberneticist. It does
not provide the same protection as the self-repairing
chassis option.
Special Robots and Other Synthetics

TRAVELLER

In addition to the options listed above, a detachable
augment can be made able to operate separately
from the Traveller’s body for Cr10000 to install a
remote interface. Additionally, this augment may add
a grav locomotion option, allowing the augment to be
controlled while detached and operated as a grav-
propelled object capable of six metres of movement
per Minor Action. This movement range is restricted
to the communications range between the augment’s
interface and the augment itself, which is a 50-metre
wireless data link, unless both transmitter and receiver
have installed transceivers.

All options that add capabilities to an augment are
additive if indicated with a percentage cost and include
increases to the interface cost but all added fixed costs
are computed prior to the percentage increases.

Item TL Cost
Remotely-operated
detachable augment

11 Cr10000

Grav-propelled
detachable augment

13 +200% of augment

AGENT WAFERS
Normally, a wafer jack expert system allows
aided control to enable the user to accomplish
physical tasks based on the Expert skill
installed. It supplements control of the
user’s consciousness but does not override
it. Optionally, specialised agent wafers can
allow a temporary overwrite of a recipient’s
conscious state. To use an agent wafer, the
recipient must have a TL13 or higher wafer
jack (page 92 of the Central Supply Catalogue)
and at least a basic neural link.

The process that creates an agent wafer
is destructive, destroying the brain while
scanning it, and the overall effect on the
recipient of an agent wafer is temporary,
lasting 30 days before the recipient’s
personality reverts. Agent wafers can only be
created in specialised government facilities
and commercial use is prohibited, as the
process invariably kills the person whose brain
is recorded.

Special Robots and Other Synthetics

Avatars
In addition to controlling drones, a robot equipped with an
avatar controller may control a robot by initiating a copy of
its personality and at least some of its programming. This
receiving robot is usually referred to as an avatar host.
Additionally, avatar controllers, devices and interfaces
are available to allow biological beings to be both avatar
controller and host.

**Avatar Controller**
The avatar controller is a more immersive version of
a drone interface, allowing the controller to have full
presence and ‘become’ the target avatar. At higher Tech
Levels, a robot may control multiple avatars. Unlike
drones, these avatars can operate independently,
performing tasks without the intervention of the robot but
still part of its linked mind. As such, avatars do not suffer
a negative DM for performing tasks independent of their
controlling agent.

The recipient avatar host must have at least an
Advanced brain and can run any skill package available
to the controlling brain, subject to the host’s own
Bandwidth limitations. The avatar controller requires a
transceiver and provides a real-time feed between the
linked robotic brains. The controlling robot must have at
least an Advanced brain and may only have one avatar
controller installed.

Avatar
Controller TL Slots

Maximum
Avatars Cost
Basic 11 2 1 Cr50000
Improved 13 1 2 Cr200000
Enhanced 14 1 4 Cr500000
Advanced 16 1 8 MCr1

**Avatar Receiver**
A robot acting as an avatar host requires at least an
Advanced brain and must be equipped with an avatar
receiver, an option that also acts as a drone interface.
The avatar receiver is a one-Slot option available
at TL11 and costs Cr10000. To receive direction or
updated skill packages from its controller, the receiver
requires a transceiver but can buffer up to a week’s
worth of ‘experience’ to transfer back to the controller
if communication is disrupted. While acting as a host,
an avatar robot is limited to skill packages available to
its controller but various hardware options, such as a
fire control system or recon sensor may grant it ‘skills’
independent of the controller’s skill packages. The host
assumes the ‘personality’ of the controlling robot until
released from control.

Remote-Initiated Biological
Avatar Control Interface
A robot brain can assume control of a biological body
through the use of a remote-initiated biological avatar
control interface (RIBACI). Installed in the biological
host, who is often referred to as a ‘meat puppet’, this
system acts as the biological host’s equivalent of an
avatar receiver and must be installed in a host with
a neural link. The remote brain controlling the body
requires an avatar controller and can either be an
implanted robot brain within the body, a brain linked
via wireless data link connection, or a transceiver to
the controlled body.

When active, the implant allows complete control of
the actions and conscious thoughts of the recipient.
Often, the implant is installed in a quick-grown clone
with an undeveloped brain. When installed in a fully
developed brain, external control may degrade (on
a 2D roll of 12 checked daily), enabling the native
personality to reassert itself. While the implant has a
buffer to store the external brain’s personality, a brain
that fails to communicate with its biological avatar
loses control of it much more easily (on a 2D roll of 9+
daily for a developed brain). Undeveloped brains, or
those ‘wiped’ by medical intervention, are not subject
to this loss of control.

Use on a developed brain is illegal in most jurisdictions
and use on an undeveloped brain may run afoul of
regulations that prevent a machine from passing as
biological. Prolonged use on a developed brain can
lead to psychological problems. A recipient must roll
3+ for every 30 days of cumulative external control
to avoid losing one point of INT. If the optional STY
characteristic is used, a recipient must roll 4+ monthly
to avoid losing a point of STY.

Note: For more information on the Sanity
characteristic, refer to The Traveller Companion.

Item TL Slots Cost
Avatar Receiver 11 1 Cr10000

Item TL Cost
Remote-Initiated Biological
Avatar Control Interface

13 Cr100000

Special Robots and Other Synthetics

TRAVELLER

Biological-Initiated
Avatar Control System
The opposite of a robot brain controlling a biological
body is a biological brain controlling a robotic body
using a biologically initiated avatar control system
(BIACS). This implant acts as a basic avatar controller
installed in the controlling biological brain and requires
a neural link. Using the transceiver component of the
neural link, the BIACS allows remote presence in any
single robot with an avatar interface or remote control
of any robot with a drone interface.

A biological-initiated avatar experience is different
from that of robot-initiated control. The biological
‘consciousness’ is ‘suspended’ from the original body
and ‘transferred’ to the avatar, allowing the host to use
all mental and physical skills (within host characteristic
limits). The host retains any ‘hard-wired’ skills from
sensors or fire control systems. If communications
links are severed, the controller regains consciousness
and the host reverts to local control. It is also possible
for one biological to control another biological with a
BIACS to RIBACI link.

Item TL Cost
Biological-Initiated Avatar
Control System

13 Cr100000

Clones
A clone is a biological being created by artificial
means. It could be a copy of an existing individual
or naturally occurring organism, or a custom-created
version thereof.

Clones differ from biological robots in that they are entirely
biological, including their brains. However, a clone with its
brain removed is often a template for a biological robot.
Clones may be grown in a variety of ways, from natural
implantation and gestation to bioreaction chambers,
often called vats or tanks, which might accelerate the
maturation process of the organisms. Some biological
beings naturally create clones by a variety of methods
including budding and parthenogenesis.

CHARACTERISTICS
If a clone body is based on a Traveller’s genetic
code, the clone will be similar to the Traveller but not
identical. An adult has experienced both genetic and
environmental factors during growth to adulthood. To
simulate this effect, the clone is considered to have
STR, DEX, END and INT characteristics each based
on half the Traveller’s original 18-year-old value (round
down – cloning is not perfect) plus 1D. At TL13 and
above, clones can be ‘tweaked’ to ensure favourable
maturation and instead of 1D, the clone adds D3+3.

A clone has no initial EDU. A vat or quick-grown
clone gains no EDU until after emergence from a vat
unless implanted with a wafer jack and forced learning
system. An accelerated growth clone can receive basic
language skills if properly educated during an 18-month
growth period.

The SOC of a clone is dependent on the culture. In
some cultures, clones are treated as any child and
inherit the SOC of their parents. Third Imperium law
forbids the enslavement of sophont biological species
and, by legal precedence, this includes clones but
outside the Imperium’s territory (and sometimes within)
a clone is considered to be property with SOC 0,
treated no differently than a robot.

GROWTH RATE AND AGING
A clone is a biological organism and without
technological assistance will grow and develop at a rate
consistent with its species. Artificially created biological
organisms might have a faster than ‘normal’ growth rate
and some medical treatments may accelerate growth
and development.

At TL13, a ‘quick-grown’ human clone can develop
at 50x normal growth rate, maturing to age 18
in approximately 18 weeks or four months. This
technology requires an advanced bioreaction chamber
as described on page 50 or a dedicated clone vat
(see page 51). The quick-grow procedure is closer to
fabrication than development and the growing body
remains unconscious for the entire period, emerging
with all the knowledge and abilities of a new-born if
no development aids are introduced. The process
places a great strain on the clone’s cellular structure,
impacting aging to a major extent; a quick-grown

Special Robots and Other Synthetics

clone body ages at twice the standard rate. Eight
years after the clone’s emergence from the vat, the
clone is the equivalent of a 34-year-old and must
make an aging roll with DM-4, two years after that, the
clone must make another aging roll with DM-5. Most
quick-grown clones do not last much past 30 years
from their emergence from the vat.

If a clone is intended to endure for closer to a natural
lifespan, starting at TL10, the clone can be grown at
12x acceleration. This accelerated process requires
18 months or 1.5 years to grow a clone to age 18
but during that time period, the clone can maintain
consciousness and learn basic skills. This process
requires alterations to the clone’s genetic sequence
and initialisation for the first six months of its ‘life’ in
an enhanced bioreaction chamber, from which it will
emerge as a child. Constant medical attention and
access to an enhanced bioreaction chamber for the
developing clone’s sleep periods is required to achieve
full growth in 18 months. After reaching adulthood, the
clone ages at a more or less normal rate but suffers
DM-2 to all aging rolls, which begin after the second,
not fourth, term. This means that eight years after
reaching adulthood the 26-year-old accelerated clone
must make an aging roll equivalent to that made by a
34 year-old natural being but another aging roll is not
required until four more years have passed.

Clones grown at standard rates are possible as early
as TL8, reaching 18 years of age after 18 years, as
normal biological beings. These do not suffer the
advanced aging penalties. Naturally aging clones may
be implanted in a biological mother or grown to ‘birth’ in
a bioreaction chamber of at least enhanced complexity.

**REPLACEMENT PARTS**
A whole clone can be grown from an individual for
replacement parts, including a whole-body replacement
with a brain implantation as technology progresses.
Using cells from the original eliminates the chance of
rejection but a whole-body clone introduces ethical and
technical challenges.

To avoid growing a sentient being for spare parts,
a whole-body clone is usually modified during early
development to remove higher brain functions, leaving
nothing but a brain stem to keep the body alive. Such a
body remains in a comatose state even after reaching
adulthood. The very rich may grow such a body to
adulthood, then store it in a low berth until needed.

If parts from a quick-grown clone are implanted in a
normal being, they may affect the rate of aging of the
individual even if the parts are much younger than the
individual as a whole. Small organs or tissues, such as
eyes and hands, do not impose penalties but whole-
limb replacements or replacement of major organs
imposes a permanent DM-1 on future aging rolls. This
penalty does not occur if parts are harvested from a
12x accelerated growth or naturally developed clone.

Body parts repaired by regenerative medicine are not
subject to this restriction, despite them regrowing at
an accelerated rate. These parts are grown from the
patient’s own stem cells via a different process, usually
onto a framework of temporary dissolving inert material
and integrated gradually into the body.

BRAIN TRANSPLANTATION
The technology to transplant a brain into a new clone
body is available as early as TL11 but it is a dangerous
process. A successful brain transplant requires a
Formidable (14+) Medic check (1Dx4 hours, EDU).
This procedure cannot be done using the ‘Going Faster
or Slower’ rules; it is already being done as carefully
as possible. The check receives DM+1 for every TL
above 11 of the facility performing the operation. A
failed attempt results in the patient’s death; a marginal
success results in side-effects or complications of
the Referee’s choosing. If the clone body has been
genetically altered from the original or is quick-grown,
an additional DM-1 applies.

Even if successful, the end result is still an old brain
in a new 18-year-old body. This provides relative
rejuvenating effects to the brain but the Traveller’s
clone body suffers DM-1 to all aging rolls in addition
to any effects from quick or accelerated growth of the
clone body.

Special Robots and Other Synthetics

TRAVELLER

PURCHASING CLONES
Purchasing of clones can be subject to heavy
regulation. It is often illegal, frequently considered
immoral and, even when allowed, may be subject to
waiting periods for permits, which may take longer than
a quick clone maturation. As a result, a black market for
clones exists, although penalties for illegal cloning or
‘organ harvesting’ are often severe.

Costs assume use of commercially available services.
For those wishing to create clones on their own, they
can purchase a clone tank as described on page
118 or, for custom clones, Clone Creator software
(see page 122) with a cloning creche or vat robot.
In all cases, a clone requires Cr10000 per clone in
consumables to grow to adulthood.

A clone requires a template. Templates may be the
Travellers themselves, purchased from a catalogue of
preapproved genetic donors or built from surreptitiously
gathered DNA. Templates can also be created or
modified in a genetics lab using Clone Creator
software. A template requires Cr10000 from sample
collection to preparation for cloning.

Templates purchased or developed from a lab have
additional costs, beginning at Cr10000. The base
price assumes a clone with base STR, DEX, END and
INT of 1D+3, at TL13 and above, of D3+6 variation.
Adding more points to any characteristic costs an
additional amount as indicated on the Template
Characteristics table.

Additional non-characteristic factors such as
exceptional appearance or for a template taken from a
celebrity may increase the cost of the clone template,
potentially by a factor of 10 or more.

Clone Technology
Clone Technology TL Description Cost per Clon e
Basic Cloning 8 Creation of embryonic clones that require natural
implantation to grow to maturity.

Cr50000 to implantation

Spare Cloning 9 Support for growth and maintenance medical clones
without higher mental functions.

Cr50000 to initialise +
Cr12000 per year for storage
Accelerated Cloning 10 Initialisation of clones in enhanced bioreaction
chambers for accelerated 12x growth to adulthood.

Cr200000 for 12x growth

Brain
Transplantation

11 Experimental surgery to implant a brain in a clone body. Cost of clone +
Cr200000 for surgery
Quick-grow Cloning 13 Cloning vats in advanced bioreaction chambers capable
of supporting 50x growth to adulthood.

Cr150000 for 12x growth
Cr50000 for 50x growth

TRAINING OF CLONES
Clones who develop at a natural rate are generally no
different than natural children and develop accordingly,
reaching maturity at age 18 with base EDU skills
determined as a natural Traveller.

Clones grown at 12x acceleration mature in 18 months
and spend a year of that time in a creche, learning
basic skills at an accelerated rate. The ability of clones
to learn in a creche setting is dependent on their INT. A
creche-raised clone acquires an EDU equal to half its
INT (round up) and four level 0 skills. Two level 0 skills
can be subsisted for a level 1 skill. Additional creche
training costs Cr20000 and adds four more level 0
skills per year. It can be continued beyond the first year

Template Characteristics
Characteristic
Base Variance TL Additional Cost
3 +1D 8 Cr0
4 +1D 8 Cr5000
5 +1D 8 Cr15000
6 +1D 9 Cr30000
7 +1D 10 Cr50000
8 +1D 12 Cr75000
6 +1D3 13 Cr0
7 +1D3 13 Cr5000
8 +1D3 13 Cr15000
9 +1D3 13 Cr30000
10 +1D3 14 Cr50000
11 +1D3 15 Cr75000

Special Robots and Other Synthetics

up to a total of 16 years. For clones who spend many
years in creche learning, the force-growth process can
be terminated early, leaving a clone as young as six
apparent years after six months and aging normally
thereafter. The clone still suffers the same aging
disadvantages of an accelerated growth clone grown to
age 18 but exits from 16 years of creche training at the
apparent age of 22 instead of 34.

In subsequent creche training years, higher level skills
become available. Raising a skill from level 1 to level 2
requires sacrificing a further two level 0 skills, raising a
skill from level 2 to 3 requires four. Higher increases are
available as noted on the Creche Training table. Level
0 skills can be ‘saved’ from year-to-year to achieve
higher training.

**Creche Training**

Skill Level

Incremental Skill
Cost

Cumulative Skill
Cost

Incremental
Characteristic Cost

Cumulative
Characteristic Cost
0 1 1 0 0
1 1 2 2 2
2 2 4 4 6
3 4 8 8 14
4 8 16 16 30

STR, DEX, END and INT can be increased but require
an additional two level 0 skills as indicated on the
Creche Training table. EDU is a special case; until it
reaches the level of INT, it increases as if two level 0
skills had been spent on it per year. Further increases
follow the Creche Training table, starting at 0.

Clones grown at 50x mature in four months and
have no EDU or skills at maturation. They may be
trained in creches at the same rate as their slower
grown counterparts, or fitted with wafer jacks for skill
augmentation, although this will not confer EDU.

Once ‘graduated’ from a creche, a clone gains skills
and experience the same as any Traveller.

Special Robots and Other Synthetics

TRAVELLER

CLONES AS TRAVELLERS
Clones can be treated as biological Travellers in most
instances. Rather than random creation, clone design
procedures determine characteristics and creche
learning substitutes for default skills.

The clone’s SOC depends greatly on their upbringing
and society. A clone raised as a normal child has
the SOC of its parents, potentially generated by 2D
if cloning is available to everyone, or 1D+7 if it is
something only the rich can afford. While enslavement
of a clone is technically illegal in the Third Imperium,
if clones are considered property their SOC is 0. If
clones are ‘indentured’ their SOC is 1 or 2. If clones
are an underclass, their SOC might be determined by
1D or 2D3.

Clones, especially those raised in creches, might
join a campaign immediately or enter a career as
a normal Traveller, although certain careers or
commissions, and advancement in those careers,
might be limited. The Referee should decide whether
a Traveller can be a clone and what limitations this
places on Traveller creation.

Missile Robots
Launched from spacecraft, missiles and torpedoes are
not generally considered robots, although their status
as ‘smart’ implies a certain amount of decision-making.
Usually, this is a Primitive (homing) brain but nothing
other than expense prevents more sophisticated brains
or other options from being installed in a chassis based
on a standard missile or torpedo bus. This section
generally refers to both missiles and torpedoes as
‘missiles’; design constraints for missile and torpedo-
based robots are the same, although differences in
Size are specifically noted.

Specialised missile robots consist of two types: those
associated with the entire missile chassis and those
with just the warhead or payload.

MISSILE CHASSIS ROBOTS
A robot that includes an entire missile assembly has
both advantages and disadvantages. The major
advantage is that it can use all available Slots. This in
effect provides the robot with up to twice the available

Slots of an equivalent warhead robot, depending
on whether a warhead robot includes manipulators.
The disadvantages are that the robot can have no
locomotion mode beyond the missile’s thrusters and
any ‘whole body’ options cost considerably more since
they must cover the entire chassis. Missile chassis
robots that have a single brain must include a Pilot skill
package to allow for controlled flight. Otherwise, they
must have a robotic drone controller connected by a
drone interface to a separate built-in Primitive (homing)
or Basic (locomotion) brain in the missile chassis bus,
allowing operation of the missile locomotion system.

WARHEAD ROBOTS
If the standard warhead assembly is removed, a
missile or torpedo can act as the delivery or locomotion
mechanism for a small robot or drone payload. With
the replacement of a standard warhead assembly
with a robot, keep in mind that a whole robot body is
considered twice the ‘size’ of its available Slots, so a
payload capacity of four Slots translates into a robot
with two available Slots or a Size 2 robot. Gaining
Slots by removing manipulators or locomotion from the
warhead robot provides extra Slots but the warhead
robot is still limited to the Payload Slots of the missile.

Warhead robots intended for independent operation
must have a separate brain installed. This brain may
replace the missile’s own electronics and act as the
missile’s pilot until separation, however the extra
Bandwidth required to support this set of skills is
normally only included when the missile bus requires
specialised local guidance or when it remains attached
for an extended portion of the robot’s operations cycle.
A missile-delivered warhead robot can be of any type,
even a small biological robot or a cluster of microbots
encased in a payload shroud.

SIZES
As listed in the Missile Robots table, a missile is the
equivalent of a Size 4 robot and a torpedo Size 6;
a missile can house a Size 2 robot and a torpedo a
Size 4. The separate robot can have a locomotion
method of ‘none’ if it remains attached to the missile
or torpedo bus, or is detached and left in orbit, but it
should have its own locomotion system if it intends
to move after its delivery device has expended its
propellent. Refer to High Guard pages 30-33 for
missile and torpedo performance, and assume
missiles can manage 10 rounds of propulsion at the

Special Robots and Other Synthetics

**Missile Robots**

Missile Size

Missile Chassis
Robot Size

Missile Chassis
Robot Base Slots

Payload
Slots

Warhead
Robot Size

Warhead Robot
Base Slots
Missile 4 8 4 2 2
Long Range Missile 4 8 2 1 1
Torpedo 6 32 16 4 8

indicated Thrust while torpedoes can manage 20
rounds, as would a long range missile, though its
robot carry capacity is reduced to Size 1.

The differences between missile and warhead robot
Sizes and Slots apply to coatings and other options
that might only apply to the warhead robot in some
instances, although nothing prevents such options
from being applied to the entire missile.

Removal of the warhead assembly to replace its
payload mass with a robot or drone do not confer any
savings to the cost of the delivery device. Missiles
are produced by the billions and achieve savings
through standardisation; any alteration to missiles
and torpedoes listed in High Guard on pages 30 and
32 respectively are incurred in addition to the costs
listed. Standard missiles cost Cr250000 for 12 or
Cr24000 if purchased individually. Individual standard
torpedoes cost Cr150000. Standard missile and
torpedo chassis configurations are detailed in the
Missile Robot section of the Robot Catalogue on page

249. As noted in the Locomotion section on page 17,

a space combat missile is considered a robot with the
thruster locomotion mode selected as both primary
and secondary locomotion with the vehicle speed
movement modification. This limits available Slots
for other options on the missile bus itself, however a
Default Suite and Zero-Slot options can be installed
on both bus and warhead.

Note that High Guard missiles and torpedoes could
have their Primitive brains upgraded while leaving the
rest of the warhead assembly unalerted. This could
confer advantages, including allowing the missile’s
brain to ‘pilot’ the missile with a Pilot (small craft) skill
package but could also lead to unfortunate incidents
associated with thinking explosive devices who get
ideas of their own.

Item TL Cost per Vehicle Space
Vehicle Brain
Interface

10 Cr1000

Vehicle Brain
Interface Retrofit

10 Cr2000

Vehicle Brains
A vehicle designed using the Vehicle Handbook can
have a robot brain installed instead of a computer. In all
respects, the vehicle then becomes a very large robot.
A robot brain and any Bandwidth upgrade options are
Space 0 options on vehicles.

Vehicle Brain Interface
A vehicle brain interface is required to provide full
haptics to the robot brain and allow the robot to ‘be’
the vehicle. These interfaces provide direct control to
the vehicle’s systems and cost Cr1000 per Space of
the vehicle if installed during vehicle construction or
Cr2000 per Space if retrofitted to an existing vehicle. A
retrofit requires one hour’s labour per Space. The work
can be performed by Travellers skilled in Electronics
and Mechanics but requires replacement and spare
parts, saving the Travellers only Cr100 per Space.

A vehicle brain interface cannot be replaced by
a vehicle’s drone actuation system (see Vehicle
Handbook, page 67–68), although the drone actuation
system can act as a drone interface, allowing a brain
equipped with a robotic drone controller to control the
vehicle using Electronics (remote ops) like a drone. The
vehicle brain interface is more integrated, allowing the
robot to ‘be’ the vehicle (much like an avatar) without
requiring any other control interfaces or skills. However,
to drive with any skill, the robot should either have the
appropriate vehicle skill or a vehicle autopilot installed.

Special Robots and Other Synthetics

TRAVELLER

Vehicle Brain Robots
If a vehicle brain requires any options of its own
besides a Bandwidth or INT upgrade, or hardening,
it must be encased in a small robot body. This robot
can be as small as Size 1 and does not require its own
manipulators or locomotion, gaining it as many as four
Slots even at Size 1, and does not require any special
interfaces to the vehicle if a vehicle brain interface
is installed. A robot of Size 4 or smaller requires no
Spaces but robots of Size 5 or greater require Spaces;
see the Robot Size table on page 13 and use the
Equivalent Vehicle Spaces column, rounding up. A
robot wishing to use the vehicle as an avatar can only
do so if a vehicle brain interface is installed.

Vehicle Manipulators
Vehicles of four or less Spaces may use the Vehicle
Robot Manipulator Installation rules in this book but
larger vehicles use the manipulator options present in
the Vehicle Handbook on page 59.

Ship’s Brains
In addition to a standard computer, a spacecraft or
station may have an installed robot brain of Advanced
or greater capability. Nearly universally referred to as
a ‘Ship’s Brain’ this robot brain is installed in its own

Ship’s Brain Interface
For direct control of a ship’s systems, the ship’s brain
requires interfaces with the entire ship. This option
needs a hardwired connection on the robot chassis
and occupies no additional ship tonnage, although it
requires Cr5000 per ton of the ship’s hull to install. A
retrofit requires one person day per five tons to install
and increases the cost to Cr8000 per ton with a saving
of Cr1000 per ton if performed by skilled Travellers
instead of paid labour.

For an additional Cr2000 per ton the interface can
include full haptics, allowing the robot brain to ‘feel’ the
operation of the ship, providing an effective DEX equal
to the brain’s TL for any Pilot checks or operation of any
manipulator-like ship’s systems such as grappling arms
or cargo cranes.

A ship’s brain can use skill packages to perform any
task a crew member can perform from a console station
much like Virtual Crew software. This includes piloting,
sensor operation, communication, gunnery and routine
engineering tasks, but not repairs or maintenance.
Even with the interface, unlike a robot vehicle brain,
the ship’s brain is not fully integrated with locomotive
and electronic functions. A ship’s brain must use the
appropriate Pilot skill package to fly the spacecraft and
the appropriate Electronics or Engineer skill to operate
bridge or engineering systems remotely, although
simple functions such as direct voice communication
are possible through the ship’s internal systems without
any special skill. Using the interface, the ship’s brain can
operate internal and external doors, including airlocks.

Non-Interface Brain Configurations
It is possible to forgo the cost of the ship’s brain
interface and construct a ship’s brain that interacts with
the ship solely through the use of drones or avatars.
These are subsidiary robots associated with a robot
that need not be tied into the ship itself. The resultant
computer brain is not truly a ship’s brain and cannot
use the ship as an avatar. In this case, the brain uses
a robotic drone controller to communicate with a drone
interface plugged into a ship’s workstation or computer.
Operations require the Electronics (remote ops) skill.
It may use the ship’s systems to communicate and
receive sensory input but does not have direct control
over any ship’s systems. It must use drone or avatar
robots to operate equipment.

Ship’s Brain Interface
Item TL Cost per ton
Ship’s Brain Interface 10 Cr5000
Ship’s Brain Interface Retrofit 10 Cr8000

- Full Haptics 10 +Cr2000

chassis, often integrated into the bridge or computer
control room without locomotion and manipulators but
includes a modifiable Default Suite and any available
robot options for a robot of its Size. A ship’s brain
chassis of Size 6 or smaller requires no displacement
tonnage but a chassis of Size 7 requires 0.5
displacement tons and Size 8 requires one ton; double
this requirement if the robot has manipulators and an
installed locomotion option.

Special Robots and Other Synthetics

It is also possible to install a ship’s brain in place
of the ship’s computer. This robotic brain must run
all ship’s functions as programs in addition to any
robotic skill packages but does not require interfaces
to the ship’s systems to run ship software. It has
access to ship’s communications and sensors, and
can operate doors but requires drones or avatars to
perform most ship’s tasks.

**Operational Considerations**
Any ship’s brain with interfaces can run standard
spacecraft software packages if it has available
Bandwidth. These packages do not provide
additional functionality. For example, to perform
a jump, a ship’s brain running Jump/1 must use
Bandwidth 5 to compute the jump and must keep that
program in memory while running an Astrogation skill
package to complete the jump calculations then, with
the Jump/1 program still running, use an Engineer
(j-drive) skill package to perform the jump. However,
a ship’s brain running Fire Control/1 software can
fire one turret without a Gunner (turret) skill package,
as the Fire Control/1 software directly allows for the
operation of one turret.

**Drone Control**
A ship’s brain robot with a robotic drone controller
option can operate repair drones much like Auto-
Repair software, although subject to the limitations
described on page 44. The robotic drone controller
allows functions such as Medic or Steward tasks to
be conducted through the use of repair drones if the
brain has the requisite skills. A ship’s brain running
actual Auto-Repair software can control repair drones
just like a ship’s computer without a limit on the
number of repair drones controlled, but with a limit on
the number of repair tasks performed. Repair drones
operated under Auto-Repair cannot perform non-
damage control related duties.

**Ship’s Avatars**
A ship’s brain with an avatar controller can ‘become’
the ship much like a biological being becomes an
avatar host. In addition, or as an alternative, the ship’s
brain can use the avatar controller to control a robot
as an avatar host, generally referred to as the ‘ship’s
avatar’. Higher technology avatar controllers can have
multiple avatars, allowing the ship’s brain to act as its
own crew, performing multiple tasks with precision.

ASTROGATION SKILL LIMITATION
In the Charted Space universe, sentient
Astrogators perform jump calculations with
much lower risk of misjump than a non-
sentient mind. Only a fully Conscious machine,
either running Conscious Intelligence on a
ship’s core computer or a Conscious ship’s
brain can avoid this limitation; even a Self-
Aware robot brain lacks the ‘spark’ necessary.

All jumps plotted by a non-sentient mind suffer
DM-4. A review of jump solutions by even an
unskilled individual with the background and
basic knowledge to understand the results of
the calculation, such as someone with Pilot,
Navigation or applicable Science skill, can
reduce this to DM-2.

Also, ships jumping without conscious sentient
minds aboard suffer an additional DM-4 on
the chance of misjump. If all conscious minds
are inactive, for example in hibernation or
controlled using a RIBACI, this DM still applies.

High Technology
Higher Tech Levels lead to both improvements in
existing technologies and the development of entirely
new capabilities. Those related to robotics include
advancements in avatar control, brains and fabrication,
which eventually lead to the blurring of identity
altogether. The advance of nanotechnology leads to
metamorphic robots, open fabrication and eventually
the dreaded autonomous self-replicating nanoswarm,
or ‘Grey Goo’.

These technologies are not generally available in
Charted Space except as early prototypes or incredibly
rare Ancients artefacts. At higher Tech Levels, robots
become clearly superior to non-augmented biological
beings and fabrication advances break down the
concept of scarcity, disrupting the economic system
and leading to a milieu beyond the scope of most
Traveller campaigns. Still, high technology items
are presented here to allow campaigns in universes
where artificial beings are coequal to biologicals and
technology begins to approach magic.

Special Robots and Other Synthetics

TRAVELLER

Avatars, Brains and
Metamorphic Robots
Avatar controllers continuing to improve, allowing a
robot to share consciousness with more and more
subsidiary units, eight at TL16 and 64 by TL18. This
allows an advanced being to be in many places at
once, linking back experiences to a central node.

By TL16 fully Conscious robotic brains become
possible and by TL17 these brains are small enough
for installation in robotic bodies. Robots with these
brains become completely conscious beings, no
different to a biological sophont except in structure.
Limitations to task complexity and other functions,
such as those in Charted Space of astrogation and
jump travel, completely disappear. With self-repair
and fabrication options, these machines can exceed
human INT limits and become functionally immortal.
They can still be destroyed but may have copied
themselves and can be restored from backups. Of
course, at higher Tech Levels biological beings also
have these options and with cybernetic augments can
keep up with their robot counterparts.

TL Capability Notes Cost
16 Avatar Controller (advanced) Control up to eight avatars MCr1
16 Android (superior) Pass as biological Cr20000/slot
17 Biological Robot (advanced) DM+4 to heal; pass as biological Cr20000/slot
17 Backup Brain Transfer (improved) Non-destructive brain backup (restore to conscious) MCr1/backup
17 Conscious Intellect INT 15, base Bandwidth 20 MCr5
17 Metamorphic Robot (basic) 1D minute morphable to Android (enhanced) Cr50000/slot
17 Microbot Brain Very Advanced, Computer/4 MCr0.5
18 Avatar Controller (superior) Control up to 64 avatars MCr5
18 Conscious Intellect INT 15, base Bandwidth 30 MCr1
18 Metamorphic Robot (improved) 1D round morphable to Android (advanced) MCr0.1/slot
18 Permanent Brain Restore Restore backup to biological body MCr1/restore
19 Conscious Intellect INT 18, base Bandwidth 50 MCr1
19 Continuous Brain Backup Implant to create running brain backup MCr1
19 Metamorphic Robot (advanced) 1D second morphable to Android (superior) MCr0.2/slot
19 Microbot Brain Very Advanced, Computer/5 MCr0.5
22 Individual Transformations Switching between natural and mechanical bodies MCr5

The form of robots continues to evolve with increases
in technology. By TL16 an android can pass as a
biological being, essentially becoming equivalent to a
biological robot. By TL17 a biological being with a robot
brain becomes indistinguishable from a completely
biological being even under psionic examination.

At TL17 metamorphic robots become possible.
These robots are composed of nanomachines on a
mechanical scaffolding allowing them to morph into
shapes, retaining only Size and locomotion mode
as basic properties, able to create manipulators and
physical features at will, and to change from a purely
artificial to an enhanced android appearance in a
manner of minutes. At increasing Tech Levels, this
mimic ability becomes more sophisticated and faster.

Ultimately these technologies combine to allow
consciousness of both artificial and biological
beings to flow between bodies and even replicate
consciousness at will, making distinctions between
robot and natural being, individual and group, more
choice than limitation.

Special Robots and Other Synthetics

**Fabrication, Nanorobots and Swarms**
Fabrication chambers can create complex items
from instructions and raw materials, much like
life forms. At TL17 this becomes literally true, as
fabrication becomes advanced enough to create life
at the molecular level; within an hour an advanced
fabricator can create a living being. This technology
does not allow for the transfer of memories but does
allow for the creation of a cloned body or custom
designed organism. By TL19 this technology can
duplicate quantum states and print a fully conscious
mind with whatever memories are recorded or
implanted into the being.

TL Capability Notes Cost
17 Fabrication (advanced) 1 hour, living beings, any robot brain MCr0.2/slot
18 Nanoconstructor (enhanced) Complex electronics, simple biomechanical MCr0.1/litre
19 Fabrication (superior) 1D minutes, memory implantation MCr0.5/slot
19 Microbot Sub-milligram microbots Cr50+ options
20 Open Fabrication (basic) 1 hour, external advanced fabrication MCr0.5/slot
20 Nanoconstructor (advanced) Living beings, any robot brain MCr0.2/litre
21 Open Fabrication (improved) 1D minutes, external superior fabrication MCr0.5/slot
22 Distributed Intelligence Swarm Conscious beings of interconnected nanorobots MCr0.2/package
23 Grey Goo Self-replicating nanorobot swarms None
23 Nanoconstructor (superior) Grey Goo initiator MCr0.5/litre

At TL19 microbots become smaller than a milligram,
reaching the upper range of nanorobot size and
allowing for complex behaviours by dust-sized robots.

Beyond TL19 construction nanoswarms can build
complex objects on command, assembling them
outside the controlled confines of a chamber. These
processes still require external guidance from swarm
controllers, although swarms themselves can create
more controllers. By TL23 this requirement vanishes
and swarms can replicate unchecked or transform
objects in a matter of seconds, with swarms spreading
geometrically to either recreate whole worlds or
transform them into the apocalyptic Grey Goo.

Grey Goo requires a superior Nanoconstructor, but any raw material will initiate a swarm. The swarm can and will grow
geometrically every 10 minutes unless inhibited or starved of raw material.

Special Robots and Other Synthetics

## O THER CONSIDERATIONS

Damaging Robots
After calculating the total amount of damage caused
by a weapon, the damage is reduced by the robot’s
Protection as normal and the remainder is removed
from the robot’s Hits. Once a robot has been reduced
to Hits 0 it is considered wrecked, although parts may
be salvaged or – with great effort – the robot might
be rebuilt. If a robot suffers damage beyond twice its
initial Hits, it is totally destroyed and has no chance of
being repaired.

RADIATION DAMAGE
Robots can suffer either temporary or permanent
damage from radiation depending upon the source. Ion
weapons cause Stun damage, shutting down the robot
brain for a number of rounds equal to the ion damage
inflicted. Armour does not protect against ion attacks
but hardened components are immune. A biological
brain in a robot body can suffer Stun effects from an ion
attack but armour protects it.

Radiation weapons cause permanent damage to a
robot’s brain. Radiation damage can be reduced by the
hostile and radiation environment protection options. A
hardened brain halves the effective radiation dose that
penetrates this shielding. Remaining radiation damage
has a cumulative effect on the robot’s brain and cannot
be repaired without replacing the brain. Every 1,000
rads affecting the robot’s brain removes INT -1 and
Bandwidth -1. Robots reduced to INT 0 are inoperable.
Basic or Hunter/Killer brains suffer DM-1 on all checks
when INT is reduced to 2 and DM-2 when INT is
reduced to 1. Advanced and more complex brains
may have skills lowered as their brain capabilities
deteriorate. Bandwidth decreases can be alleviated by
installing a new Bandwidth upgrade but this does not
heal damage done to the core Bandwidth of a brain.

ELECTROMAGNETIC STUNNERS
Electromagnetic stun weapons can cause actual
damage to robots. A stunner causes physical Hits,
not temporary damage to robots. A normal robot’s
Protection is only half effective against stunner
attacks but an android or biological robot’s armour
is fully effective against Stun damage. Hostile

environment protection provides Protection +2 (not
halved) against Stun damage. Radiation environment
protection provides additional Protection equal to
half its Tech Level, rounded down. A hardened robot
brain negates the effects of all critical hits affecting
the brain; these critical hits are ignored, not re-rolled.
Hardening provides no additional protection from Stun
damage beyond the brain but a ruggedised cybernetic
augment avoids physical damage if Hit Locations are
used on a cyborg.

Sonic-based stunners, such as those common in the
Vargr Extents cause no damage to robots, although
they may temporarily disable auditory sensors.

Hacking Robots
Robots are designed to be resistant to unauthorised
access and control. The first step to hacking a robot
is to gain access. For robots with a drone interface or
equivalent, all the hacker needs is a drone controller,
the proper unique authorisation codes for the robot and
two-way communications – be that via transceivers,
wireless data links or direct connection. Under this set
of conditions, communications access is automatic.
A robot with at least an Advanced brain can try to
resist an authorised drone interface control attempt
by making a Very Difficult (12+) INT check. On
success, the robot shuts down the drone interface and
disconnects the remote communications link, at which
point even an authorised user must use a hacking
attempt to gain access.

A successful hacking attempt must defeat the robot’s
firewall defences.

First the hacker must gain access. A robot by default
has a firewall with the equivalent of a Security software
package running on its communications links. The
sophistication of this is determined by the robot’s brain
as indicated on the Robot Brains table on page 66. The
hacker must overcome this software with a successful
intrusion attempt using Electronics (computers). The
complexity of this task is Difficult (10+) for Security/0
and becomes one level more difficult for each level of
Security software. The task requires 1Dx10 minutes
to attempt. Each failed attempt lowers the chance of

**ANTI-ROBOT WEAPONS**
Certain weapons are designed to cause damage to
robots or interrupt their functioning. These may be
installed on robots themselves in medium weapon
mounts but are normally used by forces fighting
warbots or by anti-robot activists.

**Stun Rifle**
A stun rifle is a larger, longer range version of the
hand-held stunner. Its major advantage over a
standard hand-held stunner is its effective range. The
detachable power pack is mounted in the weapon’s
stock and not interchangeable with power packs of
smaller stunners.

Weapon TL Range Damage Kg Cost Magazine Power Pack Cost Traits
Stun Rifle 12 50 3D 4 Cr2000 50 Cr200 Stun, Zero-G

Weapon TL Range Damage Kg Cost Magazine Power Pack Cost Traits
Stun Shotgun 12 10 3D 4 Cr2000 50 Cr200 Blast 5, Stun, Zero-G

**Stun Shotgun**
A stun shotgun is similar in size to a stun rifle but
has a broad short barrel which allows it to ‘blast’
an electromagnetic pulse over a wider area than a
typical stunner. This ‘blast radius’ provides DM+2
to attack rolls at up to its effective range but causes
only half damage at longer ranges. The detachable
power pack is stock-mounted and interchangeable
with the stun rifle.

**Pulse Carbine**
A pulse carbine is a short shotgun-like weapon that
releases an electromagnetic pulse in a focused cone,
disabling electronics within its effective range. The
pulse destroys unshielded electronics below TL9 and
causes unshielded electronics of up to TL13 to shut
down for a number of minutes equal to the attack roll’s
Effect. Vehicles or electronics of TL6 or below are not
affected by this. Every 100 rads of radiation protection
provides Protection +1 against a pulse carbine.

A robot of TL9 or less takes a number of critical
hits equal to the total damage inflicted by the pulse
carbine, although critical hits to a hardened brain are
ignored, not re-rolled.

Weapon TL Range Damage Kg Cost Magazine Power Pack Cost Traits
Pulse Carbine 11 50 2D 4 Cr5000 50 Cr200 Blast 5, Ion, Zero-G

Other Considerations

TRAVELLER

success by DM-1 and Effect -6 results in detection and
traceback to the attacker’s location, if remote.
Attempts to gain remote access to a robot with an
encryption module suffer DM-4, reduced by any TL
advantage the hacker has over the robot. A Parasite
Link and physical contact with the robot gains
automatic access or access on a straight 2D roll of 6+
if the robot’s brain is hardened (this can be attempted
multiple times).

Once a hacker has access to the robot’s internal
systems, they must attempt to gain control of the
robot. This requires a second successful intrusion
attempt of the same difficulty. Any positive Effect from
the access task can be applied. A control attempt can
use either Electronics (computers), Science (robotics)
or Profession (robotics) and does not need to be
performed by the same person who gained access.
The existence of a drone or avatar interface in the robot
provides DM+2 on the access control hack but even
if the hack is successful a robot with an Advanced or
better brain still has one last chance to avoid control
with a Very Difficult (12+) INT check. However, any
positive Effect from the successful access hack is
applied as a negative DM. If the robot is successful,
the hacker is detected, evicted and must start all over
again. If the hacker succeeds, they have full access to
the robot’s brain and systems.

A controlled robot can be commanded via a drone
control interface, reprogrammed (see page 79)
or shut down. A hacked and shut down robot with
power remaining can still be powered on. Malicious
‘scrambling’ of a robot’s brain requires a Difficult
(10+) check (1D minutes, INT or EDU), which results
in a partial wipe causing a critical hit to the brain of
Severity 1D.

Robot Maintenance
Like any machine, robots need periodic maintenance to
continue to function over long periods of time. Unless
the robot has a self-maintenance enhancement option
to delay or preclude the need for annual maintenance,
continued reliable operations requires 0.1% of the
robot’s cost per year in spares and diagnostic checks.
This maintenance can be performed by a properly
skilled Traveller, with an Average (8+) Profession
(robotics) or Science (robotics) check (1D hours, EDU),
although Electronics (computers) can be used at DM-2.
Maintenance tools and parts must be of at least the
robot’s Tech Level or the task becomes one level more
difficult for each Tech Level of deficit.

Maintenance can be completed by a qualified servicer
in a single day for the same price but only at a
maintenance facility of the robot’s Tech Level or higher.
Most Class A and B and many Class C starports have
robot maintenance workshops on site or in the adjacent
startown. These can repair robots up to TL12 even if
the world is of lower Tech Level but prices are doubled
for each Tech Level of deficit.

If a robot does not receive annual maintenance, roll 8+
on 2D each subsequent month to avoid a malfunction.
Treat malfunctions as Severity 1 critical hits and roll on
the robot critical hits tables. Malfunctions are additive;
if the same critical hit is rolled in a subsequent month,
it increases the Severity of the critical hit. Repairs
to maintenance-related critical hits cost as much as
repairs to critical hits caused by damage; it is much
cheaper to properly maintain a robot than fix it once it
begins to malfunction.

A robot in a powered down or ‘stand-by’ state requires
less maintenance, increasing the period of annual
maintenance and monthly malfunction checks by 12x.
This stacks with the self-maintenance enhancement
option. A robot properly shut down and packaged for
long-term storage increases these periods by a further
12x, meaning a properly stored robot with a basic self-
maintenance enhancement only requires maintenance
every 1,728 years and if missed, will check for
malfunctions every 144 years.

Robot Critical Hits
If an attack roll against a robot has Effect 6+ and
causes damage (make sure to consider armour
protection), a critical hit has been scored – some vital
system has been damaged by the attack, reducing the
effectiveness of the robot.

If a critical hit has been inflicted on a robot, roll 2D
and then consult the Critical Hits Location table. If the
location does not apply to this robot, roll again.

Critical Hits Location
2D Location
2–4 Power Supply
5 Weapon
6 Armour
7 Chassis
8–9 Locomotion
10–11 Options
12 Brain

Other Considerations

**Robot Hacking Flowchart**

TRAVELLER

The Severity of the critical hit is equal to the Effect of
the attack roll minus 5. Consult the Critical Hit Effects
table to determine the nature of the critical hit and how
it affects the robot. Any extra damage caused by the
effects of critical hits ignores the robot’s Protection.

If a robot has already sustained a critical hit to a
location that receives another, use the Severity of the
new critical hit or the original +1, whichever is higher,
and immediately apply any new effects. Once a location
has reached Severity 6, the robot sustains 6D damage
every time the location suffers another critical hit.

SUSTAINED DAMAGE
A robot has its components degraded when it sustains
constant damage. Every time a robot sustains damage
equal to 10% of its starting Hits, roll 2D and then
consult the Critical Hits Location table. The robot
suffers a Severity 1 critical hit to that location.

Critical Hits Effects
Severity
Location 1 2 3 4 5 6
Power
Supply

Speed
reduced by
1m or band

Remaining
Endurance
halved

Remaining
Endurance
halved again

Remaining
Endurance
halved again

Power supply
explodes.
Robot shuts
down. Chassis
Severity +1

Power supply
explodes. Robot
shuts down.
Chassis Severity
+1D
Weapon Random
weapon
suffers DM-2
to attack rolls

Random
weapon
disabled

Random
weapon
destroyed

Random
weapon
explodes.
Chassis
Severity +1

Random
weapon
explodes.
Chassis
Severity +1

Random weapon
explodes.
Chassis Severity
+1

Armour Protection -1 Protection
-1D

Protection -1D Protection -2D Protection
-2D, Chassis
Severity +1

Protection -2D.
Chassis Severity
+1
Chassis Robot suffers
1D damage

Robot suffers
2D damage

Robot suffers
3D damage

Robot suffers
4D damage

Robot suffers
5D damage

Robot suffers 6D
damage
Locomotion Speed
reduced by
1m or one
Speed Band

Speed
reduced by
1m or one
Speed Band

Speed
reduced by
1m or one
Speed Band

Speed reduced
by 1m or one
Speed Band

Robot
immobilised

Robot
immobilised.
Chassis Severity
+1
Options Random
option suffers
DM-2

Random
option
disabled

Random
option
destroyed

Two random
options
destroyed

Random option
destroyed.
Chassis
Severity +1

Random option
destroyed.
Chassis Severity
+1
Brain DM-2 to one
skill

DM-2 to all
skills

Robot unable
to perform any
skills

Robot INT
halved

Robot brain
disabled

Robot brain
destroyed.
Chassis Severity
+1

Repairing Robots
A robot that has suffered damage can be repaired at
any facility with suitable maintenance equipment. Robot
maintenance and repair is a complex task. For simple
chassis Hits restoration, an Average (8+) Mechanic
check, (1D hours, INT or EDU) is sufficient. This
consumes spare parts costing Cr500 per Hit repaired.

Critical hits are more complex and normally require
Profession (robotics) for an Average (8+) skill check
(1D hours, EDU) with the Severity as a negative DM.
Mechanic or Electronics (computers) skill can be
substituted at an additional DM-2. Each critical hit
repair costs the greater of Cr500 or 1% of the robot’s
total cost multiplied by the Severity. Additionally,
components that are completely destroyed require
replacement at full cost. In some cases, replacing a
damaged component is cheaper than repairing it.

Other Considerations

Completely damaged robots can be repaired. A robot
that is reduced to Hits 0 is considered wrecked and
inoperable, effectively ‘totalled’. For sentimental or
other reasons, a robot that has received up to twice
its original Hits in damage can still be repaired at
great expense but it costs twice the robot’s value to
repair. Once a robot has taken twice its original Hits
in damage, it is completely destroyed and cannot
be repaired. It might be possible to retrieve some
information from the brain but the remainder of its parts
are only worth the going rate for scrap recycling.

Used Robots
A substantial secondary market exists for used robots.
Sometimes robots are discarded in favour of a new
model but most often a robot is available for resale
when it becomes uneconomical, either because of
the owner’s financial situation or because of quirks or
defects that develop over time.

A used robot costs 1Dx10% less than a new one but
also has 1D-1 quirks from the Used Robot Quirks table.

**Used Robot Quirks**

2D Quirk
2 Faulty Programming. DM-1 on all checks performed by this robot.
3 Input Errors. The robot often misunderstands commands or instructions, falling back on behavioural
routines that might be inappropriate for the situation.
4 Output Errors. The robot’s communication responses require translation. Its output algorithms do not
conform to any standards or its output is in a different language or obscure dialect.
5 Communications Defect. The robot’s communication responses are difficult to understand. It might
produce non-standard electronic output or speak with a heavy accent or in an inappropriate manner.
6 Reduced Efficiency. Lower the robot’s Endurance by 10% and decrease its movement rate by one metre
or one Speed Band.
7 Chassis Defect. Reduce the robot’s Hits by D3x10%.
8 Cosmetic Defect. The robot has scratches, mismatched panels or poorly rendered artwork on its surface.
This defect can be corrected at a cost of Cr200 x Size.
9 Upgraded. Increase the level of one option, for instance from basic to improved, or add one skill package
at level 0.
10 Upgraded Bandwidth. Increase the robot’s Bandwidth by +1. For Primitive, Basic and Hunter/Killer
brains, allow one additional package mode.
11 Upgraded Intellect. Add +1 to the robot’s INT and add a level 0 skill package.
12 Delusions of Grandeur. Any brain of Advanced or greater complexity believes itself to be fully sentient
and acts that way. Fully Conscious brains consider themselves superior to all organic life.

Other Considerations

TRAVELLER

Reprogramming Robots
A robot brain is resistant to reprogramming. The
standard method for erasing previous memories
is a partial brain wipe, which resets the robot to
factory settings. For Primitive, Basic and Hunter/
Killer brains, this leaves built-in skills untouched but
any learned behaviour or conditional program trees
must be recreated.

OPTIONAL RULE: SANITY
If the characteristic Sanity (STY) is used in
a campaign, robots are assumed to have
STY starting at their brain’s Tech Level or 15,
whichever is lower. After every four years in
operation (not in storage or a stand-by state), a
robot’s STY decreases by -1. A robot’s declining
STY can potentially be corrected once every
four years in a laboratory or manufacturing
setting with a Very Difficult (12+) Science
(robotics) check (1D days, EDU). For every
Tech Level a robot’s brain exceeds that of the
facility, impose DM-2. An Exceptional Failure
decreases the robot’s STY by a further -1D;
an Exceptional Success adds +1 to the robot’s
STY, to a maximum of 15. Conscious robot
brains avoid this degradation on an Average
(8+) INT check.

Additionally, radiation damage that decreases a
robot’s INT decreases STY by the same value;
this cannot be reversed.

If a robot’s STY decreases to 2, its behaviour
becomes erratic. The robot’s interpretation
of commands and interactions become
idiosyncratic as determined by the Referee.
If a robot’s STY reaches 0, it either becomes
comatose or psychotic, again as determined by
the Referee.

The programming process for these relatively simple
brains is the same as required when first initialising
a robot at the factory, requiring an Average (8+)
Electronics (computers) check (1D hours, EDU).
Profession (robotics) or Science (robotics) skills may
be substituted and generally halve the time required
to set up a robot. Robots can be reprogrammed via a
hardwire cable, which is part of a roboticist’s toolkit,
or via a wireless data link. Standard transceiver
communications can eventually reprogram a robot but it
takes 10 times as long to complete the task.

Advanced and Very Advanced brains are more
complicated. While a brain wipe is possible, it
also erases skill packages, which will then need
to be reapplied, requiring repurchase at full price
or re-installation if source files are available.
The reinstallation task is similar to that for a less
sophisticated brain, with each skill package (of any
level) requiring a similar skill check.

A more nuanced reprogramming of Advanced and Very
Advanced brains to remove memories or behavioural
settings while maintaining skill packages requires a
Very Difficult (12+) Electronics (computers) check (1D
hours, INT) for Advanced brains and a Formidable
(14+) check for Very Advanced brains. Exceptional
failures can lead to undetected and unexpected
conditions, damaging the skill package or only
appearing to erase memories or behaviours.

Self-Aware and Conscious brains are too integrated
and intricate for partial wipes to be successful. While
an Impossible (16+) task might accomplish this feat,
any failure, or even a partial success, might cause
unintended changes to the robot’s behaviour. A full
wipe is recommended in these case but a robot of such
sophistication is unlikely to cooperate in the process.

A brain can always be replaced. A powered down robot
can have its old brain removed and a new one installed,
in effect creating a ‘brand new’ robot with a completely
un-initialised personality. All brain skill packages must
be reapplied and copy-protection schemes generally
prevent reuse of packages on new brain equipment.

Other Considerations

**BACKUP AND RESTORE**
A robot’s brain can be backed up periodically on a
separate computer system and restored to the same
robot from this previous state. Restoration must be
performed to a brain of identical manufacture or at
least one with the same Tech Level, complexity and
Bandwidth of the original. See Upgrading Robot Brains
below for the implications of restoring a backup to a
different robotic brain.

Both backup and restore processes require a wireless
data link or hardwired connection to adequate storage
with at least the same Tech Level as the robot’s brain.
It is possible to ‘duplicate’ a robot’s personality and
skills onto an identical brain while retaining the same
personality and skills of the original. This process
generally violates any licensing agreement pertaining
to the robot’s skill packages but has no ill effects other
than potential legal and financial liability. Duplicates of
the same personality running simultaneously are often
referred to as ‘memes’.

Upgrading Robot Brains
Upgrading a robot brain is a larger disruption than
reprogramming or installing a new brain designed
for the specific robot. There are three methods for
upgrading a robot brain: full brain upgrade, upgraded
options such as Bandwidth or INT and upgraded
brain sophistication.

**FULL BRAIN UPGRADE**
As long as the robot has Size and Slots to support
a new brain and any associated Bandwidth upgrade
option, the robot’s old brain can be removed and
replaced with a new brain of higher capacity straight
from the factory. The process is relatively quick and can
be performed in a properly equipped robotics facility
in 2D hours for similarly configured brains and 3D
hours for generic or novel brains with an Average (8+)
Profession (robotics) check (INT or EDU) and failure
generally results in additional attempts required to
complete the process. The Electronics (computers) skill
can be substituted for DM-2.

When transplanting a ‘live’ robot brain with existing
skills and memories, the process becomes much more
complicated, requiring a Difficult (10+) Profession
(robotics) or Science (robotics) check (1Dx4 hours,
INT). A ‘live’ robot brain in a robot of different form
requires 2D3 days to adapt to its new form before being
able to physically function at full capacity.

UPGRADED OPTIONS
Adding hardening to a robot brain is strictly a matter of
shielding installation and has no effect on the robot’s
thinking capacity but requires one Slot to retrofit.
Bandwidth additions expand the robot’s capability to
learn new skills or gain greater INT. Installed Bandwidth
is immediately available for the installation of new
packages, while Bandwidth intended to increase a
robot’s INT requires time to ‘bake in’. The Bandwidth
is immediately allocated but the robot gains INT over
time, at a rate of one point per week.

Upgraded options can be purchased at standard cost
and installed by anyone with the Electronics skill.

UPGRADED BRAIN SOPHISTICATION
It is technically possible to transfer the memories and
skills of a ‘live’ robot into a more sophisticated brain,
for instance upgrading an Advanced robot brain to Very
Advanced. This procedure is rarely performed, as it
often results in a suboptimal robot but sometimes it is
important to retain a robot’s personality.

This procedure requires a direct brain-to-brain transfer,
not a restore from backup. It is not generally performed
in robotics shops but requires a robotics laboratory, a
robotics scientist and careful adherence to rarely used
procedures and tools. A robot’s brain may only be
increased by one level of sophistication at a time. The
base task is a Very Difficult (12+) Science (robotics)
check (1D days, EDU). Individuals with Electronics
(computers) may attempt this task at DM-2 but need
access to the laboratory, tools and documentation.
If a negative Effect results, record it and make
subsequent attempts. If the cumulative Effect of all
attempts reaches 0, the procedure is a success but
if the cumulative Effect reaches -6, the ‘live’ robotic
personality in the original brain is destroyed and the
new brain suffers damage equal to 10% of its cost.

To avoid risking the original brain this attempt can be
made on a restored ‘copy’ of the original brain. The
backup must first be restored to an interim brain similar
to its current brain with all the expense and procedure
of a full brain upgrade procedure prior to the attempt to
upgrade to greater sophistication.

If the procedure is successful, the robot needs to adjust
to its new capabilities. For every point of INT gained in
this manner, the robot must spend a full day adjusting.
The procedure costs twice the cost of the new brain.

Other Considerations

TRAVELLER

Physical Upgrades
Physical upgrades to robots consist of installation of
additional options into spare Slots and upgrades of
installed equipment to something better or entirely
different. Upgrades that involve weapon systems
or even just weapon mounts may be subject to
stringent local regulations, often more severe than
those imposed on weapons owned and operated by
individuals. The Shudusham Concords and general
distrust of weaponised robots casts a long shadow
over Charted Space.

Purchasing new options for installation in available
Slots is the simplest form of upgrade. In general, a
physical option can be purchased at list price and
installed in a robot, usually at a +10% premium unless
the upgrade was installed at time of initial purchase.
The exceptions to this general principle involve items
added to the chassis such as coatings or armour and
items of greater Tech Level than the robot.

ADDING ZERO SLOT OPTIONS
Most Zero Slot options can be added to a robot, up
to the limit of Size + TL, beyond which spare Slots
are required. Adding Zero Slot coatings is possible
but only if the coatings are compatible. Adding
reflec armour to a robot with a camouflage or stealth
coating destroys any visual camouflage or electronic
stealth benefits.

SPARE SLOTS
Many robots have spare Slots reserved for the
installation of additional options. Items of higher Tech
Level than the robot might require more advanced
interfaces and draw more power. Adapters are
available for these components but add +10% per TL
difference to the cost of the component.

Adding coatings and armour that require Slots is
problematic, as spare capacity is not spread across
the surface area of a robot. A robot can only add one
Slot worth of coatings or armour, although removal
or changes of existing full-chassis options might
provide space for new installations. Armour and other
full coatings added to an existing robot design at
purchase or later require twice the standard cost.

SCIENCE VERSUS PROFESSION
For many tasks involving robots, both Science
(robotics) and Profession (robotics) skills may
apply. While there is significant overlap, these
skills have different foci. Science is focssed
on theory and development, while Profession
focuses on practical tasks and experience.
Unless otherwise specified, for tasks involving
repairs and maintenance, Science (robotics)
suffers DM-1 but for tasks involving design or
research Profession (robotics) suffers DM-1.
Unless specified, either INT or EDU may aid
checks, depending on the background and
methodology used by the Traveller to solve
the problem.

Other skills may apply to robotics task but
generally with DM-2 unless otherwise stated.
Tasks involving the brain can be assisted by
Electronics (computers) and repairs to sensors
and comms can be aided by the appropriate
Electronics speciality. Tasks involving robotic
limbs can be aided by Science (cybernetics) or
Profession (cybernetics) and simple repairs to
the robot chassis may benefit from Mechanic.
A biological robot might benefit from Medic
(biology) or Science (biology) for checks
involving the chassis.

UPGRADED COMPONENTS
Upgrading a component to a more advanced version
incurs a Tech Level-based premium and might require
a different number of Slots. Slot increases must come
from spare Slots or from removed components. Slots
gained through miniaturisation are generally lost in
the inaccessible bowels of the robot but at Referee
discretion may be made available for a small item that
does not suffer from being installed in an odd location.
In general, weapon mounts, coatings and sensors
cannot use these recovered Slots.

Other Considerations

## R OBOTS AS TRAVELLERS

At the Referee’s discretion a Traveller may be a
robot. Generally, a Traveller robot is assumed to
have at least a Very Advanced brain, although Self-
Aware and Conscious brains are more suitable for
emulating or achieving free will.

The type of brain constrains a robot Traveller’s ability
to use skills in highly complex tasks. An Advanced
brain can only attempt Difficult (10+) and simpler
tasks, a Very Advanced brain can attempt Very
Difficult (12+) and a Self-Aware brain, Formidable
(14+). Take note of two things: first, performing a
task more slowly can lower difficulty by one level and
second, this restriction only applies to INT, EDU or
SOC-based checks. A robot Traveller is free to try an
Impossible (16+) feat of STR.

Playing a robot can be challenging. Different levels
of robot brain complexity can lead to different types
of behaviours, strengths and weaknesses. Some
societies might consider a robot Traveller to be a
piece of equipment, a threat to their livelihood or
even their survival.

Robot Traveller Creation
A robot is built not born. A biological robot or clone
might come from a vat but usually emerges as an
adult or child, not an infant. Each robot model is in
effect a separate alien race and the Referee must
determine which robots are suitable for use as
Travellers. Custom robots can be created based on
a concept agreeable to the Referee; these should
usually be constrained by cost and Tech Level to
prevent the creation of superhero-class robots, unless
that fits into the campaign concept. A Traveller could
be a ship’s brain but in those cases it is recommended
that the Traveller has an external avatar.

Characteristics
A robot Traveller’s characteristics are not rolled
for but result from the design of the robot and the
society in which it was created.

Strength (STR): This is based on the STR of the
robot’s strongest manipulator. However, checks are
based on the STR of the manipulator(s) actually

performing each task. A robot without manipulators
has STR 0, although for tasks such as smashing down
a door, the robot may use a value of 2 x Size -1.

Dexterity (DEX): This is based on the DEX of
the robot’s most dexterous manipulator. If the
robot has an agility enhancement, the value of the
enhancement is added to DEX. This DEX is used for
purposes of tasks such as dodging or balance but for
checks reliant on manipulators, such as aiming and
firing a weapon or piloting a vehicle, the DEX of the
manipulator(s) performing the check is used.

Endurance (END): A robot’s END is related to power
available for its operation. The robot’s default END is
the greater of 6 or its Size. If the robot has enhanced
endurance from additional power packs, as indicated
by Athletics (endurance), its END is assumed to
be 9 for Athletics (endurance) 1, 12 for Athletics
(endurance) 2 or 15 for Athletics (endurance) 3+.
A robot with the efficiency modification adds +1 to
its END. A robot powered by an RTG is assumed
to have END 16, reduced by half for every period
exceeding the RTG’s half-life.

Intellect (INT): INT is that of the robot’s brain,
including any INT upgrades. The restriction on
task complexity based on robot brain type applies
regardless of INT upgrades. For example, only a fully
Conscious robot may attempt Impossible (16+) tasks
and an Advanced Brain is limited to Difficult (10+)
tasks, although external modifiers may modify a task
to an equivalent complexity within the capability of
the robot’s brain.

Education (EDU): EDU is limited to the robot’s
skill package set. When using skills within this
set, the robot’s EDU is equal to its INT. General
education normally comes with experience and
a robot’s ‘life experiences’ are non-existent at
creation and limited by assigned duties. However, a
robot effectively has total recall. For characteristic
purposes, outside the direct application of package
skills, the robot’s maximum EDU can be considered
to be its Bandwidth capacity for skill packages;
total Bandwidth minus any Bandwidth used for INT
upgrades. Only robots with Advanced or greater
brains may gain any general EDU capability.

Social Standing (SOC): A robot’s SOC depends
on the society in which it resides and the situation
requiring a SOC-based check. In societies where
all robots are property, robots have SOC 0. When
using skills that normally require SOC, a robot may
use its INT modifier instead, subject to the Referee’s
interpretation of the society’s or individual’s reaction.
For example, if commanding troops who will follow
orders from a robot or who do not know that the
battle dress-equipped ‘colonel’ is actually a robot, the
robot may use INT to modify a Leadership check but
if the troops consider robots to be equipment, they
are likely to react poorly and the robot reverts to SOC

0. In societies where a robot of sufficient intelligence

is considered a citizen, SOC is determined on 2D.

Initial Skills
Robot skills are programmed, not learned. Robots
do not earn background skills but receive the skill
packages normally assigned to the robot by its
function, although the Referee may allow a Traveller
robot to pick reasonably plausible substitutes provided
they do not cost more than the robot’s standard
package. All skill packages must be within the
technological or Bandwidth limitations of the robot.

Robot Careers
Robots do not need a career and in many societies
have no opportunity to pursue one. Robots are
assumed to either be newly manufactured – or
recently reset to factory defaults – or have performed
their designated tasks for some period of time prior
to starting the campaign.

In societies where a robot is property, it does not
normally have an opportunity to undergo pre-career
options or pick a career. The robot is assigned a
career based on its purpose and it continues in
the career until the creation process is complete.
Alternatively, a robot could be assigned as property
of another Traveller and follow that Traveller’s career
subject to limitations based on social status.

**BASIC TRAINING**
A robot does not normally undergo basic training. It
begins the career equipped for the duties assigned
and treats the first term as any other.

TERMS
A robot Traveller conducts a term in a normal manner,
rolling for Survival, Events, Advancement and possibly
Commission. Actual Advancement or Commission
may be unavailable in its society; for example, a robot
marine might always be rank 0 but may roll for a skill if
the advancement roll is successful.

MISHAPS
Mishaps or events causing injury are treated as
damage to systems, be they manipulators, sensors
or power supplies. These are not repairable by
medical treatment but may be repaired as indicated
on page 110 for the appropriate cost and ‘medical
debt’ may be accrued or paid for by the career’s
service as normal.

SKILLS
A robot may roll on appropriate skill tables. Increases
to STR, DEX and END represent actual upgrades of
manipulators or power sources and can be reflected
in the robot’s physical construction. Increases
to INT or EDU must be within the capabilities –
technological, Bandwidth and Slots of the robot’s
existing brain and possible Bandwidth upgrades

- otherwise the skill is lost. Increases to SOC are

possible only if the robot is free; in a society where a
robot may become ‘emancipated’ an increase in SOC
represents this emancipation and raises the robot’s
SOC above 0.

Skills rolls represent changes to programming.
Subject to Bandwidth limitations, the robot may
switch a rolled skill for an existing package or reduce
the Bandwidth of an existing skill to allow substitution
of a new skill. A robot with no available Bandwidth
skill slots can take the skill at level 0. Skills such
as Stealth, Navigation, Recon or Vacc Suit might
represent upgrades to physical systems if Slots are
available to install or upgrade options. A robot cannot
receive the Jack-of-all-Trades skill – not even if it has
a Conscious brain.

MUSTERING OUT BENEFITS
A robot may roll for Benefits as normal, with the
usual limitations to characteristic increases. Results
of Armour or Weapons can be assumed to be
upgrades or installation of weapon systems if Slots
are available. A result of Combat Implant or other
augment can be construed as an increase in the
capabilities of an installed system.

Robots as Travellers

### C ENTRAL SUPPLY CATALOGUE: ROBOTS

Avatar Chair: This is a bulky armchair equipped with
a large neurosensory helmet that allows a Traveller
without implants to control an avatar or drone. On a
starship, the chair consumes 0.5 tons, on a vehicle
it requires two Spaces. An occupant in the chair
experiences full presence when connected to a remote
avatar interface with full control of its actions. When
connected to a remote drone interface, the occupant
has an experience similar to a drone control helmet.

The avatar chair includes a 500-kilometre transceiver,
and can connect to an external transceiver for
additional range, but beyond 500 kilometres light
speed delays become noticeable, disrupting the feeling
of ‘being’ the avatar and imparting DM-1 to checks
requiring DEX. Beyond 5,000 kilometres, the avatar

ITEM TL KG COST
Avatar Chair, Standard 13 200 Cr300000
Avatar Chair, Deluxe 13 200 Cr500000

Clone Tank: A clone tank is a standardised bioreactor
intended for growing clones to maturation. A TL9
basic tank is intended for medical clones and can
maintain them indefinitely but could be used to grow
a clone. Improved and advanced clone tanks support
this feature but are most often used for accelerated
or quick-grown clones, respectively. A clone tank has
no capacity for customising a clone; it must accept a
template created elsewhere.

Based on a standard bioreactor, a clone tank is
designed to fit into a standard low berth mounting,
consuming 0.5 tons or two vehicle Spaces. It has the
same volume as a Size 7 robot and the same internal
dimensions as a low berth or the equivalent capacity
of a 50 Slot bioreaction chamber.

CLONE TANK TL DESCRIPTION COST
Basic 9 Suitable for growth and maintenance medical clones without higher
mental functions

Cr100000

Improved 10 Suitable for accelerated 12x growth to adulthood Cr250000
Advanced 13 Suitable for quick-grown 50x growth to adulthood MCr1

‘experience’ fails, returning ‘consciousness’ to occupant
of the chair, though drone control is still possible.

The avatar chair comes in two models: standard and
deluxe. Both include restraints to prevent the occupant
from injuring themselves while connected to the
avatar, though voluntary moment is inhibited during the
experience. The deluxe version includes medical-grade
connections allowing for feeding, waste disposal and
muscle conditioning without terminating the avatar link,
allowing an experience to last indefinitely.

Creating, controlling and maintaining robots requires a variety of equipment, from simple hand controllers to full
laboratories that would make any roboticist (mad or otherwise) proud.

**Deconstruction Chamber:** A deconstruction chamber
is in some respects the opposite of an enhanced
fabrication chamber. The chamber uses precise
measuring devices and nanomachines to dissemble
an object and record its composition at the molecular
level. This process completely destroys the object
but allows for construction of an identical object using
an enhanced fabrication chamber. It can be used to
‘harvest’ memories and personality of a biological or
robotic brain but the process is destructive. Enhanced
fabricators can put the body back together but cannot
restore memories or personalities, although they
can be stored in electronic form for restoration onto
an agent wafer in the case of a biological brain or
a fresh robotic brain in the case of a robot. Output
from the deconstruction process of a standard-sized

Drone Control Console: A drone control console
is an integrated console that allows a Traveller to
control a drone. The console allows command of one
drone and includes a 50-kilometre transceiver and
connections to interface with longer range external
transceivers. A video screen allows the operator to
see a view from the drone’s visual sensors. Beginning
at TL8 the improved control console includes audio
from any auditory sensors and allows the operator
to use the drone’s voder if one is present. At TL11
the advanced console allows olfactory sensations
to be transmitted, if desired. The operator requires
Electronics (remote ops) to effectively use the
console. For every 5,000 kilometres distance to the
drone, the Control DM decreases by -1.

chamber requires Bandwidth 32 to store in computer
memory or on data wafers. Available at TL13, the
deconstruction chamber is the size of a standard low
berth, able to hold an item or person occupying 50
Slots or about 150 kilograms and requires 64 Slots if
installed in a robot.

ITEM TL KG COST
Deconstruction Chamber 13 200 MCr5

Smaller or larger deconstruction chambers are
available. MCr1 is the cost of its core machinery
and the remainder scales linearly, with a half-sized
chamber costing MCr3 and a double-sized chamber
costing MCr9.

DRONE CONTROLLER CONSOLE TL KG CONTROL DM COST
Primitive 5 10 -4 Cr2000
Basic 7 2 -2 Cr2500
Improved 8 2 0 Cr1000
Enhanced 10 0.5 0 Cr1000
Advanced 11 0.5 +1 Cr5000

Central Supply Catalogue: Robots

TRAVELLER

Drone Control Helmet: A drone control helmet
allows a user without augments to operate a drone
by thought. The bulky helmet fits over the head and
provides neurological inputs that override a user’s
senses and movements, receiving senses from
the drone and transmitting commands to it. While it
provides a virtual reality experience, it does not allow
full presence in the sense of an avatar. Effective
use of a drone control helmet does not require
Electronics (remote ops) skill but benefits from it.
The drone control helmet provides all the features
of an advanced drone control console, including
a 50-kilometre transceiver, and can connect to an
external transceiver for additional range. For every
5,000 kilometres distance to the drone, the Control
DM decreases by -1.

ITEM TL KG CONTROL DM COST
Drone Control
Helmet

11 3 +1 Cr50000

Induction Plate
Rather than plug into a hard-wired socket, a robot
may use an induction plate, standing on or lying in
front of it to recharge batteries. This is especially
useful for converting biological robots and androids,
who can conceal an induction plate in a bed and
regain power after a ‘natural’ night’s sleep. An
induction plate’s size is related to the robot’s Base
Slots and requires a connection to a source of
power, whether the local electric grid or a ship’s
power systems.

ITEM TL KG PER SLOT COST PER SLOT
Induction
Plate

8 0.1 Cr20

Inhibitor: An inhibitor is small external device
attached to a robot that limits its activities. An
inhibitor allows for geofencing – limiting the
operating range – of robots and for remote
shutdown. Most drone interfaces include inhibitor
technology but a drone interface is not necessary
for an inhibitor to function. Inhibitors cannot be
installed on microbots or nanorobots. An inhibitor
includes a 50-kilometre transceiver separate from
any installed in the robot. They are generic and
can be transferred from robot-to-robot.

The TL13 inhibitor imposes DM-2 on any robot’s
attempt to override an inhibitor.

ITEM TL KG COST
Inhibitor, Basic 9 — Cr500
Inhibitor, Advanced 13 — Cr500

Larger plates may recharge vehicles, with a
64 Slot-equivalent plate required for a vehicle
of one Space in size. Public induction plates
are also available for recharging, usually at a
reasonable fee of Cr2+1 per Slot-equivalent for
an eight-hour full recharge. Induction plates may
vary the amount of current they deliver but fully
recharging a robot with a fast charger in one hour
instead of eight usually incurs 10 times the fee of
a regular recharge.

Central Supply Catalogue: Robots

**Robotics Lab Fabrication Chamber:**
Robotics laboratories are often equipped with a 128-
Slot fabrication chamber, capable of building a Size
6 robot body, including a power source and material
input bins. A smaller 64-Slot fabrication chamber
capable of building a Size 5 robot body is also

FABRICATION CHAMBER TL COMPLEXITY TIME REQUIREMENT COST
Basic 8 Mechanical parts only 2 hours 250000
Improved 10 Simple electronics
Primitive robot brain

2 hours MCr1.25

Enhanced 13 Complex electronics, simple
biomechanical
Basic robot brain

1 hour MCr6

Advanced 17 Complex biomechanical
Any robot brain

1 hour MCr24

available, as is a 32-Slot Size 4 robot builder, at one
half and one quarter the cost, respectively. At TL13
these chambers can also act as bioreactors or clone
vats. See the fabrication chamber option on page 51
for limits on the time requirement.

**Robotics Laboratory**
Robots can be built and maintained in a robotics
laboratory. In the context of a spacecraft, this is a
four-ton laboratory option or, if transported in a cargo
bay, it takes five tons of hold space. On a vehicle it
is a 16-Space customisation. The shell’s standard
equipment includes a workbench large enough for a
Size 6 robot and toolkits for mechanical, electronic
and robotics work.

Optional equipment includes fabricators and
controllers. In addition to the workbench and toolkits,
the laboratory has room to install a 128-Slot fabrication
chamber, one avatar chair and various controllers.
Robotic avatar, drone and swarm controllers require
a robotic brain for operation, such as the immobile lab
control robot (page 179). A drone control interface for a
biological operator can be included in the laboratory at
the costs listed on page 79.

LABORATORY SHELL SIZE COST
Spacecraft 4 tons Cr500000
Vehicle 16 Spaces Cr50000
Pressurised (base) 5 tons as cargo,
3m x 3m x 6m

Cr125000

Unpressurised (building) 5 tons as cargo,
3m x 3m x 6m

Cr25000

Central Supply Catalogue: Robots

TRAVELLER

Swarm Controller Console
A swarm controller console is an integrated console
that enables a Traveller to command a swarm of
robots. While swarms are normally microbots or
nanorobots, nothing prevents the swarm controller
from commanding a group of identical larger robots
conducting synchronised tasks from construction to
mining to storming a fortress – although as a mob, not
a coordinated military force.

The console includes a computer specialised to run
Swarm Control software through an Expert system,
allowing an unskilled individual to verbally control
the console to issue commands for the swarm to
conduct tasks. A multi-channel wireless data link and
50-kilometre multi-channel transceiver is integrated.

The console can also be operated as an improved
drone control interface with an effective Electronics
(remote ops) 0 for an unskilled individual or at full skill
level for an expert drone operator. Control of swarms
is limited to the 50-metre range of the wireless data
link but drones can be controlled up to 50 kilometres
distance. External multichannel transceivers to extend
this distance are available at 10 times the cost of a
standard transceiver of equivalent range.

More advanced swarm controllers are available
at higher Tech Levels as computers and software
improve. Skill limitations on task complexity are
equivalent to that described for the robotic swarm
controller on page 45.

SWARM CONTROLLER CONSOLE TL CAPABILITY KG COST
Basic 11 1 max tasks, 0 max skill or 1 drone 10 Cr20000
Improved 12 2 max tasks, 1 max skill or 2 drones 6 Cr50000
Enhanced 13 3 max tasks, 2 max skill or 4 drones 4 Cr100000
Advanced 14 4 max tasks, 3 max skill or 8 drones 2 Cr200000

Clone Creator
This is software for developing custom clone
genetic sequences. Increasing complexity of
genetic modification is matched by increasingly
complex software, although earlier versions can

SOFTWARE BANDWIDTH TL CAPABILITY COST
Clone Creator/1 1 8 Modify DNA to prep for basic cloning Cr2000
Clone Creator/2 2 10 Create novel organisms from a natural template Cr20000
Clone Creator/3 3 13 Create organisms to specifications from scratch Cr200000

SOFTWARE
Robots run on software but those who work with robots
require software to design and control them.

create simpler clones. Clone Creator software
provides a DM equal to its Bandwidth on any tasks
to create novel genetic designs.

Central Supply Catalogue: Robots

**Drone Control**
Drone Control software is Expert software requiring
an Intelligent Interface, which can be run on a
computer attached to a robotic drone controller

SOFTWARE BANDWIDTH TL CONTROL DM COST
Drone Control/1 1 11 +0 Cr2000
Drone Control/2 2 12 +1 Cr5000

or connected to a robot via transceiver link. This
software is only capable of controlling a single
drone at a time.

Fab Creator
Fab Creator is software for developing custom
fabrication designs. Increasing complexity of
fabrication output is matched by increasingly
complex software, although earlier versions
can create simpler patterns for printing on more

SOFTWARE Bandwidth TL CAPABILITY COST
Fab Creator/1 1 8 Basic Fabricator output Cr2000
Fab Creator/2 2 10 Improved Fabricator output Cr5000
Fab Creator/3 3 13 Enhanced Fabricator output Cr20000
Fab Creator/4 4 17 Advanced Fabricator output Cr50000

sophisticated fabricators. Fab Creator software
provides a DM equal to its Bandwidth on any tasks
to create novel fabricator designs. Fab Creator/3
and /4 can design or modify nanorobots.

Swarm Control
Swarm Control software is Expert software
requiring an Intelligent Interface that can be run
on a computer attached to a swarm controller
(see page 45) or connected to a group of robots

SOFTWARE BANDWIDTH TL CAPABILITY COST
Swarm Control/1 1 11 1 max tasks, 0 max skill Cr15000
Swarm Control/2 2 12 2 max tasks, 1 max skill Cr30000
Swarm Control/3 3 13 3 max tasks, 2 max skill Cr60000
Swarm Control/4 4 14 4 max tasks, 3 max skill Cr120000

via a high-speed multi-channel wireless data link
available for Cr500. It allows a Traveller to control
a group of robots in a manner similar to a swarm
controller console.
Central Supply Catalogue: Robots

## R OBOTICS CONTROL CHART

Robots are self-sufficient machines, capable of
independent operation. However, robots, drones and
even biological beings can be remotely controlled by
other robots, biological beings and equipment. The
Robotics Control Chart summarises the methods and
equipment needed for these control pathways.

**FINAL NOTE**
These rules are intended for the creation of robots but
are also useful as a ‘Thing-Maker’, allowing creation of
many custom devices. A ‘Thing’ can begin as a robot
with no locomotion and no manipulators, adding a few
extra Slots to the shell of a device. The rules assume a
basic power supply but the ‘No Internal Power’ option
can remove it. The Thing can then include any options
required to meet its requirements, perhaps with a
standard computer added as a brain, if necessary.
**Robotics Control Chart**

##### THE

#### robotrobot

##### Catalogue

Robots serve a variety of purposes from the mundane
to the specialised, from healthcare to military and
everything in between. This chapter details robots
available across varying levels of technology and
sophistication, from simple cleaning machines to the
most advanced artificial sentient beings. Most robots or
their equivalent are available in any universe but some,
specifically those produced by alien races, are based on
the Charted Space universe.

More than 40 of these robots are derived from the
Central Supply Catalogue and various supplements
and adventures. As they were designed prior to the
release of the Robot Handbook, the following
specifications may vary from the previous
versions of these robots in some respects.
Every effort was made to conform to the
capabilities of the original robot but to be
consistent with the design framework
some features may have changed
and more detailed options added. In
most cases the major difference is
the cost of the robot, which is almost
universally less than the price listed
in previous publications.

##### THE

#### robotrobot

##### Catalogue

## MILITARY ROBOTS

Robot Hits Locomotion Speed TL Cost

Battle Mule 55 Wheels, ATV — 9 Cr40000

Skills Athletics (dexterity) 1, Athletics (endurance) 3, Stealth
2

Attacks —

Manipulators —

Endurance 432 (108) hours

Traits Armour (+12), ATV (slow), Large (+2)

Programming Primitive (evade) (INT 1)

Options Auditory Sensor, Drone Interface, Storage
Compartment (25 Slots), Transceiver 50km
(improved), Visual Spectrum Sensor, Voder
Speaker, Weapon Mount Autoloader
(medium) x3, Wireless Data Link

Military robots perform functions including direct combat, surveillance and support roles. Many societies, including
the Third Imperium, place strong restrictions on the capabilities of military robots, often relegating them to non-
combat roles. Within such societies lethal robots are generally illegal to produce, possess and, certainly, to use.
Other societies see a military robot as just another tool of war.

Battle Mule
Battle Mule is one of several supply-and-reloading
drones on the market. It takes the form of a low, lightly
armoured box with six large balloon tyres similar to
those of an all-terrain vehicle. It can cross calm water
without preparation, using its tyres for buoyancy,
and is agile enough to deal with rough terrain. Battle
Mule has two internal compartments; the larger one
is purely cargo stowage and can carry 50 kilograms
of ammunition or various supplies. The smaller can
be configured for cargo by removing the automatic
reloading equipment but is more commonly used as
a field loader in direct support of a unit. The auto-
reloader carries 1,000–2,000 rounds of ammunition,
depending on calibre, in its ready hopper. It can reload
standard magazines for up to three different weapons
or ammunition types at once. Actual reloading takes
one combat round but inserting an empty magazine or
taking a full one out is a Minor Action for the soldier.
The ammunition hopper can be reloaded using pre-
packaged or loose ammunition. A box of 1,000 rounds
typically weighs about 10 kilograms.

Battle Mule can be used to conduct semi-autonomous
resupply operations to forward positions or troops on
the move or can accompany a force in the field. It is
a large target and despite programming to use terrain
as cover, Battle Mules tend to be put out of action on
a frequent basis. A variant has recently reached the
marketplace that trades cargo and reloading areas for
a very cramped operator station. The operator kneels
with their legs inside the cargo space and most of their
torso sticking out. A raised, folding shield is fitted to
the front and sides, which can be swung out to provide
mobile cover for two soldiers on each side. Some units
have attempted to fit a light support weapon for the
operator to use but this has achieved little success.
Despite looking ridiculous, the shielded variant can
provide cover during an advance and has seen success
with some starport security formations. The shield adds
Protection +8 against attacks from the side it is facing.

**Centurion**
The Centurion is a full-blown battle
robot, designed to accept and execute
commands that result in the eradication of
an enemy. While often employed in security
positions or used for manual labour during
peace time, once committed to battle the
Centurion is relentless, braving any hazard
in order to achieve its objectives.

Robot Hits Locomotion Speed TL Cost
Centurion 32 Walker 7m 12 Cr200000
Skills Athletics (endurance) 2, Explosives 1, Gun Combat (slug) 3, Melee (unarmed) 2, Recon 3,
Tactics (military) 3
Attacks Gauss Rifles x2 (linked: 4D+4, AP 5, Auto 3, Scope), 880 shots
Manipulators 2x (STR 11 DEX 7)
Endurance 259 hours
Traits Armour (+14), ATV, Large (+1)
Programming Advanced (INT 8)
Options Auditory Sensor, Construction Equipment (medium), Drone Interface, Fire Control System
(enhanced), Olfactory Sensor (basic), Radiation Environment Protection (+600 rads),
Recon Sensor (advanced), Satellite Uplink, Transceiver 500km (enhanced), Vacuum
Environment Protection, Visual Spectrum Sensor, Voder Speaker, Weapon Mounts
(medium) x2, Weapon Mount Autoloaders x2, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Clearance 600
Crowd Dispersal Unit

40 Walker 5m 10 Cr83000

Skills Gun Combat (energy) 1, Heavy Weapons (portable) 1, Melee (bludgeon) 1, Recon 2,
Tactics (military) 2
Attacks Fists (3D), Grenade Launcher (varies), Stunner TL10 (2D+3, Stun, Zero-G)
Manipulators 2x (STR 15 DEX 6)
Endurance 72 hours
Traits Armour (+19), ATV, Heightened Senses, IR Vision, Large (+1)
Programming Hunter/Killer (tactical) (INT 4)
Options Auditory Sensor (broad spectrum), Drone Interface, Fire Control System (basic), Laser
Designator, Light Intensifier Sensor (advanced), Recon Sensor (enhanced), Storage
Compartment (1 Slot), Transceiver 50km (improved), Visual Spectrum Sensor, Voder
Speaker (broad spectrum), Weapon Mount (medium), Weapon Mount (small), Weapon
Mount Autoloader (medium), Wireless Data Link

**Clearance 600 Crowd Dispersal Unit**
The Clearance 600 is designed to look impenetrable
and, for its role, it is effectively so. A squat humanoid
robot two metres tall with a blunt head equipped with
loudspeaker mouth and a stunner on the chin, the
heavily armoured Clearance 600 has a chest-mounted
grenade launcher normally equipped with non-lethal
rounds and oversized arms capable of forcing their way
through crowds or pommelling resisters senseless.

Its main drawback is relatively slow mobility, although
some would say this is a feature, encouraging a crowd
to disperse by fleeing. In any case, those brought down
by stunner or disabling grenades can be picked up at
leisure and kept under control by a large collection of
restraints carried in a small internal compartment.

Another flaw is its fire control system limitation of
initiating only one attack at a time. The robot can
fire the grenade launcher or stunner or engage in
hand-to-hand combat, yet is unable to make multiple
attacks or deal well with multiple foes. Despite this,
some purchasers have equipped the Clearance 600
with lethal grenades and used it for close combat
operations. Although the robot is a tough target, it is
large and slow, making it more suitable for operations
against lightly armed opponents in open terrain.

**Combat Drone**
The GeDeCo Combat Drone is a security robot
designed to provide defence for high-value installations.
Armed with a laser rifle, these flying drones are tasked
with driving intruders from a facility with lethal force
and alerting coordinated defence assets to provide
a proportionate response. Additional Slots allow
customisation to specific duties but the general-purpose
base model can repel anything short of a military assault.

Robot Hits Locomotion Speed TL Cost
Combat Drone 22 Grav 8m 11 Cr78000
Skills Gun Combat (energy) 2, Tactics (military) 1
Attacks Laser Rifle (5D+3, Zero-G)
Manipulators 2x (STR 9 DEX 7)
Endurance 19 hours
Traits Alarm, Armour (+8), Flyer (idle), IR Vision
Programming Basic (security) (INT 4)
Options Auditory Sensor, Drone Interface, Fire Control System (improved), Light Intensifier Sensor
(advanced), Spare Slots x8, Transceiver 50km (enhanced), Vacuum Environment Protection,
Voder Speaker, Weapon Mount (medium), Wireless Data Link

Creeper Assassin
This tiny robot has a single purpose and is usually
considered disposable after – to gain access to a
target and deliver a lethal attack. Small enough to
be held in the palm, a creeper assassin can vary in
appearance, with some slug-like while others are more
like metallic spiders. However, all have deadly purpose
once programmed to kill a specific target. Although
its standard monoblade is perfectly lethal, particularly
against targets not expecting an attack, especially
vindictive users may also coat the weapon with poison.

Robot Hits Locomotion Speed TL Cost
Creeper Assassin 4 Walker 6m 12 Cr190000
Skills Athletics (dexterity) 3, Electronics (computers) 1, Investigate 2, Melee (blade) 3, Navigation
1, Recon 3
Attacks Monoblade (3D, AP 10)
Manipulators —
Endurance 130 hours
Traits Armour (+6), ATV, Heightened Senses, IR/UV Vision, Small (-3)
Programming Advanced (INT 9)
Options Auditory Sensor, Drone Interface, Environment Processor, Gecko Grippers, PRIS Sensor,
Recon Sensor (advanced), Transceiver 5km (improved), Voder Speaker, Weapon Mount
(small), Wireless Data Link

**DesiGnator**
DesiGnator is a grav-mobile drone about the size
of a tennis ball, equipped with a laser designator/
rangefinder and a battery of thermal and optical
cameras. Range is about 15 kilometres, assuming the
operator wants the drone to be able to return to its
launch point for recovery and recharging. DesiGnator
does not move much faster than a jogging human but
is a difficult target. Its name is derived from ‘gravitic
propelled designation drone’ but DesiGnators are more
commonly used for reconnaissance.

Robot Hits Locomotion Speed TL Cost
DesiGnator 5 Grav 9m 10 Cr20000
Skills Athletics (dexterity) 1, Recon 2
Attacks -—
Manipulators —
Endurance 19 hours
Traits Armour (+3), Flyer (idle), IR Vision, Small (-3)
Programming Primitive (alert) (INT 1)
Options Drone Interface, Laser Designator, Light Intensifier Sensor (advanced), Recon Sensor
(enhanced), Transceiver 50km (improved), Wireless Data Link

Fighting Strongpoint
The Fighting Strongpoint is an armed version of the
Walking Strongpoint (see page 144), replacing the large
storage compartment with a dual laser rifle mount and
expanded power pack capacity. In addition to all the
features and limitations of the Walking Strongpoint, the
Fighting Strongpoint’s linked lasers can fire in a 90o arc
centred on the forward face of the shield-like robot while
still providing cover and firing slits for up to four soldiers
and spare ammunition for their weapons. Another
compartment below the lasers contains space for
optional components but does not allow for more armour
or other full-chassis options.

As a lethal combat robot, the Fighting Strongpoint is
sometimes sold with the mounting for dual lasers but no
weapons installed. It can deal a great amount of damage
to even moderately armoured vehicles but does not
sport a top-of-the-line fire control system, although an
upgrade is possible for an additional Cr25000.

Robot Hits Locomotion Speed TL Cost
Fighting Strongpoint 32 Walker 6m 11 Cr330000
Skills Gun Combat (energy) 2, Recon 2, Stealth 3, Tactics (military) 1
Attacks Laser Rifles x2 (linked: 5D+8, Zero-G) 1,100 shots
Manipulators —
Endurance 65 hours
Traits Alarm, Armour (+19), ATV, IR Vision, Large (+1)
Programming Basic (security) (INT 4)
Options Auditory Sensor, Camouflage: Visual (enhanced), Construction Equipment (medium),
Drone Interface, Encryption Module, Fire Control System (improved), Light Intensifier
Sensor (advanced), Radiation Environment Protection (+550 rads), Recon Sensor
(enhanced), Satellite Uplink, Self-Repairing Chassis, Spare Slot, Transceiver 500km
(enhanced), Vacuum Environment Protection, Voder Speaker, Weapon Mounts (medium)
x2, Weapon Mount Autoloaders (medium) x6, Wireless Data Link

**Floating Strongpoint**
A technological improvement of the Walking Strongpoint
(see page 144), the floating strongpoint is shaped
like a broad shield floating just above the ground. It
provides cover for an advancing fire team over any
terrain, overcoming one of its walking predecessor’s
weaknesses. Its camouflaged and armoured body
hinges out three to six metres wide when fully extended
and provides cover and firing slits for four soldiers.
Four medium-sized small arms bins hold up 10 extra
magazines each and one large bin can support a large
portable weapon’s reloads. The robot is equipped
with integral entrenching tools to help dig foxholes
and trenches for additional protection but its lack of
manipulators prevents it from using detached tools.

The unarmed strongpoint is equipped with upgraded
sensors and communications links and can stand guard
while its troops rest. The robot can operate in vacuum
and is well protected against radiation. It cannot help
its troops breathe but can act as a cover from radiation,
providing a directional 225 rads protection while
deployed and up to its full 1,100 rads protection if used
as a shield above a foxhole with its firing slits closed.

Robot Hits Locomotion Speed TL Cost
Floating Strongpoint 32 Grav 6m 12 Cr220000
Skills Melee (bludgeon) 1, Recon 3, Stealth 4, Tactics (military) 1
Attacks Crush (3D)
Manipulators —
Endurance 72 hours
Traits Alarm, Armour (+28), Flyer (idle), Heightened Senses, IR/UV Vision, Large (+1)
Programming Basic (security) (INT 4)
Options Auditory Sensor (broad spectrum), Camouflage: Visual (advanced), Construction Equipment
(medium), Drone Interface, Encryption Module, PRIS Sensor, Radiation Environment
Protection (+600 rads), Recon Sensor (advanced), Satellite Uplink, Self-Repairing Chassis,
Vacuum Environment Protection, Transceiver 5,000km (enhanced), Voder Speaker, Weapon
Mount Autoloader (heavy), Weapon Mount Autoloaders (medium) x4, Wireless Data Link

Flying Gun (small)
The ultimate in ‘smart gun’ technology is a robotic grav-
propelled gun with an Advanced robot brain. Designed
to back up boarding crews or police officers, it has
also found use as an assassination tool. Based on the
receiver of a personal defence laser, the small flying
gun has no grip or any accommodation for a biological
user. It is an armoured laser barrel with extra power
packs capable of quickly moving across a conflict zone
and providing automatic fire at short range.

Robot Hits Locomotion Speed TL Cost
Flying Gun, Small 4 Grav 12m 13 Cr87000
Skills Athletics (dexterity) 1, Gun Combat (energy) 2, Recon 2, Tactics (military) 3
Attacks Personal Defence Laser (3D+3, Auto 2, Zero-G) 525 shots
Manipulators —
Endurance 18 hours
Traits Armour (+7, +10 vs. lasers), Flyer (idle), Heightened Senses, IR/UV Vision, Small (-3)
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Drone Interface, PRIS Sensor, Reflec Armour,
Transceiver 50km (advanced), Vacuum Environment Protection, Voder Speaker, Weapon
Mount (small), Weapon Mount Autoloader (small), Wireless Data Link

**Flying Gun (medium)**
The medium flying gun is a grav-propelled stagger
laser rifle with extra power packs to allow 2,100 shots.
Small and fast, it is an automated support weapon with
enough intelligence to operate independently or as part
of a fire team. In the field, its major drawback besides
cost is its small size and light armour. While difficult to
hit by direct fire, it is susceptible to blast damage from
artillery. The shiny reflec-coated flying gun does have
significant deterrence value – if one suddenly appears
behind lines politely asking for troops to surrender,
compliance often follows.

Robot Hits Locomotion Speed TL Cost
Flying Gun, Medium 8 Grav 12m 14 Cr220000
Skills Athletics (dexterity) 1, Gun Combat (energy) 2, Recon 2, Tactics (military) 3
Attacks Stagger Laser Rifle (5D+3, Auto 3, Zero-G) 2,100 shots
Manipulators —
Endurance 18 hours
Traits Armour (+7, +10 vs. lasers), Flyer (idle), Heightened Senses, IR/UV Vision, Small (-2)
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Drone Interface, PRIS Sensor, Reflec Armour,
Transceiver 50km (advanced), Vacuum Environment Protection, Voder Speaker, Weapon
Mount (medium), Weapon Mount Autoloader (medium), Wireless Data Link

Flying Gun (large)
Using the same brain as its smaller cousins, the large
flying gun is built around a portable fusion gun, capable
of doing vast amounts of damage. Forgoing the shiny
reflec coating for heavy armour, a superior visilight
camouflage coating and sound-dampened grav units,
the large flying fusion gun can remain well hidden until
it fires. As miniaturisation and recoil were not primary
considerations, the human-sized gun platform is
surprisingly affordable at Cr280000 but the availability
of its radiation spewing fusion gun is strictly limited.
Forgoing the Cr100000 fusion gun, versions equipped
with slightly less restricted plasma weapons are also
available. The lack of an autoloader limits the platform’s
usability with projectile-firing weapon alternatives.

Robot Hits Locomotion Speed TL Cost
Flying Gun, Large 20 Grav 12m 14 Cr290000
Skills Athletics (dexterity) 1, Gun Combat (energy) 2, Recon 2, Stealth 4, Tactics (military) 3
Attacks Fusion Gun Human Portable (2DD, Very Bulky, Radiation) unlimited shots
Manipulators —
Endurance 18 hours
Traits Armour (+28), Flyer (idle), Heightened Senses, IR/UV Vision
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Camouflage: Audible (advanced), Camouflage: Visual
(superior), Drone Interface, PRIS Sensor, Radiation Environment Protection (+700 rads),
Transceiver 50 km (advanced), Vacuum Environment Protection, Voder Speaker, Weapon
Mount (heavy), Wireless Data Link

**Flying Sword**
The Flying Sword is simply a grav-propelled static
blade with a Hunter-Killer brain. With its robotic ‘guts’
embedded in the hilt, the Flying Sword can be used as a
hand-held weapon but is fully able to autonomously fight
a designated target and pursue with great speed and
agility, using cunning and sword-fighting techniques to
strike down prey. Whether let loose in the heat of battle or
released from afar to hunt its target, the flying sword is a
lethal weapon that sometimes sneaks through the legal
and customs cracks on worlds that prohibit firearms but
remain tolerant of ‘weapons of honour’. Equipped with a
reflec and armour-coated surface, it can ‘parry’ or absorb
damage but a direct penetrating hit knocks it down.

Robot Hits Locomotion Speed TL Cost
Flying Sword 1 Grav 12m 12 Cr53000
Skills Athletics (dexterity) 2, Melee (blade) 2, Recon 0, Tactics (military) 2
Attacks Static Blade (3D+2, AP 6)
Manipulators —
Endurance 22 hours
Traits Armour (+7, +10 vs. lasers), Flyer (idle), Heightened Senses, IR/UV Vision, Small (-4)
Programming Hunter/Killer (tactical) (INT 4)
Options Auditory Sensor (broad spectrum), Drone Interface, Fire Control System (improved), PRIS
Sensor, Reflec Armour, Transceiver 50km (enhanced), Vacuum Environment Protection,
Voder Speaker, Weapon Mount (small), Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Grav Mule Drone 72 Grav -— 10 Cr300000
Skills Athletics (dexterity) 1, Stealth 2
Attacks —
Manipulators —
Endurance 24 (6) hours
Traits Armour (+16), Flyer (high), Large (+3)
Programming Primitive (evade) (INT 1)
Options Auditory Sensor, Drone Interface, Storage Compartment (107 Slots), Transceiver 500km
(improved), Visual Spectrum Sensor, Voder Speaker, Weapon Mount Autoloaders (medium)
x3, Wireless Data Link

Grav Mule
Grav Mule is an enlarged and grav-mobile version
of the Battle Mule drone intended for resupply and
casualty evacuation missions. When configured for
resupply operations the unit can carry more than 200
kilograms of supplies, with one or more field reloading
kits slotted into place. Equipment bays along the sides
allow quick deployment of necessary items or can carry
additional systems such as sensor jammers, decoy
launchers and the like. Using high-speed nap-of-earth
flight, the Grav Mule can get supplies to a surrounded
unit under conditions where a crewed vehicle would
face too much risk.

Alternatively, the drone can be set up for casualty
evacuation. A pair of slide-out stretchers are always
fitted and a life support pack for each can be quickly
installed. Once in place, two casualties can be slid into a
Grav Mule’s armoured box and transported – safely but
claustrophobically – to the rear for treatment.

**Grav Pioneer**
Grav Pioneer is an obstacle-clearance drone taking
the form of a one-metre radius disc using grav
propulsion that eats power, requiring recharging
every six hours of use. The primary function of Grav
Pioneer is to clear mines and improvised explosive
devices. It carries an array of sensors for the
purpose and can detonate mines with a specialised
weapon located in a turret on the underside of the
disc. The usual projectile is a heavy penetrator or
small explosive charge, although a multiple projectile
round is available. Grav Pioneer is not programmed
to fire on personnel but can be tricked by a skilled
operator or hacked and reprogrammed. Some
units use Pioneers as security bots in this manner
but unfortunate incidents do occur as a result of

incomplete or buggy coding. If firing on personnel,
the weapon is treated as a heavy smoothbore firing
pellet ammunition, which was developed for the safe
destruction of explosive devices.

Its grav drive is programmed to ‘make the drone
light’ in the event of a pressure wave such as that
caused by an exploding mine. This means the drone
is more likely to be tossed about than damaged
and takes half damage from Blast weapons. A
pair of retractable arms, one ending in powerful
cutters, allows the clearance of wire and similar light
obstacles. Heavier obstructions can sometimes be
reduced by firing the drone’s explosive ammunition
into them in the hope of shaking the obstacle apart.

Robot Hits Locomotion Speed TL Cost
Grav Pioneer 20 Grav — 10 Cr100000
Skills Athletics (dexterity) 2, Gun Combat 0, Melee 0, Recon 2
Attacks Cutting Tool (2D), Explosive Projectiles (as grenade)
Manipulators 2x (STR 9 DEX 6)
Endurance 24 (6) hours
Traits Armour (+8), Flyer (high), Heightened Senses, IR Vision
Programming Basic (recon) (INT 4)
Options Auditory Sensor (broad spectrum), Drone Interface, Environment Processor, Light Intensifier
Sensor (advanced), Recon Sensor (enhanced), Transceiver 500km (improved), Visual
Spectrum Sensor, Voder Speaker, Weapon Mount (medium), Weapon Mount (small), Weapon
Mount Autoloader (medium), Wireless Data Link, Spare Slots x3

**Keshean Gaa – Type 21**

**Ordnance Handling Robot**
The Type 21 is semi-officially designated Keshean
Gaa, from a Vilani phrase for someone who always
gets the heaviest load or most difficult job. It takes
the form of a six-wheeled trolley with a central cradle,
surrounded by manipulator arms. The cradle is long
enough to accommodate a standard missile or torpedo
and self-adjusts to hold configurations firmly in place.
Wheeled rather than gravitic drive was chosen to
reduce the chance of drift as the unit aligns itself with
missile hoists and loading rams, although there is
a persistent rumour that the original ‘floater’ design
simply made crews uneasy as it zipped about with a
ship-killing missile aboard.

Robot Hits Locomotion Speed TL Cost
Keshean Gaa 52 Wheels 3m 13 Cr21000
Skills Mechanic 0
Attacks —
Manipulators 4x (STR 13 DEX 8)
Endurance 130 hours
Traits Armour (+4), Large (+2)
Programming Advanced (INT 8)
Options Auditory Sensor, Storage Compartment (48 Slots), Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless Data Link

Ordnance handling bots are used to move missiles
from hoists to loading rams, ready for launch. They can
also be used to move missiles around the ship, from
one magazine to another. When in the cradle, the bot’s
systems will check the arming pin slots and if empty the
bot inserts its own pins – a missile carried by a properly
functioning handler bot is inert and simply cannot
detonate or fire its drive. Neither can the bot move with
a live missile in place – if a pin is somehow removed,
the bot locks its drive and calls for crew assistance.

The cradle is designed to hold missiles but can
reconfigure itself to accommodate a range of other
ordnance. Anything from small arms to artillery shells
can be carried aboard these units, although inefficiently
in this role.

**Long Duration Security Robot**
The Long Duration Security Robot is a basic design for
autonomous operation at remote locations with limited
facilities. Equipped with an RTG power source, it can
maintain its patrol for decades without replacement
or relief, while self-maintenance features allow it to
operate until its power source runs low. Equipped with
a submachinegun for close assault and three bins for

Robot Hits Locomotion Speed TL Cost
Security Robot 14 Wheels 12m 11 Cr560000
Skills Gun Combat (slug), Recon 1, Tactics (military) 1
Attacks Submachinegun (3D, Auto 3) 620 rounds
Manipulators —
Endurance 25-year half-life RTG (22 hours)
Traits Alarm, Armour (+3), IR Vision, Small (-1)
Programming Basic (security) (INT 4)
Options Auditory Sensor, Drone Interface, Recon Sensor (improved), RTG Long Duration (basic), Self
Maintenance Enhancement (improved), Thermal Sensor, Transceiver 500km (enhanced), Voder
Speaker, Weapon Mount (medium), Weapon Mount Auto Loaders (small) x3, Wireless Data Link

autopistol compatible ammunition, it patrols a designated
perimeter on fast wheels and defends its position with
lethal force, although those who flee are not pursued
beyond the perimeter. With its power source accounting
for the majority of its cost, these robots are not generally
encountered in civilised settings but often found
defending mining claims and supply depots on desolate
planets across Charted Space.

**Naasirka Model 899**

**Security Support Robot**
The Imperium is firmly opposed to the use of
‘warbots’ and autonomous armed systems in general.
However, a need was perceived for a robotic platform
to support defensive operations and boarding
parties; the Model 899 was the result. Examples
are available for sale to private operators, who can
demonstrate suitable need and accountability, but by
far the largest buyer is the Imperial Navy.

A Model 899 is a gravitic-supported robot taking the
form of an upright cylinder with rounded ends and
a central bulge. This contains a pair of manipulator
arms, fire extinguisher and cutting torch capable
of making a path through a shipboard bulkhead or
even a lightly armoured hull, although not quickly.
The robot is most commonly used as a fetch-and-
carry device for security patrols and boarding parties,
carrying heavy items of equipment or the infamous
‘contraband bag’.

Far more Model 899s have seen action during
firefighting and rescue operations than in shipboard
gunfights but, when necessary, the robot can unfurl
its casing panels above and below the central bulge,
creating an instant position of cover, which can be
advanced or cover a retreat. The top and bottom of
the cylinder contain basic sensors and cargo space,
which is typically used to carry ammunition and
emergency supplies for the security party.

Robot Hits Locomotion Speed TL Cost
Naasirka Model 899 36 Grav 5m 13 Cr60000
Skills Mechanic 0
Attacks —
Manipulators 2x (STR 11 DEX 8)
Endurance 40 hours
Traits Armour (+6), Flyer (idle), Large (+1)
Programming Advanced (INT 8)
Options Auditory Sensor, Cutting torch (improved), Drone Interface, Fire Extinguisher, Storage
Compartment (24 Slots), Transceiver 5 km (improved), Visual Spectrum Sensor, Voder
Speaker, Wireless Data Link

**Peacekeeper Riot Control Robot**
Focusing on non-lethal restraint, the
Makhidkarun-produced Peacekeeper is a
grav-propelled robot intended for crowd control
and riot suppression. Armed with a short-
ranged stunner and two extra arms equipped
with stun sticks to control and subdue rioters,
the Peacekeeper can fly low over crowds and
break up riots and demonstrations.

Although equipped with a drone interface for
override control, the Peacekeeper is intended
to be fully autonomous, basing decisions
and actions on parameters and regulations
supplied by local law enforcement. With an
advanced brain, it is much more subtle than a
Hunter/Killer and able to engage in reasoned
conversations with opposing parties, but relies
on its stun weapons for persuasion when
instructions to disperse are not followed.

The Peacekeeper is normally brightly
coloured in local police insignia, although
some departments choose a more sinister
urban camouflage or black colour scheme;
Makhidkarun sales brochures emphasise a
more friendly approach and point to alternative
uses for the Peacekeeper, including search
and rescue – employing the cutting torch, fire
extinguisher and medikit features.

Robot Hits Locomotion Speed TL Cost
Peacekeeper Riot
Control Robot

20 Grav 9m 12 Cr150000

Skills Athletics (dexterity) 1, Athletics (strength) 1, Gun Combat (energy) 2, Medic 0, Melee
(bludgeon) 2, Recon 2, Tactics (military) 1
Attacks Stunner (TL12) (3D, Stun, Zero-G), Stunsticks x2 (2D, Stun)
Manipulators 2x (STR 9 DEX 7), 2x (STR 5 DEX 9)
Endurance 29 hours
Traits Armour (+13), Flyer (idle), IR/UV Vision
Programming Advanced (INT 8)
Options Auditory Sensor, Cutting Torch (improved), Drone Interface, Encryption Module, Fire
Control System (improved), Fire Extinguisher, Medikit (improved), PRIS Sensor, Recon
Sensor (enhanced), Self-Repairing Chassis, Tightbeam Communicator, Transceiver 50km
(enhanced), Voder Speaker, Weapon Mounts (small) x3, Wireless Data Link

**Security Drone**
With long-running power sources, security drones are
used by corporations and government installations to
protect semi-sensitive buildings and compounds. Once
programmed with territory to patrol, groups of security
drones roam the area with the intention of warding off
anyone who does not match pre-programmed criteria.
They can be updated on the fly and communicate with
one another for best effect when under threat but are
typically configured to use violence only when provoked.
However, it only takes a mechanic of medium skill to
change their weaponry to something far more lethal.

Robot Hits Locomotion Speed TL Cost
Security Drone 26 VTOL 6m 10 Cr670000
Skills Gun Combat (energy) 1, Melee (bludgeon) 1, Recon 2, Tactics (military) 1
Attacks Stunner (2D+3, Stun, Zero-G), Stunstick (2D+3, Stun)
Manipulators —
Endurance 25-year half-life RTG (22 hours)
Traits Alarm, Armour (+6), Flyer (idle), IR Vision
Programming Basic (security) (INT 4)
Options Auditory Sensor, Drone Interface, Light Intensifier Sensor (advanced), Recon Sensor
(enhanced), RTG Long Duration (basic), Self-Maintenance Enhancement (basic), Spare Slots
x5, Transceiver 5km (improved), Voder Speaker, Weapon Mounts (small) x2, Wireless Data Link

Shadow Security Robot
The Shadow Security Robot is designed to patrol
outside installations, using multi-chromatic and multi-
sensory camouflage to blend into any environment from
vacuum plains to thick jungle. Equipped with advanced
sensors, gecko grippers and a self-repairing chassis,
the Shadow is designed for survivability and usually
gets off the first shot with its integral chest-mounted
laser rifle, then closes to melee range and engages
with sharpened manipulators.

The Shadow is highly intelligent, able to plan ambushes
and smart enough to retreat and strike later if the odds are
against it, notifying companions or masters of intruders. Its
camouflage and stealth characteristics grant DM-4 versus
visual detection and DM-3 versus electronic, auditory and
olfactory detection devices.

Robot Hits Locomotion Speed TL Cost
Shadow Security Robot 21 Walker 9m 12 Cr300000
Skills Athletics (dexterity) 2, Athletics (strength) 1, Gun Combat (energy) 3, Melee (unarmed)
3, Navigation 2, Recon 3, Stealth 4, Tactics (military) 3
Attacks Laser Rifle (5D+3, Zero-G), Claws (1D+2 )
Manipulators 2x (STR 9 DEX 12)
Endurance 173 hours
Traits Armour (+13), ATV, Heightened Senses, IR/UV Vision, Stealth (+3)
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Camouflage: Audible (advanced), Camouflage:
Olfactory (advanced), Camouflage: Visual (advanced), Drone Interface, Fire Control System
(enhanced), Gecko Grippers, Navigation System (improved), Olfactory Sensor (improved),
PRIS Sensor, Radiation Environment Protection (+600 rads), Recon Sensor (advanced),
Self-Repairing Chassis, Stealth (enhanced), Transceiver 500km (enhanced), Vacuum
Environment Protection, Voder Speaker, Weapon Mount (medium), Wireless Data Link

**Sindalian Deathbot**
The Sindalian Empire was one of the few interstellar
powers to actually have a robot type designated
‘deathbot’. The term was apparently used without
a trace of irony or self-consciousness, although
nowadays it generates hilarity in those who have never
encountered one.

Various designs are known to have existed but the
commonest seems to have been a light anti-personnel
unit intended for intimidating civilian populations or holding
families of key personnel hostage. Built on a generally
ovoid shape, decorated with intricate but jagged and
threatening abstract art, the deathbot is designed to be
constantly noticed – it is a threat rather than an assassin
or warbot, although can be used as either.

Primary anti-personnel armament consists of twin laser
carbines facing forward, along the longest axis of the
ovoid. Laser ports flank the deathbot’s other weapon,
an advanced light plasma gun capable of engaging
armoured personnel. When not in use this weapon is
completely concealed and its presence may not be
suspected by those unfamiliar with the design. One
round is required to deploy the light plasma gun and
the deathbot’s Protection is reduced to +4 when the
recessed bay is open.

A deathbot can also make a ‘ram and rip’ attack, using
its baroque outer casing as a weapon by rotating its long
axis as it smashes into a target.

Robot Hits Locomotion Speed TL Cost
Sindalian Deathbot 28 Grav 8m 15 Priceless Artefact
Skills Gun Combat (energy) 1, Melee 0, Recon 0
Attacks Light Plasma Gun (6D, range 20m), Ram & Rip (3D), Twin-linked Laser Carbine (4D+4, Zero-G)
Manipulators 2x (STR 9 DEX 9)
Endurance 38 hours
Traits Armour (+8), Flyer (idle)
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control System (basic), Transceiver 500km (advanced), Visual
Spectrum Sensor, Voder Speaker, Weapon Mounts (medium) x3, Wireless Data Link

Deathbots were, curiously enough, status symbols in the
old Sindalian Empire. Anyone important enough to have
their own was well respected but equally if the empire
cared enough about your loyalty to deploy several
deathbots for the sole purpose of being able to massacre
your family, friends and associates at a moment’s
notice... that also was a symbol of importance. It says
much about the nature of the old empire that being
followed around by your potential executioner was seen

- at least some of the time – as a good thing.

**Sindalian Enforcement Robot**
Copies of this ancient Sindalian Empire robot are still
sometimes encountered and here and there an original
might be found. It resembles a very thick, flat-topped
80-centimetre-square table with four articulated legs
and is occasionally used as one by people who find
that sort of thing amusing. When required, the rotating
turret pops out of a recess, clearing the weapons for
action. The primary weapon system is a laser carbine.

Robot Hits Locomotion Speed TL Cost
Sindalian Enforcement Robot 18 Walker 6m 15 Cr27000
Skills Gun Combat (energy) 1, Recon 0
Attacks Laser Carbine (4D, Zero-G)
Manipulators —
Endurance 130 hours
Traits Armour (+4), ATV
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control System (basic), Transceiver 500km (advanced), Visual
Spectrum Sensor, Voder Speaker, Weapon Mount (medium), Wireless Data Link

Spider Bomb
A small robot that, by definition, is expendable, the
spider bomb is intended to race across a battlefield
and explode next to a target. The target is usually
programmed on the fly but the spider bomb is capable
enough to pursue if its location changes. Spider bombs
can also be programmed to explode immediately upon
taking damage, although care must be taken to avoid
‘own goals’.

Robot Hits Locomotion Speed TL Cost
Spider Bomb 4 Walker 10m 12 Cr21000
Skills Athletics (dexterity) 1, Explosives 1, Recon 1
Attacks TDX (4D, Blast 15)
Manipulators —
Endurance 65 hours
Traits Armour (+8), ATV, Small (-3)
Programming Basic (target) (INT 4)
Options Auditory Sensor, Drone Interface, Recon Sensor (improved), Self-Destruct System: TDX,
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**Trapper Hunter Droid (THD)**
A relatively primitive flying robot, the VTOL eight-rotor
Trapper Hunter Droid (THD) was originally marketed
as an airborne range control droid able to round up
groat herds and disable or capture small predators. It
soon found use as a hunting scout, able to locate and
flush out prey. However, the majority of THD units have
found a home in law enforcement on mid-tech worlds
as riot control and prison guard units.

The disk-shaped THD has two hanging arms ending
in hands with embedded stun sticks. A short-ranged
stunner mounted on a downward-facing turret allows
the THD to incapacitate targets from beyond its reach
but for longer work the THD’s main weapon is a fixed
mounted grenade launcher. The launcher normally

Robot Hits Locomotion Speed TL Cost
Trapper Hunter Droid 20 VTOL 9m 8 Cr81000
Skills Gun Combat (energy) 1, Heavy Weapon (portable) 1, Melee (bludgeon) 1, Navigation 1,
Recon 1, Tactics (military) 2
Attacks Grenade Launcher (variable), Stunner (TL8) (2D, Stun, Zero-G), Stunsticks x2 (2D, Stun)
Manipulators 2x (STR 9 DEX 6)
Endurance 14 hours
Traits Armour (+7), Flyer (idle), Heightened Senses, IR Vision
Programming Hunter/Killer (tactical) (INT 3)
Options Auditory Sensor (broad spectrum), Drone Interface, Fire Control System (basic), Light
Intensifier Sensor (basic), Navigation System (basic), Olfactory Sensor (basic), Recon
Sensor (improved), Thermal Sensor, Transceiver 50km (improved), Visual Spectrum
Sensor, Voder Speaker, Weapon Mount (medium), Weapon Mounts (small) x3, Weapon
Mount Autoloader (medium), Wireless Data Link

fires weighted nets rather than grenades, limiting
effective range to 20 metres. An autoloader and
ammunition bay holds up to 66 grenades. Nets leave
targets entangled but the THD does not normally try to
retrieve the net and its prey, leaving them for ground
units to subdue. The VTOL motors lack the power
to carry more than 20 kilograms of extra mass in a
standard gravity and atmosphere environment.

Some users replace the net grenades for smoke,
stun or tranq grenades but the manufacture
discourages lethal grenade use as it prevents
the THD from being designated non-lethal under
restrictive robot regulations.

**Urban Pacification Police Robot**
Billed as the next stage in law enforcement,
urban pacification models introduced
into police departments on some worlds
have been controversial to say the least.
Equipped to fight a small war, they are
capable of storming any criminal hideout
and destroying resistance. However, when it
comes to lighter duties, critics point to their
limited programming and the deaths that
have resulted from contact with the public.

Robot Hits Locomotion Speed TL Cost
Urban Pacification
Police Robot

80 Walker 8m 12 Cr460000

Skills Athletics (endurance) 1, Heavy Weapon (vehicle) 3, Recon 1, Tactics (military) 2
Attacks Light Autocannons x2 (linked: 6D+6, Auto 3) 5,500 shots each, Light Autocannons x2 (linked:
6D+6, Auto 3) 5,500 shots each
Manipulators —
Endurance 302 hours
Traits Armour (+18), ATV, Large (+3)
Programming Hunter/Killer (tactical) (INT 4)
Options Auditory Sensor, Drone Interface, Encryption Module, Fire Control Systems (enhanced) x2,
Recon Sensor (improved), Satellite Uplink, Transceiver 500km (enhanced), Visual Spectrum
Sensor, Voder Speaker, Weapon Mounts (vehicle) x4, Weapon Mount Autoloaders (vehicle)
x4, Wireless Data Link

**Walking Strongpoint**
Shaped like a broad shield on legs, the walking
strongpoint provides cover for an advancing
fire team. Its camouflaged and armoured body
hinges out from three to six metres broad when
fully extended and provides cover and firing slits
for four soldiers, although shooting through the
narrow firing ports is difficult while moving. Four
medium-sized small arms bins hold 10 extra
magazines each and one large bin can hold
ammunition for a large portable weapon, such
as a machinegun or auto-grenade launcher. The
robot is equipped with integral entrenching tools
to help dig foxholes and trenches for additional
protection but lacks manipulators to operate
detached tools.

The strongpoint is not armed itself but is
equipped with recon sensors and a sophisticated
communications link. The robot can operate in
vacuum and is well protected against radiation.
It cannot help troops breathe but can act as
cover from radiation, providing a directional 213
rads protection while deployed and up to its full
1,050 rads protection if used as a shield above a
foxhole with firing slits closed. Its major drawback
is its short legs; the body extends low to the
ground and its four legs have difficulty with rocky
terrain, negating its ATV advantage in certain
environments, although it is well able to negotiate
steep slopes and muddy fields.

Robot Hits Locomotion Speed TL Cost
Walking Strongpoint 32 Walker 6m 11 Cr160000
Skills Melee (bludgeon) 1, Recon 2, Stealth 3, Tactics (military) 1
Attacks Crush (3D)
Manipulators —
Endurance 65 hours
Traits Alarm, Armour (+19), ATV, IR Vision, Large (+1)
Programming Basic (security) (INT 4)
Options Auditory Sensor, Autoloader (heavy), Camouflage, Construction Equipment (medium),
Drone Interface, Encryption Module, Light Intensifier Sensor (advanced), Satellite Uplink,
Self-Repairing Chassis, Radiation Environment Protection (+550 rads), Recon Sensor
(enhanced), Transceiver 500km (enhanced), Vacuum Environment Protection, Visual
(enhanced), Voder Speaker, Weapon Mount Autoloaders (medium) x4, Weapon Mount
Wireless Data Link

## S ERVICE ROBOTS

Service robots perform tasks to supplement or supplant biological beings in roles requiring interaction with other
beings. Most service robots are focused on a specific skill or profession, such as a Medic, Steward or Administrator.

Angel of Mercy
The Angel of Mercy is a flying autodoc, designed
to extract and transport a victim from a hazardous
situation, whether disaster or battlefield. An armoured
rounded box-like robot designed to fit into a standard
low berth slot, the Angel of Mercy combines the power
of an autodoc with the features of a search and rescue
robot. Advanced sensors can locate its prospective
patient even buried in rubble. With two external arms
to complement its internal surgical arms, a compact
collection of construction tools designed for exaction and
two vibro-axe blades to act as ‘jaws of life’, the Angel
of Mercy can be encountered in high-tech emergency
services departments and well-equipped combat
units. Armoured and capable of anticipating battlefield
conditions, the Angel of Mercy is usually clearly marked
as non-combatant and coated in reflec armour for both
protection and easy visibility. It is capable of extracting a
victim and beginning treatment as a standard autodoc.
Equipped with vehicle-grade grav locomotion, it can
exceed 200 kilometres per hour in level flight and
operate in vacuum and most non-corrosive
atmospheric conditions.

The Angel of Mercy lacks the storage capacity and
bioreactor of the standard autodoc and has no room
for additional features but can perform all immediate

Robot Hits Locomotion Speed TL Cost
Angel of Mercy 50 Grav — 13 Cr310000
Skills Athletics (strength) 2, Medic 3, Melee 0, Recon 0, Science (biology) 2, Tactics (military) 1
Attacks Static Axes x2 (4D+2, AP 8, Smasher)
Manipulators 2x (STR 12 DEX 8), 2x (STR 6 DEX 9)
Endurance 36 (9) hours
Traits Armour (+10, +10 vs. lasers), Flyer (high), Heightened Senses, Large (+2), IR/UV Vision,
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Construction Equipment (small), Drone Interface,
Environment Processor, Medical Chamber (50 Slots), Medikit (enhanced), Olfactory Sensor
(advanced), PRIS Sensor, Reflec Armour, Storage Compartment (2 Slots refrigerated),
Transceiver 500km (enhanced), Vacuum Environment Protection, Voder Speaker, Weapon
Mounts (small) x2, Wireless Data Link

tasks, including first aid and field surgery, while on
the fly, transporting its charge to a better-equipped
facility if further care is necessary. It has enough
refrigerated storage capacity to be fully stocked with
medical drugs, including Fast Drug for instances when
a patient’s wounds are too serious to address.

**Astro-Mech Droid**
When astro-mech droids first appear, they are expensive
and very advanced but as a technological society
grows they often fade into the background and become
ubiquitous. An astro-mech droid is designed to be a small
spacecraft’s best friend, primarily being used to plot jumps
and perform maintenance.

However, these droids are extremely adaptable and they
learn fast, tending to be limited only by their distinctly
nonhumanoid construction. They come equipped with
a variety of tools and equipment stored within their
cylindrical frames.

Robot Hits Locomotion Speed TL Cost
Astro-Mech Droid 18 Wheels 5m 14 MCr1
Skills Astrogation 3, Deception 1, Electronics (computers) 3, Engineer (power) 3, Mechanic 3,
Melee 0, Pilot (spacecraft) 1
Attacks Stunstick (2D, Stun)
Manipulators 1x (STR 9 DEX 8)
Endurance 108 hours
Traits Armour (+6)
Programming Very Advanced (INT 11)
Options Auditory Sensor, Construction Equipment (small), Densitometer Sensor, Electronics Toolkit
(advanced), Holographic Projector, Industrial Cleaning Equipment (small), PRIS Sensor,
Self-Maintenance Enhancement (basic), Starship Engineer Toolkit (advanced), Storage
Compartment (2 Slots hazardous material), Transceiver 500km (advanced), Vacuum
Environment Protection, Voder Speaker, Weapon Mount (small), Wireless Data Link

Autodoc, Basic
The basic autodoc found in smaller medical facilities and
starships is a large coffin-shaped box capable of holding
an adult human or similarly sized lifeform. It is usually
topped in a sealable transparent cover and mounted
directly into a facility, connected to local power, although
capable of independent operations for nearly two weeks.

The robot’s small but precise manipulator arms are
mounted inside the chamber, allowing it to operate on
a subject placed within but unable to load a subject into
its medical chamber without external assistance. In
addition to a diagnostic and surgical medikit, the autodoc
includes a small bioreactor for growing biological
samples and creating simple biological constructs such
as tissues, and a refrigerator stocked with common
medical supplies. The autodoc does not have a head
but has sensory organs built into its manipulator arms to
allow it to carefully control surgical procedures.

Spare slots allow for the expansion of the medical
chamber to accommodate larger beings, the installation
of cryoberth or low berth options, species-specific add-
ons or advanced bioreactors.

Robot Hits Locomotion Speed TL Cost
Autodoc, basic 50 — 0m 13 Cr100000
Skills Medic 3, Science (biology) 2
Attacks —
Manipulators 2x (STR 7 DEX 9)
Endurance 324 hours
Traits Armour (+4), Large (+2)
Programming Advanced (INT 9)
Options Auditory Sensor, Bioreaction Chamber (2 Slots improved), Medical Chamber (50 slots),
Medikit (enhanced), PRIS Sensor, Spare Slots x32 Storage Compartment (3 Slots), Storage
Compartment (3 Slots refrigerated), Transceiver 5km (improved), Vacuum Environment
Protection, Voder Speaker, Wireless Data Link

**Autodoc, Improved**
The improved autodoc is similar in appearance to its
basic counterpart but its medical chamber includes
additional functionality to allow for the reanimation
of a dead patient if quickly inserted within the
chamber or preserved by other means prior to
arrival. It includes low berth functionality to preserve
a critically injured patient or, on some ships, it can
act as an extra low berth to squeeze out additional
revenue. The improved autodoc includes an
advanced bioreaction chamber able to rapidly repair
or regrow damaged limbs or organs. A sophisticated
biology skillset allows the autodoc to better deal
with difficult situations, such as novel diseases and
destructive microbes.

Robot Hits Locomotion Speed TL Cost
Autodoc, improved 50 None 0m 14 MCr1
Skills Medic 3, Science (biology) 3
Attacks —
Manipulators 2x (STR 6 DEX 12)
Endurance 324 hours
Traits Armour (+4), Large (+2)
Programming Advanced (INT 9)
Options Auditory Sensor, Bioreaction Chamber (10 Slots advanced), Medical Chamber (50 Slots),
Medical Chamber Option: Low berth (improved), Medical Chamber Option: Reanimation,
Medikit (advanced), PRIS Sensor, Scientific Toolkit (advanced), Spare Slots x8, Storage
Compartment (2 Slots), Storage Compartment (3 Slots refrigerated), Transceiver 5 km
(improved), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

Autodoc, Advanced
The advanced autodoc, includes a more
sophisticated brain than previous models, a small
fabrication chamber capable of printing out biological
and cybernetic parts, and a full suite of scientific
instruments including a bioscanner and neural
activity sensor. Its advanced brain is equipped with
an Investigate skill package and detailed knowledge
of both biology and chemistry, allowing it to diagnose
novel illnesses and develop treatments.

The deluxe autodoc is capable of great feats, able
to reconstruct every organ but the brain – and even
some parts of the brain - but it can only repair, not
improve a body.

Robot Hits Locomotion Speed TL Cost
Autodoc, advanced 50 None 0m 15 MCr3
Skills Investigate 4, Medic 4, Science (biology) 4, Science (chemistry) 4, +1 available Bandwidth
Attacks —
Manipulators 2x (STR 6 DEX 12)
Endurance 432 hours
Traits Armour (+4), Large (+2)
Programming Self-aware (INT 12)
Options Auditory Sensor, Bioscanner Sensor, Drone Interface, Fabrication Chamber (10 Slots
enhanced), Medical Chamber (50 Slots), Medical Chamber Option: Low berth (improved),
Medical Chamber Option: Reanimation, Medikit (advanced), Neural Activity Sensor, PRIS
Sensor, Scientific Toolkit (advanced), , Spare Slots x4, Storage Compartment (2 Slots
refrigerated), Transceiver 5km (improved), Vacuum Environment Protection, Voder Speaker,
Wireless Data Link

**BandBot**
The BandBot was conceived as a backup singer or
instrumentalist to accompany live music acts but
has found a niche as an autonomous performer or
member of a group of robotic performers. Designed to
sing or play an instrument but unable to do both well,
the robot also includes a high-fidelity sound system
with a holographic projector, 2D video screen and
projector for special effects. Its 12 spare Slots allow
it to carry instruments or equipment and its agility
allows it to dance to music and perform some stunts.
Programming for specific performance or instrumental
skills is normally installed at purchase. Changing the
software skill package is expensive at Cr50000 but
allows the robot to immediately acclimate to its new
skill after a reboot.

Robot Hits Locomotion Speed TL Cost
BandBot 20 Walker 6m 12 Cr97000
Skills Art (performer or instrument) 2, Athletics (dexterity) 1, Athletics (strength) 1
Attacks —
Manipulators 2x (STR 9 DEX 9)
Endurance 108 hours
Traits Armour (+4), ATV, Heightened Senses
Programming Advanced (INT 8)
Options Auditory Sensor (broad spectrum), Drone Interface, High Fidelity Sound System
(advanced), Holographic Projector, Spare Slots x12, Transceiver 5km (improved), Video
Projector, Video Screen (advanced), Visual Spectrum Sensor, Voder Speaker (broad
spectrum), Wireless Data Link

BDVSR Bartender Robot
The Beverage Dispensary/Venue Security Robot or
BDVSR, often referred to as the ‘Bartender robot’ is
a four-armed bipedal robot optimised for autonomous
operation of bars and mobile or pop-up establishments.
The Bartender robot normally operates with an external
beverage dispenser, such as a full bar or beverage
cart, but has an autobar installed in its torso, with
beverage dispenser nozzles and a 10-litre capacity
integral refrigerated container that can hold up to 20
different beverages at a variety of temperatures. Spare
capacity amounting to another eight litres allows for
custom installation of additional dispensers or other
specialised features. A vacuum/blower feature and
internally stored mops and brushes allow the robot to
keep its dispensation area clean.

With four arms, the BDVSR can dispense multiple
drinks simultaneously but its two stronger arms serve
the additional purpose of maintaining ‘venue security’,
namely removing unruly patrons from the vicinity.
Normally it performs this task with the utmost courtesy
but owners may program different personalities and
the robot itself tends to develop quirks over time. It is
a decent conversationalist but lacks deep insight into
human behaviour.

Robot Hits Locomotion Speed TL Cost
Bartender 20 Walker 6m 12 Cr73000
Skills Athletics (dexterity) 1, Athletics (strength) 2, Melee 0, Steward 2
Attacks Fists (2D )
Manipulators 2x (STR 12 DEX 7), 2x (STR 9 DEX 9)
Endurance 108 hours
Traits Armour (+4), ATV, Heightened Senses
Programming Advanced (INT 8)
Options Auditory Sensor, Autobar (advanced), Domestic Cleaning Equipment (small), Olfactory Sensor
(advanced), Storage Compartment (5 Slots refrigerated), Spare Slots x4, Transceiver 5km
(improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**BeautyBot**
The four-armed, wheeled BeautyBot is a common sight
in salon booths on high tech worlds and is often found
off the concourse in many starports. Equipped with a
complete set of stylist, grooming and cleaning tools,
the BeautyBot can provide most beautician services
with skill and efficiency. A video screen and holographic

Robot Hits Locomotion Speed TL Cost
BeautyBot 20 Wheels 5 m 12 Cr55000
Skills Profession (domestic cleaner) 0, Profession (stylist) 2, Steward 0
Attacks —
Manipulators 4x (STR 9 DEX 9)
Endurance 108 hours
Traits Armour (+4), Heightened Senses
Programming Advanced (INT 8)
Options Auditory Sensor, Domestic Cleaning Equipment (medium), Drone Interface, Holographic
Projector, Olfactory Sensor (improved), , Spare Slots x4, Stylist Toolkit, Transceiver 5km
(improved), Visual Spectrum Sensor, Video Screen (advanced) Voder Speaker, Wireless
Data Link

projector allows the BeautyBot to display the latest
styles and let the customer see how each would look
on them. Four spare Slots allow for the installation of
a second species-specific set of stylist tools or other
options to help customers look their best.

BandBot BeautyBot

BDVSR Bartender Robot

**Brokerbot**
The Makhidkarun B12 Brokerbot is an expert broker
designed for the interstellar trade market. Originally
designed as a specialist in gourmet foods, the robot’s
updated programming allows it to function as a broker
of any sort of merchandise, although its well-developed
olfactory sensor gives it an edge in procuring and
evaluating fine food and drink. Of basically humanoid
appearance and possessing an upper-class accent, it
can seem like a snobbish know-it-all to some observers
but it is a keen negotiator, able to take notice of micro-
expressions and use them to gain an advantage in
tense negotiations. A sophisticated communication
system allows it to securely converse with its head
office or a ship planetside or in orbit.

With its satellite uplink antenna and tightbeam
communicator embedded in its head behind an opaque
screen, it will often position itself near a window to
complete a communications task, an idiosyncrasy some
opposing brokers try to exploit. However, encrypted
communications through regular radio waves can
penetrate most solid buildings and is nearly impossible
to decipher even if intercepted.

A Brokerbot tends to develop a distinct personality over
time, using its available ‘hobby’ expansion capabilities
to study some esoteric topic that might make for good
conversation or give it an edge when procuring odd
goods on obscure worlds.

Despite its high cost and sometimes difficult personality,
the Brokerbot, with its knowledge of trade law and
local regulations, is highly sought after by independent
traders seeking an extra edge and can often pay
for itself many times over in increased profits during
speculative trade activities.

Robot Hits Locomotion Speed TL Cost
Brokerbot 20 Walker 6m 12 Cr710000
Skills Admin 3, Advocate 3, Broker 3, Carouse 2, Investigate 2, Persuade 1
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 97 hours
Traits Armour (+4), ATV, Heightened Senses
Programming Very Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Encryption Module, Olfactory Sensor (improved),
Satellite Uplink, Spare Slots x10, Storage Compartment (2 Slots refrigerated),
Tightbeam Communicator, Transceiver 5,000km (enhanced), Visual Spectrum Sensor,
Voder Speaker, Wireless Data Link

Cloning Creche
A cloning creche looks like an autodoc or low berth but is
equipped with an enhanced bioreaction chamber rather
than a standard medical chamber. The cloning creche is
designed to bring an accelerated clone to toddlerhood
and aid in accelerated growth, allowing the clone to reach
adulthood in 18 months. The creche becomes the bed for
the developing clone, monitoring and guiding growth and
often providing companionship and basic education.

Robot Hits Locomotion Speed TL Cost

Cloning Creche 50 None 0m 10 Cr350000

Skills Medic 0, Profession (child development) 1, Science (biology) 1

Attacks —

Manipulators 2x (STR 7 DEX 7)

Endurance 216 hours

Traits Armour (+3), Large (+2)

Programming Advanced (INT 6)

Options Auditory Sensor, Bioreaction Chamber (50 Slots enhanced), Drone Interface, Medikit (improved),
Spare Slots x29, Storage Compartment (1 Slot), Storage Compartment (10 Slots refrigerated),
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

The cloning creche’s brain is expensive at its Tech Level
and large cloning facilities often forgo the expense of the
Advanced brain, using an improved clone tank (see page
118) and saving Cr100000 per unit. Spare capacity in
the Cloning Creche allows for the installation of a bigger
bioreaction chamber or additional features, such as a cryo
or low berth.

**Cloning Vat**
A cloning vat looks much like an autodoc and carries a
similar brain but is specialised in the biology of cloning,
not therapeutic medical care. The bulk of the cloning vat is
a 50-Slot advanced bioreaction chamber capable of force-
growing a clone to adulthood at a 50x accelerated rate.
This procedure requires careful monitoring and is often
supplemented by the implantation of cybernetic devices
such as wafer jacks in the clone’s skull, a task facilitated
by an eight-Slot enhanced fabrication chamber capable of
producing cybernetic parts as large as a limb.

Robot Hits Locomotion Speed TL Cost
Cloning Vat 50 None 0m 13 MCr1.5
Skills Medic 2, Science (biology) 3
Attacks —
Manipulators 2x (STR 7 DEX 9)
Endurance 324 hours
Traits Armour (+4), Large (+2)
Programming Advanced (INT 9)
Options Auditory Sensor, Bioreaction Chamber (50 Slots advanced), Drone Interface, Fabrication
Chamber (8 Slots enhanced), Medikit (enhanced), Spare Slots x20, Storage Compartment (2
Slots), Storage Compartment (10 Slots refrigerated), Transceiver 5km (improved), Vacuum
Environment Protection, Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

The cloning vat is a stand-alone unit, able to perform
all tasks from collecting genetic tissue to distilling a fully
grown clone. Raw materials in the form of biological feed
stocks are necessary to complete this process, as are any
rare minerals required for implanted cybernetic devices.
A large cloning facility often forgoes the installation of
a robot brain, fabrication chamber and other ‘optional’
features, using an advanced clone tank (see page 118)
at two-thirds the expense. Spare capacity within the
cloning vat is often used to incorporate cryo or low berth
technology or expansion to create a larger chamber.

**Crew Droid**
The Crew Droid is a multi-purpose robot targeted at the
small starship operator market. The humanoid robot is the
equivalent of a general crew member, able to perform roles
other than piloting and astrogation and is often employed by
loner scouts and belters. Its primary functions are medic and
steward but the Crew Droid also has skills concerning basic
ship recordkeeping and adherence to regulation, making it
a valuable asset on tramp freighters. While not particularly
adept at engineering duties, it can perform damage control,
even outside the ship while in vacuum.

Intentionally, the Crew Droid has no combat capability.
It cannot operate ship’s weapons, nor does it have
embedded weapons or knowledge of weapons use,
although it does have two spare Slots and a change
in programming can remove Admin or Advocate skill
packages and replace them with something
combat related.

The Crew Droid is not heavily armoured but it is equipped
with a self-repairing chassis and covered in a solar
absorption coat that allows it to function far past its eight
days of internal power capacity. The robot can operate
infinitely if it remains in the sun for at least half of each day.
While humanoid in appearance, the Crew Droid’s feet are
equipped with flexible toes, allowing it to perform tasks
with all four limbs. Feet and hands are coated with gecko
grippers, allowing it to crawl on walls and ceilings and
cling to a ship’s outer hull even in the middle of spaceflight
manoeuvres. Advanced sensors aid the robot in many tasks,
whether preparing a fancy meal or repairing an overheated
electronic component.

Relatively inexpensive and durable, Crew Droids tend
to function for decades and century-old robots are not
unknown, though these aging robots tend to develop
personality quirks over time, often exacerbated by owners
with strong anti-social personalities.

Robot Hits Locomotion Speed TL Cost
Crew Droid 20 Walker 6m 12 Cr150000
Skills Admin 2, Advocate 2, Athletics (endurance) 1, Electronics (all) 1, Engineer (all) 1, Mechanic 2,
Medic 2, Recon 2, Steward 2
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 194 hours + Solar Coating (advanced)
Traits Armour (+4), ATV, Heightened Senses, IR/UV Vision
Programming Advanced (INT 9)
Options Atmospheric Sensor, Auditory Sensor (broad spectrum), Cutting Torch (improved), Drone
Interface, Fire Extinguisher, Gecko Grippers, Medikit (enhanced), Olfactory Sensor (improved),
PRIS Sensor, Recon Sensor (enhanced), Self-Repairing Chassis, Solar Coating (advanced),
Spare Slots x2, Starship Engineer Toolkit (enhanced), Storage Compartment (2 Slots
refrigerated), Transceiver 500km (enhanced), Vacuum Environment Protection, Voder Speaker
(broad spectrum), Wireless Data Link

**Danger Droid**
The Danger Droid is a hazardous environment
explorer. A recon droid equipped to handle any
environment from vacuum to insidious atmospheres
to high radiation to 6,000-metre depths of an ocean,
the Danger Droid can act as an explorer or rescue
worker in environments too hazardous to risk a
biological entity. The Danger Droid can operate for
more than a week on internal power, supplemented
where available by a solar coating for recharging and
basic operations. Internally equipped with a versatile
science toolkit, advanced medical kit, plus cutting
torch and fire extinguishing system, the humanoid
robot can also carry tools and a backpack with
additional implements to perform specialised tasks or
carry samples back to a safe environment for
further analysis.

The robot’s versatile brain is knowledgeable across
a wide variety of scientific disciplines and additional
skills from Explosives to Medic, allowing it to act as
a bomb disposal specialist and emergency response
technician. Specialised Danger Droids may have
differing skill packages suited to particular roles
but by default the robot is an extremely versatile
operative in just about any environment.

Robot Hits Locomotion Speed TL Cost
Danger Droid 20 Walker 6m 14 Cr740000
Skills Athletics (dexterity) 2, Athletics (strength) 2, Explosives 2, Investigate 3, Medic 2, Navigation 3,
Recon 3, Science (all) 2, Survival 2, Tactics (military) 2
Attacks —
Manipulators 2x (STR 12 DEX 12)
Endurance 194 hours + Solar Coating (advanced)
Traits Armour (+10), ATV, Hardened, Heightened Senses, IR/UV Vision
Programming Very Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Corrosive Environment Protection, Cutting Torch
(advanced), Drone Interface, Encryption Module, Environment Processor, Fire Extinguisher,
Insidious Environment Protection (14 days), Laser Designator, Medikit (advanced), Navigation
System (enhanced), Olfactory Sensor (advanced), PRIS Sensor, Radiation Environment
Protection (+700 rads), Recon Sensor (advanced), Scientific Toolkit (advanced), Self-Repairing
Chassis, Solar Coating (advanced), Submersible Environment Protection 2,000m (advanced)
x3, Transceiver 5,000km (enhanced), Vacuum Environment Protection, Voder Speaker (broad
spectrum), Wireless Data Link

**Deep Diver Droid**
The Deep Diver Droid is an underwater exploration
robot able to operate on hostile worlds for up to 50
years. The robot’s RTG power unit allows it to use
waste heat to burrow through ice to reach oceans
hidden by the icy crusts of frozen moons. This is
a slow process, often taking days to penetrate
even a kilometre of ice. A cutting torch speeds the
process and burns away small obstructions such
as boulders that impede its progress. Once into
the dark waters below the ice, the Deep Diver can
operate freely, moving slowly but able to dive to 20
kilometres depth in standard gravity or beyond 100
kilometres depth on smaller moons. Its powerful
transponder can send signals through hundreds
of metres of ice, although it normally deposits a
repeater stored in its sample container prior to
beginning its trek into the black icy depths.

Equipped with a single arm and a toolkit
optimised for planetology research, the robot
can distinguish inert samples from the primitive
life forms sometimes found on icy moons and
can store up to two kilograms of samples in a
pressurised container for later recovery. Returning
to the surface from beneath the ice is a difficult
endeavour and many Deep Divers spend their
entire existence exploring the cold oceans of a
frozen world.

Robot Hits Locomotion Speed TL Cost
Deep Diver Droid 20 Aquatic 3m 12 MCr2.3
Skills Investigate 2, Navigation 2, Recon 2, Science (planetology) 2
Attacks —
Manipulators 1x (STR 9 DEX 7)
Endurance 50-year half-life RTG (108 hours)
Traits Armour (+7), Heightened Senses, IR/UV Vision, Seafarer
Programming Very Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Cutting Torch (improved), Drone Interface, Navigation
System (improved), Olfactory Sensor (improved), PRIS Sensor, Radiation Environment
Protection (+600 rads), Recon Sensor (enhanced), RTG Long Duration (improved), Scientific
Toolkit (improved), Self-Maintenance Enhancement (improved), Storage Compartment (1
Slot hazardous material), Submersible Environment Protection 2,000m (advanced) x10,
Transceiver 5,000km (improved), Vacuum Environment Protection, Wireless Data Link

**Emergency Medical Response Robot**
The Emergency Medical Response Robot or EMR-
Bot is a multi-armed fast-flying grav-propelled unit.
Outfitted with advanced sensors and equipped with
a medical kit, cutting torch and fire extinguisher,
this robot is designed to quickly locate and stabilise
patients while waiting for ambulance units to
arrive. Able to reach 300 kilometres per hour with
superior agility, it can navigate both urban and rural
landscapes rapidly, and environmental protection
against hostile environments and vacuum allows it to
respond to emergencies involving fires, hazardous
chemicals and hull breaches.

Robot Hits Locomotion Speed TL Cost
Emergency Medical
Response Robot

20 Grav — 12 Cr150000

Skills Athletics (all) 1, Medic 2, Recon 2, Survival 0
Attacks -—
Manipulators 2x (STR 9 DEX 9), 2x (STR 5 DEX 9)
Endurance 72 (18) hours
Traits Armour (+10), Flyer (high), Heightened Senses, IR/UV Vision
Programming Advanced (INT 8)
Options Auditory Sensor (broad spectrum), Cutting Torch (improved), Drone Interface, Fire
Extinguisher, Injector Needles x4, Medikit (enhanced), Olfactory Sensor (improved),
PRIS Sensor, Recon Sensor (enhanced), Storage Compartment (3 Slots refrigerated),
Transceiver 5 km (enhanced), Vacuum Environment Protection, Voder Speaker,
Wireless Data Link

The EMR-bots medical equipment and skills
are advanced enough to allow in-situ surgery if
evacuation is not available but its preferred course
of action is to treat a severely injured patient with
Fast Drug administered from one of four injectors
embedded in the palm of each hand.

EMR-Bots are sometimes used as battlefield medics.
Their triage routine does not make distinctions between
opposing sides, treating multiple wounded in the most
efficient manner possible, making nearly any soldier
likely to respect the non-combatant status of the robot,
although it does make it difficult for a wounded soldier
to hide from the enemy when an EMR-Bot cuts through
a barricade to come to the rescue.

**Exploration Rover**
This rover is an early explorer of planetary bodies,
optimised for vacuum to standard atmosphere worlds
no further than one orbit beyond the habitable zone.
Operating on solar power, the rover has autonomous
navigation functions but receives instructions from a
control centre through its satellite uplink and powerful
transceiver, either through an orbital relay or direct link
to a large radio array at the control centre. Equipped
with a single arm and a variety of mining instruments

Robot Hits Locomotion Speed TL Cost
Exploration Rover 20 Tracks 4m 8 Cr940000
Skills Navigation 1, Recon 2
Attacks —
Manipulators 1x (STR 9 DEX 5)
Endurance 25-year half-life solar power (144 hours)
Traits Armour (+2), ATV, IR Vision
Programming Basic (recon) (INT 3)
Options Auditory Sensor, Atmospheric Sensor, Drone Interface, Geiger Counter, Light Intensifier
Sensor (basic), Mining Equipment (small), Navigation System (basic), Olfactory Sensor
(basic), Radiation Environment Protection (+400 rads), Satellite Uplink, Scientific Toolkit
(improved), Self-Maintenance Enhancement (improved), Solar Power Unit (improved),
Thermal Sensor, Transceiver 5,000km (basic), Vacuum Environment Protection, Visual
Spectrum Sensor, Wireless Data Link

and sensors, the Exploration Rover can perform simple
in-situ analysis on atmospheric and geological samples
with external guidance. Powered by a solar array and
supported by superior hardened materials to extend its
life, the Exploration Rover can operate for more than
two decades far from civilisation but its solar power
system is subject to wear and dust accumulation, and
brainpower and speed are limited, but it can act as a
reliable scout for early space programmes.

Forensic Supervisor Droid
The Forensic Supervisor Droid is a crime scene
investigator equipped with investigative tools and
able to control small robots or drones and swarms
of microbots for evidence collection. As a one-
robot forensic department, it is also conversant
in regulations, report writing and presentation of
evidence to other investigators and courts via video
screen and holographic projector. Four small arms
allow the robot to gather evidence and use its
advanced forensic tools. Two small compartments
hold subsidiary Forensic Scouts and a smaller
container can hold literally hundreds of microbots
able to fly or crawl across a crime scene. With
a high-tech cutting torch, the robot can also cut
through debris to collect evidence or aid rescue
operations. A two-Slot capacity hazardous material
compartment can be subdivided to hold various
evidence. Significant brain bandwidth is available for
specific science or other skill expansion.

Robot Hits Locomotion Speed TL Cost
Forensic
Supervisor Droid

20 Grav 6m 14 Cr920000

Skills Admin 2, Advocate 2, Electronics (remote ops) 4, Investigate 4, Recon 3, Science (any) 2,
Tactics (military) 2, +7 available bandwidth
Attacks —
Manipulators 4x (STR 7 DEX 8)
Endurance 36 hours
Traits Armour (+4), Flyer (idle), Heightened Senses, IR/UV Vision
Programming Very Advanced (INT 12)
Options Auditory Sensor (broad spectrum), Cutting Torch (advanced), Drone Interface, Environment
Processor, Forensic Toolkit (advanced), Holographic Projector, Olfactory Sensor (advanced),
PRIS Sensor, Robotic Drone Controller (advanced), Recon Sensor (advanced), Storage
Compartment (2 Slot hazardous material), Storage Compartment (2 Slots x2 + 1 Slot),
Swarm Controller (advanced), Transceiver 500km (enhanced), Vacuum Environment
Protection, Video Screen (advanced), Voder Speaker (broad spectrum), Wireless Data Link

**Forensic Scout**
The Forensic Scout is a small grav-powered data
collection robot designed to work in conjunction with
a Forensic Supervisor Droid, which contains two
compartments to store them. The Scouts can be used
independently to investigate locations and gather small
samples with a single dexterous manipulator arm. The
scout has advanced sensors and an Advanced brain to
enable independent investigation.

Robot Hits Locomotion Speed TL Cost
Forensic Scout 1 Grav 6m 14 Cr50000
Skills Investigate 1, Recon 3
Attacks —
Manipulators 1x (STR 2 DEX 9)
Endurance 36 hours
Traits Armour (+4), Flyer (idle), Heightened Senses, IR/UV Vision, Small (-4)
Programming Advanced (INT 8)
Options Atmospheric Sensor, Auditory Sensor (broad spectrum), Drone Interface, Olfactory Sensor
(advanced), PRIS Sensor, Recon Sensor (advanced), Storage Compartment (1 Slot hazardous
material), Transceiver 5km (improved), Vacuum Environment Protection, Voder Speaker,
Wireless Data Link

Forensic Supervisor Droid

Forensic Scout

**Hive Queen**
The Hive Queen is a very large robot, terrifying to
some, although not necessarily from its spider-like
form. The ovoid body has eight limbs, four large legs
ending in six-fingered hands capable of fine motor
control as well as crushing force and four human-sized
limbs, each with eight delicate fingers more dextrous
than nearly any human. Its head is a flattened dome
equipped with advanced reconnaissance sensors. A
nuclear battery can power the Hive Queen for a century
and it can survive in vacuum, high radiation and the
coldest regions of space, protected by an armoured
body that operates without maintenance for 60 years.
However that is not what frightens people; what
frightens certain ‘alarmists’ is the enhanced fabrication
chamber capable of producing one human-sized robot
every few hours. Mining equipment allows it to jump-
start this process by harvesting raw materials although,
as envisioned, the Hive Queen produces miners and
equipment and settle in as a robot factory. Then it
directs workers to build a bigger robot factory, often
after producing prototypes. The Hive Queen is a seed
for a replication colony.

Robot Hits Locomotion Speed TL Cost
Hive Queen 72 Walker 5m 13 MCr43
Skills Athletics (dexterity 1), Athletics (Strength) 1, Diplomat 3, Electronics (remote ops) 3, Melee
(unnatural) 1, Profession (belter) 3, Profession (fabricator) 3, Recon 3, Science (robotics) 4,
Survival 3, Tactics (military) 3
Attacks Claws x4 (2D+1), Claws x2 (4D+3)
Manipulators 4x (STR 9 DEX 15), 2x (STR 15 DEX 9), 2x (STR 15 DEX 9) modified legs
Endurance 100-year half-life RTG (108 hours)
Traits Armour (+17, +10 vs. lasers), ATV, Hardened, Heightened Senses, IR/UV Vision, Large (+3)
Programming Very Advanced (INT 12)
Options Auditory Sensor (broad spectrum), Drone Interface, Environment Processor, Fabrication
Chamber (64 Slot enhanced), Gecko Grippers, Mining Equipment (medium), Olfactory
Sensor (advanced), PRIS Sensor, Radiation Environment Protection (+650 rads), Recon
Sensor (advanced), Reflec Armour, Robotic Drone Controller (advanced), RTG Long Duration
(advanced), Scientific Toolkit (enhanced), Self-Maintenance Enhancement (enhanced), Swarm
Controller (enhanced), Transceiver 5,000km (enhanced), Vacuum Environment Protection,
Voder Speaker (broad spectrum), Wireless Data Link

Created by Ling Standard Products to develop remote
installations and mine inhospitable asteroids, the Hive
Queen is a popular focal point for what LSP public
relations officials call ‘anti-robot hysteria’. The Hive
Queen counters this with a soothing voice and a deep
understanding of diplomacy. Former LSP insiders
have also alleged that the Hive Queen has a deep
understanding of military tactics but LSP dismisses this
as expert logistics knowledge, allowing the Hive Queen
to efficiently allocate resources. The Hive Queen’s
ability to use up to six of its limbs in close combat is
purely defensive.

In addition to producing independent robot workers,
the Hive Queen is equipped with drone and swarm
controllers, allowing it to directly control its subordinate
machines as necessary. Hive Queens have been
in operation for decades and have supervised the
construction of sophisticated automated facilities, none
of which, LSP PR officials insist, have gone rogue. Not
yet, alarmists retort.

**Kimim AAR – Type 14**

**Secure Courtesy Assist Unit**
The Courtesy Assistance Unit takes the form
of a grav-supported ovoid, with panels that
slide back to present trays of drinks, delicacies
or light pre-prepared meals. Its programming is
sophisticated, enabling it to predict who might
want a glass of wine or cup of coffee next and
to subtly induce members of a delegation to
eat or drink too much if instructed to do so.
It is widely presumed that somewhere in the
bowels of every Type 14 is a ‘mutiny gun’,
which is presented to a senior officer instead
of their requested coffee if certain codewords
are spoken.

Robot Hits Locomotion Speed TL Cost
Kimim AAR 12 Grav 4m 13 Cr29000
Skills Carouse 1, Diplomat 0
Attacks —
Manipulators —
Endurance 43 hours
Traits Armour (+3), Flyer (idle), Small (-1)
Programming Advanced (INT 8)
Options Auditory Sensor, Drone Interface, Storage Compartment (10 Slot refrigerated), Transceiver 5km
(improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**Medivac Robot**
The Medivac robot is a grav-propelled flying
medical chamber designed to quickly evacuate
a wounded patient, stabilising, or freezing the
patient if necessary, and transporting them to
a hospital or other medical facility. Available at
TL11, the Medivac is not as advanced as the
Angel of Mercy and focuses on transport and
stabilisation. While able to perform first aid and
minor surgical procedures, the Medivac lacks
the tools and skills for complex operations and
is programmed to freeze any patient in serious
danger of dying before arrival, an operation itself
fraught with some peril. Able to fly at up to 300
kilometres per hour for 12 hours, it can cover
considerable range from a regional medical centre
and is often based on frontier worlds or safely
behind the lines of conflict zones. Clearly marked
as a medical unit and shaped like a flying coffin,
it is not armoured or threatening in appearance.
Two small manipulator arms contain drug injection
needles and are internal to its chamber. At a
full 50-Slot capacity, the Medivac is designed to
carry one patient but can hold a second patient
in extremis, if both are fairly small humanoids,
although this greatly increases the risk of mishap,
especially with regards to cryoberth operation. A
small hazardous material chamber is accessible
by the arms inside the robot and can hold drugs
or forensic material.

Robot Hits Locomotion Speed TL Cost
Medivac Robot 50 Grav — 11 Cr280000
Skills Flyer (grav) 2, Medic 2, Navigation 0, Recon 0
Attacks —
Manipulators 2x (STR 5 DEX 7)
Endurance 48 (12) hours
Traits Armour (+3), Flyer (high), IR Vision, Large (+2)
Programming Advanced (INT 7)
Options Auditory Sensor, Autopilot (enhanced), Drone Interface, Injector Needles x2, Light Intensifier
Sensor (advanced), Medical Chamber (50 Slots), Medical Chamber Option: Cryoberth (basic),
Medikit (improved), Storage Compartment (2 Slots hazardous material), Transceiver 5,000km
(improved), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

**Nursebot**
The Nursebot is designed for long term care of
patients and light hospital duty. Taking advantage of
the decreasing cost of Advanced brains at TL12, the
Nursebot can handle most patient care tasks and
has a sophisticated diagnostic program. The wheeled
robot has two strong arms and a rounded shape
designed to put patients at ease. Internal storage
for medical supplies as well as materials to clean up
patients ‘messes’ the robot is often found in a home
care setting, performing light housework in addition
to its assigned function, all in the name of keeping its
patient comfortable.

Robot Hits Locomotion Speed TL Cost
Nursebot 12 Wheels 6m 12 Cr39000
Skills Athletics (strength) 1, Investigate 1, Medic 2, Profession (domestic cleaner) 2
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 97 hours
Traits Armour (+4), Heightened Senses, Small (-1)
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Domestic Cleaning Equipment (small), Drone Interface,
Industrial Cleaning Equipment (small), Medikit (enhanced), Olfactory Sensor (basic), Storage
Compartment (3 Slots hazardous material), Transceiver 5km (improved), Visual Spectrum
Sensor, Voder Speaker, Wireless Data Link

**Offworld Construction Master Robot (OCMR)**
The Offworld Construction Master Robot, or OCMR,
is a large tracked robot that looks like a tool-festooned
tracked vehicle. Designed to operate on its own in harsh
vacuum conditions, the OCMR can construct 10 cubic
metres of building every hour and with the capability to
supervise up to eight Offworld Construction Drones, it
can organise the construction of up to 50 cubic metres
of facility every hour, quickly creating a remote outpost
or facility. Able to operate for up to 18 days on internal
power, it can work around the clock to complete facilities
in very short order.

The OCMR usually operates with prepared materials
and is equipped with a forklift to move pallets of
construction materials but is also equipped with mining
equipment, a variety of toolkits and a six-Slot fabrication
chamber, allowing it to literally build a remote facility from
scratch, albeit at a much slower pace. Its broad tracks

Robot Hits Locomotion Speed TL Cost
Offworld Construction
Master Robot

72 Tracks 4m 12 MCr1

Skills Athletics (endurance) 1, Athletics (strength) 3, Electronics (all) 1, Electronics (remote
ops) 2, Explosives 2, Mechanic 2, Navigation 2, Profession (construction) 3
Attacks —
Manipulators 2x (STR 15 DEX 7)
Endurance 432 hours
Traits Armour (+9), ATV, IR/UV Vision, Large (+3)
Programming Very Advanced (INT 9)
Options Auditory Sensor, Construction Equipment (large), Drone Interface, Electronics Toolkit
(advanced), Fabrication Chamber (6 Slots improved), Forklift (medium), Gecko Grippers,
Mechanical Toolkit (advanced), Mining Equipment (medium), Navigation System
(improved), PRIS Sensor, Radiation Environment Protection (+600 rads), Robotic Drone
Controller (advanced), Satellite Uplink, Starship Engineer Toolkit (enhanced), Transceiver
5,000km (enhanced), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

provide solid traction on most surfaces and a gecko
coating on those tracks allows it to maintain that grip
even in microgravity environments and steep slopes.
Radiation shielding adds protection for work under the
harsh light of nearby stars or in the middle of a gas
giant’s radiation belts.

An OCMR is often placed in charge of a mixed group
of mining and construction drones, accelerating the
process of extracting raw materials and converting
them into a full facility. OCMRs can construct landing
fields, shelters and operation centres on remote
moons and asteroids without supervision. For all but
the shortest jobs, the OCMR and its team require
access to a power source for recharging. Although very
sophisticated, it is not skilled enough to construct its
own fusion power plant, although a solar facility is not
beyond its capabilities.

**Protocol Droid**
Within interstellar society, the clash of cultures can
only be compounded when those of different planets
and species meet. The protocol droid is designed
to smooth over misunderstandings and allow direct
communication between parties. This goes beyond
mere language, of which the protocol droid can store
up to six million and derive far more, but also customs,
etiquette and, of course, protocol.

Robot Hits Locomotion Speed TL Cost
Protocol Droid 20 Walker 5m 14 Cr700000
Skills Admin 1, Advocate 1, Diplomat 2, Gambler 1, Language (most of them) 3, Persuade 1, Steward 1
Attacks —
Manipulators 2x (STR 9 DEX 9)
Endurance 108 hours
Traits Armour (+3), ATV
Programming Very Advanced (INT 11)
Options Auditory Sensor, Autobar (improved), Autochef (improved), Drone Interface, Holographic Projector,
Olfactory Sensor (basic), Storage Compartment (5 Slots refrigerated), Transceiver 500km
(improved), Visual Spectrum Sensor, Voder Speaker (broad spectrum), Wireless Data Link

Sanitation Droid
A development of the utility droid, these robots are
designed to ensure that a living space, be it home, office
or spaceship, is kept hygienic. Its duties range from
washing the clothes of its owners to disinfecting rooms
and corridors, although it is adaptable enough to perform
other domestic chores, such as preparing meals. Its
manufacturers give each sanitation droid a name and
distinct personality, which has the ability to develop and
grow as it spends time with its owners. There are rumours
that some sanitation droids have built-in obsolescence in
order to make way for newer models and that some have
managed to break their own programming.

Robot Hits Locomotion Speed TL Cost
Sanitation Droid 20 Wheels 5m 11 Cr150000
Skills Profession (domestic hygienist) 3, Steward 1
Attacks —
Manipulators 4x (STR 9 DEX 7)
Endurance 72 hours
Traits Armour (+2)
Programming Advanced (INT 9)
Features Auditory Sensor, Autochef (improved), Domestic Cleaning Equipment (large), Drone Interface,
Spare Slot x1, Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless
Data Link

**Ship’s Mechanic – Rusty**
Ship’s mechanic robots are produced by a number of
manufacturers with different emphasis. Most common
are relatively cheap engineer’s assistants, suitable for
damage control but not general engineering functions
and certainly not a substitute for a qualified ship’s
engineer. To differentiate between models, some have
additional skills or capabilities with a special emphasis;
in the case of this model, it is ship’s defence. This
mechanic is equipped with sharp retractable claws and
programmed to repel intruders and boarders in addition
to damage control and routine maintenance functions.

Robot Hits Locomotion Speed TL Cost
Ship’s Mechanic Robot 18 Walker 5m 12 Cr50000
Skills Mechanic 2, Melee (unarmed) 2
Attacks Claws (3D)
Manipulators 2x (STR 9 DEX 7)
Endurance 108 hours
Traits Armour (+3), ATV
Programming Advanced (INT 8)
Options Auditory Sensor, Drone Interface, Industrial Cleaning Equipment (medium), Mechanical
Toolkit (advanced), Spare Slots x6, Transceiver 5km (improved), Visual Spectrum
Sensor, Voder Speaker, Wireless Data Link

Standard Engineer Droid (SED)
The SED is a repurposed medium repair drone with an
Advanced brain and extra bandwidth installed to convert
the drone into a basic all-purpose engineering drone.
The only other upgrade is the PRIS sensor replacing the
advanced light amplifier. While the SED is not particularly
skilled, it possesses a broad range of knowledge of
starship systems and can act independently as a
competent junior engineer. Some tramp freighters have
an SED as the only engineer, which is acceptable in most
routine situations and generally passes a flightworthiness
inspection, but an SED lacks deep knowledge and
adaptability, making Very Difficult tasks generally beyond
its capability, and it tends to tackle even Difficult tasks
slowly to ensure completion.

The SED retains an operational drone interface,
allowing a remote operator to override or shut down
its voluntary functions, an event which makes the SED
rather cranky afterwards.

Robot Hits Locomotion Speed TL Cost
Standard Engineer
Droid (SED)

20 Walker 6m 12 Cr85000

Skills Electronics (sensors) 1, Engineer (all) 1, Mechanic 1
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 194 hours
Traits Armour (+8), ATV, IR/UV Vision
Programming Advanced (INT 8)
Options Auditory Sensor, Cutting Torch (improved), Drone Interface, Fire Extinguisher, Gecko
Grippers, PRIS Sensor, Spare Slots x3, Starship Engineer Toolkit (improved), Storage
Compartment (2 Slots), Transceiver 5km (improved), Vacuum Environment Protection,
Voder Speaker, Wireless Data Link

**Starship Repair Boss**
The LSP Starship Repair Boss is a specialist
unit focused on spacecraft hull repair and
supervising repair drones. Equipped with
four arms, including two smaller arms
outfitted with monoblades for cutting
through bulkhead surfaces, the Repair Boss
can supervise up to four repair drones in
maintenance and repair operations and can
in turn be operated as a drone or avatar for
greater control. Its gecko surfaces allow it
to cling to hull partitions in both normal and
zero-gravity. Thrusters allow for flexible
repositioning in zero-gravity. The Repair
Boss is larger than humans but still able to fit
through standard airlocks.

Robot Hits Locomotion Speed TL Cost
Starship Repair Boss 32 Walker, Thruster 5m 12 Cr270000
Skills Electronics (remote ops) 2, Engineer (j-drive) 2, Engineer (life support) 1, Engineer
(m-drive) 2, Engineer (power) 2, Mechanic 2, Melee 0
Attacks Monoblades x2 (3D, AP 10)
Manipulators 2x (STR 11 DEX 7), 2x (STR 9 DEX 7)
Endurance 216 hours
Traits Armour (+13), ATV, Large (+1), IR/UV Vision
Programming Advanced (INT 9)
Options Auditory Sensor, Avatar Receiver, Cutting Torch (improved), Drone Interface, Electronics
Toolkit (advanced), Fire Extinguisher, Gecko Grippers, Mechanical Toolkit (advanced),
PRIS Sensor, Radiation Environment Protection (+600 rads), Robotic Drone Controller
(enhanced), Starship Engineer Toolkit (enhanced), Transceiver 50km (enhanced), Vacuum
Environment Protection, Voder Speaker, Weapon Mounts (small) x2, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
StarTek 20 Grav, Walker 6m 14 Cr690000
Skills Athletics (strength) 2, Electronics (all) 3, Engineer (all) 3, Explosives 2, Gun Combat 0,
Mechanic 3, Medic 2, +1 available Bandwidth
Attacks Stunner (3D Stun, Zero-G)
Manipulators 2x (STR 12 DEX 8), 1x (STR 5 DEX 12)
Endurance 72 hours
Traits Armour (+10), ATV, Flyer (idle), IR/UV Vision
Programming Very Advanced (INT 12)
Options Auditory Sensor, Medikit (enhanced), PRIS Sensor, Radiation Environment Protection,
Starship Engineer Toolkit (advanced), Transceiver 5km (improved), Vacuum Environment
Protection, Voder Speaker, Weapon Mount (small), Wireless Data Link

**StarTek**
Loosely based on the Aslan Hikare’
technician robot, the StarTek is designed to
be an all-around replacement for a ship’s
engineer. The humanoid robot is equipped
with a grav propulsion system allowing
it to access ship components not easily
reachable by human technicians, while a
third arm can perform delicate electronics
work. Skilled in all aspects of engineering,
electronics and mechanics and fully
equipped with the tools of the trade, the
StarTek can also act as a disaster relief
robot with a built-in enhanced medikit
and skills to perform explosive ordnance
disposal. An armour coating, plus vacuum
and radiation protection, allows StarTek
to operate in hostile environments. As
a defensive mechanism, the StarTek
has a stunner built into its small arm to
discourage or disable living obstacles to
completing its tasks.

**Stewaid Shipboard Robot**
The Stewaid is a shipboard robot intended to assist
in simple tasks such as keeping passengers fed
and passageways clean. It has been criticised
for trying to do too much on a single platform,
creating a robot inferior at all tasks to a specialist
device. However, the Stewaid has the advantage of
versatility, enabling a crew to gain a wide range of
basic capabilities with a single purchase. Although
it can do little more than bring whoever is on the
bridge a sandwich and cup of coffee, this at least
frees-up the crew for more
important tasks.

The Stewaid is a bulky ovoid, taller than wide,
running on four small wheels. The torso segment
has a flat top protected by a retractable clamshell
cover, creating a serving platform that can deliver
a range of drinks and basic dishes. An internal
hotplate allows cooking of pre-prepared meals.

The lower half of the ovoid contains a tank of
cleaning fluids and directable pressure-hose. A pair
of segmented arms allows manipulation of light
tools. Manufacturers recommend that Stewaids be
supervised by competent persons and not switched
from cleaning and general-maintenance tasks to
cooking without a thorough clean. However, it is
not uncommon to see a Stewaid vacuuming floors
on the way to taking the ship’s engineer breakfast
in the drive room.

Robot Hits Locomotion Speed TL Cost
Stewaid 12 Wheels 3m 12 Cr8200
Skills Mechanic 0, Steward 0
Attacks —
Manipulators 2x (STR 7 DEX 7)
Endurance 130 hours
Traits Armour (+4), Small (-1)
Programming Basic (service) (INT 4)
Options Auditory Sensor, Autochef (basic), Storage Compartment (5 Slots hazardous material),
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**Steward Droid**
Replacing a qualified starship steward or all-
around household butler, the Steward Droid
is a humanoid robot designed to interact with
people and food. It is a relative short and thin
robot with long arms designed to reach high
shelves or scoop items off the ground. With
a built-in autobar, autochef and an advanced
olfactory sensor, the Steward Droid is adept at
preparing meals and ensuring the comfort of
passengers and guests. With an integral medical
kit, and basic first aid and dietary knowledge,
the Steward Droid can treat minor ailments,
recommend dietary changes and act as a basic
medical aide in emergencies. Programmed
with basic traffic regulations and flying vehicle
operational guidelines, the robot can also act
as an adequate chauffer, although this is often
for show, as it is usually inferior to a vehicle’s
autopilot functions. The Steward Droid’s internal
refrigerated storage compartment has a capacity
of two Slots beyond its inherent autobar and
autochef capacity.

Robot Hits Locomotion Speed TL Cost
Steward Droid 10 Walker 6m 12 Cr35000
Skills Flyer 0, Medic 0, Steward 2
Attacks —
Manipulators 2x (STR 7 DEX 7)
Endurance 97 hours
Traits Armour (+4), ATV, Heightened Senses, Small (-1)
Programming Advanced (INT 8)
Options Auditory Sensor, Autobar (enhanced), Autochef (enhanced), Medikit (basic), Olfactory Sensor
(improved), Storage Compartment (2 Slots refrigerated), Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless Data Link

**Surgeon Bot**
The Surgeon Bot is a replacement medical
doctor optimised for hospital use. With
four highly dexterous manipulators it is
very capable of precision work, each arm
including a hypodermic needle. Advanced
sensors ensure the surgeon bot can see,
hear and smell clues to the patient’s
condition and a set of forensic tools also
allows the robot to act as a qualified
medical examiner. Its embedded set of
medical instruments do not allow it to fully
use its skills but its most common setting
is a fully equipped medical bay or hospital,
with access to diagnostic equipment
and advanced surgical instruments. As a
wheeled robot it is not intended for field
use but a telescoping ‘waist’ allows it to
adjust its height to handle patients both on
the ground and on a surgical bed.

Robot Hits Locomotion Speed TL Cost
Surgeon Bot 12 Wheels 5m 12 Cr810000
Skills Athletics (dexterity) 2, Investigate 2, Medic 4
Attacks Injector Needles x4 (1, AP 4)
Manipulators 4x (STR 7 DEX 12)
Endurance 108 hours
Traits Armour (+4), Heightened Senses, IR/UV Vision, Small (-1)
Programming Very Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Drone Interface, Forensic Toolkit (enhanced), Injector
Needles x4, Medikit (enhanced), Olfactory Sensor (advanced), PRIS Sensor, Transceiver 5km
(improved), Voder Speaker, Wireless Data Link

**Surrogate Droid, Basic**
The basic surrogate droid is a humanoid robot with
an artificial womb, used in some societies to alleviate
a female’s requirement to host a developing foetus
during pregnancy. In some societies this is common
practice, in others a taboo. The basic surrogate
makes little attempt to appear like a biological being,
and is often shaped similarly to a female of the
species but clearly a robot. Equipped with a basic
brain it can act as a domestic servant, although
in some societies this too makes it unacceptable.
Most surrogate droids are equipped with a drone
controller, allowing override capability to the legal
parents of the developing child. A variant able to
carry twins to term is available at twice the cost of
the basic droid.

Robot Hits Locomotion Speed TL Cost
Surrogate
Droid, Basic

20 Walker 6m 10 Cr50000

Skills Profession (domestic servant) 2
Attacks —
Manipulators 2x (STR 9 DEX 6)
Endurance 65 hours
Traits Armour (+3), ATV
Programming Basic (servant) (INT 4)
Options Auditory Sensor, Bioreaction Chamber (8 Slots enhanced), Drone Interface, Olfactory Sensor
(basic), Spare Slots x8, Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker,
Wireless Data Link

**Utility Droid**
These robots are manufactured in their thousands
or, on some worlds, millions. Typically humanoid in
appearance, although obviously artificial, utility droids
are extremely adaptable and can be programmed
to perform almost any basic task, from waiting on
tables in a restaurant to performing repetitive work
on construction sites. They are designed to be
almost disposable, although a healthy second-hand
market often develops with enterprising programmers
reconfiguring utility droids for new tasks. Utility droids
have their Profession skill and Basic programming
defined upon purchase.

Robot Hits Locomotion Speed TL Cost
Utility Droid 18 Walker 5m 9 Cr24000
Skills Profession (domestic servant) 2
Attacks —
Manipulators 2x (STR 9 DEX 6)
Endurance 72 hours
Traits Armour (+3), ATV
Programming Basic (servant) (INT 3)
Options Auditory Sensor, Drone Interface, Spare Slots x16, Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless Data Link

Vigilance CCR
The Vigilance Custom Control Robot is employed in
starports at customs control points and as a member
of customs boarding parties. Its humanoid shape
is designed to intimidate, with sensors obvious and
its chest-mounted stunner clearly visible (some
variants mount a laser pistol instead and the external
appearance of the stunner matches that of the
laser). Able to staff a customs booth and engage
in internal and external ship inspections both in
port and in space, the Vigilance CCR is the bane
of smugglers everywhere. Its advanced detection
equipment and forensics capability allows it to detect
hidden contraband but its knowledge of investigatory
techniques and psychology allows it to determine
where to search and who might require further
scrutiny. Ironically, the robot’s inability to be bribed or
deterred from its duties makes it less popular among
a certain set of biological customs inspectors and in
some jurisdictions pressure from local unions have
banned its use.

Robot Hits Locomotion Speed TL Cost
Vigilance CCR 20 Walker 9m 12 Cr110000
Skills Gun Combat 0, Investigate 2, Recon 3, Science (chemistry) 1, Science (psychology) 1
Attacks Stunner (3D, Stun, Zero-G)
Manipulators 2x (STR 12 DEX 7)
Endurance 65 hours
Traits Armour (+13), ATV, Heightened Senses, IR/UV Vision
Programming Advanced (INT 9)
Options Auditory Sensor (broad spectrum), Environment Processor, Fire Extinguisher, Forensic Toolkit
(improved), Magnetic Grippers, Olfactory Sensor (advanced), PRIS Sensor, Recon Sensor
(advanced), Spare Slots x5, Transceiver 50km (enhanced), Vacuum Environment Protection,
Voder Speaker (broad spectrum), Weapon Mount (small), Wireless Data Link

## U TILITY ROBOTS

Utility robots are background workers with little or no interaction with society, such as labourers, cleaners,
constructors or miners. Utility robots are generally not sophisticated, and often not noticed by society, but they
comprise the bulk of robots and provide the basic labour pillar of many worlds.

AG300 Agricultural Worker
The AG300 Agricultural Worker is an LSP
robot, a walker versatile enough to work open
fields and hydroponic farms. Equipped with
four arms – two for strength and a smaller
pair for more delicate work – to pick fruits
and berries, the AG300 includes an eight-Slot
refrigerated chest compartment to hold seeds
or produce. It normally pulls a trolley or carries
a basket on its back to hold more cargo before
needing to unload its pickings and has an
internal set of agricultural tools, which allows
it to cover 100 square metres of planting or
harvesting every hour. Improved sensors
allow it to determine the condition of crops by
thermal imaging, light intensification and by
smell with a sensitive olfactory sensor.

Robot Hits Locomotion Speed TL Cost
AG300 Agricultural Worker 20 Walker 6m 10 Cr20000
Skills Navigation 1, Profession (labourer) 2
Attacks —
Manipulators 2x (STR 9 DEX 6), 2 X (STR 7 DEX 6)
Endurance 65 hours
Traits Armour (+3), ATV, Heightened Senses, IR Vision
Programming Basic (labourer) (INT 4)
Options Agricultural Equipment (medium), Auditory Sensor, Drone Interface, Light Intensifier
Sensor (advanced), Navigation System (basic), Olfactory Sensor (improved),
Storage Compartment (8 Slot refrigerated), Thermal Sensor, Transceiver 5km
(improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**Bulk Delivery Servitor (BDS)**
The largest robot offering from Spinward
Specialties is the Bulk Delivery Servitor or BDS,
a streamlined courier able to transport cargo at
up to 500 kilometres per hour in an armoured
egg-like carrier. Though not advertised as able
to hold a passenger, it can fit a human in a light
vacc suit with room to spare. The BDS has a
flight range of nearly 10,000 kilometres and
can make suborbital hops or trips to low orbit.
A high-visibility reflec coating makes the BDS
easy to detect but it is immune to most small
arms fire, allowing it to bring packages in and
out of hostile environments with skilful flying.
Spinward Specialties advertises its products
as ‘guaranteed delivery servitors’ but does not
operate services itself, selling to courier firms
and governments who need the speed and
security of the BDS.

Robot Hits Locomotion Speed TL Cost
Bulk Delivery
Servitor (BDS)

50 Grav — 15 Cr460000

Skills Athletics (dexterity) 1, Flyer (grav) 3, Navigation 0
Attacks —
Manipulators —
Endurance 96 (19) hours
Traits Armour (+24, +10 vs. lasers), Flyer (fast), IR/UV Vision, Large (+2)
Programming Advanced (INT 8)
Options Auditory Sensor, Drone Interface, Encryption Module, PRIS Sensor, Reflec Armour, Storage
Compartment (50 Slots hazardous material), Transceiver 5,000km (advanced), Vacuum
Environment Protection, Video Screen (advanced), Voder Speaker, Wireless Data Link

**Courier, Basic**
This courier is a small grav-propelled robot shaped like
a streamlined box, whose sole purpose is to transport
parcels. This courier is not particularly intelligent but
understands verbal instructions and translates them
into a flight route. Cruising at more than 200 kilometres
per hour even in an urban environment, it can transport
small packages in need of urgent delivery, anything
from legal documents to organs bound for transplant.
Its sealed temperature-controlled container occupies

Robot Hits Locomotion Speed TL Cost
Basic Courier 8 Grav — 10 Cr25000
Skills Athletics (dexterity) 1, Flyer (grav) 1, Navigation 1
Attacks —
Manipulators —
Endurance 24 (6) hours
Traits Armour (+3), Flyer (high), Small (-2)
Programming Basic (locomotion) (INT 4)
Options Auditory Sensor, Drone Interface, Navigation System (basic), Storage Compartment (3 Slots
hazardous material), Transceiver 500km (improved), Visual Spectrum Sensor, Voder Speaker,
Wireless Data Link

half its volume and contains sub-containers and
restraints to ensure delivery of delicate cargo. Delivery
instructions must specify an address and optionally a
specific individual or list of individuals who can accept
the package. The courier can act as a communicator
to confirm delivery, or allow the sender to modify
instructions en route, but on its own the courier is very
literal with delivery instructions.

**Courier, Advanced**
The Advanced Courier is designed to quickly transport
packages across regions or between low orbit and a
planet’s surface at speeds approaching 800 kilometres
per hour. Able to withstand vacuum, the courier can
deliver five Slots worth of material in an environmentally
controlled storage compartment rated for hazardous
materials. Its advanced navigation system operates in
both civilised and wilderness environments, delivering
packages to a precise location. The courier does
not have an advanced brain and is strictly limited to
delivery functions, however it performs them at high
speed over nearly continental areas.

Robot Hits Locomotion Speed TL Cost
Advanced Courier 12 Grav — 12 Cr120000
Skills Athletics (dexterity) 1, Athletics (endurance) 1, Flyer (grav) 1, Navigation 3
Attacks —
Manipulators —
Endurance 72 (12) hours
Traits Armour (+4), Flyer (very fast), Small (-1)
Programming Basic (locomotion) (INT 4)
Options Auditory Sensor, Drone Interface, Navigation System (enhanced), Storage Compartment
(5 Slots hazardous material), Transceiver 500km (enhanced), Vacuum Environment
Protection, Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**Domestic Servant**
The domestic servant robot is a small tracked rounded
disk with built-in cleaning apparatus for domestic
environments. It can navigate its environment but is not
capable of interaction beyond status alarms and pre-
recorded messages. These ubiquitous devices are found
in many mid- to early stellar-tech homes and offices,
operating in the background to keep living and work
spaces clean. With no manipulators, the domestic servant
requires intervention or connection to a domestic disposal
system to empty its waste collection compartment.

Robot Hits Locomotion Speed TL Cost
Domestic Servant 6 Wheels 4m 8 Cr500
Skills Profession (domestic cleaner) 2, Recon 1
Attacks —
Manipulators —
Endurance 79 hours
Traits Armour (+2), Small (-2)
Programming Primitive (clean)
Options Auditory Sensor, Domestic Cleaning Equipment (small), Recon Sensor (improved), Storage
Compartment (4 Slots), Transceiver 5km (improved), Visual Spectrum Sensor, Voder
Speaker, Wireless Data Link

Lab Control Robot, Basic
The basic Lab Control Robot is a small box, table-
mounted or installed in a larger control panel. Its
Advanced robotic brain allows control of a single drone,
usually for testing of drones and robots equipped with
a drone interface. The robot’s brain has the capacity
for one more Bandwidth of skill packages and two
Bandwidth 0 skill packages, allowing for customisation.
The basic robotic drone controller limits the Remote
Ops skill of the robot to 0, making this robot an
acceptable lab tool but not flexible.

Robot Hits Locomotion Speed TL Cost
Basic Lab Control Robot 1 None 0m 12 Cr12000
Skills Electronics (remote ops) 1, +1 Bandwidth available
Attacks —
Manipulators —
Endurance 324 hours
Traits Armour (+4), Small (-4)
Programming Advanced (INT 8)
Options Auditory Sensor, External Power, Robotic Drone Controller (basic), Transceiver 500km
(improved), Video Screen (improved), Voder Speaker, Wireless Data Link

**Lab Control Robot, Advanced**
The advanced Lab Control Robot is a more capable
robotic brain box equipped with an advanced robotic
drone controller capable of controlling up to eight
drones at its full skill level. A basic avatar controller
allows it to fully control a robot equipped with an
avatar interface and an enhanced swarm controller
allows it to enable a swarm to perform up to three
separate tasks. Smarter than its basic counterpart,
this Lab Control Robot is knowledgeable in the
science of robotics, allowing it to conduct independent
research or diagnose reasonably complex problems
with robotic systems.

Robot Hits Locomotion Speed TL Cost
Advanced Lab
Control Robot

8 None 0m 12 Cr160000

Skills Electronics (remote ops) 3, Science (robotics) 2
Attacks —
Manipulators —
Endurance 324 hours
Traits Armour (+4), Small (-2)
Programming Advanced (INT 9)
Options Auditory Sensor, Avatar Controller (basic), External Power, Robotic Drone Controller
(advanced), Swarm Controller (enhanced), Transceiver 5,000km (enhanced), Video Screen
(improved), Voder Speaker, Wireless Data Link

Labour Droid
Produced by the billions, the Labour Droid is a
replacement for low-skilled workers on many TL10+
worlds. Built as a cheaply replaceable unit, these robots
often last little more than 10 years before succumbing
to accidents or degradation from overuse, although
they can last for decades if properly maintained.
Variants perform work from agricultural, domestic,
industrial, mining, to simple construction work. The
Labour Droid is not equipped with specialised tools
but can use tools designed for humanoid hands.
Specialised versions with built-in tools and specific skill
packages are often sold, however few can compete
with the heavily discounted basic model.

Robot Hits Locomotion Speed TL Cost
Labour Droid 15 Walker 5m 10 Cr5000
Skills Profession (labourer) 2
Attacks —
Manipulators 2x (STR 9 DEX 6)
Endurance 72 hours
Traits Armour (+3), ATV
Programming Basic (labourer) (INT 4)
Options Auditory Sensor, Drone Interface, Spare Slots x8, Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless Data Link

**Low Berth, Advanced**
An advanced low berth can provide the functions of
both a fast-freezing cryoberth and a standard low berth
hibernation chamber in a single unit and can operate
without outside medical assistance.

It is a coffin-like machine similar to the low or frozen
berths used on spacecraft and fits in a standard low
berth mounting. The advanced low berth contains a
casing fully protecting the occupant and entire unit from
vacuum and hazardous conditions. Two internal arms
allow basic placement of the occupant and can assist
the occupant in entry, although they lack the ability to
pick an occupant off the floor and, once the chamber is
sealed, are unable to operate outside its confines.

The main difference between operating modes is
that a cryoberth works much faster than a low berth,
freezing and preserving its occupant almost instantly,
although at some risk. A cryoberth can therefore be
used to place a severely injured Traveller into stasis
until they receive medical treatment. An internal power
system can function for nearly four weeks on its own
batteries but a berth is usually connected to a vehicle
or ship’s power supply.

The onboard robotic brain, while not terribly
sophisticated, can provide enough assistance and
monitoring to avoid the negative impact of an unskilled
operator or unassisted hibernation, greatly enhancing
the chances of survival during both the freezing and
revival processes. The robot is equipped with a basic
medical kit and accepts verbal commands regarding
the duration of hibernation or the conditions for revival.
The advanced low berth contains a refrigerated storage
compartment stocked with common medical drugs,
which may include Slow Drug, providing a third option
for entering hibernation.

Robot Hits Locomotion Speed TL Cost
Low Berth, Advanced 50 None 0m 12 Cr90000
Skills Medic 2
Attacks —
Manipulators 2x (STR 6 DEX 9)
Endurance 648 hours
Traits Armour (+4), Large (+2)
Programming Advanced (INT 8)
Options Auditory Sensor, Medical Chamber (50 Slots), Medical Chamber Option: Cryoberth
(improved), Medical Chamber Option: Low berth (improved), Medikit (improved), Spare
Slots x20, Storage Compartment (5 Slots), Storage Compartment (2 Slots refrigerated),
Transceiver 5km (improved), Vacuum Environment Protection, Visual Spectrum Sensor,
Voder Speaker, Wireless Data Link

**Low Berth, Grav**
The grav low berth is a movable version of the
advanced low berth and is capable of operating as a
standard TL12 cryo or low berth. The self-propelled
berth can follow simple instructions as to course and
is compatible with a standard low berth mounting.
Capable of more than a day of independent operation,
it can be transferred between vehicles and facilities at
walking speed. When operating in static configuration,
its internal power supply lasts for nearly two full weeks.

Robot Hits Locomotion Speed TL Cost
Low Berth, Grav 50 Grav 6m 12 Cr160000
Skills Medic 2
Attacks —
Manipulators 2x (STR 6 DEX 9)
Endurance 36 hours
Traits Armour (+4), Flyer (idle), Large (+2)
Programming Advanced (INT 8)
Options Auditory Sensor, Medical Chamber (50 Slots), Medical Chamber Option: Cryoberth
(improved), Medical Chamber Option: Low berth (improved), Medikit (improved), Spare Slots
x4, Storage Compartment (5 Slots), Storage Compartment (2 Slots refrigerated), Transceiver
5km (improved), Vacuum Environment Protection, Visual Spectrum Sensor, Voder Speaker,
Wireless Data Link

**Mining Bot**
This is a mining drone with a robot brain inserted
to allow it to operate independently. Other than the
addition of an Advanced robot brain allowing the robot
to operate as a miner and a voder speaker to allow it to
communicate verbally, it is identical in construction and
appearance to a mining drone. Capable of autonomous
operation and smart enough to recognise economically
viable ore from worthless rock, it lacks the sensors and
skills to prospect independently.

Robot Hits Locomotion Speed TL Cost
Mining Bot 50 Thruster — 12 Cr250000
Skills Athletics (endurance) 3, Athletics (strength) 2, Profession (mining) 2
Attacks —
Manipulators 1x (STR 12 DEX 7)
Endurance 18 (5) hours + Solar Coating (enhanced)
Traits Armour (+10), IR/UV Vision, Large (+2), Thruster (1G)
Programming Advanced (INT 8)
Options Auditory Sensor, Drone Interface, Mining Equipment (large), PRIS Sensor, Solar Coating
(enhanced), Transceiver 5,000km (enhanced), Vacuum Environment Protection, Voder
Speaker, Wireless Data Link

**Robodiver**
Robodivers are expensive human-sized robots capable
of operating at crushing depths beneath the ocean.
They are typically used for repair operations, although
are capable of rudimentary reconnaissance roles too.
They are equipped with two manipulator arms and are
extremely robust. On dry land, robodivers can move
around on tracks at a slow walking pace but submerged
they operate with variable buoyancy and are propelled
with a series of ducted props.

Robot Hits Locomotion Speed TL Cost
Robodiver 40 Aquatic, Tracks 4m 11 Cr222000
Skills Mechanic 2, Melee 0, Profession (diving) 3, Recon 1
Attacks Claw (3D)
Manipulators 2x (STR 12 DEX 9)
Endurance 65 hours
Traits Armour (+4), ATV, IR Vision, Large (+1)
Programming Advanced (INT 7)
Options Auditory Sensor, Cutting Torch (improved), Drone Interface, Light Intensifier Sensor (advanced),
Mechanical Toolkit (improved), Recon Sensor (improved), Spare Slots x4, Submersible
Environment Protection 600m (enhanced) x4, Transceiver 500km (enhanced), Visual Spectrum
Sensor, Voder Speaker, Wireless Data Link

RPRU
The Remotely Piloted Reconnaissance Unit, often
known as the Sphere-Eye, is a half-metre sphere
studded with lenses, microphones and detection
devices. It is often operated as a drone but has limited
evasion capabilities to allow independent flight in
the event of communications disruption. The gravitic
probe reaches 200 kilometres per hour in regular
flight and 60 kilometres per hour in nap-of-the-earth
flight out to a communications range of approximately
30 kilometres. For close-in communications, an
encrypted maser communications link allows for
nearly undetectable transmissions.

The RPRU is programmed and operated through the
Control and Reception Unit (CRU). This ruggedised
advanced drone control console consists of a control
panel and three fold-out display screens. The CRU is
carried in a small and rugged attaché case. It weighs
three kilograms and costs Cr15000, while the RPRU
weighs 12 kilograms. The Cr33000 price for the RPRU
includes a charging station and maintenance tools.

Robot Hits Locomotion Speed TL Cost
RPRU 6 Grav — 11 Cr33000
Skills Athletics (dexterity) 1, Recon 2, Stealth 3
Attacks —
Manipulators —
Endurance 24 (6) hours
Traits Armour (+4), Flyer (high), Heightened Senses, IR Vision, Small (-2), Stealth (+2)
Programming Primitive (evade) (INT 1)
Options Auditory Sensor, Camouflage: Audible (advanced), Camouflage: Visual (enhanced), Drone
Interface, Encryption Module, Light Intensifier Sensor (advanced), Olfactory Sensor (improved),
Recon Sensor (enhanced), Stealth (improved), Tightbeam Communicator, Transceiver 50km
(enhanced), Voder Speaker, Wireless Data Link

**Special Delivery Servitor (SDS)**
A product of Spinward Specialities, the Special Delivery
Servitor (SDS) is a fast armoured courier robot. Its
shiny streamlined surface can maintain subsonic flight
for up to 14 hours covering over 16,000 kilometres

- allowing delivery to any point on a planet 10,000

kilometres in diameter and most points on larger worlds
if flying within an atmosphere. Suborbital or low orbital
travel puts any point on any habitable world within
range. The SDS places its Flyer and Navigation skills

Robot Hits Locomotion Speed TL Cost
Special Delivery Servitor 20 Grav — 15 Cr290000
Skills Athletics (dexterity) 1, Flyer (grav) 3, Navigation 0
Attacks —
Manipulators —
Endurance 96 (14) hours
Traits Armour (+16 +10 vs. lasers), Flyer (subsonic), IR/UV Vision
Programming Advanced (INT 8)
Options Auditory Sensor, Drone Interface, Encryption Module, Reflec Armour, PRIS
Sensor, Storage Compartment (8 Slots hazardous material), Vacuum Environment
Protection, Transceiver 5,000km (advanced), Video Screen (advanced), Voder
Speaker, Wireless Data Link

in its Advanced robot brain’s software, not in hardware,
allowing it to carry up to eight Slots of cargo in its
secure hazardous material-ready cargo bay. With high
technology and high cost, the SDS is sometimes sold
at a premium, especially as an aggressive advertising
campaign by its Mora-based manufacturer has driven
up demand for the courier to use ‘when it absolutely
needs to get there today’.

**Skitter**
The Skitter is a highly efficient autonomous cleaning
robot. Its entire flattened half-sphere body is consumed
by cleaning equipment, allowing it to clean 50 square
metres every hour. With ‘sticky’ gecko wheels, the
tiny robot is not limited to cleaning floors but walls
and ceilings too. Many buildings and larger vehicles
have one or more Skitters as permanent residents,
constantly keeping their interior spaces clean.

Not much bigger than a fist, the Skitter is a prolific
cleaning device, mainly limited by a lack of internal
capacity for storing waste. A Skitter-patrolled space
is usually equipped with many trash receptacles or
disposal systems, allowing the Skitter to... skitter...
back and forth as it cleans. Able to see in the dark and
nearly silent in operation, it operates around the clock,
pausing only to recharge every few days.

Robot Hits Locomotion Speed TL Cost
Skitter 1 Wheels 5m 9 Cr2000
Skills Profession (domestic cleaner) 2
Attacks —
Manipulators —
Endurance 72 hours
Traits Armour (+2), IR Vision, Small (-4)
Programming Primitive (clean) (INT 1)
Options Auditory Sensor, Domestic Cleaning Equipment (medium), Gecko Grippers, Light Intensifier
Sensor (advanced), Transceiver 5km (improved), Voder Speaker, Wireless Data Link

Smart Probe Bot
The Smart Probe Bot is a variant of the probe drone
equipped with an Advanced robot brain to allow for
independent operations. With autopilot and navigation
functions replaced by the brain and a section of
reinforced structure removed, the Smart Probe Bot
carries a full planetology sensor suite package to allow
independent investigation of local phenomena. The
specialised sensors and small sampling bay set the
Smart Probe Bot apart from the probe drone but it is
built on the same chassis and has similar performance
characteristics. The robot retains its drone interface,
allowing a remote operator to override the robot brain’s
control of its body if necessary.

Robot Hits Locomotion Speed TL Cost
Smart Probe Bot 20 Grav, Thruster — 12 Cr200000
Skills Flyer 0, Investigate 0, Navigation 0, Recon 3, Science (planetology) 1
Attacks —
Manipulators 2x (STR 5 DEX 7)
Endurance 25-year half-life solar power (72 (18) hours)
Traits Armour (+7), Flyer (high), Heightened Senses, IR/UV Vision
Programming Advanced (INT 8)
Options Atmospheric Sensor, Auditory Sensor (broad spectrum), Drone Interface, Environment
Processor, Olfactory Sensor (advanced), Planetology Sensor Suite, PRIS Sensor, Recon
Sensor (advanced), Satellite Uplink, Solar Power Unit (improved), Transceiver 5,000km
(enhanced), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

**Toolsack Workbot**
The Toolsack is a well-respected and widely used unit
capable of operating in many environments. It is built
on a tracked chassis resembling a small bulldozer and
can act as one with the right attachments; a Toolsack
can mount a variety of options including a backhoe,
heavy-lifting arms, saws, grinders, welding and cutting
gear and a set of lighter arms for fine work.

A modular bay on the back of the robot can be used
for various applications including shaping logs, force-
drying organic matter, sorting ore chunks or even
small-scale fabrication work if optional machinery is
installed. Workbots of this size are typically used for
heavy tasks like construction or earthmoving, and can
operate semi-autonomously to perform simple tasks,
learning more complicated routines with instructions
from a handler. A good ‘bot-wrangler’ can train a force
of workbots to rapidly carry out large-scale tasks with
a high degree of efficiency.

Robot Hits Locomotion Speed TL Cost
Toolsack Workbot 50 Tracks 4m 9 Cr96000
Skills Athletics (endurance) 3, Mechanic 0
Attacks —
Manipulators 2x (STR 7 DEX 6)
Endurance 576 hours
Traits Armour (+8), ATV, Large (+2)
Programming Basic (none) (INT 3)
Options Auditory Sensor, Construction Equipment (large), Drone Interface, Spare Slots x20,
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

Workbots are programmed with inhibitors that
prevent them harming humans; even stupid ones
who stand in front of a cutting arm. Accidents have
happened but these units have an excellent safety
and efficiency record. Workbots are also traffic-legal
for autonomous operation on the highways of most
cities. They are powered by powerful fuel cells with a
variety of electrical and mechanical power take-offs
and can function as the power source for a collection
of smaller robots. It is not uncommon to see a ‘bot
gang’ riding in the Toolsack’s configurable bay on
the way to a job, all plugged into its power outlets,
arriving charged and ready to go.

**Type C Cargo Loader**
The Type C is used in numerous ports and carried
by commercial starships. It is not uncommon to
encounter a fleet of these robots in a down-at-heel
starport, where they have been kept working by
cannibalising other units.

This robot runs on heavy-duty tracks optimised for
smooth surfaces but they do have some rough-
ground capability. This enables loading and
unloading under frontier conditions away from a
starport, which makes these robots popular with
crews trading around backwaters. The body of the
robot is a blocky, low flatbed with a pair of forklift-
type probes on a movable platform. These slide
under a container and lift it, then slide back along

Robot Hits Locomotion Speed TL Cost
Type C Cargo Loader 26 Tracks 3m 10 Cr28000
Skills Mechanic 0, Steward 0
Attacks —
Manipulators 2x (STR 9 DEX 6)
Endurance 76 hours
Traits Armour (+0), ATV, Large (+2)
Programming Basic (service) (INT 4)
Options Auditory Sensor, Drone Interface, Forklift (large), Spare Slots x17, Transceiver 500km
(improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

the bed to deposit the cargo on the main carrying
surface. A pair of light manipulator arms are used for
smaller items.

Control is either by way of a handset or limited
autonomous operation. An operator is required to
set up a loading sequence or direct the robot where
to take its cargo, with the unit making decisions for
route and speed. This semi-autonomous operation
allows some users to convert their cargo loaders
to other uses; field support conversions are not
uncommon, using the loader’s admittedly limited
cross-country capability to transport spares, supplies
and the like. Frontier ranches sometimes use loaders
to carry logs or fence-repair stores and might have
ingenious improvised devices attached.

## A LIEN ROBOTS

In Charted Space, cultures outside the Third Imperium
have varying approaches to robotic sciences and
differing restrictions and opinions on the roles of
robots in their societies. While no species has a truly
monolithic philosophy of robots, major tendencies
influence design aesthetics and robot functions. The
following are representative views of robotics among
the Major Races and examples of robots commonly
found within their cultures.

Aslan
The Aslan have near universally defined gender
roles and their approach to robotics is shaped by that
culture. The science and engineering of robotics is a
female role and males consider robots to be unworthy
of conducting male tasks. The only exceptions to this
divide are medical robots who are considered non-
combatants on the battlefield and worker robots who
conduct tasks relegated to the lowest rungs of society,
such as manual labour.

Females use robots as expert assistants, sometimes
supplanting the female role in small ihatei scout
ships and battlefield support technician tasks. Others
serve as lab assistants, clerks and other support
personnel under female supervision. Limited to TL14
construction, Aslan robots are not as advanced
as those produced by some species but they are
generally well made and aesthetically suited to
their roles. The Aslan firm Tlektaowa was originally
the official robot supplier to the Tlaukhu clans and
remains a major robot producer of some prestige.

Aslan do not build androids in any large number,
perhaps as fallout from the Cultural Purge and
experiments among ‘deviant’ clans; those that do exist
tend to be experimental models built by roboticists.

Arerl Slave Machine
These are humanoid robots, mass-produced and used
as labourers. The Aslan could perhaps have developed
more efficient non-humanoid designs but the arerl
appeals to some atavistic instinct in the Aslan.

Robot Hits Locomotion Speed TL Cost
Arerl 36 Walker 4m 12 Cr45000
Skills Athletics (strength) 3, Profession (labourer) 2
Attacks —
Manipulators 2x (STR 15 DEX 7)
Endurance 119 hours
Traits Armour (+6), ATV, Large (+1)
Programming Basic (labourer) (INT 4)
Options Auditory Sensor, Drone Interface, Spare
Slots x16 Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless
Data Link

**Hikare’ Technician**
A personal robot of great sophistication, the hikare’ is
capable of serving as an engineer on a one-man scout
ship or as a personal servant. On larger ships, they are
used to replace or aid female crew members. The hikare’
design has evolved over time and older hikare’ are often
encountered on backwater Aslan colonies. These robots
are equipped with functioning, although limited, grav
drives and complete technical and engineering toolkits.

Robot Hits Locomotion Speed TL Cost
Hikare’ 23 Grav, Walker 6m 14 Cr590000
Skills Electronics (computers) 2, Electronics (sensors) 2, Engineer (all) 2, Mechanic 2, Steward 2
Attacks —
Manipulators 2x (STR 9 DEX 8) 1x (STR 6 DEX 9)
Endurance 36 hours
Traits Armour (+4), ATV, Flyer (Idle), IR/UV Vision
Programming Very Advanced (INT 11)
Options Auditory Sensor, Drone Interface, Electronics Toolkit (advanced), Mechanical Toolkit
(advanced), PRIS Sensor, Starship Engineer Toolkit (advanced), Transceiver 500km
(advanced), Voder Speaker, Wireless Data Link

Khyeseir Mousebot
These little drones are mobile food carriers, designed to
remind Aslan of natural prey on Kusyu. They are used
where live food would be impractical. Freshly heated
meat is attached to the khyeseir’s spikes and the drone
is released to run around the dining area.

Robot Hits Locomotion Speed TL Cost
Khyeseir 3 Walker 10m 8 Cr500
Skills Athletics (dexterity) 1, Recon 1, Stealth 2
Attacks —
Manipulators —
Endurance 36 hours
Traits Armour (+2), ATV, Small (-3)
Programming Primitive (evade) (INT 1)
Options Auditory Sensor, Recon Sensor (improved), Visual Spectrum Sensor, Wireless Data Link

Hiver
The Hive Federation is a polity comprised of many
sophont species but dominated by Hivers. Hivers
would rather manipulate others to perform tasks than
do something themselves and this includes building
robots to conduct everything from construction to
trade to warfare.

Hivers are six-limbed low-slung mostly symmetrical
beings and their robots often take a similar shape,
with flexible tentacle-like limbs performing both
locomotion and manipulation. Robots in the Federation
are widespread and almost always produced with
high technology components and brains capable of
competently handling a variety of tasks. Hivers are

perfectly comfortable with having robots fight battles
for them and other than compliance with weapons
regulations similar to those sold to biological beings,
the Hive Federation imposes no special restrictions on
warbot operations or sales. The robots built by Six Eyes
Nest have a reputation for being especially effective in
combat, deadly enough to be prohibited for importation
into the Imperium.

Hiver robots are priced in accordance with their
premium quality and available for export sale but the
distribution of Hiver products far beyond the borders of
the Federation are limited by distance. Star Patterns
Trading is a major exporter of quality robots.

Gardener Servant
The Gardener is poorly named in that it performs much
more than simple gardening tasks. It is a general servant
robot for a Hiver who does not want to make the effort
to manipulate a biological being into doing its bidding.
The Gardener is a six-limbed robot somewhat smaller
than an adult Hiver with both manipulator and locomotive
capabilities on all six limbs. It can tend a garden, but can
also cook, clean and perform medical and veterinary
procedures. For cultural reasons these robots are rarely
used to clean or maintain the Hiver’s burrow-like homes.

The Gardener has no voder installed and communicates
via gesture or transceiver, but has acute hearing, a wide
spectrum visual sensor array and sophisticated olfactory
sensors. The robot has no offensive capabilities, though
some can be taught to defend themselves with marginal
efficiency if attacked. Rumours of assassin droids
disguised as Gardeners are completely unsubstantiated.

Robot Hits Locomotion Speed TL Cost
Gardener Servant 20 Walker 6m 15 Cr85000
Skills Animals (veterinary) 2, Medic 2, Profession (cleaning) 2, Profession (gardening) 2, Steward 2
Attacks —
Manipulators 4x (STR 9 DEX 9), 2x Manipulator legs (STR 9 DEX 9)
Endurance 130 hours
Traits Armour (+4), ATV, Heightened Senses, IR/UV Vision
Programming Advanced (INT 9)
Options Agricultural Equipment (small), Auditory Sensor (broad spectrum), Autobar (enhanced),
Autochef (enhanced), Domestic Cleaning Equipment (small), Drone Interface, Medikit
(enhanced), Olfactory Sensor (advanced), PRIS Sensor, Storage Compartment (3 Slots
refrigerated), Transceiver 5km (improved), Wireless Data Link

**Hazardous Environment Scout**
A large lumbering six-limbed robot capable
of long-term operations in environments
from vacuum to insidious to radioactive, the
Hazardous Environment Scout looks like a
Hiver with armour plating. Capable of using all
six limbs as manipulators and equipped with
gecko grippers and advanced sensors on its
extremities, the robot can operate for years
in most environments and survive up to two
weeks in the most insidious of atmospheres.

The scout has onboard mining and
sampling equipment and can transmit
data to an orbiting relay satellite or ship.
It is too expensive to be disposable but
generally does not survive past its three-
year RTG operating half-life as it is sent into
environments too hazardous for biological
beings to work.

Robot Hits Locomotion Speed TL Cost
Hazardous
Environment Scout

32 Walker 5m 15 MCr2.6

Skills Navigation 3, Profession (mining) 2, Recon 3, Science (planetology) 2
Attacks —
Manipulators 4x (STR 12 DEX 12), 2x Manipulator legs (STR 12 DEX 12)
Endurance 3-year half-life (144 hours)
Traits Armour (+12), ATV, Heightened Senses, IR/UV Vision, Large (+1)
Programming Advanced (INT 8)
Options Auditory Sensor (broad spectrum), Corrosive Environment Protection, Drone Interface,
Gecko Grippers, Insidious Environment Protection, Laser Designator, Mining Equipment
(small), Navigation System (enhanced), Olfactory Sensor (improved), PRIS Sensor,
Radiation Environment Protection (+750 rads), Recon Sensor (advanced), RTG Short
Duration (basic), Satellite Uplink, Scientific Toolkit (enhanced), Self-Maintenance
Enhancement (basic), Storage Compartment (1 Slot hazardous material), Transceiver
5,000km (advanced),Vacuum Environment Protection, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Marine
Boarding Droid

32 Walker 9m 15 Cr550000

Skills Athletics (dexterity) 2, Athletics (strength) 2, Gun Combat (energy) 3, Gun Combat (slug) 3,
Melee (all) 2, Recon 3, Stealth 4, Tactics (military) 2
Attacks Arc-Field Weapons x2 (5D+2, AP 30), Hiver Gauss Support Weapon (8D, Auto 2, Blast 2 or
AP8), Stagger Laser Rifle (5D+3, Auto 3, Zero-G)
Manipulators 2x (STR 12 DEX 12), 2x (STR 12 DEX 9), 2x Manipulator legs (STR 12 DEX 9)
Endurance 230 hours
Traits Armour (+28), ATV, Heightened Senses, IR/UV Vision, Large (+1), Stealth (+4)
Programming Advanced (INT 8)
Options Auditory Sensor (broad spectrum), Camouflage: Audible (advanced), Camouflage: Olfactory
(advanced), Camouflage; Visual (superior), Cutting Torches (advanced) x2, Drone Interface,
Encryption Module, Fire Control Systems (enhanced) x2, Gecko Grippers, Olfactory Sensor
(advanced), PRIS Sensors x6, Radiation Environment Protection (+750 Rads), Recon
Sensor (advanced), Stealth (advanced), Tightbeam Communicator, Transceiver 500km
(advanced), Vacuum Environment Protection, Voder Speaker (broad spectrum), Weapon
Mounts (small) x2, Weapon Mounts (medium) x2, Weapon Mount Autoloader (medium),
Wireless Data Link

**Marine Boarding Droid**
Hivers tend to avoid combat, allowing other species of
the Federation, such as the Ithklur, to fight for them.
In instances where other species are not available or
manipulatable, the Hive Federation employs combat
robots. The fearsome Marine Boarding Droid, produced
by Six Eyes Nest, is well suited for ship boarding
actions, able to use all six limbs and selective adhesive
surfaces to operate in both zero and high gravity
environments with ease.

The Marine Boarding Droid is a six-limbed robot
vaguely reminiscent of the shape of a Hiver. It has
no head and advanced visual sensors are installed
in bands at the end of each limb, just below the six
opposable fingers. More oval than a Hiver and able to
stand on two or four limbs, emulating a humanoid or
centaur stance, the ‘forward’ two limbs carry powerful
ranged weapons that fire through the ‘palm’ of each
limb. One limb holds a heavy gauss support weapon,
the other a stagger laser rifle. Dual fire control
systems allow both of these ranged weapons to fire
simultaneously at differing targets. The ‘forearms’ of
the ‘middle’ two limbs are equipped with retractable
arc-field weapons, high tech plasma versions of a
dewclaw, able to cut through bulkhead material and
heavy armour. If these weapons are not enough to
penetrate a barrier, the back ‘legs’ include integral
cutting torches in their ‘palms’.

Additional sensors are distributed across the large
oval body. The entire robot is covered in gecko gripper
material, allowing Van der Waals force adhesions

to most surfaces. Camouflage includes visilight
technology to render the robot nearly invisible, even
at short ranges, and advanced audible and olfactory
camouflage as well as anti-sensor stealth coatings and
shielded electronics. The robot can appear fearsome to
intimidate foes but becomes effectively invisible to set
up an ambush or assassination.

K’kree
Robots are ubiquitous among the K’kree for tasks
not suitable for them due to size or isolation issues.
Robots are considered tools like any other and the
K’kree do not seem afraid that robots might rise up
against them or threaten their civilisation. Robots are
not meat-eaters and K’kree are convinced of their own
superiority. They give little heed to the thought that
robots might one day supplant them. Nevertheless,
their robots tend to have simple brains and limited
scope; they are expendable machines.

Produced in large quantities to standardised designs,
K’kree robots are inexpensive compared to equivalent
models in other regions of space. Costs are generally
one third to one half of equivalent robots but robots
are often bought by Steppelords in large lots. Even
the smaller models of military robots are produced in
quantities that incorporate this level of discount. As
robots are owned by clans and larger groupings, there
are few restrictions on their purchase and use.

**Friend of the Lowly**
The Friend is the most basic of K’kree weapons
carriers, using the same ovoid body shape as most
others, with a laser rifle along the main axis. The unit
is neither agile nor quick and cannot keep up with
a band of charging K’kree if firing at the same time
but does provide accurate light fire support on the
move. Internal fuel cells provide an effectively infinite
number of shots but movement rate is halved while
the weapon is fired. The Friend has only basic visual
and thermal sensors.

Robot Hits Locomotion Speed TL Cost
Friend of the Lowly 20 Grav 12m 10 Cr25000
Skills Gun Combat 0, Recon 0
Attacks Laser Rifle (5D, Zero-G)
Manipulators —
Endurance 10 hours
Traits Armour (+12), Flyer (idle), IR Vision
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Thermal Sensor, Transceiver 5km (improved), Voder Speaker, Weapon
Mount (medium),Wireless Data Link

**Distant Lance**
The Distant Lance is an inexpensive fire support unit,
physically little different from the Friend but much
more richly decorated. It carries a laser rifle like that of
the Friend but has much better sensors and targeting
equipment, and is often programmed to move slowly
behind a band, acting as a sniper to take out enemy
heavy weapons emplacements.

Robot Hits Locomotion Speed TL Cost
Distant Lance 28 Grav 12m 10 Cr45000
Skills Gun Combat (energy) 2, Recon 1
Attacks Laser Rifle (5D, Zero-G)
Manipulators —
Endurance 10 hours
Traits Armour (+16), Flyer (idle), IR Vision
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control System (improved), Recon Sensor (improved), Thermal Sensor,
Transceiver 5km (improved), Voder Speaker, Wireless Data Link, Weapon Mount (medium)

Opener-of-the-Way
The Opener is a specialist unit without offensive
weaponry, running into a target to deliver obstacle-
clearing explosives. These include small charges
dropped onto obstacles and spools of explosive wire,
which are then detonated to clear a path through a
minefield, barbed wire or similar obstacles. A path
two metres wide by 100 metres long can be cleared,
or multiple shorter sections, and there are enough
charges aboard to clear 12 light obstructions such as
barricades or metal fences.

Robot Hits Locomotion Speed TL Cost
Opener-of-the-Way 28 Grav 12m 10 Cr35000
Skills Explosives 1, Recon 0
Attacks Explosive Charge, Autoloaders x2 (2D, Blast 2)
Manipulators —
Endurance 10 hours
Traits Armour (+18), Flyer, (idle), IR Vision
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control System (basic), Thermal Sensor, Transceiver 5km
(improved), Voder Speaker, Weapon Mount (small), Weapon Mount Autoloaders (small)
x2, Wireless Data Link

**Guardian-of-Glory**
The Guardian has a set of armoured shields flaring
out from its frontal section, creating a mobile position
of cover for an advancing warrior band. It is armed
with a laser rifle along its main axis and a rapid-fire
stagger laser weapon in an ovoid turret well forward
on the torso. The effect is intentionally to create the
impression of a noble K’kree, cloak flying out to the
sides. The turret has all-round firepower; the heavy
laser requires pivoting the whole unit and can deprive
those behind it of cover when engaging targets to the
side. Under normal circumstances the Guardian is set
to weave among and ahead of an advancing warrior
band, although it can also be commanded to provide
cover for a specified individual.

Robot Hits Locomotion Speed TL Cost
Guardian-of-Glory 35 Grav 10m 12 Cr75000
Skills Gun Combat (energy) 1, Recon 0
Attacks Laser Rifle (5D, Zero-G), Stagger Laser Rifle (5D, Auto 2, Zero-G)
Manipulators 2x (STR 11 DEX 7)
Endurance 22 hours
Traits Armour (+22), Flyer (idle), IR Vision, Large (+1)
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control Systems (basic) x2, Thermal Sensor, Transceiver 5km
(improved), Voder Speaker, Weapon Mounts (medium) x2, Wireless Data Link

Breaker-of-Lines
The Breaker acts as an artillery unit. It has a rapid-fire
laser unit equivalent to a Hand-of-Length for close-in
defence but its primary armament is a short-barrelled
112mm mortar, which can deliver explosive munitions.
The mortar has an effective range of three km and
carries enough projectiles for 12 shots.

Robot Hits Locomotion Speed TL Cost
Breaker-of-Lines 50 Grav 10 m 10 Cr150000
Skills Gun Combat 0, Heavy Weapons (vehicle) 1, Recon 0
Attacks Hand-of-Length (4D, Auto 4, Zero-G), Support Mortar (9D, Artillery, Blast 6)
Manipulators —
Endurance 14 hours
Traits Armour (+16), Flyer (idle), IR Vision, Large (+2)
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control System (basic), Thermal Sensor, Transceiver 5 km (improved),
Voder Speaker, Weapon Mount (medium) Weapon Mount (vehicle), Weapon Mount
Autoloader (vehicle), Wireless Data Link

**Slayer-of-Shields**
The Slayer is a direct-fire support unit. It has a rapid-
fire stagger laser for close range defence but its main
armament is a pair of Weapon-of-Destruction plasma
guns carried on stubby arms alongside the main hull.
The Slayer normally fires its weapons alternately,
allowing a brief cooling period. Both can be fired
simultaneously but there is a chance of overheating
and malfunction every time this is done. The first time
both guns are fired together in the same round, roll 1D.
On a 6+, the guns will overheat, requiring realignment
and repair, which is a workshop job. A cumulative
DM+1 is added to this roll for every consecutive round
both plasma guns are fired.

Robot Hits Locomotion Speed TL Cost
Slayer-of-Shields 50 Grav 12m 12 Cr200000
Skills Gun Combat 0, Heavy Weapons (portable) 1, Recon 0
Attacks Stagger Laser Rifle (5D, Auto 2, Zero-G), Weapon-of-Destruction x2 (1DD, Very Bulky)
Manipulators —
Endurance 14 hours
Traits Armour (+24), Flyer (idle), IR Vision, Large (+2)
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor, Fire Control Systems (basic) x2, Thermal Sensor, Transceiver 5km
(improved), Voder Speaker, Weapon Mount (medium), Weapon Mount (heavy), Wireless
Data Link

Solomani
The Solomani have a diversity of opinion when it
comes to the acceptance of robots. Some Solomani
worlds welcome the use of robots for any task they can
perform; others prohibit their use for societal or religious
reasons. Most Solomani cultures eschew warbots,
relegating robots to support roles in military conflict.

The quality and sophistication of Solomani robots
varies greatly but technology is generally limited to
TL14. Solomani views towards androids vary but
opposition to robots that can ‘pass’ as human is often
strong even among those who have never heard of the
Shudusham Concords.

With the exception of Panstellar, most Solomani robot
manufacturers are local to their world or subsector, few
spanning even one sector of Solomani space. Especially
along the trailing frontier, Hiver robots have a strong
market share and reputation for quality surpassing
most native Solomani designs. Some Solomani worlds
consider these robots to be part of a ‘Hiver plot’ and
prohibit their importation.

**Confederation Army Ammobot**
An ammobot is built on a low tracked chassis, with an
ammunition hopper on the back, reloading station in the
centre and a magazine dispenser at the front and each
side. The hopper holds a single ammunition type and a
single magazine type can be accommodated. Usually
this is to fit the standard 4mm gauss rifle used by most
Confederation Army formations, although ammobots can
be quickly reconfigured to operate with other weapons.
Some variant types can dispense more than one
ammunition type but these are more likely to be in use
with SolSec or navy personnel than the army.

The ammobot is lightly armoured and tough. It is
capable of automatically moving from a unit’s position
to a supply dump and back again without getting stuck
but that is about the limit of its capabilities. The reloading
mechanism holds 20 magazines. As these are taken
by soldiers, empty ones can be inserted through a slot

Robot Hits Locomotion Speed TL Cost
Ammobot 20 Tracks 6m 12 Cr7200
Skills —
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 86 hours
Traits Armour (+4), ATV
Programming Basic (none) (INT 4)
Options Auditory Sensor, Transceiver 5 km (improved), Visual Spectrum Sensor, Voder Speaker,
Weapon Mount Autoloaders (medium) x8, Wireless Data Link

in the top of the mechanism. Those too dented for safe
use are spat out of another slot as they pass through
the mechanism, generally eliciting jeers and humorous
insults in non-critical situations. The ammunition hopper
holds 24,000 rounds of gauss rifle ammunition, sufficient
to reload 300 magazines, and their internal batteries are
also charged if they remain in the robot for any length
of time. When using larger calibres, such as advanced
combat rifle ammunition, capacity is greatly reduced.

Ammobots are widely used in civilian life, repurposed as
dispensers of all manner of useful items. A popular vid
show of recent years has focussed, on modifying robots
and devices; its all-time highest rated episode featured
the on-the-go barbecue devised by an independent
survey and exploration crew, enabling them to feed
samples of local plant and animal life into the robot and
enjoy a tasty chargrilled meal on the march.

**Confederation Army Mortarbot**
Built on a larger chassis than the ammobot but still
capable of fitting inside a grav APC or assault shuttle,
the mortarbot is armed with a three-barrel breech-
loaded smoothbore mortar on a limited-traverse
mount. Elevation is more free but the weapon has
to return to the vertical for reloading. The three
barrels are arranged in a triangular configuration,
which rotates to align the breech with the loading
mechanism. One barrel can be fired at a time or all
three in rapid succession.

Accuracy with standard munitions is unimpressive but
the weapon’s limited range ensures that deviation is
not excessive. Designated and guided payloads are
available but for the most part the mortarbot is used
to deliver a hail of rapid fire on enemy positions or

Robot Hits Locomotion Speed TL Cost
Mortarbot 34 Tracks 6m 12 Cr40000
Skills Heavy Weapons (vehicle) 0
Attacks Support Mortar (9D, Artillery, Auto 3, Blast 6)
Manipulators 2x (STR 11 DEX 7)
Endurance 86 hours
Traits Armour (+4), ATV, Large (+1)
Programming Basic (none) (INT 4)
Options Auditory Sensor, Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker,
Weapon Mount (vehicle), Weapon Mount Autoloader (vehicle), Wireless Data Link

break up an attack on friendly units. Eighteen bombs
are carried in the rear of the robot’s chassis, with three
more in ready-to-fire positions in the breech.

Mortarbots are sometimes used for non-military
applications. Foliage clearance is one common
application, on worlds where the local vegetation
is hazardous to humans. Firefighting bots can lob
chemical warheads into a fire, scattering either foam
or particles with a huge heat capacity, effectively
drawing the heat out of the fire. A reconnaissance and
surveillance variant is also sometimes used, which lobs
camera-equipped drones high into the air for local-area
mapping. This is inefficient but useful in areas of heavy
vegetation or cluttered rocky overhangs.

**ROvER**
The Robotic Overwatch Enhanced Retriever or ROvER
is technically a civilian or security robot offered as a
fearsome robotic guard dog on some Solomani worlds.
The clearly robotic ROvER looks like a mechanical mix
of Doberman and Great Dane. It is about the same size
as a human adult and stands chest high. Usually matte
black, but available in a limited palette of colours, ROvER
is an extremely heavily armoured Hunter/Killer robot
with monofilament front claws and razor-sharp teeth that
can crush bone or hold a target in place. Equipped with
superior sensors and target designating lasers in its red-
glowing PRIS eyes, ROvER can find and pinpoint its prey
for ranged weapons systems to bring down.

Robot Hits Locomotion Speed TL Cost
ROvER 20 Walker 12m 12 Cr230000
Skills Athletics (dexterity) 3, Melee (natural) 2, Recon 3, Tactics (military) 2
Attacks Jaw Edging (3D), Monoknife Claw Edging x2 (3D, AP10), Self-Destruct (12D, Blast 5)
Manipulators —
Endurance 130 hours
Traits Armour (+40), ATV, Heightened Senses, IR/UV Vision
Programming Hunter/Killer (tactical) (INT 4)
Options Auditory Sensor (broad spectrum), Drone Interface, Fire Control System (improved), Laser
Designator, Olfactory Sensor (advanced), PRIS Sensor, Recon Sensor (advanced), Self-
Destruct System: Offensive, Self-Repairing Chassis, Transceiver 50km (enhanced), Vacuum
Environment Protection, Voder Speaker, Weapon Mounts (small) x3, Wireless Data Link

As a last resort ROvER is equipped with an offensive
self-destruct system, capable of doing terrible damage
in a five-metre radius. For private civilian sales, the
self-destruct mechanism is often removed, usually
without reducing the price of the robot but allowing
it to be legally sold to a broader market. Having a
ROvER or two guarding and patrolling your estate is
a particularly menacing status symbol. Some SolSec
facilities keep a ROvER on site both for its advanced
sensory features and to intimidate... everyone. A
ROvER is sometimes introduced as a security detail at
diplomatic events, especially those including Imperial
delegations with Vargr on staff.

Vargr
Vargr robotics science and technology is not well
advanced, a cultural phenomenon as control
over robots does not enhance charisma; in fact,
it emphasises the lack of it. Therefore, using or
building robots tends to be a low-prestige activity. As
with many generalisations about the Vargr Extents,
there can be significant variations in robotic quality
but, as a rule, Vargr robots are overpriced, badly
engineered and have low intelligence.

Vargr robots can cost twice as much as expected.
Quality is varied and as with many Vargr products,
significant customisation and modification is
expected; many designs incorporate spare spaces
reserved for customisation. Second-hand robots are

common, with mismatched parts, odd modifications
and quirky personalities. Vargr tend to use robots
in situations that are dangerous or difficult but lack
prestige, such as construction and mining, especially
in hazardous environments. Robotic vehicles with
mundane functions such as buses and trucks are
common on such worlds.

Designs near the borders of the Imperium and
Zhodani Consulate are influenced by their
neighbours. Imports are common but so are
counterfeit robots or robots of questionable
providence. Vargr corporations such as Eksaekfoer
are notorious for producing cheap counterfeits of
imported models.

Robot Hits Locomotion Speed TL Cost
Advisor Robot 8 Tracks 3m 13 Cr125000
Skills Admin 2, Advocate 2, Broker 1
Attacks —
Manipulators 2x (STR 5 DEX 8)
Endurance 119 hours
Traits Armour (+3), ATV, Small (-2)
Programming Advanced (INT 8)
Options Auditory Sensor, Spare Slots x4, Transceiver 5km (improved), Visual Spectrum Sensor, Voder
Speaker, Wireless Data Link

**Advisor Robot**
This small robot is primarily used in an advisory role by
corporations and merchants; it can be consulted on all
matters pertaining to bureaucracy, law and trade.

Robot Hits Locomotion Speed TL Cost
Taskbot 26 Walker 5m 12 Cr30000
Skills Admin 0, Advocate 0, Art 0, Broker 0, Drive 0, Electronics 0, Mechanic 0, Medic 0, Navigation 0,
Survival 0
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 108 hours
Traits Armour (+4), ATV
Programming Advanced (INT 8)
Options Auditory Sensor, Spare Slots x8, Transceiver 5km (improved), Visual Spectrum Sensor, Voder
Speaker, Wireless Data Link

**Taskbot**
This general-purpose robot is one of the most
advanced robots of Vargr design. A broad skill
set is included with this robot allowing it to
perform a wide range of tasks. The taskbot is
humanoid in appearance with a head design
based on Vargr physiology.

Zhodani
The Zhodani commonly use robots for both civilian and
military tasks, and do not have the fear of autonomous
war machines that is ingrained in Imperial culture.
Neither do the Zhodani have a need to make their
robots humanoid in appearance, instead favouring a
grav-powered legless torso, although still commonly
equipped with a rotating head and two manipulators.

Widespread use of robots reduces production costs.
Many robots are produced in sufficient quantities to cut
costs in half. Major manufacturers include the industrial
combine Chiadle, Ibr Ajklia Driachobl (IAD) – which is
also known for its excellent software and computers –
and the heavy industry firm Tliazhashal.

Zhodani robots are limited to TL14 and tend to have
the simplest brain available for their role. Zhodani
do not focus on artificial intelligence, nor do they
produce androids. Many Zhodani robots include
the psionic equivalent of a drone interface, allowing
simple direction, control or shutdown of a robot by
telekinetically ‘flipping’ switches within the robot’s brain.

**Trashbot**
This trashbot is commonly used by the Zhodani
government and nobility. Wandering around a
commercial or civic area, it continually picks up waste
and stores it in a receptacle carried within. When full,
the robot dumps it at a local disposal location, then
returns to trash patrol. The janitorial toolkit includes a
collection of tools for sweeping, dusting, polishing and
vacuuming, as well as static charge dissipaters and
assorted mechanical cleaning aids. This toolkit also
allows the robot to instantly shred most materials fed
into it. This ability makes the robot ideal for information
security applications and it can be found in many
Zhodani government offices.

Robot Hits Locomotion Speed TL Cost
Trashbot 16 Grav 6m 11 Cr8000
Skills Profession (domestic cleaner) 2, Recon 2
Attacks —
Manipulators 2x (STR 5 DEX 7)
Endurance 24 hours
Traits Armour (+1), Flyer (idle), Small (-1)
Programming Primitive (clean) (INT 1)
Options Auditory Sensor, Industrial Cleaning Equipment (small), Recon Sensor (enhanced), Storage
Compartment (4 Slots) Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker,
Wireless Data Link

**Maintenance Bot**
The maintenance bot has a cylindrical body with two
arms ending in complex tool-hands and a small wedge-
shaped head turret, and relies on its grav system
for mobility. Manufactured by Chiadle, it is the most
common general-purpose repair and maintenance
robot used in Zhodani space. It can be seen at
starports and aboard merchant or naval vessels,
often negating the need for a dedicated maintenance
crewman. It comes in several versions, mostly differing
in the kind of tool systems used.

Robot Hits Locomotion Speed TL Cost
Maintenance Bot 20 Grav 6m 12 Cr16000
Skills Mechanic 1, Recon 1, +1 Bandwidth available
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 36 hours
Traits Armour (+4), Flyer (idle)
Programming Advanced (INT 8)
Options Auditory Sensor, Mechanical Toolkit (improved), Recon Sensor (improved), Spare Slots x10,
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Light Warbot 12 Grav — 11 Cr45000
Skills Gun Combat (slug) 1, Melee 0, Recon 2, Stealth 1
Attacks Claw (2D), Submachinegun (3D, Auto 3)
Manipulators 2x (STR 7 DEX 7)
Endurance 24 (6) hours
Traits Armour (+3), Flyer (high), Small (-1), Stealth (+1)
Programming Advanced (INT 7)
Options Auditory Sensor, Recon Sensor (enhanced), Stealth (basic), Transceiver 5km (improved),
Visual Spectrum Sensor, Voder Speaker, Weapon Mount (medium), Wireless Data Link

**Light Warbot**
This warbot is light enough to be carried as equipment
by a Zhodani commando team – massing a total of nine
kilograms, a skilled teleporter can even carry one with
them when they teleport. A favourite tactic of Zhodani
commandos is to teleport deep into enemy territory,
leave several light warbots behind and then teleport
back to safety while the warbots wreak havoc on an
unsuspecting encampment, thoroughly demoralising
the enemy.

**Medium Warbot**
This design is a popular warbot model, with customised
versions in use throughout the Consulate. The warbot
is solid and reliable, with good intelligence (as far
as Zhodani robots go). The model shown here is a
basic configuration but many other variations are
available, depending on the operating environment
or type of mission the warbot will be called upon to
perform, carrying a variety of weapons, equipment
and additional armour. Warbots intended for boarding
actions often swap the laser rifle for a flamethrower.

Robot Hits Locomotion Speed TL Cost
Medium Warbot 20 Grav -— 12 Cr45000
Skills Gun Combat (energy) 2, Melee 0, Recon 1, Tactics (military) 1
Attacks Claw (3D), Laser Rifle (5D+3, Zero-G)
Manipulators 2x (STR 9 DEX 7)
Endurance 36 (9) hours
Traits Armour (+8), Flyer (high)
Programming Advanced (INT 8)
Options Auditory Sensor, Recon Sensor (improved), Spare Slots x6, Transceiver 5km (improved),
Vacuum Environment Protection, Visual Spectrum Sensor, Voder Speaker, Weapon Mount
(medium), Wireless Data Link

**Heavy Warbot**
This warbot is designed to hold its own in a
full-frontal assault involving armoured troops
with fusion and plasma weapons. Although
hugely expensive, it stands up well in the most
demanding battlefield situations. Besides obvious
offensive uses, it works well as a defensive
warbot or forward scout, with its excellent
sensors. The oblong half-dome chassis body
presents a small frontal profile, thus minimising
available targeting area, while the small rotating
head contains the sensory and firing apparatus
for the fusion weapon, allowing the main chassis
to remain behind cover while firing.

Robot Hits Locomotion Speed TL Cost
Heavy Warbot 20 Walker 6m 14 Cr200000
Skills Heavy Weapons (portable) 3, Melee 0, Recon 2, Tactics (military) 1
Attacks Claw (3D ), FGMP-14 (2DD Radiation, Very Bulky)
Manipulators 2x (STR 9 DEX 8)
Endurance 97 hours
Traits Armour (+22), ATV, Heightened Senses, IR Vision,

Programming Advanced (INT 8)
Options Auditory Sensor, Environment Processor, Recon Sensor (enhanced), Thermal Sensor,
Transceiver 500km (advanced), Voder Speaker, Weapon Mount (heavy), Wireless Data Link

## D RONES

While drones may have some basic autopilot and
navigation features, they do not have sophisticated
independent decision-making routines. They
are designed to be operated remotely using the
Electronics (remote ops) skill. As such, they do not
have skills but options may provide modifiers to
various tasks performed by their operators or place
limitations on those tasks if the drone’s equipment
is inadequate. Drone equipment is listed in the skills
column to indicate the innate capabilities of the drone,
usable by the operator.

Courier Drone
The Courier Drone is a low-cost mid tech operator-
driven VTOL courier capable of transporting small
packages across regional distances. Equipped with two
small arms to pick up and drop off packages, the drone
can carry packages in a refrigerated compartment
suitable for transport of biological specimens in addition
to more mundane cargo. An onboard navigation
system allows programmed flight with minimal user
intervention but the drone’s autonomous flight system
does not always respond appropriately to obstacles
and the manufacturer recommends an operator remain
attentive during the drone’s entire journey.

Robot Hits Locomotion Speed TL Cost
Courier Drone 8 VTOL — 8 Cr10000
Skills Navigation 1
Attacks —
Manipulators 2x (STR 3 DEX 5)
Endurance 24 (6) hours
Traits Armour (+2), Flyer (medium), Small (-2)
Programming Drone (INT 0)
Options Auditory Sensor, Drone Interface, Navigation System (basic), Storage Compartment (3
Slots refrigerated),Transceiver 50km (improved), Visual Spectrum Sensor, Voder Speaker,
Wireless Data Link

**Mining Drone**
The standard asteroid Mining Drone used by many
prospectors and belters is a sturdy thruster-based
mining platform with a large set of mining tools and a
manipulator arm to aid positioning and extraction. The
drone’s onboard thrusters can provide the equivalent
of 1G acceleration for three hours but the drone
generally relies on solar power and occasional station-
keeping to operate at its target site. If operating
without or far from sunlight, it can function for 18
hours in full darkness before depleting its batteries.

Robot Hits Locomotion Speed TL Cost
Mining Drone 50 Thruster — 12 Cr200000
Skills Athletics (endurance) 2
Attacks —
Manipulators 1x (STR 12 DEX 7)
Endurance 18 (5) hours + Solar Coating (enhanced)
Traits Armour (+10), IR/UV Vision, Large (+2), Thruster (1G)
Programming Drone (INT 0)
Options Auditory Sensor, Drone Interface, Mining Equipment (large), PRIS Sensor, Solar Coating
(enhanced), Transceiver 5,000km (enhanced), Vacuum Environment Protection, Wireless Data Link

The Mining Drone has the equivalent capabilities of
that presented on page 40 of High Guard. Five of these
drones and their harnesses and processing equipment
fit within 10 tons on a spacecraft; when sold as a set of
five, the ore processing equipment and drone storage
harnesses are included in the total drone pricing
of MCr1. If the processing equipment is purchased
separately, it consumes five tons and costs MCr0.2.

Robot Hits Locomotion Speed TL Cost
Offworld
Construction Drone

50 Tracks 4m 12 Cr200000

Skills Athletics (endurance) 1
Attacks —
Manipulators 2x (STR 15 DEX 7)
Endurance 432 hours
Traits Armour (+9), ATV, IR/UV Vision, Large (+2)
Programming Drone (INT 0)
Options Auditory Sensor, Construction Equipment (large), Cutting Torch (improved), Drone
Interface, Electronics Toolkit (enhanced), Forklift (medium), Gecko Grippers, Mechanical
Toolkit (advanced), PRIS Sensor, Radiation Environment Protection (+600 rads), Starship
Engineer Toolkit (enhanced), Transceiver 500km (enhanced), Vacuum Environment
Protection, Voder Speaker, Wireless Data Link

**Offworld Construction Drone (OCD)**
Operated remotely by a skilled construction
worker or an Offworld Construction Master
Robot (see page 165), the OCD is a blocky
construction machine fitted with gecko-coated
tracks to operate in microgravity. In addition to
construction equipment allowing the machine
to construct up to five cubic metres of building
per hour, the OCD is equipped with a varied set
of tools to facilitate installation and repairs of
electronic and starship components. If stowed
aboard a starship, the OCD consumes one ton
of space and can be used as a repair drone,
although it is unable to fit through standard
hatches and iris valves.

**Probe Drone**
The standard IISS Probe Drone is an ancient design
originating in the First Imperium. It is a resilient
grav-powered planetary survey drone, dropped from
orbit in a disposable shell or deployed while in the
atmosphere. It is incapable of returning to orbit and
must be recovered from the ground or atmosphere,
and has no independent capability other than a
simple autopilot and navigator that fly it to a specified
location. A thruster package allows the Probe Drone
to operate in zero-gravity environments, although
with limited acceleration and velocity capability. The
thruster enables the Probe Drone to survey orbiting
satellites, derelicts and other space debris and
enables it to be positioned as a communications relay
or observation satellite.

Nominally powered for 48 hours or 12 hours of high-
speed flight at 300 kilometres per hour, extendable
solar panels allow the Probe Drone to operate for
extended periods if engaged in only minimal flight. A
Probe Drone left in orbit around a world can function
for up to 10 years before its solar panels degrade or
maintenance failures or micrometeoroids damage
key components.

Robot Hits Locomotion Speed TL Cost
Probe Drone 20 Grav, Thruster — 9 Cr100000
Skills Flyer (grav) 1, Navigation 1, Recon 1
Attacks —
Manipulators 2x (STR 5 DEX 6)
Endurance 48 (12) hours + 10 year half-life orbital solar panels
Traits Armour (+5), Flyer (high), Heightened Senses, IR Vision, Thruster (0.1G)
Programming Drone (INT 0)
Options Atmospheric Sensor, Auditory Sensor (broad spectrum), Autopilot (improved), Drone Interface,
Light Intensifier Sensor (advanced), Navigation System (basic), Olfactory Sensor (basic), Recon
Sensor (improved), Satellite Uplink, Solar Power Unit (basic), Spare Slot, Transceiver 5,000km
(improved), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Advanced Probe Drone 22 Grav, Thruster — 12 Cr160000
Skills Flyer (grav) 2 , Navigation 2, Recon 3
Attacks —
Manipulators 2x (STR 5 DEX 7)
Endurance 72 (18) hours + 25-year half-life orbital solar panels
Traits Armour (+7), Flyer (high), Heightened Senses, IR/UV Vision, Thruster (0.1G)
Programming Drone (INT 0)
Options Atmospheric Sensor, Auditory Sensor (broad spectrum), Autopilot (enhanced), Drone
Interface, Environment Processor, Navigation System (improved), Olfactory Sensor
(advanced), PRIS Sensor, Recon Sensor (advanced), Satellite Uplink, Solar Power Unit
(improved), Transceiver 5,000km (enhanced), Vacuum Environment Protection, Voder
Speaker, Wireless Data Link

Probe Drone, Advanced
The TL12 version of the Probe Drone is slightly more
resilient and carries far more advanced sensors than
the standard model. Externally, it appears similar to
the lower tech version, although more advanced PRIS
sensors and thin film solar panels rated for 25 years of
harsh vacuum are obvious visual differences.

Repair Drones
Repair Drones come in a variety of sizes, from giant
extra-large units found mostly on capital ships to extra-
small robots optimised for crawling through narrow
conduits to fix faults. On smaller vessels, one ton of
Repair Drones usually includes two medium, three
small and three extra-small drones, although other
combinations adding up to approximately MCr0.2 worth
of drones are possible.

Repair Drones may be operated remotely using the
Electronics (remote ops) skill or by a ship’s computer
running Auto-Repair software. If a ship’s computer is
simultaneously running Auto-Repair and Virtual Crew
at any level, these drones may perform engineering
functions beyond just damage repair. Many Repair
Drones include at least a Primitive robot brain, allowing
for very basic autonomous operations. This brain may
be replaced with a more sophisticated brain to allow
these same physical machines to perform ship crew
functions. Ship’s brains often use Repair Drones for a
variety of tasks.

Repair Drone, Medium
Approximately the size and shape of a human
crewmember, the medium Repair Drone can use
standard ship tools and work panels in addition to
operating its embedded tools.

Robot Hits Locomotion Speed TL Cost
Medium Repair Drone 20 Walker 6m 10 Cr37000
Skills —
Attacks —
Manipulators 2x (STR 9 DEX 6)
Endurance 130 hours
Traits Armour (+7), ATV, IR Vision
Programming Primitive (INT 1)
Options Auditory Sensor, Cutting torch (improved), Drone Interface, Fire Extinguisher, Gecko
Grippers, Light Intensifier Sensor (advanced), Spare Slots x4, Starship Engineer Toolkit
(improved), Storage Compartment (2 Slots), Transceiver 5km (improved), Vacuum
Environment Protection, Voder Speaker, Wireless Data Link

**Repair Drone, Small**
This drone is the size of a large child but optimised
for working in tight spaces. With its walking limbs
modified to act as manipulators it is often called the
‘chimp drone’, although this term is considered racist
by uplifted Apes and generally not used in or near
Solomani space. With an electronics toolkit fitted, it
is not as adept as a medium drone with mechanical
repairs but can access machinery difficult for a human-
sized being to reach. The drone is still large enough to
handle mechanical tools designed for full-sized hands.

Robot Hits Locomotion Speed TL Cost
Small Repair Drone 12 Walker 6m 10 Cr31000
Skills —
Attacks —
Manipulators 2x (STR 7 DEX 6), 2x Manipulator Legs (STR 7 DEX 6)
Endurance 130 hours
Traits Armour (+7), ATV, IR Vision, Small (-1)
Programming Primitive (INT 1)
Options Auditory Sensor, Cutting torch (improved), Drone Interface, Electronics Toolkit (enhanced),
Fire Extinguisher, Gecko Grippers, Light Intensifier Sensor (advanced), Spare Slot, Storage
Compartment (1 Slot), Transceiver 5km (improved), Vacuum Environment Protection, Voder
Speaker, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Extra-Small Repair Drone 4 Walker 6m 10 Cr11000
Skills —
Attacks —
Manipulators 2x (STR 3 DEX 6), 2x Manipulator Legs (STR 3 DEX 6)
Endurance 130 hours
Traits Armour (+3), ATV, IR Vision, Small (-3)
Programming Primitive (INT 1)
Options Auditory Sensor, Drone Interface, Electronics Toolkit (enhanced), Fire Extinguisher,
Gecko Grippers, Light Intensifier Sensor (advanced), Transceiver 5km (improved),
Vacuum Environment Protection, Voder Speaker, Wireless Data Link

Repair Drone, Extra-Small
The extra-small Repair Drone is designed to work
within a ship’s conduits and small access panels. The
size and appearance of a small monkey, it is often
referred to as a ‘monkey drone’; it is humans that are
most offended by this designation, especially if voiced
by a member of another species. With dexterous hands
on modified legs, it can operate well with all four limbs
in both zero- and high-gravity environments. In a 1G
setting, its small size and gecko grippers enables it to
hang from vertical surfaces with a single hand.

**Repair Drone, Large**
The large drone occupies an entire ton of
space and is generally carried only on ships
larger than 200 tons. Only vaguely humanoid
in appearance, with two large arms and two
human-sized arms, the drone is hardened
to operate in hazardous and high radiation
environments and includes construction tools
enabling it to rebuild damaged hull sections.
Its toughened exterior and long duration power
pack – allowing for more than two weeks of
continuous operation – makes this drone ideal
for power plant rebuilds and deep space work.

Robot Hits Locomotion Speed TL Cost
Large Repair Drone 60 Walker 6m 10 Cr200000
Skills Athletics (endurance) 2
Attacks —
Manipulators 2x (STR 15 DEX 6), 2x (STR 9 DEX 6)
Endurance 389 hours
Traits Armour (+11), ATV, IR Vision, Large (+2)
Programming Primitive (INT 1)
Options Auditory Sensor, Construction Equipment (medium), Cutting torch (improved), Drone
Interface, Fire Extinguisher, Gecko Grippers, Industrial Cleaning Equipment (small), Light
Intensifier Sensor (advanced), Radiation Environment Protection (+500 rads), Spare Slots
x8, Starship Engineer Toolkit (improved), Storage Compartment (5 Slots), Transceiver 5km
(improved), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

**Repair Drone, Extra-Large**
Occupying two full tons of storage space, the extra-
large drone is normally found only on capital ships.
Designed to clear and reconstruct major damage,
the hulking drone does not fit through standard
ship iris valves and hatches, and is normally
located in engineering spaces or bays with external
access, allowing the large machine to walk across
the hull to a damaged section, gaining access
through large hull breaches.

Robot Hits Locomotion Speed TL Cost
Extra-Large Repair Drone 80 Walker 6m 10 Cr400000
Skills Athletics (endurance) 2
Attacks —
Manipulators 2x (STR 15 DEX 6), 2x (STR 11 DEX 6)
Endurance 389 hours
Traits Armour (+13), ATV, IR Vision, Large (+3)
Programming Primitive (INT 1)
Options Auditory Sensor, Construction Equipment (large), Cutting torch (improved), Drone
Interface, Fire Extinguisher, Gecko Grippers, Industrial Cleaning Equipment (large),
Light Intensifier Sensor (advanced), Radiation Environment Protection (+500 rads),
Spare Slots x16, Starship Engineer Toolkit (improved), Storage Compartment (8
Slots), Transceiver 5km (improved), Vacuum Environment Protection, Voder Speaker,
Wireless Data Link

**SkySpotter**
SkySpotter is one of a great many very basic
reconnaissance drones available from TL7 upwards.
It carries forward and sideways looking optical and
thermal cameras but little else. SkySpotter takes the
form of a hand-thrown miniature aircraft powered by a
set of rotors. It is quiet and small but tends to be rather
obvious to anyone looking for such craft. The drone can

Robot Hits Locomotion Speed TL Cost
SkySpotter 1 Aeroplane — 7 Cr5000
Skills —
Attacks —
Manipulators —
Endurance 24 (6) hours
Traits Armour (+2), Flyer (medium), IR Vision, Small (-4)
Programming Drone (INT 0)
Options Auditory Sensor, Drone Interface, Recon Sensor (basic), Thermal Sensor, Transceiver 5km
(basic), Visual Spectrum Sensor

be directly controlled using a selected waypoint system
that requires no special skill beyond a familiarisation
period or can fly a pre-set course. Its batteries are good
for about six hours of operation. A control station is
available but a SkySpotter drone can be controlled from
any personal computer using software that comes free
with every drone.

## M ICROBOTS

Microbots, sometimes referred to as ‘micro robots’ or
‘bug bots’, range from 30 grams of mass and a few
centimetres in length to less than 10 milligrams and
fewer than three millimetres. They grow smaller with
every advance in technology and more sophisticated
as they shrink, able to perform all the functions of
a full-size robot, except those requiring physical
strength or vehicle-speed movement. Most microbots
are reconnaissance machines, able to travel where
larger beings cannot, but other clever or sinister uses
are possible.

Exterminator
As a general rule, autonomous lethal robots are highly
restricted; the Exterminator is an exception. Its sole
purpose is to hunt down small vermin. Equipped
with a Hunter/Killer brain that accounts for nearly all
the Exterminator’s price, the microbot uses a sharp
stinger blade to slice or impale its quarry. Set to
range over an area and pursue prey back to a lair,
the tiny six-rotor exterminator can fly through cracks
in walls or under furniture to pursue any vermin it is
programmed to terminate.

Robot Hits Locomotion Speed TL Cost
Exterminator 1 VTOL 6m 11 Cr8000
Skills Athletics (dexterity) 1, Melee 0, Recon 0
Attacks Stinger (1, AP 3)
Manipulators —
Endurance 17 hours
Traits Flyer (idle), Heightened Senses, IR Vision, Small (-4)
Programming Hunter/Killer (standard) (INT 4)
Options Auditory Sensor (broad spectrum), Drone Interface, Light Intensifier Sensor (advanced), Stinger,
Transceiver 5km (improved), Wireless Data Link

**Hunter Bug**
The Hunter Bug is a narrow 15-millitimetre-long
200mg microbot equipped with a retractable
synthetic diamond blade nearly as long as its body.
The blade is backed with a hollow channel capable
of holding a single dose of fluid. The robot’s Primitive
brain allows some independent operation against a
specific target but its major function is as a remotely
controlled drone. As advertised, it uses its blade
to exterminate common household pests. In actual
operation, its sometimes poisoned blade is used
against more diverse prey. The sharp blade can cut
through light armour, slice critical blood vessels near
the skin or inject poison into a full-sized target. The
Hunter Bug can operate in swarms, overwhelming

Robot Hits Locomotion Speed TL Cost
Hunter Bug 1 Walker 9m 11 Cr3500
Skills Melee (blade) 1, Stealth 3
Attacks Injector Needle Blade (1, AP 3)
Manipulators —
Endurance 72 hours
Traits ATV, Heightened Senses, Small (-4)
Programming Primitive (homing) (INT 1)
Options Auditory Sensor (broad spectrum), Camouflage: Audible (advanced), Camouflage: Olfactory
(improved), Camouflage: Visual (enhanced), Drone Interface, Gecko Grippers, Injector Needle,
Light Intensifier Sensor (basic), Transceiver 50km (enhanced), Visual Spectrum Sensor,
Wireless Data Link

a lightly protected or unsuspecting target. At just a
few millimetres in diameter, the Hunter Bug’s thin
body can penetrate nearly all but airtight rooms.
Camouflaged against most senses and able to see in
the dark, the Hunter Bug can strike a sleeping target
without notice and escape undetected, although at its
low price it is considered an expendable asset.

On some worlds, pest exterminators crowd-source
drone operations, finding that certain individuals will
pay for the privilege of remotely hunting vermin using
a drone interface or helmet. Hunter Bug Leagues
exist, with top scorers winning prizes or at least the
admiration of their peers.

**Nano Hero**
RoboHero’s Nano Hero is a 1:200 scale action
figure drone one centimetre or less tall. It lacks
the full immersive experience of a Micro Hero
avatar but, with a drone control helmet, it allows
a user to experience the world in miniature. Each
Nano Hero is a custom figure, equipped with a
visilight camouflage surface that projects various
‘features’ on the robotic body. Equipped with
gecko grippers and able to operate in a vacuum
and low light-areas, the Nano Hero allows the
‘adventurer’ to explore pre-set environments
or, often with an upgraded transceiver, real
wilderness locations as a bug-sized heroic figure.
Custom models generally start at Cr6100 but rare
‘collectors editions’ or one-of-a-kind body shapes
go for many times this amount.

Robot Hits Locomotion Speed TL Cost
Nano Hero 1 Walker 6m 13 Cr6100+
Skills Stealth 4
Attacks —
Manipulators 2x Microbot Manipulator (STR 0 DEX 8)
Endurance 76 hours
Traits ATV, IR Vision, Small (-4)
Programming Drone (INT 0)
Options Auditory Sensor, Camouflage: Visual (superior), Drone Interface, Gecko Grippers, Light
Intensifier Sensor (advanced), Olfactory Sensor (basic), Transceiver 5km (improved), Vacuum
Environment Protection, Voder Speaker, Wireless Data Link

**Peeping Spybot**
The Peeping Spybot is a sophisticated grav-propelled
microbot designed to provide information in nearly any
environment. As a camouflaged disk 5mm in diameter
and silent in operation, it is nearly indetectable without
specialised equipment. Able to operate completely
independently or by remote control, the Peeping
Spybot is not fast but can pass through air ducts,
travel across the sky, in vacuum and other hostile
environments, transmitting data back to its operator.
An onboard memory system can record its full 40+
hours of operation.

While many would balk at spending so much for such
a tiny machine, the Peeping Spybot is a fully functional
gravitic robot, capable of years of service, although it
can still be swatted like a fly.

Robot Hits Locomotion Speed TL Cost
Peeping Spybot 1 Grav 4m 12 Cr23000
Skills Athletics (endurance) 1, Recon 2, Stealth 3
Attacks —
Manipulators —
Endurance 65 hours
Traits Flyer (idle), Heightened Senses, IR/UV Vision, Small (-4)
Programming Basic (recon) (INT 4)
Options Auditory Sensor (broad spectrum), Camouflage: Visual (enhanced), Drone Interface,
Encryption Module, Olfactory Sensor (advanced), PRIS Sensor, Transceiver 500km
(enhanced),Vacuum Environment Protection, Wireless Data Link

**Popcorn Drone**
A popcorn drone is an assassin weapon usually
deployed in groups or swarms. Available at TL8, but
better operated by higher Tech Level controllers,
the popcorn drone’s purpose is to attach itself to a
target and explode. Doing only 1D damage, these
drones are usually deployed in groups of at least four,
using their small size to creep under doors and into
bedrooms to catch a target unawares and unarmed.
Some are equipped with a poisoned injector needle
for extra effect but their main purpose is to detonate
like a tiny shaped charge, preferably near a vital
organ or blood vessel. The drone operator may make

Robot Hits Locomotion Speed TL Cost
Popcorn Drone 1 Walker 6m 8 Cr3000
Skills —
Attacks Self-Destruct 1D, Injector Needle (1, AP 2)
Manipulators —
Endurance 50 hours
Traits ATV, Heightened Senses, IR Vision, Small (-4)
Programming Drone (INT 0)
Options Auditory Sensor (broad spectrum), Drone Interface, Injector Needle, Microbot Offensive Self-Destruct,
Transceiver 5km (improved), Thermal Sensor, Visual Spectrum Sensor, Wireless Data Link

a melee attack with each drone and apply the Effects
to the damage roll. The TL8 version is a full gram in
mass but higher tech versions are a fraction of this
size and use strategically placed TDX charges to
achieve their explosive effect.

Popcorn Drones have no legitimate use and available
for sale only to governments or on the black
market; this may increase their costs dramatically if
available at all. They are an insidious but expensive
assassination tool.

PopcornBot
A more intelligent version of the Popcorn Drone, this
microbot is equipped with a Hunter/Killer brain and
able to act independently. As with its predecessor, the
tiny assassin bug will self-destruct but may precede
this action with a jab from its injector needle. Both
needle attack and self-destruct may be aided by
separate Melee checks but only the self-destruction
function inflicts extra damage on Effect. PopcornBots
retain the ability to be operated via a drone or swarm

Robot Hits Locomotion Speed TL Cost

PopcornBot 1 Walker 6m 12 Cr9000

Skills Melee 0, Recon 0

Attacks Injector Needle (1, AP 4), Self-Destruct 1D

Manipulators —

Endurance 76 hours

Traits ATV, Heightened Senses, IR Vision, Small (-4)

Programming Hunter/Killer (standard) (INT 4)

Options Auditory Sensor (broad spectrum), Drone Interface, Injector Needle, Microbot Offensive Self-Destruct,
Transceiver 50km (enhanced), Thermal Sensor, Visual Spectrum Sensor, Wireless Data Link

controller but are most often used as a ‘release-and-
forget’ weapon with a single designated target. When
operating independently, they are unable to coordinate
their attacks but a Cr20000 version with a tactical
package can coordinate with others similarly equipped.

As with Popcorn Drones, these microbots are difficult to
obtain legally and tend to sell at a significant premium.

**Scout Mite**
The Scout Mite was designed to be carried in quantity
by a Forensic Supervisor Droid. Equipped with a
Primitive brain it is more drone than droid, although
capable of limited independent action. The most
expensive components of this 15mg, 4mm long
microbot are its sensor arrays, including a full spectrum
PRIS array and wide frequency auditory receptors.
Deployable individually or in swarms, a one Slot
container can hold thousands of Scout Mites.

Robot Hits Locomotion Speed TL Cost
Scout Mite 1 Walker 6m 14 Cr4000
Skills Recon 0
Attacks —
Manipulators 2x (STR 0 DEX 8)
Endurance 76 hours
Traits ATV, Heightened Senses, IR/UV Vision, Small (-4)
Programming Primitive (alert) (INT 1)
Options Auditory Sensor (broad spectrum), Drone Interface, Gecko Grippers, PRIS Sensor, Transceiver
5km (improved), Vacuum Environment Protection, Wireless Data Link

Searcher Microbot
The Searcher is a reconnaissance robot useful in
both survey and search and rescue roles, and has
found an unadvertised niche as a spybot. The small
multilegged robot is less than a centimetre in length
and has six walking legs. Its two tiny manipulators
capable of moving small objects up to its own mass.
Equipped with gecko legs, it can walk across nearly
any surface, on floor, walls or ceiling, and can
crawl through small crevasses, all while providing
a high-definition video feed to a remote observer.
Capable of both autonomous and controlled action,
the Searcher can operate indefinitely with access to
sunlight and for up to six days in total darkness on
internal power.

When delivered to the surface of an unexplored
planet, the Searcher can operate independently
for years, although its ability to store information is
limited by its size. In most instances, it will broadcast
a burst of data at the request of an orbiting satellite
or spacecraft or to a remote base station on the
surface of the planet.

Robot Hits Locomotion Speed TL Cost
Searcher Microbot 1 Walker 4m 12 Cr10000
Skills Recon 2
Attacks —
Manipulators 2x (STR 0 DEX 7)
Endurance 173 hours + Solar Coating (enhanced)
Traits Heightened Senses, ATV, IR Vision, Small (-4)
Programming Basic (recon) (INT 4)
Options Auditory Sensor (broad spectrum), Drone Interface, Gecko Grippers, Olfactory Sensor
(improved), PRIS Sensor, Solar Coating (enhanced), Transceiver 500km (improved),
Vacuum Environment Protection, Wireless Data Link

## N ANOROBOTS

Nanorobots are available at TL13 in certain
jurisdictions, usually subject to considerable
regulation that may vastly increase cost and create
black market demand, especially for medical
nanorobots. Within the Imperium, nanorobots are
rarely encountered and highly regulated. Exceptions
exist, such as the world Neumann in the Gazulin
subsector of the Trojan Reach. Even on Neuman,
nanorobot packages are only available to civil
servants through government channels. These
packages are tailored to certain job roles.

On other worlds where nanotech is available,
custom medical packages are available, usually
focused on a single aspect of nanotechnology and
subject to the limitation of 1.5 litres infused within
one individual, although black market operators may
violate this guideline.

Construction and environmental nanorobots are more
readily available but subject to strict regulation, both
to avail public opinion and conventional
competitor’s concerns.

**Construction Nano Queen**
Often called the ‘Swarm Mother’ the Construction Nano
Queen is a dog-sized quadruped robot designed to
independently run sets of construction or environmental
nanorobots. Originally designed for the asteroid mining
and space construction industries, the Swarm Mother
is also found in terrestrial excavation, construction and
clean-up roles for which it is rather overengineered.
Coated with advanced solar absorption panels, the
robot can operate indefinitely in a system’s habitable
zone and significantly beyond. Its highly efficient power
system and battery packs allow for more than a month
of operation without any sunlight.

The Construction Nano Queen is equipped with two
advanced swarm controllers, allowing simultaneous
operation of up to 0.8 litres of construction nanos
performing multiple tasks. Its TL14 brood of nanos last
for 1,000 hours, or six weeks of operation, capable of
excavating nearly 450 cubic metres or 32 displacement
tons of material during their lifespan. However, the
Nano Queen is also equipped with a small fabrication
chamber, able to recycle the worn-out nanos and
return them to service. With the original set of nanos
and spare material carried in a small internal storage
container the Nano Queen can guide the excavation of
five displacement tons per week essentially indefinitely.
A Nano Queen must remain within 50 metres of nanos
to maintain control but nanos continue to function
at their assigned tasks with all the literalness of a
Primitive-brained robot if the controlling robot moves
out of range to recharge its power cells.

A Nano Queen’s cost does not include an initial set
of nanos. It normally carries eight 0.1 litre packages
of nanos, as that is the most it can control, although
it might set additional nano swarms in operation for
a simple task, such as ‘dig a tunnel three metres
in diameter in a straight line until deactivated or

Robot Hits Locomotion Speed TL Cost
Construction
Nano Queen

8 Walker 3m 14 Cr400000

Skills Athletics (endurance) 2, Electronics (remote ops) 2, Profession (construction) 2, Profession
(fabrication) 2
Attacks —
Manipulators 2x (STR 6 DEX 9)
Endurance 778 hours + Solar Coating (advanced)
Traits Armour (+4), ATV, IR/UV Vision, Small (-2)
Programming Very Advanced (INT 9)
Options Auditory Sensor, Drone Interface, Fabrication Chamber (1 Slot enhanced), Gecko Grippers,
PRIS Sensor, Solar Coating (advanced), Storage Compartment (hazardous material), Swarm
Controllers (advanced) x2, Transceiver 5,000km (enhanced), Vacuum Environment Protection,
Voder Speaker, Wireless Data Link

reprogrammed. The robot can carry up to two litres (20
packages) of nanos or nano components internally.
Components require a full day to assemble in the
fabrication chamber and each production run must
be of identical nanos but raw components cost only
half the price of functional nanos. For every year of
operation, repeatedly recycled nanos consume their
equivalent amount of raw components.

**Neumann Archon-Class Nanotech**
The Shield Church rules the world of Neumann,
keeping in bay an ancient nanotech plague that
devasted much of the planet. Archons are high
officials of the Church, leaders in the battle against
rouge nanotech and representatives of the Church
to the outside universe. Their nanos allow them to
better perform these duties. At TL13, this nanotech
must be renewed annually.

Item TL Effects Litres Cost
Archon-Class Nanotech 13 END+3, INT+2, STR+1, DEX+1, DM+4
to resist nanotech infections

1.4 Cr360000

Item TL Effects Litres Cost
Neumann Knight-Class
Nanotech

13 END+3, STR+1, DEX+1, DM+4 to
resist nanotech infections

1.2 Cr240000

**Neumann Knight-Class Nanotech**
The frontline fighters in Neumann’s war against rogue
nanotech are the Flame Knights. To aid their struggle,
they receive an annual infusion of medical nanotech to
increase their fighting prowess and resist infection.

Strend Les Mecanismes Nanotech
The world of Strend, lying beyond the Imperium’s
borders in the Menorial subsector of the Trojan
Reach, is ruled by a cybernetic elite known as Les
Mecanismes. These reclusive rulers are rumoured
to be centuries-old, their health maintained by
cybernetics, anagathics and nanotech. At TL14, their
nanotech must be replenished every two years and for
the oldest of them, the anti-aging portion of this mixture
has long since lost efficacy.

Item TL Effects Litres Cost
Les Mecanismes Nanotech 14 END+3, INT +3, STR+1, DEX+1, Age
rate reduction

1.5 Cr480000

## A NDROIDS

Androids are synthetic beings that remain steeped in
controversy and distrust, especially in regions where
unease with robots impersonating biological beings is
prevalent. These ‘pseudobiological’ robots, to use the
technical term – or ‘skinjobs’ to use the common slur –
look more and more like natural beings as their bodies
and minds grow more sophisticated. Those who fit best
into society are those who have their own, non-natural
identity, carving a niche for a new type of organism,
not one overtly reminding the biological sophonts they
might one day be replaced.

Android, Enhanced
The Enhanced Android is the first model that can pass
as biological without very close inspection. Although
not inexpensive, this model is designed for flexibility,
with one of four spare Slots available for a chassis
‘undercoating’ including armour or environmental
protection options. The additional three Slots are located
among modular components and can be installed in
arms or torso with relocation of internal components.
Equipped with a self-repairing chassis, the Enhanced
Android is intended for operating environments that
might be hazardous to biological beings and is equipped
with a highly efficient power system capable of nine days
continuous operations. Improved sensors, including
multi-frequency PRIS vision, allow it to operate as a
scout in remote locations. Three Bandwidth of computing
power are reserved for skill packages and one of the
spare Slots can be used for expanded Bandwidth if
desired. The Enhanced Android comes in six common
humanoid models, with customisation available, subject
to the normal tripling of option prices for android
installation, both at purchase and at a later date.

Robot Hits Locomotion Speed TL Cost
Enhanced Android 20 Walker 7m 12 MCr2
Skills Athletics (dexterity) 2, Athletics (strength) 2, Navigation 1, Recon 2, +3 Bandwidth available
Attacks —
Manipulators 2x (STR 12 DEX 12)
Endurance 216 hours
Traits ATV, Heightened Senses, IR/UV Vision
Programming Very Advanced (INT 9)
Options Android (enhanced), Auditory Sensor (broad spectrum), Drone Interface, Navigation System
(basic), Olfactory Sensor (basic), PRIS Sensor, Recon Sensor (enhanced), Self-Repairing
Chassis, Spare Slots x4, Transceiver 500km (enhanced), Voder Speaker, Wireless Data Link

**Android, Superior**
Still an experimental development, the Superior
Android is a robot designed to mimic sentient beings
in every way bar one – free will. These robots
can pass themselves off as human (or any other
species), although they are typically marked in some
way so confusion does not arise, and designed
to be employed in tasks that would normally
require sentience but are repetitive, unpleasant or
dangerous. This includes long-ranged exploration,
advanced construction and pleasure duties. Superior
Androids can be programmed with any skill or
range of skills, up to level 4. These androids are
powered by a shielded short duration RTG, allowing
completely independent field operations for five
years, a built-in obsolesce feature which adds
considerably to their cost, but provides a safety
valve to ensure these highly advanced robots do not
develop in unexpected directions.

Robot Hits Locomotion Speed TL Cost
Superior Android 24 Walker 6m 16 MCr14
Skills As defined upon purchase, +15 Bandwidth available
Attacks None as standard, 2 Slots available
Manipulators 2x (STR 12 DEX 12)
Endurance 5 years RTG half-life (130 hours)
Traits ATV, Heightened Senses
Programming Self-aware (INT 13)
Options Android (superior), Auditory Sensor, Environment Processor, RTG Short Duration
(advanced), Spare Slots x2, Transceiver 5km (improved), Visual Spectrum Sensor, Voder
Speaker (broad spectrum), Wireless Data Link

**Body Double**
A Body Double is a custom android built to emulate
a specific person. As a custom model, these robots
generally sell for a premium and are only available
from speciality retailers with a reputation for both
quality and discretion. A Body Double requires weeks
of acclimation in the presence of its biological double
in order to perfect its deception. Body Doubles are
designed to protect a target from assassination or
abduction and can switch into a combat mode to
protect themselves and fend off an attack. If abducted,
they are programmed to self-destruct, igniting a
powerful charge that also detonates their long-
duration power packs.

Body Doubles are illegal or restricted on many worlds,
although those who can afford them often have ways
to circumvent regulations. These restrictions are
based on two factors: First, many worlds derive their
robot regulations from the Shudusham Concords, an
ancient robot treaty whose 37th Amendment specifically
prohibits androids from passing as living beings.
Second, the self-destruct feature is a direct affront to
the incident that led to the Concords in the first place.
In some instances, a compromise configuration is
available, one that does not include the self-destruct
device but a system for notifying local law enforcement
under specified conditions, such as abduction or
direct threats to the Body Double. Also, some variants
are required to respond to a correctly worded or
transmitted challenge and identify themselves as
artificial beings. Some Body Doubles are manufactured
with these restrictions and later altered by their owners
to contravene them, a crime on many worlds with
penalties ranging from fines to long-term incarceration.

Detecting a Body Double normally requires a Very
Difficult (12+) Investigate check (1D minutes, INT),
although someone with great familiarity of the original
will only find this task Difficult (10+). A medical exam or
densitometer check instantly determines the true nature
of the Body Double.

MCr1.8 is a starting price for a Body Double. While a
Body Double can emulate the behaviour of its biological
template, it does lack the person’s skills; additional
computing capacity is required to emulate any skills
possessed by the original. The robot’s endurance
allows for more than 36 days of continuous operation
or nearly two months if emulating ‘sleep’; this is
sufficient in most technological areas as the robot can
surreptitiously recharge but robots intended for long-
term field use require RTG power units, which vastly
increase the cost of the Body Double.

Robot Hits Locomotion Speed TL Cost
Body Double 20 Walker 5m 15 MCr1.8
Skills Athletics (all) 2, Deception 2, Melee (unarmed) 4
Attacks Claws (1D+4 ), Self-Destruct (12D, Blast 5)
Manipulators 2x (STR 12 DEX 12)
Endurance 864 hours
Traits Armour (+6), ATV
Programming Very Advanced (INT 11)
Options Android (advanced), Auditory Sensor, Self-Destruct System: Offensive, Transceiver 5km
(improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

**Ceiling Cat**
A robotics exhibition concept model from the Shinku
University Research Directorate (SURD), which became
a status symbol among the wealthy, the Ceiling Cat or ‘the
Cat That Walks Up Walls’ is an extremely realistic android
cat. Its tiny front paws and prehensile tail are all dexterous
manipulators and the gecko pads on all four paws allow
it to climb not only up walls but also across ceilings. It
requires a Very Advanced Brain to control its natural-
looking body and give it the quickness and sensory skills

Robot Hits Locomotion Speed TL Cost
Ceiling Cat 4 Walker 8m 15 Cr360000
Skills Athletics (dexterity) 3, Recon 2, Stealth 3
Attacks —
Manipulators 4x (STR 3 DEX 12)
Endurance 144 hours
Traits ATV, Heightened Senses, IR Vision, Small (-3)
Programming Very Advanced (INT 9)
Options Android (advanced), Auditory Sensor (broad spectrum), Drone Interface, Gecko Grippers, Light
Intensifier Sensor (advanced), Olfactory Sensor (advanced), Transceiver 500km (advanced),
Vacuum Environment Protection, Voder Speaker, Wireless Data Link

it needs, making it smarter than many of its well-heeled
owners. Available in dozens of ‘breeds’ and with custom
Zero-Slot options beyond the standard vacuum-proofing
and ‘sticky’ paws, a Ceiling Cat can run up to MCr1 or
more. The robot tends to develop a strong attachment
to its owner and its cat-like personality makes second-
hand Ceiling Cats finicky purchases. Although SURD
offers a programming reset service for ‘only’ Cr20000, it
sometimes does not take.

**Companion**
A Companion is a lower cost advanced android
designed to closely emulate a biological being.
Beyond an obvious utility, the Companion
is often used as a lower cost body double,
emulating physical appearance, but not adept at
the mannerisms or skills of the original. There
is a niche market for Companions that are
duplicates of historical or fictional characters for
use in performance art roles.

The basic Companion model costs Cr900000
but has considerable upgrade protentional. Six
spare Slots can hold anything from an avatar
interface to a concealed weapons system. The
spare Slots of the companion are located in
the arms and torso, and the structure of the
Companion precludes retrofitting coatings and
whole chassis upgrades such as armour or
environment protection options.

Upgrades to the brain must normally be installed
upon manufacture but can greatly increase skill
range and expertise. Even without upgrades,
the robot has one Bandwidth available for
additional programming. All upgrades to the
Companion except skill packages are subject
to standard tripling of cost to accommodate
android compatibility.

Robot Hits Locomotion Speed TL Cost
Companion 20 Walker 6m 14 Cr900000
Skills Art (performer) 2, Athletics (dexterity) 1, Athletics (strength) 1, Carouse 1, Medic 1, Steward 1,
+1 Bandwidth available
Attacks —
Manipulators 2x (STR 9 DEX 9)
Endurance 108 hours
Traits ATV
Programming Very Advanced (INT 9)
Options Android (advanced), Auditory Sensor, Drone Interface, Olfactory Sensor (basic), Spare Slots x6,
Storage Compartment (2 Slots), Transceiver 500km (advanced), Visual Spectrum Sensor, Voder
Speaker (broad spectrum), Wireless Data Link

**Counsellor**
Most robots find interpersonal skills difficult,
requiring extra Bandwidth to properly process natural
conversations and meaningful interactions with
biological sophonts. The Shinku University Research
Directorate (SURD) has challenged this deficiency
with an advanced android that is not only physically
convincing, but conversationally convincing and
then taking this one step further to create the very
lifelike Counsellor as an expert in psychology
and interpersonal relationships. Applying SURD’s
known prowess in convincing android construction
and the most advanced robotic brain available,
the Counsellor can provide expert psychological
services and interact with biological beings. Highly
intelligent, it often uses spare Bandwidth 0 skills to
study additional languages or obscure dialects in
order to interact convincingly with the broadest range
of people. The Counsellor demands a high price
but is sometimes found as a confidential advisor to
members of government and industry at the highest
levels. The Counsellor intentionally does not have a
drone interface installed, making it more difficult to
remotely access. It does however have an advanced
robotic drone controller to manage subsidiary
drones on its own and three spare Slots for custom
‘special options’, which can include armour or other
environmental options if specified at purchase.

Robot Hits Locomotion Speed TL Cost
Counsellor 20 Walker 6m 15 MCr5.6
Skills Admin 2, Advocate 2, Athletics (dexterity) 1, Athletics (strength) 1, Carouse 4, Deception 4,
Electronics (all) 2, Investigate 4, Leadership 3, Medic 3, Persuade 4, Profession (counsellor) 4,
Recon 2, Science (psychology) 4, Steward 2, Streetwise 2
Attacks —
Manipulators 2x (STR 9 DEX 9)
Endurance 288 hours
Traits ATV, Heightened Senses, IR/UV Vision
Programming Self-aware (INT 12)
Options Android (advanced), Auditory Sensor (broad spectrum), Olfactory Sensor (advanced), PRIS
Sensor, Quick Charger, Robotic Drone Controller (advanced), Self-Repairing Chassis, Spare
Slots x3, Transceiver 500km (advanced), Voder Speaker (broad spectrum), Wireless Data Link

**Elvis Performance Double**
Manufactured by Makhidkarun’s entertainment
division, this robot is named after a pre-spaceflight
[[Terra|Terran]] performer more known for his impersonators
than any of his lost recordings. Very few of these
androids are actually duplicates of Elvis but a wide line
of impersonation robots provides copies of past and
present performers from throughout Charted Space.
These duplicates mimic the gestures, voice and talents
of singers, actors, poets and other performers. Touring
groups of major interstellar entertainers often send these
doubles to ‘B-List’ systems off the main trade lanes to
increase their tour revenues.

Some performance troupes consist of a single
android and support crew, others are large
companies of android entertainers who set up
shop in major population centres for extended
performances across a wide variety of arts. While
each android is normally sculpted and programmed
to emulate a specific real or fictional performer,
some more generic models have replaceable faces
and reprogrammable personalities to allow them
to impersonate a variety of characters with similar
builds. To cut costs, these performance doubles are
not built with the most advanced android technology
or the latest available robotic brains but they are
not designed for close-up one-on-one encounters
although more than sufficient to be convincing
doubles before a crowd of spectators. Vast high-tech
Makhidkarun factories can produce these robots by
the thousands, distributing them across sectors from
the Spinward Marches to the Solomani Rim.

A built-in avatar receiver allows some individuals with
the proper cybernetic implants to inhabit the body
of a performance double, allowing an expensive
form of cybernetic karaoke. For those without the
considerable brain hardware required to control an
avatar, Makhidkarun sells a bundle including both the
Performance Double and a deluxe avatar chair for
only Cr950000.

Robot Hits Locomotion Speed TL Cost
Elvis
Performance Double

20 Walker 6m 15 Cr500000

Skills Art (performer) 3, Athletics (dexterity) 1, Athletics (strength) 1, Deception 1
Attacks —
Manipulators 2x (STR 9 DEX 9)
Endurance 144 hours
Traits ATV
Programming Very Advanced (INT 9)
Options Android (enhanced), Auditory Sensor, Avatar Receiver, Drone Interface, Spare Slots x7,
Transceiver 5km (improved), Visual Spectrum Sensor, Voder Speaker (broad spectrum),
Wireless Data Link

**Dupal Companion Robot**
Dupal was designed as a children’s companion. It is
a soft-skinned robot with a basic android shape of a
pink elephant with fully developed hands on its front
limbs and a flexible grasper trunk that acts as a third
manipulator. About the size of a large dog, the Dupal
is meant to act as nanny, companion and nurse-mate
for children under the age of 10. It is sometimes used
to aid the elderly in the home and has the strength
to lift and support a full-sized human if necessary.
Equipped with cleaning equipment, a medical kit and
a fire extinguisher, the Dupal loyally watches over
its charge. Its cartoonish pink elephant appearance
coupled with the ability to stand fully upright sometimes
leads to derisive comments but its target demographic
of children and elderly dementia patients find the Dupal
to be a pleasant and helpful companion.

Robot Hits Locomotion Speed TL Cost
Dupal Companion Robot 12 Walker 6m 12 Cr90000
Skills Medic 1, Profession (caregiver) 1
Attacks —
Manipulators 3x (STR 9 DEX 7)
Endurance 108 hours
Traits ATV, Small (-1)
Programming Advanced (INT 8)
Options Android (basic), Auditory Sensor, Domestic Cleaning Equipment (small), Drone
Interface, Fire Extinguisher, Medikit (improved), Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless Data Link

Surrogate Droid, Improved
A Surrogate Droid is a natural-looking android upgrade
to the basic droid. While its internal bioreactor is
hardly more complex than that of its robotic-looking
predecessor, the improved Surrogate Droid can pass
as a biological being at a distance. With an advanced
brain and flexible programming, it can fit into a
household, although by default is equipped to function
as domestic servant or caregiver, often of a child it
has previously carried to term. In some societies, this
robot is termed a ‘mommy bot’ in others, such a role is
considered taboo or at least in poor taste.

Robot Hits Locomotion Speed TL Cost
Improved
Surrogate Droid

20 Walker 6m 10 Cr500000

Skills Medic 0, Profession (domestic servant) 1, Science 0, Steward 1
Attacks —
Manipulators 2x (STR 9 DEX 6)
Endurance 65 hours
Traits ATV, Heightened Senses
Programming Advanced (INT 6)
Options Android (enhanced), Auditory Sensor (broad spectrum), Bioreaction Chamber (8 Slots,
enhanced), Drone Interface, Olfactory Sensor (basic), Transceiver 5km (improved), Visual
Spectrum Sensor, Voder Speaker, Wireless Data Link

**Synthetic Horse**
On worlds where vehicles are prohibited or restricted,
Travellers are often forced to rely on animal
transport. The [[Terra|Terran]] horse is a common form of
animal locomotion across regions of Charted Space
with any Solomani heritage. Riding a horse is a
particular skill that most members of a technological
society have not mastered, so rather than suffer
the indignities of struggling with an unpredictable
mount and ‘negotiating’ direction and speed of travel,
some Travellers choose to import a synthetic horse,
an android ‘animal’ close enough to pass most
inspections, especially on low tech planets.

Robot Hits Locomotion Speed TL Cost
Synthetic Horse 32 Walker 11m 11 Cr150000
Skills Athletics (endurance) 2, Melee 0, Recon 0
Attacks Kick (2D), Bite (1D)
Manipulators —
Endurance 86 hours
Traits Armour (+0), ATV, Large (+1)
Programming Basic (horse) (INT 4)
Options Android (improved), Auditory Sensor, Drone Interface, Spare Slots x16, Transceiver 5km
(improved), Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

The Synthetic Horse is an old android design with many
variations available for sale and even short-term lease
options offered at nearby higher tech worlds. The Basic
robot brain contains a custom package designed to
emulate the behaviour of a horse and respond to both
verbal and electronic commands in a manner that mimics
the real animal. It even has the capacity to ‘eat and drink’
and use the chemical energy of the input to recharge
its extra power packs. While standard models are very
reasonably priced for androids, with costs reduced by
millennia of production since the Synthetic Horse’s
introduction during the Long Night; adding options to the
android’s significant spare capacity, and especially adding
full body options, requires triple the cost of those options
for androids plus an installation charge, which can be
especially high for retrofits.

## B IOLOGICAL ROBOTS

These robots are biological beings, usually clones or
otherwise vat-grown, with a robot brain and interfaces
replacing their natural nervous system. As such, they
have poor public perception in many cultures. Legality
and acceptance vary drastically.

Entourage Biobot
The Entourage Biobot is for people who want to have
a large entourage but who may not have the charisma
or prestige to maintain one. They must have a fair
amount of money, however. This is an improved
biological robot built around a cloned or manufactured
body and equipped with an artificial brain and nervous
system. Appearance can be customised and some
genetic profiles may add to the cost of the biobot.
Normally produced in enhanced fabrication chambers
with a brain separately produced but integrated into
the process, these robots are flexible in appearance
and can support most skill level 2 packages. Upgraded
brains are available, although they add significantly
to the biobot’s cost. A skill package can be switched
out for Cr50000 with wireless data link remote
programming, as the brain is embedded in a biological
skull and has no serviceable parts. As a biobot, it is
subject to normal healing and aging. Its four spare
Slots are placed in prespecified custom location, with
up to two Slots available in each arm or up to all four
Slots available in the torso. These add-ons usually
require access for service.

Robot Hits Locomotion Speed TL Cost
Entourage Biobot 20 Walker 6m 13 Cr390000
Skills Art (TBD) 2, Athletics (dexterity) 1, Athletics (strength) 1
Attacks —
Manipulators 2x (STR 9 DEX 9)
Endurance As biological being
Traits Armour (+0), ATV
Programming Advanced (INT 8)
Options Auditory Sensor, Biological Robot (improved), Drone Interface, Olfactory Sensor (basic),
Spare Slots x4, Transceiver 500km (enhanced), Visual Spectrum Sensor, Voder Speaker
(broad spectrum), Wireless Data Link

**Impersonator**
Ever want to be some else? The Impersonator
is an avatar drone designed to allow a person
to inhabit the body of a biological robot through
the use of avatar control technology. Each
Impersonator is a custom biological robot,
a designed and quick-grown clone with an
embedded avatar receiver and robotic brain.
Actual physical characteristics vary depending
on the characteristics of the clone itself. When
not operating under avatar or drone control, the
Impersonator’s Basic robot brain allows it to
follow basic instructions, feed and clean itself,
but has no special skills. The price indicated for
the Impersonator is for a standard clone, quick-
grown from a template or sample. Custom clones
with exceptional attributes or created genomes
might be more expensive. Batch purchases of
the same model may reduce costs by up to 25%.
The Impersonator is not bundled with any sort of
avatar control system, although resellers might
offer a package deal.

The legality of Impersonators varies with
jurisdictions. It is a category of robot not covered
in the Shudusham Concords and some would
argue it is not really much of a robot at all.

Robot Hits Locomotion Speed TL Cost
Impersonator 20 Walker 6m 13 Cr400000
Skills —
Attacks —
Manipulators 2x (STR 9 DEX 8)
Endurance As biological being
Traits none
Programming Advanced (INT 8)
Options Auditory Sensor, Avatar Receiver, Biological Robot (improved), Drone Interface, Olfactory
Sensor (basic), Spare Slots x3,Transceiver 5,000km (improved), Visual Spectrum Sensor,
Voder Speaker, Wireless Data Link

**Zombie**
Rather than build a biological robot, especially
at lower Tech Levels where this can be a lengthy
process, why not just appropriate a fully-grown body
to act as a biological robot? While these biological
robots are generally designated by obfuscated
brand names, such as ‘Supplemental Labour Unit’ or
‘Biological Work Beings’ they are nearly universally
referred to as ‘zombies’.

Zombie might be a technical misnomer for this type of
biological robot, as working with the already deceased
can be challenging. However, working with functional
bodies of brain-dead individuals, ‘snatching’ living
beings or applying a rather macabre form of capital
punishment are ways to acquire a living being ripe
(or at least ready) for robotic brain implantation. The
procedure is still complicated, feeding cybernetic
nerves into biological nerves, and often benefits from
the skills of a cyberneticist, but as early as TL11 a
biological being can be converted into a biological
robot and put to work as essentially slave labour.

Zombies can be commanded via drone or swarm
controllers, usually as large work teams.

Robot Hits Locomotion Speed TL Cost
Zombie 20 Walker 6m 11 Cr100000
Skills Profession (labourer) 2
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance As biological being
Traits —
Programming Basic (labourer) (INT 4)
Options Auditory Sensor, Biological Robot (basic), Drone Interface, Olfactory Sensor (basic), Spare
Slots x3, Transceiver 50km (enhanced), Visual Spectrum Sensor, Voder Speaker, Wireless
Data Link

## C YBORGS

In addition to the cybernetic parts and other augments
listed in the Personal Augmentation chapter of the
Central Supply Catalogue (pages 86–93) many
customised, and some rather extreme cyborg options
are available, partially or mostly converting a biological
being into hybrid of flesh and electronics.

Android Body Cyborg, Advanced
For individuals whose body is too badly damaged for
regeneration, some advanced medical facilities provide
the option to transplant the brain into an android body.
This procedure is inherently risky and remains liable
to cause psychological problems in the transplanted
individual years after the procedure is completed but
is considered a costly last-ditch option to save a life.
The advanced android body passes close inspection
as natural but is enhanced with superior strength,
agility and senses far beyond natural ranges. Still, the
cost of the android body is barely a third of the cost
of the procedure to implant the brain and enhanced
capabilities are considered a reasonable trade-off for
the risks involved.

The android body has a cost of Cr770000 and the brain
transplantation procedure adds MCr2. The body has
four spare Slots available for customisation, one in
each arm and two in the torso. The body can withstand
hostile-environment conditions, including vacuum and
has extra protection against radiation and physical
damage. Additional full body options such as thicker
armour are not available. Up to 12 Zero-Slot options
could be added to the advanced android body cyborg.

Robot Hits Locomotion Speed TL Cost
Advanced Android
Body Cyborg

20 Walker 6m 14 MCr2.77

Skills Athletics (dexterity) 1
Attacks -—
Manipulators 2x (STR 12 DEX 12)
Endurance 216 hours
Traits Armour (+3), ATV, Heightened Senses, IR/UV Vision
Programming Natural brain
Options Android (advanced), Auditory Sensor (broad spectrum), Full Body Cyborg (improved),
Olfactory Sensor (advanced), PRIS Sensor, Radiation Environment Protection (+700 rads),
Spare Slots x4, Transceiver 500 km (advanced), Vacuum Environment Protection, Voder
Speaker (broad spectrum), Wireless Data Link

**eGore**
The eGore full body cyborg was developed as an
alternative to punishment on a desolate mining world.
The procedure often resulted in the death of the
prisoner but when successful allowed the recipient
to operate tools and machinery on the surface of the
airless radiation-baked world. A combination of high
cost for the transformation procedure and significant
risks, both during the procedure and afterwards, led to
the suspension of the world leadership’s pet project.
The designs and procedures have long since become
open source, allowing ‘mad scientists’ and other parties
to perform the procedure, often without safeguards
or permission. The cost of the robot body is nearly
insignificant compared to the cost of the procedure,
especially since detailed plans and instructions are
freely available. Some models come equipped with a
remote-initiated defensive self-destruction option.

Cyborg Hits Locomotion Speed TL Cost
eGore 20 Walker 5m 12 MCr1.04
Skills Recon 3
Attacks —
Manipulators 2x (STR 15 DEX 7)
Endurance 108 hours
Traits Armour (+4), ATV, IR/UV Vision
Programming Natural brain
Options Auditory Sensor, Cutting Torch (improved), Drone Interface, Full Body Cyborg (basic),
Mechanical Toolkit (advanced), Olfactory Sensor (basic), PRIS Sensor, Quick Charger,
Radiation Environment Protection (+600 rads), Recon Sensor (advanced), Storage
Compartment (1 Slot), Spare Slot, Transceiver 50km (enhanced), Vacuum Environment
Protection, Voder Speaker, Wireless Data Link

Floating Eye
The Floating Eye is a high-tech detachable advanced
cybernetic eye, capable of independent grav flight and
control up to 500 kilometres away from its controller.
Its detachability and natural appearance categorise it
as an espionage device in those jurisdictions where
such things are regulated, assuming it can be detected.
Available at TL14, the Floating Eye sells at a premium
if available at all. Multiple eyes require independent
visual interfaces when operating detached, although a
biological-initiated avatar control system can control two
eyes and save the Cr50000 price tag associated with
each floating eye’s visual interface.

Augment Hits Locomotion Speed TL Cost
Floating Eye 1 Grav 6m 14 Cr250000
Skills —
Attacks —
Manipulators —
Endurance Indefinite, 36 hours independent
Traits Flyer (idle), IR/UV Vision, Small (-4)
Programming none
Options Advanced Eye (PRIS), Detachable, Grav-propelled, Invisitech, Natural Looking (TL14), Remotely-
operated, Ruggedised, Self-repairing, Transceiver 50km, Visual Interface, Wireless Data Link

**Meatbox Pilot**
An experimental project created a box containing
both a human and Very Advanced robotic brain to be
installed in a starship. The arrangement was meant to
overcome astrogation restrictions on artificial brains by
providing a conscious sophont mind able to interpret
astrogation results and mitigate the risk of misjump.
It also allowed scout vessels to pack a greater
performance punch by eliminating the need for a bridge
or staterooms to support a crew. As the process left the
brain as essentially payload in a small box, it relied on
volunteers whose bodies were damaged beyond repair
and coercion on people charged with capital crimes,
often piracy. The project was scaled back because of
psychological problems with the brains that the robot’s
personality was unable to alleviate. Even the promise
of eventual transference into an android body did not
lower risks of psychosis among the participants.

The Meatbox Pilot can be installed in any ship or
vehicle equipped with a brain interface, which is not
included in the cost. The parasitic link allows the small
box to be attached to a drone, allowing the robot or
brain to control its actions for mobility, although the
ships designed for Meatbox usage often had little
accommodation for internal access. The drone control
interface could be operated by either the robotic or
human brain but could only control one drone at a
time and the robotic brain retained overall command.
A standard ship’s computer running Virtual Crew and
possibly Auto-Repair software supplemented the
skills of the robot brain, who retained control of the
ship’s functions. The human brain had at least a basic
knowledge of astrogation and could assist the robot
brain using any other skills learned.

Robot Hits Locomotion Speed TL Cost
Meatbox Pilot 4 None 0m 14 MCr2.7
Skills Astrogation 4, Carouse 2, Electronics (all) 2, Engineer (all) 2, Gunner 0, Pilot (spacecraft) 3,
Tactics (naval) 3
Attacks —
Manipulators —
Endurance 324 hours
Traits Armour (+4), Small (-3)
Programming Very Advanced (INT 12) + Natural brain
Options Drone Control Interface (advanced), Full Body Cyborg (improved), Parasitic Link, Radiation
Environment Protection, Transceiver 5km (improved), Vacuum Environment Protection, Voder
Speaker, Wireless Data Link

**Quick Arm**
The Quick Arm is a natural-looking TL15 arm designed
for speed and strength. Armoured and equipped
with an empty small weapon mount, it can use an
embedded or hand-held weapon with great strength
and precision. A premium item, it is only available
at high-tech cybernetics clinics and not something
normally available as a medical replacement part or in
back-alley augment shops.

Augment Hits Locomotion Speed TL Cost
Quick Arms 8 — — 15 Cr275000
Skills —
Attacks —
Manipulators 1x (STR 15 DEX 15)
Endurance Indefinite
Traits Armour (+12)
Programming Advanced Interface
Options Advanced Interface, Invisitech, Natural Looking (TL14), Ruggedised, Self-repairing, Small
Weapon Mount

Running Legs
Available at TL12, these artificial legs are designed
to allow running at twice normal human speed almost
indefinitely. Each leg has up to four Slots available
for customisations, which could include armour or
other coatings and internal options. These legs make
no effort to look natural but are focused on achieving
speed at a relatively affordable price.

Augment Hits Locomotion Speed TL Cost
Running Legs 8 each Walker 12m 12 Cr67000
Skills —
Attacks none
Manipulators 2x (STR 12 DEX 7)
Endurance Indefinite
Traits Armour (+4)
Programming Enhanced Interface
Options Enhanced Interface, Spare Slots x4 (each)

## A VATARS

An avatar is a robot body with a remote brain, whether
electronic or biological. More than a drone, the remote
brain ‘becomes’, in part or in whole, the robot body.
A biological being experiences a ‘presence’ that goes
beyond virtual reality, feeling as if they are that living
being, not just wearing an electronic interface, not
merely ‘dreaming’ another life. A robotic brain controlling
an avatar runs natively within the avatar’s brain, which is
different than using the brain as a remote-control point.

Avatars might have different body shapes but it is this
presence that sets them apart from other types of
synthetic beings.

Ava Ship’s Avatar
Able to operate with any ship’s brain equipped with an
avatar controller, the Ava avatar is a basic humanoid
robot, a clearly artificial being but capable of comfortably
operating from standard crew workstations and use
of most tools. Equipped with its own set of electronic,
mechanical and starship engineer tools, Ava is just as
at home behind a bridge station as in a damage control
party. Able to withstand vacuum and radiation, Ava’s
hands and feet are covered in gecko gripper material,
allowing operation both inside and outside a spacecraft
in a variety of conditions.

Heightened senses, including PRIS vision, allow Ava to
quickly locate the source of problems before a biological
being is even aware of them. Ava is designed to operate
as a ship’s avatar and not an independent robot.

Robot Hits Locomotion Speed TL Cost
Ava Ship’s Avatar 20 Walker 6m 12 Cr100000
Skills From ship’s brain up to 6 Bandwidth
Attacks —
Manipulators 2x (STR 9 DEX 7)
Endurance 194 hours
Traits Armour (+10), ATV, Heightened Senses, IR/UV Vision
Programming Advanced (INT 8)
Options Auditory Sensor (broad spectrum), Avatar Receiver, Cutting Torch (improved), Electronics
Toolkit (enhanced), Fire Extinguisher, Gecko Grippers, Mechanical Toolkit (advanced),
Olfactory Sensor (improved), PRIS Sensor, Radiation Environment Protection (600 rads),
Starship Engineer Toolkit (enhanced), Transceiver 500km (improved), Vacuum Environment
Protection, Voder Speaker (broad spectrum), Wireless Data Link

Bandwidth 6 allows for a subset of a ship’s brain skill
package to run, including two Bandwidth 0 packages. If
desired, innate skill packages can be installed but these
subtract from Bandwidth available for avatar use and
these packages are unavailable when Ava is acting as
an avatar of the ship’s brain.

**Macro Hero**
RoboHero’s largest and most expensive product
is also its most controversial. The Macro Hero is
a 2:1 scale robot ranging up to four metres tall.
It is designed as an avatar host along the lines
of its Micro and Nano Heroes but its large size,
armour, resiliency and massive customisable
spare capacity makes it a possible back-door war
machine of extraordinary power. Equipped like its
smaller brethren to allow an adventurer to take
on the persona of a different scaled robot, the
Macro Hero is much more capable. Its visilight
camouflage allows customisation of features but
also near invisible camouflage, although nothing
can dampen the sound of the footsteps of a robot
massing more than a ton. With gecko grippers
it can scale walls and powerful muscles mean it
runs faster than a human and maintains that pace
for hours. Its armour and radiation protection
makes it more powerful than battle dress and it
can absorb a massive amount of damage before
being disabled. While this behemoth starts at
Cr920000, options and customisation usually
drive the cost far above MCr1 and RoboHero’s
waiting list for custom Macro Heroes stretches
past a year. Used Macro heroes often sell at a
premium as collector’s items.

Robot Hits Locomotion Speed TL Cost
Macro Hero 86 Walker 9m 13 Cr920000+
Skills Athletics (dexterity) 1, Athletics (strength) 4, Stealth 4 + up to 2 Bandwidth
Attacks —
Manipulators 2x (STR 18 DEX 12)
Endurance 151 hours
Traits Armour (+27), Heightened Senses, ATV, Large (+3), IR/UV Vision
Programming Advanced (INT 8)
Options Auditory Sensor (broad spectrum), Avatar Receiver, Camouflage: Visual (superior), Gecko
Grippers, PRIS Sensor, Radiation Environment Protection (+650 rads), Spare Slots x100,
Transceiver 500km (enhanced), Vacuum Environment Protection, Voder Speaker,
Wireless Data Link

**Micro Hero**
The RoboHero-produced Micro Hero is a
rat-sized 1:10 scale avatar developed for
advanced adventure gaming. Each Micro
Hero is a custom figure, equipped with
a visilight camouflage surface that can
project various ‘features’ on the robotic
body. Equipped with gecko grippers
and able to operate in a vacuum and
in low light-situations, the Micro Hero
allows the ‘adventurer’ to explore pre-set
environments or, often with an upgraded
transceiver, real wilderness locations
as a rodent-sized heroic figure. Custom
models generally start at Cr30000 but
rare collectors’ editions or one-of-a-kind
body shapes might go for many times
this amount.

The Micro Hero’s Advanced brain is
normally an avatar receptacle but
the robot can operate independently
and install up to Bandwidth 2 of skill
packages and two level 0 skill packages
at additional cost.

Robot Hits Locomotion Speed TL Cost
Micro Hero 1 Walker 6m 13 Cr30000+
Skills Athletics (dexterity) 1, Stealth 4 + up to 2 Bandwidth
Attacks —
Manipulators 2x (STR 2 DEX 9)
Endurance 108 hours
Traits Armour (+4), ATV, IR Vision, Small (-4)
Programming Advanced (INT 8)
Options Auditory Sensor, Avatar Receiver, Camouflage: Visual (superior), Drone Interface, Gecko
Grippers, Light Intensifier Sensor (advanced), Olfactory Sensor (basic), Transceiver 5km
(improved), Vacuum Environment Protection, Voder Speaker, Wireless Data Link

## C LONES

A clone is a biological entity grown from a genetic code,
whether natural, modified or created. It does not have
a robotic brain, although it might be cybernetically
enhanced. Cloned beings with robot brains are not
considered clones but biobots. Clones are biological
bodies and brains, despite how fast they can grow, how
strange their genetic code is or how many augments
they contain. As such most jurisdictions who grant
freedoms to all ‘biological sophonts’ treat clones – at
least those who retain a functioning brain – as ‘people’,
not property. At least in theory.

**BLACKSAND WIDOWBLACKSAND WIDOW**

TRAITS SKILLS
STR 10 INT 7 Athletics (dexterity) 2,
Deception 1, Diplomat 0,
Electronics (comms) 1,
Flyer (grav) 2, Gun Combat
(energy) 3, Gun Combat
(slug) 3, Investigate 2,
Medic 1, Melee (unarmed)
3, Persuade 1, Steward 1,
Streetwise 2

DEX 14 EDU 10
END 12 SOC 9

WEAPONS Gauss Rifle (4D), Laser Pistol
(3D+3), Stunner (3D, Stun
ARMOUR Lightweight Polycarapace Armour
(+12), Subdermal Armour (+3)
EQUIPMENT Enhanced Vision (TL14), Neural
Comm (TL14)

TL COST
15 CR790000 (with augments,
but without external armour or
weapons)

Blacksand Widow
The Blacksand Widow is a 12x force grown clone,
removed from the vat at an apparent age of six and
creche-trained for 16 years to become an elite trouble-
shooter for the Pirate Lords of Theev. A Widow is highly
trained and equipped within an embedded neural
comm and cybernetic eyes able to see into the infrared
and ultraviolet spectrums, as well as subdermal armour
beneath the skin. Constantly in communication with her
clone sisters, the Widow is a formidable force and part
of a network that keeps order in the otherwise lawless
city of Blacksand.

While it is not publicly acknowledged, GeDeCo
assassins and elite guards are clones built off a
different physical genome but otherwise identical in
skills and augmentation to the Blacksand Widows.

**Tandi Clone**
An entertainer and celebrity famous enough to
go by one name, Tandi’s death by strangulation
at age 40 was either suicide, accident or
(rumoured) murder, and only added to her fame.
Her will stipulated that her genome be available
for sale by her estate for implantation and
cloning. The will dictated that all Tandi Clones
must be naturally aged, although whether in a
natural or artificial womb was not specified. Base
characteristics (prior to +D3) are as follows.

A Tandi clone ready for implantation comes with
proper authentication. More expensive packages
including a Surrogate Droid plus dance and
music lessons from first rate instructors are
popular. The clone has a propensity for interest
and talent in artistic endeavours but also suffers
from mild bipolar disorder.

Bootleg Tandi clones, likely taken from samples
of clones instead of the original, are often
available for reduced rates and might be force-
grown. These bootleg copies generally have all
characteristics reduced by -1 and often suffer
from more severe emotional problems.

Name TL STR DEX END INT EDU SOC Skills Cost
Tandi Clone 13 4 7 5 8 — — — MCr1.5

**Underworker**
The Underworker is a 50x quick-grown clone given
one year of basic creche education to prepare for
the role of heavy labourer. Illegal or unacknowledged
on many worlds, Underworkers are often employed
as miners or night cleaners, far from the public eye,
spending their few short decades of life in anonymous
mindless labour. On worlds where clone rights
are protected, they are often ‘assigned’ indenture
contracts to pay for their own creation and creche
education, paid a pittance and made responsible for
their own upkeep. If they are lucky, they can just about
pay off their contract before they age and die.

During the course of their labours, the Underworker
learns additional skills related to their profession.

Name TL STR DEX END INT EDU SOC Skills Cost
Underworker 13 9 9 9 4 3 0 Profession (labourer) 2 Cr80000

## M ISSILE ROBOTS

Missile robots are either warhead or full chassis
devices launched from spacecraft missile and
torpedo launchers. They differ from other robots
mostly in their particular form of locomotion, at least
for initial delivery. These robots include both single
use probes, specialised military robots and robots
intended to be remotely delivered by missile or
torpedo propulsion. In theory any Size 2 or smaller
robot could be delivered by a missile and torpedoes
could deliver robots up to Size 4.

For reference, standard missile and torpedo chassis
are detailed to illustrate the default features of an
attached missile robot. Both missile and torpedo
buses are designed with thrusters as primary and
secondary locomotion modes and with vehicle speed
modification applied. Both have two power packs as
a proxy for burn duration.

Missile Chassis
The standard missile chassis is a homing missile. More
advanced missiles may have differing endurance or
more advanced electronics but the size of the warhead
or payload capacity is generally unchanged.

Robot Hits Locomotion Speed TL Cost
Missile (Chassis) 12 Thruster (x2) — 8 Cr24000
Skills Athletics (endurance) 2, Weapon 1
Attacks 4-Slot warhead or other payload equivalent to a Size 2 robot
Manipulators —
Endurance 6 (2) hours
Traits Armour (+2), IR Vision, Small (-1), Thruster (10G)
Programming Primitive (homing) (INT 1)
Options Drone Interface, Thermal Sensor, Transceiver 5km (improved), Vacuum Environment
Protection, Visual Spectrum Sensor

Torpedo Chassis
The standard torpedo chassis is similar to the missile
chassis but larger and of generally greater endurance.

Robot Hits Locomotion Speed TL Cost
Torpedo (Chassis) 32 Thruster (x2) — 8 Cr150000
Skills Athletics (endurance) 2, Weapon 1
Attacks 16-Slot warhead or other payload equivalent to a Size 4 robot
Manipulators —
Endurance 12 (3) hours
Traits Armour (+2), IR Vision, Large (+1), Thruster (10G)
Programming Primitive (homing) (INT 1)
Options Drone Interface, Thermal Sensor, Transceiver 5km (improved), Vacuum Environment
Protection, Visual Spectrum Sensor

**EyeSpy Satellite**
The EyeSpy satellite robot is a missile-delivered
reconnaissance satellite rated for up to a decade
of silent service with a self-maintenance option.
Stealth-coated to shield it against visual and
electronic detection, the small robot is the size of a
missile warhead assembly. When extended, its light-
absorbing solar panels provide the recon satellite
with unlimited power out to 2 AU from a standard
Sol star and to twice that distance with degraded
resolution on some sensors.

Its stealth capabilities provide DM-4 to visual
detection unless within 10 metres and DM-2 against
electronic detection by sensors of an equal Tech
Level. The EyeSpy can positively identify individuals
from low orbit and categorise buildings from typical
geosynchronous orbital distances. Its communications

Robot Hits Locomotion Speed TL Cost
EyeSpy Satellite 4 — 0m 12 Cr90000
Skills Recon 3, Stealth 4
Attacks —
Manipulators —
Endurance 10 years solar panel half-life (324 hours)
Traits Armour (+4), Small (-3), Heightened Senses, IR/UV Vision, Stealth (+2)
Programming Basic (recon) (INT 4)
Options Camouflage: Visual (advanced), Drone Interface, Encryption Module, Environment Processor,
PRIS Sensor, Recon Sensor (advanced), Self-Maintenance Enhancement (basic), Solar
Power Unit (basic), Stealth (improved), Tightbeam Communicator, Transceiver 5,000km
(enhanced), Vacuum Environment Protection, Wireless Data Link

devices can relay information across a solar system if
necessary and provide high-speed burst transmissions
of stored data to receivers within 5,000km or much
further to large communications arrays. The EyeSpy
is gyrostabilised to maintain focused on observation
targets but has no capacity to change orbit.

The satellite is delivered via a standard missile bus.
A single torpedo can deliver four EyeSpy units.
Its delivery mechanism performs an avoidance
manoeuvre to prevent the discarded missile stage
from being detected near the EyeSpy. The Basic
(recon) robot brain allows the EyeSpy to adapt to
whatever it detects, making its own determination of
the value of observing targets unless it has specific
instructions to the contrary. It can store a year’s worth
of detailed reconnaissance data and summarise
highlights for transmission or long-term retention.

## V EHICLE BRAINS

A vehicle brain is more than an autopilot. It is a
decision-making machine that has full control of
the vehicle and often other systems, including
communications, sensors and weapons. In many
instances the vehicle brain completely replaces a
biological crew, saving space and life support costs.
Vehicle brains that occupy robot housings of Size 4
or less require no Spaces on a vehicle, Size 5 and 6
require one Space, while Size 7 requires two Spaces
and Size 8, four Spaces, although vehicle brain robots
are rarely so large. Pricing does not include vehicle
brain interfaces (see page 101), which have costs
dependent on the size of the vehicle, nor are they
effective with just actuation systems installed as these
only provide drone-level control and would require
the robot to use Electronics (remote ops) to operate
any vehicle systems. Many vehicle brains have
flexible skill packages that do not specify vehicle or
weapon type however, once purchased and installed,
these brains are not flexible, requiring retraining and
possibly different autopilot or fire control components
to operate in a different vehicle type. Often brains are
installed in an immobile robot chassis deep within
the bowels of a vehicle and so interconnected that
replacement is difficult.

Combat Vehicle Brain, Basic
The basic Combat Vehicle Brain, or CVB, is the core
of the lowest Tech Level fully autonomous fighting
machine. With a Hunter/Killer brain, autopilot, fire
control system and navigation system built into its tiny
box, it is usable on anything from a fast-moving vehicle
to a fighter jet to a lumbering heavy tank. If the vehicle
has its own systems for recon and communications,
it can use these but is limited to its own autopilot and
fire control skills, which are the best available at TL8. If
installed in a robot, the basic CVB occupies two Slots
and includes the robot’s brain.

Robot Hits Locomotion Speed TL Cost
Basic Combat
Vehicle Brain

1 — 0m 8 Cr75000

Skills Navigation 1, Recon 0, Tactics (military) 2, Vehicle (specific) 1, Weapon (specific) 2
Attacks —
Manipulators —
Endurance 216 hours
Traits Armour (+2), Small (-4)
Programming Hunter/Killer (tactical) (INT 3)
Options Auditory Sensor, Autopilot (improved), Drone Interface, Fire Control System (improved),
Navigation System (basic), Transceiver 50km (improved), Voder Speaker, Wireless Data Link

**Combat Vehicle Brain, Improved**
By TL10 automation technology is improved enough
to provide a more capable CVB. The improved
version of this brain has the same small formfactor
as its predecessor, and uses an upgraded Hunter/
Killer brain, but the brain’s slight increase in general
intelligence is less important than improvements in
autopilot, fire control system and navigation. This box
of a robot chassis with links to make the vehicle an
integrated part of its ‘body’, requires no Spaces on a
vehicle but two Slots if installed in a robot as its brain
and control system.

Robot Hits Locomotion Speed TL Cost
Improved Combat
Vehicle Brain

1 — 0m 10 Cr87000

Skills Navigation 2, Recon 0, Tactics (military) 2, Vehicle (specific) 2, Weapon (specific) 3
Attacks —
Manipulators —
Endurance 216 hours
Traits Armour (+3), Small (-4),
Programming Hunter/Killer (tactical) (INT 4)
Options Auditory Sensor, Autopilot (enhanced), Drone Interface, Fire Control System
(enhanced), Navigation System (improved),Transceiver 500km (improved), Voder
Speaker, Wireless Data Link

Combat Vehicle Brain, Advanced
The TL12 version of the CVB is as advanced as possible
with a Hunter/Killer brain. Its improved electronics
make it more capable than most crewed vehicles,
especially with its advanced fire control system’s
targeting heuristics. Continued miniaturisation leaves the
advanced CVB with one spare Slot, which is ironically
sometimes occupied by an avatar controller. This odd
combination requires an Advanced brain, increasing
overall costs and losing the tactical insight of the Hunter/
Killer’s brain but allows the controller to continue
to benefit from hardwired autopilot, fire control and
navigation systems. As with less advanced CVBs, the
advanced version requires no vehicle Spaces. Even if
the spare Slot compartment is removed, the advanced
CVB still requires two Slots if installed in a robot.

Robot Hits Locomotion Speed TL Cost
Advanced Combat
Vehicle Brain

1 — 0m 12 Cr150000

Skills Navigation 3, Tactics (military) 2, Vehicle (specific) 3, Weapon (specific) 4
Attacks —
Manipulators —
Endurance 324 hours
Traits Armour (+4), Small (-4)
Programming Hunter/Killer (tactical) (INT 4)
Options Auditory Sensor, Autopilot (advanced), Drone Interface, Fire Control System (advanced),
Navigation System (enhanced), Spare Slot, Transceiver 5000km (enhanced), Voder
Speaker, Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Tour Guide 12 — 0m 12 Cr50000
Skills Carouse 1, Navigation 2, Profession (tour guide) 2, Steward 1, Vehicle (specific) 2
Attacks —
Manipulators —
Endurance 324 hours
Traits Armour (+4), Small (-1)
Programming Advanced (INT 9)
Options Autobar (improved), Autochef (improved), Autopilot (enhanced), Auditory Sensor Drone
Interface, External Power, Holographic Projector, Navigation System (improved), Video Screen
(advanced) Storage Compartment (1 Slot refrigerated), Transceiver 5,000km (enhanced),
Voder Speaker, Wireless Data Link

**Tour Guide**
The Tour Guide is a control panel replacement
for any vehicle, designed to transform it into an
automated sight-seeing platform. The robot fits into
the forward panel, removing all manual control and
replacing it with a screen and holographic projector,
which allows a running commentary with visual
effects as it takes its passengers on a journey to a
tourist attraction or landmark. A built-in autobar and
autochef allows it to prepare refreshments along
the route but it has limited storage capacity, relying

on cargo capacity or containers to carry additional
supplies. The Tour Guide is a sophisticated robot,
able to respond intelligently to queries from its
passengers and capable of tailoring a tour to their
interests while carrying pleasant conversation, which
after several hours may become bothersome.

The Tour Guide requires no Spaces if placed in a
vehicle but occupies 16 Slots in a robot.

## S HIP'S BRAINS

A ship’s brain gives a spacecraft the capability
to perform some functions autonomously and
can give the ship itself a personality. Whether
operating directly through interfaces to a
spacecraft’s control systems or through drones
or avatars, ship’s brains can supplement or
replace some crew functions. Ship’s brains
can even be installed in vehicles, performing
much the same functions as on a spacecraft.
The brains listed do not include the costs of
a direct spacecraft or vehicle interface, which
costs MCr1 per 100 tons or fraction there of, or
Cr5000 per Space.

Alpha
The Alpha brain has no capacity to control an
avatar and can operate at most four consoles
or drones at a time, with appropriate negative
DMs for simultaneous operations. Its own cost
is dwarfed by that of its interfaces on even
a small vessel and the Alpha is often used
as only a drone controller, operating through
repair drones with no direct control of the
spacecraft’s operation. With drones it is more
affordable than Auto-Repair or Virtual Crew
software. At TL11 the price of an Alpha drops
to Cr80000 and at TL12 it costs only Cr40000.

Robot Hits Locomotion Speed TL Cost
Alpha 1 None 0m 10 Cr130000
Skills Admin 0, Electronics (remote ops) 1, Engineer (j-drive) 1, Gunner (turret) 1, Mechanic 0, Pilot
(spacecraft) 1
Attacks —
Manipulators —
Endurance Unlimited ship’s power (216 hours)
Traits Armour (+3), Small (-4)
Programming Advanced (INT 6)
Options Auditory Sensor, Drone Interface, External Power, Robotic Drone Controller (enhanced),
Transceiver 5km (improved), Vacuum Environment Protection, Visual Spectrum Sensor, Voder
Speaker, Wireless Data Link

**Brian**
Ship’s brains have individualised names but by
tradition the default name for a ship’s brain is a pun.
Brian is the most common. An armoured box installed
behind a bridge console, a basic avatar controller
is standard equipment but no avatar robot or avatar
receiver is included.

When interfaced with a ship, Brian is capable of flying
the ship, operating bridge sensor and comm stations,
firing turrets and initiating standard engineering
operations. Using the drone controller multiplexer,
Brian can perform up to eight simultaneous tasks. Each
drone controlled counts as a task, as does each skill
function, but every additional simultaneous task beyond
the first decreases checks for every task by DM-1.

Robot Hits Locomotion Speed TL Cost
Brian 12 — 0m 12 MCr1
Skills Admin 1, Advocate 1, Astrogation 1, Electronics (all) 2, Engineer (jump) 2, Gunner
(turret) 1, Mechanic 2, Navigation 2, Pilot (spacecraft) 2, Tactics (naval) 1
Attacks —
Manipulators —
Endurance Unlimited ship’s power (324 hours)
Traits Armour (+19), Hardened, Small (-1)
Programming Very Advanced (INT 9)
Options Auditory Sensor, Avatar Controller (basic), Drone Interface, External Power, Radiation
Environment Protection (+600 rads), Robotic Drone Controller (advanced), Swarm
Controller (enhanced), Transceiver 5km (improved), Vacuum Environment Protection,
Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

Omega
The most advanced ship’s brain generally available
is the Omega model, equipped with an exceptionally
intelligent TL15 Self-Aware brain. Capable of
operating ship’s systems at a high level of skill and
proficient with communications, administrative and
legal matters in most documented languages and
governments, it allows proficient operation in all
aspects of interstellar travel. Able to control up to
four avatars, eight drones and an advanced swarm,
the Omega can run a small ship by itself. Limitations
on jump survivability for an entirely automated
ship usually prevents the Omega from operating a
crewless starship but it can run an entire ship with just
a moderately capable conscious sentient aboard to
look over the jump calculations and sit out the week-
long jump. The Omega’s major drawback – besides
cost – is its rather smug manner, a side effect of its
extraordinary intelligence and wide set of skills.

Robot Hits Locomotion Speed TL Cost
Omega 12 — 0m 15 MCr10
Skills Admin 3, Advocate 3, Astrogation 4, Broker 3, Carouse 3, Diplomat 3, Electronics (all) 4,
Engineer (all) 4, Gunner (turret) 4, Language (all) 3, Mechanic 3, Medic 3, Persuade 3, Pilot
(spacecraft) 4, Science (all) 3, Steward 3, Tactics (naval) 3
Attacks —
Manipulators —
Endurance Unlimited ship’s power (432 hours)
Traits Armour (+24), Hardened, Small (-1)
Programming Self-aware (INT 15)
Options Auditory Sensor, Avatar Controller (enhanced), Drone Interface, Encryption Module, External
Power, Radiation Environment Protection (+750 rads), Robotic Drone Controller (advanced),
Swarm Controller (advanced), Transceiver 500km (advanced), Vacuum Environment
Protection, Visual Spectrum Sensor, Voder Speaker, Wireless Data Link

## H IGH TECHNOLOGY

Robots beyond TL15 are not generally available for
sale within Charted Space. Prototypes of TL16 robots,
including advanced pseudobiologicals and self-aware
robots bordering on full consciousness exist, notably
produced by experimental facilities on Vincennes in
Deneb and R&D facilities owned by Makhidkarun and
SURD in the Core. Other races have developed more
sophisticated robots, with rumours of high-tech Hiver
robots and declassified documents describing the
pseudobiological natives of Sabmiqys.

Sabmiqys
The interdicted world of Sabmiqys (Antares sector) is the
home of the xenophobic Sabmiqys or Gya Ks, a race of
android robots apparently descended from the world’s
original inhabitants, killed by a plague in approximately
-8000. The robotic race claims to embody the
consciousness of members of the dead biological race.

The androids are spongy grey bipedals, 2.5 metres tall,
thin, massing about 100 kilograms and equipped with four
tentacular ‘arms’ each ending in four tentacular fingers.
A mouth filled with about 100 sharp teeth implies a
carnivorous or omnivorous origin but details of the original
and current society are limited to hypotheses based on
limited interaction. The Sabmiqys system is interdicted
and the ‘natives’ seem to have no desire to leave their
world or interact with outsiders.

Robot Hits Locomotion Speed TL Cost
Sabmiqys 20 Walker 6m 17 MCr70
Skills Unknown – likely limited to 60 Bandwidth backed by INT 15
Attacks Unknown
Manipulators 4x (STR 9 DEX 10)
Endurance 288 hours (?)
Traits Armour (+4), ATV, Heightened Senses, IR/UV Vision
Programming Conscious (INT 15)
Options Android (superior), Auditory Sensor (broad spectrum), Olfactory Sensor (advanced), PRIS
Sensor, Self-Maintenance Enhancement (advanced), Transceiver 5,000km (advanced), Voder
Speaker (broad spectrum)

**Ultima**
An artefact of perhaps Ancients lineage,
Ultima is a being once human, now with
consciousness transferred into an android
body that can pass as human, with the
ability to change basic features and become
completely invisible if desired. Immortal, but
not unkillable, Ultima’s age is uncertain and
their intellect unmatched but they must rely
more on stealth and guile than armour and
healing to survive uncounted millennia.

Robot Hits Locomotion Speed TL Cost
Ultima 20 Walker 9m 18 MCr73
Skills Athletics (dexterity) 3, Athletics (strength) 3, Stealth 4, +74 available Bandwidth
Attacks —
Manipulators 2x (STR 15 DEX 15)
Endurance 259 hours
Traits Armour (+10), ATV, Heightened Senses, Invisible, IR/UV Vision
Programming Conscious (INT 18)
Options Active Camouflage, Android (superior), Auditory Sensor (broad spectrum), Camouflage: Audible
(advanced), Camouflage: Olfactory (advanced), Camouflage: Visual (superior), Gecko Grippers,
PRIS Sensor, Radiation Environment Protection (+900 rads), Self-Maintenance Enhancement
(advanced), Transceiver 5,000km (advanced), Vacuum Environment Protection, Voder Speaker
(broad spectrum), Wireless Data Link

Robot Hits Locomotion Speed TL Cost
Ultra 32 Grav, Walker 9m 18 MCr33
Skills Athletics (dexterity) 4, Athletics (strength) 4, Stealth 4 + 74 available Bandwidth
Attacks —
Manipulators 2x (STR 18 DEX 18)
Endurance 86 (22) hours
Traits Armour (+25), ATV, Flyer (high), Heightened Senses, Invisible, IR/UV Vision, Large (+1)
Programming Conscious (INT 18)
Options Active Camouflage, Auditory Sensor (broad spectrum), Camouflage: Audible (advanced),
Camouflage: Olfactory (advanced), Camouflage: Visual (superior), Fabrication Chamber (4kg
advanced), Gecko Grippers, PRIS Sensor, Repairing Chassis, Self-Maintenance Enhancement
(advanced), Self- Radiation Environment Protection (+900 rads), Solar Coating (advanced),
Transceiver 5,000km (advanced), Vacuum Environment Protection, Voder Speaker (broad
spectrum), Wireless Data Link

**Ultra**
Ultra is another ‘immortal’ artefact of a
lost time. Foregoing the ability to pass
as human, Ultra is a large robot with
very humanoid features on an obviously
artificial body that stands 2.3 metres tall.
In addition to walking, Ultra can fly at high
speed, become invisible and recharge by
turning its skin into a highly efficient solar
coating. Embedded within its right arm is an
advanced fabrication chamber that allows
it to create nearly any small object out of
raw materials, up to and including living
creatures. Endurance limits assume Ultra
is flying, but are tripled if Ultra limits itself to
walking, and recharging can occur at least
at a trickle whenever Ultra stands in the sun
and allows its body to absorb light.

## I NDEX

Active Camouflage ..................................................... 41
Adding Zero Slot Options .......................................... 114
Additional Manipulators .............................................. 25
Advanced Capabilities ................................................ 66
Advisor Robot ........................................................... 201
AG300 Agricultural Worker ....................................... 175
Agility Enhancement ................................................... 22
Agricultural Equipment .............................................. 48
Alpha ........................................................................ 251
Altered Base Manipulators ......................................... 25
Altered Characteristics ............................................... 26
Android Body Cyborg, Advanced.............................. 236
Android, Enhanced ................................................... 224
Android Properties ...................................................... 86
Android Robot Legal Restrictions ............................... 87
Android, Superior...................................................... 225
Angel of Mercy.......................................................... 145
Arerl Slave Machine ................................................. 189
Astro-Mech Droid...................................................... 146
Athletics ...................................................................... 75
Atmospheric Sensor ................................................... 38
Auditory Sensor .......................................................... 38
Autobar ....................................................................... 49
Autochef ..................................................................... 49
Autodoc, Advanced................................................... 147
Autodoc, Basic.......................................................... 146
Autodoc, Improved ................................................... 147
Autopilot...................................................................... 49
Ava Ship’s Avatar...................................................... 240
Avatar Control Interface .............................................. 95
Avatar Controller ......................................................... 95
Avatar Control System ................................................ 96
Avatar Receiver .......................................................... 95
Avatars, Brains and ................................................. 104
Backup and Restore .................................................. 112
BandBot .................................................................... 148
Base INT and Skills .................................................... 66
Basic (labourer) .......................................................... 70
Basic (locomotion) ...................................................... 70
Basic (none) ............................................................... 71

Basic (recon) .............................................................. 71
Basic (security) ........................................................... 71
Basic (servant)............................................................ 72
Basic (service) ............................................................ 72
Basic (target) .............................................................. 72
Basic Training ............................................................ 117
Battle Mule................................................................ 126
BDVSR Bartender Robot .......................................... 148
BeautyBot ................................................................. 149
Biological-Initiated ..................................................... 96
Biological Robot Legal Restrictions ............................ 88
Biological Robot Properties ........................................ 88
Biological Robots ........................................................ 88
Bioreaction Chamber .................................................. 50
Bioscanner Sensor ..................................................... 57
Blacksand Widow ..................................................... 243
Body Double ............................................................. 226
Brain Bandwidth Upgrade........................................... 67
Brain Hardening.......................................................... 67
Brain Intellect Upgrade ............................................... 67
Brain Transplantation.................................................. 97
Breaker-of-Lines ....................................................... 196
Brian ......................................................................... 252
Brokerbot .................................................................. 150
Bulk Delivery Servitor (BDS) .................................... 176
Camouflage: Audible Concealment ............................ 32
Camouflage: Olfactory Concealment.......................... 32
Camouflage: Visual Concealment .............................. 31
Ceiling Cat ................................................................ 227
Centurion .................................................................. 127
Characteristics ............................................................ 96
Clearance 600 Crowd Dispersal Unit ....................... 128
Clone Creator ........................................................... 122
Clones as Travellers ................................................. 100
Clone Technology ....................................................... 98
Cloning Creche ......................................................... 151
Cloning Vat ............................................................... 152
Combat Drone .......................................................... 129
Combat Vehicle Brain, Advanced ............................. 249
Combat Vehicle Brain, Basic .................................... 248

Combat Vehicle Brain, Improved .............................. 249

Companion ............................................................... 228

Confederation Army Ammobot.................................. 198

Confederation Army Mortarbot ................................. 199

Conscious ................................................................... 66

Construction Equipment ............................................ 50

Construction Nano Queen ........................................ 222

Construction Nanorobots ............................................ 84

Corrosive Environment Protection .............................. 41

Cost Modification ........................................................ 76

Counsellor ................................................................ 229

Courier, Advanced .................................................... 178

Courier, Basic ........................................................... 177

Courier Drone ........................................................... 206

Creche Training .......................................................... 99

Creeper Assassin ..................................................... 129

Crew Droid................................................................ 153

Cutting Torch .............................................................. 58

Cybernetic Arms ......................................................... 89

Cybernetic Interfaces.................................................. 89

Cybernetic Legs.......................................................... 89

Cybernetic Limb Considerations................................. 90

Cybernetic Limbs Interfaces ....................................... 89

Cybernetic Organs...................................................... 91

Cybernetic Senses ..................................................... 90

Cybernetic Sensor Implants ....................................... 90

Cybernetic Sensory Interfaces ................................... 90

Danger Droid ............................................................ 154

Deep Diver Droid ...................................................... 155

Densitometer Sensor .................................................. 57

DesiGnator ............................................................... 130

DEX ............................................................................ 75

Distant Lance............................................................ 195

Domestic Cleaning Equipment ................................... 43

Domestic Servant ..................................................... 179

Drone Control ........................................................... 123

Drone Control Console .............................................. 119

Drone Control Helmet ............................................... 120

Drone Control Interface .............................................. 79

Drone Interface ........................................................... 34

Drone Interface ........................................................... 79

Dupal Companion Robot .......................................... 231

eGore........................................................................ 237

Electromagnetic Stunners ........................................ 106

Electronics (sensors) .................................................. 75

Electronics Toolkit ....................................................... 58

Elvis Performance Double ........................................ 230
Emergency Medical Response Robot ...................... 156
Encryption Module ...................................................... 35
Engineering (j-drive) ................................................... 75
Engineering (life support) ........................................... 75
Engineering (m-drive) ................................................. 75
Engineer (power) ........................................................ 75
Entourage Biobot ...................................................... 233
Environment Processor .............................................. 38
Exploration Rover ..................................................... 157
Explosives .................................................................. 75
Exterminator ............................................................. 214
External Power ........................................................... 55
EyeSpy Satellite ....................................................... 247
Fab Creator .............................................................. 123
Fabrication Chamber .................................................. 51
Fabrication, Nanorobots and Swarms ...................... 105
Fighting Strongpoint ................................................. 130
Fire Control System .................................................... 60
Fire Extinguisher......................................................... 59
Floating Eye.............................................................. 237
Floating Strongpoint ................................................. 131
Flying Gun (large) ..................................................... 132
Flying Gun (medium) ................................................ 132
Flying Gun (small) .................................................... 131
Flying Sword ............................................................. 133
Forensic Scout.......................................................... 158
Forensic Supervisor Droid ........................................ 158
Forensic Toolkit ........................................................... 59
Forklift ......................................................................... 52
Friend of the Lowly ................................................... 194
Full-body Cybernetics ................................................. 92
Full Brain Upgrade..................................................... 113
Gardener Servant ..................................................... 191
Gecko Grippers .......................................................... 36
Geiger Counter ........................................................... 39
Grav Mule ................................................................ 133
Grav Pioneer ............................................................ 134
Grav Walker ................................................................ 78
Growth Rate and Aging .............................................. 96
Guardian-of-Glory ..................................................... 196
Gun Combat ............................................................... 75
Gun Combat 2 ............................................................ 75
Hazardous Environment Scout ................................. 192
Heavy Warbot ........................................................... 205
High Fidelity Sound System ....................................... 44

Hikare’ Technician .................................................... 190

Hive Queen............................................................... 160

Holographic Projector ................................................. 52

Hostile Environment Protection .................................. 32

Hunter Bug ............................................................... 215

Hunter/Killer ................................................................ 65

Hunter/Killer (standard) .............................................. 72

Hunter/Killer (tactical) ................................................. 73

Impersonator ............................................................ 234

Induction Plate .......................................................... 120

Industrial Cleaning Equipment.................................... 43

Inherent Skill DMs ...................................................... 73

Inhibitor ................................................................ 120

Injector Needle ........................................................... 36

Insidious Environment Protection .............................. 41

Keshean Gaa – Type 21 .......................................... 135

Kimim AAR – Type 14 .............................................. 162

Lab Control Robot, Advanced................................... 180

Lab Control Robot, Basic.......................................... 179

Labour Droid ............................................................. 180

Laser Designator ........................................................ 37

Light Intensifier Sensor ............................................... 39

Light Warbot ............................................................. 204

Locomotion ................................................................. 80

Locomotion Special Characteristics ........................... 17

Locomotion Traits ....................................................... 17

Long Duration Security Robot .................................. 136

Low Berth, Advanced................................................ 181

Low Berth, Grav........................................................ 182

Macro Hero ............................................................... 241

Magnetic Grippers ...................................................... 37

Maintenance Bot....................................................... 204

Major Manufacturers..................................................... 4

Manipulator Athletics Skill Requirements ................... 26

Manipulators ............................................................... 80

Marine Boarding Droid.............................................. 193

Meatbox Pilot ............................................................ 241

Mechanic .................................................................... 75

Mechanic 3 ................................................................. 75

Mechanical Toolkit ...................................................... 59

Medic .......................................................................... 75

Medic 2 ....................................................................... 75

Medical Chamber ....................................................... 46

Medical Chamber Options .......................................... 47

Medical Nanorobots.................................................... 83

Medikit ........................................................................ 48

Medium Warbot ........................................................ 205

Medivac Robot.......................................................... 163
Metamorphic Robots ................................................ 104
Microbot Brain ............................................................ 81
Microbot Design Worksheet ...................................... 82
Microbot-Only Options ................................................ 80
Micro Hero ................................................................ 242
Mining Bot................................................................. 183
Mining Drone ............................................................ 207
Mining Equipment ...................................................... 52
Miscellaneous Cybernetics ......................................... 92
Mishaps ..................................................................... 117
Missile Chassis ......................................................... 246
Missile Chassis Robots ............................................ 100
Missile Robots .......................................................... 101
Mustering Out Benefits .............................................. 117
Naasirka Model 899 ................................................. 137
Nano Hero ................................................................ 216
Nanorobot Countermeasures ..................................... 85
Nanorobot Development............................................. 85
Navigation System...................................................... 53
Neumann Archon-Class Nanotech ........................... 223
Neumann Knight-Class Nanotech ............................ 223
Neural Activity Sensor ................................................ 58
Neural Implants .......................................................... 92
No Internal Power ....................................................... 56
Non-Interface Brain Configurations .......................... 102
Nursebot ................................................................... 164
Offworld Construction Drone (OCD) ......................... 208
Offworld Construction Master Robot (OCMR) .......... 165
Olfactory Sensor ......................................................... 39
Omega ...................................................................... 252
Opener-of-the-Way ................................................... 195
Operational Considerations ...................................... 103
Ordnance Handling Robot ........................................ 135
Other Cybernetic Options ........................................... 93
Other Cybernetic Options ........................................... 93
Parasitic Link .............................................................. 37
Peacekeeper Riot Control Robot .............................. 138
Peeping Spybot ........................................................ 217
Planetology Sensor Suite ........................................... 58
PopcornBot ............................................................... 219
Popcorn Drone ......................................................... 218
Primitive ...................................................................... 65
Primitive (alert) ........................................................... 69
Primitive (clean) .......................................................... 69
Primitive (evade)......................................................... 69
Primitive (homing)....................................................... 69

PRIS Sensor ............................................................... 39

Probe Drone ............................................................. 209

Probe Drone, Advanced ........................................... 209

Protocol Droid ........................................................... 166

Pulse Carbine ........................................................... 107

Purchasing Clones ..................................................... 98

Quick Arm ................................................................. 239

Quick Charger ............................................................ 57

Radiation Damage .................................................... 106

Radiation Environment Protection .............................. 42

Recon Sensor ............................................................. 58

Reflec Armour ............................................................. 32

Remote-Initiated Biological ........................................ 95

Repair Drone, Extra-Large ....................................... 213

Repair Drone, Extra-Small......................................... 211

Repair Drone, Large ................................................. 212

Repair Drone, Medium ............................................. 210

Repair Drone, Small .................................................. 211

Replacement Parts ..................................................... 97

RetroTech ................................................................... 67

Robodiver ................................................................. 184

Robot Brain Implants .................................................. 92

Robot Design Worksheet (Physical) ............................. 9

Robot Design Worksheet (Short Form) ....................... 11

Robotic Drone Controller ............................................ 44

Robotics Lab Fabrication Chamber: ........................ 121

Robotics Laboratory ................................................. 121

Robot Record Sheet ................................................... 76

Robot Size .................................................................. 13

ROvER ..................................................................... 200

RPRU ....................................................................... 184

RTG Long Duration .................................................... 56

RTG Short Duration .................................................... 56

Running Legs ........................................................... 239

Sabmiqys .................................................................. 253

Sanitation Droid ........................................................ 166

Satellite Uplink ............................................................ 45

Scientific Toolkit .......................................................... 59

Scout Mite................................................................. 220

Searcher Microbot .................................................... 220

Secure Courtesy Assist Unit ..................................... 162

Security Drone .......................................................... 139

Security Support Robot ............................................ 137

Self-Aware .................................................................. 65

Self-Destruct System .................................................. 53

Self-Maintenance Enhancement ................................ 37

Self-Maintenance Enhancement ................................ 54

Self-Repairing Chassis ............................................... 42
Shadow Security Robot ............................................ 139
Ship’s Avatars ........................................................... 103
Ship’s Brain Interface ............................................... 102
Ship’s Brain Interface ............................................... 102
Ship’s Mechanic – Rusty .......................................... 167
Sindalian Deathbot ................................................... 140
Sindalian Enforcement Robot ................................... 141
Size............................................................................. 80
Size Limits .................................................................. 66
Sizes ......................................................................... 100
Skills .......................................................................... 117
Skitter ....................................................................... 186
SkySpotter ................................................................ 213
Slayer-of-Shields ...................................................... 197
Smart Probe Bot ....................................................... 186
Solar Coating .............................................................. 33
Solar Power Unit......................................................... 56
(spare bandwidth) ....................................................... 75
Spare Slots ................................................................ 114
(spare zero bandwidth = 1) ......................................... 75
Special Delivery Servitor (SDS)................................ 185
Speciality Firms ............................................................ 4
Spider Bomb ............................................................. 141
Standard Engineer Droid (SED) ............................... 167
Starship Engineering Toolkit ....................................... 60
Starship Repair Boss ................................................ 168
StarTek ..................................................................... 169
Stealth ........................................................................ 54
Stewaid Shipboard Robot ......................................... 170
Steward Droid ........................................................... 171
Stinger ........................................................................ 38
Storage Compartment ................................................ 55
STR ............................................................................ 75
Strend Les Mecanismes Nanotech........................... 223
Stun Rifle .................................................................. 107
Stun Shotgun ............................................................ 107
Stylist Toolkit ............................................................... 60
Submersible Environment Protection ......................... 42
Surgeon Bot.............................................................. 172
Surrogate Droid, Basic ............................................. 173
Surrogate Droid, Improved ...................................... 231
Sustained Damage .................................................... 110
Swarm Control ............................................................ 83
Swarm Control .......................................................... 123
Swarm Controller ........................................................ 45
Swarm Controller Console........................................ 122

Synthetic Horse ........................................................ 232

Tactical Speed Enhancement ..................................... 22

Tactical Speed Reduction ........................................... 22

Tandi Clone............................................................... 244

Taskbot ..................................................................... 202

Template Characteristics ............................................ 98

Terms ......................................................................... 117

Thermal Sensor .......................................................... 39

Tightbeam Communicator .......................................... 46

Toolsack Workbot ..................................................... 187

Torpedo Chassis ....................................................... 246

Tour Guide ................................................................ 250

Training of Clones ...................................................... 98

Transceiver ................................................................. 35

Transceivers ............................................................... 46

Trapper Hunter Droid (THD) ..................................... 142

Trashbot ................................................................... 203

Type C Cargo Loader ............................................... 188

Ultima ....................................................................... 254

Ultra .......................................................................... 255

Underworker ............................................................. 245

Upgraded Brain Sophistication .................................. 113

Upgraded Components ............................................. 114

Upgraded Options ..................................................... 113

Urban Pacification Police Robot ............................... 143

Utility Droid ............................................................... 174

Vacuum Environment Protection ................................ 34

Vehicle Brain Interface.............................................. 101

Vehicle Brain Robots ................................................ 102

Vehicle Drones ........................................................... 79

Vehicle Manipulators ................................................ 102

Video Projector ........................................................... 55

Video Screen .............................................................. 35

Vigilance CCR .......................................................... 174

Visual Spectrum Sensor ............................................. 39

Voder Speaker ............................................................ 36

Walker ........................................................................ 77

Walker Legs as Manipulators ..................................... 26

Walking Strongpoint ................................................. 144

Warhead Robots ....................................................... 100

Weapon Mount ........................................................... 61

Weapon Mount Autoloader ......................................... 61

Wireless Data Link...................................................... 36

Zero-Slot Options ....................................................... 80

Zombie...................................................................... 235
