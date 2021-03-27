# Slaves API
___

Библиотека для игры [Рабы](https://vk.com/app7794757_434463725#/) на Python.

# Большая просьба

Поставьте звездочку на репозиторий. Это много для меня значит.


# Версии
Т.к. разработчики могут менять свое api, здесь будут описаны версии библиотеки для актуализации.

Если вы получаете ошибки, проверьте, актуальная ли у вас версия. Обновитесь и если ошибки не исчезают, делайте пулл реквест

**Текущая версия:** 2

# Порядок установки
```shell script
git clone https://github.com/Phinnik/slaves_api.git
pip install virtualenv
virtualenv venv
venv\Scripts\activate.bat
cd slaves_api
pip install -r requirements.txt
```

# Пример использования
```python
from slaves import Api
api = Api('YOUR AUTHORIZATION STRING')

print(f'Цена Павла Дурова: {api.user_get(1).price} р.')
# >>> Цена Павла Дурова: 28820753 р.
```

# Документация
https://phinnik.github.io/slaves_api/index.html

# Благодарности
* [@zerd05](https://github.com/zerd05)
