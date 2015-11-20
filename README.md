# edk-date-picker

edk-date-picker is a material design date picker component that is compatible with Polymer 1.0+. It is developed by considering material design principles. This responsive component detects page orientation and transforms itself as landscape or portrait.

[MomentJS](http://momentjs.com/) library is used for date functions. Javascript file which contains localization properties is included in this component.
So any language might be set easily by using "locale" attribute. The default one is Turkish.

### Examples

Simple Use:

    <edk-date-picker></edk-date-picker>

Complex Use:

    <edk-date-picker range-selector
                     min="01.15.2015"
                     max="01.25.2015"
                     format="dd.MM.yyyy"
                     locale="tr"
                     value="{{dateValue}}"
                     on-date-selected="_selectionCallback"
                     on-date-cleared="_clearCallback"
                     on-ok-clicked="_okCallback">
    </edk-date-picker>

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--edk-date-picker-color` | General color that effects everything inside component | #009688

### Screenshots

![Portrait Mode View](https://raw.github.com/Turksat/edk-date-picker/master/portrait-mode.png)

![Landscape Mode View](https://raw.github.com/Turksat/edk-date-picker/master/landscape-mode.png)


## Dependenciess

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go into the project main folder and download the element's dependencies:

    bower install

Runnning a simple web server is enough to see the component working.

