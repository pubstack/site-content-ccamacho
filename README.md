# How to publish new content in www.formulad.org

This tutorial will help you to go through the process of
creating a new post on the different categories for the
press team content.

## Create a user in gitlab.com

As all the site is text files based, we will
use GitLab for versioning and to control the
deployment pipelines when a press team
member publish new content to the site.

## Accesing the content repository

This is the first view that a writher should see when posting new
content.

![](images/tutorial_00.png)

* A: Content repo address. This is the current repository address ussually `site-content-<username>`.
* B: Images folder. I this folder each writer can add their own pictures for their articles, there
must be uploaded only JPG, PNG and GIF images.
* C: Demo post with all markdown syntax. This is a demo post with all the information needed to create
new articles. Writers can copy/paste this file and update it according their needs.
* D: This README.md tutorial

## Demo post content and syntax

This section will describe how each article must be created in order to work with the
publishing workflows.


### General description

![](images/tutorial_01.png)

* A: The article language, it can be `en` if it's English or `es` if it's an Spanish article.
* B: The main article picture, this will be the picture displayed in the website's main page,
also will be the main at the beginning of the article, the name must be
`assets/images_articles/<username>/images/<image>`. The only that needs to be changes is the
file name, as the example already have the correct path.
* C: The author name
* D: The author flickr picture id, this value will be provided in the example, so it shouldnt be
needed to update it.
* E: The writer gitlab user id, this valued is correctly provided in the example so it shouldnt be
needed to update it.
* F: This value `published` is configured to false by default, once the article is revised and
ready to be published an user with higher privileges will change it, it shoulnd't be updated
by writers.


![](images/tutorial_02.png)

* A: The article body, the syntax used for all articles in Markdown, so by default we provide a
full example with all components that will be needed. Writers can update this as needed and all
the parts not needed can be removed until the end of the file.

![](images/tutorial_03.png)

* A: This is an example about the code required to add an image aligned to the left of the article.


![](images/tutorial_04.png)

### How to upload a new post

The first step is to download, rename the demo file and upload the new one.
![](images/tutorial_05.png)




### How to upload a new image
![](images/tutorial_06.png)



## How to verify the recently posted article

## Finishing the process
![](images/tutorial_07.png)

