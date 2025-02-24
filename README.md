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

## Disclaimers

As the original websites are no longer online, the following disclaimers are provided:

This project is not associated with SEGA or SONIC TEAM in any way, shape or form. This is a fan-run repository trying to archive a little bit of history from the early 2000s. Images are copyright of SONICTEAM/SEGA as noted in each screenshot. The [original Terms of Use can be found on an archived page from the original VBBS](https://web.archive.org/web/20040619000922if_/http://www.sonicteam.com/pso/minhiro2/nb.html).

This archive is intended solely for non-commercial, educational, and personal use. No part of this content should be used for commercial purposes without the proper rights and permissions from the respective copyright holders.

All archived material is provided "as-is" without any warranties—express or implied. The maintainers of this repository are not liable for any errors or omissions, or for any consequences arising from the use of the content.

Some materials featured here may be included under the doctrine of fair use for purposes such as commentary, criticism, research, or historical preservation. This inclusion is not intended to infringe upon the rights of the original copyright holders.

All trademarks, logos, and service marks belong to their respective owners.

Thank you to all who originally contributed to the VBBS all those years ago.
