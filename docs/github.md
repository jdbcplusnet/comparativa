# GitHub

## Comparativa de versiones

[Comparativa de versiones](https://github.com/pricing#github-one)

### Version Gratuita

* Repositorios público / privado sin límites.
* Sin límite de colaboradores.
* 2000 acciones por minuto / mes. Sin límite para repositorio público.
* 500 MB de almacenamiento para repositorio privado. Sin límite para repositorio público.
* Soporte de la comunidad.


### Versión Team - 4$ al mes por usuario

* Repositorios público / privado sin límites.
* 3000 acciones por minuto / mes. Sin límite para repositorio público.
* 2GB de almacenamiento para repositoro privado. Sin límite para repositorio público.
* Propietario del código del repositorio. (https://docs.github.com/es/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/about-code-owners)


### Versión Enterprise - 21$ al mes por usuario

* Todo lo que incluye la versión Team.
* Single Sign-on SAML.
* 50.000 acciones por minuto / mes. Sin límite para repositorio público.
* 50GB de almacenamiento para repositorio privado. Sin límite para repositorio público.
* Registro de auditoria.


### Versión GitHub One - Contactar con ventas para precio

* Todo lo que incluye la versión Enterprise
* [Seguridad basada en la comunidad](https://github.com/features/security)
* Métricas con [GitHub Insights](https://github.com/features/insights)
* [Soporte 24/7](https://github.com/premium-support)
* [Aprendizaje continuo](https://lab.github.com) - Permite crear cursos.


## Acciones de GitHub (GitHub Actions)

[Introducción a GitHub Actions](https://docs.github.com/en/free-pro-team@latest/actions/learn-github-actions/introduction-to-github-actions)

GitHub Actions es la herramienta CI/CD interna de GitHub. Nos permite establecer un flujo de trabajo (workflow) que puede ser disparado mediante diferentes eventos que ocurren en el repositorio, como merge o push a una determinada rama.


### Definición de Acciones

Todas las acciones de GitHub se definen usando el formato YAML.

Creamos un directorio *.github* en el directorio raíz del repositorio, seguido del directorio *workflows* dentro de *.github*.
Después creamos un fichero *main.yml*, que es donde la acción es definida.


### Rama gh-pages

Desde la configuración del repositorio en GitHub (Settings) debemos indicar que la documentación del proyecto estará disponible en la rama gh-pages del repositorio.