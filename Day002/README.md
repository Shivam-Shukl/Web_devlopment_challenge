
# Day 002 — HTML Basics

This folder contains my Day 002 notes and practice files on HTML (HyperText Markup Language). Below is a concise guide summarizing what I learned, example snippets I practiced, and links to useful tools and resources.

## What I learned

HTML (HyperText Markup Language) is the standard language used to create and structure content on web pages.

- HyperText: Links that connect web pages together.
- Markup Language: Uses tags to give structure and meaning to content.

Historical note: The very first website — https://info.cern.ch/hypertext/WWW/TheProject.html

## Tools to install (recommended)

1. Visual Studio Code
   - https://code.visualstudio.com/

2. Useful VS Code extensions
   - Live Server (to preview pages in real time)
     - https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server
   - Prettier (code formatter)
     - https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

## HTML concepts & examples

Below are the main tags and their purposes that I practiced.

### 1. Headings (<h1> to <h6>)
Used to define titles and section headings. They give structure and hierarchy to the document.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

- Use <h1> once per page for the main title, then <h2>, <h3>, ... for subsections.

### 2. Paragraph (<p>)
Groups sentences into paragraphs. Browsers add spacing before and after a paragraph.

```html
<p>This is the first paragraph. It contains several sentences about a topic.</p>
<p>This is a second, separate paragraph.</p>
```

### 3. Horizontal Rule (<hr>)
Defines a thematic break or separation between content sections.

```html
<p>This is the first topic.</p>
<hr />
<p>This is a completely different topic.</p>
```

### 4. Line Break (<br>)
For single line breaks (like in addresses or poems). Don't use it for spacing between paragraphs.

```html
<p>221B Baker Street<br>
London, England</p>
```

### 5. Lists (<ul>, <ol>, <li>)
Create ordered (numbered) and unordered (bulleted) lists. Useful for grouping related items.

Unordered list example:
```html
<ul>
  <li>Tea Bag</li>
  <li>Water</li>
  <li>Sugar</li>
  <li>Milk</li>
</ul>
```

Ordered list example:
```html
<ol>
  <li>First, boil the water in a kettle.</li>
  <li>Add tea bag, sugar and milk into it.</li>
  <li>Keep boiling it for 5 minutes.</li>
  <li>Serve the tea by pouring it into a cup.</li>
</ol>
```

Nesting lists is simply placing one list inside an <li> of another list.

### 6. Anchor tag (<a>)
Creates hyperlinks. Use the `href` attribute for the destination and optionally `target` for where it opens.

```html
<a href="https://www.coderarmy.in/" target="_blank">Visit Coder Army</a>
```

Common `target` values:
- `_self` — open in same tab (default)
- `_blank` — open in a new tab

### 7. Image tag (<img>)
Embeds images. It's self-closing and needs `src` and `alt` attributes.

```html
<img src="images/photo.jpg" alt="A descriptive text about the image" />
```

- `src`: path to the image (required)
- `alt`: description for accessibility and when the image fails to load (required for good practice)

## What I practiced
- Creating heading structures and semantic hierarchy
- Writing paragraphs and using <br> appropriately
- Using <hr> to separate topics
- Building ordered and unordered lists (including nested lists)
- Creating links with `<a>` and opening them in new tabs
- Embedding images with `alt` text

I practiced nested lists and wrote a few small HTML files to apply these tags.

## Next steps / Recommendations
- Continue practicing by building small pages (profile, recipe, blog post).
- Learn basic CSS to style the HTML structure.
- Learn the semantic HTML5 tags (header, nav, main, section, article, footer).
- Use Live Server to preview pages while developing.

## Resources
- First website: https://info.cern.ch/hypertext/WWW/TheProject.html
- VS Code: https://code.visualstudio.com/
- Live Server extension: https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server
- Prettier extension: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

---

If you'd like, I can:
- Add the HTML practice files to this folder as example pages.
- Create an index.html that demonstrates all the tags above in one page.
