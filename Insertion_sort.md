# Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

### 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

#### Birinci adım:
* 27 22'den büyük olduğu için değiştirmiyoruz -> [22,27,16,2,18,6]

#### İkinci adım:
* 16 27'den küçük olduğu için yer değiştiriyoruz -> [22,16,27,2,18,6]
* 16 22'den küçük olduğu için yer değiştiriyoruz -> [16,22,27,2,18,6]

#### Üçüncü adım:
* 2 27'den küçük olduğu için yer değiştiriyoruz -> [16,22,2,27,18,6]
* 2 22'den küçük olduğu için yer değiştiriyoruz -> [16,2,22,27,18,6]
* 2 16'den küçük olduğu için yer değiştiriyoruz -> [2,16,22,27,18,6]

#### Dördüncü adım:
* 18 27'den küçük olduğu için yer değiştiriyoruz -> [2,16,22,18,27,6]
* 18 22'den küçük olduğu için yer değiştiriyoruz -> [2,16,18,22,27,6]
* 18 16'den büyük olduğu için yer değiştirmiyoruz -> [2,16,18,22,27,6]

#### Beşinci adım:
* 6 27'den küçük olduğu için yer değiştiriyoruz -> [2,16,18,22,6,27]
* 6 22'den küçük olduğu için yer değiştiriyoruz -> [2,16,18,6,22,27]
* 6 18'den küçük olduğu için yer değiştiriyoruz -> [2,16,6,18,22,27]
* 6 16'den küçük olduğu için yer değiştiriyoruz -> [2,6,16,18,22,27]

### 2.Big-O gösterimini yazınız.
* O(n^2)

### 3.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizi sıralandıktan sonra 18 ortada olduğu için Average Case.

### 4.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre sıralayınız.

* [3,7,5,8,2,9,4,15,6]
* [3,5,7,8,2,9,4,15,6]
* [3,5,7,8,2,9,4,15,6]
* [3,5,7,2,8,9,4,15,6]
* [3,5,2,7,8,9,4,15,6]
* [3,2,5,7,8,9,4,15,6]
* [2,3,5,7,8,9,4,15,6]
* [2,3,5,7,8,4,9,15,6]
* [2,3,5,7,4,8,9,15,6]
* [2,3,5,4,7,8,9,15,6]
* [2,3,4,5,7,8,9,15,6]
* [2,3,4,5,7,8,9,6,15]
* [2,3,4,5,7,8,6,9,15]
* [2,3,4,5,7,6,8,9,15]
* [2,3,4,5,6,7,8,9,15]