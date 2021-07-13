Порядок выполнения действий:

Клонировать репозиторий: git clone https://github.com/Yaroslav-Rakov/uklon-devops-test2.git

Перейти в папку uklon-devops-test2: cd uklon-devops-test2

Перейти в папку myapp: cd myapp

Создать образ из Dockerfile: sudo docker build . -t second_task/node-web-app

Создать контейнер из образа и запустить его: docker run -p 3000:3000 -d second_task/node-web-app

Открыть в браузере: http://localhost:3000/
