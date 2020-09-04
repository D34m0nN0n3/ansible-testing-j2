Ansible-testing-j2
===
Copyright (C) 2020 Dmitriy Prigoda <deamon.none@gmail.com> 
This script is free software: Everyone is permitted to copy and distribute verbatim copies of 
the GNU General Public License as published by the Free Software Foundation, either version 3
of the License.

EN.

## For check Jinja 2 template and vars

Tested on:
- CentOS 8 
- Ansible = 2.9.5

### Hint:
Run Playbook:
`ansible-playbook playbook.yml --extra-vars <var>` or `ansible-playbook playbook.yml -e <var>`

Using vars/Использование переменныч:
* "{'var_name': true}" - type bool
* "{'var_name':['value 1','value 2','value 3']}" - type array
* "var_name" - type string

All templates must be copied to the "templates" folder.

RU.

## Для тестирование шаблонов Jinja 2 и переменных

Протестировано на:
- CentOS 8 
- Ansible = 2.9.5

### Подсказка:
Запуск сценария:
`ansible-playbook playbook.yml --extra-vars <var>` или `ansible-playbook playbook.yml -e <var>`

Использование переменныч:
* "{'var_name': true}" - тип булев
* "{'var_name':['value 1','value 2','value 3']}" - тип массив
* "var_name" - тип строчный

Все шаблоны необходимо скопировать в папку "templates".
