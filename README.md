# Java часть
<h3>Новая тема: Циклы/h3><br>
http://study-java.ru/uroki-java/java-operatory-tsikla-for-while-do-while-operator-break/
  
Задачи<br>
1) При помощи цикла for вывести на экран нечетные числа от 1 до 99.
2) Дано число n при помощи цикла for посчитать факториал n!
3) Перепишите программы с использованием цикла while.
4) Даны переменные x и n вычислить x^n.
5) Вывести 10 первых чисел последовательности 0, -5,-10,-15..
6) Переделайте последний пример на break.Необходимо, чтобы заданный символ встречался в строке хотя бы 2 раза.

<h3>Повтор тем</h3><br>
Условные операторы и типы данных<br>

1) Книга<br> 
https://yadi.sk/d/o91cnpmanY6QTg<br> 
Глава 4 стр 59-66<br>
Доп материал<br>
http://study-java.ru/uroki-java/urok-8-java-logicheskye-i-uslovnye-operatory/

Задачи<br>
1) https://stepik.org/lesson/12762/step/8?unit=3110<br>
2) Даны 4 числа типа int. Сравнить их и вывести наименьшее на консоль.<br>
3) Вывести на консоль количество максимальных чисел среди этих четырех.<br>
4) Даны 5 чисел (тип int). Вывести вначале наименьшее, а затем наибольшее из данных чисел.<br>
5) Даны имена 2х человек (тип String). Если имена равны, то вывести сообщение о том, что люди являются тезками.<br>
6) Дано число месяца (тип int). Необходимо определить время года (зима, весна, лето, осень) и вывести на консоль.<br>

<h3>Остатки предыдущих уроков</h3><br>
дополнительные источники<br>
http://study-java.ru/uroki-java/urok-5-sozdanie-i-vyzov-klassa-v-java/<br>
http://study-java.ru/uroki-java/urok-6-sintaksis-java-peremennye-i-tipy-dannyh/<br>
http://study-java.ru/uroki-java/arifmeticheskie-operatory-i-matematika-v-java/<br>
http://study-java.ru/uroki-java/urok-7-preobrazovanie-tipov-v-java/<br>

Предыдущие задачи:<br>
Дополнительные задачи<br>
1) https://stepik.org/lesson/12759/step/6?unit=3107<br>
2) https://stepik.org/lesson/12759/step/8?unit=3107<br>
3) https://stepik.org/lesson/12759/step/12?unit=3107<br>
4) https://stepik.org/lesson/12760/step/3?unit=3108<br>

Факультативные
5) https://stepik.org/lesson/12759/step/15?unit=3107<br>
6) https://stepik.org/lesson/12760/step/9?unit=3108<br>


Первый модуль Minecraft mod<br>
TODO

Help<br>
https://ru.wikibooks.org/wiki/Java<br>
https://yadi.sk/d/1TZb4AztWKsqew<br>

Book for modding<br>
https://yadi.sk/d/OLol0bBCajn6Bw<br>

Source:<br>
https://github.com/AdityaGupta1/minecraft-modding-book.git<br>

Eclipse<br>
https://www.eclipse.org/downloads/<br>

Eclipse manual<br>
http://study-java.ru/uroki-java/urok-3-znakomstvo-s-eclipse/<br>

Git manual<br>
https://git-scm.com/book/ru/v1/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-Git

Git for Windows<br>
https://gitforwindows.org/<br>

Git шпаргалка<br>

Откройте cmd консоль. Win button + R затем cmd и Enter<br>

Проверьте персональную конфигурацию:
<pre><code>$ git config --global -l</code></pre>

Если необходимо сменить имя и почту
<pre><code>$ git config --global user.name "John Doe" 
git config --global user.email johndoe@example.com
git config --global -l</code></pre>

Работа с новым кодом<br>
Клонируйте репо и перейдите в его каталог<br>

<pre><code>$ git clone https://github.com/algo2-lesnaya-skazka/lesson8_java
cd lesson8_java/
git branch -av
git checkout {kkholopov} </code></pre>

Откройте проект в Eclipse и сохраняйте прямо в репо каталог, перед коммитом не забудьте удалить bin

<pre><code>$ git add *
$ git commit -am  “Add lesson8_java files”
$ git push origin {kkholopov} </code></pre>

