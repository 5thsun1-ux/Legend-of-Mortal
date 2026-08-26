# Legend of Mortal Dialogue Simulator — 活俠傳 Dialogue Simulator

**An unofficial, fan-made tool for staging Legend of Mortal fan fiction and dialogue on screen and sharing it with audiences across different countries and regions.**

> Inspired by the dialogue-screen composition of the wuxia game *Legend of Mortal* (活俠傳), this tool lets you play your own script in a game-like presentation. It runs directly in a browser with no installation required.

**▶ Try it now:** https://5thsun1-ux.github.io/Legend-of-Mortal/

## Key Features

- **Game-inspired dialogue presentation:** The active speaker moves forward and appears brighter, while other characters move back and become darker. Normal playback supports a typewriter effect; video export displays each complete sentence immediately.
- **Bulk script conversion:** Paste fiction or screenplay text and identify speakers and expressions from formats such as `[Name] = Dialogue` and `Name: Dialogue`.
- **Branching choices:** Includes a “Your choice…” screen, Routes 1–3, and automatic return to the common route.
- **Incident and item presentation:** Create book scenes with illustrations and vertical titles, plus item panels above the dialogue box.
- **Stage direction:** Configure entry, exit, horizontal and vertical movement, shaking, fades, rushes, and group actions for each line.
- Supports **recall, autoplay, fullscreen, background music, and dance mode**.
- **Five-language UI and automatic translation:** 한국어 · 日本語 · 台灣繁體 · 中国简体 · English.
- **Multiple output formats:** Standalone HTML, JPG scene ZIP, high-quality WebM, under-5MB WebM, and icon-enhanced recall-dialogue JPG pages.
- **Autosave and backup:** Work is saved automatically in the browser and can be backed up or moved with JSON.
- **Single-file structure:** The editor and exported story HTML package the required code, styles, and fan-made default graphics into one file.

## Name and Copyright Notice

- Tool name: **Legend of Mortal Dialogue Simulator**
- Type: Unofficial, fan-made derivative-work tool for *Legend of Mortal*
- Rights to the original game and its characters, setting, and proper nouns belong to their respective rights holders.
- This tool **contains no images, icons, or audio from the original game.**
- The code and default graphics—including the ink-wash title background, incident book, ending background and book, and default dance track—were created for this tool.
- The only built-in data referenced from the original work is a **proper-noun glossary for consistent multilingual translation**, covering character names, aliases, locations, factions, items, and similar terms. Inclusion in the glossary does not claim ownership of those names.
- Any license covering the source code and original components does not extend to the original work’s names, setting, or terminology.
- Users are responsible for the rights and permitted use of any images, icons, music, or text they upload.
- Before publishing your results, review the original rights holder’s fan-work guidelines and use the tool for personal, non-commercial fan creation.

## Purpose

Legend of Mortal Dialogue Simulator was created to make fan fiction, dialogue scenes, and short side stories easy to present in a format resembling a game screen, and to let Korean, Japanese, Traditional Chinese, Simplified Chinese, and English-speaking audiences enjoy them together.

This is an editor for the **visual presentation and sharing of stories**. It contains no combat, character development, exploration, original-story progression, or other functionality that could replace the original game. It is not intended to reproduce or substitute for the original game.

## Outputs You Can Create and Share

- **Standalone HTML:** Play the completed work from one HTML file without the editor
- **Scene screenshots:** Save the opening, dialogue scenes, and ending in a JPG ZIP
- **High-quality WebM:** Export video with stage effects and background music
- **Under-5MB WebM:** Automatically adjust quality for upload size limits
- **Recall-dialogue JPG:** Save character icons and the full script as vertical pages
- **JSON:** Store, back up, and move the project between environments

When all translations are complete, a single HTML file can switch instantly among five languages. JPG and WebM exports use the language selected at export time.

## About Dance Mode

Dance mode was not created for a serious practical purpose.

**It was added simply because I wanted the characters to step away from the story and battles for a moment, dance together, and have fun with the music.**

The current background and characters remain on screen while the characters sway, jump, and rotate. Lighting and sparkles react to the music. Turn it on whenever you want a lighthearted break.

---

# Feature Guide

The following sections follow the editor from top to bottom.

## Opening Screen

- Select Korean, Japanese, Traditional Chinese, Simplified Chinese, or English UI
- Enter a work title
- Automatically add a large-title opening to screenshots and videos
- Switch language instantly in a fully translated standalone HTML

