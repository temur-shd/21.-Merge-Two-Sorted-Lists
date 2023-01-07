# 21.-Merge-Two-Sorted-Lists
21. İki Sıralanmış Listeyi Birleştir (LinkedList)

<br>
Input: list1 = [1,2,4], list2 = [1,3,4]
Output: [1,1,2,3,4,4]

Soruda Kısıtlamalar verilmiştir:

Her iki listedeki düğüm sayısı [0, 50] aralığındadır.
-100 <= Düğüm.val <= 100
Hem list1 hem de list2, azalan sıraya göre sıralanır.

Yeni Boş bir dummy node oluşturuyoruz ve liste1 ve liste2 'yi döngü yardımıyla ilerleyerek tarıyoruz ve küçük olanı dummy node'a atıyoruz. next() fonksiyonu ile yineleyicideki sonraki öğeyi döndürüyoruz.
