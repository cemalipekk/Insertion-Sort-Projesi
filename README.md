# Insertion-Sort-Projesi
 *   [22,27,16,2,18,6] dizisinin insertion sort türüne göre aşamalarını yazınız

 ```
 [22,27,16,2,18,6] n
 [2,27,16,22,18,6] n-1
 [2,6,16,22,18,27] n-2
 [2,6,16,18,22,27] 1
```
 *   [22,27,16,2,18,6] dizisinin Big O gösterimini yazınız
```
O(n²) yani olacaktır.
``` 

* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Sıralandıktan sonra ortada olduğu için Average Case kapsamına girer.
```

*   [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
``` 
[7,3,5,8,2,9,4,15,6] n
[2,3,5,8,7,9,4,15,6] n-1
[2,3,4,8,7,9,5,15,6] n-2
[2,3,4,5,7,9,8,15,6] n-3
[2,3,4,5,6,9,8,15,7] n-4
[2,3,4,5,6,7,8,15,9] n-5
[2,3,4,5,6,7,8,9,15] 1


