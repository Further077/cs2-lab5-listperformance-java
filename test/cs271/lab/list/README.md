# This is my README
# This is my README
Questions

TestList

1. LinkedList will work but performance speeds will differ as a LinkedList are efficient for addition/removal at ends of the list, but slow for accessing random elements.
2. Calling remove(5) removes Integer 77 from list at index 5.
3. list.remove(Integer.valueOf(5)) removes element by object value(5).

TestIterator 

1. LinkedList will work but performance speeds will differ as a LinkedList are efficient for addition/removal at ends of the list, but slow for accessing random elements.
2. list.remove causes the test to fail. 

TestPerformance

Combined (ArrayList & LinkedList) Totals

Size: 10 Time: .142s

Size 100 Time: .274s

Size: 1000 Time: 1.706s

Size: 10000 Time: 23.47s

The LinkedList performed better overall as the size increased. 

LinkedList:
As the size increased, the run times for accessing the LinkedList increased (.023 to 8.09)
where the runtimes for the add/remove methods decreased(.068 to .056).

ArrayList:
As the size increased, the run times for the access method increased slightly (.012 to .014) 
where the add/remove method runtimes increased greatly (.049 to 15.31)
