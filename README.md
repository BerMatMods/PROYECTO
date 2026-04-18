Aquí tienes un README profesional para tu proyecto de Yape:

```markdown
<div align="center">

![Yape Logo](https://i.postimg.cc/FRNhhv8k/1755961471955.jpg)

# 💜 YAPE - Versión Modificada

[![Versión](https://img.shields.io/badge/versión-2.5-purple?style=for-the-badge)](https://github.com/BerMatMods/PROYECTO)
[![Estado](https://img.shields.io/badge/estado-Activo-brightgreen?style=for-the-badge)](https://github.com/BerMatMods/PROYECTO)
[![Licencia](https://img.shields.io/badge/licencia-EDUCATIVA-orange?style=for-the-badge)](https://github.com/BerMatMods/PROYECTO)
[![Desarrollador](https://img.shields.io/badge/desarrollador-BerMatMods-turquoise?style=for-the-badge)](https://github.com/BerMatMods)

**Aplicación de pagos móviles estilo Yape con funcionalidades mejoradas**

[![Características](https://img.shields.io/badge/📱-Características-742384?style=for-the-badge)](#-características)
[![Instalación](https://img.shields.io/badge/⬇️-Instalación-2DD4BF?style=for-the-badge)](#-instalación)
[![Uso](https://img.shields.io/badge/📖-Uso-00c853?style=for-the-badge)](#-uso)

</div>

---

## 📱 Sobre el Proyecto

**YAPE** es una réplica funcional de la popular aplicación de pagos móviles peruanos, desarrollada con fines educativos. Esta versión modificada incluye características adicionales y una interfaz optimizada para brindar una experiencia de usuario mejorada.

> ⚠️ **Importante:** Esta aplicación es solo para fines educativos. No me hago responsable del mal uso que se le pueda dar.

---

## ✨ Características

<div align="center">

| 📱 | 💸 | 🔄 |
|:-:|:-:|:-:|
| **Interfaz Moderna** | **Envío de Dinero** | **Historial** |
| Diseño responsive y atractivo | Transferencias rápidas y seguras | Registro completo de transacciones |

| 📸 | 🎨 |  |
|:-:|:-:|:-:|
| **Cámara QR** | **Personalización** | **Seguridad** |
| Escaneo de códigos QR | Edición de perfil y saldo | Código de seguridad en transacciones |

</div>

### Funcionalidades Principales

- ✅ **Envío de dinero** a contactos
- ✅ **Escaneo de códigos QR** para pagos
- ✅ **Historial de transacciones** con recibos detallados
- ✅ **Gestión de perfil** (foto, nombre, teléfono)
- ✅ **Control de saldo** editable
- ✅ **Modo oscuro/claro** en saldo
- ✅ **Notificaciones** personalizadas
- ✅ **Diseño 100% responsive** para móviles
- ✅ **Animaciones** y efectos visuales
- ✅ **Sin conexión** a base de datos (localStorage)

---

## 🖼️ Capturas de Pantalla

<div align="center">

### 🏠 Pantalla Principal
![Home](https://via.placeholder.com/300x600/742384/ffffff?text=Pantalla+Principal)

### 💰 Enviar Dinero
![Send](https://via.placeholder.com/300x600/2DD4BF/ffffff?text=Enviar+Dinero)

### 📜 Historial
![History](https://via.placeholder.com/300x600/00c853/ffffff?text=Historial)

### 🧾 Recibo
![Receipt](https://via.placeholder.com/300x600/fbbd00/000000?text=Recibo)

</div>

---

## 🚀 Instalación

### Opción 1: Clonar Repositorio

```bash
# Clona el repositorio
git clone https://github.com/BerMatMods/PROYECTO.git

# Navega al directorio
cd PROYECTO

