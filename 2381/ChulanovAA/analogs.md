﻿## Сравнение аналогов
###  Экспертная система
Система, использующая предопределенные правила анализа, обработки музыкальной композиции и дальнейшей классификации. Эффективна в случае наличия большого объема исследований сигналов, соответствующих музыке, например, в отношении классической музыки.
### Приложение jSymbolic
Приложение для расчета высокоуровневых параметров музыкальных композиций: высота звука, аккорды, мелодия, ритм, используемые инструменты, динамика. Приложение работает только с файлами формата MIDI.
### Приложение jAudio
Приложение для расчета низкоуровневных параметров музыкальных композиций: центроид, ролл-офф, амплитудный спектр, компактность, гистограмма ударов, мел-частотные кепстральные коэффициенты (MFCC) и др. На основе данных параметров также рассчитываются некоторые высокоуровневые параметры музыки, такие как музыкальный жанр, с помощью классификации методом k-ближайших соседей.
## Критерии сравнения аналогов
### Скорость
В связи с запросами современных пользователей по ожидаемому времени отклика приложения данный критерий является одним из самых важных.
### Точность расчетов 
Потеря информации о композиции при расчетах ведет к дальнейшему ухудшению работы приложения на стадии сравнения композиций по параметрам и  при поиске подобных.
### Возможность применения в приложении по поиску подобной музыки
Пользователь имеет возможность производить поиск для абсолютно любой композиции, поэтому разрабатываемая система должна рассчитывать параметры для музыки различных жанров, стилей и т.д.
## Таблица сравнения по критериям
Аналог\Критерий | Скорость | Точность расчетов | Возможность применения
--------------- | -------- | ----------------- | ----------------------
Экспертная система | + | + | -
Приложение jSymbolic | + | - | +/-
Приложение jAudio | - | + | +
## Выводы по итогам сравнения
В таблцие сравнения по критериям было показано, что экспертная система быстро и точно работает в случае некторых жанров (классической музыки), тогда как для других жанров подробного теоретического описания не имеется, что делает невозможным использование такой системы в поиске подобной музыки. Расчет высокоуровневых параметров на основе данных в формате MIDI позволяет обрабатывать любую музыку, однако при преобразовании композиций к формату MIDI теряется информация о звуках, которые невозможно синтезировать, в частности, полностью пропадает наличие вокала. Расчет низкоуровневых параметров является медленным по сравнению с другими аналогами в связи с необходимостью получения высокоуровневых параметров (жанра, ритма и т. д.) с помощью классификации. По результатам сравнения аналогов можно сделать вывод, что развитие метода расчета низкоуровневых параметров в сторону ускорения непосредственно расчета или дальнейшей классификации позволит получить быстро работающую систему при этом с точным расчетом параметров и возможностью производить этот расчет для любых композиций.
## Источники
1. McKay, C., and I. Fujinaga. 2006a. jSymbolic: A feature extractor for MIDI files. Proceedings of the International Computer Music Conference. 302–5.
2. Tzanetakis,  G.,  G.  Essl,  and  P.  Cook.  2001.  Automatic musical  genre  classification  of  audio  signals.  Proceedings of the International Symposium on Music Information Retrieval. 205–210.
3. McEnnis, D., C. McKay, I. Fujinaga, and P. Depalle. 2005. jAudio: A feature extraction library. Proceedings of the International Conference on Music Information Retrieval. 600–3.