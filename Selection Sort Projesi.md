[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] n
2

En küçüğü seçilir ve baştaki ile yer değiştirilir.

[2,27,16,22,18,6] n-1
6
İkinci en küçük seçilir ve 2. sıra ile degiştirilir.

[2,6,16,22,18,27] n -2
16 ok
18
[2,6,16,18,22,27] 1
22

Big-O gösterimini yazınız.
Big-o : O(n^2)


Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] 
2
[2,3,5,8,7,9,4,15,6] 
3 ok, 4
[2,3,4,8,7,9,5,15,6] 
5
[2,3,4,5,7,9,8,15,6] 
6
[2,3,4,5,6,9,8,15,7]
