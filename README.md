# NEON NES 🎮

An Android NES emulator with English and Arabic, touch/gamepad controls, save states and an offline game library.

**[Download NEON NES 1.18 for Android](https://raw.githubusercontent.com/jameelabo/NeonNES/main/NeonNES-v1.18.apk)**

## Install

Requires Android 8.0 or newer. Download the APK and open it. Allow installation from the app opening the APK if Android asks. Install updates over the existing app without uninstalling to keep your imported games and save states.

English is the default. Change language in **Settings → Language**.

## Features

- Import local `.nes` games into your library.
- Original STAR CATCH demo included.
- Touch controls, keyboard and standard gamepad support.
- Landscape layout: large centered display, D-pad on the left, A/B and SELECT/START on the right.
- Fullscreen by default on Android.
- Save slots, autosave and JSON save-state import/export.
- Sound, speed, CRT effect and vibration settings.
- Optional Libretro cover downloads. Playing imported games works offline; downloading covers requires internet access.

## بالعربية

محاكي NES للأندرويد، يدعم العربية والإنجليزية ويعمل بألعاب تستوردها من جهازك، مع حفظ التقدم وأزرار لمس ودعم ذراع التحكم.

**[تحميل NEON NES 1.18](https://raw.githubusercontent.com/jameelabo/NeonNES/main/NeonNES-v1.18.apk)**

- يحتاج Android 8 أو أحدث.
- ثبّت التحديث فوق نسختك الحالية دون حذفها، للحفاظ على الألعاب ونقاط الحفظ.
- الإنجليزية افتراضية؛ اختر العربية من **Settings → Language**.
- شاشة لعب كبيرة في الوسط، الأسهم يسارًا وأزرار A/B وSELECT/START يمينًا.
- ملء الشاشة افتراضي، ومكتبة ألعاب محلية، وحفظ تلقائي واستيراد/تصدير نقاط الحفظ.

## Notes

NES iNES support and compatibility vary by cartridge/mapper. File export requires Android 10 or newer. This repository distributes app builds and the original STAR CATCH demo inside the APK; no third-party commercial ROMs are included. Import games you have permission to use.

- Package: `com.jimmy.neonnes`
- Version: `1.18` / version code `19`
- Emulator engine: JSNES 2.1.0, Apache 2.0 — [license](JSNES-LICENSE.txt).
- Signing keys, personal saves and private workspace data are excluded.
