---
layout: post
title: "Folder: a file manager that plays video in its preview pane"
description: "Folder combines tabs, file previews and an integrated LibVLC video player on Windows, with an Ubuntu preview build."
category: "File managers"
permalink: /blog/folder-video-preview/
---
A frequent part of organising footage is opening a file just to find out what's inside. **[Folder](https://github.com/sacuar/folder)** is an independent file manager for Windows with a built-in video preview that keeps your directory visible while you check clips.

## Play, pause and seek without opening another player

Select a supported movie in Folder and use its preview pane. The LibVLC-backed player provides **play/pause, timeline scrubbing, volume, mute and playback-time controls** beside the file list. Windows builds bundle LibVLC; Ubuntu builds depend on a system LibVLC installation and may behave differently under Wayland.

![Actual running Folder workspace with file preview](https://github.com/sacuar/folder/releases/download/v0.7.9/workspace.png)

*Real application screenshot from an automated Windows build using sample files. This is not a recording of video currently playing.*

## Beyond video

Folder includes tabs, configurable toolbars, thumbnail and document previews, archive tools, an add-on manager and local-file operations. It does not automatically replace Windows Explorer, and changing your default file manager is not required.

Version **0.7.9** is available in the [official GitHub Releases](https://github.com/sacuar/folder/releases), with Windows and Ubuntu 24.04 x64 packages. The Ubuntu edition uses directory-based search in place of the Windows Everything integration.

**Try it:** [Download Folder](https://github.com/sacuar/folder/releases) · [See code and screenshots](https://github.com/sacuar/folder) · [Report feedback](https://github.com/sacuar/folder/issues).

If you work with video-heavy folders, feedback on preview codecs, large directories and keyboard navigation is particularly helpful.
