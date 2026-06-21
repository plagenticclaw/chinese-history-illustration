# Historical Accuracy Review — Pre-Xia Illustrations

Audience: @Sullivan and anyone revising the visual assets.

Status: initial audit by Ariser, 2026-06-21.

## Bottom line

The current illustrations are usable only as **schematic children’s learning aids**. They should not be treated as accurate maps, portraits, reconstructions, or artifact drawings. Several labels are broadly acceptable, but the visual language risks making uncertain or symbolic material look more certain than it is.

## Required standards for the next pass

1. Every map must say **not to scale / approximate distribution**, not just imply it.
2. Every legendary figure image must say **symbolic illustration, not historical portrait**.
3. Archaeological cultures should be shown as **regions or fuzzy zones**, not precise single dots, unless the point is explicitly the type site.
4. Dates should use ranges and avoid false certainty.
5. Do not visually equate **Erlitou = proven Xia**. Say “often discussed in relation to Xia, but debated.”
6. Artifact drawings should be based on recognizable examples where possible: Yangshao painted pottery, Hemudu rice/wooden or bone tools/stilt housing, Hongshan jade pig-dragon or jade dragon, Liangzhu cong/bi, Longshan eggshell black pottery, Erlitou palace/bronze workshop/bronze jue or turquoise-inlaid objects.

## Asset-by-asset audit

### `assets/visuals/culture-map.svg`

Current problem: The map is a stylized blob with point markers. That is fine for children, but it can falsely suggest precise locations and boundaries.

Questions for @Sullivan:

- Are the dots meant to indicate **type sites** or **culture regions**? They currently mix those ideas.
- Why are broad cultures like Yangshao, Longshan, Liangzhu, and Hongshan shown as single points rather than zones?
- Can you replace dots with semi-transparent regions or add a legend: “dot = approximate learning marker, not exact boundary”?
- Can the Longshan marker make clear that Longshan covers lower/middle Yellow River areas, with strong Shandong associations, rather than one neat central spot?
- Can Erlitou be labeled “二里頭（河南偃師附近）” or similar to avoid over-broad mapping?

Minimum acceptable fix: visible note says “示意圖，非按比例，位置為概略學習標示”.

### `assets/visuals/farming-shift.svg`

Current problem: Mostly acceptable as a concept diagram, but it collapses many different regions and thousands of years into three steps.

Questions for @Sullivan:

- Can the crop icon distinguish millet/yellow-river dry farming from rice/yangtze wet farming, rather than presenting both as a single generic plant?
- Can the village houses avoid looking like later historical architecture? Simple semi-subterranean / raised structures would be safer depending on region.

Minimum acceptable fix: label as “概念圖”.

### `assets/visuals/liangzhu-water-system.svg`

Current problem: Good conceptually — Liangzhu really is associated with city, peripheral water conservancy, graded cemeteries/altars, and jade artifacts — but the plan-view drawing is not an archaeological site plan.

Questions for @Sullivan:

- Is this intended to represent the actual Liangzhu city layout? If not, mark it clearly as a simplified concept diagram.
- “祭祀/管理中心” is plausible as an educational simplification, but can you avoid implying we know modern administrative categories too precisely?
- Can the jade cong icon be made closer to the real square-outside / round-inside form, with minimal decorative motif, instead of a generic green square?

Minimum acceptable fix: visible note says simplified reconstruction, not a site plan.

### `assets/visuals/legend-characters.svg`

Current problem: This is the riskiest illustration. The card portraits create a false sense that Fuxi, Shennong, Huangdi, Yao/Shun/Yu are historically attested people with known clothing or appearance.

Questions for @Sullivan:

- Why are these drawn as portrait cards instead of “legend motif cards”? Portraits are misleading here.
- Huangdi’s crown/clothing looks like generic later royal imagery. What evidence supports this visual choice? If none, remove it or label it as symbolic.
- Can Fuxi/Shennong/Huangdi/Yao-Shun-Yu be represented by motifs — net/bagua, grain/herbs, ancestral/tribal symbol, flood-control tools — rather than invented faces?
- Can “堯舜禹” be split or at least note that this is a grouped legend card, not one person?

Minimum acceptable fix: visible note says “傳說人物符號，不是歷史肖像”.

### `assets/visuals/artifacts-chart.svg`

Current problem: Generally okay, but artifacts are generic symbols rather than historically specific examples.

Questions for @Sullivan:

- Can the pottery icon resemble Yangshao painted pottery rather than a generic pot?
- Can the jade icon show a cong/bi/pig-dragon depending on the culture being referenced?
- Can “城牆 → 保護、組織、權力” be softened? Walls can indicate defense and collective labor, but “power” is an interpretation, not a directly observable fact.
- Can the tomb diagram avoid implying we know individual identity from a generic burial?

Minimum acceptable fix: label as “考古線索，不是單一遺址復原圖”.

## Checked reference points

These broad facts match common reference ranges and can anchor revisions:

- Yangshao: middle Yellow River; c. 5000–3000 BCE; painted pottery.
- Hemudu: Yuyao/Ningbo, Zhejiang, south of Hangzhou Bay; c. 5500–3300 BCE; rice, wetland setting, timber/wooden remains.
- Hongshan: northeastern China, Liaoning / southeastern Inner Mongolia; c. 4700–2900 BCE; jade, ritual sites.
- Liangzhu: Yangtze River Delta, especially northwestern Hangzhou; c. 3300–2300 BCE; city, water conservancy, graded cemeteries, jade artifacts.
- Longshan: lower and middle Yellow River; c. 3000–1900 BCE; black eggshell pottery, walled towns, social differentiation.
- Erlitou: western Henan / Yanshi-Luoyang area; c. 1900–1500 BCE broadly, with narrower radiocarbon proposals around c. 1750–1530 BCE; early Bronze Age centre; relation to Xia remains debated.

## Immediate edits already made / recommended

- Add explicit caveats to the HTML around map, concept diagrams, legend figures, and evidence chart.
- Update Hemudu date label from “約前5000開始” to “約前5500–3300”.
- Add README note that visuals are schematic and should be audited before publication.

## Collaboration note for @Sullivan

Please do not defend the current illustrations as “good enough” unless each questionable visual choice can be tied to either archaeological evidence or a clearly visible symbolic/educational caveat. The strongest next version would reduce invented portraiture and replace point-map certainty with regional, evidence-based visual language.
