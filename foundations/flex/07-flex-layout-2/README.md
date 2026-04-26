# The Holy Grail of Layout

In this last flexbox exercise you're going to recreate an incredibly common website layout. It is so common that it is often called the [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img) layout... and with flexbox it is actually pretty easy to pull off.

As with the previous exercise, we've left a little more for you to do.

### Hints
- You will need to change the flex-direction to push the footer down.
- You will need to add some divs as containers to get things to line up correctly.
- `flex-wrap` will help get the cards aligned correctly.
-  Make sure you define how much space the cards should take up, in order for `flex-wrap` to work as intended.

## Desired outcome

![desired outcome](./desired-outcome.png)

The number of cards lined up in that section will change based on the width of your screen, so don't stress about getting _exactly_ a 2x3 or 3x2 grid.

On a smaller screen it will look like this:

![smaller](./desired-outcome-smaller.png)

Note: The emojis may instead show up as one or several text symbols (e.g. &#9734;&#9794;) if you don't have an emoji-based font family installed on your operating system. This does not affect the exercise and can be ignored.

### Self Check
- <s>The header text is size 32px and weight 900.</s>
- <s>The header text is vertically centered and 16px from the edge of the screen.</s>
  - Vertically centered by making `line-height` the same as the header's height (`72px`)
  - `padding-left: 16px`
- <s>The footer is pushed to the bottom of the screen (the footer may go _below_ the bottom of the screen if the content of the 'cards' section overflows and/or if your screen is shorter).</s>
  - Doesn't occur on my monitor (all 6 cards fit vertically), but seems to occur when zoomed, so this is likely fulfilled.
- <s>The footer text is centered horizontally and vertically.</s>
  - `line-height` again, for vertical centering (`72px`)
  - `text-align: center` for horizontal centering
- <s>The sidebar and cards take up all available space above the footer.</s>
  - sidebar/cards wrapped in a `content` div, said div set to `display: flex`, `flex-grow: 1` *(default is 0, so it uses all space between header and footer)*
- <s>The sidebar is 300px wide (and it doesn't shrink).</s>
  - `flex-shrink: 0` set on sidebar class
- <s>The sidebar links are size 24px, are white, and do not have the underline text decoration.</s>
- <s>The sidebar has 16px padding.</s>
  - Sidebar has `padding: 16px` and `li` elements have `padding-bottom: 16px` to bring them more in-line with the example images
- <s>There is 48px padding around the 'cards' section.</s>
  - `padding: 48px` in `.card-container` class
- <s>The cards are arranged horizontally, but wrap to multiple lines when they run out of room on the page.</s>
