## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

> Binary Search Tree: Bir düğüm her iki tarafa da referans verebiliyor. Sağ ve sol olarak. Sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.


            7
            /   \
         5     8 
         /   \     \
      1       6       9
      /   \
     0     3
         /   \         
        2     4

Root(kök) 7’dir
Rootun sağı -> [8, 9]
Rootun solu -> [0, 1, 2, 3, 4, 5, 6]