# Andamios ARCOHN - Panel de Transacciones Financieras

Dashboard profesional para visualizar, filtrar y exportar transacciones financieras con gráficos interactivos.

## Características

- 🔐 Acceso protegido con contraseña
- 📊 Gráficos de donnut personalizables (3 vistas diferentes)
- 📅 Filtrado por rango de fechas
- 🎨 Diseño corporativo con colores de Nautilus
- 💾 Exportación a Excel, PDF e impresión
- 📈 Estadísticas en tiempo real
- 📝 Detalles de transacciones con notas

## Acceso

**Contraseña:** P2336grupoSTG

## Instrucciones de Despliegue en Vercel

### Método 1: Con Git Hub (Recomendado)

1. Crea un repositorio en GitHub con estos archivos
2. Ve a https://vercel.com
3. Haz clic en "New Project"
4. Conecta tu repositorio de GitHub
5. Vercel deployará automáticamente

### Método 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

### Método 3: Despliegue Manual

1. Ve a https://vercel.com/new
2. Sube el archivo `index.html`
3. ¡Listo!

## Archivos Incluidos

- `index.html` - Aplicación completa (HTML, CSS, JavaScript)
- `package.json` - Configuración del proyecto
- `README.md` - Este archivo

## Tecnologías Utilizadas

- Chart.js - Gráficos
- SheetJS (XLSX) - Exportación a Excel
- html2pdf - Exportación a PDF
- Vanilla JavaScript

## Estructura de Datos

Las transacciones incluyen:
- Fecha (YYYY-MM-DD)
- Monto (en Lempiras)
- Tipo (Manual, Reembolso, Transferencia)
- Método (Tarjeta Crédito, Depósito, etc.)
- Notas explicativas

## Funciones de Exportación

- **Excel:** Descarga datos filtrados en formato .xlsx
- **PDF:** Genera reporte en PDF de la tabla de transacciones
- **Imprimir:** Imprime directamente desde el navegador

## Gráficos Disponibles

1. **Método de Pago** - Distribución por método de pago
2. **Tipo de Transacción** - Pagos vs Reembolsos
3. **Período** - Distribución por mes/año

## Seguridad

- Contraseña protegida en cliente
- Sin almacenamiento externo de datos
- Datos manejados localmente en el navegador
- HTTPS automático en Vercel

## Personalización

Para cambiar transacciones, edita el array `transactions` en el archivo HTML.

## Soporte

Para reportar problemas o solicitar cambios, contacta a Gabu.

---

**Andamios ARCOHN** © 2026
