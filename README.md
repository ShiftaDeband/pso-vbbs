# pso-vbbs

A backup of the Phantasy Star Online Visual BBS image data. Images are viewable at the [ShiftaDeband VBBS](https://shiftadeband.com/vbbs/).

## About

This project is an attempt to archive all available Phantasy Star Online Visual BBS images from the [Wayback Machine](https://web.archive.org/).

While not perfect, it attempts to preserve as many of these images as possible. This currently includes all valid images that once existed in the archive.

However, not all images that were posted to the VBBS are included in this project. Thousands of images may be lost forever unless a more complete backup exists or is discovered.

## Attribution

The attribution JSON file, `Attribution.json`, is in the root folder and includes details for images where attribution was available. The `image` field matches the root project folder structure. If attribution was found, the `author` field contains the original poster's username; otherwise, the field is `null`.

If the `author` field has a value, a [Wayback Machine](https://web.archive.org/) archive of the page exists, though it may not be the most recent version.

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

Further information about the exact day that it was posted could be accomplished by scraping the Visual BBS for this information, but since many of the pages are missing, it would not be possible for all posts.
