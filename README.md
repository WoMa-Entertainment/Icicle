# Icicle Server

Icicle is a drop-in replacement for Paper, with (some) legacy/compatibility functionality and API removed.

Critically, the Material enum is removed, and replaced with the more modern alternatives: 
ItemType and BlockType (which are already included in Paper, but are still not yet a first-class citizen)

This makes it easier to support more custom content.

There are no builds available (yet), as this is an experimental server-software, not intended for non-experimental 
hosts/users.

Builds can be compiled by cloning this repository and using

```bash
./gradlew jar
```

or

```bash
./gradlew createPaperclipJar
```

and 

```bash
./gradlew generateDevelopmentBundle
```