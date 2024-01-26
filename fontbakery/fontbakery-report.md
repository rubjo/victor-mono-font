## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[15] VictorMono-MediumItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* minus
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060301
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25BF
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C3
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<330.0,730.0>--<371.0,727.0>> -> L<<371.0,727.0>--<405.0,727.0>>

	* oneeighth (U+215B): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* onehalf (U+00BD): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* onequarter (U+00BC): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni00B9 (U+00B9): L<<345.0,776.0>--<378.0,773.0>> -> L<<378.0,773.0>--<411.0,773.0>>

	* uni0409 (U+0409): L<<245.0,730.0>--<286.0,727.0>> -> L<<286.0,727.0>--<450.0,727.0>>

	* uni0426 (U+0426): L<<467.0,85.0>--<467.0,85.0>> -> L<<467.0,85.0>--<467.0,85.0>>

	* uni042B (U+042B): L<<180.0,353.0>--<180.0,353.0>> -> L<<180.0,353.0>--<180.0,353.0>>

	* uni044B (U+044B): L<<168.0,271.0>--<168.0,271.0>> -> L<<168.0,271.0>--<168.0,271.0>>

	* uni0459 (U+0459): L<<210.0,565.0>--<243.0,562.0>> -> L<<243.0,562.0>--<415.0,562.0>>

	* uni046A (U+046A): L<<296.0,406.0>--<294.0,386.0>> -> L<<294.0,386.0>--<294.0,385.0>>

	* uni0490 (U+0490): L<<610.0,853.0>--<584.0,727.0>> -> L<<584.0,727.0>--<571.0,658.0>>

	* uni0491 (U+0491): L<<580.0,688.0>--<554.0,562.0>> -> L<<554.0,562.0>--<539.0,492.0>>

	* uni04A4 (U+04A4): L<<504.0,740.0>--<504.0,740.0>> -> L<<504.0,740.0>--<691.0,740.0>>

	* uni04C3 (U+04C3): L<<198.0,350.0>--<193.0,350.0>> -> L<<193.0,350.0>--<138.0,350.0>>

	* uni04F8 (U+04F8): L<<180.0,353.0>--<180.0,353.0>> -> L<<180.0,353.0>--<180.0,353.0>>

	* uni04F9 (U+04F9): L<<168.0,271.0>--<168.0,271.0>> -> L<<168.0,271.0>--<168.0,271.0>>

	* uni0526 (U+0526): L<<460.0,29.0>--<460.0,29.0>> -> L<<460.0,29.0>--<461.0,29.0>>

	* uni2081 (U+2081): L<<254.0,348.0>--<287.0,345.0>> -> L<<287.0,345.0>--<320.0,345.0>>

	* uni2150 (U+2150): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* uni2151 (U+2151): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* uni2152 (U+2152): L<<210.0,348.0>--<243.0,345.0>> -> L<<243.0,345.0>--<275.0,345.0>>

	* uni2153 (U+2153): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* uni2155 (U+2155): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* uni2159 (U+2159): L<<194.0,776.0>--<227.0,773.0>> -> L<<227.0,773.0>--<260.0,773.0>>

	* uni215F (U+215F): L<<191.0,776.0>--<224.0,773.0>> -> L<<224.0,773.0>--<257.0,773.0>>

	* uni21CA (U+21CA): L<<267.0,251.0>--<267.0,251.0>> -> L<<267.0,251.0>--<268.0,251.0>>

	* uni21CB (U+21CB): L<<32.0,298.0>--<486.0,298.0>> -> L<<486.0,298.0>--<487.0,298.0>>

	* uni21CB (U+21CB): L<<486.0,298.0>--<487.0,298.0>> -> L<<487.0,298.0>--<586.0,298.0>>

	* uni21CC (U+21CC): L<<-34.0,298.0>--<65.0,298.0>> -> L<<65.0,298.0>--<65.0,298.0>>

	* uni21CC (U+21CC): L<<514.0,429.0>--<513.0,429.0>> -> L<<513.0,429.0>--<59.0,429.0>>

	* uni21CC (U+21CC): L<<613.0,429.0>--<514.0,429.0>> -> L<<514.0,429.0>--<513.0,429.0>>

	* uni21CC (U+21CC): L<<65.0,298.0>--<65.0,298.0>> -> L<<65.0,298.0>--<519.0,298.0>>

	* uni21CE (U+21CE): L<<365.0,537.0>--<417.0,537.0>> -> L<<417.0,537.0>--<417.0,537.0>>

	* uni21F3 (U+21F3): L<<138.0,304.0>--<151.0,364.0>> -> L<<151.0,364.0>--<165.0,424.0>>

	* uni21F3 (U+21F3): L<<254.0,493.0>--<227.0,364.0>> -> L<<227.0,364.0>--<199.0,234.0>>

	* uni21F3 (U+21F3): L<<328.0,234.0>--<355.0,364.0>> -> L<<355.0,364.0>--<382.0,493.0>>

	* uni21F3 (U+21F3): L<<444.0,424.0>--<430.0,364.0>> -> L<<430.0,364.0>--<417.0,304.0>>

	* uni25C1 (U+25C1): L<<478.0,80.0>--<411.0,121.0>> -> L<<411.0,121.0>--<56.0,336.0>>

	* uni25C3 (U+25C3): L<<396.0,179.0>--<340.0,213.0>> -> L<<340.0,213.0>--<138.0,336.0>>

	* uni25C5 (U+25C5): L<<478.0,161.0>--<414.0,188.0>> -> L<<414.0,188.0>--<45.0,336.0>>

	* uniE0A1 (U+E0A1): L<<267.0,54.0>--<271.0,-31.0>> -> L<<271.0,-31.0>--<271.0,-130.0>>

	* uniE0A1 (U+E0A1): L<<348.0,104.0>--<343.0,205.0>> -> L<<343.0,205.0>--<343.0,289.0>> 

	* xi (U+03BE): L<<577.0,727.0>--<570.0,694.0>> -> L<<570.0,694.0>--<566.0,659.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* aacute (U+00E1): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* abreve (U+0103): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* acircumflex (U+00E2): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* adieresis (U+00E4): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* agrave (U+00E0): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* amacron (U+0101): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* aogonek (U+0105): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* aring (U+00E5): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* atilde (U+00E3): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* eta (U+03B7): L<<124.0,435.0>--<148.0,452.0>>/L<<148.0,452.0>--<126.0,438.0>> = 2.8400211487847256

	* etatonos (U+03AE): L<<124.0,435.0>--<148.0,452.0>>/L<<148.0,452.0>--<126.0,438.0>> = 2.8400211487847256

	* section (U+00A7): B<<383.0,366.5>-<367.0,391.0>-<315.0,394.0>>/L<<315.0,394.0>--<315.0,394.0>> = 3.301865674434948

	* section (U+00A7): L<<315.0,394.0>--<315.0,394.0>>/B<<315.0,394.0>-<266.0,395.0>-<235.0,384.0>> = 1.169139327907133

	* uni01CE (U+01CE): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni0411 (U+0411): B<<80.0,128.0>-<80.0,120.0>-<80.0,114.0>>/B<<80.0,114.0>-<88.0,147.0>-<100.5,197.0>> = 13.62699485989153

	* uni0412 (U+0412): B<<98.0,242.0>-<91.0,204.0>-<87.0,172.0>>/B<<87.0,172.0>-<92.0,203.0>-<99.0,240.5>> = 2.0373306968196756

	* uni0412 (U+0412): B<<99.0,240.5>-<106.0,278.0>-<115.0,320.0>>/B<<115.0,320.0>-<105.0,280.0>-<98.0,242.0>> = 1.9414863909143467

	* uni041C (U+041C): B<<154.0,151.0>-<152.0,239.0>-<153.0,391.0>>/B<<153.0,391.0>-<129.0,264.0>-<112.0,185.0>> = 10.324410244302001

	* uni041C (U+041C): B<<384.5,171.0>-<407.0,267.0>-<444.0,424.0>>/B<<444.0,424.0>-<415.0,356.0>-<392.5,302.5>> = 9.835962713975968

	* uni0430 (U+0430): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni043C (U+043C): B<<368.0,109.0>-<379.0,163.0>-<400.0,257.0>>/B<<400.0,257.0>-<364.0,179.0>-<331.5,118.0>> = 12.181810612728775

	* uni0495 (U+0495): B<<168.0,218.0>-<134.0,186.0>-<117.0,104.0>>/L<<117.0,104.0>--<131.0,173.0>> = 0.24294197822102134

	* uni0495 (U+0495): L<<117.0,104.0>--<131.0,173.0>>/L<<131.0,173.0>--<94.0,0.0>> = 0.6026070139694377

	* uni04CD (U+04CD): B<<127.0,151.0>-<125.0,239.0>-<126.0,391.0>>/B<<126.0,391.0>-<102.0,264.0>-<85.0,185.0>> = 10.324410244302001

	* uni04CD (U+04CD): B<<363.0,196.0>-<385.0,287.0>-<417.0,424.0>>/B<<417.0,424.0>-<388.0,356.0>-<365.5,302.5>> = 9.94957954289133

	* uni04CE (U+04CE): B<<371.0,125.0>-<382.0,176.0>-<400.0,257.0>>/B<<400.0,257.0>-<364.0,179.0>-<331.5,118.0>> = 12.246332859680393

	* uni04D1 (U+04D1): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni04D3 (U+04D3): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EA1 (U+1EA1): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EA3 (U+1EA3): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EA5 (U+1EA5): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EA7 (U+1EA7): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EA9 (U+1EA9): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EAB (U+1EAB): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EAD (U+1EAD): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EAF (U+1EAF): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EB1 (U+1EB1): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EB3 (U+1EB3): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497

	* uni1EB5 (U+1EB5): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497 

	* uni1EB7 (U+1EB7): B<<316.0,56.0>-<316.0,62.0>-<318.0,65.0>>/B<<318.0,65.0>-<291.0,29.0>-<254.5,8.0>> = 3.1798301198640497 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] VictorMono-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* minus
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060301
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25BF
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C3
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* oneeighth (U+215B): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* onehalf (U+00BD): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* onehalf (U+00BD): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* onequarter (U+00BC): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* onequarter (U+00BC): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* uni00B9 (U+00B9): L<<239.0,773.0>--<240.0,773.0>> -> L<<240.0,773.0>--<240.0,773.0>>

	* uni00B9 (U+00B9): L<<240.0,773.0>--<240.0,773.0>> -> L<<240.0,773.0>--<306.0,773.0>>

	* uni04C3 (U+04C3): L<<179.0,350.0>--<175.0,350.0>> -> L<<175.0,350.0>--<124.0,350.0>>

	* uni2081 (U+2081): L<<239.0,345.0>--<240.0,345.0>> -> L<<240.0,345.0>--<240.0,345.0>>

	* uni2081 (U+2081): L<<240.0,345.0>--<240.0,345.0>> -> L<<240.0,345.0>--<306.0,345.0>>

	* uni2150 (U+2150): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* uni2150 (U+2150): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* uni2151 (U+2151): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* uni2151 (U+2151): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* uni2152 (U+2152): L<<195.0,345.0>--<196.0,345.0>> -> L<<196.0,345.0>--<196.0,345.0>>

	* uni2152 (U+2152): L<<196.0,345.0>--<196.0,345.0>> -> L<<196.0,345.0>--<262.0,345.0>>

	* uni2152 (U+2152): L<<73.0,772.0>--<74.0,772.0>> -> L<<74.0,772.0>--<74.0,772.0>>

	* uni2152 (U+2152): L<<74.0,772.0>--<74.0,772.0>> -> L<<74.0,772.0>--<140.0,772.0>>

	* uni2153 (U+2153): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* uni2153 (U+2153): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* uni2155 (U+2155): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* uni2155 (U+2155): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* uni2159 (U+2159): L<<88.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<89.0,773.0>>

	* uni2159 (U+2159): L<<89.0,773.0>--<89.0,773.0>> -> L<<89.0,773.0>--<155.0,773.0>>

	* uni215F (U+215F): L<<85.0,773.0>--<86.0,773.0>> -> L<<86.0,773.0>--<86.0,773.0>>

	* uni215F (U+215F): L<<86.0,773.0>--<86.0,773.0>> -> L<<86.0,773.0>--<152.0,773.0>>

	* uni21CA (U+21CA): L<<272.0,251.0>--<273.0,251.0>> -> L<<273.0,251.0>--<273.0,251.0>>

	* uni21CB (U+21CB): L<<-1.0,298.0>--<454.0,298.0>> -> L<<454.0,298.0>--<454.0,298.0>>

	* uni21CB (U+21CB): L<<454.0,298.0>--<454.0,298.0>> -> L<<454.0,298.0>--<554.0,298.0>>

	* uni21CC (U+21CC): L<<-9.0,298.0>--<91.0,298.0>> -> L<<91.0,298.0>--<91.0,298.0>>

	* uni21CC (U+21CC): L<<91.0,298.0>--<91.0,298.0>> -> L<<91.0,298.0>--<546.0,298.0>>

	* uni21CE (U+21CE): L<<310.0,537.0>--<363.0,537.0>> -> L<<363.0,537.0>--<363.0,537.0>>

	* uni25C1 (U+25C1): L<<478.0,80.0>--<411.0,121.0>> -> L<<411.0,121.0>--<56.0,336.0>>

	* uni25C3 (U+25C3): L<<396.0,179.0>--<340.0,213.0>> -> L<<340.0,213.0>--<138.0,336.0>>

	* uni25C5 (U+25C5): L<<478.0,161.0>--<414.0,188.0>> -> L<<414.0,188.0>--<45.0,336.0>>

	* uniE0A1 (U+E0A1): L<<267.0,54.0>--<271.0,-31.0>> -> L<<271.0,-31.0>--<271.0,-130.0>> 

	* uniE0A1 (U+E0A1): L<<348.0,104.0>--<343.0,205.0>> -> L<<343.0,205.0>--<343.0,289.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<363.0,364.0>-<340.0,391.0>-<288.0,394.0>>/L<<288.0,394.0>--<288.0,394.0>> = 3.301865674434948

	* section (U+00A7): L<<258.0,96.0>--<258.0,96.0>>/B<<258.0,96.0>-<168.0,100.0>-<126.0,146.0>> = 2.5448043798130455 

	* section (U+00A7): L<<288.0,394.0>--<288.0,394.0>>/B<<288.0,394.0>-<238.0,395.0>-<210.0,385.0>> = 1.1457628381748262 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] VictorMono-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* h
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2078
	* uni2079
	* uni207A
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2088
	* uni2089
	* uni208A
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* oneeighth (U+215B): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* onehalf (U+00BD): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* onehalf (U+00BD): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* onequarter (U+00BC): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* onequarter (U+00BC): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* rho (U+03C1): L<<70.0,281.0>--<70.0,281.0>> -> L<<70.0,281.0>--<70.0,281.0>>

	* uni00B9 (U+00B9): L<<245.0,772.0>--<246.0,772.0>> -> L<<246.0,772.0>--<246.0,772.0>>

	* uni00B9 (U+00B9): L<<246.0,772.0>--<246.0,772.0>> -> L<<246.0,772.0>--<301.0,772.0>>

	* uni04C3 (U+04C3): L<<193.0,357.0>--<191.0,357.0>> -> L<<191.0,357.0>--<125.0,357.0>>

	* uni2081 (U+2081): L<<245.0,342.0>--<246.0,342.0>> -> L<<246.0,342.0>--<246.0,342.0>>

	* uni2081 (U+2081): L<<246.0,342.0>--<246.0,342.0>> -> L<<246.0,342.0>--<301.0,342.0>>

	* uni2150 (U+2150): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* uni2150 (U+2150): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* uni2151 (U+2151): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* uni2151 (U+2151): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* uni2152 (U+2152): L<<207.0,342.0>--<208.0,342.0>> -> L<<208.0,342.0>--<208.0,342.0>>

	* uni2152 (U+2152): L<<208.0,342.0>--<208.0,342.0>> -> L<<208.0,342.0>--<263.0,342.0>>

	* uni2152 (U+2152): L<<74.0,773.0>--<75.0,773.0>> -> L<<75.0,773.0>--<75.0,773.0>>

	* uni2152 (U+2152): L<<75.0,773.0>--<75.0,773.0>> -> L<<75.0,773.0>--<130.0,773.0>>

	* uni2153 (U+2153): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* uni2153 (U+2153): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* uni2155 (U+2155): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* uni2155 (U+2155): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* uni2159 (U+2159): L<<94.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<95.0,772.0>>

	* uni2159 (U+2159): L<<95.0,772.0>--<95.0,772.0>> -> L<<95.0,772.0>--<150.0,772.0>>

	* uni215F (U+215F): L<<93.0,772.0>--<94.0,772.0>> -> L<<94.0,772.0>--<94.0,772.0>>

	* uni215F (U+215F): L<<94.0,772.0>--<94.0,772.0>> -> L<<94.0,772.0>--<149.0,772.0>>

	* uni21B4 (U+21B4): L<<10.0,727.0>--<415.0,727.0>> -> L<<415.0,727.0>--<415.0,727.0>>

	* uni21B4 (U+21B4): L<<415.0,727.0>--<415.0,727.0>> -> L<<415.0,727.0>--<421.0,727.0>>

	* uni25C1 (U+25C1): L<<470.0,94.0>--<415.0,127.0>> -> L<<415.0,127.0>--<70.0,336.0>>

	* uni25C3 (U+25C3): L<<388.0,193.0>--<344.0,219.0>> -> L<<344.0,219.0>--<152.0,336.0>>

	* uni25C5 (U+25C5): L<<470.0,172.0>--<416.0,195.0>> -> L<<416.0,195.0>--<65.0,336.0>>

	* uniE0A1 (U+E0A1): L<<257.0,97.0>--<263.0,-32.0>> -> L<<263.0,-32.0>--<263.0,-123.0>> 

	* uniE0A1 (U+E0A1): L<<358.0,61.0>--<351.0,206.0>> -> L<<351.0,206.0>--<351.0,282.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): L<<266.0,102.0>--<266.0,102.0>>/B<<266.0,102.0>-<171.0,104.0>-<131.5,150.0>> = 1.2060487792199448 

	* section (U+00A7): L<<280.0,402.0>--<280.0,402.0>>/B<<280.0,402.0>-<231.0,403.0>-<203.0,391.0>> = 1.169139327907133 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<243.0,720.0>--<71.0,721.0>>

	* uni2077 (U+2077): L<<325.0,720.0>--<153.0,721.0>>

	* uni2087 (U+2087): L<<325.0,290.0>--<153.0,291.0>> 

	* uni2150 (U+2150): L<<478.0,290.0>--<306.0,291.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] VictorMono-ExtraLightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon_semicolon.liga
	* seven
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2078
	* uni2079
	* uni207A
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2088
	* uni2089
	* uni208A
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B6
	* uni25B7
	* uni25BB
	* uni25BD
	* uni25C0
	* uni25C1
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE08
	* uniEE09
	* uniEE0A
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
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
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Q (U+0051): L<<272.0,42.0>--<272.0,42.0>> -> L<<272.0,42.0>--<272.0,42.0>>

	* one (U+0031): L<<341.0,729.0>--<368.0,727.0>> -> L<<368.0,727.0>--<394.0,727.0>>

	* oneeighth (U+215B): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* onehalf (U+00BD): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* onequarter (U+00BC): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* section (U+00A7): L<<305.0,457.0>--<305.0,457.0>> -> L<<305.0,457.0>--<311.0,457.0>>

	* section (U+00A7): L<<305.0,457.0>--<311.0,457.0>> -> L<<311.0,457.0>--<311.0,457.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni00B9 (U+00B9): L<<353.0,775.0>--<374.0,773.0>> -> L<<374.0,773.0>--<404.0,773.0>>

	* uni0409 (U+0409): L<<245.0,729.0>--<272.0,727.0>> -> L<<272.0,727.0>--<429.0,727.0>>

	* uni0459 (U+0459): L<<210.0,564.0>--<235.0,562.0>> -> L<<235.0,562.0>--<394.0,562.0>>

	* uni0490 (U+0490): L<<599.0,844.0>--<576.0,727.0>> -> L<<576.0,727.0>--<566.0,678.0>>

	* uni0491 (U+0491): L<<567.0,678.0>--<543.0,562.0>> -> L<<543.0,562.0>--<532.0,513.0>>

	* uni049B (U+049B): L<<497.0,18.0>--<497.0,18.0>> -> L<<497.0,18.0>--<497.0,18.0>>

	* uni04A4 (U+04A4): L<<512.0,740.0>--<512.0,740.0>> -> L<<512.0,740.0>--<689.0,740.0>>

	* uni04B0 (U+04B0): L<<111.0,278.0>--<247.0,278.0>> -> L<<247.0,278.0>--<247.0,278.0>>

	* uni04B0 (U+04B0): L<<299.0,278.0>--<299.0,278.0>> -> L<<299.0,278.0>--<435.0,278.0>>

	* uni04C3 (U+04C3): L<<218.0,361.0>--<217.0,361.0>> -> L<<217.0,361.0>--<143.0,361.0>>

	* uni2081 (U+2081): L<<261.0,343.0>--<282.0,341.0>> -> L<<282.0,341.0>--<312.0,341.0>>

	* uni2150 (U+2150): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* uni2151 (U+2151): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* uni2152 (U+2152): L<<179.0,775.0>--<200.0,773.0>> -> L<<200.0,773.0>--<230.0,773.0>>

	* uni2152 (U+2152): L<<227.0,343.0>--<248.0,341.0>> -> L<<248.0,341.0>--<277.0,341.0>>

	* uni2153 (U+2153): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* uni2155 (U+2155): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* uni2159 (U+2159): L<<202.0,775.0>--<223.0,773.0>> -> L<<223.0,773.0>--<253.0,773.0>>

	* uni215F (U+215F): L<<201.0,775.0>--<222.0,773.0>> -> L<<222.0,773.0>--<252.0,773.0>>

	* uni21B4 (U+21B4): L<<498.0,727.0>--<498.0,727.0>> -> L<<498.0,727.0>--<504.0,727.0>>

	* uni21B4 (U+21B4): L<<94.0,727.0>--<498.0,727.0>> -> L<<498.0,727.0>--<498.0,727.0>>

	* uni21C8 (U+21C8): L<<318.0,496.0>--<304.0,519.0>> -> L<<304.0,519.0>--<246.0,616.0>>

	* uni21CA (U+21CA): L<<139.0,111.0>--<239.0,208.0>> -> L<<239.0,208.0>--<263.0,231.0>>

	* uni21CA (U+21CA): L<<263.0,231.0>--<263.0,231.0>> -> L<<263.0,231.0>--<263.0,231.0>>

	* uni21CB (U+21CB): L<<39.0,296.0>--<502.0,296.0>> -> L<<502.0,296.0>--<503.0,296.0>>

	* uni21CB (U+21CB): L<<502.0,296.0>--<503.0,296.0>> -> L<<503.0,296.0>--<572.0,296.0>>

	* uni21CB (U+21CB): L<<542.0,431.0>--<78.0,431.0>> -> L<<78.0,431.0>--<77.0,431.0>>

	* uni21CB (U+21CB): L<<78.0,431.0>--<77.0,431.0>> -> L<<77.0,431.0>--<9.0,431.0>>

	* uni21CC (U+21CC): L<<-21.0,296.0>--<48.0,296.0>> -> L<<48.0,296.0>--<49.0,296.0>>

	* uni21CC (U+21CC): L<<48.0,296.0>--<49.0,296.0>> -> L<<49.0,296.0>--<512.0,296.0>>

	* uni21CC (U+21CC): L<<531.0,431.0>--<530.0,431.0>> -> L<<530.0,431.0>--<67.0,431.0>>

	* uni21CC (U+21CC): L<<599.0,431.0>--<531.0,431.0>> -> L<<531.0,431.0>--<530.0,431.0>>

	* uni21F3 (U+21F3): L<<146.0,289.0>--<162.0,364.0>> -> L<<162.0,364.0>--<179.0,439.0>>

	* uni21F3 (U+21F3): L<<241.0,487.0>--<216.0,364.0>> -> L<<216.0,364.0>--<189.0,240.0>>

	* uni21F3 (U+21F3): L<<341.0,240.0>--<366.0,364.0>> -> L<<366.0,364.0>--<392.0,487.0>>

	* uni21F3 (U+21F3): L<<436.0,439.0>--<419.0,364.0>> -> L<<419.0,364.0>--<403.0,289.0>>

	* uni25C1 (U+25C1): L<<467.0,100.0>--<417.0,130.0>> -> L<<417.0,130.0>--<76.0,336.0>>

	* uni25C3 (U+25C3): L<<385.0,199.0>--<346.0,222.0>> -> L<<346.0,222.0>--<158.0,336.0>>

	* uni25C5 (U+25C5): L<<467.0,178.0>--<418.0,198.0>> -> L<<418.0,198.0>--<74.0,336.0>>

	* uniE0A1 (U+E0A1): L<<253.0,118.0>--<260.0,-32.0>> -> L<<260.0,-32.0>--<260.0,-119.0>>

	* uniE0A1 (U+E0A1): L<<362.0,40.0>--<354.0,206.0>> -> L<<354.0,206.0>--<354.0,278.0>> 

	* xi (U+03BE): L<<556.0,678.0>--<556.0,678.0>> -> L<<556.0,678.0>--<556.0,678.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* aacute (U+00E1): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* abreve (U+0103): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* acircumflex (U+00E2): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* adieresis (U+00E4): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* agrave (U+00E0): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* alpha (U+03B1): B<<416.5,461.0>-<421.0,410.0>-<416.0,351.0>>/B<<416.0,351.0>-<444.0,441.0>-<474.0,564.0>> = 12.437497996735985

	* alphatonos (U+03AC): B<<416.5,461.0>-<421.0,410.0>-<416.0,351.0>>/B<<416.0,351.0>-<444.0,441.0>-<474.0,564.0>> = 12.437497996735985

	* amacron (U+0101): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* aogonek (U+0105): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* aring (U+00E5): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* atilde (U+00E3): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* eta (U+03B7): L<<140.0,455.0>--<156.0,468.0>>/L<<156.0,468.0>--<141.0,458.0>> = 5.40379136024966

	* etatonos (U+03AE): L<<140.0,455.0>--<156.0,468.0>>/L<<156.0,468.0>--<141.0,458.0>> = 5.40379136024966

	* section (U+00A7): L<<234.0,105.0>--<234.0,105.0>>/B<<234.0,105.0>-<170.0,106.0>-<136.0,128.0>> = 0.8951737102109718

	* section (U+00A7): L<<305.0,406.0>--<305.0,406.0>>/B<<305.0,406.0>-<232.0,407.0>-<197.0,376.0>> = 0.7848246029917126

	* uni01CE (U+01CE): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni041C (U+041C): B<<156.5,243.5>-<157.0,338.0>-<160.0,478.0>>/B<<160.0,478.0>-<123.0,305.0>-<97.0,196.5>> = 10.844558514701301

	* uni041C (U+041C): B<<410.5,207.0>-<435.0,323.0>-<476.0,514.0>>/B<<476.0,514.0>-<431.0,411.0>-<399.0,333.0>> = 11.484948065459864

	* uni0430 (U+0430): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni0436 (U+0436): L<<186.0,0.0>--<272.0,400.0>>/L<<272.0,400.0>--<177.0,209.0>> = 14.311054244234684

	* uni0436 (U+0436): L<<352.0,562.0>--<266.0,162.0>>/L<<266.0,162.0>--<362.0,357.0>> = 14.077497847198194

	* uni043C (U+043C): B<<137.0,164.0>-<131.0,229.0>-<128.0,332.0>>/B<<128.0,332.0>-<105.0,223.0>-<89.5,154.5>> = 13.583484519558297

	* uni043C (U+043C): B<<399.0,178.5>-<413.0,244.0>-<435.0,345.0>>/B<<435.0,345.0>-<390.0,247.0>-<350.0,165.5>> = 12.375491549188196

	* uni0443 (U+0443): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni045E (U+045E): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni0495 (U+0495): B<<139.0,208.0>-<120.0,174.0>-<108.0,116.0>>/L<<108.0,116.0>--<133.0,237.0>> = 0.015658862561084688

	* uni0495 (U+0495): L<<108.0,116.0>--<133.0,237.0>>/L<<133.0,237.0>--<83.0,0.0>> = 0.23931335551673033

	* uni0497 (U+0497): L<<186.0,0.0>--<272.0,400.0>>/L<<272.0,400.0>--<177.0,209.0>> = 14.311054244234684

	* uni0497 (U+0497): L<<352.0,562.0>--<266.0,162.0>>/L<<266.0,162.0>--<362.0,357.0>> = 14.077497847198194

	* uni04A6 (U+04A6): B<<333.0,364.5>-<302.0,331.0>-<283.0,243.0>>/L<<283.0,243.0>--<292.0,285.0>> = 0.08889950897404644

	* uni04A6 (U+04A6): L<<283.0,243.0>--<292.0,285.0>>/L<<292.0,285.0>--<231.0,0.0>> = 0.013730117029914043

	* uni04A6 (U+04A6): L<<386.0,727.0>--<312.0,380.0>>/B<<312.0,380.0>-<330.0,419.0>-<354.5,433.0>> = 12.736776957382107

	* uni04C2 (U+04C2): L<<186.0,0.0>--<272.0,400.0>>/L<<272.0,400.0>--<177.0,209.0>> = 14.311054244234684

	* uni04C2 (U+04C2): L<<352.0,562.0>--<266.0,162.0>>/L<<266.0,162.0>--<362.0,357.0>> = 14.077497847198194

	* uni04CD (U+04CD): B<<143.5,243.5>-<144.0,338.0>-<146.0,478.0>>/B<<146.0,478.0>-<109.0,305.0>-<83.5,196.5>> = 11.25368188514726

	* uni04CD (U+04CD): B<<400.0,223.5>-<424.0,336.0>-<462.0,514.0>>/B<<462.0,514.0>-<418.0,411.0>-<385.5,333.0>> = 11.080635931217921

	* uni04CE (U+04CE): B<<137.0,164.0>-<131.0,229.0>-<128.0,332.0>>/B<<128.0,332.0>-<105.0,223.0>-<89.5,154.5>> = 13.583484519558297

	* uni04CE (U+04CE): B<<395.0,157.5>-<410.0,228.0>-<435.0,345.0>>/B<<435.0,345.0>-<390.0,247.0>-<350.0,165.5>> = 12.602505255419027

	* uni04D1 (U+04D1): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni04D3 (U+04D3): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni04DD (U+04DD): L<<186.0,0.0>--<272.0,400.0>>/L<<272.0,400.0>--<177.0,209.0>> = 14.311054244234684

	* uni04DD (U+04DD): L<<352.0,562.0>--<266.0,162.0>>/L<<266.0,162.0>--<362.0,357.0>> = 14.077497847198194

	* uni04EF (U+04EF): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni04F1 (U+04F1): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni04F3 (U+04F3): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni1EA1 (U+1EA1): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EA3 (U+1EA3): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EA5 (U+1EA5): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EA7 (U+1EA7): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EA9 (U+1EA9): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EAB (U+1EAB): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EAD (U+1EAD): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EAF (U+1EAF): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EB1 (U+1EB1): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EB3 (U+1EB3): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EB5 (U+1EB5): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EB7 (U+1EB7): B<<326.0,41.0>-<326.0,74.0>-<332.0,94.0>>/B<<332.0,94.0>-<307.0,46.0>-<265.5,16.5>> = 10.812758389857821

	* uni1EF5 (U+1EF5): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni1EF7 (U+1EF7): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* uni1EF9 (U+1EF9): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* xi (U+03BE): L<<556.0,678.0>--<556.0,678.0>>/B<<556.0,678.0>-<443.0,657.0>-<376.0,636.5>> = 10.527786119963531

	* y (U+0079): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* yacute (U+00FD): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* ycircumflex (U+0177): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517

	* ydieresis (U+00FF): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517 

	* ygrave (U+1EF3): B<<361.5,41.5>-<371.0,73.0>-<375.0,91.0>>/B<<375.0,91.0>-<366.0,72.0>-<343.0,61.5>> = 12.81736823279517 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] VictorMono-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* minus
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060301
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* rho (U+03C1): L<<66.0,281.0>--<66.0,281.0>> -> L<<66.0,281.0>--<66.0,281.0>>

	* uni04B0 (U+04B0): L<<115.0,273.0>--<239.0,273.0>> -> L<<239.0,273.0>--<239.0,273.0>>

	* uni04B0 (U+04B0): L<<307.0,273.0>--<307.0,273.0>> -> L<<307.0,273.0>--<432.0,273.0>>

	* uni04C3 (U+04C3): L<<186.0,354.0>--<183.0,354.0>> -> L<<183.0,354.0>--<125.0,354.0>>

	* uni21BD (U+21BD): L<<-2.0,443.0>--<88.0,443.0>> -> L<<88.0,443.0>--<88.0,443.0>>

	* uni21BD (U+21BD): L<<88.0,443.0>--<88.0,443.0>> -> L<<88.0,443.0>--<546.0,443.0>>

	* uni21C1 (U+21C1): L<<-1.0,443.0>--<457.0,443.0>> -> L<<457.0,443.0>--<458.0,443.0>>

	* uni21C1 (U+21C1): L<<457.0,443.0>--<458.0,443.0>> -> L<<458.0,443.0>--<548.0,443.0>>

	* uni21CC (U+21CC): L<<458.0,430.0>--<457.0,430.0>> -> L<<457.0,430.0>--<-1.0,430.0>>

	* uni21CC (U+21CC): L<<548.0,430.0>--<458.0,430.0>> -> L<<458.0,430.0>--<457.0,430.0>>

	* uni25C1 (U+25C1): L<<474.0,87.0>--<413.0,124.0>> -> L<<413.0,124.0>--<63.0,336.0>>

	* uni25C3 (U+25C3): L<<393.0,186.0>--<342.0,216.0>> -> L<<342.0,216.0>--<145.0,336.0>>

	* uni25C5 (U+25C5): L<<474.0,167.0>--<415.0,192.0>> -> L<<415.0,192.0>--<55.0,336.0>>

	* uniE0A1 (U+E0A1): L<<263.0,75.0>--<268.0,-31.0>> -> L<<268.0,-31.0>--<268.0,-126.0>>

	* uniE0A1 (U+E0A1): L<<353.0,84.0>--<347.0,206.0>> -> L<<347.0,206.0>--<347.0,286.0>> 

	* yen (U+00A5): L<<307.0,275.0>--<307.0,273.0>> -> L<<307.0,273.0>--<307.0,212.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<366.0,366.5>-<342.0,395.0>-<284.0,398.0>>/L<<284.0,398.0>--<284.0,398.0>> = 2.9609361341637563

	* section (U+00A7): L<<262.0,99.0>--<262.0,99.0>>/B<<262.0,99.0>-<169.0,102.0>-<128.5,148.0>> = 1.8476102659945155 

	* section (U+00A7): L<<284.0,398.0>--<284.0,398.0>>/B<<284.0,398.0>-<235.0,399.0>-<207.0,388.0>> = 1.169139327907133 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] VictorMono-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* hbar
	* hcircumflex
	* hungarumlaut
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* minus
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060300.case
	* uni03060301
	* uni03060301.case
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2508
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25BF
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C3
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE06
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* oneeighth (U+215B): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* onehalf (U+00BD): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* onehalf (U+00BD): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* onequarter (U+00BC): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* onequarter (U+00BC): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* uni00B9 (U+00B9): L<<237.0,772.0>--<238.0,772.0>> -> L<<238.0,772.0>--<238.0,772.0>>

	* uni00B9 (U+00B9): L<<238.0,772.0>--<238.0,772.0>> -> L<<238.0,772.0>--<309.0,772.0>>

	* uni04C3 (U+04C3): L<<172.0,346.0>--<167.0,346.0>> -> L<<167.0,346.0>--<123.0,346.0>>

	* uni2081 (U+2081): L<<237.0,346.0>--<238.0,346.0>> -> L<<238.0,346.0>--<238.0,346.0>>

	* uni2081 (U+2081): L<<238.0,346.0>--<238.0,346.0>> -> L<<238.0,346.0>--<309.0,346.0>>

	* uni2150 (U+2150): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* uni2150 (U+2150): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* uni2151 (U+2151): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* uni2151 (U+2151): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* uni2152 (U+2152): L<<189.0,346.0>--<190.0,346.0>> -> L<<190.0,346.0>--<190.0,346.0>>

	* uni2152 (U+2152): L<<190.0,346.0>--<190.0,346.0>> -> L<<190.0,346.0>--<261.0,346.0>>

	* uni2152 (U+2152): L<<73.0,772.0>--<74.0,772.0>> -> L<<74.0,772.0>--<74.0,772.0>>

	* uni2152 (U+2152): L<<74.0,772.0>--<74.0,772.0>> -> L<<74.0,772.0>--<145.0,772.0>>

	* uni2153 (U+2153): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* uni2153 (U+2153): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* uni2155 (U+2155): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* uni2155 (U+2155): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* uni2159 (U+2159): L<<86.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<87.0,772.0>>

	* uni2159 (U+2159): L<<87.0,772.0>--<87.0,772.0>> -> L<<87.0,772.0>--<158.0,772.0>>

	* uni215F (U+215F): L<<83.0,772.0>--<84.0,772.0>> -> L<<84.0,772.0>--<84.0,772.0>>

	* uni215F (U+215F): L<<84.0,772.0>--<84.0,772.0>> -> L<<84.0,772.0>--<155.0,772.0>>

	* uni21BD (U+21BD): L<<-17.0,450.0>--<94.0,450.0>> -> L<<94.0,450.0>--<94.0,450.0>>

	* uni21BD (U+21BD): L<<94.0,450.0>--<94.0,450.0>> -> L<<94.0,450.0>--<546.0,450.0>>

	* uni21C1 (U+21C1): L<<-1.0,450.0>--<451.0,450.0>> -> L<<451.0,450.0>--<451.0,450.0>>

	* uni21C1 (U+21C1): L<<451.0,450.0>--<451.0,450.0>> -> L<<451.0,450.0>--<562.0,450.0>>

	* uni21D6 (U+21D6): L<<198.0,620.0>--<199.0,620.0>> -> L<<199.0,620.0>--<199.0,620.0>>

	* uni21D6 (U+21D6): L<<199.0,620.0>--<199.0,620.0>> -> L<<199.0,620.0>--<331.0,620.0>>

	* uni21D6 (U+21D6): L<<24.0,620.0>--<198.0,620.0>> -> L<<198.0,620.0>--<199.0,620.0>>

	* uni21D7 (U+21D7): L<<214.0,620.0>--<346.0,620.0>> -> L<<346.0,620.0>--<346.0,620.0>>

	* uni21D7 (U+21D7): L<<346.0,620.0>--<346.0,620.0>> -> L<<346.0,620.0>--<347.0,620.0>>

	* uni21D7 (U+21D7): L<<346.0,620.0>--<347.0,620.0>> -> L<<347.0,620.0>--<521.0,620.0>>

	* uni21D8 (U+21D8): L<<521.0,107.0>--<347.0,107.0>> -> L<<347.0,107.0>--<346.0,107.0>>

	* uni21D9 (U+21D9): L<<199.0,107.0>--<198.0,107.0>> -> L<<198.0,107.0>--<24.0,107.0>>

	* uni25C1 (U+25C1): L<<481.0,73.0>--<409.0,118.0>> -> L<<409.0,118.0>--<49.0,336.0>>

	* uni25C3 (U+25C3): L<<400.0,172.0>--<338.0,210.0>> -> L<<338.0,210.0>--<131.0,336.0>>

	* uni25C5 (U+25C5): L<<481.0,155.0>--<412.0,185.0>> -> L<<412.0,185.0>--<35.0,336.0>>

	* uniE0A1 (U+E0A1): L<<272.0,31.0>--<275.0,-31.0>> -> L<<275.0,-31.0>--<275.0,-134.0>> 

	* uniE0A1 (U+E0A1): L<<343.0,127.0>--<339.0,205.0>> -> L<<339.0,205.0>--<339.0,293.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* section (U+00A7): B<<283.0,93.0>-<269.0,92.0>-<254.0,93.0>>/L<<254.0,93.0>--<254.0,93.0>> = 3.8140748342903783

	* section (U+00A7): B<<360.5,360.5>-<339.0,385.0>-<291.0,389.0>>/L<<291.0,389.0>--<291.0,389.0>> = 4.763641690726143

	* section (U+00A7): L<<254.0,93.0>--<254.0,93.0>>/B<<254.0,93.0>-<166.0,98.0>-<123.0,144.0>> = 3.251945600363818 

	* section (U+00A7): L<<291.0,389.0>--<291.0,389.0>>/B<<291.0,389.0>-<242.0,391.0>-<214.0,382.0>> = 2.3373058591238247 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<232.0,705.0>--<63.0,706.0>>

	* uni2077 (U+2077): L<<314.0,705.0>--<145.0,706.0>>

	* uni2087 (U+2087): L<<314.0,279.0>--<145.0,280.0>> 

	* uni2150 (U+2150): L<<460.0,279.0>--<291.0,280.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] VictorMono-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresis
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* endash
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* hbar
	* hcircumflex
	* hungarumlaut
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* minus
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060300.case
	* uni03060301
	* uni03060301.case
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni0308
	* uni030A
	* uni030A.case
	* uni030B
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0491
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2508
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25BF
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C3
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE06
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni21C4 (U+21C4): L<<484.0,600.0>--<484.0,600.0>> -> L<<484.0,600.0>--<484.0,600.0>>

	* uni21C4 (U+21C4): L<<61.0,218.0>--<61.0,218.0>> -> L<<61.0,218.0>--<61.0,218.0>>

	* uni21C5 (U+21C5): L<<100.0,675.0>--<100.0,675.0>> -> L<<100.0,675.0>--<100.0,675.0>>

	* uni21C5 (U+21C5): L<<354.0,52.0>--<354.0,52.0>> -> L<<354.0,52.0>--<354.0,52.0>>

	* uni21C6 (U+21C6): L<<484.0,127.0>--<484.0,127.0>> -> L<<484.0,127.0>--<484.0,127.0>>

	* uni21C6 (U+21C6): L<<61.0,509.0>--<61.0,509.0>> -> L<<61.0,509.0>--<61.0,509.0>>

	* uni21C7 (U+21C7): L<<61.0,218.0>--<61.0,218.0>> -> L<<61.0,218.0>--<61.0,218.0>>

	* uni21C7 (U+21C7): L<<61.0,600.0>--<61.0,600.0>> -> L<<61.0,600.0>--<61.0,600.0>>

	* uni21C8 (U+21C8): L<<111.0,675.0>--<111.0,675.0>> -> L<<111.0,675.0>--<111.0,675.0>>

	* uni21C8 (U+21C8): L<<343.0,675.0>--<343.0,675.0>> -> L<<343.0,675.0>--<343.0,675.0>>

	* uni21C9 (U+21C9): L<<484.0,218.0>--<484.0,218.0>> -> L<<484.0,218.0>--<484.0,218.0>>

	* uni21C9 (U+21C9): L<<484.0,600.0>--<484.0,600.0>> -> L<<484.0,600.0>--<484.0,600.0>>

	* uni21CA (U+21CA): L<<111.0,52.0>--<111.0,52.0>> -> L<<111.0,52.0>--<111.0,52.0>>

	* uni21CA (U+21CA): L<<343.0,52.0>--<343.0,52.0>> -> L<<343.0,52.0>--<343.0,52.0>>

	* uni21F5 (U+21F5): L<<100.0,52.0>--<100.0,52.0>> -> L<<100.0,52.0>--<100.0,52.0>>

	* uni21F5 (U+21F5): L<<354.0,675.0>--<354.0,675.0>> -> L<<354.0,675.0>--<354.0,675.0>>

	* uni21F6 (U+21F6): L<<466.0,176.0>--<466.0,176.0>> -> L<<466.0,176.0>--<466.0,176.0>>

	* uni21F6 (U+21F6): L<<466.0,409.0>--<466.0,409.0>> -> L<<466.0,409.0>--<466.0,409.0>>

	* uni21F6 (U+21F6): L<<466.0,643.0>--<466.0,643.0>> -> L<<466.0,643.0>--<466.0,643.0>>

	* uni25A9 (U+25A9): L<<366.0,200.0>--<366.0,200.0>> -> L<<366.0,200.0>--<413.0,200.0>>

	* uni25C1 (U+25C1): L<<485.0,67.0>--<407.0,115.0>> -> L<<407.0,115.0>--<42.0,336.0>>

	* uni25C3 (U+25C3): L<<404.0,166.0>--<336.0,207.0>> -> L<<336.0,207.0>--<124.0,336.0>>

	* uni25C5 (U+25C5): L<<485.0,150.0>--<411.0,182.0>> -> L<<411.0,182.0>--<26.0,336.0>>

	* uniE0A1 (U+E0A1): L<<277.0,11.0>--<279.0,-31.0>> -> L<<279.0,-31.0>--<279.0,-137.0>> 

	* uniE0A1 (U+E0A1): L<<338.0,147.0>--<335.0,205.0>> -> L<<335.0,205.0>--<335.0,296.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[15] VictorMono-ThinItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon_semicolon.liga
	* seven
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2078
	* uni2079
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2088
	* uni2089
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2501
	* uni2502
	* uni2503
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2579
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B6
	* uni25B7
	* uni25BB
	* uni25BD
	* uni25C0
	* uni25C1
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE08
	* uniEE09
	* uniEE0A
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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

	- Glyph name: uni0495	Contours detected: 2	Expected: 1

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

	- Glyph name: uni0495	Contours detected: 2	Expected: 1

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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<345.0,729.0>--<368.0,727.0>> -> L<<368.0,727.0>--<390.0,727.0>>

	* section (U+00A7): L<<240.0,108.0>--<239.0,108.0>> -> L<<239.0,108.0>--<238.0,108.0>>

	* section (U+00A7): L<<242.0,152.0>--<244.0,152.0>> -> L<<244.0,152.0>--<244.0,152.0>>

	* section (U+00A7): L<<305.0,454.0>--<306.0,454.0>> -> L<<306.0,454.0>--<307.0,454.0>>

	* section (U+00A7): L<<306.0,454.0>--<307.0,454.0>> -> L<<307.0,454.0>--<307.0,454.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni0409 (U+0409): L<<245.0,729.0>--<267.0,727.0>> -> L<<267.0,727.0>--<422.0,727.0>>

	* uni0459 (U+0459): L<<210.0,564.0>--<232.0,562.0>> -> L<<232.0,562.0>--<387.0,562.0>>

	* uni0490 (U+0490): L<<596.0,841.0>--<573.0,727.0>> -> L<<573.0,727.0>--<565.0,685.0>>

	* uni0491 (U+0491): L<<563.0,675.0>--<539.0,562.0>> -> L<<539.0,562.0>--<530.0,520.0>>

	* uni04A4 (U+04A4): L<<515.0,740.0>--<515.0,740.0>> -> L<<515.0,740.0>--<688.0,740.0>>

	* uni21F3 (U+21F3): L<<149.0,284.0>--<166.0,364.0>> -> L<<166.0,364.0>--<184.0,444.0>>

	* uni21F3 (U+21F3): L<<237.0,485.0>--<212.0,364.0>> -> L<<212.0,364.0>--<186.0,242.0>>

	* uni21F3 (U+21F3): L<<345.0,242.0>--<370.0,364.0>> -> L<<370.0,364.0>--<395.0,485.0>>

	* uni21F3 (U+21F3): L<<433.0,444.0>--<415.0,364.0>> -> L<<415.0,364.0>--<398.0,284.0>>

	* uni25C1 (U+25C1): L<<463.0,106.0>--<419.0,133.0>> -> L<<419.0,133.0>--<83.0,336.0>>

	* uni25C3 (U+25C3): L<<381.0,205.0>--<348.0,225.0>> -> L<<348.0,225.0>--<165.0,336.0>>

	* uni25C5 (U+25C5): L<<463.0,183.0>--<419.0,201.0>> -> L<<419.0,201.0>--<83.0,336.0>>

	* uniE0A1 (U+E0A1): L<<248.0,138.0>--<256.0,-32.0>> -> L<<256.0,-32.0>--<256.0,-116.0>>

	* uniE0A1 (U+E0A1): L<<367.0,20.0>--<358.0,206.0>> -> L<<358.0,206.0>--<358.0,275.0>> 

	* xi (U+03BE): L<<562.0,727.0>--<557.0,699.0>> -> L<<557.0,699.0>--<555.0,685.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* aacute (U+00E1): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* abreve (U+0103): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* acircumflex (U+00E2): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* adieresis (U+00E4): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* agrave (U+00E0): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* alpha (U+03B1): B<<416.0,415.5>-<415.0,370.0>-<410.0,322.0>>/B<<410.0,322.0>-<443.0,421.0>-<478.0,564.0>> = 12.48808576894849

	* alphatonos (U+03AC): B<<416.0,415.5>-<415.0,370.0>-<410.0,322.0>>/B<<410.0,322.0>-<443.0,421.0>-<478.0,564.0>> = 12.48808576894849

	* amacron (U+0101): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* aogonek (U+0105): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* aring (U+00E5): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* atilde (U+00E3): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* beta (U+03B2): B<<70.0,264.0>-<74.0,283.0>-<78.0,304.0>>/L<<78.0,304.0>--<78.0,303.0>> = 10.784297867562596

	* beta (U+03B2): L<<78.0,304.0>--<78.0,303.0>>/L<<78.0,303.0>--<135.0,567.0>> = 12.183656585987398

	* eta (U+03B7): L<<145.0,462.0>--<159.0,473.0>>/L<<159.0,473.0>--<146.0,464.0>> = 3.4620730561348747

	* etatonos (U+03AE): L<<145.0,462.0>--<159.0,473.0>>/L<<159.0,473.0>--<146.0,464.0>> = 3.4620730561348747

	* q (U+0071): L<<310.0,-165.0>--<360.0,67.0>>/B<<360.0,67.0>-<350.0,46.0>-<326.0,28.0>> = 13.301141542189754

	* thorn (U+00FE): L<<232.0,727.0>--<180.0,488.0>>/B<<180.0,488.0>-<193.0,516.0>-<218.0,535.0>> = 12.630042712834918

	* uni01CE (U+01CE): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni041C (U+041C): B<<158.0,257.0>-<159.0,357.0>-<162.0,505.0>>/B<<162.0,505.0>-<124.0,332.0>-<96.5,217.0>> = 11.227221244994508

	* uni041C (U+041C): B<<417.5,217.0>-<442.0,338.0>-<484.0,540.0>>/B<<484.0,540.0>-<436.0,427.0>-<400.5,341.5>> = 11.26912099350199

	* uni0430 (U+0430): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni0436 (U+0436): L<<190.0,0.0>--<278.0,418.0>>/L<<278.0,418.0>--<175.0,208.0>> = 14.238193042722758

	* uni0436 (U+0436): L<<348.0,562.0>--<259.0,144.0>>/L<<259.0,144.0>--<363.0,359.0>> = 13.794177486099546

	* uni043C (U+043C): B<<138.0,178.5>-<133.0,249.0>-<131.0,360.0>>/B<<131.0,360.0>-<105.0,242.0>-<88.0,168.0>> = 13.458187556993218

	* uni043C (U+043C): B<<407.5,192.0>-<422.0,263.0>-<445.0,372.0>>/B<<445.0,372.0>-<410.0,294.0>-<377.0,224.5>> = 12.251482771720417

	* uni0443 (U+0443): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni045E (U+045E): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni0495 (U+0495): B<<137.0,214.5>-<118.0,180.0>-<105.0,120.0>>/L<<105.0,120.0>--<131.0,244.0>> = 0.38304656040815044

	* uni0497 (U+0497): L<<190.0,0.0>--<278.0,418.0>>/L<<278.0,418.0>--<175.0,208.0>> = 14.238193042722758

	* uni0497 (U+0497): L<<348.0,562.0>--<259.0,144.0>>/L<<259.0,144.0>--<363.0,359.0>> = 13.794177486099546

	* uni04A6 (U+04A6): B<<312.0,341.5>-<294.0,307.0>-<281.0,247.0>>/L<<281.0,247.0>--<301.0,343.0>> = 0.456833743714383

	* uni04A6 (U+04A6): L<<281.0,247.0>--<301.0,343.0>>/L<<301.0,343.0>--<228.0,0.0>> = 0.2465895955480018

	* uni04A6 (U+04A6): L<<383.0,727.0>--<307.0,371.0>>/B<<307.0,371.0>-<325.0,415.0>-<351.5,431.0>> = 10.198238773802803

	* uni04C2 (U+04C2): L<<190.0,0.0>--<278.0,418.0>>/L<<278.0,418.0>--<175.0,208.0>> = 14.238193042722758

	* uni04C2 (U+04C2): L<<348.0,562.0>--<259.0,144.0>>/L<<259.0,144.0>--<363.0,359.0>> = 13.794177486099546

	* uni04CD (U+04CD): B<<149.0,257.0>-<150.0,357.0>-<153.0,505.0>>/B<<153.0,505.0>-<115.0,332.0>-<87.5,217.0>> = 11.227221244994508

	* uni04CD (U+04CD): B<<411.0,229.0>-<435.0,348.0>-<475.0,540.0>>/B<<475.0,540.0>-<427.0,427.0>-<391.5,341.5>> = 11.246465486769319

	* uni04CE (U+04CE): B<<138.0,178.5>-<133.0,249.0>-<131.0,360.0>>/B<<131.0,360.0>-<105.0,242.0>-<88.0,168.0>> = 13.458187556993218

	* uni04CE (U+04CE): B<<402.5,166.5>-<418.0,243.0>-<445.0,372.0>>/B<<445.0,372.0>-<410.0,294.0>-<377.0,224.5>> = 12.3451415023782

	* uni04D1 (U+04D1): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni04D3 (U+04D3): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni04DD (U+04DD): L<<190.0,0.0>--<278.0,418.0>>/L<<278.0,418.0>--<175.0,208.0>> = 14.238193042722758

	* uni04DD (U+04DD): L<<348.0,562.0>--<259.0,144.0>>/L<<259.0,144.0>--<363.0,359.0>> = 13.794177486099546

	* uni04EF (U+04EF): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni04F1 (U+04F1): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni04F3 (U+04F3): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni1EA1 (U+1EA1): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EA3 (U+1EA3): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EA5 (U+1EA5): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EA7 (U+1EA7): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EA9 (U+1EA9): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EAB (U+1EAB): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EAD (U+1EAD): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EAF (U+1EAF): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EB1 (U+1EB1): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EB3 (U+1EB3): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EB5 (U+1EB5): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EB7 (U+1EB7): B<<331.5,76.0>-<334.0,93.0>-<337.0,103.0>>/B<<337.0,103.0>-<312.0,51.0>-<269.0,19.0>> = 8.977571447844545

	* uni1EF5 (U+1EF5): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni1EF7 (U+1EF7): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* uni1EF9 (U+1EF9): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* y (U+0079): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* yacute (U+00FD): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* ycircumflex (U+0177): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675

	* ydieresis (U+00FF): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675 

	* ygrave (U+1EF3): B<<371.5,62.0>-<377.0,83.0>-<379.0,96.0>>/B<<379.0,96.0>-<372.0,75.0>-<348.0,63.5>> = 9.68878656036675 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] VictorMono-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* h
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon_semicolon.liga
	* seven
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2078
	* uni2079
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2088
	* uni2089
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2501
	* uni2502
	* uni2503
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2579
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B6
	* uni25B7
	* uni25BB
	* uni25BD
	* uni25C0
	* uni25C1
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE08
	* uniEE09
	* uniEE0A
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* yen (U+00A5) contains a short segment L<<250.0,280.0>--<249.0,282.0>>

	* yen (U+00A5) contains a short segment L<<296.0,282.0>--<295.0,280.0>>

	* uni00B9 (U+00B9) contains a short segment L<<251.0,773.0>--<251.0,773.0>>

	* onequarter (U+00BC) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* onehalf (U+00BD) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* germandbls (U+00DF) contains a short segment L<<245.0,407.0>--<254.0,407.0>>

	* uni03D7 (U+03D7) contains a short segment L<<69.0,0.0>--<82.0,19.0>>

	* uni0404 (U+0404) contains a short segment L<<106.0,343.0>--<106.0,327.0>>

	* uni042D (U+042D) contains a short segment L<<439.0,385.0>--<439.0,400.0>>

	* uni042E (U+042E) contains a short segment L<<176.0,385.0>--<176.0,400.0>>

	* uni043A (U+043A) contains a short segment B<<227.0,280.0>-<221.0,280.0>-<215.0,280.0>>

	* uni044D (U+044D) contains a short segment L<<439.0,302.0>--<439.0,317.0>>

	* uni044E (U+044E) contains a short segment L<<176.0,302.0>--<176.0,317.0>>

	* uni0454 (U+0454) contains a short segment L<<106.0,260.0>--<106.0,245.0>>

	* uni045C (U+045C) contains a short segment B<<227.0,280.0>-<221.0,280.0>-<215.0,280.0>>

	* uni0464 (U+0464) contains a short segment L<<176.0,385.0>--<176.0,400.0>>

	* uni0464 (U+0464) contains a short segment L<<222.0,343.0>--<222.0,327.0>>

	* uni0465 (U+0465) contains a short segment L<<176.0,302.0>--<176.0,317.0>>

	* uni0465 (U+0465) contains a short segment L<<222.0,260.0>--<222.0,245.0>>

	* uni046A (U+046A) contains a short segment B<<253.0,392.0>-<262.0,393.0>-<273.0,393.0>>

	* uni046A (U+046A) contains a short segment B<<273.0,393.0>-<283.0,393.0>-<292.0,392.0>>

	* uni046B (U+046B) contains a short segment B<<252.0,319.0>-<262.0,320.0>-<273.0,320.0>>

	* uni046B (U+046B) contains a short segment B<<273.0,320.0>-<284.0,320.0>-<294.0,319.0>>

	* uni0494 (U+0494) contains a short segment B<<258.5,-175.5>-<247.0,-173.0>-<236.0,-167.0>>

	* uni0497 (U+0497) contains a short segment L<<489.0,0.0>--<489.0,3.0>>

	* uni049B (U+049B) contains a short segment B<<227.0,280.0>-<221.0,280.0>-<215.0,280.0>>

	* uni049C (U+049C) contains a short segment L<<217.0,364.0>--<216.0,364.0>>

	* uni049D (U+049D) contains a short segment L<<227.0,280.0>--<226.0,280.0>>

	* uni049F (U+049F) contains a short segment B<<227.0,280.0>-<221.0,280.0>-<215.0,280.0>>

	* uni04A1 (U+04A1) contains a short segment B<<227.0,280.0>-<221.0,280.0>-<215.0,280.0>>

	* uni04A6 (U+04A6) contains a short segment B<<374.0,-175.5>-<362.0,-173.0>-<352.0,-167.0>>

	* uni04A7 (U+04A7) contains a short segment B<<356.0,-175.5>-<344.0,-173.0>-<334.0,-167.0>>

	* uni04A8 (U+04A8) contains a short segment B<<385.0,30.0>-<393.0,29.0>-<402.0,29.0>>

	* uni04A9 (U+04A9) contains a short segment B<<385.0,30.0>-<393.0,29.0>-<402.0,29.0>>

	* uni04A9 (U+04A9) contains a short segment B<<254.0,29.0>-<263.0,29.0>-<272.0,30.0>>

	* uni04C3 (U+04C3) contains a short segment B<<234.0,-175.5>-<222.0,-173.0>-<212.0,-167.0>>

	* uni04EC (U+04EC) contains a short segment L<<439.0,385.0>--<439.0,400.0>>

	* uni04ED (U+04ED) contains a short segment L<<439.0,302.0>--<439.0,317.0>>

	* uni0512 (U+0512) contains a short segment L<<491.0,0.0>--<490.0,0.0>>

	* uni0513 (U+0513) contains a short segment L<<491.0,0.0>--<490.0,0.0>>

	* uni2081 (U+2081) contains a short segment L<<251.0,340.0>--<251.0,340.0>>

	* lira (U+20A4) contains a short segment B<<127.0,447.0>-<127.0,457.0>-<127.0,469.0>>

	* lira (U+20A4) contains a short segment B<<173.0,469.0>-<173.0,457.0>-<173.0,447.0>>

	* uni2150 (U+2150) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* uni2151 (U+2151) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* uni2152 (U+2152) contains a short segment L<<75.0,773.0>--<75.0,773.0>>

	* uni2152 (U+2152) contains a short segment L<<220.0,340.0>--<220.0,340.0>>

	* uni2153 (U+2153) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* uni2155 (U+2155) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* uni2159 (U+2159) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* oneeighth (U+215B) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* uni215F (U+215F) contains a short segment L<<100.0,773.0>--<100.0,773.0>>

	* uni21BC (U+21BC) contains a short segment L<<79.0,296.0>--<78.0,295.0>>

	* uni21BD (U+21BD) contains a short segment L<<78.0,432.0>--<79.0,431.0>>

	* uni21C0 (U+21C0) contains a short segment L<<467.0,295.0>--<466.0,296.0>>

	* uni21C1 (U+21C1) contains a short segment L<<466.0,431.0>--<467.0,432.0>>

	* uni21C8 (U+21C8) contains a short segment L<<306.0,544.0>--<306.0,543.0>>

	* uni21C8 (U+21C8) contains a short segment L<<273.0,502.0>--<273.0,503.0>>

	* uni21C8 (U+21C8) contains a short segment L<<273.0,503.0>--<272.0,502.0>>

	* uni21C8 (U+21C8) contains a short segment L<<240.0,543.0>--<240.0,543.0>>

	* uni21CA (U+21CA) contains a short segment L<<240.0,184.0>--<240.0,184.0>>

	* uni21CA (U+21CA) contains a short segment L<<272.0,225.0>--<273.0,224.0>>

	* uni21CA (U+21CA) contains a short segment L<<273.0,224.0>--<273.0,225.0>>

	* uni21CA (U+21CA) contains a short segment L<<306.0,184.0>--<306.0,183.0>>

	* uni21CB (U+21CB) contains a short segment L<<79.0,432.0>--<78.0,431.0>>

	* uni21CB (U+21CB) contains a short segment L<<466.0,295.0>--<467.0,296.0>>

	* uni21CC (U+21CC) contains a short segment L<<467.0,431.0>--<466.0,432.0>>

	* uni21CC (U+21CC) contains a short segment L<<78.0,296.0>--<79.0,295.0>>

	* uni21F6 (U+21F6) contains a short segment L<<293.0,489.0>--<294.0,489.0>>

	* uni21F6 (U+21F6) contains a short segment L<<294.0,489.0>--<293.0,490.0>>

	* uni251E (U+251E) contains a short segment L<<250.0,341.0>--<227.0,341.0>>

	* uni251F (U+251F) contains a short segment L<<227.0,386.0>--<250.0,386.0>>

	* uni2521 (U+2521) contains a short segment L<<250.0,318.0>--<227.0,318.0>>

	* uni2522 (U+2522) contains a short segment L<<227.0,409.0>--<250.0,409.0>>

	* uni2526 (U+2526) contains a short segment L<<318.0,341.0>--<295.0,341.0>>

	* uni2527 (U+2527) contains a short segment L<<295.0,386.0>--<318.0,386.0>>

	* uni2529 (U+2529) contains a short segment L<<318.0,318.0>--<295.0,318.0>>

	* uni252A (U+252A) contains a short segment L<<295.0,409.0>--<318.0,409.0>>

	* uni2543 (U+2543) contains a short segment L<<318.0,341.0>--<318.0,318.0>>

	* uni2543 (U+2543) contains a short segment L<<318.0,318.0>--<295.0,318.0>>

	* uni2544 (U+2544) contains a short segment L<<250.0,318.0>--<227.0,318.0>>

	* uni2544 (U+2544) contains a short segment L<<227.0,318.0>--<227.0,341.0>>

	* uni2545 (U+2545) contains a short segment L<<295.0,409.0>--<318.0,409.0>>

	* uni2545 (U+2545) contains a short segment L<<318.0,409.0>--<318.0,386.0>>

	* uni2546 (U+2546) contains a short segment L<<227.0,386.0>--<227.0,409.0>>

	* uni2546 (U+2546) contains a short segment L<<227.0,409.0>--<250.0,409.0>>

	* uni2573 (U+2573) contains a short segment L<<0.0,1091.0>--<25.0,1091.0>>

	* uni2573 (U+2573) contains a short segment L<<521.0,1091.0>--<545.0,1091.0>>

	* uni2573 (U+2573) contains a short segment L<<545.0,-364.0>--<521.0,-364.0>> 

	* uni2573 (U+2573) contains a short segment L<<25.0,-364.0>--<0.0,-364.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* oneeighth (U+215B): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* oneeighth (U+215B): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* onehalf (U+00BD): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* onehalf (U+00BD): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* onequarter (U+00BC): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* onequarter (U+00BC): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni00B9 (U+00B9): L<<250.0,773.0>--<251.0,773.0>> -> L<<251.0,773.0>--<251.0,773.0>>

	* uni00B9 (U+00B9): L<<251.0,773.0>--<251.0,773.0>> -> L<<251.0,773.0>--<296.0,773.0>>

	* uni2081 (U+2081): L<<250.0,340.0>--<251.0,340.0>> -> L<<251.0,340.0>--<251.0,340.0>>

	* uni2081 (U+2081): L<<251.0,340.0>--<251.0,340.0>> -> L<<251.0,340.0>--<296.0,340.0>>

	* uni2150 (U+2150): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* uni2150 (U+2150): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni2151 (U+2151): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* uni2151 (U+2151): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni2152 (U+2152): L<<219.0,340.0>--<220.0,340.0>> -> L<<220.0,340.0>--<220.0,340.0>>

	* uni2152 (U+2152): L<<220.0,340.0>--<220.0,340.0>> -> L<<220.0,340.0>--<265.0,340.0>>

	* uni2152 (U+2152): L<<74.0,773.0>--<75.0,773.0>> -> L<<75.0,773.0>--<75.0,773.0>>

	* uni2152 (U+2152): L<<75.0,773.0>--<75.0,773.0>> -> L<<75.0,773.0>--<120.0,773.0>>

	* uni2153 (U+2153): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* uni2153 (U+2153): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni2155 (U+2155): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* uni2155 (U+2155): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni2159 (U+2159): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* uni2159 (U+2159): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni215F (U+215F): L<<100.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<145.0,773.0>>

	* uni215F (U+215F): L<<99.0,773.0>--<100.0,773.0>> -> L<<100.0,773.0>--<100.0,773.0>>

	* uni25C1 (U+25C1): L<<463.0,106.0>--<419.0,133.0>> -> L<<419.0,133.0>--<83.0,336.0>>

	* uni25C3 (U+25C3): L<<381.0,205.0>--<348.0,225.0>> -> L<<348.0,225.0>--<165.0,336.0>>

	* uni25C5 (U+25C5): L<<463.0,183.0>--<419.0,201.0>> -> L<<419.0,201.0>--<83.0,336.0>>

	* uniE0A1 (U+E0A1): L<<248.0,138.0>--<256.0,-32.0>> -> L<<256.0,-32.0>--<256.0,-116.0>> 

	* uniE0A1 (U+E0A1): L<<367.0,20.0>--<358.0,206.0>> -> L<<358.0,206.0>--<358.0,275.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* alpha (U+03B1): B<<382.5,449.5>-<396.0,394.0>-<403.0,331.0>>/B<<403.0,331.0>-<414.0,426.0>-<418.0,562.0>> = 12.945027242663903

	* alphatonos (U+03AC): B<<382.5,449.5>-<396.0,394.0>-<403.0,331.0>>/B<<403.0,331.0>-<414.0,426.0>-<418.0,562.0>> = 12.945027242663903 

	* uni04A6 (U+04A6): L<<288.0,727.0>--<288.0,369.0>>/B<<288.0,369.0>-<297.0,413.0>-<320.5,430.0>> = 11.56013079421777 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* seveneighths (U+215E): L<<250.0,730.0>--<76.0,731.0>>

	* uni2077 (U+2077): L<<332.0,730.0>--<158.0,731.0>>

	* uni2087 (U+2087): L<<332.0,297.0>--<158.0,298.0>>

	* uni2150 (U+2150): L<<489.0,297.0>--<315.0,298.0>>

	* uni2196 (U+2196): L<<329.0,577.0>--<117.0,578.0>>

	* uni2196 (U+2196): L<<44.0,334.0>--<43.0,620.0>>

	* uni2196 (U+2196): L<<85.0,547.0>--<86.0,334.0>>

	* uni2197 (U+2197): L<<428.0,578.0>--<216.0,577.0>>

	* uni2197 (U+2197): L<<459.0,334.0>--<460.0,547.0>>

	* uni2197 (U+2197): L<<502.0,620.0>--<501.0,334.0>>

	* uni2198 (U+2198): L<<216.0,185.0>--<428.0,184.0>>

	* uni2198 (U+2198): L<<460.0,215.0>--<459.0,428.0>>

	* uni2198 (U+2198): L<<501.0,428.0>--<502.0,142.0>>

	* uni2199 (U+2199): L<<117.0,184.0>--<329.0,185.0>>

	* uni2199 (U+2199): L<<43.0,142.0>--<44.0,428.0>>

	* uni2199 (U+2199): L<<86.0,428.0>--<85.0,215.0>>

	* uni21D6 (U+21D6): L<<25.0,334.0>--<24.0,620.0>>

	* uni21D7 (U+21D7): L<<521.0,620.0>--<520.0,334.0>>

	* uni21D8 (U+21D8): L<<520.0,393.0>--<521.0,107.0>> 

	* uni21D9 (U+21D9): L<<24.0,107.0>--<25.0,393.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] VictorMono-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* h
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* kappa
	* l
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* male
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* rtblock
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon_semicolon.liga
	* seven
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2078
	* uni2079
	* uni207A
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2088
	* uni2089
	* uni208A
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B6
	* uni25B7
	* uni25BB
	* uni25BD
	* uni25C0
	* uni25C1
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE08
	* uniEE09
	* uniEE0A
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
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
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1424 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* eth (U+00F0): L<<481.0,226.0>--<481.0,225.0>> -> L<<481.0,225.0>--<481.0,224.0>>

	* eth (U+00F0): L<<481.0,227.0>--<481.0,226.0>> -> L<<481.0,226.0>--<481.0,225.0>>

	* oneeighth (U+215B): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* oneeighth (U+215B): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* onehalf (U+00BD): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* onehalf (U+00BD): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* onequarter (U+00BC): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* onequarter (U+00BC): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* partialdiff (U+2202): L<<486.0,228.0>--<486.0,227.0>> -> L<<486.0,227.0>--<486.0,224.0>>

	* rho (U+03C1): L<<73.0,281.0>--<73.0,281.0>> -> L<<73.0,281.0>--<73.0,281.0>>

	* section (U+00A7): L<<273.0,457.0>--<273.0,457.0>> -> L<<273.0,457.0>--<277.0,457.0>>

	* section (U+00A7): L<<273.0,457.0>--<277.0,457.0>> -> L<<277.0,457.0>--<277.0,457.0>>

	* uni00B9 (U+00B9): L<<247.0,773.0>--<248.0,773.0>> -> L<<248.0,773.0>--<248.0,773.0>>

	* uni00B9 (U+00B9): L<<248.0,773.0>--<248.0,773.0>> -> L<<248.0,773.0>--<298.0,773.0>>

	* uni04B0 (U+04B0): L<<111.0,278.0>--<246.0,278.0>> -> L<<246.0,278.0>--<246.0,278.0>>

	* uni04B0 (U+04B0): L<<299.0,278.0>--<299.0,278.0>> -> L<<299.0,278.0>--<435.0,278.0>>

	* uni04C3 (U+04C3): L<<199.0,361.0>--<198.0,361.0>> -> L<<198.0,361.0>--<126.0,361.0>>

	* uni2081 (U+2081): L<<247.0,341.0>--<248.0,341.0>> -> L<<248.0,341.0>--<248.0,341.0>>

	* uni2081 (U+2081): L<<248.0,341.0>--<248.0,341.0>> -> L<<248.0,341.0>--<298.0,341.0>>

	* uni2150 (U+2150): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* uni2150 (U+2150): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* uni2151 (U+2151): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* uni2151 (U+2151): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* uni2152 (U+2152): L<<213.0,341.0>--<214.0,341.0>> -> L<<214.0,341.0>--<214.0,341.0>>

	* uni2152 (U+2152): L<<214.0,341.0>--<214.0,341.0>> -> L<<214.0,341.0>--<264.0,341.0>>

	* uni2152 (U+2152): L<<74.0,773.0>--<75.0,773.0>> -> L<<75.0,773.0>--<75.0,773.0>>

	* uni2152 (U+2152): L<<75.0,773.0>--<75.0,773.0>> -> L<<75.0,773.0>--<125.0,773.0>>

	* uni2153 (U+2153): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* uni2153 (U+2153): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* uni2155 (U+2155): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* uni2155 (U+2155): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* uni2159 (U+2159): L<<96.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<97.0,773.0>>

	* uni2159 (U+2159): L<<97.0,773.0>--<97.0,773.0>> -> L<<97.0,773.0>--<147.0,773.0>>

	* uni215F (U+215F): L<<95.0,773.0>--<96.0,773.0>> -> L<<96.0,773.0>--<96.0,773.0>>

	* uni215F (U+215F): L<<96.0,773.0>--<96.0,773.0>> -> L<<96.0,773.0>--<146.0,773.0>>

	* uni21B4 (U+21B4): L<<412.0,727.0>--<412.0,727.0>> -> L<<412.0,727.0>--<418.0,727.0>>

	* uni21B4 (U+21B4): L<<8.0,727.0>--<412.0,727.0>> -> L<<412.0,727.0>--<412.0,727.0>>

	* uni21CA (U+21CA): L<<272.0,231.0>--<273.0,231.0>> -> L<<273.0,231.0>--<273.0,231.0>>

	* uni21CB (U+21CB): L<<-1.0,296.0>--<463.0,296.0>> -> L<<463.0,296.0>--<464.0,296.0>>

	* uni21CB (U+21CB): L<<463.0,296.0>--<464.0,296.0>> -> L<<464.0,296.0>--<533.0,296.0>>

	* uni21CB (U+21CB): L<<546.0,431.0>--<82.0,431.0>> -> L<<82.0,431.0>--<81.0,431.0>>

	* uni21CB (U+21CB): L<<82.0,431.0>--<81.0,431.0>> -> L<<81.0,431.0>--<12.0,431.0>>

	* uni21CC (U+21CC): L<<12.0,296.0>--<81.0,296.0>> -> L<<81.0,296.0>--<82.0,296.0>>

	* uni21CC (U+21CC): L<<464.0,431.0>--<463.0,431.0>> -> L<<463.0,431.0>--<-1.0,431.0>>

	* uni21CC (U+21CC): L<<533.0,431.0>--<464.0,431.0>> -> L<<464.0,431.0>--<463.0,431.0>>

	* uni21CC (U+21CC): L<<81.0,296.0>--<82.0,296.0>> -> L<<82.0,296.0>--<546.0,296.0>>

	* uni25C1 (U+25C1): L<<467.0,100.0>--<417.0,130.0>> -> L<<417.0,130.0>--<76.0,336.0>>

	* uni25C3 (U+25C3): L<<385.0,199.0>--<346.0,222.0>> -> L<<346.0,222.0>--<158.0,336.0>>

	* uni25C5 (U+25C5): L<<467.0,178.0>--<418.0,198.0>> -> L<<418.0,198.0>--<74.0,336.0>>

	* uniE0A1 (U+E0A1): L<<253.0,118.0>--<260.0,-32.0>> -> L<<260.0,-32.0>--<260.0,-119.0>> 

	* uniE0A1 (U+E0A1): L<<362.0,40.0>--<354.0,206.0>> -> L<<354.0,206.0>--<354.0,278.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* alpha (U+03B1): B<<380.0,466.5>-<395.0,418.0>-<403.0,361.0>>/B<<403.0,361.0>-<411.0,446.0>-<414.0,562.0>> = 13.366032194447602

	* alphatonos (U+03AC): B<<380.0,466.5>-<395.0,418.0>-<403.0,361.0>>/B<<403.0,361.0>-<411.0,446.0>-<414.0,562.0>> = 13.366032194447602

	* delta (U+03B4): B<<417.0,304.5>-<417.0,306.0>-<417.0,305.0>>/B<<417.0,305.0>-<410.0,388.0>-<377.0,420.5>> = 4.820766078092611

	* section (U+00A7): L<<269.0,105.0>--<269.0,105.0>>/B<<269.0,105.0>-<173.0,106.0>-<134.0,152.0>> = 0.5968094512291737

	* section (U+00A7): L<<277.0,406.0>--<277.0,406.0>>/B<<277.0,406.0>-<203.0,407.0>-<176.0,377.5>> = 0.774220164928034 

	* uni04A6 (U+04A6): L<<291.0,727.0>--<291.0,376.0>>/B<<291.0,376.0>-<301.0,416.0>-<323.0,431.5>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni2198 (U+2198): L<<212.0,189.0>--<416.0,188.0>> 

	* uni2199 (U+2199): L<<129.0,188.0>--<333.0,189.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] VictorMono-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* element
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* five
	* fiveeighths
	* florin
	* four
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon_semicolon.liga
	* seven
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* threeeighths
	* threequarters
	* trademark
	* two
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B5
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060301
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0490
	* uni0491
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CF
	* uni04D1
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2071
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni215A
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DC
	* uni21DD
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F9
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A6
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B1
	* uni25B3
	* uni25B5
	* uni25B7
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BF
	* uni25C1
	* uni25C3
	* uni25C5
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CC
	* uni25CE
	* uni25CF
	* uni25D4
	* uni25D5
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25EB
	* uni25EC
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FF
	* uni2716
	* uni27E8
	* uni27E9
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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

	- Glyph name: uni041B	Contours detected: 2	Expected: 1

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

	- Glyph name: uni041B	Contours detected: 2	Expected: 1

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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<334.0,730.0>--<370.0,727.0>> -> L<<370.0,727.0>--<402.0,727.0>>

	* oneeighth (U+215B): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* onehalf (U+00BD): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* onequarter (U+00BC): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni00B9 (U+00B9): L<<347.0,776.0>--<377.0,773.0>> -> L<<377.0,773.0>--<408.0,773.0>>

	* uni0409 (U+0409): L<<245.0,730.0>--<282.0,727.0>> -> L<<282.0,727.0>--<443.0,727.0>>

	* uni0459 (U+0459): L<<210.0,565.0>--<240.0,562.0>> -> L<<240.0,562.0>--<408.0,562.0>>

	* uni0490 (U+0490): L<<607.0,850.0>--<582.0,727.0>> -> L<<582.0,727.0>--<570.0,665.0>>

	* uni0491 (U+0491): L<<576.0,685.0>--<551.0,562.0>> -> L<<551.0,562.0>--<537.0,499.0>>

	* uni04A4 (U+04A4): L<<506.0,740.0>--<507.0,740.0>> -> L<<507.0,740.0>--<691.0,740.0>>

	* uni04B0 (U+04B0): L<<115.0,273.0>--<238.0,273.0>> -> L<<238.0,273.0>--<238.0,273.0>>

	* uni04B0 (U+04B0): L<<306.0,273.0>--<306.0,273.0>> -> L<<306.0,273.0>--<432.0,273.0>>

	* uni04C3 (U+04C3): L<<205.0,354.0>--<201.0,354.0>> -> L<<201.0,354.0>--<140.0,354.0>>

	* uni2081 (U+2081): L<<256.0,347.0>--<286.0,344.0>> -> L<<286.0,344.0>--<317.0,344.0>>

	* uni2150 (U+2150): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* uni2151 (U+2151): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* uni2152 (U+2152): L<<215.0,347.0>--<245.0,344.0>> -> L<<245.0,344.0>--<276.0,344.0>>

	* uni2153 (U+2153): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* uni2155 (U+2155): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* uni2159 (U+2159): L<<196.0,776.0>--<226.0,773.0>> -> L<<226.0,773.0>--<257.0,773.0>>

	* uni215F (U+215F): L<<194.0,776.0>--<224.0,773.0>> -> L<<224.0,773.0>--<255.0,773.0>>

	* uni21BD (U+21BD): L<<128.0,443.0>--<128.0,443.0>> -> L<<128.0,443.0>--<585.0,443.0>>

	* uni21BD (U+21BD): L<<38.0,443.0>--<128.0,443.0>> -> L<<128.0,443.0>--<128.0,443.0>>

	* uni21C1 (U+21C1): L<<39.0,443.0>--<496.0,443.0>> -> L<<496.0,443.0>--<497.0,443.0>>

	* uni21C1 (U+21C1): L<<496.0,443.0>--<497.0,443.0>> -> L<<497.0,443.0>--<587.0,443.0>>

	* uni21CA (U+21CA): L<<266.0,245.0>--<266.0,245.0>> -> L<<266.0,245.0>--<266.0,245.0>>

	* uni21F3 (U+21F3): L<<141.0,299.0>--<155.0,364.0>> -> L<<155.0,364.0>--<170.0,429.0>>

	* uni21F3 (U+21F3): L<<250.0,491.0>--<224.0,364.0>> -> L<<224.0,364.0>--<196.0,236.0>>

	* uni21F3 (U+21F3): L<<332.0,236.0>--<359.0,364.0>> -> L<<359.0,364.0>--<385.0,491.0>>

	* uni21F3 (U+21F3): L<<441.0,429.0>--<427.0,364.0>> -> L<<427.0,364.0>--<413.0,299.0>>

	* uni21F6 (U+21F6): L<<319.0,197.0>--<283.0,233.0>> -> L<<283.0,233.0>--<274.0,243.0>>

	* uni25C1 (U+25C1): L<<474.0,87.0>--<413.0,124.0>> -> L<<413.0,124.0>--<63.0,336.0>>

	* uni25C3 (U+25C3): L<<393.0,186.0>--<342.0,216.0>> -> L<<342.0,216.0>--<145.0,336.0>>

	* uni25C5 (U+25C5): L<<474.0,167.0>--<415.0,192.0>> -> L<<415.0,192.0>--<55.0,336.0>>

	* uniE0A1 (U+E0A1): L<<263.0,75.0>--<268.0,-31.0>> -> L<<268.0,-31.0>--<268.0,-126.0>> 

	* uniE0A1 (U+E0A1): L<<353.0,84.0>--<347.0,206.0>> -> L<<347.0,206.0>--<347.0,286.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* aacute (U+00E1): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* abreve (U+0103): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* acircumflex (U+00E2): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* adieresis (U+00E4): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* agrave (U+00E0): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* amacron (U+0101): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* aogonek (U+0105): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* aring (U+00E5): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* atilde (U+00E3): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* eta (U+03B7): L<<129.0,442.0>--<150.0,457.0>>/L<<150.0,457.0>--<131.0,445.0>> = 3.262033477396575

	* etatonos (U+03AE): L<<129.0,442.0>--<150.0,457.0>>/L<<150.0,457.0>--<131.0,445.0>> = 3.262033477396575

	* perthousand (U+2030): B<<301.5,254.5>-<324.0,236.0>-<321.0,192.0>>/B<<321.0,192.0>-<335.0,237.0>-<361.0,255.0>> = 13.381004629434754

	* perthousand (U+2030): B<<327.0,61.5>-<305.0,80.0>-<308.0,123.0>>/B<<308.0,123.0>-<294.0,78.0>-<267.5,60.5>> = 13.290585273386876

	* section (U+00A7): B<<386.0,369.5>-<369.0,396.0>-<312.0,398.0>>/L<<312.0,398.0>--<312.0,398.0>> = 2.0095538130210473

	* section (U+00A7): L<<226.0,99.0>--<226.0,99.0>>/B<<226.0,99.0>-<134.0,103.0>-<102.0,150.0>> = 2.4895529219991284

	* section (U+00A7): L<<312.0,398.0>--<312.0,398.0>>/B<<312.0,398.0>-<263.0,399.0>-<231.5,387.5>> = 1.169139327907133

	* section (U+00A7): L<<320.0,463.0>--<319.0,463.0>>/B<<319.0,463.0>-<411.0,459.0>-<443.0,411.5>> = 2.4895529219991284

	* uni01CE (U+01CE): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni0412 (U+0412): B<<100.0,224.0>-<118.0,316.0>-<144.0,439.0>>/B<<144.0,439.0>-<121.0,371.0>-<107.0,303.0>> = 6.751748961943725

	* uni0412 (U+0412): B<<86.0,178.5>-<79.0,122.0>-<77.0,93.0>>/B<<77.0,93.0>-<82.0,132.0>-<100.0,224.0>> = 3.3605733042732053

	* uni041B (U+041B): B<<35.0,48.0>-<41.0,40.0>-<40.0,40.0>>/B<<40.0,40.0>-<55.0,41.0>-<99.5,122.5>> = 3.8140748342903783

	* uni041C (U+041C): B<<154.5,161.5>-<153.0,256.0>-<155.0,419.0>>/B<<155.0,419.0>-<129.0,291.0>-<111.0,207.0>> = 10.779010932012476

	* uni041C (U+041C): B<<393.0,183.5>-<417.0,286.0>-<455.0,455.0>>/B<<455.0,455.0>-<388.0,297.0>-<350.0,204.0>> = 10.307087507660789

	* uni0430 (U+0430): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni043C (U+043C): B<<137.5,134.0>-<130.0,188.0>-<125.0,273.0>>/B<<125.0,273.0>-<108.0,182.0>-<95.0,126.0>> = 13.948096184373602

	* uni043C (U+043C): B<<375.5,121.5>-<388.0,182.0>-<412.0,285.0>>/B<<412.0,285.0>-<373.0,200.0>-<338.0,132.5>> = 11.530334726539667

	* uni046A (U+046A): L<<296.0,403.0>--<293.0,378.0>>/L<<293.0,378.0>--<293.0,379.0>> = 6.842773412630916

	* uni0495 (U+0495): B<<166.5,224.5>-<132.0,192.0>-<114.0,108.0>>/L<<114.0,108.0>--<129.0,183.0>> = 0.7848246029917126

	* uni0495 (U+0495): L<<114.0,108.0>--<129.0,183.0>>/L<<129.0,183.0>--<91.0,0.0>> = 0.4208428582663126

	* uni04C5 (U+04C5): B<<-1.0,48.0>-<5.0,40.0>-<4.0,40.0>>/B<<4.0,40.0>-<19.0,41.0>-<63.5,122.5>> = 3.8140748342903783

	* uni04CD (U+04CD): B<<132.5,161.5>-<131.0,256.0>-<133.0,419.0>>/B<<133.0,419.0>-<107.0,291.0>-<89.0,207.0>> = 10.779010932012476

	* uni04CD (U+04CD): B<<375.0,206.0>-<398.0,304.0>-<432.0,455.0>>/B<<432.0,455.0>-<365.0,297.0>-<327.0,204.0>> = 10.289991307500339

	* uni04CE (U+04CE): B<<137.5,134.0>-<130.0,188.0>-<125.0,273.0>>/B<<125.0,273.0>-<108.0,182.0>-<95.0,126.0>> = 13.948096184373602

	* uni04CE (U+04CE): B<<379.0,136.5>-<391.0,194.0>-<412.0,285.0>>/B<<412.0,285.0>-<373.0,200.0>-<338.0,132.5>> = 11.652154060014634

	* uni04D1 (U+04D1): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni04D3 (U+04D3): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni0512 (U+0512): B<<35.0,48.0>-<41.0,40.0>-<40.0,40.0>>/B<<40.0,40.0>-<55.0,41.0>-<99.5,122.5>> = 3.8140748342903783

	* uni1EA1 (U+1EA1): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EA3 (U+1EA3): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EA5 (U+1EA5): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EA7 (U+1EA7): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EA9 (U+1EA9): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EAB (U+1EAB): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EAD (U+1EAD): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EAF (U+1EAF): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EB1 (U+1EB1): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EB3 (U+1EB3): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903

	* uni1EB5 (U+1EB5): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903 

	* uni1EB7 (U+1EB7): B<<319.5,61.0>-<320.0,70.0>-<323.0,74.0>>/B<<323.0,74.0>-<296.0,34.0>-<258.0,10.5>> = 2.8505476560174903 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] VictorMono-SemiBoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hungarumlaut
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* minus
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060300.case
	* uni03060301
	* uni03060301.case
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2508
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25BF
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C3
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE06
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0427	Contours detected: 2	Expected: 1

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

	- Glyph name: uni049C	Contours detected: 2	Expected: 1

	- Glyph name: uni049E	Contours detected: 2	Expected: 1

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04B8	Contours detected: 2	Expected: 1

	- Glyph name: uni04BA	Contours detected: 2	Expected: 1

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

	- Glyph name: uni04F4	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni0526	Contours detected: 2	Expected: 1

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

	- Glyph name: uni040C	Contours detected: 3	Expected: 2

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0427	Contours detected: 2	Expected: 1

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

	- Glyph name: uni049C	Contours detected: 2	Expected: 1

	- Glyph name: uni049E	Contours detected: 2	Expected: 1

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04B8	Contours detected: 2	Expected: 1

	- Glyph name: uni04BA	Contours detected: 2	Expected: 1

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

	- Glyph name: uni04F4	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 3	Expected: 5

	- Glyph name: uni0526	Contours detected: 2	Expected: 1

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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<326.0,731.0>--<372.0,727.0>> -> L<<372.0,727.0>--<409.0,727.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni0409 (U+0409): L<<245.0,731.0>--<292.0,727.0>> -> L<<292.0,727.0>--<457.0,727.0>>

	* uni0422 (U+0422): L<<214.0,727.0>--<214.0,727.0>> -> L<<214.0,727.0>--<616.0,727.0>>

	* uni0426 (U+0426): L<<465.0,95.0>--<465.0,95.0>> -> L<<465.0,95.0>--<465.0,95.0>>

	* uni044B (U+044B): L<<167.0,264.0>--<167.0,264.0>> -> L<<167.0,264.0>--<167.0,264.0>>

	* uni0459 (U+0459): L<<210.0,565.0>--<246.0,562.0>> -> L<<246.0,562.0>--<422.0,562.0>>

	* uni0490 (U+0490): L<<614.0,856.0>--<587.0,727.0>> -> L<<587.0,727.0>--<573.0,651.0>>

	* uni0491 (U+0491): L<<585.0,691.0>--<558.0,562.0>> -> L<<558.0,562.0>--<542.0,485.0>>

	* uni04A4 (U+04A4): L<<500.0,740.0>--<501.0,740.0>> -> L<<501.0,740.0>--<501.0,740.0>>

	* uni04A4 (U+04A4): L<<501.0,740.0>--<501.0,740.0>> -> L<<501.0,740.0>--<692.0,740.0>>

	* uni04AC (U+04AC): L<<214.0,727.0>--<214.0,727.0>> -> L<<214.0,727.0>--<616.0,727.0>>

	* uni04F9 (U+04F9): L<<167.0,264.0>--<167.0,264.0>> -> L<<167.0,264.0>--<167.0,264.0>>

	* uni2152 (U+2152): L<<204.0,349.0>--<242.0,346.0>> -> L<<242.0,346.0>--<275.0,346.0>>

	* uni21BC (U+21BC): L<<102.0,277.0>--<101.0,277.0>> -> L<<101.0,277.0>--<-9.0,277.0>>

	* uni21BC (U+21BC): L<<553.0,277.0>--<102.0,277.0>> -> L<<102.0,277.0>--<101.0,277.0>>

	* uni21BD (U+21BD): L<<139.0,450.0>--<139.0,450.0>> -> L<<139.0,450.0>--<590.0,450.0>>

	* uni21BD (U+21BD): L<<29.0,450.0>--<139.0,450.0>> -> L<<139.0,450.0>--<139.0,450.0>>

	* uni21C1 (U+21C1): L<<31.0,450.0>--<483.0,450.0>> -> L<<483.0,450.0>--<483.0,450.0>>

	* uni21C1 (U+21C1): L<<483.0,450.0>--<483.0,450.0>> -> L<<483.0,450.0>--<593.0,450.0>>

	* uni21D6 (U+21D6): L<<105.0,620.0>--<280.0,620.0>> -> L<<280.0,620.0>--<280.0,620.0>>

	* uni21D6 (U+21D6): L<<280.0,620.0>--<280.0,620.0>> -> L<<280.0,620.0>--<280.0,620.0>>

	* uni21D6 (U+21D6): L<<280.0,620.0>--<280.0,620.0>> -> L<<280.0,620.0>--<412.0,620.0>>

	* uni21D7 (U+21D7): L<<277.0,620.0>--<409.0,620.0>> -> L<<409.0,620.0>--<409.0,620.0>>

	* uni21D7 (U+21D7): L<<409.0,620.0>--<409.0,620.0>> -> L<<409.0,620.0>--<410.0,620.0>>

	* uni21D7 (U+21D7): L<<409.0,620.0>--<410.0,620.0>> -> L<<410.0,620.0>--<584.0,620.0>>

	* uni21D8 (U+21D8): L<<301.0,107.0>--<301.0,107.0>> -> L<<301.0,107.0>--<301.0,107.0>>

	* uni21D9 (U+21D9): L<<303.0,107.0>--<171.0,107.0>> -> L<<171.0,107.0>--<170.0,107.0>>

	* uni21F3 (U+21F3): L<<136.0,309.0>--<148.0,364.0>> -> L<<148.0,364.0>--<160.0,419.0>>

	* uni21F3 (U+21F3): L<<259.0,495.0>--<231.0,364.0>> -> L<<231.0,364.0>--<203.0,232.0>>

	* uni21F3 (U+21F3): L<<323.0,232.0>--<351.0,364.0>> -> L<<351.0,364.0>--<378.0,495.0>>

	* uni21F3 (U+21F3): L<<446.0,419.0>--<434.0,364.0>> -> L<<434.0,364.0>--<422.0,309.0>>

	* uni25C1 (U+25C1): L<<481.0,73.0>--<409.0,118.0>> -> L<<409.0,118.0>--<49.0,336.0>>

	* uni25C3 (U+25C3): L<<400.0,172.0>--<338.0,210.0>> -> L<<338.0,210.0>--<131.0,336.0>>

	* uni25C5 (U+25C5): L<<481.0,155.0>--<412.0,185.0>> -> L<<412.0,185.0>--<35.0,336.0>>

	* uniE0A1 (U+E0A1): L<<272.0,31.0>--<275.0,-31.0>> -> L<<275.0,-31.0>--<275.0,-134.0>>

	* uniE0A1 (U+E0A1): L<<343.0,127.0>--<339.0,205.0>> -> L<<339.0,205.0>--<339.0,293.0>> 

	* xi (U+03BE): L<<581.0,727.0>--<574.0,693.0>> -> L<<574.0,693.0>--<569.0,652.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* eta (U+03B7): L<<118.0,428.0>--<144.0,446.0>>/L<<144.0,446.0>--<120.0,431.0>> = 2.6897703231502974

	* etatonos (U+03AE): L<<118.0,428.0>--<144.0,446.0>>/L<<144.0,446.0>--<120.0,431.0>> = 2.6897703231502974

	* n (U+006E): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* nacute (U+0144): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* ncaron (U+0148): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* ntilde (U+00F1): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* section (U+00A7): B<<380.0,363.5>-<365.0,386.0>-<319.0,389.0>>/L<<319.0,389.0>--<319.0,389.0>> = 3.7313969991604012

	* section (U+00A7): L<<319.0,389.0>--<319.0,389.0>>/B<<319.0,389.0>-<269.0,391.0>-<238.0,381.0>> = 2.2906100426384346

	* u (U+0075): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uacute (U+00FA): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* ubreve (U+016D): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* ucircumflex (U+00FB): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* udieresis (U+00FC): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* ugrave (U+00F9): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uhorn (U+01B0): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uhungarumlaut (U+0171): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* umacron (U+016B): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni0146 (U+0146): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* uni01D4 (U+01D4): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni01D6 (U+01D6): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni01D8 (U+01D8): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni01DA (U+01DA): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni01DC (U+01DC): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni040D (U+040D): B<<411.0,108.5>-<405.0,76.0>-<405.0,77.0>>/B<<405.0,77.0>-<404.0,64.0>-<420.0,64.0>> = 4.398705354995508

	* uni0411 (U+0411): B<<117.0,281.0>-<87.0,223.0>-<85.0,146.0>>/B<<85.0,146.0>-<91.0,173.0>-<99.0,206.5>> = 11.040940180323686

	* uni0411 (U+0411): B<<99.0,206.5>-<107.0,240.0>-<117.0,281.0>>/B<<117.0,281.0>-<87.0,223.0>-<85.0,146.0>> = 13.642914775990052

	* uni0418 (U+0418): B<<411.0,108.5>-<405.0,76.0>-<405.0,77.0>>/B<<405.0,77.0>-<404.0,64.0>-<420.0,64.0>> = 4.398705354995508

	* uni0419 (U+0419): B<<411.0,108.5>-<405.0,76.0>-<405.0,77.0>>/B<<405.0,77.0>-<404.0,64.0>-<420.0,64.0>> = 4.398705354995508

	* uni041C (U+041C): B<<152.5,138.5>-<150.0,220.0>-<151.0,358.0>>/B<<151.0,358.0>-<128.0,235.0>-<112.5,161.0>> = 10.176348206826502

	* uni041C (U+041C): B<<374.0,156.0>-<395.0,244.0>-<430.0,387.0>>/B<<430.0,387.0>-<408.0,333.0>-<389.0,289.0>> = 8.413275235559427

	* uni0426 (U+0426): B<<411.0,108.5>-<405.0,76.0>-<405.0,77.0>>/B<<405.0,77.0>-<404.0,64.0>-<420.0,64.0>> = 4.398705354995508

	* uni0427 (U+0427): B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>>/L<<498.0,627.0>--<497.0,622.0>> = 11.309932474020227

	* uni0427 (U+0427): L<<498.0,627.0>--<497.0,622.0>>/B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>> = 7.125016348901757

	* uni0428 (U+0428): B<<445.0,112.5>-<440.0,75.0>-<440.0,77.0>>/B<<440.0,77.0>-<439.0,64.0>-<455.0,64.0>> = 4.398705354995508

	* uni0429 (U+0429): B<<445.0,112.5>-<440.0,75.0>-<440.0,77.0>>/B<<440.0,77.0>-<439.0,64.0>-<455.0,64.0>> = 4.398705354995508

	* uni0438 (U+0438): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni0439 (U+0439): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni043C (U+043C): B<<358.5,95.0>-<368.0,143.0>-<387.0,224.0>>/B<<387.0,224.0>-<354.0,154.0>-<324.5,100.5>> = 12.039442089081186

	* uni043F (U+043F): L<<205.0,479.0>--<199.0,468.0>>/B<<199.0,468.0>-<239.0,520.0>-<283.0,547.5>> = 8.958132362862301

	* uni0446 (U+0446): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni045D (U+045D): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni045F (U+045F): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni0495 (U+0495): B<<170.5,211.0>-<137.0,179.0>-<120.0,99.0>>/L<<120.0,99.0>--<133.0,165.0>> = 0.8540094495837945

	* uni0495 (U+0495): L<<120.0,99.0>--<133.0,165.0>>/L<<133.0,165.0>--<98.0,0.0>> = 0.8332425858635236

	* uni04B6 (U+04B6): B<<481.0,622.0>-<482.0,625.0>-<482.0,627.0>>/L<<482.0,627.0>--<481.0,622.0>> = 11.309932474020227

	* uni04B6 (U+04B6): L<<482.0,627.0>--<481.0,622.0>>/B<<481.0,622.0>-<482.0,625.0>-<482.0,627.0>> = 7.125016348901757

	* uni04B8 (U+04B8): B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>>/L<<498.0,627.0>--<497.0,622.0>> = 11.309932474020227

	* uni04B8 (U+04B8): L<<498.0,627.0>--<497.0,622.0>>/B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>> = 7.125016348901757

	* uni04BA (U+04BA): B<<83.0,105.0>-<82.0,102.0>-<82.0,100.0>>/L<<82.0,100.0>--<83.0,105.0>> = 11.309932474020195

	* uni04BA (U+04BA): L<<82.0,100.0>--<83.0,105.0>>/B<<83.0,105.0>-<82.0,102.0>-<82.0,100.0>> = 7.125016348901705

	* uni04CB (U+04CB): B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>>/L<<498.0,627.0>--<497.0,622.0>> = 11.309932474020227

	* uni04CB (U+04CB): L<<498.0,627.0>--<497.0,622.0>>/B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>> = 7.125016348901757

	* uni04CD (U+04CD): B<<121.5,138.5>-<119.0,220.0>-<120.0,358.0>>/B<<120.0,358.0>-<96.0,235.0>-<81.0,161.0>> = 10.625760639178845

	* uni04CD (U+04CD): B<<348.5,183.0>-<369.0,265.0>-<399.0,387.0>>/B<<399.0,387.0>-<376.0,333.0>-<357.5,289.0>> = 9.25538690856302

	* uni04CE (U+04CE): B<<356.5,85.0>-<366.0,134.0>-<387.0,224.0>>/B<<387.0,224.0>-<354.0,154.0>-<324.5,100.5>> = 12.106506958390462

	* uni04E2 (U+04E2): B<<411.0,108.5>-<405.0,76.0>-<405.0,77.0>>/B<<405.0,77.0>-<404.0,64.0>-<420.0,64.0>> = 4.398705354995508

	* uni04E3 (U+04E3): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni04E4 (U+04E4): B<<411.0,108.5>-<405.0,76.0>-<405.0,77.0>>/B<<405.0,77.0>-<404.0,64.0>-<420.0,64.0>> = 4.398705354995508

	* uni04E5 (U+04E5): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni04F4 (U+04F4): B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>>/L<<498.0,627.0>--<497.0,622.0>> = 11.309932474020227

	* uni04F4 (U+04F4): L<<498.0,627.0>--<497.0,622.0>>/B<<497.0,622.0>-<498.0,625.0>-<498.0,627.0>> = 7.125016348901757

	* uni0526 (U+0526): L<<47.0,100.0>--<48.0,105.0>>/B<<48.0,105.0>-<48.0,102.0>-<47.0,100.0>> = 11.309932474020195

	* uni1EE5 (U+1EE5): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni1EE7 (U+1EE7): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni1EE9 (U+1EE9): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni1EEB (U+1EEB): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni1EED (U+1EED): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni1EEF (U+1EEF): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uni1EF1 (U+1EF1): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uogonek (U+0173): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455

	* uring (U+016F): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455 

	* utilde (U+0169): L<<335.0,83.0>--<340.0,94.0>>/B<<340.0,94.0>-<301.0,42.0>-<261.5,14.5>> = 12.425942865427455 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] VictorMono-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciicircum
	* asciitilde
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* comma
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* dieresis
	* dieresistonos
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emdash
	* emptyset
	* endash
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hungarumlaut
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* minus
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* openbullet
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesinglbase
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni02BC
	* uni03020300
	* uni03020300.case
	* uni03020301
	* uni03020301.case
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060300
	* uni03060300.case
	* uni03060301
	* uni03060301.case
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni0308
	* uni030A
	* uni030A.case
	* uni030B
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2015
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207C
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208C
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2508
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254D
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B5
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25B9
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25BF
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C3
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C9
	* uni25CC
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE06
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0427	Contours detected: 2	Expected: 1

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

	- Glyph name: uni049E	Contours detected: 2	Expected: 1

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04B8	Contours detected: 2	Expected: 1

	- Glyph name: uni04BA	Contours detected: 2	Expected: 1

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

	- Glyph name: uni04F4	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 4	Expected: 5

	- Glyph name: uni0526	Contours detected: 2	Expected: 1

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

	- Glyph name: uni040C	Contours detected: 3	Expected: 2

	- Glyph name: uni0410	Contours detected: 3	Expected: 2

	- Glyph name: uni0411	Contours detected: 4	Expected: 2

	- Glyph name: uni0412	Contours detected: 2	Expected: 3

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni041D	Contours detected: 3	Expected: 1

	- Glyph name: uni0422	Contours detected: 2	Expected: 1

	- Glyph name: uni0426	Contours detected: 2	Expected: 1

	- Glyph name: uni0427	Contours detected: 2	Expected: 1

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

	- Glyph name: uni049E	Contours detected: 2	Expected: 1

	- Glyph name: uni04A2	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni04A4	Contours detected: 3	Expected: 1

	- Glyph name: uni04B8	Contours detected: 2	Expected: 1

	- Glyph name: uni04BA	Contours detected: 2	Expected: 1

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

	- Glyph name: uni04F4	Contours detected: 4	Expected: 3

	- Glyph name: uni04F8	Contours detected: 4	Expected: 5

	- Glyph name: uni04F9	Contours detected: 4	Expected: 5

	- Glyph name: uni0526	Contours detected: 2	Expected: 1

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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* one (U+0031): L<<322.0,731.0>--<373.0,727.0>> -> L<<373.0,727.0>--<413.0,727.0>>

	* oneeighth (U+215B): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* onehalf (U+00BD): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* onequarter (U+00BC): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni00B9 (U+00B9): L<<339.0,776.0>--<381.0,772.0>> -> L<<381.0,772.0>--<415.0,772.0>>

	* uni0409 (U+0409): L<<245.0,731.0>--<296.0,727.0>> -> L<<296.0,727.0>--<464.0,727.0>>

	* uni0422 (U+0422): L<<212.0,727.0>--<212.0,727.0>> -> L<<212.0,727.0>--<617.0,727.0>>

	* uni0459 (U+0459): L<<210.0,565.0>--<249.0,562.0>> -> L<<249.0,562.0>--<429.0,562.0>>

	* uni0490 (U+0490): L<<617.0,859.0>--<590.0,727.0>> -> L<<590.0,727.0>--<574.0,644.0>>

	* uni0491 (U+0491): L<<589.0,694.0>--<562.0,562.0>> -> L<<562.0,562.0>--<544.0,478.0>>

	* uni04A4 (U+04A4): L<<498.0,740.0>--<498.0,740.0>> -> L<<498.0,740.0>--<693.0,740.0>>

	* uni04AC (U+04AC): L<<212.0,727.0>--<212.0,727.0>> -> L<<212.0,727.0>--<617.0,727.0>>

	* uni0526 (U+0526): L<<463.0,36.0>--<463.0,36.0>> -> L<<463.0,36.0>--<464.0,36.0>>

	* uni2081 (U+2081): L<<249.0,351.0>--<291.0,347.0>> -> L<<291.0,347.0>--<325.0,347.0>>

	* uni2150 (U+2150): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* uni2151 (U+2151): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* uni2152 (U+2152): L<<178.0,776.0>--<220.0,772.0>> -> L<<220.0,772.0>--<254.0,772.0>>

	* uni2153 (U+2153): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* uni2155 (U+2155): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* uni2159 (U+2159): L<<188.0,776.0>--<230.0,772.0>> -> L<<230.0,772.0>--<264.0,772.0>>

	* uni215F (U+215F): L<<184.0,776.0>--<226.0,772.0>> -> L<<226.0,772.0>--<260.0,772.0>>

	* uni21C4 (U+21C4): L<<49.0,218.0>--<49.0,218.0>> -> L<<49.0,218.0>--<49.0,218.0>>

	* uni21C4 (U+21C4): L<<551.0,600.0>--<552.0,600.0>> -> L<<552.0,600.0>--<552.0,600.0>>

	* uni21C5 (U+21C5): L<<183.0,675.0>--<183.0,675.0>> -> L<<183.0,675.0>--<184.0,675.0>>

	* uni21C5 (U+21C5): L<<306.0,52.0>--<306.0,52.0>> -> L<<306.0,52.0>--<306.0,52.0>>

	* uni21C6 (U+21C6): L<<111.0,509.0>--<111.0,509.0>> -> L<<111.0,509.0>--<111.0,509.0>>

	* uni21C7 (U+21C7): L<<139.0,600.0>--<139.0,600.0>> -> L<<139.0,600.0>--<140.0,600.0>>

	* uni21C7 (U+21C7): L<<58.0,218.0>--<58.0,218.0>> -> L<<58.0,218.0>--<58.0,218.0>>

	* uni21C8 (U+21C8): L<<195.0,675.0>--<195.0,675.0>> -> L<<195.0,675.0>--<196.0,675.0>>

	* uni21C8 (U+21C8): L<<427.0,675.0>--<427.0,675.0>> -> L<<427.0,675.0>--<428.0,675.0>>

	* uni21C9 (U+21C9): L<<461.0,218.0>--<462.0,218.0>> -> L<<462.0,218.0>--<462.0,218.0>>

	* uni21C9 (U+21C9): L<<542.0,600.0>--<543.0,600.0>> -> L<<543.0,600.0>--<543.0,600.0>>

	* uni21CA (U+21CA): L<<296.0,52.0>--<296.0,52.0>> -> L<<296.0,52.0>--<296.0,52.0>>

	* uni21CA (U+21CA): L<<64.0,52.0>--<64.0,52.0>> -> L<<64.0,52.0>--<64.0,52.0>>

	* uni21F3 (U+21F3): L<<263.0,497.0>--<235.0,364.0>> -> L<<235.0,364.0>--<206.0,230.0>>

	* uni21F3 (U+21F3): L<<319.0,230.0>--<347.0,364.0>> -> L<<347.0,364.0>--<375.0,497.0>>

	* uni21F5 (U+21F5): L<<437.0,675.0>--<437.0,675.0>> -> L<<437.0,675.0>--<438.0,675.0>>

	* uni21F5 (U+21F5): L<<51.0,52.0>--<51.0,52.0>> -> L<<51.0,52.0>--<51.0,52.0>>

	* uni21F6 (U+21F6): L<<452.0,176.0>--<453.0,176.0>> -> L<<453.0,176.0>--<453.0,176.0>>

	* uni21F6 (U+21F6): L<<502.0,409.0>--<503.0,409.0>> -> L<<503.0,409.0>--<503.0,409.0>>

	* uni21F6 (U+21F6): L<<551.0,643.0>--<552.0,643.0>> -> L<<552.0,643.0>--<552.0,643.0>>

	* uni25A9 (U+25A9): L<<366.0,200.0>--<366.0,200.0>> -> L<<366.0,200.0>--<413.0,200.0>>

	* uni25C1 (U+25C1): L<<485.0,67.0>--<407.0,115.0>> -> L<<407.0,115.0>--<42.0,336.0>>

	* uni25C3 (U+25C3): L<<404.0,166.0>--<336.0,207.0>> -> L<<336.0,207.0>--<124.0,336.0>>

	* uni25C5 (U+25C5): L<<485.0,150.0>--<411.0,182.0>> -> L<<411.0,182.0>--<26.0,336.0>>

	* uniE0A1 (U+E0A1): L<<277.0,11.0>--<279.0,-31.0>> -> L<<279.0,-31.0>--<279.0,-137.0>> 

	* uniE0A1 (U+E0A1): L<<338.0,147.0>--<335.0,205.0>> -> L<<335.0,205.0>--<335.0,296.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Q (U+0051): B<<286.0,79.5>-<289.0,80.0>-<286.0,79.0>>/B<<286.0,79.0>-<339.0,97.0>-<372.0,155.0>> = 0.32370152491859816

	* eta (U+03B7): L<<113.0,421.0>--<142.0,441.0>>/L<<142.0,441.0>--<115.0,425.0>> = 3.9416207304570023

	* etatonos (U+03AE): L<<113.0,421.0>--<142.0,441.0>>/L<<142.0,441.0>--<115.0,425.0>> = 3.9416207304570023

	* section (U+00A7): B<<377.0,361.0>-<363.0,382.0>-<322.0,385.0>>/L<<322.0,385.0>--<322.0,385.0>> = 4.184916125118406

	* section (U+00A7): L<<322.0,385.0>--<322.0,385.0>>/B<<322.0,385.0>-<272.0,388.0>-<241.0,378.5>> = 3.4336303624505082

	* uni0411 (U+0411): B<<102.0,233.0>-<96.0,215.0>-<93.0,196.0>>/B<<93.0,196.0>-<97.0,213.0>-<102.0,233.0>> = 4.2678933002906865

	* uni0411 (U+0411): B<<93.0,196.0>-<97.0,213.0>-<102.0,233.0>>/B<<102.0,233.0>-<96.0,215.0>-<93.0,196.0>> = 4.398705354995508

	* uni041C (U+041C): B<<152.0,127.0>-<149.0,202.0>-<150.0,329.0>>/B<<150.0,329.0>-<132.0,233.0>-<119.5,170.0>> = 10.168516729367832

	* uni041C (U+041C): B<<364.5,141.5>-<384.0,222.0>-<417.0,351.0>>/B<<417.0,351.0>-<400.0,310.0>-<385.0,275.5>> = 8.171233559949721

	* uni0427 (U+0427): B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>>/L<<496.0,632.0>--<495.0,626.0>> = 8.972626614896358

	* uni0427 (U+0427): L<<496.0,632.0>--<495.0,626.0>>/B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>> = 9.462322208025613

	* uni042B (U+042B): B<<464.0,599.0>-<491.0,637.0>-<507.0,697.0>>/L<<507.0,697.0>--<503.0,678.0>> = 3.0427591385095694

	* uni042B (U+042B): L<<507.0,697.0>--<503.0,678.0>>/B<<503.0,678.0>-<508.0,703.0>-<514.0,727.0>> = 0.5787255656073457

	* uni043C (U+043C): B<<350.0,82.0>-<358.0,124.0>-<375.0,195.0>>/B<<375.0,195.0>-<330.0,102.0>-<292.5,44.5>> = 12.355783879377563

	* uni044A (U+044A): B<<163.0,103.5>-<149.0,159.0>-<163.0,232.0>>/B<<163.0,232.0>-<163.0,230.0>-<166.5,245.5>> = 10.856413348062235

	* uni044B (U+044B): B<<-4.0,103.5>-<-18.0,159.0>-<-4.0,232.0>>/B<<-4.0,232.0>-<-4.0,231.0>-<-1.0,243.5>> = 10.856413348062235

	* uni044C (U+044C): B<<85.0,103.5>-<71.0,159.0>-<85.0,232.0>>/B<<85.0,232.0>-<85.0,231.0>-<88.0,243.5>> = 10.856413348062235

	* uni0495 (U+0495): B<<173.0,205.0>-<140.0,174.0>-<123.0,95.0>>/L<<123.0,95.0>--<135.0,160.0>> = 1.6843689566377198

	* uni0495 (U+0495): L<<123.0,95.0>--<135.0,160.0>>/L<<135.0,160.0>--<102.0,0.0>> = 1.1939314929046991

	* uni04B6 (U+04B6): B<<476.0,626.0>-<476.0,629.0>-<477.0,632.0>>/L<<477.0,632.0>--<476.0,626.0>> = 8.972626614896358

	* uni04B6 (U+04B6): L<<477.0,632.0>--<476.0,626.0>>/B<<476.0,626.0>-<476.0,629.0>-<477.0,632.0>> = 9.462322208025613

	* uni04B8 (U+04B8): B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>>/L<<496.0,632.0>--<495.0,626.0>> = 8.972626614896358

	* uni04B8 (U+04B8): L<<496.0,632.0>--<495.0,626.0>>/B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>> = 9.462322208025613

	* uni04BA (U+04BA): B<<85.0,101.0>-<85.0,98.0>-<84.0,95.0>>/L<<84.0,95.0>--<85.0,101.0>> = 8.972626614896358

	* uni04BA (U+04BA): L<<84.0,95.0>--<85.0,101.0>>/B<<85.0,101.0>-<85.0,98.0>-<84.0,95.0>> = 9.462322208025613

	* uni04CB (U+04CB): B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>>/L<<496.0,632.0>--<495.0,626.0>> = 8.972626614896358

	* uni04CB (U+04CB): L<<496.0,632.0>--<495.0,626.0>>/B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>> = 9.462322208025613

	* uni04CD (U+04CD): B<<116.0,127.0>-<113.0,202.0>-<114.0,329.0>>/B<<114.0,329.0>-<96.0,233.0>-<83.5,170.0>> = 10.168516729367832

	* uni04CD (U+04CD): B<<334.5,169.5>-<353.0,243.0>-<381.0,351.0>>/B<<381.0,351.0>-<364.0,310.0>-<349.0,275.5>> = 7.986110522356772

	* uni04CE (U+04CE): B<<349.0,76.5>-<357.0,119.0>-<375.0,195.0>>/B<<375.0,195.0>-<330.0,102.0>-<292.5,44.5>> = 12.4964607122985

	* uni04F4 (U+04F4): B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>>/L<<496.0,632.0>--<495.0,626.0>> = 8.972626614896358

	* uni04F4 (U+04F4): L<<496.0,632.0>--<495.0,626.0>>/B<<495.0,626.0>-<495.0,629.0>-<496.0,632.0>> = 9.462322208025613

	* uni04F8 (U+04F8): B<<464.0,599.0>-<491.0,637.0>-<507.0,697.0>>/L<<507.0,697.0>--<503.0,678.0>> = 3.0427591385095694

	* uni04F8 (U+04F8): L<<507.0,697.0>--<503.0,678.0>>/B<<503.0,678.0>-<508.0,703.0>-<514.0,727.0>> = 0.5787255656073457

	* uni04F9 (U+04F9): B<<-4.0,103.5>-<-18.0,159.0>-<-4.0,232.0>>/B<<-4.0,232.0>-<-4.0,231.0>-<-1.0,243.5>> = 10.856413348062235

	* uni0526 (U+0526): B<<47.0,101.0>-<47.0,98.0>-<46.0,95.0>>/L<<46.0,95.0>--<47.0,101.0>> = 8.972626614896358 

	* uni0526 (U+0526): L<<46.0,95.0>--<47.0,101.0>>/B<<47.0,101.0>-<47.0,98.0>-<46.0,95.0>> = 9.462322208025613 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] VictorMono-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoAscender is 1000 when it should be 1100 [code: bad-typo-ascender]
