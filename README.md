# grid-resize
Resizing a grid on hover

I wanted to see if we can easily have a grid based layout that shifts all elements when one is hovered.

One fly in the ointment is the text, something like https://kizu.dev/fit-to-width/ looks interesting, however a bit complicated. Therefore I have just used container queries and clamp.

I used css vars for the grid, and change those on hover.

This takes advantage of `has`, eg `.grid:has(.left:hover)`.