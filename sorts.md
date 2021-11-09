PROJE 1

 a) [22,27,16,2,18,6] -> Insertion Sort

a.1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    1-> [22,27,16,2,18,6] -> n
    2-> [16,22,27,2,18,6] -> n-1
    3-> [2,16,22,27,18,6] -> n-2
    4-> [2,16,18,22,27,6] -> n-3
    4-> [2,6,16,18,22,27] -> n-4

a.2) Big-O gösterimini yazınız.

    O(n^2)

a.3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    
    Best Case = O(n)
    Average Case = O(n^2)
    Worst Case = O(n^2)


a.4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

    Average Case Kapsamına Girer



 b) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    1- [3,7,5,8,2,9,4,15,6]
    2- [3,5,7,8,2,9,4,15,6]
    3- [3,5,7,8,2,9,4,15,6]
    4- [2,3,5,7,8,9,4,15,6]

-------------------------------------------------------------------------------------------------------------------------------------------

PROJE 2

[16,21,11,8,12,22] -> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

        [16,21,11]  [8,12,22]

     [16]  [21,11]  [8]  [12,22]

  [16]  [21]  [11]  [8]  [12]  [22]

     [16]  [11,21]  [8]  [12,22]
 
        [11,16,21]  [8,12,22]

          [8,11,12,16,21,22]


2) Big-O gösterimini yazınız.

    O(nlogn)

-------------------------------------------------------------------------------------------------------------------------------------------

PROJE 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

7        7       7       7       7       7       7       7        7       7              
        5       5       5 8     5 8     5 8     5 8     5 8      5 8     5 8   
               1       1       1       1 6     1 6     1 6 9    1 6 9   1 6 9
                                3       3     0 3     0 3      0 3     0 3
                                                                  4     2 4