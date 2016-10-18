Proposal to Add Emoji Sequences for Days and Months to the Unicode Standard
===========================================================================

-   **Author:** Christoph Päper

-   **Mail:** christoph.paeper\@crissov.de

-   **Submitted:** 2016-09-[18]

Introduction
------------

I hereby request the addition of 19 ZWJ emoji sequences to the Unicode Standard
to represent the 7 days of the week and the 12 month of  the year in the
international calendar as defined in ISO 8601. At least three existing
characters, possibly as much as five, would additionally be required to have the
`Emojy` property set to `Yes` to be available in an emoji sequence.

Rationals, glyph examples, character properties as well as discussion of
inclusion and exclusion factors are included on the following pages. As per
[emoji submission
guidelines](http://www.unicode.org/emoji/selection.html\#submission) this
document does not include the character proposal form.

The semantic distinction between 📆 U+1F4C6 and 🗓 U+1F5D3 is hard to see in
many deployed fonts and image collections. It may be beneficial to designate
them to specific lengths: day and week, respectively. Although such a separation
is not part of this proposal, it assumes that 📆 U+1F4C6 is more likely to
represent a date specific to a single day than 🗓 U+1F5D3 is.

Glyph and Design
----------------

### Possible Bases

-   📅 U+1F4C5 monthly (or annual?) calendar

-   📆 U+1F4C6 tear-off daily calendar

-   🗓 U+1F5D3 flip/spiral daily (or weekly?) calendar

### Possible Modifiers

1.  ☽ U+263D or ☾ U+263E *Moon*

    -   already emoji: U+1F311–8 🌑🌒🌓🌔🌕🌖🌗🌘 – should be reserved for the
        dates of the actual lunar phases

    -   already emoji: U+1F31A–D 🌚🌛🌜🌝

2.  ♂ U+2642 *Mars* (already emoji in 4.0 as Male sign)

3.  ☿ U+263F *Mercury*

4.  ♃ U+2643 *Jupiter*

5.  ♀ U+2640 *Venus* (already emoji in 4.0 as Female sign)

6.  ♄ U+2644 *Saturn*

7.  ☉ U+2609 or ☼ U+263C *Sun*

    -   already emoji: U+1F31E 🌞

    -   already emoji: U+2600 ☀️

\_\_\_\_

1.  ♈ U+2648 *Aries*

2.  ♉ U+2649 *Taurus*

3.  ♊ U+264A *Gemini*

4.  ♋ U+264B *Cancer*

5.  ♌ U+264C *Leo*

6.  ♍ U+264D *Virgo*

7.  ♎ U+264E *Libra*

8.  ♏ U+264F *Scorpius*

9.  ♐ U+2650 *Sagittarius*

10. ♑ U+2651 *Capricorn*

11. ♒ U+2652 *Aquarius*

12. ♓ U+2653 *Pisces*

### Sequences

1.  📆‍‍☽ U+1F4C6+200D+263D / 📆‍☾ U+1F4C6+200D+263E Monday

2.  📆‍‍♂ U+1F4C6+200D+2642 Tuesday

3.  📆‍☿ U+1F4C6+200D+263F Wednesday

4.  📆‍♃ U+1F4C6+200D+2643 Thursday

5.  📆‍♀ U+1F4C6+200D+2640 Friday

6.  📆‍♄ U+1F4C6+200D+2644 Saturday

7.  📆‍☉ U+1F4C6+200D+2609 / 📆‍☼ U+1F4C6+200D+263C Sunday

\_\_\_\_

 

1.  📅‍♑ U+1F4C5+200D+2651 January

2.  📅‍♒ U+1F4C5+200D+2652 February

3.  📅‍♓ U+1F4C5+200D+2653 March

4.  📅‍♈ U+1F4C5+200D+2648 April

5.  📅‍♉ U+1F4C5+200D+2649 May

6.  📅‍♊ U+1F4C5+200D+264A June

7.  📅‍♋ U+1F4C5+200D+264B July

8.  📅‍♌ U+1F4C5+200D+264C August

9.  📅‍♍ U+1F4C5+200D+264D September

10. 📅‍♎ U+1F4C5+200D+264E October

11. 📅‍♏ U+1F4C5+200D+264F November

12. 📅‍♐ U+1F4C5+200D+2650 December

Description

![Sample Picture](.png)

Character Properties
--------------------

The preferred name of the character is “[\_\_\_\_\_\_]”. It should be added to
the [\_\_\_\_\_\_] block near other [\_\_\_\_\_\_] emoji. Properties of the
[\_\_\_\_\_\_] emoji should be identical to those of other emoji.

-   General Category: Other Symbol (So)

-   Canonical Combining Class: 0

-   Bidirectional Class: Other Neutral (ON)

-   Bidi Mirrored: No

No case-mapping is required. The character does not decompose in any way. It is
not whitespace nor a control character. It has no numeric value. It does [NOT\|]
make use of emoji modifiers. It has [TEXT\|EMOJI] presentation by default. In
collation order it should be sorted near other [\_\_\_\_\_\_] emoji. It should
definitely be part of the [\_\_\_\_\_\_] category.

Factors for Inclusion
---------------------

### A. Compatibility:

There are no known legacy character sets containing [\_\_\_\_\_\_].

### B. Expected Usage Level:

I have included several charts supplied by Google Trends showing the frequency
of searches for “[\_\_\_\_\_\_]” in comparison to other emoji.

Google search for the term “[\_\_\_\_\_\_]” returns [\_\_\_\_\_\_] results,
which is more than for [\_\_\_\_\_\_].

### C. Image distinctiveness:

...

### D. Completeness:

...

### E. Frequently Requested:

...

Factors for Exclusion
---------------------

### F. Overly Specific:

This proposal does not try to add an emoji for each and every calendar date.

### G. Open-ended:

There are several other kinds of days with special meaning within a culture,
country or community or just for an individual. Many of them could be
represented by more than one emoji. An emoji sequence that doesn’t result in a
single composed glyph seems acceptable for most of them – some can already be
encountered frequently.

-   Work day, school day, business day

    -   ⚙ U+2699 *Gear* (⛭ U+26ED is similar but not an emoji yet)

    -   ⚒ U+2692 / 🛠 U+1F6E0 / 🔧 U+1F527 / 🔨 U+1F528 *Tools*

    -   📆‍⚙ U+1F4C6+200D+2699 Workday – also “Settings”

    -   📆‍⚒ U+1F4C6+200D+2692 Workday

    -   📆‍🛠 U+1F4C6+200D+1F6E0 Workday

-   Weekend, bank holiday

    -   🚫 U+1F6AB

    -   ⛔️ U+26D4+FE0F

-   Lunar phases

    -   full moon 🌕 U+1F315 / 🌝 U+1F31D

    -   new moon 🌑 U+1F311 / 🌚 U+1F31A

    -   other 🌖🌗🌘 U+1F316–8 / 🌒🌓🌔 U+1F312–4 / 🌛 U+1F31B / 🌜 U+1F31C / 🌙
        U+1F319

-   Unknown date

    -   📆‍❓ U+1F4C6+200D+2753

    -   📆‍❔ U+1F4C6+200D+2754

-   Marked date, highlighted date, event; date/start of something

    -   📆‍⭕️ U+1F4C6+200D+2B55+FE0F

-   Checked date, passed date, ticked-off date, deadline; end of something

    -   📆‍❌ U+1F4C6+200D+274C

-   Start of season or term

    -   hunting (possibly parallel, non-exclusive, not full coverage)

        -   📆‍🥆 generic

        -   📆‍🐰 / 📆‍🐇 rabbit, hare

        -   📆‍🐻 bear

        -   📆‍🐗 boar

        -   📆‍🦆 duck

        -   📆‍🦊 fox

        -   📆‍🦌 deer

        -   📆‍🎣 fishing

    -   spring, summer, autumn/fall, winter (successive, exclusive, full
        coverage of the year)

        -   meteorologic (local definition)

        -   astronomic (hemispheric definition): Northward (March) equinox,
            (June) solstice, Southward (September) equinox, (December) solstice

        -   astrologic (hemispheric definition) ☊☋☌☍?⚬⚭⚮⚯?

        -   academic (local definition)

        -   fiscal (local or individual definition)

    -   touristic 🏊🎿⛷🎢🏕🏖 (usually successive and exclusive, not necessarily
        full coverage of the year)

    -   sport ⚽️🏀🏈⚾️🎾🏐🏉🏒🏑🏏⛵️🚤 (possibly parallel except for internal
        hierarchies like play-offs, non-exclusive, not full coverage of the
        year)

#### Anniversary

-   Generic celebration

    -   📆‍🎊 U+1F4C6+200D+1F38A

    -   📆‍🎉 U+1F4C6+200D+1F389

-   Birthday, release date, name day

    -   📆‍🎁 U+1F4C6+200D+1F381

    -   📆‍🎂 U+1F4C6+200D+1F382

    -   📆‍📛 U+1F4C6+200D+1F4DB

-   Wedding day; Valentine’s day

    -   📆‍💒 U+1F4C6+200D+1F492

    -   📆‍💍 U+1F4C6+200D+1F48D

    -   📆‍⚭ U+1F4C6+200D+26AD+FE0F – not an emoji yet

    -   📆‍💕 U+1F4C6+200D+1F495

    -   📆‍❤️ U+1F4C6+200D+2764+FE0F – also “Like”

    -   📆‍💘 U+1F4C6+200D+1F498

    -   📆‍💝 U+1F4C6+200D+1F49D

#### Holidays

-   Public Holiday

    -   Labor Day – may use a similar kind of symbolism as working day

-   National holiday, independence day, (re)unification day, constitution day,
    monarch’s birthday …

    -   U+1F4C6 + ZWJ + \<Regional Identifier\>, e.g. 📆‍🇺🇸 = 4 July

-   Memorial day, remembrance day, veteran’s day, peace day, victory day

    -   📆‍☮️ U+1F4C6+200D+262E+FE0F

    -   📆‍⚔ U+1F4C6+200D+2694

    -   📆‍🛡 U+1F4C6+200D+1F6E1 – also “Protected”

    -   📆‍⚰ U+1F4C6+200D+26B0

    -   📆‍⚱ U+1F4C6+200D+26B1

    -   📆‍✌️ U+1F4C6+200D+270C+FE0F

    -   📆‍🔖 U+1F4C6+200D+1F516

-   Religious holiday

    -   Christian Holiday … (Catholic 📆‍✝️ U+271D, Orthodox 📆‍☦️ U+2626, Coptic,
        Protestant, …), e.g.

        -   Lord’s/Church Day = Sunday

        -   Easter: Good Friday = Crucifixion, Easter Sunday = Resurrection

        -   Ascension:

        -   Pentecost:

        -   Corpus Christi:

        -   All Hallows: 📆‍👼 U+1F47C

        -   Christmas: 📆‍🎄 U+1F384, 📆‍🎅 U+1F385, 📆‍👼 U+1F47C, 📆‍🌠 U+1F320

    -   Jewish holiday 📆‍✡️ U+2721+FE0F / 📆‍🔯 U+1F52F

        -   Chanukka: 📆‍🕎 U+1F54E

        -   Jom Kippur:

        -   Pessach:

    -   Islamic holiday 📆‍☪️ U+262A+FE0F

This list may be long but it is not endless.

Some people might want to extend this schema to calendars other than the
international standard calendar, e.g. an Islamic or Chinese lunisolar one. That
would be limited sets in themselves and do not affect this proposal directly.

### H. Already Representable:

One might assume that it would be more culturally neutral to number the days of
the week 1…7 and months of the year 01…12, but there is actually quite some
disagreement about the details, especially regarding the start of the week.
Existing symbols are therefore preferred, though rarely used.

For people within a particular culture, there may be more intuitive or more
common emoji compounds for days or months, but none are as universal as the
ancient astronomical/astrological symbols that developed alongside the Roman /
Julian / Gregorian calendar. For instance, a contemporary US citizen might use
these compounds for the months of the year, using a familiar event in each of
them:

 

1.  📅‍🍾 / 📅‍🥂 / 📅‍🎆 / 📅‍🎇 January = New Year celebrations

2.  📅‍💘 / 📅‍💑 February = Valentine’s Day or Carnival / Mardi Gras

3.  📅‍🌱 March = Start of Spring

4.  📅‍🥚 / 📅‍🤥 April = Easter or April’s Fool Day

5.  📅‍🎺 May = Cinco de Mayo

6.  📅‍🌞 / 📅‍☀️ June = Start of Summer

7.  📅‍🇺🇸 / 📅‍📜 / 📅‍🎆 / 📅‍🎇 / 📅‍🗽 July = Independence Day

8.  📅‍🏖 August = Summer

9.  📅‍🗽 / 📅‍🇺🇸 / 📅‍✈️ / 📅‍💢 / 📅‍🍃 / 📅‍🍂 September = 9/11 Remembrance or
    Start of Fall

10. 📅‍🎃 / 📅‍👻 / 📅‍😈 / 📅‍👿 / 📅‍👹 / 📅‍👺 October = Halloween

11. 📅‍🦃 / 📅‍🏈 November = Thanksgiving

12. 📅‍🎄 / 📅‍🎅 / 📅‍👼 / 📅‍❄️ / 📅‍⛄️ / 📅‍☃️ / 📅‍🌨 December = Christmas or Start of
    Winter

 

### I. Logos, Brands etc.

Most planetary symbols have also been equated to deities since antiquity and so
are the days of the week and some months, but since only existing characters are
proposed to be used, it is not introducing any new symbol for or image of a god
or similar religious being.

### J. Transient:

Although there have been calendar reform every now and then, the international
standard calendar has been stable for centuries. The details that might be
changed (such as the date of Easter) do not affect the proposal.

References
----------

[1] \_\_\_\_\_\_: \_\_\_\_\_\_ (\_\_\_\_\_\_)

License
-------

The sample images and the sample font included in this proposal were created by
me and me alone. I hereby declare that the Unicode Consortium and its members
are granted the right to use, edit and redistribute these contents in any way
they want without restriction. Copies of the sample images and font are
available at the following address:

Screenshots were taken from Google Trends (https://www.google.com/trends/) and
Twitter (https://twitter.com).
