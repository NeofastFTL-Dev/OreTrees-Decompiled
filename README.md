# OreTrees (Rebuilt from decompiled sources)

NeoForge 1.21.1 mod recovered from published `.class` files in
https://github.com/NeofastFTL-Dev/OreTrees

## Package

Actual bytecode package is `com.nftl.oretrees` (GitHub folders used `com/neofastftl/...`).

## Requirements

- Java 21
- **At least 4 GB RAM** for the first Gradle run
- Internet (downloads NeoForge, Minecraft, mappings)

## Build

```bash
chmod +x gradlew
./gradlew build
```

Output jar: `build/libs/oretrees-1.0.0.jar`

## Run client (dev)

```bash
./gradlew runClient
```

## Notes

- Sources were decompiled with CFR 0.152
- JEI plugin is under `src/optional/jei/`
- Resources (models, loot, recipes, worldgen) should be copied from the original OreTrees repo if missing
- License remains All Rights Reserved as in the original
