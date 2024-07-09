# HTML के सभी टैग्स (All HTML Tags)

## 1. दस्तावेज़ संरचना टैग्स (Document Structure Tags)

### `<html>`
HTML दस्तावेज़ की जड़ है।
```html
<html>
    <!-- Content goes here -->
</html>
```

### `<head>`
हेड सेक्शन मेटाडेटा और अन्य लिंक को शामिल करता है।
```html
<head>
    <title>Document Title</title>
</head>
```

### `<title>`
वेब पेज का शीर्षक निर्दिष्ट करता है।
```html
<title>Page Title</title>
```

### `<body>`
बॉडी टैग में वे सभी तत्व होते हैं जो वेब पेज पर प्रदर्शित होते हैं।
```html
<body>
    <!-- Content goes here -->
</body>
```

### `<meta>`
मेटाडेटा को निर्दिष्ट करता है।
```html
<meta charset="UTF-8">
<meta name="description" content="Free Web tutorials">
```

### `<link>`
बाहरी संसाधनों को लिंक करने के लिए।
```html
<link rel="stylesheet" href="styles.css">
```

### `<style>`
इंटर्नल CSS स्टाइल को निर्दिष्ट करने के लिए।
```html
<style>
    body { background-color: lightblue; }
</style>
```

## 2. टेक्स्ट प्रारूपण टैग्स (Text Formatting Tags)

### `<h1> - <h6>`
हेडिंग टैग्स, `<h1>` सबसे बड़ा और `<h6>` सबसे छोटा होता है।
```html
<h1>This is a heading</h1>
<h2>This is a heading</h2>
```

### `<p>`
पैराग्राफ टैग, टेक्स्ट को पैराग्राफ के रूप में प्रदर्शित करता है।
```html
<p>This is a paragraph.</p>
```

### `<b>` और `<strong>`
टेक्स्ट को बोल्ड बनाने के लिए।
```html
<b>This text is bold</b>
<strong>This text is strong</strong>
```

### `<i>` और `<em>`
टेक्स्ट को इटैलिक बनाने के लिए।
```html
<i>This text is italic</i>
<em>This text is emphasized</em>
```

### `<u>`
टेक्स्ट को अंडरलाइन करने के लिए।
```html
<u>This text is underlined</u>
```

### `<br>`
लाइन ब्रेक के लिए।
```html
This is a line break<br>Next line starts here.
```

### `<hr>`
हॉरिजॉन्टल रूल/लाइन।
```html
<p>This is a paragraph.</p>
<hr>
<p>This is another paragraph.</p>
```

## 3. लिस्ट टैग्स (List Tags)

### `<ul>` और `<li>`
अनऑर्डर्ड लिस्ट (बुलेटेड लिस्ट) के लिए।
```html
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
</ul>
```

### `<ol>` और `<li>`
ऑर्डर्ड लिस्ट (नंबर लिस्ट) के लिए।
```html
<ol>
    <li>List item 1</li>
    <li>List item 2</li>
</ol>
```

### `<dl>`, `<dt>`, और `<dd>`
डिफिनिशन लिस्ट के लिए।
```html
<dl>
    <dt>Coffee</dt>
    <dd>Black hot drink</dd>
    <dt>Milk</dt>
    <dd>White cold drink</dd>
</dl>
```

## 4. लिंक टैग्स (Link Tags)

### `<a>`
हाइपरलिंक के लिए।
```html
<a href="https://www.example.com">Visit Example</a>
```

## 5. इमेज टैग (Image Tag)

### `<img>`
छवियों को वेब पेज पर प्रदर्शित करता है।
```html
<img src="image.jpg" alt="Description of image">
```

## 6. तालिका टैग्स (Table Tags)

### `<table>`, `<tr>`, `<th>`, और `<td>`
टेबल बनाने के लिए।
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

## 7. फॉर्म टैग्स (Form Tags)

### `<form>`, `<input>`, `<label>`, `<textarea>`, `<button>`, `<select>`, और `<option>`
फॉर्म बनाने के लिए।
```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <textarea id="message" name="message">Enter your message here</textarea>
    <button type="submit">Submit</button>
</form>
```

## 8. मल्टीमीडिया टैग्स (Multimedia Tags)

### `<audio>` और `<video>`
ऑडियो और वीडियो सामग्री को एम्बेड करने के लिए।
```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

## 9. अन्य उपयोगी टैग्स (Other Useful Tags)

### `<div>`
ब्लॉक-स्तरीय डिवीजन या अनुभाग।
```html
<div>
    <p>This is a division.</p>
</div>
```

### `<span>`
इनलाइन डिवीजन या अनुभाग।
```html
<p>This is <span style="color: red;">red text</span> in a paragraph.</p>
```

### `<iframe>`
दूसरे HTML पेज को एम्बेड करने के लिए।
```html
<iframe src="https://www.example.com" width="300" height="200"></iframe>
```

### `<script>`
जावास्क्रिप्ट को एम्बेड करने के लिए।
```html
<script>
    alert('Hello, World!');
</script>
```

### `<noscript>`
उन ब्राउज़रों के लिए जो जावास्क्रिप्ट का समर्थन नहीं करते।
```html
<noscript>
    Your browser does not support JavaScript!
</noscript>
```

### `<canvas>`
ड्रॉइंग के लिए।
```html
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
    Your browser does not support the HTML canvas tag.
</canvas>
```

## निष्कर्ष (Conclusion)
यह HTML के सभी प्रमुख टैग्स का सारांश है। HTML टैग्स और उनके उपयोग को समझना वेब विकास का एक महत्वपूर्ण हिस्सा है।