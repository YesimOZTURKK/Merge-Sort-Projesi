# Merge-Sort-Projesi
---
## SORULAR

1. [16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 

2.  Merge Sort Big-O gösterimini yazınız.

---
## CEVAPLAR

1.  Bu bölümde önce parçalara ayırıp sonrasında birleştireceğiz.
     * [16,21,11,8,12,22]
     
   [16,21,11]      [8,12,22] 
  
   [16] [21,11]    [8] [12,22]
 
   [16] [21][11]   [8] [12][22]
 
   [16] [11,21]    [8] [12,22]
 
   [11,16,21]      [8,12,22]
 
      [8,11,12,16,21,22]
 
 2.  Big-O= O(nlogn)
