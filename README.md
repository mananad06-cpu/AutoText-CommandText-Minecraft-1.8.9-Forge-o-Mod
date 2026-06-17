# AutoText Mod

**AutoText** es un mod para Minecraft 1.8.9 (Forge) que permite crear macros de texto y comandos, asignarlos a combinaciones de teclas y ejecutarlos al instante. Ideal para agilizar la comunicación y el uso de comandos en servidores.

## Características
- 📝 Crea macros con texto o comandos (prefijo `/` automático).
- ⌨️ Asigna teclas con modificadores: **Ctrl**, **Shift**, **Alt**.
- 🎨 Interfaz gráfica limpia y fácil de usar.
- 💾 Guardado automático en JSON.
- 🔌 Sin conflictos con otros mods (usa eventos de Forge).

## Capturas de pantalla

### Panel principal
![Panel principal](screenshots/panel_principal.png)

### Editor de macros
![Editor de macros](screenshots/editor.png)

## Instalación
1. Descarga el archivo `.jar` desde la sección [Releases](../../releases).
2. Colócalo en la carpeta `mods` de tu cliente de Minecraft Forge 1.8.9.
3. ¡Disfruta!

## Uso
- Pulsa la tecla asignada a tu macro (con o sin modificadores) para enviar el mensaje o comando.
- Abre el panel de configuración desde el botón **"Config AutoText"** en la pantalla del chat.

## Configuración de macros
Cada macro tiene los siguientes campos:

| Campo       | Descripción |
|-------------|-------------|
| Nombre      | Identificador del macro. |
| Texto       | Mensaje o comando a enviar (máx. 250 caracteres). |
| Tecla       | Tecla de activación (ej. `H`, `C`, `F1`). |
| Modificadores| Ctrl, Shift, Alt (puedes combinar varios). |
| Comando     | Si está activado, añade `/` al inicio automáticamente. |
| Activado    | Habilita o deshabilita el macro sin borrarlo. |

## Ejemplo de macros predefinidos
| Nombre     | Tecla | Modificadores | Tipo    | Texto |
|------------|-------|---------------|---------|-------|
| Soporte    | H     | -             | Comando | `/help` |
| Clan Chat  | C     | Ctrl          | Texto   | `Hola equipo!` |
| Gamemode   | G     | Alt           | Comando | `/gamemode creative` |

## Compatibilidad
- ✅ Forge 1.8.9
- ✅ Cliente y servidor (solo cliente, no requiere instalación en el servidor)
- ✅ Compatible con la mayoría de mods (OptiFine, JEI, etc.)

## Desarrollo
Este mod está desarrollado en Java usando la API de Minecraft Forge. El código está disponible bajo licencia MIT.

## Créditos
- **Autor**: CewlDown
- **Discord**: [Únete a nuestra comunidad](https://discord.gg/sTFPcZZJFU)

---

⭐ ¡Si te gusta el mod, no olvides dejar una estrella en GitHub!
