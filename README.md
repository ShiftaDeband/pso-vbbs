# pso-vbbs
A backup of the Phantasy Star Online Visual BBS image data. Used by the [Random PSO Visual BBS Image](https://shiftadeband.com/vbbs/) generator.

## About
This project was an attempt to archive all of the possible Visual BBS images from the web.archive.org service. 

While not perfect, it is an attempt to back up as many of these files as possible. At the time, this should contain all of the valid images that existed at one point in the archive. 

This does not mean that all images are backed up, however. Thousands of images are likely forever lost to time unless another more complete backup exists and/or is found.

## Attribution
There's an attribution folder for all of the images for which it could be obtained. The structure of the folders matches the folder structure of root project, meaning that if attribution was found, it should have information about the original poster's username. This also means that a web.archive.org page exists for it in the archive, though it may not be the most recent version of the post.

Unfortunately, the Dreamcast Visual BBS structure is different and unreliable due to how posts were made, which means that attribution cannot be reliably determined for most of the images that are archived.

## Dates
Each image has information about the dates in which it was posted, which is not necessarily the date or time it was taken. This differs between versions of the game:

### Dreamcast
The Dreamcast Visual BBS date format is found in the filename of the image in quesion. For example: `Dreamcast/20010531045019.jpg` would be:

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
