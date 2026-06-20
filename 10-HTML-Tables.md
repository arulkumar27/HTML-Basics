# HTML Tables

## Overview

Tables are used to display structured data in rows and columns.

## Basic Table

```html
<table>
    <tr>
        <th>Name</th>
        <th>Role</th>
    </tr>

    <tr>
        <td>Arul</td>
        <td>DevOps Engineer</td>
    </tr>
</table>
```

## Table Elements

### Table

```html
<table>
```

Creates a table.

### Table Row

```html
<tr>
```

Creates a row.

### Table Header

```html
<th>
```

Creates a heading cell.

### Table Data

```html
<td>
```

Creates a data cell.

## Colspan Example

```html
<td colspan="2">Merged Column</td>
```

## Rowspan Example

```html
<td rowspan="2">Merged Row</td>
```

## Complete Example

```html
<table border="1">
    <tr>
        <th>Employee</th>
        <th>Department</th>
    </tr>

    <tr>
        <td>Arul</td>
        <td>Cloud</td>
    </tr>

    <tr>
        <td>Kumar</td>
        <td>DevOps</td>
    </tr>
</table>
```

## Real-Time Example

Companies use tables for:

* Employee records
* Sales reports
* Project tracking
* Attendance management

## Interview Questions

### Which tag creates a table row?

```html
<tr>
```

### Which tag creates table headers?

```html
<th>
```

### Which tag creates table data cells?

```html
<td>
```
