### main idea of js
- save the data
- generate the HTML
- make it interactive

- data = information
- (information about our products)


How do we know which product to add?

### Data Attribute
- is just anoter HTML attribute
- allow us to attach any information to an html element

### syntax for data attribute
- is just an Html attribute
  - i.e name = value;
- have to start with "data-"
- then give it any name
- seperate the word with dash(-) i.e data-product-name which is also known as kebab-case

### Modules
- better way to organize our code espically in bigger projects

### Get a Variable Out of a File
1. Add type="module" attribute
2. Export
3. Import

### import syntax
```
import { cart, addtoCart} from "../data/cart.js";

or

import * as cartModule from '../data/cart.js';
cartModule.cart;
cartModule.addToCart('id'); // import everything from the file named cart.js and group this together inside the object cartModule. we can access each import as a property or a method

```
### type="module" attribute
Let's this file get variables out of other files.

### Things to remember while using modules
- put all imports at the top of the file
- we need to use live server

### Benefits of using module
- helps us avoid naming conflicts
- donot have to worry about the order of the file

### entry point
```
<script type="module" src="scripts/amazon.js"></script>
```

### Normilizing the data or deduplicating the data

### utils = utility

### External Libraries
- code that are written by others and we can use those codes in our projects
- code that are outside of our projects