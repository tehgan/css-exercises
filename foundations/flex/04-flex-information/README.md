# A very common website feature

The goal of this exercise is to recreate a section that is found on many informational websites.

For this one you will need to edit the HTML a little bit too. We can't be making things _too_ easy for you. You'll want to add containers around the various elements so that you can flex them. Good luck!

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- <s>All items are centered on the page (horizontally, not vertically).</s> (`align-text` title, `justify-content` main *(row of plant items)*)
- <s>The title is centered on the page.</s> (`align-text` title; doesn't need to be flexbox, only one element, width is implicitly set to auto meaning it scales with browser window)
- <s>There is 32px between the title and the 'items.'</s> (`margin-bottom: 32px` title)
- <s>There is 52px between each item.</s> (`gap: 52px` main)
- <s>The items are arranged horizontally on the page.</s> (`justify-content: center` main)
- <s>The items are only 200px wide and the text wraps.</s> (`max-width: 200px` plant, text wraps implicitly)
- <s>The item text is centered.</s> (`text-align: center` plant (inherited by text))
