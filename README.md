

## Перенос документов с разным составом реквизитов и табличных частей 

УНФ - > 3УП 2.5 

### Перенос Справочника "Физические лица"

- [Перенос с созданием ПКС для Реквизита  `Пол`](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/d1fa462fb965e831560643c50429c44e8303bd1c) - ***БЕЗ*** *контроля уникальности Кода Элемента*
- [Включена опция *Автоматически генерировать код, если он не задан*](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/ecbffb0f179d2ace20e96f5b308f64a9e0c10b52#diff-35fc13a27fda76ff80c6edd898bf98a0dc765efa8ec67b8ca9eac7e11e57d217) 
- [Отключен перенос Значения для Поля `Код`](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/4df0fe97a31fc14fd6693e6b368627d88138f3ac#diff-35fc13a27fda76ff80c6edd898bf98a0dc765efa8ec67b8ca9eac7e11e57d217)

### Перенос Справочника "Сотрудники"
 *все ссылки на коммиты  до PR* 

- [Перенос основных данных ](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/202b821f4a3577fdf55ee236883e852cb350ad18#diff-35fc13a27fda76ff80c6edd898bf98a0dc765efa8ec67b8ca9eac7e11e57d217)

- [Программная установка  свойств:  `Актуальность`, `ВидДоговора`, `ВидЗанятости`](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/715be295ea5f3007a9ce3cbade5b9f31c4dac6d7#diff-35fc13a27fda76ff80c6edd898bf98a0dc765efa8ec67b8ca9eac7e11e57d217) -  Обработчик `ПередВыгрузкой`

- [Программная установка Реквизита "Организация"](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/44eb18aa65771ae3276ae117cd9d0469032b25ee)



### Перенос Документа "Прием на работу"

- [Перенос основных данных ](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/588d8b294c0f5a893d9eedba45b9815c29c93469#diff-35fc13a27fda76ff80c6edd898bf98a0dc765efa8ec67b8ca9eac7e11e57d217)

- [Заполнение поля `Краткий Состав Документа` (Форма Списка)](https://github.com/alex-dev-2020/ConvSB1.6toHRM2.5/commit/22dd2b3c4bd5c7ae0a618e561714b37db270222d#diff-35fc13a27fda76ff80c6edd898bf98a0dc765efa8ec67b8ca9eac7e11e57d217) -  Обработчик `ПослеЗагрузки`

