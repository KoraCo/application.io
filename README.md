<!DOCTYPE HTML>
<html>
 <head>
  <meta charset="utf-8">
  <title>Ипотечный калькулятор</title>
 <style> 
   body {
     background:#FFFFF0;
      font-size:20px;
      text-shadow: 1px 1px 2px #2F4F4F; 
      font-weight: bold;
    }
   form {
    width:50%;
    margin-left:25%;
    background:#F0F8FF;
   }
   select {
    width: 315px;   
    }
   #but {
    margin-left:85px;
    width:150px;
    padding:8px;
    text-shadow: 2px 3px 3px #2F4F4F;
    background:	#696969;
    border: 2px inset #2E8B57;
   }
 
</style>
 </head>
 <body>
 <form name="test" method="post" action="function.php">
<fieldset>
  <legend>Ипотечный калькулятор</legend>
  <p><input type="text" size="40" value="Стоимость апартаментов" autofocus required> <input type="text" size="40" value="Первый взнос" required></p>
  <p><input type="text" size="40" value="Процентная ставка" required> <input type="text" size="40" value="Количество месяцев ипотеки" required></p>
  <p><select>
    <option value="s2" selected>Погашение</option>  
    <option value="s1">Простое</option>
    <option value="s3">Аннуитет</option>
   </select> 
</p>
 <p><input id="but" type="submit" value="Отправить"> <input id="but" type="reset" value="Очистить"></p>
</fieldset>
 </form>
 </body>
</html>
