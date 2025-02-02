# CSS Full Theory  
Learn CSS (Cascading Style Sheets) from basics.  

### Benefits of CSS:
- Keeps code clean and maintainable by separating styles from content.  

------------------------------------------------------------------------

## 01 - Introduction to CSS  

CSS can be applied in three ways:  
- **Internal CSS**: Defined within the `<style>` tag in the HTML `<head>`.  
- **Inline CSS**: Applied directly to an element using the `style` attribute.  
- **External CSS**: Defined in a separate `.css` file linked to the HTML.  

------------------------------------------------------------------------

## 02 - CSS Selectors  

### Simple Selectors:  
- **Class Selector (`.`)**: Targets elements with a specific class name.  
- **ID Selector (`#`)**: Targets a unique element with a specific ID.  

### Other Selectors:  
- **Universal Selector (`*`)**: Selects all elements in the document.  
- **Grouping Selector**: Combines multiple selectors with a comma to apply the same style to them.  

### Specificity:  
- **ID > class**: ID selectors have higher specificity than class selectors.  


### - Combinator Selectors  

- **Descendant Selector (`div p`)**: Selects all `p` elements inside `div`.  
- **Child Selector (`div > p`)**: Selects direct children of a `div`.  
- **Adjacent Sibling Selector (`div + p`)**: Selects the first `p` immediately following `div`.  
- **General Sibling Selector (`div ~ p`)**: Selects all `p` siblings of `div`.  

### 04 - Pseudo Selectors and Elements  

- **`:hover`**: Applied when an element is hovered over by the user.  
- **`::before`**: Inserts content before an element’s actual content.  
- **`::after`**: Inserts content after an element’s actual content.  
- **`:focus`**: Applied when an element (like a form input) is focused on.  

### 05 - Attribute Selectors  

- **`p[class="demo"]`**: Selects `p` elements with the class "demo".  
- **`p[title~="flower"]`**: Selects `p` elements whose `title` attribute contains "flower".  
- **`p[title|="demo"]`**: Selects `p` elements whose `title` attribute starts with "demo".  
- **`p[class^="de"]`**: Selects `p` elements whose class starts with "de".  
- **`p[class$="mo"]`**: Selects `p` elements whose class ends with "mo".  
- **`p[class*="em"]`**: Selects `p` elements whose class contains "em".  

### 06 - CSS Comments  

- Use comments to make your code more readable and to leave notes for future reference.  
- **Syntax**: `/* Your comment here */`.  

### 07 - Better Comments Extension  

- **Purpose**: Helps in structuring comments with labels like `TODO`, `FIXME`, `NOTE`, and others to improve readability and manageability of your codebase.  

------------------------------------------------------------------------

Stay tuned for more CSS topics!
