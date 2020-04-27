---
club: lambda
layout: post
header_line: "How to create a new post"
---

### Guidelines to create a new post:
To create a new post, follow the given steps:

1. Write your post in markdown
2. Make sure to have different paragraphs in your post 
3. The front matter of your post should look similar to the following:
```
    ---
    layout:post
    club: "your-club"
    header-line <optional>: "To be displayed below the headline"
    ---
```
4. The club name should be the same as the name of the club which shall present this post. The name should be written in lowercase, without spaces.
5. Save your file in the `_posts` directory in the format `yyyy-mm-dd-title.md`
6. In case your title contains more than a single word, save your post as `yyyy-mm-dd-word1-word2-word3.md`, i.e. each word of the title should be connected by hyphens. For example, this post is saved as `2019-04-25-new-post-readme.md` 

### Additional Notes:
In case you want to have an image at the top of your post, *DO NOT* attach the image on the top of the post. Instead, 
add it in front-matter as `hero_image:"your file here"`


