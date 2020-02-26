![Less build](https://github.com/cleoold/Pretty-CSS-Stuff/workflows/Less%20build/badge.svg)

# Pretty-CSS-Stuff
Personal collection of CSS button widgets

### Preview
https://cleoold.github.io/Pretty-CSS-Stuff/

### Where to get
Inside `dist` folder, download and embed `cosbuttons-min.css`.

### Stripping unwanted styles
If you do not want this color for example:
```css
.cos-btn-transparent-black:extend(.cos-btn-transparent all) {
    ...
}
```
You can remove them and only keep the necessary ones. Then run following commands
```bash
% npm run install
% npm run build
```
And take the same file inside `dist`.
