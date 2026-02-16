# Servicio Automotriz Martínez - Landing Pages

Landing pages profesionales para Servicio Automotriz Martínez, taller mecánico premium en Aguascalientes, México.

## 🚀 Descripción

Este repositorio contiene las páginas de aterrizaje (landing pages) del negocio Servicio Automotriz Martínez. Las páginas están diseñadas para:

- Atraer nuevos clientes
- Mostrar los servicios ofrecidos
- Facilitar el contacto y agendamiento de citas
- Mejorar la presencia online y SEO local

## 📁 Estructura del Proyecto

```
landing-pages-Taller-Martinez/
├── index.html                  # Página principal
├── taller azul profundo.html   # Variante de diseño alternativa
├── README.md                   # Este archivo
├── .gitignore                  # Archivos ignorados por Git
├── robots.txt                  # Directivas para motores de búsqueda
├── sitemap.xml                 # Mapa del sitio para SEO
└── 404.html                    # Página de error personalizada
```

## 🌟 Características

- **Diseño Responsive**: Optimizado para móviles, tablets y desktop
- **SEO Optimizado**: Meta tags, structured data (Schema.org), Open Graph
- **Accesibilidad**: Atributos alt en imágenes, estructura semántica HTML5
- **Performance**: Carga rápida con CDN (Tailwind CSS)
- **Profesional**: Diseño moderno con efectos de vidrio y animaciones sutiles

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (via Tailwind CSS CDN)
- JavaScript Vanilla
- Google Fonts (Inter & Outfit)
- Schema.org JSON-LD para SEO

## 📦 Despliegue

### Requisitos Previos

- Servidor web (Apache, Nginx, o hosting estático)
- Soporte para HTTPS (recomendado)

### Instrucciones de Despliegue

1. **Subir archivos al servidor**:
   ```bash
   # Copiar todos los archivos HTML al directorio público del servidor
   scp *.html usuario@servidor:/var/www/html/
   scp robots.txt sitemap.xml usuario@servidor:/var/www/html/
   ```

2. **Configurar dominio**:
   - Apuntar el dominio `servicioautomotrizmartinez.com` al servidor
   - Configurar certificado SSL/TLS

3. **Verificar funcionamiento**:
   - Acceder a https://servicioautomotrizmartinez.com/
   - Verificar formulario de contacto
   - Probar responsividad en diferentes dispositivos

### Despliegue en Servicios Cloud

#### GitHub Pages
```bash
# Habilitar GitHub Pages en Settings > Pages
# Seleccionar rama main y directorio root
```

#### Netlify
```bash
# Conectar repositorio
# Deploy automático desde la rama main
```

#### Vercel
```bash
# Importar proyecto desde GitHub
# Deploy automático en cada commit
```

## 🔧 Desarrollo Local

Para probar localmente:

```bash
# Clonar el repositorio
git clone https://github.com/Barcenas86/landing-pages-Taller-Martinez.git

# Navegar al directorio
cd landing-pages-Taller-Martinez

# Abrir con servidor local (ejemplo con Python)
python3 -m http.server 8000

# Abrir en navegador
# http://localhost:8000
```

## 📊 SEO y Analytics

- **Google Search Console**: Verificar indexación y errores
- **Google Analytics**: (Opcional) Agregar código de tracking
- **Google My Business**: Mantener información actualizada
- **Schema.org**: Markup de negocio local implementado

## 📞 Información de Contacto

- **Teléfono**: +52 449 568 9068
- **WhatsApp**: +52 449 568 9068
- **Ubicación**: Aguascalientes, México
- **Coordenadas**: 21.8536506, -102.2608863

## ✅ Checklist de Producción

- [x] HTML validado y bien formado
- [x] Sin errores de consola
- [x] Todas las imágenes con atributos alt
- [x] Meta tags completos (SEO, OG, Twitter Cards)
- [x] Favicon configurado
- [x] Schema.org JSON-LD implementado
- [x] Enlaces HTTPS
- [x] Diseño responsive
- [x] .gitignore configurado
- [x] robots.txt presente
- [x] sitemap.xml presente
- [x] Página 404 personalizada

## 📝 Mantenimiento

### Actualizar Información

1. **Modificar horarios**: Editar la sección de Schema.org en `<head>`
2. **Cambiar teléfono**: Buscar y reemplazar el número en los archivos HTML
3. **Actualizar servicios**: Editar la sección "Servicios" en el HTML
4. **Nuevas imágenes**: Reemplazar URLs de Google Photos/CDN

### Mejoras Futuras

- [ ] Implementar sistema de backend para formulario de contacto
- [ ] Agregar galería de trabajos realizados
- [ ] Blog de consejos automotrices
- [ ] Sistema de reservas online
- [ ] Integración con CRM

## 📄 Licencia

© 2023-2026 Servicio Automotriz Martínez. Todos los derechos reservados.

## 🤝 Contribuciones

Este es un proyecto privado. Para cambios o sugerencias, contactar al equipo de desarrollo.

---

**Última actualización**: Febrero 2026
