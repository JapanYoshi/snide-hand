# Snide-Hand

Snide Hand is a handwriting font based on my own handwriting. My reference photos were taken from semi-rushed writing on 7mm-ruled paper with a 0.4mm felt-tipped pen. It supports: Latin, Cyrillic, Polytonic Greek, (some) IPA, and Shavian.

![Preview image goes here.](./previews/image0.png)

Making this font is a huge undertaking, and it may never be truly complete. It can be enjoyed by anyone free of charge in the interim, flaws and all.

## Known issues

* **Corrupted kerning table.** The first row of each kerning column has to be `All others`, but somehow, the `All others` row has been deleted, and I can't add it back. Consequently, the letter spacing is all screwed up when exported on Windows.

## Features

### Latin

* Supports Vietnamese; contains all letters with diacritics necessary for Vietnamese and `Dong sign`.

* Supports (some) IPA.

### Cyrillic

* Supports Ukrainian; contains `Cyrillic letter ge with upturn` and `Hryvnia sign`.

* Supports "Bulgarian" (cursive-like) letterforms, implemented as the `locl` OpenType feature for Bulgarian language. (Several letters only contain cursive-like letterforms, such as `Cyrillic small letter pe` and `Cyrillic small letter tse`.)

### Greek

* Supports Polytonic Greek.

### Shavian

* Incorporates ligatures for the sequences 𐑩𐑯 /ən/, 𐑾𐑯 /iən/, and 𐑦𐑙 /ɪŋ/.

## How to edit/build

The project file is stored as [the `./SnideHand.sfdir` directory](./SnideHand.sfdir). You can open it in the FontForge open-source cross-platform font editor.

## Acknowledgments

Thank you to [Local Fonts](https://localfonts.eu) for helping me troubleshoot an issue with corrupted kerning.