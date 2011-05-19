A fork of [https://github.com/fourdman/symbolicatecrash-fix](https://github.com/fourdman/symbolicatecrash-fix)

iOS crash report symbolication is broken in XCode 4 with archived builds. Read more at [http://factotum.me/blog/2011/04/cant-symbolicate-xcode4-archive-builds/](http://factotum.me/blog/2011/04/cant-symbolicate-xcode4-archive-builds/)

Also, original symbolicate crash requires executable file in order to symbolicate crashed address from crash log. This repository contains yet another fix for symbolicatecrash that uses dSYM to resolve crashed address when there is no executable found on disk.

To fix your iOS crash report symbolication, move /usr/local/bin/symbolicatecrash aside and copy in the version in this repo.

Filed as rdar://problem/9241304