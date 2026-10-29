# WAR OF ZOMBIES

Game zombie survival open world, third person, berlatar lima provinsi Kalimantan. Unreal Engine 4.27, target Android.

## Status
Ini adalah **fondasi project**: kode C++ gameplay, konfigurasi Android, naskah cerita/cutscene, dan pipeline build APK. Kode belum pernah dikompilasi di Unreal Engine. Model 3D, animasi, map, dan cutscene visual harus dibuat di Editor (lihat `Docs/CONTENT_SETUP.md`). Belum ada APK jadi di repo ini.

## Isi
- `Source/WarOfZombies/` — pemain, zombie (Walker/Runner/Brute), kerumunan, penyintas, bandit, kejadian acak, trigger cutscene, game mode
- `Config/` — pengaturan Android (arm64, ASTC), input, packaging
- `Docs/STORY.md` — cerita 5 bab dan naskah semua cutscene
- `Docs/GDD.md` — desain game dan target performa mobile
- `Docs/CONTENT_SETUP.md` — daftar aset/Blueprint yang harus dibuat
- `Docs/BUILD_APK.md` — cara build APK (lokal dan GitHub Actions)

## Mulai cepat
1. `git lfs install`, lalu push folder ini ke repo GitHub.
2. Buka `WarOfZombies.uproject` di UE 4.27, compile C++.
3. Ikuti `Docs/CONTENT_SETUP.md`.
4. Build APK sesuai `Docs/BUILD_APK.md`.
