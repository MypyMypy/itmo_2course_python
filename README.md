# Проектирование и развертывание веб-решений в эко-системе Python

`Версия Python 3.12.0`

### Установка Python Ubuntu 20.04

- `sudo apt update && sudo apt upgrade -y`
- `sudo apt install python3.12 (или другая версия);`
- `sudo apt-cache policy python3.12`
- `sudo update-alternatives --list python`
- `sudo update-alternatives --config python | sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.12 3 (чем больше число, тем больше приоритет)`
- `python -V`

### Настройка виртуального окружения в VS Code

- > \>Python: Create Environment > Python 3.12.0
- > \>Python: Select Interpreter > Python 3.12.0

### Запуск локального сервера MkDocs:

- `pip install mkdocs & mkdocs --version`
- `mkdocs serve`

### Иные команды MkDocs

- `mkdocs new [dir-name]`
- `mkdocs build`
- `mkdocs serve`
- `mkdocs -h`
