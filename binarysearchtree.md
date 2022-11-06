# Binary Search Tree

## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

> Root 7'dir. 
```
  7
  ```

> 5 sayısı 7'den küçük olduğu için 7'nin sol tarafına yazılır.
    ```
        7
      /
    5
    ```

> 1 sayısı 7 ve 5'ten küçük olduğu için 5'in sol tarafına yazılır.
```
         7
        /
       5
      /
     1 
```

> 8 sayısı 7'den büyük olduğu için 7'nin sağ tarafına yazılır.
```
       7
      / \
     5   8
    /
   1
   ```

> 3 sayısı 5 ve 7'den küçüktür ama !'den küçük değildir. O yüzden 1'in sağ tarafına yazılır.
```
       7
      / \
     5   8
    / 
   1 
    \
     3
   ```

> 6 sayısı 7'den küçüktür ama 5'ten büyüktür. O yüzden 5'in sağ tarafına yazılır.
```
       7
      / \
     5   8
    / \
   1   6
    \
     3
 ```

> 0 sayısı 7,5 ve 1'den küçük olduğu için 1'in sol tarafına yazılır.
```
       7
      / \
     5   8
    / \
   1   6
  / \
 0   3
 ```

 > 9 sayısı 7 ve 8'den büyük olduğu için 8'in sağ tarafına yazılır.
 ```
       7
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3
 ```

 > 4 sayısı 5 ve 7'den küçük ama 1 ve 3'ten büyük olduğu için 3'ün sağ tarafına yazılır.
 ```
       7
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3
      \
       4
```

> 2 sayısı 5, 7 ve 3'ten küçük olduğu için 3'ün sol tarafına yazılır.
```
       7
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3
    / \
   2   4
```
