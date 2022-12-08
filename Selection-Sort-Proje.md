# Patika Veri Yapıları ve Algoritmalar Eğitimi Insert-Selection Sort Ödevi

### [Patika Eğitim Linki](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar)

## [22,27,16,2,18,6] -> Insertion Sort

1. 22 ile 27 karşılaştırılır, değişiklik olmaz. [22,27,16,2,18,6]
2. 27 ile 16 karşılaştırılır. 16 ile 27 yer değiştirir. 22 ile 16 karşılaştırır, 22 ile 16 yer değiştirir. [16,22,27,2,18,6]
3. 27 ile 2 karşılaştırılır. 27 ile 2 yer değiştirir. 22 ile 2 karşılaştırır, 22 ile 7 yer değiştir. 16 ile 2 karşılaştırır, 2 ile 16 yer değiştir. [2,16,22,27,18,6]
4. 27 ile 18 karşılaştırılır, 27 ile 18 yer değiştirir. 18 ile 22 karşılaştılır, 18 ile 22 yer değiştirir. 16 ile 18 karşılaştırır, değişiklik olmaz. [2,16,18,22,27,6]
5. 27 ile 6 karşılaştırılır, 27 ile 6 yer değiştirir. 22 ile 6 karşılaştılır, 22 ile 6 yer değiştirir. 18 ile 6 karşılaştılır, 18 ile 6 yer değiştirir. 16 ile 6 karşılaştılır, 16 ile 6 yer değiştirir.2 ile 6 karşılaştırır, değişiklik olmaz. [2,6,16,18,22,27]

* O($n^2$)

* Avarage Case. Aradığımız sayı ortada.  [2,6,16,18,22,27]

## [7,3,5,8,2,9,4,15,6] -> Selection Sort

1. [2,7,3,5,8,9,4,15,6]
1. [2,3,7,5,8,9,4,15,6]
1. [2,3,4,7,5,8,9,15,6]
1. [2,3,4,5,7,8,9,15,6]
1. [2,3,4,5,6,7,8,9,15]
