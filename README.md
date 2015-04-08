# Blog

## Usage

### New author

Add a new author in the `authors` variable located in `_config.yml`. Moreover, you should add a picture in `/assets/authors` with your name

Example:

```ruby
authors:
  john:
    name: John Doe
    bio: A real good story teller
```

Then, copy your avatar to `/assets/authors/john.jpg`

### Write a blog post

Create a new file in `_posts` containing the date and the title of your post. Blogposts are written in markdown.
If you want to add an image to a blog post, you can just copy your image to `/assets/article_images/<blog-post>/<name-of-your-image>`

#### Metadata

* `author: <short-name>`: the name of the author. Should be the key in the authors list (i.e: `john` instead of `John Doe`)
* `image: /assets/article_images/<blog-post>/cover.jpg`: the link to the cover image. Don't forget to check image rights, size and to optimize it
* `layout: post`: except if you really know what you're currently doing, it should be `post` everytime
* `published: <boolean>`: indicates if the post is published or not

## Credits

The blog is powered by [jekyll now](https://github.com/barryclark/jekyll-now) with the [mediator theme](https://github.com/dirkfabisch/mediator).
