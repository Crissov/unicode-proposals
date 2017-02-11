Proposal to Add Emoji Symbols for **Land-Bound Vehicles** to Unicode 
====================================================================

-   **Author:** Christoph Päper

-   **Mail:** christoph.paeper@crissov.de

-   **Submitted:** 2017-02-05

Introduction
------------

I hereby request the addition of 
two **Motorcycle** emojis, 
a **Trailer** emoji, 
at least one **Light Automobile** emoji,
at least one **Work** or **Construction Vehicle** emoji and 
a **Snowmobile** emoji 
to a future version of the Unicode Standard.
Rationals, glyph examples, character properties as well as discussion of
inclusion and exclusion factors are included on the following pages. As per
[emoji submission guidelines](http://www.unicode.org/emoji/selection.html#submission) 
this document does not include the character proposal form.

1. ![`A`][Motorcycle]  ![`AM/1/2`][Motorbike] ![][Food Delivery Scooter]  
   Generic *Motorcycle* and *Light Motorcycle* or *Motorbike* (without rider)

2. ![`E`][Lorry Trailer]  
   Generic *Trailer* 

3. ![`B1`][Small Car] ![][Quad Bike]  ![Trike][Golf Cart] <!--![][Trike]-->  
   *Light Automobile*, or *Quadricycle*/*Quad*/*All-Terrain Vehicle (ATV)* <!--(incl. *Wheelchair* ♿️)--> and *Tricycle*/*Trike*

4. ![][Excavator] ![][Bulldozer] ![][Forklift]  
   *Excavator* or *Bulldozer* or *Forklift*

5. ![][Snowmobile]  
   *Snowmobile*

6. ![][Steering Wheel] ![][Tire]  
   *Steering Wheel* or *Starwheel*, generic *Wheel* or *Tyre*/*Tire*

7. ![][Tractor] ![][Light Tractor] ![][Harvester]  
   *Tractor* either considerably more or less powerful than 🚜 U+1F69C, or *Harvester*

Unicode already includes a number of vehicle and transportation emojis. 
I am proposing one way to assess their completeness, which should result in a limited number of possible future extensions. This is vehicle classes in driving permits. I will limit this approach to motorized street-bound vehicles since these are most commonly used.

<!--
* Font Awesome requests: truck/pickup
* ASCII art
-->

### Vehicle Classes of the International Driving Permit 🌐

Established by the Conventions on Road Traffic in 1926, 1949 and 1968 (last amended in 2011), almost all countries recognize and issue licenses complying to some variant of the International Driving Permit (IDP). 
Many national and local laws defining driver’s licenses are designed to be compatible with the IDP. The vehicle classes of the Inter-American Driving Permit (IADP) are also a subset of the IDP (wherein 7700 lb. approximate 3.5 t).

The IDP is build upon 4 major classes (`A`, `B`, `C`, `D` since 1926 or 1949), 3 restricting minor classes (`A1`, `C1`, `D1` since 2011) and 1 extending minor class (`E` since 1949).

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
No Unicode emoji represents a trailer either. <!-- Annex 5 -->

Annex 6 (5), Domestic Driving Permit:

> The categories of vehicles for which the driving permit may be valid are the following:
>
> | |  |
> |-------|-------------|
> |   A   | Motorcycles; |
> |   B   | Motor vehicles, other than those in category A, having a permissible maximum mass not exceeding 3,500 kg and not more than eight seats in addition to the driver’s seat; |
> |   C   | Motor vehicles, other than those in category D, whose permissible maximum mass exceeds 3,500 kg; |
> |   D   | Motor vehicles used for the carriage of passengers and having more than eight seats in addition to the driver’s seat; |> |   E   | Combination of vehicles of which the driving vehicle is in a category or categories for which the driver is licensed (B, and/or C and/or D), but which are not themselves in that category or those categories. |

Annex 6 (5), Domestic Driving Permit, 1968 version with 2011 additions *highlighted*:

> The categories of vehicles for which the driving permit may be valid are the following:
>
> || |
> |-------|-------------|
> |   A   | Motorcycles; |
> |   B   | Motor vehicles, other than those in category A, having a permissible maximum mass not exceeding 3,500 kg and not more than eight seats in addition to the driver’s seat; *or motor vehicles of category B coupled to a trailer the permissible maximum mass of which does not exceed 750 kg; or motor vehicles of category B coupled to a trailer the permissible maximum mass of which exceeds 750 kg but does not exceed the unladen mass of the motor vehicle, where the combined permissible maximum mass of the vehicles so coupled does not exceed 3,500 kg;* |
> |   C   | Motor vehicles, other than those in category D, having a permissible maximum mass exceeding 3,500 kg; *or motor vehicles of category C coupled to a trailer the permissible maximum mass of which does not exceed 750 kg;* |
> |   D   | Motor vehicles used for the carriage of passengers and having more than eight seats in addition to the driver’s seat; *or motor vehicles of category D coupled to a trailer the permissible maximum mass of which does not exceed 750 kg;* |> |  *BE*   | *Motor vehicles of category B coupled to a trailer the permissible maximum mass of which exceeds 750 kg and exceeds the unladen mass of the motor vehicle; or motor vehicles of category B coupled to a trailer the permissible maximum mass of which exceeds 750 kg, where the combined permissible maximum mass of the vehicles so coupled exceeds 3,500 kg;* |
> |  *CE*   | *Motor vehicles of category C coupled to a trailer whose permissible maximum mass exceeds 750 kg;* |
> |  *DE*   | *Motor vehicles of category D coupled to a trailer whose permissible maximum mass exceeds 750 kg.* |

>Under categories A, B, C, CE, D and DE, domestic legislation may introduce the following subcategories of vehicles for which the driving permit may be valid:>
> || |
> |-------|-------------|
> | A1  | Motorcycles with a cubic capacity not exceeding 125 cm³ and a power not exceeding 11 kW (light motorcycles);> | B1  | Motor tricycles and quadricycles;> | C1  | Motor vehicles, with the exception of those in category D, the permissible maximum mass of which exceeds 3,500 kg but does not exceed 7,500 kg; or motor vehicles of subcategory C1 coupled to a trailer, the permissible maximum mass of which does not exceed 750 kg;> | D1  | Motor vehicles used for the carriage of passengers and having more than 8 seats in addition to the driver’s seat but not more than 16 seats in addition to the driver’s seat; or motor vehicles of subcategory D1 coupled to a trailer, the permissible maximum mass of which does not exceed 750 kg;> | C1E | Motor vehicles of subcategory C1 coupled to a trailer the permissible maximum mass of which exceeds 750 kg but does not exceed the unladen mass of the motor vehicle, where the combined permissible maximum mass of the vehicles so coupled does not exceed 12,000 kg;> | D1E | Motor vehicles of subcategory D1 coupled to a trailer, not used for the carriage of persons, the permissible maximum mass of which exceeds 750 kg but does not exceed the unladen mass of the motor vehicle, where the combined permissible maximum mass of the vehicles so coupled does not exceed 12,000 kg.

**source**

### Vehicle Classes of the European Driving License 🇪🇺

The [European Driving License (EDL)][EDL] is a proper superset of the IDP in that it adds some vehicle classes that apply to all member countries: `A2`, `AM`, `B1` since 2013. 

| Class | Type | Emoji | Description | Trailer Class |
|-------|------|-------|-------------|--------------|
| AM | Moped            | 🛵 Motor Scooter     | ≤ 50 cm³ ∧ ≤ 45 km/h | — |
| A  | Motorcycle       | 🏍 Racing Motorcycle |   > 50 cm³ ∨ 45 km/h | — |
| A1 | Light Motorcycle | **N/A**              | A ≤ 125 cm³ ∧ 11 kW | — |
| A2 | Medium Motorcycle| **N/A**              | A ≤ 35 kW ∧ ≤ 0.2 kW/kg | — |
| B  | Automobile / Car | 🚗 Automobile        |   ≤ 3.5 t | BE |
| B1 | Quad & Trike     | **N/A**              | > 50 cm³ ∨ > 4 kW,<br> B ≤ 15 kW ∧ ≤ 0.45 t | — |
| C  | Lorry            | 🚛 Articulated Lorry |   > 3.5 t | CE |
| C1 | Truck            | 🚚 Delivery Truck    | C ≤ 7.5 t | C1E |
| D  | Bus              | 🚌 Bus               |   > 1+8 💺 | DE |
| D1 | Minibus          | 🚐 Minibus           | D ≤ 1+16 💺 | D1E |
| …E | Trailer          | **N/A**              |   > 0.75 t | — |

U+1F6F5 Motor Scooter 🛵, introduced with TUS9 in mid-2016, applies to one of the extra classes, probably `AM`, the others do not have appropiate emoji representations  yet – also none already proposed or accepted for future versions of the standard. 
Emoji representation of the class `A2` requires a motorcycle ranging between a moped or scooter and the light one missing for IDP class `A1`. 
There are several common types of lighter automobiles that class `B1` applies to, e.g. ones without a roofed passenger cabin with either four or three wheels or a single-track motorcycle with cabin and safety belt.

### Vehicle Classes of National Driving Licenses

Some member countries of the EDL have introduced or retained additional *national classes*. 
Most of these do (usually) not partake in normal street traffic.

Interestingly, several of these specialized vehicle classes already have emoji representations, although it is unclear whether 🚜 Tractor should represent the bigger, stronger and faster kind which is often used with heavy machinery (`F`) or, much like a lorry, to pull two trailers at once (“`FE`”), or a smaller, weaker, slower kind (“`F1`”).

#### Tractors and Other Work Vehicles 🚜

| Class | Emoji | Description |
|-------|-------|-------------|
| F🇱🇺🇭🇷🇸🇮🇦🇹🇵🇹, F/H🇬🇧, F1🇱🇺, G🇧🇪🇱🇮, L🇩🇪/T🇩🇪, LT🇫🇮, R🇪🇪/T🇪🇪, T🇳🇱🇨🇿🇩🇰, Tkt🇧🇬, Tr🇷🇴 (F), W🇮🇪 | 🚜 | Agricultural or forestry tractors with or without trailers
| F2🇱🇺, L🇩🇪, T🇫🇮 | **N/A** | Industrial tractor
| F🇱🇺🇦🇹🇵🇹, F3🇱🇺, G🇱🇮🇸🇮, L🇩🇪/T🇩🇪, T🇨🇿🇫🇮, Tkt🇧🇬, Tr🇷🇴 (F), M🇩🇰 | **N/A** | Agricultural machines (harvester, fodder mixer …)
| G🇭🇷🇦🇹🇬🇧, W🇮🇪 | 🏗 | Work vehicle, heavy equipment (loader, forklift, excavator, road roller …)
| K🇭🇺🇬🇧 | **N/A** | Garden tractor, animal-drawn vehicle; vehicles controlled by a pedestrian
<!--
| Class | Type | Emoji | Description |
|-------|------|-------|-------------|
| F🇱🇺 | | | Tractors and motorized machines < 12 t
| F🇭🇷🇸🇮 | | | Tractors with or without trailers
| F🇦🇹🇵🇹 | | | Agricultural and forestry tractors, agricultural machines
| F🇬🇧 | | | Agricultural or forestry tractors, including any such vehicle drawing a trailer but ∉ H🇬🇧| F🇱🇮 | | | Vehicles ≤ 40 km/h
| F1🇱🇺 | | | Farm tractor
| F2🇱🇺 | | | Industrial tractor 
| F3🇱🇺 | | | Motorised machine
| G🇧🇪    | Tractor | 🚜 Tractor**?** | Tractor
| G🇱🇮 | | | Agricultural vehicles
| L🇩🇪 | Tractor | 🚜 Tractor**?** | Agricultural or forestry tractors, designed ≤ 40 km/h; combinations of these vehicles and trailers driven ≤ 25 km/h; self-propelling machinery, self-propelling fodder mixer vehicles, forklift trucks and other industrial trucks, each designed ≤ 25 km/h; combinations of these vehicles and trailers
| LT🇫🇮 | | | Road-rated tractors and vehicles towed by them
| R, T🇪🇪 | | | Wheeled tractors and mobile machinery / Tractor, mobile machinery and tractor train
| T🇳🇱     | Tractor | 🚜 Tractor**?** | 
| T🇨🇿     | Tractor | 🚜 Tractor**?** | tractors and self-propelled working machines; the vehicle may be coupled with a trailer. 
| T🇩🇪 | | | Tractors designed ≤ 60 km/h and self-propelling machinery or self-propelling fodder mixer vehicles designed ≤ 40 km/h; designed for agriculture or forestry and used for such purposes (all may include trailers).
| T🇭🇺 | | | Agricultural tractor and 2 heavy trailers, slow vehicle and trailer + K🇭🇺
| T🇵🇱 | | | Agricultural tractors
| T🇸🇰 | | | Agricultural tractors and forestry tractors, as well as other special motor vehicles; motor vehicles in this category may be coupled with a trailer
| T🇫🇮 | | | Tractors (excluding road-rated tractors), motorised working machinery and snowmobiles, including vehicles towed by them
| T🇳🇴 | | | Tractor, design ≤ 40 km/h
| Tkt🇧🇬 | | | Agricultural or forestry tractor, agricultural machines
| Tr←F🇷🇴 | | | Agricultural and forestry tractors, agricultural machines
| T/M🇩🇰 | | | Tractor/Motorised equipment
| W🇮🇪 | Work | | Land Tractor and Work Vehicle
| G     | Work | 🏗 Construction Site**?**| Excavator and other work machinery
| G🇭🇷 | | | Heavy equipment (working machinery such as loader, forklift, etc.)
| G🇦🇹 | | | (Special vehicles such as excavators)
| G🇵🇹 | | | (Professional drivers: BG, C[E]G, D[E]G)
| G🇸🇮 | | | Motocultivators and mobile machinery
| G🇬🇧 | | | Road rollers| K🇭🇺 | | | Garden tractor, animal-drawn vehicle
| K🇬🇧 | | | Mowing machines ∉ A🇬🇧; vehicles controlled by a pedestrian-->

#### Tram 🚋

| Class | Type | Emoji | Description |
|-------|------|-------|-------------|
| H🇭🇷🇬🇧, Tv🇷🇴 (I), Tkm🇧🇬, TRAM🇱🇻, V🇭🇺 | Tram | 🚋 | Cablecar, streetcar, track-laying vehicles steered by their tracks| T🇱🇹, Tb🇷🇴 (H), TR🇭🇺, TROL🇱🇻 | Trolley Bus | 🚎 |  
<!--
| Class | Type | Emoji | Description |
|-------|------|-------|-------------|
| H🇭🇷🇬🇧 | Tram | 🚋 Tram | Track-laying vehicles steered by their tracks| V🇭🇺 | Tram | 🚋 Tram | → `H` Cablecar, Streetcar
| Tv←I🇷🇴, Tkm🇧🇬, TRAM🇱🇻 | Tram | 🚋 Tram | → `H` Cablecar, Streetcar
| T🇱🇹, Tb←H🇷🇴, TR🇭🇺, TROL🇱🇻 | Trolley Bus | 🚎 Trolley Bus |  
-->

#### Other

| Class | Emoji | Description |
|-------|-------|-------------|
| A2🇱🇺, F🇮🇹 | ♿️ | Motorised vehicle / special licence for disabled person
| A3🇱🇺🇧🇪, M🇩🇪🇭🇺🇳🇴, P🇬🇧 | 🛵 | Moped → `AM`/`A2` (2-wheeled) cycle with auxiliary engine
| BTP🇪🇸 | 🚒🚑🚓🚨 🚐 | Priority vehicles for emergency services, school/public passenger transport, ≤ 3.5 t, ≤ 1+8 💺| C1🇱🇮 | 🚒 🚙 | Fire engine and caravan > 3.5 t
| H🇦🇹 | ⚠️<!--☢️☣️--> | Vehicles for dangerous goods
| L🇬🇧 | ⚡️ | Motor vehicles propelled by electrical power| N🇬🇧 | N/A | Vehicles used for short distances on public roads
| S🇳🇴 (A+), T🇫🇮 | **N/A** | Snowmobile with or without a trailer sledge

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

![][Steering Wheel]
![][Tire]


Glyphs and Design
-----------------

Trailers 

- ![Small, flat trailer][]
- ![Large, high trailer][]
- ![Single-axis trailer][]
- ![Double-axis trailer][Lorry Semi Trailer]
- ![Two-axes trailer][Lorry Trailer]
- ![Horse trailer][Horse Wagon]
- ![Caravan trailer][Camper]
- ![Boat trailer][]
- ![Bulk container trailer][]
- ![Fluid container trailer][Lorry Trailer Tank]

Motorbikes (without rider)

- ![Motorcycle or Motorbike][]
- ![Heavy Motorcycle][]
- ![Medium Motorcycle][]
- ![Light Motorcycle][Food Delivery Scooter]
- ![Electro bike]]
- ![Pedelec][]

