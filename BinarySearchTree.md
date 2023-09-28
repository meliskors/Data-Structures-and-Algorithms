[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


<!-- Binary Search Tree

     • Binary Search Tree (BST), verilerin hızlı bir şekilde aranmasını, ekleme ve silme işlemlerini gerçekleştirmesini sağlayan bir veri yapısıdır. BST, ağaç şeklinde bir veri yapısıdır ve her düğüm (node) maksimum iki çocuk düğüme sahip olabilir. Bu çocuk düğümler, sol ve sağ alt ağaçları temsil eder. 

-->

1. Adım: İlk elemanı ağacın kök düğümü olarak ekleyelim: [7]

2. Adım: 5, 1, 8, 3, 6, 0, 9, 4, 2 sırayla eklenirken ağaç aşağıdaki gibi büyür:

     7
    /
   5
  / \
 1   8
  \
   3
    \
     6
      \
       0
        \
         9
          \
           4
            \
             2

Bu ağaç, her düğümün sol çocuğunun kendisinden küçük, sağ çocuğunun ise kendisinden büyük olduğu bir yapıya sahiptir.
