## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[11] VictorMono-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni25A9 (U+25A9): L<<403.0,220.0>--<403.0,220.0>> -> L<<403.0,220.0>--<454.0,220.0>>

	* uni25C1 (U+25C1): L<<534.0,74.0>--<448.0,126.0>> -> L<<448.0,126.0>--<46.0,370.0>>

	* uni25C3 (U+25C3): L<<444.0,183.0>--<370.0,228.0>> -> L<<370.0,228.0>--<136.0,370.0>>

	* uni25C5 (U+25C5): L<<534.0,165.0>--<452.0,200.0>> -> L<<452.0,200.0>--<29.0,370.0>>

	* uniE0A1 (U+E0A1): L<<305.0,12.0>--<307.0,-34.0>> -> L<<307.0,-34.0>--<307.0,-151.0>> 

	* uniE0A1 (U+E0A1): L<<372.0,162.0>--<369.0,226.0>> -> L<<369.0,226.0>--<369.0,326.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] VictorMono-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Victor Mono ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* delta (U+03B4): L<<459.0,332.0>--<459.0,332.0>> -> L<<459.0,332.0>--<459.0,332.0>>

	* eth (U+00F0): L<<529.0,249.0>--<529.0,248.0>> -> L<<529.0,248.0>--<529.0,247.0>>

	* oneeighth (U+215B): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* oneeighth (U+215B): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* onehalf (U+00BD): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* onehalf (U+00BD): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* onequarter (U+00BC): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* onequarter (U+00BC): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* partialdiff (U+2202): L<<534.0,251.0>--<534.0,251.0>> -> L<<534.0,251.0>--<534.0,251.0>>

	* rho (U+03C1): L<<81.0,309.0>--<81.0,309.0>> -> L<<81.0,309.0>--<81.0,309.0>>

	* section (U+00A7): L<<300.0,502.0>--<304.0,502.0>> -> L<<304.0,502.0>--<304.0,502.0>>

	* uni00B9 (U+00B9): L<<272.0,850.0>--<273.0,850.0>> -> L<<273.0,850.0>--<273.0,850.0>>

	* uni00B9 (U+00B9): L<<273.0,850.0>--<273.0,850.0>> -> L<<273.0,850.0>--<329.0,850.0>>

	* uni04C3 (U+04C3): L<<218.0,396.0>--<218.0,396.0>> -> L<<218.0,396.0>--<218.0,396.0>>

	* uni2081 (U+2081): L<<272.0,375.0>--<273.0,375.0>> -> L<<273.0,375.0>--<273.0,375.0>>

	* uni2081 (U+2081): L<<273.0,375.0>--<273.0,375.0>> -> L<<273.0,375.0>--<329.0,375.0>>

	* uni2150 (U+2150): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* uni2150 (U+2150): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* uni2151 (U+2151): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* uni2151 (U+2151): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* uni2152 (U+2152): L<<235.0,375.0>--<236.0,375.0>> -> L<<236.0,375.0>--<236.0,375.0>>

	* uni2152 (U+2152): L<<236.0,375.0>--<236.0,375.0>> -> L<<236.0,375.0>--<291.0,375.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152): L<<82.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<137.0,850.0>>

	* uni2153 (U+2153): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* uni2153 (U+2153): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* uni2155 (U+2155): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* uni2155 (U+2155): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* uni2159 (U+2159): L<<106.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<107.0,850.0>>

	* uni2159 (U+2159): L<<107.0,850.0>--<107.0,850.0>> -> L<<107.0,850.0>--<163.0,850.0>>

	* uni215F (U+215F): L<<105.0,850.0>--<106.0,850.0>> -> L<<106.0,850.0>--<106.0,850.0>>

	* uni215F (U+215F): L<<106.0,850.0>--<106.0,850.0>> -> L<<106.0,850.0>--<162.0,850.0>>

	* uni25A9 (U+25A9): L<<231.0,201.0>--<232.0,201.0>> -> L<<232.0,201.0>--<232.0,201.0>>

	* uni25A9 (U+25A9): L<<369.0,201.0>--<369.0,201.0>> -> L<<369.0,201.0>--<370.0,201.0>>

	* uni25C1 (U+25C1): L<<513.0,110.0>--<459.0,143.0>> -> L<<459.0,143.0>--<84.0,370.0>>

	* uni25C3 (U+25C3): L<<423.0,219.0>--<381.0,245.0>> -> L<<381.0,245.0>--<174.0,370.0>>

	* uni25C5 (U+25C5): L<<513.0,195.0>--<460.0,218.0>> -> L<<460.0,218.0>--<81.0,370.0>>

	* uniE0A1 (U+E0A1): L<<278.0,130.0>--<286.0,-35.0>> -> L<<286.0,-35.0>--<286.0,-132.0>> 

	* uniE0A1 (U+E0A1): L<<399.0,44.0>--<390.0,227.0>> -> L<<390.0,227.0>--<390.0,307.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* alpha (U+03B1): B<<418.0,511.0>-<434.0,457.0>-<443.0,394.0>>/B<<443.0,394.0>-<452.0,489.0>-<456.0,618.0>> = 13.541971506473004

	* alphatonos (U+03AC): B<<418.0,511.0>-<434.0,457.0>-<443.0,394.0>>/B<<443.0,394.0>-<452.0,489.0>-<456.0,618.0>> = 13.541971506473004

	* section (U+00A7): L<<296.0,116.0>--<296.0,116.0>>/B<<296.0,116.0>-<225.0,117.0>-<183.0,140.0>> = 0.8069294551021693 

	* uni04A6 (U+04A6): L<<321.0,800.0>--<321.0,414.0>>/B<<321.0,414.0>-<331.0,458.0>-<355.5,475.0>> = 12.80426606528674 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<271.0,798.0>--<81.0,799.0>>

	* uni2077 (U+2077): L<<361.0,798.0>--<171.0,799.0>>

	* uni2087 (U+2087): L<<361.0,323.0>--<171.0,324.0>>

	* uni2150 (U+2150): L<<532.0,323.0>--<342.0,324.0>>

	* uni2196 (U+2196): L<<47.0,683.0>--<367.0,682.0>>

	* uni2196 (U+2196): L<<48.0,362.0>--<47.0,683.0>>

	* uni2197 (U+2197): L<<233.0,682.0>--<553.0,683.0>>

	* uni2197 (U+2197): L<<553.0,683.0>--<552.0,362.0>>

	* uni2198 (U+2198): L<<552.0,473.0>--<553.0,153.0>>

	* uni2199 (U+2199): L<<47.0,153.0>--<48.0,473.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<347.0,682.0>>

	* uni21D6 (U+21D6): L<<28.0,362.0>--<27.0,683.0>>

	* uni21D7 (U+21D7): L<<253.0,682.0>--<573.0,683.0>>

	* uni21D7 (U+21D7): L<<573.0,683.0>--<572.0,362.0>>

	* uni21D8 (U+21D8): L<<572.0,438.0>--<573.0,117.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<253.0,118.0>>

	* uni21D9 (U+21D9): L<<27.0,117.0>--<28.0,438.0>> 

	* uni21D9 (U+21D9): L<<347.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] VictorMono-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* yen (U+00A5) contains a short segment L<<263.0,301.0>--<262.0,303.0>>

	* yen (U+00A5) contains a short segment L<<338.0,303.0>--<338.0,301.0>>

	* section (U+00A7) contains a short segment L<<288.0,109.0>--<288.0,109.0>>

	* section (U+00A7) contains a short segment B<<293.0,509.0>-<302.0,509.0>-<313.0,509.0>>

	* section (U+00A7) contains a short segment L<<313.0,509.0>--<313.0,509.0>>

	* section (U+00A7) contains a short segment B<<307.0,109.0>-<298.0,109.0>-<288.0,109.0>>

	* section (U+00A7) contains a short segment L<<313.0,438.0>--<313.0,438.0>>

	* uni00B9 (U+00B9) contains a short segment L<<267.0,850.0>--<267.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* germandbls (U+00DF) contains a short segment L<<257.0,460.0>--<279.0,460.0>>

	* xi (U+03BE) contains a short segment B<<514.0,800.0>-<520.0,801.0>-<527.0,803.0>>

	* xi (U+03BE) contains a short segment L<<527.0,731.0>--<517.0,731.0>>

	* xi (U+03BE) contains a short segment B<<512.0,507.0>-<519.0,508.0>-<527.0,509.0>>

	* xi (U+03BE) contains a short segment B<<526.0,438.0>-<521.0,438.0>-<516.0,438.0>>

	* rho (U+03C1) contains a short segment L<<73.0,309.0>--<73.0,309.0>>

	* rho (U+03C1) contains a short segment L<<73.0,309.0>--<73.0,309.0>>

	* omega (U+03C9) contains a short segment B<<262.0,318.0>-<262.0,326.0>-<263.0,336.0>>

	* omega (U+03C9) contains a short segment B<<337.0,336.0>-<338.0,326.0>-<338.0,318.0>>

	* omegatonos (U+03CE) contains a short segment B<<262.0,318.0>-<262.0,326.0>-<263.0,336.0>>

	* omegatonos (U+03CE) contains a short segment B<<337.0,336.0>-<338.0,326.0>-<338.0,318.0>>

	* uni0404 (U+0404) contains a short segment L<<130.0,366.0>--<130.0,360.0>>

	* uni042D (U+042D) contains a short segment L<<471.0,435.0>--<471.0,440.0>>

	* uni042E (U+042E) contains a short segment L<<187.0,435.0>--<187.0,440.0>>

	* uni043A (U+043A) contains a short segment B<<238.0,297.0>-<230.0,297.0>-<221.0,297.0>>

	* uni044A (U+044A) contains a short segment L<<194.0,549.0>--<193.0,549.0>>

	* uni044D (U+044D) contains a short segment L<<471.0,344.0>--<471.0,349.0>>

	* uni044E (U+044E) contains a short segment L<<187.0,344.0>--<187.0,349.0>>

	* uni0454 (U+0454) contains a short segment L<<130.0,275.0>--<130.0,269.0>>

	* uni045C (U+045C) contains a short segment B<<238.0,297.0>-<230.0,297.0>-<221.0,297.0>>

	* uni0464 (U+0464) contains a short segment L<<187.0,435.0>--<187.0,440.0>>

	* uni0464 (U+0464) contains a short segment L<<262.0,366.0>--<262.0,360.0>>

	* uni0465 (U+0465) contains a short segment L<<187.0,344.0>--<187.0,349.0>>

	* uni0465 (U+0465) contains a short segment L<<262.0,275.0>--<262.0,269.0>>

	* uni046A (U+046A) contains a short segment B<<285.0,443.0>-<292.0,443.0>-<300.0,443.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,443.0>-<308.0,443.0>-<315.0,443.0>>

	* uni046B (U+046B) contains a short segment B<<280.0,363.0>-<290.0,363.0>-<300.0,363.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,363.0>-<310.0,363.0>-<320.0,363.0>>

	* uni0494 (U+0494) contains a short segment B<<283.5,-193.5>-<270.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-114.0>-<270.0,-122.0>-<283.5,-124.5>>

	* uni049B (U+049B) contains a short segment B<<238.0,297.0>-<230.0,297.0>-<221.0,297.0>>

	* uni049F (U+049F) contains a short segment B<<243.0,297.0>-<235.0,297.0>-<226.0,297.0>>

	* uni04A1 (U+04A1) contains a short segment B<<238.0,297.0>-<230.0,297.0>-<221.0,297.0>>

	* uni04A6 (U+04A6) contains a short segment B<<398.0,-193.5>-<385.0,-191.0>-<375.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<375.0,-114.0>-<385.0,-122.0>-<398.0,-124.5>>

	* uni04A7 (U+04A7) contains a short segment B<<389.5,-193.5>-<377.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-114.0>-<377.0,-122.0>-<389.5,-124.5>>

	* uni04A8 (U+04A8) contains a short segment B<<279.0,55.0>-<284.0,55.0>-<289.0,55.0>>

	* uni04B0 (U+04B0) contains a short segment L<<263.0,300.0>--<263.0,301.0>>

	* uni04B0 (U+04B0) contains a short segment L<<338.0,301.0>--<338.0,300.0>>

	* uni04C3 (U+04C3) contains a short segment B<<256.0,-193.5>-<243.0,-191.0>-<233.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<233.0,-114.0>-<243.0,-122.0>-<256.0,-124.5>>

	* uni04C3 (U+04C3) contains a short segment L<<204.0,389.0>--<204.0,389.0>>

	* uni04C3 (U+04C3) contains a short segment L<<204.0,389.0>--<201.0,389.0>>

	* uni04E1 (U+04E1) contains a short segment L<<317.0,276.0>--<320.0,276.0>>

	* uni04E8 (U+04E8) contains a short segment L<<471.0,435.0>--<471.0,440.0>>

	* uni04E8 (U+04E8) contains a short segment L<<130.0,366.0>--<130.0,360.0>>

	* uni04EA (U+04EA) contains a short segment L<<471.0,435.0>--<471.0,440.0>>

	* uni04EA (U+04EA) contains a short segment L<<130.0,366.0>--<130.0,360.0>>

	* uni04EC (U+04EC) contains a short segment L<<471.0,435.0>--<471.0,440.0>>

	* uni04ED (U+04ED) contains a short segment L<<471.0,344.0>--<471.0,349.0>>

	* uni2081 (U+2081) contains a short segment L<<267.0,378.0>--<267.0,378.0>>

	* uni2150 (U+2150) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<220.0,484.0>--<220.0,468.0>>

	* uni2152 (U+2152) contains a short segment L<<222.0,378.0>--<222.0,378.0>>

	* uni2153 (U+2153) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<99.0,850.0>--<99.0,850.0>>

	* uni21C8 (U+21C8) contains a short segment L<<350.0,590.0>--<350.0,590.0>>

	* uni21C8 (U+21C8) contains a short segment L<<250.0,589.0>--<250.0,590.0>>

	* uni21CA (U+21CA) contains a short segment L<<250.0,210.0>--<250.0,211.0>>

	* uni21CA (U+21CA) contains a short segment L<<350.0,211.0>--<350.0,210.0>>

	* uni21CE (U+21CE) contains a short segment L<<193.0,215.0>--<198.0,208.0>>

	* uni21CE (U+21CE) contains a short segment L<<406.0,587.0>--<403.0,592.0>>

	* uni21DC (U+21DC) contains a short segment L<<86.0,400.0>--<88.0,399.0>>

	* uni21DC (U+21DC) contains a short segment L<<88.0,399.0>--<88.0,401.0>>

	* uni21DC (U+21DC) contains a short segment L<<88.0,401.0>--<86.0,400.0>>

	* uni21DD (U+21DD) contains a short segment L<<514.0,400.0>--<513.0,401.0>>

	* uni21DD (U+21DD) contains a short segment L<<513.0,401.0>--<513.0,399.0>>

	* uni21DD (U+21DD) contains a short segment L<<513.0,399.0>--<514.0,400.0>>

	* uni21F6 (U+21F6) contains a short segment L<<300.0,266.0>--<301.0,267.0>>

	* uni21F6 (U+21F6) contains a short segment L<<301.0,267.0>--<300.0,267.0>>

	* uni21F6 (U+21F6) contains a short segment L<<300.0,533.0>--<301.0,534.0>> 

	* uni21F6 (U+21F6) contains a short segment L<<301.0,534.0>--<300.0,534.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* oneeighth (U+215B): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* onehalf (U+00BD): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* onehalf (U+00BD): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* onequarter (U+00BC): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* onequarter (U+00BC): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* rho (U+03C1): L<<73.0,309.0>--<73.0,309.0>> -> L<<73.0,309.0>--<73.0,309.0>>

	* uni00B9 (U+00B9): L<<266.0,850.0>--<267.0,850.0>> -> L<<267.0,850.0>--<267.0,850.0>>

	* uni00B9 (U+00B9): L<<267.0,850.0>--<267.0,850.0>> -> L<<267.0,850.0>--<334.0,850.0>>

	* uni04C3 (U+04C3): L<<204.0,389.0>--<201.0,389.0>> -> L<<201.0,389.0>--<137.0,389.0>>

	* uni2081 (U+2081): L<<266.0,378.0>--<267.0,378.0>> -> L<<267.0,378.0>--<267.0,378.0>>

	* uni2081 (U+2081): L<<267.0,378.0>--<267.0,378.0>> -> L<<267.0,378.0>--<334.0,378.0>>

	* uni2150 (U+2150): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* uni2150 (U+2150): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* uni2151 (U+2151): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* uni2151 (U+2151): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* uni2152 (U+2152): L<<221.0,378.0>--<222.0,378.0>> -> L<<222.0,378.0>--<222.0,378.0>>

	* uni2152 (U+2152): L<<222.0,378.0>--<222.0,378.0>> -> L<<222.0,378.0>--<289.0,378.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152): L<<82.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<149.0,850.0>>

	* uni2153 (U+2153): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* uni2153 (U+2153): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* uni2155 (U+2155): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* uni2155 (U+2155): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* uni2159 (U+2159): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* uni2159 (U+2159): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<168.0,850.0>>

	* uni215F (U+215F): L<<98.0,850.0>--<99.0,850.0>> -> L<<99.0,850.0>--<99.0,850.0>>

	* uni215F (U+215F): L<<99.0,850.0>--<99.0,850.0>> -> L<<99.0,850.0>--<166.0,850.0>>

	* uni25C1 (U+25C1): L<<522.0,96.0>--<455.0,136.0>> -> L<<455.0,136.0>--<69.0,370.0>>

	* uni25C3 (U+25C3): L<<432.0,205.0>--<377.0,238.0>> -> L<<377.0,238.0>--<159.0,370.0>>

	* uni25C5 (U+25C5): L<<522.0,183.0>--<457.0,211.0>> -> L<<457.0,211.0>--<60.0,370.0>>

	* uniE0A1 (U+E0A1): L<<289.0,82.0>--<295.0,-34.0>> -> L<<295.0,-34.0>--<295.0,-139.0>>

	* uniE0A1 (U+E0A1): L<<388.0,92.0>--<382.0,227.0>> -> L<<382.0,227.0>--<382.0,315.0>> 

	* yen (U+00A5): L<<338.0,303.0>--<338.0,301.0>> -> L<<338.0,301.0>--<338.0,234.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<402.5,403.5>-<376.0,435.0>-<313.0,438.0>>/L<<313.0,438.0>--<313.0,438.0>> = 2.726310993906212

	* section (U+00A7): L<<288.0,109.0>--<288.0,109.0>>/B<<288.0,109.0>-<186.0,112.0>-<141.5,162.5>> = 1.68468431789628 

	* section (U+00A7): L<<313.0,438.0>--<313.0,438.0>>/B<<313.0,438.0>-<258.0,439.0>-<227.5,427.0>> = 1.041626676009815 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni2196 (U+2196): L<<47.0,683.0>--<376.0,682.0>>

	* uni2196 (U+2196): L<<48.0,353.0>--<47.0,683.0>>

	* uni2197 (U+2197): L<<224.0,682.0>--<553.0,683.0>>

	* uni2197 (U+2197): L<<553.0,683.0>--<552.0,353.0>>

	* uni2198 (U+2198): L<<552.0,476.0>--<553.0,147.0>>

	* uni2199 (U+2199): L<<47.0,147.0>--<48.0,476.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<356.0,682.0>>

	* uni21D6 (U+21D6): L<<28.0,353.0>--<27.0,683.0>>

	* uni21D7 (U+21D7): L<<244.0,682.0>--<573.0,683.0>>

	* uni21D7 (U+21D7): L<<573.0,683.0>--<572.0,353.0>>

	* uni21D8 (U+21D8): L<<572.0,447.0>--<573.0,117.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<244.0,118.0>>

	* uni21D9 (U+21D9): L<<27.0,117.0>--<28.0,447.0>> 

	* uni21D9 (U+21D9): L<<356.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] VictorMono-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment B<<235.0,398.0>-<230.0,393.0>-<224.0,388.0>>

	* at (U+0040) contains a short segment B<<445.5,251.0>-<453.0,237.0>-<472.0,237.0>>

	* K (U+004B) contains a short segment L<<237.0,381.0>--<236.0,381.0>>

	* k (U+006B) contains a short segment L<<197.0,373.0>--<217.0,373.0>>

	* m (U+006D) contains a short segment L<<128.0,618.0>--<128.0,600.0>>

	* sterling (U+00A3) contains a short segment B<<243.0,359.0>-<244.0,355.0>-<246.0,350.0>>

	* yen (U+00A5) contains a short segment L<<254.0,295.0>--<253.0,297.0>>

	* yen (U+00A5) contains a short segment L<<347.0,297.0>--<346.0,295.0>>

	* section (U+00A7) contains a short segment L<<321.0,428.0>--<321.0,428.0>>

	* registered (U+00AE) contains a short segment L<<273.0,450.0>--<269.0,450.0>>

	* uni00B9 (U+00B9) contains a short segment L<<261.0,850.0>--<261.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* eth (U+00F0) contains a short segment L<<546.0,238.0>--<546.0,238.0>>

	* uni0136 (U+0136) contains a short segment L<<237.0,381.0>--<236.0,381.0>>

	* uni0137 (U+0137) contains a short segment L<<197.0,373.0>--<217.0,373.0>>

	* OE (U+0152) contains a short segment L<<297.0,0.0>--<297.0,12.0>>

	* Kappa (U+039A) contains a short segment L<<237.0,381.0>--<236.0,381.0>>

	* xi (U+03BE) contains a short segment B<<513.0,800.0>-<524.0,802.0>-<535.0,804.0>>

	* xi (U+03BE) contains a short segment L<<535.0,715.0>--<518.0,715.0>>

	* xi (U+03BE) contains a short segment B<<535.0,426.0>-<526.0,426.0>-<518.0,426.0>>

	* rho (U+03C1) contains a short segment L<<64.0,308.0>--<64.0,308.0>>

	* rho (U+03C1) contains a short segment L<<64.0,308.0>--<64.0,309.0>>

	* uni03CF (U+03CF) contains a short segment L<<237.0,381.0>--<236.0,381.0>>

	* uni040C (U+040C) contains a short segment L<<135.0,465.0>--<158.0,465.0>>

	* uni040E (U+040E) contains a short segment L<<325.0,225.0>--<325.0,226.0>>

	* uni041A (U+041A) contains a short segment L<<135.0,465.0>--<158.0,465.0>>

	* uni0423 (U+0423) contains a short segment L<<325.0,225.0>--<325.0,226.0>>

	* uni044A (U+044A) contains a short segment L<<205.0,533.0>--<205.0,533.0>>

	* uni046A (U+046A) contains a short segment B<<290.0,450.0>-<295.0,450.0>-<300.0,450.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,450.0>-<305.0,450.0>-<310.0,450.0>>

	* uni046B (U+046B) contains a short segment B<<281.0,370.0>-<290.0,370.0>-<300.0,370.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,370.0>-<310.0,370.0>-<319.0,370.0>>

	* uni0494 (U+0494) contains a short segment B<<282.5,-193.5>-<269.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-99.0>-<269.0,-106.0>-<282.5,-108.5>>

	* uni0495 (U+0495) contains a short segment B<<288.0,-193.5>-<276.0,-191.0>-<267.0,-184.0>>

	* uni0495 (U+0495) contains a short segment B<<267.0,-99.0>-<276.0,-106.0>-<287.5,-108.5>>

	* uni049A (U+049A) contains a short segment L<<135.0,465.0>--<158.0,465.0>>

	* uni049B (U+049B) contains a short segment B<<231.0,290.0>-<221.0,289.0>-<211.0,289.0>>

	* uni049E (U+049E) contains a short segment L<<143.0,465.0>--<167.0,465.0>>

	* uni049F (U+049F) contains a short segment B<<239.0,290.0>-<229.0,289.0>-<219.0,289.0>>

	* uni04A0 (U+04A0) contains a short segment L<<152.0,465.0>--<175.0,465.0>>

	* uni04A1 (U+04A1) contains a short segment B<<231.0,290.0>-<221.0,289.0>-<211.0,289.0>>

	* uni04A6 (U+04A6) contains a short segment B<<388.5,-193.5>-<375.0,-191.0>-<366.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<366.0,-99.0>-<375.0,-106.0>-<388.5,-108.5>>

	* uni04A7 (U+04A7) contains a short segment B<<388.0,-193.5>-<376.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-99.0>-<376.0,-106.0>-<387.5,-108.5>>

	* uni04B0 (U+04B0) contains a short segment L<<254.0,295.0>--<254.0,295.0>>

	* uni04B0 (U+04B0) contains a short segment L<<346.0,295.0>--<346.0,295.0>>

	* uni04C3 (U+04C3) contains a short segment L<<135.0,465.0>--<158.0,465.0>>

	* uni04C3 (U+04C3) contains a short segment B<<255.0,-193.5>-<242.0,-191.0>-<232.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<232.0,-99.0>-<242.0,-106.0>-<255.0,-108.5>>

	* uni04C3 (U+04C3) contains a short segment L<<190.0,381.0>--<190.0,381.0>>

	* uni04C3 (U+04C3) contains a short segment B<<190.0,381.0>-<187.0,381.0>-<184.0,381.0>>

	* uni04C4 (U+04C4) contains a short segment B<<251.0,-99.0>-<260.0,-106.0>-<271.5,-108.5>>

	* uni04EE (U+04EE) contains a short segment L<<325.0,225.0>--<325.0,226.0>>

	* uni04F0 (U+04F0) contains a short segment L<<325.0,225.0>--<325.0,226.0>>

	* uni04F2 (U+04F2) contains a short segment L<<325.0,225.0>--<325.0,226.0>>

	* uni2081 (U+2081) contains a short segment L<<261.0,381.0>--<261.0,381.0>>

	* uni2150 (U+2150) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<81.0,850.0>--<81.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<208.0,381.0>--<208.0,381.0>>

	* uni2153 (U+2153) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<92.0,850.0>--<92.0,850.0>>

	* uni21BA (U+21BA) contains a short segment B<<281.0,742.0>-<290.0,742.0>-<300.0,742.0>>

	* uni21BB (U+21BB) contains a short segment B<<300.0,742.0>-<310.0,742.0>-<319.0,742.0>>

	* uni21C8 (U+21C8) contains a short segment L<<359.0,585.0>--<360.0,584.0>>

	* uni21C8 (U+21C8) contains a short segment L<<240.0,584.0>--<241.0,584.0>>

	* uni21CA (U+21CA) contains a short segment L<<241.0,216.0>--<240.0,216.0>>

	* uni21CA (U+21CA) contains a short segment L<<360.0,216.0>--<359.0,215.0>>

	* uni21DA (U+21DA) contains a short segment L<<300.0,577.0>--<291.0,569.0>>

	* uni21DA (U+21DA) contains a short segment L<<291.0,231.0>--<300.0,223.0>>

	* uni21DB (U+21DB) contains a short segment L<<300.0,223.0>--<309.0,231.0>>

	* uni21DB (U+21DB) contains a short segment L<<309.0,569.0>--<300.0,577.0>>

	* uni21F6 (U+21F6) contains a short segment L<<285.0,269.0>--<286.0,270.0>>

	* uni21F6 (U+21F6) contains a short segment L<<286.0,270.0>--<285.0,270.0>>

	* uni21F6 (U+21F6) contains a short segment L<<351.0,327.0>--<354.0,329.0>>

	* uni21F6 (U+21F6) contains a short segment L<<354.0,329.0>--<354.0,329.0>>

	* uni21F6 (U+21F6) contains a short segment L<<285.0,530.0>--<286.0,530.0>>

	* uni21F6 (U+21F6) contains a short segment L<<286.0,530.0>--<285.0,531.0>>

	* uni21F6 (U+21F6) contains a short segment L<<351.0,587.0>--<354.0,589.0>>

	* uni21F6 (U+21F6) contains a short segment L<<354.0,589.0>--<354.0,589.0>>

	* partialdiff (U+2202) contains a short segment L<<551.0,240.0>--<551.0,240.0>>

	* notelement (U+2209) contains a short segment L<<357.0,533.0>--<355.0,533.0>> 

	* notsubset (U+2284) contains a short segment L<<357.0,533.0>--<355.0,533.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* K (U+004B): L<<237.0,381.0>--<236.0,381.0>> -> L<<236.0,381.0>--<161.0,381.0>>

	* Kappa (U+039A): L<<237.0,381.0>--<236.0,381.0>> -> L<<236.0,381.0>--<161.0,381.0>>

	* oneeighth (U+215B): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* oneeighth (U+215B): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* onehalf (U+00BD): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* onehalf (U+00BD): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* onequarter (U+00BC): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* onequarter (U+00BC): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* uni00B9 (U+00B9): L<<260.0,850.0>--<261.0,850.0>> -> L<<261.0,850.0>--<261.0,850.0>>

	* uni00B9 (U+00B9): L<<261.0,850.0>--<261.0,850.0>> -> L<<261.0,850.0>--<339.0,850.0>>

	* uni0136 (U+0136): L<<237.0,381.0>--<236.0,381.0>> -> L<<236.0,381.0>--<161.0,381.0>>

	* uni03CF (U+03CF): L<<237.0,381.0>--<236.0,381.0>> -> L<<236.0,381.0>--<161.0,381.0>>

	* uni04B0 (U+04B0): L<<129.0,295.0>--<254.0,295.0>> -> L<<254.0,295.0>--<254.0,295.0>>

	* uni04B0 (U+04B0): L<<346.0,295.0>--<346.0,295.0>> -> L<<346.0,295.0>--<472.0,295.0>>

	* uni2081 (U+2081): L<<260.0,381.0>--<261.0,381.0>> -> L<<261.0,381.0>--<261.0,381.0>>

	* uni2081 (U+2081): L<<261.0,381.0>--<261.0,381.0>> -> L<<261.0,381.0>--<339.0,381.0>>

	* uni2150 (U+2150): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* uni2150 (U+2150): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* uni2151 (U+2151): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* uni2151 (U+2151): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* uni2152 (U+2152): L<<207.0,381.0>--<208.0,381.0>> -> L<<208.0,381.0>--<208.0,381.0>>

	* uni2152 (U+2152): L<<208.0,381.0>--<208.0,381.0>> -> L<<208.0,381.0>--<287.0,381.0>>

	* uni2152 (U+2152): L<<80.0,850.0>--<81.0,850.0>> -> L<<81.0,850.0>--<81.0,850.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<81.0,850.0>> -> L<<81.0,850.0>--<160.0,850.0>>

	* uni2153 (U+2153): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* uni2153 (U+2153): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* uni2155 (U+2155): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* uni2155 (U+2155): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* uni2159 (U+2159): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* uni2159 (U+2159): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<173.0,850.0>>

	* uni215F (U+215F): L<<91.0,850.0>--<92.0,850.0>> -> L<<92.0,850.0>--<92.0,850.0>>

	* uni215F (U+215F): L<<92.0,850.0>--<92.0,850.0>> -> L<<92.0,850.0>--<170.0,850.0>>

	* uni25C1 (U+25C1): L<<530.0,81.0>--<450.0,129.0>> -> L<<450.0,129.0>--<53.0,370.0>>

	* uni25C3 (U+25C3): L<<440.0,190.0>--<372.0,231.0>> -> L<<372.0,231.0>--<143.0,370.0>>

	* uni25C5 (U+25C5): L<<530.0,171.0>--<453.0,203.0>> -> L<<453.0,203.0>--<39.0,370.0>>

	* uniE0A1 (U+E0A1): L<<300.0,34.0>--<303.0,-34.0>> -> L<<303.0,-34.0>--<303.0,-147.0>> 

	* uniE0A1 (U+E0A1): L<<377.0,140.0>--<373.0,226.0>> -> L<<373.0,226.0>--<373.0,322.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<396.5,396.5>-<373.0,424.0>-<321.0,428.0>>/L<<321.0,428.0>--<321.0,428.0>> = 4.398705354995508 

	* section (U+00A7): L<<321.0,428.0>--<321.0,428.0>>/B<<321.0,428.0>-<266.0,430.0>-<235.5,420.0>> = 2.082565279730795 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni2196 (U+2196): L<<47.0,683.0>--<385.0,682.0>>

	* uni2197 (U+2197): L<<215.0,682.0>--<553.0,683.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<365.0,682.0>>

	* uni21D7 (U+21D7): L<<235.0,682.0>--<573.0,683.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<235.0,118.0>> 

	* uni21D9 (U+21D9): L<<365.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] VictorMono-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 4	Expected: 3

	- Glyph name: uni04D2	Contours detected: 5	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 4	Expected: 3

	- Glyph name: uni04D2	Contours detected: 5	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<358.0,804.0>--<404.0,800.0>> -> L<<404.0,800.0>--<450.0,800.0>>

	* oneeighth (U+215B): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* onehalf (U+00BD): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* onequarter (U+00BC): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni00B9 (U+00B9): L<<375.0,853.0>--<413.0,850.0>> -> L<<413.0,850.0>--<454.0,850.0>>

	* uni0409 (U+0409): L<<270.0,804.0>--<315.0,800.0>> -> L<<315.0,800.0>--<503.0,800.0>>

	* uni0422 (U+0422): L<<235.0,800.0>--<235.0,800.0>> -> L<<235.0,800.0>--<678.0,800.0>>

	* uni0459 (U+0459): L<<231.0,622.0>--<276.0,618.0>> -> L<<276.0,618.0>--<465.0,618.0>>

	* uni0490 (U+0490): L<<675.0,942.0>--<646.0,800.0>> -> L<<646.0,800.0>--<629.0,715.0>>

	* uni0491 (U+0491): L<<643.0,760.0>--<614.0,618.0>> -> L<<614.0,618.0>--<596.0,533.0>>

	* uni04A4 (U+04A4): L<<551.0,814.0>--<551.0,814.0>> -> L<<551.0,814.0>--<761.0,814.0>>

	* uni04AC (U+04AC): L<<235.0,800.0>--<235.0,800.0>> -> L<<235.0,800.0>--<678.0,800.0>>

	* uni04B0 (U+04B0): L<<129.0,295.0>--<252.0,295.0>> -> L<<252.0,295.0>--<252.0,295.0>>

	* uni04B0 (U+04B0): L<<344.0,295.0>--<344.0,295.0>> -> L<<344.0,295.0>--<472.0,295.0>>

	* uni2081 (U+2081): L<<276.0,384.0>--<314.0,381.0>> -> L<<314.0,381.0>--<355.0,381.0>>

	* uni2150 (U+2150): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* uni2151 (U+2151): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* uni2152 (U+2152): L<<225.0,384.0>--<261.0,381.0>> -> L<<261.0,381.0>--<303.0,381.0>>

	* uni2153 (U+2153): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* uni2155 (U+2155): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* uni2159 (U+2159): L<<209.0,853.0>--<247.0,850.0>> -> L<<247.0,850.0>--<288.0,850.0>>

	* uni215F (U+215F): L<<206.0,853.0>--<244.0,850.0>> -> L<<244.0,850.0>--<285.0,850.0>>

	* uni21F6 (U+21F6): L<<288.0,270.0>--<343.0,311.0>> -> L<<343.0,311.0>--<368.0,329.0>>

	* uni25C1 (U+25C1): L<<530.0,81.0>--<450.0,129.0>> -> L<<450.0,129.0>--<53.0,370.0>>

	* uni25C3 (U+25C3): L<<440.0,190.0>--<372.0,231.0>> -> L<<372.0,231.0>--<143.0,370.0>>

	* uni25C5 (U+25C5): L<<530.0,171.0>--<453.0,203.0>> -> L<<453.0,203.0>--<39.0,370.0>>

	* uniE0A1 (U+E0A1): L<<300.0,34.0>--<303.0,-34.0>> -> L<<303.0,-34.0>--<303.0,-147.0>>

	* uniE0A1 (U+E0A1): L<<377.0,140.0>--<373.0,226.0>> -> L<<373.0,226.0>--<373.0,322.0>> 

	* xi (U+03BE): L<<639.0,800.0>--<631.0,762.0>> -> L<<631.0,762.0>--<626.0,718.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* aacute (U+00E1): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* abreve (U+0103): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* acircumflex (U+00E2): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* adieresis (U+00E4): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* agrave (U+00E0): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* amacron (U+0101): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* aogonek (U+0105): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* aring (U+00E5): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* atilde (U+00E3): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* eta (U+03B7): L<<130.0,470.0>--<151.0,486.0>>/L<<151.0,486.0>--<132.0,474.0>> = 5.028303963405733

	* etatonos (U+03AE): L<<130.0,470.0>--<151.0,486.0>>/L<<151.0,486.0>--<132.0,474.0>> = 5.028303963405733

	* u (U+0075): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uacute (U+00FA): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* ubreve (U+016D): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* ucircumflex (U+00FB): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* udieresis (U+00FC): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* ugrave (U+00F9): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uhorn (U+01B0): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uhungarumlaut (U+0171): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* umacron (U+016B): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni01CE (U+01CE): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni01D4 (U+01D4): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni01D6 (U+01D6): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni01D8 (U+01D8): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni01DA (U+01DA): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni01DC (U+01DC): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni040D (U+040D): B<<452.5,119.0>-<446.0,83.0>-<446.0,84.0>>/B<<446.0,84.0>-<445.0,71.0>-<462.0,71.0>> = 4.398705354995508

	* uni0411 (U+0411): B<<109.0,227.5>-<118.0,264.0>-<129.0,308.0>>/B<<129.0,308.0>-<97.0,245.0>-<93.0,162.0>> = 12.891434383114033

	* uni0411 (U+0411): B<<129.0,308.0>-<97.0,245.0>-<93.0,162.0>>/B<<93.0,162.0>-<100.0,191.0>-<109.0,227.5>> = 10.811326726541196

	* uni0418 (U+0418): B<<452.5,119.0>-<446.0,83.0>-<446.0,84.0>>/B<<446.0,84.0>-<445.0,71.0>-<462.0,71.0>> = 4.398705354995508

	* uni0419 (U+0419): B<<452.5,119.0>-<446.0,83.0>-<446.0,84.0>>/B<<446.0,84.0>-<445.0,71.0>-<462.0,71.0>> = 4.398705354995508

	* uni041C (U+041C): B<<168.5,153.0>-<166.0,243.0>-<167.0,396.0>>/B<<167.0,396.0>-<146.0,287.0>-<131.5,213.5>> = 10.530545158511565

	* uni041C (U+041C): B<<411.5,171.5>-<435.0,268.0>-<473.0,424.0>>/B<<473.0,424.0>-<448.0,366.0>-<427.5,318.0>> = 9.627658769289505

	* uni0426 (U+0426): B<<452.5,119.0>-<446.0,83.0>-<446.0,84.0>>/B<<446.0,84.0>-<445.0,71.0>-<462.0,71.0>> = 4.398705354995508

	* uni0428 (U+0428): B<<490.0,124.5>-<484.0,83.0>-<484.0,84.0>>/B<<484.0,84.0>-<483.0,71.0>-<500.0,71.0>> = 4.398705354995508

	* uni0429 (U+0429): B<<490.0,124.5>-<484.0,83.0>-<484.0,84.0>>/B<<484.0,84.0>-<483.0,71.0>-<500.0,71.0>> = 4.398705354995508

	* uni0430 (U+0430): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni0438 (U+0438): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni0439 (U+0439): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni043C (U+043C): B<<394.5,104.5>-<405.0,157.0>-<426.0,246.0>>/B<<426.0,246.0>-<389.0,170.0>-<356.5,111.0>> = 12.682372219244682

	* uni0446 (U+0446): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni045D (U+045D): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni045F (U+045F): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni0495 (U+0495): B<<187.5,232.0>-<150.0,197.0>-<132.0,108.0>>/L<<132.0,108.0>--<143.0,168.0>> = 1.0448234499568467

	* uni0495 (U+0495): L<<132.0,108.0>--<143.0,168.0>>/L<<143.0,168.0>--<108.0,0.0>> = 1.3794311165512716

	* uni04A6 (U+04A6): B<<370.0,372.0>-<342.0,337.0>-<323.0,248.0>>/L<<323.0,248.0>--<326.0,264.0>> = 1.4311296072544009

	* uni04A6 (U+04A6): L<<323.0,248.0>--<326.0,264.0>>/L<<326.0,264.0>--<270.0,0.0>> = 1.3564771680483239

	* uni04A7 (U+04A7): B<<342.0,232.0>-<309.0,197.0>-<290.0,108.0>>/L<<290.0,108.0>--<297.0,142.0>> = 0.4171508844683901

	* uni04A7 (U+04A7): L<<290.0,108.0>--<297.0,142.0>>/L<<297.0,142.0>--<267.0,0.0>> = 0.2956881782984543

	* uni04CD (U+04CD): B<<133.0,153.0>-<130.0,243.0>-<131.0,396.0>>/B<<131.0,396.0>-<111.0,287.0>-<96.5,213.5>> = 10.02285663571349

	* uni04CD (U+04CD): B<<382.5,201.0>-<405.0,291.0>-<438.0,424.0>>/B<<438.0,424.0>-<413.0,366.0>-<392.5,318.0>> = 9.382873272253692

	* uni04CE (U+04CE): B<<392.0,94.0>-<402.0,148.0>-<426.0,246.0>>/B<<426.0,246.0>-<389.0,170.0>-<356.5,111.0>> = 12.19798414976938

	* uni04D1 (U+04D1): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni04D3 (U+04D3): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni04E2 (U+04E2): B<<452.5,119.0>-<446.0,83.0>-<446.0,84.0>>/B<<446.0,84.0>-<445.0,71.0>-<462.0,71.0>> = 4.398705354995508

	* uni04E3 (U+04E3): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni04E4 (U+04E4): B<<452.5,119.0>-<446.0,83.0>-<446.0,84.0>>/B<<446.0,84.0>-<445.0,71.0>-<462.0,71.0>> = 4.398705354995508

	* uni04E5 (U+04E5): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EA1 (U+1EA1): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EA3 (U+1EA3): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EA5 (U+1EA5): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EA7 (U+1EA7): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EA9 (U+1EA9): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EAB (U+1EAB): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EAD (U+1EAD): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EAF (U+1EAF): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EB1 (U+1EB1): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EB3 (U+1EB3): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EB5 (U+1EB5): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EB7 (U+1EB7): B<<345.0,52.0>-<341.0,55.0>-<343.0,59.0>>/B<<343.0,59.0>-<313.0,24.0>-<275.5,5.0>> = 14.036243467926457

	* uni1EE5 (U+1EE5): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EE7 (U+1EE7): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EE9 (U+1EE9): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EEB (U+1EEB): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EED (U+1EED): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EEF (U+1EEF): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni1EF1 (U+1EF1): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uni2076 (U+2076): L<<321.0,698.0>--<317.0,696.0>>/B<<317.0,696.0>-<344.0,706.0>-<376.0,706.0>> = 6.24191434741498

	* uni2086 (U+2086): L<<222.0,229.0>--<218.0,227.0>>/B<<218.0,227.0>-<245.0,237.0>-<277.0,237.0>> = 6.24191434741498

	* uni2159 (U+2159): L<<379.0,229.0>--<375.0,227.0>>/B<<375.0,227.0>-<402.0,237.0>-<434.0,237.0>> = 6.24191434741498

	* uni215A (U+215A): L<<379.0,229.0>--<375.0,227.0>>/B<<375.0,227.0>-<402.0,237.0>-<434.0,237.0>> = 6.24191434741498

	* uogonek (U+0173): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635

	* uring (U+016F): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635 

	* utilde (U+0169): L<<368.0,91.0>--<374.0,103.0>>/B<<374.0,103.0>-<331.0,46.0>-<287.5,16.0>> = 10.465338428600635 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] VictorMono-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21DC	Contours detected: 2	Expected: 1

	- Glyph name: uni21DD	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment B<<234.0,400.0>-<226.0,394.0>-<220.0,388.0>>

	* m (U+006D) contains a short segment L<<124.0,618.0>--<124.0,592.0>>

	* sterling (U+00A3) contains a short segment B<<235.0,363.0>-<238.0,355.0>-<242.0,347.0>>

	* yen (U+00A5) contains a short segment L<<259.0,298.0>--<258.0,300.0>>

	* yen (U+00A5) contains a short segment L<<342.0,300.0>--<342.0,298.0>>

	* section (U+00A7) contains a short segment L<<284.0,106.0>--<284.0,106.0>>

	* section (U+00A7) contains a short segment L<<317.0,512.0>--<317.0,512.0>>

	* section (U+00A7) contains a short segment L<<317.0,433.0>--<317.0,433.0>>

	* uni00B9 (U+00B9) contains a short segment L<<264.0,850.0>--<264.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* germandbls (U+00DF) contains a short segment L<<253.0,463.0>--<279.0,463.0>>

	* OE (U+0152) contains a short segment L<<302.0,0.0>--<302.0,17.0>>

	* xi (U+03BE) contains a short segment B<<514.0,800.0>-<522.0,802.0>-<531.0,803.0>>

	* xi (U+03BE) contains a short segment L<<531.0,724.0>--<517.0,724.0>>

	* xi (U+03BE) contains a short segment B<<510.0,509.0>-<520.0,510.0>-<531.0,512.0>>

	* xi (U+03BE) contains a short segment B<<531.0,432.0>-<523.0,432.0>-<517.0,432.0>>

	* rho (U+03C1) contains a short segment L<<69.0,308.0>--<69.0,308.0>>

	* rho (U+03C1) contains a short segment L<<69.0,308.0>--<69.0,309.0>>

	* uni0404 (U+0404) contains a short segment L<<134.0,362.0>--<134.0,360.0>>

	* uni040E (U+040E) contains a short segment B<<325.0,206.0>-<327.0,213.0>-<329.0,221.0>>

	* uni0423 (U+0423) contains a short segment B<<325.0,206.0>-<327.0,213.0>-<329.0,221.0>>

	* uni042D (U+042D) contains a short segment L<<467.0,438.0>--<467.0,440.0>>

	* uni042E (U+042E) contains a short segment L<<184.0,438.0>--<184.0,440.0>>

	* uni043A (U+043A) contains a short segment B<<235.0,294.0>-<226.0,293.0>-<216.0,293.0>>

	* uni044A (U+044A) contains a short segment L<<199.0,542.0>--<198.0,542.0>>

	* uni044D (U+044D) contains a short segment L<<467.0,347.0>--<467.0,349.0>>

	* uni044E (U+044E) contains a short segment L<<184.0,347.0>--<184.0,349.0>>

	* uni0454 (U+0454) contains a short segment L<<134.0,271.0>--<134.0,269.0>>

	* uni045C (U+045C) contains a short segment B<<235.0,294.0>-<226.0,293.0>-<216.0,293.0>>

	* uni0464 (U+0464) contains a short segment L<<184.0,438.0>--<184.0,440.0>>

	* uni0464 (U+0464) contains a short segment L<<267.0,362.0>--<267.0,360.0>>

	* uni0465 (U+0465) contains a short segment L<<184.0,347.0>--<184.0,349.0>>

	* uni0465 (U+0465) contains a short segment L<<267.0,271.0>--<267.0,269.0>>

	* uni046A (U+046A) contains a short segment B<<288.0,446.0>-<294.0,447.0>-<300.0,447.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,447.0>-<306.0,447.0>-<312.0,446.0>>

	* uni046B (U+046B) contains a short segment B<<281.0,366.0>-<290.0,367.0>-<300.0,367.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,367.0>-<310.0,367.0>-<319.0,366.0>>

	* uni0494 (U+0494) contains a short segment B<<283.5,-193.5>-<270.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-107.0>-<270.0,-114.0>-<283.5,-117.0>>

	* uni049B (U+049B) contains a short segment B<<235.0,294.0>-<226.0,293.0>-<216.0,293.0>>

	* uni049F (U+049F) contains a short segment B<<241.0,294.0>-<232.0,293.0>-<223.0,293.0>>

	* uni04A1 (U+04A1) contains a short segment B<<235.0,294.0>-<226.0,293.0>-<216.0,293.0>>

	* uni04A6 (U+04A6) contains a short segment B<<393.5,-193.5>-<380.0,-191.0>-<371.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<371.0,-107.0>-<380.0,-114.0>-<393.5,-117.0>>

	* uni04A7 (U+04A7) contains a short segment B<<389.0,-193.5>-<377.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-107.0>-<377.0,-114.0>-<388.5,-117.0>>

	* uni04A8 (U+04A8) contains a short segment B<<278.0,62.0>-<279.0,62.0>-<279.0,62.0>>

	* uni04B0 (U+04B0) contains a short segment L<<259.0,297.0>--<259.0,298.0>>

	* uni04B0 (U+04B0) contains a short segment L<<342.0,298.0>--<342.0,297.0>>

	* uni04C3 (U+04C3) contains a short segment B<<255.5,-193.5>-<242.0,-191.0>-<232.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<232.0,-107.0>-<242.0,-114.0>-<255.5,-117.0>>

	* uni04C3 (U+04C3) contains a short segment L<<197.0,385.0>--<197.0,385.0>>

	* uni04C3 (U+04C3) contains a short segment L<<197.0,385.0>--<193.0,385.0>>

	* uni04E8 (U+04E8) contains a short segment L<<467.0,438.0>--<467.0,440.0>>

	* uni04E8 (U+04E8) contains a short segment L<<134.0,362.0>--<134.0,360.0>>

	* uni04EA (U+04EA) contains a short segment L<<467.0,438.0>--<467.0,440.0>>

	* uni04EA (U+04EA) contains a short segment L<<134.0,362.0>--<134.0,360.0>>

	* uni04EC (U+04EC) contains a short segment L<<467.0,438.0>--<467.0,440.0>>

	* uni04ED (U+04ED) contains a short segment L<<467.0,347.0>--<467.0,349.0>>

	* uni04EE (U+04EE) contains a short segment B<<325.0,206.0>-<327.0,213.0>-<329.0,221.0>>

	* uni04F0 (U+04F0) contains a short segment B<<325.0,206.0>-<327.0,213.0>-<329.0,221.0>>

	* uni04F2 (U+04F2) contains a short segment B<<325.0,206.0>-<327.0,213.0>-<329.0,221.0>>

	* uni2081 (U+2081) contains a short segment L<<264.0,379.0>--<264.0,379.0>>

	* uni2150 (U+2150) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<81.0,850.0>--<81.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<225.0,488.0>--<225.0,483.0>>

	* uni2152 (U+2152) contains a short segment L<<216.0,379.0>--<216.0,379.0>>

	* uni2153 (U+2153) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni21C8 (U+21C8) contains a short segment L<<354.0,587.0>--<354.0,587.0>>

	* uni21C8 (U+21C8) contains a short segment L<<246.0,586.0>--<246.0,587.0>>

	* uni21CA (U+21CA) contains a short segment L<<246.0,213.0>--<246.0,214.0>>

	* uni21CA (U+21CA) contains a short segment L<<354.0,213.0>--<354.0,213.0>>

	* uni21CE (U+21CE) contains a short segment L<<199.0,211.0>--<201.0,209.0>>

	* uni21CE (U+21CE) contains a short segment L<<400.0,590.0>--<399.0,591.0>>

	* uni21F6 (U+21F6) contains a short segment L<<293.0,268.0>--<294.0,268.0>>

	* uni21F6 (U+21F6) contains a short segment L<<294.0,268.0>--<293.0,269.0>>

	* uni21F6 (U+21F6) contains a short segment L<<353.0,319.0>--<356.0,322.0>>

	* uni21F6 (U+21F6) contains a short segment L<<356.0,322.0>--<356.0,322.0>>

	* uni21F6 (U+21F6) contains a short segment L<<293.0,531.0>--<294.0,532.0>>

	* uni21F6 (U+21F6) contains a short segment L<<294.0,532.0>--<293.0,532.0>>

	* uni21F6 (U+21F6) contains a short segment L<<353.0,583.0>--<356.0,586.0>> 

	* uni21F6 (U+21F6) contains a short segment L<<356.0,586.0>--<356.0,586.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* oneeighth (U+215B): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* onehalf (U+00BD): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* onehalf (U+00BD): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* onequarter (U+00BC): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* onequarter (U+00BC): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni00B9 (U+00B9): L<<263.0,850.0>--<264.0,850.0>> -> L<<264.0,850.0>--<264.0,850.0>>

	* uni00B9 (U+00B9): L<<264.0,850.0>--<264.0,850.0>> -> L<<264.0,850.0>--<337.0,850.0>>

	* uni04C3 (U+04C3): L<<197.0,385.0>--<193.0,385.0>> -> L<<193.0,385.0>--<136.0,385.0>>

	* uni2081 (U+2081): L<<263.0,379.0>--<264.0,379.0>> -> L<<264.0,379.0>--<264.0,379.0>>

	* uni2081 (U+2081): L<<264.0,379.0>--<264.0,379.0>> -> L<<264.0,379.0>--<337.0,379.0>>

	* uni2150 (U+2150): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2150 (U+2150): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni2151 (U+2151): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2151 (U+2151): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni2152 (U+2152): L<<215.0,379.0>--<216.0,379.0>> -> L<<216.0,379.0>--<216.0,379.0>>

	* uni2152 (U+2152): L<<216.0,379.0>--<216.0,379.0>> -> L<<216.0,379.0>--<288.0,379.0>>

	* uni2152 (U+2152): L<<80.0,850.0>--<81.0,850.0>> -> L<<81.0,850.0>--<81.0,850.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<81.0,850.0>> -> L<<81.0,850.0>--<154.0,850.0>>

	* uni2153 (U+2153): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2153 (U+2153): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni2155 (U+2155): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2155 (U+2155): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni2159 (U+2159): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2159 (U+2159): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni215F (U+215F): L<<94.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<95.0,850.0>>

	* uni215F (U+215F): L<<95.0,850.0>--<95.0,850.0>> -> L<<95.0,850.0>--<168.0,850.0>>

	* uni21F6 (U+21F6): L<<293.0,269.0>--<353.0,319.0>> -> L<<353.0,319.0>--<356.0,322.0>>

	* uni21F6 (U+21F6): L<<293.0,532.0>--<353.0,583.0>> -> L<<353.0,583.0>--<356.0,586.0>>

	* uni25C1 (U+25C1): L<<526.0,89.0>--<452.0,133.0>> -> L<<452.0,133.0>--<61.0,370.0>>

	* uni25C3 (U+25C3): L<<436.0,198.0>--<374.0,235.0>> -> L<<374.0,235.0>--<151.0,370.0>>

	* uni25C5 (U+25C5): L<<526.0,177.0>--<455.0,207.0>> -> L<<455.0,207.0>--<50.0,370.0>>

	* uniE0A1 (U+E0A1): L<<294.0,60.0>--<299.0,-34.0>> -> L<<299.0,-34.0>--<299.0,-143.0>>

	* uniE0A1 (U+E0A1): L<<383.0,114.0>--<378.0,226.0>> -> L<<378.0,226.0>--<378.0,318.0>> 

	* yen (U+00A5): L<<342.0,300.0>--<342.0,298.0>> -> L<<342.0,298.0>--<342.0,238.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<310.0,106.0>-<297.0,105.0>-<284.0,106.0>>/L<<284.0,106.0>--<284.0,106.0>> = 4.398705354995508

	* section (U+00A7): B<<400.0,400.5>-<375.0,430.0>-<317.0,433.0>>/L<<317.0,433.0>--<317.0,433.0>> = 2.9609361341637563

	* section (U+00A7): L<<284.0,106.0>--<284.0,106.0>>/B<<284.0,106.0>-<184.0,110.0>-<138.5,160.5>> = 2.2906100426384346 

	* section (U+00A7): L<<317.0,433.0>--<317.0,433.0>>/B<<317.0,433.0>-<262.0,435.0>-<231.0,424.0>> = 2.082565279730795 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni04B8 (U+04B8): L<<430.0,0.0>--<429.0,339.0>>

	* uni04B9 (U+04B9): L<<430.0,0.0>--<429.0,223.0>>

	* uni2196 (U+2196): L<<47.0,683.0>--<381.0,682.0>>

	* uni2197 (U+2197): L<<219.0,682.0>--<553.0,683.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<361.0,682.0>>

	* uni21D7 (U+21D7): L<<239.0,682.0>--<573.0,683.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<239.0,118.0>> 

	* uni21D9 (U+21D9): L<<361.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] VictorMono-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* yen (U+00A5) contains a short segment L<<275.0,308.0>--<274.0,310.0>>

	* yen (U+00A5) contains a short segment L<<326.0,310.0>--<325.0,308.0>>

	* uni00B9 (U+00B9) contains a short segment L<<276.0,850.0>--<276.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* germandbls (U+00DF) contains a short segment L<<269.0,448.0>--<279.0,448.0>>

	* uni03D7 (U+03D7) contains a short segment L<<76.0,0.0>--<90.0,21.0>>

	* uni03D7 (U+03D7) contains a short segment B<<100.0,586.0>-<92.0,586.0>-<78.0,578.0>>

	* uni0404 (U+0404) contains a short segment L<<117.0,377.0>--<117.0,360.0>>

	* uni042D (U+042D) contains a short segment L<<483.0,423.0>--<483.0,440.0>>

	* uni042E (U+042E) contains a short segment L<<194.0,423.0>--<194.0,440.0>>

	* uni043A (U+043A) contains a short segment B<<249.0,308.0>-<243.0,308.0>-<236.0,308.0>>

	* uni044D (U+044D) contains a short segment L<<483.0,332.0>--<483.0,349.0>>

	* uni044E (U+044E) contains a short segment L<<194.0,332.0>--<194.0,349.0>>

	* uni0454 (U+0454) contains a short segment L<<117.0,286.0>--<117.0,269.0>>

	* uni045C (U+045C) contains a short segment B<<249.0,308.0>-<243.0,308.0>-<236.0,308.0>>

	* uni0464 (U+0464) contains a short segment L<<194.0,423.0>--<194.0,440.0>>

	* uni0464 (U+0464) contains a short segment L<<244.0,377.0>--<244.0,360.0>>

	* uni0465 (U+0465) contains a short segment L<<194.0,332.0>--<194.0,349.0>>

	* uni0465 (U+0465) contains a short segment L<<244.0,286.0>--<244.0,269.0>>

	* uni046A (U+046A) contains a short segment B<<278.0,431.0>-<289.0,432.0>-<300.0,432.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,432.0>-<311.0,432.0>-<322.0,431.0>>

	* uni046B (U+046B) contains a short segment B<<277.0,351.0>-<288.0,352.0>-<300.0,352.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,352.0>-<312.0,352.0>-<323.0,351.0>>

	* uni0494 (U+0494) contains a short segment B<<284.5,-193.5>-<271.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-138.0>-<271.0,-145.0>-<284.5,-147.5>>

	* uni0497 (U+0497) contains a short segment L<<538.0,0.0>--<538.0,3.0>>

	* uni049B (U+049B) contains a short segment B<<249.0,308.0>-<243.0,308.0>-<236.0,308.0>>

	* uni049D (U+049D) contains a short segment L<<249.0,308.0>--<249.0,308.0>>

	* uni049F (U+049F) contains a short segment B<<249.0,308.0>-<243.0,308.0>-<236.0,308.0>>

	* uni04A1 (U+04A1) contains a short segment B<<249.0,308.0>-<243.0,308.0>-<236.0,308.0>>

	* uni04A6 (U+04A6) contains a short segment B<<411.5,-193.5>-<398.0,-191.0>-<387.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<387.0,-138.0>-<398.0,-145.0>-<411.5,-147.5>>

	* uni04A7 (U+04A7) contains a short segment B<<391.5,-193.5>-<378.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-138.0>-<378.0,-145.0>-<391.5,-147.5>>

	* uni04A8 (U+04A8) contains a short segment B<<423.0,33.0>-<432.0,32.0>-<442.0,32.0>>

	* uni04A9 (U+04A9) contains a short segment B<<423.0,33.0>-<432.0,32.0>-<442.0,32.0>>

	* uni04A9 (U+04A9) contains a short segment B<<279.0,32.0>-<289.0,32.0>-<299.0,33.0>>

	* uni04C3 (U+04C3) contains a short segment B<<257.5,-193.5>-<244.0,-191.0>-<233.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<233.0,-138.0>-<244.0,-145.0>-<257.5,-147.5>>

	* uni04EC (U+04EC) contains a short segment L<<483.0,423.0>--<483.0,440.0>>

	* uni04ED (U+04ED) contains a short segment L<<483.0,332.0>--<483.0,349.0>>

	* uni2081 (U+2081) contains a short segment L<<276.0,374.0>--<276.0,374.0>>

	* lira (U+20A4) contains a short segment B<<140.0,492.0>-<140.0,503.0>-<140.0,516.0>>

	* lira (U+20A4) contains a short segment B<<190.0,516.0>-<190.0,503.0>-<190.0,492.0>>

	* uni2150 (U+2150) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<242.0,374.0>--<242.0,374.0>>

	* uni2153 (U+2153) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<110.0,850.0>--<110.0,850.0>>

	* uni21F6 (U+21F6) contains a short segment L<<322.0,261.0>--<323.0,262.0>>

	* uni21F6 (U+21F6) contains a short segment L<<323.0,262.0>--<322.0,262.0>>

	* uni21F6 (U+21F6) contains a short segment L<<322.0,538.0>--<323.0,539.0>>

	* uni21F6 (U+21F6) contains a short segment L<<323.0,539.0>--<322.0,539.0>>

	* uni251E (U+251E) contains a short segment L<<275.0,375.0>--<250.0,375.0>>

	* uni251F (U+251F) contains a short segment L<<250.0,425.0>--<275.0,425.0>>

	* uni2521 (U+2521) contains a short segment L<<275.0,350.0>--<250.0,350.0>>

	* uni2522 (U+2522) contains a short segment L<<250.0,450.0>--<275.0,450.0>>

	* uni2526 (U+2526) contains a short segment L<<350.0,375.0>--<325.0,375.0>>

	* uni2527 (U+2527) contains a short segment L<<325.0,425.0>--<350.0,425.0>>

	* uni2529 (U+2529) contains a short segment L<<350.0,350.0>--<325.0,350.0>>

	* uni252A (U+252A) contains a short segment L<<325.0,450.0>--<350.0,450.0>>

	* uni2543 (U+2543) contains a short segment L<<350.0,375.0>--<350.0,350.0>>

	* uni2543 (U+2543) contains a short segment L<<350.0,350.0>--<325.0,350.0>>

	* uni2544 (U+2544) contains a short segment L<<275.0,350.0>--<250.0,350.0>>

	* uni2544 (U+2544) contains a short segment L<<250.0,350.0>--<250.0,375.0>>

	* uni2545 (U+2545) contains a short segment L<<325.0,450.0>--<350.0,450.0>>

	* uni2545 (U+2545) contains a short segment L<<350.0,450.0>--<350.0,425.0>>

	* uni2546 (U+2546) contains a short segment L<<250.0,425.0>--<250.0,450.0>>

	* uni2546 (U+2546) contains a short segment L<<250.0,450.0>--<275.0,450.0>>

	* uni2573 (U+2573) contains a short segment L<<0.0,1200.0>--<27.0,1200.0>>

	* uni2573 (U+2573) contains a short segment L<<573.0,1200.0>--<600.0,1200.0>>

	* uni2573 (U+2573) contains a short segment L<<600.0,-400.0>--<573.0,-400.0>> 

	* uni2573 (U+2573) contains a short segment L<<27.0,-400.0>--<0.0,-400.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* oneeighth (U+215B): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* onehalf (U+00BD): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* onehalf (U+00BD): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* onequarter (U+00BC): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* onequarter (U+00BC): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni00B9 (U+00B9): L<<275.0,850.0>--<276.0,850.0>> -> L<<276.0,850.0>--<276.0,850.0>>

	* uni00B9 (U+00B9): L<<276.0,850.0>--<276.0,850.0>> -> L<<276.0,850.0>--<326.0,850.0>>

	* uni2081 (U+2081): L<<275.0,374.0>--<276.0,374.0>> -> L<<276.0,374.0>--<276.0,374.0>>

	* uni2081 (U+2081): L<<276.0,374.0>--<276.0,374.0>> -> L<<276.0,374.0>--<326.0,374.0>>

	* uni2150 (U+2150): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* uni2150 (U+2150): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni2151 (U+2151): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* uni2151 (U+2151): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni2152 (U+2152): L<<241.0,374.0>--<242.0,374.0>> -> L<<242.0,374.0>--<242.0,374.0>>

	* uni2152 (U+2152): L<<242.0,374.0>--<242.0,374.0>> -> L<<242.0,374.0>--<292.0,374.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152): L<<82.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<132.0,850.0>>

	* uni2153 (U+2153): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* uni2153 (U+2153): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni2155 (U+2155): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* uni2155 (U+2155): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni2159 (U+2159): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* uni2159 (U+2159): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni215F (U+215F): L<<109.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<110.0,850.0>>

	* uni215F (U+215F): L<<110.0,850.0>--<110.0,850.0>> -> L<<110.0,850.0>--<160.0,850.0>>

	* uni25C1 (U+25C1): L<<509.0,117.0>--<461.0,146.0>> -> L<<461.0,146.0>--<91.0,370.0>>

	* uni25C3 (U+25C3): L<<419.0,226.0>--<383.0,248.0>> -> L<<383.0,248.0>--<181.0,370.0>>

	* uni25C5 (U+25C5): L<<509.0,201.0>--<461.0,221.0>> -> L<<461.0,221.0>--<91.0,370.0>>

	* uniE0A1 (U+E0A1): L<<273.0,152.0>--<282.0,-35.0>> -> L<<282.0,-35.0>--<282.0,-128.0>> 

	* uniE0A1 (U+E0A1): L<<404.0,22.0>--<394.0,227.0>> -> L<<394.0,227.0>--<394.0,303.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* alpha (U+03B1): B<<428.5,461.5>-<438.0,413.0>-<443.0,361.0>>/B<<443.0,361.0>-<455.0,466.0>-<460.0,618.0>> = 12.01212630878437

	* alphatonos (U+03AC): B<<428.5,461.5>-<438.0,413.0>-<443.0,361.0>>/B<<443.0,361.0>-<455.0,466.0>-<460.0,618.0>> = 12.01212630878437 

	* uni04A6 (U+04A6): L<<317.0,800.0>--<317.0,406.0>>/B<<317.0,406.0>-<327.0,455.0>-<353.0,473.5>> = 11.534620653644708 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<275.0,803.0>--<84.0,804.0>>

	* uni2077 (U+2077): L<<365.0,803.0>--<174.0,804.0>>

	* uni2087 (U+2087): L<<365.0,327.0>--<174.0,328.0>>

	* uni2150 (U+2150): L<<538.0,327.0>--<347.0,328.0>>

	* uni2196 (U+2196): L<<363.0,634.0>--<129.0,636.0>>

	* uni2196 (U+2196): L<<47.0,683.0>--<363.0,682.0>>

	* uni2196 (U+2196): L<<48.0,366.0>--<47.0,683.0>>

	* uni2196 (U+2196): L<<93.0,601.0>--<95.0,367.0>>

	* uni2197 (U+2197): L<<237.0,682.0>--<553.0,683.0>>

	* uni2197 (U+2197): L<<471.0,636.0>--<237.0,634.0>>

	* uni2197 (U+2197): L<<505.0,367.0>--<507.0,601.0>>

	* uni2197 (U+2197): L<<553.0,683.0>--<552.0,366.0>>

	* uni2198 (U+2198): L<<237.0,204.0>--<471.0,202.0>>

	* uni2198 (U+2198): L<<507.0,237.0>--<505.0,471.0>>

	* uni2198 (U+2198): L<<552.0,472.0>--<553.0,155.0>>

	* uni2198 (U+2198): L<<553.0,155.0>--<237.0,156.0>>

	* uni2199 (U+2199): L<<129.0,202.0>--<363.0,204.0>>

	* uni2199 (U+2199): L<<363.0,156.0>--<47.0,155.0>>

	* uni2199 (U+2199): L<<47.0,155.0>--<48.0,472.0>>

	* uni2199 (U+2199): L<<95.0,471.0>--<93.0,237.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<343.0,682.0>>

	* uni21D6 (U+21D6): L<<28.0,366.0>--<27.0,683.0>>

	* uni21D7 (U+21D7): L<<257.0,682.0>--<573.0,683.0>>

	* uni21D7 (U+21D7): L<<573.0,683.0>--<572.0,366.0>>

	* uni21D8 (U+21D8): L<<572.0,434.0>--<573.0,117.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<257.0,118.0>>

	* uni21D9 (U+21D9): L<<27.0,117.0>--<28.0,434.0>> 

	* uni21D9 (U+21D9): L<<343.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] VictorMono-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<372.0,803.0>--<404.0,800.0>> -> L<<404.0,800.0>--<437.0,800.0>>

	* oneeighth (U+215B): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* onehalf (U+00BD): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* onequarter (U+00BC): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni00B9 (U+00B9): L<<384.0,852.0>--<410.0,850.0>> -> L<<410.0,850.0>--<446.0,850.0>>

	* uni0409 (U+0409): L<<270.0,803.0>--<302.0,800.0>> -> L<<302.0,800.0>--<479.0,800.0>>

	* uni0459 (U+0459): L<<231.0,621.0>--<263.0,618.0>> -> L<<263.0,618.0>--<441.0,618.0>>

	* uni0490 (U+0490): L<<663.0,931.0>--<636.0,800.0>> -> L<<636.0,800.0>--<624.0,739.0>>

	* uni0491 (U+0491): L<<628.0,749.0>--<601.0,618.0>> -> L<<601.0,618.0>--<588.0,557.0>>

	* uni04A4 (U+04A4): L<<560.0,814.0>--<560.0,814.0>> -> L<<560.0,814.0>--<759.0,814.0>>

	* uni04B0 (U+04B0): L<<124.0,303.0>--<267.0,303.0>> -> L<<267.0,303.0>--<267.0,303.0>>

	* uni04B0 (U+04B0): L<<333.0,303.0>--<333.0,303.0>> -> L<<333.0,303.0>--<477.0,303.0>>

	* uni04C3 (U+04C3): L<<233.0,393.0>--<230.0,393.0>> -> L<<230.0,393.0>--<156.0,393.0>>

	* uni051D (U+051D): L<<356.0,425.0>--<356.0,423.0>> -> L<<356.0,423.0>--<385.0,127.0>>

	* uni2081 (U+2081): L<<284.0,379.0>--<310.0,377.0>> -> L<<310.0,377.0>--<346.0,377.0>>

	* uni2150 (U+2150): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* uni2151 (U+2151): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* uni2152 (U+2152): L<<243.0,379.0>--<269.0,377.0>> -> L<<269.0,377.0>--<305.0,377.0>>

	* uni2153 (U+2153): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* uni2155 (U+2155): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* uni2159 (U+2159): L<<218.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<280.0,850.0>>

	* uni215F (U+215F): L<<217.0,852.0>--<243.0,850.0>> -> L<<243.0,850.0>--<279.0,850.0>>

	* uni25C1 (U+25C1): L<<517.0,103.0>--<457.0,140.0>> -> L<<457.0,140.0>--<77.0,370.0>>

	* uni25C3 (U+25C3): L<<427.0,212.0>--<379.0,242.0>> -> L<<379.0,242.0>--<167.0,370.0>>

	* uni25C5 (U+25C5): L<<517.0,189.0>--<458.0,214.0>> -> L<<458.0,214.0>--<71.0,370.0>>

	* uniE0A1 (U+E0A1): L<<283.0,107.0>--<290.0,-35.0>> -> L<<290.0,-35.0>--<290.0,-135.0>>

	* uniE0A1 (U+E0A1): L<<394.0,67.0>--<386.0,227.0>> -> L<<386.0,227.0>--<386.0,310.0>>

	* w (U+0077): L<<356.0,425.0>--<356.0,423.0>> -> L<<356.0,423.0>--<385.0,127.0>>

	* wacute (U+1E83): L<<356.0,425.0>--<356.0,423.0>> -> L<<356.0,423.0>--<385.0,127.0>>

	* wcircumflex (U+0175): L<<356.0,425.0>--<356.0,423.0>> -> L<<356.0,423.0>--<385.0,127.0>>

	* wdieresis (U+1E85): L<<356.0,425.0>--<356.0,423.0>> -> L<<356.0,423.0>--<385.0,127.0>> 

	* wgrave (U+1E81): L<<356.0,425.0>--<356.0,423.0>> -> L<<356.0,423.0>--<385.0,127.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* aacute (U+00E1): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* abreve (U+0103): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* acircumflex (U+00E2): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* adieresis (U+00E4): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* agrave (U+00E0): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* amacron (U+0101): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* aogonek (U+0105): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* aring (U+00E5): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* atilde (U+00E3): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* beta (U+03B2): B<<74.0,315.0>-<78.0,338.0>-<84.0,363.0>>/L<<84.0,363.0>--<84.0,362.0>> = 13.495733280795811

	* beta (U+03B2): L<<84.0,363.0>--<84.0,362.0>>/L<<84.0,362.0>--<140.0,625.0>> = 12.020347015582294

	* eta (U+03B7): L<<148.0,494.0>--<165.0,506.0>>/L<<165.0,506.0>--<150.0,496.0>> = 1.5275254422129318

	* etatonos (U+03AE): L<<148.0,494.0>--<165.0,506.0>>/L<<165.0,506.0>--<150.0,496.0>> = 1.5275254422129318

	* section (U+00A7): L<<253.0,113.0>--<253.0,113.0>>/B<<253.0,113.0>-<150.0,115.0>-<116.0,167.0>> = 1.1123996162975507

	* uni01CE (U+01CE): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni040C (U+040C): B<<149.5,419.0>-<180.0,554.0>-<224.0,751.0>>/B<<224.0,751.0>-<223.0,749.0>-<222.0,751.0>> = 13.974668231542802

	* uni0411 (U+0411): B<<79.5,89.0>-<79.0,72.0>-<78.0,62.0>>/B<<78.0,62.0>-<79.0,68.0>-<81.0,75.5>> = 3.7517290705259434

	* uni0412 (U+0412): B<<109.0,213.5>-<135.0,340.0>-<182.0,558.0>>/B<<182.0,558.0>-<156.0,501.0>-<138.0,437.0>> = 12.353108912725059

	* uni0412 (U+0412): B<<84.5,113.5>-<83.0,80.0>-<84.0,73.0>>/B<<84.0,73.0>-<83.0,87.0>-<109.0,213.5>> = 4.044485574180925

	* uni041A (U+041A): B<<149.5,419.0>-<180.0,554.0>-<224.0,751.0>>/B<<224.0,751.0>-<223.0,749.0>-<222.0,751.0>> = 13.974668231542802

	* uni041C (U+041C): B<<171.5,253.5>-<172.0,352.0>-<174.0,497.0>>/B<<174.0,497.0>-<144.0,354.0>-<122.5,256.0>> = 11.058029735985247

	* uni041C (U+041C): B<<455.5,280.5>-<479.0,385.0>-<512.0,533.0>>/B<<512.0,533.0>-<469.0,433.0>-<437.0,355.5>> = 10.697913002378257

	* uni0430 (U+0430): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni0436 (U+0436): L<<392.0,618.0>--<299.0,199.0>>/L<<299.0,199.0>--<396.0,391.0>> = 14.288957784714055

	* uni043C (U+043C): B<<151.0,165.5>-<144.0,232.0>-<139.0,336.0>>/B<<139.0,336.0>-<117.0,225.0>-<101.5,156.0>> = 13.963118529145326

	* uni043C (U+043C): B<<430.0,181.0>-<444.0,248.0>-<467.0,349.0>>/B<<467.0,349.0>-<421.0,248.0>-<379.0,165.5>> = 11.657898060260559

	* uni0495 (U+0495): B<<156.0,223.0>-<135.0,186.0>-<121.0,123.0>>/L<<121.0,123.0>--<132.0,172.0>> = 0.12374879140829186

	* uni0495 (U+0495): L<<121.0,123.0>--<132.0,172.0>>/L<<132.0,172.0>--<95.0,0.0>> = 0.5123085402796489

	* uni0497 (U+0497): L<<392.0,618.0>--<299.0,199.0>>/L<<299.0,199.0>--<396.0,391.0>> = 14.288957784714055

	* uni049A (U+049A): B<<149.5,419.0>-<180.0,554.0>-<224.0,751.0>>/B<<224.0,751.0>-<223.0,749.0>-<222.0,751.0>> = 13.974668231542802

	* uni049C (U+049C): B<<113.5,419.0>-<144.0,554.0>-<188.0,751.0>>/B<<188.0,751.0>-<187.0,749.0>-<186.0,751.0>> = 13.974668231542802

	* uni04A6 (U+04A6): B<<346.5,363.0>-<328.0,326.0>-<314.0,263.0>>/L<<314.0,263.0>--<323.0,304.0>> = 0.1480507803440259

	* uni04A6 (U+04A6): L<<314.0,263.0>--<323.0,304.0>>/L<<323.0,304.0>--<258.0,0.0>> = 0.3117449767808557

	* uni04A6 (U+04A6): L<<428.0,800.0>--<349.0,426.0>>/B<<349.0,426.0>-<368.0,465.0>-<393.0,478.5>> = 14.047137316736588

	* uni04A7 (U+04A7): B<<318.0,223.0>-<299.0,186.0>-<285.0,123.0>>/L<<285.0,123.0>--<288.0,136.0>> = 0.4658090827654013

	* uni04A7 (U+04A7): L<<285.0,123.0>--<288.0,136.0>>/L<<288.0,136.0>--<259.0,0.0>> = 0.9574144715507428

	* uni04C2 (U+04C2): L<<392.0,618.0>--<299.0,199.0>>/L<<299.0,199.0>--<396.0,391.0>> = 14.288957784714055

	* uni04CD (U+04CD): B<<151.5,253.5>-<152.0,352.0>-<154.0,497.0>>/B<<154.0,497.0>-<124.0,354.0>-<102.5,256.0>> = 11.058029735985247

	* uni04CD (U+04CD): B<<427.0,236.5>-<453.0,352.0>-<493.0,533.0>>/B<<493.0,533.0>-<449.0,433.0>-<417.0,355.5>> = 11.287738572312918

	* uni04CE (U+04CE): B<<151.0,165.5>-<144.0,232.0>-<139.0,336.0>>/B<<139.0,336.0>-<117.0,225.0>-<101.5,156.0>> = 13.963118529145326

	* uni04CE (U+04CE): B<<426.5,163.5>-<441.0,234.0>-<467.0,349.0>>/B<<467.0,349.0>-<421.0,248.0>-<379.0,165.5>> = 11.747034139233925

	* uni04D1 (U+04D1): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni04D3 (U+04D3): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni04DD (U+04DD): L<<392.0,618.0>--<299.0,199.0>>/L<<299.0,199.0>--<396.0,391.0>> = 14.288957784714055

	* uni1EA1 (U+1EA1): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EA3 (U+1EA3): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EA5 (U+1EA5): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EA7 (U+1EA7): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EA9 (U+1EA9): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EAB (U+1EAB): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EAD (U+1EAD): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EAF (U+1EAF): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EB1 (U+1EB1): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EB3 (U+1EB3): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209

	* uni1EB5 (U+1EB5): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209 

	* uni1EB7 (U+1EB7): B<<356.5,73.5>-<358.0,86.0>-<361.0,93.0>>/B<<361.0,93.0>-<332.0,44.0>-<288.5,15.0>> = 7.420014895261209 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] VictorMono-ExtraLightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Victor Mono ExtraLight' / SUBFAMILY_NAME = 'Italic'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 5	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 5	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<376.0,802.0>--<404.0,800.0>> -> L<<404.0,800.0>--<433.0,800.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni0409 (U+0409): L<<270.0,802.0>--<298.0,800.0>> -> L<<298.0,800.0>--<471.0,800.0>>

	* uni0459 (U+0459): L<<231.0,620.0>--<259.0,618.0>> -> L<<259.0,618.0>--<433.0,618.0>>

	* uni0490 (U+0490): L<<660.0,928.0>--<633.0,800.0>> -> L<<633.0,800.0>--<623.0,747.0>>

	* uni0491 (U+0491): L<<624.0,746.0>--<597.0,618.0>> -> L<<597.0,618.0>--<585.0,565.0>>

	* uni049B (U+049B): L<<547.0,20.0>--<547.0,20.0>> -> L<<547.0,20.0>--<547.0,20.0>>

	* uni04A4 (U+04A4): L<<563.0,814.0>--<563.0,814.0>> -> L<<563.0,814.0>--<758.0,814.0>>

	* uni04B7 (U+04B7): L<<535.0,20.0>--<535.0,20.0>> -> L<<535.0,20.0>--<536.0,20.0>>

	* uni04C3 (U+04C3): L<<240.0,396.0>--<239.0,396.0>> -> L<<239.0,396.0>--<157.0,396.0>>

	* uni2152 (U+2152): L<<196.0,852.0>--<219.0,850.0>> -> L<<219.0,850.0>--<252.0,850.0>>

	* uni25A9 (U+25A9): L<<231.0,201.0>--<232.0,201.0>> -> L<<232.0,201.0>--<232.0,201.0>>

	* uni25A9 (U+25A9): L<<369.0,201.0>--<369.0,201.0>> -> L<<369.0,201.0>--<370.0,201.0>>

	* uni25C1 (U+25C1): L<<513.0,110.0>--<459.0,143.0>> -> L<<459.0,143.0>--<84.0,370.0>>

	* uni25C3 (U+25C3): L<<423.0,219.0>--<381.0,245.0>> -> L<<381.0,245.0>--<174.0,370.0>>

	* uni25C5 (U+25C5): L<<513.0,195.0>--<460.0,218.0>> -> L<<460.0,218.0>--<81.0,370.0>>

	* uniE0A1 (U+E0A1): L<<278.0,130.0>--<286.0,-35.0>> -> L<<286.0,-35.0>--<286.0,-132.0>>

	* uniE0A1 (U+E0A1): L<<399.0,44.0>--<390.0,227.0>> -> L<<390.0,227.0>--<390.0,307.0>>

	* xi (U+03BE): L<<550.0,449.0>--<550.0,449.0>> -> L<<550.0,449.0>--<550.0,449.0>>

	* xi (U+03BE): L<<611.0,747.0>--<611.0,747.0>> -> L<<611.0,747.0>--<611.0,747.0>> 

	* xi (U+03BE): L<<622.0,800.0>--<617.0,774.0>> -> L<<617.0,774.0>--<614.0,747.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* aacute (U+00E1): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* abreve (U+0103): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* acircumflex (U+00E2): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* adieresis (U+00E4): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* agrave (U+00E0): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* alpha (U+03B1): B<<460.5,478.5>-<462.0,434.0>-<458.0,386.0>>/B<<458.0,386.0>-<489.0,484.0>-<522.0,620.0>> = 12.789903135613704

	* alphatonos (U+03AC): B<<460.5,478.5>-<462.0,434.0>-<458.0,386.0>>/B<<458.0,386.0>-<489.0,484.0>-<522.0,620.0>> = 12.789903135613704

	* amacron (U+0101): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* aogonek (U+0105): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* aring (U+00E5): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* atilde (U+00E3): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* beta (U+03B2): B<<77.0,307.0>-<80.0,327.0>-<85.0,349.0>>/L<<85.0,349.0>--<85.0,348.0>> = 12.80426606528674

	* beta (U+03B2): L<<85.0,349.0>--<85.0,348.0>>/L<<85.0,348.0>--<144.0,624.0>> = 12.066399851159668

	* eta (U+03B7): L<<154.0,501.0>--<169.0,512.0>>/L<<169.0,512.0>--<156.0,503.0>> = 1.5586842062107429

	* etatonos (U+03AE): L<<154.0,501.0>--<169.0,512.0>>/L<<169.0,512.0>--<156.0,503.0>> = 1.5586842062107429

	* section (U+00A7): L<<258.0,116.0>--<258.0,116.0>>/B<<258.0,116.0>-<187.0,117.0>-<149.5,141.0>> = 0.8069294551021693

	* uni01CE (U+01CE): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni0411 (U+0411): B<<75.5,60.0>-<75.0,42.0>-<74.0,40.0>>/B<<74.0,40.0>-<76.0,45.0>-<89.5,94.0>> = 4.763641690726066

	* uni041C (U+041C): B<<172.5,268.5>-<173.0,373.0>-<176.0,527.0>>/B<<176.0,527.0>-<135.0,336.0>-<107.0,216.5>> = 10.999231411050573

	* uni041C (U+041C): B<<465.0,296.0>-<489.0,406.0>-<522.0,563.0>>/B<<522.0,563.0>-<474.0,451.0>-<438.5,365.5>> = 11.32832598206029

	* uni0430 (U+0430): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni0436 (U+0436): L<<388.0,618.0>--<293.0,179.0>>/L<<293.0,179.0>--<398.0,393.0>> = 13.924494197664945

	* uni043C (U+043C): B<<151.0,181.0>-<145.0,253.0>-<141.0,367.0>>/B<<141.0,367.0>-<116.0,246.0>-<99.0,171.0>> = 13.683264125905913

	* uni043C (U+043C): B<<439.5,196.5>-<455.0,269.0>-<479.0,380.0>>/B<<479.0,380.0>-<442.0,299.0>-<407.5,227.5>> = 12.349983661826617

	* uni0443 (U+0443): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni045E (U+045E): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni0495 (U+0495): B<<153.0,229.5>-<132.0,192.0>-<118.0,128.0>>/L<<118.0,128.0>--<128.0,176.0>> = 0.5707983463054168

	* uni0495 (U+0495): L<<118.0,128.0>--<128.0,176.0>>/L<<128.0,176.0>--<91.0,0.0>> = 0.10396138196181057

	* uni0497 (U+0497): L<<388.0,618.0>--<293.0,179.0>>/L<<293.0,179.0>--<398.0,393.0>> = 13.924494197664945

	* uni04A6 (U+04A6): B<<344.5,369.5>-<325.0,332.0>-<312.0,268.0>>/L<<312.0,268.0>--<331.0,359.0>> = 0.3114383301611489

	* uni04A6 (U+04A6): L<<312.0,268.0>--<331.0,359.0>>/L<<331.0,359.0>--<255.0,0.0>> = 0.15956043099486183

	* uni04A6 (U+04A6): L<<425.0,800.0>--<343.0,417.0>>/B<<343.0,417.0>-<363.0,461.0>-<389.5,476.5>> = 12.359414497075196

	* uni04C2 (U+04C2): L<<388.0,618.0>--<293.0,179.0>>/L<<293.0,179.0>--<398.0,393.0>> = 13.924494197664945

	* uni04CD (U+04CD): B<<158.0,268.5>-<159.0,373.0>-<161.0,527.0>>/B<<161.0,527.0>-<120.0,336.0>-<92.0,216.5>> = 11.371182599569133

	* uni04CD (U+04CD): B<<439.5,245.0>-<466.0,368.0>-<508.0,563.0>>/B<<508.0,563.0>-<459.0,451.0>-<424.0,365.5>> = 11.474436033434575

	* uni04CE (U+04CE): B<<151.0,181.0>-<145.0,253.0>-<141.0,367.0>>/B<<141.0,367.0>-<116.0,246.0>-<99.0,171.0>> = 13.683264125905913

	* uni04CE (U+04CE): B<<435.0,173.5>-<451.0,251.0>-<479.0,380.0>>/B<<479.0,380.0>-<442.0,299.0>-<407.5,227.5>> = 12.304119529526993

	* uni04D1 (U+04D1): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni04D3 (U+04D3): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni04DD (U+04DD): L<<388.0,618.0>--<293.0,179.0>>/L<<293.0,179.0>--<398.0,393.0>> = 13.924494197664945

	* uni04EF (U+04EF): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni04F1 (U+04F1): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni04F3 (U+04F3): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni1EA1 (U+1EA1): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EA3 (U+1EA3): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EA5 (U+1EA5): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EA7 (U+1EA7): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EA9 (U+1EA9): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EAB (U+1EAB): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EAD (U+1EAD): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EAF (U+1EAF): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EB1 (U+1EB1): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EB3 (U+1EB3): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EB5 (U+1EB5): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EB7 (U+1EB7): B<<359.0,46.0>-<358.0,84.0>-<366.0,103.0>>/B<<366.0,103.0>-<337.0,50.0>-<292.0,18.0>> = 5.85249339582191

	* uni1EF5 (U+1EF5): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni1EF7 (U+1EF7): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* uni1EF9 (U+1EF9): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* xi (U+03BE): L<<611.0,747.0>--<611.0,747.0>>/B<<611.0,747.0>-<487.0,723.0>-<413.5,700.0>> = 10.954062643398332

	* y (U+0079): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* yacute (U+00FD): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* ycircumflex (U+0177): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023

	* ydieresis (U+00FF): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023 

	* ygrave (U+1EF3): B<<403.5,66.5>-<409.0,87.0>-<412.0,101.0>>/B<<412.0,101.0>-<403.0,79.0>-<377.5,67.5>> = 10.15426658020023 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] VictorMono-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<363.0,803.0>--<404.0,800.0>> -> L<<404.0,800.0>--<446.0,800.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni0409 (U+0409): L<<270.0,803.0>--<311.0,800.0>> -> L<<311.0,800.0>--<494.0,800.0>>

	* uni0459 (U+0459): L<<231.0,621.0>--<272.0,618.0>> -> L<<272.0,618.0>--<456.0,618.0>>

	* uni0490 (U+0490): L<<671.0,938.0>--<643.0,800.0>> -> L<<643.0,800.0>--<628.0,724.0>>

	* uni0491 (U+0491): L<<638.0,756.0>--<610.0,618.0>> -> L<<610.0,618.0>--<593.0,542.0>>

	* uni04A4 (U+04A4): L<<552.0,814.0>--<554.0,814.0>> -> L<<554.0,814.0>--<554.0,814.0>>

	* uni04A4 (U+04A4): L<<554.0,814.0>--<554.0,814.0>> -> L<<554.0,814.0>--<760.0,814.0>>

	* uni04C3 (U+04C3): L<<217.0,385.0>--<213.0,385.0>> -> L<<213.0,385.0>--<152.0,385.0>>

	* uni2152 (U+2152): L<<196.0,853.0>--<229.0,850.0>> -> L<<229.0,850.0>--<269.0,850.0>>

	* uni21F6 (U+21F6): L<<295.0,269.0>--<348.0,306.0>> -> L<<348.0,306.0>--<370.0,322.0>>

	* uni25C1 (U+25C1): L<<526.0,89.0>--<452.0,133.0>> -> L<<452.0,133.0>--<61.0,370.0>>

	* uni25C3 (U+25C3): L<<436.0,198.0>--<374.0,235.0>> -> L<<374.0,235.0>--<151.0,370.0>>

	* uni25C5 (U+25C5): L<<526.0,177.0>--<455.0,207.0>> -> L<<455.0,207.0>--<50.0,370.0>>

	* uniE0A1 (U+E0A1): L<<294.0,60.0>--<299.0,-34.0>> -> L<<299.0,-34.0>--<299.0,-143.0>> 

	* uniE0A1 (U+E0A1): L<<383.0,114.0>--<378.0,226.0>> -> L<<378.0,226.0>--<378.0,318.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* aacute (U+00E1): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* abreve (U+0103): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* acircumflex (U+00E2): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* adieresis (U+00E4): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* agrave (U+00E0): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* amacron (U+0101): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* aogonek (U+0105): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* aring (U+00E5): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* atilde (U+00E3): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* eta (U+03B7): L<<136.0,478.0>--<156.0,493.0>>/L<<156.0,493.0>--<139.0,482.0>> = 3.9646547228560465

	* etatonos (U+03AE): L<<136.0,478.0>--<156.0,493.0>>/L<<156.0,493.0>--<139.0,482.0>> = 3.9646547228560465

	* section (U+00A7): B<<273.0,106.0>-<259.0,105.0>-<244.0,106.0>>/L<<244.0,106.0>--<244.0,106.0>> = 3.8140748342903783

	* section (U+00A7): L<<244.0,106.0>--<244.0,106.0>>/B<<244.0,106.0>-<145.0,111.0>-<109.0,163.5>> = 2.8912695962204467

	* uni01CE (U+01CE): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni0411 (U+0411): B<<89.0,140.0>-<89.0,133.0>-<88.0,126.0>>/B<<88.0,126.0>-<97.0,163.0>-<110.5,217.0>> = 5.541204778039828

	* uni0412 (U+0412): B<<108.5,267.0>-<102.0,230.0>-<97.0,198.0>>/B<<97.0,198.0>-<102.0,229.0>-<109.0,266.0>> = 0.2816878952012382

	* uni0412 (U+0412): B<<109.0,266.0>-<116.0,303.0>-<125.0,344.0>>/B<<125.0,344.0>-<115.0,304.0>-<108.5,267.0>> = 1.6554865391191917

	* uni041C (U+041C): B<<168.5,220.5>-<168.0,306.0>-<169.0,432.0>>/B<<169.0,432.0>-<142.0,292.0>-<123.5,204.5>> = 10.461163569999902

	* uni041C (U+041C): B<<435.0,245.0>-<457.0,336.0>-<488.0,465.0>>/B<<488.0,465.0>-<456.0,391.0>-<431.5,332.5>> = 9.872690421427679

	* uni0430 (U+0430): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni043C (U+043C): B<<404.5,120.0>-<417.0,180.0>-<440.0,282.0>>/B<<440.0,282.0>-<400.0,197.0>-<364.5,130.0>> = 12.494010144158457

	* uni0495 (U+0495): B<<161.5,209.5>-<141.0,174.0>-<128.0,114.0>>/L<<128.0,114.0>--<139.0,169.0>> = 0.9151902017154558

	* uni0495 (U+0495): L<<128.0,114.0>--<139.0,169.0>>/L<<139.0,169.0>--<104.0,0.0>> = 0.39064698879520277

	* uni04A6 (U+04A6): B<<369.0,380.0>-<340.0,344.0>-<320.0,254.0>>/L<<320.0,254.0>--<324.0,273.0>> = 0.6401496695237154

	* uni04A6 (U+04A6): L<<320.0,254.0>--<324.0,273.0>>/L<<324.0,273.0>--<266.0,0.0>> = 0.10573115791444299

	* uni04A7 (U+04A7): B<<341.0,240.0>-<308.0,204.0>-<289.0,114.0>>/L<<289.0,114.0>--<294.0,142.0>> = 1.7960668845243355

	* uni04A7 (U+04A7): L<<289.0,114.0>--<294.0,142.0>>/L<<294.0,142.0>--<264.0,0.0>> = 1.8046505218404962

	* uni04CD (U+04CD): B<<138.5,220.5>-<138.0,306.0>-<139.0,432.0>>/B<<139.0,432.0>-<112.0,292.0>-<93.5,204.5>> = 10.461163569999902

	* uni04CD (U+04CD): B<<398.5,215.0>-<422.0,314.0>-<458.0,465.0>>/B<<458.0,465.0>-<426.0,391.0>-<401.5,332.5>> = 9.975625190119656

	* uni04CE (U+04CE): B<<408.0,138.0>-<420.0,194.0>-<440.0,282.0>>/B<<440.0,282.0>-<400.0,197.0>-<364.5,130.0>> = 12.396857580188302

	* uni04D1 (U+04D1): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni04D3 (U+04D3): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EA1 (U+1EA1): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EA3 (U+1EA3): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EA5 (U+1EA5): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EA7 (U+1EA7): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EA9 (U+1EA9): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EAB (U+1EAB): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EAD (U+1EAD): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EAF (U+1EAF): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EB1 (U+1EB1): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EB3 (U+1EB3): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489

	* uni1EB5 (U+1EB5): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489 

	* uni1EB7 (U+1EB7): B<<348.0,62.5>-<348.0,69.0>-<350.0,71.0>>/B<<350.0,71.0>-<320.0,32.0>-<280.0,9.0>> = 7.431407971172489 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] VictorMono-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1423 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0497	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C2	Contours detected: 4	Expected: 2

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* yen (U+00A5) contains a short segment L<<267.0,303.0>--<266.0,305.0>>

	* yen (U+00A5) contains a short segment L<<334.0,305.0>--<333.0,303.0>>

	* section (U+00A7) contains a short segment L<<292.0,113.0>--<292.0,113.0>>

	* section (U+00A7) contains a short segment B<<297.0,505.0>-<302.0,505.0>-<308.0,505.0>>

	* section (U+00A7) contains a short segment L<<308.0,505.0>--<308.0,505.0>>

	* section (U+00A7) contains a short segment B<<303.0,113.0>-<298.0,113.0>-<292.0,113.0>>

	* uni00B9 (U+00B9) contains a short segment L<<270.0,850.0>--<270.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* germandbls (U+00DF) contains a short segment L<<261.0,455.0>--<279.0,455.0>>

	* eth (U+00F0) contains a short segment L<<533.0,245.0>--<533.0,245.0>>

	* delta (U+03B4) contains a short segment L<<300.0,552.0>--<300.0,552.0>>

	* delta (U+03B4) contains a short segment L<<455.0,324.0>--<455.0,324.0>>

	* xi (U+03BE) contains a short segment L<<514.0,800.0>--<522.0,802.0>>

	* xi (U+03BE) contains a short segment L<<522.0,739.0>--<516.0,739.0>>

	* xi (U+03BE) contains a short segment B<<522.0,443.0>-<518.0,443.0>-<515.0,443.0>>

	* rho (U+03C1) contains a short segment L<<77.0,309.0>--<77.0,309.0>>

	* rho (U+03C1) contains a short segment L<<77.0,309.0>--<77.0,309.0>>

	* omega (U+03C9) contains a short segment B<<267.0,320.0>-<267.0,325.0>-<267.0,331.0>>

	* omega (U+03C9) contains a short segment B<<333.0,331.0>-<333.0,325.0>-<333.0,321.0>>

	* omegatonos (U+03CE) contains a short segment B<<267.0,320.0>-<267.0,325.0>-<267.0,331.0>>

	* omegatonos (U+03CE) contains a short segment B<<333.0,331.0>-<333.0,325.0>-<333.0,321.0>>

	* uni03D7 (U+03D7) contains a short segment B<<104.0,571.0>-<96.0,571.0>-<81.5,561.5>>

	* uni0404 (U+0404) contains a short segment L<<125.0,370.0>--<125.0,360.0>>

	* uni042D (U+042D) contains a short segment L<<475.0,430.0>--<475.0,440.0>>

	* uni042E (U+042E) contains a short segment L<<189.0,430.0>--<189.0,440.0>>

	* uni043A (U+043A) contains a short segment B<<242.0,301.0>-<235.0,301.0>-<226.0,301.0>>

	* uni044A (U+044A) contains a short segment L<<187.0,557.0>--<187.0,557.0>>

	* uni044D (U+044D) contains a short segment L<<475.0,339.0>--<475.0,349.0>>

	* uni044E (U+044E) contains a short segment L<<189.0,339.0>--<189.0,349.0>>

	* uni0454 (U+0454) contains a short segment L<<125.0,279.0>--<125.0,269.0>>

	* uni045C (U+045C) contains a short segment B<<242.0,301.0>-<235.0,301.0>-<226.0,301.0>>

	* uni0464 (U+0464) contains a short segment L<<189.0,430.0>--<189.0,440.0>>

	* uni0464 (U+0464) contains a short segment L<<255.0,370.0>--<255.0,360.0>>

	* uni0465 (U+0465) contains a short segment L<<189.0,339.0>--<189.0,349.0>>

	* uni0465 (U+0465) contains a short segment L<<255.0,279.0>--<255.0,269.0>>

	* uni046A (U+046A) contains a short segment B<<283.0,439.0>-<291.0,439.0>-<300.0,439.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,439.0>-<309.0,439.0>-<317.0,439.0>>

	* uni046B (U+046B) contains a short segment B<<279.0,358.0>-<289.0,359.0>-<300.0,359.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,359.0>-<311.0,359.0>-<321.0,358.0>>

	* uni0494 (U+0494) contains a short segment B<<284.0,-193.5>-<271.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-123.0>-<271.0,-130.0>-<284.0,-132.5>>

	* uni049B (U+049B) contains a short segment B<<242.0,301.0>-<235.0,301.0>-<226.0,301.0>>

	* uni049C (U+049C) contains a short segment L<<243.0,394.0>--<243.0,394.0>>

	* uni049F (U+049F) contains a short segment B<<245.0,301.0>-<238.0,301.0>-<230.0,301.0>>

	* uni04A1 (U+04A1) contains a short segment B<<242.0,301.0>-<235.0,301.0>-<226.0,301.0>>

	* uni04A6 (U+04A6) contains a short segment B<<403.0,-193.5>-<390.0,-191.0>-<379.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<379.0,-123.0>-<390.0,-130.0>-<403.0,-132.5>>

	* uni04A7 (U+04A7) contains a short segment B<<390.5,-193.5>-<378.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-123.0>-<378.0,-130.0>-<390.5,-132.5>>

	* uni04A8 (U+04A8) contains a short segment B<<436.0,47.0>-<439.0,47.0>-<442.0,47.0>>

	* uni04A8 (U+04A8) contains a short segment B<<279.0,47.0>-<289.0,47.0>-<299.0,48.0>>

	* uni04B0 (U+04B0) contains a short segment L<<267.0,303.0>--<267.0,303.0>>

	* uni04B0 (U+04B0) contains a short segment L<<333.0,303.0>--<333.0,303.0>>

	* uni04C3 (U+04C3) contains a short segment B<<256.5,-193.5>-<243.0,-191.0>-<233.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<233.0,-123.0>-<243.0,-130.0>-<256.5,-132.5>>

	* uni04C3 (U+04C3) contains a short segment L<<212.0,393.0>--<212.0,393.0>>

	* uni04C3 (U+04C3) contains a short segment L<<212.0,393.0>--<210.0,393.0>>

	* uni04E0 (U+04E0) contains a short segment L<<310.0,453.0>--<320.0,453.0>>

	* uni04E1 (U+04E1) contains a short segment L<<307.0,271.0>--<320.0,271.0>>

	* uni04EC (U+04EC) contains a short segment L<<475.0,430.0>--<475.0,440.0>>

	* uni04ED (U+04ED) contains a short segment L<<475.0,339.0>--<475.0,349.0>>

	* uni2081 (U+2081) contains a short segment L<<270.0,377.0>--<270.0,377.0>>

	* lira (U+20A4) contains a short segment B<<132.0,506.0>-<132.0,509.0>-<132.0,513.0>>

	* lira (U+20A4) contains a short segment B<<198.0,516.0>-<198.0,510.0>-<198.0,506.0>>

	* uni2150 (U+2150) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<229.0,377.0>--<229.0,377.0>>

	* uni2153 (U+2153) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<104.0,850.0>--<104.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* uni21C8 (U+21C8) contains a short segment L<<345.0,592.0>--<345.0,592.0>>

	* uni21C8 (U+21C8) contains a short segment L<<255.0,592.0>--<255.0,592.0>>

	* uni21CA (U+21CA) contains a short segment L<<255.0,208.0>--<255.0,208.0>>

	* uni21CA (U+21CA) contains a short segment L<<345.0,208.0>--<345.0,208.0>>

	* uni21CE (U+21CE) contains a short segment L<<413.0,582.0>--<406.0,593.0>>

	* uni21F6 (U+21F6) contains a short segment L<<308.0,264.0>--<309.0,265.0>>

	* uni21F6 (U+21F6) contains a short segment L<<309.0,265.0>--<308.0,265.0>>

	* uni21F6 (U+21F6) contains a short segment L<<308.0,535.0>--<309.0,535.0>>

	* uni21F6 (U+21F6) contains a short segment L<<309.0,535.0>--<308.0,536.0>>

	* partialdiff (U+2202) contains a short segment L<<538.0,245.0>--<538.0,245.0>>

	* uni2573 (U+2573) contains a short segment L<<0.0,1200.0>--<35.0,1200.0>>

	* uni2573 (U+2573) contains a short segment L<<565.0,1200.0>--<600.0,1200.0>>

	* uni2573 (U+2573) contains a short segment L<<600.0,-400.0>--<565.0,-400.0>>

	* uni2573 (U+2573) contains a short segment L<<35.0,-400.0>--<0.0,-400.0>>

	* uni25A9 (U+25A9) contains a short segment L<<129.0,437.0>--<131.0,439.0>>

	* uni25A9 (U+25A9) contains a short segment L<<131.0,439.0>--<129.0,441.0>>

	* uni25A9 (U+25A9) contains a short segment L<<471.0,439.0>--<471.0,440.0>>

	* uni25A9 (U+25A9) contains a short segment L<<471.0,440.0>--<470.0,439.0>>

	* uni25A9 (U+25A9) contains a short segment L<<470.0,439.0>--<471.0,439.0>>

	* uni25A9 (U+25A9) contains a short segment L<<471.0,301.0>--<469.0,300.0>> 

	* uni25A9 (U+25A9) contains a short segment L<<469.0,300.0>--<471.0,298.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* oneeighth (U+215B): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* onehalf (U+00BD): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* onehalf (U+00BD): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* onequarter (U+00BC): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* onequarter (U+00BC): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* rho (U+03C1): L<<77.0,309.0>--<77.0,309.0>> -> L<<77.0,309.0>--<77.0,309.0>>

	* uni00B9 (U+00B9): L<<269.0,850.0>--<270.0,850.0>> -> L<<270.0,850.0>--<270.0,850.0>>

	* uni00B9 (U+00B9): L<<270.0,850.0>--<270.0,850.0>> -> L<<270.0,850.0>--<331.0,850.0>>

	* uni04B0 (U+04B0): L<<124.0,303.0>--<267.0,303.0>> -> L<<267.0,303.0>--<267.0,303.0>>

	* uni04B0 (U+04B0): L<<333.0,303.0>--<333.0,303.0>> -> L<<333.0,303.0>--<477.0,303.0>>

	* uni04C3 (U+04C3): L<<212.0,393.0>--<210.0,393.0>> -> L<<210.0,393.0>--<138.0,393.0>>

	* uni2081 (U+2081): L<<269.0,377.0>--<270.0,377.0>> -> L<<270.0,377.0>--<270.0,377.0>>

	* uni2081 (U+2081): L<<270.0,377.0>--<270.0,377.0>> -> L<<270.0,377.0>--<331.0,377.0>>

	* uni2150 (U+2150): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* uni2150 (U+2150): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* uni2151 (U+2151): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* uni2151 (U+2151): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* uni2152 (U+2152): L<<228.0,377.0>--<229.0,377.0>> -> L<<229.0,377.0>--<229.0,377.0>>

	* uni2152 (U+2152): L<<229.0,377.0>--<229.0,377.0>> -> L<<229.0,377.0>--<290.0,377.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152): L<<82.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<143.0,850.0>>

	* uni2153 (U+2153): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* uni2153 (U+2153): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* uni2155 (U+2155): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* uni2155 (U+2155): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* uni2159 (U+2159): L<<103.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<104.0,850.0>>

	* uni2159 (U+2159): L<<104.0,850.0>--<104.0,850.0>> -> L<<104.0,850.0>--<165.0,850.0>>

	* uni215F (U+215F): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* uni215F (U+215F): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<164.0,850.0>>

	* uni25C1 (U+25C1): L<<517.0,103.0>--<457.0,140.0>> -> L<<457.0,140.0>--<77.0,370.0>>

	* uni25C3 (U+25C3): L<<427.0,212.0>--<379.0,242.0>> -> L<<379.0,242.0>--<167.0,370.0>>

	* uni25C5 (U+25C5): L<<517.0,189.0>--<458.0,214.0>> -> L<<458.0,214.0>--<71.0,370.0>>

	* uniE0A1 (U+E0A1): L<<283.0,107.0>--<290.0,-35.0>> -> L<<290.0,-35.0>--<290.0,-135.0>> 

	* uniE0A1 (U+E0A1): L<<394.0,67.0>--<386.0,227.0>> -> L<<386.0,227.0>--<386.0,310.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): L<<292.0,113.0>--<292.0,113.0>>/B<<292.0,113.0>-<188.0,115.0>-<144.5,165.5>> = 1.1017061152063952 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni2196 (U+2196): L<<47.0,683.0>--<372.0,682.0>>

	* uni2196 (U+2196): L<<48.0,358.0>--<47.0,683.0>>

	* uni2197 (U+2197): L<<228.0,682.0>--<553.0,683.0>>

	* uni2197 (U+2197): L<<553.0,683.0>--<552.0,358.0>>

	* uni2198 (U+2198): L<<552.0,474.0>--<553.0,150.0>>

	* uni2199 (U+2199): L<<47.0,150.0>--<48.0,474.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<352.0,682.0>>

	* uni21D6 (U+21D6): L<<28.0,358.0>--<27.0,683.0>>

	* uni21D7 (U+21D7): L<<248.0,682.0>--<573.0,683.0>>

	* uni21D7 (U+21D7): L<<573.0,683.0>--<572.0,358.0>>

	* uni21D8 (U+21D8): L<<572.0,442.0>--<573.0,117.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<248.0,118.0>>

	* uni21D9 (U+21D9): L<<27.0,117.0>--<28.0,442.0>> 

	* uni21D9 (U+21D9): L<<352.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] VictorMono-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni040C	Contours detected: 3	Expected: 2

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni041C	Contours detected: 2	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni049C	Contours detected: 2	Expected: 1

	- Glyph name: uni049E	Contours detected: 2	Expected: 1

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni040C	Contours detected: 3	Expected: 2

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni041C	Contours detected: 2	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni049C	Contours detected: 2	Expected: 1

	- Glyph name: uni049E	Contours detected: 2	Expected: 1

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<367.0,803.0>--<404.0,800.0>> -> L<<404.0,800.0>--<442.0,800.0>>

	* oneeighth (U+215B): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* onehalf (U+00BD): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* onequarter (U+00BC): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni00B9 (U+00B9): L<<382.0,853.0>--<412.0,850.0>> -> L<<412.0,850.0>--<449.0,850.0>>

	* uni0409 (U+0409): L<<270.0,803.0>--<307.0,800.0>> -> L<<307.0,800.0>--<487.0,800.0>>

	* uni0459 (U+0459): L<<231.0,621.0>--<268.0,618.0>> -> L<<268.0,618.0>--<449.0,618.0>>

	* uni0490 (U+0490): L<<668.0,935.0>--<640.0,800.0>> -> L<<640.0,800.0>--<626.0,731.0>>

	* uni0491 (U+0491): L<<634.0,753.0>--<606.0,618.0>> -> L<<606.0,618.0>--<591.0,549.0>>

	* uni04A4 (U+04A4): L<<557.0,814.0>--<557.0,814.0>> -> L<<557.0,814.0>--<760.0,814.0>>

	* uni04C3 (U+04C3): L<<225.0,389.0>--<221.0,389.0>> -> L<<221.0,389.0>--<154.0,389.0>>

	* uni2081 (U+2081): L<<282.0,381.0>--<312.0,378.0>> -> L<<312.0,378.0>--<349.0,378.0>>

	* uni2150 (U+2150): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* uni2151 (U+2151): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* uni2152 (U+2152): L<<196.0,853.0>--<226.0,850.0>> -> L<<226.0,850.0>--<264.0,850.0>>

	* uni2152 (U+2152): L<<237.0,381.0>--<267.0,378.0>> -> L<<267.0,378.0>--<304.0,378.0>>

	* uni2153 (U+2153): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* uni2155 (U+2155): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* uni2159 (U+2159): L<<216.0,853.0>--<246.0,850.0>> -> L<<246.0,850.0>--<283.0,850.0>>

	* uni215F (U+215F): L<<214.0,853.0>--<244.0,850.0>> -> L<<244.0,850.0>--<281.0,850.0>>

	* uni21F6 (U+21F6): L<<302.0,267.0>--<359.0,308.0>> -> L<<359.0,308.0>--<371.0,316.0>>

	* uni25C1 (U+25C1): L<<522.0,96.0>--<455.0,136.0>> -> L<<455.0,136.0>--<69.0,370.0>>

	* uni25C3 (U+25C3): L<<432.0,205.0>--<377.0,238.0>> -> L<<377.0,238.0>--<159.0,370.0>>

	* uni25C5 (U+25C5): L<<522.0,183.0>--<457.0,211.0>> -> L<<457.0,211.0>--<60.0,370.0>>

	* uniE0A1 (U+E0A1): L<<289.0,82.0>--<295.0,-34.0>> -> L<<295.0,-34.0>--<295.0,-139.0>> 

	* uniE0A1 (U+E0A1): L<<388.0,92.0>--<382.0,227.0>> -> L<<382.0,227.0>--<382.0,315.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* aacute (U+00E1): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* abreve (U+0103): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* acircumflex (U+00E2): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* adieresis (U+00E4): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* agrave (U+00E0): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* amacron (U+0101): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* aogonek (U+0105): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* aring (U+00E5): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* atilde (U+00E3): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* beta (U+03B2): B<<72.0,324.0>-<76.0,350.0>-<83.0,380.0>>/L<<83.0,380.0>--<83.0,378.0>> = 13.134022306396327

	* beta (U+03B2): L<<83.0,380.0>--<83.0,378.0>>/L<<83.0,378.0>--<136.0,625.0>> = 12.110597767654415

	* eta (U+03B7): L<<142.0,486.0>--<160.0,499.0>>/L<<160.0,499.0>--<144.0,489.0>> = 3.832269746194733

	* etatonos (U+03AE): L<<142.0,486.0>--<160.0,499.0>>/L<<160.0,499.0>--<144.0,489.0>> = 3.832269746194733

	* section (U+00A7): B<<424.0,406.5>-<405.0,436.0>-<343.0,438.0>>/L<<343.0,438.0>--<343.0,438.0>> = 1.8476102659945155

	* section (U+00A7): L<<249.0,109.0>--<249.0,109.0>>/B<<249.0,109.0>-<147.0,113.0>-<112.0,165.5>> = 2.245742565895049

	* section (U+00A7): L<<343.0,438.0>--<343.0,438.0>>/B<<343.0,438.0>-<289.0,439.0>-<254.5,426.0>> = 1.0609116902641509

	* section (U+00A7): L<<352.0,509.0>--<351.0,509.0>>/B<<351.0,509.0>-<453.0,505.0>-<488.0,452.5>> = 2.245742565895049

	* uni01CE (U+01CE): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni0412 (U+0412): B<<110.5,247.5>-<130.0,347.0>-<158.0,480.0>>/B<<158.0,480.0>-<133.0,407.0>-<117.5,333.0>> = 7.0159178029836005

	* uni0412 (U+0412): B<<94.5,198.0>-<87.0,137.0>-<85.0,104.0>>/B<<85.0,104.0>-<91.0,148.0>-<110.5,247.5>> = 4.296936759508032

	* uni041B (U+041B): B<<38.5,53.0>-<45.0,44.0>-<44.0,44.0>>/B<<44.0,44.0>-<60.0,45.0>-<109.0,134.5>> = 3.576334374997269

	* uni041C (U+041C): B<<169.5,236.5>-<169.0,328.0>-<171.0,463.0>>/B<<171.0,463.0>-<143.0,321.0>-<123.0,228.5>> = 10.305895467374684

	* uni041C (U+041C): B<<445.0,262.5>-<468.0,360.0>-<500.0,498.0>>/B<<500.0,498.0>-<427.0,327.0>-<385.0,224.0>> = 10.062417101416205

	* uni0430 (U+0430): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni043C (U+043C): B<<151.5,148.0>-<143.0,207.0>-<138.0,301.0>>/B<<138.0,301.0>-<119.0,202.0>-<104.5,139.5>> = 13.908838366281712

	* uni043C (U+043C): B<<413.5,134.0>-<427.0,200.0>-<453.0,314.0>>/B<<453.0,314.0>-<410.0,221.0>-<371.5,146.5>> = 11.966492131817503

	* uni046A (U+046A): L<<326.0,443.0>--<322.0,416.0>>/L<<322.0,416.0>--<322.0,417.0>> = 8.426969021480636

	* uni0495 (U+0495): B<<158.5,216.0>-<138.0,180.0>-<125.0,118.0>>/L<<125.0,118.0>--<136.0,171.0>> = 0.11696410015863204

	* uni0495 (U+0495): L<<125.0,118.0>--<136.0,171.0>>/L<<136.0,171.0>--<100.0,0.0>> = 0.16354602446378

	* uni04A6 (U+04A6): B<<368.0,387.0>-<337.0,351.0>-<318.0,258.0>>/L<<318.0,258.0>--<323.0,284.0>> = 0.6611634912680927

	* uni04A6 (U+04A6): L<<318.0,258.0>--<323.0,284.0>>/L<<323.0,284.0>--<263.0,0.0>> = 1.0437951225794602

	* uni04A7 (U+04A7): B<<319.0,216.0>-<300.0,180.0>-<287.0,118.0>>/L<<287.0,118.0>--<292.0,141.0>> = 0.4226976125639478

	* uni04A7 (U+04A7): L<<287.0,118.0>--<292.0,141.0>>/L<<292.0,141.0>--<262.0,0.0>> = 0.2532953415264555

	* uni04C5 (U+04C5): B<<-1.5,53.0>-<5.0,44.0>-<4.0,44.0>>/B<<4.0,44.0>-<20.0,45.0>-<69.0,134.5>> = 3.576334374997269

	* uni04CD (U+04CD): B<<144.5,236.5>-<144.0,328.0>-<146.0,463.0>>/B<<146.0,463.0>-<118.0,321.0>-<98.0,228.5>> = 10.305895467374684

	* uni04CD (U+04CD): B<<412.0,226.0>-<437.0,333.0>-<475.0,498.0>>/B<<475.0,498.0>-<402.0,327.0>-<360.0,224.0>> = 10.148410869184074

	* uni04CE (U+04CE): B<<151.5,148.0>-<143.0,207.0>-<138.0,301.0>>/B<<138.0,301.0>-<119.0,202.0>-<104.5,139.5>> = 13.908838366281712

	* uni04CE (U+04CE): B<<416.5,150.0>-<430.0,213.0>-<453.0,314.0>>/B<<453.0,314.0>-<410.0,221.0>-<371.5,146.5>> = 11.985414119079715

	* uni04D1 (U+04D1): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni04D3 (U+04D3): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni0512 (U+0512): B<<38.5,53.0>-<45.0,44.0>-<44.0,44.0>>/B<<44.0,44.0>-<60.0,45.0>-<109.0,134.5>> = 3.576334374997269

	* uni1EA1 (U+1EA1): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EA3 (U+1EA3): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EA5 (U+1EA5): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EA7 (U+1EA7): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EA9 (U+1EA9): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EAB (U+1EAB): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EAD (U+1EAD): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EAF (U+1EAF): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EB1 (U+1EB1): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EB3 (U+1EB3): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063

	* uni1EB5 (U+1EB5): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063 

	* uni1EB7 (U+1EB7): B<<351.5,67.5>-<352.0,77.0>-<355.0,82.0>>/B<<355.0,82.0>-<326.0,38.0>-<284.0,12.0>> = 2.4247570440379063 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] VictorMono-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04A6	Contours detected: 2	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 4	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 1	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 1	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04A6	Contours detected: 2	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 5	Expected: 3

	- Glyph name: uni04D2	Contours detected: 6	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 3	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 6	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 6	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<380.0,802.0>--<405.0,800.0>> -> L<<405.0,800.0>--<429.0,800.0>>

	* oneeighth (U+215B): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* onehalf (U+00BD): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* onequarter (U+00BC): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* section (U+00A7): L<<264.0,119.0>--<263.0,119.0>> -> L<<263.0,119.0>--<262.0,119.0>>

	* section (U+00A7): L<<266.0,167.0>--<268.0,167.0>> -> L<<268.0,167.0>--<268.0,167.0>>

	* section (U+00A7): L<<336.0,499.0>--<337.0,499.0>> -> L<<337.0,499.0>--<338.0,499.0>>

	* section (U+00A7): L<<337.0,499.0>--<338.0,499.0>> -> L<<338.0,499.0>--<338.0,499.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni00B9 (U+00B9): L<<390.0,852.0>--<410.0,850.0>> -> L<<410.0,850.0>--<441.0,850.0>>

	* uni03D7 (U+03D7): L<<433.0,34.0>--<433.0,34.0>> -> L<<433.0,34.0>--<482.0,30.0>>

	* uni0409 (U+0409): L<<270.0,802.0>--<294.0,800.0>> -> L<<294.0,800.0>--<464.0,800.0>>

	* uni0459 (U+0459): L<<231.0,620.0>--<255.0,618.0>> -> L<<255.0,618.0>--<426.0,618.0>>

	* uni0490 (U+0490): L<<656.0,925.0>--<630.0,800.0>> -> L<<630.0,800.0>--<621.0,754.0>>

	* uni0491 (U+0491): L<<619.0,743.0>--<593.0,618.0>> -> L<<593.0,618.0>--<583.0,572.0>>

	* uni04A4 (U+04A4): L<<566.0,814.0>--<566.0,814.0>> -> L<<566.0,814.0>--<757.0,814.0>>

	* uni2081 (U+2081): L<<289.0,376.0>--<309.0,374.0>> -> L<<309.0,374.0>--<340.0,374.0>>

	* uni2150 (U+2150): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* uni2151 (U+2151): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* uni2152 (U+2152): L<<196.0,852.0>--<216.0,850.0>> -> L<<216.0,850.0>--<247.0,850.0>>

	* uni2152 (U+2152): L<<255.0,376.0>--<275.0,374.0>> -> L<<275.0,374.0>--<306.0,374.0>>

	* uni2153 (U+2153): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* uni2155 (U+2155): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* uni2159 (U+2159): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* uni215F (U+215F): L<<224.0,852.0>--<244.0,850.0>> -> L<<244.0,850.0>--<275.0,850.0>>

	* uni25C1 (U+25C1): L<<509.0,117.0>--<461.0,146.0>> -> L<<461.0,146.0>--<91.0,370.0>>

	* uni25C3 (U+25C3): L<<419.0,226.0>--<383.0,248.0>> -> L<<383.0,248.0>--<181.0,370.0>>

	* uni25C5 (U+25C5): L<<509.0,201.0>--<461.0,221.0>> -> L<<461.0,221.0>--<91.0,370.0>>

	* uniE0A1 (U+E0A1): L<<273.0,152.0>--<282.0,-35.0>> -> L<<282.0,-35.0>--<282.0,-128.0>>

	* uniE0A1 (U+E0A1): L<<404.0,22.0>--<394.0,227.0>> -> L<<394.0,227.0>--<394.0,303.0>> 

	* xi (U+03BE): L<<618.0,800.0>--<614.0,777.0>> -> L<<614.0,777.0>--<611.0,754.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* aacute (U+00E1): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* abreve (U+0103): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* acircumflex (U+00E2): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* adieresis (U+00E4): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* agrave (U+00E0): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* alpha (U+03B1): B<<458.0,457.0>-<457.0,407.0>-<451.0,354.0>>/B<<451.0,354.0>-<487.0,463.0>-<526.0,620.0>> = 11.81829323050143

	* alphatonos (U+03AC): B<<458.0,457.0>-<457.0,407.0>-<451.0,354.0>>/B<<451.0,354.0>-<487.0,463.0>-<526.0,620.0>> = 11.81829323050143

	* amacron (U+0101): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* aogonek (U+0105): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* aring (U+00E5): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* atilde (U+00E3): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* beta (U+03B2): B<<79.0,301.0>-<82.0,317.0>-<86.0,334.0>>/L<<86.0,334.0>--<86.0,333.0>> = 13.240519915187184

	* beta (U+03B2): L<<86.0,334.0>--<86.0,333.0>>/L<<86.0,333.0>--<148.0,624.0>> = 12.027508540388842

	* eta (U+03B7): L<<160.0,508.0>--<173.0,518.0>>/L<<173.0,518.0>--<161.0,510.0>> = 3.8785245028476374

	* etatonos (U+03AE): L<<160.0,508.0>--<173.0,518.0>>/L<<173.0,518.0>--<161.0,510.0>> = 3.8785245028476374

	* g (U+0067): B<<400.0,42.0>-<410.0,80.0>-<415.0,108.0>>/B<<415.0,108.0>-<407.0,90.0>-<376.5,76.0>> = 13.837817319180342

	* gbreve (U+011F): B<<400.0,42.0>-<410.0,80.0>-<415.0,108.0>>/B<<415.0,108.0>-<407.0,90.0>-<376.5,76.0>> = 13.837817319180342

	* gcircumflex (U+011D): B<<400.0,42.0>-<410.0,80.0>-<415.0,108.0>>/B<<415.0,108.0>-<407.0,90.0>-<376.5,76.0>> = 13.837817319180342

	* gdotaccent (U+0121): B<<400.0,42.0>-<410.0,80.0>-<415.0,108.0>>/B<<415.0,108.0>-<407.0,90.0>-<376.5,76.0>> = 13.837817319180342

	* q (U+0071): L<<341.0,-182.0>--<396.0,74.0>>/B<<396.0,74.0>-<385.0,51.0>-<358.5,31.0>> = 13.43464219773104

	* thorn (U+00FE): L<<255.0,800.0>--<198.0,537.0>>/B<<198.0,537.0>-<212.0,567.0>-<240.0,588.5>> = 12.788302744774331

	* uni0123 (U+0123): B<<400.0,42.0>-<410.0,80.0>-<415.0,108.0>>/B<<415.0,108.0>-<407.0,90.0>-<376.5,76.0>> = 13.837817319180342

	* uni01CE (U+01CE): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni041C (U+041C): B<<174.0,284.0>-<175.0,394.0>-<179.0,557.0>>/B<<179.0,557.0>-<136.0,367.0>-<106.0,240.0>> = 11.346370489161266

	* uni041C (U+041C): B<<473.0,310.0>-<497.0,425.0>-<532.0,591.0>>/B<<532.0,591.0>-<479.0,468.0>-<440.5,374.5>> = 11.404883013439028

	* uni0430 (U+0430): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni0434 (U+0434): B<<400.0,42.0>-<410.0,80.0>-<415.0,108.0>>/B<<415.0,108.0>-<407.0,90.0>-<376.5,76.0>> = 13.837817319180342

	* uni0436 (U+0436): L<<209.0,0.0>--<306.0,460.0>>/L<<306.0,460.0>--<193.0,229.0>> = 14.159350747847943

	* uni0436 (U+0436): L<<383.0,618.0>--<286.0,159.0>>/L<<286.0,159.0>--<400.0,395.0>> = 13.850216661794825

	* uni043C (U+043C): B<<151.5,197.0>-<146.0,275.0>-<144.0,399.0>>/B<<144.0,399.0>-<115.0,268.0>-<96.5,186.5>> = 13.406534737727165

	* uni043C (U+043C): B<<448.5,212.0>-<465.0,290.0>-<490.0,410.0>>/B<<490.0,410.0>-<452.0,324.0>-<415.5,247.5>> = 12.070451251151052

	* uni0443 (U+0443): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni045E (U+045E): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni0495 (U+0495): L<<208.0,572.0>--<119.0,153.0>>/L<<119.0,153.0>--<144.0,268.0>> = 0.27278086069819923

	* uni0497 (U+0497): L<<209.0,0.0>--<306.0,460.0>>/L<<306.0,460.0>--<193.0,229.0>> = 14.159350747847943

	* uni0497 (U+0497): L<<383.0,618.0>--<286.0,159.0>>/L<<286.0,159.0>--<400.0,395.0>> = 13.850216661794825

	* uni04A6 (U+04A6): B<<343.0,376.0>-<323.0,338.0>-<309.0,272.0>>/L<<309.0,272.0>--<338.0,408.0>> = 0.06106987615954117

	* uni04C2 (U+04C2): L<<209.0,0.0>--<306.0,460.0>>/L<<306.0,460.0>--<193.0,229.0>> = 14.159350747847943

	* uni04C2 (U+04C2): L<<383.0,618.0>--<286.0,159.0>>/L<<286.0,159.0>--<400.0,395.0>> = 13.850216661794825

	* uni04CD (U+04CD): B<<164.0,284.0>-<165.0,394.0>-<169.0,557.0>>/B<<169.0,557.0>-<126.0,367.0>-<96.0,240.0>> = 11.346370489161266

	* uni04CD (U+04CD): B<<451.5,252.0>-<478.0,382.0>-<522.0,591.0>>/B<<522.0,591.0>-<469.0,468.0>-<430.5,374.5>> = 11.422276995756208

	* uni04CE (U+04CE): B<<151.5,197.0>-<146.0,275.0>-<144.0,399.0>>/B<<144.0,399.0>-<115.0,268.0>-<96.5,186.5>> = 13.406534737727165

	* uni04CE (U+04CE): B<<450.0,220.5>-<466.0,296.0>-<490.0,410.0>>/B<<490.0,410.0>-<452.0,324.0>-<415.5,247.5>> = 11.950082143543716

	* uni04D1 (U+04D1): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni04D3 (U+04D3): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni04DD (U+04DD): L<<209.0,0.0>--<306.0,460.0>>/L<<306.0,460.0>--<193.0,229.0>> = 14.159350747847943

	* uni04DD (U+04DD): L<<383.0,618.0>--<286.0,159.0>>/L<<286.0,159.0>--<400.0,395.0>> = 13.850216661794825

	* uni04EF (U+04EF): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni04F1 (U+04F1): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni04F3 (U+04F3): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni04F6 (U+04F6): L<<49.0,-14.0>--<49.0,-14.0>>/B<<49.0,-14.0>-<17.0,-13.0>-<8.5,12.0>> = 1.789910608246076

	* uni1EA1 (U+1EA1): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EA3 (U+1EA3): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EA5 (U+1EA5): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EA7 (U+1EA7): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EA9 (U+1EA9): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EAB (U+1EAB): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EAD (U+1EAD): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EAF (U+1EAF): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EB1 (U+1EB1): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EB3 (U+1EB3): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EB5 (U+1EB5): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EB7 (U+1EB7): B<<364.5,84.0>-<367.0,103.0>-<371.0,113.0>>/B<<371.0,113.0>-<343.0,56.0>-<296.0,21.0>> = 4.360156955667345

	* uni1EF5 (U+1EF5): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni1EF7 (U+1EF7): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* uni1EF9 (U+1EF9): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* y (U+0079): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* yacute (U+00FD): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* ycircumflex (U+0177): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048

	* ydieresis (U+00FF): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048 

	* ygrave (U+1EF3): B<<408.5,68.5>-<415.0,92.0>-<417.0,106.0>>/B<<417.0,106.0>-<410.0,83.0>-<383.0,69.5>> = 8.797410709991048 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] VictorMono-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1457 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Core is almost fulfilled. Missing codepoints:

	- 0x2116 (NUMERO SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x051A (CYRILLIC CAPITAL LETTER QA)


	- 0x051B (CYRILLIC SMALL LETTER QA)


	- 0x20B4 (HRYVNIA SIGN)


	- 0x20B8 (TENGE SIGN)
 

	- 0x20AE (TUGRIK SIGN)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1E3E (LATIN CAPITAL LETTER M WITH ACUTE)


	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x1E3F (LATIN SMALL LETTER M WITH ACUTE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)
 

	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
numbersign_numbersign_numbersign.liga, numbersign_numbersign_numbersign_numbersign.liga and asciitilde_asciitilde_greater.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- iogonek.dotless

	- uni030C.alt 

	- uni1ECB.dotless
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 4	Expected: 3

	- Glyph name: uni04D2	Contours detected: 5	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 4	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3

	- Glyph name: uni2552	Contours detected: 1	Expected: 2

	- Glyph name: uni2553	Contours detected: 1	Expected: 2

	- Glyph name: uni2555	Contours detected: 1	Expected: 2

	- Glyph name: uni2556	Contours detected: 1	Expected: 2

	- Glyph name: uni2558	Contours detected: 1	Expected: 2

	- Glyph name: uni2559	Contours detected: 1	Expected: 2

	- Glyph name: uni255B	Contours detected: 1	Expected: 2

	- Glyph name: uni255C	Contours detected: 1	Expected: 2

	- Glyph name: uni255E	Contours detected: 1	Expected: 2

	- Glyph name: uni2561	Contours detected: 1	Expected: 2

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dkshade	Contours detected: 54	Expected: 73

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 3	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 3	Expected: 1

	- Glyph name: ltshade	Contours detected: 54	Expected: 46

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: shade	Contours detected: 54	Expected: 85

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0429	Contours detected: 2	Expected: 1

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042E	Contours detected: 3	Expected: 2

	- Glyph name: uni0432	Contours detected: 2	Expected: 3

	- Glyph name: uni0434	Contours detected: 3	Expected: 2

	- Glyph name: uni0437	Contours detected: 2	Expected: 1

	- Glyph name: uni0443	Contours detected: 2	Expected: 1

	- Glyph name: uni0446	Contours detected: 2	Expected: 1

	- Glyph name: uni0449	Contours detected: 2	Expected: 1

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni0458	Contours detected: 3	Expected: 2

	- Glyph name: uni045E	Contours detected: 3	Expected: 2

	- Glyph name: uni046A	Contours detected: 1	Expected: 2

	- Glyph name: uni046B	Contours detected: 1	Expected: 2

	- Glyph name: uni0496	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04C1	Contours detected: 4	Expected: 2

	- Glyph name: uni04C7	Contours detected: 3	Expected: 1

	- Glyph name: uni04C9	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04D0	Contours detected: 4	Expected: 3

	- Glyph name: uni04D2	Contours detected: 5	Expected: 4

	- Glyph name: uni04DC	Contours detected: 5	Expected: 3

	- Glyph name: uni04DF	Contours detected: 4	Expected: 3

	- Glyph name: uni04EF	Contours detected: 3	Expected: 2

	- Glyph name: uni04F1	Contours detected: 4	Expected: 3

	- Glyph name: uni04F3	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 4	Expected: 5

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni21C7	Contours detected: 2	Expected: 1

	- Glyph name: uni21C9	Contours detected: 2	Expected: 1

	- Glyph name: uni21E0	Contours detected: 4	Expected: 3

	- Glyph name: uni21E1	Contours detected: 5	Expected: 3

	- Glyph name: uni21E2	Contours detected: 4	Expected: 3

	- Glyph name: uni21E3	Contours detected: 5	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3 

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<354.0,804.0>--<404.0,800.0>> -> L<<404.0,800.0>--<454.0,800.0>>

	* oneeighth (U+215B): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* onehalf (U+00BD): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* onequarter (U+00BC): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni00B9 (U+00B9): L<<373.0,854.0>--<414.0,850.0>> -> L<<414.0,850.0>--<457.0,850.0>>

	* uni0409 (U+0409): L<<270.0,804.0>--<320.0,800.0>> -> L<<320.0,800.0>--<510.0,800.0>>

	* uni0422 (U+0422): L<<233.0,800.0>--<233.0,800.0>> -> L<<233.0,800.0>--<679.0,800.0>>

	* uni0459 (U+0459): L<<231.0,622.0>--<281.0,618.0>> -> L<<281.0,618.0>--<472.0,618.0>>

	* uni0490 (U+0490): L<<679.0,945.0>--<649.0,800.0>> -> L<<649.0,800.0>--<631.0,708.0>>

	* uni0491 (U+0491): L<<648.0,763.0>--<618.0,618.0>> -> L<<618.0,618.0>--<598.0,526.0>>

	* uni04A4 (U+04A4): L<<548.0,814.0>--<548.0,814.0>> -> L<<548.0,814.0>--<762.0,814.0>>

	* uni04AC (U+04AC): L<<233.0,800.0>--<233.0,800.0>> -> L<<233.0,800.0>--<679.0,800.0>>

	* uni04C5 (U+04C5): L<<510.0,77.0>--<510.0,77.0>> -> L<<510.0,77.0>--<510.0,77.0>>

	* uni2081 (U+2081): L<<274.0,386.0>--<315.0,382.0>> -> L<<315.0,382.0>--<358.0,382.0>>

	* uni2150 (U+2150): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* uni2151 (U+2151): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* uni2152 (U+2152): L<<196.0,854.0>--<237.0,850.0>> -> L<<237.0,850.0>--<280.0,850.0>>

	* uni2153 (U+2153): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* uni2155 (U+2155): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* uni2159 (U+2159): L<<207.0,854.0>--<248.0,850.0>> -> L<<248.0,850.0>--<291.0,850.0>>

	* uni215F (U+215F): L<<203.0,854.0>--<244.0,850.0>> -> L<<244.0,850.0>--<287.0,850.0>>

	* uni21C8 (U+21C8): L<<440.0,598.0>--<423.0,582.0>> -> L<<423.0,582.0>--<343.0,508.0>>

	* uni21CA (U+21CA): L<<297.0,292.0>--<345.0,218.0>> -> L<<345.0,218.0>--<356.0,202.0>>

	* uni21F6 (U+21F6): L<<281.0,272.0>--<348.0,321.0>> -> L<<348.0,321.0>--<367.0,335.0>>

	* uni25A9 (U+25A9): L<<403.0,220.0>--<403.0,220.0>> -> L<<403.0,220.0>--<454.0,220.0>>

	* uni25C1 (U+25C1): L<<534.0,74.0>--<448.0,126.0>> -> L<<448.0,126.0>--<46.0,370.0>>

	* uni25C3 (U+25C3): L<<444.0,183.0>--<370.0,228.0>> -> L<<370.0,228.0>--<136.0,370.0>>

	* uni25C5 (U+25C5): L<<534.0,165.0>--<452.0,200.0>> -> L<<452.0,200.0>--<29.0,370.0>>

	* uniE0A1 (U+E0A1): L<<305.0,12.0>--<307.0,-34.0>> -> L<<307.0,-34.0>--<307.0,-151.0>>

	* uniE0A1 (U+E0A1): L<<372.0,162.0>--<369.0,226.0>> -> L<<369.0,226.0>--<369.0,326.0>> 

	* xi (U+03BE): L<<643.0,800.0>--<635.0,759.0>> -> L<<635.0,759.0>--<629.0,711.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eta (U+03B7): L<<124.0,463.0>--<147.0,480.0>>/L<<147.0,480.0>--<127.0,467.0>> = 3.445366834255142

	* etatonos (U+03AE): L<<124.0,463.0>--<147.0,480.0>>/L<<147.0,480.0>--<127.0,467.0>> = 3.445366834255142

	* section (U+00A7): B<<414.0,397.0>-<399.0,420.0>-<354.0,424.0>>/L<<354.0,424.0>--<354.0,424.0>> = 5.0796078600145425

	* section (U+00A7): L<<354.0,424.0>--<354.0,424.0>>/B<<354.0,424.0>-<299.0,427.0>-<265.0,416.5>> = 3.1221304621157

	* uni0411 (U+0411): B<<104.0,223.0>-<107.0,236.0>-<110.0,249.0>>/B<<110.0,249.0>-<107.0,237.0>-<104.0,223.0>> = 1.041626676009815

	* uni0411 (U+0411): B<<110.0,249.0>-<107.0,237.0>-<104.0,223.0>>/B<<104.0,223.0>-<107.0,236.0>-<110.0,249.0>> = 0.8998597149042695

	* uni041C (U+041C): B<<167.5,141.0>-<164.0,224.0>-<165.0,365.0>>/B<<165.0,365.0>-<145.0,258.0>-<131.5,188.5>> = 10.180975084928074

	* uni041C (U+041C): B<<400.5,156.0>-<422.0,244.0>-<459.0,386.0>>/B<<459.0,386.0>-<440.0,341.0>-<423.5,303.0>> = 8.286104209458127

	* uni043B (U+043B): B<<430.0,117.0>-<434.0,89.0>-<434.0,84.0>>/B<<434.0,84.0>-<435.0,88.0>-<441.5,100.5>> = 14.036243467926484

	* uni043C (U+043C): B<<385.0,91.0>-<394.0,137.0>-<412.0,215.0>>/B<<412.0,215.0>-<362.0,112.0>-<321.0,49.0>> = 12.899030202311511

	* uni044A (U+044A): B<<179.5,114.0>-<164.0,175.0>-<180.0,255.0>>/B<<180.0,255.0>-<180.0,253.0>-<183.5,270.0>> = 11.309932474020195

	* uni044B (U+044B): B<<-4.5,114.0>-<-20.0,175.0>-<-4.0,255.0>>/B<<-4.0,255.0>-<-4.0,254.0>-<-1.0,268.0>> = 11.309932474020195

	* uni044C (U+044C): B<<93.5,114.0>-<78.0,175.0>-<94.0,255.0>>/B<<94.0,255.0>-<94.0,254.0>-<97.0,268.0>> = 11.309932474020195

	* uni0495 (U+0495): B<<190.0,225.5>-<153.0,191.0>-<135.0,104.0>>/L<<135.0,104.0>--<147.0,167.0>> = 0.9050713078765724

	* uni0495 (U+0495): L<<135.0,104.0>--<147.0,167.0>>/L<<147.0,167.0>--<112.0,0.0>> = 1.0524775003000704

	* uni04A6 (U+04A6): B<<371.0,365.5>-<345.0,331.0>-<326.0,244.0>>/L<<326.0,244.0>--<329.0,257.0>> = 0.675171535279699

	* uni04A6 (U+04A6): L<<326.0,244.0>--<329.0,257.0>>/L<<329.0,257.0>--<274.0,0.0>> = 0.9150858053016531

	* uni04A7 (U+04A7): B<<342.5,225.5>-<310.0,191.0>-<292.0,104.0>>/L<<292.0,104.0>--<299.0,141.0>> = 0.9762461526483608

	* uni04A7 (U+04A7): L<<292.0,104.0>--<299.0,141.0>>/L<<299.0,141.0>--<269.0,0.0>> = 1.2983553635744387

	* uni04C6 (U+04C6): B<<430.0,117.0>-<434.0,89.0>-<434.0,84.0>>/B<<434.0,84.0>-<435.0,88.0>-<441.5,100.5>> = 14.036243467926484

	* uni04CD (U+04CD): B<<127.5,141.0>-<124.0,224.0>-<125.0,365.0>>/B<<125.0,365.0>-<105.0,258.0>-<91.5,188.5>> = 10.180975084928074

	* uni04CD (U+04CD): B<<367.5,186.5>-<388.0,267.0>-<419.0,386.0>>/B<<419.0,386.0>-<400.0,341.0>-<383.5,303.0>> = 8.289279370414317

	* uni04CE (U+04CE): B<<383.5,84.5>-<392.0,131.0>-<412.0,215.0>>/B<<412.0,215.0>-<362.0,112.0>-<321.0,49.0>> = 12.501149240476877

	* uni04F9 (U+04F9): B<<-4.5,114.0>-<-20.0,175.0>-<-4.0,255.0>>/B<<-4.0,255.0>-<-4.0,254.0>-<-1.0,268.0>> = 11.309932474020195 

	* uni0513 (U+0513): B<<430.0,117.0>-<434.0,89.0>-<434.0,84.0>>/B<<434.0,84.0>-<435.0,88.0>-<441.5,100.5>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 28 | 152 | 1668 | 85 | 1290 | 0 |
| 0% | 1% | 5% | 52% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
