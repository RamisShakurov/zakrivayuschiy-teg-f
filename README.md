# Проектная работа - 4
### Ссылка на репозиторий: https://github.com/RamisShakurov/zakrivayuschiy-teg-f
### Ссылка на githubPage https://ramisshakurov.github.io/zakrivayuschiy-teg-f/
### Ссылка на макет https://www.figma.com/design/owJjxYMoWakoqm0WQYlCmK/4-%D1%81%D0%BF%D1%80%D0%B8%D0%BD%D1%82.-%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BD%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-(Copy)?m=auto&t=1Cdy5sN2dYwOzGUw-6

# Исправление № 1

## index.html:
1. Поменял тег div для header__logo на span. Удалил перенос строки.
2. Имена классов для изображений поменял на соответсвующий им фильтры.
3. Заменил article на div. Для изображений с подписью добавил figure и figcaption.
4. Добавлены отступы во вложенных элементах.
5. Для элементов разметки, не несущих смысловой нагрузки добавлен атрибут aria-hidden="true"
6. изображениям добавлена ленивая загрузка.
7. Для элементов без текстового значения добавлен атрибут aria-label.
8. Лишний класс в карточках удален, численные классы убраны.
9. В dialog__text убран перенос строки.
10. Кнопка "ок" переписана в нижнем регистре и стилизована в css через text-transform. 
11. Убран footer. Кнопка и диалоговое окно вынесены за main. 
## style.css:
1. Для страницы задан background-color.
2. Убран inline-size: 100vw.
3. Применены логические элементы для header
4. Убрана тень с текста
5. Сверху и снизу добавлена рамка для изображений
6. Добавлен transition для кнопок ("like", "сохранить на память", "ок"). Теперь кнопки имеют единый класс стилизации. Добавлены fosus, hover через единый класс.
7. Сущность sprint_number-4 удалена из проекта.
8. Удалил высоту у всех контентных и текстовых блоков.
9. Убран transition для диалогового окна.

## global.css :
1. Добавлен корректный альтернативный шрифт.

## variables.css:
1. breakpoint-simulation удален
2. Градиент переделан

## animation.css 
1. Все анимации переделаны в соотвесвтии с заданием
# SVG:
1. в floppy.svg fill="black" заменен на currentColor, что позволяет гибко управлять заливкой через css
## Общий комментарий
1. Для изображений добавлен aspect-ration 1/1 Теперь картинки пропорциональны при любых разрешениях

# Исправление № 2
## style.css
1. Для диалогового окна добавлена функция расчета отступов clamp. Теперь текст умещается в 3 строки до ширины просмотра до 320px 
