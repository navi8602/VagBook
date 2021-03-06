---
layout: docs
title: Визуальное отображение помощи при парковке в MMI
weight: '12'
description: Визуальное отображение помощи при парковке MMI
keywords: Визуальное отображение помощи при парковке MMI
date: 2020-04-05T13:38:35.713Z
---
## Визуальное отображение помощи при парковке в MMI

{{<hint info>}}В блоке управления системой помощи при парковке вы можете активировать визуальное отображения на дисплеи системы помощи при парковке через MMI на Audi A1 8X. Работает только на моделях с PDC спереди и сзади!{{</hint>}}

### **Кодирование блока 10 (Система помощи при парковке)**

1. Выберете блок 10 (Система помощи при парковке)
2. Права доступа: Введите код доступа 71679
3. Длинное кодирование: найдите байт 0 и поставьте галочку в бит 3\
   (08 выбрать визуальный дисплей активен (BAP NEW))

{{<hint warning>}}Перезагрузите MMI (нажмите и удерживайте клавишу возврата (назад), кнопку подтверждения и клавишу навигации, одновременно. Затем MMI выключается и перезапускается. Занимает около 60 секунд){{</hint>}}

![MMI RESET AUDI A1 8X](/images/uploads/MMI-3G-RESET.png "MMI RESET AUDI A1 8X")


### Кроме того, дисплей не должен работать с активным битом 3

1. Длинное кодирование: найдите байт 0 и поставьте галочку в бит 2\
   (04 выбрать визуальный дисплей активен (BAP ALT))
2. Уберите галочу с бит 3

{{<hint danger>}}И помните, что все манипуляции с блоками и кодировкой, Вы делаете на свой страх и риск.{{</hint>}}