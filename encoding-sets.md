Emoji Selection Process
===

Mark Davis, presumably on behalf of the Emoji Subcommittee, submitted a whitepaper on 28 June 2017 to clarify the influence of major vendors (Apple, Facebook, Google, Microsoft, Twitter, maybe also non-member Samsung), entitled _Emoji and Vendors: for consideration by the UTC_. It was on the [agenda of UTC#152], but I cannot find any mention of it in the [minutes of UTC#152]. In the preface of UTC#153, members of WG2, notably Michael Everson for Ireland and Andrew West for Great Britain, criticized the current, rushed process of encoding emojis and some of its results, but while [] documents this quarrel, again there seems to have been no discussion or resolution. 

I have no doubt that the text accurately describes how the process of encoding new emoji characters currently works. As already documented in [L2/147], which is backed by [L2/329], I strongly believe this process needs refinements.

Below, I will only quote from _section 2_ of the document [L2/206], because _section 1_ just describes uncontroversial common knowledge about the encoding process for *usual* characters. It expressively assumes that emojis are unusual, a notion I will contest.

[agenda of UTC#152]: http://www.unicode.org/L2/L2017/17221.htm "L2/17-221"
[minutes of UTC#152]: http://www.unicode.org/L2/L2017/17222.htm "L2/17-222"
[agenda of UTC#153]: http://www.unicode.org/L2/L2017/17361.htm "L2/17-361"
[minutes of UTC#153]: http://www.unicode.org/L2/L2017/17362.htm "L2/17-362"
[L2/147]: http://www.unicode.org/L2/L2017/17147-emoji-subcommittee.pdf "Request for greater transparency in the Emoji Subcommittee by Andrew West, Charlotte Buff and Christoph Päper"
[L2/206]: http://www.unicode.org/L2/L2017/17206-emoji-and-vendors.pdf "Emoji and Vendors: for consideration by the UTC by Mark Davis"
[L2/329]: http://www.unicode.org/L2/L2017/17329-n4888-future-add-nsai.pdf "Future Additions to ISO/IEC 10646 (WG2 N4888)"

> Emoji characters are quite different.

Pictographs
---

> There is an unlimited number of possible images of things, and there is no goal to encode them all, or even any large number of them.

My first issue is with terminology. We must not think of emojis as images!

An _image_ depicts some graphic original and in the case of a _picture_ it is the original itself.

icon, 

motivated, arbitrary

pictograph

Popularity
---

> the goal is to progressively add sets of emoji that will be popular

There are different types and measures of popularity.

* _Local and global popularity_: geographically, 
* _Recurring and fading popularity_: 
* _Relative and absolute popularity_: 
* _Perceived and actual popularity_: 
* _Local popularity_: 
* _Local popularity_: 
* ​

Vendors
---

> It would be pointless … to include an emoji that did not end up being supported by major vendors. 

Gatekeeper

Even if it made commercial sense to limit the annual amount of new emojis to a couple dozens, that does not mean the UCS cannot take more pictographic additions than that. If there were many pictographs available in Unicode, the job of the ESC would be mostly reduced to recommending which ones should get the `Emoji` property and what their default rendering should be (i.e. VS-15 `text` or VS-16 `emoji`).

Sets
---



Synthesis
---

combining emoticons

Conclusion
---



Annex: Sets
---



### Astrological metaphors

https://github.com/Crissov/unicode-proposals/issues/388

#### Celtic zodiac signs

The Celtic zodiac is based on a lunar cycle and thus includes 13 signs.

I have not yet determined whether there ever was a canonical set of zodiac signs and how much is specified by recent neo-pagan culture.

#### Amerindian spirit or totem animals

I do not know whether pre-columbian Amerindian peoples identified the same constellations as did the Europeans, but there seems to be an established folk tradition now to correlate the 12 old-world zodiac signs with new-world totems or spirit animals. There is some variation among sources as to which animals are used, but it is always only animals.

| Sign                                     | Start date   | Equivalent       |
| ---------------------------------------- | ------------ | ---------------- |
| **Goose**, ![🐻] Bear                    | December 22  | ![♑] Capricorn   |
| **Otter**, **Magpie**                    | January 20   | ![♒] Aquarius    |
| ![🐺] Wolf, (![🐆]) Cougar, ![🐳] ![🐋] Whale | February 20  | ![♓] Pisces      |
| **Falcon**, **Hawk**, ![🐺] Wolf         | March 20     | ![♈] Aries       |
| **Beaver**, **Elk/Moose**                | April 20     | ![♉] Taurus      |
| ![🦌]Deer, ![🦅] Eagle                   | May 21       | ![♊] Gemini      |
| (![🐦]) **Woodpecker / Flicker**, (![🐟]) **Salmon** | June 21      | ![♋] Cancer      |
| (![🐟]) **Salmon / Sturgeon**, (![🐆]) **Cougar** | July 22      | ![♌] Leo         |
| ![🐻] Bear, ![🦉] Owl                    | August 22    | ![♍] Virgo       |
| Raven / Crow, ![🕊️] Dove                | September 22 | ![♎] Libra       |
| ![🐍] Snake, **Eel**                     | October 23   | ![♏] Scorpius    |
| ![🦉] Owl, ![🐴] ![🐎]  Horse, **Elk/Moose** | November 23  | ![♐] Sagittarius |


[🐻]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f43b.png "U+1F43B Bear"
[🦌]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f98c.png "U+1F98C Deer"
[🦅]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f985.png "U+1F985 Eagle"
[🐦]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f426.png "U+1F426 Bird"
[🐟]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f41f.png "U+1F41F Fish"
[🐻]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f43b.png "U+1F43B Bear"
[🦉]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f989.png "U+1F989 Owl"
[🕊️]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f54a.png "U+1F54A Dove"
[🐍]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40d.png "U+1F40D Snake"
[🐴]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f434.png "U+1F434 Horse"
[🐆]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f406.png "U+1F406 Leopard"
[🐎]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40e.png "U+1F40E Horse"
[🐳]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f433.png "U+1F433 Whale"
[🐋]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40b.png "U+1F40B Whale"
[🐺]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f43a.png "U+1F43A Wolf"

[♑]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2651.png "U+2651 Capricorn"
[♒]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2652.png "U+2652 Aquarius"
[♓]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2653.png "U+2653 Pisces"
[♈]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2648.png "U+2648 Aries"
[♉]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2649.png "U+2649 Taurus"
[♊]: https://rawgit.com/emojitwo/emojitwo/master/png/48/264a.png "U+264A Gemini"
[♋]: https://rawgit.com/emojitwo/emojitwo/master/png/48/264b.png "U+264B Cancer"
[♌]: https://rawgit.com/emojitwo/emojitwo/master/png/48/264c.png "U+264C Leo"
[♍]: https://rawgit.com/emojitwo/emojitwo/master/png/48/264d.png "U+264D Virgo"
[♎]: https://rawgit.com/emojitwo/emojitwo/master/png/48/264e.png "U+264E Libra"
[♏]: https://rawgit.com/emojitwo/emojitwo/master/png/48/264f.png "U+264F Scorpius"
[♐]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2650.png "U+2650 Sagittarius"

#### Local variants of Asian zodiac signs

In Japan, the Dragon 🐉/🐲 is sometimes depicted as a **seahorse** instead.

### Lucky Charms

| Emoji         | Charm                                    |
| ------------- | ---------------------------------------- |
| ![🐖] ![🐷]   | Pig                                      |
| **N/A**       | Penny or Coin                            |
| **N/A**       | Chimney Sweep                            |
| ![🍀]         | Four-Leaf Clover                         |
| **N/A**       | Horseshoe                                |
| ![🐞]         | Ladybug                                  |
| ![🍄]         | Mushroom, _Amanita muscaria_ / fly agaric |
| (![🐰]/![🐇]) | Rabbit foot                              |
| ![🌱]         | Mistletoe                                |
| **N/A**       | Wishbone                                 |
| ![❤️]/…       | (Red) Heart                              |
| ![🔑]/![🗝️]  | Key                                      |

[🍄]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f344.png "U+1F344 Mushroom"
[🌱]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f331.png "U+1F331 Seedling"
[❤️]: https://rawgit.com/emojitwo/emojitwo/master/png/48/26.png "U+2 Heavy Black Heart = Red Heart"
[🔑]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f511.png "U+1F511 Key"
[🗝️]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f5dd.png "U+1F5DD Old Key"


### Driving license categories

https://github.com/Crissov/unicode-proposals/blob/vehicles/vehicles.md

#### Vehicle Classes of the International Driving Permit 🌐

Established by the Conventions on Road Traffic in 1926, 1949 and 1968 (last amended in 2011), almost all countries recognize and issue licenses complying to some variant of the International Driving Permit (IDP). 
Many national and local laws defining driver’s licenses are designed to be compatible with the IDP. The vehicle classes of the Inter-American Driving Permit (IADP) are also a subset of the IDP (wherein 7700 lb. approximate 3.5 t).

The IDP is build upon 4 major classes (`A`, `B`, `C`, `D` since 1926 or 1949), 3 restricting minor classes (`A1`, `C1`, `D1` since 2011) and 1 extending minor class (`E` since 1949).

#### Vehicle Classes of the European Driving License 🇪🇺

The [European Driving License (EDL)][EDL] is a proper superset of the IDP in that it adds some vehicle classes that apply to all member countries: `A2`, `AM`, `B1` since 2013. 

| Class     | Type              | Emoji   | Description                              | Trailer Class |
| --------- | ----------------- | ------- | ---------------------------------------- | ------------- |
| AM![🇪🇺] | Moped             | ![🛵]   | ≤ 50 cm³ ∧ ≤ 45 km/h                     | —             |
| A         | Motorcycle        | ![🏍]   | > 50 cm³ ∨ 45 km/h                       | —             |
| A1        | Light Motorcycle  | **N/A** | A ≤ 125 cm³ ∧ 11 kW                      | —             |
| A2![🇪🇺] | Medium Motorcycle | **N/A** | A ≤ 35 kW ∧ ≤ 0.2 kW/kg                  | —             |
| B         | Automobile / Car  | ![🚗]   | ≤ 3.5 t                                  | BE            |
| B1![🇪🇺] | Quad & Trike      | **N/A** | > 50 cm³ ∨ > 4 kW,<br> B ≤ 15 kW ∧ ≤ 0.45 t | —             |
| C         | Lorry             | ![🚛]   | B > 3.5 t                                | CE            |
| C1        | Truck             | ![🚚]   | C ≤ 7.5 t                                | C1E           |
| D         | Bus               | ![🚌]   | B > 1+8 💺                               | DE            |
| D1        | Minibus           | ![🚐]   | D ≤ 1+16 💺                              | D1E           |
| …E        | Trailer           | **N/A** | > 0.75 t                                 | —             |

As of version 10.0 of the Unicode Standard (UTS10) and version 5.0 of Unicode Technical Standard #51 (UTS51), 
there are at least 5 characters with default emoji representation defined coherently which can reasonably designate all two-track vehicle classes. 
Alas, U+1F3CD Racing Motorcycle 🏍 is interpreted as depicting more of an activity than a vehicle by some vendors, who therefore drew it with a rider on top, cf. U+1F40E Horse 🐎 vs. U+1F3C7 Horse Racing 🏇 and U+1F6B2 Bicycle 🚲 vs. U+1F6B4 Bicyclist 🚴.

There is no emoji of a **light motorcycle** to represent class `A1`, because 🛵 U+1F6F5 Motor Scooter is *too* light. It applies to one of the European classes, probably `AM`, the others do not have appropriate emoji representations yet – also none already proposed or accepted for future versions of the standard. 
Emoji representation of the class `A2` requires a **medium motorcycle** ranging between a moped or scooter and the light one missing for IDP class `A1`. 
There are several common types of **lighter automobiles** that class `B1` applies to, e.g. ones without a roofed passenger cabin with either four or three wheels (*quad* or *trike*) or a single-track motorcycle with cabin and safety belt.

No Unicode emoji represents a **trailer** either.

#### Vehicle Classes of National Driving Licenses

Some member countries of the EDL have introduced or retained additional *national classes*. 
Most of these do (usually) not partake in normal street traffic.

Interestingly, several of these specialized vehicle classes already have emoji representations, although it is unclear whether 🚜 Tractor should represent the bigger, stronger and faster kind which is often used with heavy machinery (`F`) and, much like a lorry, to pull two trailers at once (“`FE`”), or a smaller, weaker, slower kind (“`F1`”).

##### Tractors and Other Work Vehicles

| Class                                    | Emoji   | Description                              |
| ---------------------------------------- | ------- | ---------------------------------------- |
| F![🇱🇺]![🇭🇷]![🇸🇮]![🇦🇹]![🇵🇹], F/H![🇬🇧], F1![🇱🇺], G![🇧🇪]![🇱🇮], L/T![🇩🇪], LT![🇫🇮], R/T![🇪🇪], T![🇳🇱]![🇨🇿]![🇩🇰], Tkt![🇧🇬], Tr![🇷🇴] (F), W![🇮🇪] | ![🚜]   | Agricultural or forestry tractors with or without trailers |
| F2![🇱🇺], L![🇩🇪], T![🇫🇮]            | **N/A** | Industrial tractor                       |
| F![🇱🇺]![🇦🇹]![🇵🇹], F3![🇱🇺], G![🇱🇮]![🇸🇮], L/T![🇩🇪], T![🇨🇿]![🇫🇮], Tkt![🇧🇬], Tr![🇷🇴] (F), M![🇩🇰] | **N/A** | Agricultural machines (harvester, fodder mixer …) |
| G![🇭🇷]![🇦🇹]![🇬🇧], W![🇮🇪]         | (![🏗]  | Work vehicle, heavy equipment (loader, forklift, excavator, road roller …) |
| K![🇭🇺]![🇬🇧]                          | **N/A** | Garden tractor, animal-drawn vehicle; vehicles controlled by a pedestrian |

##### Public transport

| Class                                    | Type        | Emoji | Description                              |
| ---------------------------------------- | ----------- | ----- | ---------------------------------------- |
| H![🇭🇷]![🇬🇧], I/Tv![🇷🇴], Tkm![🇧🇬], TRAM![🇱🇻], V![🇭🇺] | Tram        | ![🚋] | Cablecar, streetcar, track-laying vehicles steered by their tracks |
| T![🇱🇹], H/Tb![🇷🇴], TR![🇭🇺], TROL![🇱🇻] | Trolley Bus | ![🚎] |                                          |

##### Other

| Class                                    | Emoji       | Description                              |
| ---------------------------------------- | ----------- | ---------------------------------------- |
| A2![🇱🇺], F![🇮🇹]                      | ♿️          | Motorised vehicle / special licence for disabled person |
| A3![🇱🇺]![🇧🇪], M![🇩🇪]![🇭🇺]![🇳🇴], P![🇬🇧] | 🛵          | Moped → `AM`/`A2` (2-wheeled) cycle with auxiliary engine |
| BTP![🇪🇸]                               | 🚒🚑🚓🚨 🚐 | Priority vehicles for emergency services, school/public passenger transport, ≤ 3.5 t, ≤ 1+8 💺 |
| C1![🇱🇮]                                | 🚒 🚙       | Fire engine and caravan > 3.5 t          |
| H![🇦🇹]                                 | ⚠️          | Vehicles for dangerous goods             |
| L![🇬🇧]                                 | ⚡️          | Motor vehicles propelled by electrical power |
| N![🇬🇧]                                 | N/A         | Vehicles used for short distances on public roads |
| S/A+![🇳🇴], T![🇫🇮]                    | **N/A**     | Snowmobile with or without a trailer sledge |

[🇦🇹]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1e6-1f1f9.png "Austria"
[🇧🇪]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1e7-1f1ea.png "Belgium"
[🇧🇬]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1e7-1f1ec.png "Bulgaria"
[🇨🇿]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1e8-1f1ff.png "Czechia"
[🇩🇪]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1e9-1f1ea.png "Germany"
[🇩🇰]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1e9-1f1f0.png "Denmark"
[🇪🇪]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ea-1f1ea.png "Estonia"
[🇪🇸]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ea-1f1f8.png "Spain"
[🇪🇺]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ea-1f1fa.png "European Union"
[🇫🇮]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1eb-1f1ee.png "Finland"
[🇬🇧]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ec-1f1e7.png "Great Britain"
[🇭🇷]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ed-1f1f7.png "Croatia"
[🇭🇺]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ed-1f1fa.png "Hungary"
[🇮🇪]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ee-1f1ea.png "Ireland"
[🇮🇹]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1ee-1f1f9.png "Italy"
[🇱🇮]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f1-1f1ee.png "Liechtenstein"
[🇱🇺]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f1-1f1fa.png "Luxembourg"
[🇱🇻]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f1-1f1fb.png "Latvia"
[🇱🇹]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f1-1f1f9.png "Lithuania"
[🇳🇱]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f3-1f1f1.png "Netherlands"
[🇳🇴]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f3-1f1f4.png "Norway"
[🇵🇹]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f5-1f1f9.png "Portugal"
[🇷🇴]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f7-1f1f4.png "Romania"
[🇸🇮]: https://rawgit.com/emojitwo/emojitwo/master/png/16/1f1f8-1f1ee.png "Slovenia"

[France]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f1eb-1f1f7.png "France"
[Germany]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f1e9-1f1ea.png "Germany"
[Switzerland]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f1e8-1f1ed.png "Switzerland"
[Italy]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f1ee-1f1f9.png "Italy"
[Spain]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f1ea-1f1f8.png "Spain"


[🚋]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f68b.png "U+1F68B Cablecar"
[🚎]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f68e.png "U+1F68E Trolley Bus"
[🚜]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f69c.png "U+1F69C Tractor"
[🏗]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f3d7.png "U+1F3D7 Building Site"
[🛵]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f6f5.png "U+1F6F5 Motor Scooter"
[🏍]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f3cd.png "U+1F3CD Racing Motorcycle"
[🚗]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f697.png "U+1F697 Automobile"
[🚛]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f69b.png "U+1F69B Articulated Lorry"
[🚚]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f69a.png "U+1F69A Delivery Truck"
[🚌]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f68c.png "U+1F68C Bus"
[🚐]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f690.png "U+1F690 Minibus"

### Road warning signs

https://github.com/Crissov/unicode-proposals/issues/106#issuecomment-310614492

https://commons.wikimedia.org/wiki/Category:Animal-related_warning_road_signs

#### Australia

| Sign                                     | Emoji                    | Animal                      |
| ---------------------------------------- | ------------------------ | --------------------------- |
| [![Kangaroo crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Australia_road_sign_W5-29.svg/120px-Australia_road_sign_W5-29.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-29.svg) | ![🦘] | Kangaroo                    |
| [![Herds crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Australia_road_sign_W5-38.svg/120px-Australia_road_sign_W5-38.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-38.svg) [![Cattle crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Australia_road_sign_W5-SA63.svg/120px-Australia_road_sign_W5-SA63.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-SA63.svg) | ![🐄] ![🐑]              | Herds: cattle, sheep        |
| [![Camel crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Australia_road_sign_W5-44.svg/120px-Australia_road_sign_W5-44.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-44.svg) | ![🐪]![🐫]               | Camel                       |
| [![Rhea crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Australia_road_sign_W5-45.svg/120px-Australia_road_sign_W5-45.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-45.svg) |   **N/A**                       | **Rhea/Ratite**             |
| [![Horse crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Australia_road_sign_W5-46.svg/120px-Australia_road_sign_W5-46.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-46.svg) [![Horseback rider crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Australia_road_sign_W5-V111.svg/120px-Australia_road_sign_W5-V111.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-V111.svg) | ![🐎] ![🏇]              | Horse with or without rider |
| [![Koala crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7f/Australia_road_sign_W5-47.svg/120px-Australia_road_sign_W5-47.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-47.svg) | ![🐨]                    | Koala                       |
| [![Wombat crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/2/25/Australia_road_sign_W5-48.svg/120px-Australia_road_sign_W5-48.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-48.svg) [![Wombat crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/Australia_road_sign_W5-V112.svg/120px-Australia_road_sign_W5-V112.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-V112.svg) | **N/A**                         | **Wombat**                  |
| [![Deer crossing](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Australia_road_sign_W5-V134.svg/120px-Australia_road_sign_W5-V134.svg.png)](https://commons.wikimedia.org/wiki/File:Australia_road_sign_W5-V134.svg) | ![🦌]                    | Deer                        |

#### Europe / Vienna Convention

https://en.wikipedia.org/wiki/Comparison_of_European_road_signs#Warning

| Sign                                     | Emoji | Animal       |
| ---------------------------------------- | ----- | ------------ |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Zeichen_101-12_-_Viehtrieb%2C_StVO_2017.svg/120px-Zeichen_101-12_-_Viehtrieb%2C_StVO_2017.svg.png) | ![🐮] ![🐄]      | Cattle       |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/07/Zeichen_101-13_-_Reiter%2C_StVO_2017.svg/120px-Zeichen_101-13_-_Reiter%2C_StVO_2017.svg.png) | ![🏇]      | Horseback Rider        |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Zeichen_101-14_-_Amphibienwanderung%2C_StVO_2017.svg/120px-Zeichen_101-14_-_Amphibienwanderung%2C_StVO_2017.svg.png) | ![🐸]      | Frog or Toad |

#### Africa SADC-RTSM

| Sign                                     | Emoji             | Animal       |
| ---------------------------------------- | ----------------- | ------------ |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/SADC_road_sign_W310-RHT.svg/120px-SADC_road_sign_W310-RHT.svg.png) | ![🐮] ![🐄] ![🐂] | Cattle       |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/SADC_road_sign_W311-RHT.svg/120px-SADC_road_sign_W311-RHT.svg.png) | ![🐎] ![🐴]       | Horse        |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/SADC_road_sign_W312-RHT.svg/120px-SADC_road_sign_W312-RHT.svg.png) | ![🐑] ![🐏]       | Sheep        |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/SADC_road_sign_W313-RHT.svg/120px-SADC_road_sign_W313-RHT.svg.png) | **N/A**                  | **Antelope** |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/SADC_road_sign_W356-RHT.svg/120px-SADC_road_sign_W356-RHT.svg.png) | ![🏇]             | Horseback Rider        |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/SADC_road_sign_W357-RHT.svg/120px-SADC_road_sign_W357-RHT.svg.png) | ![🐘]             | Elephant     |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/SADC_road_sign_W358-RHT.svg/120px-SADC_road_sign_W358-RHT.svg.png) |    **N/A**               | **Warthog**  |
| ![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/SADC_road_sign_W359-RHT.svg/120px-SADC_road_sign_W359-RHT.svg.png) | ![🦛] | Hippopotamus |

### USA

https://commons.wikimedia.org/wiki/Category:Diagrams_of_animal-related_U.S._Warning_Signs

| Sign | Emoji | Animal |
| ---- | ----- | ------ |
|      |       |        |

### Kung-fu styles

https://en.wikipedia.org/wiki/Five_Animals

https://github.com/Crissov/unicode-proposals/issues/399

| Emoji       | Southern  | Alternative | Qigong            | Xingyiquan  |
| ----------- | --------- | ----------- | ----------------- | ----------- |
| ![🐯] ![🐅] | tiger     | tiger       | tiger (wood)      | tiger       |
| **N/A**     | **crane** | **crane**   | **crane** (metal) |             |
| ![🐍]       | snake     | snake       |                   | snake       |
| ![🐒] ![🐵] |           | monkey      | monkey (fire)     | monkey      |
| ![🐉] ![🐲] | dragon    |             |                   | dragon      |
| ![🐻]       |           |             | bear (earth)      | bear        |
| ![🐆]       | leopard   |             |                   |             |
| **N/A**     |           | **mantis**  |                   |             |
| ![🦌]       |           |             | deer (water)      |             |
| ![🐎] ![🐴] |           |             |                   | horse       |
| ![🐊]       |           |             |                   | alligator   |
| ![🐓]       |           |             |                   | cockerel    |
| ![🦅]       |           |             |                   | eagle       |
| **N/A**     |           |             |                   | **hawk**    |
| **N/A**     |           |             |                   | **swallow** |
| **N/A**     |           |             |                   | **ostrich** |


[🐅]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f405.png "U+1F405 Tiger"
[🐯]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f42f.png "U+1F42F Tiger Face"
[🐍]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40d.png "U+1F40D Snake"
[🐒]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f412.png "U+1F412 Monkey"
[🐵]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f435.png "U+1F435 Monkey Face"
[🐉]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f409.png "U+1F409 Dragon"
[🐲]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f432.png "U+1F432 Dragon Face"
[🐻]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f43b.png "U+1F43B Bear"
[🐆]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f406.png "U+1F406 Leopard"
[🦌]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f98c.png "U+1F98C Deer"
[🐎]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40e.png "U+1F40E Horse"
[🐴]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f434.png "U+1F434 Horse Face"
[🏇]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f3c7.png "U+1F3C7 Horse Racing"
[🐊]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40a.png "U+1F40A Crocodile"
[🐓]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f413.png "U+1F413 Rooster"
[🦅]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f985.png "U+1F985 Eagle"
[🐞]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f41e.png "U+1F41E Lady Beetle"
[🐰]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f430.png "U+1F430 Rabbit Face"
[🐇]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f407.png "U+1F407 Rabbit"
[🐖]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f416.png "U+1F416 Pig"
[🐷]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f437.png "U+1F437 Pig Face"
[🐮]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f42e.png "U+1F42E Cow Face"
[🐄]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f404.png "U+1F404 Cow"
[🐂]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f402.png "U+1F402 Ox"
[🐪]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f42a.png "U+1F42A Dromedary Camel"
[🐫]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f42b.png "U+1F42B Bactrian Camel"
[🐘]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f418.png "U+1F418 Elephant"
[🐑]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f411.png "U+1F411 Sheep"
[🐏]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f40f.png "U+1F40F Ram"
[🐐]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f410.png "U+1F410 Goat"
[🐨]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f428.png "U+1F428 Koala"
[🦘]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f998.png "U+1F998 Kangaroo"
[🦛]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f99b.png "U+1F99B Hippopotamus"
[🐸]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f438.png "U+1F438 Frog"

### Alternative European card suits

https://github.com/Crissov/unicode-proposals/issues/289

The standard international, originally French, [card suits](https://en.wikipedia.org/wiki/Suit_(cards)) are Clubs, Spades, Hearts and Diamonds. Due to compatibility with legacy character sets, Unicode has had these rather abstract symbols in hollow _White_ ♡♢♤♧ and filled _Black_ ♠♣♥♦ forms since forever (U+2660–7). Most original Japanese emoji sets also featured them: some in black and red, others using four different colors: red heart, blue spade, orange (or golden) diamond and green club. Unicode emojis use the filled _Black_ variants for all of them, which are, for some obscure reason, not found at successive codepoints.

![Comparison of original Japanese card suits emoji from a conversion table released jointly by NTT Docomo and KDDI au in 2015](img/japanese-card-suits.png)

There are, however, local variants of the four suits that derive from the [Minor Arcana](https://en.wikipedia.org/wiki/Minor_Arcana). 

- *Wands*: batons, staves, acorns, clovers, clubs
- *Cups*: roses, hearts
- *Swords*: pikes, shields, leaves, spades
- *Pentacles*: coins, disks, rings, jingle bells, tiles, rings, crescents, diamonds

| ![France]                                | ![Germany]                               | ![Switzerland]                           | ![Italy]                                 | ![Spain]                                 | Tarot                                    |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| ![trèfles](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/SuitClubs.svg/32px-SuitClubs.svg.png) | ![Eichel/Ecker](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Bay_eichel.svg/19px-Bay_eichel.svg.png) | ![Eicheln](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/EichelndeutschschweizerBlatt.svg/17px-EichelndeutschschweizerBlatt.svg.png) | ![bastoni](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Seme_bastoni_carte_trevisane.svg/4px-Seme_bastoni_carte_trevisane.svg.png) | ![bastos](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a9/Seme_bastoni_carte_spagnole.svg/12px-Seme_bastoni_carte_spagnole.svg.png) | ![Marseille](https://upload.wikimedia.org/wikipedia/commons/thumb/8/85/Tarot_de_Marseille_clubs01.jpg/62px-Tarot_de_Marseille_clubs01.jpg) ![Piedmont](https://upload.wikimedia.org/wikipedia/commons/thumb/6/66/Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Batons.jpg/68px-Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Batons.jpg) |
| ![carreaux](https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/SuitDiamonds.svg/32px-SuitDiamonds.svg.png) | ![Schellen](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Bay_schellen.svg/32px-Bay_schellen.svg.png) | ![Schellen](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/SchellendeutschschweizerBlatt.svg/35px-SchellendeutschschweizerBlatt.svg.png) | ![denari](https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Seme_denari_carte_trevisane.svg/35px-Seme_denari_carte_trevisane.svg.png) | ![oros](https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Seme_denari_carte_spagnole.svg/35px-Seme_denari_carte_spagnole.svg.png) | ![Marseille](https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Tarot_de_Marseille_coins01.jpg/62px-Tarot_de_Marseille_coins01.jpg) ![Piedmont](https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Coins.jpg/68px-Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Coins.jpg) |
| ![piques](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/SuitSpades.svg/32px-SuitSpades.svg.png) | ![Gras/Grün/Laub/Blatt](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Bay_gras.svg/32px-Bay_gras.svg.png) | ![Schilten](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Bouclier_jeu_de_carte.svg/24px-Bouclier_jeu_de_carte.svg.png) | ![spade](https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Seme_spade_carte_trevisane.svg/13px-Seme_spade_carte_trevisane.svg.png) | ![espadas](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Seme_spade_carte_spagnole.svg/10px-Seme_spade_carte_spagnole.svg.png) | ![Marseille](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/Tarot_de_Marseille_swords01.jpg/62px-Tarot_de_Marseille_swords01.jpg) ![Piedmont](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Swords.jpg/69px-Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Swords.jpg) |
| ![cœurs](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f0/SuitHearts.svg/35px-SuitHearts.svg.png) | ![Herz/Rot](https://upload.wikimedia.org/wikipedia/commons/thumb/5/50/Bay_herz.svg/35px-Bay_herz.svg.png) | ![Rosen](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/RosendeutschschweizerBlatt.svg/35px-RosendeutschschweizerBlatt.svg.png) | ![coppe](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Seme_coppe_carte_trevisane.svg/17px-Seme_coppe_carte_trevisane.svg.png) | ![copas](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Seme_coppe_carte_spagnole.svg/25px-Seme_coppe_carte_spagnole.svg.png) | ![Marseille](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Tarot_de_Marseille_cups01.jpg/62px-Tarot_de_Marseille_cups01.jpg) ![Piedmont](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Cups.jpg/68px-Piedmontese_tarot_deck_-_Solesio_-_1865_-_Ace_of_Cups.jpg) |

#### ![♠] Spades

| Emoji | Suit |
| ![🍂] ![🍁] ![🍃] | Leaf |
| ![🛡] | Shield |
| ![⚔] ![🗡] | Sword / Wand / Staff / Pike / Stave |

#### ![♣] Clubs

  -   - ![🌰] Acorn
  - Baton / Club
  - ![🍀] ![☘] Clover
- ![♥]
  - ![🏵] ![🌹] ![🌼] ![🌷]  ![🌸]  Rose (flower, blossom)
  - ![🏆] Cup
- ![♦]
  - ![🏅]  ![💰]  Coin
  - ![💎] Diamond
  - ![💍] Ring
  - ![🔔] ![🛎] ![🎐] Bell
  - ![🌙] ![🌛] ![🌜]  Crescent


[♠]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2660.png	"U+2660"
[🍂]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f342.png	"U+1F342"
[🍁]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f341.png	"U+1F341"
[🍃]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f343.png	"U+1F343"
[🛡]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f6e1.png "U+1F6E1 Shield"
[⚔]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2694.png	"U+2694"
[🗡]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f5e1.png	"U+1F5E1"
[♣]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2663.png	"U+2663 Black Clubs"
[🌰]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f330.png	"U+1F330"
[🍀]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f340.png	"U+1F340"
[☘]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2618.png	"U+2618"
[♥]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2665.png	"U+2665"
[🏵]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f3f5.png	"U+1F3F5"
[🌹]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f339.png	"U+1F339"
[🌼]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f33c.png	"U+1F33C"
[🌷]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f337.png	"U+1F337"
[🌸]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f338.png "U+1F338 Cherry Blossom"
[🏆]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f3c6.png	"U+1F3C6"
[♦]: https://rawgit.com/emojitwo/emojitwo/master/png/48/2666.png	"U+2666"
[🏅]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f3c5.png	"U+1F3C5"
[💰]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f4b0.png	"U+1F4B0"
[💎]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f48e.png	"U+1F48E"
[💍]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f48d.png	"U+1F48D"
[🔔]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f514.png	"U+1F514"
[🛎]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f6ce.png	"U+1F6CE"
[🎐]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f390.png	"U+1F390"
[🌙]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f319.png	"U+1F319"
[🌛]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f31b.png	"U+1F31B"
[🌜]: https://rawgit.com/emojitwo/emojitwo/master/png/48/1f31c.png	"U+1F31C"

### Body parts

- Genitalia
- Mamma
- Buttocks

### Finger games

- rock, paper, scissors
- rock, paper, scissors, lizard, Spock
- ...

### Heraldry

https://en.wikipedia.org/wiki/List_of_heraldic_charges#Beasts