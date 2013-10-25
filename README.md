# Blog experiment
This is a part of the blog-experiment project. It's intended to be used as a git submodule. It contains blog content - posts.
The blog engine is powered by [Poet](https://github.com/jsantell/poet) you can find more info there.

## Files
Each [Markdown](http://daringfireball.net/projects/markdown/syntax) file inside the `posts` folder represents a post.

**Note:** The filename is important since it gets translated to the actual permalink URL to that post.

## Post metadata
Each post starts with a metadata that describes it. The data is wrapped using three dashes `---`.

* `title` Title of the post.
* `author` Post author's full name.
* `date` Date shown when the post was published. (shown in the post header)
* `draft` Boolean true/false if you want this post to be a draft.
* `tags` An array of tags you want this post to belong to.

Example:
```
---
title: "Lorem ipsum"
author: "Nil Gradisnik"
date: "10-24-2013"
draft: false
tags: ["news", "announcements"]
---
```

As long as the dates are set correctly, posts will be sorted by newest first.

## Writing
1. Create a new file inside news folder
2. Set the metadata properly at the top of the file
3. Write the content
4. Save/commit the file into the repository

### Read more
You can define where the post preview ends by using this keywork `<!--more-->`. All the content above this keywork will be shown on the main page, but the content below will be hidden until you get to the full post.

### Author
Nil Gradisnik <nil.gradisnik@gmail.com>