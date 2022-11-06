# Insertion Sort Projesi
## A. [22,27,16,2,18,6]

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Avarage case: Aradığımız sayının ortada olması,Worst case:Aradığımız sayının sonda olması, Best case:Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## B. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Cevaplar
## A1. 
>[2,27,16,22,18,6]
>[2,6,16,22,18,27]
>[2,6,16,18,22,27]
## A2.
O(n²) = O(6²) = O(36)
## A3.
**Avarage Case**: Big-O=n² Aradığımız sayının ortada olması, örnekteki 16 ve 18 gibi.
**Worst Case**: Big-O=n²  Aradığımız sayının sonda olması, örnekteki 27 gibi.
**Best Case**: Big-O=n  Aradığımız sayının en başta olması, örnekteki 2 gibi.
## A4.
18 Avarage case kapsamına girer.
## B.
> 1.adım [2,3,5,8,7,9,4,15,6]
> 2.adım [2,3,4,8,7,9,5,15,6]
> 3.adım [2,3,4,5,7,9,8,15,6]
> 4.adım [2,3,4,5,6,9,8,15,7]