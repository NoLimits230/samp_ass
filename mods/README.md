# Mod Package untuk InMay RP Launcher

## Cara Upload Mod

### Skin Pack (texdb)
1. Siapkan file texdb kamu (folder berisi file-file texture SA)
2. Compress jadi **texdb.zip** (isi zip langsung file-filenya, bukan dalam subfolder)
3. Upload ke folder ini dengan nama `texdb.zip`
4. User klik "Download Skin Pack" di ingame Settings → otomatis download dan replace

### Anim Pack (anim)
1. Siapkan 3 file: `anim.ifp`, `cuts.img`, `ped.ifp`
2. Compress jadi **anim.zip** (ketiga file langsung di root zip)
3. Upload ke folder ini dengan nama `anim.zip`
4. User klik "Download Anim Pack" di ingame Settings → otomatis download dan replace

## Struktur Zip yang Benar

```
texdb.zip
├── file1.txd
├── file2.txd
└── ...

anim.zip
├── anim.ifp
├── cuts.img
└── ped.ifp
```

## Path Tujuan di Device
- texdb → `/Android/data/com.newgamersrp.game/files/texdb/`
- anim  → `/Android/data/com.newgamersrp.game/files/anim/`
