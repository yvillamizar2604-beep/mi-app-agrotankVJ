# AGROTANK VI - App de Gestión Agrícola y Lechera

App web en Flask para registrar usuarios, cultivos (fresa, arándanos, etc.), clima, lotes, producción agrícola/lechera y generar reportes con gráficos.

## Funcionalidades
- Autenticación con roles (Admin, Operario, Producción).
- Registro de parámetros hidropónicos con alertas de rangos.
- Gestión de lotes y trazabilidad.
- Reportes con correlaciones y exports (Excel/PDF placeholders).

## Instalación Local
1. Clona el repo: `git clone https://github.com/tuusuario/mi-app-agrotank.git`
2. Entra: `cd mi-app-agrotank`
3. Instala: `pip install -r requirements.txt`
4. Ejecuta: `python app.py`
5. Abre: http://127.0.0.1:5000
- Usuario: admin | Pass: admin123

## Despliegue
- Hostinger cPanel: Crea Python App > Sube archivos > pip install requirements.
- Heroku/Vercel: Usa Procfile con `web: gunicorn app:app`.

## Estructura
- `app.py`: Rutas y lógica.
- `models.py`: Modelos SQLAlchemy.
- `templates/`: HTML con Bootstrap.

## Licencia
MIT
