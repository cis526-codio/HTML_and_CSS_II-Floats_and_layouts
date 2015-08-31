As stated earlier, when there is a "meaningfull" html element that can be used, use it. Don't use divs and spans everywhere. We will follow with 2 concrete examples.

### 1) List example
(You can also see it on the left)

```html
<div class="list">
  <span class="element"> Item 1 </span>
  <span class="element"> Item 2 </span>
  <span class="element"> Item 3 </span>
</div>
```

Don't use divs and spans if you want to make a list, then use a real list instead :

```html
<ul>
  <li> Item 1 </li>
  <li> Item 2 </li>
  <li> Item 3 </li>
</ul>
```

Try to use html elements which have meaning whenever possible.

{Check It!|assessment}(test-2960585299)

|||guidance

Solution :

```html
<!DOCTYPE html>
<html>
<head>
  <title>Divs and spans</title>
  <style>
    .list {
      margin-left:2em;
    }

    .list .element {
      display:block;
    }
  </style>
</head>
<body>
  <h1> Divs and spans </h1>
  
  <h2> Don't abuse them : list example </h2>
  
  <ul>
    <li> Item 1 </li>
    <li> Item 2 </li>
    <li> Item 3 </li>
  </ul>
  
</body>
</html>
```
