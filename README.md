# Wansoft Dashboard 📊

> Dashboard administrativo para **Wansoft by Clip** — Sistema integral de gestión empresarial.

## 🎯 Descripción

**Wansoft** es una plataforma de gestión empresarial todo en uno que centraliza:

- 📋 **Reportes** — Análisis detallado de tu negocio
- 💲 **Ingresos** — Seguimiento de ventas y ganancias
- 💸 **Egresos** — Control de gastos y costos operacionales
- 📦 **Inventario** — Gestión de stock e inventarios
- 🛒 **Ecommerce** — Tienda en línea integrada
- 🖥️ **Punto de Venta** — Sistema POS para ventas en físico
- 👥 **Administración** — Gestión de usuarios y permisos
- ⚙️ **Configuración** — Personalización del sistema
- 📄 **Facturas** — Emisión y gestión de facturas digitales
- </> **Liberaciones** — Control de versiones y actualizaciones

## ✨ Características

### Dashboard Principal
- **KPIs Principales**: Visualiza de un vistazo:
  - Estado de licencia
  - Órdenes abiertas
  - Última sincronización
  - Última venta recibida

### Gráficos de Análisis
- **Reporte de Utilidad Marginal**: Visualización interactiva con Chart.js
  - Ventas Netas (en azul)
  - Costos (en rojo)
  - Margen (en verde)
  - Período: Mayo 2025 - Mayo 2026

### Sección "Por Inventariar"
Acceso rápido a:
- Órdenes de compra
- Notas de entrada
- Devoluciones
- Ventas pendientes

### Interfaz Responsiva
- **Sidebar izquierdo**: Navegación principal y menú
- **Rail derecho**: Acciones rápidas (búsqueda, home, refresh, etc.)
- **Diseño adaptable**: Funciona en desktop, tablet y mobile

## 🤖 Bot Conversacional

Integración de **ElevenLabs Conversational AI** para soporte en tiempo real:
```html
<elevenlabs-convai agent-id="agent_7801kqaxextffd2r1e8g4yj5fe5c"></elevenlabs-convai>
```

El bot está disponible en la esquina inferior derecha para asistencia inmediata.

## 🛠️ Tecnologías Utilizadas

- **HTML5** — Estructura semántica
- **CSS3** — Diseño moderno con CSS variables
- **Chart.js** — Gráficos interactivos
- **Open Sans** — Tipografía (Google Fonts)
- **ElevenLabs Convai** — IA conversacional

## 📱 Diseño Responsivo

Breakpoints:
- **Desktop**: 1100px+ (4 columnas en grillas)
- **Tablet**: 700px - 1100px (2 columnas)
- **Mobile**: < 700px (1 columna, sidebar oculto)

## 🎨 Paleta de Colores

```css
--sidebar: #2c3e7b          /* Azul oscuro principal */
--bg: #f5f6f8               /* Gris claro de fondo */
--card: #ffffff             /* Blanco para tarjetas */
--blue: #4a90d9             /* Azul para datos */
--red: #d9534f              /* Rojo para alertas */
--green: #5cb85c            /* Verde para márgenes */
--yellow: #f0ad4e           /* Amarillo para estados */
```

## 🚀 Cómo Usar

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/andremoura-sketch/waldowansoft.git
   cd waldowansoft
   ```

2. **Abrir en navegador**
   ```bash
   # Opción 1: Abrir directamente el archivo
   open index.html
   
   # Opción 2: Usar un servidor local
   python -m http.server 8000
   # Luego acceder a: http://localhost:8000
   ```

3. **Ver el dashboard**
   - Explora los KPIs principales
   - Interactúa con el gráfico de utilidad marginal
   - Accede a secciones de inventario
   - Usa el bot conversacional para soporte

## 📊 Datos de Ejemplo

El dashboard incluye datos de demostración:
- **Licencia**: VIGENTE
- **Órdenes abiertas**: $710.00 (2 órdenes)
- **Última sincronización**: MÁS DE 48 HORAS (alerta)
- **Última venta**: 2026-05-14 14:11:12

## 🔧 Personalización

### Cambiar colores
Edita las variables CSS en la sección `:root`:
```css
:root {
  --sidebar: #tu-color-aqui;
  --blue: #tu-azul-aqui;
  /* ... etc */
}
```

### Modificar datos
Actualiza los valores en:
- Los KPI cards (líneas 170-190)
- El gráfico (línea 270+)
- Las secciones de inventario (líneas 210-225)

### Agregar/eliminar menús
Modifica la lista en el sidebar (líneas 100-111):
```html
<li><a href="#"><span class="icon">🆕</span> Mi nuevo menú</a></li>
```

## ��� Contribuciones

Los cambios y mejoras son bienvenidos. Por favor:
1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**André Moura**  
📧 andre.moura@payclip.com  
🔗 [GitHub](https://github.com/andremoura-sketch)  
Parte del ecosistema **Clip**

## 🆘 Soporte

¿Preguntas o problemas? Usa el bot conversacional integrado en el dashboard o abre un issue en GitHub.

---

**Hecha con ❤️ para equipos que envían** — *Wansoft by Clip*
