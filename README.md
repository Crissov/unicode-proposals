Unicode Proposals
=================

This repository collects (draft) proposals for new emojis and other Unicode characters.
The collection also contains templates, related sources, references and other helpful material related to the Unicode standard.

Emoji
-----

A [new emoji](http://unicode.org/emoji/selection.html) can be made in three different ways: 

* If rather original, it may require the assignment of an individual codepoint, usually in the upper areas of the Supplementary Multilingual Plane (SMP), U+1F9*xy*. This usually happens once a year with a new point release of the Unicode Technical Standard. The deadline for proposals for Unicode 12.0 to be released in early 2019 is set to 15 March 2018.
* An existing character can be repurposed by adding the `Emoji` property once and using Variation Selector 16 &lsquo;VS-16&rsquo; U+FE0F henceafter. These are not documented ditrectly in the Unicode Standard (TUS), but in [Unicode Technical Standard #51 (UTS#51)](http://unicode.org/reports/tr51/) The deadline for such proposals is usually later than the one for new codepoints. The release date of a new major version of UTS#51 is always synchronized with TUS, but there *may* be additional ones.
* There are several types of canonic character sequences which can be registered. The most import type are multiple emojis forced to form a ligature by a Zero-Width Joiner (ZWJ) U+200D between components. Country flags use pairs of Regional Indicator Symbols and are added automatically if ISO 3166-1 changes, whereas their subdivisions are encoded with Tag Characters on a Waving Black Flag base using ISO 3166-2 codes. Additional Emoji Tag Sequences may be proposed.

Contribution
------------

You can contribute to an [existing issue](https://github.com/Crissov/unicode-proposals/issues) (e.g. for [animals](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Aanimal), [flags](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Aflag), [emoticons](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Aemoticon) or [food](https://github.com/Crissov/unicode-proposals/issues?q=is%3Aissue+is%3Aopen+label%3Afood)) or [raise a new one](https://github.com/Crissov/unicode-proposals/issues/new) to **wish for additional proposals**. 
The thing most direly needed in emoji proposals are example graphics that ideally can be used freely (even commercially) and without strong attribution requirements.

Your help is always appreciated, but &ndash; for emojis &ndash; please read about the [Unicode Proposal Process](http://unicode.org/emoji/selection.html) first. (Emojione has published a [synopsis](https://www.emojione.com/blog/so-you-want-to-propose-an-emoji-to-unicode-heres-how) that&rsquo;s probably easier and quicker to read.)

You could also take your ideas and contributions to [Emoji Nation](http://www.emojination.org) who have helped to push through the majority of recent successful emoji proposals.

Drafted and Submitted Proposals
-------------------------------

See branches and pull requests for more work-in-progress items.

* [Fourth wise monkey: _Do-No-Evil Monkey_](fourth-monkey.md)
* [Make emoji flags for non-countries optional](dependent-regions.md)

* [Markdown **Template** for an Emoji Proposal](proposal.template.md)

Older white papers
------------------

Similar discussions are now found in the repository issues on Github.

* [New ZWJ sequences for choosing the primary color of emojis](color-selection.md)
* [Relationship and Family Emojis and Character Sequences](relationships.md)
* [More ZWJ sequences for emoji professions](professions.md)
* [Some ZWJ sequences and some unique emojis to replace current metaphors and line art](sexual-activities.md)
* [Conventional emoji “short names” (`:short_codes:`) as HTML named entities](emoji-entities.md)
* [Evidence of raunchy emoji metaphors in sexting etc.](references/sexting.md)
* [Emoji ligatures instead of Tag sequences for subregion flags](iso_3166-2-emoji.md)
