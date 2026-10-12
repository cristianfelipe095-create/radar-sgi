# Radar SGI

Radar SGI es una aplicación web para registrar **no conformidades** y hacer seguimiento a sus **planes de acción** dentro de un Sistema de Gestión Integrado (SGI) que trabaja con tres normas:

| Norma | Ámbito |
|---|---|
| **ISO 9001** | Gestión de la calidad |
| **ISO 14001** | Gestión ambiental |
| **ISO 28000** | Gestión de la seguridad en la cadena de suministro |

La idea es simple: que cada hallazgo quede registrado en un solo lugar, con un responsable, una fecha y un plan para cerrarlo, y que el equipo vea de un vistazo qué está pendiente antes de que llegue la auditoría.

> **Estado:** en desarrollo. Por ahora el repositorio tiene la documentación inicial del proyecto; el código de la aplicación aún no está publicado.

## ¿Qué problema resuelve?

En muchos SGI las no conformidades viven en hojas de cálculo, correos y actas separadas por norma. Eso hace difícil saber cuántas hay abiertas, quién las tiene a cargo y cuáles ya vencieron. Radar SGI reúne todo en una sola herramienta y funciona como un "radar" que avisa lo que necesita atención.

## Funcionalidades previstas

- **Registro de no conformidades**: origen (auditoría interna, externa, queja, inspección, etc.), norma y requisito afectado, descripción, evidencia y clasificación (mayor, menor u observación).
- **Análisis de causa**: espacio para documentar la causa raíz (por ejemplo, 5 porqués o diagrama de Ishikawa).
- **Planes de acción**: acciones de corrección, correctivas y preventivas, cada una con responsable, fecha compromiso y estado.
- **Seguimiento y cierre**: verificación de la eficacia de las acciones antes de cerrar la no conformidad.
- **Alertas**: señales para acciones próximas a vencer o vencidas.
- **Tablero**: vista general por norma, proceso, estado y responsable.
- **Preparación de auditorías**: historial y evidencias listas para consultar.

## Flujo de una no conformidad

```
Registro → Análisis de causa → Plan de acción → Ejecución → Verificación de eficacia → Cierre
```

## Metas del proyecto

1. **Centralizar la información del SGI** en un solo lugar.
2. **Detectar a tiempo lo que necesita atención**: acciones vencidas, hallazgos repetidos y riesgos.
3. **Mantener la documentación clara y al día** para preparar auditorías y revisiones sin trabajo de última hora.

Más detalle en [BIENVENIDA.md](BIENVENIDA.md).

## Estructura del repositorio

| Ruta | Contenido |
|---|---|
| `README.md` | Este archivo: descripción general del proyecto |
| `BIENVENIDA.md` | Presentación y metas del proyecto |

A medida que el proyecto avance se sumarán las carpetas `datos/`, `capturas/` y `docs/`, además del código de la aplicación.

## Autor

Cristian Velásquez