Light automobiles

- [![Quadricycle “Quad” by Andrejs Kirma (CC BY 3.0 US)][Quad Bike]](https://thenounproject.com/andrejs/collection/vehicle/?i=601272)
- ![Tricycle “Trike”][Trike]

Work vehicles

- ![Excavator]
- ![Bulldozer]
- ![Forklift]

Special-purpose or special-terrain vehicles

- ![][Snowmobile]

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
   + 🛢/⛽️ tanker
   + 🚗 car carrier
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

<!--
* 🚕 – identical to Automobile, maybe matching color
* 🚓 – identical to Automobile, maybe matching color
* 🚑 – identical to Automobile, maybe matching color
* 🚒 – identical to Automobile, maybe matching color
-->
* 🚕🚓🚑🚒 – all identical to Automobile, maybe matching color
* 🚎 – similar to Bus or Minibus, overhead cable should extend
* 🏎 – quite unusual, but should match direction of other vehicles, perhaps Tractor Pull

All existing front-facing or “`Oncoming`” vehicle emojis also exist as (default) side-views and should probably not be expected to be used with a Trailer emoji.

* 🚘 → 🚗
* 🚍 → 🚌
* 🚖 → 🚕
* 🚔 → 🚓
* 🐴 → 🐎🏇

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

![Screenshot of emojitracker.com, with vehicle and related emojis highlighted]()

I have included several charts supplied by Google Trends showing the frequency of searches for “[______]” in comparison to other emoji.

Google search for the term “[______]” returns [______] results, which is more than for [______].

### C. Image distinctiveness

Yes … it’s good enough for street signs and driving licenses. Since these are using glyphs that are monochrome and, unlike usual emoji, may vary in width, it would be advisable to enable [text representation](http://www.unicode.org/emoji/charts/emoji-variants.html) with VS-15 in for all IDP/EDL characters. Of the applicable existing code points, only U+1F3CD Racing Motorcycle has text presentation (perhaps because it’s considered an activity instead of a vehicle) in Unicode 9.0. Emoji 5.0 adds several new variation sequences, but only U+1F691-FE0E is remotely relevant.

Emoji | U+ | VS-15
------|----|-----
🛵 | 1F6F5 | no
🏍 | 1F3CD | yes
🚗 | 1F697 | no
🚛 | 1F69B | no
🚚 | 1F69A | no
🚌 | 1F68C | no
🚐 | 1F690 | no
🚜 | 1F69C | no
🚋 | 1F68B | no
🚎 | 1F68E | no
🚒 | 1F692 | no
🚓 | 1F693 | no
🚑 | 1F691 | E5

### D. Completeness

Yes, the proposed emojis would cover all automobile classes currently distinguished in license and registration laws of most countries. 
This proposal does not cover cases of distinction “under the hood”, 
which are mostly relevant for taxation and insurance and not clearly visible from the outside.

### E. Frequently Requested

Not really.
There are lots of vehicle emojis already and new ones are requested much less than emoticons, hand signs, flags, animals or food. 
Completeness is the major argument to legitimate this proposal.

A *pickup truck* emoji is frequently requested in some areas, but is not included in this proposal because it usually does not require a separate driving permit (but it may be taxed differently, for instance).

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

This proposal explicitly does not deal with naval (e.g. Jetski), aerial (e.g. Hot-Air Balloon), rail-based (e.g. Mining Tub, Hyperloop) and non-motorized (e.g. Skateboard, Rollerskates, Stroller, Monocycle) vehicles. Some of these have their own sets of (international) license requirements and existing emojis, or may be proposed separately. 
It also does not cover <!-- special-purpose, professional vehicles, which usually require special training and are mostly operated outside regular traffic, 
e.g. Forklift, Excavator, Bulldozer, Harvesters and Garbage Truck,
as well as --> single-vendor product categories,
e.g. Segway.

### H. Already Representable

U+1F683 Railway Car 🚃 could be reused as a *Trailer*, but a 🛤 rail vehicle looks and feels strange in combination with 🛣 street-bound tractors. 
However, similar considerations apply as to the combination of it with other emojis, i.e. locomotives of all kinds: Railway Car works …

* 🚂🚃 – … well enough with the Steam Locomotive <!--Tender?-->
* 🚋🚃, 🚞🚃 – … reasonably with the Tram Car and Mountain Railway, except for the cable and mountain, which may be shown respectively
* 🚅🚃, 🚄🚃, 🚈🚃 – … not well with any of the other left-facing trains – should probably have adapted design
* 🚝🚃, 🚟🚃 – … hardly with special types of rails
* 🚆🚃, 🚇🚃, 🚊🚃 – … not at all with front-facing Train, Metro and Tram – doesn’t have to
* 🛲🚃 – possibly with Diesel Locomotive which isn’t defined as an emoji yet

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

  [Convention on Road Traffic](https://www.unece.org/fileadmin/DAM/trans/conventn/Conv_road_traffic_EN.pdf)
  [EU Driving License Handbook](https://circabc.europa.eu/sd/a/13f8d59f-9934-4bd3-9b97-eedaac36eb36/driving-licence_en.pdf)
  [EDL]: http://ec.europa.eu/transport/road_safety/topics/driving-licence/eu-driving_licence_en
  
Andrejs Kirma https://thenounproject.com/andrejs/collection/vehicle/
Daria Moskvina https://thenounproject.com/dasska/collection/transport/
Martin Hofmann https://thenounproject.com/martskin/collection/motorcycons/

  [Trailer Home]: ../references/598255-200.png "Trailer Home"
  [Camper]: ../references/601273-200.png "Camper"

  [Cargo Truck]: ../references/601210-200.png "Cargo Truck"
  [Lorry]: ../references/601211-200.png "Lorry"
  [Lorry Semi Trailer]: ../references/601225-200.png "Lorry Semi Trailer"
  [Lorry Trailer]: ../references/601227-200.png "Lorry Trailer"
  [Lorry Trailer Tank]: ../references/601236-200.png "Lorry Trailer Tank"

  [Bulldozer]: ../references/601266-200.png "Bulldozer"
  [Excavator]: ../references/601268-200.png "Excavator"
  [Forklift]: ../references/598193-200.png "Forklift"

  [Tractor]: ../references/598191-200.png "Tractor"
  [Light Tractor]: ../references/598192-200.png "Tractor Roofless"
  [Harvester]: ../references/598281-200.png "Harvester"

  [Quad Bike]: ../references/601272-200.png "Quad Bike"
  [Small Car]: ../references/598252-200.png "Smart Car"

  [Car Sedan]: ../references/601216-200.png "Car Sedan"
  [Family Car]: ../references/601217-200.png "Family Car"
  [Station Wagon]: ../references/601222-200.png "Station Wagon"
  [Jeep]: ../references/601223-200.png "Jeep"
  [Hatchback Car]: ../references/601214-200.png "Hatchback Car"
  [Roadster]: ../references/601203-200.png "Roadster"
  [Convertible]: ../references/601204-200.png "Convertible"

  [Golf Cart]: ../references/683083-200.png "Golf Cart"
  [Scooter]: ../references/683084-200.png "Food Delivery Scooter"
  [Ice Cream Cart]: ../references/683151-200.png "Ice Cream Cart"
  [Steering Wheel]: ../references/683116-200.png "Steering Wheel"
  [Wheelbarrow]: ../references/633289-200.png "Wheelbarrow"
  [Horse Wagon]: ../references/601776-200.png "Horse Wagon"
  [Monocycle]: ../references/572803-200.png "Monocycle"
  [Skateboard]: ../references/546282-200.png "Skateboard"
  [Stroller]: ../references/499293-200.png "Baby Stroller"
  [Tire]: ../references/509908-200.png "Tire"
  [Balloon]: ../references/563366-200.png "Air Balloon"
  [Zeppelin]: ../references/563365-200.png "Zeppelin"


License
-------

The sample images ~~and the sample font~~ included in this proposal were created by Andrejy Kirma for the Noun Project and are licensed as Creative Commons By-Name
~~me and me alone~~. 
I hereby declare that the Unicode Consortium and its members are granted the right to use, edit and redistribute these contents in any way they want without restriction. 

Source code and and other ressources of this proposal are available at Github: <http://github.com/Crissov/unicode-proposals/>

<!--
Screenshots were taken from …
-->