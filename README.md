# Harp Blog Prototype

__Testing a new structure for improving the Harp default blog.__

This version includes:

- Dynamic title
- Markup decoration wrapping the post (thumblr style)
- Disqus comments embeded on post pages
- "Read more" feature demonstration in posts
- Posts with metadata

## Using this template with Harp Platform

1. Create a new app
2. Enter `jorgepedret/harp-blog-prototype` as a Custom Boilerplate
3. Select your subdomain
4. Click the Start button

## Using this template with Harp

```
$ git clone git@github.com:jorgepedret/harp-blog-prototype.git
$ cd harp-blog-prototype
$ harp server
// Go to http://localhost:9966
```

## Files and directories

__/public/posts/__

This is where your posts go. Duplicate one of your previous posts to create a new post.

__/public/posts/_data.json__

This is where your post's metadata goes. Take a look at the example data and it'll all make sense.

__/public/_decorator.jade__

This is the decorator that wraps around the post to give it the _tumblr-like_ look. This is also where the _disqus_ widget is embeded.

__/public/about.jade__

A sample _about_ page.

__/public/css/main.less__

Where the main CSS lives

__/public/css/_bootstrap.less__

This is where you configure Twitter Bootstrap. I'm using v3 which is mobile first a less bulky. Feel free to enable/disable components depending on what you need.

__/public/_layout.jade__

This is your default layout. Feel free to play with this file, but don't touch the middle part unless you know what you're doing.

__/public/_data.js__

This is where the title for your root pages lives. You can also add other data that will be accessible through your globals.

__/public/404.jade__

Custom 404 file.

__/harp.json__

Global configuration. Configure your blog title and disqus options.