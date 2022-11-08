# everything-recognition
Упражнение на чтение кода. Распознавание образов

Программа обращается к веб-камере компьютера, покадрово получает с нее видеопоток и выделяет прямоугольниками распознанные лица до тех пор, пока пользователь не нажмет клавишу 'q'.  

Для установки и запуска программы выполните следующие действия: 

* Создайте виртуальное окружение Python с помощью команды `pip venv "имя-каталога"`. 
* Скопируйте репозиторий `everything-recognition` в каталог виртуального окружения. Для этого необходимо открыть оболочку Git и выполнить в ней следующую команду:  `git clone "https://github.com/devmanorg/everything-recognition.git"`
* Активируйте виртуальное окружение с помощью пакетного файла `activate.bat`, который расположен в подкаталоге `Scripts` виртуального окружения. 
* Установите требуемые для выполнения программы зависимости с помощью команды `pip install -r requirements.txt`.
* При необходимости укажите в файле `config.py`, какие именно области и каким цветом должна выделять программа. Присвойте значение `True` параметру draw, чтобы отслеживать профиль, анфас, улыбку, глаза и т.д. Параметр color задает цвет рамки. Доступны следующие категории: 
  - `Face front` - анфас лица
  - `Face profile` - профиль лица
  - `Smile` - улыбка
  - `Eyes` - глаза
  - `Full body` - тело
  - `Cat face` - кошачья голова  
* Запустите файл `run.py`.

