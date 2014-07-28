# SUIT CSS components-text-input

Read more about [SUIT CSS](https://github.com/suitcss/suit/).

## Installation

* Download: [zip](https://github.com/briandrum/suitcss-text-input/zipball/master)

## Features

## Available classes

* `TextInput`: core component
* `TextInput--multiline`: multiline input
* `TextInput-label`:
* `TextInput-field`:
* `TextInput-field:enabled`:
* `TextInput-field:disabled`:
* `TextInput-field:invalid`:
* `TextInput-field:in-range`:
* `TextInput-field:out-of-range`:
* `TextInput-field:read-only`:
* `TextInput-field:required`:

## Configurable variables

* `--TextInput-border-color`
* `--TextInput-border-width`
* `--TextInput-color`
* `--TextInput-disabled-opacity`
* `--TextInput-font`
* `--TextInput-padding`

## Use

```html
<div class="TextInput [TextInput--disabled|TextInput--multiline]">
  <div>

  </div>
</div>
```

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To generate the testing build.

```
npm run build-test
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 9+
