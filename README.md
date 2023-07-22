- Nombre de la app: gestor_app
- Ver requirements.txt para replicar requerimientos de dependencias.
- URL al montar servidor local: http://127.0.0.1:8000/gestor_app
- Para SPRINT, se adjunta en el raíz del proyecto archivo dbsprint.pgsql
- admin:admin y rodrigolfh:contraseña
- Si no se exporta y se parte con base desde cero, ojo que hay que crear un grupo de usuarios en la db llamado 'usuario_normal'.
- Configuración de la base:
  DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'postgres',
        'USER': 'admin',
        'PASSWORD': 'admin',
        'HOST': 'localhost',
        'PORT': '5433'
    }
}




