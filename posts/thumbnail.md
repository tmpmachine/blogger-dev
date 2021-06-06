# Post thumbnail best practice

Provide thumbnail with source from YouTube, or default thumbnail image if source is empty (doesn't have thumbnail),  
```xml
<b:if cond="data:post.featuredImage.isYoutube">
  <img class="thumbnail Youtube" expr:src='data:post.thumbnailUrl'/>
<b:elseif cond='data:post.featuredImage != ""'/>
  <img class="thumbnail" expr:src='data:post.featuredImage'/>
<b:else/>
  <img class="thumbnail" src="https://1.bp.blogspot.com/-Nhc1pM7eOXQ/X0BiafCtGMI/AAAAAAAANPg/D6deHMMuuccYyDlDq8Mfi-afZwmyPcGBgCLcBGAsYHQ/s100/66773032_877684889258401_3684245117129981952_n.jpg"/>
</b:if>

<style>
  /* additional styles for each thumbnail */
</style>
```
