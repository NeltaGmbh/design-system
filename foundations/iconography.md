# Iconography

## Beautifully crafted open source icons

Premium designed icons for use in web, iOS, Android, and desktop apps. Support for SVG and web font. Completely open source, MIT licensed and built by the [Ionic Framework](https://ionicframework.com/) team.

## Usage

Ionicons is a completely open-source icon set with 1,300 icons crafted for web, iOS, Android, and desktop apps. Ionicons was made for [Ionic Framework](https://ionicframework.com/), a cross-platform hybrid and Progressive Web App framework.

## Using the Web Component

The Ionicons Web Component is an easy and performant way to use Ionicons in your app. The component will dynamically load an SVG for each icon, so your app is only requesting the icons that you need.

Also note that only visible icons are loaded, and icons which are "below the fold" and hidden from the user's view do not make fetch requests for the svg resource.

### Installation

If you're using Ionic Framework, Ionicons is packaged by default, so no installation is necessary. Want to use Ionicons without Ionic Framework? Place the following  near the end of your page, right before the closing &lt;/body&gt; tag, to enable them.

```text
<script src="https://unpkg.com/ionicons@5.2.3/dist/ionicons.js"></script>
```

### Basic usage

To use a built-in icon from the Ionicons package, populate the `name` attribute on the `ion-icon` component:

```text
lang: html
---
<ion-icon name="heart"></ion-icon>
```

### Custom icons

To use a custom SVG, provide its url in the `src` attribute to request the external SVG file. The `src` attribute works the same as `<img src="...">` in that the url must be accessible from the webpage that's making a request for the image. Additionally, the external file can only be a valid `svg` and does not allow scripts or events within the `svg` element.

```text
lang: html
---
<ion-icon src="/path/to/external/file.svg"></ion-icon>
```

## Variants

Each app icon in Ionicons has a `filled`, `outline` and `sharp` variant. These different variants are provided to make your app feel native to a variety of platforms. The filled variant uses the default name without a suffix. Note: Logo icons do not have outline or sharp variants.

```text
lang: html
---
<ion-icon name="heart"></ion-icon> <!--filled-->
<ion-icon name="heart-outline"></ion-icon> <!--outline-->
<ion-icon name="heart-sharp"></ion-icon> <!--sharp-->
```

### Platform specificity

When using icons in Ionic Framework you can specify different icons per platform. Use the `md` and `ios` attributes and provide the platform specific icon/variant name.

```text
lang: html
---
<ion-icon ios="heart-outline" md="heart-sharp"></ion-icon>
```

## Size

To specify the icon size, you can use the `size` attribute for our pre-defined font sizes.

```text
lang: html
---
<ion-icon size="small"></ion-icon>
<ion-icon size="large"></ion-icon>
```

Or you can set a specific size by applying the `font-size` CSS property on the `ion-icon` component. It's recommended to use pixel sizes that are a multiple of 8 \(8, 16, 32, 64, etc.\)

```text
lang: css
---
ion-icon {
  font-size: 64px;
}
```

## Color

Specify the icon color by applying the `color` CSS property on the `ion-icon` component.

```text
lang: css
---
ion-icon {
  color: blue;
}
```

## Stroke weight

When using an `outline` icon variant it is possible to adjust the stroke weight, for improved visual balance relative to the icon's size or relative to the weight of adjacent text. You can set a specific size by applying the `--ionicon-stroke-weight` CSS custom property to the `ion-icon` component. The default value is `32px`

```text
lang: html
---
<ion-icon name="heart-outline"></ion-icon>
```

```text
lang: css
---
ion-icon {
  --ionicon-stroke-width: 16px;
}
```

