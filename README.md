#jquery.reverse

Simple plugin that reverses the results from a jQuery result set.

* * *

###Usage

```html
<div id='module1' class='module'>Module 1</div>
<div id='module2' class='module'>Module 2</div>
<div id='module3' class='module'>Module 3</div>
```

```javascript
var modules = $('.module');
=> [<div id='module1' class='module'>Module 1</div>
<div id='module2' class='module'>Module 2</div>
<div id='module3' class='module'>Module 3</div>]

modules = modules.reverse();
=> [<div id='module3' class='module'>Module 3</div>
<div id='module2' class='module'>Module 2</div>
<div id='module1' class='module'>Module 1</div>]
```

### Bower installation

    bower install jquery.reverse