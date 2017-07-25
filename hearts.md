Proposal for New Emojis: **Colored Hearts**
=======================================

- **Author:** Christoph Päper <christoph.paeper@crissov.de>
- **Submitted:** 2017-07-15
- **Latest version:** <https://crissov.github.io/unicode-proposals/hearts>

Introduction
------------

I hereby request the addition of **White Heart**, **Gray Heart**, **Pink Heart**, **Brown Heart**, **Teal Heart** and **Violet Heart** emojis to the Unicode Standard. 
Rationals and glyph examples as well as discussion of inclusion and exclusion factors are included on the following pages.
As per [emoji submission guidelines](http://www.unicode.org/emoji/selection.html#submission), this document does not include the character proposal form.

Names
-----

It should not be necessary for the CLDR names to deviate from the UCD names. The gray heart emoji would probably need to use British spelling at least in the UCD, i.e. _Gr**e**y Heart_ (but I will use _a_ in this document).

| CLDR name    | CLDR keywords (English)                  |
| ------------ | ---------------------------------------- |
| White Heart  | **snow, cold, wedding, argent**          |
| Grey Heart   | **gray, stone, iron, metal, cendrée**    |
| Pink Heart   | **fuchsia, magenta, love, cute, kawaii, IR, infrared, sanguine** |
| Brown Heart  | **chocolate, poop, brunâtre, tenné**     |
| Teal Heart   | **turquoise, aqua, cyan, blue, céleste, ciel, sky, ice, cold** |
| Violet Heart | **lilac, UV, ultraviolet, murrey, rainbow** |
| Red Heart    | heart, **red, warm, hot, love, gules, rainbow** |
| Blue Heart   | blue, **indigo, , rainbow**              |
| Green Heart  | green, **eco, vert, rainbow**            |
| Yellow Heart | yellow, **or, gold, rainbow**            |
| Orange Heart | orange, **rainbow**                      |
| Purple Heart | purple, **purpure, rainbow**             |
| Black Heart  | black, evil, wicked, **emo, sable**      |

It might be reasonable to also include the keyword `color` (or `colour`) with all heart emojis listed above.

Images
------

The glyphs are the same as for the existing heart emojis, just with different fill color or (monochrome) hatching pattern.

| Twemoji                                  | Emojitwo                           | Text style                               |
| ---------------------------------------- | ---------------------------------- | ---------------------------------------- |
| ![solid white fill](img/white-heart_twemoji.svg) | ![](img/white-heart_emojitwo.svg)  | ![no hatching](img/argent-heart_emojitwo.svg) |
| ![solid gray fill](img/gray-heart_twemoji.svg) | ![](img/gray-heart_emojitwo.svg)   | ![pattern of alternating horizontal and vertical dashes](img/cendree-heart_emojitwo.svg) |
| ![solid pink fill](img/pink-heart_twemoji.svg) | ![](img/pink-heart_emojitwo.svg)   | ![crosshatch of horizontal lines and diagonal from top left to bottom right](img/sanguine-heart_emojitwo.svg) |
| ![solid brown fill](img/brown-heart_twemoji.svg) | ![](img/brown-heart_emojitwo.svg)  | ![crosshatch of vertical lines and diagonal from top left to bottom right](img/brunatre-heart_emojitwo.svg) |
| ![solid teal fill](img/teal-heart_twemoji.svg) | ![](img/teal-heart_emojitwo.svg)   | ![horizontal dash-dot pattern](img/celeste-heart_emojitwo.svg) |
| ![solid violet fill](img/violet-heart_twemoji.svg) | ![](img/violet-heart_emojitwo.svg) | ![diagonal crosshatch, i.e. diamond pattern](img/murrey-heart_emojitwo.svg) |

### Licenses

Twemoji and Emojitwo (originally Emojione) artworks are both released under a CC-BY license and so are the derived graphics used herein.

Emojixpress graphics are either redistributed Apple emojis or custom graphics mimicking that design. The legal status of both types is uncertain. They are used herein under conditions of Fair Use for documentation purposes only. 

Factors for Inclusion
---------------------

### A.	Compatibility

There are no known legacy character sets containing any of these additional heart emojis.

#### Colored Metals, Gemstones etc.

|  Tincture | ⚗️ Metal         |  Gemstone |  Planet / Roman deity |  Day     |
| ---------- | ---------------- | ---------- | ---------------------- | --------- |
| ￯ Argent   | `Ag` Silver      | Pearl      | ☽️ Moon / Luna         | Monday    |
| ❤️ Gules   | `Fe` Iron        | Ruby       | ♂️ Mars                | Tuesday   |
|  Azure    | `Sn` Tin         | Sapphire   | ♃️ Jupiter             | Wednesday |
|  Purpure  | `Hg` Quicksilver | Amethyst   | ☿️ Mercury             | Thursday  |
|  Vert     | `Cu` Copper      | Emerald    | ♀️ Venus               | Friday    |
|  Sable    | `Pb` Lead        | Diamond    | ♄️ Saturn              | Saturday  |
|  Or       | `Au` Gold        | Topaz      | ☉️ Sun / Sol           | Sunday    |


The proposed **White Heart** completes a set of colored hearts that relates to (European/Mediterranean) vexillology, heraldry, mythology, astrology, alchemy and folk symbolism as shown in the first row of the table above.

#### Colors of the Rainbow

Some descriptions of the history of the Pride or Rainbow Flag attribute the colors of the 8-stripe version by Gilbert Baker (1978) to certain concepts of life and society:

| Stripe Color | Meaning                        |
| ------------ | ------------------------------ |
| (hot) pink   | sexuality                      |
| red          | life                           |
| orange       | healing (friendship)           |
| yellow       | sunlight (vitality and energy) |
| green        | nature                         |
| turquoise    | magic / art                    |
| indigo       | serenity / harmony             |
| violet       | spirit (gratitude)             |

In the quoted case, **Pink Heart** and **Teal Heart** would complete the set. Either the existing Purple Heart or the proposed **Violet Heart** would be used for _violet_ here. Depending upon that, either the Blue Heart or the Purple Heart would represent _indigo_.

#### Flag Colors

Many striped flags that do not qualify for codes based upon ISO 3166 can be represented sufficiently by a sequence of colored hearts and possibly other emojis. In an English context at least, left to right emojis correspond to left to right or top to bottom stripes. Only for some of them, existing colored hearts offer enough options. Examples:

- Pan-African flag:	red-black-green
- Kurdish flag: red-sun/white-green
- Anarchy flag: red-black
- Romani flag: blue-wheel-green
- Asexuality flag: black-**gray**-white-purple
- Gynephilia flag: black-**gray**-white-**violet/pink**
- Androphilia flag: black-**gray**-white-blue
- Pansexuality flag: **pink**-yellow-blue
- Transgenderism flag: **teal**-**pink**-white-**pink**-**teal**
- _Bear_ flag: **brown**-orange-yellow-**rosy/pink**-white-**gray**-black

<!-- insert Live Loud Graphics Design overview http://www.liveloudgraphics.com/ -->

#### Brand Colors

Unlike flag colors, the brand colors of companies, sport teams etc. &ndash; if there is more than one &ndash; often do not have a canonical order, except sometimes for jersey colors.

- Green Bay Packers: green-yellow

### B.	Expected Usage Level 

#### Frequency

Existing heart emojis are used frequently. Some users and cultural groups associate special, sometimes arbitrary connotations with certain colors and therefore tend to use those hearts considerably more often than others. It seems reasonable to expect long-term usage similar to the currently least used colored heart emoji, which is still more than the vast number of other emojis.

#### Multiple Usages and Use in Sequences

Individual colored hearts or sequences thereof are already being used to represent entities whose emblems are ineligible for encoding, e.g. sports teams and university alma maters. With the proposed extension, almost all such uses would be covered. The heart as a universally understood symbol of affection is particularly appropriate for the use by fans and members.

### C.	Image distinctiveness 

The colors at the infrared and ultraviolet ends of the rainbow are often confused, because they both look reddish to humans. With this proposal, Purple and Violet would be as far apart as possible.

Languages and societies differ in which and how many colors they distinguish on a primary level. For some people, it will be an uncommon choice to decide between green, teal and blue, for instance. The proposed colors have been chosen to provide appropriate options for all cultures.

### D.	Completeness

This proposal aims to complete the set of solid color heart emojis. There may be some conventions that make additional distinctions which could justify future additions, but these are thought to be few. For example, all canonical tinctures of European heraldry are covered by the proposal, but some banners, coat of arms etc. may use more exotic colors or materials like metals, woods and furs. 

I am also not considering color patterns at all. A Rainbow Heart emoji is frequently requested, but could be realized as a sequence just like the Rainbow Flag. I do not know of nor expect reasonable demand for other patterns at this time.

There are at least three ways to form a heart shape with one&rsquo;s fingers: 

1. crossed thumb and index finger
2. thumbs and index fingers (and possible other) touching at tips
3. wrists and paired fingernails touching

The first of these three is the only one that is made with a single hand. I can see them all being proposed as new hand gesture emojis, but especially for those requiring both hands I seriously doubt they would make appropriate candidates.

In tattoos and other forms of abstract art that regularly involves hearts, there are some additional adornments that could be proposed to become emojis in the future. Common examples include burning, bleeding and melting hearts, a stitched broken heart as well as hearts with a pair of wings, a crown, a dagger or sword piercing it, a chain or padlock binding it or with a keyhole. These all go well beyond mere color variants and are thus out of scope of this proposal.

Another emoji that is missing but could be argued for on the basis that there is now a Brain emoji, is an Anatomical Heart.

### E.	Frequently Requested

Absolute request numbers are of little value.

#### Emojixpress

I here present request and usage data from emojirequest.com and emojistats.com, both run by Unicode member Emoji Xpress.

| Color                                    | Requests | Daily use  | Image                                    |
| ---------------------------------------- | -------- | ---------- | ---------------------------------------- |
| red (+ card suit)                        | N/A      | 68k + 2.3k | ![](http://www.emojistats.org/images/50/heavy_black_heart.png) |
| blue                                     | N/A      | 5.3k       | ![](http://www.emojistats.org/images/50/blue_heart.png) |
| [pink](https://www.emojirequest.com/r/PinkHeartEmoji) | 23k      | 4.5k       | ![](http://www.emojistats.org/images/50/Pink_Heart_In_Text_Moji.png) |
| purple                                   | N/A      | 4.4k       | ![](http://www.emojistats.org/images/50/purple_heart.png) |
| yellow                                   | N/A      | 2.2k       | ![](http://www.emojistats.org/images/50/yellow_heart.png) |
| green                                    | N/A      | 2.0k       | ![](http://www.emojistats.org/images/50/green_heart.png) |
| [ice / teal](https://www.emojirequest.com/r/IceHeartEmoji) | 16k      | 2.0k       | ![](http://www.emojistats.org/images/50/Ice_Heart_In_Text_Moji.png) |
| [orange](https://www.emojirequest.com/r/OrangeHeartEmoji) | ~~19k~~  | 1.8k       | ![](http://www.emojistats.org/images/50/Orange_Heart_In_Text_Moji.png) |
| [rainbow](https://www.emojirequest.com/r/WhiteHeartEmoji) | 35k      | 1.7k       | ![](http://www.emojistats.org/images/50/Rainbow_Heart_In_Text_Moji.png) |
| [stone / gray](https://www.emojirequest.com/r/StoneHeartEmoji) | 15k      | 1.7k       | ![](http://www.emojistats.org/images/50/Stone_Heart_In_Text_Moji.png) |
| [black](https://www.emojirequest.com/r/BlackHeartEmoji) | ~~25k~~  | 1.6k       | ![](http://www.emojistats.org/images/50/black_heart.png) |
| [white](https://www.emojirequest.com/r/WhiteHeartEmoji) | 17k      | 1.6k       | ![](http://www.emojistats.org/images/50/White_Heart_In_Text_Moji.png) |
| [fire](https://www.emojirequest.com/r/FireHeartEmoji) | 19k      | 0.7k       | ![](http://www.emojistats.org/images/50/Fire_Heart_In_Text_Moji.png) |

Interestingly, the theoretical demand for the rainbow heart is much higher than its actual usage.

#### Twitter

- many for [_white_](https://twitter.com/search?q="white%20heart"%20emoji)
- many for [_gray_](https://twitter.com/search?q="gray%20heart"%20emoji) and [_grey_](https://twitter.com/search?q="grey%20heart"%20emoji)
- a lot for [_pink_](https://twitter.com/search?q="pink%20heart"%20emoji), mostly complaining about there not being a plain variant since some implementations show the heart emojis with adornment in pink
- some for [_brown_](https://twitter.com/search?q="brown%20heart"%20emoji) and some for [_chocolate_](https://twitter.com/search?q="chocolate%20heart"%20emoji)
- many for [_teal_](https://twitter.com/search?q="teal%20heart"%20emoji) and [_turquoise_](https://twitter.com/search?q="turquoise%20heart"%20emoji) or even [_light-blue_](https://twitter.com/search?q="light-blue%20heart"%20emoji), just one for [_cyan_](https://twitter.com/search?q="cyan%20heart"%20emoji), some for [_ice_](https://twitter.com/search?q="ice%20heart"%20emoji) and [_icy_](https://twitter.com/search?q="icy%20heart"%20emoji))
- [_violet_](https://twitter.com/search?q="violet%20heart"%20emoji) is most often equated with _purple_ in English, [_lilac_](https://twitter.com/search?q="lilac%20heart"%20emoji) less so but still

#### Google Trends

#### Petitions

Factors for Exclusion
---------------------

### F.	Overly Specific

Some may argue that existing colored heart emojis are sufficient to cover all scenarios, but see H.

### G.	Open-ended

There are infinite colors, but the goal of this proposal is to complete the set of colors that need to be distinguished in written symbolism.

### H.	Already Representable

No. Some colors may be similar to others, but I tried to present at least one case for each pair where a distinction is necessary in at least one context.

### I.	Logos, Brands etc.

No. Some brands incorporate heart symbols in their corporate logo design, but none are known that relied on color alone as a distinctive feature. Several user interfaces employ a single heart icon, but there are GUIs that use a set of colored icons to arbitrarily assigns tags or labels to entities (like files or messages). No people or deities are strongly associated with a heart symbol of a particular color.

### J.	Transient

No. Color perception and heart symbolism are cultural universals that have existed for all of human history and are more than likely to stay important.

### K.	Faulty Comparison

No. I am not arguing that other colored hearts should be added, just because Black Heart and Orange Heart were introduced with Unicode 9.0 and 10.0, respectively. Each emoji proposed has enough merits of its own.

Sort location
-------------

### Category

In [collation order](http://unicode.org/emoji/charts/emoji-ordering.html#emotion), they should be sorted with other heart emojis in the `emotion` group of the `Smileys & People` section. Heart emojis could alternatively become part of the `Symbols` category.

### Emoji before

The achromatic White and Gray Hearts should be grouped with the Black Heart. The order of colored heart emojis should follow the electromagnetic spectrum descending from the red end, to make the most popular reddish colors come first. All other heart emojis should follow after the colored hearts in a semantically just sequence.

#### Now

1. Arrow
2. Red
3. Beating
4. Broken
5. Pair
6. Sparkling
7. Growing
8. Blue
9. Green
10. Yellow
11. Orange
12. Purple
13. Black
14. Ribbon
15. Revolving
16. Decoration
17. Exclamation
18. Letter

#### Then

1. Violet
2. Pink
3. Red
4. Brown
5. Orange
6. Yellow
7. Green
8. Teal
9. Blue
10. Purple
11. Black
12. Gray
13. White
14. Decoration
15. Sparkling
16. Ribbon
17. Arrow
18. Broken
19. Beating
20. Growing
21. Pair
22. Revolving
23. Exclamation
24. Letter

Other Information
-----------------

### Character Properties

The characters do not decompose in any way, unless combining color swatches would be introduced before their addition. 
They do not make use of emoji modifiers. 
No ZWJ sequences are proposed in this document that included them.
They have emoji presentation by default and reasonable text presentation has been shown above. 

References
----------

[1] ______: ______ (______)

License
-------

The sample images and the sample font included in this proposal were created by me and me alone. I hereby declare that the Unicode Consortium and its members are granted the right to use, edit and redistribute these contents in any way they want without restriction.
Copies of the sample images and font are available at the following address:

Screenshots were taken from [Google Trends](https://www.google.com/trends/) and [Twitter](https://twitter.com).
