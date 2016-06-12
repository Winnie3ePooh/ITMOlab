# ITMOlab
Модуль оповещения студентов о приближающемся экзамене

Для запуска использовать команду: JOB_TYPES=... node worker.js, где вместо "..." названия файлов с работами через запятую.

Основная документация по испоьзуемым модулям:
- Agenda - https://github.com/rschmukler/agenda
- Nodemailer - https://github.com/nodemailer/nodemailer и https://nodemailer.com/
- Node Email Templates - https://github.com/niftylettuce/node-email-templates

Все разрабатываемые файлы с "работами" для Agenda необходимо помещать в lib/jobs.

Шаблоны почтовых сообщений в каталог lib/templates/папка_шаблона.

Настройка сервера отправки происходит в файле "mailer.js" из каталога "lib".
