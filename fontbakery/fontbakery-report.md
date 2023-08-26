## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> All tabular figures must have the same width across the RIBBI-family. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/tnum_horizontal_metrics">com.google.fonts/check/family/tnum_horizontal_metrics</a>)</summary><div>


* 🔥 **FAIL** The most common tabular glyph width is 950. But there are other tabular glyphs with different widths such as the following ones:
	{997: ['zero.tnum', 'one.tnum', 'two.tnum', 'three.tnum', 'four.tnum', 'five.tnum', 'six.tnum', 'seven.tnum', 'eight.tnum', 'nine.tnum', 'period.tnum', 'comma.tnum', 'colon.tnum', 'semicolon.tnum', 'periodcentered.tnum', 'numbersign.tnum', 'slash.tnum', 'underscore.tnum', 'quotedbl.tnum', 'quotesingle.tnum', 'paragraph.tnum', 'section.tnum', 'degree.tnum', 'bar.tnum', 'cent.tnum', 'dollar.tnum', 'Euro.tnum', 'sterling.tnum', 'yen.tnum', 'plus.tnum', 'minus.tnum', 'multiply.tnum', 'divide.tnum', 'equal.tnum', 'greater.tnum', 'less.tnum', 'plusminus.tnum', 'percent.tnum', 'zero.tnum', 'one.tnum', 'two.tnum', 'three.tnum', 'four.tnum', 'five.tnum', 'six.tnum', 'seven.tnum', 'eight.tnum', 'nine.tnum', 'period.tnum', 'comma.tnum', 'colon.tnum', 'semicolon.tnum', 'periodcentered.tnum', 'numbersign.tnum', 'slash.tnum', 'underscore.tnum', 'quotedbl.tnum', 'quotesingle.tnum', 'paragraph.tnum', 'section.tnum', 'degree.tnum', 'bar.tnum', 'cent.tnum', 'dollar.tnum', 'Euro.tnum', 'sterling.tnum', 'yen.tnum', 'plus.tnum', 'minus.tnum', 'multiply.tnum', 'divide.tnum', 'equal.tnum', 'greater.tnum', 'less.tnum', 'plusminus.tnum', 'percent.tnum']}. [code: inconsistent-widths]
</div></details><br></div></details><details><summary><b>[12] LibreCaslonCondensed-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̆ j̇ j̊ j̋ ǰ j̒ j̦̀ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l 

	- l + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- eight.numerator

	- five.denominator

	- four.numerator

	- grave.cap

	- hungarumlaut.cap

	- i.loclTRK

	- macron.cap

	- nine.denominator

	- nine.numerator

	- ogonek.cap

	- ogonek.curve

	- ogonek.curve.cap

	- one.denominator

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- ring.cap

	- seven.denominator

	- six.denominator

	- six.numerator

	- tilde.cap

	- uni030C.alt

	- zero.denominator 

	- zero.numerator
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: equal	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: gravecomb	Contours detected: 0	Expected: 1

	- Glyph name: acutecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: tildecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: equal	Contours detected: 1	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 883 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 788:
plus

Width = 814:
less

Width = 816:
divide, greater

Width = 890:
logicalnot

Width = 899:
plusminus

