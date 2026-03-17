# OBIRTUS Launcher

Launcher de eventos de Minecraft con instalacion automatica de mods, Discord OAuth y sistema de skins.

## Estado
- En construccion.

## Caracteristicas
- Seleccion de eventos y lanzamiento con un clic.
- Instalacion de mods por evento (Forge/Fabric).
- Auto-conexion al servidor.
- Discord login y notificaciones.
- Skins por mod (CustomSkinLoader) o plugin del servidor.
- Dashboard web para crear y aprobar eventos.
- Auto-update con GitHub Releases (electron-updater).

## Requisitos
- Windows 10/11 (soportado por el build actual).
- Java 17 o superior recomendado.
- Discord Desktop abierto para Rich Presence.

## Skins
El launcher solo soporta skins con:
- Mod cliente (CustomSkinLoader), o
- Plugin en el servidor.

Si usas CustomSkinLoader en Forge, el launcher puede requerirlo por evento.

Recomendado:
- Ely.by Server Skins System: https://ely.by/server-skins-system
- Descargas Ely.by: https://ely.by/load

## CustomSkinLoader (cliente)
Ruta esperada:
```
assets/skin-mods/customskinloader.jar
```

## Backend y Dashboard
El backend vive en `backend/` y trae su propio README:
```
backend/README.md
```

Incluye:
- Login con Discord
- Whitelist
- Creacion y aprobacion de eventos

## Troubleshooting
- Forge abre en Vanilla: revisa que el evento tenga `loader` correcto.
- RPC no aparece: activa "Mostrar actividad actual" en Discord.
- Mods no cargan: verifica URLs directas a `.jar`.

## Roadmap (idea)
- Soporte para NeoForge/Quilt.
- Descarga automatica de CustomSkinLoader desde un CDN propio.
- Vista de logs dentro del launcher.

