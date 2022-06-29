# Merge Sort Project


## Soru 1
*MERGE SORT divide and conquere yapısını benimser. İlk başta tüm sayıları tek hane kalana kadar böleceğiz ardından sıralayarak birleştireceğiz.*

  * CEVAP

      * [16,21,11,8,12,22]

      * [16,21,11] [8,12,22]

      * [16] [21,11]  -  [8] [12,22]

      * [16] [21] [11] - [8] [12] [22]

      * 16 [11,21] 8 [12,22]

      * [11,16,21] [8,12,22]

      * [8,11,12,16,21,22]
      
    ---
      ## Soru 2
      * Big-O gösterimini yazınız.*

* CEVAP

  O(nlog(n))