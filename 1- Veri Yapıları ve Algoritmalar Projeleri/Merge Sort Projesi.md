[16,21,11,8,12,22] -> Merge Sort
## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
> Merge Sort: Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor.

[16,21,11] - [8,12,22] -> Diziyi ikiye ayırıyorum

[16,21] - [11] - [8,12] - [22] -> Tekrar ikiye ayırıyorum

[16] - [21] - [11] - [8] - [12] - [22] -> Son kez ikiye ayırarak bütün elemanları tek tek ayırmış oldum. Şimdi bu tekli dizileri sıralı olarak ikili şekilde birleştiriyorum.

[16,21] - [8,11] - [12,22] -> Bu iki elemanlı dizileri de  sıralı şekilde birleştiriyorum.

[8,11,16,21] - [12,22] -> İlk iki diziyi birleştirdim. Şimdi son adımda kalan üçüncü diziyi birleştiriyorum.

[8,11,12,16,21,22] -> Dizimin son hali.

## Big-O gösterimini yazınız.

O(nlogn)