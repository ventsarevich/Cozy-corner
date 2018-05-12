 # Парное программирование
 В рамках данной лабораторной работы нами были опробованы следующие стили:
 * Ведущий-ведомый
 * Удаленное ПП
 * Пинг-понг

### 1. Винцаревич Влад (ведущий) и Казак Надежда (ведомый)

Разрабатывали: работа проводилась над акциями на отдельные позиции в меню блюд и напитков. А именно был разработан механизм создания, с указанным сроком действия и их удаление. Помимо этого имеется возможность из всего меня отобразить только акционные продукты для любителей вкусно, а главное недорого покушать.
Понравилось: Данный подход позволил немного ускорить процесс разработки, относительно предполагаемых заранее оценок. При этом нельзя сказать что ускорение было сильно значительным. Помимо вышесказанного в процессе работы была возможность обсудить и исправить сразу на месте, в том числе с помощью при помощи известного приема "тыкнуть в экран".
Проблемы: Приходилось решать разногласия, которые особенно часто встречались на начальном этапе по методам реализации, прямо на месте, а уже потом приступать за работу. При этом создавалось маральное давление, что время идет, а работа не движется. Но решив стартовые вопросы дела пошли лучше.

### 2. Бурак Евгений (ведущий) и Жуланова Алина (ведомый) (удаленное)
Разрабатывали: отдельные элементы фронта для отображения акций на сранице. Также отображение списка администраторов, для тех, кто вошел под аккаунтом администратора
Разработка происходила c использованием TeamViewer и Skype (т.е. удаленно). 
Понравилось: наличие пары помогает немного быстрее и эффективнее решать проблемы, с которыми раньше сталкиваться не приходилось. Т.е. появляется проблема, находим предполагаемые пути ее решения, и начинаем паралельно гуглить, пока кто-то не найдет ответ на вопрос. Основной выйгрыш по времени получился именно на этапе поиска информации, т.к. сама работа в паре, но удаленно, по ощущениям проходила не так быстро, как хотелось бы. Также выросла вероятность отловить глупую ошибку по мере работы (налету), т.к. что не заметил один, то заметил второй.
Проблемы: основной проблемой стал поиск времени, подходящий одновременно обоим для работы. При этом нельзя сказать что проблема решилась, просто пришлось пойти на компромиссы.

### 3. Демидок Юрий и Жуланова Алина (пинг-понг) (удаленное)
Разрабатывали: механизм правильного отображения нужного фронта для пользователей, гостей, администраторов и стаффа на основе финальной версии организации БД. Помимо этого были пофикшены минорные баги, замеченные с формой авторизации. Пинг-понг был выбран потому, что хотелось уделить большее внимание новой для нас библотеке sileneum, использовавшейся для тестирования.
Разработка происходила c использованием TeamViewer и Skype.
Понравилось: неплохая(но хотелось бы чуть быстрее) скорость работы (после обсуждения как и что будем делать). Удалось заметить минорный баг с формой авторизации и пофиксить его. Успешно адаптировали выбор фронта для финальной структуры БД.
Проблемы: некоторые трудности при работе с TeamViewer, разногласия в начале по выбору способа тестирования, разногласия по поводу того, стоит ли переключать тему IntelliJ на светлую(!).

### 4. Винцаревич Влад (ведущий) и Казак Надежда (ведомый)

Разрабатывали: функционал для отображения отзывов на странице. Работали над функционалом вместе, за одним ноутбуком.
Понравилось: 
Понравилось: работая вместе мы указывали на ошибки друг друга, что помогало избегать критических ошибок + разная точка зрения помогала подойти к разработке с разных сторон и находить универсальное решение проблем. Данный подход походит на Code review, которое в свою очередь является + гибкой разработки и scrum в частности.
Проблемы: работая по отдельности функционал мог бы быть написан быстрее, однако менее качественно.

## Выводы:
В заключении можно сказать, что парное программировани, несмотря на все свои недостатки, такие как увеличение времени разработки (или, как минимум, не особо сильное ускорение), необходимость идти на компромиссы одного из разработчиков в вопросах настройки IDE и тп, данное решение имеет право на существование. Оно помогает сплотить людей, работающих над одной задачей, помимо этого увеличивается инспекция за текущей работой, что помагает отлавливать некоторые ошибки на лету. Но это работает тогда, когда у вас нет проблем с ощущением дискомфорта, когда "кто-то стоит за спиной". Еще одном моментом является то, что сколько людей, столько и мнений. Это является одновременно и проблемой, и преимуществом(ведь чем больше вариантов, тем больше шанс того, что среди них будет именно тот, что подойдет как нельзя кстати в данной ситуации). Но главным полюсом парного программирования является то, что это может быть очень сильным инструментом, когда попадаешь в тупиковую ситуацию, из которой, какзалось бы, нету выхода. В таких ситуациях помощ товарищя - это один из немногих вариантов решения. Но при этом использование парного программирования, как основного инструмента в больших проектов вряд ли принесет пользу, так как скорее только замедлит процесс. Его лучше использовать для решения отдельных сложных ситуаций, либо на старте работы, для более качественного планирования. В целом же, можно сказать, что поставленные перед нами задачи были выполнены.