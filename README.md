# Rekap Skill — 19 November 2026

Total: **65 skill** terpasang di `~/workspace/custom-skills/`, plus 1 katalog referensi.
Semua sudah bisa dipanggil. Yang bertanda **referensi saja** belum terhubung dan jangan dihubungkan tanpa keputusan Boss.

---

## 1. Pipeline & Video YouTube (16 skill)

| Skill | Sumber | Fungsi singkat |
|---|---|---|
| penjelasan-dan-cerita | sobis-youtube-skills | Naskah penjelasan & cerita, anti-slop, gerbang kualitas naskah |
| video-suara-bawaan | sobis-youtube-skills | Mesin utama generate video + dialog asli bahasa Indonesia |
| kemasan-video | sobis-youtube-skills | Packaging: judul, caption, diagram, tema Hallmark |
| muse-video-prompt-skill | masonmosen/muse-video-prompt-skill | Template prompt 6 bagian + sambung klip + cek frame |
| muse-animated-short-film | sonlovinbot-team/Muse-animated-short-film | Film pendek animasi 8 tahap, character sheet + keyframe |
| muse-video | LuoJiangYong/muse-video-skill | Pre-produksi sinematik: ide, naskah, storyboard, prompt |
| muse-video-prompt | dichenxiang/muse-video-prompt | Wawancara sutradara + aturan sambung frame terakhir |
| muse-video-useapi | useapi/muse-api | API pihak ketiga untuk gambar & video Muse — **referensi saja, belum terhubung** |
| h3-prompt-writing | MiniMax-AI/MiniMax-H3 | Penulis prompt video H3 (T2VA/I2VA/FL2VA/Ref2VA) — satu-satunya skill H3 yang portable |
| music-video-subtitle-generator | MiniMax-AI/MiniMax-H3 | MV + lirik tersinkron, protokol sambung antar-shot — **Hub-only** |
| 3d-animation-short-generator | MiniMax-AI/MiniMax-H3 | Short animasi 3D — **Hub-only** |
| minimalist-product-ad-generator | MiniMax-AI/MiniMax-H3 | Iklan produk minimalis — **Hub-only** |
| brand-promo-video-generator | MiniMax-AI/MiniMax-H3 | Promo brand/produk — **Hub-only** |
| papercraft-stop-motion-explainer | MiniMax-AI/MiniMax-H3 | Explainer papercraft stop-motion — **Hub-only** |
| paper-collage-explainer-generator | MiniMax-AI/MiniMax-H3 | Explainer kolase kertas — **Hub-only** |
| co-op-game-intro-generator | MiniMax-AI/MiniMax-H3 | Intro game co-op 2 pemain — **Hub-only** |
| handdrawn-live-video-generator | MiniMax-AI/MiniMax-H3 | Animasi gambar tangan + live-action — **Hub-only** |

Catatan: API MiniMax H3 (platform.minimax.io) sudah diriset tapi **Boss menolak dihubungkan dulu** — info API hanya referensi. PIPELINE.md sobis tersimpan di `workspace/goals/youtube-content-creation/files/PIPELINE-sobis.md`.

---

## 2. Packaging & Render Deterministik (17 skill)

| Skill | Sumber | Fungsi singkat |
|---|---|---|
| remotion-best-practices | remotion-dev/skills | Router: aturan umum semua skill Remotion |
| remotion-create | remotion-dev/skills | Scaffold proyek video React |
| remotion-markup | remotion-dev/skills | Menulis markup Remotion |
| remotion-studio | remotion-dev/skills | Preview & edit di Remotion Studio |
| remotion-render | remotion-dev/skills | Render komposisi jadi MP4 |
| remotion-maps | remotion-dev/skills | Peta & animasi peta di Remotion |
| remotion-captions | remotion-dev/skills | Caption tersinkron kata per kata |
| remotion-saas | remotion-dev/skills | Remotion sebagai layanan |
| remotion-interactivity | remotion-dev/skills | Video interaktif |
| remotion-docs | remotion-dev/skills | Cari dokumentasi Remotion |
| remotion-license | remotion-dev/skills | Aturan lisensi Remotion |
| remotion-upgrade | remotion-dev/skills | Upgrade versi Remotion |
| remotion-multimedia | remotion-dev/skills | Audio, gambar & video di Remotion |
| remotion | remotion-dev/remotion | Gambaran umum engine Remotion (skill buatan sendiri) |
| remotion-new-markup | remotion-dev/remotion | Markup Remotion baru yang bisa diedit |
| motion-canvas | motion-canvas/motion-canvas | Animasi vektor TypeScript + editor preview (skill buatan sendiri) |
| manim | ManimCommunity/manim | Animasi matematika presisi ala 3Blue1Brown (skill buatan sendiri) |

Catatan: Remotion / Motion Canvas / Manim itu tiga pilihan renderer — pilih satu per proyek, jangan dicampur. Lisensi Remotion dua tingkat (gratis untuk individu & perusahaan kecil).

---

## 3. Animasi & Motion (8 skill)

| Skill | Sumber | Fungsi singkat |
|---|---|---|
| motion-design | LottieFiles/motion-design-skill | Prinsip motion design: timing, easing, personality — lapisan prinsip di atas semua engine |
| motion | motiondivision/motion | Library animasi React/JS/Vue (dulu Framer Motion) — skill buatan sendiri |
| animejs | juliangarnier/anime | Engine animasi JS ringan, timeline & stagger — skill buatan sendiri |
| gsap | greensock/GSAP | Engine animasi standar industri, semua plugin gratis — skill buatan sendiri |
| ola | franciscop/ola | Menghaluskan satu angka secara live — skill buatan sendiri |
| shifty | jeremyckahn/shifty | Tween engine minimal berbasis Promise — skill buatan sendiri |
| tweenjs | CreateJS/TweenJS | Tween engine chainable (CreateJS) — skill buatan sendiri |
| lottie-web | airbnb/lottie-web | Player animasi Lottie (After Effects via Bodymovin) — skill buatan sendiri |

