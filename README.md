# AuraMusic AI

![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Release](https://img.shields.io/github/v/release/hubkalukas/rozhodn-ne-ai-pro-blbosti?label=Latest%20APK)

Offline hudební přehrávač pro Android s chytrými doporučeními přímo v zařízení ve stylu YouTube Music.

> **English summary:** AuraMusic AI is an Android offline music player featuring YouTube Music–style smart recommendations powered by on-device open-source algorithms (exponential time decay, Markov transition chains, circadian hour-of-day matching, and artist diversity) with local playback-time tracking.

---

## ⬇️ Stažení aplikace

- **[Stáhnout AuraMusic-v1.2.0.apk (nejnovější verze)](https://github.com/hubkalukas/rozhodn-ne-ai-pro-blbosti/releases/latest/download/AuraMusic-v1.2.0.apk)**
- Kompletní přehled verzí a soubor `update-manifest.json` najdeš v sekci [Releases](https://github.com/hubkalukas/rozhodn-ne-ai-pro-blbosti/releases).

---

## Hlavní funkce (v1.2.0)

- **Záložka Doporučeno ve stylu YouTube Music:**
  - *Přehrát znovu* — skladby, ke kterým se nejčastěji vracíš
  - *Rychlý výběr* s chytrým rádiem
  - *Nedávno přehrané* a *Zapomenuté klenoty*
  - *Filtry nálad*
- **Chytré doporučovací algoritmy lokálně v telefonu:**
  - Exponenciální časový rozpad (*exponential time decay*)
  - Markovův řetězec přechodů mezi skladbami (*Markov chain*)
  - Cirkadiánní shoda podle denní hodiny poslechu
  - Řízená diverzita interpretů, aby se nehrál pořád jeden autor dokola
- **Statistiky poslechu:** Přesný záznam času poslechu každé skladby v lokální databázi (`playback_events`) a žebříček *Nejposlouchanější podle času*.
- **Spolehlivá knihovna bez limitu 128 souborů:** Automatický převod Android SAF výběrů na trvalé `MediaStore` URI.

---

## Instalace

1. Stáhni nejnovější soubor `AuraMusic-v1.2.0.apk` ze sekce [Releases](https://github.com/hubkalukas/rozhodn-ne-ai-pro-blbosti/releases).
2. Otevři stažené APK v telefonu a povol instalaci z neznámých zdrojů, pokud si ji systém vyžádá.
3. Po spuštění povol přístup k hudebním souborům v zařízení.