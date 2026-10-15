# BeefBonus Fabric (Minecraft Java 1.21.1)

BeefBonus memberi hadiah acak saat pemain memakan Cooked Beef. Hadiah dibagi menjadi empat tingkat kemungkinan: umum, tidak umum, langka, dan sangat langka.

## Build

Persyaratan: JDK 21 dan koneksi internet untuk mengunduh dependensi Gradle/Fabric.

Di folder proyek, jalankan:

```bash
gradle build
```

JAR hasil build berada di `build/libs/beefbonus-1.0.0.jar`.

## Instalasi

Pasang Fabric Loader untuk Minecraft Java 1.21.1, lalu salin JAR hasil build ke folder `mods`. Mod ini tidak ditujukan untuk Minecraft Bedrock. Launcher seperti PojavLauncher atau Zalith dapat menjalankannya jika profilnya menggunakan Minecraft Java 1.21.1 + Fabric dan Java 21.

## Catatan

Ini adalah proyek sumber, belum berupa JAR yang sudah dikompilasi atau diuji dalam game. Build memerlukan Gradle dan akses internet untuk mengunduh Minecraft/Fabric dependencies.
