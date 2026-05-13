<div align="center">
  <a href="https://obirtus-launcher.vercel.app/">
    <img src="https://raw.githubusercontent.com/Togamer0109q/Launcher-Obirtus/refs/heads/main/banner.png" alt="Obirtus Launcher Banner" width="100%" />
  </a>
  <br />
  <br />
  <a href="https://obirtus-launcher.vercel.app/">
    <img src="https://raw.githubusercontent.com/Togamer0109q/Launcher-Obirtus/refs/heads/main/icon.png" alt="Obirtus Launcher Logo" width="120" height="120" />
  </a>

  # OBIRTUS Launcher

  **Launcher de eventos de Minecraft moderno, rápido y personalizable** <br> con instalación automática de mods, Discord OAuth y un robusto sistema de skins.

  [![Website](https://img.shields.io/badge/Website-obirtus--launcher.vercel.app-00e5ff?style=for-the-badge&logo=vercel)](https://obirtus-launcher.vercel.app/)
  [![Estado](https://img.shields.io/badge/Estado-En_Construcción-ff8c00?style=for-the-badge)](#)
  [![Plataforma](https://img.shields.io/badge/Plataforma-Windows_10%20%7C%2011-0078d7?style=for-the-badge&logo=windows)](#)

</div>

<hr />

## ✨ Características Principales

-  **Selección de Eventos con Un Clic:** Explora los eventos disponibles e inicia tu instancia al instante sin configuraciones manuales.
-  **Instalación Automática de Mods:** Descarga e instala colecciones de mods (Forge/Fabric) por evento en tiempo real.
-  **Auto-Conexión al Servidor:** Olvídate de añadir la IP manualmente; entra directo a jugar.
-  **Integración con Discord:** Inicia sesión de manera segura con Discord OAuth y muestra tu actividad con Discord Rich Presence (RPC).
-  **Sistema Avanzado de Skins:** Compatible con skins por mod (`CustomSkinLoader`) o mediante plugins del servidor (Soporte nativo para Ely.by).
-  **Dashboard Web Administrativo:** Panel de control web para crear eventos, aprobar solicitudes y gestionar la whitelist.
-  **Auto-Updates Inclusivos:** Sistema de actualización inteligente basado en GitHub Releases mediante `electron-updater`.

---

## 💻 Requisitos del Sistema

Para disfrutar de la mejor experiencia posible, asegúrate de cumplir con los siguientes requisitos:

- **Sistema Operativo:** Windows 10 o Windows 11. *(Soporte actual de la build)*.
- **Entorno de Ejecución:** Java 17 o superior (Recomendado).

##  Sistema de Skins

El launcher está optimizado para funcionar con los siguientes métodos de visualización de skins:

1. **Mod de Cliente:** Mediante `CustomSkinLoader`.
2. **Plugin del Servidor:** Gestionado internamente en tu servidor (ej. SkinsRestorer).

> [!TIP]
> **Para usuarios de Forge:** Si utilizas `CustomSkinLoader`, el launcher puede exigirlo de manera automática al unirse a un evento para garantizar que la experiencia sea unificada.

###  Recomendaciones (Ely.by)
- Sistema de Skins para Servidores: [Ely.by Server Skins System](https://ely.by/server-skins-system)
- Galería y Descargas: [Ely.by Load](https://ely.by/load)

## 🛠️ Troubleshooting (Solución de Problemas)

¿Tienes problemas con el launcher? Aquí tienes las soluciones más frecuentes:

- **¿Forge/Fabric se abre en su versión Vanilla (sin mods)?**
  *Solución:* Revisa en tu Dashboard Web que el evento tenga el valor `loader` configurado correctamente (ej. `forge`, `fabric`).
- **¿Los mods de un evento no cargan o fallan al descargar?**
  *Solución:* pidele al creador de el evento que las URLs de descarga sean enlaces **directos** a los archivos `.jar` ya que si no es asi no funciona.

---

## 🚀 Roadmap (Próximamente)

Continuamente mejoramos el launcher para llevarlo al siguiente nivel:

- [ ] 🟢 **Soporte para NeoForge y Quilt** como nuevos modloaders.
- [ ] ☁️ **Descarga automática de CustomSkinLoader** directamente desde nuestro CDN privado.
- [ ] 📋 **Consola Integrada:** Vista en vivo de los logs internos de Minecraft y del Launcher sin salir de la app.
- [ ] 💻 **Inicio de minecraft** Botones directos para marketplace, servidores recomendados y mucho mas sin salir de minecraft.

---

<div align="center">
  <b>Desarrollado con ❤️ para la comunidad</b><br>
  <a href="https://obirtus-launcher.vercel.app/">Visita nuestro sitio oficial</a>
</div>

