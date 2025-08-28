# 8x8 Pixel-Font Editor
This html page is a pixel font editor
for retro bitmap fonts. It supports
the full Unicode range.

You might instantly run it using
github's preview feature:
[HMTL Preview](https://htmlpreview.github.io/?https://github.com/KungPhoo/8x8-pixel-font-editor/blob/main/8x8-font-editor.html)


## User Interface
A the top you find 2 input boxes.
Here, you enter the Unicode point range
you want to edit in hex numbers.

The Update button will change to the
range.

Next, you see a grid of glyphs you can
edit. Click any character to edit it.

Below, there's an 8x8 pixel field to edit
the pixels for your font.

Next, there are a few buttons:
- Extract from Standard Font - generate
  an 8x8 representation of the glyph as
  your browser would show it.

- Extract from Unifont - generate
  an 8x8 representation of the glyph as
  [Unifont](https://unifoundry.com/index.html)
  would show it.

- Extract from Noto Emoji - generate
  an 8x8 representation of the glyph as
  [Noto Emoji](https://fonts.google.com/noto/specimen/Noto+Emoji)
  would show it.

- Copy, Paste - copy and paste from/to an
  internal clipboard buffer.
- Mirror
- Rotate 90°

Next, you find a code representation
of the glyphs currently visible.

At the bottom is a text area.
If you paste text here and press
"Parse C++ Input", the pixels will be
read and used.

Pressing "Generate Full C++ Input"
will generate the bits code for all
defined characters and put them into
the text area.

The defined glyphs are stored in the
browsers's localStorage for convenience.

## LICENSES
- The EDITOR is released under the
  [Unlicense](https://unlicense.org/)
  terms.

- FONTS are licensed as stated in
  the separate files.

