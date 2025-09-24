# 1) Insertion Sort – [22, 27, 16, 2, 18, 6]

Insertion Sort mantığı: Her adımda diziyi soldan sağa gezer, o anki elemanı uygun pozisyona (önceki sıralanmış alt dizi içine) yerleştirir.

## Adımlar:

Başlangıç: [22, 27, 16, 2, 18, 6]
İlk eleman (22) zaten sıralı kabul edilir.

27 eklenir → [22, 27, 16, 2, 18, 6] (zaten büyük, yer değiştirme gerek yok)

16 eklenir → 27’den küçük, 22’den küçük → [16, 22, 27, 2, 18, 6]

2 eklenir → hepsinden küçük → [2, 16, 22, 27, 18, 6]

18 eklenir → 27’den küçük, 22’den küçük, 16’dan büyük → [2, 16, 18, 22, 27, 6]

6 eklenir → 27’den küçük, 22’den küçük, 18’den küçük, 16’dan küçük, 2’den büyük →
[2, 6, 16, 18, 22, 27]

Son sıralı dizi: [2, 6, 16, 18, 22, 27]

## Big-O Gösterimi:

Insertion Sort en kötü durumda O(n²) çalışır.

Burada n = 6 → Worst Case: 36 adım civarı karşılaştırma.

Big-O: O(n²)

## 18 sayısı hangi case’e girer?

Sıralı dizi: [2, 6, 16, 18, 22, 27]

Best case → en başta olmalı (2)

Worst case → en sonda olmalı (27)

Average case → ortada olmalı → 18 ortadadır

Cevap: Average Case.

# 2) Selection Sort – [7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort: Her adımda minimum değeri bulup, baştaki eleman ile yer değiştirir.

İlk 4 adım:

Başlangıç: [7, 3, 5, 8, 2, 9, 4, 15, 6]
Minimum: 2 → 7 ile yer değiştir:
[2, 3, 5, 8, 7, 9, 4, 15, 6]

Kalan [3, 5, 8, 7, 9, 4, 15, 6] içinde minimum 3, zaten doğru yerde:
[2, 3, 5, 8, 7, 9, 4, 15, 6]

Kalan [5, 8, 7, 9, 4, 15, 6] içinde minimum 4 → 5 ile yer değiştir:
[2, 3, 4, 8, 7, 9, 5, 15, 6]

Kalan [8, 7, 9, 5, 15, 6] içinde minimum 5 → 8 ile yer değiştir:
[2, 3, 4, 5, 7, 9, 8, 15, 6]

İlk 4 adım sonrası dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6].
