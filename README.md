# Mash Up Like the Masters, ver. 1
The first iteration of "Mash Up Like the Masters" project made with JavaScript and p5.js. 
The project was ideated, prototyped and coded in NYU class Interactive Computing with professor Craig Kapp.

The experience allows the user to mash pieces of the 20th century's most famous artworks together and create collages that can be saved. There are two possible approaches: educational and inspiration-searching.

Educationally, the user is encouraged to critically think about the artwork they are modifying and infer the meaning artists put into creation of their art objects. There is a "Learn and Get Inspired" tab that gives a context on the time the artists lived and their place of origin; each artist's profile is linked to their corresponding page on the MoMA website.

For all those who are searching for inspiration, this is a perfect opportunity to experimentally mash different styles, colors and patterns for unexpected discoveries. Looking for the juxtapositions to form dynamically? Animate your canvas (and stop them at any point) for more unexpected contrasts and encounters.

This project builds on an idea of natural learning happening through rapid juxtapositions of our old and new knowledge, as well as stark contrasts or notable similarities between seemingly unrelated pieces of art. The interface presents a unique opportunity for the user to interactively compare, contrast, juxtapose, and see how collisions of different styles and ideas give birth to new ways of seeing.

## Technical documentation
- An off-screen buffer for the canvas (p5.js)
- Tabbing logic (js) to navigate between different panels
- A dropdown filter that controls which assets get generated for each artist (js)
- An onclick function allowing to choose an asset and make it appear on the canvas based on the mouse position (js + p5.js)
- HTML buttons with event handlers to let the user modify the objects or canvas in various ways

