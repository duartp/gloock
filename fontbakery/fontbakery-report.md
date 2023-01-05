## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[9] Gloock-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


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

	- And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- two.onum

	- one.onum

	- zero.onum

	- four.onum

	- caron.alt

	- five.onum

	- nine.onum

	- seven.onum

	- eight.onum

	- six.onum 

	- And 3 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3 

	- And 3 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E3F (U+0E3F): L<<299.0,33.0>--<296.0,33.0>> -> L<<296.0,33.0>--<30.0,33.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* B (U+0042): B<<513.5,482.0>-<464.0,440.0>-<384.0,430.0>>/B<<384.0,430.0>-<458.0,426.0>-<513.5,400.5>> = 10.21907440781888

	* eight (U+0038): B<<495.0,528.5>-<444.0,491.0>-<357.0,483.0>>/B<<357.0,483.0>-<427.0,475.0>-<478.0,442.0>> = 11.7736045029192

	* eight (U+0038): B<<96.0,404.0>-<157.0,471.0>-<263.0,483.0>>/B<<263.0,483.0>-<176.0,491.0>-<125.0,529.0>> = 11.712619129980897

	* uni0E3F (U+0E3F): B<<469.5,446.5>-<428.0,410.0>-<358.0,401.0>>/B<<358.0,401.0>-<454.0,397.0>-<512.0,350.5>> = 9.712350690558281

	* uni2078 (U+2078): B<<288.0,634.5>-<260.0,614.0>-<212.0,609.0>>/B<<212.0,609.0>-<270.0,602.0>-<303.5,565.5>> = 12.828586684610446

	* uni2078 (U+2078): B<<68.5,565.5>-<102.0,602.0>-<160.0,609.0>>/B<<160.0,609.0>-<112.0,614.0>-<84.0,634.5>> = 12.828586684610446

	* uni2088 (U+2088): B<<288.0,154.5>-<260.0,134.0>-<212.0,129.0>>/B<<212.0,129.0>-<270.0,122.0>-<303.5,85.5>> = 12.828586684610446

	* uni2088 (U+2088): B<<68.5,85.5>-<102.0,122.0>-<160.0,129.0>>/B<<160.0,129.0>-<112.0,134.0>-<84.0,154.5>> = 12.828586684610446 

	* And uni20BF (U+20BF): B<<513.5,482.0>-<464.0,440.0>-<384.0,430.0>>/B<<384.0,430.0>-<458.0,426.0>-<513.5,400.5>> = 10.21907440781888 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* a (U+0061): L<<330.0,95.0>--<331.0,298.0>>

	* aacute (U+00E1): L<<330.0,95.0>--<331.0,298.0>>

	* abreve (U+0103): L<<330.0,95.0>--<331.0,298.0>>

	* acircumflex (U+00E2): L<<330.0,95.0>--<331.0,298.0>>

	* adieresis (U+00E4): L<<330.0,95.0>--<331.0,298.0>>

	* agrave (U+00E0): L<<330.0,95.0>--<331.0,298.0>>

	* amacron (U+0101): L<<330.0,95.0>--<331.0,298.0>>

	* aogonek (U+0105): L<<330.0,95.0>--<331.0,298.0>>

	* aring (U+00E5): L<<330.0,95.0>--<331.0,298.0>>

	* atilde (U+00E3): L<<330.0,95.0>--<331.0,298.0>> 

	* And 40 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 9 | 114 | 7 | 105 | 0 |
| 0% | 0% | 4% | 49% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
