Relationship and Family Emojis and Character Sequences
======================================================

* http://www.unicode.org/emoji/charts/emoji-zwj-sequences.html

Existing Constituent Characters
-------------------------------

### Combinators and Variant Selectors

Name                      | Abbr. | Unicode |   | Notes
--------------------------|-------|---------|---|-------------------------------------------------
**Zero-Width Joiner**     | ZWJ   | U+200D  |   | available as `&zwj;` in HTML
**Variation Selector 15** | VS-15 | U+FE0E  |   | forces `text` representation if possible at all
**Variation Selector 16** | VS-16 | U+FE0F  |   | forces `emoji` representation if possible at all
**Emoji Modifier Fitzpatrick Type-1-2** | FP-12 | U+1F3FB | &#x1F3FB; | very light complexion, ‘white’
**Emoji Modifier Fitzpatrick Type-3**   | FP-3  | U+1F3FC | &#x1F3FC; | light complexion, ‘tan’
**Emoji Modifier Fitzpatrick Type-4**   | FP-4  | U+1F3FD | &#x1F3FD; | medium complexion, ‘olive’
**Emoji Modifier Fitzpatrick Type-5**   | FP-5  | U+1F3FE | &#x1F3FE; | dark complexion, ‘brown’
**Emoji Modifier Fitzpatrick Type-6**   | FP-6  | U+1F3FF | &#x1F3FF; | very dark complexion, ‘black’

I’m using only FP-12 and FP-6 below, just because the maximum contrast is easiest to spot, also compared to the default simpsonesque yellow skin tone. 

### Bases

Name                  | Unicode | default   | `text`            | `emoji`           | Notes
----------------------|---------|-----------|-------------------|-------------------|-------------
**Boy**               | U+1F466 | &#x1F466; | &#x1F466;&#xFE0E; | &#x1F466;&#xFE0F; | &#x1F466;&#x1F3FB; &#x1F466;&#x1F3FC; &#x1F466;&#x1F3FD; &#x1F466;&#x1F3FE; &#x1F466;&#x1F3FF;
**Girl**              | U+1F467 | &#x1F467; | &#x1F467;&#xFE0E; | &#x1F467;&#xFE0F; | &#x1F467;&#x1F3FB; &#x1F467;&#x1F3FC; &#x1F467;&#x1F3FD; &#x1F467;&#x1F3FE; &#x1F467;&#x1F3FF;
**Man**               | U+1F468 | &#x1F468; | &#x1F468;&#xFE0E; | &#x1F468;&#xFE0F; | &#x1F468;&#x1F3FB; &#x1F468;&#x1F3FC; &#x1F468;&#x1F3FD; &#x1F468;&#x1F3FE; &#x1F468;&#x1F3FF;
**Woman**             | U+1F469 | &#x1F469; | &#x1F469;&#xFE0E; | &#x1F469;&#xFE0F; | &#x1F469;&#x1F3FB; &#x1F469;&#x1F3FC; &#x1F469;&#x1F3FD; &#x1F469;&#x1F3FE; &#x1F469;&#x1F3FF;
**Old Man**           | U+1F474 | &#x1F474; | &#x1F474;&#xFE0E; | &#x1F474;&#xFE0F; | &#x1F474;&#x1F3FB; &#x1F474;&#x1F3FC; &#x1F474;&#x1F3FD; &#x1F474;&#x1F3FE; &#x1F474;&#x1F3FF;
**Old Woman**         | U+1F475 | &#x1F475; | &#x1F475;&#xFE0E; | &#x1F475;&#xFE0F; | &#x1F475;&#x1F3FB; &#x1F475;&#x1F3FC; &#x1F475;&#x1F3FD; &#x1F475;&#x1F3FE; &#x1F475;&#x1F3FF;
**Baby**              | U+1F476 | &#x1F476; | &#x1F476;&#xFE0E; | &#x1F476;&#xFE0F; | &#x1F476;&#x1F3FB; &#x1F476;&#x1F3FC; &#x1F476;&#x1F3FD; &#x1F476;&#x1F3FE; &#x1F476;&#x1F3FF;
**Heavy Black Heart** | U+2764  | &#x2764;  | &#x2764;&#xFE0E;  | &#x2764;&#xFE0F;  | usually red (not black), not to be confused with Black Heart Suit
**Kiss**              | U+1F46B | &#x1F48B; | &#x1F48B;&#xFE0E; | &#x1F48B;&#xFE0F; |

