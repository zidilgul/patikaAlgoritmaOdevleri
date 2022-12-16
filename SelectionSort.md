# Selection Sort Projesi 

## 1. Insertion Sort 

a. [22,27,16,2,18,6] -> Insertion Sort
  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  
  : 1.aşama -> [2,27,16,22,18,6] en küçük elemanı ilk sıraya yerleştirdik ve ilk sıradaki elemanı bu elemanın yerine taşıdık.
    2.aşama -> [2,6,16,22,18,27] ikinci elemandan itibaren aynı işlemler yapıldı.
    3.aşama -> [2,6,16,22,18,27] 3. elemanın yeri doğru değişiklik olmadı.
    4.aşama -> [2,6,16,18,22,27] dördüncü elemandan itibaren 2.aşamadaki işlemler yapıldı. Bu aşamadan sonra 5. eleman kontrolü yapılır.
   Elemanların yeri doğru olduğu için değişiklik yapılmadı.
   
b. Big O gösterimi yapınız
  
  :  O(n^2)
  
c. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

  : Average case.
  
 ## 2. Selection Sort
  
 [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 
 
 : 1.aşama -> [2,3,5,8,7,9,4,15,6] listenin ilk elemanı alınır kendinden sonraki elemanlarla karşılaştırılır en küçükle yer değiştirir.
   2.aşama -> [2,3,4,8,7,9,5,15,6] listenin ikinci elemanı alınır kendinden sonraki elemanlarla karşılaştırılır en küçükle yer değiştirir. 
   3.aşama -> [2,3,4,5,7,9,8,15,6] listenin üçüncü elemanı alınır kendinden sonraki elemanlarla karşılaştırılır en küçükle yer değiştirir.
   4.aşama -> [2,3,4,5,6,9,8,15,7] listenin dördüncü elemanı alınır kendinden sonraki elemanlarla karşılaştırılır en küçükle yer değiştirir. 
