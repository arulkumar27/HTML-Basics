# HTML Forms

## Overview

HTML forms are used to collect user input and send data to a server for processing.

## Why Forms Are Important

Forms are used in:

* Login Pages
* Registration Pages
* Contact Forms
* Surveys
* Feedback Systems
* Online Shopping Checkout Pages

## Basic Form

```html
<form>
    <label>Name:</label>
    <input type="text">

    <br><br>

    <input type="submit" value="Submit">
</form>
```

## Common Input Types

### Text Input

```html
<input type="text">
```

### Password Input

```html
<input type="password">
```

### Email Input

```html
<input type="email">
```

### Number Input

```html
<input type="number">
```

### Date Input

```html
<input type="date">
```

### Radio Button

```html
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female
```

### Checkbox

```html
<input type="checkbox"> HTML
<input type="checkbox"> CSS
```

### Text Area

```html
<textarea rows="5" cols="30"></textarea>
```

### Dropdown

```html
<select>
    <option>India</option>
    <option>USA</option>
</select>
```

## Real-Time Example

A job application portal uses forms to collect:

* Name
* Email
* Resume
* Experience
* Skills

## Interview Questions

### What is the purpose of the form tag?

The form tag collects and submits user data.

### Which input type hides entered characters?

```html
<input type="password">
```
