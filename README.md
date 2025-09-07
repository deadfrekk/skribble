
demo: https://cuts.neocities.org/skribbler

Updated demo, this time with tags: https://cuts.neocities.org/papirverksted/manus

i wanted to create an automated way to randomly offset each character in a paragraph.
this is what i came up with.

include a tag with the class "skribbler" and it will become a tag with the class skribbled with a paragraph tag with an unique id "paragraph0" (the number will increase).
inside N of paragraph, each character will become an inline style span element. 

blankspaces has been converted to a Three-per-em space, since the inline-block display option does not display a blank space.
usefull blankspaces with width can be found here: https://www.namecheap.com/visual/font-generator/whitespace/

this project is meant to be customized and was only ever a proof of concept.
