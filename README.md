# Music Manager (Cancionero) — descargas para Android

Instaladores **APK** de Music Manager, compilados y **firmados** automáticamente por GitHub
Actions desde el repositorio de código.

## 📲 Instalar

**Enlace directo (siempre la última versión):**

```
https://github.com/danielvaldess/cancionero-apk/releases/latest/download/music-manager.apk
```

1. Abre el enlace en el **teléfono**.
2. Android pedirá permitir "instalar apps de orígenes desconocidos" para el navegador: acepta.
3. Abre el archivo descargado e instala.

Cada versión trae además un archivo `.apk.sha256` para comprobar que la descarga no se corrompió.

## 📦 Versiones

| Versión | Enlace |
|---|---|
| Última | [Releases](../../releases/latest) |

> El APK se firma con la misma clave en cada compilación, así que las actualizaciones se
> instalan **encima** de la versión anterior sin desinstalar (y conservan los datos locales).

## ⚙️ Servidor

La app trae grabada la dirección del servidor (`VITE_API_URL` al compilar) y además permite
escribirla a mano en **Perfil → Cuenta → Servidor**, que es lo que permite apuntar al servidor
de pruebas o al real sin recompilar.
