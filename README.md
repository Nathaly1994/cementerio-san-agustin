# Sistema de Gestión Cementerio San Agustín - La Concordia

Sistema integral con inteligencia artificial para la gestión automatizada de pagos, reservas y servicios del Cementerio Parroquial San Agustín en La Concordia, Santo Domingo.

## 📊 Datos del Proyecto

- **Población objetivo:** 51,386 usuarios registrados
- **Investigación:** 165 encuestados (99% confianza, 10% margen error)
- **Aceptación del sistema:** 85-95% aprobación
- **Tecnología principal:** React Native + Expo SDK 53 + Gemini AI

## 🎯 Problemática Identificada

El cementerio enfrentaba serios desafíos operativos:
- ❌ Sin herramientas digitales
- ❌ Personal con baja competencia tecnológica  
- ❌ Procesos manuales lentos y poco confiables
- ❌ Pérdida de documentos físicos
- ❌ Sin consultas online (solo presenciales)

## ✅ Solución Implementada

### Funcionalidades Principales

**🤖 Asistente Virtual con IA (90% aceptación)**
- Consultas 24/7 sobre disponibilidad de bóvedas
- Información sobre precios, ubicaciones y características
- Respuestas automáticas basadas en Gemini AI
- Procesamiento de lenguaje natural

**📱 Gestión Automatizada de Reservas (88% aceptación)**
- Verificación de disponibilidad en tiempo real
- Proceso de reserva completamente automático
- Confirmación inmediata de reservas
- Modificación y cancelación automática

**💳 Sistema de Pagos Digitales**
- Procesamiento automático de pagos
- Múltiples métodos de pago
- Generación de recibos digitales
- Historial de transacciones

**📊 Panel de Gestión Administrativa**
- Análisis predictivo con IA
- Reportes automatizados
- Gestión de inventario de bóvedas
- Control de estados (disponible/reservada/ocupada)

## 🛠️ Tecnologías Utilizadas

- **Frontend:** React Native + Expo SDK 53
- **Lenguaje:** TypeScript (85.8%), JavaScript (14.2%)
- **IA:** Google Gemini (OpenAI integration)
- **Backend:** Node.js API (cementerio-api/)
- **Base de datos:** MySQL + phpMyAdmin
- **IDE:** Android Studio

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js v18+
- Expo CLI
- Android Studio (opcional)

### Instalación
```bash
# Clonar repositorio
git clone https://github.com/Nathaly1994/cementerio-san-agustin.git
cd cementerio-san-agustin

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env
# Editar .env con tus API keys

# Ejecutar aplicación
npx expo start
