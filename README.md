# Отчёты и отзывы по практикам магистрантов кафедры СП СПбГУ 2022-2024 гг.

## Структура репозитория

Образовательная программа / Фамилия Имя Отчество / семестр_№

## Порядок размещения отчётов и отзывов

1. «Форкнуть» этот репозиторий. Дальше работать со своим «форком».
2. В каталоге со своими программой / ФИО завести подкаталог нужного семестра (если ещё не).
   * Если каталога с ФИО почему-то нет — завести самим. ФИО **полностью**, т.е. не «Вася Чапаев», а «Чапаев Василий Иванович»!
3. Положить туда свои материалы — по отчёту и отзыву для каждого испрашиваемого зачёта. Слайды — на ваше усмотрение.
4. Отправить материалы на сервер.
5. Убедиться, что результат выглядит достойно, но пристойно.
5. Отправить pull request в исходный (этот) репозиторий. Ветви использовать не требуется, достаточно `main -> main`.
6. Готовиться сделать доклад на зачёте к назначенному времени.

## Оформление

Отчёты и отзывы принимаются в форматах PDF, `.docx`, `.odt`. Желательно PDF, поскольку его легче смотреть. Отзывы, если на одну страничку, можно картинкой, но нормального качества.

Текст отчёта рекомендуется готовить при помощи TeX, для чего можно воспользоваться [кафедральным шаблоном](https://github.com/spbu-se/matmex-diploma-template), MS Office или других офисных пакетов. Слайды к докладу также можно подготовить при помощи TeX на основе [шаблона](https://github.com/spbu-se/report_presentation_template), MS Office на основе [шаблонов СПбГУ](https://pr.spbu.ru/brandbook.html#templatePresentations) или других средств. Общее требование — чтобы материалы выглядели опрятно (в чём шаблоны конечно помогают).

## Маленькие хитрости

Из разряда «шуруп, забитый молотком, держится лучше гвоздя, завинченного отвёрткой».

### Как точно не надо делать

* Импортироавть PDF (особенно ТеХовскую) в офис и таким образом получать себе «шаблон». Почти каждый год сталкиваемся с таким кринге.
  Не делали слайдов в ТеХе — жаль, попробуйте; но офисные шаблоны с сайта СПбГУ по красоте им точно не уступают.
* Вписывать «научного руководителя», который не давал на это согласия. При таком отношении велик шанс это согласие уже не получить никогда.
* Плагиатить, а особенно брать куски текста с сайтов с рефератами и т.д. У комиссии глаз намётан, и даже без антиплагиата обычно такие вещи видно
  секунд за 20, а потом ещё секунд за 30 находятся конкретные пруфы недобросовестного заимствования. Надёжный способ вылететь с зачёта, не успев закончить речь.
  * добросовестно самоплагиатить можно

### Призовая игра для тех, кто дожил до конца второго семестра

Встречаются пуллреквесты, в которых номинально обновлены куча отчётов и отзывов за все предыдущие семестры. Такое не принимается. Три способа сделать правильно.

1. *По-взрослому*. Клонировать свой форк локально, добавить в него репозиторий из `spbu-se`, как `upstream`, сделать `pull` из `upstream`,
   добавить свои новые файлы, сделать `push` в свой форк, и потом сделать пуллреквест в репозиторий в `spbu-se`.
   Если Вы умеете так делать, и собираетесь это сделать, вы можете гордиться, и смело претендовать на позицию техлида в IT-компании.
2. *По-хипстерски*. Если от предыдущего пункта вы упали в обморок, уронили митболы и заляпали свитшот смузи, то вам
   [сюда](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).
   Оказывается, можно всё делать в браузере, а не пользоваться этой непонятно кому нужной командной оболочкой эпохи холодной войны!
3. *Честно*. Пишете куратору, что мол так и так, сложнааа, не осилю ни того, ни другого. Тогда будем работать индивидуально. Навёрстывать. Это наша работа.