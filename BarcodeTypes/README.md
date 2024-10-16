## Типы штрих кодов для классификации

### Одномерные:

#### Code-39
имя для разметки: **"code_39"**  
Одномерный штрихкод, который поддерживает цифры, буквы латинского алфавита и несколько специальных символов. Используется в логистике и маркировке товаров и пропусков.

![code_39](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/code-39.png)

Соотношение сторон может варьироваться, но обычно составляет около 3:1 между шириной и высотой.

#### EAN-8
имя для разметки: **"ean_8"**  
Компактный вариант EAN-13, содержащий 8 цифр. Применяется для маркировки небольших товаров, на которых нет места для более длинных штрихкодов.

![ean-8](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/ean-8.png)

Стандартный размер EAN-8 имеет фиксированную пропорцию ширины к высоте, которая обычно составляет 73.42% по ширине к высоте (т.е., ширина примерно на 30% меньше высоты).

#### EAN-13
имя для разметки: **"ean_13"**  
Наиболее распространенный штрихкод в мире, состоящий из 13 цифр. Используется для маркировки розничных товаров и отслеживания в системах логистики.

![ean-13](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/ean-13.png)

Как и EAN-8, имеет фиксированную пропорцию, соотношение ширины к высоте обычно около 73.42%.

#### EAN-128
имя для разметки: **"ean_128"**  
Расширенный вариант стандартов EAN, содержащий больше информации, включая символы ASCII. Подходит для использования в транспортировке и логистике.

![ean-128](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/ean-128.png)

Зависит от количества закодированных данных, но обычно соотношение сторон соответствует традиционным вертикально ориентированным штрихкодам.

#### Interleaved 2 of 5
имя для разметки: **"interleaved_2_of_5"**  
Одномерный штрихкод, числовой, где цифры закодированы попарно, что обеспечивает высокую плотность данных. Широко используется в складских системах и инвентаризации.

![interleaved 2 of 5](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/interleaved_2_of_5.png)

Соотношение может варьироваться в зависимости от количества данных, обычно ширина штрихов к пробелам составляет 3:1.

#### UPC-A
имя для разметки: **"upc_a"**  
Распространенный в Северной Америке штрихкод, состоящий из 12 цифр. Используется для идентификации товаров в розничной торговле.

![upc-a](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/upc-a.png)

Имеет фиксированное соотношение, как правило, около 73.42%.

#### UPC-E
имя для разметки: **"upc_e"**  
Компактная версия UPC-A, предназначенная для упаковки малого размера, где необходимо сократить длину штрихкода.

![upc-e](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/1D/upc-e.png)

Сжаленный вариант UPC-A, также сохраняет пропорцию около 73.42%.

### Двумерные:

#### Aztec Code
имя для разметки: **"aztec_code"**  
Двумерный штрихкод, способный кодировать большие объемы данных на небольшом пространстве. Часто используется в билетах и транспортных приложениях.

![aztec_code](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/2D/AztecCode.png)

Форма кодировки — квадратная, так что соотношение сторон близко 1:1.

#### Data Matrix
имя для разметки: **"data_matrix"**  
Квадратный или прямоугольный двумерный штрихкод, который может закодировать большое количество информации. Часто используется в маркировке мелких объектов, таких как электронные компоненты.

![data_matrix](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/2D/DataMatrix.png)

Также имеет квадратную или прямоугольную форму, поэтому соотношение сторон для квадратных символов составляет 1:1.

#### MaxiCode
имя для разметки: **"maxi_code"**  
Двумерный штрихкод, разработанный для высокоскоростного сканирования и используемый в основном в логистике и транспортных системах, особенно для почтовых и курьерских услуг.

![maxi_code](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/2D/MaxiCode.png)

Максимальная кодовая зона круглая (гексагональная структура), и по существу имеет соотношение сторон 1:1, хотя визуально выглядит не как квадрат.

#### PDF417
имя для разметки: **"pdf_417"**  
Широкоформатный двумерный штрихкод, способный включать в себя большие объемы данных, такие как текстовые документы или фотографии. Применяется в удостоверениях, проездных билетах и документах.

![pdf417](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/2D/PDF417.png)

Этот штрихкод прямоугольной формы, соотношение ширины к высоте варьируется в зависимости от количества данных, обычно от 2:1 до 4:1.

#### QR
имя для разметки: **"qr"**  
Двумерный штрихкод, широко используемый благодаря своей высокой скорости сканирования и возможности хранения данных, таких как URL, контактная информация и прочее. Применяется в маркетинге, оплатах и прочих сферах.

![qr](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/2D/QR.png)

Квадратный штрихкод соотношение сторон 1:1.

### Смешанные:

#### Databar Expanded Stacked
имя для разметки: **"databar_expanded_stacked"**  
Гибридный штрихкод, который сочетает в себе плотность и компактность. Используется для маркировки фруктов, овощей и других товаров в розничной торговле, где требуется дополнительная информация, например, вес или цена.

![databar_expanded_stacked](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/other/databar_expanded_stacked.png)

Соотношение сторон может быть гибким и зависит от количества строк и закодированных данных, но в сложенном виде может иметь более вытянутую прямоугольную форму. Обычно это около 3:1 или больше по ширине.

Вот как должны выглядеть атрибуты разметки:
![regoin_attributes](https://github.com/CD7567/mipt2024f-4-common-knowledge/blob/BarcodeClassificator/BarcodeTypes/img/region_attributes.png)

в помощь определитель типов штрихкодов - [ASPOSE](https://products.aspose.app/barcode/ru/recognize#)