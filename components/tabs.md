---
description: >-
  Tabs are used to organize content by grouping similar information on the same
  page.
---

# Tabs

## Tabs Underline

The Underline form of tabs.

![](../.gitbook/assets/concept-1.svg)

```markup
<ul
class="nav tabs-underline nav-justified"
id="myTab"
role="tablist"
>
<li class="nav-item" role="presentation">
  <a
    class="nav-link active"
    id="home-tab"
    data-toggle="tab"
    href="#home"
    role="tab"
    aria-controls="home"
    aria-selected="true"
    >Home</a
  >
</li>
<li class="nav-item" role="presentation">
  <a
    class="nav-link"
    id="profile-tab"
    data-toggle="tab"
    href="#profile"
    role="tab"
    aria-controls="profile"
    aria-selected="false"
    >Profile</a
  >
</li>
<li class="nav-item" role="presentation">
  <a
    class="nav-link"
    id="contact-tab"
    data-toggle="tab"
    href="#contact"
    role="tab"
    aria-controls="contact"
    aria-selected="false"
    >Contact</a
  >
</li>
</ul>
<div class="tab-content" id="myTabContent">
<div
  class="tab-pane fade show active"
  id="home"
  role="tabpanel"
  aria-labelledby="home-tab"
>
  Nelta - Tab 1
</div>
<div
  class="tab-pane fade"
  id="profile"
  role="tabpanel"
  aria-labelledby="profile-tab"
>
  Nelta - Tab 2
</div>
<div
  class="tab-pane fade"
  id="contact"
  role="tabpanel"
  aria-labelledby="contact-tab"
>
  Nelta - Tab 3
</div>
</div>
```

## Tabs Filled

The Filled form of tabs.

![](../.gitbook/assets/concept-2.svg)

```markup
<ul class="nav tabs-filled nav-justified" id="myTab" role="tablist">
  <li class="nav-item" role="presentation">
    <a
      class="nav-link active"
      id="pilot-tab"
      data-toggle="tab"
      href="#pilot"
      role="tab"
      aria-controls="pilot"
      aria-selected="true"
      >Pilot</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="care-tab"
      data-toggle="tab"
      href="#care"
      role="tab"
      aria-controls="care"
      aria-selected="false"
      >Care</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="claim-tab"
      data-toggle="tab"
      href="#claim"
      role="tab"
      aria-controls="claim"
      aria-selected="false"
      >Claim</a
    >
  </li>
</ul>
<div class="tab-content" id="myTabContent">
  <div
    class="tab-pane fade show active"
    id="pilot"
    role="tabpanel"
    aria-labelledby="pilot-tab"
  >
    Nelta - Tab 1
  </div>
  <div
    class="tab-pane fade"
    id="care"
    role="tabpanel"
    aria-labelledby="care-tab"
  >
    Nelta - Tab 2
  </div>
  <div
    class="tab-pane fade"
    id="claim"
    role="tabpanel"
    aria-labelledby="claim-tab"
  >
    Nelta - Tab 3
  </div>
</div>
```

## Tabs Filled Rounded

The Rounded Filled form of tabs.

![](../.gitbook/assets/concept-3.svg)

```markup
<ul
  class="nav tabs-filled-rounded nav-justified"
  id="myTab"
  role="tablist"
>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link active"
      id="pilott-tab"
      data-toggle="tab"
      href="#pilott"
      role="tab"
      aria-controls="pilott"
      aria-selected="true"
      >Pilot</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="caree-tab"
      data-toggle="tab"
      href="#caree"
      role="tab"
      aria-controls="caree"
      aria-selected="false"
      >Care</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="claimm-tab"
      data-toggle="tab"
      href="#claimm"
      role="tab"
      aria-controls="claimm"
      aria-selected="false"
      >Claim</a
    >
  </li>
</ul>
<div class="tab-content" id="myTabContent">
  <div
    class="tab-pane fade show active"
    id="pilott"
    role="tabpanel"
    aria-labelledby="pilott-tab"
  >
    Nelta - Tab 1
  </div>
  <div
    class="tab-pane fade"
    id="caree"
    role="tabpanel"
    aria-labelledby="caree-tab"
  >
    Nelta - Tab 2
  </div>
  <div
    class="tab-pane fade"
    id="claimm"
    role="tabpanel"
    aria-labelledby="claimm-tab"
  >
    Nelta - Tab 3
  </div>
</div>
```

## Tabs Active Only

The Active-Only form of tabs.

![](../.gitbook/assets/concept-4.svg)

```markup
<ul
  class="nav tabs-activeonly nav-justified"
  id="myTab"
  role="tablist"
>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link active"
      id="pilottt-tab"
      data-toggle="tab"
      href="#pilottt"
      role="tab"
      aria-controls="pilottt"
      aria-selected="true"
      >Pilot</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="careee-tab"
      data-toggle="tab"
      href="#careee"
      role="tab"
      aria-controls="careee"
      aria-selected="false"
      >Care</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="claimmm-tab"
      data-toggle="tab"
      href="#claimmm"
      role="tab"
      aria-controls="claimmm"
      aria-selected="false"
      >Claim</a
    >
  </li>
</ul>
<div class="tab-content" id="myTabContent">
  <div
    class="tab-pane fade show active"
    id="pilottt"
    role="tabpanel"
    aria-labelledby="pilottt-tab"
  >
    Nelta - Tab 1
  </div>
  <div
    class="tab-pane fade"
    id="careee"
    role="tabpanel"
    aria-labelledby="careee-tab"
  >
    Nelta - Tab 2
  </div>
  <div
    class="tab-pane fade"
    id="claimmm"
    role="tabpanel"
    aria-labelledby="claimmm-tab"
  >
    Nelta - Tab 3
  </div>
</div>
```

