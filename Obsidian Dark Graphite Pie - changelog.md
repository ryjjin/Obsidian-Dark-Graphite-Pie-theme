## v.0.9.3:

- line indents in lists in text editing mode are now the same (earlier, starting from the second line in the list item, the text was shifted by 1-2 characters)
- fonts and font sizes in edit mode and preview mode are now the same
- the text is no longer crossed out in the completed checklist items
- completed checklist items are painted over with red gray (I wanted to make the same color as in the text editing mode, but there is some strange filter for color, everything is not_chb repainted in generally other colors)
- page preview when hovering over the link has become larger

## v.0.9.4:

- in the menu, the color of the headers was corrected (after the update, instead of white on a dark gray background, it became gray on a dark gray background)
- the completed checklist items are painted over with the accent color (found a color filter in the settings and turned it off)
- fixed the color of the text in the buttons in the menu (everything was fine in the dark theme, but in the light theme there was a gray font on a gray background, the button text was almost invisible)

## v.0.9.9:

- fixed light theme colors when opening the command list via ctrl + P
- fixed font colors in backlinks module (titles were hard to read)

## v.0.10.4:

- reduced indentation at the bottom of the file tree (appeared in versions 0.10.+)
- removed the disappearance of coloring of the line with the name of the active file when you hover over it with the mouse pointer (appeared in version 0.10.+)
- pop-up page preview no longer disappears if the distance to the bottom of the page is less than the preview size, and does not affect the display of the current page
- text colors and text highlighting in the tag bar and table of contents are now like in the navigation menu

## v.0.10.5:

- changed the way of rendering the completed checklists (the appearance has changed a little, but now they should be rendered the same on both Win and Mac devices, regardless of the screen resolution)
- indents of lines in checklists in preview mode are now aligned (previously there was a shift of 1-2 characters between the first and next lines of text if the checklist item took more than one line), the indentation sizes are now attached not to pixels, but to units of characters