# Binary-Search-Tree-Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root 7'dir. 
* 5 roottan küçük olduğu için soluna yazılır
* 1 roottan küçük ve 5 ten küçük olduğu için 5 in soluna yazılır
* 8 roottan büyük olduğu için 7 nin sağına yazılır
* 3 roottan küçük 5 ten küçük, 1 den büyük olduğu için 1 in sağına yazılır
* 6 roottan küçük 5 ten büyük olduğu için 5 in sağına yazılır
* 0 roottan küçük 5 ten küçük, 1 den küçük olduğu için 1 in soluna yazılır
* 9 roottan büyük 8 den büyük olduğu için 8 in sağına yazılır
* 4 roottan küçük 5 ten küçük, 1 den büyük, 3 ten büyük olduğu için 3 ün sağına yazılır
* 2 roottan küçük 5 ten küçük, 1 den büyük, 3 ten küçük olduğu için 3 ün soluna yazılır


                               (7)
                              /   \
                            (5)    (8)
                            / \      \
                          (1) (6)     (9)
                         /   \
                       (0)   (3)
                            /   \
                          (2)   (4)
