# SmartFridge-QR-Control-IoT-Sync

# 1.Описание проекта 
 SmartFridge — это приложение на Python с использованием библиотеки Kivy, которое позволяет пользователям управлять запасами продуктов в холодильнике с помощью QR-кодов и IoT-технологий. Приложение уведомляет пользователей о сроках годности продуктов и позволяет 
 легко отслеживать их запасы.

# 2.Функциональные возможности

 Сканирование QR-кодов для добавления продуктов.
 Уведомления о сроках годности продуктов.
 Управление запасами продуктов через удобный интерфейс.
 Синхронизация данных с IoT-устройством.
# 3.Установка и развертывание Требования

 Python 3.6 или выше
 Kivy 2.0 или выше
 Дополнительные библиотеки (указаны в libraries.txt)
# 4.Шаги по установке

 Клонирование репозитория

 git clone https://github.com/yourusername/SmartFridge.git cd SmartFridge

 Создание виртуального окружения

 python -m venv venv source venv/bin/activate # Для MacOS

 Установка зависимостей Убедитесь, что у вас установлен pip, затем выполните:

 pip install -r requirements.txt

 Запуск приложения После установки всех зависимостей, запустите приложение:

 python main.py

# 5.Развертывание приложения с помощью Buildozer 
 Если вы хотите развернуть ваше приложение на Android, вам понадобится использовать Buildozer.
 Установка Buildozer Убедитесь, что у вас установлен Python и pip, затем выполните:

 pip install buildozer

 Инициализация Buildozer В корневом каталоге вашего проекта выполните:

 buildozer init

 Это создаст файл buildozer.spec, в котором вы можете настроить параметры вашего приложения.
 Настройка файла buildozer.spec Откройте файл buildozer.spec и измените необходимые параметры, такие как название приложения, версия и зависимости.
 Сборка приложения Для сборки APK-файла выполните:

 buildozer -v android debug

 Этот процесс может занять некоторое время, так как Buildozer будет загружать все необходимые зависимости и инструменты. 5) Установка приложения на устройство После успешной сборки вы можете установить приложение на подключенное Android-устройство с помощью:

 buildozer android deploy run

 1)Запустите приложение. 
 2)Используйте камеру устройства для сканирования QR-кода на продукте. 
 3) Добавьте информацию о продукте в систему. 
 4)Получайте уведомления о сроках годности и управляйте запасами через интерфейс приложения.

 Требования

 Python 3.6 или выше
 Kivy 2.0 или выше
 Дополнительные библиотеки (указаны в libraries.txt)
# 6.Ссылка на репозиторий https://github.com/Vladv2008/SmartFridge-QR-Control-IoT-Sync-

# 7.Видеоролик

 [Ссылка на видеоролик с демонстрацией работы приложения](Ссылка на ролик)

# 8.Разработчики

 Агаев Эмин (Backend разработка)
 Воропаев Владислав(Документация)
 Гораш Богдан(Frontend разработка)
