# Issue 01 Incorrect checkboxes visualisation

Completed checklist items are drawn incorrectly on MacOS: instead of a filled red square on a white background (as in Win version), a green square on a red background is displayed

Source: [Incorrect checkboxes visualisation](https://github.com/ryjjin/Obsidian-Dark-Graphite-Pie-theme/issues/1)


## Связанные тесты

### Obsidian (Win10)

- отрисовываются корректно (красный квадрат на белом фоне), когда открыто две и более вкладок, но при открытии одной вкладки во весь экран заметно, что отметка о выполнении растягивается меньше нужного (когда открыто две вкладки - такое слегка заметно только у чеклистов в цитатах)
- скобки чеклиста в эдит режиме немного выше центра строки
- при этом в превью режиме отметка чеклиста находится даже чуть-чуть ниже центра строки
- при изменении масштаба размер красного квадрата не изменяется (а размер элемента на фоне - меняется вместе с текстом), что приводит к ошибкам в отрисовке

![[Checkbox Obsidian Win10.png]]

### Obsidian (MacOS 10.13)

- в превью режиме отметка чеклиста выглядит как зеленый квадрат поверх красного фона
- скобки чеклиста в эдит режиме немного выше центра строки
- при этом в превью режиме отметка чеклиста находится заметно ниже центра строки
- при изменении масштаба красный фон пропадает, зеленый квадрат начинает отображаться на белом фоне, при некоторых значениях скейла рисуется ровно, при остальных - квадрат съезжает относительно центра фона

![[Checkbox Obsidian MacOS.png|320]]

### Publish: Opera (Win10)

- чеклисты пытаются отображаться так же, как приложении на Win, но получается пиратская копия: у всех элементов острые углы, красный квадрат немного меньше размером (или фон - чуть больше) - из-за чего видно штатную отметку о выполнении на фоне
- при скейле отрисовка слегка изменяется, но +- такая же

![[Checkbox Publish Opera Win10.png]]

### Publish: Firefox (Win10)

- чеклисты отображаются так, как будто вообще никаких настроек нет (обычные серые квадраты)
- при скейле отрисовка не изменяется

![[Checkbox Publish Firefox Win10.png]]

### Publish: Firefox (MacOS)

- чеклисты отображаются приятными синими флажками (т.е. как планировалось отображать на MacOS, но почему-то синим вместо красного)
- отметка чеклиста находится заметно ниже центра строки
- при скейлинге отрисовка не изменяется

![[Checkbox Publish Firefox MacOS.png|350]]

### Publish: Safari (MacOS)

- отметка чеклиста выглядит как красный квадрат поверх синего фона
- отметка чеклиста находится чуть ниже центра строки
- при скейлинге отрисовка не изменяется

![[Checkbox Publish Safari MacOS.png|350]]

### Publish: Firefox (Android)

- чеклисты отображаются приятными синими флажками
- отметка чеклиста немного смещена влево, из-за чего самый край не влезает на экран
- отметка чеклиста находится ровно по центру строки
- при скейлинге отрисовка не изменяется

![[Checkbox Publish Firefox Android.png|350]]

### Publish: Chrome (Android)

- чеклисты отображаются в стиле клиента Obsidian на Win (красный квадрат на белом фоне)
- отметка чеклиста немного смещена влево, из-за чего упирается в левый край экрана
- отметка чеклиста находится ровно по центру строки
- красный квадрат в изначальном масштабе страницы почему-то отрисовывается как прямоугольник, который заходит на боковые грани фона и не доходит до нижней грани
- при увеличении масштаба отрисовка становится более корректной

![[Checkbox Publish Chrome Android.png|420]]

### Publish: Firefox, Safari, Chrome (iOS)

- на всех браузерах на айпаде отображается одинаково: отметка чеклиста выглядит как красный квадрат поверх серого фона, на сером фоне видно белую отметку о выполнении
- при скейлинге отрисовка не изменяется

![[Checkbox Publish Safari iOS.png|400]]

## Решение

