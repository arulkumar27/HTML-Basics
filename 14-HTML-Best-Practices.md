# HTML Best Practices

## Overview

Writing clean HTML improves performance, readability, maintainability, SEO, and accessibility.

## Use Semantic HTML

Prefer:

```html
<header>
<nav>
<section>
<footer>
```

Instead of:

```html
<div>
<div>
<div>
<div>
```

## Maintain Proper Indentation

Good:

```html
<section>
    <h1>Welcome</h1>
    <p>HTML Basics</p>
</section>
```

Bad:

```html
<section><h1>Welcome</h1><p>HTML Basics</p></section>
```

## Use Meaningful Names

Good:

```html
id="employee-list"
```

Bad:

```html
id="abc123"
```

## Always Add Alt Text

```html
<img src="logo.png" alt="Company Logo">
```

## Close Tags Properly

```html
<p>Paragraph</p>
```

## Use Lowercase Tags

Good:

```html
<h1>Welcome</h1>
```

Bad:

```html
<H1>Welcome</H1>
```

## Validate HTML

Use HTML validators to identify coding errors.

## Real-Time Example

Large companies maintain coding standards to ensure multiple developers can work on the same project efficiently.

## Interview Questions

### Why should alt attributes be used?

For accessibility and image fallback text.

### Why is proper indentation important?

It improves readability and maintenance.
