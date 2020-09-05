# `iso8601` 
```html
<time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'></time>
```
Resulted in in *iso8601* formatted timestamp. e.g. `2020-08-28T18:15:00+07:00`.

<br>

# `format` operator
```html
<b:eval expr='data:post.date format "MMM dd" '/>
```
Resulted in Month (short) and day format. e.g. `Aug 05`.

# Known date format
format | Description | result
---|---|---
MMM | Month (short) | Aug
dd | Day | 05
YYY | Full year | 2020

<br>

---

# References
https://so-how-do-i.blogspot.com/2017/03/change-my-post-timestamps-to-custom.html
