# Selection-Sort-Projesi
# Proje: Insertion ve Selection Sort Algoritmaları

## Amaç
Bu proje, Insertion Sort ve Selection Sort algoritmalarının nasıl çalıştığını ve bu algoritmaların hangi durumlarda etkili olduğunu göstermektedir.

## Insertion Sort Aşamaları

1. Başlangıç: [22, 27, 16, 2, 18, 6]
2. Adım 1: [22, 27, 16, 2, 18, 6] (22 sabit)
3. Adım 2: [16, 22, 27, 2, 18, 6] (16 yerine geçirildi)
4. Adım 3: [2, 16, 22, 27, 18, 6] (2 yerine geçirildi)
5. Adım 4: [2, 16, 18, 22, 27, 6] (18 yerine geçirildi)
6. Adım 5: [2, 6, 16, 18, 22, 27] (6 yerine geçirildi)

Insertion Sort Big-O Gösterimi: O(n^2)

Insertion Sort Time Complexity:
- Ortalama durum: O(n^2)
- En kötü durum: O(n^2)
- En iyi durum: O(n)

## 18 Sayısı
- En iyi durum: Aranan sayı dizinin başında olduğunda O(1).
- Ortalama durum: Aranan sayı dizinin ortasında olduğunda O(n/2).
- En kötü durum: Aranan sayı dizinin sonunda olduğunda O(n).

## Selection Sort Aşamaları (İlk 4 Adım)

1. Başlangıç: [7, 3, 5, 8, 2, 9, 4, 15, 6]
2. Adım 1: [2, 3, 5, 8, 7, 9, 4, 15, 6] (2 en küçük, 1. sıraya geçirildi)
3. Adım 2: [2, 3, 4, 8, 7, 9, 5, 15, 6] (4 en küçük, 2. sıraya geçirildi)
4. Adım 3: [2, 3, 4, 5, 7, 9, 8, 15, 6] (5 en küçük, 3. sıraya geçirildi)

