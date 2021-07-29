---
layout: default
title:  Images
nav_order: 3
---
# Adding images to your page or post

#### Adding an image is super easy! Here are a few methods
[View the source Markdown for this page](https://raw.githubusercontent.com/ubc-lib-geo/gis-workshop-waml-template/master/content/examples/images.md)



___

**Add an image from the web:**

Start an in-line link with an exclamation point then place the alt text in the brackets followed by the image link in the parentheses:

```
![Kenobi](https://upload.wikimedia.org/wikipedia/en/3/32/Ben_Kenobi.png)
```

![Kenobi](https://upload.wikimedia.org/wikipedia/en/3/32/Ben_Kenobi.png)

You can also add images "reference style." This is handy if you don't want to clutter up your Markdown or if you need to use an image more than once. You can just place the references at the bottom of the page. It goes like this:

```
![GOAT][Simone]

[Simone]: https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Simone_Biles_Rio_2016e.jpg/256px-Simone_Biles_Rio_2016e.jpg
```

![GOAT][Simone]

Nice job!

___  

**Add an image from your directory:**

You can also add images from a file directory. If you're using GitHub Pages, that means you would want a folder where your content or images live in your GitHub repository. But note that internal links from a "post" can be a little tricky. See the [documentation](https://jekyllrb.com/docs/liquid/tags/#links).  

```
![Good Boy](content/img/mtn-dog.jpg)
```

![Good Boy](content/img/mtn-dog.jpg)


Sweet!

___

**Add a different format:**

Want to put a gif in there? No problem!

```
![Surfer Boy](https://media.giphy.com/media/dJUtqIcqeyMvK/giphy.gif)
```

![Surfer Boy](https://media.giphy.com/media/dJUtqIcqeyMvK/giphy.gif)

"gif" is pronounced with a hard "g"
{: .note}

___

**Link an image:**

To link an image, you just need to embed the image syntax within the syntax for a hyperlink:

Here's a regular link:

```
[CUB site](https://www.colorado.edu/)
```

[CUB site](https://www.colorado.edu/)

Here's a linked image:

```
[![CU Logo](https://www.colorado.edu/profiles/express/themes/ucb/images/cu-boulder-logo-text-white.svg)](https://www.colorado.edu/)
```

[![CU Logo](https://www.colorado.edu/profiles/express/themes/ucb/images/cu-boulder-logo-text-white.svg)](https://www.colorado.edu/)

_Click Me!_

So easy, right?!

____

**Need to get extra fancy?**

You can also add html directly to Markdown. Say you wanted to change the size of an image, for example.


```
<img src='content/img/mtn-dog.jpg' width='250' alt='Good Boy'>
```


<img src='content/img/mtn-dog.jpg' width='250' alt='Good Boy'>


![Snakes](https://i.giphy.com/media/5xtDartXnQbcW5CfM64/giphy.webp)

<!--reference links-->
[Simone]: https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Simone_Biles_Rio_2016e.jpg/256px-Simone_Biles_Rio_2016e.jpg
