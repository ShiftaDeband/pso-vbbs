# pso-vbbs

A backup of the Phantasy Star Online Visual BBS image data. Images are viewable at the [ShiftaDeband VBBS](https://shiftadeband.com/vbbs/).

## About

This project is an attempt to archive all available Phantasy Star Online Visual BBS images from the [Wayback Machine](https://web.archive.org/).

While not perfect, it is an attempt to back up as many of these images as possible. At the time, this should contain all the valid images that existed at one point in the archive.

This does not mean that all images are backed up, however. Thousands of images are likely forever lost to time unless another more complete backup exists or is found.

## Attribution

An attribution JSON file, `Attribution.json`, is in the root folder for all the images for which it could be obtained. The structure of the `image` field matches the folder structure of root project, meaning that if attribution was found, the `author` field will contain the original poster's username. If no attribution was found, the field will be null.

If the author field has a value, this also means that a web.archive.org page exists for it in the archive, though it may not be the most recent version of the page.

Unfortunately, the Dreamcast Visual BBS structure is different and unreliable due to how posts were made, which means that attribution cannot be reliably determined for the images that are archived.

## Dates

Each image has information about the dates in which it was posted, which is not necessarily the date or time it was taken. This differs between versions of the game:

### Dreamcast

The Dreamcast Visual BBS date format is found in the filename of the image in question. For example: `Dreamcast/20010531045019.jpg` would be:

- Year: 2001
- Month: 05
- Day: 31
- Hour: 04
- Minute: 50
- Second: 19

### GameCube

The GameCube Visual BBS date information comes from the folder structure. For example, `Episode III/200403/143.png` would be:

- Year: 2004
- Month: 03

Further information about the exact day that it was posted could be accomplished by scraping the Visual BBS for this information, but since many of the pages are missing, it will not be possible for all posts.
