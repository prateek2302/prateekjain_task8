# Laundry Services Hamburger Menu in Mobile

## Problem Description
This project implements a mobile hamburger menu for the Laundry Services web page without using any JavaScript or external frameworks (such as Bootstrap).

## Implementation Highlights
1. **No JavaScript**: Handled menu toggling entirely in pure CSS using the `:focus` pseudo-class on the button and sibling selector combinators (`+` and `:focus-within`).
2. **Hidden by default**: The desktop navigation links are hidden on mobile viewports via media queries, and the hamburger button is enabled.
3. **Menu List Styling**: Positioned absolutely/fixed on the right side of the screen with a dark backdrop matching the assignment specifications.
4. **Pure CSS**: Uses responsive units and flexbox layout.