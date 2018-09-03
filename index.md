var Dropdown = require('dropdown');

var dropdown = new Dropdown('.fruits-dropdown');

dropdown
.add('Banana')
.add('Apple', function(){ console.log('Apple selected'); })
.add('Lemon', function(){ console.log('Lemon'); })
.add('Remove "Apple"', function(){
  dropdown.remove('Lemon');
})
.focus('Apple');

## Salticidae Inventory of Nicaragua 

Here will be information regarding the general purpose of this page.

### How to Use this Field Guide
1. observe your specimine
2. note the color and shape
3. take a photo for later reference
4. identify using the dichotomous key

### Spiders

[About Us](Darachnid.github.io/About.md)
