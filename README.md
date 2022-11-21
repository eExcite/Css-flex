# Css-flex
Про flex для HTML



 .conteiner 
{
    display: flex;
    flex-basis: 33%;
    
}

.item
{
    padding: 40px;
    font-size: 25px;
    border: 1px solid black;
    width: fit-content;
    height: fit-content;
}

.item_1
{
    
}

.item_2
{
    
}

.item_3
{
    
}


/* 

главная ось - Х
второстепенная ось - Y
Оси могут меняться из-за flex-ов 

justify-content - выравнивание относительно главной оси 

justify-content: space-between; делает одинаковое растояние между элементами
justify-content: space-around; делает одинаковые отступы со всех сторон
justify-content: center; помещает элемент в середину основной оси
justify-content: flex-end; помещает в конец оси(flex-start помещает в начало)


align-items - выравнивание относительно второстепенной оси

align-items: center; - помещает в центр всего контейнера
align-items: flex-start; - помещает в начало контейнера
align-items: flex-end; - помещает в конец контейнера

align-self - редактирует отдельные элементы

align-self: center; - помещает в центр всего контейнера
align-slef: flex-start; - помещает в начало контейнера
align-slef: flex-end; - помещает в конец контейнера



flex-direction - изменение основной оси

flex-direction: column; - все элементы становятся в колонку
flex-direction: column-reverse; - все элементы становятся в колонку в обратном порядке
flex-direction: row-reverse; - все элементы становятся в линию в обратном порядке
flex-direction: row; - все элементы становятся в линию

flex-wrap - редактирует длинну строки

flex-wrap: nowrap; - запрещает переносить элементы которые не вместились на новую строку
flex-wrap: wrap; - переносит элементы которые не вместились на новую строку 
flex-wrap: wrap-rewerse; - переносит элементы которые не вместились на новую строку в обратном порядке

flex-basis - растягивает элемент относительно главной оси

flex-shrink - отвечает за то как быстро будет ужиматься элемент

 */