Existing Precomposed Characters and ZWJ Sequences for Pairs or Couples
----------------------------------------------------------------------

Unicode | Chars     | Sample    | Description
--------|-----------|-----------|--------------
U+1F46B | 1 + 0 = 1 | &#x1F46B; | female and male holding hands
U+1F46C | 1 + 0 = 1 | &#x1F46C; | male couple holding hands
U+1F46D | 1 + 0 = 1 | &#x1F46D; | female couple holding hands
U+1F491 | 1 + 0 = 1 | &#x1F491; | female and male in love
U+1F469+2764+1F469 | 3 + 3 = 6 | &#x1F469;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F469; | female couple in love
U+1F468+2764+1F468 | 3 + 3 = 6 | &#x1F468;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F468; | male couple in love
U+1F48F | 1 + 0 = 1 | &#x1F48F; | female and male kissing
U+1F469+2764+1F48B+1F469 | 4 + 4 = 8 | &#x1F469;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F48B;&zwj;&#x1F469; | female couple kissing
U+1F468+2764+1F48B+1F468 | 4 + 4 = 8 | &#x1F468;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F48B;&zwj;&#x1F468; | male couple kissing

Composition Variants of Existing ZWJ Sequences for Pairs or Couples
-------------------------------------------------------------------

Unicode Bases            | Chars     | Sample                               | Description
-------------------------|-----------|--------------------------------------|-------------
U+1F469+2764+1F469       | 3 + 2 = 5 | &#x1F469;&zwj;&#x2764;&zwj;&#x1F469; | female couple in love; without VS16
U+1F468+2764+1F468       | 3 + 2 = 5 | &#x1F468;&zwj;&#x2764;&zwj;&#x1F468; | male couple in love; without VS16
U+1F469+2764+1F468       | 3 + 3 = 6 | &#x1F469;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F468; | female and male in love; decomposed U+1F491
U+1F468+2764+1F469       | 3 + 3 = 6 | &#x1F468;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F469; | male and female in love; reversed U+1F491
U+1F469+2764+1F468       | 3 + 2 = 5 | &#x1F469;&zwj;&#x2764;&zwj;&#x1F468; | female and male in love; decomposed U+1F491 without VS16
U+1F468+2764+1F469       | 3 + 2 = 5 | &#x1F468;&zwj;&#x2764;&zwj;&#x1F469; | male and female in love; reversed U+1F491 without VS16
U+1F469+2764+1F48B+1F468 | 4 + 4 = 8 | &#x1F469;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F48B;&zwj;&#x1F468; | female and male kissing; decomposed U+1F48F
U+1F468+2764+1F48B+1F469 | 4 + 4 = 8 | &#x1F468;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F48B;&zwj;&#x1F469; | male and female kissing; reversed U+1F48F
U+1F469+2764+1F48B+1F468 | 4 + 3 = 7 | &#x1F469;&zwj;&#x2764;&zwj;&#x1F48B;&zwj;&#x1F468; | female and male kissing; decomposed U+1F48F without VS16
U+1F468+2764+1F48B+1F469 | 4 + 3 = 7 | &#x1F468;&zwj;&#x2764;&zwj;&#x1F48B;&zwj;&#x1F469; | male and female kissing; reversed U+1F48F without VS16
U+1F469+1F48B+1F468      | 3 + 2 = 5 | &#x1F469;&zwj;&#x1F48B;&zwj;&#x1F468; | female and male kissing without heart
U+1F468+1F48B+1F469      | 3 + 2 = 5 | &#x1F468;&zwj;&#x1F48B;&zwj;&#x1F469; | male and female kissing without heart
U+1F469+1F48B+1F469      | 3 + 2 = 5 | &#x1F469;&zwj;&#x1F48B;&zwj;&#x1F469; | female couple kissing without heart
U+1F468+1F48B+1F468      | 3 + 2 = 5 | &#x1F468;&zwj;&#x1F48B;&zwj;&#x1F468; | male couple kissing without heart

