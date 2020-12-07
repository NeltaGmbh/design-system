---
description: 'Avatar is used to display a picture, typically next to a person''s name.'
---

# Avatar

## Default

![](../.gitbook/assets/default.svg)

```markup
<div class="avatar">
    <div class="icon">NS</div>
    <div class="name">Name Surname</div>
</div>
```

## Sizes

When you want to add avatar by sizes, you will need to have the class `.avatar` and then add the size `.avatar-[size]`.

![](../.gitbook/assets/sizes.svg)

```markup
<div class="row">

    <div class="col-md">
        <div class="avatar avatar-small">
            <div class="icon">SM</div>
            <div class="name">Small</div>
        </div>
    </div>

    <div class="col-md">
        <div class="avatar avatar-medium">
            <div class="icon">MD</div>
            <div class="name">Medium</div>
        </div>
    </div>

    <div class="col-md">
        <div class="avatar avatar-large">
            <div class="icon">LG</div>
            <div class="name">Large</div>
        </div>
    </div>

    <div class="col-md">
        <div class="avatar avatar-huge">
            <div class="icon">HU</div>
            <div class="name">Huge</div>
        </div>
    </div>

</div>
```

## Photo Avatar

You can use Photo Avatar for different sizes also. Just add `.avatar-[size]` and the image will be responsive to the size.

![](../.gitbook/assets/avatar.svg)

```markup
<div class="avatar">
    <div class="icon"><img src="https://picsum.photos/200" alt=""></div>
    <div class="name">Name Surname</div>
</div>
```

