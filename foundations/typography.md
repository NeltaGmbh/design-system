# Typography

Typography is one of the most important aspects of the design system to establish early on—think of how much information you'll communicate to users through type. Type could account for 85-90% of any given screen. Typography is often one of the foundational components you will want to get a handle on as it will need to work harmoniously with other elements like icons and UI controls. Your line-heights may even influence many other structural elements like spacing and grids. Here are a few key areas you'll want to think through.

Documentation and examples for Nelta typography, including global settings, headings, body text, lists, and more.

## Typeface: [Lato](https://fonts.google.com/specimen/Lato?sidebar.open=true&selection.family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900)

```css
font-family: 'Lato', sans-serif;
```

## Typeface Display: Nexa

```css
font-family: 'Nexa', sans-serif;
```

## Scale

Augmented Fourth Typography is more than just a way to make text look great on a webpage. It’s a **deceptively simple design system** that maintains perfect proportionality in any design. We use the Augmented Fourth scale 1.414 with a base size of 16px \(1em\).

```text
span: 6
rows:
  - Tag: H1
    Font Size PX: 90px
    Font Size REM: 5.653rem
    Line Height: 1.15
  - Tag: H2
    Font Size PX: 63px
    Font Size REM: 3.998rem
    Line Height: 1.15
  - Tag: H3
    Font Size PX: 45px
    Font Size REM: 2.827rem
    Line Height: 1.15
  - Tag: H4
    Font Size PX: 31px
    Font Size REM: 1.999rem
    Line Height: 1.15
  - Tag: H5
    Font Size PX: 22px
    Font Size REM: 1.414rem
    Line Height: 1.15
  - Tag: P
    Font Size PX: 16px
    Font Size REM: 1rem
    Line Height: 1.65
  - Tag: small
    Font Size PX: 11px
    Font Size REM: 0.707rem
    Line Height: 1.65
```

```text
span: 6
rows:
  - Tag: Display 1
    Font Size PX: 177px
    Font Size REM: 11.089rem
    Line Height: 1.15
  - Tag: Display 2
    Font Size PX: 109px
    Font Size REM: 6.854rem
    Line Height: 1.15
  - Tag: Display 3
    Font Size PX: 67px
    Font Size REM: 4.236rem
    Line Height: 1.15
  - Tag: Display 4
    Font Size PX: 41px
    Font Size REM: 2.618rem
    Line Height: 1.15
```

## Headings

All HTML headings, `<h1>` through `<h5>`, are available.

```text
{
    "headings": [90,63,45,31,22],
    "font": 'Lato', sans-serif,
    "color": "#11173D"
}
```

`.h1` through `.h5` classes are also available, for when you want to match the font styling of a heading but cannot use the associated HTML element.

```markup
<h1 class="h1">h1. Nelta heading</h1>
<h2 class="h2">h2. Nelta heading</h2>
<h3 class="h3">h3. Nelta heading</h3>
<h4 class="h4">h4. Nelta heading</h4>
<h5 class="h5">h5. Nelta heading</h5>
```

## Customizing headings

Use the included utility classes to recreate the small secondary heading text.

```markup
<h3>
  Fancy display heading
  <small class="text-muted">With faded secondary text</small>
</h3>
```

## Display headings

```markup
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
```

## Typographic styles

Change the font weight, styles, and alignment with these utilities.

```markup
<p>You can use the mark tag to <mark>highlight</mark> text.</p>
<p><del>This line of text is meant to be treated as deleted text.</del></p>
<p><s>This line of text is meant to be treated as no longer accurate.</s></p>
<p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
<p><u>This line of text will render as underlined</u></p>
<p><small>This line of text is meant to be treated as fine print.</small></p>
<p><strong>This line rendered as bold text.</strong></p>
<p><em>This line rendered as italicized text.</em></p>
<p class="text-uppercase">Uppercase</p>
<p class="no-wrap">No wrap</p>
<p class="lead">Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus.</p>
<p class="user-select-none">User Select None</p>
```

## Word-break

There are two utilities for adjusting how lines and words of text break when they exceed the width of their containing element:

1. `break-word` sets `word-break: break-word` and `overflow-wrap: break-word`, which will only break words if they would exceed the line length _after wrapping_.
2. `wb-break-all` sets `word-break: break-all`, which will force a word to break regardless of whether it's shorter than the line length. See [MDN's](https://developer.mozilla.org/en-US/docs/Web/CSS/word-break#Values) `word-break` docs for more info.

```markup
<p class="break-word p-2 col-3">.break-word will only break long words that exceed the line length, such as supercalifragilisticexpialidocious. Long words like "exceedingly" will simply break to the next line.</p>
<p class="wb-break-all p-2 col-3">.wb-break-all will break any word that meets the end its line, and should be used sparingly. As you can see here, it's not particularly nice to read text that breaks in weird places.</p>
```

## Text alignment

```markup
<p class="text-left">Left align</p>
<p class="text-center">Center</p>
<p class="text-right">Right align</p>
```

## Abbreviations

Stylized implementation of HTML’s `<abbr>` element for abbreviations and acronyms to show the expanded version on hover. Abbreviations have a default underline and gain a help cursor to provide additional context on hover and to users of assistive technologies.

Add `.initialism` to an abbreviation for a slightly smaller font-size.

```markup
<p><abbr title="attribute">attr</abbr></p>
<p><abbr title="HyperText Markup Language" class="initialism">HTML</abbr></p>
```

## Blockquotes

For quoting blocks of content from another source within your document. Wrap `<blockquote class="blockquote">` around any HTML as the quote.

```markup
<blockquote class="blockquote">
  <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
</blockquote>
```

## Naming a source

Add a `<footer class="blockquote-footer">` for identifying the source. Wrap the name of the source work in `<cite>`.

```markup
<blockquote class="blockquote">
  <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
```

## List styles

### Unstyled

Remove bullets from an unordered list or numbers from an ordered list by applying `.list-style-none` to the `<ul>`.

```markup
<ul class="list-style-none">
  <li>First list item</li>
  <li>Second list item</li>
  <li>Third list item</li>
</ul>
```

### Inline

Remove a list’s bullets and apply some light `margin` with a combination of two classes, `.list-inline` and `.list-inline-item`.

```markup
<ul class="list-inline">
  <li class="list-inline-item">Lorem ipsum</li>
  <li class="list-inline-item">Phasellus iaculis</li>
  <li class="list-inline-item">Nulla volutpat</li>
</ul>
```

