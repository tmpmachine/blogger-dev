```xml
<b:loop values='data:posts' var='post'>
  <img expr:src='data:post.thumbnailUrl'/> 
  <a expr:src='data:post.url'/> <data:post.url/> </a> 
  <h1><data:post.title/></h1> 
  <p><data:post.body/></p> 
</b:loop>
```
