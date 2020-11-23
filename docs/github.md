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


## GitHub Actions

[GitHub Actions Introduction](https://docs.github.com/en/free-pro-team@latest/actions/learn-github-actions/introduction-to-github-actions)

GitHub Actions are a CI/CD tool that is tied directly into GitHub’s ecosystem.

This allows you to set up workflows that can be triggered through many different events that might take place in your repository, such as a merge or push to a specific branch.

### The Action

All GitHub Actions are defined using YAML.

Lets create a *.github* directory in the outermost directory of your repository, followed by a *workflows* directory within the *.github* one. 
Then create a *main.yml* file, which is where the action will be defined.