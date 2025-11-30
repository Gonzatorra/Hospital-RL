# Hospital-RL
## Instalación
Pasos a seguir:
Entrar en el siguiente link e instalar Python 3.9.13
https://www.python.org/downloads/windows/
Primer link (Windows installer (64-bit))


Ejecutar lo descargado y añadirlo al PATH


Comprobar versiones instaladas
py -0
Tiene que salir la 3.9

Ir al sitio donde quieras crear el environment y crearlo:
py -3.9 -m venv nombre_venv


Activar el environment
nombre_venv\Scripts\activate


Instalar las dependencias/librerias
pip install -r requirements.txt

Descomprimir .zip

Comprobar ml-agents

mlagents-learn config/doctor_config.yaml --run-id=DoctorV2 --force


