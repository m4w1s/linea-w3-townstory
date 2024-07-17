# Linea W3: Townstory

## Как запустить
Для работы требуется установленный Node.js v18 или выше (https://nodejs.org/en/download)

Первым делом скачиваем архив (Зеленая кнопка `Code` -> `Download ZIP`) и распаковываем.

Затем нужно открыть терминал (CMD или PowerShell на Windows) и перейти в папку где находится файл package.json.
<details>
  <summary>Как это сделать?</summary>

  В проводнике копируем путь к папке и вставляем в терминале:
  ```bash
  cd путь_к_папке
  ```
</details>

#### Далее выполняем следующие команды:

Установка зависимостей
```bash
npm install
```

Запуск
```bash
npm start
```

## Настройка

Кошельки нужно добавить в `data/wallets.txt`. Каждый приватный ключ с новой строки.\
Можно использовать тот же формат что использовался в боте.

Все остальные настройки как RPC, задержки, количество потоков и тд. находятся в `data/config.js`.

По умолчанию:\
RPC: `https://linea.blockpi.network/v1/rpc/public`\
Задержки: `от 150 до 300 секунд`\
Количество потоков: `2`\
Перемешать кошельки: `да`

Можно запускать повторно на тех же кошельках, второй раз минтить NFT бот не будет.
