# Public launch and discoverability checklist

This document separates **verified repository content** from **launch tasks that require a real Windows build or a manual GitHub settings change**. It is not evidence that binaries were tested.

## Priority A — trust and working downloads
- [ ] Run each Windows installer in a clean Windows 10/11 environment; record installer filename, architecture, checksum, launch test and uninstall result.
- [ ] For Quick Photo Viewer, test the full update path starting with an existing 2.9.x installation and confirm displayed version matches the current release.
- [ ] For Folder, test file opening, preview, tabs, keyboard controls and ordinary non-admin use.
- [ ] For CaptureForge, run the native Qt build and OCR smoke test before promoting a stable installer.
- [ ] For Lumen, test opening/saving projects and clarify the intended licence before seeking source contributors.
- [ ] Publish release notes and known limitations alongside every binary. Avoid claims of cross-platform availability without platform tests.

## Priority B — public presentation
- [x] Create a consistent promotional banner for each of the four featured desktop applications.
- [x] Give each project a concise value proposition, release navigation and transparent development status.
- [x] Present all four projects on the GitHub profile homepage.
- [ ] Add a short, real **screen recording** to each project. Never represent an illustration as an application screenshot.
- [ ] Verify the release screenshots load when logged out; replace broken links with committed real screenshots if needed.
- [ ] Add branded social preview images through each repository's GitHub settings.
- [ ] Pin the four desktop applications on the GitHub profile.

## Priority C — discoverability
Repository descriptions to enter in GitHub Settings (manual metadata change; not yet applied):

| Repository | Suggested description | Suggested topics |
|---|---|---|
| `quick_photo_viewer` | Fast, distraction-free Windows photo viewer with local browsing, zoom and fullscreen. | `photo-viewer`, `image-viewer`, `windows`, `pyside6`, `desktop-app` |
| `folder` | Customisable Windows file manager with tabs, previews and useful file tools. | `file-manager`, `windows`, `file-explorer`, `pyside6`, `desktop-app` |
| `captureforge` | Native Windows screenshot, annotation and local OCR workspace built with Qt. | `screenshot`, `ocr`, `qt6`, `windows`, `screen-capture` |
| `Lumen` | Lightweight, keyboard-first editor for local text and code projects. | `text-editor`, `code-editor`, `python`, `webview`, `desktop-app` |

Choose only topics that reflect implemented features; avoid spammy tags.

## Suggested outreach sequence
1. **Technical user test:** Post a short, reproducible demo and ask for feedback on the current Windows build.
2. **Release post:** Once installation is tested, publish a 30-second tour and direct download link.
3. **Community discovery:** Share the specific problem solved in appropriate project communities, respecting each community's self-promotion policy.
4. **Follow-up:** Publish a small changelog demonstrating that user feedback produced fixes.

## Useful measures
Record weekly repository views, GitHub release downloads, unique installer issue reports and external referrals. Stars are useful but not equivalent to retained active users. Do not buy stars or manufacture testimonials.

## Legal and security
Folder has an MIT licence. Quick Photo Viewer, CaptureForge and Lumen currently have missing or unresolved source distribution permissions: obtain a deliberate maintainer licensing decision, with dependency review, before labelling them 'open source' or inviting unrestricted code reuse. Windows binaries may be unsigned: release pages must state this plainly.
