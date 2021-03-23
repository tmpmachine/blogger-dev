# Blog Widget
| data | description | type
|---|---|---
| `posts` | List of [posts](#posts) by page type | array |

# Posts
Available on [Blog widget](#blog-widget) > `posts`.
| data | description | type |
|---|---|---|
| `featuredImage` | Returns first image URL for both image added by URL and image hosted on Google Product (Photos, YouTube, Blogger). | string |
| `featuredImage.isYoutube` | Check if post featured origin is YouTube | boolean |
| `thumbnailUrl` | Returns first image URL. Only available for image hosted on Google Products (Photos, YouTube, Blogger). | string |
| `title` | Post title | string |
| `body` | Post content, summary included | string |
