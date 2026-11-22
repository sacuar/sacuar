# SACUAR Tools — launch kit

## Positioning

**Portfolio promise:** Practical Windows desktop tools for everyday tasks. No unnecessary complexity.

**Focus:** Demonstrate one real workflow at a time, describe limitations transparently, invite genuine testing and improvement.

**Official destination:** https://github.com/sacuar

## Ready-to-post launch messages

### Portfolio introduction (GitHub Discussions, social)
Four desktop projects, one focus: fewer distractions during everyday computer work.

- **Quick Photo Viewer:** local photo browsing, keyboard navigation and fullscreen viewing.
- **Folder:** tabbed file management with previews and a customisable workspace.
- **CaptureForge:** screen capture, annotation and local OCR.
- **Lumen:** lightweight keyboard-first text and code editing.

Each project has source, Windows release assets and clear development notes. I'd particularly value feedback on installer reliability, keyboard usability and performance. Explore: https://github.com/sacuar

### Quick Photo Viewer (targeted launch)
I made Quick Photo Viewer for people who want to browse local images without opening a full editing suite. It includes folder navigation, thumbnails, fullscreen and keyboard shortcuts. Version 2.9.6 introduces a consent-based verified installer-updater; I am testing upgrades from 2.9.5. If you use Windows 10/11, I'd welcome feedback on launch speed, large folders and installation. https://github.com/sacuar/quick_photo_viewer

### Folder (targeted launch)
I'm developing Folder, a tabbed Windows file manager that prioritises previews and a configurable workspace. It provides image, PDF and selected document previews, an add-on manager and practical file tools. I'd value feedback on navigation and the features that make everyday file work faster. Current Windows releases: https://github.com/sacuar/folder/releases

### CaptureForge (developer/tester outreach)
CaptureForge is a native C++/Qt Windows project for screen capture, annotations and local OCR. A Windows CI installer and smoke-test pipeline is in place; interactive usability feedback and extra OCR samples are still welcome. https://github.com/sacuar/captureforge

### Lumen (developer/tester outreach)
Lumen is an early-stage keyboard-first editor for text and code with tabs, project navigation and search. It does not claim full Sublime Text plugin compatibility. Feedback on editing latency, file handling and plugin API limitations is especially useful. Source licensing remains unresolved, so please check LICENSING.md before considering code reuse. https://github.com/sacuar/Lumen

## Honest 21-second video storyboard

The short downloadable motion-graphics teaser uses these six scenes (3.5 seconds each):
1. SACUAR Tools — Four tools. More control.
2. Quick Photo Viewer — Local images, zoom, fullscreen.
3. Folder — Tabs, previews and custom workspace.
4. CaptureForge — Capture, annotate and recognise.
5. Lumen — Tabs, search and keyboard-first editing.
6. github.com/sacuar — Explore the projects.

**Do not label the teaser a product demonstration.** Replace scenes with validated recordings from the actual released applications when available, with version labels.

## Useful screenshots for future demos

- Quick Photo Viewer: https://github.com/sacuar/quick_photo_viewer/releases/latest/download/workspace.png
- Folder workspace: https://github.com/sacuar/folder/releases/latest/download/workspace.png
- Folder add-ons: https://github.com/sacuar/folder/releases/latest/download/addons.png
- Lumen editor: https://github.com/sacuar/Lumen/blob/main/docs/screenshots/Capture1.png

Only use source screenshots for a given app. If a link is missing or a capture is unrepresentative, record a fresh screenshot from a tested build.

## GitHub settings work still required

The current connector cannot edit repository topics, descriptions, pinned repositories, Pages settings or social preview upload settings. Before announcing a public website, enable Pages for `sacuar/sacuar` from main `/docs` and confirm the deployed URL. Use each application's `assets/social-preview.svg` as visual source; GitHub Settings may require a PNG or JPEG conversion for social previews.

## Publish order

1. Confirm a functioning Windows installer and manual upgrade for Quick Photo Viewer.
2. Verify screenshots and update metadata.
3. Share the first release to a small targeted audience and fix reported issues.
4. Repeat with Folder; position CaptureForge and Lumen as tester previews.
5. Track real downloads and substantive issue reports; avoid star-buying, spam or inflated adoption claims.
