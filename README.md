# Mellifera Deseret

This Deseret alphabet font is derived from [Gentium Plus](https://github.com/silnrsi/font-gentium/), Victor Gaultney's excellent cosmopolitan typeface family.

v0.1 (~2022.2.26) ([OTF file](./MelliferaDeseretMaster.otf))

![image](https://user-images.githubusercontent.com/57601680/155855283-08b2bb7f-d982-4eb1-91c1-3a70d509f7db.png)

---

For copyright and licensing information - including any Reserved Font Names - see [OFL.txt](OFL.txt).

For practical information about using, modifying and redistributing this font see [OFL-FAQ.txt](OFL-FAQ.txt).

---

##  Motivation

The Deseret alphabet was produced as an English-language spelling reform from 1847 and used somewhat actively from 1854 until 1869.  The 40-letter basic Deseret alphabet occupies U+10400–U+1044f.

![](https://upload.wikimedia.org/wikipedia/commons/9/96/1860_Utah_%2410_gold_piece.jpeg)

Most Deseret typefaces are either sans-serif (Noto Sans Deseret, TuBeeRound) or heavy slab-serif types (QueenBee, Times Bee).  As Deseret letterforms are not terribly different from other Gentium alphabets (Cyrillic, Latin, and Greek), their addition as a sister typeface to Gentium is a natural extension of the SIL font's mandate and will make for an easy-reading serif implementation for running copy.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Information_wants_to_be_free_in_five_different_modern_computer_fonts_for_the_Deseret_alphabet.svg/1920px-Information_wants_to_be_free_in_five_different_modern_computer_fonts_for_the_Deseret_alphabet.svg.png)


##  Letterforms

Deseret glyphs are Latin-like, and in a few instances overlap directly with coincident Latin letterforms, such as Deseret 𐐛 Eth with Latin L.  In order to distinguish letterforms, I will always refer to a Deseret alphabet character with its symbol and name, e.g. 𐐃 Long Ah or 𐐄 Long O.

As with another type-first alphabet, Cherokee, Deseret possesses several features that would likely have been eroded with a long period of handwriting first.  For instance, Deseret frequently requires rightward serifs, which are a bit awkward and heavy in serif type.  Deseret was apparently visually conceived as being written with a horizontally-held pen, leading to difficulties in working with a conventionally-held (45°) pen and the serifs and letterforms.  (For instance, the slash in 𐐆 Short I feels as if it runs the wrong direction from upper left to lower right; the letter pairs 𐐝 Es/𐐠 Zhee and 𐐤 En/𐐥 Eng are difficult to distinguish from each other.)

![](https://pbs.twimg.com/media/FH-n28cXMAMbnih?format=png&name=900x900)

- [Joshua Erickson, “Serif Bee Font Page”](http://www.chem.ucla.edu/~jericks/Serif.html)
- [_The Book of Mormon_ typeset in slab-serif Deseret alphabet](https://archive.org/details/bookofmormdeseretalpha00)

Here is a comparison of "Twinkle, Twinkle, Little Star" in short samples from five other fonts and my current work in Mellifera:

![Screenshot_20220102_093737](https://user-images.githubusercontent.com/57601680/147880867-7ec8c8f0-c73f-46ab-982a-72608d514758.png)

Running text is much easier on the eyes in Mellifera; the same text as running copy.  (Note that I have not done any serious work on kerning yet, so please forgive the uneven spacing.)

![Screenshot_20220102_095043](https://user-images.githubusercontent.com/57601680/147881266-9d8e2171-2f7a-4631-8c6d-b97fe3f012fd.png)

Similar to the Latin alphabet, structurally-related letterforms are not phonetically related to each other.  Deseret letterforms can be divided into the following typographic series:

#### Series I:

- 𐐀 Long I
- 𐐁 Long E
- 𐐂 Long A
- 𐐍 Ow
- 𐐒 Bee
- 𐐔 Dee
- 𐐚 Vee
- 𐐞 Zee
- 𐐟 Esh

#### Series II:

- 𐐃 Long Ah
- 𐐄 Long O
- 𐐅 Long Oo

#### Series III:

- 𐐆 Short I
- 𐐇 Short E
- 𐐈 Short A
- 𐐉 Short Ah
- 𐐊 Short O
- 𐐑 Pee
- 𐐛 Eth

#### Series IV:

- 𐐋 Short Oo
- 𐐓 Tee
- 𐐙 Ef
- 𐐢 El
- 𐐌 Ay
- 𐐐 H
- 𐐡 Er

#### Series V:

- 𐐎 Wu
- 𐐗 Kay
- 𐐘 Gay

#### Series VI:

- 𐐏 Yee
- 𐐜 Thee
- 𐐖 Jee

#### Series VII:

- 𐐕 Chee
- 𐐣 Em

#### Series VIII:

- 𐐝 Es
- 𐐠 Zhee

#### Series IX:

- 𐐤 En
- 𐐥 Eng

Letterforms within a series must be sufficiently distinct to allow immediate visual discrimination in reading running text.

The most common modifier is a sort of hook or loop at the top of some glyphs.  Unfortunately, due to the relative clutter of some letterforms (notably 𐐍 Ow), it is impossible to adopt a single glyph form as the loop modifier.

Another common modifier is the rightwards vertical, treated as a capital I in many typefaces.  However, this makes it necessary to clearly distinguish the following three letters from each other:

- 𐐁 Long E
- 𐐂 Long A
- 𐐒 Bee

(We set aside for now ligature glyphs and their variant forms.)


##  Font Design

### Composing Mellifera from Gentium

As Gentium began life with calligraphic letterforms, I have adapted the Deseret letters in a way as compatible as I think possible.  For instance, consider the letters 𐐁 Long E and 𐐚 Vee; since Gentium has a properly-formed analogue in both U+0510 Cyrillic Capital Letter Reversed Ze and U+0190 Latin Capital Letter Open E, adjusted for the proper shape (rather than horizontally flipped), I can adopt either directly as 𐐁 Long E.  In this case, because Deseret tends to be heavy in letterforms already, I adopt the lighter of the two, U+0190, which does not include the lower serif.  For 𐐚 Vee, I adapt the U+a7ab Latin Capital Letter Reversed Open E which has the corresponding form.

Continuing in this way, I have hewed to using existing Gentium letterforms in producing Deseret letters.  U+0277 Latin Small Letter Closed Omega, U+029a Latin Small Letter Closed Open E, and U+025e Latin Small Letter Closed Reversed Open E have been employed for some of the medium-complexity Deseret glyphs.

### Resolving Series

_The following entries are given as DESERET Sound (majuscule source/miniscule source)._

#### Series I:

Deseret clearly conceives of a vertical line as sufficient to distinguish one letter from another, e.g. 𐐂 Long A/𐐒 Bee.  This leaves us pleasant room to work with ascenders and descenders in the miniscules.

- 𐐀 Long I (from U+03d1 Greek Theta Symbol/from U+029a Latin Small Letter Closed Open E plus U+044d Cyrillic Small Letter E)
- 𐐞 Zee (from U+0431 Cyrillic Small Letter Be plus U+0190 Latin Capital Letter Open E/from U+0255 Latin Small Letter C with Curl)
- 𐐁 Long E (from U+0190 Latin Capital Letter Open E/from U+025b Latin Small Letter Open E)
- 𐐚 Vee (from U+a7ab Latin Capital Letter Reversed Open E/from U+025c Latin Small Letter Reversed Open E)
- 𐐂 Long A (from U+0190 Latin Capital Letter Open E/from U+029a Latin Small Letter Closed Open E)
- 𐐍 Ow (ditto plus U+1db9 Modifier Letter Small V with Hook)
- 𐐒 Bee (from U+0190 Latin Capital Letter Open E plus U+042f Cyrillic Capital Letter Ya/from U+029a Latin Small Letter Closed Open E plus ASCII l)
- 𐐔 Dee (from ASCII C plus U+042f Cyrillic Capital Letter Ya plus U+1db9 Modifier Letter Small V with Hook/from U+???? Latin Small A Single Story)
- 𐐟 Esh (from ASCII I plus U+042d Cyrillic Capital Letter E/from ASCII l plus U+???? Latin Small D SC)

#### Series II:

These are primarily architected around the structure of the letter 𐐄.

- 𐐄 Long O (from ASCII O/from ASCII o)
- 𐐃 Long Ah (ditto plus U+1db9 Modifier Letter Small V with Hook)
- 𐐅 Long Oo (ditto plus Latin Small Capital I)

#### Series III:

Although e.g. 𐐈 Short A is always vertical at the right-hand side in previous fonts, in handwriting it assumes a form much like a checkmark, motivating the tilted version here (and making for a less cluttered 𐐉 Short Ah).

- 𐐆 Short I (from ASCII I/from ASCII I)
- 𐐇 Short E (from U+042d Cyrillic Capital Letter E plus ASCII I/from ASCII l plus U+2202 Partial Differential)
- 𐐈 Short A (from ASCII v plus ASCII V/from U+2c71 Latin Small Letter V with Right Hook)
- 𐐉 Short Ah (from ASCII w plus ASCII W/from U+2c73 Latin Small Letter W with Hook)
- 𐐊 Short O (from ASCII I plus U+042d Cyrillic Capital Letter E/from ASCII i plus U+025b Latin Small Letter Open E)
- 𐐑 Pee (from U+0413 Cyrillic Capital Letter Ghe/from U+1d26 Greek Letter Small Capital Gamma)
- 𐐛 Eth (from U+00a3 Pound Sign/from U+???? Latin Small L SC)

Miniscules with a vertical component (such as 𐐆 Short I) use a small-capital block letter I as their basis, but could also use a dotless i.

#### Series IV:

- 𐐋 Short Oo (from ASCII I plus U+a76e Latin Capital Letter Con/from ASCII q)
- 𐐓 Tee (from U+042d Cyrillic Capital Letter E plus ASCII I/from U+027f Latin Small Letter Reverse R with Fishhook)
- 𐐙 Ef (from ASCII P plus U+03c1 Greek Small Letter Rho/from ASCII q plus U+03c1 Greek Small Letter Rho)
- 𐐢 El (from ASCII I plus ASCII C/from U+026d Latin Small Letter L With Retroflex Hook)

The obvious thing for these is to base them on modifications of phi and psi.  I added ascenders on the majuscules.

- 𐐌 Ay (from U+a7b2 Latin Capital Letter J With Crossed Tail/from U+???? Latin Small Letter Dotless J With Crossed Tail)
- 𐐐 H (from ASCII I plus U+03c6 Greek Small Letter Phi/from U+03c6 Greek Small Letter Phi)
- 𐐡 Er (from ASCII I plus U+0cad Latin Small Letter T With Curl/from ASCII l plus U+026c Latin Small Letter L With Belt)

#### Series V:

- 𐐎 Wu (from U+a6b6 Latin Capital Letter Omega plus ASCII L/from U+03c9 Greek Small Letter Omega)
- 𐐗 Kay (from U+a6b6 Latin Capital Letter Omega plus U+03d6 Greek Pi Symbol/from U+0277 Latin Small Letter Closed Omega)
- 𐐘 Gay (ditto plus U+1db9 Modifier Letter Small V with Hook)

#### Series VI:

These are perhaps the most whimsical letterforms and present the most challenge aside from the 𐐌 Ay/𐐐 H/𐐡 Er and 𐐝 Es.  I was conservative on 𐐏 Yee and 𐐜 Thee (particularly as this latter is very commonly used as a standalone "the" in English) but opted for a whimsical connected descender on the miniscule 𐐖 Jee.

- 𐐏 Yee (from ASCII V plus U+03d1 Greek Theta Symbol/from U+03b3 Greek Small Letter Gamma plus U+0255 Latin Small Letter T With Curl)
- 𐐜 Thee (from U+0194 Latin Capital Letter Gamma/from U+0263 Latin Small Letter Gamma) (alt. from U+f26e Latin Capital Ram's Horns)
- 𐐖 Jee (from ASCII c plus Xi/from ASCII c plus ASCII y)

#### Series VII:

- 𐐕 Chee (from ASCII C/from ASCII c)
- 𐐣 Em (from U+042d Cyrillic Capital Letter E/from U+044d Cyrillic Small Letter E)

#### Series VIII:

- 𐐝 Es (from U+0286 Latin Small Letter Esh Plus Curl plus U+1d9d Modifer Letter Small C with Curl/ASCII S/from U+???? Latin Small Ou SC)
- 𐐠 Zhee (from ASCII S/from ASCII s)

𐐝 Es in particular is an uncharacteristically ornate character.  In this version, I opted for tall forms of the minuscule to avoid clutter.

#### Series IX:

- 𐐤 En (from U+a746 Latin Capital Letter Broken L plus ASCII I/from U+a747 Latin Small Broken L)
- 𐐥 Eng (from U+0418 Cyrillic Capital Letter I/from U+020c Cyrillic Small Letter I)


### Miniscules

Many of the thorniest design problems involve the lower-case letters, which in conventional Deseret are simply smaller forms of the majuscules.  This is aesthetically unsatisfactory and makes for difficult reading in long-form text.  The introduction of ascenders and descenders goes against the initial intent of the designers (who wished to preserve metal type by not wearing out ascenders and descenders) but follows the lead of other Deseret font designers such as John Jenkins in the _Deseret Alphabet Classics_ series.

###  Ligatures

The original Deseret alphabet specification from 1855 included two ligatures:

- 𐐦 Oi
- 𐐧 Ew

By 1859, these were replaced with two variant forms.  ([Discussion](https://en.wikipedia.org/wiki/Deseret_alphabet#Encodings))

v0.0 (~2021.12.26):

![](https://user-images.githubusercontent.com/57601680/147884127-f2036533-cbc2-4561-a467-8f0e3d84b48d.png)

v.0.1 (~2022.2.26):

![image](https://user-images.githubusercontent.com/57601680/155855632-2585f9e4-6860-475e-bb31-2f4e36865fd6.png)

---

- [Deseret Alphabet page](http://deseretalphabet.org/)
- [_Deseret Alphabet Classics_](http://www.deseretalphabet.info/classics/)
