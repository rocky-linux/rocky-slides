# How to generate your presentation

## Install Marp

Install Marp and Marp-Cli based on their documentation:

* https://github.com/marp-team/marp-cli

## Generate your deck

Feel free to rename the `./slides/demo.md` for anything you like and to customize your presentation.

Then execute the marp command:

```
marp slides/demo.md --bespoke.progress --html -o public/index.html
```

Don't forget to copy the `./slides/{css,img}` folder into your `public` repository.

You can now open the `./public/index.html` file in your preferred browser.

### Using Github Actions

You can also fork this repos and modify the `./slides/demo.md` for your needs and use our GitHub actions to generate your presentation.

## Demo

Please visite our GitHub page [here](https://rocky-linux.github.io/rocky-slides/)