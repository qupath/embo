---
title:  "Introduction"
layout: page
categories: introduction
tags: qupath
description: "QuPath workshop"
---

## EMBO Practical Course:<br/> Advanced Methods in Bioimage Analysis

**Welcome to the QuPath practical website for the [EMBO course](https://www.embl.de/training/events/2021/BIA21-01/programme/)!**

This page will contain the key links & data you will need.

Because at least some of you are already familiar with QuPath, and this is an advanced course, we want to focus on things that are *beyond* what is explained in the [QuPath documentation](https://qupath.readthedocs.io/) and [existing video tutorials](http://youtube.com/c/qupath).

With that in mind, we ask you to come prepared so we can maximize the usefulness of the session.

<div class="warning" markdown="block">

### Important preparation!

**Please do the following things _before_ 1 July 2021**:

1. **Download and install** the [**latest stable release of QuPath (v0.2.3)**](https://github.com/qupath/qupath/releases/)
2. **Download the sample images** (you will be sent a direct link by email, but they're also [here](https://qupath.readthedocs.io/en/0.2/docs/intro/acknowledgements.html))
3. **Familiarize yourself with QuPath** via the following tutorials:
  * [Getting started](https://qupath.readthedocs.io/en/0.2/docs/starting/index.html#getting-started)
  * [Projects](https://qupath.readthedocs.io/en/0.2/docs/tutorials/projects.html)
  * [Detecting tissue](https://qupath.readthedocs.io/en/0.2/docs/tutorials/thresholding.html)
  * [Cell detection](https://qupath.readthedocs.io/en/0.2/docs/tutorials/cell_detection.html)
  * [Cell classification](https://qupath.readthedocs.io/en/0.2/docs/tutorials/cell_classification.html)
  * [Pixel classification](https://qupath.readthedocs.io/en/0.2/docs/tutorials/pixel_classification.html)

</div>

QuPath *should* be straightforward to install and work on most computers.
We recommend running it locally to make the most of interactively working with large images.

If you get stuck, you can find help through:

* the [QuPath documentation](https://qupath.readthedocs.io), which includes [installation instructions](https://qupath.readthedocs.io/en/latest/docs/intro/installation.html)
* the [QuPath user forum](https://forum.image.sc/tag/qupath)

If you still have trouble, please let us know early so we can help!

<details markdown="1" class="gifview">
<summary>Why QuPath?</summary>
<br/>
One reason to use QuPath is that it can handle *whole slide images*: intimidating large, high-resolution 2D images, usually of complex tissue sections.

However, QuPath isn't *just* for whole slide images, and there are lots of other applications where it can help.

![Looking at a whole slide image]({{site.baseurl}}/assets/images/gifs/eyes.gif){: .shadow-image .max-width-90}
</details>

## Practical plan

Our plan for the 90 minute practical session is to show how QuPath can be useful both for advanced algorithm developers and for end users.
We intend to cover as much of the following as time allows:

* **What's new in QuPath v0.3?**
* **Making ground truth image annotations (reasonably) fun**
* **Better together: advanced scripting with QuPath + friends**
  * **StarDist**
  * **ImageJ**
  * **OpenCV**
  * **Java Topology Suite**

We're putting the finishing touches on QuPath v0.3.0, which we hope to release in June.
If this happens, we'll notify you and ask you to download that so you can explore the very latest features.
