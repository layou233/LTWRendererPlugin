# LTW Renderer Plugin

Mainly borrowed from a previous *illegal* plugin of the same functionality, but this time it is legal.

No more toxic, just pick what you like.

Tested and works on FCL.

## Differences from the old one:

1. Based on OpenLTW, compiled from source.
2. 0 line of plugin code, only provides libraries, no Kotlin runtime, etc.
3. ABI split. Download only the ABI you want. Universal APK is also provided.

## Build

Pre-built APKs are provided in Release. In case you want to build it by yourself, just type:

```shell
./gradlew :app:assembleRelease
```

If you get `make (e=206)` error on Windows, try adding this to art/ltw/src/main/tinywrapper/Application.mk:

```
APP_SHORT_COMMANDS := true
```

## Credit

- artDev & [LTW](https://github.com/artdeell/LTW): The upstream repo.
- [FCLRendererPlugin](https://github.com/FCL-Team/FCLRendererPlugin): R.I.P
- The launcher community

I personally wish artDev all the best in his future work and life. Your past work and contributions are invaluable to the community.
