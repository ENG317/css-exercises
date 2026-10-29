# Exercise 5 - Enter the Grid

**FIRST: Open this README in Preview mode**

**Goal**: Recreate a layout that you find in the wilds of the world with CSS `grid`. Wireframe it or snap it as an image, and include it in your project folder. If your rendering looks great on a laptop-size screen, you're good for now. We will spend some time working on grid flexibility with `@media` queries soon!

Past students have recreated the layout scheme that they inferred by deconstructing:

* a wall of posters,
* furniture position in a room,
* book/shelves,
* wall of a stonework building with windows/doors, etc.,
* cubism artwork,
* a star constellation,
* and so on ...

You can use placeholder content and images (see [https://placehold.co/](https://placehold.co/)), if you'd like.

## Version Control Requirement

You must iterate your design via multiple commits that prove you are not using generative AI to create this assignment. This is essential, because I want you to learn how to develop layouts on your own. I want you to learn this technique, not prompt a computer how to potentially do it for you.

I realize that you still could iteratively prompt this work. However, I will be quizzing you in class, potentially multiple times, after this assignment to test your grid-making skills to assess your capabilities.

## Folder Setup

Follow this procedure to setup your coding folder:

1. Within this root folder, create a new folder with your lastname.
   - **NOTE** `lastname` is your last name. Mine would be: `lindgren`.
2. Inside the root of *your personal coding folder*, create the an HTMl file named `index.html`.
3. Again, inside the root of *your personal coding folder*, create an `assets` folder.
4. Inside `assets`, create a `.keep` file, add your wireframe image, and create a `css` folder.
5. Inside `css`, create `grids.css` to link to `index.html`.
6. `※\(^o^)/※` Start writing some code! `※\(^o^)/※`

**Learning Objectives**:

Learn grid terminology and practice applying `grid-template-columns` &amp; new grid values (`fr`, `min` and `max` content, `minmax()`, and `repeat()`)

1. Apply the following terms:
   * grid container and items
   * grid lines and line numbers
   * grid tracks
   * grid cells vs. areas
   * implicit vs. explicit grids
   * grid gaps
   * New values: `fr`, `min-content`, `max-content`, `minmax()`, `repeat()`
2. Setup a grid container with grid items.
3. Infer from your layout source, what HTML structure and content will create a *grid_container* --> *grid_items* (children) relationship appropriate for your design concept.
4. Apply at least the following rules to create your concept in CSS with grid:
   1. `grid-template-columns`
      * Values for `grid-template-columns`: use some variation, as needed, with the new `fr` unit, perhaps some other sizing unit (px, %, em, rem, vw, etc.) and the `repeat()` and `minmax()` notation.
   2. `grid-template-rows` is optional, due to "implicit" grids.
   3. `gap`: Apply spacing between grid items.

## Important Warnings & Tips

### Warnings

- Be careful where and how you apply **absolute values** to elements.
   - Absolute values **fix the size**.
   - If you shrink the viewport width, some elements may break your grid cell/area.

### Tips

- Open your site with the live server tool in your browser.
- Practice using the browser's specific grid inspection tool.
- If you'd like to spice it up with your own flare, feel free to practice some basic typography and color schemes.
- Keep practicing the art of documenting your code and writing your CSS from more general rules to more specific in the HTML source order.
