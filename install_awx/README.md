# Playbook AWX_install.

Automatización para la instalación del operador de AWX.
### Requerimientos.

- ansible-core

### Tested on:

- Debian
- Ubuntu

### Ejemplo.

````bash
$ ansible-playbook -i inventory main.yml -e awx_version="2.15.0"
````

