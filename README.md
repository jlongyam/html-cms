# [html-cms](https://github.com/jlongyam/html-cms)

Tiny CMS in single file plain html

## Goal

- Code playground html, js, css
- Code preview
- File snippet
- Keep `<mark>`
- Small size, `8 KB`
- Configurable
- Mobile friendly
- Data stored in EOF
- [Demo](https://jlongyam.github.io/html-cms/src/file.html)

## View mode

### Method 1

Switch page view by added `data-mode`

value: `snippet` or `website`, default is **empty**

Example:

```html
<html lang="en" data-mode="snippet">
```

### Method 2

Add query search to URL `file.html?mode=[Value]` 

Example:

```URL
/display.html?mode=snippet
or
/display.html?admin=snippet
```

If `data-set` was present in `file.html` then want to go back to

admin mode, it can be access by `?admin`

Demo:

- [mode snippet](https://jlongyam.github.io/html-cms/src/file.html?mode=snippet)
- [mode website](https://jlongyam.github.io/html-cms/src/file.html?mode=website)

## Roadmap

- [x] Fix tab on desktop
- [ ] Add marker button for mobile
- [x] Add mode `live` and mode `snippet`
- [ ] Use sessionStorage
- [ ] Split content to tabs
- [ ] Additional menu space
- [x]] Minify
- [x] Responsive

[MIT](LICENSE) License

## Changelog

- v0.1.0
	
	first stable release

- v0.0.2

	single file `display.html`