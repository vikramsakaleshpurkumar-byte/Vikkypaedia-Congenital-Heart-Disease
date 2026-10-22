# Source and extraction review notes

## Scope and recovery

The exact downloaded file was identified by SHA-256. All 29 chapter starts matched normalized visible title text on their declared first source pages. The chapter body covers PDF15–526 without gaps or duplicate pages. Front matter, the video catalog, printed index and back matter remain reference resources. Full original source-page image coverage is 535/535.

The PDF has defective ActualText replacement tags that suppress visible words and clauses in ordinary extraction. Visible glyph extraction with `TEXT_IGNORE_ACTUALTEXT=2048` restored a net 35,479 characters across 512 body pages. This reads supplied visible glyphs; no text was guessed and the original PDF was not modified. Alternating column margins and split inline text blocks required page-specific geometry. See [text audit](build/text_recovery_audit.json).

Some mathematical symbol-font mappings remain imperfect in extracted text. No global digit-to-symbol substitution was made. Use original page views to verify equations, numbers, table relationships, imaging labels, footnotes and credits. Reading order and all searchable prose have not received an exhaustive line-by-line audit. Recovered paragraph breaks can differ from the original layout.

Printed page-number labels were detected on 511/512 body pages. PDF154 has no visible printed page numeral in its full-page figure layout; no printed label was invented there. PDF citations remain canonical. See [printed-label audit](build/printed_page_audit.json) and [boundary audit](build/chapter_boundary_audit.json).

## Media

There are 858 raster image placements and 291 supplemental vector-diagram renders, for 1149 individual views. These are placements/crops, not a claim of that many unique numbered figures. Automatic caption association leaves 44 placements without a confident matched caption. Other associations and crop bounds may also need visual review; complete original pages preserve context. Tables and boxes remain available in original page views even where searchable extraction flattens their relationships.

The source contains a video inventory but zero embedded video files. No video playback or publisher-media access is claimed.

## Teaching review boundaries

Every chapter has six authored cards and five authored four-option questions. The five guided outcomes map to a lesson, a card and a question; case decisions are counted separately. Page-range checks and technical tests cannot verify every clinical claim. Selected model source checks and source-page renders were performed during authoring; this is not independent specialist review or assessment validation.

One source statement flagged during selected review concerns septal tricuspid leaflet offset: PDF180 describes normal offset using 15/20mm values, while PDF190 uses exceeding those values in diagnostic discussion. These passages warrant specialist checking in their original context. The authored teaching avoids adopting a numerical diagnostic cutoff from this inconsistency and uses morphology and atrialization. This is a review flag, not a confirmed publisher erratum or a substituted threshold.

The course has not been systematically reconciled with current guidelines. Clinical decisions and prescribing require current clinical references and appropriate supervision. Fictional cases teach recognition/reasoning and are not patient-specific advice.
