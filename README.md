# Morrow Coffee Responsive Website

## Project overview
Morrow Coffee is a cafe landing page built with semantic HTML and CSS. It introduces the cafe, shows three menu items, and provides location and opening-hour details.

## Responsive layout
- Above 820 px: the hero uses two columns and the menu shows three cards in a row.
- At 820 px and below: the menu changes to two columns.
- At 560 px and below: navigation moves to a second row, the hero stacks, and menu cards become horizontal rows.

## Techniques used
The page uses CSS Grid, media queries, flexible heading sizes with `clamp()`, and responsive images with `aspect-ratio` and `object-fit`. It also includes image descriptions, keyboard focus styles, and reduced-motion support.

## Design challenges
The main challenge was keeping menu text readable as the screen became narrower. The layout changes card arrangement at tablet and mobile widths instead of only shrinking the text.

## Viewport review
Check the page at 1440 px, 768 px, and 390 px. Look for horizontal scrolling, overlapping text, readable menu cards, and images that keep their proportions.
