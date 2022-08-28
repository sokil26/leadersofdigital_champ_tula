# leadersofdigital_champ_tula
Решение для цифрового прорыва  тула
Мое решение основывается на предсказании так называемых временных рядов, в которых надо предсказать следующие значения по предыдущим.

В качестве модели я использовал LAMA  от сбера.

Ключевой особенностью решения является обогащение данных дополнительным признаком - численность населения. Ещё я отчистил данные от населенных пунктов, информации о которых, нет после 2019 года в датасете, что облегчило сбор данных. Так же важную роль сыграла последующая обработка предсказания модели:

модуль от предсказанных значений
округление при помощи round а не int

для получения данных о численности населения запустите файл ``parser.py``
