 www.patika.dev 

### 1.Soru

## Insertion Sort Projesi

[22,27,16,2,18,6]

# 1.)İlk sayıdan başlayarak kendisinden küçük olan sayıları "|" sembolünün soluna,büyük olanları da sağına koyarız.

1.)[22 |,27,16,2,18,6]

2.)[22,27 |,16,2,18,6]

3.)[16,22,27 |,2,18,6]

4.)[2,16,22,27 |,18,6]

5.)[2,16,18,22,27 |,6]

6.)[2,6,16,18,22,27 ]

# 2.)Big O Gösterimi

Best Case = O(n)

Average Case = O(n^2)

Worst Case = O (n^2)

# 3.)Time Complexity

Worst Case : [27,22,18,16,6,2]

Best Case : [2,6,16,18,22,27]

# 4.) 18 sayısının Case 'i nedir?

Average Case = [2,6,16,18,22,27]


### 2.Soru

# 1.)[16,21,11,8,12,22]

1.adımda verilen dizi ikiye bölünür.

2.adımda kalan 3 er sayı da kendi içinde bölünür.

3.adımda kendi içinde sayılar sıralanır ve iki ayrı şekilde sıralama yapılır.

4.adımda iki ayrı şekilde sıralanan 3 er sayı birleştirilerek kendi aralarında sıralama yapılır.

# 2.)Big O Gösterimleri

Best Case = O(n*logn)

Average Case = O(n*logn)

Worst Case = O(n*logn)


# 3.Soru 

[7,5,1,8,3,6,0,9,4,2]

1.adımda ilk elemanımız root olur,daha sonrasında sağa doğru tek tek ilerleyerek Binary Search Tree 'nin sağına ve soluna elemanlar yazılarak

sonuç elde edilir.

                                             7 
                                           /   \
                                          5      8
                                         / \       \
                                        1    6       9          
                                       /  \          
                                      0     3 
                                           /  \
                                          2     4
