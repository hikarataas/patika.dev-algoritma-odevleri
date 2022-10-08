https://app.patika.dev/hikaratas

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

          [16,21,11,8,12,22]
                 / \
                /   \
        [16,21,11]  [8,12,22]
                 / \
                /   \
        [16,21][11] [8,12][22]
                  / \
                 /   \
    [16] [21] [11]   [8][12][22]
                 /  \
                /    \
    [16,21][8,11]   [12,22]
                 /  \
                /    \
    [8,11,16,21]    [12,22]
                  |
          [8,11,12,16,21,22]
        
        Big-O gösterimi 0(nlogn)
Big-O gösterimini yazınız.