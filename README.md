Requires npm >= 6.9, because this uses [package aliases](https://github.com/npm/rfcs/blob/latest/implemented/0001-package-aliases.md) to install multiple versions of `sodium-native` side by side.

You also need a platform & node version for which `sodium-native` ships prebuilds. I used node 10.

To install:

```
git checkout npm-aliases
npm install --ignore-scripts
```

Then run:

```
node pass.js
node fail.js
```
