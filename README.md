# shohruhtehnikum.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homework 5</title>
<style>
 *{
    box-sizing: border-box;
 }
 body {margin: 0;
background-color:#f1f1f1ca}
 .homework {
    background-color:  #a5aaaf;
    padding: 20px;
    text-align: center;
    font-size: 30px;
 }
 .tabl1 {
    padding: 20px 50px;
    color: #43130c;
    font-size: 20px;
 }
 li {
    background: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/29841/arrow.png") 0 50% no-repeat;
    list-style-type: none;
    padding-left: 15px;
    font-size: 20px;
    transition: all 0.1s;
    width: max-content;
 }
 li:hover {
    background: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/29841/arrow.png") 5 50% no-repeat;
    list-style-type: none;
    padding-left: 20px;
    font-size: 25px;
    height: min-content;

 }
 .tabl1 p {
    font-size: 30px;
 }
 .psevk {
    padding: 100px 50px;
    color: #43130c;
    font-size: 20px;
    float: left;
    width: 50%;

 }
 .pseve {
    padding: 100px 50px;
    color: #43130c;
    font-size: 20px;
    float: left;
    width: 50%;

 }
 .table {
    padding: 20px;
    text-align: center;
    font-size: 20px;

 }
  table{
    border: 10px color black;
    background-color:rgba(0, 255, 255, 0.367);
    margin: auto;
    border-collapse:collapse;
 }
 table th{
border: 2px solid black;
padding: 20px 30px;
 }
 table td {
    border: 2px solid black;
    padding: 20px 30px;
    transition: all 0.3s;
     }
table tr{
    transition: all 0.5s;
}
     table tr:hover{
    background-color:azure;
}
.psevs{
    padding: 100px 50px;
    color: #43130c;
    font-size: 20px;
    float: left;
    width: 50%;
}
.psevv{
    padding: 100px 50px;
    color: #43130c;
    font-size: 20px;
    float: left;
    width: 50%;
}
.comment{
    background-color:#f1f1f1;
    padding: 20px;
    text-align: center;
    font-size: 18px;
}
.forma{
    margin: auto;
    padding: 20px;
    text-align: center;
    font-size: 25px;

}
input{
    width: 20%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 3px solid #ccc;
    -webkit-transition: 0.5s;
    transition: 0.5s;
    outline: none;
    border-radius: 5px;
    font-size: 18px;

    }
input:focus{
   width: 25%;
    border: 3px solid #555;
}
.forma textarea{
   width: 30%;
   height: 70px;
   padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 3px solid #ccc;
    -webkit-transition: 0.5s;
    transition: 0.5s;
    outline: none;
    border-radius: 5px;
    font-size: 18px;
}
.forma textarea:focus{
    width: 35%;
    border: 3px solid #555;
}
input:last-child{
    width: 15%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 3px solid rgb(41, 22, 22);
    -webkit-transition: 0.5s;
    transition: 0.5s;
    outline: none;
    border-radius: 5px;
   background:#5e6872;
   color: white;
   font-size: 25px;
}
input:last-child:active{
    background:white;
    color:#43130c;
}
   </style>
</head>
<body>
   <div class="homework"> <h1>Homework 5</h1></div>
   <div class="tabl1">
    <P><b>Стилизовать при помощи псевдокласов и псевдоэлементов:</b></P>
    <ul>
        <li>Таблицу</li>
        <li>Список</li>
        <li>Элементы формы</li>
    </ul></div>
    <div class="psevk">
        <h2>Что такое ПСЕВДОКЛАССЫ?</h2>
        <p>— это событие, при котором будет срабатывать стиль</p>
    </div>
    <div class="pseve">
        <h2>
            Что такое ПСЕВДОЭЛЕМЕНТЫ?
        </h2>
        <p>— это сгенерированный элемент, созданный через CSS</p>
    </div>
   <div class="table"> <h2>Таблица псевдоклассов и псевдоэлементов:</h2>
    <table>
        <tr>
            <th>
                ПСЕВДОКЛАССЫ
            </th>
            <th>
                Значение
            </th>
            <th>
                ПСЕВДОЭЛЕМЕНТЫ
            </th>
            <th>
                Значение
            </th>
        </tr>
        <tr>
            <td>
                <b>:hover</b>
            </td>
            <td>
                наведение
            </td>
            <td>
                <b>::after</b>
            </td>
            <td>
                создаёт псевдоэлемент, который является последним потомком выбранного элемента
            </td>
        </tr>
        <tr>
            <td>
               <b> :active</b>
            </td>
            <td>
                клик
            </td>
            <td>
               <b> ::before</b> 
            </td>
            <td>
                создаёт псевдоэлемент,который является первым потомком выбранного элемента
            </td>
        </tr>
        <tr>
            <td>
               <b> :focus</b> 
            </td>
            <td>
                фокус на элемент
            </td>
            <td>
                <b>::marker</b>
            </td>
            <td>
                применяет стили к маркеру элемента списка, которые обычно содержит значок или номер
            </td>
        </tr>
    </table></div>
    <div class="psevs">
        <h2> ПСЕВДОКЛАССЫ СТРУКТУРЫ</h2>
        <ul>
            <li><b>:first-child</b> — первый дочерний элемент </li>
            <li><b>:last-child</b> — посещенные ссылки</li>
            <li><b>:only-child</b> — единственный дочерний элемент</li>
            <li><b>:nth-child()</b> — находит элементы по паттерну</li>
        </ul>
    </div>
    <div class="psevv">
        <h2>
            ПСЕВДОКЛАССЫ ДЛЯ ЭЛЕМЕНТОВ ВВОДА
        </h2>
        <ul>
       <li><b>:optional</b> — необязательные элементы</li>
       <li><b>:required</b> — обязательные элементы</li>
       <li><b>:valid</b>— элементы, которые прошли валидацию</li>
       <li><b>:checked</b> — выбранные элементы radio, checkbox и внутри select</li>
        </ul>
    </div>
   <div class="comment"> <h2>Если это работа вам понравилься, оставьте комментарии</h2></div>
   <div class="forma"> <form action="https://api.telegram.org/bot826230283:AAEqYlTgCVVATQRI465LUnxQjl0genQUFpo/sendMessage" method="post" onsubmit="alert(submit!);return false">
        <input type="hidden" name="chat_id" value="975938940">
        <b>Ваше имя:</b> <br>

        <input type="text" name="text" placeholder="First name">
       <br> <input type="text" name="text" placeholder="Last name">
        <br>Email:<br>
<input Email="text" name="email" placeholder="Email">
<br>Комментарии: <br>
<textarea name="message" " placeholder="Comments..."></textarea>
<br>
<b><input type="submit" value="Отправить"></b>

    </form></div>
</body>
</html>
