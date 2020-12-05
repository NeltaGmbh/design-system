# Color Palette

## Secondary Colors

### Blue Palette

```text
colors:
  - {name: "$blue-1", value: "#1C2445"}
  - {name: "$blue-2", value: "#2A3564"}
  - {name: "$blue-3", value: "#374683"}
  - {name: "$blue-4", value: "#4557A2"}
  - {name: "$blue-5", value: "#5268C1"}
  - {name: "$blue-6", value: "#6079E0"}
  - {name: "$blue-7", value: "#6D8AFF"}
```

### Yellow Palette

```text
colors:
  - {name: "$yellow-1", value: "#E0FF43"}
  - {name: "$yellow-2", value: "#CEEB3F"}
  - {name: "$yellow-3", value: "#BCD63A"}
  - {name: "$yellow-4", value: "#AAC236"}
  - {name: "$yellow-5", value: "#97AD31"}
  - {name: "$yellow-6", value: "#85992D"}
  - {name: "$yellow-7", value: "#738428"}
```

### Neutral Palette

```text
colors:
  - {name: "$neutral-1", value: "#051225"}
  - {name: "$neutral-2", value: "#2D3848"}
  - {name: "$neutral-3", value: "#555E6C"}
  - {name: "$neutral-4", value: "#7E858F"}
  - {name: "$neutral-5", value: "#A6ABB2"}
  - {name: "$neutral-6", value: "#CED1D6"}
  - {name: "$neutral-7", value: "#F6F7F9"}
```

## Gradients

#### Blue - Linear

Left to Right

```text
span: 3
name: "$blue-1"
value: "#1C2445"
```

```text
span: 3
name: "$blue-4"
value: "#4557A2"
```

#### Yellow - Linear

Left to Right

```text
span: 3
name: "$yellow-1"
value: "#E0FF43"
```

```text
span: 3
name: "$yellow-4"
value: "#AAC236"
```

### Color pairings

Each background color is paired with a foreground color. The foreground is considered text and ensures that any color chosen is accessible. However, there may be cases where the background color is used for the text color. In such cases it's the responsibility of the designer to meet WCAG 2.1 AA requirements.

#### White foreground

```text
span: 6
rows:
  - N: 1
    Foreground Color: '#ffffff'
    Background Color: '#11173D'
    Result: Pass - 17.30 - Super
  - N: 2
    Foreground Color: '#ffffff'
    Background Color: '#1C2445'
    Result: Pass - 15.13 - Super
  - N: 3
    Foreground Color: '#ffffff'
    Background Color: '#262C4E'
    Result: Pass - 13.52 - Super
  - N: 4
    Foreground Color: '#ffffff'
    Background Color: '#3C4160'
    Result: Pass - 9.92 - Very good
  - N: 5
    Foreground Color: '#ffffff'
    Background Color: '#E0FF4F'
    Result: Fail - 1.13 - Very poor
  - N: 6
    Foreground Color: '#ffffff'
    Background Color: '#D0ED49'
    Result: Fail - 1.32 - Very poor
  - N: 7
    Foreground Color: '#ffffff'
    Background Color: '#DADADA'
    Result: Fail - 1.40 - Very poor
  - N: 8
    Foreground Color: '#ffffff'
    Background Color: '#EAEAEA'
    Result: Fail - 1.20 - Very poor
  - N: 9
    Foreground Color: '#ffffff'
    Background Color: '#F2F2F2'
    Result: Fail - 1.12 - Very poor
```

### Main color foreground

```text
span: 6
rows:
  - N: 1
    Foreground Color: '#11173D'
    Background Color: '#1C2445'
    Result: Fail - 1.14 - Very poor
  - N: 2
    Foreground Color: '#11173D'
    Background Color: '#262C4E'
    Result: Fail - 1.28 - Very poor
  - N: 3
    Foreground Color: '#11173D'
    Background Color: '#3C4160'
    Result: Fail - 1.74 - Very poor
  - N: 4
    Foreground Color: '#11173D'
    Background Color: '#E0FF4F'
    Result: Pass - 15.31 - Super
  - N: 5
    Foreground Color: '#11173D'
    Background Color: '#D0ED49'
    Result: Pass - 13.09 - Super
  - N: 6
    Foreground Color: '#11173D'
    Background Color: '#DADADA'
    Result: Pass - 12.38 - Super
  - N: 7
    Foreground Color: '#11173D'
    Background Color: '#EAEAEA'
    Result: Pass - 14.38 - Super
  - N: 8
    Foreground Color: '#11173D'
    Background Color: '#F2F2F2'
    Result: Pass - 15.45 - Super
  - N: 9
    Foreground Color: '#11173D'
    Background Color: '#FFFFFF'
    Result: Pass - 17.30 - Super
```

### Contrast color foreground

```text
span: 6
rows:
  - N: 1
    Foreground Color: '#E0FF4F'
    Background Color: '#11173D'
    Result: Pass - 15.31 - Super
  - N: 2
    Foreground Color: '#E0FF4F'
    Background Color: '#1C2445'
    Result: Pass - 13.39 - Super
  - N: 3
    Foreground Color: '#E0FF4F'
    Background Color: '#262C4E'
    Result: Pass - 11.97 - Super
  - N: 4
    Foreground Color: '#E0FF4F'
    Background Color: '#3C4160'
    Result: Pass - 8.78 - Very good
  - N: 5
    Foreground Color: '#E0FF4F'
    Background Color: '#D0ED49'
    Result: Fail - 1.17 - Very poor
  - N: 6
    Foreground Color: '#E0FF4F'
    Background Color: '#DADADA'
    Result: Fail - 1.24 - Very poor
  - N: 7
    Foreground Color: '#E0FF4F'
    Background Color: '#EAEAEA'
    Result: Fail - 1.06 - Very poor
  - N: 8
    Foreground Color: '#E0FF4F'
    Background Color: '#F2F2F2'
    Result: Fail - 1.01 - Very poor
  - N: 9
    Foreground Color: '#E0FF4F'
    Background Color: '#FFFFFF'
    Result: Fail - 1.13 - Very poor
```

### Color gradient palettes

#### Main color

```text
colors:
   - {value: "#11173D"}
   - {value: "#393E5D"}
   - {value: "#60647E"}
   - {value: "#888B9E"}
   - {value: "#B0B2BE"}
   - {value: "#D7D8DF"}
   - {value: "#FFFFFF"}
```

#### Contrast color

```text
colors:
   - {value: "#E0FF4F"}
   - {value: "#E5FF6C"}
   - {value: "#EAFF8A"}
   - {value: "#F0FFA7"}
   - {value: "#F5FFC4"}
   - {value: "#FAFFE2"}
   - {value: "#FFFFFF"}
```

