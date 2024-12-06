## 👨‍💻 Instalación 

Sigue estos pasos para configurar y ejecutar el proyecto **be-loved-web** en tu entorno local.

### Pre-requisitos

Asegúrate de tener instalado lo siguiente en tu máquina:

- [Python](https://www.python.org/) (versión 3.13.x o superior)
- [Git](https://git-scm.com/)

### Pasos a seguir

Primero, abre una terminal o cmd (windows).

* Instalar virtualenv (Manejador de 'Virtual Environments')

```bash
pip install virtualenv
```

* clona el repositorio del proyecto desde GitHub.

```bash
git clone https://github.com/Volkergz/Farmapp_website.git
```

*  Accede al directorio del proyecto clonado

```bash
cd AutosDelMar
```

* Cree un ambiente virtual

```bash
virtualenv <nombre-ambiente>
```

* Active el ambiente virtual

```bash
.\<nombre-ambiente>\Scripts\activate
```


* Instale las dependecias del proyecto

```bash
pip install -r requirements.txt
```

* Inicie el servidor de desarrollo
```bash
py manage.py runserver
```
#### El servidor se ejecutará en http://localhost:8000. Abre esta URL en tu navegador para ver el proyecto en acción.
