# 📦 smtp2mqtt-releases

Tento veřejný repozitář slouží jako oficiální distribuční kanál a auto-update manifest pro LoxBerry plugin **smtp2mqtt** (SMTP to MQTT Bridge pro Hikvision kamery, interkomy a Loxone automatizaci).

---

## 🚀 Instalace na LoxBerry

Pro instalaci pluginu do LoxBerry:
1. Otevřete webové rozhraní LoxBerry (**Plugin Management** -> **Install plugin**).
2. Do pole **Plugin URL or Archive URL** vložte:
   ```text
   https://github.com/onhala/smtp2mqtt-releases/releases/download/v2.2.0/smtp2mqtt-loxberry-v2.2.0.zip
   ```
3. Klikněte na **Install plugin**.

---

## 🔄 Automatické aktualizace (AutoUpdate)

LoxBerry plugin je nakonfigurován pro automatickou detekci nových verzí přes:
- **Release kanál:** `https://raw.githubusercontent.com/onhala/smtp2mqtt-releases/master/release.cfg`
- **Pre-release kanál:** `https://raw.githubusercontent.com/onhala/smtp2mqtt-releases/master/prerelease.cfg`

---

## 🔒 Vývoj a zdrojový kód

Zdrojový vývojový repozitář je privátní (`onhala/smtp2mqtt`). Tento repozitář obsahuje výhradně zkompilované distribuční archivy a manifesty.
