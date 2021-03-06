---
layout: post
title: "Рецепты Hazel: автоматическая уборка рабочего стола"
date: 2013-10-18 10:26
comments: true
categories: OSX Workflow Hazel
icon: Hazel_icon.png
---
[Hazel](http://www.noodlesoft.com/hazel.php) это удобное средство для автоматизации действий с файлами и я скорее всего ещё не раз напишу о нём, т.к. я от него в восторге.

Основной принцип действия Hazel — выбираем папки для отслеживания и задаем для них набор правил и действий. Когда изменяются какие-то файлы в отслеживаемой папке, Hazel запускает цепочку соответствующих ей правил и, если правило сработало, запускаются соотвествующие ему действия.

### Уборка рабочего стола с Hazel

Рабочий стол у меня служит чем-то вроде временной папки. Само по себе название "рабочий стол" говорит о том, что это место для тех документов, с которыми ты в данный момент работаешь. Я никогда не понимал использование рабочего стола в качестве запускалки программ и полный отказ от рабочего стола (последнее активно практикуют линуксоиды, а первое — пользователи windows).

Каждый день мне по скайпу сбрасывают много файлов и больше всего скриншоты. Ими бывает просто заваливает в момент обсуждения какого-то рабочего момента. Некоторые даже отказываются принимать скриншоты через скайп и настаивают на использовании сервисов, таких как [monosnap](http://paul.elms.pro/blog/2013/04/15/sravnieniie-i-obzor-populiarnykh-oblachnykh-skrinshotierov/). Я не так принципиален и в результате мой рабочий стол был постоянно завален файлами, которые я просматривал из скайпа, а вот функции удалить полученный файл в скайпе небыло.

В общем, я хочу показать как Hazel убирает мой рабочий стол, сейчас я экспериментирую со следующей схемой. Все файлы на рабочем столе делятся на четыре группы: новые файлы (которые только что добавлены, помечаются синей меткой чтобы проще было их найти), обычные файлы (лежат дольше 30 минут), старые файлы (более суток, помечаются красным чтобы сигнализировать неизбежное). Ещё есть оранжевые файлы, такой меткой я помечаю те файлы, которые должны задержаться на рабочем столе дольше стандартной схемы.

Кроме того, в Hazel есть функция автоматической очистки корзины при превышении объема в 10gb (удаляются самые старые по очереди) и для файлов, залежавшихся более чем на неделю. Это на самом деле очень удобно и мне не приходится настаивать, чтобы коллеги присылали ссылки на скриншоты вместо файлов.
<!--more-->

### Проще всего показать эти правила на скриншотах

<a class="screenshot" href="https://www.monosnap.com/image/CCoIluBtxYcY03j6oqhSq8sML.png" rel="screenshot" title="Удаление старых файлов в корзину"><img src="https://www.monosnap.com/image/CCoIluBtxYcY03j6oqhSq8sML.png" alt="hazel" /></a>
<a class="screenshot" href="https://www.monosnap.com/image/36A2VH58Zbp1xbo9uv51HxnH7.png" rel="screenshot" title="Новые файлы"><img src="https://www.monosnap.com/image/36A2VH58Zbp1xbo9uv51HxnH7.png" alt="hazel" /></a>
<a class="screenshot" href="https://www.monosnap.com/image/jGoahTmJsud9N9FTiXnyMrfsr.png" rel="screenshot" title="Старые файлы, через 24 часа будут в корзине"><img src="https://www.monosnap.com/image/jGoahTmJsud9N9FTiXnyMrfsr.png" alt="hazel" /></a>
<a class="screenshot" href="https://www.monosnap.com/image/mXjYG40GAmE02YJnmItQxoCCF.png" rel="screenshot" title="Обычные файлы, без метки"><img src="https://www.monosnap.com/image/mXjYG40GAmE02YJnmItQxoCCF.png" alt="hazel" /></a>
<a class="screenshot" href="https://www.monosnap.com/image/BSsU5kh2E5vY8YsvouY0qYuTB.png" rel="screenshot" title="Правила очистки корзины"><img src="https://www.monosnap.com/image/BSsU5kh2E5vY8YsvouY0qYuTB.png" alt="hazel" /></a>