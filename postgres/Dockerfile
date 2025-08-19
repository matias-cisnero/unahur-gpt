# 1. Partimos de la imagen oficial y muy estable de PostgreSQL 16
FROM postgres:16-bookworm

# 2. Actualizamos los repositorios e instalamos la extensión pgvector
#    El paquete se llama así para la versión 16 de Postgres
RUN apt-get update && apt-get install -y postgresql-16-pgvector

# 3. (Opcional) Copiamos un script de inicialización si fuera necesario
#    Por ahora no lo necesitamos, pero es bueno saber que se puede.