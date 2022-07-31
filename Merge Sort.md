https://app.patika.dev/aspirique
## Veri Yapıları ve Algoritmalar > Merge Sort Projesi
---
### [16,21,11,8,12,22] 
### Dizinin sort türüne göre aşamaları:
- [16,21,11] [8,12,22]
- [16,21] [11] [8,12] [22]
- [16] [21] [11] [8] [12] [22]
- [16,21] [11] [8,12] [22]
- [11,16,21] [8,12,22]
- [8,11,12,16,21,22]

### Big-O gösterimi:
---
Best/Average/Worst: Her şartta arrayları ikiye bölüp sıralayıp tekrar birleştirdiğinden O(n*logn)
