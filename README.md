# Hospital-RL
## Instalación
Pasos a seguir:
1. Entrar en el siguiente link e instalar Python 3.9.13
- https://www.python.org/downloads/windows/
Primer link (Windows installer (64-bit))


2. Ejecutar lo descargado y añadirlo al PATH


3. Comprobar versiones instaladas
- > py -0
Tiene que salir la 3.9

4. Ir al sitio donde quieras crear el environment y crearlo:
- > py -3.9 -m venv nombre_venv


5. Activar el environment
- > nombre_venv\Scripts\activate


6. Instalar las dependencias/librerias
- > pip install -r requirements.txt

7. Descomprimir .zip

8. Comprobar ml-agents
- > mlagents-learn config/doctor_config.yaml --run-id=DoctorV2 --force


