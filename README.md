# CMC Website Presentation Page

This HTML file creates a webpage designed to showcase presentation videos, an audio file, a YouTube video, and a downloadable PDF document. The page includes side-by-side videos, an audio section, an embedded YouTube video, and a section to view or download a PDF.

## Table of Contents
- [Page Structure](#page-structure)
- [Features](#features)
- [Usage](#usage)
- [Customization](#customization)

## Page Structure
The page is structured as follows:
1. **Title and Favicon**: The page title is set to "CMC", and a favicon is added.
2. **Header Section**: Contains an introductory header for the video presentation.
3. **Side-by-Side Videos**: Displays two videos side-by-side, each with separate sources (`mp4` and `webm`).
4. **Audio Section**: Embeds an audio file with support for `mp3` and `ogg` formats.
5. **Embedded YouTube Video**: Displays a YouTube video within an `iframe`.
6. **PDF Document and Download Link**: Provides an inline view of a PDF document and a link for downloading it.

## Features
- **Responsive Videos**: Each video scales to a maximum width of 520px, with rounded corners.
- **Audio Player**: Allows playback of an audio file with a control bar.
- **Embedded YouTube Video**: Integrates an external YouTube video within the page.
- **PDF Viewer and Download Link**: Displays a PDF in an embedded `iframe` and provides an option to download it.

## Usage
To view the page:
1. Open `index.html` in a web browser.
2. Ensure the `video`, `audio`, and `pdf` folders contain the required media files as specified in the `src` attributes.

## Customization
- **Change Video, Audio, or PDF Source**: Replace file paths in the `<source>` or `src` attributes.
- **Adjust Styles**: Modify inline styles (e.g., `max-width`, `border-radius`) or add a custom CSS file.
- **Replace Favicon**: Update the `href` in the `<link>` tag to use a different favicon image.

## Requirements
- Ensure the following folders/files are available:
  - `video/cmc video.mp4`, `video/cmc video.webm`, `video/cmc2.mp4`, `video/cmc2.webm`
  - `audio/cmc audio.mp3`, `audio/cmc audio.ogg`
  - `pdf/cmc digital&AI.pdf`
- An internet connection is needed to view the embedded YouTube video.

## Notes
- The HTML file uses French for certain headings and can be easily translated or modified.
- Autoplay is enabled for videos and muted to avoid unwanted sound on page load.

