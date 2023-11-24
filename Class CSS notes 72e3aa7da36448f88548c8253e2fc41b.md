# Class CSS notes

**Margin**

are used to create space around elements 

**Padding**

used to create space around an elements content, inside of any defined borders

# The CSS font-family Property

In CSS, we use the `font-family` property to specify the font of a text.

| Serif | Times New RomanGeorgiaGaramond |
| --- | --- |
| Sans-serif | ArialVerdanaHelvetica |
| Monospace | Courier NewLucida ConsoleMonaco |
| Cursive | Brush Script MTLucida Handwriting |
| Fantasy | CopperplatePapyrus |

```html
.p1 {
  font-family: "Times New Roman", Times, serif;
}

.p2 {
  font-family: Arial, Helvetica, sans-serif;
}

.p3 {
  font-family: "Lucida Console", "Courier New", monospace;
}
```

# CSS [attribute] Selector

The `[attribute]` selector is used to select elements with a specified attribute.

The following example selects all <a> elements with a target attribute:

# Example

```html
a[target] {  background-color: yellow;}
```

# CSS [attribute="value"] Selector

The `[attribute="value"]` selector is used to select elements with a specified attribute and value.

```html
a[target="_blank"] {
```

```html
background-color: yellow;
```

```html
}
```

`c**olor**`

 Sets the text color of an element.

```html
**color: blue**
```

**`font-size`:**

 Specifies the size of the font.

 

```html
**font-size: 16px;**
```

**`margin`:**

Sets the margin space around an element.

```html
 **margin: 10px;**
```

**`padding`:**

Specifies the padding space inside an element.

```html
 **padding: 20px;**
```

**`background-color`:**

 Sets the background color of an element.

```html
 **background-color: #ecf0f1;**
```

**`border`:**

 Defines the border properties of an element.

 

```html
**border: 1px solid #ddd;**
```

**`text-align`:**

 Sets the horizontal alignment of text content.

```html
 **text-align: center;**
```

**`display`:**

 Specifies how an element should be displayed.

```html
 **display: block;**
```

**`width`:**

 Sets the width of an element.

```html
 **width: 300px;**
```

**`height`:**

 Sets the height of an element.

```html
 **height: 150px;**
```