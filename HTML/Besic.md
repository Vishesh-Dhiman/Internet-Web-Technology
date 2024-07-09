# HTML के मूल तत्व (Basics of HTML)

## HTML दस्तावेज़ (HTML Document)
HTML दस्तावेज़ एक टेक्स्ट फाइल होती है जिसे ब्राउज़र में वेब पेज के रूप में प्रदर्शित किया जाता है। HTML दस्तावेज़ का विस्तार `.html` या `.htm` होता है।

## HTML का मूल संरचना (Basic Structure of HTML)
HTML दस्तावेज़ की मूल संरचना निम्नलिखित होती है:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Document Title</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

### DOCTYPE घोषणा (DOCTYPE Declaration)
```html
<!DOCTYPE html>
```
यह HTML5 दस्तावेज़ की प्रकार को निर्दिष्ट करता है।

### HTML टैग (HTML Tag)
```html
<html>
```
यह टैग पूरे HTML दस्तावेज़ को इंगित करता है।

### हेड टैग (Head Tag)
```html
<head>
    <title>Document Title</title>
</head>
```
हेड टैग में मेटाडेटा और अन्य लिंक शामिल होते हैं।

### टाइटल टैग (Title Tag)
```html
<title>Document Title</title>
```
यह टैग वेब पेज का शीर्षक निर्धारित करता है जो ब्राउज़र टैब में दिखाई देता है।

### बॉडी टैग (Body Tag)
```html
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
</body>
```
बॉडी टैग में वे सभी तत्व होते हैं जो वेब पेज पर प्रदर्शित होते हैं।

## HTML सिंटैक्स (Syntax of HTML)
HTML टैग्स एंगल ब्रैकेट्स `< >` के भीतर होते हैं। प्रत्येक टैग का एक ओपनिंग टैग और एक क्लोजिंग टैग होता है।

### उदाहरण:
```html
<p>This is a paragraph.</p>
```
यहां `<p>` ओपनिंग टैग है और `</p>` क्लोजिंग टैग है।

## HTML टैग्स और एट्रिब्यूट्स (HTML Tags and Attributes)
HTML टैग्स तत्वों को निर्दिष्ट करते हैं, जबकि एट्रिब्यूट्स तत्वों के गुणों को निर्दिष्ट करते हैं।

### उदाहरण:
```html
<a href="https://www.example.com">Visit Example</a>
```
यहां `<a>` टैग है और `href` एट्रिब्यूट है।

## HTML टैग्स के प्रकार (Types of HTML Tags)

### 1. सिंगल टैग्स (Single Tags)
ये टैग्स स्वयं ही बंद हो जाते हैं।
```html
<img src="image.jpg" alt="Image">
<br>
```

### 2. डबल टैग्स (Double Tags)
ये टैग्स ओपनिंग और क्लोजिंग टैग्स के रूप में आते हैं।
```html
<p>This is a paragraph.</p>
<div>This is a division.</div>
```

## नेस्टिंग के नियम (Rules of Nesting)
HTML टैग्स को सही क्रम में नेस्ट किया जाना चाहिए। ओपनिंग टैग्स और क्लोजिंग टैग्स को सही ढंग से मिलाना आवश्यक है।

### गलत उदाहरण:
```html
<p>This is <b>bold text.</p></b>
```

### सही उदाहरण:
```html
<p>This is <b>bold text</b>.</p>
```

## बेसिक टैग्स (Basic Tags)

### HTML टैग (HTML Tag)
```html
<html>
```
यह टैग पूरे HTML दस्तावेज़ को दर्शाता है।

### हेड टैग (Head Tag)
```html
<head>
```
यह टैग मेटाडेटा और अन्य लिंक को शामिल करता है।

### टाइटल टैग (Title Tag)
```html
<title>
```
यह टैग वेब पेज का शीर्षक निर्धारित करता है।

### बॉडी टैग्स (Body Tags)
```html
<body>
```
यह टैग वेब पेज की सामग्री को शामिल करता है।

```html
<h1> - <h6>
```
हेडिंग टैग्स, `<h1>` सबसे बड़ा और `<h6>` सबसे छोटा होता है।

```html
<p>
```
पैराग्राफ टैग, टेक्स्ट को पैराग्राफ के रूप में प्रदर्शित करता है।

```html
<a>
```
एंकर टैग, लिंक को निर्दिष्ट करता है।

```html
<img>
```
इमेज टैग, छवियों को वेब पेज पर प्रदर्शित करता है।

## निष्कर्ष (Conclusion)
HTML वेब पेज बनाने के लिए मूलभूत भाषा है। इसकी संरचना और टैग्स को समझना वेब विकास का पहला कदम है।
