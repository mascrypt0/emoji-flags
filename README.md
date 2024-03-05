<<<<<<< HEAD
# npm-emoji-flags
=======
# emoji-flags
>>>>>>> 0d2cd2460a2f98f2b7f216534b52d2ae6515ace3

> Get country languages from country flag emojis

## Install

```sh
<<<<<<< HEAD
npm install npm-emoji-flags
=======
npm install emoji-flags
>>>>>>> 0d2cd2460a2f98f2b7f216534b52d2ae6515ace3
```

## Usage

```js
const { isValidCode, isValidEmoji, getLanguagesFromCode, getLanguagesFromEmoji } = require("country-emoji-languages");

isValidCode("IN"); // true

isValidEmoji("🇮🇳"); // true

getLanguagesFromCode("IN"); // ['bn', 'en', 'gu', 'hi', 'pa', 'ta', 'te']

getLanguagesFromEmoji("🇮🇳"); // ['bn', 'en', 'gu', 'hi', 'pa', 'ta', 'te']
```

## To Do's

-   Return language names along with codes
