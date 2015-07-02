totem-application
=================

[![XWiki labs logo](https://labs.xwiki.com/xwiki/bin/download/Developments/Xlabs/xwiki-labs-project.png "XWiki labs")](https://labs.xwiki.com/xwiki/bin/view/Main/WebHome)

Application that allows to create totems.

A Totem is a content composed of several sections and each section contains multiple items.

A section can be displayed with different ways according to the concept of displayers (For example : Carousel, Article, image, video, simple text ...etc).

In a section several parameters can be configured such as : section width, section order, background-color, background-image ... etc.

## Building and installing from source

In order to build you'll need [maven](http://maven.apache.org). Make sure you have a suitable `settings.xml` in your `.m2` directory as described [here](http://dev.xwiki.org/xwiki/bin/view/Community/Building).

* run `mvn install`
* Import the generated XAR under `totem-application/target/` to an XWiki instance.

## Dependencies
* Multiselect custom display 1.2 (to install through the Extension Manager)
