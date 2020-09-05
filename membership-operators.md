# `in` operator
Example(s) :
```html
<b:eval expr='"Foo" in ["Foo","Bar","Baz"]'/>
```
The result of the operation will be: true since the string Foo is in the array.

<br>

# `contains` operator
Example(s) :
```html
<b:eval expr='["Foo","Bar","Baz"] contains "Foo"'/>
```
The result will be: true since the array contains the string Foo. The result can be false if the dataset does not contain Foo.

```html
 <b:eval expr='data:blog.searchQuery contains "label:" AND data:blog.searchQuery contains "Music"'/>
```
Result `true` if search query contains both word "label:" and "Music" as in `?q=label:Music`.
 
<br>

# References
https://bloggerbook.blakbin.com/2018/11/blogger-membership-operator.html
