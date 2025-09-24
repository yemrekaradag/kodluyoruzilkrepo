# Merge Sort – [16, 21, 11, 8, 12, 22]

## Mantık:

Diziyi sürekli ikiye böl → tek eleman kalana kadar.

Sonra küçük küçük sıralı dizileri birleştir (merge).

Aşamalar

Başlangıç:
[16, 21, 11, 8, 12, 22]

İkiye böl:
[16, 21, 11] ve [8, 12, 22]

Tekrar böl:

[16, 21, 11] → [16] ve [21, 11]

[8, 12, 22] → [8] ve [12, 22]

Tekrar böl:

[21, 11] → [21] ve [11]

[12, 22] → [12] ve [22]

Birleştir (merge işlemleri):

[21] + [11] → [11, 21]

[16] + [11, 21] → [11, 16, 21]

[12] + [22] → [12, 22]

[8] + [12, 22] → [8, 12, 22]

Son birleştirme:
[11, 16, 21] + [8, 12, 22] → [8, 11, 12, 16, 21, 22]

Sonuç: [8, 11, 12, 16, 21, 22]

## Big-O Gösterimi

Merge Sort her zaman O(n log n) çalışır.

Çünkü:

Bölme işlemi → log n derinlik

Her seviyede birleşme işlemi → O(n)

Toplam: O(n log n)

Best Case = Average Case = Worst Case = O(n log n)
