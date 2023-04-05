# data_structures

[22,27,16,2,18,6] -> Insertion Sort

n = 6

1.adım -> en küçük sayı, 2, en başa yazılır (n). 
2.adım -> geri kalan veri içerisinde yeni en küçük sayı, 6, ikinci sıraya yazılır (n-1).
3.adım -> geri kalan veri içerisinde yeni en küçük sayı, 16, ikinci sıraya yazılır (n-2).
4.adım -> geri kalan veri içerisinde yeni en küçük sayı, 18, ikinci sıraya yazılır (n-3).
5.adım -> geri kalan veri içerisinde yeni en küçük sayı, 22, ikinci sıraya yazılır (n-4).
6.adım -> son kalan sayı arrayin en sonuna yazılır.

Big-O(n^2)

18 ortada olduğu için Average case.

[7,3,5,8,2,9,4,15,6]

1.adım -> [2,3,5,8,7,9,4,15,6]
2.adım -> [2,3,5,8,7,9,4,15,6] - en küçük sayı zaten olması gerektiği yerde
3.adım -> [2,3,4,8,7,9,5,15,6]
4.adım -> [2,3,4,5,7,9,8,15,6]

-------------------------------------------------------------------------------------------------------------
[16,21,11,8,12,22] -> Merge Sort

[16,21,11]  [8,12,22]

[16,21] [11]  [8,12] [22]

[16] [21] [11] [8] [12] [22]

[16,21] [11] [8,12] [22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22]

Big-O(nlong(n))

-------------------------------------------------------------------------------------------------------------

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree

root = 6 olsun.

root'un sağında 6'dan büyük elemanlar bulunur. solunda 6'dan küçük elemanlar bulunur.

küçük elemanlar -> [5,1,3,0,4,2]
-küçük elemanlar için yeni root = 3 olsun.

-solunda kalanlar -> [1,0,2]
      root = 0
      solunda kalanlar -> []
      sağında kalanlar -> [1,2]
        root = 1
        solunda kalanlar -> []
        sağında kalanlar -> [2]
 
 -sağında kalanlar -> [5,4]
      root = 5
      solunda kalanlar -> [4]
      sağında kalanlar -> []

büyük elemanlar -> [7,8,9]
-büyük elemanlar için yeni root = 8 olsun.
  
  -solunda kalanlar -> [7]
  
  -sağında kalanlar -> [9]





