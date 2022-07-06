# kodluyoruz merge sort projesi

[16,21,11,8,12,22] -> Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.

1- diziyi tek eleman kalana kadar parcalıyoruz:
  - **1** [16,21,11] ve [8,12,22]
  - **2** [16]  [21,11] ve [8,12]  [22]
  - **3** [16]  [21]  [11] ve [8]  [12]  [22] *simdi birleştirirken sıralıyoruz*
  - **4** [16]  [11,21]  ve [8,12]  [22]
  - **5** [11,16,21] ve [8,12,22]
  - **6** [8,11,12,16,21,22]
  
2- Big-o-notation: O(nlogn)
  n = 6, O(6log6)
  
