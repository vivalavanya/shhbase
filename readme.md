# Руководство по работе с ssh

### Дамп базы данных mysql с vps (Применять в той папке куда будет делаться выгрузка)

mysqldump -u [login] -p [dbname] > [Название файла на сервере с расширением sql] --no-tablespaces

### Скачивание файлов с ssh на компьютер

scp [путь до папки на сервере root@199.99.99.9:/путь][путь до папки на компьютере (/users/ivanmiheev/downloads/)]

### Добавление папки в архив

tar -zcvf [Название архива с расширением tar.gz][путь до папки на сервере (root@99.99.999.999:/путь/)]
