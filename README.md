# Patika-Java-Project03-Binary-Search-Tree

# Proje 3

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


## YANIT:

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

- bu dizide root dizideki ilk değer olan 7'dir. 

- 7 root olduğuna göre 7'den sonra gelen 5 rakamı 7'den küçük olduğu için 7'nin soluna alınır, 

- 5'den sonra gelen 1 rakamı 7'den küçük olduğu için 7'nin soluna alınır, solda 5 rakamı olduğu için gelen 1 rakamı onunla da karşılaştırılır ve 5'den küçük olduğu için 5'in soluna alınır,

- 1 rakamından sonra dizindeki 8 rakamına sıra gelir ve ilk olarak root seçilen 7 rakamı ile karşılaştırılır ve büyük olduğu için 7'nin sağına alınır. Burada başka rakam yoktur, dizideki diğer rakam olan 3'e geçilir.

- bu şekilde sıralama tüm liste için devam eder ve sonunda aşağıdaki tree görüntüsü ortaya çıkar.

![image](https://user-images.githubusercontent.com/99753834/154845032-f6b15ad2-d94e-4fc3-b2e6-c97955ffc1cf.png)

