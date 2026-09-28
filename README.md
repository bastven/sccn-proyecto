# sccn-proyecto
Prototipo SCCN — Sistema de coordinación ante catástrofes

# SCCN — Sistema de Centralización y Coordinación ante Catástrofes Naturales

Prototipo funcional de software para la coordinación operativa entre un 
Puesto de Mando Central y brigadas en terreno durante catástrofes naturales.

## 🎯 Problema que resuelve
- Falta de visibilidad unificada del mando sobre brigadas y zonas de riesgo.
- Pérdida de reportes cuando cae la señal en terreno.
- Ausencia de canal inmediato de emergencia (S.O.S.).

## 🚀 Demo
Abre el archivo: `src/SCCN_ProyectoCatastrofes.html` en cualquier navegador.

**Credenciales de prueba:**
- Comandante: `comandante` / `mando123`
- Brigadista: `brigadista` / `campo123`

## 🛠️ Tecnologías aplicadas
- **SaaS:** Tailwind CSS, Leaflet, Google Fonts (vía CDN)
- **IaaS (arquitectura objetivo):** AWS EC2 para backend Node.js + WebSocket
- **DBaaS (arquitectura objetivo):** PostgreSQL + PostGIS gestionado
- **Seguridad:** OWASP A03 (Injection), ISO/IEC 27001, JWT simulado

## 📋 Cumplimiento normativo
- Ley 19.628 (Protección de datos personales, Chile)
- Ley 19.223 (Delitos informáticos, Chile)
- Ley 21.459 (Actualización delitos informáticos, 2022)
- Ley 21.663 (Ley Marco de Ciberseguridad, 2024)
- ISO/IEC 27001
- OWASP Top 10 — A03:2021

## 📁 Estructura del repositorio
- `docs/` — Informe técnico y diagramas UML
- `src/` — Código fuente del prototipo
- `capturas/` — Evidencia visual
- `testing/` — Matriz de pruebas T01-T17

## 📊 Testing
17 casos de prueba manuales cubriendo autenticación, seguridad, offline-first 
y botón S.O.S. Ver `testing/resultados-testing.md`.

## 👤 Autor
[Ayleen Gonzalez]
[Bastian Venegas]
[ayleen.gonzalez07@inacapmail.cl]
[bastian.venegas10@inacapmail.cl]
