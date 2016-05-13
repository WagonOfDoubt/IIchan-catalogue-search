# 🔰 IIchan catalogue search
![Screenshot](http://i.imgur.com/yAVQmqY.png)
Userscript для поиска в каталоге имиджборды iichan.hk

### Установка
<pre>
1. Разумеется, сперва понадобится движок юзескриптов. 
Tampermonkey для Chrom[ium|e].
Greasemonkey для Firefox.
Violent monkey для Opera.

2. Далее выбирайте версию скрипта для вашего браузера. 
.es6.user.js для новых, в зависимости от того, <a href="http://kangax.github.io/compat-table/es6/">поддерживает</a> <a href="http://caniuse.com/#search=ES6">ли</a> его ваш браузер.
</pre>

### Использование
```
Скрипт ищет по мере набора фразы. Поиск регистронезависим.

Искaть можно по (без <>): 
- Номеру треда
- Теме треда
- Кусочку сообщения ОП-поста (который попадает в каталог)
<цукас> найдёт всех Цукас

- Дате (месяцу/дню/году/часу/минуте) создания треда
<января 2011> найдёт все треды, созданные в Январе 2011
<сентяб> найдёт все треды за Сентябрь
<2008> найдёт все треды за 2088 год
<18:00> найдёт все треды запощенные в шесть часов вечера

- Регулярному выражению
<$^> найдёт все треды без текста в ОП-посте
```


Должен работать в не слишкoм старых Chrome/Firefox/Opera. 

Был протестирован с Firefox 26 и Opera 12.


### Сборка (for advanced users)
```
git clone https://github.com/aslian/IIchan-catalogue-search.git
cd IIchan-catalogue-search
npm install
make
```
