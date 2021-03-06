# HSE_FCS_SE-FASM2
## Бен Мустафа Анас, БПИ191
Домашняя работа №2 курса "Архитектуры вычислительных систем".
Код по каждой задаче прикреплен в соответствующей папке.

### Вариант №5
### Условие: Разработать программу, которая вводит одномерный массив A[N] и некое число Х, и выводит пользователю массив B, который состоит из элементов массива А, не равных Х.


## Результаты работы программы
#### Тест 1.
Для начала проверим работу программы на маленьком введенном массиве. 
- **Результат работы**</br>
  Действительно, при введённом пользователем числе Х = 5, в выходном массиве пропадают все элементы, равные 5:
  ![](Materials/TestsScreenshots/Test4.png)</br>
  
#### Тест 2.
Теперь увеличим размер массива и проверим программу.
- **Результат работы**</br>
  Вновь верное выполнение.
  ![](Materials/TestsScreenshots/Test3.png)</br>
  
#### Тест 3.
Граничный случай. Попробуем создать массив, состоящий только из чисел X. 
- **Результат работы**</br>
  Действительно, на выходе мы должны были получить пустой массив. Его и получили.
  ![](Materials/TestsScreenshots/test2.png)</br>
  
#### Тест 4.
Рассмотрим длинный массив, содержащий также отрицательные числа.
- **Результат работы**</br>
  Всё работает отлично.
  
  ![](Materials/TestsScreenshots/Test1.jpeg)</br>
 
## Код программы, исполняемый файл, а также скриншоты приведены в папке Materials.

## Список использованных источников/ресурсов:
  - Tomasz Grysztar. Flat Assembler Programmer’s Manual [Электронный ресурс]. – Официальный сайт FASM. Режим доступа: http://flatassembler.net/docs.php?article=manual
  - Vitali Kremez. FASM: Flat Assembler, also known as "FASM": Sample Code. [Электронный ресурс] Режим доступа: https://vk-intel.org/2017/04/03/fasm-flat-assembler-also-known-as-fasm-sample-code/
