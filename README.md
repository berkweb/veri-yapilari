# veri-yapilari

**Odev#1**
Insertion Sort:

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

      #Cevaplar:
  
          [6,27,16,2,18,22]
          [6,2,16,27,18,22]
          [6,2,16,27,18,22]
          [6,2,16,18,27,22]
          [6,2,16,18,22,27]

                Big-O -> Islemler n'den 1'e kadar gidecegi icin, 1'den n'e kadar olan sayilarin toplami sonucu verecektir.
                    n.(n+1)/2 
                    =n^2

                ->  o(n^2)

           Time Complexity: [6,2,16,18,22,27] siralama yandaki gibi olacagindan 6 = Lower , 27 = Higher ve 18 = Middle olacaktir.
              Bu durumda 18 sayisi icin, Average Case uygundur.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

          #Cevaplar:

          [2,3,5,8,7,4,15,6]
          [2,3,5,8,7,4,15,6]
          [2,3,4,8,7,5,15,6]
          [2,3,4,5,7,8,15,6]


**Odev 2**

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

                  #Cevaplar:

                  [16,21,11] - [8,12,22]
                  [16,21] [11] - [8,12] [22]
                  [16] [21] [11] [8] [12] [22]
                  [16,21] [8,11] [12,22]
                  [8,11,12,16,21,22]

                  Big-O gosterimi : O(nlogn) olacaktir.
                  