Complexion Variants of Existing Characters and ZWJ Sequences for Pairs or Couples
---------------------------------------------------------------------------------

Unicode Bases            | Chars     | Sample                               | Description
-------------------------|-----------|--------------------------------------|-------------
U+1F46B                  | 1 + 1 = 2 | &#x1F46B;&#x1F3FF; | dark female and male holding hands
U+1F46C                  | 1 + 1 = 2 | &#x1F46C;&#x1F3FF; | dark male couple holding hands
U+1F46D                  | 1 + 1 = 2 | &#x1F46D;&#x1F3FF; | dark female couple holding hands
U+1F491                  | 1 + 1 = 2 | &#x1F491;&#x1F3FF; | dark female and male in love
U+1F48F                  | 1 + 1 = 2 | &#x1F48F;&#x1F3FF; | dark female and male kissing
U+1F469+2764+1F468       | 3 + 5 = 8 | &#x1F469;&#x1F3FB;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F468;&#x1F3FF; | light female and dark male in love
U+1F468+2764+1F469       | 3 + 5 = 8 | &#x1F468;&#x1F3FB;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F469;&#x1F3FF; | light male and dark female in love
U+1F469+2764+1F469       | 3 + 5 = 8 | &#x1F469;&#x1F3FB;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F469;&#x1F3FF; | light female and dark female in love
U+1F468+2764+1F468       | 3 + 5 = 8 | &#x1F468;&#x1F3FB;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F468;&#x1F3FF; | light male and dark male in love
U+1F469+2764+1F48B+1F468 | 4 + 6 = 10| &#x1F469;&#x1F3FB;&zwj;&#x2764;&#xFE0F;&zwj;&#x1F48B;&zwj;&#x1F468;&#x1F3FF; | light female and dark male kissing; decomposed U+1F48F

Existing Precomposed Characters and ZWJ Sequences for Families and Groups
-------------------------------------------------------------------------

### Three-Member Families

Unicode Bases       | Description                             | Sample
--------------------|-----------------------------------------|--------------------------------------
U+1F46A             | father, mother, child (son)             | &#x1F46A;
U+1F468+1F469+1F466 | father, mother, son; decomposed U+1F46A | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F466;
U+1F468+1F469+1F467 | father, mother, son                     | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F467;
U+1F468+1F468+1F466 | father, father, son                     | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F466;
U+1F468+1F468+1F467 | father, father, daughter                | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F467;
U+1F469+1F469+1F466 | mother, mother, son                     | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F466;
U+1F469+1F469+1F467 | mother, mother, daughter                | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F467;

### Four People

Unicode Bases             | Description                        | Sample
--------------------------|------------------------------------|-----------------------------------------------------
U+1F468+1F469+1F467+1F466 | father, mother, daughter, son      | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F467;&zwj;&#x1F466;
U+1F468+1F469+1F466+1F466 | father, mother, son, son           | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F466;&zwj;&#x1F466;
U+1F468+1F469+1F467+1F467 | father, mother, daughter, daughter | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F467;&zwj;&#x1F467;
U+1F468+1F468+1F467+1F466 | father, father, daughter, son      | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F467;&zwj;&#x1F466;
U+1F468+1F468+1F466+1F466 | father, father, son, son           | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F466;&zwj;&#x1F466;
U+1F468+1F468+1F467+1F467 | father, father, daughter, daughter | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F467;&zwj;&#x1F467;
U+1F469+1F469+1F467+1F466 | mother, mother, daughter, son      | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F467;&zwj;&#x1F466;
U+1F469+1F469+1F466+1F466 | mother, mother, son, son           | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F466;&zwj;&#x1F466;
U+1F469+1F469+1F467+1F467 | mother, mother, daughter, daughter | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F467;&zwj;&#x1F467;

