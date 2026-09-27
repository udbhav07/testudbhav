# testudbhav

Test pages for the [AccessAI](https://github.com/RushiVivek/AccessAI-AG33) project.
They are **deliberately inaccessible**: scan them with AccessAI to see what it
fixes and how it verifies its own changes.

| Page | What's wrong with it |
|---|---|
| [experiment.html](https://udbhav07.github.io/testudbhav/experiment.html) | Images without alt text, missing and wrong form labels, low-contrast text |
| [demo_all_sources.html](https://udbhav07.github.io/testudbhav/demo_all_sources.html) | Low contrast set in all four places colour can live: inline styles, legacy HTML attributes, a `<style>` block, and an external stylesheet |

The originals live in AccessAI's `backend/tests/fixtures/`, where the automated
tests use them. If you change a page there, copy it here as well.
