# Manual del Usuario por Rol

**Sistema de Gestión Académica 2026**
Liceo Gastronomía y Turismo de Quilpué
SLEP Marga Marga

---

## Tabla de Contenidos

1. [Rol: Administrador](#1-rol-administrador)
2. [Rol: Equipo Directivo](#2-rol-equipo-directivo)
3. [Rol: Docente](#3-rol-docente)
4. [Rol: Inspector](#4-rol-inspector)
5. [Rol: Equipo PIE](#5-rol-equipo-pie)
6. [Rol: Paradocente](#6-rol-paradocente)

---

## 1. Rol: Administrador

### Acceso total al sistema

| Módulo | Permisos |
|---|---|
| Notas | Lectura y escritura |
| Asistencia | Lectura y escritura |
| Alumnos | Lectura y escritura |
| Certificados | Lectura y escritura |
| Citaciones | Lectura y escritura |
| Hoja de Vida | Lectura y escritura |
| Estadísticas | Lectura y escritura |
| Usuarios | Lectura y escritura |

### Funcionalidades:

#### Gestión de Usuarios
- Crear nuevos usuarios
- Modificar permisos de usuarios existentes
- Eliminar usuarios
- Asignar cursos y asignaturas a docentes
- Cambiar contraseñas

#### Gestión de Alumnos
- Agregar alumnos manualmente
- Importar alumnos desde CSV
- Retirar/reincorporar alumnos
- Ver y editar hoja de vida (apoderados, condiciones, PIE)

#### Notas y Asistencia
- Ingresar y modificar notas de todos los cursos
- Ver y modificar asistencia de todos los cursos
- Generar certificados de notas

#### Sincronización
- Subir datos a Google Sheets
- Descargar datos desde Google Sheets
- Exportar backup local (JSON)
- Importar backup local (JSON)

---

## 2. Rol: Equipo Directivo

| Módulo | Permisos |
|---|---|
| Notas | Solo lectura |
| Asistencia | Solo lectura |
| Alumnos | Lectura y escritura |
| Certificados | Lectura y escritura |
| Citaciones | Lectura y escritura |
| Hoja de Vida | Lectura y escritura |
| Diagnóstico PIE | Solo lectura |
| Informes PIE | Solo lectura |
| Estadísticas | Lectura y escritura |
| Usuarios | Sin acceso |

### Funcionalidades:

#### Certificados
- Generar certificados de notas individuales
- Generar certificados de todo el curso
- Imprimir certificados

#### Citaciones
- Crear citaciones a apoderados
- Modificar citaciones existentes
- Eliminar citaciones
- Filtrar por curso y departamento

#### Estadísticas
- Ver estadísticas generales del curso
- Ver estadísticas de asistencia
- Ver estadísticas de rendimiento
- Imprimir informes

#### Alumnos
- Ver lista de alumnos
- Agregar nuevos alumnos
- Importar desde CSV
- Retirar/reincorporar alumnos

---

## 3. Rol: Docente

| Módulo | Permisos |
|---|---|
| Notas | Solo lectura |
| Asistencia | Solo lectura |
| Alumnos | Sin acceso |
| Certificados | Sin acceso |
| Citaciones | Sin acceso |
| Hoja de Vida | Sin acceso |
| Diagnóstico PIE | Sin acceso |
| Informes PIE | Sin acceso |
| Estadísticas | Solo lectura |
| Usuarios | Sin acceso |

### Funcionalidades:

#### Notas (Solo Lectura)
- Ver notas de sus cursos asignados
- Ver notas por asignatura
- Ver promedios semestrales y anuales

#### Asistencia (Solo Lectura)
- Ver asistencia de sus cursos
- Ver estadísticas de asistencia
- Ver alertas de inasistencia (< 85%)

#### Estadísticas (Solo Lectura)
- Ver estadísticas de sus cursos
- Ver comparación entre asignaturas
- Ver distribución de notas

### Cursos y Asignaturas Asignadas:
El docente solo puede ver los cursos y asignaturas que el Administrador le haya asignado.

---

## 4. Rol: Inspector

| Módulo | Permisos |
|---|---|
| Notas | Solo lectura |
| Asistencia | Solo lectura |
| Alumnos | Lectura y escritura |
| Certificados | Lectura y escritura |
| Citaciones | Lectura y escritura |
| Hoja de Vida | Lectura y escritura |
| Diagnóstico PIE | Sin acceso |
| Informes PIE | Sin acceso |
| Estadísticas | Lectura y escritura |
| Usuarios | Sin acceso |

### Funcionalidades:

#### Alumnos
- Ver lista de alumnos
- Agregar nuevos alumnos
- Importar desde CSV
- Retirar/reincorporar alumnos
- Ver y editar hoja de vida

#### Certificados
- Generar certificados de notas
- Imprimir certificados

#### Citaciones
- Crear citaciones a apoderados
- Modificar citaciones existentes
- Eliminar citaciones

#### Estadísticas
- Ver estadísticas generales
- Ver estadísticas de asistencia
- Imprimir informes

---

## 5. Rol: Equipo PIE

| Módulo | Permisos |
|---|---|
| Notas | Solo lectura |
| Asistencia | Sin acceso |
| Alumnos | Sin acceso |
| Certificados | Sin acceso |
| Citaciones | Solo lectura |
| Hoja de Vida | Solo lectura |
| Diagnóstico PIE | Lectura y escritura |
| Informes PIE | Lectura y escritura |
| Estadísticas | Solo lectura |
| Usuarios | Sin acceso |

### Funcionalidades:

#### Diagnóstico PIE
- Ingresar diagnósticos de alumnos
- Modificar diagnósticos existentes
- Ver historial de diagnósticos

#### Informes PIE
- Generar informes de alumnos PIE
- Ver informes existentes
- Imprimir informes

#### Notas (Solo Lectura)
- Ver notas de alumnos
- Ver promedios

#### Citaciones (Solo Lectura)
- Ver citaciones existentes
- Filtrar por curso

---

## 6. Rol: Paradocente

| Módulo | Permisos |
|---|---|
| Notas | Sin acceso |
| Asistencia | Solo lectura |
| Alumnos | Sin acceso |
| Certificados | Sin acceso |
| Citaciones | Solo lectura |
| Hoja de Vida | Solo lectura |
| Diagnóstico PIE | Sin acceso |
| Informes PIE | Sin acceso |
| Estadísticas | Solo lectura |
| Usuarios | Sin acceso |

### Funcionalidades:

#### Asistencia (Solo Lectura)
- Ver asistencia de cursos
- Ver estadísticas de asistencia
- Ver alertas de inasistencia

#### Citaciones (Solo Lectura)
- Ver citaciones existentes
- Filtrar por curso

#### Hoja de Vida (Solo Lectura)
- Ver fichas de alumnos
- Ver datos de apoderados
- Ver condiciones especiales

#### Estadísticas (Solo Lectura)
- Ver estadísticas generales
- Ver estadísticas de asistencia

---

## Notas Importantes

### Navegador Recomendado
- Google Chrome o Microsoft Edge (Chromium)
- También funciona en Firefox

### Sincronización
- El sistema sincroniza automáticamente con Google Sheets
- Los datos se guardan en localStorage del navegador
- Se recomienda exportar backups periódicamente

### Soporte
- Contactar al Administrador del sistema para problemas técnicos
- El Administrador puede gestionar usuarios y permisos

---

*Manual generado para SISacad2026LGT v4.0 — Liceo Gastronomía y Turismo de Quilpué 2026*
