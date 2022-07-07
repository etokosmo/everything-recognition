# Скрипт для распознавания образов

Скрипт умеет находить лицо человека (профиль и анфас) и его глаза в режиме реального времени.

Лицо человека обрамляется синей рамкой, глаза человека обрамляются желтыми прямоугольниками.

Для работы скрипта необходим доступ к видеокамере на вашем устройстве.

## Пример работы программы

### Профиль человека

### Анфас человека

### Глаза человека

> В разработке:
> - нахождение улыбки человека;
> - нахождение человека в полный рост;
> - нахождение мордочек котов.

## Конфигурации

Скрипт написан на языке программирование Python. 

Для запуска вам необходим Python версии 3.10.

Скачайте код, и в данной директории запускайте скрипт.

## Запуск

- Скачайте код
- Через консоль в директории с кодом установите виртуальное окружение командой:

```bash
python3 -m venv env
```

- Активируйте виртуальное окружение командой:
```bash
source env/bin/activate
```

- Установите библиотеки командой:
```bash
pip install -r requirements.txt
```

- Для скрипт командой:
```bash
python3 run.py
```