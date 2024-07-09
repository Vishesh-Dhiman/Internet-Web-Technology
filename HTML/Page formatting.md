# पेज प्रारूपण (Page Formatting)

## नया पैराग्राफ जोड़ना (Adding a New Paragraph)
HTML में नया पैराग्राफ जोड़ने के लिए `<p>` टैग का उपयोग किया जाता है। प्रत्येक `<p>` टैग एक नया पैराग्राफ बनाता है।
```html
<p>This is the first paragraph.</p>
<p>This is the second paragraph.</p>
```

## लाइन ब्रेक जोड़ना (Adding a Line Break)
लाइन ब्रेक जोड़ने के लिए `<br>` टैग का उपयोग किया जाता है। यह टैग टेक्स्ट को अगली लाइन में स्थानांतरित करता है।
```html
<p>This is a line.<br>This is the next line.</p>
```

## रिक्त स्थान जोड़ना (Inserting a Blank Space)
HTML में रिक्त स्थान जोड़ने के लिए &nbsp; (non-breaking space) का उपयोग किया जाता है। यह टैग लगातार रिक्त स्थान को बनाए रखता है।
```html
<p>This is some text.&nbsp;&nbsp;&nbsp;This text is after three spaces.</p>
```

## पेज बैकग्राउंड बदलना (Changing Page Background)
पेज के बैकग्राउंड को बदलने के लिए CSS का उपयोग किया जाता है। इसे `<style>` टैग के भीतर या बाहरी CSS फाइल के माध्यम से किया जा सकता है।
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
    <p>This page has a light blue background.</p>
</body>
</html>
```

## `<div>` और `<span>` टैग (Div and Span Tags)

### `<div>` टैग
`<div>` टैग का उपयोग ब्लॉक-स्तरीय तत्व बनाने के लिए किया जाता है। यह आमतौर पर वेब पेज के विभिन्न अनुभागों को समूहीकृत करने के लिए उपयोग किया जाता है।
```html
<div style="background-color: lightgrey; padding: 20px;">
    <h2>Div Example</h2>
    <p>This is a paragraph inside a div.</p>
</div>
```

### `<span>` टैग
`<span>` टैग का उपयोग इनलाइन तत्व बनाने के लिए किया जाता है। यह विशेष रूप से टेक्स्ट के छोटे हिस्सों को स्टाइल करने के लिए उपयोग किया जाता है।
```html
<p>This is a <span style="color: red;">red</span> word in a paragraph.</p>
```

## उदाहरण (Example)
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: lightyellow;
        }
        .highlight {
            background-color: lightgreen;
            padding: 10px;
        }
        .important {
            color: red;
        }
    </style>
</head>
<body>
    <p>This is the first paragraph.</p>
    <p>This is the second paragraph.<br>This line is after a line break.</p>
    <p>This is some text.&nbsp;&nbsp;&nbsp;This text is after three spaces.</p>
    <div class="highlight">
        <h2>Div Example</h2>
        <p>This is a paragraph inside a div.</p>
    </div>
    <p>This is a <span class="important">very important</span> word in a paragraph.</p>
</body>
</html>
```

इस उदाहरण में, हमने एक नया पैराग्राफ जोड़ा, लाइन ब्रेक और रिक्त स्थान शामिल किए, पेज बैकग्राउंड को बदल दिया, और `<div>` और `<span>` टैग का उपयोग करके विभिन्न हिस्सों को स्टाइल किया है।
