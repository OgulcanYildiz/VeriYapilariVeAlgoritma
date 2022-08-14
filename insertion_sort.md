# Insertion Sort Projesi #

[Patika.dev linkim](https://app.patika.dev/ogulcaanyldz)

### [22,27,16,2,18,6]  ##

- Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

1. Insertion sort listede soldan sağa ilerleken her elemanı solundaki eleman ile kıyaslayıp, küçükten büyüğe sıralar.
2. 22 sayısı en baştadır bü yüzden ona dokunulmaz ve devam eder.
3. 27 sayısı bir solundaki 22 ile kıyaslanır daha büyük olduğu için yerinde kalmaya devam eder.
4. 16 sayısı 27 ile kıyaslanır ve 27'nin yerini alır daha sonra da 22 ile kıyaslanınca onun yerine geçer ve yeni sıralama [16,22,27,2,18,6] olur.
5. Sıra 2 sayısına gelince sırasıyla 27-22-16 ile yer değiştirir yeni sıralama [2,16,22,27,18,6] olur.
6. 18 sayısı da 27 ve 22 ile yer değiştirir 16 dan büyük olduğu için orada kalır. Yeni sıralama [2,16,18,22,27,6] olur.
7. Son olarak 6 sayısı bir solundakiyle kıyaslanarak 2 ve 16 sayısının arasına yerleşir dizinin son hali [2,6,16,18,22,27] olacaktır.

- Dizinin Big-O gösterimini yazınız.
O(n^2)

- Time Complexity:

1. Best Case: Aradığımız sayının dizinin en başında olması durumu. "n"

2. Average Case: Aradığımız sayının ortada olması, gerçek hayatta karşılaşmamızı beklediğimiz durum. "n^2"

3. Worst Case: Aradığımız sayının sonda olması. "n^2" 

- Dizi Sıralandıktan Sonra 18 Sayısı Hangi Case Kapsamına Girer ? 
 
 Dizimizin ortanca terimi olduğu için average case kapsamına girer.

- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. [7,3,5,8,2,9,4,15,6]
2. [3,7,5,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]  
