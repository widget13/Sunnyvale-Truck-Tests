# Sunnyvale-Truck-Tests

Truck qualification grading sheets. Phase 1 is index.html. Data is stored only on the device being used.

## Editing the tests

Open `editor.html` (it is not linked from the menu). Sign in with a fine-grained GitHub access token limited to this repository with **Contents: Read and write**. Pick a test, tap a task to change its title, description, points, or type (scored, pass/fail, critical safety), reorder, delete, or add tasks, then tap **Save to live test**. The change goes live in 1-2 minutes. Every save is a commit, so any change can be undone from the repository history on GitHub.

The editor has three tabs: **Tasks & questions**, **Page text** (briefings, scenarios, proctor instructions, headings, buttons), and **PDF & pop-ups** (wording the PDF summary and pop-up messages build). In the text tabs, put `**double stars**` around words to make them bold and `__double underscores__` for italics. Before every save the editor checks that the page structure and code are intact, and refuses to save if not.

Section names (used in the tabs, summary and PDF) are in the page code in several places, so renaming a section is not done in the editor.

The blank printable sheets are built from the tests automatically, so they always match.
