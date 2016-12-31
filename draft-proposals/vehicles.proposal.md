Proposal to Add at least **6** Missing Symbols for **Land-Bound Vehicle Classes in International Driving Permits** to the Unicode Standard
=======================================================================================

-   **Author:** Christoph Päper

-   **Mail:** christoph.paeper@crissov.de

-   **Submitted:** 2016-12-31

Introduction
------------

I hereby request the addition of 
two **Motorcycle**, 
a **Trailer**, 
a **Light Automobile**,
a **Construction Vehicle** and 
a **Snowmobile emoji** 
to a future version of the Unicode Standard.
Rationals, glyph examples, character properties as well as discussion of
inclusion and exclusion factors are included on the following pages. As per
[emoji submission guidelines](http://www.unicode.org/emoji/selection.html#submission) 
this document does not include the character proposal form.

1. Generic *Motorcycle* `A` and *Light Motorcycle* or *Motorbike* (without rider)

2. Generic *Trailer* `E`

3. *Light Automobile* `B1`, or *Quadricycle*/*Quad* (incl. *Wheelchair* ♿️) and *Tricycle*/*Trike*

4. *Excavator* or *Bulldozer* or *Forklift* `G`

5. *Snowmobile* `S`

6. *Steering Wheel* or *Starwheel*, or generic *Wheel* or *Tyre*/*Tire*

Unicode already includes a number of vehicle and transportation emojis. 
I am proposing one way to assess their completeness, which should result in a limited number of possible future extensions. This is vehicle classes in driving permits. I will limit this approach to motorized street-bound vehicles since these are most commonly used.

<!--
* Font Awesome requests: truck/pickup
* ASCII art
-->

### Vehicle Classes of the International Driving Permit 🌐

First established in 19**xy, nnn** countries recognize and issue licenses complying to the International Driving Permit (IDP) as of 2016. 
Many national and local laws defining driver’s licenses are designed to be compatible with the IDP.

The IDP is build upon 4 major classes (`A`, `B`, `C`, `D`), 3 restricting minor classes (`A1`, `C1`, `D1`) and 1 extending minor class (`E`).

As of version 9.0 of the Unicode Standard (UTS9) and version 4.0 of Unicode Technical Report #51 (UTR51), 
there are at least 5 characters with default emoji represenation defined coherently which can reasonably designate all two-track vehicle classes. 
U+1F3CD Racing Motorcycle is interpreted as depicting more of an activity than a vehicle by some vendors, who therefore drew it with a rider on top, cf. U+1F40E Horse 🐎 vs. U+1F3C7 Horse Racing 🏇.

| Class | Type | Emoji | Description | Trailer Class |
|-------|------|-------|-------------|--------------|
| A  | Motorcycle       | 🏍 Racing Motorcycle |   > 50 cm³ ∨ 45 km/h | — |
| A1 | Light Motorcycle | **N/A**              | A ≤ 125 cm³ ∧ 11 kW | — |
| B  | Automobile / Car | 🚗 Automobile        |   ≤ 3.5 t | BE |
| C  | Lorry            | 🚛 Articulated Lorry |   > 3.5 t | CE |
| C1 | Truck            | 🚚 Delivery Truck    | C ≤ 7.5 t | C1E |
| D  | Bus              | 🚌 Bus               |   > 1+8 💺 | DE |
| D1 | Minibus          | 🚐 Minibus           | D ≤ 1+16 💺 | D1E |
| E  | Trailer          | **N/A**              |   > 0.75 t | — |

There is no emoji of a light motorcycle to represent class `A1`, because 🛵 U+1F6F5 Motor Scooter is *too* light as shall be seen below.
No Unicode emoji represents a trailer either.

**source**

### Vehicle Classes of the European Driving Permit 🇪🇺

The European Drivin Permit (EDP) is a proper superset of the IDP in that it adds some vehicle classes that apply to all member countries: `A2`, `AM`, `B1` as of 2016. 

| Class | Type | Emoji | Description | Trailer Class |
|-------|------|-------|-------------|--------------|
| AM | Moped            | 🛵 Motor Scooter     | ≤ 50 cm³ ∧ ≤ 45 km/h | — |
| A  | Motorcycle       | 🏍 Racing Motorcycle |   > 50 cm³ ∨ 45 km/h | — |
| A1 | Medium Motorcycle| **N/A**              | A ≤ 125 cm³ ∧ 11 kW | — |
| A2 | Light Motorcycle | **N/A**              | A ≤ 35 kW ∧ ≤ 0.2 kW/kg | — |
| B  | Automobile / Car | 🚗 Automobile        |   ≤ 3.5 t | BE |
| B1 | Quad & Trike     | **N/A**              | > 50 cm³ ∨ > 4 kW,<br> B ≤ 15 kW ∧ ≤ 0.45 t | — |
| C  | Lorry            | 🚛 Articulated Lorry |   > 3.5 t | CE |
| C1 | Truck            | 🚚 Delivery Truck    | C ≤ 7.5 t | C1E |
| D  | Bus              | 🚌 Bus               |   > 1+8 💺 | DE |
| D1 | Minibus          | 🚐 Minibus           | D ≤ 1+16 💺 | D1E |
| E  | Trailer          | **N/A**              |   > 0.75 t | — |

U+1F6F5 Motor Scooter 🛵, introduced with UTC9 in mid-2016, applies to one of the extra classes, `AM`, the others do not have appropiate emoji representations  yet – also none already proposed or accepted for future versions of the standard. 
Emoji representation of the class `A2` requires a motorcycle ranging between a moped or scooter and the light one missing for IDP class `A1`. 
There are several common types of lighter automobiles that class `B1` applies to, e.g. ones without a roofed passenger cabin with either four or three wheels or a single-track motorcycle with cabin and safety belt.

Some member countries of the EDP have introduced or retained additional *national classes*. 
Most of these do (usually) not partake in normal street traffic.

| Class | Type | Emoji | Description | Trailer Class |
|-------|------|-------|-------------|--------------|
| F     | (Heavy) Tractor | 🚜 Tractor**?** | Tractor with trailers | — |
| G     | Work / Construction | 🏗 Construction Site**?**| Excavator and other work machinery | — |
| H     | Tram | 🚋 Tram | Cablecar, Streetcar | — |
| L     | (Light) Tractor / Agriculture | 🚜 Tractor**?** | Tractor with machinery, Autonomous harvesters | (T) |
| M     | Moped | 🛵 Motor Scooter | → `AM` or `A2` | — |
| S     | Snowmobile | **N/A** |  | — |
| T     |  |  | → `F` | — |
| TRAM  |  |  | → `H` | — |
| TROL  | Trolley Bus | 🚎 Trolley Bus |  | — |
| W     | Work |  | → `F`/`G` | — |

Interestingly, several of these specialized vehicle classes already have emoji representations, although it is unclear whether 🚜 Tractor should represent the bigger, stronger and faster kind which is often used with heavy machinery (`F`) or, much like a lorry, to pull two trailers at once (“`FE`”), or a smaller, weaker, slower kind (`L`, “`F1`”).

<!--
* Emergency vehicle 🚓🚑🚒
* RV 🚙
* Taxi 🚕
* Bicycle 🚲🚴🚵

special purpose vehicle:
towing truck, …
-->
**source**

### Wheels

Glyphs and Design
-----------------

Trailers 

- ![Small, flat trailer](.png)
- ![Large, high trailer](.png)
- ![Single-axis trailer](.png)
- ![Double-axis trailer](.png)
- ![Two-axes trailer](.png)
- ![Horse trailer](.png)
- ![Caravan trailer](.png)
- ![Boat trailer](.png)
- ![Bulk container trailer](.png)
- ![Fluid container trailer](.png)

Motorbikes (without rider)

- ![Motorcycle or Motorbike](.png)
- ![Heavy Motorcycle](.png)
- ![Medium Motorcycle](.png)
- ![Light Motorcycle](.png)
- ![Electro bike](.png)
- ![Pedelec](.png)

Light automobiles

- [![Quadricycle “Quad” by Andrejs Kirma (CC BY 3.0 US)](.png)](https://thenounproject.com/andrejs/collection/vehicle/?i=601272)
- ![Tricycle “Trike”](.png)

Work vehicles

- ![Excavator](.png)
- ![Bulldozer](.png)
- ![Forklift](.png)

Special-purpose or special-terrain vehicles

- ![Snowmobile](.png)

### Trailer combinations

Although many vehicles can be used to pull a trailer and the `E` classes share a common, generic definition of one, actual non-selfdriving vehicles may look very different. Vendors may therefore choose to display a more appropriate Trailer glyph depending on the preceding character. I present here an *informative* list of suggestions. It is expected that these also be supported with ZWJ in between and that popular sequences may be documented by Unicode in the future.

* 🚗 Automobile – may be same height (≥ 750 kg, possibly 2 axes) 
           or flat (< 750 kg, 1 axis)
* 🚙 Caravan
  + 🐎/🐴 Horse trailer
  + 🚤 Boat trailer
  + ⛺️/🏕 Camper
  + 🏠 Motor Home
* 🚌 – may be larger than for Automobile, 1 or 2 axes
* 🚐 – may be larger than for Automobile, 1 axis
* 🚚 – matching style, 2 axes
* 🚛 – may already include a (single) trailer (possibly carrying a container), because almost useless without, except when it can carry a container itself
   + 🛢/⛽️
   + 🚗 
   + …
* 🚜 Crops Car (2 axes)
* 🏍 Sidecar? / Tuktuk?
* 🚲 Baby Carrier or Transport Trailer (1 axis)
* 🐎 Carriage (2 axes) – transport
* 🏇 Sulky (1 axis) – sport
* 🐕 Wheeled Dog Sledge
    (could use U+1F6F7 Sled for traditional winter version)
* 🐃🐂🐄 Carriage (1 axis)
* 🐪🐫 ? – camels are mostly used for carrying, not pulling
* 🐘 ? – elephants are mostly used for carrying sedan chairs, not pulling carts
* 🚶 Wheelbarrow / Handcart
* 🏃 Rickshaw

Some additional ones are also possible, but do not need special handling except for design considerations:

* 🚕 – identical to Automobile, maybe matching color
* 🚓 – identical to Automobile, maybe matching color
* 🚑 – identical to Automobile, maybe matching color
* 🚒 – identical to Automobile, maybe matching color
* 🚎 – similar to Bus or Minibus, overhead cable should extend
* 🏎 – quite unusual, but should match direction of other vehicles, Tractor Pull

All existing front-facing (“`Oncoming`”) vehicle emojis also exist as (default) side-views and should probably not be expected to be used with a Trailer emoji.

* 🚘
* 🚍
* 🚖
* 🚔
* 🐴

### Motorcycle

All *Motorcycle* vehicle emojis should have a design note to discourage showing a rider. A person should only be visible in something like *Motorcycling*, i.e. an activity not a vehicle.❌ 
The exsiting character Racing Motorcycle should be annotated accordingly.

Character Properties
--------------------

The preferred names of the characters are “[______]”. 
They should be added to the Transport and Map Symbols block near other vehicle emoji. 
Properties of the vehicle emojis should be identical to those of other emoji.

-   General Category: Other Symbol (`So`)

-   Canonical Combining Class: `0`

-   Bidirectional Class: Other Neutral (`ON`)

-   Bidi Mirrored: No

No case-mapping is required. 
The characters do not decompose in any way. 
They are not whitespace nor control characters. 
They have no numeric value. 
They do not make use of emoji modifiers. 
They all have has emoji presentation by default, but should be available as monochrome text-style as well. 
In collation order they should be sorted near other motor vehicle emojis. 
They should definitely be part of the vehicle category.

Factors for Inclusion
---------------------

### A. Compatibility

There are no known legacy character sets containing any of the proposed characters. 
Unicode has one code point assigned to a vehicle symbol that is not marked as an emoji (yet): ⛟ U+26DF Black Truck. It does not seem to differ clearly from Delivery Truck and Articulated Lorry.
Cars are also featured on some other symbol characters (traffic signs):

- ⛍ U+26CD Disabled Car
- ⛐ U+26D0 Car Sliding

All vehicle emojis capable should face in the same direction (i.e. left in LTR text) to enable good visual fallback of sequences without ligation. Not all existing fonts comply to that.

### B. Expected Usage Level

Rather low. Although most people use at least one kind of vehicle every day, most vehicle emojis are among the lesser used, at least [on Twitter](http://emojitracker.com).

![Screenshot of emojitracker.com from 17 December 2016, with vehicle and related emojis highlighted]()

I have included several charts supplied by Google Trends showing the frequency of searches for “[______]” in comparison to other emoji.

Google search for the term “[______]” returns [______] results, which is more than for [______].

### C. Image distinctiveness

Yes … it’s good enough for street signs

### D. Completeness

Yes, the proposed emojis would cover all automobile classes currently distinguished in license and registration laws of most countries. 
This proposal does not cover cases of distinction “under the hood”, 
which are mostly relevant for taxation and insurance and not clearly visible from the outside.

### E. Frequently Requested

Not really.
There are lots of vehicle emojis already and new ones are requested much less than emoticons, hand signs, flags, animals or food. 
Completeness is the major argument to legitimate this proposal.

A *pickup truck* emoji is frequently requested from some areas, but is not included in this proposal because it usually does not require a separate driving permit.

Factors for Exclusion
---------------------

### F. Overly Specific

No. 
The selected decisive criterion for this proposal is legal distinction. 
If lawmakers around the globe see a need to require different licenses for different vehicle categories and even agree on many of them internationally, 
it seems very likely that users will frequently need the same kind of differentiation.

The *Trailer* emoji is intended to be generic and does not distinguish e.g. Horsebox and Caravan. 
This should be done with emoji sequences. 
Popular ones could later be standardized as ZWJ ligatures.

The different two-wheel single-track vehicles may seem like being overly specific, **but …**

### G. Open-ended

Driving Permit classes *may* be extended in the future, 
but that’s not expected to result in more than a handful of characters in the predictable future, 
e.g. Self-Driving Car or Flying Car.
This proposal specifically does not request emojis for different types (or even brands) of cars that commonly require the same license, 
e.g. Electric Car, Sedan, Convertible, Minivan and Pickup Truck. 
If someone wanted to propose something like that, they would perhaps base it upon the coding standard used by car rental companies world-wide. 

Drivers of military vehicles, such as a Tank, may also require a special licenses and extra training, but such classes are not covered by this proposal, because respective international documentation (e.g. by NATO or UN) was not available to the author.

This proposal explicitly does not deal with naval (e.g. Jetski), aerial (e.g. Hot-Air Balloon), rail-based (e.g. Mining Tub, Hyperloop) and non-motorized (e.g. Skateboard, Rollerskates, Stroller, Monocycle) vehicles, many of which have their own sets of (international) license requirements and existing emojis, or may be proposed separately . 

It also does not cover <!-- special-purpose, professional vehicles, which usually require special training and are mostly operated outside regular traffic, 
e.g. Forklift, Excavator, Bulldozer, Harvesters and Garbage Truck,
as well as --> single-vendor product categories,
e.g. Segway.

### H. Already Representable

U+1F683 Railway Car 🚃 could be reused as a *Trailer*, but looks and feels strange in combination with street-bound vehicles (🛣 vs. 🛤). 
However, similar considerations apply as to the combination with other emojis, i.e. locomotives of all kinds:

* 🚂🚃 – the Railway Car works well enough with the Steam Locomotive <!--– Tender?-->
* 🚋🚃, 🚞🚃 – it kinda works with the Tram Car and Mountain Railway, except for the cable and mountain, which may be shown respectively
* 🚅🚃, 🚄🚃, 🚈🚃 – it doesn’t work well with any of the other left-facing trains, but should probably adapt its design accordingly
* 🚝🚃, 🚟🚃 – it’s worse with special types of rails
* 🚆🚃, 🚇🚃, 🚊🚃 – it doesn’t work at all with front-facing Train, Metro and Tram, but probably also doesn’t have to
* 🛲🚃 – Diesel Locomotive isn’t defined in Unicode as an emoji, but could be colorful in fonts

U+1F6F5 Motor Scooter 🛵 (often displayed without a rider) and U+1F3DC Racing Motorcycle 🏍 (often displayed with a rider) could be reused as a generic motorized two-wheeled vehicle, 
but the usual glyphs are more appropriate to signify subcategories of generic *Motorcycles* or *Motorbikes*.

A *Snowmobile* could be represented as a sequence of a motorcycle and an emoji for winter, snow or skiing, 
e.g. U+2744 ❄️, U+2603 ☃️, U+26C4 ⛄️, U+1F328 🌨, U+1F3C2 🏂, U+1F3BF 🎿, U+26F7 ⛷, U+26F8 ⛸ or U+1F6F7 🛷 Sled.

### I. Logos, Brands etc.

Does not apply. 
Glyph design should usually be agnostic of particular manufacturers, except in special-purpose typefaces,
e.g. promotional ones or ones intended for brand use.

### J. Transient

The need for a licensed human driver may vanish for some vehicles in the years to come due to advances in automation, 
but the overall categories will remain for at least a couple of decades and have been quite stable for about half a century.

References
----------

[1] ______: ______ (______)

https://thenounproject.com/andrejs/collection/vehicle/
https://thenounproject.com/andrejs/collection/vehicle-filled/

![Trailer Home](../references/598255-200.png)
![Camper](../references/601273-200.png)

![Cargo Truck](../references/601210-200.png)
![Lorry](../references/601211-200.png)
![Lorry Semi Trailer](../references/601225-200.png)
![Lorry Trailer](../references/601227-200.png)
![Lorry Trailer Tank](../references/601236-200.png)

![Bulldozer](../references/601266-200.png)
![Excavator](../references/601268-200.png)
![Forklift](../references/598193-200.png)

![Tractor](../references/598191-200.png)
![Tractor Roofless](../references/598192-200.png)
![Harvester](../references/598281-200.png)

![Quad Bike](../references/601272-200.png)
![Smart Car](../references/598252-200.png)

![Car Sedan](../references/601216-200.png)
![Family Car](../references/601217-200.png)
![Station Wagon](../references/601222-200.png)
![Jeep](../references/601223-200.png)
![Hatchback Car](../references/601214-200.png)
![Roadster](../references/601203-200.png)
![Convertible](../references/601204-200.png)

![Golf Cart](../references/683083-200.png)
![Food Delivery Scooter](../references/683084-200.png)
![Ice Cream Cart](../references/683151-200.png)
![Steering Wheel](../references/683116-200.png)
![Wheelbarrow](../references/633289-200.png)
![Horse Wagon](../references/601776-200.png)
![Monocycle](../references/572803-200.png)
![Skateboard](../references/546282-200.png)
![Baby Stroller](../references/499293-200.png)
![Tire](../references/509908-200.png)
![Air Balloon](../references/563366-200.png)
![Zeppelin](../references/563365-200.png)
<!--
![Male Torso](../references/687411-200.png)
![Female Torso](../references/687410-200.png)
-->
https://thenounproject.com/dasska/collection/transport/

License
-------

The sample images and the sample font included in this proposal were created by
me and me alone. I hereby declare that the Unicode Consortium and its members
are granted the right to use, edit and redistribute these contents in any way
they want without restriction. Copies of the sample images and font are
available at the following address:

Screenshots were taken from Google Trends (https://www.google.com/trends/) and
Twitter (https://twitter.com).
