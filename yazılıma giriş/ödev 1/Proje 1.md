# PROJE-1 (Insertion Sort Projesi)
## [22,27,16,2,18,6] (n) => Insertion Sort
### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
#### 1.Aşama
##### (2) ile (22) elemanları yer değiştirir. [2,27,16,22,18,6] (n-1)
#### 2.Aşama
##### (6) ile (27) elemanları yer değiştirir. [2,6,16,22,18,27] (n-2)
#### 3.Aşama
##### (18) ile (22) elemanları yer değiştirir. [2,6,16,18,22,27] (n-3)
#### SONUÇ: [2,6,16,18,22,27]
### 2. Big-O gösterimini yazınız.
#### n + (n-1) + (n-2) + (n-3) + .... + 1  = n.(n+1)/2 = (n + n^2) / 2
#### Domine eden fonksiyon dikkate alınır. n^2
#### SONUÇ: O(n^2)
### 3. Time Complexity:
#### Worst case: [27,22,18,16,6,2] => O(n^2)
#### Average Case: [2,6,16,18,22,27] => O(n^2)
#### Best Case: [2,6,16,18,22,27] => O(n)
### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
#### Avarage case kapsamına girer çünkü ortadadır.
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
#### 1.Aşama
##### [2,3,5,8,7,9,4,15,6]
#### 2.Aşama
##### [2,3,4,8,7,9,5,15,6]
#### 3.Aşama
##### [2,3,4,5,7,9,8,15,6]
#### 4.Aşama
##### [2,3,4,5,6,9,8,15,7]