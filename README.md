# Scrapper WhatsApp One Conversation

Extrae conversaciones completas de **WhatsApp Web** y las descarga como archivo `.txt`.

## 🚀 Modo de uso

### Opción A: Bookmarklet (recomendado)
1. Crea un nuevo marcador en tu navegador
2. En la URL del marcador, pega el código de `bookmarklet.js` (todo en una línea, precedido por `javascript:`)
3. Abre WhatsApp Web, entra al chat deseado
4. Haz clic en el marcador
5. Usa **Auto-scroll** y luego **Descargar**

### Opción B: Consola del navegador
1. Abre WhatsApp Web y el chat que quieres extraer
2. Presiona `F12` → pestaña **Console**
3. Pega el contenido de `scraper.js`
4. Presiona `Enter`

## 📊 Panel de control

Una vez activo, verás un panel con:
- **🔒 Chat bloqueado**: nombre del grupo/conversación actual
- **Capturados**: total de mensajes únicos encontrados
- **Con fecha / Sin**: mensajes con/sin timestamp
- **▶ Auto-scroll**: carga automáticamente mensajes antiguos
- **⬇ Descargar .txt**: guarda todo en un archivo de texto

## 🛡️ Seguridad

- El script **no envía datos a ningún servidor**
- Todo el procesamiento ocurre en tu navegador
- Se detiene automáticamente si cambias de chat

## ⚠️ Limitaciones

- Requiere que el teléfono esté conectado a internet
- WhatsApp Web puede pedir "click para obtener mensajes antiguos"
- Mensajes muy antiguos pueden no cargar si el teléfono no los sincroniza

## 📁 Estructura
