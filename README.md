В данном проекте(задании) были выполнены следующие пункты:
Фильтры и пагинация
1. Добавлен постраничный вывод на /news/, на странице было выведены все новости и статьи, а так же добавлена возможность перехода по страницам прибольшем количестве новостей(статей).
2. Так же на этой странице была возможность искать новости по определённым критериям. Критерии следующие:
- по названию(Title);
- по категории(PostCategory);
- по указываемой дате(Publication date from);
- по автору(Author).
3. Выполнели фильтрацию сразу по нескольким критериям. Форма генерирутся с помощью django-filter.

Создание, редактирование и удаление объектов:
Создание и редоктирование объектов
- /news/create/;
Удаление объектов
- /news/<int:pk>/delete/.
