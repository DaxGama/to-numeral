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


### Languages Supported

| Language         | 1234                                     |
|------------------|------------------------------------------|
| English          | one thausand two hundred and thirty-four |
| English (Indian) | one thausand two hundred and thirty-four |
| French           | mille deux cent trente-quatre            |
| Hindi            | एक हज़ार दो सौ चौंतीस                      |
| Gujarati         | એક હજાર બેસો ચોત્રીસ                       |


### Demo
https://daxgama.github.io/to-numeral-demo/


### Change Log

##### 0.0.42
- Initial release
