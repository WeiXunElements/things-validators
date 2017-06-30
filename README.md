# things-validators

## It is a validator container for importing the configured validator at once.


### It has the following validators.
```html
<things-validator-email></things-validator-email>
<things-validator-phone></things-validator-phone>
<things-validator-url></things-validator-url>
<things-validator-a-month-ago></things-validator-a-month-ago>
<things-validator-before-today></things-validator-before-today>
<things-validator-after-today></things-validator-after-today>
```

Example:
```html
    <things-input-field
       validator="things-validator-email">
    </things-input-field>
```


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-validators/`, where `things-validators` is the name of the directory containing it.
