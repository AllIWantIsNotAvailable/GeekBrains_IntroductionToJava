# [Задача №1](https://github.com/AllIWantIsNotAvailable/GeekBrains_IntroductionToJava/blob/main/seminars/Sem03_Introduction_to_JAVA_Collections/HomeWork/src/Task01.java):
## Комментарии к задаче:
> - создали список длиной 10 и заполнили псевдослучайными значениями от 0 до 10; 
> - применили метод списка removeIf() с лямбда-выражением;
> 
> П.С. С этим все понятно.
>

# [Задача №2](https://github.com/AllIWantIsNotAvailable/GeekBrains_IntroductionToJava/blob/main/seminars/Sem03_Introduction_to_JAVA_Collections/HomeWork/src/Task02.java):
## Комментарии к задаче:
> - импортировали метод для создания списка из задания №1;
> - Collections.min() и Collections.max() – нашли минимальное и максимальное значение в списке;
> - у `Collections` нет метода `average()`, но если обратится к `List.stream()` и применить `mapToInt()` чтобы получить значения хранящихся в списке `Integer`, то у вернувшейся структуры `map()` уже есть `average()` – получили среднее.
>
> П.С. В целом все понятно, про stream() читаю дополнительно.
>

# [Задача №3](https://github.com/AllIWantIsNotAvailable/GeekBrains_IntroductionToJava/blob/main/seminars/Sem03_Introduction_to_JAVA_Collections/HomeWork/src/Task03.java):
## Комментарии к задаче:
> - имеем строковый массив с названиями планет;
> - создаем список строк какой-то длины, с помощью `Random.nextInt()` получаем случайное значение от 0 до длины массива строк - 1, чтобы организовать случайное заполнение списка;
> - у `List.stream()` есть метод `filter()`, а у последнего есть `count()`, поэтому долго не думая: в цикле перебираем исходный массив с названиями планет, по условию фильтрации получаем временные структуры, считаем количество элементов в них, если больше чем 0 – выводим в консоль форматированную строку.
>
> П.С. В целом все понятно, про stream() читаю дополнительно. 
>

# [Задача №4](https://github.com/AllIWantIsNotAvailable/GeekBrains_IntroductionToJava/blob/main/seminars/Sem03_Introduction_to_JAVA_Collections/HomeWork/src/TaskStar04.java):
## Комментарии к задаче:
> - с рекурсивным дроблением исходного массива на его меньшие части – все понятно;
> - с тем как массивы сливаются тоже все понятно;
>
> П.С. Такие алгоритмы стоило бы разбирать в группе, а не давать как звездочки... они куда полезнее, чем считать: минимумы, максимумы и среднее с помощью 1-го метода... 
> 