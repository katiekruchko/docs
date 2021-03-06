Работа с листами подписчиков
============================

Точка подключения:
   
.. code-block:: json

   https://devino.online

Создание листа подписчиков (POST)
---------------------------------

.. code-block:: json

   /api/v1/subscriber_lists?name=<Название листа подписчиков>
   
   
Параметры запроса:
 
+----------------------+------------+--------------------------------------------------------+--------------+
|      Параметр        | Тип данных |    Описание                                            |Обязательный  |
+======================+============+========================================================+==============+
| name                 |   string   |  Название листа подписчиков                            |       Да     |
+----------------------+------------+--------------------------------------------------------+--------------+


Пример овтета:

.. code-block:: json

   {
      "id": 0,
      "name": "string"
   }
   
 
Параметры ответа:
 
+----------------------+------------+--------------------------------------------------------+--------------+
|      Параметр        | Тип данных |    Описание                                            |Обязательный  |
+======================+============+========================================================+==============+
| id                   |   integer  |  Идентификатор листа                                   |       Да     |
+----------------------+------------+--------------------------------------------------------+--------------+
| name                 |   string   |  Название листа подписчиков                            |       Да     |
+----------------------+------------+--------------------------------------------------------+--------------+


Вывод листа подписчиков (GET)
-----------------------------

.. code-block:: json

   /api/v1/subscriber_lists/{id}
   
   
Параметры запроса:
 
+----------------------+------------+--------------------------------------------------------+--------------+
|      Параметр        | Тип данных |    Описание                                            |Обязательный  |
+======================+============+========================================================+==============+
| id                   |   integer  |  Идентификатор листа                                   |       Да     |
+----------------------+------------+--------------------------------------------------------+--------------+


Пример овтета:

.. code-block:: json

   {
      "id": 0,
      "name": "string"
   }
   
 
Параметры ответа:
 
+----------------------+------------+--------------------------------------------------------+--------------+
|      Параметр        | Тип данных |    Описание                                            |Обязательный  |
+======================+============+========================================================+==============+
| id                   |   integer  |  Идентификатор листа                                   |       Да     |
+----------------------+------------+--------------------------------------------------------+--------------+
| name                 |   string   |  Название листа подписчиков                            |       Да     |
+----------------------+------------+--------------------------------------------------------+--------------+


