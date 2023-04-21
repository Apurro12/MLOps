# aprendizaje_maquina_II
Full E2E model implementation using mlflow

# Las migrations estan en alembic
https://alembic.sqlalchemy.org/en/latest/

Para correr las migrations hay que cambiar el file migrations/sqlalchemy.url
y poner el conection string del postgres donde queramos correr las migrations

* Subir migration: alembic upgrade head
* roolback migration: alembic downgrade base
