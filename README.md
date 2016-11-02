# css-checkbox-radio
Beautify Radio and Checkbox.

### Demo

[Demo](https://github.com/chutou/css-checkbox-radio)

### Install
- bower: `bower install --save css-checkbox-radio`
- npm: `npm install --save css-checkbox-radio`

### Usage

```html
<link rel="stylesheet" href="bower_components/css-checkbox-radio/dist/css-checkbox-radio.css">
```

**Checkbox**

```html
<h1>css-checkbox-radio</h1>
    <div class="col-6">
        <h2>checkbox default</h2>
        <div>
            <input class="checkbox" type="checkbox" name="layout" id="1">
            <label for="1">Normal</label>
        </div>
        <div>
            <input class="checkbox" type="checkbox" name="layout" id="2" checked="checked">
            <label for="2">Checked</label>
        </div>
        <div>
            <input class="checkbox" type="checkbox" name="layout" id="3" disabled="disabled">
            <label for="3">
                Disabled
            </label>
        </div>
        <div>
            <input class="checkbox" type="checkbox" name="layout" id="4" checked disabled="disabled">
            <label for="4">Checked && Disabled</label>
        </div>
        <h2>checkbox large</h2>
        <div>
            <input class="checkbox" type="checkbox" name="layout" id="10">
            <label class="lg" for="10">Normal</label>
        </div>
        <div>
            <input class="checkbox" type="checkbox" name="layout" id="20" checked="checked">
            <label class="lg" for="20">Checked</label>
        </div>
    </div>
```

**Radio**

```html
<div class="col-6">
        <h2>radio default</h2>
        <div>
            <input class="radio" type="radio" name="radio" id="11">
            <label for="11">Normal</label>
        </div>
        <div>
            <input class="radio" type="radio" name="radio" id="22" checked>
            <label for="22">Checked</label>
        </div>
        <div>
            <input class="radio" type="radio" id="33" disabled="disabled">
            <label for="33">Disabled</label>
        </div>
        <div>
            <input class="radio" type="radio" id="44" disabled="disabled" checked>
            <label for="44">Checked && Disabled</label>
        </div>
        <h2>radio large</h2>
        <div>
            <input class="radio" type="radio" name="radio-large" id="101">
            <label class="lg" for="101">Normal</label>
        </div>
        <div>
            <input class="radio" type="radio" name="radio-large" id="202" checked>
            <label class="lg" for="202">Checked</label>
        </div>
    </div>
```

### Browser compatibility

- Chrome
- Firefox
- Safari
- Opera
- IE9 && IE9+


### License

  [MIT](LICENSE)
