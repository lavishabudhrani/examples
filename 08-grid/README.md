# CSS Grid

Welcome to the **wonderful** world of CSS Grid!

If you have learned any sort of web layout technique(s) prior to this year, I have bad news: we've been hacking the web. The early creativity of web designers forced us to adopt properties and techniques which were never designed to do proper layout as we have in print for years. But we somehow made them work through many headaches and tears.

All major browsers implemented the CSS Grid specification in 2017. This has been a development [20 years in the making](https://alistapart.com/article/the-story-of-css-grid-from-its-creators). We can finally lay out web pages in a simple, logical way, without hacks (as it should be).

## First...

Download [Firefox](https://www.mozilla.org/en-US/firefox/).


## Examples

Notes about the examples in this repository:

- All the CSS is enclosed within `style` tags inside each page `head`. This is for the sake of simplicity. We are "prototyping" these examples. In any other situation, we would just put these rules in an external file. You should still continue to use external style sheets for everything, even applying grid. Making a CSS grid is *not* contingent on the rules being applied in `style` tags.

- The examples just lay out color boxes. This is for the sake of simplicity. Instead of these boxes, it might be your header, navigation, sections within a main, articles in a section, footer, etc. Grid can be applied to *anything.*

- The examples use a class to apply grid. Grid is *not* contingent on using a grid in order to work. Grid can be applied to any selector.


### 01 Define a Grid

Properties we'll cover:
  - `display`
  - `grid-template-columns`
  - `grid-template-rows`
  - `grid-auto-rows`
  - `grid-column-gap`
  - `grid-row-gap`
  - `grid-gap` (shorthand for `grid-column-gap`, `grid-row-gap`)

Additional information
  - The `fr` unit
  - `repeat()` notation
  - `minmax()` notation


### 02 Line Based Positioning

Properties we'll cover:
  - `grid-column-start`
  - `grid-column-end`
  - `grid-row-start`
  - `grid-row-end`


### 03 Named Lines

Properties we'll cover:
  - `grid-column` (shorthand for `grid-column-start`, `grid-column-end`)
  - `grid-row` (shorthand for `grid-row-start`, `grid-row-end`)

Additional information:
  - [bracket] notation


### 04 Magic Lines, Part 1

Properties we'll cover:
  - `grid-area`


### 05 Grid Template Areas

Properties we'll cover:
  - `grid-template-areas`


### 06 Magic Lines, Part 2

Additional Information
- Using grid lines to overlay an element on the grid.


### 07 Contingency Plans

Properties we'll cover:
  - `@supports`

### 08 Extra: Mobile Grid

Additional Information
  - Adding responsiveness through `@media` queries


## Additional Resources

- [Grid By Example](https://gridbyexample.com/) Rachel Andrews' ultimate resource for all-things CSS Grid: articles, examples, patterns, tutorials, etc.
- [Grid By Example: Video Tutorial](https://gridbyexample.com/video/) Andrews' fantastic 19-part  introduction to CSS Grid.
- [Layout Labs](http://labs.jensimmons.com/): Jen Simmons' testing ground for new layout techniques.
- [*The New CSS Layout*, Ch. 3](https://alistapart.com/article/the-new-css-layout-excerpt): An excerpt from Andrews' new book on CSS layout. If you would like to [purchase a copy](https://abookapart.com/products/the-new-css-layout) (~$10, ebook).