# Abre el archivo HTML en tu navegador
open index.html
```

### Opción 2: Descarga Directa

1. Ve a la [página del repositorio](https://github.com/BerMatMods/PROYECTO)
2. Haz clic en **"Code"** > **"Download ZIP"**
3. Extrae el archivo ZIP
4. Abre `index.html` en tu navegador

### Opción 3: Usar Online

```
Simplemente abre el archivo HTML en cualquier navegador moderno
```

---

## 📖 Uso

### Primeros Pasos

1. **Abrir la aplicación**: Abre el archivo `index.html` en tu navegador
2. **Personalizar perfil**: Ve al menú lateral y edita tu información
3. **Configurar saldo**: Establece tu saldo inicial desde el menú
4. **Comenzar a usar**: ¡Listo para realizar transacciones!

### Realizar un Pago

1. Haz clic en **"YAPEAR"** (botón turquesa)
2. Ingresa el número de celular (9 dígitos)
3. Escribe el nombre del destinatario
4. Ingresa el monto a enviar
5. Confirma la transacción
6. ¡Recibe tu recibo con código de seguridad!

### Escanear QR

1. Presiona **"ESCANEAR QR"** (botón blanco)
2. Apunta al código QR (simulado)
3. El pago se procesará automáticamente

### Ver Historial

1. Haz clic en **"Mostrar movimientos"**
2. Toca cualquier transacción para ver el recibo completo
3. Comparte o cierra el recibo

---

## 🛠️ Tecnologías Utilizadas

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

### Detalles Técnicos

- **Frontend**: HTML5, CSS3, JavaScript Vanilla
- **Iconos**: Font Awesome 6.5.0
- **Almacenamiento**: LocalStorage del navegador
- **Diseño**: Responsive, Mobile-First
- **Compatibilidad**: Todos los navegadores modernos

---

## 📂 Estructura del Proyecto

```
PROYECTO/
│
├── index.html              # Archivo principal
├── README.md               # Documentación
├── Audio/                  # Archivos de audio
│   └── Audio cuando te yapean.mp3
├── Anuncios/               # Imágenes promocionales
│   ├── Anuncio de yape2.jpg
│   └── Anuncio de yape3.jpg
└── assets/                 # Recursos adicionales (opcional)
```

---

## 🎨 Personalización

### Cambiar Colores

Edita las variables CSS en el `<style>`:

```css
:root {
  --yape-purple: #742384;        /* Color principal */
  --yape-turquoise: #2DD4BF;     /* Color secundario */
  --yape-green: #00c853;         /* Color de éxito */
}
```

### Modificar Datos por Defecto

En la sección `<script>`:

```javascript
let userData = {
  name: 'Tu Nombre',
  nickname: 'Tu Apodo',
  email: 'tu@email.com',
  balance: 1000.00
};
```

---

## 🔧 Funciones Disponibles

### Menú Lateral

- 📝 **Editar Perfil**: Cambia foto, nombre, email y teléfono
- 💵 **Editar Saldo**: Modifica tu saldo disponible
- 🗑️ **Borrar Historial**: Limpia todas las transacciones
- ⚙️ **Configuración**: Ajustes de seguridad y notificaciones
- ℹ️ **Información**: Detalles de la app y desarrollador

### Servicios

- 📱 Recargar celular
- 🛍️ Tienda
- 💱 Dólares
- 🚌 Viajar en bus
- 🛡️ SOAT
- Y más servicios demostrativos

---

## 🐛 Solución de Problemas

### La app no carga
- Verifica que el archivo HTML esté completo
- Abre la consola del navegador (F12) para ver errores
- Usa un navegador actualizado (Chrome, Firefox, Safari)

### El audio no suena
- Permite la reproducción de audio en el navegador
- Verifica el volumen del dispositivo
- Revisa la conexión a internet (si el audio está alojado online)

### Los datos no se guardan
- Verifica que el navegador tenga activado localStorage
- No uses modo incógnito (los datos se borran al cerrar)
- Limpia la caché y recarga la página

---

## 📱 Compatibilidad

| Plataforma | Versión | Estado |
|------------|---------|--------|
| **Chrome** | 90+ | ✅ Compatible |
| **Firefox** | 88+ | ✅ Compatible |
| **Safari** | 14+ | ✅ Compatible |
| **Edge** | 90+ | ✅ Compatible |
| **Opera** | 76+ | ✅ Compatible |
| **iOS Safari** | 14+ | ✅ Compatible |
| **Android Chrome** | 90+ | ✅ Compatible |

---

## 🔐 Privacidad y Seguridad

- ✅ **Sin backend**: Todos los datos se almacenan localmente
- ✅ **Sin servidores**: No se envía información a ningún servidor
- ✅ **Privacidad total**: Tus datos nunca salen de tu dispositivo
- ✅ **Código abierto**: Puedes auditar todo el código

---

## 📝 Licencia

<div align="center">

**⚠️ LICENCIA EDUCATIVA**

Este proyecto es de carácter **EDUCATIVO** y **DEMOSTRATIVO**.

- ✅ Puedes usarlo para aprender
- ✅ Puedes modificarlo para practicar
- ✅ Puedes compartirlo con fines educativos
- ❌ **NO** usar para fines comerciales
- ❌ **NO** usar para engañar o estafar
- ❌ **NO** hacerse pasar por la app oficial

**El desarrollador no se hace responsable del mal uso de esta aplicación.**

</div>

---

## 👨‍ Desarrollador

<div align="center">

![Developer Avatar](https://ui-avatars.com/api/?name=AnthZz+Berrocal&background=742384&color=fff&size=128)

### **AnthZz Berrocal**

**𖤍𝐞𝐫𝐌𝐚_𝐂𝐨𝐝𝐞𖤍**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BerMatMods)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/BerMatMods)

**Desarrollador Full Stack • Creador de Mods • Entusiasta del Código**

</div>

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas para fines educativos:

1. Haz un Fork del proyecto
2. Crea una rama (`git checkout -b feature/MejoraIncreible`)
3. Commit tus cambios (`git commit -m 'Añadir mejora increíble'`)
4. Push a la rama (`git push origin feature/MejoraIncreible`)
5. Abre un Pull Request

---

## 📞 Soporte

¿Tienes preguntas o problemas?

- 📧 **Email**: anthzzhacks@gmail.com
- 💬 **Telegram**: [@BerMatMods](https://t.me/BerMatMods)
- 🐛 **Issues**: [Reportar bug](https://github.com/BerMatMods/PROYECTO/issues)

---

## 🙏 Agradecimientos

- **Font Awesome** por los iconos
- **La comunidad** por el apoyo constante
- **Tú** por usar esta aplicación educativa

---

## 🔗 Enlaces Útiles

- [Repositorio Oficial](https://github.com/BerMatMods/PROYECTO)
- [Reportar Bug](https://github.com/BerMatMods/PROYECTO/issues)
- [Solicitar Característica](https://github.com/BerMatMods/PROYECTO/issues)
- [Descargar Última Versión](https://github.com/BerMatMods/PROYECTO/releases)

---

<div align="center">

### ⭐ ¡Si te gusta el proyecto, dale una estrella! ⭐

**© 2022-2026 BerMatCode • Desarrollador Oficial**

**𖤍𝐞𝐫𝐌𝐚_𝐂𝐨𝐝𝐞**

---

![Divider](https://i.imgur.com/742384.png)

**Hecho con 💜 y mucho ☕**

</div>
```

