## Fontbakery report

Fontbakery version: 0.8.12

<details><summary><b>[23] VictorMono-ExtraLightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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

	* uni041C (U+041C): B<<459.0,237.5>-<486.0,370.0>-<532.0,591.0>>/B<<532.0,591.0>-<479.0,468.0>-<440.5,374.5>> = 11.55299951480003

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

	* uni04CE (U+04CE): B<<443.0,184.0>-<460.0,268.0>-<490.0,410.0>>/B<<490.0,410.0>-<452.0,324.0>-<415.5,247.5>> = 11.90941800593337

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
</div></details><br></div></details><details><summary><b>[22] VictorMono-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<362.0,803.0>--<404.0,800.0>> -> L<<404.0,800.0>--<446.0,800.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni0409 (U+0409): L<<270.0,803.0>--<311.0,800.0>> -> L<<311.0,800.0>--<495.0,800.0>>

	* uni042B (U+042B): L<<201.0,393.0>--<200.0,391.0>> -> L<<200.0,391.0>--<198.0,387.0>>

	* uni0459 (U+0459): L<<231.0,621.0>--<272.0,618.0>> -> L<<272.0,618.0>--<457.0,618.0>>

	* uni0490 (U+0490): L<<672.0,939.0>--<643.0,800.0>> -> L<<643.0,800.0>--<628.0,723.0>>

	* uni0491 (U+0491): L<<639.0,757.0>--<610.0,618.0>> -> L<<610.0,618.0>--<593.0,541.0>>

	* uni04A4 (U+04A4): L<<552.0,814.0>--<554.0,814.0>> -> L<<554.0,814.0>--<554.0,814.0>>

	* uni04A4 (U+04A4): L<<554.0,814.0>--<554.0,814.0>> -> L<<554.0,814.0>--<760.0,814.0>>

	* uni04C3 (U+04C3): L<<216.0,384.0>--<212.0,384.0>> -> L<<212.0,384.0>--<152.0,384.0>>

	* uni04CC (U+04CC): L<<277.0,64.0>--<355.0,64.0>> -> L<<355.0,64.0>--<355.0,64.0>>

	* uni04F8 (U+04F8): L<<201.0,393.0>--<200.0,391.0>> -> L<<200.0,391.0>--<198.0,387.0>>

	* uni2152 (U+2152): L<<196.0,853.0>--<230.0,850.0>> -> L<<230.0,850.0>--<269.0,850.0>>

	* uni21CE (U+21CE): L<<402.0,591.0>--<459.0,591.0>> -> L<<459.0,591.0>--<459.0,591.0>>

	* uni21F6 (U+21F6): L<<294.0,269.0>--<347.0,307.0>> -> L<<347.0,307.0>--<370.0,323.0>>

	* uni25C1 (U+25C1): L<<526.0,88.0>--<452.0,132.0>> -> L<<452.0,132.0>--<60.0,370.0>>

	* uni25C3 (U+25C3): L<<436.0,197.0>--<374.0,234.0>> -> L<<374.0,234.0>--<150.0,370.0>>

	* uni25C5 (U+25C5): L<<526.0,177.0>--<455.0,207.0>> -> L<<455.0,207.0>--<49.0,370.0>>

	* uniE0A1 (U+E0A1): L<<295.0,57.0>--<299.0,-34.0>> -> L<<299.0,-34.0>--<299.0,-144.0>>

	* uniE0A1 (U+E0A1): L<<382.0,117.0>--<377.0,226.0>> -> L<<377.0,226.0>--<377.0,319.0>> 

	* xi (U+03BE): L<<635.0,800.0>--<628.0,765.0>> -> L<<628.0,765.0>--<623.0,725.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* aacute (U+00E1): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* abreve (U+0103): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* acircumflex (U+00E2): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* adieresis (U+00E4): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* agrave (U+00E0): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* amacron (U+0101): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* aogonek (U+0105): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* aring (U+00E5): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* atilde (U+00E3): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* eta (U+03B7): L<<136.0,477.0>--<155.0,492.0>>/L<<155.0,492.0>--<138.0,481.0>> = 5.384920269255084

	* etatonos (U+03AE): L<<136.0,477.0>--<155.0,492.0>>/L<<155.0,492.0>--<138.0,481.0>> = 5.384920269255084

	* section (U+00A7): B<<420.5,403.0>-<403.0,430.0>-<347.0,433.0>>/L<<347.0,433.0>--<347.0,433.0>> = 3.0664855011258196

	* section (U+00A7): L<<347.0,433.0>--<347.0,433.0>>/B<<347.0,433.0>-<292.0,434.0>-<258.0,422.5>> = 1.041626676009815

	* uni01CE (U+01CE): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni0411 (U+0411): B<<89.0,141.0>-<89.0,134.0>-<89.0,130.0>>/B<<89.0,130.0>-<98.0,166.0>-<111.0,218.5>> = 14.036243467926484

	* uni0412 (U+0412): B<<104.0,237.0>-<109.0,266.0>-<115.0,299.0>>/B<<115.0,299.0>-<109.0,269.0>-<104.0,237.0>> = 1.0050860052537793

	* uni0412 (U+0412): B<<115.0,299.0>-<109.0,269.0>-<104.0,237.0>>/B<<104.0,237.0>-<109.0,266.0>-<115.0,299.0>> = 0.9017478812867337

	* uni041C (U+041C): B<<169.0,165.5>-<167.0,262.0>-<169.0,428.0>>/B<<169.0,428.0>-<142.0,289.0>-<123.5,201.5>> = 10.302230382402634

	* uni041C (U+041C): B<<421.5,186.0>-<446.0,290.0>-<486.0,460.0>>/B<<486.0,460.0>-<455.0,388.0>-<431.0,330.5>> = 10.054043338707212

	* uni0430 (U+0430): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni043C (U+043C): B<<403.0,118.5>-<415.0,177.0>-<439.0,278.0>>/B<<439.0,278.0>-<399.0,194.0>-<363.5,128.0>> = 12.09641436555474

	* uni046A (U+046A): L<<323.0,426.0>--<323.0,425.0>>/L<<323.0,425.0>--<326.0,447.0>> = 7.765166018425308

	* uni0495 (U+0495): B<<185.5,239.5>-<148.0,204.0>-<129.0,113.0>>/L<<129.0,113.0>--<140.0,169.0>> = 0.6803891489616283

	* uni0495 (U+0495): L<<129.0,113.0>--<140.0,169.0>>/L<<140.0,169.0>--<104.0,0.0>> = 0.9122390736868143

	* uni04A6 (U+04A6): B<<369.0,379.5>-<340.0,344.0>-<321.0,253.0>>/L<<321.0,253.0>--<324.0,272.0>> = 2.82080307001409

	* uni04A6 (U+04A6): L<<321.0,253.0>--<324.0,272.0>>/L<<324.0,272.0>--<267.0,0.0>> = 2.8629404655814823

	* uni04A7 (U+04A7): B<<341.0,239.5>-<308.0,204.0>-<289.0,113.0>>/L<<289.0,113.0>--<295.0,142.0>> = 0.1040605094705115

	* uni04A7 (U+04A7): L<<289.0,113.0>--<295.0,142.0>>/L<<295.0,142.0>--<264.0,0.0>> = 0.6256493038352423

	* uni04CD (U+04CD): B<<139.0,165.5>-<137.0,262.0>-<138.0,428.0>>/B<<138.0,428.0>-<111.0,289.0>-<93.0,201.5>> = 10.647356457103584

	* uni04CD (U+04CD): B<<397.0,213.5>-<421.0,312.0>-<456.0,460.0>>/B<<456.0,460.0>-<425.0,388.0>-<400.5,330.5>> = 9.989326747803279

	* uni04CE (U+04CE): B<<407.0,137.0>-<419.0,192.0>-<439.0,278.0>>/B<<439.0,278.0>-<399.0,194.0>-<363.5,128.0>> = 12.371451997524732

	* uni04D1 (U+04D1): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni04D3 (U+04D3): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EA1 (U+1EA1): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EA3 (U+1EA3): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EA5 (U+1EA5): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EA7 (U+1EA7): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EA9 (U+1EA9): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EAB (U+1EAB): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EAD (U+1EAD): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EAF (U+1EAF): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EB1 (U+1EB1): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EB3 (U+1EB3): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546

	* uni1EB5 (U+1EB5): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546 

	* uni1EB7 (U+1EB7): B<<347.0,61.5>-<347.0,68.0>-<349.0,70.0>>/B<<349.0,70.0>-<320.0,31.0>-<280.0,8.5>> = 8.365886124032546 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[22] VictorMono-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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

	* uni041C (U+041C): B<<459.0,237.5>-<486.0,370.0>-<532.0,591.0>>/B<<532.0,591.0>-<479.0,468.0>-<440.5,374.5>> = 11.55299951480003

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

	* uni04CE (U+04CE): B<<443.0,184.0>-<460.0,268.0>-<490.0,410.0>>/B<<490.0,410.0>-<452.0,324.0>-<415.5,247.5>> = 11.90941800593337

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
</div></details><br></div></details><details><summary><b>[22] VictorMono-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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

	* uni04CD (U+04CD): B<<127.5,141.0>-<124.0,224.0>-<125.0,365.0>>/B<<125.0,365.0>-<105.0,258.0>-<91.5,188.5>> = 10.180975084928074

	* uni04CD (U+04CD): B<<367.5,186.5>-<388.0,267.0>-<419.0,386.0>>/B<<419.0,386.0>-<400.0,341.0>-<383.5,303.0>> = 8.289279370414317

	* uni04CE (U+04CE): B<<383.5,84.5>-<392.0,131.0>-<412.0,215.0>>/B<<412.0,215.0>-<362.0,112.0>-<321.0,49.0>> = 12.501149240476877 

	* uni04F9 (U+04F9): B<<-4.5,114.0>-<-20.0,175.0>-<-4.0,255.0>>/B<<-4.0,255.0>-<-4.0,254.0>-<-1.0,268.0>> = 11.309932474020195 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[22] VictorMono-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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

	* uni041C (U+041C): B<<459.0,237.5>-<486.0,370.0>-<532.0,591.0>>/B<<532.0,591.0>-<479.0,468.0>-<440.5,374.5>> = 11.55299951480003

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

	* uni04CE (U+04CE): B<<443.0,184.0>-<460.0,268.0>-<490.0,410.0>>/B<<490.0,410.0>-<452.0,324.0>-<415.5,247.5>> = 11.90941800593337

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
</div></details><br></div></details><details><summary><b>[24] VictorMono-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* yen (U+00A5) contains a short segment L<<266.0,302.0>--<265.0,304.0>>

	* yen (U+00A5) contains a short segment L<<335.0,304.0>--<335.0,302.0>>

	* section (U+00A7) contains a short segment B<<295.0,507.0>-<302.0,507.0>-<310.0,507.0>>

	* section (U+00A7) contains a short segment B<<305.0,111.0>-<298.0,111.0>-<291.0,111.0>>

	* section (U+00A7) contains a short segment L<<291.0,177.0>--<291.0,177.0>>

	* section (U+00A7) contains a short segment L<<310.0,441.0>--<310.0,441.0>>

	* uni00B9 (U+00B9) contains a short segment L<<269.0,850.0>--<269.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* germandbls (U+00DF) contains a short segment L<<260.0,457.0>--<279.0,457.0>>

	* xi (U+03BE) contains a short segment B<<514.0,800.0>-<519.0,801.0>-<524.0,802.0>>

	* xi (U+03BE) contains a short segment L<<524.0,737.0>--<516.0,737.0>>

	* xi (U+03BE) contains a short segment B<<512.0,505.0>-<518.0,506.0>-<524.0,507.0>>

	* xi (U+03BE) contains a short segment B<<523.0,441.0>-<519.0,441.0>-<515.0,441.0>>

	* rho (U+03C1) contains a short segment L<<76.0,309.0>--<76.0,309.0>>

	* rho (U+03C1) contains a short segment L<<76.0,309.0>--<76.0,309.0>>

	* omega (U+03C9) contains a short segment B<<265.0,320.0>-<265.0,325.0>-<266.0,333.0>>

	* omega (U+03C9) contains a short segment B<<335.0,333.0>-<335.0,325.0>-<335.0,319.0>>

	* omegatonos (U+03CE) contains a short segment B<<265.0,320.0>-<265.0,325.0>-<266.0,333.0>>

	* omegatonos (U+03CE) contains a short segment B<<335.0,333.0>-<335.0,325.0>-<335.0,319.0>>

	* uni0404 (U+0404) contains a short segment L<<127.0,368.0>--<127.0,360.0>>

	* uni042D (U+042D) contains a short segment L<<474.0,432.0>--<474.0,440.0>>

	* uni042E (U+042E) contains a short segment L<<188.0,432.0>--<188.0,440.0>>

	* uni043A (U+043A) contains a short segment B<<241.0,300.0>-<233.0,299.0>-<225.0,299.0>>

	* uni044A (U+044A) contains a short segment L<<189.0,555.0>--<189.0,555.0>>

	* uni044D (U+044D) contains a short segment L<<474.0,341.0>--<474.0,349.0>>

	* uni044E (U+044E) contains a short segment L<<188.0,341.0>--<188.0,349.0>>

	* uni0454 (U+0454) contains a short segment L<<127.0,277.0>--<127.0,269.0>>

	* uni045C (U+045C) contains a short segment B<<241.0,300.0>-<233.0,299.0>-<225.0,299.0>>

	* uni0464 (U+0464) contains a short segment L<<188.0,432.0>--<188.0,440.0>>

	* uni0464 (U+0464) contains a short segment L<<257.0,368.0>--<257.0,360.0>>

	* uni0465 (U+0465) contains a short segment L<<188.0,341.0>--<188.0,349.0>>

	* uni0465 (U+0465) contains a short segment L<<257.0,277.0>--<257.0,269.0>>

	* uni046A (U+046A) contains a short segment B<<284.0,440.0>-<291.0,440.0>-<300.0,440.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,440.0>-<309.0,440.0>-<316.0,440.0>>

	* uni046B (U+046B) contains a short segment B<<280.0,360.0>-<289.0,360.0>-<300.0,360.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,360.0>-<311.0,360.0>-<320.0,360.0>>

	* uni0494 (U+0494) contains a short segment B<<283.5,-193.5>-<270.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-120.0>-<270.0,-127.0>-<283.5,-130.0>>

	* uni049B (U+049B) contains a short segment B<<241.0,300.0>-<233.0,299.0>-<225.0,299.0>>

	* uni049F (U+049F) contains a short segment B<<245.0,300.0>-<237.0,299.0>-<228.0,299.0>>

	* uni04A1 (U+04A1) contains a short segment B<<241.0,300.0>-<233.0,299.0>-<225.0,299.0>>

	* uni04A6 (U+04A6) contains a short segment B<<401.5,-193.5>-<388.0,-191.0>-<378.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<378.0,-120.0>-<388.0,-127.0>-<401.5,-130.0>>

	* uni04A7 (U+04A7) contains a short segment B<<390.0,-193.5>-<377.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-120.0>-<377.0,-127.0>-<389.5,-130.0>>

	* uni04A8 (U+04A8) contains a short segment B<<279.0,49.0>-<287.0,49.0>-<296.0,50.0>>

	* uni04B0 (U+04B0) contains a short segment L<<266.0,302.0>--<266.0,302.0>>

	* uni04B0 (U+04B0) contains a short segment L<<335.0,302.0>--<335.0,302.0>>

	* uni04C3 (U+04C3) contains a short segment B<<256.5,-193.5>-<243.0,-191.0>-<233.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<233.0,-120.0>-<243.0,-127.0>-<256.5,-130.0>>

	* uni04C3 (U+04C3) contains a short segment L<<209.0,391.0>--<209.0,391.0>>

	* uni04C3 (U+04C3) contains a short segment L<<209.0,391.0>--<207.0,391.0>>

	* uni04E0 (U+04E0) contains a short segment L<<313.0,455.0>--<320.0,455.0>>

	* uni04E1 (U+04E1) contains a short segment L<<310.0,273.0>--<320.0,273.0>>

	* uni04EC (U+04EC) contains a short segment L<<474.0,432.0>--<474.0,440.0>>

	* uni04ED (U+04ED) contains a short segment L<<474.0,341.0>--<474.0,349.0>>

	* uni2081 (U+2081) contains a short segment L<<269.0,377.0>--<269.0,377.0>>

	* lira (U+20A4) contains a short segment L<<131.0,508.0>--<131.0,512.0>>

	* lira (U+20A4) contains a short segment B<<200.0,516.0>-<200.0,512.0>-<200.0,508.0>>

	* uni2150 (U+2150) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<227.0,377.0>--<227.0,377.0>>

	* uni2153 (U+2153) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<103.0,850.0>--<103.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<101.0,850.0>--<101.0,850.0>>

	* uni21C8 (U+21C8) contains a short segment L<<346.0,592.0>--<347.0,591.0>>

	* uni21C8 (U+21C8) contains a short segment L<<253.0,591.0>--<254.0,591.0>>

	* uni21CA (U+21CA) contains a short segment L<<254.0,209.0>--<253.0,209.0>>

	* uni21CA (U+21CA) contains a short segment L<<347.0,209.0>--<346.0,208.0>>

	* uni21CE (U+21CE) contains a short segment L<<188.0,217.0>--<195.0,208.0>>

	* uni21CE (U+21CE) contains a short segment L<<411.0,584.0>--<405.0,592.0>>

	* uni21F6 (U+21F6) contains a short segment L<<305.0,265.0>--<306.0,265.0>>

	* uni21F6 (U+21F6) contains a short segment L<<306.0,265.0>--<305.0,266.0>>

	* uni21F6 (U+21F6) contains a short segment L<<305.0,534.0>--<306.0,535.0>>

	* uni21F6 (U+21F6) contains a short segment L<<306.0,535.0>--<305.0,535.0>>

	* uni2285 (U+2285) contains a short segment L<<215.0,63.0>--<221.0,63.0>>

	* uni2573 (U+2573) contains a short segment L<<0.0,1200.0>--<37.0,1200.0>>

	* uni2573 (U+2573) contains a short segment L<<563.0,1200.0>--<600.0,1200.0>>

	* uni2573 (U+2573) contains a short segment L<<600.0,-400.0>--<563.0,-400.0>>

	* uni2573 (U+2573) contains a short segment L<<37.0,-400.0>--<0.0,-400.0>>

	* uni25A9 (U+25A9) contains a short segment L<<131.0,299.0>--<131.0,300.0>>

	* uni25A9 (U+25A9) contains a short segment L<<131.0,300.0>--<131.0,300.0>> 

	* uni25A9 (U+25A9) contains a short segment L<<131.0,300.0>--<131.0,299.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* oneeighth (U+215B): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* onehalf (U+00BD): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* onehalf (U+00BD): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* onequarter (U+00BC): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* onequarter (U+00BC): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* rho (U+03C1): L<<76.0,309.0>--<76.0,309.0>> -> L<<76.0,309.0>--<76.0,309.0>>

	* uni00B9 (U+00B9): L<<268.0,850.0>--<269.0,850.0>> -> L<<269.0,850.0>--<269.0,850.0>>

	* uni00B9 (U+00B9): L<<269.0,850.0>--<269.0,850.0>> -> L<<269.0,850.0>--<332.0,850.0>>

	* uni04B0 (U+04B0): L<<125.0,302.0>--<266.0,302.0>> -> L<<266.0,302.0>--<266.0,302.0>>

	* uni04B0 (U+04B0): L<<335.0,302.0>--<335.0,302.0>> -> L<<335.0,302.0>--<476.0,302.0>>

	* uni04C3 (U+04C3): L<<209.0,391.0>--<207.0,391.0>> -> L<<207.0,391.0>--<138.0,391.0>>

	* uni2081 (U+2081): L<<268.0,377.0>--<269.0,377.0>> -> L<<269.0,377.0>--<269.0,377.0>>

	* uni2081 (U+2081): L<<269.0,377.0>--<269.0,377.0>> -> L<<269.0,377.0>--<332.0,377.0>>

	* uni2150 (U+2150): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* uni2150 (U+2150): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* uni2151 (U+2151): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* uni2151 (U+2151): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* uni2152 (U+2152): L<<226.0,377.0>--<227.0,377.0>> -> L<<227.0,377.0>--<227.0,377.0>>

	* uni2152 (U+2152): L<<227.0,377.0>--<227.0,377.0>> -> L<<227.0,377.0>--<290.0,377.0>>

	* uni2152 (U+2152): L<<81.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<82.0,850.0>>

	* uni2152 (U+2152): L<<82.0,850.0>--<82.0,850.0>> -> L<<82.0,850.0>--<145.0,850.0>>

	* uni2153 (U+2153): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* uni2153 (U+2153): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* uni2155 (U+2155): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* uni2155 (U+2155): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* uni2159 (U+2159): L<<102.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<103.0,850.0>>

	* uni2159 (U+2159): L<<103.0,850.0>--<103.0,850.0>> -> L<<103.0,850.0>--<166.0,850.0>>

	* uni215F (U+215F): L<<100.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<101.0,850.0>>

	* uni215F (U+215F): L<<101.0,850.0>--<101.0,850.0>> -> L<<101.0,850.0>--<164.0,850.0>>

	* uni25C1 (U+25C1): L<<519.0,101.0>--<456.0,138.0>> -> L<<456.0,138.0>--<74.0,370.0>>

	* uni25C3 (U+25C3): L<<429.0,210.0>--<378.0,240.0>> -> L<<378.0,240.0>--<164.0,370.0>>

	* uni25C5 (U+25C5): L<<519.0,187.0>--<458.0,213.0>> -> L<<458.0,213.0>--<67.0,370.0>>

	* uniE0A1 (U+E0A1): L<<285.0,99.0>--<292.0,-35.0>> -> L<<292.0,-35.0>--<292.0,-137.0>>

	* uniE0A1 (U+E0A1): L<<392.0,75.0>--<385.0,227.0>> -> L<<385.0,227.0>--<385.0,312.0>> 

	* yen (U+00A5): L<<335.0,304.0>--<335.0,302.0>> -> L<<335.0,302.0>--<335.0,230.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<404.5,406.0>-<377.0,439.0>-<310.0,441.0>>/L<<310.0,441.0>--<310.0,441.0>> = 1.709814044141387 

	* section (U+00A7): L<<310.0,441.0>--<310.0,441.0>>/B<<310.0,441.0>-<255.0,442.0>-<224.5,429.5>> = 1.041626676009815 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<266.0,791.0>--<77.0,792.0>>

	* uni2077 (U+2077): L<<356.0,791.0>--<167.0,792.0>>

	* uni2087 (U+2087): L<<356.0,318.0>--<167.0,319.0>>

	* uni2150 (U+2150): L<<523.0,318.0>--<334.0,319.0>>

	* uni2196 (U+2196): L<<47.0,683.0>--<373.0,682.0>>

	* uni2196 (U+2196): L<<48.0,357.0>--<47.0,683.0>>

	* uni2197 (U+2197): L<<227.0,682.0>--<553.0,683.0>>

	* uni2197 (U+2197): L<<553.0,683.0>--<552.0,357.0>>

	* uni2198 (U+2198): L<<552.0,475.0>--<553.0,149.0>>

	* uni2199 (U+2199): L<<47.0,149.0>--<48.0,475.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<353.0,682.0>>

	* uni21D6 (U+21D6): L<<28.0,357.0>--<27.0,683.0>>

	* uni21D7 (U+21D7): L<<247.0,682.0>--<573.0,683.0>>

	* uni21D7 (U+21D7): L<<573.0,683.0>--<572.0,357.0>>

	* uni21D8 (U+21D8): L<<572.0,443.0>--<573.0,117.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<247.0,118.0>>

	* uni21D9 (U+21D9): L<<27.0,117.0>--<28.0,443.0>> 

	* uni21D9 (U+21D9): L<<353.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[22] VictorMono-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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

	- Glyph name: uni043C	Contours detected: 2	Expected: 1

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

	- Glyph name: uni043C	Contours detected: 2	Expected: 1

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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<369.0,800.0>--<370.0,800.0>> -> L<<370.0,800.0>--<370.0,800.0>>

	* one (U+0031): L<<370.0,803.0>--<404.0,800.0>> -> L<<404.0,800.0>--<439.0,800.0>>

	* sigma (U+03C3): L<<369.0,632.0>--<369.0,632.0>> -> L<<369.0,632.0>--<639.0,632.0>>

	* uni0409 (U+0409): L<<270.0,803.0>--<304.0,800.0>> -> L<<304.0,800.0>--<481.0,800.0>>

	* uni0459 (U+0459): L<<231.0,621.0>--<265.0,618.0>> -> L<<265.0,618.0>--<443.0,618.0>>

	* uni0490 (U+0490): L<<665.0,933.0>--<637.0,800.0>> -> L<<637.0,800.0>--<625.0,737.0>>

	* uni0491 (U+0491): L<<630.0,751.0>--<603.0,618.0>> -> L<<603.0,618.0>--<589.0,555.0>>

	* uni04A4 (U+04A4): L<<559.0,814.0>--<559.0,814.0>> -> L<<559.0,814.0>--<759.0,814.0>>

	* uni04B0 (U+04B0): L<<125.0,302.0>--<265.0,302.0>> -> L<<265.0,302.0>--<265.0,302.0>>

	* uni04B0 (U+04B0): L<<334.0,302.0>--<334.0,302.0>> -> L<<334.0,302.0>--<476.0,302.0>>

	* uni04C3 (U+04C3): L<<230.0,391.0>--<227.0,391.0>> -> L<<227.0,391.0>--<155.0,391.0>>

	* uni04F6 (U+04F6): L<<60.0,-14.0>--<60.0,-14.0>> -> L<<60.0,-14.0>--<60.0,-14.0>>

	* uni25C1 (U+25C1): L<<519.0,101.0>--<456.0,138.0>> -> L<<456.0,138.0>--<74.0,370.0>>

	* uni25C3 (U+25C3): L<<429.0,210.0>--<378.0,240.0>> -> L<<378.0,240.0>--<164.0,370.0>>

	* uni25C5 (U+25C5): L<<519.0,187.0>--<458.0,213.0>> -> L<<458.0,213.0>--<67.0,370.0>>

	* uniE0A1 (U+E0A1): L<<285.0,99.0>--<292.0,-35.0>> -> L<<292.0,-35.0>--<292.0,-137.0>>

	* uniE0A1 (U+E0A1): L<<392.0,75.0>--<385.0,227.0>> -> L<<385.0,227.0>--<385.0,312.0>> 

	* xi (U+03BE): L<<628.0,800.0>--<622.0,770.0>> -> L<<622.0,770.0>--<618.0,738.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* aacute (U+00E1): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* abreve (U+0103): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* acircumflex (U+00E2): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* adieresis (U+00E4): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* agrave (U+00E0): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* amacron (U+0101): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* aogonek (U+0105): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* aring (U+00E5): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* atilde (U+00E3): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* eta (U+03B7): L<<146.0,491.0>--<163.0,504.0>>/L<<163.0,504.0>--<148.0,494.0>> = 3.7152891054287163

	* etatonos (U+03AE): L<<146.0,491.0>--<163.0,504.0>>/L<<163.0,504.0>--<148.0,494.0>> = 3.7152891054287163

	* section (U+00A7): L<<340.0,441.0>--<340.0,441.0>>/B<<340.0,441.0>-<286.0,442.0>-<252.0,428.5>> = 1.0609116902641509

	* uni01CE (U+01CE): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni040C (U+040C): B<<148.5,421.0>-<179.0,555.0>-<222.0,750.0>>/B<<222.0,750.0>-<221.0,747.0>-<221.0,749.0>> = 5.999507320394351

	* uni0411 (U+0411): B<<82.0,134.0>-<82.0,93.0>-<80.0,73.0>>/B<<80.0,73.0>-<82.0,80.0>-<85.0,91.0>> = 10.234802763423207

	* uni0412 (U+0412): B<<110.0,227.0>-<134.0,348.0>-<175.0,536.0>>/B<<175.0,536.0>-<146.0,468.0>-<128.5,395.0>> = 10.794095592918126

	* uni0412 (U+0412): B<<87.5,142.0>-<84.0,95.0>-<84.0,79.0>>/B<<84.0,79.0>-<86.0,106.0>-<110.0,227.0>> = 4.236394799058849

	* uni041A (U+041A): B<<148.5,421.0>-<179.0,555.0>-<222.0,750.0>>/B<<222.0,750.0>-<221.0,747.0>-<221.0,749.0>> = 5.999507320394351

	* uni041C (U+041C): B<<170.5,248.0>-<171.0,344.0>-<173.0,486.0>>/B<<173.0,486.0>-<143.0,343.0>-<122.0,247.0>> = 11.04133678331204

	* uni041C (U+041C): B<<439.0,210.5>-<465.0,328.0>-<508.0,522.0>>/B<<508.0,522.0>-<467.0,426.0>-<436.0,352.0>> = 10.628987665308317

	* uni0430 (U+0430): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni0436 (U+0436): L<<394.0,618.0>--<302.0,206.0>>/L<<302.0,206.0>--<395.0,391.0>> = 14.101106586835634

	* uni043C (U+043C): B<<151.0,159.5>-<143.0,223.0>-<139.0,324.0>>/B<<139.0,324.0>-<117.0,217.0>-<102.0,150.5>> = 13.886478888700472

	* uni043C (U+043C): B<<420.5,144.0>-<435.0,215.0>-<462.0,338.0>>/B<<462.0,338.0>-<417.0,239.0>-<376.5,159.0>> = 12.06319785160932

	* uni0495 (U+0495): B<<156.5,220.5>-<136.0,184.0>-<123.0,121.0>>/L<<123.0,121.0>--<133.0,172.0>> = 0.5655696419656314

	* uni0495 (U+0495): L<<123.0,121.0>--<133.0,172.0>>/L<<133.0,172.0>--<97.0,0.0>> = 0.7277653290495846

	* uni0497 (U+0497): L<<394.0,618.0>--<302.0,206.0>>/L<<302.0,206.0>--<395.0,391.0>> = 14.101106586835634

	* uni049A (U+049A): B<<148.5,421.0>-<179.0,555.0>-<222.0,750.0>>/B<<222.0,750.0>-<221.0,747.0>-<221.0,749.0>> = 5.999507320394351

	* uni049E (U+049E): B<<215.5,702.0>-<221.0,725.0>-<226.0,750.0>>/B<<226.0,750.0>-<225.0,747.0>-<225.0,749.0>> = 7.125016348901705

	* uni04A6 (U+04A6): B<<367.5,392.0>-<336.0,355.0>-<315.0,261.0>>/L<<315.0,261.0>--<323.0,295.0>> = 0.6471899590838583

	* uni04A6 (U+04A6): L<<315.0,261.0>--<323.0,295.0>>/L<<323.0,295.0>--<260.0,0.0>> = 1.1855607800357206

	* uni04A7 (U+04A7): B<<340.0,252.0>-<306.0,215.0>-<286.0,121.0>>/L<<286.0,121.0>--<289.0,138.0>> = 2.0034985849241354

	* uni04A7 (U+04A7): L<<286.0,121.0>--<289.0,138.0>>/L<<289.0,138.0>--<260.0,0.0>> = 1.859752096124908

	* uni04B6 (U+04B6): L<<594.0,61.0>--<594.0,62.0>>/L<<594.0,62.0>--<556.0,-118.0>> = 11.920738539922306

	* uni04C2 (U+04C2): L<<394.0,618.0>--<302.0,206.0>>/L<<302.0,206.0>--<395.0,391.0>> = 14.101106586835634

	* uni04CD (U+04CD): B<<149.0,248.0>-<149.0,344.0>-<151.0,486.0>>/B<<151.0,486.0>-<122.0,343.0>-<101.0,247.0>> = 10.657023560590153

	* uni04CD (U+04CD): B<<422.5,233.0>-<448.0,346.0>-<487.0,522.0>>/B<<487.0,522.0>-<446.0,426.0>-<415.0,352.0>> = 10.63218667033068

	* uni04CE (U+04CE): B<<151.0,159.5>-<143.0,223.0>-<139.0,324.0>>/B<<139.0,324.0>-<117.0,217.0>-<102.0,150.5>> = 13.886478888700472

	* uni04CE (U+04CE): B<<423.5,159.0>-<438.0,227.0>-<462.0,338.0>>/B<<462.0,338.0>-<417.0,239.0>-<376.5,159.0>> = 12.24348605303573

	* uni04D1 (U+04D1): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni04D3 (U+04D3): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni04DD (U+04DD): L<<394.0,618.0>--<302.0,206.0>>/L<<302.0,206.0>--<395.0,391.0>> = 14.101106586835634

	* uni1EA1 (U+1EA1): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EA3 (U+1EA3): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EA5 (U+1EA5): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EA7 (U+1EA7): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EA9 (U+1EA9): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EAB (U+1EAB): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EAD (U+1EAD): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EAF (U+1EAF): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EB1 (U+1EB1): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EB3 (U+1EB3): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158

	* uni1EB5 (U+1EB5): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158 

	* uni1EB7 (U+1EB7): B<<355.0,71.5>-<356.0,83.0>-<359.0,89.0>>/B<<359.0,89.0>-<330.0,42.0>-<287.0,14.0>> = 5.110417561031158 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[22] VictorMono-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1450 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['f'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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

	* uni041C (U+041C): B<<459.0,237.5>-<486.0,370.0>-<532.0,591.0>>/B<<532.0,591.0>-<479.0,468.0>-<440.5,374.5>> = 11.55299951480003

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

	* uni04CE (U+04CE): B<<443.0,184.0>-<460.0,268.0>-<490.0,410.0>>/B<<490.0,410.0>-<452.0,324.0>-<415.5,247.5>> = 11.90941800593337

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
</div></details><br></div></details><details><summary><b>[24] VictorMono-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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
</div></details><br></div></details><details><summary><b>[24] VictorMono-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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
</div></details><br></div></details><details><summary><b>[25] VictorMono-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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
</div></details><br></div></details><details><summary><b>[24] VictorMono-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
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
</div></details><br></div></details><details><summary><b>[24] VictorMono-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment B<<234.0,400.0>-<227.0,394.0>-<220.0,388.0>>

	* m (U+006D) contains a short segment L<<124.0,618.0>--<124.0,593.0>>

	* sterling (U+00A3) contains a short segment B<<236.0,362.0>-<239.0,355.0>-<243.0,347.0>>

	* yen (U+00A5) contains a short segment L<<258.0,298.0>--<257.0,300.0>>

	* yen (U+00A5) contains a short segment L<<343.0,300.0>--<342.0,298.0>>

	* section (U+00A7) contains a short segment L<<317.0,433.0>--<317.0,433.0>>

	* uni00B9 (U+00B9) contains a short segment L<<264.0,850.0>--<264.0,850.0>>

	* onequarter (U+00BC) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* onehalf (U+00BD) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* eth (U+00F0) contains a short segment L<<542.0,240.0>--<542.0,240.0>>

	* OE (U+0152) contains a short segment L<<301.0,0.0>--<301.0,17.0>>

	* xi (U+03BE) contains a short segment B<<513.0,800.0>-<522.0,802.0>-<531.0,803.0>>

	* xi (U+03BE) contains a short segment L<<531.0,723.0>--<517.0,723.0>>

	* xi (U+03BE) contains a short segment B<<510.0,509.0>-<520.0,511.0>-<531.0,512.0>>

	* xi (U+03BE) contains a short segment B<<531.0,432.0>-<524.0,432.0>-<517.0,432.0>>

	* rho (U+03C1) contains a short segment L<<68.0,308.0>--<68.0,308.0>>

	* rho (U+03C1) contains a short segment L<<68.0,308.0>--<68.0,309.0>>

	* uni0404 (U+0404) contains a short segment L<<134.0,361.0>--<134.0,360.0>>

	* uni040E (U+040E) contains a short segment B<<325.0,208.0>-<327.0,214.0>-<329.0,222.0>>

	* uni0423 (U+0423) contains a short segment B<<325.0,208.0>-<327.0,214.0>-<329.0,222.0>>

	* uni042D (U+042D) contains a short segment L<<466.0,439.0>--<466.0,440.0>>

	* uni042E (U+042E) contains a short segment L<<184.0,439.0>--<184.0,440.0>>

	* uni043A (U+043A) contains a short segment B<<234.0,293.0>-<225.0,292.0>-<216.0,292.0>>

	* uni044A (U+044A) contains a short segment L<<200.0,541.0>--<199.0,541.0>>

	* uni044D (U+044D) contains a short segment L<<466.0,348.0>--<466.0,349.0>>

	* uni044E (U+044E) contains a short segment L<<184.0,348.0>--<184.0,349.0>>

	* uni0454 (U+0454) contains a short segment L<<134.0,270.0>--<134.0,269.0>>

	* uni045C (U+045C) contains a short segment B<<234.0,293.0>-<225.0,292.0>-<216.0,292.0>>

	* uni0464 (U+0464) contains a short segment L<<184.0,439.0>--<184.0,440.0>>

	* uni0464 (U+0464) contains a short segment L<<268.0,361.0>--<268.0,360.0>>

	* uni0465 (U+0465) contains a short segment L<<184.0,348.0>--<184.0,349.0>>

	* uni0465 (U+0465) contains a short segment L<<268.0,270.0>--<268.0,269.0>>

	* uni046A (U+046A) contains a short segment B<<288.0,447.0>-<294.0,447.0>-<300.0,447.0>>

	* uni046A (U+046A) contains a short segment B<<300.0,447.0>-<306.0,447.0>-<312.0,447.0>>

	* uni046B (U+046B) contains a short segment B<<281.0,367.0>-<290.0,367.0>-<300.0,367.0>>

	* uni046B (U+046B) contains a short segment B<<300.0,367.0>-<310.0,367.0>-<319.0,367.0>>

	* uni0494 (U+0494) contains a short segment B<<283.0,-193.5>-<270.0,-191.0>-<260.0,-184.0>>

	* uni0494 (U+0494) contains a short segment B<<260.0,-106.0>-<270.0,-113.0>-<283.0,-116.0>>

	* uni0495 (U+0495) contains a short segment B<<285.0,-193.5>-<273.0,-191.0>-<264.0,-184.0>>

	* uni0495 (U+0495) contains a short segment B<<264.0,-106.0>-<273.0,-113.0>-<285.0,-116.0>>

	* uni049B (U+049B) contains a short segment B<<234.0,293.0>-<225.0,292.0>-<216.0,292.0>>

	* uni049F (U+049F) contains a short segment B<<241.0,293.0>-<232.0,292.0>-<222.0,292.0>>

	* uni04A1 (U+04A1) contains a short segment B<<234.0,293.0>-<225.0,292.0>-<216.0,292.0>>

	* uni04A6 (U+04A6) contains a short segment B<<393.0,-193.5>-<380.0,-191.0>-<370.0,-184.0>>

	* uni04A6 (U+04A6) contains a short segment B<<370.0,-106.0>-<380.0,-113.0>-<393.0,-116.0>>

	* uni04A7 (U+04A7) contains a short segment B<<389.0,-193.5>-<377.0,-191.0>-<367.0,-184.0>>

	* uni04A7 (U+04A7) contains a short segment B<<367.0,-106.0>-<377.0,-113.0>-<388.5,-116.0>>

	* uni04B0 (U+04B0) contains a short segment L<<258.0,297.0>--<258.0,298.0>>

	* uni04B0 (U+04B0) contains a short segment L<<342.0,298.0>--<342.0,297.0>>

	* uni04C3 (U+04C3) contains a short segment B<<255.5,-193.5>-<242.0,-191.0>-<232.0,-184.0>>

	* uni04C3 (U+04C3) contains a short segment B<<232.0,-106.0>-<242.0,-113.0>-<255.5,-116.0>>

	* uni04C3 (U+04C3) contains a short segment L<<196.0,384.0>--<196.0,384.0>>

	* uni04C3 (U+04C3) contains a short segment L<<196.0,384.0>--<192.0,384.0>>

	* uni04E8 (U+04E8) contains a short segment L<<466.0,439.0>--<466.0,440.0>>

	* uni04E8 (U+04E8) contains a short segment L<<134.0,361.0>--<134.0,360.0>>

	* uni04EA (U+04EA) contains a short segment L<<466.0,439.0>--<466.0,440.0>>

	* uni04EA (U+04EA) contains a short segment L<<134.0,361.0>--<134.0,360.0>>

	* uni04EC (U+04EC) contains a short segment L<<466.0,439.0>--<466.0,440.0>>

	* uni04ED (U+04ED) contains a short segment L<<466.0,348.0>--<466.0,349.0>>

	* uni04EE (U+04EE) contains a short segment B<<325.0,208.0>-<327.0,214.0>-<329.0,222.0>>

	* uni04F0 (U+04F0) contains a short segment B<<325.0,208.0>-<327.0,214.0>-<329.0,222.0>>

	* uni04F2 (U+04F2) contains a short segment B<<325.0,208.0>-<327.0,214.0>-<329.0,222.0>>

	* uni2081 (U+2081) contains a short segment L<<264.0,379.0>--<264.0,379.0>>

	* uni2150 (U+2150) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2151 (U+2151) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<81.0,850.0>--<81.0,850.0>>

	* uni2152 (U+2152) contains a short segment L<<225.0,488.0>--<225.0,485.0>>

	* uni2152 (U+2152) contains a short segment L<<215.0,379.0>--<215.0,379.0>>

	* uni2153 (U+2153) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2155 (U+2155) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni2159 (U+2159) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* oneeighth (U+215B) contains a short segment L<<98.0,850.0>--<98.0,850.0>>

	* uni215F (U+215F) contains a short segment L<<95.0,850.0>--<95.0,850.0>>

	* uni21C8 (U+21C8) contains a short segment L<<355.0,587.0>--<355.0,587.0>>

	* uni21C8 (U+21C8) contains a short segment L<<245.0,586.0>--<246.0,587.0>>

	* uni21CA (U+21CA) contains a short segment L<<246.0,213.0>--<245.0,214.0>>

	* uni21CA (U+21CA) contains a short segment L<<355.0,213.0>--<355.0,213.0>>

	* uni21CE (U+21CE) contains a short segment L<<200.0,210.0>--<201.0,209.0>>

	* uni21CE (U+21CE) contains a short segment L<<399.0,591.0>--<399.0,591.0>>

	* uni21E1 (U+21E1) contains a short segment L<<300.0,693.0>--<298.0,691.0>>

	* uni21E1 (U+21E1) contains a short segment L<<302.0,691.0>--<300.0,693.0>>

	* uni21E3 (U+21E3) contains a short segment L<<300.0,107.0>--<302.0,109.0>>

	* uni21E3 (U+21E3) contains a short segment L<<298.0,109.0>--<300.0,107.0>>

	* uni21F6 (U+21F6) contains a short segment L<<292.0,268.0>--<293.0,268.0>>

	* uni21F6 (U+21F6) contains a short segment L<<293.0,268.0>--<292.0,269.0>>

	* uni21F6 (U+21F6) contains a short segment L<<352.0,319.0>--<356.0,323.0>>

	* uni21F6 (U+21F6) contains a short segment L<<356.0,323.0>--<356.0,323.0>>

	* uni21F6 (U+21F6) contains a short segment L<<292.0,531.0>--<293.0,532.0>>

	* uni21F6 (U+21F6) contains a short segment L<<293.0,532.0>--<292.0,532.0>>

	* uni21F6 (U+21F6) contains a short segment L<<352.0,583.0>--<356.0,586.0>>

	* uni21F6 (U+21F6) contains a short segment L<<356.0,586.0>--<356.0,586.0>> 

	* partialdiff (U+2202) contains a short segment L<<547.0,242.0>--<547.0,242.0>> [code: found-short-segments]
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

	* uni04C3 (U+04C3): L<<196.0,384.0>--<192.0,384.0>> -> L<<192.0,384.0>--<136.0,384.0>>

	* uni2081 (U+2081): L<<263.0,379.0>--<264.0,379.0>> -> L<<264.0,379.0>--<264.0,379.0>>

	* uni2081 (U+2081): L<<264.0,379.0>--<264.0,379.0>> -> L<<264.0,379.0>--<337.0,379.0>>

	* uni2150 (U+2150): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2150 (U+2150): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni2151 (U+2151): L<<97.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<98.0,850.0>>

	* uni2151 (U+2151): L<<98.0,850.0>--<98.0,850.0>> -> L<<98.0,850.0>--<171.0,850.0>>

	* uni2152 (U+2152): L<<214.0,379.0>--<215.0,379.0>> -> L<<215.0,379.0>--<215.0,379.0>>

	* uni2152 (U+2152): L<<215.0,379.0>--<215.0,379.0>> -> L<<215.0,379.0>--<288.0,379.0>>

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

	* uni21CE (U+21CE): L<<341.0,591.0>--<399.0,591.0>> -> L<<399.0,591.0>--<399.0,591.0>>

	* uni21F6 (U+21F6): L<<292.0,269.0>--<352.0,319.0>> -> L<<352.0,319.0>--<356.0,323.0>>

	* uni21F6 (U+21F6): L<<292.0,532.0>--<352.0,583.0>> -> L<<352.0,583.0>--<356.0,586.0>>

	* uni25C1 (U+25C1): L<<526.0,88.0>--<452.0,132.0>> -> L<<452.0,132.0>--<60.0,370.0>>

	* uni25C3 (U+25C3): L<<436.0,197.0>--<374.0,234.0>> -> L<<374.0,234.0>--<150.0,370.0>>

	* uni25C5 (U+25C5): L<<526.0,177.0>--<455.0,207.0>> -> L<<455.0,207.0>--<49.0,370.0>>

	* uniE0A1 (U+E0A1): L<<295.0,57.0>--<299.0,-34.0>> -> L<<299.0,-34.0>--<299.0,-144.0>> 

	* uniE0A1 (U+E0A1): L<<382.0,117.0>--<377.0,226.0>> -> L<<377.0,226.0>--<377.0,319.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<399.5,400.0>-<375.0,429.0>-<317.0,433.0>>/L<<317.0,433.0>--<317.0,433.0>> = 3.94518622903751 

	* section (U+00A7): L<<317.0,433.0>--<317.0,433.0>>/B<<317.0,433.0>-<262.0,434.0>-<231.5,423.0>> = 1.041626676009815 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<259.0,782.0>--<72.0,783.0>>

	* uni2077 (U+2077): L<<349.0,782.0>--<162.0,783.0>>

	* uni2087 (U+2087): L<<349.0,311.0>--<162.0,312.0>>

	* uni2150 (U+2150): L<<512.0,311.0>--<325.0,312.0>>

	* uni2196 (U+2196): L<<47.0,683.0>--<381.0,682.0>>

	* uni2197 (U+2197): L<<219.0,682.0>--<553.0,683.0>>

	* uni21D6 (U+21D6): L<<27.0,683.0>--<361.0,682.0>>

	* uni21D7 (U+21D7): L<<239.0,682.0>--<573.0,683.0>>

	* uni21D8 (U+21D8): L<<573.0,117.0>--<239.0,118.0>> 

	* uni21D9 (U+21D9): L<<361.0,118.0>--<27.0,117.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] VictorMono-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0132 (LATIN CAPITAL LIGATURE IJ)
 

	- 0x0133 (LATIN SMALL LIGATURE IJ)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 rune bjørnerås (https://github.com/rubjo/victor-mono-font)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Copyright 2023 Rune Bj&#248;rner&#229;s (https://github.com/rubjo/victor-mono-font)'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Rune Bjørnerås (https://github.com/rubjo/victor-mono-font)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1100. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** hhea.lineGap is "200" it should be 0 [code: bad-hhea.lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1306, but got 1100 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 529, but got 250 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni031B

	- uni0326

	- uni0327 

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1416 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni25A9 (U+25A9): L<<403.0,220.0>--<403.0,220.0>> -> L<<403.0,220.0>--<454.0,220.0>>

	* uni25C1 (U+25C1): L<<534.0,74.0>--<448.0,126.0>> -> L<<448.0,126.0>--<46.0,370.0>>

	* uni25C3 (U+25C3): L<<444.0,183.0>--<370.0,228.0>> -> L<<370.0,228.0>--<136.0,370.0>>

	* uni25C5 (U+25C5): L<<534.0,165.0>--<452.0,200.0>> -> L<<452.0,200.0>--<29.0,370.0>>

	* uniE0A1 (U+E0A1): L<<305.0,12.0>--<307.0,-34.0>> -> L<<307.0,-34.0>--<307.0,-151.0>> 

	* uniE0A1 (U+E0A1): L<<372.0,162.0>--<369.0,226.0>> -> L<<369.0,226.0>--<369.0,326.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 168 | 153 | 1682 | 85 | 1135 | 0 |
| 0% | 5% | 5% | 52% | 3% | 35% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
