# Cascading Style Sheets (08 Periods)

## परिचय (Introduction)
Cascading Style Sheets (CSS) एक स्टाइल शीट भाषा है जिसका उपयोग HTML तत्वों को स्वरूपित करने के लिए किया जाता है। CSS वेब पेज की उपस्थिति और लेआउट को नियंत्रित करता है।

## CSS के लाभ (Benefits of CSS)
- **डिज़ाइन में सुधार**: CSS का उपयोग करके वेब पेज की डिज़ाइन को बेहतर बनाया जा सकता है।
- **कोड पुन: प्रयोज्यता**: एक ही CSS फाइल को कई HTML पेजों में उपयोग किया जा सकता है।
- **लोडिंग समय में सुधार**: CSS फाइल अलग से लोड होती है, जिससे पेज की लोडिंग गति तेज होती है।
- **अन्य तकनीकों के साथ संगतता**: CSS, HTML और JavaScript के साथ आसानी से एकीकृत होता है।

## CSS सिंटैक्स (CSS Syntax)
CSS नियम (rule) में एक चयनकर्ता (selector) और घोषणाएं (declarations) होती हैं। घोषणाओं में संपत्ति (property) और मान (value) शामिल होते हैं।
```css
selector {
    property: value;
}
```

### उदाहरण (Example)
```css
body {
    background-color: lightblue;
}

h1 {
    color: navy;
    margin-left: 20px;
}
```

## CSS कार्यान्वयन (CSS Implementation)

### 1. इनलाइन CSS (Inline CSS)
HTML तत्व के भीतर `style` एट्रिब्यूट का उपयोग करके।
```html
<p style="color:blue;">This is a blue paragraph.</p>
```

### 2. आंतरिक CSS (Internal CSS)
HTML दस्तावेज़ के `<head>` सेक्शन में `<style>` टैग के भीतर।
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: lightblue;
        }
    </style>
</head>
<body>
    <p>This is a paragraph.</p>
</body>
</html>
```

### 3. बाहरी CSS (External CSS)
बाहरी CSS फाइल का उपयोग करके, जिसे `<link>` टैग के माध्यम से HTML में जोड़ा जाता है।
```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <p>This is a paragraph.</p>
</body>
</html>
```

`styles.css`:
```css
body {
    background-color: lightblue;
}
p {
    color: blue;
}
```

## CSS चयनकर्ता (CSS Selectors)

### आईडी चयनकर्ता (ID Selectors)
एक विशिष्ट तत्व को स्टाइल करने के लिए।
```css
#unique-element {
    color: red;
}
```
```html
<p id="unique-element">This is a unique element.</p>
```

### क्लास चयनकर्ता (Class Selectors)
एक या अधिक तत्वों को स्टाइल करने के लिए।
```css
.highlight {
    background-color: yellow;
}
```
```html
<p class="highlight">This is highlighted text.</p>
<p class="highlight">This is also highlighted text.</p>
```

### समूह चयनकर्ता (Grouping Selectors)
एक ही स्टाइल को कई चयनकर्ताओं पर लागू करने के लिए।
```css
h1, h2, p {
    color: green;
}
```

### यूनिवर्सल चयनकर्ता (Universal Selectors)
सभी तत्वों को स्टाइल करने के लिए।
```css
* {
    font-family: Arial, sans-serif;
}
```

### CSS छद्म-क्लास (Pseudo-classes)
एक विशेष स्थिति में तत्वों को स्टाइल करने के लिए।
```css
a:hover {
    color: red;
}
```
```html
<a href="#">Hover over this link</a>
```

## CSS गुण (CSS Properties)

### बैकग्राउंड-कलर (background-color)
```css
body {
    background-color: lightblue;
}
```

### बैकग्राउंड-इमेज (background-image)
```css
body {
    background-image: url('background.jpg');
}
```

### बॉर्डर-स्टाइल (border-style)
```css
p {
    border-style: solid;
}
```

### ऊंचाई (height)
```css
div {
    height: 200px;
}
```

### चौड़ाई (width)
```css
div {
    width: 50%;
}
```

### रंग (color)
```css
p {
    color: blue;
}
```

### टेक्स्ट-अलाइन (text-align)
```css
h1 {
    text-align: center;
}
```

### फॉन्ट-फैमिली (font-family)
```css
p {
    font-family: Arial, sans-serif;
}
```

### फॉन्ट-स्टाइल (font-style)
```css
em {
    font-style: italic;
}
```

### फॉन्ट-साइज (font-size)
```css
h1 {
    font-size: 2em;
}
```

### फॉन्ट-वेट (font-weight)
```css
strong {
    font-weight: bold;
}
```

## बॉक्स मॉडल (Box Model in CSS)
CSS बॉक्स मॉडल प्रत्येक HTML तत्व को एक बॉक्स के रूप में मानता है जिसमें मार्जिन, बॉर्डर, पैडिंग और सामग्री होती है।

### मार्जिन (margin)
```css
div {
    margin: 20px;
}
```

### बॉर्डर (border)
```css
div {
    border: 1px solid black;
}
```

### पैडिंग (padding)
```css
div {
    padding: 10px;
}
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>CSS Example</title>
    <style>
        body {
            background-color: lightyellow;
            font-family: Arial, sans-serif;
        }
        #unique-element {
            color: red;
        }
        .highlight {
            background-color: yellow;
        }
        h1, h2, p {
            color: green;
        }
        a:hover {
            color: red;
        }
        div {
            width: 50%;
            height: 200px;
            margin: 20px;
            border: 1px solid black;
            padding: 10px;
        }
    </style>
</head>
<body>
    <h1>This is heading 1</h1>
    <h2>This is heading 2</h2>
    <p>This is a paragraph.</p>
    <p id="unique-element">This is a unique element.</p>
    <p class="highlight">This is highlighted text.</p>
    <a href="#">Hover over this link</a>
    <div>This is a box model example.</div>
</body>
</html>
```

इस उदाहरण में, हमने विभिन्न CSS गुणों और चयनकर्ताओं का उपयोग करके HTML पेज को स्टाइल किया है।
```