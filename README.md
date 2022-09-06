# Audio Tools Library (ATL) for Java

Fully managed, portable and easy-to-use Java library to read and edit audio data and metadata (tags) from various audio formats, playlists and CUE sheets.


## Current status

[![Build status](https://ci.appveyor.com/api/projects/status/s4y0e3g6fxncdhi6/branch/master?svg=true)](https://ci.appveyor.com/project/weisenzcharles/alt/branch/master) [![codecov](https://codecov.io/gh/weisenzcharles/alt/branch/master/graph/badge.svg)](https://codecov.io/gh/weisenzcharles/alt) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=weisenzcharles_alt&metric=alert_status)](https://sonarcloud.io/dashboard?id=weisenzcharles_alt)

## What is ATL Java ?

This library is aimed at giving Java developers a managed, portable and easy-to-use library to **read and write metadata from digital audio files and playlists** with one single unified API, whatever the underlying format.

```java
import org.mediabrowser.alt;

Track theTrack = new Track(audioFilePath);

theTrack.Save();
```

You'll find more working code on the [Code snippets section of the Documentation](https://github.com/weisenzcharles/alt/wiki), including what you need to manage embedded pictures (e.g. cover), chapters , lyrics and playlists
