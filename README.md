20. Найти все файлы с заданным расширением в папке и ее подпапках. Для чтения набора файлов и подпапок в папке использовать класс java.io.File (метод listFiles()). Реализация с использованием очереди. Вначале в очередь помещается папка, в которой ищем файлы. Затем, в цикле, пока в очереди есть элементы, выбираем из очереди элемент (папку). Для данной папки находим все вложенные элементы: если это нужный файл, помещаем его в итоговый список, если это папка, то добавляем ее в очередь. Заменить в реализации очередь на стек, объяснить, каким образом и почему изменится порядок найденных файлов.
1 курс 1 группа Колбасов
