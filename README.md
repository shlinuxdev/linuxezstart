Linux EZ start repo

To start work with linuxezstrat download and install AM335xSDK  07_00_00_00 from http://software-dl.ti.com/sitara_linux/esd/AM335xSDK/latest/index_FDS.html
Follow instructions in SDK Docs.
Be sure that you use x86 or x64 platform.

Чтобы начать работать с linuxezstart скачайте и установите AM335xSDK  07_00_00_00 из http://software-dl.ti.com/sitara_linux/esd/AM335xSDK/latest/index_FDS.html
Следуйте инструкциям из документации.
Для 32-х и 64-хбитных систем тербования к настройке системы могут быть разными.

Для тех кто устанваливает на Ubuntu версии отличной от 10.04 и 12.04:
после запуска .bin и распаковки файлов в указанный каталог, находим в каталоге bin файл setup-host-check.sh
В 42 строке добаляем версию Вашего дистрибутива Ubuntu (например для 14.04: -a "$host" != "trusty") для обхода проверки версии Ubuntu
