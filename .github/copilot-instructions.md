# Project rules

- Keep the app self-contained in `index.html`; it has no dependencies or build step. Open that file directly in a browser to run it.
- Keep quiz data in the `questions` array. Each `correct` value is the zero-based index of its answer.
- When changing the number of questions, update the displayed total, progress ARIA maximum, and results denominator too.
- Use the existing CSS variables for colors and keep light and dark themes in sync.
- Preserve keyboard access, visible focus, screen-reader feedback, and reduced-motion support.
- There is no configured test or lint command. Verify UI changes in the integrated browser.
