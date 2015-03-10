# lexo
A small javascript that performs conversions to simpler lexocographically sortable keys ideal for use in firebase (to sort on)

## Usage

Use npm to install in your project:
```sh
npm install lexo
```
or, clone and include in your project using require (CommonJS, NodeJS):
```javascript
var lexo = require('lexo');
```

or, simply include as a script tag:
```html
<script src="lexo.js" />
```

It exposes a few hash objects such as:

lexo.LimitFilter = function(strSearch) returns a json hash object with startAt and endAt simplified keys. The endat key is a "Lexo" increment from strSearch which makes it easy for to order and limit (think priority) for narrowing searches - imagine a user typing in the first three letters of a user's name and receiving back all the matching records where name matches those letters.



