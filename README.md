# cv

Responsive CV template made in pure HTML, CSS & JS

Here's a brief README section explaining the HTML structure:

---

## HTML Structure

The CV is built using semantic HTML. Each **page** is a `<div>` inside `<main>` — it renders as an A4 sheet. Add a new `<div>` to add a new page.

```html
<main>
  <div> <!-- Page 1 -->
    ...
  </div>
  <div> <!-- Page 2 -->
    ...
  </div>
</main>
```

Inside each page, use **`<section>`** to group related content (e.g. Experience, Education, Skills), each with an `<h3>` as the section title.

```html
<section>
  <h3>Experience</h3>
  ...
</section>
```

Each entry within a section is an **`<article>`**, structured as follows:

```html
<article>
  <span>
    <h4>Job Title / Degree</h4>
    <span>|</span>
    <small>Date range</small>
  </span>
  <span>
    <small>Organization</small>
    <span>|</span>
    <small>Location or grade</small>
  </span>
  <ul>
    <li>Description point</li>
  </ul>
</article>
```

The **banner** (name + contact info) uses `<section role="banner">` with an `<h1>` for the name, `<h2>` for the subtitle, and a `<header>` containing `<a>` elements for contact links.
