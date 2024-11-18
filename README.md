# Gmail to Google Sheets Automation 🚀

Automatización que importa datos desde Gmail a Google Sheets. Este proyecto es ideal para automatizar la gestión de informes repetitivos en la nube, compatible con archivos **CSV** y **XLSX**.

---

## 🚩 **Características**
- Automatiza la búsqueda de correos con archivos adjuntos específicos.
- Compatible con archivos CSV y XLSX.
- Exporta automáticamente los datos a una pestaña específica en Google Sheets.

---

## 💻 **Cómo funciona**
1. El script busca correos en Gmail con un término específico en el asunto.
2. Descarga el archivo adjunto (CSV o XLSX).
3. Los importa a una hoja de cálculo de Google Sheets.

---

## ⚙️ **Cómo usarlo**
1. Crea un nuevo proyecto en Apps Script desde Google Drive.
2. Copia el contenido de `import-data` en el editor de Apps Script.
3. Configura:
   - El término de búsqueda (`MAIL_SUBJECT`) en Gmail.
   - La ID de la hoja de cálculo (`SPREADSHEET_ID`).
   - El nombre de la pestaña (`SHEET_NAME`).
4. Ejecuta la función `importarDatosSesiones`. Aunque recomiendo configurarlo para que se ejecute de madrugada o cuando consideres (cuando te suela llegar el mail).

---

## 🛠️ **Tecnologías**
- **Google Apps Script**
- **Google Sheets**
- **Gmail API**

---
