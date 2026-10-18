# Источники словаря организаций

Cutter3000: источники встроенного словаря организаций

4000 разных существительных отобраны из русских названий фильмов и сериалов Wikidata. Структурированные данные Wikidata распространяются по CC0: https://www.wikidata.org/wiki/Wikidata:Licensing
Запрос: SELECT DISTINCT ?title WHERE { VALUES ?kind { wd:Q11424 wd:Q5398426 } ?work wdt:P31 ?kind; rdfs:label ?title. FILTER(LANG(?title)="ru") } LIMIT 60000
Дата получения: 16.10.2026. Использованы 48014 полных строк ответа. Для слов сохранено происхождение в документации исходников проекта. Дополнительно включены экранные вымышленные названия. Итог: 4074 разные записи. Это словарь названий для тестовых данных; наличие названия не означает отсутствие одноименной реальной организации или разрешение использовать товарный знак.

Фильтр существительных: https://github.com/Harrix/Russian-Nouns — использован только текстовый список для отбора, чужой код не выполнялся. Слова с явной ненормативной и сексуальной лексикой и технические обозначения каталогов отсеяны. Применена следующая лицензия фильтра:
# The MIT License

Copyright © 2018-present Sergienko Anton

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Происхождение 4000 слов](organization-dictionary-provenance-20261016.json). Отдельные названия добавлены вручную; общий список хранится в текстовом макете расширения.
