# HTML-accessibility-design
Contrast:
With contrast, I design such that the forground texts and image have sufficient contrast with the background colors to make the image clearer and improves texts readability .

Color usage:
Since some users could be blind, I putbthatinto consideration and don’t rely only on color to convey information. Rather, I used the asterisk symbol to tell the user which field is mandatory.

Focus:
For the keyboard navigation, I used a red highlight that moves as you tab through the page.

Interactivity:
Imused the mouse over style to provide distinct color fornthe button elemrnt such that the color changes to greenyellow when hovered.
I ensure the field and the checkbox have a descriptive label adjacent to them
I grouped content into mainheading and subheading using different text sizes so it is easier to scan through

Image and media alternatives.
I included an alt for the image using the text"Picture of a woman coding" as required.

ARIA
I added a role attribute to my checkbox div element, then on my accessibility tree, Role:checkbox and Checked:false are displayed.
To change the false to true, I added an aria-check="true" attribute.
Now the screen reader diplays Checked,Checkbox.
