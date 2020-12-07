---
description: A banner displays a prominent message at the top of the screen.
---

# Banner

## Appearance

### Warning

The default form of a banner. Use `.banner-warning` banners when you want the user to take a specific action or to warn them that something is about to go wrong.

![](../.gitbook/assets/warning.svg)

```markup
<div class="banner-warning">
    <ion-icon name="warning"></ion-icon>
    <p>Warning goes here</p>
</div>
```

### Error

![](../.gitbook/assets/error.svg)

Use `.banner-error` banners to inform users something critical has happened and requires immediate attention.

```markup
<div class="banner-error">
    <ion-icon name="alert-circle"></ion-icon>
    <p>Error message goes here</p>
</div>
```

