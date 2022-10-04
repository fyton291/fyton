# fyton

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


ÇÖZÜM:
[22,27,16,2,18,6] -> Insertion Sort için:
n kadar sayı var yani 6 sayı var
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
olarak düzenlenmiş oldu
6 tane sayı arasında en küçüğü bulduk
sonra 5 sayı içinde en küçüğü bulup yer değiştik
4 sayı içinde yer değişimi olmadı ama baktık yinede
geriye kalan 3 sayı içinde yer değişimi oldu
geriye kalan son 2 sayı içinde en küçüğü kontrol edildi
ve en son olarak en büyük sayı sağda kaldı
Big O gösterimi olarak insertion da n^2 olarak gösterilir. = O(n^2)
dizi sıralanınca 18 sayısı average case olacaktır beklenendir.
veya şu şekilde düşünürsek 2 ye bölüp bakar ve sayı sağda mı soldamı diye baktığımız anda sayı aslında sağda kaldığını görürüz ve bizim için O(logn ) olacaktır.


ÇÖZÜM 2=
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

https://app.patika.dev/fyton
