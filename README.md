# 📊 SISTEMA DE REGISTRO DE TURNOS - EDITORIAL BINOMIO

![Version](https://img.shields.io/badge/version-2.5.0-blue)
![Firebase](https://img.shields.io/badge/Firebase-Integrado-orange)
![License](https://img.shields.io/badge/license-Private-red)
![Status](https://img.shields.io/badge/status-Producción-brightgreen)

---

## 📋 DESCRIPCIÓN

Sistema web **multi-usuario** para el registro y control de turnos laborales (mañana/tarde) con **almacenamiento en la nube (Firebase)** y **guardado automático en carpeta local**. Diseñado específicamente para la **Editorial Binomio**, incluye **animaciones automáticas de festividades bolivianas** y un potente **panel de desarrollador con editor en tiempo real**.

---

## ✨ CARACTERÍSTICAS PRINCIPALES

### 🔐 SISTEMA DE USUARIOS
- ✅ Selección y creación de usuarios
- ✅ Persistencia en localStorage
- ✅ Cambio rápido entre usuarios

### ☁️ ALMACENAMIENTO EN NUBE
- ✅ Autenticación con Google
- ✅ Firestore en tiempo real
- ✅ Sincronización automática
- ✅ Backup automático

### 📅 REGISTRO DE TURNOS
- ✅ Entrada/Salida - Turno Mañana
- ✅ Entrada/Salida - Turno Tarde
- ✅ Cálculo automático de horas
- ✅ Salario por hora configurable
- ✅ Cálculo de pago en tiempo real
- ✅ Notificación vía WhatsApp
- ✅ Detección de días festivos y domingos

### 💾 GUARDADO AUTOMÁTICO EN CARPETA LOCAL
- ✅ File System Access API (Chrome/Edge)
- ✅ Sin intervención del usuario (solo 1er permiso)
- ✅ Backup completo mensual

### 🎉 FESTIVIDADES BOLIVIANAS AUTOMÁTICAS
- ✅ Carnaval de Oruro
- ✅ Día del Mar
- ✅ Día de la Independencia
- ✅ Día de los Difuntos
- ✅ San Juan
- ✅ Navidad y Año Nuevo
- ✅ Viernes Santo
- ✅ Corpus Christi
- ✅ Animaciones con partículas
- ✅ Detección automática por fecha

### 📊 TABLA DE REGISTROS
- ✅ Días completos del mes (1 al 31)
- ✅ Filtro dinámico por mes
- ✅ Resaltado de domingos
- ✅ Totales de horas y pagos
- ✅ Actualización en tiempo real

### 🔧 PANEL DE DESARROLLADOR
- ✅ Editor de código en vivo
- ✅ Implementación de mejoras en tiempo real
- ✅ Persistencia de mejoras
- ✅ Restauración del sistema
- ✅ Feedback visual inmediato

### 📁 EXPORTACIÓN/IMPORTACIÓN
- ✅ Exportar a JSON (mes completo)
- ✅ Importar desde JSON
- ✅ Backup completo del sistema
- ✅ Migración entre dispositivos

---

## 🛠️ TECNOLOGÍAS UTILIZADAS

| Tecnología | Versión | Uso |
|------------|---------|-----|
| HTML5 | - | Estructura semántica |
| CSS3 | - | Estilos y animaciones |
| JavaScript ES6+ | - | Lógica del sistema |
| Firebase | 10.7.1 | Autenticación + Firestore |
| Google Fonts | - | Roboto, Playfair Display |
| Font Awesome | 6.4.0 | Iconografía |
| SheetJS | 0.18.5 | Exportación Excel (respaldo) |

---

## ⚙️ CONFIGURACIÓN DE FIREBASE

```javascript
// ⚠️ IMPORTANTE: Reemplazar con tus propias credenciales
const firebaseConfig = {
    apiKey: "AIzaSyDREED85Ig_NLyLEMzLtjRLwrYPZn1Em0g",
    authDomain: "registro-binomio.firebaseapp.com",
    projectId: "registro-binomio",
    storageBucket: "registro-binomio.firebasestorage.app",
    messagingSenderId: "1005145229027",
    appId: "1:1005145229027:web:e8f6a5c7027d33ed7727d6",
    measurementId: "G-TRYZPKQG0J"
};

