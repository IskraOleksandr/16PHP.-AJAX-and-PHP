--AJAX и PHP

Создать в БД табличку с полями Name (text), Surname (text), 
Country (text), City (text), Salary (integer) и записать туда 30 строк.
Создать страницу, где отобразить содержимое этой таблички в теге <table>. 
Добавить заголовок для тега <table> и фильтры для каждого столбца (сортировать 
по возрастанию и убыванию). Для полей City и Country добавить фильтр с существующими 
в таблице странами и городами (если страна повторяется несколько раз, в фильтре 
показывать ее только один раз) и для каждого из них добавить checkbox. 
При выборе checkbox отображать только те записи, в которых страна или город совпадает с выбором. 
Всю фильтрацию делать без перезагрузки страницы (при помощи AJAX отправлять выбранный фильтр, 
в методе на сервере фильтровать по переданному фильтру и возвращать отфильтрованную коллекцию, 
которую перерисовывать на стороне клиента в таблице).
![image](https://github.com/IskraOleksandr/16PHP.-AJAX-and-PHP/assets/140179368/c611c5a1-bfd4-4b53-a5c6-fc768d3e118b)
