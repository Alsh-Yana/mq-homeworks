# Карточка пользователя

## Описание

Заказы от фотографов продолжают поступать. Поэтому вы решили создать сайт, на котором каждый фотограф сможет разместить свое портфолио. Информация о каждом из фотографов будет представлена в виде карточек с контактными данными. Сейчас при всех разрешениях экрана такая карточка выглядит одинаково:
 
![User card layout current](../../sources/adaptive-layout-card-current.jpg)

Нужно изменить верстку таким образом, чтобы на устройствах с шириной экрана от `767px` и меньше или от `1301px` и больше карточка выглядела так: 

![User card layout target on a full & small screen](../../sources/adaptive-layout-card-target.jpg)

А на устройствах с шириной экрана в диапазоне от `768px` до `1300px` включительно — так:

![User card layout target on a tablet screen](../../sources/adaptive-layout-card-ipad.jpg)

## Процесс реализации

1. Если вы выполняете задание в песочнице CodePen, в начале работы добавьте в тег `<head>` этот метатег `<meta name="viewport" content="width=device-width, initial-scale=1.0">`. Если вы выполняете задание локально, этот метатег уже добавлен.

2. Для элемента с классом `profile__preview:before` добавить прозрачность `0.7` и цвет фона `#481bae` только для устройств, у которых ширина экрана от `767px` и меньше или от `1301px` и больше.

3. Для элемента с классом `profile` добавить цвет фона `#481bae` только для устройств, у которых ширина экрана в диапазоне от `768px` до `1300px` включительно. 

4. Для элемента с классом `profile__preview` добавить ширину и высоту по `140px`, сплошную рамку цветом `#ffffff` и шириной `5px` только для устройств, у которых ширина экрана в диапазоне от `768px` до `1300px` включительно. 

5. Закруглить углы у элемента с классом `profile__preview` только для устройств, у которых ширина экрана в диапазоне от `768px` до `1300px` включительно. 

6. Протестируйте на обычном мониторе. У вас должно получиться так:

![User card layout target on a desktop](../../sources/adaptive-layout-card-step0.jpg)

6. Протестируйте результат в эмуляторе, выбрав iPad. У вас должно получиться так:

![User card layout target on a tablet](../../sources/adaptive-layout-card-step1.jpg)

7. Протестируйте результат в эмуляторе, выбрав iPhone 4. У вас должно получиться так:

![User card layout target on a small screen](../../sources/adaptive-layout-card-step2.jpg)

## Реализация

Внесите изменения во вкладке CSS. [Перед началом работы сделайте форк пена](https://codepen.io/Netology/pen/WXEvVX).
