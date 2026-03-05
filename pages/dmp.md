---
title: Data Management Plan
layout: page
permalink: /dmp.html
---


# Project Title – Project Subtitle

## Data Management Plan

### Project Description

Our project is a collection of pieces of art, all depicting tragic couples from Greek mythology. These objects can be dated from the 15th to the 19th century, and are sourced from a variety of museums in the USA and Europe. This project is hosted on GitHub, utilizing the CollectionBuilder Sheets template for GitHub Pages.

### Roles and Responsibilities

#### Group Members: Summer Maxim, Arden Messinger

We have shared responsibilities for this project. We’ve split the duties of finding and uploading objects, writing metadata, and working on the technical side of the website.

### Anticipated Data

We have gathered our data from various museums in the USA and Europe. This data consists of images of artwork depicting tragic couples from Greek mythology, and associated information such as the creator and the date and locations of creation.

| Item Description | File Type | Size (in MB) | \# of Items | License(s) | Sources |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Image files of artwork of tragic couples in Greek mythology** | **.JPG** | **28.9** | **24** | **Public Domain CC-BY-NC-SA CC0 CC-BY CC-BY-NC-ND**  | **Philadelphia Museum of Art, British Museum, Paris Musées, BALaT KIK-IRPA, Getty Museum, National Galleries of Scotland, The Metropolitan Museum of Art, The National Gallery, Spencer Museum of Art** |
| **Image files of artwork of tragic couples in Greek mythology** | **.PNG** | **9.21** | **1** | **Public Domain** | **Städel Museum** |

**Documentation and Metadata**

All of our metadata will be accessible through our public GitHub repository and the “Data” tab on our CollectionBuilder website. In addition, our data dictionary will be available on the data management plan tab of our website.

### Storage and Backup

Our images and metadata are stored in multiple places. They are both stored on GitHub, and there are backups on Google Drive and our personal computers. Our repository is stored on GitHub.

### Data Sharing

Our data is publicly shared on both our GitHub repository and our CollectionBuilder website. People are able to download the source data directly from our repository. We also provide source links for each object, linking to their original museum collection page where we collected our data.

### Period of Data Retention

We plan to keep our backups of our data on Google Drive and our personal computers. We will maintain our CollectionBuilder site for the duration of the term. Afterwards, the site will remain publicly accessible, though we will not actively maintain or update it.

### Licensing and Ethical Issues

All of the images in our collection are under the public domain, and many of them are also under a Creative Commons license that permits them to be used for our purposes. Each object has a link to its applicable rights statement.

## Appendix: Data Dictionary

| field | definition | example |
| :---- | :---- | :---- |
| objectid | Unique identifier for each object | tlph01 |
| filename | Name of the file, including file type extension. Our filenames consist of the tragic couple depicted in the image, the medium of the artwork, and a number for differentiation | paris\_helen\_drawing\_01.jpg |
| title | The title of the object, as listed in its museum context. If there was not a listed title, we listed the scene depicted and the medium of the artwork. | Drawing of the Abduction of Helen |
| creator | The name of the artist or printmaker who created the object | Bartolommeo Pinelli |
| date | The year or time period the object was created | 1827 |
| description | A brief description of the piece of art | Drawing of Helen and Paris walking towards a Trojan boat on a rocky shore |
| medium | The art medium of the object | Drawing |
| subject | The names of the characters depicted in the piece of art | paris;helen |
| location | The location where the object is currently housed | London, England |
| location\_created | The location where the object was created, if known | Rome, Italy |
| latitude | The geographic coordinate detailing the north-south position of the location of the object’s creation, if known | 41.5336 |
| longitude | The geographic coordinate detailing the east-west position of the location of the object’s creation, if known | 12.2858 |
| source | A link to the museum’s digital collection listing of the object | [https://www.britishmuseum.org/collection/object/P\_1868-0612-2323](https://www.britishmuseum.org/collection/object/P_1868-0612-2323) |
| identifier | The unique identifier provided to an object by the museum where it is housed | 18,680,612.23 |
| type | A specification of the type of object. All of the objects in this collection are specified as StillImage | Image;StillImage |
| format | The file type of the object | image/jpg |
| rights | The copyright license the object is under | CC BY-NC-SA |
| rightsstatement | A link to the rights statement defining how the object can be shared with the public | [http://creativecommons.org/licenses/by-nc-sa/4.0/](http://creativecommons.org/licenses/by-nc-sa/4.0/) |

