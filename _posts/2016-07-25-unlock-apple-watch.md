---
published: false
draft: true
---
## Почему может не работать разблокировка macOS часами Apple Watch? Ответ здесь

Я в этом году практически полностью выпал из информационного потока. Но Apple Keynote я не мог пропустить, и там меня, среди прочего, заинтересовала функция разблокировка Мака с помощью часов.
На выходных я обновился до macOS Sierra и не обнаружил птичку для включения этой опции. Пишу этот пост чтобы помочь тем, кто столкнулся с такой же проблемой.

Оказывается, у Apple помимо старой "two-step" авторизации (когда на все устройства приходил короткий код для разблокировки) появился ещё и другой механизм "two-factor" авторизации. Во всех статьях пишут что должна быть включена двухфакторная авторизация, где-то даже прилагается скриншот на котором, на самом деле, включена старая two-step авторизация. В комментариях многие, судя по всему, не знают этого факта, и никто не напишет. Пришлось самому догадаться.

В общем, новая авторизация включается не через сайт управления Apple ID, а только с одного из устройств iOS 9 / OS X 10.11 и выше. Нужно отключить two-step авторизацию (если включена) и подключить новую two-factor через настройки iCloud на устройстве. Работает!