# Уровень 2: расширенные тесты #

баллы:
  * **2** - тест пройден в полном объеме
  * **1** - скорее пройден, чем не пройден: _тест или пройден с некоторыми незначительными недочетами, или для работы потребовалось совершить незначительные дополнительные настройки, или установить дополнительное программное обеспечение_
  * **-1** - скорее не пройден, чем пройден: _тест проходит не в полном объеме, существующие проблемы или не устранимы, или их устранение требует специальных навыков и серьезной модификации системы (пересборка ядра)_
  * **-2** - тест не пройден вообще


статус:
  * ![http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png](http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png) **pass** - тест пройден (баллы 2)
  * ![http://en.opensuse.org/images/thumb/b/bc/Icon-cross.png/22px-Icon-cross.png](http://en.opensuse.org/images/thumb/b/bc/Icon-cross.png/22px-Icon-cross.png) **fail** - тест не пройден (баллы от -2 до 1)
  * ![http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png](http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png) **N/A** - тест не выполнялся

<a href='Hidden comment: 
###############################################
************** Оборудование *******************
###############################################
'></a>

# Оборудование #

<table border='1px'>

<tr>
<td><i><b>Тест</b></i></td><td><i><b>Подробнее</b></i></td><td><i><b>Баллы</b></i></td><td><i><b>Статус</b></i></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Видео **************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Видео: 3-D, композитинг</h2></td><td></td><td></td><td></td>
</tr><tr>
<td width='50px' /><td>поддержка 3-D ускорения</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr><tr>
<td /><td>работа 3-D эффектов в текущем оконном менеджере (compiz/kwin)</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr>

<tr>
<td /><td><h3>Работа 3-D программ</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>glxgears</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr><tr>
<td /><td>blender</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>3D-mark (аналог от phoronix)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>warsaw</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>xmoto</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<tr>
<td /><td><h3>Совместная работа 3-D программ</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>Несколько окон с 3D играми, блендером (стабильность работы, переключение по alt+tab)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Несколько окон с 3D играми + полноэкранная игра (стабильность работы, переключение по alt+tab)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<tr>
<td /><td><h3>Совместная работа композитинга и 3-D программ</h3></td>
<td></td>
<td></td><td></td>
</tr><tr>
<td /><td>Несколько окон с 3D играми, блендером (стабильность работы, переключение по alt+tab)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Несколько окон с 3D играми + полноэкранная игра (стабильность работы, переключение по alt+tab)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<tr>
<td /><td><h3>Разное</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>Выход из ВСЕХ полноэкранных приложений (игр) должен работать по alt+tab</td>
<td>
<a href='http://code.google.com/p/perfectdesktop/wiki/tc_HW_Video_FullscreenAltTab'><img src='http://www.gstatic.com/codesite/ph/images/tearoff_icon.gif' /></a>
</td>
<td>-1</td><td><img src='http://en.opensuse.org/images/thumb/b/bc/Icon-cross.png/22px-Icon-cross.png' /></td>
</tr><tr>
<td /><td>Аналогично - во ВСЕХ полноэкранных приложениях (играх) должны работать все глобальные горячие клавиши - например регулятор громкости на мультимедиа-клавиатуре</td>
<td>
<a href='http://code.google.com/p/perfectdesktop/wiki/tc_HW_Video_FullscreenHotKeys'><img src='http://www.gstatic.com/codesite/ph/images/tearoff_icon.gif' /></a>
</td>
<td>-1</td><td><img src='http://en.opensuse.org/images/thumb/b/bc/Icon-cross.png/22px-Icon-cross.png' /></td>
</tr><tr>
<td /><td>При возвращении в игру все должно продолжиться без проблем</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Suspend (Disk/RAM) должен корректно работать для полноэкранных запущенных игр и для оконных 3D игр тоже</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Звук **************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Звук</h2></td><td></td><td></td><td></td>
</tr><tr>
<td /><td><h3>Совместная работа разных программ</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>skype+amarok</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>flash+amarok</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Включение и выключение *********
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Включение и выключение</h2></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>Suspend to disk</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Suspend to RAM</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Спикер *************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Спикер</h2>
Спикер должен быть выключен по умолчанию ВЕЗДЕ</td><td></td><td></td><td></td>
</tr><tr>
<td /><td>в терминале по ctrl+alt+f1 при нажатии tab не должен пищать</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr><tr>
<td /><td>в xterm при нажатии tab не должен пищать</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr><tr>
<td /><td>по ctrl+alt+backspace не должен пищать (при включенной защите от случайного перезапуска X-сервера найти другой способ оповестить пользователя о том, что эта операция опасна)</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr>
</table>



<a href='Hidden comment: 
###############################################
************** Мультимедиа ********************
###############################################
'></a>

# Мультимедиа #

<table border='1px'>

<tr>
<td><i><b>Тест</b></i></td><td><i><b>Подробнее</b></i></td><td><i><b>Баллы</b></i></td><td><i><b>Статус</b></i></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Видео **************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Видео</h2></td><td></td><td></td><td></td>
</tr><tr>
<td width='50px' /><td>Возможность выбора звуковой/видео дорожки</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<tr>
<td /><td><h3>Горячие клавиши</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>пробел: пауза/играть</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr><tr>
<td /><td>стрелки вправо/влево: перемотка на небольшой отрезок</td>
<td>
<a href='http://code.google.com/p/perfectdesktop/wiki/tc_MM_Video_HKeys_LeftRight'><img src='http://www.gstatic.com/codesite/ph/images/tearoff_icon.gif' /></a>
</td>
<td>1</td><td><img src='http://en.opensuse.org/images/thumb/b/bc/Icon-cross.png/22px-Icon-cross.png' /></td>
</tr><tr>
<td /><td>pg up/pg down: перемотка на большой отрезок</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr><tr>
<td /><td>alt+enter/двойной клик: переключение полноэкранного и оконного режимов</td>
<td></td>
<td>2</td><td><img src='http://en.opensuse.org/images/thumb/4/4f/Icon-checked.png/22px-Icon-checked.png' /></td>
</tr>

<tr>
<td /><td><h3>Субтитры</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>Автоматическая подгрузка</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Выбор файла вручную</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Задание смещения</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Корректное чтение русских субтитров (проверить разные форматы в разных кодировках)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>
</table>



<a href='Hidden comment: 
###############################################
************** Интернет ***********************
###############################################
'></a>

# Интернет #

<table border='1px'>

<tr>
<td><i><b>Тест</b></i></td><td><i><b>Подробнее</b></i></td><td><i><b>Баллы</b></i></td><td><i><b>Статус</b></i></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Флеш - плагин от Adobe *********
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Флеш - плагин от Adobe</h2></td><td></td><td></td><td></td>
</tr><tr>
<td width='50px' /><td>общая работоспособность - открыть пару сайтов (youtube и какую-нибудь игрушку)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>полноэкранный режим (не должен вешать систему)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>проверить как работает звук совместно с другими программами (см предыдущие тесты)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Skype **************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Skype</h2></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>Качественный звук в обоих направлениях</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Web-камера</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>Совместная работа звука с другими программами (см предыдущие тесты)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** Jabber *************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>Jabber</h2></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>логин</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>обмен сообщениями (в русской кодировке)</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>обмен файлами</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<tr>
<td /><td><h3>Gtalk/jingle</h3></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>голосовой вызов</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>видео через веб-камеру</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>

<a href='Hidden comment: 
***********************************************
************** ICQ ****************************
***********************************************
'></a><br>
<br>
<tr>
<td><h2>ICQ</h2></td><td></td><td></td><td></td>
</tr><tr>
<td /><td>логин</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>обмен сообщениями в русской кодировке</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>прием оффлайн-сообщений в русской кодировке</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>обмен файлами</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr><tr>
<td /><td>(необязательно) поддержка звуковых тем/смайликов</td>
<td></td>
<td></td><td><img src='http://en.opensuse.org/images/thumb/5/57/Icon-question.png/22px-Icon-question.png' /></td>
</tr>
</table>