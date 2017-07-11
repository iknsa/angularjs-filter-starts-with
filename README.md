# iKNSA AngularJS Filter By 'Start With'

### This is a small module with a filter for array of strings which filter the list with the start-with

## Installation:
```
bower install --save 
```

#### Example:
In your controller
```
scope.glossaries = [];
scope.activeLetter = 'a';
```

In your template
```
<ul class="pagination">
    <li ng-class="{active: activeLetter === 'a'}"><a href ng-click="activeLetter = 'a'">A</a></li>
    <li ng-class="{active: activeLetter === 'b'}"><a href ng-click="activeLetter = 'b'">B</a></li>
    <li ng-class="{active: activeLetter === 'c'}"><a href ng-click="activeLetter = 'c'">C</a></li>
    <li ng-class="{active: activeLetter === 'd'}"><a href ng-click="activeLetter = 'd'">D</a></li>
    <li ng-class="{active: activeLetter === 'e'}"><a href ng-click="activeLetter = 'e'">E</a></li>
    <li ng-class="{active: activeLetter === 'f'}"><a href ng-click="activeLetter = 'f'">F</a></li>
    <li ng-class="{active: activeLetter === 'g'}"><a href ng-click="activeLetter = 'g'">G</a></li>
    <li ng-class="{active: activeLetter === 'h'}"><a href ng-click="activeLetter = 'h'">H</a></li>
    <li ng-class="{active: activeLetter === 'i'}"><a href ng-click="activeLetter = 'i'">I</a></li>
    <li ng-class="{active: activeLetter === 'j'}"><a href ng-click="activeLetter = 'j'">J</a></li>
    <li ng-class="{active: activeLetter === 'k'}"><a href ng-click="activeLetter = 'k'">K</a></li>
    <li ng-class="{active: activeLetter === 'l'}"><a href ng-click="activeLetter = 'l'">L</a></li>
    <li ng-class="{active: activeLetter === 'm'}"><a href ng-click="activeLetter = 'm'">M</a></li>
    <li ng-class="{active: activeLetter === 'n'}"><a href ng-click="activeLetter = 'n'">N</a></li>
    <li ng-class="{active: activeLetter === 'o'}"><a href ng-click="activeLetter = 'o'">O</a></li>
    <li ng-class="{active: activeLetter === 'p'}"><a href ng-click="activeLetter = 'p'">P</a></li>
    <li ng-class="{active: activeLetter === 'q'}"><a href ng-click="activeLetter = 'q'">Q</a></li>
    <li ng-class="{active: activeLetter === 'r'}"><a href ng-click="activeLetter = 'r'">R</a></li>
    <li ng-class="{active: activeLetter === 's'}"><a href ng-click="activeLetter = 's'">S</a></li>
    <li ng-class="{active: activeLetter === 't'}"><a href ng-click="activeLetter = 't'">T</a></li>
    <li ng-class="{active: activeLetter === 'u'}"><a href ng-click="activeLetter = 'u'">U</a></li>
    <li ng-class="{active: activeLetter === 'v'}"><a href ng-click="activeLetter = 'v'">V</a></li>
    <li ng-class="{active: activeLetter === 'w'}"><a href ng-click="activeLetter = 'w'">W</a></li>
    <li ng-class="{active: activeLetter === 'x'}"><a href ng-click="activeLetter = 'x'">X</a></li>
    <li ng-class="{active: activeLetter === 'y'}"><a href ng-click="activeLetter = 'y'">Y</a></li>
    <li ng-class="{active: activeLetter === 'z'}"><a href ng-click="activeLetter = 'z'">Z</a></li>
</ul>

<tr ng-repeat="glossary in glossaries | iknsaAngularjsFilterStartsWithFilter: activeLetter">
</tr>
```
