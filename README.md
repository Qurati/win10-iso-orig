# Образ Windows 10

## MediaCreationTool
> [!TIP]
> **Используйте VPN.** MediaCreationTool откроется только при условии, что вы не находитесь в рф

Через MediaCreationTool не выйдет сразу создать загрузочную флешку, по крайней мере у меня не вышло, поэтому создаём ISO-образ и загоняем на флешку

-[Программа на google диске проекта](https://drive.google.com/drive/folders/1bjeIDKUrnl0hw7dgoK7dIvRZ43yTh653?usp=sharing)

-[Сайт Microsoft **(только с VPN)**](https://download.microsoft.com/download/9/e/a/9eac306f-d134-4609-9c58-35d1638c2363/MediaCreationTool_22H2.exe)

## Загрузка образа на флешку
>[!IMPORTANT]
>**rufus будет ругаться** на загрузчик UEFI, но ничего страшного нет

Загрузка образа осуществляется при помощи программы rufus, которая также есть на google диске. Ничего сложного в этом нет.
1. Установить ISO-образ c [google диска](https://drive.google.com/drive/folders/1bjeIDKUrnl0hw7dgoK7dIvRZ43yTh653?usp=sharing) или создать самим через MediaCreationTool. Разницы нет
2. Взять флешку от 8гб на которую будет осуществляться загрузка Windows и **отформатировать** её в формате **FAT32**. 
3. После этого заходим в rufus и в поле "Устройство" выбираем нужный нам накопитель. 
4. В строке «Метод загрузки» кликнуть по кнопке «Выбрать», и указать путь к сохраненному ISO-образу.
5. В графе «Схема раздела» отметить соответствующую таблицу разделов: MBR или GPT. Это повлияет на пункт «Целевая система».
6. В поле «Новая метка тома» можно задать название для флешки.
7. В строке «Файловая система» отобразится доступный вариант, который зависит от выбора «Схемы раздела» в пункте 5. Для MBR — только NTFS, для GPT — NTFS или FAT32 (приоритетный).
8. Нажать кнопку «Готов». Подтвердить намерение форматирования в окне предупреждения. Дождаться завершения процедуры.

-[сайт Rufus](https://rufus.ie/downloads/)

-[Программа на google диске проекта](https://drive.google.com/drive/folders/1bjeIDKUrnl0hw7dgoK7dIvRZ43yTh653?usp=sharing)

 ## Ссылки

-[Google диске проекта, где хранятся нужные программы и ISO-образ](https://drive.google.com/drive/folders/1bjeIDKUrnl0hw7dgoK7dIvRZ43yTh653?usp=sharing)

-[Сайт загрузки Rufus](https://rufus.ie/downloads/)

-[Сайт Microsoft, где можно установить MediaCreationTool самому **(только с VPN)**](https://download.microsoft.com/download/9/e/a/9eac306f-d134-4609-9c58-35d1638c2363/MediaCreationTool_22H2.exe)
