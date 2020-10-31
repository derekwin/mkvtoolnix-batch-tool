# MKVToolNix Batch Tool
> Batch video and subtitle processing program to help you add (merge) or remove subtitles from your video library. Allows you to process all of a folder's subdirectories in a single batch.
<br><br>

<p align="center">
  <img src="https://user-images.githubusercontent.com/8584126/97788727-3ab68e00-1b78-11eb-8c71-ac4c9f63e0c1.gif" />
</p>
<br>

## 💾 Downloads
MKVToolNix Batch Tool works on Windows 32-bit (x86) and Windows 64-bit (x64) operating systems, see the project's [releases&nbsp;page](https://github.com/iPzard/mkvtoolnix-batch-tool/releases) for download links.
<br><br>

## 🔨 Merging subtitles
When merging subtitles, each subdirectory ***must*** contain one video file and at least one subtitle file, otherwise the directory will be skipped. Other non-video, non-subtitle files, may be included and will be ignored.<br><br>

The language of each subtitle file is determined automatically by parsing through text in the files, the language that matches your <b>Default Language Track</b> from the settings page (defaults to English) will be set as the default subtitle track on your videos.<br><br>

**Directory example:**
<pre>
  <code>
    📂Movies
    ┣ 📂Resident Evil (2002) 👈 <b>only one video, and one subtitle file per sub directory</b>
    ┃ ┣ 📺Resident Evil (2002) [1080p].mp4
    ┃ ┗ 📜Resident Evil (2002) [1080p] English.srt
    ┃ ┗ 📜Resident Evil (2002) [1080p] Spanish.srt
    ┃ ┗ 📜Resident Evil (2002) [1080p] French.srt
    ┣ 📂Resident Evil Afterlife (2010)
    ┃ ┣ 📺Resident Evil Afterlife (2010) [1080p].avi
    ┃ ┣ 📜Resident Evil Afterlife (2010) [1080p].ass
    ┃ ┗ 🎨Movie poster.png 👈 <b>extra non-video, non-subtitle files may exist</b>
    ┣ 📂Resident Evil Apocalypse (2004)
    ┃ ┣ 📺Resident Evil Apocalypse (2004) [1080p].mkv
    ┃ ┗ 📜Resident Evil Apocalypse (2004) [1080p].pgs 👈 <b>language is determined automatically</b>
    ┃ ┗ 📜Resident Evil Apocalypse (2004) [1080p] German.pgs
    ┣ 📂Resident Evil Extinction (2007)
    ┃ ┣ 📺Resident Evil Apocalypse (2004) [1080p].wmv
    ┃ ┗ 📜Resident Evil Apocalypse (2004) [1080p].ssa
    ┣ 📂Resident Evil Retribution (2012)
    ┃ ┣ 📺Resident Evil Retribution (2012) [1080p].ogg
    ┃ ┗ 📜Resident Evil Retribution (2012) [1080p] English.sup
    ┃ ┗ 📜Resident Evil Retribution (2012) [1080p] Italian.sup
    ┃ ┗ 📜Resident Evil Retribution (2012) [1080p] Japanese.sup
    ┃ ┗ 📜Resident Evil Retribution (2012) [1080p] Russian.sup
    ┣ 📂Resident Evil The Final Chapter (2016)
    ┃ ┣ 📺Resident Evil The Final Chapter (2016) [1080p].ogm
    ┃ ┗ 📜Resident Evil The Final Chapter (2016) [1080p] Dutch.srt
    ┃ ┗ 📜Resident Evil The Final Chapter (2016) [1080p] Swedish.srt
    ┃ ┗ 📜Resident Evil The Final Chapter (2016) [1080p] Portuguese.srt
  </code>
</pre>
<br>

## 🪓 Removing subtitles
When removing subtitles, each subdirectory ***must*** contain one video file, otherwise the directory will be skipped. Other non-video, may be included and will be ignored.<br><br>

**Directory example:**
<pre>
  <code>
    📂Movies
    ┣ 📂Resident Evil (2002) 👈 <b>only one video file per sub directory</b>
    ┃ ┗ 📺Resident Evil (2002) [1080p].mp4
    ┣ 📂Resident Evil Afterlife (2010)
    ┃ ┣ 📺Resident Evil Afterlife (2010) [1080p].avi
    ┃ ┗ 🎨Movie poster.png 👈 <b>extra non-video files may exist</b>
    ┣ 📂Resident Evil Apocalypse (2004)
    ┃ ┣ 📺Resident Evil Apocalypse (2004) [1080p].mkv
    ┃ ┗ 📜Resident Evil Apocalypse (2004) [1080p].srt 👈 <b>extra non-video files may exist</b>
    ┣ 📂Resident Evil Extinction (2007)
    ┃ ┗ 📺Resident Evil Apocalypse (2004) [1080p].wmv
    ┣ 📂Resident Evil Retribution (2012)
    ┃ ┗ 📺Resident Evil Retribution (2012) [1080p].ogg
    ┣ 📂Resident Evil The Final Chapter (2016)
    ┃ ┗ 📺Resident Evil The Final Chapter (2016) [1080p].ogm
  </code>
</pre>
<br>

## 🗃️ Supported files
The following file types are supported.

**Video**:
* *AVI*, *M4V*, *MKV*, *MOV*, *MP4*, *MPG*, *MPEG*, *OGG*, *OGM*, *WEBM*, *WMV*

**Subtitle**:
* *ASS*, *PGS*, *SRT*, *SSA*, *SUP*
<br>

## 🦟 Software bugs
Bugs reported on the project's [issues page](https://github.com/iPzard/mkvtoolnix-batch-tool/issues) will be exterminated as quickly as possible.
<br><br><br>

## 🙏 Attribution
* MKV batch processing is powered by [MKVToolNix](https://gitlab.com/mbunkus/mkvtoolnix)
* SVG icons used are from [Font Awesome](https://fontawesome.com)
<br>

## 🏷️ License
GPLv2 © [iPzard](https://github.com/iPzard/mkvtoolnix-batch-tool/blob/master/LICENSE)