add sting Задание №3 – Ветки

# devops-netology
Первая правка

## Описание какие файлы будут проигнорированы в будущем благодаря добавленному .gitignore


# Локальные каталоги .terraform
** / .terraform / *

# файлы .tfstate
* .tfstate
* .tfstate. *

# Файлы журнала сбоев
crash.log

# Исключить все файлы .tfvars, которые могут содержать отправляемые данные
* .tfvars

# Игнорировать файлы переопределения, поскольку они обычно используются для локального переопределения ресурсов и поэтому не отметились
override.tf
override.tf.json
* _override.tf
* _override.tf.json

# Игнорировать файлы конфигурации CLI
.terraformrc
terraform.rc