# Arpic Fonts — Bionic Reading Typeface

**English** | [Русский](README.ru.md)

**Arpic Sans** and **Arpic Serif** are open-source bionic reading fonts designed to guide your eyes through text using bold fixation points at the beginning of each word.

Everything works natively at the font level via OpenType `calt` (*Contextual Alternates*) — no browser extensions, plugins, or scripts required.

## Included Fonts

| Font | File | Style | Contrast |
| :--- | :--- | :--- | :--- |
| **Arpic Sans** | `Arpic-Sans.ttf` | Sans-serif | Medeo Sans Display Regular + Bold |
| **Arpic Serif** | `Arpic-Serif.ttf` | Serif | Medeo Serif Regular + Auto-Bold |

## Features

* **Full Cyrillic & Latin support** — works out of the box with Russian (including `Ё`, `Й`, and extended Cyrillic), English, and European diacritics (`Arpic Sans` also supports Greek).
* **High visual contrast** — uses a strong Regular-to-Bold transition for clear fixation points.
* **Clean word boundaries** — alphabetic `f`-ligatures (`ff`, `fi`, `fl`) are disabled in `Arpic Sans` so bolding applies character-by-character without breaking words.
* **Zero dependencies** — works anywhere OpenType `calt` is supported.

## Highlighting Logic

The number of bolded letters scales automatically with word length:

| Word Length | Bolded Letters | Example |
| :--- | :--- | :--- |
| 1–3 letters | 1 | **t**he, **f**ox |
| 4–5 letters | 2 | **qu**ick, **br**own |
| 6–7 letters | 3 | **rea**ding, **let**ters |
| 8–9 letters | 4 | **bion**ic, **cont**rast |
| 10–12 letters | 5 | **typos**graphy, **fixat**ion |
| 13+ letters | 6 | **progra**mming |

## Installation & Usage

1. Download the `.ttf` files from the repository (or the **Releases** page).
2. Install them on your OS (Windows, macOS, Linux) or copy them into your e-reader's fonts folder.
3. Select **Arpic Sans** or **Arpic Serif** in your app.

> **Note:** OpenType Contextual Alternates (`calt`) are enabled by default in modern browsers, OS UI, Microsoft Word, and advanced e-readers (such as KOReader). If bolding does not appear automatically in your reading app, enable **Contextual Alternates / Ligatures / OpenType features** in the app's typography settings.

## Credits & License

* Based on the **Medeo** font family ([DNFD/medeo-font](https://github.com/DNFDEVS/medeo-font)).
* Licensed under the **SIL Open Font License, Version 1.1** (see `LICENSE` for details).
