# How To Install


Add to your project manifiest by path [%UnityProject%]/Packages/manifiest.json new Scope:

```json
{
  "dependencies": {
    "com.littlebigfun.addressable-importer": "https://github.com/favoyang/unity-addressable-importer.git",
    "com.unigame.unicore": "https://github.com/UnioGame/unigame.core.git",
    "com.unigame.localization": "https://github.com/UnioGame/unigame.localization.git",
    "com.unigame.rx": "https://github.com/UnioGame/unigame.rx.git",
    "com.cysharp.unitask" : "https://github.com/Cysharp/UniTask.git?path=src/UniTask/Assets/Plugins/UniTask",
    "com.unigame.unibuildpipeline" : "https://github.com/UnioGame/unigame.buildpipeline.git"
  }
}
```

# UniBuild.Commands
Additional Commands for commnads based build pipeline for Unity

Contents:

- Addressables Commands
- Distribution Commands
- WebRequest Commands
- FTP Commands

To enable FTP support install

```
    "com.unigame.fluentftp": "https://github.com/UnioGame/FuentFTP.git",
```

- AddressablesImporter Commands
- Android Commands



# Android Commands

# Addressable Importer Support

Original Package: https://github.com/favoyang/unity-addressable-importer

**AddressableImporterRefreshAssets** - Allow you to refresh addressable by defined rules

## Android Debug Symbols Rezip 

Rezip your debug symbols into smaller one with only selected android architectures

- Fix This issue
https://forum.unity.com/threads/making-android-symbols-package-smaller.1109600/

![](https://github.com/UniGameTeam/UniBuild.Commands/blob/master/Editor/GitAssets/rezip_command.png)
