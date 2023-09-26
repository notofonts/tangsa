## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[13] NotoSansTangsa-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "1.50600" while name version string (for platform 3, encoding 1) is "Version 1.505; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, syriac, tifinagh, tai-le, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `tangsa` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* actangsa
	* aqtangsa
	* awctangsa
	* awqtangsa
	* awxshorttangsa
	* awxtangsa
	* awztangsa
	* axtangsa
	* aztangsa
	* batangsa
	* catangsa
	* chatangsa
	* datangsa
	* dhatangsa
	* ectangsa
	* eighttangsa
	* eqtangsa
	* extangsa
	* eztangsa
	* fatangsa
	* fivetangsa
	* fourtangsa
	* gatangsa
	* ghatangsa
	* htatangsa
	* httatangsa
	* ictangsa
	* iqtangsa
	* ixtangsa
	* iztangsa
	* katangsa
	* khatangsa
	* mctangsa
	* mqtangsa
	* mztangsa
	* natangsa
	* ngatangsa
	* ngfinaltangsa
	* nhatangsa
	* ninetangsa
	* nyatangsa
	* octangsa
	* onetangsa
	* oqtangsa
	* oxtangsa
	* oztangsa
	* patangsa
	* phatangsa
	* ratangsa
	* satangsa
	* sixtangsa
	* tatangsa
	* thatangsa
	* threetangsa
	* tsatangsa
	* twotangsa
	* uctangsa
	* uectangsa
	* ueqtangsa
	* uexlongtangsa
	* uextangsa
	* uezshorttangsa
	* ueztangsa
	* uictangsa
	* uiqtangsa
	* uiuctangsa
	* uiuqtangsa
	* uiuxtangsa
	* uiuztangsa
	* uixtangsa
	* uiztangsa
	* uqtangsa
	* uxtangsa
	* uztangsa
	* vctangsa
	* vqtangsa
	* vxtangsa
	* vztangsa
	* xatangsa
	* yatangsa
	* zatangsa and zerotangsa
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=236.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=343.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=440.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=545.0,Y=713.0 (should be at cap-height 714?)

	* six (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=543.0,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?)

	* m (U+006D): X=627.5,Y=537.0 (should be at x-height 536?)

	* n (U+006E): X=291.5,Y=537.0 (should be at x-height 536?)

	* sterling (U+00A3): X=444.5,Y=712.5 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=758.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=394.5,Y=-0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=432.5,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=432.5,Y=-0.5 (should be at baseline 0?)

	* abreve (U+0103): X=249.0,Y=713.5 (should be at cap-height 714?)

	* abreve (U+0103): X=348.5,Y=714.5 (should be at cap-height 714?)

	* Cacute (U+0106): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cacute (U+0107): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=394.5,Y=-0.5 (should be at baseline 0?)

	* emacron (U+0113): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=432.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gbreve (U+011F): X=555.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=261.0,Y=713.5 (should be at cap-height 714?)

	* gbreve (U+011F): X=360.5,Y=714.5 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gdotaccent (U+0121): X=555.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=527.5,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=543.0,Y=712.0 (should be at cap-height 714?)

	* uni0123 (U+0123): X=555.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=591.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

	* ubreve (U+016D): X=276.0,Y=713.5 (should be at cap-height 714?)

	* ubreve (U+016D): X=375.5,Y=714.5 (should be at cap-height 714?)

	* breve (U+02D8): X=179.0,Y=713.5 (should be at cap-height 714?)

	* breve (U+02D8): X=278.5,Y=714.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=-50.0,Y=713.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=49.5,Y=714.5 (should be at cap-height 714?)

	* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?)

	* vztangsa (U+16A78): X=178.0,Y=715.0 (should be at cap-height 714?)

	* vqtangsa (U+16A7A): X=178.0,Y=715.0 (should be at cap-height 714?)

	* awztangsa (U+16A88): X=422.0,Y=1.5 (should be at baseline 0?)

	* awqtangsa (U+16A8A): X=154.0,Y=716.0 (should be at cap-height 714?)

	* uictangsa (U+16A8D): X=218.0,Y=0.5 (should be at baseline 0?)

	* uixtangsa (U+16A8F): X=480.0,Y=1.0 (should be at baseline 0?)

	* uiuztangsa (U+16A98): X=358.5,Y=713.5 (should be at cap-height 714?)

	* uiuctangsa (U+16A99): X=358.5,Y=713.5 (should be at cap-height 714?)

	* uiuxtangsa (U+16A9B): X=358.5,Y=713.5 (should be at cap-height 714?)

	* mztangsa (U+16A9C): X=542.0,Y=1.5 (should be at baseline 0?)

	* mztangsa (U+16A9C): X=395.5,Y=1.5 (should be at baseline 0?)

	* mqtangsa (U+16A9E): X=144.0,Y=713.0 (should be at cap-height 714?)

	* mqtangsa (U+16A9E): X=335.5,Y=715.0 (should be at cap-height 714?)

	* yatangsa (U+16AA5): X=491.0,Y=715.0 (should be at cap-height 714?)

	* thatangsa (U+16AB9): X=234.5,Y=2.0 (should be at baseline 0?)

	* fivetangsa (U+16AC5): X=78.0,Y=712.0 (should be at cap-height 714?)

	* seventangsa (U+16AC7): X=318.0,Y=716.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<228.0,134.0>--<228.0,127.0>>

	* at (U+0040) contains a short segment B<<636.0,296.0>-<635.0,286.0>-<635.0,275.5>>

	* at (U+0040) contains a short segment B<<635.0,275.5>-<635.0,265.0>-<635.0,262.0>>

	* at (U+0040) contains a short segment B<<646.5,207.5>-<658.0,194.0>-<672.0,194.0>>

	* M (U+004D) contains a short segment L<<220.0,560.0>--<216.0,560.0>>

	* M (U+004D) contains a short segment L<<465.0,168.0>--<468.0,168.0>>

	* N (U+004E) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* N (U+004E) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* Q (U+0051) contains a short segment L<<409.0,-10.0>--<398.0,-10.0>>

	* W (U+0057) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* a (U+0061) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* d (U+0064) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* m (U+006D) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* n (U+006E) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* p (U+0070) contains a short segment L<<220.0,475.0>--<227.0,475.0>>

	* r (U+0072) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* u (U+0075) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ordfeminine (U+00AA) contains a short segment L<<242.0,589.0>--<242.0,597.0>>

	* Ntilde (U+00D1) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Ntilde (U+00D1) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* agrave (U+00E0) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aacute (U+00E1) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* acircumflex (U+00E2) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* atilde (U+00E3) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* adieresis (U+00E4) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aring (U+00E5) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* ntilde (U+00F1) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* ugrave (U+00F9) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* amacron (U+0101) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* abreve (U+0103) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* aogonek (U+0105) contains a short segment L<<396.0,74.0>--<392.0,74.0>>

	* dcaron (U+010F) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<412.0,71.0>--<406.0,71.0>>

	* hbar (U+0127) contains a short segment L<<227.0,584.0>--<227.0,575.0>>

	* Nacute (U+0143) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Nacute (U+0143) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* nacute (U+0144) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* uni0145 (U+0145) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* uni0145 (U+0145) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* uni0146 (U+0146) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* Ncaron (U+0147) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Ncaron (U+0147) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* ncaron (U+0148) contains a short segment L<<212.0,476.0>--<220.0,476.0>>

	* Eng (U+014A) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* Eng (U+014A) contains a short segment L<<591.0,274.0>--<594.0,274.0>>

	* eng (U+014B) contains a short segment L<<212.0,476.0>--<221.0,476.0>>

	* racute (U+0155) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* uni0157 (U+0157) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* rcaron (U+0159) contains a short segment L<<213.0,454.0>--<220.0,454.0>>

	* umacron (U+016B) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uring (U+016F) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* uogonek (U+0173) contains a short segment L<<445.0,70.0>--<437.0,70.0>>

	* Wcircumflex (U+0174) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wgrave (U+1E80) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wacute (U+1E82) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Wdieresis (U+1E84) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>>

	* Euro (U+20AC) contains a short segment B<<237.0,378.0>-<237.0,374.0>-<236.5,367.5>>

	* Euro (U+20AC) contains a short segment B<<236.5,367.5>-<236.0,361.0>-<236.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<236.0,352.0>-<236.0,345.0>-<236.0,337.5>>

	* Euro (U+20AC) contains a short segment B<<236.0,337.5>-<236.0,330.0>-<237.0,322.0>>

	* Euro (U+20AC) contains a short segment B<<88.0,352.0>-<88.0,360.0>-<88.0,367.0>>

	* Euro (U+20AC) contains a short segment B<<88.0,367.0>-<88.0,374.0>-<89.0,378.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* oqtangsa (U+16A72) contains a short segment L<<354.0,599.0>--<354.0,599.0>>

	* aztangsa (U+16A74) contains a short segment L<<191.0,459.0>--<191.0,459.0>>

	* actangsa (U+16A75) contains a short segment B<<420.0,263.0>-<426.0,263.0>-<433.0,263.0>>

	* vctangsa (U+16A79) contains a short segment B<<467.0,263.0>-<473.0,263.0>-<480.0,263.0>>

	* eqtangsa (U+16A7E) contains a short segment B<<319.0,388.0>-<321.0,388.0>-<324.0,388.0>>

	* ictangsa (U+16A81) contains a short segment B<<300.0,579.0>-<300.0,593.0>-<288.0,602.5>>

	* ixtangsa (U+16A83) contains a short segment B<<300.0,579.0>-<300.0,593.0>-<288.0,602.5>>

	* uctangsa (U+16A85) contains a short segment B<<184.5,185.0>-<181.0,173.0>-<181.0,163.0>>

	* uqtangsa (U+16A86) contains a short segment B<<415.0,524.0>-<415.0,519.0>-<415.0,516.0>>

	* awctangsa (U+16A89) contains a short segment B<<159.0,434.0>-<159.0,439.0>-<159.0,444.0>>

	* ngfinaltangsa (U+16A90) contains a short segment L<<317.0,595.0>--<312.0,602.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<327.0,389.0>-<339.0,396.0>-<350.0,402.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<350.0,402.0>-<361.0,408.0>-<372.0,414.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<564.0,422.0>-<569.0,419.0>-<573.5,416.5>>

	* uexlongtangsa (U+16A91) contains a short segment B<<573.5,416.5>-<578.0,414.0>-<583.0,411.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<661.0,362.0>-<668.0,366.0>-<676.0,371.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<764.0,301.0>-<756.0,296.0>-<751.0,294.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<501.0,335.0>-<492.0,340.0>-<483.5,344.5>>

	* uexlongtangsa (U+16A91) contains a short segment B<<483.5,344.5>-<475.0,349.0>-<466.0,354.0>>

	* uezshorttangsa (U+16A92) contains a short segment B<<225.0,588.5>-<216.0,598.0>-<206.0,598.0>>

	* uectangsa (U+16A94) contains a short segment B<<592.0,125.5>-<601.0,116.0>-<611.0,116.0>>

	* ueqtangsa (U+16A96) contains a short segment B<<225.0,588.5>-<216.0,598.0>-<206.0,598.0>>

	* uiuqtangsa (U+16A9A) contains a short segment B<<1036.0,386.0>-<1036.0,396.0>-<1036.0,404.0>>

	* khatangsa (U+16AA1) contains a short segment B<<206.0,185.0>-<203.0,173.0>-<203.0,163.0>>

	* phatangsa (U+16AA9) contains a short segment B<<186.5,594.5>-<178.0,592.0>-<178.0,584.0>>

	* matangsa (U+16AAB) contains a short segment B<<276.0,123.0>-<279.0,123.0>-<283.0,123.0>>

	* datangsa (U+16AB1) contains a short segment B<<571.0,125.5>-<580.0,116.0>-<590.0,116.0>>

	* datangsa (U+16AB1) contains a short segment B<<217.0,588.5>-<208.0,598.0>-<198.0,598.0>>

	* catangsa (U+16AB5) contains a short segment B<<149.0,592.0>-<149.0,588.0>-<149.0,586.0>>

	* fatangsa (U+16ABB) contains a short segment L<<373.0,426.0>--<373.0,438.0>>

	* sixtangsa (U+16AC6) contains a short segment B<<192.5,167.5>-<185.0,160.0>-<185.0,151.0>>

	* ninetangsa (U+16AC9) contains a short segment B<<302.0,142.0>-<302.0,136.0>-<305.5,131.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wdieresis (U+1E84): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wgrave (U+1E80): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* aztangsa (U+16A74): L<<190.0,714.0>--<191.0,459.0>>

	* yatangsa (U+16AA5): L<<367.0,598.0>--<78.0,597.0>>

	* yatangsa (U+16AA5): L<<78.0,714.0>--<491.0,715.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansTangsa-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "1.50600" while name version string (for platform 3, encoding 1) is "Version 1.505; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, syriac, tifinagh, tai-le, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `tangsa` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* actangsa
	* awctangsa
	* awqtangsa
	* awxshorttangsa
	* axtangsa
	* batangsa
	* catangsa
	* chatangsa
	* datangsa
	* dhatangsa
	* ectangsa
	* eqtangsa
	* eztangsa
	* fatangsa
	* gatangsa
	* htatangsa
	* httatangsa
	* ictangsa
	* iqtangsa
	* ixtangsa
	* katangsa
	* mctangsa
	* mqtangsa
	* mxtangsa
	* mztangsa
	* natangsa
	* ngatangsa
	* oqtangsa
	* oxtangsa
	* patangsa
	* phatangsa
	* ratangsa
	* sixtangsa
	* tatangsa
	* thatangsa
	* threetangsa
	* tsatangsa
	* twotangsa
	* uectangsa
	* ueqtangsa
	* uextangsa
	* uezshorttangsa
	* ueztangsa
	* uictangsa
	* uiqtangsa
	* uiuctangsa
	* uiuqtangsa
	* uiuxtangsa
	* uixtangsa
	* uiztangsa
	* uqtangsa
	* uxtangsa
	* vctangsa
	* vqtangsa
	* vxtangsa
	* vztangsa
	* xatangsa
	* zatangsa and zerotangsa
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tangsa Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<179.0,99.0>--<179.0,94.0>>

	* at (U+0040) contains a short segment B<<620.0,294.0>-<619.0,278.0>-<619.0,269.5>>

	* at (U+0040) contains a short segment B<<619.0,269.5>-<619.0,261.0>-<619.0,258.0>>

	* M (U+004D) contains a short segment L<<190.0,607.0>--<186.0,607.0>>

	* M (U+004D) contains a short segment L<<454.0,141.0>--<458.0,141.0>>

	* N (U+004E) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* N (U+004E) contains a short segment L<<585.0,140.0>--<588.0,140.0>>

	* Q (U+0051) contains a short segment B<<414.0,-9.0>-<409.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<398.0,-10.0>-<393.0,-10.0>>

	* a (U+0061) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* d (U+0064) contains a short segment L<<436.0,72.0>--<431.0,72.0>>

	* m (U+006D) contains a short segment L<<182.0,467.0>--<188.0,467.0>>

	* n (U+006E) contains a short segment L<<182.0,467.0>--<188.0,467.0>>

	* p (U+0070) contains a short segment L<<184.0,467.0>--<189.0,467.0>>

	* r (U+0072) contains a short segment L<<181.0,443.0>--<185.0,443.0>>

	* u (U+0075) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* Ntilde (U+00D1) contains a short segment L<<585.0,140.0>--<588.0,140.0>>

	* agrave (U+00E0) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* aacute (U+00E1) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* acircumflex (U+00E2) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* atilde (U+00E3) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* adieresis (U+00E4) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* aring (U+00E5) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* ntilde (U+00F1) contains a short segment L<<182.0,467.0>--<188.0,467.0>>

	* ugrave (U+00F9) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* amacron (U+0101) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* abreve (U+0103) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* aogonek (U+0105) contains a short segment L<<398.0,75.0>--<394.0,75.0>>

	* dcaron (U+010F) contains a short segment L<<436.0,72.0>--<431.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<435.0,72.0>--<431.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* Nacute (U+0143) contains a short segment L<<585.0,140.0>--<588.0,140.0>>

	* nacute (U+0144) contains a short segment L<<182.0,467.0>--<188.0,467.0>>

	* uni0145 (U+0145) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* uni0145 (U+0145) contains a short segment L<<585.0,140.0>--<588.0,140.0>>

	* uni0146 (U+0146) contains a short segment L<<182.0,467.0>--<188.0,467.0>>

	* Ncaron (U+0147) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* Ncaron (U+0147) contains a short segment L<<585.0,140.0>--<588.0,140.0>>

	* ncaron (U+0148) contains a short segment L<<182.0,467.0>--<188.0,467.0>>

	* Eng (U+014A) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* Eng (U+014A) contains a short segment L<<585.0,181.0>--<588.0,181.0>>

	* eng (U+014B) contains a short segment L<<182.0,467.0>--<189.0,467.0>>

	* racute (U+0155) contains a short segment L<<181.0,443.0>--<185.0,443.0>>

	* uni0157 (U+0157) contains a short segment L<<181.0,443.0>--<185.0,443.0>>

	* rcaron (U+0159) contains a short segment L<<181.0,443.0>--<185.0,443.0>>

	* umacron (U+016B) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uring (U+016F) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<544.5,-155.5>-<557.0,-153.0>-<565.0,-151.0>>

	* uogonek (U+0173) contains a short segment L<<447.0,71.0>--<442.0,71.0>>

	* Euro (U+20AC) contains a short segment B<<199.0,352.0>-<199.0,343.0>-<199.0,333.5>>

	* Euro (U+20AC) contains a short segment B<<199.0,333.5>-<199.0,324.0>-<200.0,314.0>>

	* Euro (U+20AC) contains a short segment B<<92.0,352.0>-<92.0,362.0>-<92.5,371.5>>

	* Euro (U+20AC) contains a short segment B<<92.5,371.5>-<93.0,381.0>-<93.0,386.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* aztangsa (U+16A74) contains a short segment L<<165.0,448.0>--<166.0,448.0>>

	* axtangsa (U+16A77) contains a short segment B<<453.0,215.0>-<453.0,210.0>-<453.0,204.0>>

	* vxtangsa (U+16A7B) contains a short segment B<<515.0,215.0>-<515.0,209.0>-<515.0,204.0>>

	* eqtangsa (U+16A7E) contains a short segment B<<298.0,427.0>-<290.0,426.0>-<281.0,426.0>>

	* uztangsa (U+16A84) contains a short segment B<<563.0,499.0>-<563.0,491.0>-<563.0,483.0>>

	* awctangsa (U+16A89) contains a short segment B<<167.0,427.0>-<167.0,433.0>-<167.0,440.0>>

	* uiztangsa (U+16A8C) contains a short segment B<<477.0,688.0>-<484.0,688.0>-<490.0,688.0>>

	* uiztangsa (U+16A8C) contains a short segment B<<377.0,572.0>-<377.0,575.0>-<377.0,576.0>>

	* uictangsa (U+16A8D) contains a short segment B<<618.0,501.0>-<618.0,492.0>-<618.0,483.0>>

	* uictangsa (U+16A8D) contains a short segment B<<184.0,441.0>-<174.0,440.0>-<164.0,440.0>>

	* uiqtangsa (U+16A8E) contains a short segment B<<266.0,333.0>-<269.0,339.0>-<272.0,345.0>>

	* ngfinaltangsa (U+16A90) contains a short segment L<<366.0,630.0>--<362.0,638.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<295.0,378.0>-<299.0,381.0>-<304.0,384.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<304.0,384.0>-<316.0,391.0>-<327.5,397.5>>

	* uexlongtangsa (U+16A91) contains a short segment B<<327.5,397.5>-<339.0,404.0>-<350.0,411.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<492.0,420.0>-<502.0,414.0>-<514.0,407.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<602.0,355.0>-<607.0,358.0>-<613.0,362.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<679.0,314.0>-<673.0,310.0>-<668.0,307.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<348.0,324.0>-<342.0,320.0>-<334.0,316.0>>

	* uezshorttangsa (U+16A92) contains a short segment L<<501.0,375.0>--<498.0,379.0>>

	* ueztangsa (U+16A95) contains a short segment B<<518.0,375.0>-<516.0,379.0>-<514.0,382.0>>

	* watangsa (U+16AA6) contains a short segment B<<736.0,303.0>-<737.0,310.0>-<737.0,319.0>>

	* phatangsa (U+16AA9) contains a short segment B<<156.5,623.5>-<148.0,620.0>-<148.0,609.0>>

	* tatangsa (U+16AB0) contains a short segment L<<357.0,572.0>--<357.0,585.0>>

	* shatangsa (U+16AB4) contains a short segment B<<421.0,446.0>-<414.0,446.0>-<405.0,442.0>>

	* threetangsa (U+16AC3) contains a short segment B<<175.0,533.0>-<174.0,525.0>-<174.0,517.0>>

	* fivetangsa (U+16AC5) contains a short segment B<<293.0,438.0>-<290.0,438.0>-<286.0,438.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uezshorttangsa (U+16A92): L<<556.0,290.0>--<501.0,375.0>> -> L<<501.0,375.0>--<498.0,379.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* aztangsa (U+16A74): L<<164.0,714.0>--<165.0,448.0>>

	* eighttangsa (U+16AC8): L<<301.0,420.0>--<302.0,0.0>>

	* eztangsa (U+16A7C): L<<493.0,626.0>--<376.0,625.0>>

	* yatangsa (U+16AA5): L<<367.0,628.0>--<74.0,627.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansTangsa-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "1.50600" while name version string (for platform 3, encoding 1) is "Version 1.505; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, syriac, tifinagh, tai-le, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `tangsa` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* actangsa
	* awxshorttangsa
	* batangsa
	* catangsa
	* chatangsa
	* datangsa
	* dhatangsa
	* eqtangsa
	* eztangsa
	* httatangsa
	* ictangsa
	* ixtangsa
	* mctangsa
	* mqtangsa
	* mxtangsa
	* natangsa
	* oqtangsa
	* patangsa
	* phatangsa
	* ratangsa
	* tatangsa
	* thatangsa
	* threetangsa
	* tsatangsa
	* uectangsa
	* ueqtangsa
	* uextangsa
	* uezshorttangsa
	* ueztangsa
	* uictangsa
	* uiqtangsa
	* uiuctangsa
	* uiuqtangsa
	* uiztangsa
	* uxtangsa
	* vctangsa
	* vqtangsa
	* vxtangsa
	* vztangsa and xatangsa
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* m (U+006D) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* n (U+006E) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* p (U+0070) contains a short segment L<<169.0,463.0>--<173.0,463.0>>

	* r (U+0072) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ntilde (U+00D1) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* germandbls (U+00DF) contains a short segment B<<382.0,412.0>-<382.0,399.0>-<388.5,388.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<445.0,72.0>--<441.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Nacute (U+0143) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* nacute (U+0144) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* uni0145 (U+0145) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* uni0145 (U+0145) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* uni0146 (U+0146) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Ncaron (U+0147) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ncaron (U+0147) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* ncaron (U+0148) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Eng (U+014A) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Eng (U+014A) contains a short segment L<<582.0,142.0>--<586.0,142.0>>

	* eng (U+014B) contains a short segment L<<170.0,463.0>--<175.0,463.0>>

	* racute (U+0155) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* uni0157 (U+0157) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* rcaron (U+0159) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<539.5,-158.5>-<551.0,-156.0>-<559.0,-155.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Wcircumflex (U+0174) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wgrave (U+1E80) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wacute (U+1E82) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wdieresis (U+1E84) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Euro (U+20AC) contains a short segment B<<184.0,390.0>-<183.0,380.0>-<183.0,371.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,371.0>-<183.0,362.0>-<183.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,352.0>-<183.0,343.0>-<183.0,332.5>>

	* Euro (U+20AC) contains a short segment B<<183.0,332.5>-<183.0,322.0>-<184.0,311.0>>

	* Euro (U+20AC) contains a short segment B<<95.0,311.0>-<94.0,323.0>-<94.0,331.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,331.0>-<94.0,339.0>-<94.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,352.0>-<94.0,363.0>-<94.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,373.5>-<95.0,384.0>-<95.0,390.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* aztangsa (U+16A74) contains a short segment L<<154.0,444.0>--<155.0,444.0>>

	* uqtangsa (U+16A86) contains a short segment B<<430.0,343.0>-<430.0,340.0>-<430.0,336.0>>

	* awctangsa (U+16A89) contains a short segment B<<171.0,423.0>-<170.0,431.0>-<170.0,438.0>>

	* uiztangsa (U+16A8C) contains a short segment B<<359.0,576.0>-<359.0,579.0>-<359.0,582.0>>

	* uixtangsa (U+16A8F) contains a short segment B<<765.0,257.0>-<763.0,252.0>-<761.0,247.0>>

	* ngfinaltangsa (U+16A90) contains a short segment L<<387.0,644.0>--<383.0,653.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<285.0,374.0>-<294.0,380.0>-<305.0,387.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<305.0,387.0>-<314.0,393.0>-<323.0,398.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<323.0,398.0>-<332.0,403.0>-<341.0,409.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<462.0,419.0>-<473.0,413.0>-<485.0,406.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<577.0,352.0>-<581.0,355.0>-<586.0,358.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<644.0,319.0>-<638.0,315.0>-<633.0,312.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<396.0,372.0>-<384.0,363.0>-<371.0,354.5>>

	* uexlongtangsa (U+16A91) contains a short segment B<<371.0,354.5>-<358.0,346.0>-<345.0,338.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<345.0,338.0>-<338.0,333.0>-<331.0,328.5>>

	* uexlongtangsa (U+16A91) contains a short segment B<<331.0,328.5>-<324.0,324.0>-<317.0,320.0>>

	* uezshorttangsa (U+16A92) contains a short segment B<<497.0,369.0>-<493.0,375.0>-<489.5,380.5>>

	* uezshorttangsa (U+16A92) contains a short segment B<<489.5,380.5>-<486.0,386.0>-<483.0,392.0>>

	* ueztangsa (U+16A95) contains a short segment B<<520.0,369.0>-<516.0,375.0>-<512.0,381.5>>

	* ueztangsa (U+16A95) contains a short segment B<<512.0,381.5>-<508.0,388.0>-<504.0,394.0>>

	* watangsa (U+16AA6) contains a short segment B<<723.0,293.0>-<723.0,305.0>-<723.0,319.0>>

	* shatangsa (U+16AB4) contains a short segment B<<395.0,461.0>-<390.0,461.0>-<382.5,457.0>>

	* shatangsa (U+16AB4) contains a short segment L<<319.0,415.0>--<328.0,410.0>>

	* fivetangsa (U+16AC5) contains a short segment B<<297.0,440.0>-<288.0,440.0>-<280.0,440.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* aztangsa (U+16A74): L<<153.0,714.0>--<154.0,444.0>>

	* eighttangsa (U+16AC8): L<<285.0,432.0>--<286.0,0.0>>

	* oxtangsa (U+16A73): L<<418.0,223.0>--<417.0,104.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSansTangsa-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "1.50600" while name version string (for platform 3, encoding 1) is "Version 1.505; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** No dotted circle glyph present and font uses a complex shaper [code: missing-dotted-circle-complex]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, syriac, tifinagh, tai-le, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `tangsa` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* actangsa
	* awctangsa
	* awqtangsa
	* awxshorttangsa
	* axtangsa
	* batangsa
	* catangsa
	* chatangsa
	* datangsa
	* dhatangsa
	* ectangsa
	* eighttangsa
	* eqtangsa
	* extangsa
	* eztangsa
	* fatangsa
	* fivetangsa
	* fourtangsa
	* gatangsa
	* ghatangsa
	* htatangsa
	* httatangsa
	* ictangsa
	* iqtangsa
	* ixtangsa
	* iztangsa
	* katangsa
	* khatangsa
	* mctangsa
	* mqtangsa
	* mxtangsa
	* mztangsa
	* natangsa
	* ngatangsa
	* ngfinaltangsa
	* oqtangsa
	* oxtangsa
	* patangsa
	* phatangsa
	* ratangsa
	* satangsa
	* sixtangsa
	* tatangsa
	* thatangsa
	* threetangsa
	* tsatangsa
	* twotangsa
	* uctangsa
	* uectangsa
	* ueqtangsa
	* uextangsa
	* uezshorttangsa
	* ueztangsa
	* uictangsa
	* uiqtangsa
	* uiuctangsa
	* uiuqtangsa
	* uiuxtangsa
	* uiuztangsa
	* uixtangsa
	* uiztangsa
	* uqtangsa
	* uxtangsa
	* uztangsa
	* vctangsa
	* vqtangsa
	* vxtangsa
	* vztangsa
	* xatangsa
	* zatangsa and zerotangsa
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Tangsa SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=241.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=334.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=449.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=540.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* four (U+0034): X=340.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=461.0,Y=716.0 (should be at cap-height 714?)

	* six (U+0036): X=482.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=531.0,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=543.5,Y=712.0 (should be at cap-height 714?)

	* S (U+0053): X=399.5,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=388.5,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=423.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=126.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=440.0,Y=712.0 (should be at cap-height 714?)

	* section (U+00A7): X=129.0,Y=1.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=485.5,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=490.0,Y=715.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=139.0,Y=712.0 (should be at cap-height 714?)

	* ae (U+00E6): X=740.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=308.5,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=388.5,Y=-1.0 (should be at baseline 0?)

	* egrave (U+00E8): X=423.0,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ntilde (U+00F1): X=167.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=153.0,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=217.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cacute (U+0107): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=485.5,Y=-2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=388.5,Y=-1.0 (should be at baseline 0?)

	* emacron (U+0113): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecaron (U+011B): X=423.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.5,Y=712.0 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=543.5,Y=712.0 (should be at cap-height 714?)

	* uni0122 (U+0122): X=531.0,Y=0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=543.5,Y=712.0 (should be at cap-height 714?)

	* Eng (U+014A): X=586.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=700.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=807.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=399.5,Y=712.0 (should be at cap-height 714?)

	* sacute (U+015B): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=399.5,Y=712.0 (should be at cap-height 714?)

	* scedilla (U+015F): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=399.5,Y=712.0 (should be at cap-height 714?)

	* scaron (U+0161): X=126.5,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=399.5,Y=712.0 (should be at cap-height 714?)

	* uni0219 (U+0219): X=126.5,Y=-2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=80.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-467.0,Y=712.0 (should be at cap-height 714?)

	* uni1E9E (U+1E9E): X=354.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=471.5,Y=-2.0 (should be at baseline 0?)

	* mztangsa (U+16A9C): X=530.0,Y=2.0 (should be at baseline 0?)

	* mztangsa (U+16A9C): X=385.5,Y=2.0 (should be at baseline 0?)

	* mqtangsa (U+16A9E): X=461.0,Y=1.0 (should be at baseline 0?)

	* mqtangsa (U+16A9E): X=141.0,Y=713.0 (should be at cap-height 714?)

	* gatangsa (U+16AA2): X=280.0,Y=712.5 (should be at cap-height 714?)

	* yatangsa (U+16AA5): X=471.0,Y=715.0 (should be at cap-height 714?)

	* phatangsa (U+16AA9): X=413.0,Y=1.0 (should be at baseline 0?)

	* batangsa (U+16AAA): X=402.5,Y=1.0 (should be at baseline 0?)

	* tatangsa (U+16AB0): X=410.0,Y=1.0 (should be at baseline 0?)

	* thatangsa (U+16AB9): X=226.0,Y=1.5 (should be at baseline 0?)

	* fatangsa (U+16ABB): X=417.0,Y=1.0 (should be at baseline 0?)

	* zatangsa (U+16ABE): X=403.0,Y=713.0 (should be at cap-height 714?)

	* fourtangsa (U+16AC4): X=362.0,Y=712.0 (should be at cap-height 714?)

	* fivetangsa (U+16AC5): X=85.0,Y=712.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<202.0,115.0>--<202.0,109.0>>

	* at (U+0040) contains a short segment B<<627.0,295.0>-<627.0,282.0>-<626.5,272.5>>

	* at (U+0040) contains a short segment B<<626.5,272.5>-<626.0,263.0>-<626.0,260.0>>

	* M (U+004D) contains a short segment L<<204.0,585.0>--<200.0,585.0>>

	* M (U+004D) contains a short segment L<<459.0,153.0>--<463.0,153.0>>

	* N (U+004E) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* N (U+004E) contains a short segment L<<588.0,158.0>--<591.0,158.0>>

	* Q (U+0051) contains a short segment B<<412.0,-10.0>-<408.0,-10.0>-<403.5,-10.0>>

	* Q (U+0051) contains a short segment B<<403.5,-10.0>-<399.0,-10.0>-<395.0,-10.0>>

	* a (U+0061) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* d (U+0064) contains a short segment L<<425.0,71.0>--<420.0,71.0>>

	* m (U+006D) contains a short segment L<<196.0,471.0>--<203.0,471.0>>

	* n (U+006E) contains a short segment L<<196.0,471.0>--<203.0,471.0>>

	* p (U+0070) contains a short segment L<<201.0,470.0>--<207.0,470.0>>

	* r (U+0072) contains a short segment L<<196.0,448.0>--<202.0,448.0>>

	* u (U+0075) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* Ntilde (U+00D1) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* Ntilde (U+00D1) contains a short segment L<<588.0,158.0>--<591.0,158.0>>

	* germandbls (U+00DF) contains a short segment B<<437.0,409.0>-<437.0,396.0>-<445.5,385.5>>

	* agrave (U+00E0) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aacute (U+00E1) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* acircumflex (U+00E2) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* atilde (U+00E3) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* adieresis (U+00E4) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aring (U+00E5) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* ntilde (U+00F1) contains a short segment L<<196.0,471.0>--<203.0,471.0>>

	* ugrave (U+00F9) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uacute (U+00FA) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* ucircumflex (U+00FB) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* udieresis (U+00FC) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* amacron (U+0101) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* abreve (U+0103) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* aogonek (U+0105) contains a short segment L<<397.0,75.0>--<393.0,75.0>>

	* dcaron (U+010F) contains a short segment L<<425.0,71.0>--<420.0,71.0>>

	* dcroat (U+0111) contains a short segment L<<424.0,71.0>--<419.0,71.0>>

	* Nacute (U+0143) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* Nacute (U+0143) contains a short segment L<<588.0,158.0>--<591.0,158.0>>

	* nacute (U+0144) contains a short segment L<<196.0,471.0>--<203.0,471.0>>

	* uni0145 (U+0145) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* uni0145 (U+0145) contains a short segment L<<588.0,158.0>--<591.0,158.0>>

	* uni0146 (U+0146) contains a short segment L<<196.0,471.0>--<203.0,471.0>>

	* Ncaron (U+0147) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* Ncaron (U+0147) contains a short segment L<<588.0,158.0>--<591.0,158.0>>

	* ncaron (U+0148) contains a short segment L<<196.0,471.0>--<203.0,471.0>>

	* Eng (U+014A) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* Eng (U+014A) contains a short segment L<<588.0,224.0>--<591.0,224.0>>

	* eng (U+014B) contains a short segment L<<196.0,471.0>--<204.0,471.0>>

	* racute (U+0155) contains a short segment L<<196.0,448.0>--<202.0,448.0>>

	* uni0157 (U+0157) contains a short segment L<<196.0,448.0>--<202.0,448.0>>

	* rcaron (U+0159) contains a short segment L<<196.0,448.0>--<202.0,448.0>>

	* umacron (U+016B) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* ubreve (U+016D) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uring (U+016F) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* Uogonek (U+0172) contains a short segment B<<549.5,-152.0>-<563.0,-149.0>-<572.0,-147.0>>

	* uogonek (U+0173) contains a short segment L<<446.0,70.0>--<440.0,70.0>>

	* Euro (U+20AC) contains a short segment B<<217.0,383.0>-<217.0,377.0>-<216.5,369.0>>

	* Euro (U+20AC) contains a short segment B<<216.5,369.0>-<216.0,361.0>-<216.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<216.0,352.0>-<216.0,344.0>-<216.0,335.5>>

	* Euro (U+20AC) contains a short segment B<<216.0,335.5>-<216.0,327.0>-<217.0,318.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* aztangsa (U+16A74) contains a short segment L<<177.0,453.0>--<177.0,453.0>>

	* eqtangsa (U+16A7E) contains a short segment B<<308.0,386.0>-<315.0,386.0>-<322.0,386.0>>

	* eqtangsa (U+16A7E) contains a short segment B<<302.0,423.0>-<299.0,423.0>-<295.0,423.0>>

	* awctangsa (U+16A89) contains a short segment B<<163.0,430.0>-<163.0,436.0>-<163.0,442.0>>

	* uiztangsa (U+16A8C) contains a short segment B<<396.0,567.0>-<396.0,568.0>-<396.0,569.0>>

	* uictangsa (U+16A8D) contains a short segment B<<642.0,496.0>-<642.0,492.0>-<642.0,491.0>>

	* uiqtangsa (U+16A8E) contains a short segment B<<257.0,335.0>-<255.0,335.0>-<252.0,335.0>>

	* ngfinaltangsa (U+16A90) contains a short segment L<<343.0,614.0>--<339.0,621.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<309.0,383.0>-<322.0,391.0>-<335.0,398.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<335.0,398.0>-<348.0,405.0>-<360.0,413.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<526.0,421.0>-<535.0,416.0>-<546.0,409.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<629.0,359.0>-<635.0,362.0>-<642.0,366.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<719.0,308.0>-<712.0,304.0>-<707.0,301.0>>

	* uexlongtangsa (U+16A91) contains a short segment B<<476.0,340.0>-<467.0,345.0>-<458.0,350.5>>

	* uexlongtangsa (U+16A91) contains a short segment B<<458.0,350.5>-<449.0,356.0>-<440.0,361.0>>

	* khatangsa (U+16AA1) contains a short segment B<<655.0,405.0>-<655.0,399.0>-<655.0,393.0>>

	* phatangsa (U+16AA9) contains a short segment B<<170.5,610.0>-<162.0,607.0>-<162.0,597.0>>

	* tatangsa (U+16AB0) contains a short segment L<<363.0,576.0>--<363.0,578.0>>

	* ninetangsa (U+16AC9) contains a short segment B<<277.0,119.0>-<277.0,113.0>-<281.5,108.0>>

	* ninetangsa (U+16AC9) contains a short segment B<<271.0,335.0>-<268.0,335.0>-<266.0,335.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* aztangsa (U+16A74): L<<176.0,714.0>--<177.0,453.0>>

	* eighttangsa (U+16AC8): L<<319.0,407.0>--<320.0,0.0>>

	* yatangsa (U+16AA5): L<<367.0,614.0>--<76.0,613.0>>

	* yatangsa (U+16AA5): L<<76.0,714.0>--<471.0,715.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 12 | 39 | 474 | 25 | 395 | 0 |
| 0% | 1% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
