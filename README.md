# bem-methodology

БЭМ
Без макета.
Создаем папку blocks - внутри нее наши блоки(папки): container, header, main-title, menu, lead,page, subtitle.

Этим папкам создаем файлы css page.css
В проекте подключаем их правильно. В style.css -
@import "block/page/page.css"
Так делаем со всеми файлами

В папке container создаем папку \_size_m - создаем файл container_size_m.css. Подключаем в style.css \*вероятно это для адаптива или для модификатора.

В папке header - папки \_logo -файл header\_\_logo.css и \_menu -файл header.css

page - класс page для body.

Блок - логическое разделение. В блок можно вкладывать другие блоки
Элемент не может существовать без блока.
Модификатор может применяться к блоку и к элементу. Модификатор придает внешний вид (стили).
Миксование классов- когда элементу задаем сразу модификатор

Почитать: 3 подхода для организации структуры для методологии бэм
