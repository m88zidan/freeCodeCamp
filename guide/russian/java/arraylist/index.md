---
title: ArrayList
localeTitle: ArrayList
---
# ArrayList

ArrayList является частью чего-то, называемого _Framework Collection_ .

Структура _Collection_ состоит из всех интерфейсов и классов, которые могут содержать набор значений (аналогично [массивам](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html) ). **ArrayList** - это класс, который находится в этой иерархии и известен как _**объект Collection**_ . Он реализует интерфейс _List,_ который, в свою очередь, реализует интерфейс _Collection_ . Этот интерфейс _Collection_ можно найти в пакете `java.util` . Вам нужно будет импортировать этот пакет.

ArrayList - это класс, который используется для создания динамических массивов. Он медленнее, чем обычные массивы, но допускает много манипуляций. Его можно инициализировать, чтобы иметь определенный размер, или он будет иметь размер по умолчанию 10 единиц.

`java ArrayList<String> names = new ArrayList<>(); ArrayList<Integer> ages = new ArrayList<>(5);`

В приведенном выше фрагменте угловые брекеты `<>` принимают общий тип данных как аргумент, определяющий тип данных элементов в ArrayList. Первые `names` ArrayList указаны как содержащие элементы _String_ . Таким образом, будет разрешено содержать только элементы String. Его размер не указан, поэтому он будет иметь размер по умолчанию 10. Второй `ages` ArrayList указал, что он будет содержать целые числа. Но ArrayList не может содержать примитивы, он содержит только объекты. Таким образом, чтобы он мог хранить целые числа, поплавки и т. Д., Мы можем использовать классы-оболочки. `names` будут иметь заданный размер 5.

Поскольку ArrayList реализует _List_ , ArrayList может быть создан с использованием следующего синтаксиса: `java List<Integer> students = new ArrayList<>();`

ArrayList является динамическим, то есть он будет увеличиваться по размеру, если потребуется, и аналогичным образом уменьшить размер, если элементы будут удалены из него. Это то, что делает его лучше использовать, чем обычные массивы.

ArrayList позволяет нам случайным образом обращаться к элементам. ArrayList очень похож на _Vector_ во многих отношениях. Но это быстрее, чем векторы. Главное отметить, что - векторы быстрее, чем массивы, но ArrayLists - нет.

Поэтому, когда дело доходит до выбора между двумя - если скорость критическая, следует учитывать Vectors, иначе ArrayLists лучше, когда дело доходит до хранения большого количества элементов и эффективного доступа к ним.