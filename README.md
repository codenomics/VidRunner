# VidRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.7** (Oct 8, 2026)

- [VidRunner_v1.7_no-install.zip](https://github.com/codenomics/VidRunner/releases/download/v1.7/VidRunner_v1.7_no-install.zip) - 37 MB
- [VidRunner_v1.7_Setup.exe](https://github.com/codenomics/VidRunner/releases/download/v1.7/VidRunner_v1.7_Setup.exe) - 37 MB
- [VidRunner_v1.7_source.zip](https://github.com/codenomics/VidRunner/releases/download/v1.7/VidRunner_v1.7_source.zip) - 106 KB

What's new in v1.7:

- updater versioning fix**

Older versions are on the [Releases page](https://github.com/codenomics/VidRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find VidRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## Source code

Want to see how it works, or build it yourself? Download the file ending in `_source.zip` above, extract it and double-click `Build.bat`. It only uses the C# compiler that already comes with Windows, so there is nothing to install.

## More details

```
VIDRUNNER
=========

Makes lyric videos. Open a song, paste the words, tap along to the song to
time each line, pick a picture, and save an MP4 you can upload anywhere.


GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > VidRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the VidRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click VidRunner.exe. Nothing is installed; to remove it, delete
  the folder.

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.

The first time you make a video, VidRunner offers to download FFmpeg, a
free helper program that makes video files. Click "Get it for me". It is
saved once and used from then on.


USING IT
--------
1. Open song... (or drag the song into the window).
2. Paste lyrics..., one line of the song per line.
3. Tap-sync, then press ENTER the moment each line starts.
   Space pauses / plays, Backspace undoes the last tap, Esc finishes. "Tap delay fix" moves every
   tap a little earlier to make up for reaction time.
4. Click a line to fix its time (Set to now, or -0.1 s / +0.1 s; Remove
   timing clears it). Double-click a line to jump the song to it, and
   right-click a line for more (Edit words, Merge, Delete).
5. Pick a picture, size, text size (in pixels), color and position. Drag the
   words in the preview to place them. The preview is exactly what the
   video will show.
6. Text tab: pick a font (each is shown in its own style; click the star to
   keep favorites at the top), then outline, shadow and glow. Any color box
   has Custom... for a color picker.
7. Animation tab: choose how a line comes in and goes out (Slide, Zoom,
   Typewriter, Glitch, Decode, Hologram, Light sweep and more), a
   separate direction for in and out, and speed and strength. Press Play to watch it. Save look...
   and Load look... keep your text and animation settings as a template.
8. Test clip (10 s) checks a short piece fast. Export video... makes the
   whole video (MP4, 30 frames per second).

Save project keeps your work. Import .lrc / Save .lrc read and write lyrics
with times. F1 opens the guide, which shows the version number and has a
Check for updates button.


GOOD TO KNOW
------------
- Without FFmpeg VidRunner can still play .mp3 and .wav songs and tap-sync
  them, but it cannot show the wave picture or make videos.
- Settings are kept in %APPDATA%\VidRunner\settings.txt.
- Updates: when VidRunner starts it checks GitHub for a newer version (it only
  reads the public release page; nothing is sent). If there is one and you
  aren't in the middle of editing, it asks whether to update; otherwise a note
  appears in the status bar. With the installer, Update now offers to save your
  project, downloads the new installer (about 40 MB, FFmpeg is included) and
  runs it; with the no-install zip it opens the download page. After "Check
  for updates" says you're up to date, a button there turns the startup check
  off.
- If something goes wrong, VidRunner-log.txt next to VidRunner.exe says what.
- To remove VidRunner: delete its folder, plus %APPDATA%\VidRunner.
```

