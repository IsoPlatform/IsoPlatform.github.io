# ISO Platform

![ISO Platform](https://img.shields.io/badge/ISO-Platform-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Plataforma web dedicada a la implementación y mejora continua de sistemas de gestión basados en estándares internacionales ISO.

## 🎯 Descripción

**ISO Platform** es una organización enfocada en promover la excelencia operacional a través de la implementación de sistemas de gestión integrados basados en los estándares ISO 9001 (Gestión de Calidad), ISO 14001 (Gestión Ambiental) e ISO 45001 (Seguridad y Salud Ocupacional).

## 🌟 Características

- **Información completa** sobre ISO 9001, ISO 14001 e ISO 45001
- **Recursos educativos** sobre cada estándar
- **Diseño responsive** compatible con todos los dispositivos
- **Arquitectura escalable** preparada para incorporar más estándares ISO
- Construido con **Jekyll** para GitHub Pages

## 📋 Estándares Cubiertos

### ISO 9001:2015 - Gestión de Calidad
Sistema de gestión de calidad enfocado en la satisfacción del cliente y mejora continua.

### ISO 14001:2015 - Gestión Ambiental
Sistema de gestión ambiental para reducir el impacto ecológico y promover la sostenibilidad.

### ISO 45001:2018 - Seguridad y Salud Ocupacional
Sistema de gestión para prevenir lesiones y enfermedades relacionadas con el trabajo.

## 🚀 Instalación y Uso Local

### Prerrequisitos

- Ruby 2.5.0 o superior
- RubyGems
- GCC y Make

### Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/IsoPlatform/isoplatform.github.io.git
cd isoplatform.github.io
```

2. Instala las dependencias:
```bash
bundle install
```

3. Ejecuta el servidor local:
```bash
bundle exec jekyll serve
```

4. Abre tu navegador en `http://localhost:4000`

## 📁 Estructura del Proyecto

```
isoplatform.github.io/
├── _config.yml          # Configuración de Jekyll
├── _layouts/            # Plantillas HTML
│   └── default.html
├── assets/              # Recursos estáticos
│   └── css/
│       └── style.css
├── index.md             # Página principal
├── iso9001.md           # Página ISO 9001
├── iso14001.md          # Página ISO 14001
├── iso45001.md          # Página ISO 45001
├── about.md             # Acerca de
├── Gemfile              # Dependencias Ruby
└── README.md            # Este archivo
```

## 🎨 Personalización

### Modificar el contenido

Los archivos principales están en formato Markdown (.md) en la raíz del proyecto. Edítalos para actualizar el contenido.

### Modificar estilos

Los estilos CSS se encuentran en `assets/css/style.css`. Personalízalos según tus necesidades.

### Configuración del sitio

Edita `_config.yml` para cambiar:
- Título del sitio
- Descripción
- URL base
- Otros ajustes de Jekyll

## 🌐 Despliegue en GitHub Pages

1. Asegúrate de que el repositorio se llame `[tu-usuario].github.io` o configura GitHub Pages en la configuración del repositorio
2. Haz push de tus cambios:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```
3. Ve a Settings > Pages en tu repositorio
4. Selecciona la rama `main` como fuente
5. Tu sitio estará disponible en `https://isoplatform.github.io`

## 🔮 Futuro

Este proyecto está diseñado para escalar e incorporar otros estándares ISO relevantes, incluyendo:

- ISO 27001 - Gestión de Seguridad de la Información
- ISO 50001 - Gestión de la Energía
- ISO 22000 - Gestión de Seguridad Alimentaria
- ISO 20000 - Gestión de Servicios de TI
- ISO 37001 - Sistemas Antisoborno
- Y muchos más...

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas colaborar:

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📧 Contacto

Para más información, visita [github.com/IsoPlatform](https://github.com/IsoPlatform)

---

**ISO Platform** - Excelencia en Gestión a través de Estándares Internacionales
