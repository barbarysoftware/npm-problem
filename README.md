## Instructions

1. Install all npm dependencies
2. Run `npm run convert-board-css`

This makes a copy the file `./css/board.css` called `./css/embedded-board.css` with all rem measurements changed to px

## The problem

The postcss-rem-to-responsive-pixel plugin, by default, converts 1 rem to 16 px.

But I need to convert 1 rem to 10 px.

The postcss-rem-to-responsive-pixel can be configured, but as a beginner at both npm and postcss, I can't understand the config instructions for postcss-rem-to-responsive-pixel. It seems to use a different structure than we currently use in postcss.config.js

