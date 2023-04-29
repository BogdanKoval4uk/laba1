# Лабораторная работа номер 1

## Домашнее задание

   1. Скачайте библиотеку boost с помощью утилиты wget. Адрес для скачивания https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz.
   2. Разархивируйте скаченный файл в директорию ~/boost_1_69_0
   3. Подсчитайте количество файлов в директории ~/boost_1_69_0 не включая вложенные директории.
   4. Подсчитайте количество файлов в директории ~/boost_1_69_0 включая вложенные директории.
   5. Подсчитайте количество заголовочных файлов, файлов с расширением .cpp, сколько остальных файлов (не заголовочных и не .cpp).
   6. Найдите полный путь до файла any.hpp внутри библиотеки boost.
   7. Выведите в консоль все файлы, где упоминается последовательность boost::asio.
   8. Скомпилирутйе boost. Можно воспользоваться инструкцией или ссылкой.
   9. Перенесите все скомпилированные на предыдущем шаге статические библиотеки в директорию ~/boost-libs.
   10.Подсчитайте сколько занимает дискового пространства каждый файл в этой директории.
   11.Найдите топ10 самых "тяжёлых".


## Выполнение домашнего задания

### 1 задание
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2020-36-14.png)
wreg  -  скачивание файла и сохранение в текущей директории

#### 2 задание
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2021-32-04.png)
tar -xf  - распаковка файла
tar -C   - используется для указания папки

###3 задание
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2021-32-04.png)
переход в директории
find -type f  - счёт файлов в директоии,  где maxdepth 1 — глубина поиска

###4 задание


![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2021-42-38.png)

###5 задание



![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2021-47-57.png)

###6 задание
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2021-54-10.png)
wc -l    - отображение файлов

###7 задание

![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2021-56-56.png)

grep -r    - первый параметр представляет регулярный параметр для поиска, а второй представляет каталог, в котором необходимо искать (в данном случае текущий каталог)

###8 задание

![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2022-04-37.png)
./script.sh   - запуск скрипта
--prefix=Prefix   - папка для установки программы
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2022-04-37.png)

###9 задание 
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2022-13-09.png)
mkdir   - создание директории (папки)
![image](https://github.com/BogdanKoval4uk/laba1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-04-10%2022-13-14.png)
mv   -  переместить файлы или директории
