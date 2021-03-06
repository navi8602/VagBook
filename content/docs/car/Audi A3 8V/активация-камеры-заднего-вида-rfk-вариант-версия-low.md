---
layout: docs
title: Активация камеры заднего вида (RFK) - вариант | версия LOW
weight: "31"
description: Активация камеры заднего вида (RFK) - вариант | версия LOW
keywords: Активация камеры заднего вида (RFK) - вариант | версия LOW
date: 2020-04-26T11:16:57.604Z
---
## Активация камеры заднего вида (RFK) - вариант | версия LOW

{{< hint info >}}В информационно-развлекательном блоке управления вы можете активировать модернизированную / модифицированную камеру заднего вида на Audi A3 8V. Если на автомобиле установлена ​​оригинальная камера заднего вида (RFK) или точная камера, она может отображаться в MMI (навигационная система PLUS / RMC) после активации, если включена задняя передача. Помощь при парковке (датчики заднего хода) не является абсолютно необходимой{{< /hint >}}

### **Кодирование блока 5F (информационно-развлекательная система)**

1. Выберете блок 5F (информационно-развлекательная система)
2. Длинное кодирование
3. Адаптация
3. Выберите байт 19 и поставьте галочку в бит 4

{{< hint warning >}}если имеется парковочные датчики, их также необходимо отрегулировать следующим образом{{< /hint>}}

### **Кодирование блока 10 (система помощи при парковке)**

1. Выберете блок 10 (система помощи при парковке)
2. Длинное кодирование
3. Адаптация
3. Выберите байт 2 и поставьте галочку в бит 4

{{< hint danger >}}И помните, что все манипуляции с блоками и кодировкой, Вы делаете на свой страх и риск.{{< /hint>}}