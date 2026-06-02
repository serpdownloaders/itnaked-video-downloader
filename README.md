# Itnaked Downloader (Browser Extension)

> Save media from ItNaked `/views/` relay pages with one-click detection for iframe-based m3u8 or mp4 sources when available.

Itnaked Downloader is a browser extension built specifically around the direct `/views/<id>/` route on ItNaked. Instead of claiming broad coverage across every page type, this tool focuses on the relay-page flow where an embedded iframe hands playback to a media surface. When that handoff reveals an m3u8 playlist or direct mp4 file, you can capture it with a single click.

- Focused on ItNaked `/views/<id>/` pages for targeted media detection
- Detects media surfaced through embedded iframe relay handoffs
- Supports both m3u8 playlist and direct mp4 source formats
- Fast, private, one-click download workflow
- Verified target with realistic expectations about extraction behavior

## Links

- :rocket: Get it here: [Itnaked Downloader](https://serp.ly/itnaked-downloader)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/itnaked-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/itnaked-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/itnaked-downloader/issues)

## Preview

![Itnaked Downloader workflow preview](https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/source-repo-readmes/itnaked-downloader/assets/workflow-preview.png)

## Table of Contents

- [Why Itnaked Downloader](#why-itnaked-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download Videos from Itnaked](#step-by-step-tutorial-how-to-download-videos-from-itnaked)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [Notes](#notes)
- [License](#license)
- [About Itnaked](#about-itnaked)

## Why Itnaked Downloader

Most video downloaders treat every website the same way, assuming a uniform page structure and predictable media placement. Itnaked does not follow that pattern. Its `/views/` pages use a lightweight relay approach where an embedded iframe hands playback to an external surface, and the media source only becomes visible after that handoff completes. Generic tools often miss this behavior entirely.

Itnaked Downloader was built with this specific page flow in mind. Rather than scanning the entire page for video elements, it waits for the relay to finish and then checks for the exposed m3u8 or mp4 source. This targeted approach means you get results when media is actually available, without false positives or wasted attempts on pages that do not contain downloadable content.

## Features

- Direct focus on ItNaked `/views/<id>/` pages for precise media detection
- Relay-page awareness that accounts for embedded iframe handoff behavior
- Detection of both m3u8 playlist and direct mp4 source formats
- One-click download initiation after media source is identified
- Fast scanning that respects the page loading sequence
- Private download process without unnecessary data collection
- Clean popup interface showing detected media options
- Compatible with standard browser download management

## How It Works

1. Install the extension from the latest release.
2. Open Itnaked and go to a supported `/views/<id>/` page.
3. Start playback so the extension can detect the media through the embedded relay.
4. Open the popup or use the on-page controls.
5. Choose the quality option you want.
6. Start the download and wait for the MP4 export to finish.
7. Save the final file locally.

## Step-by-Step Tutorial: How to Download Videos from Itnaked

1. Navigate to an Itnaked page that uses the `/views/<id>/` route pattern in the address bar.
2. Let the page load completely, including any embedded iframe or player handoff.
3. Start video playback so the media source becomes visible to the detection system.
4. Click the extension icon in your browser toolbar to open the downloader popup.
5. Wait while the extension scans the page for available media sources.
6. Review any detected m3u8 or mp4 options listed in the popup interface.
7. Select your preferred quality or format option if multiple choices appear.
8. Click the download button and save the resulting MP4 file to your device.

## Supported Formats

- Input: m3u8 playlists and direct mp4 sources surfaced through Itnaked relay pages
- Output: MP4

Saved files use MP4 so they are easier to replay on standard media players, move between devices, or archive locally.

## Who It's For

- People who frequently visit Itnaked `/views/` pages and want to save media locally
- Users who prefer targeted download tools over generic all-purpose extractors
- Individuals who understand the relay-page behavior and want a tool built for it
- Anyone looking for a private, one-click download experience without unnecessary complexity

## Common Use Cases

- Saving a specific video from an Itnaked view page for offline viewing
- Archiving content accessed through the `/views/<id>/` route pattern
- Collecting media that appears after the embedded iframe handoff completes
- Avoiding repetitive streaming by keeping local copies of frequently accessed content
- Building a personal library of Itnaked media without relying on third-party services

## Troubleshooting

**No media detected on the page**
Make sure you are on a valid Itnaked `/views/<id>/` page and that video playback has started. The extension needs the relay handoff to complete before it can identify the media source.

**The download does not start**
Check that your browser allows downloads from the extension. Some browsers may block automatic downloads or require permission for new download sources.

**The popup shows no options**
Refresh the page and try again. Occasionally the relay handoff may not complete on the first load, and a fresh page load can resolve this.

**The downloaded file will not play**
Ensure the file downloaded completely. Partial downloads can result from interruptions. Try downloading again with a stable internet connection.

**The extension icon is grayed out**
The extension may not be activated on the current page. Verify you are on a supported Itnaked URL and that the extension is enabled in your browser settings.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/itnaked-downloader](https://serp.ly/itnaked-downloader)

## Installation Instructions

1. Open the latest release page: [GitHub Releases](https://github.com/serpapps/itnaked-downloader/releases/latest)
2. Download the correct build for your browser.
3. Install the extension.
4. Open a supported Itnaked page.
5. Use the popup to detect and download the media.

## FAQ

**What makes this different from other video downloaders?**
This extension is built specifically around Itnaked's `/views/<id>/` page structure and embedded relay behavior. It does not make broad claims about working on every page type and focuses on the specific flow where media becomes visible through an iframe handoff.

**What formats can I download?**
The extension detects both m3u8 playlists and direct mp4 sources when they are exposed through the page relay. Output files are saved in MP4 format for broad compatibility.

**Do I need an account to use the extension?**
You can test the extension with 3 free downloads using email verification. Unlimited downloads require a paid license, but no credit card is needed for the trial.

**Why does the extension need page playback to start?**
The media source only becomes visible after the embedded relay handoff completes, which typically requires playback to begin. The extension waits for this signal before scanning for available sources.

**Is the extension safe to use?**
The extension operates with standard browser permissions and only accesses the specific Itnaked pages you visit. It does not collect unnecessary data or interact with unrelated websites.

## Notes

- Only download content you own or have explicit permission to save
- An internet connection is required for downloads
- This extension is built around Itnaked's `/views/<id>/` page pattern and may not work on other page types
- Media detection depends on the embedded relay handoff completing successfully

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## About Itnaked

Itnaked is a content platform that uses a lean page structure with embedded relay handoffs for media playback. Itnaked Downloader provides a focused tool for saving media from these specific view pages without overpromising on broader site coverage.
