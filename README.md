# InMay RP Launcher — GitHub Assets

## Struktur Folder

```
├── config/
│   └── server.json     ← Konfigurasi IP, port, password server
└── mods/
    ├── texdb.zip       ← Skin pack (upload di sini)
    ├── anim.zip        ← Anim pack (upload di sini)
    └── README.md       ← Panduan upload mod
```

## Konfigurasi Server (config/server.json)
Edit file `config/server.json` untuk mengubah IP/port/password tanpa rebuild APK.
Launcher membaca nilai dari `ServerConfig.java` — developer bisa edit langsung di sana.

## URL yang Dipakai Launcher
```
Base URL: https://raw.githubusercontent.com/NoLimits230/sampMobilee/main/mods/
texdb.zip: https://raw.githubusercontent.com/.../mods/texdb.zip
anim.zip:  https://raw.githubusercontent.com/.../mods/anim.zip
```

## Cara Update Mod
1. Buat zip file sesuai format di `mods/README.md`
2. Upload/replace file zip di folder `mods/`
3. User buka ingame Settings → Download Mods → klik tombol yang sesuai
4. File otomatis terdownload dan di-extract ke path yang benar
