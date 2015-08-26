# Glyph Nanny

![Screen Shot](screenshot.png "Screen Shot")

This tool provides live feedback about the technical quality of a glyph. The goal is to help new type designers get through the "Beziers Are Frustrating!" phase a little more quickly. Keep in mind that the displayed notes and marks are generated by math and are not a definitive list of things that *must* be corrected. It's always (okay, not always) acceptable to break the rules as long as you have a good reason. Think of the comments as reminders to think through why you have things where they are.

If you want to turn the display on or off, or edit the list of tests performed, look under Extensions > Glyph Nanny in the application menu.

Also located under Extensions > Glyph Nanny in the application menu is an option for testing an entire font.

## Versions

### 0.3 (not yet released)

- Test for unnamed anchors.
- Test for stem width inconsistency. This uses the Stem Snap values defined in the PostScript hinting settings to determine the desired stem widths.
- Removed the "unusually high number of contours" test. It was very slow.


### 0.2

Minor bug fixes.

### 0.1

Initial version.