* 🔥 **FAIL** Victor Mono Regular: OS/2 sTypoDescender is -227 when it should be -250 [code: bad-typo-descender]
* 🔥 **FAIL** Victor Mono Regular: hhea Ascender is 1000 when it should be 1100 [code: bad-hhea-ascender]
* 🔥 **FAIL** Victor Mono Regular: hhea Descender is -227 when it should be -250 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ j̦̀ j̦́ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̉ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈ [code: soft-dotted]
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
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* .notdef
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Alpha
	* Alphatonos
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* Beta
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* Chi
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Epsilon
	* Epsilontonos
	* Eta
	* Etatonos
	* Eth
	* Euro
	* F
	* G
	* Gamma
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Iota
	* Iotadieresis
	* Iotatonos
	* Itilde
	* J
	* Jcircumflex
	* K
	* Kappa
	* L
	* Lacute
	* Lambda
	* Lcaron
	* Lslash
	* M
	* Mu
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* Nu
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohorn
	* Ohungarumlaut
	* Omacron
	* Omegatonos
	* Omicron
	* Omicrontonos
	* Oslash
	* Otilde
	* P
	* Phi
	* Pi
	* Psi
	* Q
	* Q_j.liga
	* R
	* Racute
	* Rcaron
	* Rho
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* Sigma
	* T
	* Tau
	* Tbar
	* Tcaron
	* Theta
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhorn
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Upsilon
	* Upsilondieresis
	* Upsilontonos
	* Uring
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Xi
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* Zeta
	* a
	* a.ss01
	* a_e.liga
	* a_l.liga
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* agrave
	* alpha
	* alphatonos
	* amacron
	* ampersand
	* ampersand_ampersand.liga
	* aogonek
	* approxequal
	* aring
	* arrowboth
	* arrowdblboth
	* arrowdbldown
	* arrowdblleft
	* arrowdblright
	* arrowdblup
	* arrowdown
	* arrowleft
	* arrowright
	* arrowup
	* arrowupdn
	* arrowupdnbse
	* asciitilde_asciitilde.liga
	* asciitilde_asciitilde_greater.liga
	* asciitilde_at.liga
	* asciitilde_greater.liga
	* asciitilde_hyphen.liga
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* backslash_slash.liga
	* bar
	* bar_equal.liga
	* bar_equal_greater.liga
	* bar_greater.liga
	* bar_hyphen.liga
	* bar_hyphen_greater.liga
	* bar_hyphen_less.liga
	* beta
	* block
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* brokenbar
	* bullet
	* c
	* cacute
	* carriagereturn
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* chi
	* circle
	* colon_colon.liga
	* colon_colon_less.liga
	* colon_equal.liga
	* colon_greater.liga
	* colon_less.liga
	* copyright
	* currency
	* d
	* d_e.liga
	* d_l.liga
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* delta
	* divide
	* dkshade
	* dnblock
	* dollar
	* dollar_greater.liga
	* dotlessi
	* e
	* e_e.liga
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* element
	* ellipsis
	* emacron
	* emptyset
	* eng
	* eogonek
	* epsilon
	* epsilontonos
	* equal
	* equal_asciitilde.liga
	* equal_colon_equal.liga
	* equal_equal.liga
	* equal_equal_equal.liga
	* equal_equal_greater.liga
	* equal_exclam_equal.liga
	* equal_greater.liga
	* equal_greater_equal.liga
	* equal_greater_greater.liga
	* equal_less_equal.liga
	* equal_less_less.liga
	* equal_slash_equal.liga
	* equivalence
	* eta
	* etatonos
	* eth
	* exclam
	* exclam_asciitilde.liga
	* exclam_equal.liga
	* exclam_equal_equal.liga
	* exclamdbl
	* exclamdown
	* existential
	* f
	* f_f.liga
	* f_f_i.liga
	* f_i.liga
	* f_j.liga
	* f_r.liga
	* f_s.liga
	* f_y.liga
	* female
	* filledbox
	* filledrect
	* five
	* five.dnom
	* five.numr
	* fiveeighths
	* florin
	* four
	* four.dnom
	* four.numr
	* fraction
	* franc
	* g
	* gamma
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* gradient
	* greater
	* greater_colon.liga
	* greater_equal.liga
	* greater_equal_greater.liga
	* greater_greater_equal.liga
	* greater_greater_hyphen.liga
	* greater_hyphen.liga
	* greater_hyphen_bar.liga
	* greater_hyphen_greater.liga
	* greaterequal
	* guillemotleft
	* guillemotright
	* h
	* h_e.liga
	* h_l.liga
	* hbar
	* hcircumflex
	* hyphen_asciitilde.liga
	* hyphen_bar.liga
	* hyphen_greater.liga
	* hyphen_greater_greater.liga
	* hyphen_hyphen_greater.liga
	* hyphen_less.liga
	* hyphen_less_less.liga
	* i
	* i.loclTRK
	* i_e.liga
	* i_l.liga
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* intersection
	* invbullet
	* invcircle
	* iogonek
	* iota
	* iotadieresis
	* iotadieresistonos
	* iotatonos
	* itilde
	* j
	* jcircumflex
	* k
	* k_e.liga
	* k_l.liga
	* kappa
	* l
	* l_e.liga
	* l_l.liga
	* lacute
	* lambda
	* lcaron
	* less
	* less_asciitilde.liga
	* less_asciitilde_asciitilde.liga
	* less_asciitilde_greater.liga
	* less_bar.liga
	* less_bar_greater.liga
	* less_colon.liga
	* less_dollar.liga
	* less_dollar_greater.liga
	* less_equal.liga
	* less_equal_equal.liga
	* less_equal_greater.liga
	* less_equal_less.liga
	* less_exclam_hyphen_hyphen.liga
	* less_greater.liga
	* less_hyphen.liga
	* less_hyphen_bar.liga
	* less_hyphen_greater.liga
	* less_hyphen_hyphen.liga
	* less_hyphen_less.liga
	* less_less_equal.liga
	* less_less_hyphen.liga
	* less_plus.liga
	* less_plus_greater.liga
	* less_slash.liga
	* less_slash_greater.liga
	* lessequal
	* lfblock
	* lira
	* logicaland
	* logicalnot
	* logicalor
	* lozenge
	* lslash
	* ltshade
	* m
	* m_e.liga
	* m_l.liga
	* male
	* multiply
	* n
	* n_e.liga
	* n_l.liga
	* nacute
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.ss07
	* notelement
	* notequal
	* notsubset
	* ntilde
	* nu
	* numbersign
	* numbersign_numbersign.liga
	* numbersign_numbersign_numbersign.liga
	* numbersign_numbersign_numbersign_numbersign.liga
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohorn
	* ohungarumlaut
	* omacron
	* omega
	* omegatonos
	* omicron
	* omicrontonos
	* one
	* one.dnom
	* one.numr
	* oneeighth
	* onehalf
	* onequarter
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* p
	* paragraph
	* parenleft
	* parenright
	* partialdiff
	* percent
	* period_equal.liga
	* period_hyphen.liga
	* perthousand
	* phi
	* pi
	* plus
	* plus_greater.liga
	* plus_plus.liga
	* plus_plus_plus.liga
	* plusminus
	* product
	* propersubset
	* propersuperset
	* psi
	* q
	* question
	* question_equal.liga
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* r_e.liga
	* r_l.liga
	* racute
	* radical
	* rcaron
	* reflexsubset
	* reflexsuperset
	* registered
	* rho
	* ring
	* rtblock
	* s
	* s_e.liga
	* s_l.liga
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* semicolon_semicolon.liga
	* seven
	* seven.dnom
	* seven.numr
	* seven.ss06
	* seveneighths
	* shade
	* sigma
	* six
	* six.dnom
	* six.numr
	* six.ss07
	* slash
	* slash_backslash.liga
	* slash_equal.liga
	* slash_equal_equal.liga
	* slash_greater.liga
	* sterling
	* summation
	* t
	* t_e.liga
	* t_l.liga
	* t_t.liga
	* tau
	* tbar
	* tcaron
	* theta
	* thorn
	* three
	* three.dnom
	* three.numr
	* threeeighths
	* threequarters
	* trademark
	* triagdn
	* triaglf
	* triagrt
	* triagup
	* two
	* two.dnom
	* two.numr
	* u
	* u_e.liga
	* u_l.liga
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhorn
	* uhungarumlaut
	* umacron
	* underscore_underscore.liga
	* uni00B2
	* uni00B3
	* uni00B5
	* uni00B9
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0162
	* uni0163
	* uni01CD
	* uni01CE
	* uni01CF
	* uni01D0
	* uni01D1
	* uni01D2
	* uni01D3
	* uni01D4
	* uni01D5
	* uni01D6
	* uni01D7
	* uni01D8
	* uni01D9
	* uni01DA
	* uni01DB
	* uni01DC
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni03020303
	* uni03020303.case
	* uni03020309
	* uni03020309.case
	* uni03060303
	* uni03060303.case
	* uni03060309
	* uni03060309.case
	* uni030A
	* uni030A.case
	* uni037E
	* uni0394
	* uni03A9
	* uni03BC
	* uni03C2
	* uni03CF
	* uni03D7
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0414.loclBGR
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041B.loclBGR
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0424.loclBGR
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0431.loclSRB
	* uni0432
	* uni0432.loclBGR
	* uni0433
	* uni0433.loclBGR
	* uni0433.loclSRB
	* uni0434
	* uni0434.loclBGR
	* uni0434.loclSRB
	* uni0435
	* uni0436
	* uni0436.loclBGR
	* uni0437
	* uni0437.loclBGR
	* uni0438
	* uni0438.loclBGR
	* uni0439
	* uni0439.loclBGR
	* uni043A
	* uni043A.loclBGR
	* uni043B
	* uni043B.loclBGR
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni043F.loclBGR
	* uni043F.loclSRB
	* uni0440
	* uni0441
	* uni0442
	* uni0442.loclBGR
	* uni0442.loclSRB
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0446.loclBGR
	* uni0447
	* uni0448
	* uni0448.loclBGR
	* uni0448.loclSRB
	* uni0449
	* uni0449.loclBGR
	* uni044A
	* uni044A.loclBGR
	* uni044B
	* uni044C
	* uni044C.loclBGR
	* uni044D
	* uni044E
	* uni044E.loclBGR
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045D.loclBGR
	* uni045E
	* uni0462
	* uni0463
	* uni0464
	* uni0465
	* uni0466
	* uni0467
	* uni046A
	* uni046B
	* uni0470
	* uni0471
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni048E
	* uni048F
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni049E
	* uni049F
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04A6
	* uni04A7
	* uni04A8
	* uni04A9
	* uni04AA
	* uni04AB
	* uni04AC
	* uni04AD
	* uni04AE
	* uni04AF
	* uni04B0
	* uni04B1
	* uni04B2
	* uni04B3
	* uni04B4
	* uni04B5
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04BC
	* uni04BD
	* uni04BE
	* uni04BF
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04C3
	* uni04C4
	* uni04C5
	* uni04C6
	* uni04C7
	* uni04C8
	* uni04C9
	* uni04CA
	* uni04CB
	* uni04CC
	* uni04CD
	* uni04CE
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DA
	* uni04DB
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E0
	* uni04E1
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EA
	* uni04EB
	* uni04EC
	* uni04ED
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni04FC
	* uni04FD
	* uni0500
	* uni0501
	* uni0510
	* uni0511
	* uni0512
	* uni0513
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni0526
	* uni0527
	* uni1E9E
	* uni1EA0
	* uni1EA1
	* uni1EA2
	* uni1EA3
	* uni1EA4
	* uni1EA5
	* uni1EA6
	* uni1EA7
	* uni1EA8
	* uni1EA9
	* uni1EAA
	* uni1EAB
	* uni1EAC
	* uni1EAD
	* uni1EAE
	* uni1EAF
	* uni1EB0
	* uni1EB1
	* uni1EB2
	* uni1EB3
	* uni1EB4
	* uni1EB5
	* uni1EB6
	* uni1EB7
	* uni1EB8
	* uni1EB9
	* uni1EBA
	* uni1EBB
	* uni1EBC
	* uni1EBD
	* uni1EBE
	* uni1EBF
	* uni1EC0
	* uni1EC1
	* uni1EC2
	* uni1EC3
	* uni1EC4
	* uni1EC5
	* uni1EC6
	* uni1EC7
	* uni1EC8
	* uni1EC9
	* uni1ECA
	* uni1ECB
	* uni1ECC
	* uni1ECD
	* uni1ECE
	* uni1ECF
	* uni1ED0
	* uni1ED1
	* uni1ED2
	* uni1ED3
	* uni1ED4
	* uni1ED5
	* uni1ED6
	* uni1ED7
	* uni1ED8
	* uni1ED9
	* uni1EDA
	* uni1EDB
	* uni1EDC
	* uni1EDD
	* uni1EDE
	* uni1EDF
	* uni1EE0
	* uni1EE1
	* uni1EE2
	* uni1EE3
	* uni1EE4
	* uni1EE5
	* uni1EE6
	* uni1EE7
	* uni1EE8
	* uni1EE9
	* uni1EEA
	* uni1EEB
	* uni1EEC
	* uni1EED
	* uni1EEE
	* uni1EEF
	* uni1EF0
	* uni1EF1
	* uni1EF4
	* uni1EF5
	* uni1EF6
	* uni1EF7
	* uni1EF8
	* uni1EF9
	* uni2070
	* uni2071
	* uni2074
	* uni2075
	* uni2076
	* uni2077
	* uni2078
	* uni2079
	* uni207A
	* uni207D
	* uni207E
	* uni207F
	* uni2080
	* uni2081
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2086
	* uni2087
	* uni2088
	* uni2089
	* uni208A
	* uni208D
	* uni208E
	* uni2090
	* uni2091
	* uni2092
	* uni2093
	* uni2094
	* uni2095
	* uni2096
	* uni2097
	* uni2098
	* uni2099
	* uni209A
	* uni209B
	* uni209C
	* uni2150
	* uni2151
	* uni2152
	* uni2153
	* uni2154
	* uni2155
	* uni2156
	* uni2157
	* uni2158
	* uni2159
	* uni215A
	* uni215F
	* uni2189
	* uni2196
	* uni2197
	* uni2198
	* uni2199
	* uni219A
	* uni219B
	* uni219C
	* uni219D
	* uni219E
	* uni219F
	* uni21A0
	* uni21A1
	* uni21A2
	* uni21A3
	* uni21A4
	* uni21A5
	* uni21A6
	* uni21A7
	* uni21A9
	* uni21AA
	* uni21AB
	* uni21AC
	* uni21AD
	* uni21AE
	* uni21AF
	* uni21B0
	* uni21B1
	* uni21B2
	* uni21B3
	* uni21B4
	* uni21B9
	* uni21BA
	* uni21BB
	* uni21BC
	* uni21BD
	* uni21BE
	* uni21BF
	* uni21C0
	* uni21C1
	* uni21C2
	* uni21C3
	* uni21C4
	* uni21C5
	* uni21C6
	* uni21C7
	* uni21C8
	* uni21C9
	* uni21CA
	* uni21CB
	* uni21CC
	* uni21CD
	* uni21CE
	* uni21CF
	* uni21D5
	* uni21D6
	* uni21D7
	* uni21D8
	* uni21D9
	* uni21DA
	* uni21DB
	* uni21DC
	* uni21DD
	* uni21DE
	* uni21DF
	* uni21E0
	* uni21E1
	* uni21E2
	* uni21E3
	* uni21E4
	* uni21E5
	* uni21E6
	* uni21E7
	* uni21E8
	* uni21E9
	* uni21EA
	* uni21F3
	* uni21F4
	* uni21F5
	* uni21F6
	* uni21F7
	* uni21F8
	* uni21F9
	* uni21FA
	* uni21FB
	* uni21FC
	* uni21FD
	* uni21FE
	* uni21FF
	* uni2285
	* uni2308
	* uni2309
	* uni230A
	* uni230B
	* uni2500
	* uni2501
	* uni2502
	* uni2503
	* uni2505
	* uni2506
	* uni2507
	* uni2509
	* uni250A
	* uni250B
	* uni250C
	* uni250D
	* uni250E
	* uni250F
	* uni2510
	* uni2511
	* uni2512
	* uni2513
	* uni2514
	* uni2515
	* uni2516
	* uni2517
	* uni2518
	* uni2519
	* uni251A
	* uni251B
	* uni251C
	* uni251D
	* uni251E
	* uni251F
	* uni2520
	* uni2521
	* uni2522
	* uni2523
	* uni2524
	* uni2525
	* uni2526
	* uni2527
	* uni2528
	* uni2529
	* uni252A
	* uni252B
	* uni252C
	* uni252D
	* uni252E
	* uni252F
	* uni2530
	* uni2531
	* uni2532
	* uni2533
	* uni2534
	* uni2535
	* uni2536
	* uni2537
	* uni2538
	* uni2539
	* uni253A
	* uni253B
	* uni253C
	* uni253D
	* uni253E
	* uni253F
	* uni2540
	* uni2541
	* uni2542
	* uni2543
	* uni2544
	* uni2545
	* uni2546
	* uni2547
	* uni2548
	* uni2549
	* uni254A
	* uni254B
	* uni254E
	* uni254F
	* uni2550
	* uni2551
	* uni2552
	* uni2553
	* uni2554
	* uni2555
	* uni2556
	* uni2557
	* uni2558
	* uni2559
	* uni255A
	* uni255B
	* uni255C
	* uni255D
	* uni255E
	* uni255F
	* uni2560
	* uni2561
	* uni2562
	* uni2563
	* uni2564
	* uni2565
	* uni2566
	* uni2567
	* uni2568
	* uni2569
	* uni256A
	* uni256B
	* uni256C
	* uni256D
	* uni256E
	* uni256F
	* uni2570
	* uni2571
	* uni2572
	* uni2573
	* uni2575
	* uni2577
	* uni2578
	* uni2579
	* uni257A
	* uni257B
	* uni257C
	* uni257D
	* uni257E
	* uni257F
	* uni2581
	* uni2582
	* uni2583
	* uni2585
	* uni2586
	* uni2587
	* uni2589
	* uni258A
	* uni258B
	* uni258D
	* uni258E
	* uni258F
	* uni2594
	* uni2595
	* uni2596
	* uni2597
	* uni2598
	* uni2599
	* uni259A
	* uni259B
	* uni259C
	* uni259D
	* uni259E
	* uni259F
	* uni25A1
	* uni25A2
	* uni25A3
	* uni25A4
	* uni25A5
	* uni25A6
	* uni25A7
	* uni25A8
	* uni25A9
	* uni25AA
	* uni25AB
	* uni25AD
	* uni25AE
	* uni25AF
	* uni25B0
	* uni25B1
	* uni25B3
	* uni25B4
	* uni25B6
	* uni25B7
	* uni25B8
	* uni25BB
	* uni25BD
	* uni25BE
	* uni25C0
	* uni25C1
	* uni25C2
	* uni25C5
	* uni25C6
	* uni25C7
	* uni25C8
	* uni25C9
	* uni25CD
	* uni25CE
	* uni25CF
	* uni25D0
	* uni25D1
	* uni25D2
	* uni25D3
	* uni25D4
	* uni25D5
	* uni25D6
	* uni25D7
	* uni25DA
	* uni25DB
	* uni25E0
	* uni25E1
	* uni25E2
	* uni25E3
	* uni25E4
	* uni25E5
	* uni25E7
	* uni25E8
	* uni25E9
	* uni25EA
	* uni25EB
	* uni25EC
	* uni25ED
	* uni25EE
	* uni25EF
	* uni25F0
	* uni25F1
	* uni25F2
	* uni25F3
	* uni25F4
	* uni25F5
	* uni25F6
	* uni25F7
	* uni25F8
	* uni25F9
	* uni25FA
	* uni25FB
	* uni25FC
	* uni25FD
	* uni25FE
	* uni25FF
	* uni2716
	* uni2756
	* uni27E8
	* uni27E9
	* uni2B16
	* uni2B17
	* uni2B18
	* uni2B19
	* uni2B1A
	* uniA65E
	* uniA65F
	* uniE0A0
	* uniE0A1
	* uniE0A2
	* uniE0B0
	* uniE0B1
	* uniE0B2
	* uniE0B3
	* uniEE00
	* uniEE01
	* uniEE02
	* uniEE03
	* uniEE04
	* uniEE05
	* uniEE07
	* uniEE08
	* uniEE09
	* uniEE0A
	* uniEE0B
	* union
	* universal
	* uogonek
	* upblock
	* upsilon
	* upsilondieresis
	* upsilondieresistonos
	* upsilontonos
	* uring
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* xi
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.ss02
	* zero.ss03
	* zero.ss04
	* zero.ss05 and zeta
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss05 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss08 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1458 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 1 glyphs (0.07%) have a different width. You should check the widths of: ['colon_colon_less.liga'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Q (U+0051): L<<274.0,49.0>--<277.0,49.0>> -> L<<277.0,49.0>--<277.0,49.0>>

	* one (U+0031): L<<338.0,730.0>--<369.0,727.0>> -> L<<369.0,727.0>--<397.0,727.0>>

	* sigma (U+03C3): L<<335.0,575.0>--<335.0,575.0>> -> L<<335.0,575.0>--<581.0,575.0>>

	* uni0409 (U+0409): L<<245.0,730.0>--<276.0,727.0>> -> L<<276.0,727.0>--<435.0,727.0>>

	* uni0459 (U+0459): L<<210.0,564.0>--<237.0,562.0>> -> L<<237.0,562.0>--<400.0,562.0>>

	* uni0490 (U+0490): L<<603.0,847.0>--<578.0,727.0>> -> L<<578.0,727.0>--<568.0,672.0>>

	* uni0491 (U+0491): L<<571.0,681.0>--<546.0,562.0>> -> L<<546.0,562.0>--<534.0,507.0>>

	* uni0497 (U+0497): L<<511.0,96.0>--<510.0,92.0>> -> L<<510.0,92.0>--<467.0,-107.0>>

	* uni04A4 (U+04A4): L<<505.0,740.0>--<510.0,740.0>> -> L<<510.0,740.0>--<510.0,740.0>>

	* uni04A4 (U+04A4): L<<510.0,740.0>--<510.0,740.0>> -> L<<510.0,740.0>--<690.0,740.0>>

	* uni04C3 (U+04C3): L<<212.0,357.0>--<210.0,357.0>> -> L<<210.0,357.0>--<141.0,357.0>>

	* uni2152 (U+2152): L<<179.0,775.0>--<204.0,773.0>> -> L<<204.0,773.0>--<234.0,773.0>>

	* uni21B4 (U+21B4): L<<501.0,727.0>--<501.0,727.0>> -> L<<501.0,727.0>--<507.0,727.0>>

	* uni21B4 (U+21B4): L<<96.0,727.0>--<501.0,727.0>> -> L<<501.0,727.0>--<501.0,727.0>>

	* uni21C8 (U+21C8): L<<317.0,489.0>--<317.0,489.0>> -> L<<317.0,489.0>--<317.0,489.0>>

	* uni21CA (U+21CA): L<<264.0,238.0>--<264.0,238.0>> -> L<<264.0,238.0>--<264.0,238.0>>

	* uni21F3 (U+21F3): L<<144.0,294.0>--<159.0,364.0>> -> L<<159.0,364.0>--<175.0,434.0>>

	* uni21F3 (U+21F3): L<<245.0,489.0>--<219.0,364.0>> -> L<<219.0,364.0>--<192.0,238.0>>

	* uni21F3 (U+21F3): L<<337.0,238.0>--<363.0,364.0>> -> L<<363.0,364.0>--<389.0,489.0>>

	* uni21F3 (U+21F3): L<<438.0,434.0>--<422.0,364.0>> -> L<<422.0,364.0>--<407.0,294.0>>

	* uni21F6 (U+21F6): L<<281.0,241.0>--<309.0,260.0>> -> L<<309.0,260.0>--<339.0,281.0>>

	* uni25C1 (U+25C1): L<<470.0,94.0>--<415.0,127.0>> -> L<<415.0,127.0>--<70.0,336.0>>

	* uni25C3 (U+25C3): L<<388.0,193.0>--<344.0,219.0>> -> L<<344.0,219.0>--<152.0,336.0>>

	* uni25C5 (U+25C5): L<<470.0,172.0>--<416.0,195.0>> -> L<<416.0,195.0>--<65.0,336.0>>

	* uniE0A1 (U+E0A1): L<<257.0,97.0>--<263.0,-32.0>> -> L<<263.0,-32.0>--<263.0,-123.0>>

	* uniE0A1 (U+E0A1): L<<358.0,61.0>--<351.0,206.0>> -> L<<351.0,206.0>--<351.0,282.0>> 

	* xi (U+03BE): L<<569.0,727.0>--<563.0,697.0>> -> L<<563.0,697.0>--<560.0,673.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* aacute (U+00E1): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* abreve (U+0103): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* acircumflex (U+00E2): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* adieresis (U+00E4): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* agrave (U+00E0): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* amacron (U+0101): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* aogonek (U+0105): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* aring (U+00E5): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* atilde (U+00E3): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* eta (U+03B7): L<<135.0,449.0>--<153.0,463.0>>/L<<153.0,463.0>--<136.0,452.0>> = 4.969740728110216

	* etatonos (U+03AE): L<<135.0,449.0>--<153.0,463.0>>/L<<153.0,463.0>--<136.0,452.0>> = 4.969740728110216

	* section (U+00A7): L<<230.0,102.0>--<230.0,102.0>>/B<<230.0,102.0>-<136.0,105.0>-<105.0,152.0>> = 1.8279682443049605

	* section (U+00A7): L<<308.0,402.0>--<308.0,402.0>>/B<<308.0,402.0>-<235.0,403.0>-<200.0,373.5>> = 0.7848246029917126

	* uni01CE (U+01CE): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni0411 (U+0411): B<<71.5,79.5>-<71.0,64.0>-<71.0,56.0>>/B<<71.0,56.0>-<72.0,61.0>-<74.0,67.5>> = 11.309932474020195

	* uni0412 (U+0412): B<<76.5,101.5>-<75.0,71.0>-<76.0,66.0>>/B<<76.0,66.0>-<75.0,76.0>-<98.5,192.0>> = 5.599339336520484

	* uni0412 (U+0412): B<<98.5,192.0>-<122.0,308.0>-<166.0,509.0>>/B<<166.0,509.0>-<142.0,456.0>-<125.5,397.5>> = 12.01486487955383

	* uni041C (U+041C): B<<155.5,229.5>-<156.0,319.0>-<158.0,450.0>>/B<<158.0,450.0>-<131.0,321.0>-<111.0,232.0>> = 10.946811569485886

	* uni041C (U+041C): B<<402.0,196.5>-<426.0,306.0>-<466.0,487.0>>/B<<466.0,487.0>-<427.0,395.0>-<397.5,324.5>> = 10.510965410274828

	* uni0430 (U+0430): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni0436 (U+0436): L<<357.0,562.0>--<272.0,179.0>>/L<<272.0,179.0>--<360.0,355.0>> = 14.05208415856879

	* uni043C (U+043C): B<<137.5,149.5>-<131.0,209.0>-<127.0,304.0>>/B<<127.0,304.0>-<106.0,203.0>-<92.0,141.0>> = 14.15666317189914

	* uni043C (U+043C): B<<385.0,135.0>-<399.0,202.0>-<424.0,317.0>>/B<<424.0,317.0>-<382.0,225.0>-<344.0,150.0>> = 12.27295474868539

	* uni0495 (U+0495): B<<142.0,202.5>-<123.0,169.0>-<111.0,112.0>>/L<<111.0,112.0>--<129.0,201.0>> = 0.4549767742003321

	* uni0495 (U+0495): L<<111.0,112.0>--<129.0,201.0>>/L<<129.0,201.0>--<86.0,0.0>> = 0.6416073177664681

	* uni0497 (U+0497): L<<357.0,562.0>--<272.0,179.0>>/L<<272.0,179.0>--<360.0,355.0>> = 14.05208415856879

	* uni049C (U+049C): B<<103.5,380.5>-<131.0,503.0>-<170.0,682.0>>/B<<170.0,682.0>-<170.0,681.0>-<169.0,683.0>> = 12.291348762866589

	* uni04A6 (U+04A6): B<<333.5,358.5>-<304.0,325.0>-<286.0,239.0>>/L<<286.0,239.0>--<289.0,256.0>> = 1.8135085391658403

	* uni04A6 (U+04A6): L<<286.0,239.0>--<289.0,256.0>>/L<<289.0,256.0>--<235.0,0.0>> = 1.903235630530334

	* uni04C2 (U+04C2): L<<357.0,562.0>--<272.0,179.0>>/L<<272.0,179.0>--<360.0,355.0>> = 14.05208415856879

	* uni04CD (U+04CD): B<<138.0,229.5>-<138.0,319.0>-<140.0,450.0>>/B<<140.0,450.0>-<113.0,321.0>-<93.5,232.0>> = 10.946811569485886

	* uni04CD (U+04CD): B<<388.5,216.0>-<412.0,322.0>-<449.0,487.0>>/B<<449.0,487.0>-<409.0,395.0>-<379.5,324.5>> = 10.859503235321993

	* uni04CE (U+04CE): B<<137.5,149.5>-<131.0,209.0>-<127.0,304.0>>/B<<127.0,304.0>-<106.0,203.0>-<92.0,141.0>> = 14.15666317189914

	* uni04CE (U+04CE): B<<387.5,148.0>-<401.0,212.0>-<424.0,317.0>>/B<<424.0,317.0>-<382.0,225.0>-<344.0,150.0>> = 12.182368611494265

	* uni04D1 (U+04D1): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni04D3 (U+04D3): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni04DD (U+04DD): L<<357.0,562.0>--<272.0,179.0>>/L<<272.0,179.0>--<360.0,355.0>> = 14.05208415856879

	* uni1EA1 (U+1EA1): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EA3 (U+1EA3): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EA5 (U+1EA5): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EA7 (U+1EA7): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EA9 (U+1EA9): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EAB (U+1EAB): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EAD (U+1EAD): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EAF (U+1EAF): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EB1 (U+1EB1): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EB3 (U+1EB3): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883

	* uni1EB5 (U+1EB5): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883 

	* uni1EB7 (U+1EB7): B<<324.0,66.5>-<325.0,78.0>-<328.0,84.0>>/B<<328.0,84.0>-<302.0,40.0>-<262.0,13.5>> = 4.014175695410883 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 42 | 174 | 1654 | 85 | 1268 | 0 |
| 0% | 1% | 5% | 51% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
