# An entire page!

Flexbox is useful for laying out entire pages as well as the smaller components we've already been working with. For this exercise, we're leaving you with a little more work to do, with some things you may not have encountered yet. It's perfectly acceptable to google things you're unsure of!

### Hints
- You may want to search something like `CSS remove list bullets`.  We've done this for you in previous examples, but not here. Yay learning.
- Finding out how to style links in CSS might help you get rid of that pesky underline decoration...
- We've added `height: 100vh` to the `body`... this makes the body exactly the same height as the viewport. To stick the footer to the bottom you will need to use flex and change the direction to column.

## Desired Outcome
![desired outcome](./desired-outcome.png)

### Self Check

- The header is at the top of the page, the footer is at the bottom, and they stay in place if you resize your screen.
  - *Mostly*; footer won't overlap the content, so overflow begins at ~425px on my browser (3840x2160 1.5x scale)
- The header and footer have padding.
  - `padding: 0 16px` *(vertical, horizontal)*
  - Links are `ul` so they had to have their `padding-left` explicitly set to `0` (`40` by-default in Firefox and Chromium)
- The links in the header and footer are pushed to either side.
  - `header` and `footer` are both `display: flex` with `justify-content: space-between`
- There is space between the links in the header and footer.
  - Both `header` and `footer` were given a `gap: 16px`
- The footer has a light gray background (`#eeeeee`).
- The logo, input and buttons are centered in the screen.
  - `body` is `display: flex` with `flex-direction: column` and `justify-content: space-between`.
  - 3 elements; `header`, `content`, and `footer`, so each element goes where they need to.
- The buttons have an appropriate amount of padding.
  - `padding: 8px`
- There is space between the logo, input and buttons.
  - `.content` has `gap: 16px`
