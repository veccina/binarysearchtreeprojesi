# Binary Search Tree Proje
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Root olarak ilk değer 7 alınır.
            

                        7 (root)
                      /   \
                     5     8 
                   /   \     \
                  1     6     9
                 / \
                0   3
                  /  \
                 2    4
1. Görüldüğü üzere dizide ilk olarak 5 bulunmaktadır bu sebeple root'un sol çocuğu olur.
2.  Dizide sırada 1 bulunmaktadır. 1 hem roottan hem 5'ten küçük olduğu için 5'in sol çocuğu olur.
3. Dizide sırada 8 bulunmaktadır. 8 roottan büyük olduğu için sağ çocuğu olur.
4. Dizide sırada 3 bulunur. 3 roottan, 5'ten küçük ancak 1'ten büyüktür bu sebeple 1'in sağ çocuğu olur.
5. Dİzide sırada 6 bulunmaktadır. 6 Elemanı roottan küçük ancak 5'ten büyüktür bu sebeple 5'in sağ çocuğu olur.
6. Sırada 0 bulunmaktadır. 0, hem root hem 5 hem de 1'ten küçük olduğu için 1'in sol çocuğu olur.
7. Sırada 9 bulunmaktadır. 9, roottan ve 8'ten büyük olduğu için 8'in sağ çocuğu olur.
8. sırada 4 bulunmaktadır. 4, roottan ve 5'ten küçük ancak 1 ve 3'ten büyüktür. Bu sebeple 3'ün sağ çocuğu olur.
9. Son olarak 2 değeri roottan, 5'ten küçük 1'den büyüktür. Ancak 3 değerinden küçüktür. Bu sebeple 3 değerinin sol çocuğu olur.