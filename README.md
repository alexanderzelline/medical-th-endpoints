# medical-th-endpoints

Colección de Bruno para la API REST de la plataforma Clínica Medical TH.

## Requisitos

- [Bruno](https://www.usebruno.com/) v1.x
- Servidor local corriendo en `http://localhost:8000`

## Uso

1. Abre Bruno
2. Clic en **Open Collection**
3. Selecciona esta carpeta
4. En el selector de environment (esquina superior derecha) elige **local**

## Módulos

| Módulo | Endpoints |
|---|---|
| `notificaciones/smtp` | Listar, Detalle |
| `notificaciones/plantillas` | Listar, Detalle, Crear, Editar, Reemplazar, Eliminar |
| `notificaciones/campanas` | Listar, Detalle, Progreso |

## Variables de entorno

| Variable | Valor por defecto |
|---|---|
| `base_url` | `http://localhost:8000` |
