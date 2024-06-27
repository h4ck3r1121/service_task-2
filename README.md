# Задание №2 (Service)
1. Открыть файл "hosts" и прописать IP-адрес сервера, и, если нужно, имя пользователя и путь к private-ключу. Если private-ключа нет, то обратиться к главному системному администратору или руководителю проекта.
2. Перейти по пути "roles/robertdebock.gitlab_runner/defaults" и открыть файл "mail.yml". Ввести нужные данные для регистрации и запуска GitLab-раннера. Если что-то непонятно, то переходим по [ссылке] (https://github.com/robertdebock/ansible-role-gitlab_runner) и изучаем инструкцию.
3. Проверяем "main.yml". В переменной "gitlab_runner_executor" должен быть указан "shell".
4. Запустить "install-needed-software.yml" с ключом "-b".
