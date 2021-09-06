---
description: >-
  A radio input allows people to select only one option from a number of
  choices. Radio is generally displayed in a radio group.
---

# Radio

![](../.gitbook/assets/radio.png)

```markup
<div class="row">
  <div class="col-12">
      <div class="custom-control custom-radio">
          <input type="radio" id="customRadio1" name="customRadio" class="custom-control-input">
          <label class="custom-control-label" for="customRadio1">Unselected</label>
        </div>
        <div class="custom-control custom-radio">
          <input type="radio" id="customRadio2" name="customRadio" class="custom-control-input" checked>
          <label class="custom-control-label" for="customRadio2">Selected</label>
        </div>
  </div>
</div>

<div class="row">
  <div class="col-12">
      <div class="custom-control custom-radio">
          <input type="radio" id="customCheckDisabled1" name="disabledNone" class="custom-control-input" disabled>
          <label class="custom-control-label" for="customCheckDisabled1">Disabled Unselected</label>
        </div>
        <div class="custom-control custom-radio">
          <input type="radio" id="customCheckDisabled2" name="disabledSelected" class="custom-control-input" disabled checked>
          <label class="custom-control-label" for="customCheckDisabled2">Disabled Selected</label>
        </div>
  </div>
</div>
```

