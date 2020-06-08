# Zigbee to MQTT шлюз для корпуса D2MG на дин рейку.

<img src="https://github.com/badenbaden/sls-gateway-din-rail/blob/master/%D0%92%D0%B8%D0%B4%20%D1%81%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%BE%D0%BD%D0%B5%D0%BD%D1%82%D0%B0%D0%BC%D0%B8.png" data-canonical-src="https://github.com/badenbaden/sls-gateway-din-rail/blob/master/%D0%92%D0%B8%D0%B4%20%D1%81%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%BE%D0%BD%D0%B5%D0%BD%D1%82%D0%B0%D0%BC%D0%B8.png" height="500"/><img src="https://github.com/badenbaden/sls-gateway-din-rail/blob/master/%D0%9F%D0%BB%D0%B0%D1%82%D0%B0%2C%20%D0%B2%D0%B8%D0%B4%20%D1%81%D0%B2%D0%B5%D1%80%D1%85%D1%83.png" data-canonical-src="https://github.com/badenbaden/sls-gateway-din-rail/blob/master/%D0%9F%D0%BB%D0%B0%D1%82%D0%B0%2C%20%D0%B2%D0%B8%D0%B4%20%D1%81%D0%B2%D0%B5%D1%80%D1%85%D1%83.png" height="500"/><img src="https://github.com/badenbaden/sls-gateway-din-rail/blob/master/%D0%9F%D0%BB%D0%B0%D1%82%D0%B0%2C%20%D0%B2%D0%B8%D0%B4%20%D1%81%D0%BD%D0%B8%D0%B7%D1%83.png" data-canonical-src="https://github.com/badenbaden/sls-gateway-din-rail/blob/master/%D0%9F%D0%BB%D0%B0%D1%82%D0%B0%2C%20%D0%B2%D0%B8%D0%B4%20%D1%81%D0%BD%D0%B8%D0%B7%D1%83.png" height="500"/>


Плата тестовая, в железе не проверенная!!!

Версия шлюза zigbee to mqtt для корпуса D2MG на дин рейку.
Плату можно использовать как в корпусе на дин рейку, так и корпусе, напечатанном на 3Д принтере. Также есть возможность использования в качестве USB zigbee стика. 

Шлюз разрабатывался под прошивку SLS:
https://slsys.github.io/Gateway/
Всю информацию по прошивке, настройке и т.д. смотреть там.

Исходная версия схемы, на основе которой разработана плата:
https://modkam.ru/?p=1342

Для использовании в качестве шлюза не запаивать - C8, C9, R6, R7, R8.
Питание строго 5 вольт!!! Вводная клема питания соединена с разъемом USB и CH340E, при большем питании можно спалить что нибудь.

Для использования в качестве стика верхняя часть платы вообще не нужна (Все что выше CC2538), при желании обрезать плату.
не запаивать - C5, C6, С7, R1, R4, R5, U5, кнопку, H2, H3 (про верхнюю часть платы я уже говорил, там ничео не нужно паять).
запаивать - C8, C9, R6, R7, R8, CC2538+CC2592.






# sls-gateway-din-rail
Zigbee to MQTT gateway with din rail case D2MG

The zigbee to mqtt gateway version for the D2MG din rail enclosure.
The board can be used both in a DIN rail enclosure and in a case printed on a 3D printer. It is also possible to use a zigbee stick as a USB.
