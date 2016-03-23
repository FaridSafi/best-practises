# Best Practises

### Style Guide
See [AirBnb style guide](https://github.com/airbnb/javascript)

### Architecture / Structual best practises
See [Mantra](https://github.com/kadirahq/mantra) and its [spec](https://kadirahq.github.io/mantra/)

### Naming Convention
Upper camel case for files which exports single React component or class e.g. `PostList.js`.

Otherwise, use underscore e.g. `method_stubs`.

#### Sharing component names
React & React Native components should share names and method names where possible.

### Code Sharing
* Config - immutable javascript object with Twitter URL
* Translations - share translation key json e.g. `"send_bitcoin": "Send Bitcoin"`
* Share classes / prototypal methods - e.g. `transaction.getUser()`

### Design Langauge
Material design components.

Using [Material UI](http://www.material-ui.com/) for web app

[Material UI Kit](https://github.com/xinthink/react-native-material-kit) cna be used for RN app
