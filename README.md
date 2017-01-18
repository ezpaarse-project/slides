# Slides
Repository for hosting various slideshows based on [reveal.js](https://github.com/hakimel/reveal.js/).

## Available slideshows
  - [Javascript for newbies](https://ezpaarse-project.github.io/slides/javascript-for-newbies/)

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
