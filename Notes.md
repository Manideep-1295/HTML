## What is CSS?
Cascading Style Sheets
- Giving skin to your skeleton page

## Types of CSS
1. Inline CSS
![Inline CSS](image.png)
2. Internal CSS  
Preferred for initial load of the html page  
Keep it short and sweet
3. External CSS  
Preferred for reusability and separation  
![Internal & External CSS](image-1.png)

## CSS Terminology
![CSS Terms](image-2.png)

## CSS Stylings
### Text Styling - I  
1. font-size
2. font-weight
3. font-style //Italic,underline 
4. color
    - Color Name
    - RGB (x,y,z) Where x,y,z ∈ 0 to 255
    - Using Styles tab in inspect
    - HEX representation
    - rgba() a ∈ 0 to 1 which is responsible for opacity
    - hsl(hue(color), saturation, lightness)
    - lch () -> Better color gammet(sRGB)
    - sRGB(), DCP, Adobe sRGB -> Color Gammets
### Text Styling - II
1. text-transform - Case changing
2. text-align - left,right
3. text-decoration - underline,link
4. letter-spacing
5. line-height

#### Font Family
1. Serif - In latin it means Decoration
2. Sans Serif - Sans means NO in latin
- Dont add more than 3 fonts in your webpage, beacause the loading time of these fonts is more.

### Para vs Anchor
Para elements print the content in a new line while the anchor tag prints it side by side
Because Para elements occupy the entire width of the parent tag. Its because the display is block 
Where anchor is inline.
All the block elements take the entire width of the container
Block elements :
All header tags 
Inline elements :
span, anchor etc.
span - inline element
div - block element