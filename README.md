# cw_4_hh_vacancies

## Описание
Этот проект предназначен для поиска и анализа вакансий с сайта hh.ru. Пользователи могут искать вакансии по ключевым словам, фильтровать результаты по различным критериям, сохранять вакансии в файл и анализировать сохраненные данные.


## Использование

Для работы с проектом вам необходимо иметь установленный Python версии 3.12 или выше и инструмент управления зависимостями [Poetry](https://python-poetry.org/). Проект использует библиотеку requests для работы с API.

### Установка Poetry

Если у вас еще не установлен Poetry, вы можете установить его, следуя инструкциям на официальном [сайте Poetry](https://python-poetry.org/docs/).

Установите зависимости проекта, выполнив следующую команду в корневом каталоге проекта:
poetry install

Убедитесь, что все зависимости установлены, используя файл `pyproject.toml` или `poetry.lock` для управления зависимостями.

## Как использовать
1. Установите необходимые зависимости.
2. Запустите `main.py` и следуйте инструкциям в консоли для поиска и фильтрации вакансий.
3. Сохраните интересующие вакансии в файл для дальнейшего анализа.

## Примеры использования
После запуска `main.py` введите ключевое слово для поиска, например, "Python разработчик". Выберите фильтры, следуя подсказкам в консоли. Результаты будут отфильтрованы и показаны вам для дальнейших действий.
