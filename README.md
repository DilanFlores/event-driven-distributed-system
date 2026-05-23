# 🚀 Sistema Distribuido Basado en Eventos

Sistema distribuido orientado al procesamiento, monitoreo y visualización de datos en tiempo real mediante una arquitectura moderna, desacoplada y escalable.

---

## 📌 Descripción

Este proyecto implementa una arquitectura distribuida basada en eventos utilizando **Apache Kafka** como sistema central de mensajería para permitir la comunicación asíncrona entre múltiples servicios.

La solución integra servicios desarrollados en:

- .NET
- Node.js (Express)
- Python

Además, incorpora funcionalidades como:

- Procesamiento distribuido de datos
- Tareas en segundo plano con Hangfire
- Generación de archivos PDF
- Integración con SQL Server (AdventureWorks)
- Visualización y monitoreo mediante Power BI

---

# ⚙️ Tecnologías Utilizadas

## Backend
- .NET
- Node.js + Express
- Python

## Mensajería y Procesamiento
- Apache Kafka
- Hangfire

## Base de Datos
- SQL Server
- AdventureWorks

## Monitoreo y Visualización
- Power BI

---

# ✨ Características

- ✅ Arquitectura basada en eventos
- ✅ Procesamiento distribuido de datos
- ✅ Comunicación asíncrona entre servicios
- ✅ Streaming de eventos mediante Kafka
- ✅ Tareas en segundo plano con Hangfire
- ✅ Generación automática de reportes PDF
- ✅ Integración con SQL Server
- ✅ Dashboards y monitoreo con Power BI
- ✅ Arquitectura multi-servicio

---

# 📊 Flujo General del Sistema

1. Los servicios productores generan eventos.
2. Apache Kafka distribuye los mensajes de forma asíncrona.
3. Los servicios consumidores procesan los eventos recibidos.
4. La información se almacena en SQL Server.
5. Power BI visualiza métricas y datos del sistema.
6. Las tareas automatizadas y reportes se ejecutan en segundo plano.

---

# 🎯 Objetivos del Proyecto

- Implementar una arquitectura distribuida escalable.
- Aplicar patrones de comunicación asíncrona.
- Integrar múltiples tecnologías backend.
- Mejorar el desacoplamiento y escalabilidad del sistema.
- Centralizar el monitoreo y procesamiento de datos.

```
