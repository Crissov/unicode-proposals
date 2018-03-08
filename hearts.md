Proposal for New Emojis: **Colored Hearts**
=======================================

- **Author:** Christoph Päper <christoph.paeper@crissov.de>
- **Submitted:** 2018-02-26
- **Latest version:** <https://crissov.github.io/unicode-proposals/hearts>

| ![Gray Heart](img/gray-heart_emojitwo.svg) | ![White Heart](img/white-heart_emojitwo.svg) | ![Brown Heart](img/brown-heart_emojitwo.svg) | ![Pink Heart](img/pink-heart_emojitwo.svg) | ![Maroon Heart](img/maroon-heart_emojitwo.svg) | ![Teal Heart](img/teal-heart_emojitwo.svg) | |
|---|---|---|---|---|---|---|
| ![Black Heart](img/1f5a4_emojitwo.svg) | ![Yellow Heart](img/1f49b_emojitwo.svg) | ![Orange Heart](img/1f9e1_emojitwo.svg) | ![Red Heart](img/2764_emojitwo.svg) | ![Purple Heart](img/1f49c_emojitwo.svg) | ![Blue Heart](img/1f499_emojitwo.svg) | ![Green Heart](img/1f49a_emojitwo.svg) |


Introduction
------------

I hereby request the addition of **Gray Heart**, **White Heart**, **Brown Heart**, **Pink Heart**, **Maroon Heart** and **Teal Heart** emojis to the Unicode Standard. These six emojis only differ by color. 

These emojis, like existing colored hearts, have two effective purposes: 

1. Indicate affection for something that is associated with a certain color.
2. Act as a color swatch (without negative connotations).

The following examples for color meaning and associations are not meant to be exhaustive.

+ The Gray Heart lies between the White Heart and the existing Black Heart to indicate a non-binary state. The color is associated with concrete, stone, possibly metal and ashes, boredom.
+ The White Heart contrasts with the Black Heart. The color stands for immaculacy, innocence, marriage, virginity, snow and, in some cultures, death.
+ The Brown Heart resembles a piece of chocolate. The color also stands for coffee, darker human skin tones, soil, dirt and feces.
+ The Pink Heart shall be disunified from the Red Heart. The color stands for (baby) girls, cuteness, warmth, lighter human skin tones, venous blood and sex.
+ The Maroon Heart is also close to the Red Heart. The color stands for arterial blood and heat.
+ The Teal Heart is a lighter Blue Heart. The color stands for (baby) boys, sky, water, ice, cold, luxury.

