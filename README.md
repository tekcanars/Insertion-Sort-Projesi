Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


1)Insertion Sort Steps 
22 < 27 ? [22, 27, 16, 2, 18, 6]
16 < 27 ? [22, 16, 27, 2, 18, 6]
16 < 22 ? [16, 22, 27, 2, 18, 6]
2 < 27 ? [16, 22, 2, 27, 18, 6]
2 < 22 ? [16, 2, 22, 27, 18, 6]
2 < 16 ? [2, 16, 22, 27, 18, 6]
18 < 27 ? [2, 16, 22, 18, 27, 6]
18 < 22 ? [2, 16, 18, 22, 27, 6]
6 < 27 ? [2, 16, 18, 22, 6, 27]
6 < 22 ? [2, 16, 18, 6, 22, 27]
6 < 18 ? [2, 16, 6, 18, 22, 27]
6 < 16 ? [2, 6, 16, 18, 22, 27]

2)Big O Notation = O(n^2)

3) Time Complexity 
Average case n^2
Worst case n^2
Best case n

4)Average case situation for 18

5) 3 < 7 ? [3,7,5,8,2,9,4,15,6]
5 < 7 ? [3,5,7,8,2,9,4,15,6]
2 < 8 ? [3,5,7,2,8,9,4,15,6]
2 < 7 ? [3,5,2,7,8,9,4,15,6] ...