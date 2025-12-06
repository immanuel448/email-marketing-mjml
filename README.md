# Email Marketing con MJML  
Plantillas MJML compiladas a HTML compatible con Gmail, Outlook y otros clientes de correo.

## 📌 ¿Qué es este repositorio?
Este proyecto contiene ejemplos de emails creados en MJML y compilados a HTML listo para usar en plataformas de email marketing como:

- Mailchimp  
- Klaviyo  
- MoEngage  
- HubSpot  
- Campaign Monitor  

## ⚙️ Requisitos
- Node.js instalado  
- MJML instalado globalmente:

npm install -g mjml

## 🚀 Compilar MJML a HTML
Cada vez que edites un archivo .mjml, debes generar nuevamente su versión HTML:

mjml archivo.mjml -o archivo.html

Ejemplo:

mjml promo.mjml -o promo.html

## 🔁 Modo automático (opcional)
Para recompilar automáticamente cada vez que guardes cambios:

mjml promo.mjml -w -o promo.html

## 📄 Estructura del proyecto
/
├── promo.mjml       # Archivo MJML editable
├── promo.html       # Archivo HTML generado
└── README.md

## 📝 Notas
- MJML permite escribir emails con estructura limpia y moderna.  
- El HTML generado por MJML es compatible con Gmail, Outlook y clientes que no soportan CSS moderno.  
- El archivo .mjml es el que editas; el .html es el que subes a tu plataforma de correos.
