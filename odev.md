# Insertion Sort Projesi

## Odev A

### Soru: 
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Cevaplar:

### 1. Soru - Sort Aşamaları:
- 22,27,16,2,18,6  n
- 22,27,16,2,18,6  n-1
- 16,22,27,2,18,6  n-2
- 2,16,22,27,18,6  n-3
- 2,16,18,22,27,6  n-4
- 2,6,16,18,22,27  1

### 2. Soru - Big O:

- O(n^2)

### 3. Soru - Time Complexity:
1. Best Case: O(n)
2. Worst Case: O(n^2)
3. Avarage Case: O(n^2)

### 4. Soru - 18 sayısı
- 18 number at Avarage Case

---
## Odev B

### Soru: 
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### Cevap:

- 7,3,5,8,2,9,4,15,6
- 3,7,5,8,2,9,4,15,6
- 3,5,7,8,2,9,4,15,6
- 2,3,5,7,8,9,4,15,6

