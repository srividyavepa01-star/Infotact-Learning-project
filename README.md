# Infotact-Learning-project
My training projecct repository 
from sqlalchemy import create_engine

engine = create_engine(
    "postgresql://USERNAME:PASSWORD@HOST:5432/postgres"
)

connection = engine.connect()
print("Connected successfully!")
connection.close()
