# Generador de Presupuestos

Una aplicación web simple y profesional para crear presupuestos personalizados y generar imágenes listas para compartir con tus clientes.

## 🚀 Características

- **Interfaz intuitiva**: Diseño limpio y moderno con Tailwind CSS
- **Generación de imágenes**: Convierte presupuestos en imágenes PNG de alta calidad
- **Copia al portapapeles**: Copia la imagen directamente al portapapeles para compartir en WhatsApp, email, etc.
- **Cálculos automáticos**: Subtotal, envío y total se calculan automáticamente
- **Responsive**: Funciona en dispositivos móviles y de escritorio
- **Marca de agua**: Incluye marca de agua "OFICIAL" en las imágenes generadas

## 📋 Cómo usar

1. **Abre el archivo `index.html`** en tu navegador web
2. **Ingresa el nombre del cliente** en el campo correspondiente
3. **Agrega productos**:
   - Cantidad
   - Nombre del producto
   - Precio unitario
4. **Agrega costo de envío** si es necesario
5. **Haz clic en "COPIAR IMAGEN AL PORTAPAPELES"** para generar y copiar la imagen
6. **Pega la imagen** (Ctrl+V) en tu aplicación de mensajería o email

## 🛠️ Tecnologías utilizadas

- **HTML5**: Estructura de la aplicación
- **CSS3 + Tailwind CSS**: Estilos y diseño responsivo
- **JavaScript (Vanilla)**: Lógica de la aplicación
- **html2canvas**: Generación de imágenes desde el DOM

## 📁 Estructura del proyecto

```
budget-pt/
├── index.html          # Archivo principal de la aplicación
└── README.md           # Este archivo
```

## 🌐 Compatibilidad

- Navegadores modernos con soporte para:
  - Clipboard API
  - Canvas API
  - ES6+

## 📝 Personalización

Puedes personalizar la aplicación editando el archivo `index.html`:

- **Colores**: Modifica las clases de Tailwind CSS
- **Texto**: Cambia los mensajes y etiquetas
- **Marca de agua**: Edita el texto en la clase `.watermark`
- **Estilos**: Ajusta el CSS personalizado

## 🤝 Contribuir

Si quieres contribuir a este proyecto:

1. Haz un fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -am 'Agrega nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

Creado por [ciscojmg](https://github.com/ciscojmg)

---

¡Gracias por usar el Generador de Presupuestos! Si te gusta, dale una ⭐ al repositorio.

*Última actualización: Enero 2026*