---
title: 'How to Download From Youtube'
date: 2024-11-14T16:28:32+02:00
Description: 'How to Download From Youtube using yt-dlp and ffmpeg'
draft: false
Tags: ['youtube', 'download', 'yt-dlp', 'yt-dl', 'youtube']
Categories: ['tools', 'cli-tools']
DisableComments: false
thumbnail: 'images/how-to-use-yt-dlp.png'
toc: true
---

There is still some situations when you want to download video from YouTube with best quality. And so many options. Web is full of online solutions from browser extensions to standalone third-party applications. But what about quality? All this free and cheap solutions allows you to download 720p max. But what about higher resolutions? And again, web full of paid third-parties that in description can allow you to do that. But is it worth? Of course no. In this short article I will give you best free solution that helps you download video from youtube not only in FullHD, but also in 2K and 4K. Let's go.

# Preparations

We need only two things:

- YT-DLP for your operating system
- ffmpeg also for your operating system

The `yt-dlp` will download for us video and audio from youtube link with best existing video and audio. `Ffmpeg` we will need to merge separate video and audio files into one.

Yes this is the main thing. Without ffmpeg all you can is still get 720p single file included video and audio from youtube. That how youtube works. Starting from FullHD resolution there is two separate files for audio and video content. We can get them, but `yt-dlp` alone can't merge them. And here `ffmpeg` comes and help us.

And of course i recommend to create a separate folder for downloads and depending of your system put `yt-dlp` and `ffmpeg` binaries here also.

![YT-DLP](/images/how-to-use-yt-dlp.png)

## Downloading YT-DLP

You can grab YT-DLP from it's [official repository](https://github.com/yt-dlp/yt-dlp/).
Installation section in README provide quick access to binary for your OS.

![Downloading YT-DLP](/images/2024/11/yt-dlp-readme.png)

Grab binary for your system and if needed put in folder I mention before. For updating it you can call `yt-dlp -U` command and get latest version.

## Downloading ffmpeg

FFmpeg you can get from it's [official site](https://ffmpeg.org/download.html).

Again if needed put it's binaries to the created folder we mention above.

## Additional optional step

If needed modify `Path` variable to add YT-DLP and FFmpeg to it after install. So you can call `yt-dlp` from any place of your system.

# Download YouTube video with best quality

Once you finished previous steps and rady you can easily download desired video from youtube. That's pretty simple:

1. Open `Terminal` and `cd` to the folder where you want to download video.
2. Type `yt-dlp -f "bv+ba/b" <your-youtube-link>`
3. Wait till download and merge finished.
4. Enjoy.

## P.S.

YT-DLP provide way more possibilities and options in downloading from youtube. You can choose format, download whole playlists and other things. Gladly they provide good documentation about all options they have.
