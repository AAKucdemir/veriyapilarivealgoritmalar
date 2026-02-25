# veriyapilarivealgoritmalar

[22,27,16,2,18,6] bu verileri insertion sort sıralayacam
[22,27,16,2,18,6] 22 sayısını şeçtim ve en sola sıraladım
[22,27,16,2,18,6] 27 sayısını seçtim ve 22 büyük olduğu için sıralamada aynı kaldı
[16,22,27,2,18,6] 16 sayısını şeçtim 22 ve 27 küçük olduğu için en sola yerlestiridim
[2,16,22,27,18,6] 2 sayısını şeçtim 2 ve 27,22,18,16,6 küçük olduğu için en sola yerleştirdim
[2,16,18,22,27,6] 18 sayısını şeçtim 18 ve 22,27 küçük olduğu için sola yerleştirdim
[2,6,16,18,22,27] 6 sayısını şeçtim 6 ve 16,18,22,27 küçük olduğu için en sola ekledim


big-o gösterimi
Best Case: O(n)

Average Case: O(n²)

Worst Case: O(n²)


18 sayısı hangi kapsamalara girer
[2, 6, 16, 18, 22, 27]
18 sayısı ortada bir yerdedir
 cevap=average case

 
1 adım
[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin selection sort`a göre ilk dört adımı yazacam 
[2,3,5,8,7,9,4,15,6] en küçük sayı 2 dir

2 adım  
[3,5,8,7,9,4,15,6]
en küçük 3 zaten yerinde
[2,3,5,8,7,9,4,15,6]

3 adım 
(5,8,7,9,4,15,6)
En küçük: 4

Swap (5 ↔ 4)

[2, 3, 4, 8, 7, 9, 5, 15, 6]

 4 adım
 [8,7,9,4,15,6]
 en küçük 5
 [2, 3, 4, 8, 7, 9, 5, 15, 6]

 
 cevap= [2, 3, 4, 8, 7, 9, 5, 15, 6]
