## synk

synk is a command line tool for uploading Minecraft mods to distribution platforms, currently CurseForge, Modrinth and GitHub Releases. 

### Installation

synk is written in Dart, meaning you require the Dart SDK to build it. You can either install that or 
download one of the precompiled scatter binaries from the [Actions](https://github.com/gliscowo/synk/actions) section

To compile scatter, execute the following commands from the root of this repository

```shell
dart pub get
dart compile exe bin/synk.dart
```

Then take the generated `synk.exe` file and move it somewhere convenient. After that you can run it to get started