Proposed
========

## Two People

### Couple

Unicode Bases | Description       | Sample
--------------|-------------------|-------------------------
U+1F468+1F469 | male and female   | &#x1F468;&zwj;&#x1F469;
U+1F469+1F468 | female and male   | &#x1F469;&zwj;&#x1F468;
U+1F468+1F468 | male and male     | &#x1F468;&zwj;&#x1F468;
U+1F469+1F469 | female and female | &#x1F469;&zwj;&#x1F469;

### Parent and Child

Unicode Bases | Description         | Sample
--------------|---------------------|------------------------
U+1F468+1F466 | father and son      | &#x1F468;&zwj;&#x1F466;
U+1F469+1F466 | mother and son      | &#x1F469;&zwj;&#x1F466;
U+1F468+1F467 | father and daughter | &#x1F468;&zwj;&#x1F467;
U+1F469+1F467 | mother and daughter | &#x1F469;&zwj;&#x1F467;
U+1F468+1F476 | father and baby     | &#x1F468;&zwj;&#x1F476;
U+1F469+1F476 | mother and baby     | &#x1F469;&zwj;&#x1F476;

### Grandparent and Grandchild

Unicode Bases | Description                   | Sample
--------------|-------------------------------|------------------------
U+1F474+1F466 | grandfather and grandson      | &#x1F474;&zwj;&#x1F466;
U+1F475+1F466 | grandmother and grandson      | &#x1F475;&zwj;&#x1F466;
U+1F474+1F467 | grandfather and granddaughter | &#x1F474;&zwj;&#x1F467;
U+1F475+1F467 | grandmother and granddaughter | &#x1F475;&zwj;&#x1F467;
U+1F474+1F476 | grandfather and baby          | &#x1F474;&zwj;&#x1F476;
U+1F475+1F476 | grandmother and baby          | &#x1F475;&zwj;&#x1F476;

### Grandparent and Child

Unicode Bases | Description              | Sample
--------------|--------------------------|------------------------
U+1F474+1F468 | grandfather and son      | &#x1F474;&zwj;&#x1F468;
U+1F475+1F468 | grandmother and son      | &#x1F475;&zwj;&#x1F468;
U+1F474+1F469 | grandfather and daughter | &#x1F474;&zwj;&#x1F469;
U+1F475+1F469 | grandmother and daughter | &#x1F475;&zwj;&#x1F469;

### Siblings

Unicode Bases | Description         | Sample
--------------|---------------------|-------------------------
U+1F466+1F466 | brother and brother | &#x1F466;&zwj;&#x1F466;
U+1F466+1F467 | brother and sister  | &#x1F466;&zwj;&#x1F467;
U+1F467+1F466 | sister and brother  | &#x1F467;&zwj;&#x1F466;
U+1F467+1F467 | sister and sister   | &#x1F467;&zwj;&#x1F467;
U+1F466+1F476 | brother and baby    | &#x1F466;&zwj;&#x1F476;
U+1F467+1F476 | sister and baby     | &#x1F467;&zwj;&#x1F476;
U+1F476+1F466 | baby and brother    | &#x1F476;&zwj;&#x1F466;
U+1F476+1F467 | baby and sister     | &#x1F476;&zwj;&#x1F467;
U+1F476+1F476 | baby and baby       | &#x1F476;&zwj;&#x1F476;

## Three People

### Parent and Children

