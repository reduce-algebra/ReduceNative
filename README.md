# ReduceNative

A native (well, not quite) code based REDUCE CAS port to Android

## Implementation details

This project uses Katex to render REDUCE output, so it can be quite slow.  
REDUCE binary itself is built with a proprietary toolchain. It is static, so it may cause problems with future Android versions, if you want to continue this project, you'd better go with NDK.

## Further development

I will be happy if you fork this project so my work will not get lost, but I will not provide any support for this project.

The reason is the ongoing hostility of Android [towards native applications](https://github.com/termux/termux-app/issues/1072) and [their access to files](https://www.xda-developers.com/android-q-storage-access-framework-scoped-storage/), so I found this platform not worthwile anymore.
