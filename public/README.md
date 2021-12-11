### Примечание
Ветка static-ref необходима для деплоя референса на специальный стенд

установите cli инструментарий:

`npm install -g firebase-tools`

залогиньтесь в аккаунт с доступом к нашему тестовому окружению:

`firebase login`

Положите standalone build референсного проекта в эту папку и затем разверните командой: 

`firebase deploy --only hosting:nb-test-task-dev`
