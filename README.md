A fork of [https://github.com/chrispix/symbolicatecrash-fix] 

iOS crash report symbolication is broken in XCode 4 with archived builds. Read more at [http://factotum.me/blog/2011/04/cant-symbolicate-xcode4-archive-builds/](http://factotum.me/blog/2011/04/cant-symbolicate-xcode4-archive-builds/)

To fix your iOS crash report symbolication, move /usr/local/bin/symbolicatecrash aside and copy in the version in this repo.

Filed as rdar://problem/9241304