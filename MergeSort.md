[16,21,11,8,12,22] -> Merge Sort

<!--Merge Sort

   • Büyük veri kümeleleri üzerinde etkili bir şekilde çalışır. Bu algoritma, "böl ve fethet" (divide and conquer) stratejisine dayanır.Merge Sort'un en önemli avantajlarından biri, her iki parçanın sıralanması ve birleştirilmesi işlemlerinin istikrarlı bir şekilde çalışmasıdır. Ayrıca, bu algoritma en kötü durumda bile O(nlogn) zaman karmaşıklığına sahiptir. Bu, büyük veri kümeleleri üzerinde hızlı ve etkili bir sıralama işlemi sağlar.
 -->

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. Adım: Bölme (Divide)
Diziyi ortadan ikiye bölelim:
Sol Parça: [16, 21, 11]
Sağ Parça: [8, 12, 22]

2. Adım: Sol ve Sağ Parçaları Sıralama (Conquer)
Her iki parçayı ayrı ayrı sıralayalım:
Sol Parça: [11, 16, 21]
Sağ Parça: [8, 12, 22]

3. Adım: Birleştirme (Merge)
Şimdi sıralanmış sol ve sağ parçaları birleştirerek orijinal diziyi oluşturalım. Bu sırada küçükten büyüğe sıralama yaparız:

Birleştirilmiş Dizi: [8, 11, 12, 16, 21, 22]


Big-O gösterimini yazınız.

<!-- O(nlogn) -->
