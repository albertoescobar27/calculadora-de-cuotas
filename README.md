# 🏡 Calculadora de Cuotas de Terrenos

Una aplicación web interactiva y completa para calcular las cuotas mensuales de financiamiento de terrenos, diseñada para facilitar la gestión de ventas y la información para los clientes. Desarrollada con HTML, CSS y JavaScript puro, esta herramienta ofrece una experiencia de usuario intuitiva y funcionalidades avanzadas para un análisis financiero detallado.

## ✨ Características Principales

### 💰 Cálculos Financieros
- **Cálculo de Precio Total:** Determina el precio de contado del terreno multiplicando el precio por metro cuadrado por los metros cuadrados del terreno
- **Gestión de Prima/Adelanto:** Permite ingresar un valor de prima o adelanto que se resta del precio total del terreno
- **Cálculo de Cuotas Mensuales:** Calcula la cuota mensual a pagar en función del tiempo de financiamiento en años
- **Tasa de Interés Anual Opcional:** Incluye la opción de aplicar una tasa de interés anual para cálculos más realistas y detallados

### 🏷️ Condiciones Especiales del Lote
- Define descripciones personalizadas para condiciones específicas (ej. "Lote esquinero", "Vista al parque", "Descuento por pronto pago")
- Asigna un valor monetario a estas condiciones
- Elige si el valor de la condición se suma o se resta del precio total del terreno

### 📊 Reportes y Análisis
- **Resumen Detallado del Financiamiento:** Muestra un desglose claro de todos los valores calculados
- **Tabla de Amortización Completa:** Genera una tabla detallada que muestra el desglose de cada cuota mensual (capital e interés) y el saldo pendiente
- **Exportación a Excel (XLSX):** Permite descargar un reporte completo con:
  - Una hoja con el resumen detallado del financiamiento
  - Una hoja con la tabla de amortización completa para todos los meses del préstamo

### 🎨 Experiencia de Usuario
- **Interfaz Moderna y Responsiva:** Diseño adaptable a diferentes tamaños de pantalla
- **Validación en Tiempo Real:** Asegura que los datos ingresados sean correctos y coherentes
- **Formato de Moneda Local:** Los valores se formatean automáticamente a Lempiras Hondureñas (Lps)
- **Animaciones Suaves:** Transiciones y efectos visuales para una mejor experiencia

## 📋 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Conexión a internet (para cargar la librería SheetJS)

## 🛠️ Instalación y Uso

### Opción 1: Uso Directo
1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/calculadora-cuotas-terrenos.git
