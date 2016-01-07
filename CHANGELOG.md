# Changelog




## 1.0.4 (07 Jan 2016)

### New
- option for faster but more inaccurate seeking.
- experimental nude detection to skip images which are considered nude
- dont overwrite existing images by default (increments filename by 1 by default)
- switch for overwriting and skipping existing images

### Changes
- log used config file and values in debug mode 
- update some of the dependencies
- use recent version of godeps to link to the saved deps

## 1.0.3 (24 Aug 2015)

### New
- option to save current settings to a settings file
- include default font and images in the binary
- added new filters
- added --to and --from options to use specific parts of the video file only
- option to provide a custom output path

## 1.0.2 (24 Aug 2015)

### New
- new filters: "fancy", "sephia" and "cross"
- option to include meta data in the header (bitrate, FPS and codecs)

### Change
- use all available cores to improve speed
 
## 1.0.1 (22 Jul 2015)

### Change
- hotfix to don't save images that are considered to black

## 1.0.0 (22 Jul 2015)

Inital release




