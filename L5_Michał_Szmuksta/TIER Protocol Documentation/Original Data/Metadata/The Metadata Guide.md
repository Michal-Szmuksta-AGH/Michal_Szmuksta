## Metadata guide


"drinks.csv":
Jest to zbiór danych zawierający informację o średniej rocznej ilości serwowanych alkoholi na osobę w danym państwie.
Średnia pojemność kufla, kieliszka i szota zostały przyjęte na podstawie poniższych danych:
https://www.rethinkingdrinking.niaaa.nih.gov/How-much-is-too-much/what-counts-as-a-drink/whats-A-Standard-drink.aspx.
Dane pochodzą z roku 2010 i dotyczą ludzi w wieku 15 lat i powyżej. Zaprezentowane dane pochodzą z światowej organizacji
zdrowia (World Health Organisation, Global Information System on Alcohol and Health (GISAH), 2010) i są dostępne pod linkiem:
https://github.com/fivethirtyeight/data/tree/master/alcohol-consumption
Poniżej przedstawiono opis każdej kolumny tabeli:
- Nazwa państwa, którego dotyczy badanie w języku Angielskim.
- Średnia roczna liczba kufli piw serwowanych na osobę.
- Średnia roczna liczba kieliszków wina serwowanych na osobę.
- Średnia roczna liczba szotów alkoholu spirytusowego serwowanego na osobę.
- Średnia roczna ilość czystego alkoholu spożywanego przez osobę.


"countries-continents.csv":
Jest to zbiór danych zawierający nazwy państw i przyporządkowane im nazwy kontynentów na których się znajdują.
Dane pochodzą z następującego źródła:
https://github.com/dbouquin/IS_608/blob/master/NanosatDB_munging/Countries-Continents.csv.
Poniżej przedstawiono opis każdej kolumny tabeli:
- Nazwa kontynentu na którym leży dane państwo w języku Angielskim.
- Nazwa państwa, którego w języku Angielskim.


"countries-continents_additional_data.csv":
Jest to zbiór danych uzupełniających zbiór "countries-continents.csv" o niewystępujące w nim rekordy, a występujące w
"drinks.csv" z uwagi na inną nazwę państwa czy też inny zapis nazwy państwa w języku Angielskim. Zbiór jest stworzony
ręcznie za pomocą skryptu Creating_additional_table.py w folderze Command Files. Informacje użyte do stworzenia bazy
są dostępnych w serwisie Wikipedia: https://en.wikipedia.org/wiki/Main_Page.
Poniżej przedstawiono opis każdej kolumny tabeli:
- Nazwa kontynentu na którym leży dane państwo w języku Angielskim.
- Nazwa państwa, którego w języku Angielskim.


 

