# Turn to Page…

Choose-your-own-adventure stories from **The Black Root Press**, Portland, Oregon, as small web apps.

## Stories

| Story | Folder | Endings |
|---|---|---|
| The Last Zine on the Table | [`last-zine/`](last-zine/) | 3 |
| The Little Library at the End of the Road | [`little-library/`](little-library/) | 2 |
| The Gift That Wasn’t Yours | [`the-gift/`](the-gift/) | 3 |
| The Immortal Latte: A Mini Adventure | [`immortal-latte/`](immortal-latte/) | 3 |

Each story is one self-contained `index.html`: the text, the hand-drawn illustrations (inline SVG), styles and script are all in that file. The only outside requests are for Google Fonts, and the page falls back to Courier and Georgia without them.

## Running it

Open `index.html` in a browser. To put it online, turn on GitHub Pages (Settings → Pages → Deploy from branch → `main`, `/ (root)`). The landing page sits at the root, and each story sits at `/<folder>/`.

## Playing

- Tap a choice to turn to its page. On a keyboard, press **1** or **2**.
- The boxes in the top corner track which endings you've found. They're saved in your own browser only, separately for each story.
- Each page has its own link, such as `#page-3`, plus `#endings`.
- The first three stories come from the *Turn to Page…* zine; their pages are renumbered so every story starts on page 2.

Written by Luke Allis · The Black Root Press · theblackrootpress.com
