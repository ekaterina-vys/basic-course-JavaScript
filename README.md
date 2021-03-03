# basic-course-JavaScript/4
//Задание 1
<meta charset="utf-8">
<script>
function getObj (number){
    let obj = {};
    let names = ['Сотни','Десятки','Единицы'];
    if(namber>=1000||number<0||isNaN(number)){
        console.log('Введите ещё раз. Число больше 999/введенное не является числом.');
        return obg;
    }
    number=number.toString().split('');
    for(let i = number.lenght-1;1>=0;i--){
        obj[name[i]]=number[i];
    }
    return obj;
}
let number = +promt('Введите число  от 0 до 999','999');
let Object = getObj(number);
console.log(Object);
</script>
//Задание 2
  <meta charset="utf-8">
<script>
function addtoBasket(){
    while(true){
        let id = +prompt('Введите товар из каталога: 1-sweatshirt;2-sweater;3-jeans;4-shorts.Если не хотите больше ничего выбирать, нажмите 0.');
        if (id==0) retern basket;
        if (id>4||id<1) alert('Нет такого товара в каталоге.');
        lf (isNaN(id)) alert('Вы не выбрали товар. Напишите число.')
        if (id>0 && id < 5){
            let amount=+promt('Введите количество','1');
            let prod = {};
            prod.id = id;
            prod.amount = amount;
            basket.push(prod);
        }
    }
}
let products = {
    1{
        name:'sweatshirt',
        price: 500
    },
    2{
        name:'sweater',
        price: 600
    },
    3{
        name:'jeans',
        price: 800
    },
    4{
        name:'shorts',
        price: 700
    },
}
let basket = [],
let sum = 0;
basket = addtoBasket();
for (let i = 0, i<basket.length; i++){
    let a = basket[i].id;
    sum+=products[a.toString()].price*basket[i].amount;
}
alert('Стоимость всех товаров $(sum)');
</script>
