# mkt
Программа для анализа инвестиций по каждой сделке на основе брокерского отчета и данных торгов из терминала QUIK. Поддерживается формат HTML отчета от "сбербанк брокера". Если вам нужен анализ сделок по отчетам других брокеров, пришлите мне образец отчета в любом формате (с замененными на случайные, но не удаленными персональными данными) для построения парсера для вашего брокера. Также специальный скрипт формирует отчет о торгах прямо из терминала QUIK.

По вопросам и предложениям можно писать в дискорд https://discord.gg/jJx5zMU

Changelog

0.1.0
- Добавлен расчет прибыли по FIFO и LIFO за выбранный период как по отдельной бумаге, так и по всем суммарно.
- Lua скрипт для формирования отчета непосредственно из терминала. Теперь можно обойтись и без отчетов брокера для анализа интрадэя. Но для полного анализа всех торгов за период до подключения скрипта отчет все же необходим.
- Поддержка формата отчета от брокера Сбербанка.

0.0.1
- Расчет средней для каждой сделки на основе брокерского отыета.
