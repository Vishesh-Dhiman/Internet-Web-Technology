# सूचियां बनाना (Creating Lists)

## ऑर्डर्ड लिस्ट (Ordered List)
ऑर्डर्ड लिस्ट में आइटम्स को संख्याओं के साथ प्रदर्शित किया जाता है। इसे `<ol>` और `<li>` टैग्स के माध्यम से बनाया जाता है।
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Ordered List Example</title>
</head>
<body>
    <h2>Ordered List</h2>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
</body>
</html>
```

## अनऑर्डर्ड लिस्ट (Unordered List)
अनऑर्डर्ड लिस्ट में आइटम्स को बुलेट्स के साथ प्रदर्शित किया जाता है। इसे `<ul>` और `<li>` टैग्स के माध्यम से बनाया जाता है।
```html
<ul>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ul>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Unordered List Example</title>
</head>
<body>
    <h2>Unordered List</h2>
    <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>
</body>
</html>
```

## डिफिनिशन लिस्ट (Definition List)
डिफिनिशन लिस्ट में शब्दों और उनकी व्याख्या को प्रदर्शित किया जाता है। इसे `<dl>`, `<dt>`, और `<dd>` टैग्स के माध्यम से बनाया जाता है।
```html
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
    <dt>JavaScript</dt>
    <dd>Programming language of the Web</dd>
</dl>
```

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Definition List Example</title>
</head>
<body>
    <h2>Definition List</h2>
    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
        <dt>JavaScript</dt>
        <dd>Programming language of the Web</dd>
    </dl>
</body>
</html>
```

## सभी सूचियों का संयोजन (Combining All Lists)

### उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <title>All Lists Example</title>
</head>
<body>
    <h2>Ordered List</h2>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>

    <h2>Unordered List</h2>
    <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>

    <h2>Definition List</h2>
    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
        <dt>JavaScript</dt>
        <dd>Programming language of the Web</dd>
    </dl>
</body>
</html>
```

इस उदाहरण में, हमने ऑर्डर्ड लिस्ट, अनऑर्डर्ड लिस्ट, और डिफिनिशन लिस्ट का उपयोग करके विभिन्न प्रकार की सूचियों को प्रदर्शित किया है।
