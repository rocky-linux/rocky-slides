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