<h2>Motivation</h2>
Play with dark mode as basic as possible. Here dark mode is implemented via class

<h2>Implementation</h2>
<ul>
<li>create a class name dark-mode (you can choose any name)

```css

.dark-mode {
  background-color: black;
  color: white;
}

```
</li>


<li>toggle the dark mode class on the body element

```javascript

var element = document.body;
   element.classList.toggle("dark-mode");
```
</li>

<li>the default style (called in general light mode) is applied when dark-mode class is not applied

```css
body {
  padding: 25px;
  background-color: white;
  color: black;
  font-size: 25px;
}
```

</li>
</ul>
