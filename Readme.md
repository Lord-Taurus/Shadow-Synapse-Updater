# 🛰️ Synapse Update Infrastructure

![Updater](https://img.shields.io/badge/Service-AutoUpdater.NET-blueviolet?style=for-the-badge)
![Security](https://img.shields.io/badge/Access-Public_Repo-red?style=for-the-badge)
![Maintenance](https://img.shields.io/badge/Status-Automated-success?style=for-the-badge)

Ez a privát tároló a **Synapse** ökoszisztéma frissítési folyamatait szolgálja ki. Itt tárolódnak a verziókezelő XML fájlok, a kiadási jegyzékek (changelogs) és a telepítőcsomagok metaadatai.

---

## 📂 Felépítés

A repo az alábbi fájlstruktúrát követi az **AutoUpdater.NET** kompatibilitás érdekében:

* 📁 `releases/` - Itt találhatók a bináris `.zip` vagy `.msi` csomagok (opcionális, ha nem a GitHub Release-t használod).
* 📄 `update.xml` - A központi konfigurációs fájl, amelyet a kliens lekérdez.
* 📄 `Update.md` - A frissítő ablakban megjelenő részletes módosítási lista.

---
