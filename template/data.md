# <b:with>
Set scoped variable.
```xhtml
<b:with var='pageLabels' value='{"Blogger Development Series","Guitar Tutorial"}'>
  <b:if cond='data:blog.searchQuery in data:pageLabels OR data:blog.searchLabel in data:pageLabels'>
    You are searching posts containing any of these labels: Blogger Dev, Guitar Tutorial
  </b:if>
</b:with>
```