Width = 773:
multiply
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=775.0,Y=-1.0 (should be at baseline 0?)

	* S (U+0053): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* S (U+0053): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* g (U+0067): X=361.0,Y=-518.0 (should be at descender -520?)

	* ordfeminine (U+00AA): X=436.0,Y=1524.5 (should be at cap-height 1523?)

	* eth (U+00F0): X=670.0,Y=1525.0 (should be at cap-height 1523?)

	* dcaron (U+010F): X=1085.0,Y=1525.0 (should be at cap-height 1523?)

	* gcircumflex (U+011D): X=361.0,Y=-518.0 (should be at descender -520?)

	* gbreve (U+011F): X=361.0,Y=-518.0 (should be at descender -520?)

	* gdotaccent (U+0121): X=361.0,Y=-518.0 (should be at descender -520?)

	* uni0123 (U+0123): X=361.0,Y=-518.0 (should be at descender -520?)

	* lcaron (U+013E): X=577.0,Y=1525.0 (should be at cap-height 1523?)

	* napostrophe (U+0149): X=94.5,Y=1523.5 (should be at cap-height 1523?)

	* Sacute (U+015A): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* Sacute (U+015A): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* Scircumflex (U+015C): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* Scircumflex (U+015C): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* uni015E (U+015E): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* uni015E (U+015E): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* Scaron (U+0160): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* Scaron (U+0160): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* tcaron (U+0165): X=568.0,Y=1525.0 (should be at cap-height 1523?)

	* Uogonek (U+0172): X=754.0,Y=-519.0 (should be at descender -520?)

	* Uogonek (U+0172): X=754.0,Y=-519.0 (should be at descender -520?)

	* uni0218 (U+0218): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* uni0218 (U+0218): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* apostrophe (U+02BC): X=31.5,Y=1523.5 (should be at cap-height 1523?)

	* uni1E62 (U+1E62): X=796.0,Y=1525.0 (should be at cap-height 1523?)

	* uni1E62 (U+1E62): X=836.0,Y=1525.0 (should be at cap-height 1523?)

	* uni2082 (U+2082): X=576.0,Y=-1.0 (should be at baseline 0?)

	* uni2086 (U+2086): X=650.0,Y=-1.0 (should be at baseline 0?)

	* uni2087 (U+2087): X=363.0,Y=-1.5 (should be at baseline 0?) 

	* uni2089 (U+2089): X=378.5,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ffi (U+FB03): L<<1153.0,1049.0>--<1444.0,1077.0>> -> L<<1444.0,1077.0>--<1468.0,1077.0>>

	* ffi (U+FB03): L<<924.0,1049.0>--<1153.0,1049.0>> -> L<<1153.0,1049.0>--<1444.0,1077.0>>

	* fi (U+FB01): L<<370.0,1049.0>--<598.0,1049.0>> -> L<<598.0,1049.0>--<891.0,1077.0>> 

	* fi (U+FB01): L<<598.0,1049.0>--<891.0,1077.0>> -> L<<891.0,1077.0>--<914.0,1077.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[18] LibreCaslonCondensed-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0327 (COMBINING CEDILLA)
 

	- 0x0328 (COMBINING OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Libre Caslon Condensed Medium | Libre Caslon Condensed Medium |
| Subfamily Name | Regular | Italic |
| Full Name | Libre Caslon Condensed Medium Italic | Libre Caslon Condensed Medium Italic |
| Poscript Name | LibreCaslonCondensed-MediumItalic | LibreCaslonCondensed-MediumItalic |
| Typographic Family Name | Libre Caslon Condensed | Libre Caslon Condensed |
| Typographic Subfamily Name | Medium Italic | Medium Italic | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/italic_names">com.google.fonts/check/name/italic_names</a>)</summary><div>


* 🔥 **FAIL** Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'. [code: bad-subfamilyname]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l

	- l + t

	- s + p 

	- p + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- AE.001

	- C.001

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- grave.cap

	- hungarumlaut.cap

	- macron.cap

	- ring.cap

	- tilde.cap

	- uni03BC.001 

	- uni2070.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: wgrave	Contours detected: 3	Expected: 2

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3 

	- Glyph name: wgrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 858 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 831:
plus

Width = 783:
equal

Width = 848:
logicalnot

Width = 845:
plusminus

Width = 794:
multiply

Width = 830:
divide, minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The value of post.italicAngle (-22.582992553710938) seems very high (over -20° or 20°) and should be confirmed. [code: over-20-degrees]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk (U+002A): X=611.0,Y=1524.0 (should be at cap-height 1523?)

	* comma (U+002C): X=89.0,Y=-1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=142.0,Y=-1.0 (should be at baseline 0?)

	* A (U+0041): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* d (U+0064): X=718.5,Y=1047.5 (should be at x-height 1049?)

	* g (U+0067): X=824.0,Y=1047.0 (should be at x-height 1049?)

	* w (U+0077): X=197.5,Y=-0.5 (should be at baseline 0?)

	* section (U+00A7): X=-21.0,Y=1.5 (should be at baseline 0?)

	* section (U+00A7): X=990.0,Y=1524.5 (should be at cap-height 1523?)

	* uni00B2 (U+00B2): X=852.0,Y=1524.5 (should be at cap-height 1523?)

	* threequarters (U+00BE): X=808.5,Y=1523.5 (should be at cap-height 1523?)

	* Agrave (U+00C0): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Aacute (U+00C1): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Acircumflex (U+00C2): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Atilde (U+00C3): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Adieresis (U+00C4): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Aring (U+00C5): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* atilde (U+00E3): X=960.0,Y=1521.0 (should be at cap-height 1523?)

	* eth (U+00F0): X=992.0,Y=1525.0 (should be at cap-height 1523?)

	* ntilde (U+00F1): X=961.0,Y=1521.0 (should be at cap-height 1523?)

	* otilde (U+00F5): X=950.0,Y=1521.0 (should be at cap-height 1523?)

	* oslash (U+00F8): X=208.0,Y=-1.0 (should be at baseline 0?)

	* Amacron (U+0100): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Abreve (U+0102): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* Aogonek (U+0104): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* cdotaccent (U+010B): X=689.0,Y=1522.5 (should be at cap-height 1523?)

	* edotaccent (U+0117): X=664.0,Y=1522.5 (should be at cap-height 1523?)

	* gdotaccent (U+0121): X=559.0,Y=1522.5 (should be at cap-height 1523?)

	* itilde (U+0129): X=685.0,Y=1521.0 (should be at cap-height 1523?)

	* utilde (U+0169): X=960.0,Y=1521.0 (should be at cap-height 1523?)

	* wcircumflex (U+0175): X=197.5,Y=-0.5 (should be at baseline 0?)

	* zdotaccent (U+017C): X=556.0,Y=1522.5 (should be at cap-height 1523?)

	* Aringacute (U+01FA): X=1019.0,Y=1524.0 (should be at cap-height 1523?)

	* oslashacute (U+01FF): X=203.0,Y=1.0 (should be at baseline 0?)

	* dotaccent (U+02D9): X=399.5,Y=1522.0 (should be at cap-height 1523?)

	* uni1E45 (U+1E45): X=712.0,Y=1522.5 (should be at cap-height 1523?)

	* wgrave (U+1E81): X=197.5,Y=-0.5 (should be at baseline 0?)

	* wacute (U+1E83): X=197.5,Y=-0.5 (should be at baseline 0?)

	* wdieresis (U+1E85): X=197.5,Y=-0.5 (should be at baseline 0?)

	* uni1EBD (U+1EBD): X=913.0,Y=1521.0 (should be at cap-height 1523?)

	* uni1EF9 (U+1EF9): X=779.0,Y=1521.0 (should be at cap-height 1523?)

	* dagger (U+2020): X=628.0,Y=1525.0 (should be at cap-height 1523?)

	* daggerdbl (U+2021): X=674.0,Y=1525.0 (should be at cap-height 1523?)

	* uni2120 (U+2120): X=475.5,Y=1521.5 (should be at cap-height 1523?)

	* threeeighths (U+215C): X=810.5,Y=1523.5 (should be at cap-height 1523?)

	* ff (U+FB00): X=984.0,Y=1523.5 (should be at cap-height 1523?)

	* fl (U+FB02): X=963.5,Y=1522.0 (should be at cap-height 1523?)

	* ffi (U+FB03): X=984.0,Y=1523.5 (should be at cap-height 1523?)

	* ffl (U+FB04): X=1545.0,Y=1524.0 (should be at cap-height 1523?) 

	* st (U+FB06): X=1346.5,Y=1522.0 (should be at cap-height 1523?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* iogonek (U+012F): L<<245.0,10.0>--<372.0,89.0>>/B<<372.0,89.0>-<236.0,-51.0>-<159.0,-156.5>> = 13.946751611649468 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] LibreCaslonCondensed-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̆ j̇ j̊ j̋ ǰ j̒ j̦̀ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l 

	- l + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- eight.numerator

	- five.denominator

	- four.numerator

	- grave.cap

	- hungarumlaut.cap

	- i.loclTRK

	- macron.cap

	- nine.denominator

	- nine.numerator

	- ogonek.cap

	- ogonek.curve

	- ogonek.curve.cap

	- one.denominator

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- ring.cap

	- seven.denominator

	- six.denominator

	- six.numerator

	- tilde.cap

	- uni030C.alt

	- zero.denominator 

	- zero.numerator
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: gravecomb	Contours detected: 0	Expected: 1

	- Glyph name: acutecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: tildecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 864 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 778:
plus

Width = 804:
less

Width = 806:
greater

Width = 867:
logicalnot

Width = 881:
plusminus

Width = 766:
multiply

Width = 795:
divide
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=819.0,Y=-2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=445.0,Y=1524.5 (should be at cap-height 1523?)

	* uni2076 (U+2076): X=349.5,Y=1521.5 (should be at cap-height 1523?)

	* uni2082 (U+2082): X=621.0,Y=2.0 (should be at baseline 0?)

	* uni2086 (U+2086): X=714.0,Y=-2.0 (should be at baseline 0?)

	* uni2086 (U+2086): X=282.0,Y=-2.0 (should be at baseline 0?)

	* uni2087 (U+2087): X=403.0,Y=-1.5 (should be at baseline 0?)

	* uni2089 (U+2089): X=392.5,Y=2.0 (should be at baseline 0?)

	* st (U+FB06): X=1055.5,Y=1524.5 (should be at cap-height 1523?) 

	* st (U+FB06): X=999.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[13] LibreCaslonCondensed-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̆ j̇ j̊ j̋ ǰ j̒ j̦̀ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l 

	- l + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- eight.numerator

	- five.denominator

	- four.numerator

	- grave.cap

	- hungarumlaut.cap

	- i.loclTRK

	- macron.cap

	- nine.denominator

	- nine.numerator

	- ogonek.cap

	- ogonek.curve

	- ogonek.curve.cap

	- one.denominator

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- ring.cap

	- seven.denominator

	- six.denominator

	- six.numerator

	- tilde.cap

	- uni030C.alt

	- zero.denominator 

	- zero.numerator
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 1	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: gravecomb	Contours detected: 0	Expected: 1

	- Glyph name: acutecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: tildecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1

	- Glyph name: OE	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 892 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 793:
plus

Width = 819:
less

Width = 821:
greater

Width = 901:
logicalnot

Width = 908:
plusminus

Width = 776:
multiply

Width = 826:
divide
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=328.0,Y=1521.0 (should be at cap-height 1523?)

	* quotedbl (U+0022): X=87.0,Y=1521.0 (should be at cap-height 1523?)

	* quotesingle (U+0027): X=87.0,Y=1521.0 (should be at cap-height 1523?)

	* S (U+0053): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* S (U+0053): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* g (U+0067): X=830.5,Y=1049.5 (should be at x-height 1049?)

	* section (U+00A7): X=294.5,Y=1522.5 (should be at cap-height 1523?)

	* ordfeminine (U+00AA): X=432.0,Y=1524.5 (should be at cap-height 1523?)

	* edieresis (U+00EB): X=579.0,Y=1521.5 (should be at cap-height 1523?)

	* edieresis (U+00EB): X=712.5,Y=1521.5 (should be at cap-height 1523?)

	* edieresis (U+00EB): X=277.0,Y=1521.5 (should be at cap-height 1523?)

	* edieresis (U+00EB): X=410.0,Y=1521.5 (should be at cap-height 1523?)

	* idieresis (U+00EF): X=335.0,Y=1521.5 (should be at cap-height 1523?)

	* idieresis (U+00EF): X=468.5,Y=1521.5 (should be at cap-height 1523?)

	* idieresis (U+00EF): X=33.0,Y=1521.5 (should be at cap-height 1523?)

	* idieresis (U+00EF): X=166.0,Y=1521.5 (should be at cap-height 1523?)

	* eth (U+00F0): X=658.0,Y=1522.0 (should be at cap-height 1523?)

	* odieresis (U+00F6): X=577.0,Y=1521.5 (should be at cap-height 1523?)

	* odieresis (U+00F6): X=710.5,Y=1521.5 (should be at cap-height 1523?)

	* odieresis (U+00F6): X=275.0,Y=1521.5 (should be at cap-height 1523?)

	* odieresis (U+00F6): X=408.0,Y=1521.5 (should be at cap-height 1523?)

	* ydieresis (U+00FF): X=569.0,Y=1521.5 (should be at cap-height 1523?)

	* ydieresis (U+00FF): X=702.5,Y=1521.5 (should be at cap-height 1523?)

	* ydieresis (U+00FF): X=267.0,Y=1521.5 (should be at cap-height 1523?)

	* ydieresis (U+00FF): X=400.0,Y=1521.5 (should be at cap-height 1523?)

	* Sacute (U+015A): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* Sacute (U+015A): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* Scircumflex (U+015C): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* Scircumflex (U+015C): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* uni015E (U+015E): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* uni015E (U+015E): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* Scaron (U+0160): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* Scaron (U+0160): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* uni0218 (U+0218): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* uni0218 (U+0218): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* uni1E62 (U+1E62): X=777.0,Y=1525.0 (should be at cap-height 1523?)

	* uni1E62 (U+1E62): X=811.0,Y=1525.0 (should be at cap-height 1523?)

	* wdieresis (U+1E85): X=771.0,Y=1521.5 (should be at cap-height 1523?)

	* wdieresis (U+1E85): X=904.5,Y=1521.5 (should be at cap-height 1523?)

	* wdieresis (U+1E85): X=469.0,Y=1521.5 (should be at cap-height 1523?)

	* wdieresis (U+1E85): X=602.0,Y=1521.5 (should be at cap-height 1523?)

	* uni2086 (U+2086): X=232.0,Y=1.0 (should be at baseline 0?)

	* uni2087 (U+2087): X=343.0,Y=-1.0 (should be at baseline 0?) 

	* fl (U+FB02): X=648.5,Y=1521.5 (should be at cap-height 1523?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ffi (U+FB03): L<<1102.0,1049.0>--<1367.0,1071.0>> -> L<<1367.0,1071.0>--<1385.0,1071.0>>

	* ffi (U+FB03): L<<869.0,1049.0>--<1102.0,1049.0>> -> L<<1102.0,1049.0>--<1367.0,1071.0>>

	* fi (U+FB01): L<<340.0,1049.0>--<572.0,1049.0>> -> L<<572.0,1049.0>--<838.0,1071.0>> 

	* fi (U+FB01): L<<572.0,1049.0>--<838.0,1071.0>> -> L<<838.0,1071.0>--<855.0,1071.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* OE (U+0152): B<<1009.0,69.0>-<991.0,58.0>-<972.0,49.0>>/L<<972.0,49.0>--<1106.0,88.0>> = 9.118814898431209 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] LibreCaslonCondensed-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0327 (COMBINING CEDILLA)
 

	- 0x0328 (COMBINING OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l

	- l + t

	- s + p 

	- p + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- AE.001

	- C.001

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- grave.cap

	- hungarumlaut.cap

	- macron.cap

	- ring.cap

	- tilde.cap

	- uni03BC.001 

	- uni2070.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: wgrave	Contours detected: 3	Expected: 2

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3 

	- Glyph name: wgrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 837 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 864:
less, greater

Width = 764:
equal

Width = 849:
plusminus

Width = 791:
multiply

Width = 836:
divide, minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The value of post.italicAngle (-22.582992553710938) seems very high (over -20° or 20°) and should be confirmed. [code: over-20-degrees]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=80.0,Y=-2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=133.0,Y=-2.0 (should be at baseline 0?)

	* A (U+0041): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* a (U+0061): X=723.0,Y=1047.5 (should be at x-height 1049?)

	* d (U+0064): X=709.0,Y=1047.5 (should be at x-height 1049?)

	* g (U+0067): X=811.0,Y=1051.0 (should be at x-height 1049?)

	* q (U+0071): X=739.5,Y=1047.5 (should be at x-height 1049?)

	* braceleft (U+007B): X=775.0,Y=1521.5 (should be at cap-height 1523?)

	* degree (U+00B0): X=767.0,Y=1522.5 (should be at cap-height 1523?)

	* threequarters (U+00BE): X=527.0,Y=1521.5 (should be at cap-height 1523?)

	* Agrave (U+00C0): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Aacute (U+00C1): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Acircumflex (U+00C2): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Atilde (U+00C3): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Adieresis (U+00C4): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Aring (U+00C5): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* acircumflex (U+00E2): X=825.0,Y=1521.0 (should be at cap-height 1523?)

	* ecircumflex (U+00EA): X=806.0,Y=1521.0 (should be at cap-height 1523?)

	* icircumflex (U+00EE): X=562.0,Y=1521.0 (should be at cap-height 1523?)

	* ocircumflex (U+00F4): X=832.0,Y=1521.0 (should be at cap-height 1523?)

	* ucircumflex (U+00FB): X=840.0,Y=1521.0 (should be at cap-height 1523?)

	* Amacron (U+0100): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Abreve (U+0102): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* Aogonek (U+0104): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* aogonek (U+0105): X=688.0,Y=1.0 (should be at baseline 0?)

	* ccircumflex (U+0109): X=816.0,Y=1521.0 (should be at cap-height 1523?)

	* gcircumflex (U+011D): X=647.0,Y=1521.0 (should be at cap-height 1523?)

	* hcircumflex (U+0125): X=937.0,Y=1521.0 (should be at cap-height 1523?)

	* jcircumflex (U+0135): X=579.0,Y=1521.0 (should be at cap-height 1523?)

	* napostrophe (U+0149): X=318.0,Y=1525.0 (should be at cap-height 1523?)

	* scircumflex (U+015D): X=704.0,Y=1521.0 (should be at cap-height 1523?)

	* wcircumflex (U+0175): X=1099.0,Y=1521.0 (should be at cap-height 1523?)

	* ycircumflex (U+0177): X=658.0,Y=1521.0 (should be at cap-height 1523?)

	* Aringacute (U+01FA): X=1028.0,Y=1524.0 (should be at cap-height 1523?)

	* apostrophe (U+02BC): X=494.0,Y=1525.0 (should be at cap-height 1523?)

	* circumflex (U+02C6): X=419.0,Y=1521.0 (should be at cap-height 1523?)

	* uni2088 (U+2088): X=312.0,Y=1.0 (should be at baseline 0?)

	* uni2120 (U+2120): X=477.5,Y=1522.5 (should be at cap-height 1523?)

	* uni2154 (U+2154): X=835.0,Y=1521.0 (should be at cap-height 1523?)

	* threeeighths (U+215C): X=531.0,Y=1521.5 (should be at cap-height 1523?) 

	* seveneighths (U+215E): X=860.0,Y=1522.0 (should be at cap-height 1523?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Eng (U+014A): L<<1439.0,1441.0>--<930.0,-21.0>> -> L<<930.0,-21.0>--<917.0,-56.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* iogonek (U+012F): L<<202.0,0.0>--<341.0,89.0>>/B<<341.0,89.0>-<207.0,-50.0>-<123.5,-164.5>> = 13.418317466805592 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] LibreCaslonCondensed-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0327 (COMBINING CEDILLA)
 

	- 0x0328 (COMBINING OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Libre Caslon Condensed SemiBold | Libre Caslon Condensed SemiBold |
| Subfamily Name | Regular | Italic |
| Full Name | Libre Caslon Condensed SemiBold Italic | Libre Caslon Condensed SemiBold Italic |
| Poscript Name | LibreCaslonCondensed-SemiBoldItalic | LibreCaslonCondensed-SemiBoldItalic |
| Typographic Family Name | Libre Caslon Condensed | Libre Caslon Condensed |
| Typographic Subfamily Name | SemiBold Italic | SemiBold Italic | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection ITALIC bit should be set. [code: bad-ITALIC]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/italic_names">com.google.fonts/check/name/italic_names</a>)</summary><div>


* 🔥 **FAIL** Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'. [code: bad-subfamilyname]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l

	- l + t

	- s + p 

	- p + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- AE.001

	- C.001

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- grave.cap

	- hungarumlaut.cap

	- macron.cap

	- ring.cap

	- tilde.cap

	- uni03BC.001 

	- uni2070.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: wgrave	Contours detected: 3	Expected: 2

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3 

	- Glyph name: wgrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 824 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 851:
less, greater

Width = 801:
equal

Width = 858:
logicalnot

Width = 840:
plusminus

Width = 798:
multiply
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The value of post.italicAngle (-22.582992553710938) seems very high (over -20° or 20°) and should be confirmed. [code: over-20-degrees]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* semicolon (U+003B): X=151.0,Y=1.0 (should be at baseline 0?)

	* grave (U+0060): X=566.0,Y=1521.0 (should be at cap-height 1523?)

	* p (U+0070): X=337.0,Y=1050.0 (should be at x-height 1049?)

	* p (U+0070): X=185.0,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=217.5,Y=-1.0 (should be at baseline 0?)

	* dieresis (U+00A8): X=904.0,Y=1521.5 (should be at cap-height 1523?)

	* dieresis (U+00A8): X=525.5,Y=1521.5 (should be at cap-height 1523?)

	* uni00B2 (U+00B2): X=849.5,Y=1524.0 (should be at cap-height 1523?)

	* uni03BC.1 (U+00B5): X=60.0,Y=1.0 (should be at baseline 0?)

	* oslash (U+00F8): X=217.0,Y=1.0 (should be at baseline 0?)

	* thorn (U+00FE): X=158.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=217.5,Y=-1.0 (should be at baseline 0?)

	* oslashacute (U+01FF): X=214.0,Y=2.0 (should be at baseline 0?)

	* dotaccent (U+02D9): X=343.0,Y=1521.5 (should be at cap-height 1523?)

	* uni03BC (U+03BC): X=38.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=217.5,Y=-1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=217.5,Y=-1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=217.5,Y=-1.0 (should be at baseline 0?) 

	* daggerdbl (U+2021): X=173.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ff (U+FB00): L<<517.0,970.0>--<514.0,961.0>> -> L<<514.0,961.0>--<351.0,396.0>>

	* ffi (U+FB03): L<<517.0,970.0>--<514.0,961.0>> -> L<<514.0,961.0>--<351.0,396.0>> 

	* ffl (U+FB04): L<<516.0,970.0>--<513.0,961.0>> -> L<<513.0,961.0>--<351.0,396.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] LibreCaslonCondensed-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̆ j̇ j̊ j̋ ǰ j̒ j̦̀ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l 

	- l + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- eight.numerator

	- five.denominator

	- four.numerator

	- grave.cap

	- hungarumlaut.cap

	- i.loclTRK

	- macron.cap

	- nine.denominator

	- nine.numerator

	- ogonek.cap

	- ogonek.curve

	- ogonek.curve.cap

	- one.denominator

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- ring.cap

	- seven.denominator

	- six.denominator

	- six.numerator

	- tilde.cap

	- uni030C.alt

	- zero.denominator 

	- zero.numerator
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: gravecomb	Contours detected: 0	Expected: 1

	- Glyph name: acutecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: tildecomb	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0302	Contours detected: 0	Expected: 1

	- Glyph name: uni0304	Contours detected: 0	Expected: 1

	- Glyph name: uni0306	Contours detected: 0	Expected: 1

	- Glyph name: uni0307	Contours detected: 0	Expected: 1

	- Glyph name: uni0308	Contours detected: 0	Expected: 2

	- Glyph name: uni030A	Contours detected: 0	Expected: 2

	- Glyph name: uni030B	Contours detected: 0	Expected: 2

	- Glyph name: uni030C	Contours detected: 0	Expected: 1

	- Glyph name: uni0312	Contours detected: 0	Expected: 1

	- Glyph name: uni0327	Contours detected: 0	Expected: 1

	- Glyph name: uni0328	Contours detected: 0	Expected: 1

	- Glyph name: uni1E9E	Contours detected: 0	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 873 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 783:
plus

Width = 809:
less

Width = 811:
greater

Width = 878:
logicalnot

Width = 890:
plusminus

Width = 769:
multiply

Width = 805:
divide
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=205.0,Y=-2.0 (should be at baseline 0?)

	* g (U+0067): X=369.0,Y=-521.0 (should be at descender -520?)

	* g (U+0067): X=768.0,Y=1047.0 (should be at x-height 1049?)

	* ordfeminine (U+00AA): X=440.5,Y=1524.5 (should be at cap-height 1523?)

	* atilde (U+00E3): X=255.5,Y=1522.5 (should be at cap-height 1523?)

	* atilde (U+00E3): X=574.0,Y=1522.0 (should be at cap-height 1523?)

	* ntilde (U+00F1): X=329.5,Y=1522.5 (should be at cap-height 1523?)

	* ntilde (U+00F1): X=648.0,Y=1522.0 (should be at cap-height 1523?)

	* otilde (U+00F5): X=293.0,Y=1522.5 (should be at cap-height 1523?)

	* otilde (U+00F5): X=611.0,Y=1522.0 (should be at cap-height 1523?)

	* gcircumflex (U+011D): X=369.0,Y=-521.0 (should be at descender -520?)

	* gbreve (U+011F): X=369.0,Y=-521.0 (should be at descender -520?)

	* gdotaccent (U+0121): X=369.0,Y=-521.0 (should be at descender -520?)

	* uni0123 (U+0123): X=369.0,Y=-521.0 (should be at descender -520?)

	* itilde (U+0129): X=59.0,Y=1522.5 (should be at cap-height 1523?)

	* itilde (U+0129): X=377.0,Y=1522.0 (should be at cap-height 1523?)

	* utilde (U+0169): X=263.5,Y=1522.5 (should be at cap-height 1523?)

	* utilde (U+0169): X=582.0,Y=1522.0 (should be at cap-height 1523?)

	* tilde (U+02DC): X=76.5,Y=1522.5 (should be at cap-height 1523?)

	* tilde (U+02DC): X=474.0,Y=1522.0 (should be at cap-height 1523?)

	* uni1EBD (U+1EBD): X=283.5,Y=1522.5 (should be at cap-height 1523?)

	* uni1EBD (U+1EBD): X=602.0,Y=1522.0 (should be at cap-height 1523?)

	* uni1EF9 (U+1EF9): X=323.5,Y=1522.5 (should be at cap-height 1523?)

	* uni1EF9 (U+1EF9): X=642.0,Y=1522.0 (should be at cap-height 1523?)

	* quotesinglbase (U+201A): X=205.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=543.0,Y=-2.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=205.0,Y=-2.0 (should be at baseline 0?)

	* uni2086 (U+2086): X=682.0,Y=-1.0 (should be at baseline 0?)

	* uni2086 (U+2086): X=265.0,Y=-1.0 (should be at baseline 0?)

	* uni2087 (U+2087): X=383.0,Y=-1.0 (should be at baseline 0?)

	* uni2089 (U+2089): X=385.5,Y=2.0 (should be at baseline 0?) 

	* ffi (U+FB03): X=1268.0,Y=1522.5 (should be at cap-height 1523?) [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[14] LibreCaslonCondensed-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0327 (COMBINING CEDILLA)
 

	- 0x0328 (COMBINING OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + b

	- b + f

	- f + h

	- h + f

	- f + i

	- i + f

	- f + j

	- j + f

	- f + k

	- k + f

	- f + l

	- l + f

	- f + t

	- t + b

	- h + i

	- i + j

	- j + k

	- k + l

	- l + t

	- s + p 

	- p + t [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libre Caslon Condensed' / SUBFAMILY_NAME = 'Bold Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- AE.001

	- C.001

	- acute.cap

	- breve.cap

	- caron.alt

	- caron.cap

	- circumflex.cap

	- dieresis.cap

	- dotaccent.cap

	- grave.cap

	- hungarumlaut.cap

	- macron.cap

	- ring.cap

	- tilde.cap

	- uni03BC.001 

	- uni2070.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: wgrave	Contours detected: 3	Expected: 2

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3 

	- Glyph name: wgrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 818 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 845:
less, greater

Width = 820:
equal

Width = 869:
logicalnot

Width = 836:
plusminus

Width = 801:
multiply
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The value of post.italicAngle (-22.582992553710938) seems very high (over -20° or 20°) and should be confirmed. [code: over-20-degrees]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=929.0,Y=1521.0 (should be at cap-height 1523?)

	* comma (U+002C): X=108.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=160.0,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=804.0,Y=1.5 (should be at baseline 0?)

	* p (U+0070): X=336.0,Y=1048.0 (should be at x-height 1049?)

	* v (U+0076): X=210.0,Y=1.5 (should be at baseline 0?)

	* w (U+0077): X=238.0,Y=-1.5 (should be at baseline 0?)

	* y (U+0079): X=581.0,Y=-1.5 (should be at baseline 0?)

	* dieresis (U+00A8): X=1069.5,Y=1524.0 (should be at cap-height 1523?)

	* dieresis (U+00A8): X=675.0,Y=1524.0 (should be at cap-height 1523?)

	* uni00B2 (U+00B2): X=847.0,Y=1521.5 (should be at cap-height 1523?)

	* onequarter (U+00BC): X=669.0,Y=1524.0 (should be at cap-height 1523?)

	* onequarter (U+00BC): X=810.0,Y=1524.0 (should be at cap-height 1523?)

	* onehalf (U+00BD): X=669.0,Y=1524.0 (should be at cap-height 1523?)

	* onehalf (U+00BD): X=810.0,Y=1524.0 (should be at cap-height 1523?)

	* yacute (U+00FD): X=581.0,Y=-1.5 (should be at baseline 0?)

	* ydieresis (U+00FF): X=581.0,Y=-1.5 (should be at baseline 0?)

	* Gcircumflex (U+011C): X=804.0,Y=1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=804.0,Y=1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=804.0,Y=1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=804.0,Y=1.5 (should be at baseline 0?)

	* lacute (U+013A): X=861.5,Y=1942.0 (should be at ascender 1940?)

	* wcircumflex (U+0175): X=238.0,Y=-1.5 (should be at baseline 0?)

	* ycircumflex (U+0177): X=581.0,Y=-1.5 (should be at baseline 0?)

	* florin (U+0192): X=830.0,Y=1522.0 (should be at cap-height 1523?)

	* tilde (U+02DC): X=513.0,Y=1523.5 (should be at cap-height 1523?)

	* wgrave (U+1E81): X=238.0,Y=-1.5 (should be at baseline 0?)

	* wacute (U+1E83): X=238.0,Y=-1.5 (should be at baseline 0?)

	* wdieresis (U+1E85): X=238.0,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=581.0,Y=-1.5 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=581.0,Y=-1.5 (should be at baseline 0?)

	* quoteright (U+2019): X=862.0,Y=1522.0 (should be at cap-height 1523?)

	* uni2078 (U+2078): X=872.0,Y=1522.0 (should be at cap-height 1523?)

	* uni2086 (U+2086): X=324.5,Y=1.5 (should be at baseline 0?)

	* uni2153 (U+2153): X=669.0,Y=1524.0 (should be at cap-height 1523?)

	* uni2153 (U+2153): X=810.0,Y=1524.0 (should be at cap-height 1523?)

	* oneeighth (U+215B): X=669.0,Y=1524.0 (should be at cap-height 1523?)

	* oneeighth (U+215B): X=810.0,Y=1524.0 (should be at cap-height 1523?)

	* fiveeighths (U+215D): X=467.0,Y=1524.0 (should be at cap-height 1523?)

	* fiveeighths (U+215D): X=742.0,Y=1524.0 (should be at cap-height 1523?)

	* seveneighths (U+215E): X=546.0,Y=1524.0 (should be at cap-height 1523?) 

	* seveneighths (U+215E): X=949.0,Y=1524.0 (should be at cap-height 1523?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asterisk (U+002A): L<<607.0,1322.0>--<612.0,1391.0>> -> L<<612.0,1391.0>--<612.0,1465.0>> 

	* lslash (U+0142): L<<343.0,800.0>--<344.0,804.0>> -> L<<344.0,804.0>--<606.0,1552.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 17 | 95 | 942 | 49 | 746 | 0 |
| 0% | 1% | 5% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
