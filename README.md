# ITMOlab
Модуль оповещения студентов о приближающемся экзамене

Для запуска использовать команду: JOB_TYPES=... node worker.js, где вместо "..." названия файлов с работами через запятую.
Основная документация по испоьзуемым модулям:
1. Agenda - https://github.com/rschmukler/agenda
2. Nodemailer - https://github.com/nodemailer/nodemailer и https://nodemailer.com/
3. Node Email Templates - https://github.com/niftylettuce/node-email-templates

Все разрабатываемые файлы с "работами" для Agenda необходимо помещать в lib/jobs.
Шаблоны почтовых сообщений в каталог lib/templates/папка_шаблона.
