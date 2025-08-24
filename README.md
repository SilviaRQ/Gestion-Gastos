# 📊 Gestión de Gastos Automatizada con n8n

Este proyecto permite registrar gastos de manera automática usando **Telegram** y **Google Sheets**, gracias a un workflow en [n8n](https://n8n.io/).

## 🚀 Descripción

El sistema funciona de la siguiente manera:
1. El usuario envía un mensaje a un bot de Telegram, por ejemplo:
supermercado 1500

2. El workflow en n8n procesa el mensaje:
- Separa la **descripción** (`supermercado`) y el **monto** (`1500`).
- Agrega la **fecha actual**.
3. Los datos se envían automáticamente a un **Google Sheet**, donde quedan registrados en una tabla de gastos.

## ⚙️ Tecnologías utilizadas
- [n8n](https://n8n.io/) como motor de automatización.
- Bot de Telegram.
- Google Sheets como base de datos de gastos.

## 📂 Estructura del repositorio
- `/workflows`: contiene los `.json` exportados de n8n para importar directamente.
- `/docs`: imágenes y diagramas del flujo.
- `README.md`: documentación del proyecto.

## 📌 Estado del proyecto
🚧 En construcción. Actualmente la automatización básica funciona, pero está en etapa de mejora.  

## 💡 Posibles mejoras a futuro
- [ ] Manejar distintos tipos de monedas.  
- [ ] Categorizar gastos automáticamente según palabras clave.  
- [ ] Enviar reportes semanales o mensuales por Telegram.  
- [ ] Generar gráficos de gastos directamente desde Google Sheets o Power BI.  
- [ ] Añadir validaciones en los mensajes (ejemplo: corregir formatos incorrectos).  

---
