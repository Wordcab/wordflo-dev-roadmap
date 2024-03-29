# Wordflo Development Roadmap

Wordflo is the world's fastest transcript editing experience, leveraging first-principle design and proprietary voice intelligence technology to accelerate the time it takes to get to final-perfect transcription.The transcript editor is for high-impact calls in regulated spaces, and is meant to augment existing compliance and QA teams. You can find a demo at [wordflo.ai](http://wordflo.ai).

## Changes on 03/29/2024
- Better start/end capitalization for reassigned words.
- History does not save Overlay toggles.
- Various bug fixes around comments, history, and speaker reassignment.

## Changes on 03/21/2024
- Visualize basic session history
- Empty comments act as highlights
- Comments can be opened by clicking the transcript highlights with CTRL + click
- Speaker reassignment is now part of history and can be undone

## Changes on 03/10/2024

- Added Wordflo pricing page.
- Added actual file name on top of Wordflo page.
- Comments can now be edited/deleted in-session (WIP).

## Changes on 03/08/2024

- Added Wordflo official landing page.
- Added comment backend infrastructure and experimental comments front-end (WIP).

## Changes on 03/03/2024

- CSV export option.
- URL params in Wordflo URL are now encrypted and expire, adding more security.
- Back button in Wordflo goes back to dashboard.

## Changes on 02/22/2024

- Ability to move word pointer left and right with the arrow keys, when paused.
- Hold SHIFT to select text while moving arrow key left/right.
- Auto-capitalization and other fixes on every change.
- ToC headers highlighted depending on where word pointer is in transcript.
- Notification system implemented (used in "copy to clipboard" feature).
- New "copy to clipboard" feature both in highlight tooltip and via CTRL+C.
- Automatically saved changes (strikethroughs, edits, and speaker changes). ToC not yet saved.
- "Backspace" key for deleting highlighted text.

## Development Roadmap
- Export transcript with table of contents as transcript "headers".
- ToC changes saved.
- ToC headers added to exported transcript.
- Streamlined speaker assignment.
- Toggle paragraphs for large chunks of text with a single shortcut `P`.
- Firefox support.