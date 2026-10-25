# Script Timer

Paste a script and see how long it will take to read aloud, section by section.

**Open it:** https://seegree.github.io/script-timer/

It runs entirely in your browser: no account, no install, and your script is never uploaded.

## Use

1. Paste your script into the box on the left, or click **Load sample** to try it.
2. The right side shows the total runtime and a breakdown for each section.
3. Set the speaking rate with the **WPM** control in the header (60–300, default 150 words per minute). Double-click it to reset. The rate is remembered next time.

## How sections are found

A new section starts at any line that is:

- a Markdown heading, such as `# Intro`
- written in ALL CAPS, such as `KEY FEATURES`
- ended with a colon, such as `Demo:`
- wrapped in brackets, such as `[Call to action]`

Text before the first heading becomes "Untitled Section". If no headings are found, the whole script is treated as one section.

## Reading the breakdown

- Each section shows its word count, its runtime, and its share of the total.
- The **timecode** shows where the section starts and ends. Click it to jump to that section in the script.
- Click a section's title to rename it.
- **HEAVY** marks a section over 35% of the total runtime. **THIN** marks one under 5 seconds.

## Target length

Enter a target such as `1:30`, `90`, or `1m30s`. The app shows how far over or under the script runs, and roughly how many words to cut or add.

## Run it locally

Open `index.html` in a current browser. It loads React from a CDN, so it needs an internet connection.
