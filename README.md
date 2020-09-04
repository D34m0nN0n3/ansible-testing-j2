Ansible-testing-j2
===
Copyright (C) 2020 Dmitriy Prigoda <deamon.none@gmail.com> 
This script is free software: Everyone is permitted to copy and distribute verbatim copies of 
the GNU General Public License as published by the Free Software Foundation, either version 3
of the License.

## For check Jinja 2 template and vars/Для тестирование шаблонов Jinja 2 и переменных

Tested on/Протестировано на:
- CentOS 8 
- Ansible = 2.9.5

### Hint/Подсказка:
Run Playbook/Запуск сценария:
`ansible-playbook playbook.yml --extra-vars <var>` or/или `ansible-playbook playbook.yml -e <var>`

Using vars/Использование переменныч:
* "{'var_name': true}" - type bool (тип булев)
* "{'var_name':['value 1','value 2','value 3']}" - type array (тип массив)
* "var_name" - type string (тип строчный)
