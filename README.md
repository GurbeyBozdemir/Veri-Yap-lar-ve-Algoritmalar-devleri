# Veri Yapıları ve Algoritmalar > Insertion Sort Projesi
---
### 1) [22,27,16,2,18,6] Sort Türüne göre aşamaları
---
* [22,27,16,2,18,6]
* [22,16,27,2,18,6]
* [16,22,27,2,18,6]
---
* [16,22,2,27,18,6]
* [16,2,22,27,18,6]
* [2,16,22,27,18,6]
---
* [2,16,22,18,27,6]
* [2,16,18,22,27,6]
---
* [2,16,18,22,6,27]
* [2,16,18,6,22,27]
* [2,16,6,18,22,27]
* [2,6,16,18,22,27]

### 2) Big-O Gösterimi
---
O(n²)

### 3) Best/Worst/Average Case
---
* Best case: Dizinin halihazırda sıralı olması: O(n)
* Average/Worst case: Dizinin tersine sıralı olması: O(n²)

### 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
---
Orta kısımda kaldığından Average case.

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
---
* [7,3,5,8,2,9,4,15,6]
* [3,7,5,8,2,9,4,15,6]
---
* [3,5,7,8,2,9,4,15,6]
---
* [3,5,7,2,8,9,4,15,6]
* [3,5,2,7,8,9,4,15,6]
* [3,2,5,7,8,9,4,15,6]
* [2,3,5,7,8,9,4,15,6]
---
* [2,3,5,7,8,4,9,15,6]
* [2,3,5,7,4,8,9,15,6]
* [2,3,5,4,7,8,9,15,6]
* [2,3,4,5,7,8,9,15,6]
