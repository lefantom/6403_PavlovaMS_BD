Лабораторная 3. Потоковая обработка в Apache Flink
В этой лабораторной вы будете работать с Apache Flink - фреймворком и движком распределённой обработки потоков данных.

Задание
Выполнить следующие задания из набора заданий репозитория https://github.com/ververica/flink-training-exercises:

RideCleanisingExercise
RidesAndFaresExercise
HourlyTipsExerxise
ExpiringStateExercise
Решения могут быть выполнены на двух языках: Java или Scala. Каждому заданию соответствует .java или .scala файл с шаблоном решения и файл с тестом решения. Тесты расположены в папке test.

Для выполнения заданий вам потребуется датасет с данными о поездках такси в Нью-Йорке https://github.com/apache/flink-training/blob/master/README.md#using-the-taxi-data-streams. Файлы nycTaxiFares.gz и nycTaxiRides.gz вы можете найти в папке data https://gitlab.com/ssau.tk.courses/big_data/-/tree/master/data.

Начало работы
git clone https://github.com/ververica/flink-training-exercises
Откройте проект в IntelliJ IDEA
Перед выполнением заданий укажите путь к данным в переменных pathToRideData и pathToFareData в файле ./flink-training-exercises/src/main/java/com/ververica/flinktraining/exercises/datastream_java/utils/ExerciseBase.java.
Для выполнения первого задания на Scala откройте файл ./flink-training-exercises/src/main/scala/com/ververica/flinktraining/exercises/datastream_scala/basics/RideCleansingExercise.scala. В месте решения вы найдёте throw new MissingSolutionException().
Запустите тест ./flink-training-exercises/src/test/java/com/ververica/flinktraining/exercises/datastream_java/basics/RideCleansingScalaTest.java. Тест должен завершиться успешно, но сама программа будет завершаться аварийно с исключением MissingSolutionException.
Реализуйте недостающий код. С помощью теста проверьте корректность работы вашего решения.
Зарегистрируйтесь на сайте https://training.ververica.com для доступа к теоретическим материалам и дополнительным упражнениям.
