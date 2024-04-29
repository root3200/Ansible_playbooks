# Playbook AWX_install.

Automatización para la instalación del operador de AWX.
### Requerimientos.

- ansible-core

### Probado en:

- Debian
- Ubuntu

### Ejemplo.

````bash
$ ansible-playbook -i inventory main.yml -e awx_version="2.15.0"
````
>Compruebe la version en:

[awx_operator/releases](https://github.com/ansible/awx-operator/releases)


---

>NOTA: recuerde cambiar la contraseña en su primer inicio.

````bash
TASK [debug] *********************************************************************************************************************************************************
ok: [debian1] => {
    "msg": "You password 8G07i1oZelWQsesme0RN7B5guJgcQGj6 "
}
````
