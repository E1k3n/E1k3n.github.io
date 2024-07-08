---
title: My First Post
date: 2024-07-08T20:03:46+02:00
draft: true
toc: false
images: 
tags:
  - untagged
---
# Template post

## Add content 
Add a new page to your site.

```
hugo new content content/posts/my-first-post.md
```

Hugo created the file in the content/posts directory. Open the file with your editor.

```
+++
title = 'My First Post'
date = 2024-01-14T07:07:07+01:00
draft = true
+++
```
Notice the **draft** value in the front matter is **true**. By default, Hugo does not publish draft content when you build the site. Learn more about draft, future, and expired content.

Add some Markdown to the body of the post, but do not change the draft value.

+++
title = 'My First Post'
date = 2024-01-14T07:07:07+01:00
draft = true
+++
## Introduction

This is **bold** text, and this is *emphasized* text.

Visit the [Hugo](https://gohugo.io) website!
Save the file, then start Hugo’s development server to view the site. You can run either of the following commands to include draft content.

hugo server --buildDrafts
hugo server -D
View your site at the URL displayed in your terminal. Keep the development server running as you continue to add and change content.

When satisfied with your new content, set the front matter draft parameter to false.>)