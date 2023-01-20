This is the README for GrannePack Web Dev Snippets.

# GrannePack Web Dev Snippets

This extension pack of HTML-, CSS-, & SCSS-related *snippets* is aimed at students in [Scott Granneman’s](https://www.granneman.com/) beginning Web Development courses. Other languages may be added at later times.

## Other extension packs focusing on extensions

In addition, I have also created extension packs of *extensions*, also for students in [my](https://www.granneman.com/) beginning Web Development courses:

* [HTML](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-html)
* [CSS](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-css)
* [Git](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-git)
* [Markdown](https://marketplace.visualstudio.com/items?itemName=granneman.grannepack-markdown)

## Snippets

In the following tables, `${0}` represents the *final* cursor position. In most cases, this is the *only* place the cursor could be, so it is also where your cursor will be immediately after expanding the snippet. If there is more than one cursor position, however, then `${1}`, `{2}`, & so on represent each tab stop, ending at `${0}`.

### HTML

`a`:

```html
<a href="${1}">${0}</a>
```

`address`:

```html
<address>
  ${0}
</address>
```

`article`:

```html
<article>
  ${0}
</article>
```

`aside`:

```html
<aside>
  ${0}
</aside>
```

`b`:

```html
<b>${1}</b>${0}
```

`blockquote`:

```html
<blockquote>
  ${0}
</blockquote>
```

`caption` (for `<table>`):

```html
<caption>
  ${0}
</caption>
```

`dd`:

```html
<dd>${0}</dd>
```

`div`:

```html
<div>
  ${0}
</div>
```

`dl`:

```html
<dl>
  ${0}
</dl>
```

`dt`:

```html
<dt>${0}</dt>
```

`em`:

```html
<em>${0}</em>
```

`figcaption`:

```html
<figcaption>
  ${0}
</figcaption>
```

`figure`:

```html
<figure>
  ${0}
</figure>
```

`footer`:

```html
<footer>
  ${0}
</footer>
```

`head`:

```html
<head>
  ${0}
</head>
```

`header`:

```html
<header>
  ${0}
</header>
```

`html`:

```html
<html>
  ${0}
</html>
```

`i`:

```html
<i>${0}</i>
```

`img`:

```html
<img src="{0}" alt="" width="" height="" srcset="">
```

`li`:

```html
<li>${0}</li>
```

`link`:

```html
<link rel="stylesheet" href="{0}">
```

`main`:

```html
<main>
  ${0}
</main>
```

`meta`:

```html
<meta charset="UTF-8">${0}
```

`nav`:

```html
<nav>
  ${0}
</nav>
```

`ol`:

```html
<ol>
  ${0}
</ol>
```

`ol+`:

```html
<ol>
  <li>${1}</li>
  <li>${2}</li>
  <li>${3}</li>${0}
</ol>
```

`option`:

```html
<option>${1}</option>${0}
```

`p`:

```html
<p>
  ${0}
</p>
```

`script`:

```html
<script src="{0}"></script>
```

`section`:

```html
<section>
  ${0}
</section>
```

`strong`:

```html
<strong>${0}</strong>
```

`style`:

```html
<style>
  ${0}
</style>
```

`table`:

```html
<table>
  ${0}
</table>
```

`td`:

```html
<td>${0}</td>
```

`th`:

```html
<th>${0}</th>
```

`tr`:

```html
<tr>
  ${0}
</tr>
```

`trd`:

```html
<tr>
  <td>${0}</td>
</tr>
```

`trh`:

```html
<tr>
  <th>${0}</th>
</tr>
```

`ul`:

```html
<ul>
  ${0}
</ul>
```

`ul+`:

```html
<ul>
  <li>${1}</li>
  <li>${2}</li>
  <li>${0}</li>
</ul>
```

`video`:

```html
<video src="" poster="" width="" height="" controls></video>
```

`video+`:

```html
<video poster="" width="" height="" controls>
  <source src="{1}" type="video/webm">
  <source src="{2}" type="video/mp4">
</video>
```

### CSS

`,condensed` (Condensed font stack):

```css
Oswald, 'Avenir Next Condensed', AvenirNextCondensed-Medium, HelveticaNeue, sans-serif-condensed, 'Gill Sans Nova Cond', 'Arial Nova Condensed', 'Arial Narrow', sans-serif;${0}
```

`,h1com` (Large section comment):

```css
/****************************************
${1}
****************************************/
```

`,h2com`  (Small section comment):

```css
/**********
${1}
**********/
```

`,hx` (Headings selector list):

```css
h1, h2, h3, h4, h5, h6
```

`,uifonts` (Common UI fonts stack):

```css
system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', 'Liberation Sans', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji'${0}
```

### SCSS

`,condensed` (Condensed Font Stack):

```scss
Oswald, 'Avenir Next Condensed', AvenirNextCondensed-Medium, HelveticaNeue, sans-serif-condensed, 'Gill Sans Nova Cond', 'Arial Nova Condensed', 'Arial Narrow', sans-serif;${0}
```

`,h1com` (Large section comment):

```scss
//****************************************
// ${1}
//****************************************
```

`,h2com` (Small section comment):

```scss
//**********
// ${1}
//**********
```

`,hx` (Headings selector list):

```scss
h1, h2, h3, h4, h5, h6
```

`,uifonts` (Common UI Fonts Stack):

```scss
system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', 'Liberation Sans', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji' !default;${0}
```

More to come!
