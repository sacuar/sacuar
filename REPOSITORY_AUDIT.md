# GitHub repository cleanup audit — 16 November 2026

This is an **initial audit**, not a claim that every repository has been reviewed file by file. GitHub repository search returned approximately **157** repositories for `sacuar`. No repositories were permanently deleted or renamed, and no existing published EXE/release was overwritten.

## Completed improvements

| Repository | Done |
|---|---|
| [Lumen](https://github.com/sacuar/Lumen) | Replaced placeholder README, showcased existing real screenshots, added contributor guide, roadmap, issue/PR templates and Python smoke-test CI. Removed duplicate `readme.md` and misleading `gitignore`; kept `README.md` / `.gitignore`. |
| [IPTV Stream Checker](https://github.com/sacuar/IPTV_stream_checker) | Replaced outdated README, kept screenshot and original EXE, added CI and contributor guide. Removed 15 generated PyInstaller files including an identical duplicate EXE from `dist/` (**89.4 MB** of files removed from the latest checkout). Git history and old releases still retain prior objects. |
| [Quick Photo Viewer](https://github.com/sacuar/quick_photo_viewer) | Added contributor documentation, preserving the stable 2.9 viewer and all existing releases. |
| [FileOrganizer](https://github.com/sacuar/FileOrganizer) | Corrected broken external-download instructions, highlighted destructive file moves, credited original MIT copyright holder, and invited focused contributions. |
| [`.github`](https://github.com/sacuar/.github) | Replaced unrelated crack/registration-key advertising in the published `profile/README.md` with a genuine, credited software directory. Past Git history remains unchanged. |
| [GitHub user profile](https://github.com/sacuar) | Created a curated profile README with genuine Lumen/IPTV screenshot images, Quick Photo Viewer icon, verified project links, and contribution invitations. |

## Current flagship projects — keep and maintain

- [Lumen](https://github.com/sacuar/Lumen): Python/JavaScript desktop editor; tests and contribution roadmap.
- [Quick Photo Viewer](https://github.com/sacuar/quick_photo_viewer): Windows photo viewer; preserve stable baseline.
- [BANG IPTV](https://github.com/sacuar/MyIPTV): live-TV playlist player; keep previous release tags.
- [IPTV Stream Checker](https://github.com/sacuar/IPTV_stream_checker): standalone M3U checker; release preserved.

## Candidate empty or legacy repositories — owner review needed

| Repository | Verified observation | Recommended decision |
|---|---|---|
| [exoplayer-intro-master](https://github.com/sacuar/exoplayer-intro-master) | **Empty (0 KB)**, created December 2020, no stars at inspection. | Strong candidate to delete if there are no external dependencies, tags or important settings. |
| [ExoService](https://github.com/sacuar/ExoService) | **Not empty**, only ~1 KB, last pushed May 2023. | Inspect code/branches before archive or deletion. |
| [IPTVtest](https://github.com/sacuar/IPTVtest) | **Not empty**, ~17 KB, last pushed July 2023. | Review whether tests are still needed; archive if purely historical. |
| [testnodejs](https://github.com/sacuar/testnodejs) | Very small experiment (~8 KB at repository listing). | Review the contents before deciding to archive. |

**Nothing in this table has been deleted.** Size and inactivity alone cannot prove that a project is useless. Old links, branch history, tags and dependencies may matter.

## Forks and third-party attribution

These repositories are **forks**, not automatically redundant copies of your own work:

- [Pointframe](https://github.com/sacuar/Pointframe): upstream [dimitar-radenkov/Pointframe](https://github.com/dimitar-radenkov/Pointframe), a Windows screen-capture/recording tool.
- [automated_mockups](https://github.com/sacuar/automated_mockups): upstream [CTDave001/automated_mockups](https://github.com/CTDave001/automated_mockups).
- [PhotoLab](https://github.com/sacuar/PhotoLab): upstream [p-ranav/PhotoLab](https://github.com/p-ranav/PhotoLab).
- [iptv-1](https://github.com/sacuar/iptv-1), [IPTV-2](https://github.com/sacuar/IPTV-2), [iptv-links](https://github.com/sacuar/iptv-links), [iptv-cli](https://github.com/sacuar/iptv-cli): forks with other credited upstream authors.

Keep forks if they contain useful changes or are needed for existing work. Archive or remove them only after examining their divergence and dependencies; do not relabel other people's code as original.

## Name / link needing clarification

**Screen CaptureForge**: The owner confirms this application was built locally **but has not been uploaded to GitHub**. Do not create a misleading download link, claim it has been tested here, or rename the unrelated Pointframe fork. A new repository can be published after the owner supplies the existing project files (source, documentation and real screenshots).

The similarly named `sacuar/iptv` was not accessible through the current GitHub read action. Its contents were not verified and **no duplicate claim or cleanup was made**.

## How to complete the remaining cleanup safely

1. Confirm old repos have no useful unique branches, tags, releases, issues, dependencies or external links.
2. Archive uncertain projects before permanently deleting them. Archiving is reversible.
3. Download backup archives before deleting confirmed empty/obsolete projects.
4. Use the repository's GitHub **Settings → General → Danger Zone** for archive, rename or deletion. The connected GitHub actions here do **not** expose repository delete/rename/archive controls.
5. Keep old EXE release tags while migrating documentation to an actively maintained flagship project.
6. Review contributor and copyright/licence terms before advertising a project as open source.

## Repeatable upkeep

- GitHub Actions now checks Lumen's editor metadata and basic syntax; M3U Stream Checker has source syntax CI.
- Review open issues and failed builds before publishing versions.
- Do not infer stream availability, software safety, or screenshot authenticity from GitHub badge colours.

This audit is a living checklist; it does **not** schedule automatic repository modifications.
