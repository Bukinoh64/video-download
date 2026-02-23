# Video Downloader

Простой веб-сервис для скачивания видео с популярных сайтов.

## Что умеет

- Скачивать видео с YouTube, TikTok, Twitter, Instagram, Facebook, VK и других сайтов
- Сохранять историю загрузок
- Отменять загрузку во время процесса

## Установка

1. Установите FFmpeg:
   - Windows: winget install ffmpeg
   - Linux: sudo apt install ffmpeg
   - Mac: brew install ffmpeg

2. Установите зависимости:
      pip install -r requirements.txt
   

## Запуск

- Windows: запустите файл run.bat
- Linux/Mac: выполните ./run.sh

После запуска откройте http://localhost:5000 или http://127.0.0.1:5000/ в браузере.

## Использование

1. Вставьте ссылку на видео
2. Нажмите "Скачать"
3. Скачанный файл появится в папке downloads/
