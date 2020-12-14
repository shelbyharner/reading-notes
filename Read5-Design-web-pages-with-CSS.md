# Read5 Design Web Pages with CSS

CSS allows you to create rules that will specify how the content of the the webpage will look. For example, color, font family and style, layout and navigation. 

## CSS Selectors
    - Universial selector: applies to all elements in the document (ex.* {})
    - Type selector: matches element names (ex. h1, h2, h3)
    - Class selector: matches an element whose class attribute matches the one after the period (ex. .note or p.note)
    - ID selector: matches an element whose attribute matches the value after the pound or hash symbol (ex. #introduction)
    - Child selector: matches an element that is a direct child of another (ex. li>a{})
    - Descendant selector: matches an element that is a descendent of another specified element (not only a direct child) (ex. p a {})
    - Adjacent sibling selector: matches an element that is the next sibling of another (ex. h1+p)
    - General sibling selector:  matches an element that is a sibling of another but it doesn't have to be the directly preceding element (ex. h1~p)

CSS treats HTML elements as if they were in their own box and uses rules to indicate how the elements should look. 

CSS rules usually go in their own document, however they can also appear within the HTML document. 

## CSS Color Codes
    - RGB Value (Values for red/green/blue expressed as numbers between 0-255)
    - Hex Codes (Values for red/green/blue in dexadecimal code - #xxyyzz)
    - Color names are preset to be used but are very limited in options
    - Hue shade of a color, can be saturation and brighness
    - Saturation is the amount of grey in a color
    - Brightness is how much black is in the color
