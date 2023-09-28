Proje 1
[22,27,16,2,18,6] -> Insertion Sort



Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

<!-- Insertion Sort
          • Bir dizi elemanını sıralamak için kullanılan bir sıralama algoritmasıdır. Verilen diziyi sıralamak için her adımda dizinin bir elemanını alır ve bu elemanı sıralı bir altdiziye ekler.
-->
Başlangıç Dizi: [22, 27, 16, 2, 18, 6]

1. Adım: Dizi başlangıçta sadece ilk elemandan oluşuyor, bu yüzden zaten sıralıdır.
Sıralı Dizi: [22] [27, 16, 2, 18, 6]

2. Adım: İkinci eleman olan 27'yi alalım ve sıralı dizi içinde uygun konumunu bulalım.
Sıralı Dizi: [22, 27] [16, 2, 18, 6]

3. Adım: Üçüncü eleman olan 16'yı alalım ve sıralı dizi içinde uygun konumunu bulalım.
Sıralı Dizi: [16, 22, 27] [2, 18, 6]

4. Adım: Dördüncü eleman olan 2'yi alalım ve sıralı dizi içinde uygun konumunu bulalım.
Sıralı Dizi: [2, 16, 22, 27] [18, 6]

5. Adım: Beşinci eleman olan 18'i alalım ve sıralı dizi içinde uygun konumunu bulalım.
Sıralı Dizi: [2, 16, 18, 22, 27] [6]

6. Adım: Altıncı ve son eleman olan 6'yı alalım ve sıralı dizi içinde uygun konumunu bulalım.
Sıralı Dizi: [2, 6, 16, 18, 22, 27]

------

Big-O gösterimini yazınız.

Dizinin sıralanması <!--O(n^2)--> zaman karmaşıklığına sahiptir, çünkü her eleman diğer elemanlarla karşılaştırılır ve sıralı konuma yerleştirilirken iç içe döngüler kullanılır. İç içe döngüler n sayısı ile çarpıldığı için zaman karmaşıklığı <!--O(n^2)--> olur.

------

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı dizinin ortasında yer aldığı için <!-- Average Case --> kapsamına girer.

----

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

<!-- Selection Sort 
   • Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Baktın ki 2.sıradaki eleman en küçük hiç dokunma!!!. Hemen 3. sıraya geç. 4, 5 derken dizi bitti.
-->

1. Adım: İlk adımda en küçük eleman 2'dir. Bu elemanı dizinin başındaki elemanla yer değiştiririz.
Dizi Durumu: [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. Adım: İkinci en küçük elemanı bulmak için kalan diziyi tararız. Bu eleman 3'tür ve bu elemanı dizinin ikinci elemanıyla yer değiştiririz.
Dizi Durumu: [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. Adım: Üçüncü en küçük elemanı bulmak için kalan diziyi tararız. Bu eleman 4'tür ve bu elemanı dizinin üçüncü elemanıyla yer değiştiririz.
Dizi Durumu: [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. Adım: Dördüncü en küçük elemanı bulmak için kalan diziyi tararız. Bu eleman 5'tir ve bu elemanı dizinin dördüncü elemanıyla yer değiştiririz.
Dizi Durumu: [2, 3, 4, 5, 7, 9, 8, 15, 6]