## ① Background Selection

- Upload multiple background images
- Favorite and reorder backgrounds
- Change the background from a specific dialogue line
- Match multilingual asset names using Excel place names and the glossary

## ② Characters

- Add character images individually or by folder
- Search by English character ID or official multilingual name
- Place up to 10 characters on screen
- Manage multiple expression images
- Set character size, horizontal position, and mirroring
- Add character icons and change them by dialogue line
- Add original characters without images

## ③ Incidents and Items

- Display an incident book over a selected dialogue range
- Display an item image above the dialogue box
- Set incident titles and item names
- Add book illustrations and item images
- Preserve the same composition in screenshot and video exports

## ④ Dialogue Input

- Select a speaker and enter dialogue
- Paste and convert multiple paragraphs at once
- Import TXT, Markdown, and JSON
- Import formatted Excel scripts
- Write a common route and Routes 1–3
- Connect up to three choices to branches
- Edit dialogue directly in the list
- Assign background, BGM, expression, and icon by line
- Adjust character entry, exit, position, size, and mirroring
- Configure screen shake, fades, character shake, vertical movement, rushes, group movement, waits, and font size

## ⑤ Ending

- Enter an ending title
- Enter ending narration
- Add an illustration to the book cover
- Preview the ending screen
- Add the ending to images and videos only when a title, narration, or illustration exists

## ⑥ Legend of Mortal Glossary and Automatic Translation

- Search multilingual character names, aliases, work titles, locations, factions, items, martial arts, and other terms
- View and copy Korean, Japanese, Traditional Chinese, Simplified Chinese, and English forms
- Hide contents before searching to reduce spoilers
- Protect character names and glossary terms before machine translation
- Normalize registered Traditional, Simplified, and Japanese character variants before translation
- Translate general sentences with Chrome’s built-in desktop translator
- Edit translated text directly in each language
- Browser translation may be less capable than current professional translation services or AI translation. Review and revise the results whenever natural, high-quality translation is required.

## ⑦ Playback and Export

- Play from the beginning and move between previous and next lines
- Autoplay
- Recall screen
- Select, upload, and change background music by line
- Dance mode
- Fullscreen
- Export standalone HTML
- Export JPG scene ZIP
- Export high-quality WebM
- Export under-5MB WebM
- Export icon-enhanced recall-dialogue JPG pages

---

## Quick Start

1. Open the page, choose a UI language, and enter the work title on the opening screen.
2. Upload a background in **① Background Selection**.
3. Add character images in **② Characters**. When adding a folder, use an English character ID or a registered multilingual name as the folder name.
4. If needed, create book illustrations or item effects in **③ Incidents**.
5. In **④ Dialogue Input**, select a speaker or paste a script and press `Convert and add`.
6. Configure **⑤ Ending** and **⑥ Glossary and Automatic Translation** when needed.
7. Check the result with `▶ From start` in **⑦ Playback**, then save it in the format you want.

See the guidance in each panel for detailed controls.

## Repository Contents

| File | Description |
|---|---|
| `index.html` | The single-file simulator containing scripts, styles, and fan-made default graphics |
| `README.md` | Introduction, usage, feature, and copyright documentation |
| `LICENSE` | License for the source code and original components; does not include rights to the original work’s names, setting, or proper nouns |

## Running Locally

Download `index.html` and double-click it. Basic editing and playback require no installation or server.

The first use of Chrome’s built-in automatic translation may require an internet connection to download language packs. A standalone HTML file with saved translations does not call the translation service again.

---

## Recommended Environment

- Basic editing, playback, and export: Latest desktop Chrome or Edge recommended
- Creating automatic translations: **Desktop Chrome 138 or later** recommended
- Playing a translated HTML: Works in ordinary modern browsers because it does not invoke the translator again

## Closing

I hope Legend of Mortal Dialogue Simulator helps bring fan stories and imagined scenes onto the screen and makes them easier to share with people who use different languages.

Please enjoy it alongside the original game.

---

## Short Description

**Legend of Mortal Dialogue Simulator** is an unofficial fan-made tool for presenting fan fiction and dialogue scenes in a game-screen format and exporting them as HTML, JPG, WebM, or recall-dialogue images. It contains no original-game images, icons, or audio—only a proper-noun glossary for multilingual translation. It includes no combat, progression, or other functionality that could replace the original game, and was created to help Korean, Japanese, Traditional Chinese, Simplified Chinese, and English-speaking users share fan works.
