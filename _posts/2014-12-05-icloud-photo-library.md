---
layout: post
title: Как загрузить фотографии в iCloud Photo Library
description: Как загрузить большое количество фотографий в iCloud Photo с корректными метаданными
date: 2014-12-05 13:10
comments: true
categories: iCloud Drive iOS Photo OSX
icon: iCloudPhoto_icon.png
---

В общем я тут переключил iCloud на 200GB план с одной целью – загрузить в Photo Library все фотографии, которые у меня по старинке хранились в iPhoto (80GB). Редактировать фотографии гораздо удобнее на iPad, чем на маке, кроме того мне надоело переносить фотографии в iPhoto и теперь вся коллекция будет всегда с собой и занимает не очень много места.

Но как загрузить 80GB фото и видео в iCloud пока Apple не выпустила приложение для OS X? Есть несколько способов, но не все из них одинаково полезны.

## Загрузка через веб-интерфейс iCloud.com

Казалось бы самый очевидный способ, но есть одна проблема – почему-то у всех загружаемых фотографий дата на следующие сутки от фактической. Видимо не учитывает часовой пояс или что-то ещё в этом роде. Т.к. для меня даты фотографий очень важны, то этот способ не подходит.

## Программы со встроенными файл-менеджерами на iOS

Пробовал [Documents by Readdle](https://itunes.apple.com/ru/app/documents-5-bystryj-prosmotrsik/id364901807?mt=8&at=10lbPv) и [GoodReader](https://itunes.apple.com/ru/app/goodreader/id777310222?mt=8&at=10lbPv) – портят мета-информацию в экспортируемых изображениях (стирают дату съемки, местоположение и т.д.). Потом нашел все-таки файл-менеджер, который не портит метаданные: [Stash](https://itunes.apple.com/ru/app/stash-private-photos-videos/id364575517?mt=8&at=10lbPv). [А вот статья](http://www.macstories.net/ios/importing-photos-in-icloud-photo-library-on-ios-with-correct-dates-and-metadata/), описывающая решение этой проблемы при помощи Stash, но я не хотел покупать её только из-за этого и решил сначала посмотреть другие варианты. И они нашлись.

## Dropbox

Было бы логично положить фотографии в какой-нибудь облачный диск, а оттуда сохранить их в приложении на iOS. Честно говоря, я пробовал только Dropbox, и он позволяет делать это только по одной фотографии. Правда мета-данные он не портит, что уже хорошо. Другие облачные хранилища не пробовал т.к. нашел наконец-то самый удобный для меня способ.

## AirDrop, ТА-ДА!

У AirDrop тоже есть ограничение на количество файлов (оно варьируется непонятным мне образом, но обычно можно отправить за раз около 100 файлов), но это все равно самый быстрый способ.

AirDrop отправляет данные очень быстро (аж стриминг видео из интернета подвисает), при этом не требует никаких дополнительных действий – фотографии просто складируются куда нужно, не приходится ничего нажимать на телефоне или планшете, только отправлять пачки файлов одна за другой с мака.

P.S. Будьте внимательны – у меня были ролики MOV с камеры, которые iOS почему-то не понимает. Если отправлять пачку фото и таких видео вместе, то AirDrop вам ничего не скажет, эти видео просто молча не попадут в библиотеку и всё. Поэтому, если видео не много, советую отдельно разобраться с фото и уже после аккуратно заливать видео.