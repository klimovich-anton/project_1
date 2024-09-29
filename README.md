git init //создание локального репозитория
git add . //поставили под версионный контроль
git commit -m "create gitignore" //сделали коммит
git remote add origin //создаем связь с удаленным репозиторием, предварительно созданным на github
git log / git status //посмотреть историю коммитов, статус - состояние на данный момент
git branch test //создание локальной ветки
git checkout test //перейти на ветку
git push -u origin https://github.com/klimovich-anton/project_1.git //запушить локальный репозитеорий в удаленный в ветку main
git push -u origin test 
