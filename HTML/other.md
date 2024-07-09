# अन्य HTML तत्व (Other HTML Elements)

## इमेज (Images)
HTML में इमेज को `<img>` टैग के माध्यम से जोड़ा जाता है। `src` एट्रिब्यूट इमेज के स्थान को निर्दिष्ट करता है और `alt` एट्रिब्यूट वैकल्पिक टेक्स्ट को निर्दिष्ट करता है।
```html
<img src="image.jpg" alt="Description of image">
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Image Example</title>
</head>
<body>
    <h2>Image</h2>
    <img src="image.jpg" alt="Beautiful scenery">
</body>
</html>
```

## टेक्स्ट लिंक (Text Links)
टेक्स्ट लिंक बनाने के लिए `<a>` टैग का उपयोग किया जाता है। `href` एट्रिब्यूट लिंक के गंतव्य को निर्दिष्ट करता है।
```html
<a href="https://www.example.com">Visit Example</a>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Text Link Example</title>
</head>
<body>
    <h2>Text Link</h2>
    <a href="https://www.example.com">Visit Example</a>
</body>
</html>
```

## इमेज लिंक (Image Links)
इमेज लिंक बनाने के लिए `<a>` टैग के भीतर `<img>` टैग का उपयोग किया जाता है।
```html
<a href="https://www.example.com">
    <img src="image.jpg" alt="Description of image">
</a>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Image Link Example</title>
</head>
<body>
    <h2>Image Link</h2>
    <a href="https://www.example.com">
        <img src="image.jpg" alt="Beautiful scenery">
    </a>
</body>
</html>
```

## नई विंडो या टैब में पेज खोलना (Opening a Page in New Window or Tab)
नया पेज नई विंडो या टैब में खोलने के लिए, `<a>` टैग में `target="_blank"` एट्रिब्यूट का उपयोग किया जाता है।
```html
<a href="https://www.example.com" target="_blank">Open in new tab</a>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Open in New Tab Example</title>
</head>
<body>
    <h2>Open in New Tab</h2>
    <a href="https://www.example.com" target="_blank">Open Example in new tab</a>
</body>
</html>
```

## पेज के एक ही भाग को लिंक करना (Linking to an Area of the Same Page)
पेज के एक ही भाग को लिंक करने के लिए, एंकर (`id` एट्रिब्यूट) और लिंक में `href="#id"` का उपयोग किया जाता है।
```html
<a href="#section1">Go to Section 1</a>
...
<h2 id="section1">Section 1</h2>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Same Page Link Example</title>
</head>
<body>
    <h2>Linking to an Area of the Same Page</h2>
    <a href="#section1">Go to Section 1</a>
    <a href="#section2">Go to Section 2</a>
    
    <h2 id="section1">Section 1</h2>
    <p>This is section 1.</p>
    
    <h2 id="section2">Section 2</h2>
    <p>This is section 2.</p>
</body>
</html>
```

## तालिका टैग का परिचय (Introduction to Table Tags)
HTML में तालिका बनाने के लिए `<table>`, `<tr>`, `<th>`, और `<td>` टैग्स का उपयोग किया जाता है।
```html
<table>
    <tr>
        <th>Heading 1</th>
        <th>Heading 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Table Example</title>
</head>
<body>
    <h2>Table</h2>
    <table border="1">
        <tr>
            <th>Heading 1</th>
            <th>Heading 2</th>
        </tr>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </table>
</body>
</html>
```

### तालिकाओं के लाभ और सीमाएं (Advantages and Limitations of Tables)

#### लाभ (Advantages)
- डेटा का सुव्यवस्थित प्रस्तुतीकरण
- संख्यात्मक डेटा को समझना आसान

#### सीमाएं (Limitations)
- लचीलेपन की कमी
- मोबाइल उपकरणों पर अच्छी तरह से प्रदर्शित नहीं होता
- CSS ग्रिड और फ्लेक्सबॉक्स के साथ अधिक आधुनिक लेआउट विकल्प

## फ्रेम्स और आईफ्रेम्स (Frames & IFrames)

### आईफ्रेम (IFrame)
दूसरे HTML पेज को एम्बेड करने के लिए।
```html
<iframe src="https://www.example.com" width="300" height="200"></iframe>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>IFrame Example</title>
</head>
<body>
    <h2>IFrame</h2>
    <iframe src="https://www.example.com" width="300" height="200"></iframe>
</body>
</html>
```

## HTML फॉर्म्स (HTML Forms)
फॉर्म बनाने के लिए `<form>`, `<input>`, `<label>`, `<textarea>`, `<button>`, `<select>`, और `<option>` टैग्स का उपयोग किया जाता है।
```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <textarea id="message" name="message">Enter your message here</textarea>
    <button type="submit">Submit</button>
</form>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Form Example</title>
</head>
<body>
    <h2>Form</h2>
    <form action="/submit" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="message">Message:</label>
        <textarea id="message" name="message">Enter your message here</textarea><br><br>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```

## XHTML का परिचय (Introduction to XHTML)
XHTML (Extensible HyperText Markup Language) HTML का एक कठोर संस्करण है, जो XML के नियमों का पालन करता है। XHTML दस्तावेज़ को सही ढंग से पार्स करने के लिए इसे ठीक से स्वरूपित किया जाना चाहिए।

### XHTML का उदाहरण (XHTML Example)
```xhtml
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>XHTML Example</title>
</head>
<body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
    <img src="image.jpg" alt="Description of image" />
</body>
</html>
```

### XHTML की विशेषताएं (Features of XHTML)
- सभी टैग्स को ठीक से बंद किया जाना चाहिए।
- सभी टैग्स को लोअरकेस में लिखा जाना चाहिए।
- सभी एट्रिब्यूट्स को उद्धरण चिह्नों में बंद किया जाना चाहिए।