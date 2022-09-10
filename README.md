Описание

Проект связанный с API, где описаны основные возможности для проекта YATUBE.

Для клонирования проекта используйте:

```plaintext
git clone https://github.com/Ramiras123/api_final_yatube.git	
```

Затем создайте виртуальное окружение проекта 

```plaintext
python -m ven venv
```

После установите основные библиотеки для работы 

```plaintext
pip install -r requirements.txt
```

Можете запускать проект. 

Примеры работы с API описаны по ссылке /redoc/, где и есть основная документация проекта

Проект расчитан на авторизованных и неавторизованных пользователей по ключу JWT 

Для создания публикации используйте API 

```plaintext
POST /api/v1/posts/
```

Где нужно указать body:

```plaintext
{ "text": "string", "image": "string", "group": 0 }
```

Удаление:

```plaintext
DEL /api/v1/posts/{id}/
```

Все возможные примеры использования описаны в /redoc/
