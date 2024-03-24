# A very common website feature

The goal of this exercise is to recreate a section that is found on many informational websites.

For this one you will need to edit the HTML a little bit too. We can't be making things _too_ easy for you. You'll want to add containers around the various elements so that you can flex them. Good luck!

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- All items are centered on the page (horizontally, not vertically).✅
- The title is centered on the page.
    - changing `text-align` of `body` would do. I used flex box in this case which took a couple more lines.
- There is 32px between the title and the 'items.'✅
    - `margin-bottom`
- There is 52px between each item.✅
    - `gap`
- The items are arranged horizontally on the page.✅
- The items are only 200px wide and the text wraps.✅
    - `max-width`
    - **text did wrap without mentioning any property in the CSS**
- The item text is centered.✅
    - `justify-content` and `text-align`
