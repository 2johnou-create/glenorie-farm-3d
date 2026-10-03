# Glenorie Farm — 3D concept 02

Updated on 4 October 2026 from the new P6 interior sheet and the earlier plan set.

Open `output/glenorie-farm-3d.html` in a browser. The viewer is self-contained and works offline with JavaScript and WebGL enabled. The GLB file is a model in metres with named groups and materials. Source geometry is in `src/model.js`.

## Source basis

- `New Design v2_P6.pdf`, updated single P6 sheet supplied 4 October 2026 (sheet itself retains the 3 October feedback date): one approximately 3 m indoor feature tree; approximately 3 m feature wall; same rendered finish on wall and bar; removable seating and farm product furniture.

- `New Design v2_P1.pdf`, P1–P6, feedback dated 3 October 2026: commercial/farm boundaries; side entrance; kitchen, toilet and roastery requirements; curved fixed counter; removable workshop furniture; concealed storage access.
- `13. The Shed Company_1435 Old Northern Road, Glenorie NSW.pdf`, A.05–A.09: floor and roof geometry, 5 m structural bays, elevations and sections.

The notes within the PDFs are treated as source design proposals. They do not establish that any alteration, approval pathway or column removal has been approved.

## Model dimensions

| Item | Model value | Basis |
| --- | --- | --- |
| Building length | 25.00 m | A.05/A.06: five 5 m bays |
| Existing shed depth | 10.00 m | A.06 |
| Extension depth | 4.50 m | A.06 |
| Commercial footprint | 15.00 × 14.50 m = 217.50 m² | New design P1 |
| Kitchen footprint | 4.00 × 6.50 m | New design P3/P4 |
| Toilet block footprint | 6.00 × 4.00 m | New design P4 |
| Roastery footprint | 5.00 × 4.00 m | New design P3/P4; P3 has a question mark |
| Existing eaves / ridge | 4.00 / 4.88 m above model floor | A.08/A.09 |
| Extension outer / high edge | 3.33 / 3.80 m above model floor | A.07/A.09 |
| Farm storage | Approximately 5.00 × 6.75 m | Traced from new design P1/P4 |
| Open entry bay | Approximately 5.00 × 3.25 m | Traced from new design P1/P4 |
| Foliage prep | Approximately 5.00 × 10.00 m | Traced from new design P1 |
| Indoor feature tree | 3.00 m overall, including planter | Updated P6 |
| Feature wall | 3.00 m high | Updated P6 |
| Tractor carport | Approximately 10.00 × 4.50 m | New design P1 plus A.06 roof extent |

Room dimensions describe partition centreline footprints; clear internal dimensions are reduced by the modelled wall thicknesses. The supplied sketches are conceptual, so their drawn proportions do not always match the written room sizes. Written dimensions take priority here.

## Interior interpretation

The kitchen occupies the upper right of the revised plan, the toilet block sits immediately below it, and the glazed roastery occupies the lower right. Toilet room A is a cleaning store, B is unisex, and C is an accessible-room concept. Each has a schematic basin. A sliding glass entrance separates the shared toilet lobby from the workshop. Kitchen service access and a two-door external lobby are represented.

The service counter follows the revised curved form, with coffee equipment and a back bench. Its top and fascia share exactly the same concrete-style material as the new 3 m feature wall. The feature wall is interpreted as the workshop face of the toilet block, continuing from the counter’s south end. The existing 1.3 m sliding-glass toilet entrance remains within this wall. A single 3 m broadleaf feature tree sits in the farm-product-display zone. Its trunk, branches and leaf canopy are modelled, with a rendered planter. Four removable product tables surround the planter, following the marked-up arrangement. The tree’s species and exact position are illustrative; its overall model height includes the planter.

Three movable tables each have eight workshop chairs. Their positions have been adjusted from the sketch to clear retained posts and the new tree planter. The second table is shorter and closer to the first, leaving the tree/display zone open. Window benches and produce displays are also movable. The 24-seat count refers to workshop chairs; window benches would add people if used simultaneously.

The concealed staff gate is estimated at 1.8 m wide to represent pallet access. Its real opening and route should be chosen for the actual pallet, handling equipment and storage operations. Farm-facing glazing, a stock gate and the side entrance are proposed opening interpretations rather than a confirmed joinery schedule.

The roastery machines are schematic representations of the proposed 6 kg and 1.5 kg equipment. They do not carry manufacturer dimensions, extraction requirements or service clearances.

## Assumptions and unresolved details

1. A.08 labels the south extension eave 3.30 m; A.07/A.09 use 3.33 m. The model uses 3.33 m. A.06 states a 5° extension pitch, while the 3.33–3.80 m levels over 4.5 m imply approximately 6°. The model follows the stated height levels. Roof joins, gutters, ridge and flashing geometry are simplified.
2. Elevations show floor RL 174.000; sections show RL 173.250. All model floors use a relative 0.00 m datum. Site terrain, cuts, fill, slab depth and foundations have not been reconstructed. Ground and planting are illustrative.
3. The existing roof is interpreted as a gable from the elevations and sections. The intermediate roof-plan lines and detailed roof assembly are not resolved.
4. Structural posts are retained. Major grid posts follow the plan; minor posts are traced approximately. Member sections are schematic. No structural calculation, new portal design or column removal has been performed.
5. Doors, partitions, counter dimensions, furniture, finishes, plumbing fixtures and machine positions are concept estimates. The kitchen has 3.0 m partitions; internal toilet-room partitions and roastery glazing use 2.8 m; the workshop-facing feature wall is 3.0 m as annotated in P6. These are chosen for visualisation, not supplied heights.
6. Window annotation wording such as “60–90 cm height” is ambiguous about sill versus pane height. Ribbon windows are represented with approximately 0.8 m panes and approximately 1.35–1.4 m sills. These need confirmation.
7. An operable glass stock gate is represented as closed in this first model. Door swings and door mechanics are not animated.
8. The geometry expresses the intended separation of kitchen, toilets and roastery. It does not model certified ventilation, acoustic performance, accessible circulation, fire separation or egress. These details need coordination with the architect and relevant consultants.
9. The new design identifies the commercial boundary as the approved DA area. This model follows that boundary without independently verifying council consent or the CC/CDC pathway.

10. The P6 feature wall is 0.20 m thick in the model. Its exact junction, substrate, top detail and finish specification need further design. The full-height feature wall remains visible in cutaway mode; a separate layer toggle hides the wall and tree together.

## Controls and files

- Cutaway, exterior, floor-plan, three eye-level views and a dedicated interior-features view.
- Roof and full frame toggles; adjustable wall cut height; ancillary farm-space toggle.
- Room labels and dimensions.
- Workshop layout or cleared event layout. The counter, equipment, feature wall and tree stay in place.
- Three finish studies: warm farm café, industrial and neutral.
- Save the full building as GLB, or save a current image. GLB export includes full-height walls, roof, columns and all furniture regardless of viewer toggles.

`output/glenorie-farm-concept-02.glb` is the full 3D building export. PNG files in `output/` show the saved views. The HTML viewer bundles Three.js 0.180.0, licensed under MIT; see `vendor/package/LICENSE`.

## Verification

Checked in a local browser: seven camera views, 24 workshop chairs, one 3 m tree, a 3 m feature wall, shared wall/counter materials, the retained toilet entrance, zero furniture intersections with retained columns or the new feature wall/planter, the cleared layout, finish selection, dimensions, notes dialog, mobile layout, screenshot capture and GLB export. The exported GLB header and named geometry groups were verified. The browser reported no JavaScript errors. These checks validate the model viewer and file, not the building design.
