# Game of Thrones gifs

Storage place for all my favorite Game of Thrones gifs (in glorious gfycat form). This is my own custom fork of jglovier/gifs completely dedicated to collecting GoT gifs. I borrowed some of the basic scss and layout ideas from him. For a broader collection of gifs, please check out [his repository](https://github.com/jglovier/gifs).

## USage

I went ahead and built a page generation script that will create a static html page out of imy list of gfys. First, you need to compile the sass to css. Then you generate the `index.html` page

```bash
$ compass compile
$ ./gfy.py
```

That's it! The new index page is ready to go.

## Contributing

If you have a gif that you think belongs, please fork and submit a pull request. Simply add the link to the gfycat to the dictionary in `gfy.py` and it should be good to go!