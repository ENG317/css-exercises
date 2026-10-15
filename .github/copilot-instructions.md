# Copilot instructions for this repository

## Project purpose
This repository is a collection of static HTML/CSS exercises for NCSU ENG 317. It is not a production web app or a JavaScript project: the work is primarily markup and stylesheet changes intended to be viewed in a browser and checked with DevTools.

The top-level structure is organized by assignment:
- `1-selection/`: selector and layout practice using a card-based page.
- `2-sizing-units/`: exercises focused on CSS units (`px`, `vw`, `%`, `em`, `rem`) and image sizing.
- `3-typography/`: typography and color-system exercises using CSS variables and multiple vibe/style-guide examples.

Each exercise folder includes its own `README.md` with assignment-specific instructions. Read the relevant exercise README before making changes.

## Build, test, and lint commands
There are no build, test, or lint scripts configured in this repository.

- No `package.json`, `Makefile`, or CI toolchain is present.
- There is no automated test suite for HTML/CSS.
- There is no single “unit test” command to run for these exercises.

Validation for this repo is visual and browser-based:
- Open the relevant `.html` file in a browser or with a VS Code live preview/Live Server extension.
- Use browser DevTools to inspect rendered layout and confirm CSS changes.
- Treat the README instructions for each exercise as the acceptance criteria.

## High-level architecture
This repo is intentionally simple and assignment-driven:
- The root `README.md` contains course-level notes and explicit guidance about working within student folders.
- Each exercise folder is a self-contained mini-project with starter HTML/CSS files.
- Several folders include a template file such as `copyme.html`, `copyme.css`, or `tocopy.html`/`tocopy.css` that students copy and rename for their own work.
- Student work usually lives beside the starter files within the same assignment folder or in a renamed subfolder, rather than in a shared application structure.

The codebase does not have a framework layer, bundler, or server runtime. The important “architecture” is the relationship between:
- HTML structure in the exercise page
- CSS selectors and declarations in the stylesheet
- browser rendering and DevTools inspection

## Key conventions and repository-specific patterns
- Read the assignment README before editing: the instructions are part of the work product and often spell out naming and structure requirements.
- Do not overwrite the original starter/template files if the exercise expects students to copy and rename them first.
- In exercises like `1-selection`, keep student work in their own named copy of the HTML/CSS files and update the stylesheet link in the HTML.
- Use the class and ID naming patterns already established in the starter files when completing exercises. The assignments intentionally teach selector patterns and component names.
- The CSS files often use comments as section headings to document the exercise steps. Keep those headings when they help organize the work.
- Favor direct, assignment-specific CSS rules over introducing extra tooling or abstraction; this repo is designed to teach fundamentals, not framework-driven patterns.
- Treat `:root` variables and component/class naming patterns as part of the course conventions when they appear in a given exercise.

## Working style in this repo
- Keep changes focused to the assignment being worked on.
- Prefer small, testable iterations in the browser rather than large, speculative CSS rewrites.
- Use browser inspection to confirm selectors and computed styles before moving to the next prompt in the exercise.
- When adding new markup or CSS, aim for the structure expected by the assignment README and the starter template.

## When helping in Copilot sessions
- Respect the classroom context: this repository is instructional and intentionally hands-on.
- Avoid turning these exercises into a framework-based app or adding unrelated tooling.
- Prefer checking the exercise-specific README and the starter template before proposing file edits.
- Keep guidance aligned with the assignment, not with general production-web practices.
