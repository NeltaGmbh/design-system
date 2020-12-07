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

### Blue - Linear

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

### Yellow - Linear

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

## Color pairings

Each background color is paired with a foreground color. The foreground is considered text and ensures that any color chosen is accessible. However, there may be cases where the background color is used for the text color. In such cases it's the responsibility of the designer to meet WCAG 2.1 AA requirements.

### White foreground

| N | Foreground Color | Background Color | Result |
| :--- | :--- | :--- | :--- |
| 1 | \#ffffff | \#11173D | Pass - 17.30 - Super |
| 2 | \#ffffff | \#1C2445 | Pass - 15.13 - Super |
| 3 | \#ffffff | \#262C4E | Pass - 13.52 - Super |
| 4 | \#ffffff | \#3C4160 | Pass - 9.92 - Very good |
| 5 | \#ffffff | \#E0FF4F | Fail - 1.13 - Very poor |
| 6 | \#ffffff | \#D0ED49 | Fail - 1.32 - Very poor |
| 7 | \#ffffff | \#DADADA | Fail - 1.40 - Very poor |
| 8 | \#ffffff | \#EAEAEA | Fail - 1.20 - Very poor |
| 9 | \#ffffff | \#F2F2F2 | Fail - 1.12 - Very poor |

### Main color foreground

| N | Foreground Color | Background Color | Result |
| :--- | :--- | :--- | :--- |
| 1 | \#11173D | \#1C2445 | Fail - 1.14 - Very poor |
| 2 | \#11173D | \#262C4E | Fail - 1.28 - Very poor |
| 3 | \#11173D | \#3C4160 | Fail - 1.74 - Very poor |
| 4 | \#11173D | \#E0FF4F | Pass - 15.31 - Super |
| 5 | \#11173D | \#D0ED49 | Pass - 13.09 - Super |
| 6 | \#11173D | \#DADADA | Pass - 12.38 - Super |
| 7 | \#11173D | \#EAEAEA | Pass - 14.38 - Super |
| 8 | \#11173D | \#F2F2F2 | Pass - 15.45 - Super |
| 9 | \#11173D | \#FFFFFF | Pass - 17.30 - Super |

### Contrast color foreground

| N | Foreground Color | Background Color | Result |
| :--- | :--- | :--- | :--- |
| 1 | \#E0FF4F | \#11173D | Pass - 15.31 - Super |
| 2 | \#E0FF4F | \#1C2445 | Pass - 13.39 - Super |
| 3 | \#E0FF4F | \#262C4E | Pass - 11.97 - Super |
| 4 | \#E0FF4F | \#3C4160 | Pass - 8.78 - Very good |
| 5 | \#E0FF4F | \#D0ED49 | Fail - 1.17 - Very poor |
| 6 | \#E0FF4F | \#DADADA | Fail - 1.24 - Very poor |
| 7 | \#E0FF4F | \#EAEAEA | Fail - 1.06 - Very poor |
| 8 | \#E0FF4F | \#F2F2F2 | Fail - 1.01 - Very poor |
| 9 | \#E0FF4F | \#FFFFFF | Fail - 1.13 - Very poor |

## Color gradient palettes

### Main color

|  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| \#11173D | \#393E5D | \#60647E | \#888B9E | \#B0B2BE | \#D7D8DF | \#FFFFFF |

### Contrast color

|  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| \#E0FF4F | \#E5FF6C | \#EAFF8A | \#F0FFA7 | \#F5FFC4 | \#FAFFE2 | \#FFFFFF |

