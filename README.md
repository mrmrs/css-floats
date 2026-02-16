# css-floats

Functional CSS for floats

## Filesize

| File | Size |
|------|------|
| `dist/floats.css` | 641 bytes |
| `dist/floats.min.css` | 421 bytes (145 Gzipped) |

## Install

```sh
npm install css-floats
```

## Usage

### Import

```css
@import "css-floats";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-floats/dist/floats.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-floats/dist/floats.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.fl` | `float: left;   display: inline;` |
| `.fr` | `float: right;   display: inline;` |
| `.fn` | `float: none;` |
| `.fl-s` | `float: left;     display: inline;` |
| `.fr-s` | `float: right;     display: inline;` |
| `.fn-s` | `float: none;` |
| `.fl-m` | `float: left;     display: inline;` |
| `.fr-m` | `float: right;     display: inline;` |
| `.fn-m` | `float: none;` |
| `.fl-l` | `float: left;     display: inline;` |
| `.fr-l` | `float: right;     display: inline;` |
| `.fn-l` | `float: none;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.fl-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/floats.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/floats.css` — formatted
- `dist/floats.min.css` — minified

## License

MIT
