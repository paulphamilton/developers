# Small Victories Developer Resources

These are resources for customizing the functionality and appearance of a Small Victories website. They range from easy to more advanced – some are drag-and-drop and some require some coding. They’re all meant to extend the basic functionality of Small Victories to allow you to build customized, full-function websites for personal, enterprise, or client uses.

If you’re looking for help with basic Small Victories stuff like setting up a custom URL, ordering and naming files, adding captions to images, or using individual themes, check out the Small Victories [Getting Started Guide](http://docs.smallvictori.es).

## Introduction

There are three main ways to build custom Small Victories websites.

1. [Customize a Default theme](#customizing-a-default-theme)
2. [Use a Custom theme](#using-a-custom-theme)
3. [Build your own theme](#building-your-own-theme)
4. [Host your own code](#hosting-your-own-code)

```
.
├── drop-ins                       # code snippets
├── themes-default                 # default SV templates
├── themes-custom                  # custom sites based on default templates
└── build-your-own                 # building a theme from scratch
```

----

## Drop-ins

Drop-ins are code snippets that perform specific functions in a Small Victories website. Each one has a `README` file with instructions on how to use it.

```
.
├── drop-ins
│   ├── add-opengraph
│   ├── filters-feed
│   └── filters-slideshow
.
```
----

## Customizing a Default theme
Default themes are the standard themes built into Small Victories. You can customize theme however you please, from simple stuff like changing the fonts to completely reconfiguring the layout.

We’ve included two sets of files for you to reference:
### `/default-files`
This is exactly how a new SV site appears in your Dropbox when it’s created, including default files. As with a real SV site, this doesn’t include the base HTML, CSS, or JS for the template.

Use this when: you want to run a site locally and customize it using CSS and JS.

## `/source-files`
This is the source code – including HTML/CSS/JS – for a template.

Use this when: you want to reference the page structure, specific class names, etc.

For more info on individual default themes, go the Themes page.

```
.
├── themes-default                 # default SV themes
│   ├── default-files              # generated files when creating a new SV site
│      ├── blank
│      ├── blog
│      ├── campaign
│      ├── document
│      ├── ecommerce
│      ├── feed
│      ├── homepage
│      ├── html
│      ├── presentation
│      └── slideshow
│   └── source-files                # compiled theme HTML when exporting an SV site
│      ├── blank
│      ├── blog
│      ├── campaign
│      ├── document
│      ├── ecommerce
│      ├── feed
│      ├── homepage
│      ├── html
│      ├── presentation
│      └── slideshow
.
```

----

## Using a Custom theme
Custom themes are themes built by the SV community. By following the instructions included in the `README`, you can use these themes for your own SV sites. You can also add your own further modifications to a Custom theme.

```
.
├── themes-custom                  # custom themes
│   ├── djh-photo-theme            # generated files when creating a new SV site
│   └── unstack                    # compiled theme HTML when exporting an SV site
.
```

----

## Building your own theme

To build your own themes, you’ll need some basic understanding of HTML/CSS/JS.

#### Workflow


####

----

## Hosting your own code

If you just need to host your own HTML/CSS/JS, whether for simple sites or using your own static site generator, SV is perfect for that too.

1. Create a new site
2. Set the theme to HTML
3. Drop in your filesstatic

You can use HTML/CSS/JS files plus any assets you need. You can use relative filepaths just as you would normally.
