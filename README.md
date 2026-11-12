# Turn to Page…

Choose-your-own-adventure stories from **The Black Root Press**, Portland, Oregon, as small web apps.

## Stories

| Story | Folder | Endings |
|---|---|---|
| The Immortal Latte: A Mini Adventure | [`immortal-latte/`](immortal-latte/) | 3 |

Each story is one self-contained `index.html`: the text, the hand-drawn illustrations (inline SVG), styles and script are all in that file. The only outside requests are for Google Fonts, and the page falls back to Courier and Georgia without them.

## Running it

Open `index.html` in a browser. To put it online, turn on GitHub Pages (Settings → Pages → Deploy from branch → `main`, `/ (root)`). The landing page sits at the root, and each story sits at `/<folder>/`.

## The Immortal Latte

- Tap a choice to turn to its page. On a keyboard, press **1** or **2**.
- The cups in the top corner track which endings you've found. They're saved in your own browser only.
- Each page has its own link: `#page-2` … `#page-7`, plus `#endings`.

Written by Luke Allis · The Black Root Press · theblackrootpress.com
