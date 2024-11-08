# pkgbox
Exportacion - Importacion

Control y Tracking de documentos, paquetes y cajas.

# Instalando el Sistema

El proyecto atendera la necesidad de aplicar controles y tracking de los documentos, paqueteria y cajas que son exportadas e importadas.

# Instaladores

| Nombre                   | Instalador                                                                                                                                                                                                                     |
|:-------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `Compilador`             | [Python3](https://www.python.org/downloads/release/python-396/ "Python3")                                                                                                                                                      |
| `IDE de programación`    | [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code"), [Sublime Text](https://www.sublimetext.com/ "Sublime Text") |
| `Motor de base de datos` | [Sqlite Studio](https://github.com/pawelsalawa/sqlitestudio/releases "Sqlite Studio"), [PostgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads "PostgreSQL"), [MariaDB](https://mariadb.org "MariaDB") |
| `DevOps` | [Docker](https://www.docker.com "Docker"), [DockerHub](https://hub.docker.com "DockerHub") |


# Pasos de instalación

##### 1) Descomprimir el proyecto en el workspace de desarrollo

```bash
cd /path/devops

git clone [pkgbox](https://github.com/kayrosama/pkgbox.git "pkgbox")

```

##### 2) Preparamos el entorno virtual, instalamos las librerias del proyecto e inicializamos la aplicacion

Para Linux:

```bash
apt-get update && apt-get full-upgrade -y
apt-get install -f -y python3-pip python3-venv 
.
cd /path/devops/pkgbox
python3 -m venv .venv
source .venv/bin/active
python3 -m pip install -r requirements.txt
.
python3 manage.py runserver
. o
python manage.py runserver 0:8000 
. o
python manage.py runserver 0.0.0.0:8000
.
```

##### 3) Instalando y configurando el complemento de [weasyprint](https://weasyprint.org/ "weasyprint")

Linux - Instalar las [librerias](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#linux "librerias") correspondientes a la distribución que tenga instalado en su computador y/o imagen Docker.

##### 4) Activando el entorno virtual del proyecto

Para Linux:

```bash
.
.
.
```

##### 6) Creando tablas del sistema

Para Linux:

```bash
.
.
.
```

##### 9) Iniciando el servicio

Para Linux:

```bash
.
.
.
```

------------
#####10) Paso 1: Crear un proyecto Django

Para Linux:

```bash
.
.
.
```

#####11) Creando tablas del sistema

#  Gracias 

**Colaboradores**

gschama

***KSM***

