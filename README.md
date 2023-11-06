# SF2000 FixHebrew

This repository provides a fix for Hebrew translation issues with the Datafrog SF2000 gaming console. The fix addresses the problem of reversed strings due to the lack of Right-to-Left (RTL) language support on the device.

## Preview
[preview video](https://youtu.be/ywXL_uPuQjU)

## Usage

To apply the fix: 
1. Navigate to the [releases page](https://github.com/amir16yp/sf2000-fixhebrew/releases/latest)  and download the latest version of the fix in a zip format. 
2. Unzip the downloaded file and locate the `Resources` folder within it. 
3. Copy the `Resources` folder to the root directory of your SF2000 SD card, replacing any existing files when prompted.
## How It Works

The fix includes corrected versions of the following files which originally contained Hebrew strings displayed in reverse order:
### `xjebd.clq` 
- This file is found in the `Resources` folder on the SD card and contains Hebrew translation strings.
- As the SF2000 console does not support RTL text rendering, the strings were originally displayed backwards. The fix reverses the text in the file so that it appears correctly when the console mistakenly renders it in reverse.
### `vidca.bvs`
- This file provides the User settings screen with icons and labels in Hebrew, represented in an image format.
- The Hebrew strings within this file were corrected using Paint.net to display properly on the device.
### `exaxz.hsp`
- Contains the labels for the main menu options "Games Exist" and "Start: Open" across all supported languages, including Hebrew.
- The original file had the Hebrew strings in reverse order, which was corrected by editing the image files to ensure the text is readable on the console.
