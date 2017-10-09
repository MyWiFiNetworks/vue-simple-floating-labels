# Vue simple floating labels

Simple floating labels as a Vue component without jQuery.

[Check out the demo](https://sabatinomasala.github.io/vue-simple-floating-labels/)

## Getting started

Pull in the package:
``` 
yarn add vue-simple-floating-labels
```

Import the component:
```
import FloatingLabel from 'vue-simple-floating-labels'
export default {
    components: {
        FloatingLabel
    }
}
```
Use in your template:
```
<FloatingLabel
    :config="{label: 'Example'}">
    <input name="example" type="text">
</FloatingLabel>
```

## Config

### hasClearButton (default `true`)
Input field should have a clear button.

### Line (default `true`)
Input field should have a line below it (for accessibility reasons)

### Scale (default `true`)
Turn scale animation on or off

### labelOffset
Set the top and left property of the label.

**Defaults:**
```
{
    top: '10px',
    left: '8px'
}
``` 

### color
Specify the focusColor, lineColor and blurredColor.

**Defaults:**
```
{
    focusColor: '#128CED',
    lineColor: '#128CED',
    blurredColor: 'rgba(3, 23, 40, 0.34)'
}
```

## TODO
* Textarea
* Options
* Integrate with vee-validate

## Credit

* Inspiration: [Pen by Oscar Waczynski](https://codepen.io/osifer/pen/eWvxzB)