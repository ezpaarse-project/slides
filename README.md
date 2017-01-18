# Slides
Repository for hosting various slideshows based on [reveal.js](https://github.com/hakimel/reveal.js/). Available at [ezpaarse-project.github.io](https://ezpaarse-project.github.io/slides/).

## How to add a slideshow
Create a new directory for your slideshow:
```console
  mkdir myslideshow
```

Copy the patched index file from the `reveal.js` directory:
```console
  cp reveal.js/index.html myslideshow/
```

Edit as you wish, then add it to the repository:
```console
  git add myslideshow
  git commit myslideshow -m "new slideshow!"
  git push
```

You're done! You can access your slidehow at https://ezpaarse-project.github.io/slides/myslideshow/

## How to view locally
In most cases, you just need to open `index.html` in your favourite browser. However, some features like **PDF export** only work if you serve this repository from a local webserver.

Here is one solution using Node.js:
```console
  # Install a webserver module
  npm install -g http-server

  # Run the webserver on the root of the repository
  http-server /path/to/the/slides
```
Then open [http://localhost:8080/](http://localhost:8080/).
