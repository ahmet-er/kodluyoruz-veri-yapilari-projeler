# insertion sort project

1. [22,27,16,2,18,6] -> insertion sort türüne göre aşamaları:
- **1** [2,27,16,22,18,6]
- **2** [2,6,16,22,18,27]
- **3** [2,6,16,22,18,27] *16 sayısı yerinde oldugu icin ayni kalir*
- **4** [2,6,16,18,22,27]
- **5** [2,6,16,18,22,27] *22 sayısı yerinde oldugu icin ayni kalir*
- **6** [2,6,16,18,22,27] *27 sayısı yerinde oldugu icin ayni kalir*

2. Big-o notation: *O(n^2)*
  n=6, O(6^2) = ***O(36)***

3. Time Complexity:
  - Average Case: **16, 18**
  - Worst Case: **27**
  - Best Case: **2**

4. Dizi sıralandıktan sonra 18 sayısı *average case* kapsamına girer.

## ikinci dizi [7,3,5,8,2,9,4,15,6] ilk 4 adımını sıralama:
- **1** [2,3,5,8,7,9,4,15,6]
- **2** [2,3,5,8,7,9,4,15,6] *3 sayısı yerinde oldugu icin ayni kalir*
- **3** [2,3,4,8,7,9,5,15,6]
- **4** [2,3,4,5,7,9,8,15,6]
