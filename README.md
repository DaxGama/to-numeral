# to-numeral
Converts numbers to words, supports multiple languages

### Install
`npm install to-numeral`


### API

#### `toWords(number)`
Converts an integer into words.
If number is decimal, the decimals will be removed.
```js
import englishNumeral from "to-numeral/dist/lang/english";
englishNumeral.toWords(1234); // “one thausand two hundred and thirty-four”
```

### Demo
[Demo](https://daxgama.github.io/to-numeral-demo/)


### Change Log

##### 0.0.42
- Initial release