Unicode Bases       | Description                | Sample
--------------------|----------------------------|--------------------------------------
U+1F468+1F466+1F466 | father, son, son           | &#x1F468;&zwj;&#x1F466;&zwj;&#x1F466;
U+1F468+1F467+1F467 | father, daughter, daughter | &#x1F468;&zwj;&#x1F467;&zwj;&#x1F467;
U+1F468+1F466+1F467 | father, son, daughter      | &#x1F468;&zwj;&#x1F466;&zwj;&#x1F467;
U+1F468+1F467+1F466 | father, daughter, son      | &#x1F468;&zwj;&#x1F467;&zwj;&#x1F466;
U+1F468+1F476+1F466 | father, baby, son          | &#x1F468;&zwj;&#x1F476;&zwj;&#x1F466;
U+1F468+1F476+1F467 | father, baby, daughter     | &#x1F468;&zwj;&#x1F476;&zwj;&#x1F467;
U+1F468+1F467+1F476 | father, daughter, baby     | &#x1F468;&zwj;&#x1F467;&zwj;&#x1F476;
U+1F468+1F466+1F476 | father, son, baby          | &#x1F468;&zwj;&#x1F466;&zwj;&#x1F476;
U+1F468+1F476+1F476 | father, baby, baby         | &#x1F468;&zwj;&#x1F476;&zwj;&#x1F476;
U+1F469+1F466+1F466 | mother, son, son           | &#x1F469;&zwj;&#x1F466;&zwj;&#x1F466;
U+1F469+1F467+1F467 | mother, daughter, daughter | &#x1F469;&zwj;&#x1F467;&zwj;&#x1F467;
U+1F469+1F466+1F467 | mother, son, daughter      | &#x1F469;&zwj;&#x1F466;&zwj;&#x1F467;
U+1F469+1F467+1F466 | mother, daughter, son      | &#x1F469;&zwj;&#x1F467;&zwj;&#x1F466;
U+1F469+1F476+1F466 | mother, baby, son          | &#x1F469;&zwj;&#x1F476;&zwj;&#x1F466;
U+1F469+1F476+1F467 | mother, baby, daughter     | &#x1F469;&zwj;&#x1F476;&zwj;&#x1F467;
U+1F469+1F467+1F476 | mother, daughter, baby     | &#x1F469;&zwj;&#x1F467;&zwj;&#x1F476;
U+1F469+1F466+1F476 | mother, son, baby          | &#x1F469;&zwj;&#x1F466;&zwj;&#x1F476;
U+1F469+1F476+1F476 | mother, baby, baby         | &#x1F469;&zwj;&#x1F476;&zwj;&#x1F476;

### Parents and Baby

Unicode Bases       | Description          | Sample
--------------------|----------------------|--------------------------------------
U+1F468+1F469+1F476 | father, mother, baby | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F476;
U+1F469+1F468+1F476 | mother, father, baby | &#x1F469;&zwj;&#x1F468;&zwj;&#x1F476;
U+1F468+1F468+1F476 | mother, mother, baby | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F476;
U+1F469+1F469+1F476 | father, father, baby | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F476;

### Grandparents and Grandchild

### Grandparents and Child

### Three Generations

### Siblings

## Four People

Just other possible sequence orders.

Unicode Bases             | Description      | Sample
--------------------------|------------------|----------------------------------------------
U+1F469+1F468+1F467+1F466 |  | &#x1F469;&zwj;&#x1F468;&zwj;&#x1F467;&zwj;&#x1F466;
U+1F469+1F468+1F466+1F466 |  | &#x1F469;&zwj;&#x1F468;&zwj;&#x1F466;&zwj;&#x1F466; 
U+1F469+1F468+1F467+1F467 |  | &#x1F469;&zwj;&#x1F468;&zwj;&#x1F467;&zwj;&#x1F467;
U+1F468+1F469+1F466+1F467 |  | &#x1F468;&zwj;&#x1F469;&zwj;&#x1F466;&zwj;&#x1F467;
U+1F468+1F468+1F466+1F467 |  | &#x1F468;&zwj;&#x1F468;&zwj;&#x1F466;&zwj;&#x1F467;
U+1F469+1F469+1F466+1F467 |  | &#x1F469;&zwj;&#x1F469;&zwj;&#x1F466;&zwj;&#x1F467;

## Five People
