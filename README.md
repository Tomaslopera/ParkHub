# Park Hub
ParkHub es un proyecto de reservas de parqueaderos que permite registrar usuarios, iniciar sesión, cambiar contraseña, realizar una reserva y ver el historial de reservas. El proyecto posee un diseño intuitivo desarrollado en react y para el almacenamiento de la base de datos se diseñó una API mediante FastAPI utilizando la librería SQLAlchemy para la conexión con la base de datos en MySQL.

**Integrantes:** Tomás Lopera, Pedro Sierra, David Betancur

**Development**
  
  > BACKEND: Tomás Lopera
  
  > FULL-STACK: Tomás Lopera
  
  > FRONTEND: Pedro Sierra

## Ejecucutar proyecto (Desarrollo)
**Frontend**

    cd frontend

> Descargar librerias:

    npm i

> Levantar entorno de desarrollo:

    npm run dev

**Backend**

    cd backend

> Descargar librerias:

    pip install fastapi
    pip install uvicorn
    pip install sqlalchemy
    pip instal pydantic
    pip install bcrypt
    pip install passlib
    pip install pymysql

> Levantar entorno de desarrollo:

    uvicorn app:app --reload

**MySQL**
> Para el proyecto se utilizó MySQL Workbench para la visualización de las tablas de la Base de Datos

    create database PARKHUB;
