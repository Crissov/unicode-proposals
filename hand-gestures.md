Proposal to Add Several Hand and Finger Emojis to the Unicode Standard
======================================================

- **Author:** Christoph Päper
- **Mail:** christoph.paeper@crissov.de
- **Submitted:** 2016-09-[__]

Introduction
------------

I hereby request the addition of [______] emojis to the Unicode Standard. ___ of them are entirely new characters, ___ are existing character without the `Emoji` property set. Rationals, glyph examples, character properties as well as discussion of inclusion and exclusion factors are included on the following pages.
As per emoji submission guidelines (http://www.unicode.org/emoji/selection.html#submission) this document does not include the character proposal form.

### Evaluating

Besides thumbs up and down for approval and rejection, the thumb spread from the fist and pointing to the side is frequently used for a indeterminate or neutral decision. The hand and its orientation does not matter.

### Pointing

The index finger is used almost universally to point out a direction. Alternatively, the thumb is used in some cases or additional adjacent fingers together with the index finger, including the complete open hand.

### Counting

Most, but by far not all, manual counting systems count to *five* on a single hand by raising the appropriate number of fingers. There are cultural differences on which fingers are used and how the hand is normally oriented, i.e. whether the palm is facing the reader. Since both hands are used for counting to *ten* in these systems, both orientations should be encoded either at separate code points or by using a new kind of emoji sequence employing ZWJ.

1. 3 main variants:
	1. thumb (👍)
	2. index finger (☝️👆)
	3. pinky only
2. 3 main variants:
	1. thumb and index finger
	2. index and middle finger (Victory sign ✌️ = air quotes)
	3. pinky and ring finger
3. 3 main variants (notable pop culture reference: *Inglorious Basterds*):
	1. thumb, index and middle finger (see [L2/16-071](http://www.unicode.org/L2/L2016/16071-three-fingers.pdf) for non-counting use)
	2. index, middle and ring finger
	3. pinky, ring and middle finger
4. 2 main variants:
	1. all but pinky
	2. all but thumb
5. 3 main variants:
	1. all fingers splayed 🖐
	2. all fingers hold together, either openly ✋ or as a fist ✊

A closed fist can either mean 0, 5 or 10. A zero value is also often gestured by the thumb forming a ring with one or more fingers, similar to the OK gesture 👌.

Counting finger links by tipping them with the thumb, one can count to 12 on a single hand. The OK gesture 👌 would be 1.

Then there’s 4-bit (0…15) and 8-bit (0…255) counting where the thumb(s) hold down the ‘0’ fingers and the ‘1’ fingers are raised. All kinds of endianness are possible at one’s personal preference. These 16 emojis per hand would accordingly cover all hand gestures with raised fingers except for the ones where the thumb is also showing, e.g. the rather popular ASL ‘ILY’ (*I love you*) gesture with only ring and middle finger bend and thus distinct from the sign of the horns 🤘. 

All raised fingers are canonically pointing up. Some otherwise identical conventional hand gestures may rely on a specific orientation (vertical or horizontal; up, down, right or left; palm facing reader or not; left or right hand), e.g. the universal sign for Hand Gun is thumb and index finger raised with the thumb instead of the index finger pointing up.

### Spelling

There are several finger alphabets for different scripts in use worldwide. For the roman script alone, there are at least __ ones known, many of which share symbols for most letters, though.

### Gesturing

Many hand gestures have unambiguous and well known meaning among a single (sub-)culture, but may conflict across cultures and also with proper sign languages. Some of them have already been encoded, even ones that are considered obscene in many places (e.g. 🖕👌✌️🖖✊). There are more worthy of inclusion: *pistol*, *loser*

### Signing

Proper sign languages, predominantly used in the deaf community and with babies, are outside the scope of this proposal. See Sign Writing, which is being proposed for inclusion in Unicode, and similar notational conventions instead.

### Playing

There are many games like Roshambo that are based on finger gestures. Unicode annotation explicitly mentions *rock* ✊, *paper* ✋ and *scissors* ✌️ already. Locally popular traditional variants need one or more of these gestures:

- *paper* ✋: may be required to have the palm facing down, splaying may be acceptable 🖐
- *water*: open palm facing up, like a giving gesture
- *scissors* ✌️: may be required to have the raised fingers pointing sideways, the Vulcan greeting 🖖 may be an acceptable alternative
- *bird, lizard, snake* are similar with fingers forming a head pointing sideways, palm facing down
	- *bird*: tips of all fingers and thumb touching each other, forming a head with beak
	- *lizard*: tips of thumb, index and middle finger touching, forming a head
	- *snake*: fingers held next to each other, thumb touches the base  or middle link of index and possibly ring finger
- the Japanese *snake*, however, is just a raised index finger ☝️/👆, 
- *slug* (also Japanese): extended thumb 👍, pointing sideways, like hitchhiker’s thumb
- *frog* (also Japanese): extended pinky, pointing sideways
- *well/fountain*: similar to OK gesture 👌, but the ring formed of thumb and index finger faces up and the fingers are hold together, i.e. half-closed between ✊ and ✋
- *bull, fox, dog*: all similar to the devil sign 🤘 with pinky and index finger raised
	* the *bull* faces sidewards and often has the tip of the thumb touching the nails of ring and middle finger touching, so 
	* the *fox* is like the bull except that the tips of thumb, ring and middle finger are touching, forming a muzzle/snout; sometimes known as a *dog* instead
- *wolf*: thumb and index finger form a mouth, ring finger is bend to form an eye, pinky is raised to make an ear and the middle finger is either hold with the index or the ring finger; sometimes also known as a *dog* instead

Glyph and Design
----------------

### Hands pointing up like ☝️ U+261D and 👆 U+1F446
U+ | Sample | Description
------|---|----------
1F59E | 🖞 | Usually thumb on the left facing reader (own right, other’s left)
1F5A0 | 🖠 | Ambiguous, thumb on the left, probably opposite hand of U+1F59E
1F5A2 | 🖢 | Ambiguous, thumb on the left, probably opposite hand of U+1F446

The emoji U+261D has the thumb on the right, palm facing the reader (own left, other’s right hand), U+1F446 the same hand turned. Some non-emoji fonts instead use the opposite hand for U+261D.

### Hands pointing down like 👇 U+1F447
U+ | Sample | Description
------|---|----------
 261F | ☟ | Often thumb on the right, palm facing reader (own left, other’s right), but not at all consistent across fonts
1F597 | 🖗 | Usually thumb on the left, palm facing reader (own right, other’s left)
1F59F | 🖟 | Usually thumb on the right facing reader (own right, other’s left)
1F5A1 | 🖡 | Ambiguous, thumb on the right, probably opposite hand of U+1F59F
1F5A3 | 🖣 | Ambiguous, thumb on the right, probably opposite hand of U+261F

The emoji U+1F447 has the thumb on the right, palm facing away from the reader (own left, other’s right hand).

### Hands pointing left like 👈 U+1F448
U+ | Sample | Description
------|---|----------
 261A | ☚ | Ambiguous, probably opposite hand of U+261C
 261C | ☜ | Usually thumb on top, palm facing reader (own right, other’s left)
1F598 | 🖘 | Usually thumb on bottom facing reader (own right, other’s left) 
1F59A | 🖚 | Ambiguous, thumb on bottom, probably opposite hand of U+1F598 
1F59C | 🖜 | Ambiguous, thumb on top, probably opposite hand or side of U+261C 

The emoji U+1F448 has the thumb on top, palm facing away from the reader (own left, other’s right hand).

### Hands pointing right like 👉 U+1F449
U+ | Sample | Description
------|---|----------
 261B | ☛ | Ambiguous, probably opposite hand of U+261E
 261E | ☞ | Usually thumb on top, palm facing reader (own left, other’s right)
1F599 | 🖙 | Usually thumb on bottom facing reader (own left, other’s right) 
1F59B | 🖛 | Ambiguous, thumb on bottom, probably opposite hand of U+1F599
1F59D | 🖝 | Ambiguous, thumb on top, probably opposite hand or side of U+261E 

The emoji U+1F449 has the thumb on top, palm facing away from the reader (own right, other’s left hand).

### Other hand gestures with alternatives
Non-Emoji | Sample | Sample | Emoji
------|---|---|------
1F594 | 🖔 | ✌️ | 270C
1F58E | 🖎 | ✍️ | 270D
1F58F | 🖏 | 👌 | 1F44C
1F592 | 🖒 | 👍 | 1F44D
1F593 | 🖓 | 👎 | 1F44E
1F591 | 🖑 | 🖐 | 1F590

All of the existing emojis are using one’s own right hand or other’s left hand in the reference glyphs and most fonts. (Emoji One currently uses the opposite hand for thumbs up, as does Facebook’s infamous “like” button.) The non-emoji characters use the same hand, but turned except for the writing hands U+270D (own right) and U+1F58E (own left). Many emoji fonts have a glyph for U+1F44C that actually better resembles the reference glyph of U+1F58F.

### Left hand versus right hand

Right-handedness is the major preference in all the world’s populations. It’s therefore not discriminating to use it as the default hand (from the reader’s perspective) for emojis, although the emojis pointing left and down are already using the opposite hand. In most cases, we could therefore associate White hand characters with one’s own right hand and Black ones with one’s own left hand.

### Gloves, Rings

Description

![Sample Picture](.png)

Character Properties
--------------------

The preferred name of the character is “[______]”. The new ones should either be added to the Supplemental Symbols and Pictographs block near other gesture emojis (at U+1F918–E currently) or in a new block in the SMP designated specifically to finger spelling and counting. Properties of the manual gesture emojis should be identical to those of other emoji.

* General Category: Other Symbol (So)
* Canonical Combining Class: 0
* Bidirectional Class: Other Neutral (ON)
* Bidi Mirrored: No

No case-mapping is required. The character does not decompose in any way. It is not whitespace nor a control character. It has no numeric value. All of the proposed characters do make use of emoji modifiers. They have emoji presentation by default. In collation order they should be sorted near each other and other hand and finger emojis and preferably by number of fingers raised. They should definitely be part of the [______] category.

Factors for Inclusion
---------------------

### A. Compatibility:

There are no known legacy character sets containing [______].

### B. Expected Usage Level: 

I have included several charts supplied by Google Trends showing the frequency of searches for “[______]” in comparison to other emoji. 

Google search for the term “[______]” returns [______] results, which is more than for [______].

### C. Image distinctiveness: 

...

### D. Completeness:

...

### E. Frequently Requested:

...

Factors for Exclusion
---------------------

### F. Overly Specific:

...

### G. Open-ended:

A block of 32 rows of 16 characters each, i.e. 512 code points would be required to cover raised fingers in all combinations and orientations (up, down, right or left; palm facing reader or not; left/black or right/white hand). Some of the code points would be left empty because they are already encoded elsewhere. This would not include more complex gestures like the OK sign or the ones for duodecimal counting, but it would cover controversial ones like “The Shocker” (raised pinky, middle and index finger) in all orientations.

### H. Already Representable:

A possible alternative to encoding all finger combinations would be to use ZWJ sequences of emojis with a single raised/extended finger each. That means 5 per hand, direction and orientation, which could also be coded as separate characters, so a minimum of just 13 characters would be required to code the same 512 variants, and some could even reuse existing ones: Thumb Raised 👍👎, Index Finger Raised ☝️👆, Middle Finger Raised 🖕, Ring Finger Raised, Pinky Raised; Palm Facing Reader ✋🖐☝️, Palm Facing Away 👆; Left/Black Hand, Right/White Hand; Pointing Up 👆☝️⬆️, Pointing Right 👉➡️, Pointing Down 👇⬇️, Pointing Left 👈⬅️. The Pistol sign could be 👍‍👆‍↔️ then, for instance, and a neutral, sideways thumb could be 👍‍↔️ (thumb direction), 👍‍⬆️ (fingers direction) or 👍‍👎 (semantic).

### I. Logos, Brands etc.

...

### J. Transient:

...

References
----------

[1] ______: ______ (______)

License
-------

The sample images and the sample font included in this proposal were created by me and me alone. I hereby declare that the Unicode Consortium and its members are granted the right to use, edit and redistribute these contents in any way they want without restriction.
Copies of the sample images and font are available at the following address:

Screenshots were taken from Google Trends (https://www.google.com/trends/) and Twitter (https://twitter.com).
