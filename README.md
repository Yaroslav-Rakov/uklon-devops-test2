Порядок выполнения действий:

1. Клонировать репозиторий: git clone https://github.com/Yaroslav-Rakov/uklon-devops-test2.git

2. Перейти в папку uklon-devops-test2: cd uklon-devops-test2

3. Перейти в папку myapp: cd myapp

4. Создать образ из Dockerfile: sudo docker build . -t second_task/node-web-app

5. Создать контейнер из образа и запустить его: docker run -p 3000:3000 -d second_task/node-web-app

6. Открыть в браузере: http://localhost:3000/