Glyph examples and discussion of inclusion and exclusion factors are included on the following pages. As per the [emoji submission guidelines](http://www.unicode.org/emoji/selection.html#submission), this document does not include the character proposal form.

Names
-----

It should not be necessary for the English CLDR names to deviate from the UCD names. The gray heart emoji would probably need to use British spelling in the UCD, i.e. _Gr**e**y Heart_, but I will consistently use _a_ in this document.

| CLDR name        | CLDR keywords (English)                                      |
| ---------------- | ------------------------------------------------------------ |
| **Gray Heart**   | **gray, stone, iron, metal, ash, _cendrée_**                 |
| **White Heart**  | **snow, cold, wedding, _argent_**                            |
| **Brown Heart**  | **chocolate, cocoa, earth, poop, _brunâtre, tenné_**         |
| **Pink Heart**   | **fuchsia, magenta, love, IR, infrared, warm, _sanguine_, rainbow** |
| **Maroon Heart** | **dark red, berry, hot, _murrey_**                           |
| **Teal Heart**   | **turquoise, aqua, cyan, blue, _céleste, ciel_, sky, ice, cold** |
| Red Heart        | heart, **red, warm, hot, love, _gules_, rainbow**            |
| Blue Heart       | blue, **indigo, _azure_, rainbow**                           |
| Green Heart      | green, **eco, _vert_, rainbow**                              |
| Yellow Heart     | yellow, **gold, _or_, rainbow**                              |
| Orange Heart     | orange, **rainbow**                                          |
| Purple Heart     | purple, **violet, lilac, UV, ultraviolet, _purpure_, rainbow** |
| Black Heart      | black, evil, wicked, **emo, _sable_**                        |

It might be reasonable to also include the keyword _color_ (or _colour_) with all heart emojis listed above. Adding _heart_ would be redundant with the name and has thus been omitted.

Images
------

The glyphs are the same as for the existing heart emojis, just with different fill color or (monochrome) hatching pattern. The colors themselves are usually already available in the shared color palete of emoji sets. The White Heart in particular would benefit from some kind of outline stroke or shadow for increased contrast.

| Twemoji                                            | Emojitwo                           | Text style                                                   |
| -------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------ |
| ![solid white fill](img/white-heart_twemoji.svg)   | ![](img/white-heart_emojitwo.svg)  | ![no hatching](img/argent-heart_emojitwo.svg)                |
| ![solid gray fill](img/gray-heart_twemoji.svg)     | ![](img/gray-heart_emojitwo.svg)   | ![pattern of alternating horizontal and vertical dashes](img/cendree-heart_emojitwo.svg) |
| ![solid pink fill](img/pink-heart_twemoji.svg)     | ![](img/pink-heart_emojitwo.svg)   | ![crosshatch of horizontal lines and diagonal from top left to bottom right](img/sanguine-heart_emojitwo.svg) |
| ![solid brown fill](img/brown-heart_twemoji.svg)   | ![](img/brown-heart_emojitwo.svg)  | ![crosshatch of vertical lines and diagonal from top left to bottom right](img/brunatre-heart_emojitwo.svg) |
| ![solid teal fill](img/teal-heart_twemoji.svg)     | ![](img/teal-heart_emojitwo.svg)   | ![horizontal dash-dot pattern](img/celeste-heart_emojitwo.svg) |
| ![solid maroon fill](img/maroon-heart_twemoji.svg) | ![](img/maroon-heart_emojitwo.svg) | ![diagonal crosshatch, i.e. diamond pattern](img/murrey-heart_emojitwo.svg) |

Factors for Inclusion
---------------------

### A.	Compatibility

There are no known legacy character sets containing any of these additional heart emojis except for the Pink Heart:

- Apple displayed the Growing Heart emoji U+1F497 as a solid and static pink heart before the release of iOS 5 in 2011. [![Growing Heart in iOS 5.0](https://emojipedia-us.s3.amazonaws.com/thumbs/160/apple/125/growing-heart_1f497.png)](https://emojipedia.org/apple/ios-4.0/growing-heart/) 
- The Red Heart U+2764 in Google’s Noto Color Emoji before mid-2017 was pink. The respective Heart Suit emoji U+2665 was more orange than red.  
  [![Red Heart in Android 4.4 through 7.1](https://emojipedia-us.s3.amazonaws.com/thumbs/60/google/3/heavy-black-heart_2764.png)](https://emojipedia.org/google/android-5.0/heavy-black-heart/)
  [![Heart Suit  in Android 4.4 through 7.1](https://emojipedia-us.s3.amazonaws.com/thumbs/60/google/3/black-heart-suit_2665.png)](https://emojipedia.org/google/android-5.0/black-heart-suit/)
- The original emoji sets from Japanese vendors [Softbank](https://crissov.github.io/original-emoji/softbank/), [KDDI](https://crissov.github.io/original-emoji/kddi-au/) and [E-Mobile](https://crissov.github.io/original-emoji/emobile/) as well as [Gmail](https://crissov.github.io/original-emoji/gmail/) also had the Red Heart U+2764 with a pink color distinguishing it from the Heart Suit emoji U+2665 shown in red.  
  ![Softbank: E+022](http://creation.mb.softbank.jp/mc/tech/tech_pic/img/E022_20.gif) ![KDDI: B0C](http://mail.google.com/mail/e/ezweb_ne_jp/B0C) ![E-Mobile: F991](https://rawgit.com/Crissov/original-emoji/master/y-mobile/m/F991.gif) ![Gmail: B0C](http://mail.google.com/mail/e/B0C)  
  ![Softbank: E+20C](http://creation.mb.softbank.jp/mc/tech/tech_pic/img/E20C_20.gif) ![KDDI: B1A](http://mail.google.com/mail/e/ezweb_ne_jp/B1A) ![E-Mobile: F8EE](https://rawgit.com/Crissov/original-emoji/master/y-mobile/m/F8EE.gif) ![Gmail: B1A](http://mail.google.com/mail/e/B1A)
- More complex heart emojis are displayed in pink instead of red by most vendors.

Softbank also had the Heart with Ribbon U+1F49D (unified with the Sparkling Heart U+1F496) shown in brown, probably because it was strongly associated with chocolate.  
![E+437](http://creation.mb.softbank.jp/mc/tech/tech_pic/img/E437_20_ani.gif)

#### Heraldic tinctures

The hatching patterns in monochromatic Unicode sample glyphs are taken from European heraldry (_Petra Sancta_ system), although the patterns have not been universally accepted throughout history.

[![Illustration of different heraldic hatching pattern systems from Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Coa_Illustration_Tinctures_Eng_2.svg/708px-Coa_Illustration_Tinctures_Eng_2.svg.png)](https://commons.wikimedia.org/wiki/File:Coa_Illustration_Tinctures_Eng_2.svg)

The number of traditional tinctures in heraldry is rather limited (cf. [L2/11-094 = WG2/N4011](http://www.unicode.org/L2/L2011/11094-n4011-hatching.pdf) and [L2/17-394](http://www.unicode.org/L2/L2017/17394-n49xx-hair-and-hatching.pdf) by Michael Everson), but still not fully covered by emoji hearts. The proposed additions fill this gap and the hatching patterns used in the representative glyphs are hence straightforward.

The tincture _carnation_ has been omitted  from this proposal, because it strongly relates to skin tone and would thus probably be subject to be an Emoji Modifier Base and take part in sequences with the Fitzpatrick Modifiers. The six colored hearts that would be generated this way can be approximated reasonably well with existing and proposed colored heart emojis.

| 🛡️ Tincture | 🎨 Color |
| ---------- | --------- |
| 💛 _or_       | yellow or gold |
| ❌ _argent_   | **white** or silver |
| ❤️ _gules_    | red |
| 💙 _azure_    | (water) blue |
| 💚 _vert_     | (grass) green |
| 🖤 _sable_    | black |
| 💜 _purpure_  | purple or violet |
| 🧡 _orange_   | orange |
| ❌ _cendrée_   | **gray** |
| ❌ _sanguine_   | (blood) red: **pink** |
| ❌ _murrey_   | **maroon** or dark red to dark purple |
| ❌ _bleu-céleste_ or _bleu de ciel_   | sky blue or light blue: **teal** |
| ❌ _carnation_   | (rosy) skin or flesh |
| ❌ _tenné_ or _brunâtre_   | **brown** |


#### European symbolism

| 🛡️ Tincture | ⚗️ Metal          | 💎 Gem    | 🌐 Planet / Deity | 📆 Day     |
| ---------- | ---------------- | -------- | ---------------- | --------- |
| ❌ Argent   | `Ag` Silver      | Pearl    | ☽️ Moon / Luna    | Monday    |
| ❤️ Gules    | `Fe` Iron        | Ruby     | ♂️ Mars           | Tuesday   |
| 💙 Azure    | `Sn` Tin         | Sapphire | ♃️ Jupiter        | Wednesday |
| 💜 Purpure  | `Hg` Quicksilver | Amethyst | ☿️ Mercury        | Thursday  |
| 💚 Vert     | `Cu` Copper      | Emerald  | ♀️ Venus          | Friday    |
| 🖤 Sable    | `Pb` Lead        | Diamond  | ♄️ Saturn         | Saturday  |
| 💛 Or       | `Au` Gold        | Topaz    | ☉️ Sun / Sol      | Sunday    |

The proposed **White Heart** completes a set of colored hearts that relates to European and Mediterranean vexillology, heraldry, mythology, astrology, alchemy and folk symbolism as shown in the table above.

#### Flag Colors

Many striped flags that do not qualify for codes based upon ISO 3166 can be represented sufficiently by a colloquial sequence of color swatches, possibly interspersed with other emojis, which does not need to be documented by Unicode. 

Since hearts already come in the most colors and are positively connotated, they are an intuitive choice for the necessary color swatches. In a Western context at least, a left to right sequence of emojis corresponds to a flag of left to right or top to bottom stripes. 

For some of these flags, existing emojis offer enough options:

| Sequence | Flag | Components |
|----|----|----|
| ❤️🖤💚 | Pan-African flag | red, black, green |
| ❤️🖤 | Anarchy flag | red, black (or vice versa) |
| ❤️☀️💚 | Kurdish flag | red, sun on white, green |
| 🖤☀️❤️ | Australian Aboriginal flag | yellow circle (or sun) on black and red |
| 💙☸️💚 | Romani flag | (red) wheel on blue and green |
| ❤️☀️🌳❤️ | Oromo flag | red, tree on sun on green, red |
| ⭐💚 | Esperanto flag | star, green |

*White* is a very common color in flags that is missing as a heart symbol, although white circle (U+26AA) and white squares (e.g. U+2B1C) are available as emojis. 

Most designs of the many [flags developed for representing sexual identiy groups]() in particular have been inspired by the Rainbow Flag with its horizontal stripes, but are often using colors not found in classic vexillology.

+ Asexuality flag: black-**gray**-**white**-purple
+ Gynephilia flag: black-**gray**-**white**-**violet/pink**
+ Androphilia flag: black-**gray**-**white**-blue
+ Pansexuality flag: **pink**-yellow-blue
+ Transgenderism flag: **teal**-**pink**-**white**-**pink**-**teal**
+ _Bear_ flag: **brown**-orange-yellow-**pink**-**white**-**gray**-black

#### Brand Colors

Unlike flag colors, the brand colors of companies, sport teams etc. &ndash; if there is more than one &ndash; often do not have a canonical order, except sometimes for jersey colors. 

Fans like to express their support by putting their team colors everywhere. The proposed colored heart emojis extend these possibilities to more franchises. In many leagues, combinations of two or three heart emojis would suffice. A superficial inspection of the team colors of some leagues with international recognition (e.g. [NBA](https://uni-watch.com/2012/12/23/making-the-nba-just-about-the-uni-colors/)) shows that almost all are sufficiently covered with this proposal, except there may be a case to distinguish _navy_ (dark blue) from blue and teal (light blue) as well as _dark green_ from (lime) green.

In some national sports, animals etc. featured in the (nick) names of the teams fulfill much the same role.

#### Colors of the Rainbow

There is no right answer to the question how many colors there are in the rainbow. Some people draw one with as little as three or four colors, often in an inaccurate order, while other paint a seemless gradient. The [Roy G. Biv mnemonic](https://en.wikipedia.org/wiki/ROYGBIV) seems popular in English, resulting in many seven-color rainbows, although rainbows with eight or more distinct color bands still also occur.

However, the exact look certainly also depends on the pens, crayons or other material available. Emojis are effectively used like drawing stamps. The five non-black emoji hearts available before Unicode 10.0 have been used to this effect as are the six ones available now with the addition of the Orange Heart U+1F9E1.

Some descriptions of the history of the Pride Flag or Rainbow Flag attribute the colors of the 8-stripe version by Gilbert Baker (1978) to certain concepts of life and society:

| | Stripe Color | Meaning                        |
| --- | ------------ | ------------------------------ |
| ❌ | (hot) pink   | sexuality                      |
| ❤️ | red          | life                           |
| 🧡 | orange       | healing (friendship)           |
| 💛 | yellow       | sunlight (vitality and energy) |
| 💚 | green        | nature                         |
| ❌ | turquoise    | magic / art                    |
| 💙 | indigo       | serenity / harmony             |
| 💜 | violet       | spirit (gratitude)             |

In the quoted case, **Pink Heart** and **Teal Heart** (for _turquoise_) would complete the set. A case could perhaps be made for a _navy_ or _indigo_ heart, since many existing Blue Heart emojis are rather light.

#### Other Color Sets

The set of colored heart emojis with the proposed additions White Heart, Gray Heart and Brown Heart would also cover all color swatches once proposed in [L2/16-318](http://www.unicode.org/L2/L2016/16318-ten-colors.pdf) by Paul D. Hunt.

### B. Expected Usage Level

#### Frequency

Existing heart emojis are used frequently. Only faces are more popular in general. Some users and cultural groups associate special, sometimes arbitrary connotations with certain colors and therefore tend to use those hearts considerably more often than others. It seems reasonable to expect long-term usage similar to the currently least used colored heart emoji, which is still more than the vast number of other emojis.

#### Multiple Usages and Use in Sequences

Individual colored hearts or short sequences thereof are already being used to represent entities whose emblems are ineligible for encoding, e.g. sports teams and university alma maters. With the proposed extension, almost all such uses would be covered. The heart as a universally understood symbol of affection is particularly appropriate for the use by fans and members.

### C.	Image distinctiveness

The colors at the infrared and ultraviolet ends of the rainbow are often confused, because they both look reddish to humans. Languages and societies differ in which and how many colors they distinguish on a primary level, see [WALS][WALS133]. For some people, it will be an uncommon choice to decide between green, teal and blue, for instance. The proposed colors have been chosen to provide appropriate options for most cultures.

Some vendors choose a rather light tint for the Blue Heart and Red Heart emojis and might have to adjust these if the Teal Heart and Pink Heart emojis are accepted.

### D.	Completeness

This proposal aims to _finalize_ the set of solid color heart emojis. There may be some conventions that make additional distinctions which could justify future additions, but these are thought to be few. For example, all canonical tinctures of European heraldry are covered by the proposal, but some banners, coats of arms etc. may use non-standard colors. 

I am also not considering hearts with *color patterns* at all. A Rainbow Heart emoji, associated with `#LoveIsLove` and _Marriage for All_, is frequently requested, but could be realized as a sequence just like the Rainbow Flag. I do not know of nor expect reasonable demand for other patterns at this time, but hearts formed from different materials are popular and have specific semantics, e.g. _crystal_, _ice_, _fire_, _stone_ (see above), _flower_ or _gingerbread_.

There are at least four ways to form a heart shape *gesture* with one&rsquo;s hands: 

1. tips of crossed thumb and index finger (single hand)
2. thumb nails and index finger tips (and possible other fingers) touching
3. thumb tips and index finger nails (and possible other fingers) touching
4. wrists and paired fingernails (except thumbs) touching

The first of these three is the only one that is made with a single hand. I can see them all being proposed as new hand gesture emojis, but especially for those requiring both hands I seriously doubt they would make appropriate candidates.

In tattoos and other forms of abstract art that regularly involves hearts, there are some additional adornments that could be proposed to become emojis in the future. Common examples include *burning*, *bleeding* and *melting* hearts, a *stitched* broken heart as well as hearts with a pair of *wings*, a *crown*, a *dagger* or *sword* piercing it, a *chain* or *padlock* binding it or with a *keyhole*. These all go well beyond mere color variants and are thus out of scope of this proposal.

Another emoji that is missing but could be argued for on the basis that there is now a Brain emoji, is an *anatomical* Heart Organ.

### E.	Frequently Requested

Absolute request numbers are of little value, although they are high for additional heart emojis.

#### Emoji Xpress

I here present request data from [EmojiRequest.com](http://emojirequest.com) and usage data from [EmojiStats.com](http://emojistats.com) as of mid-February 2018. Both services are run by Unicode member Emoji Xpress and at least the former has been used to assess future emoji popularity before.

| Color                                                        | Requests | Daily use   | Image                                                        |
| ------------------------------------------------------------ | -------- | ----------- | ------------------------------------------------------------ |
| red (+ card suit)                                            | N/A      | 89k + 2.5k  | ![](http://www.emojistats.org/images/50/heavy_black_heart.png) |
| [pink](https://www.emojirequest.com/r/PinkHeartEmoji)        | 30k      | 7.8k        | ![](http://www.emojistats.org/images/50/Pink_Heart_In_Text_Moji.png) |
| blue                                                         | N/A      | 5.8k        | ![](http://www.emojistats.org/images/50/blue_heart.png)      |
| purple                                                       | N/A      | 4.9k        | ![](http://www.emojistats.org/images/50/purple_heart.png)    |
| [orange](https://www.emojirequest.com/r/OrangeHeartEmoji)    | ~~25k~~  | 2.6k + 1.1k | ![](http://www.emojistats.org/images/50/Orange_Heart_In_Text_Moji.png) |
| [white](https://www.emojirequest.com/r/WhiteHeartEmoji)      | 24k      | 3.5k        | ![](http://www.emojistats.org/images/50/White_Heart_In_Text_Moji.png) |
| [ice / teal](https://www.emojirequest.com/r/IceHeartEmoji)   | 23k      | 2.7k        | ![](http://www.emojistats.org/images/50/Ice_Heart_In_Text_Moji.png) |
| yellow                                                       | N/A      | 2.7k        | ![](http://www.emojistats.org/images/50/yellow_heart.png)    |
| [black](https://www.emojirequest.com/r/BlackHeartEmoji)      | ~~28k~~  | 2.5k        | ![](http://www.emojistats.org/images/50/black_heart.png)     |
| green                                                        | N/A      | 2.4k        | ![](http://www.emojistats.org/images/50/green_heart.png)     |
| [stone / gray](https://www.emojirequest.com/r/StoneHeartEmoji) | 22k      | 2.3k        | ![](http://www.emojistats.org/images/50/Stone_Heart_In_Text_Moji.png) |
| [rainbow](https://www.emojirequest.com/r/WhiteHeartEmoji)    | 45k      | 1.7k        | ![](http://www.emojistats.org/images/50/Rainbow_Heart_In_Text_Moji.png) |
| [fire](https://www.emojirequest.com/r/FireHeartEmoji)        | 29k      | 0.8k        | ![](http://www.emojistats.org/images/50/Fire_Heart_In_Text_Moji.png) |

Interestingly, the theoretical demand for the Rainbow Heart is much higher than its actual usage. The uses of the custom Pink Heart and the White Heart exceed several existing ones. The Ice Heart and Stone Heart may be used to estimate the popularity of the proposed Teal Heart and Gray Heart, respectively. There is no equivalent for the Brown Heart and the Maroon Heart, although the Fire Heart may be used for some purposes the latter is intended for.

#### Emojipedia

Apparently, a White Heart emoji is currently among the most frequently requested additions at Emojipedia, as a [blog post](https://blog.emojipedia.org/top-emoji-requests-2018/) explains. The author does not disclose actual numbers or metrics, just provides a qualitative assertion, but as a Unicode Member and active participant in emoji standardization, such Emojipedia should probably be trusted. In a footnote, a connection is made to ♡ U+2661 WHITE HEART SUIT which has emoji presentation on Windows. Like ♥️ U+2665 BLACK HEART SUIT, this would be inappropriate for unification as a heart emoji of any particular color.

#### Twitter

Checking tweets for emoji requests is a very inaccurate and skewed measure, but at the very least it shows that there is actual demand.

- many for [_white_](https://twitter.com/search?q="white%20heart"%20emoji)
- many for [_gray_](https://twitter.com/search?q="gray%20heart"%20emoji) and [_grey_](https://twitter.com/search?q="grey%20heart"%20emoji)
- a lot for [_pink_](https://twitter.com/search?q="pink%20heart"%20emoji), mostly complaining about there not being a plain variant since some implementations show the heart emojis with adornment in pink
- some for [_brown_](https://twitter.com/search?q="brown%20heart"%20emoji) and some for [_chocolate_](https://twitter.com/search?q="chocolate%20heart"%20emoji) (e.g. Hershey Kiss)
- many for [_teal_](https://twitter.com/search?q="teal%20heart"%20emoji) and [_turquoise_](https://twitter.com/search?q="turquoise%20heart"%20emoji) or even [_light-blue_](https://twitter.com/search?q="light-blue%20heart"%20emoji), just one for [_cyan_](https://twitter.com/search?q="cyan%20heart"%20emoji), some for [_ice_](https://twitter.com/search?q="ice%20heart"%20emoji) and [_icy_](https://twitter.com/search?q="icy%20heart"%20emoji)

#### Google Trends

Although the emoji submission guidelines recommend to check [Google Trends](https://trends.google.com/trends/explore?q=pink%20heart,red%20heart,white%20heart,brown%20heart,rainbow%20heart) for emoji requests, I strongly believe this short-term popularity metric does not provide an adequate indication of future popularity. A proper analysis may be helpful to augment the Twitter results when it spans at least a full year to rule out seasonal effects. The color terms have several close aliases that cannot be combined in this tool.

Factors for Exclusion
---------------------

### F.	Overly Specific

Some may argue that existing colored heart emojis are sufficient to cover all scenarios, but see H.

### G.	Open-ended

There are infinite colors, but the goal of this proposal is to complete the set of colors that need to be distinguished in written symbolism.

### H.	Already Representable

No. Some colors may be similar to existing ones, but for each pair there is at least one case where a distinction is necessary in at least one context.

### I.	Logos, Brands etc.

No. Some brands incorporate heart symbols in their corporate logo design, but none are known that relied on color alone as a distinctive feature. Several user interfaces employ a single heart icon, but there are GUIs that use a set of colored icons to arbitrarily assigns tags or labels to entities (like files or messages). No people or deities are strongly associated with a heart symbol of a particular color.

### J.	Transient

No. Color perception and heart symbolism are cultural universals that have existed for all of human history and are more than likely to stay important.

### K.	Faulty Comparison

No. I am not arguing that other colored hearts should be added, just because Black Heart and Orange Heart were introduced with Unicode 9.0 and 10.0, respectively. Each emoji proposed has enough merits of its own.

Sort location
-------------

### Category

In [collation order](http://unicode.org/emoji/charts/emoji-ordering.html#emotion), the new characters should be sorted with other heart emojis in the `emotion` group of the `Smileys & People` section. Heart emojis could alternatively become part of the `Symbols` category.

### Emoji before

The achromatic White and Gray Hearts should be grouped with the Black Heart. The order of colored heart emojis should follow the electromagnetic spectrum descending from the red end, to make the most popular reddish colors come first. All other heart emojis should follow after the colored hearts in a semantically just sequence.

1. Pink
2. Red
3. Maroon
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

## Character Properties

The characters do not decompose in any way, unless combining color swatches would be introduced before their addition. They do not make use of emoji modifiers. No ZWJ sequences are proposed in this document that included them. They have emoji presentation by default and reasonable text presentation has been shown above. 

### Licenses

Copies of the sample images are available at the following address: <https://github.com/Crissov/unicode-proposals/>

The sample images included in this proposal were created by me. I hereby declare that the Unicode Consortium and its members are granted the right to use, edit and redistribute these contents in accordance with CC-BY 4.0.

Twemoji and Emojitwo (originally Emojione) vector and bitmap artworks are both released under the CC-BY 4.0 license and so are the derived graphics used herein. Noto Emoji graphics are also available with an CC-BY 4.0 license and are cited unaltered herein.

Bitmaps of emojis used by Japanese telecommunication providers Softbank and KDDI or their subsidies and of Google Mail are also only quoted verbatim for documentation purposes. Emoji Xpress bitmap graphics are either redistributed Apple emojis or custom graphics mimicking that design. The legal status of both types is uncertain. They are used herein under conditions of Fair Use for documentation purposes only. 

[WALS133]: http://wals.info/chapter/133 "Paul Kay & Luisa Maffi: Number of Basic Colour Categories. The World Atlas of Language Structures Online chapter 133"

