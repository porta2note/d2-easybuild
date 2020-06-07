Descent 2 "Easybuild"

This project is an attempt to make an as-close-to-reference-as-possible source package for Descent 2, buildable with easily available tools, from the original source release.

The goal of this project is getting a source package that builds DOS executables under a DOS build environment. To that end, this repo will stick to 8.3, non-case-sensitive filenames and CR-LF line endings. (Descent 2 source also specifies a "Win" target for Windows 9x - if enough code is left in there to make this functional, we'll add that too.)

The original source release removed code for sound, networking, and serial as they were under 3rd-party copyright and not distributable by Parallax Software. This project will NOT attempt to replace that code or introduce any changes or bugfixes. That will be the job of future forks.

This source bundle does NOT include the INIT subdirectory in the first level, which contained stuff specific to OpusMake, which is NLA. If we need those, we'll add them back in. 

Note: this code is distributed under the PARALLAX SOURCE CODE LICENSE, which can be found in ORIGREAD.TXT. Additions to the source package by contributors to this repo will be put into the PUBLIC DOMAIN where necessary.