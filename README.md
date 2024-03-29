<h1 align="center">Support's Heaven</h1>

<p align="center">

<img src="https://img.shields.io/badge/made%20for-GTA%20SA--MP-blue" >

<img src="https://img.shields.io/badge/Server-SRP%20|%20ERP-red">

<img src="https://img.shields.io/github/languages/top/qrlk/supports-heaven">

<img src="https://img.shields.io/badge/dynamic/json?color=blueviolet&label=users%20%28active%29&query=result&url=http%3A%2F%2Fqrlk.me%2Fdev%2Fmoonloader%2Fusers_active.php%3Fscript%3Dsupport's_heaven">

<img src="https://img.shields.io/badge/dynamic/json?color=blueviolet&label=users%20%28all%20time%29&query=result&url=http%3A%2F%2Fqrlk.me%2Fdev%2Fmoonloader%2Fusers_all.php%3Fscript%3Dsupport's_heaven">

<img src="https://img.shields.io/date/1531947600?label=released" >

</p>

A **[moonloader](https://gtaforums.com/topic/890987-moonloader/)** script which combines a set of useful features for role-playing server's support staff (**[gta samp](https://sa-mp.com/)**).  

It requires **[CLEO 4+](http://cleo.li/?lang=ru)**, **[SAMPFUNCS 5+](https://blast.hk/threads/17/page-59#post-279414)**, **[MoonImgui](https://blast.hk/threads/19292/)** and **[Samp.Lua](https://blast.hk/threads/14624/)**.

---

**The following description is in Russian, because it is the main language of the user base**.
<details>
  <summary>Описание на русском языке.</summary>
 
# Описание
**Support's Heaven** - это lua скрипт для MoonLoader, который добавляет в игру множество полезных инструментов для игроков-саппортов.  
Подробная информация: [тут](https://blast.hk/threads/22928/)  
Поддерживаемые проекты: **Samp-Rp**, **Evolve-Rp**. 

## Список функций:

* **Автоматическое разрешение зависимостей.**

  * Для запуска скрипта необходим только сам скрипт и moonloader v026+.
  * Все необходимое скрипт может скачать автоматически после вашего согласия.
  * Список необходимых для работы скрипта штук (кроме ML):

    * CLEO 4+.
    * SampFuncs.
    * Dear Imgui.
    * SAMP.Lua.
    * 100 mp3 звуков для уведомлений.
    * Файлы ресурсов под ваш проект: шпоры, house.txt и vehicle.txt.


* **Работа с саппорт-чатом.**

  * Возможность скрыть вопросы в чате.
  * Возможность изменить цвет вопросов в чате.
  * Возможность скрыть ваши ответы в чате.
  * Возможность изменить цвет ваших ответов в чате.
  * Возможность скрыть чужие ответы в чате.
  * Возможность изменить цвет чужих ответов в чате.

* **Работа с смс-чатом.**

  * Возможность скрыть входящие смс в чате.
  * Возможность изменить цвет входящих смс в чате.
  * Возможность скрыть исходящие смс в чате.
  * Возможность изменить цвет исходящих смс в чате.
  * Возможность скрыть "Сообщение доставлено" в чате (SRP).
  * Возможность изменить цвет "Сообщение доставлено" в чате (SRP).

* **Спец. функции для саппортов.**

  * **Автоматическое начало рабочего дня саппорта.**

    * После логина рабочий день саппорта начнётся автоматически.

  * **Быстрый ответ на последний вопрос.**

    * По нажатию хоткея откроется чат с шаблоном "/pm id ", где id - игрок, задавший самый последний вопрос.

  * **/hh в чате.**

    * Использование: /hh id [id дома].
    * Достает из house.txt информацию о доме и отправляет через /pm id.
    * Пример: ID 494 | CLASS S | COST 25 000 000.

  * **/hc в чате.**

    * Использование: /hc id [id/название машины].
    * Достает из vehicle.txt информацию о доме и отправляет через /pm id.
    * Пример: 492 | Greenwood | N | 140.000 | 78 m/h | 1680.

  * **Список проигнорированных вопросов.**

    * По нажатию хоткея откроется диалог с проигнорированными саппортами вопросами, откуда можно быстро дать ответ.

  * **Быстрый ответ на последний вопрос из базы.**

    * По нажатию хоткея откроется диалог с последним вопросом и вариантами ответов, настроенными ранее.

  * **Быстрый ответ по id из базы.**

    * В чате "/pm id " откроет диалог с вопросом игрока id и вариантами ответов, настроенными ранее.

  * **Возможность настроить базу быстрых ответов, не выходя из игры и не перезапуская скрипт.**

* **Шпора.**

  * Прямо в игре вы можете посмотреть информацию о моде, не сворачивая игру.
  * Шпора представлена в виде картинок, разбитых по категориям, по которым можно переключатся в меню.
  * Шпора активируется хоткеем, открывается отдельное окно прямо внутри игры.
  * Есть несколько режимов отображания: авторесайз, сохранение пропорций и прокрутка вручную.
  * Есть режим лупы: когда изображение рядом с курсором увеличивается в два раза.
  * Сначала скрипт подгрузит мой набор шпор, а потом вы можете настроить свой как вам угодно. Настраивать можно прямо в игре. Если что-то сломается - удалите папку с именем вашего проекта и скрипт подгрузит мою стабильную версию.
  * Чтобы лучше понять, как это работает, посмотрите видео в шапке.

* **Мессенджер саппорта.**

  * Когда кто-то задаёт вопрос, в мессенджере создается диалог с этим игроком.
  * Диалог попадает в список, который сортируется по разным признакам: времени, активным фильтрам, есть ли непрочитанные сообщения, ответили ли другие саппорты на этот вопрос. Все как в обычных мессенджерах.
  * Непрочитанные диалоги меняют цвет, показывается количество непрочитанных сообщений.
  * Диалог закрывается по нажатию правой кнопки.
  * Открыв диалог, можно увидеть краткую информацию об игроке: его ник, lvl, id, онлайн ли он, сколько времени прошло с того момента, как игрок задал вопрос.
  * В диалоге можно прочитать вопрос, ответы других саппортов (можно их скрыть), и ответить самому.
  * В мессенджере работают функции /hh и /hc: id игрока вводить не нужно, просто /hh [id дома], если есть совпадение, будет показана подсказка.
  * В мессенджере есть функция /fr - поиск по базе быстрых ответов по номеру или тексту.
  * Хоткей открытия мессенджера саппорта.
  * Хоткей открытия диалога с последним заданным вопросом.
  * Возможность изменить цвет сообщений в диалогах на свой.

* **Мессенджер смс.**

  * Внешне похож на мессенджер саппорта, но с некоторыми улучшениями.
  * В отличии от саппортского мессенджера, все ваши переписки могут храниться в отдельной базе данных, т.е. вы не потеряете свои диалоги после выхода из игры.
  * Возможность создать новый диалог. Вписываешь в поле id, ник, если есть совпадение - выводится подсказка. Потом enter и всё - диалог создан.
  * Не работают /hh, /hc и /fr.
  * Непрочитанные диалоги меняют цвет, показывается количество непрочитанных сообщений.
  * В диалоге есть кнопка быстрой проверки игрока на afk.
  * Фильтр по нику и онлайну.
  * Возможность закрепить диалоги с друзьями: в списке они будут выше остальных.
  * Возможность заблокировать собеседника: сообщения от него не будут вас тревожить.
  * Возможность очистить диалог.
  * Возможность удалить диалог.
  * Хоткей открытия мессенджера смс.
  * Хоткей открытия диалога с последней смс.
  * Хоткей открытия мессенджера с фокусом на начало нового диалога.
  * Возможность изменить цвет сообщений в диалогах на свой.

* **Блокнот.**

  * Обычный внутриигровой блокнот, куда можно что-то быстро записать и сохранить.
  * Работают ctrl+z, ctrl+a, ctrl+c, ctrl+v и т.п.
  * Хоткей открытия блокнота.

* **Логгер ответов.**

  * Все ваши ответы записываются в .csv таблицу.
  * Таблицу можно посмотреть прямо в игре, либо в любом табличном процессоре (Excel, Google Sheets).
  * **Сохраняется следующее:**

    * ID вопроса.
    * Ник игрока, задавшего вопрос.
    * Вопрос.
    * Ответ.
    * Время, которое прошло между вопросом и ответов.
    * Дата и время ответа.

  * При каждом запуске скрипта/ручном обновлении .csv считывается для отображения лога ответов/статистики в виде гистограммы.
  * Обработка 100.000 ответов занимает 3 секунды.

* **Просмотр лога ответов.**

  * Просмотр лога ответов прямо в игре в виде таблицы.
  * Выбор года, месяца и дня для просмотра лога за эту дату.
  * В сампе сутки начинаются в 05:00, поэтому ответ 19.07.2018 в 01:04 будет относиться к 18.07.2018.
  * Возможность вручную обновить .csv без перезапуска скрипта.
  * Возможность скопировать вопрос/ответ правой кнопкой мыши.

* **Гистограмма.**

  * Статистика ответов по месяцам: вы можете в наглядном виде посмотреть количество ответов за день и за весь месяц.
  * Статистика отображается в виде [гистограммы]('https://ru.wikipedia.org/wiki/%D0%93%D0%B8%D1%81%D1%82%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0').
  * Возможность вручную обновить .csv без перезапуска скрипта.

* **Счётчик саппорта.**

  * С точностью до минуты отображает время, которое вы уже провели на посту саппорта.
  * Дата и время "заступления" на пост настраивается в настройках.

* **Уведомления - саппорты.**

  * Возможность включить звуковое уведомление о вопросе, на выбор есть 100 отобранных мною звуков.
  * Возможность включить звуковое уведомление об ответе, на выбор есть 100 отобранных мною звуков.
  * Возможность включить звуковое уведомление о чужом ответе, на выбор есть 100 отобранных мною звуков.
  * В будущем количество звуков может увеличиться.

* **Уведомления - смс.**

  * Возможность включить звуковое уведомление о входящей смс, на выбор есть 100 отобранных мною звуков.
  * Возможность включить звуковое уведомление об исходящей смс, на выбор есть 100 отобранных мною звуков.
  * В будущем количество звуков может увеличиться.

* **Информация о скрипте.**

  * Все кликабельные ссылки, информация о скрипте, changelog собраны в одном месте.

* **Настройки.**

  * Хочется отдельно отметить возможность кастомизации скрипта под себя.
  * Главное меню скрипта выглядит как куча "спойлеров" из активных функций.
  * "Спойлеры" можно открывать и закрывать и играться с каждым элементом в большом окне.
  * Окно можно растягивать, элементы будут подстраиваться под размер окна.
  * Нажав правую кнопку по "спойлеру", все окно заполнится одним элементом.
  * Это окно можно растягивать и элемент будет заполнять свободное пространство не только по горизонтали, но и по вертикали.
  * В меню можно вернутся, нажав кнопку "в меню".
  * Всего в настройках скрипта 15 вкладок, на каждой своя группа.
  * Каждой настройке дан комментарий что она делает, наведите курсор на (?) и получите информацию.
  * Каждую функцию можно выключить, большинство из них можно настроить. Вы можете купить его и выключить всё, кроме блокнота и смс мессенджера, и всё остальное вы даже не заметите.
  * Хоткеи настраиваются через [Исходник - Софт - ImGui Custom](https://blast.hk/threads/22080/), а не через .ini или как-нибудь ещё.
  * Все хоткеи могут быть выключены, кроме хоткея открытия главного меню.
  * Возможно рендерить курсор через гта, чтобы он был виден на скринах и видео.
</details>
