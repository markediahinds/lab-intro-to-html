# HTML Introduction Lab

In this lab, you will have an opportunity to get familiar with some of the more common and basic tags of HTML.

---

## Lab Setup

### Getting started

1. Fork and clone this repository.

1. Navigate to the `settings` tab on GitHub, then choose `Pages` from the menu. Configure the `Build and Deployment` to have a `Source` of `Deploy from a branch` and select the `main` branch for deployment. Deployments can take a few minutes, so get started on the lab, and then be sure to check the deployment after you have made a few commits.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

## Instructions

### Make a home page with navigation

Create a home page with the appropriate boilerplate code, and then add the following:

- An `h1` element that says `Home`.
- A `nav` element that will contain links to other HTML files:

- Create a new folder called `sundial` and add an `index.html` file.
- Add boilerplate code and an `h1` with the word `Sundial` and add navigation that allows you to navigate back to home and also to the following `index.html` file
- Then, create another new folder called `recipe` and add an `index.html` file.
- Add boilerplate code and an `h1` with the word `Recipe` and add navigation that allows you to navigate back to home and also to the `Sundial` `index.html` file

> **Note**: Remember, you can open the HTML file in your browser by typing `open index.html` in the terminal.

### Format a page about Sundials

Go to the `index.html` file in the `sundial folder`.

In the file, you will copy and paste the Sundial text below into your html file.

```html
Sundial From Wikipedia, the free encyclopedia. A sundial measures time by the
position of the sun. The most commonly seen designs, such as the 'ordinary' or
standard garden sundial, cast a shadow on a flat surface marked with the hours
of the day. As the position of the sun changes, the time indicated by the shadow
changes. However, sundials can be designed for any surface where a fixed object
casts a predictable shadow. Most sundial designs indicate apparent solar time.
Minor design variations can measure standard and daylight saving time, as well.
History Sundials in the form of obelisks (3500 BC) and shadow clocks (1500 BC)
are known from ancient Egypt, and were developed further by other cultures,
including the Chinese, Greek, and Roman cultures. A type of sundial without
gnomon is described in the old Old Testament (Isaiah 38:2). The mathematician
and astronomer Theodosius of Bithynia (ca. 160 BC-ca. 100 BC) is said to have
invented a universal sundial that could be used anywhere on Earth. The French
astronomer Oronce Fine constructed a sundial of ivory in 1524. The Italian
astronomer Giovanni Padovani published a treatise on the sundial in 1570, in
which he included instructions for the manufacture and laying out of mural
(vertical) and horizontal sundials. Giuseppe Biancani's Construction instrumenti
ad horologia solaria discusses how to make a perfect sundial, with accompanying
illustrations. Installation of standard sundials Many ornamental sundials are
designed to be used at 45 degrees north. By tilting such a sundial, it may be
installed so that it will keep time. However, some mass-produced garden sundials
are inaccurate because of poor design and cannot be corrected.
```

[Source: Wikiversity](https://en.wikiversity.org/wiki/Web_Design/HTML_Challenges)

**Note:** You can put the navigation at the bottom of the page

Now double-click the file to open it in your browser, and you'll see it doesn't look like the example image below. You haven't added any HTML tags to your code, so the browser renders your text exactly as is.

[![Html challenge1.png](https://upload.wikimedia.org/wikiversity/en/3/3d/Html_challenge1.png)](https://en.wikiversity.org/wiki/File:Html_challenge1.png#/media/File:Html_challenge1.png)

_By Michael Nelson - screenshot on ubuntu Linux, [CC BY-SA 2.5](http://creativecommons.org/licenses/by-sa/2.5 "Creative Commons Attribution 2.5")_

Your challenge will be to add HTML tags to make your file look like the one in the image:

- headings (`<h1>`, `<h2>`, `<h3>` etc.)
- paragraphs (`<p>`)
- emphasis and strong (`<em>` and `<strong>`)

A web browser will display the `h1` heading very large, the `h6` heading relatively small, and all the other headings in between! But don't get into the habit of selecting an `h4` heading just because it's the size you want! You can always modify the size of your elements using your stylesheet (more on that later).

The key is to use the headings to structure your information in a practical (and meaningful) way! For example, every page should only have one main heading - your `h1` heading. An `h2` heading should only be a sub-heading of your `h1` heading. Similarly, an `h3` heading should only be a sub-heading of an `h2` heading, etc.

### Create a recipe page

Make a file `recipe.html` that renders a recipe of your choice. It should include elements so that it looks very similar to this:

![screenshot](./images/pbjImage.png)

Include the following:

1. A main heading. `<h1>`
1. An image of your choice (remember you can size it by using the `height` attribute if it is too big or too small).
1. A description. `<p>`
1. An unordered list of ingredients. `<ul>`
1. An ordered list of directions. `<ol>`
1. Add a link to a similar recipe somewhere online.
