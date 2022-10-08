https://app.patika.dev/hikaratas
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

                  [Root]
                    [7]
                    / \
                   /   \
                 [5]   [8]
                 / \     \
                /   \     \
              [1]   [6]   [9]
              /  \     
             /    \
           [0]    [3]
                  / \
                 /   \
               [2]   [4]

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
1-) Root: 7 dir.

2-) 5 Sayısı 7'den küçük olduğu için 7'nin soluna eklenir.

3-) 1 Sayısı 7'den ve 5'den küçük olduğu için 5'in soluna eklenir.

4-) 8 Sayısı 7'den büyük olduğu için 7'nin sağına eklenir.

5-) 3 Sayısı 7 ve 5'den küçük, 1'den büyük olduğu için 1'in sağına eklenir.

6-) 6 Sayısı 7'den küçük 5'den büyük olduğu için 5'in sağına eklenir.

7-) 0 Sayısı 7'den 5 ve 1'den küçük olduğu için 1'in soluna eklenir.

8-) 9 Sayısı 7'den ve 8'den büyük olduğu için 8'in sağına eklenir.

9-) 4 Sayısı 7'den ve 5'den küçük, 1 ve 3'den büyük olduğu için 3'ün sağına eklenir.

10-) 2 Sayısı 7'den ve 5'den küçük, 1'den büyük olduğu için 1'in sağına, 3'den küçük olduğu için 3'ün soluna eklenir.