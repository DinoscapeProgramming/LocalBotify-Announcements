# Update - v1.3.1

Say hello to the brand new dialog system for your bot to communicate with the app.

## Why?

- Show errors in a user friendly way
- Ask the user for API credentials
- _et cetera_

## How?

Use our [npm package](https://www.npmjs.com/package/localbotify)'s `alert()`, `confirm()`, `prompt()` methods to push notifications to the client through our new channel in `channels/dialog.txt`.

As an example, this is how to use `alert()`:

```js
const { alert } = requireCore("localbotify");

alert("Title", "Body / Description");
```

---

_Made with ❤️ by [Dinoscape](https://github.com/DinoscapeProgramming)_