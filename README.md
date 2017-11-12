# NET.W.2017.Astapchik.10
EPAM training day 10 homework
1. Для объектов класса Book (ISBN, автор, название, издательство, год издания, количество страниц, цена) (домашнее задание 8-ого дня)
реализовать возможность строкового представления различного вида. Например, для объекта со значениями ISBN = 978-0-7356-6745-7, AuthorName  = Jeffrey Richter, Title = CLR via C#, Publisher = Microsoft Press, Year = 2012, NumberOPpages = 826, Price = 59.99$, могут быть следующие варианты:
- Jeffrey Richter, CLR via C#
- Jeffrey Richter, CLR via C#, "Microsoft Press", 2012
- ISBN 13: 978-0-7356-6745-7, Jeffrey Richter, CLR via C#, "Microsoft Press", 2012, P. 826.
- Jeffrey Richter, CLR via C#, "Microsoft Press", 2012
- ISBN 13: 978-0-7356-6745-7, Jeffrey Richter, CLR via C#, "Microsoft Press", 2012, P. 826., 59.99$.
- и т.д.
https://github.com/DmitriyAstapchik/NET.W.2017.Astapchik.08/blob/master/BookSystem/Book.cs
2. Не изменяя класс Book, добавить для объектов данного класса дополнительную возможность форматирования, изначально не предусмотренную классом. 
https://github.com/DmitriyAstapchik/NET.W.2017.Astapchik.08/blob/master/BookSystem/BookFormatter.cs
3. Для реализованных в пп. 1, 2 функциональностей разработать модульные тесты.
https://github.com/DmitriyAstapchik/NET.W.2017.Astapchik.08/tree/master/BookSystem.Tests
4. Выполнить рефакторинг класса (с целью сокращения повторного кода) в алгоритмах Евклида (для рефакторинга использовать делегаты, рефакторинг возможен только в случае, когда все метод находятся в одном классе!). Интерфейс класса измениться не должен.
https://github.com/DmitriyAstapchik/NET.W.2017.Astapchik.04/blob/master/Homework/GCDCalculator.cs
5. В класс с алгоритмом сортировки не прямоугольной матрицы, принимающим как компаратор интерфейс IComparer<int[]> добавить метод, принимающий как параметр делегат-компаратор, инкапсулирующий логику сравнения строк матрицы. Протестировать работу разработанного метода на примере сортировки матрицы, используя прежние критерии сравнения. Класс реализовать двумя способами, «замкнув» в первом варианте реализацию метода сортировки с делегатом на метод с интерфейсом, во втором – наоборот.
https://github.com/DmitriyAstapchik/NET.W.2017.Astapchik.05/blob/master/Homework/BubbleSorter.cs
https://github.com/DmitriyAstapchik/NET.W.2017.Astapchik.05/blob/master/Homework.Tests/BubbleSorterTests.cs
