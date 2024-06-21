<h1><a href="http://camohub.github.io/jquery-sortable-lists/index.html">jquery-sortable-lists</a></h1>
<h2>jQuery plugin to sorting lists also the tree structures with every possible option.</h2>

<h3>Updated the library to ES6 standard with jQuery support.</h3>
<p><b>This code is ES6 version of <a href="https://github.com/camohub/jquery-sortable-lists">jquery-sortable-lists</a>.</b></p>


## How to use?
<p>
Instead of <code>$('#myList').sortableLists( options );</code></p>

```bash
import SortableList from './js/sortableList';
const sortable = new SortableList('#sTree2', options);
sortable.sortableListsToArray();
sortable.sortableListsToHierarchy();
sortable.sortableListsToString();
```
