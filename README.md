# Школа сильных программистов. Курс "Тестирование в Python"

Полезные ресурсы в отношении тестирования в Python из круса ["Тестирование в Python"](https://education.borshev.com/python-testing) [Школы сильных программистов](https://education.borshev.com/). Упомянутые в крусе, а так же найденные в процессе изучения.

## Полезные материалы из нулевой недели курса

* [Полифморфизм простыми словами](https://medium.com/devschacht/polymorphism-207d9f9cd78).
* [Typeclasses in Python](https://sobolevn.me/2021/06/typeclasses-in-python) 
* [classes](https://classes.readthedocs.io/en/latest/) - Умный, питонический, ad-hoc, типизированный полиморфизм для Python.
* [unittest](https://docs.python.org/3/library/unittest.html) - Стандартный модуль для реализации юнит-тестов.
* [pytest](https://docs.pytest.org/en/latest/) - Популярный фреймворк для создания и выполнения тестов в Python.
* [pytest-mypy-plugins](https://github.com/TypedDjango/pytest-mypy-plugins) - Плагин `pytest` для тестирования типов, стабов и плагинов `mypy`.
* [pytest-mock](https://pytest-mock.readthedocs.io/en/latest/) - плагин `pytest` предоставляет фикстуру `mocker`, которая является тонкой оберткой вокруг API патчей, предоставляемых стандартным пакетом `mock`
* [HTTPretty](https://github.com/gabrielfalcao/HTTPretty) - Лучшая mock библиотека для HTTP вызовов. Базируется на мокании сокетов.
* [doctest](https://docs.python.org/3/library/doctest.html) - Модуль `doctest` ищет фрагменты текста, которые выглядят как интерактивные сессии Python, а затем выполняет эти сессии, чтобы проверить, что они работают именно так, как показано.
* [pytest-modified-env](https://github.com/wemake-services/pytest-modified-env) - Плагин Pytest для сбоя теста, если после него остается измененный `os.environ`.
* [unittest.mock](https://docs.python.org/3/library/unittest.mock.html) - mock object library
* [Mocks Aren't Stubs](https://martinfowler.com/articles/mocksArentStubs.html)
* [Mocks and explicit contracts](https://dashbit.co/blog/mocks-and-explicit-contracts)
* [Engineering guide to writing correct User Stories](https://sobolevn.me/2019/02/engineering-guide-to-user-stories)

## Полезные материалы из первой недели курса

* [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - Линтер, который умеет мерить всю сложность и следит за именами.
* [Complexity Waterfall](https://sobolevn.me/2019/10/complexity-waterfall) - Статья, которая описывает, как сложность перетекает из одного места в другое.
* [Mimesis: The Fake Data Generator](https://github.com/lk-geimfari/mimesis) - Лучшая библиотека для генерации фековых данных.
* [Django-fakery](https://github.com/fcurella/django-fakery) - Генерация `Django` моделей.
* [flake8-pytest-style](https://github.com/m-burst/flake8-pytest-style) - Плагин `flake8` проверяет общие проблемы в тестах написанных на основе `pytest`.
* [PEP 692 - Keyword collisions](https://peps.python.org/pep-0692/#keyword-collisions) - про разные типы аргументов.
* 

## Другие пололезные материалы

* [pytest-bdd](https://github.com/pytest-dev/pytest-bdd) - BDD library for the pytest runner
* [pytest-deadfixtures](https://github.com/jllorencetti/pytest-deadfixtures) - Простой плагин для составления списка неиспользуемых или дублирующихся фикстур в тестах pytest.
* [Make tests a part of your app](https://sobolevn.me/2021/02/make-tests-a-part-of-your-app) - _**#вопрос** есть опыт использования кастомных hypothesis-стратегий для генерации сущностей типа UserData вместо фикстур с mimesis? Может есть какие-то известные потенциальные проблемы с этим? **#ответ** Никита Соболев: Да, есть. Нужно сначала делать правила, потом генерацию. Желательно правила привязывать к бизнес логике (из чата в Telegram)_
* [factory_boy](https://github.com/FactoryBoy/factory_boy) - As a fixtures replacement tool, it aims to replace static, hard to maintain fixtures with easy-to-use factories for complex objects.
* [pytest-watcher](https://github.com/olzhasar/pytest-watcher) - Rerun pytest when your code changes.
* [pytest-testmon](https://testmon.org/) - pytest-testmon is a pytest plugin which selects and executes only tests you need to run.


## Материалы не по теме курса

* [behave](https://github.com/behave/behave) - behave is behavior-driven development, Python style.
* [conventional: comments](https://conventionalcomments.org/) - Комментарии, которые легко читать и понимать.
* [Make VS Code Awesome](https://makevscodeawesome.com/) - Курс по настройке VS Code.
* [naming](https://github.com/wemake-services/wemake-python-styleguide/blob/master/wemake_python_styleguide/violations/naming.py) - Гайд по неймингу в Python от wemake-services.
* [glom](https://github.com/mahmoud/glom) - Python's nested data operator (and CLI), for all your declarative restructuring needs. Got data? Glom it!
* [wemake-django-template](https://github.com/wemake-services/wemake-django-template/) - Bleeding edge django3.2 template focused on code quality and security.
