# Selected-source teaching audit: chapters 14–21

Delivered `batch_014_017.py` and `batch_018_021.py` only. These import the new Perloff `authoring` helper and do not call `save()`. The prior neonatal course and other authors' ranges were not edited.

## Actual counts and structural validation

- Eight chapters, six cards each: 48 cards.
- Five distinct authored SBA MCQs and five measurable learning units per chapter: 40 MCQs and 40 units.
- Four fictional progressive cases, chapters 15, 17, 18 and 21; three stages each: 12 additional decisions. These do not fill the MCQ quotas.
- A fresh Python process explicitly placed `work/perloff_course` first on `sys.path`; the imported helper's absolute location was checked.
- Every card, MCQ and case-stage reference is inside the assigned chapter. Every SBA has four distinct options; the shuffled correct answer's option note equals its rationale. Every case has three stages and a valid answer index.
- No numeric prescribing regimen is taught.

## Evidence map

| Chapter | Selected objectives | Supporting PDF pages |
|---|---|---|
|14|Restriction; delayed infant heart failure; resistance-driven reversal; changing murmur; aortic valve complication; spontaneous closure|267,270,268,275,288,266|
|15|Outlet septal malalignment; relative resistances; softening in a hypoxic episode; posture; systemic pressure ceiling; collateral pulmonary supply|297,301,309,307,302,301|
|16|Pragmatic anatomy; subpulmonary streaming; subaortic high flow; pulmonary obstruction; essential left ventricular exit; straddling|326,331,327,327,326,327|
|17|Ductal insertion; left-heart volume load; continuous sound timing; differential cyanosis; window comparison; silent patency|346,351,358,355,367,351|
|18|Postnatal coronary perfusion; collateral benefit and steal; papillary dysfunction; ECG; coronary origin imaging; adult risk|373,374,377,379,381,376|
|19|Fistula anatomy; chamber loading; steal; murmur location; diastolic LV drainage; proximal coronary dilation|385,386,386,389,390,385|
|20|Sinus-to-chamber relation; abrupt volume burden; new continuous murmur; temporal pattern; conduction injury; unruptured pouch sound|396,396,399,402,403,403|
|21|Atrial exit; ductal pulmonary supply; variable RV morphology; pressure-dependent coronary perfusion; ECG limitations; functional versus anatomic atresia|410,410,407,410,414,407|

Selected original PDF passages were read directly in page batches while extraction progressed, then the normalized `visible_evidence`/`visible_source` material was consulted. The source contains malformed `/ActualText` metadata; `TEXT_IGNORE_ACTUALTEXT` is needed to recover visible glyph text. Suppressed fragments were not interpreted as clinical source errors, guessed, or repaired with global punctuation replacement.

Review status is **model-selected-source-checked**, not independent specialist review. The audit does not claim exhaustive line-by-line review of every table, caption, reference or page in these long chapters. Source-edition clinical recognition teaching is distinguished from independently current treatment guidance. No external update search, specialist review, formal simulation validation or clinical performance assessment was performed.

## Instructional limits

Cases are coherent fictional reasoning exercises, with later data introduced only at later stages. They assess knowledge and interpretation rather than demonstrated bedside competence. Units use clinical application for presentation and diagnostic interpretation, deep dive for hemodynamic and anatomic synthesis, and essentials for core definitions; absent levels remain explicitly represented by the helper. Full reference chapters contain additional anatomy, imaging variants and adult/infant examples beyond the selected five-unit pathway.
