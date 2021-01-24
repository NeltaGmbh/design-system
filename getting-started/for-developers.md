# For developers

### Installation

`nelta-framework` is served as an [npm package](https://www.npmjs.com/package/nelta-framework).

Add them to your project by running:

```javascript
// with npm
npm install nelta-framework
```

### Usage

#### CSS

Copy-paste the stylesheet `<link>` into your `<head>` before all other stylesheets to load our CSS.

```markup
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/nelta-framework@0.1.16/dist/bundle.css">
```

#### JS

Many of our components require the use of JavaScript to function. Specifically, they require [jQuery](https://jquery.com/), [Popper.js](https://popper.js.org/), and our own JavaScript plugins. We use [jQuery’s slim build](https://blog.jquery.com/2016/06/09/jquery-3-0-final-released/), but the full version is also supported.

```markup
<script src="https://unpkg.com/ionicons@5.2.3/dist/ionicons.js"></script>
<script src="https://cdn.jsdelivr.net/npm/nelta-framework@0.1.16/dist/bundle.js"></script>
```

### Starter template <a id="starter-template"></a>

Starter template is a snippet code for blank HTML page. Use the below snippet as a way to quickly start any new blank page.

```markup
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required Meta Tags Always Come First -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Title -->
    <title>Nelta!</title>

    <!-- Favicon -->
    <link rel="shortcut icon" href="./favicon.ico">
    
    <!-- CSS Front Template -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/nelta-framework@0.1.16/dist/bundle.css">
  </head>

  <body>
    <h1>Hello, world!</h1>

    <!-- JS Icons and Nelta Framework -->
    <script src="https://unpkg.com/ionicons@5.2.3/dist/ionicons.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/nelta-framework@0.1.16/dist/bundle.js"></script>

  </body>
</html>
```

### **Provided development tools include:**

{% page-ref page="../foundations/grid.md" %}

{% page-ref page="../foundations/typography.md" %}

{% page-ref page="../others/component-status.md" %}

