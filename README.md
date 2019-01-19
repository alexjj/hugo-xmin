# Lord Percy

> A theme for [Hugo](https://gohugo.io)

Lord Percy is rather simple, but quite attractive

Lord Percy is forked from the **XMin** theme, written by [Yihui Xie](https://yihui.name). I've tweaked it and combined it with my simple [CSS framework](https://github.com/alexjj/light-and-shite), for use on my own personal [site](https://alexjj.com).

### Instructions

1: Install Hugo.

See the [official instructions](https://gohugo.io/getting-started/installing)

2: Create a new site.

```
hugo new site mysite
```

3: Initialize git

```
cd mysite
git init
```

4: Clone the repo

```
git submodule add https://github.com:alexjj/lord-percy.git themes/lord-percy
```

5: Have a look in the `exampleSite` directory in the `themes\lord-percy` folder. You can copy the `content/`, and `config.toml` files to get started. 

6: Run `hugo server` and enjoy!

### New Posts

To make new posts, simply use the command line:

```
hugo new post/my-first-post.md
```

### Colour

At the top of `/static/style.css` you will see the variable --maincolour defined. Edit this to change the theme's colour.

#### Screenshot

todo..
