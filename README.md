# Electron Frameworks

This repository contains a collection of binary frameworks that are bundled by 
Electron. These assets are downloaded as part of Electron's 
[bootstrapping process](https://github.com/electron/electron/blob/master/script/update-external-binaries.py).

- [DirectX SDK](https://msdn.microsoft.com/en-us/library/windows/desktop/ee663275(v=vs.85).aspx)
- [MS Visual Studio C++ Runtime](https://msdn.microsoft.com/en-us/library/abx4dbyh.aspx)
- [Mantle](https://github.com/Mantle)
- [Reactive Cocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)
- [Squirrel](https://github.com/squirrel)

For the full list, see the [releases page](https://github.com/electron/electron-frameworks/releases)

## Creating a new Release

1. Download all the assets from the previous release
1. Create a new release
1. Upload the files to the new release, replacing the ones that need updating.