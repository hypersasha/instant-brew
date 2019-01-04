<img src="http://vinnichenko.net/wp-content/uploads/2016/02/iOS-Style-Checkbox.jpg" width="120"/>

### Компонент `<Switch>`
Данный компонент добавляет элемент переключателя на страницу Вашего приложения.

```jsx
<Switch
    micro={true}
    onSwitch={(isActive) => { alert('im switched!'); }}
    label={"Переключалка"}
    />
```
Список props, которые может принимать данный компонент.

|Название|Тип|Описание|
| ------------ | ------------ | ------------ |
| label  | string  | Текст кнопки переключателя. |
| micro  | bool  | Включить уменьшенную версию кнопки переключателя.  |
| isActive | bool | Значение переключателя. Если данный prop указан, state-значение переключателя **игнорируется.** |
| onSwitch  | function  | Фукнция, вызываемая при изменении состояния переключателя. Принимает аргумент isActive (bool) - новое состояние переключателя.  |