Catatan: MCP LottieFiles Creator dan MCP Motion (`npx motion-ai`) **belum terhubung** — jangan dihubungkan tanpa keputusan Boss.

---

## 4. Gambar 2D, 3D & Game (16 skill)

| Skill | Sumber | Fungsi singkat |
|---|---|---|
| twojs | jonobr1/two.js | API gambar 2D (WebGL/Canvas/SVG) — skill buatan sendiri |
| konva | konvajs/konva | Canvas 2D interaktif: editor, diagram, whiteboard — skill buatan sendiri |
| tweakpane | cocopon/tweakpane | Panel tuning parameter live, export preset JSON — skill buatan sendiri |
| hairline-create | lucasmarkes/hairline | Gambar garis isometrik yang merespons pointer — 10 aturan tetap |
| hairline-adopt | lucasmarkes/hairline | Mengadopsi gambar SVG jadi figur Hairline |
| anatomy | wheresryan22/anatomy | Penjelasan teknis sebagai mesin isometrik yang bekerja |
| anatomy-reveal | annnguyentt/anatomy-reveal-skill | Halaman anatomi produk + film reveal MP4 (deterministik, dari geometri) |
| lume | lume/lume | 3D HTML berbasis elemen (masih alpha) — skill buatan sendiri |
| threejs | mrdoob/three.js | Library 3D JavaScript umum (WebGL/WebGPU) — skill buatan sendiri |
| babylonjs | BabylonJS/Babylon.js | Engine game/rendering 3D web lengkap (Apache-2.0) — skill buatan sendiri |
| godot | godotengine/godot | Game engine 2D/3D lengkap (GDScript/C#) — skill buatan sendiri |
| blender | blender/blender | Suite 3D lengkap + video editor (GPL v3) — skill buatan sendiri |
| react-three-rapier | pmndrs/react-three-rapier | Fisika (Rapier WASM) untuk React Three Fiber — skill buatan sendiri |
| react-postprocessing | pmndrs/react-postprocessing | Grading sinematik (Bloom, Depth of Field) untuk 3D — skill buatan sendiri |
| three-quarks | Alchemist0823/three.quarks | Sistem partikel & VFX untuk three.js — skill buatan sendiri |
| proton | drawcall/Proton | Library partikel ringan (api, ledakan, kembang api) — skill buatan sendiri |
| gifenc | mattdesl/gifenc | Encoder GIF dari frame (grafis datar saja, bukan foto/video) — skill buatan sendiri |

---

## 5. Audio & Media (4 skill)

| Skill | Sumber | Fungsi singkat |
|---|---|---|
| librosa | librosa/librosa | Analisis audio Python: tempo, beat, fitur musik — skill buatan sendiri |
| whisperx | m-bain/whisperX | Transkripsi + timestamp per kata + diarization pembicara — skill buatan sendiri |
| openverse | api.openverse.org | Cari gambar & audio berlisensi terbuka (800jt+ gambar) — skill buatan sendiri |
| ffmpeg | FFmpeg/FFmpeg | Perakitan video/audio: potong, gabung, subtitle, konversi (binary v8.1.2 sudah terpasang) — skill buatan sendiri |

Catatan: WhisperX diarization butuh token Hugging Face — **belum disiapkan**, jangan disiapkan tanpa keputusan Boss. Openverse: periksa lisensi tiap item; BY-NC tidak aman untuk channel monetisasi.

---

## 6. Bahasa Indonesia (2 skill)

| Skill | Sumber | Fungsi singkat |
|---|---|---|
| bahasa-indonesia | ajipurn/bahasa-indonesia-skill | Agen bicara bahasa Indonesia natural: register, gaya daerah, tingkat tutur |
| bahasa-skills | alvinindra/bahasa-skills | Kaidah tulis Indonesia bebas AI slop: inti, marketing, website, SEO, peneliti |

Catatan: bahasa-skills langsung mendukung misi anti-slop Divisi R&D — judul, deskripsi, caption, dan naskah.

---

## 7. Katalog Referensi (bukan skill)

| Item | Sumber | Fungsi |
|---|---|---|
| awesome-muse-ai-skills | AdityaRaj2434/awesome-muse-ai-skills | Daftar kurasi ~30 skill Muse AI (hyperframes, openfilm, story-animator, hallmark, dll.) — disimpan sebagai referensi, belum ada yang dipasang |

---

## 8. Skill yang sudah ada sebelumnya

| Skill | Fungsi |
|---|---|
| reference_photo_video | Foto referensi orang asli jadi video dengan wajah aman: foto series + voiceover untuk wajah close-up, animasi hanya untuk pemandangan/dari belakang |

---

## Aturan penting yang berlaku untuk semua skill

- **Tidak ada** library animasi/3D/game di atas yang menganimasikan foto asli atau menjaga wajah asli. Untuk wajah asli tetap pakai foto series + voiceover.
- **Tidak ada** model video (Muse built-in maupun H3) yang menjaga wajah asli.
- Yang **belum terhubung / belum dibeli** tanpa keputusan Boss: useapi.net, MiniMax H3 API, Muse4AI, LottieFiles Creator MCP, Motion MCP & Motion+, token Hugging Face untuk diarization WhisperX.
- Repo besar diklon ke `~/tmp-clones/` dengan `--depth 1 --filter=blob:none`, lalu dihapus setelah dipelajari (`/tmp` hanya 512 MB).
