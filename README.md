### Giosg ui-toolkit

This repo provides an independent extension to Bootstrap 3.

ui-toolkit does not override any styles by default. It is only applied to elements that are inside a container that has class `giosg`

Currently it provides the following:
- New color schemes
- New optional styles for some of the Bootstrap elements like `button` and `panel`
- New elements like `input-inline-edit`

ui-toolkit does not work without Boostrap 3 so it needs to be installed separately. Boostrap is not included in this repo.

ui-toolkit is also somewhat compatible with other Bootstrap extensions like Flatify

### Usage after installing

Just check https://giosg.github.io/ui-toolkit/

### Folder structure
- `sass`
    - Sass files for compiling the toolkit
- `dist`
    - Compiled CSS files
- `icons`
    - Giosg icons generated with IcoMoon.

### How to install

Giosg ui-toolkit extends Bootstrap 3 so you need to install it beforehand.

```
npm install https://github.com/giosg/ui-toolkit
```

```
bower install https://github.com/giosg/ui-toolkit
```

### How to develop

- `npm install`
- Run `npm run build` or `npm run watch`
- Open `index.html` with your favorite browser
- If you want to update icons then check README.md under `icons/`

After you have made changes you should commit changes to `sass` files and the built files under `dist`
