# Self-hosted Chinese webfonts

QZSongti is a WOFF2 subset of Noto Serif SC (variable weights 200–900):
https://github.com/google/fonts/tree/main/ofl/notoserifsc

QZFangsong is a WOFF2 subset of Zhuque Fangsong v0.212:
https://github.com/TrionesType/zhuque/releases/tag/v0.212

Both are licensed under SIL OFL 1.1; licenses and upstream copyright notices are included. Internal subset family names were changed. Glyph outlines have not been edited.

Songti is split into homepage/common glyphs and remaining article glyphs; CSS unicode-range loads only needed files. FangSong is used only by the opening-quote paragraphs. No remote font service is required.

These files cover the current visible site text. When adding new text, rebuild the subsets and unicode ranges to include new characters (otherwise those new characters use the CSS system fallback). Keep weight ranges and licenses.
