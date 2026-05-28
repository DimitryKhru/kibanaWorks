git init - инициализация локального гит репозитория
git add .- добавлляем наши файлы к трекингу
git commit -m "TEXT" - закомитить файл

git branch -M main  - создать ветку или перейти к ветке
git push -u origin master - отправить в ветку мастер

git checkout -b feature/new-feature. Команда git checkout -b — это сокращение для двух команд: git branch feature/new-feature (создание ветки) и git checkout feature/new-feature (переключение на неё).

ssh-keygen -t rsa -b 4096 -C "stalinsvet@example.com" - генерация ключа 
Далее по пути Users/УЗ видим два серта один приватный второй публичный с раcширением .pub
берем pub ключ и устанавливаем руками его в гитхаб




Подключение к репозиторию
1ю Создать папку
2. Выполнить команду git init
3. git remote add origin git@github.com:DimitryKhru/kibanaWorks.git - добавить репозиторий
4. git pull origin master - выгрузить ветку местер