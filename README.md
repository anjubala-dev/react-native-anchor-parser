# react-native-anchor-parser



## Installation

#### # Using npm

```bash
npm install react-native-anchor-parser
```

#### # Using yarn

```bash
yarn add react-native-anchor-parser
```

## Demo

#### Code provided in Examples folder.

<!-- [![Screenshot1.gif](https://i.postimg.cc/jjpKJqR8/Screenshot1.gif)](https://postimg.cc/sB4bkrQS)
[![Screenshot2.gif](https://i.postimg.cc/L50xn5p5/Screenshot2.gif)](https://postimg.cc/XBdfPVX6) -->

## Usage

```
import { ArchorParser } from 'react-native-anchor-parser'

...

let yourString = `Lorem Ipsum is simply dummy text of the printing and typesetting industry <a href="https://example.com">Example Show1</a> Lorem Ipsum is simply dummy text of the printing and typesetting industry <a href="https://example.com">Example Show1</a> Lorem Ipsum is simply dummy text of the printing and typesetting industry`

...

<ArchorParser
    string={yourString}
    stringStyle={{ fontSize: 20 }}
    linkStyle={{ fontSize: 20, color: '#2980b9' }} />
    
```

### Props

- [`string`](#string)

- [`numberOfLines`](#int)

- [`stringStyle`](#showFlag)

- [`linkStyle`](#linkStyle)



### string

string is present default value

| Type  | Required |
| ----- | -------- |
| string  | Yes      |

---

### numberOfLines

numberOfLines for showing lines of string, default is 0

| Type  | Required |
| ----- | -------- |
| int   | No      |

---

### stringStyle

style object for text/string

| Type     | Required |
| -------- | -------- |
| object   | No       |

---

### linkStyle

style object for link

| Type     | Required |
| -------- | -------- |
| object | No       |

---


## License

[MIT](https://choosealicense.com/licenses/mit/)
