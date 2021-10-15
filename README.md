<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8">
  <title>output</title>
 </head>
 <body>
              <h1>ПЕРЕВОД В ДЮЙМЫ</h1>
  <form oninput="result.value=(cm.value/2.54).toFixed(2)">
    <p>Введите длину в сантиметрах: 
    <input type="number" name="cm" autofocus></p>
    <p>Длина в дюймах: <output name="result">0</output></p>
  </form>
              <h1>ПЕРЕВОД В КВАДРАТНЫЕ МЕТРЫ</h1>
    <form oninput="result.value=(cm.value/10000).toFixed(10)">
    <p>Введите длину в сантиметрах: 
    <input type="number" name="cm" autofocus></p>
    <p>Длина в квадратных метрах <output name="result">1</output></p>
 </body>
</html>
