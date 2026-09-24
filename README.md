# ConstrucHub Desktop — Releases

> 📦 **Feed oficial de descargas** de la aplicación de escritorio de [ConstrucHub](https://construc-hub-nine.vercel.app) — gestión integral para la construcción turística.

Este repositorio **solo aloja los instaladores publicados** (releases firmados criptográficamente). El código fuente de la aplicación vive en el repositorio **privado** del proyecto.

## ⬇️ Descargar

| Archivo | Uso |
|---|---|
| `ConstrucHub_<versión>_x64-setup.exe` | **Recomendado** — instalador NSIS con auto-actualización interna |
| `ConstrucHub_<versión>_x64_en-US.msi` | Alternativa tradicional (sin auto-actualización) |

👉 Descarga siempre el más reciente desde la página de [**Releases**](https://github.com/ReidelAlcantara/ConstrucHub-Desktop/releases/latest).

## 🔄 Auto-actualización

Si ya tienes la app instalada (instalador `.exe`), **no necesitas volver a descargar nada**: al abrirla, la aplicación comprueba este repositorio y se actualiza sola. Las actualizaciones están firmadas digitalmente (`latest.json` + firmas `.sig`).

## 🛡️ Veracidad de los instaladores

Cada asset `.exe` / `.msi` lleva su firma `.sig` correspondiente, verificada por el actualizador interno antes de instalar. No instales binarios que no provengan de este repositorio.

## 🧩 Plataforma

- Windows 10/11 (x64)
- Construida con Tauri 2 · React 19 · motor de sincronización Rust con persistencia SQLite local (modo offline)
