Merge Sort, divide and conquer yöntemiyle çalışan bir sıralama algoritmasıdır. Bu nedenle, verilen dizi ilk olarak iki eşit parçaya ayrılır. Bu parçalar tek tek sıralanır, sonra iki parça tekrar birleştirilir ve böylece dizi tamamen sıralanmış hale gelir.

1. Adım: [16, 21, 11, 8, 12, 22] -> [16, 21, 11] [8, 12, 22]
2.  Adım: [16, 21, 11] -> [16, 21] [11] ve [8, 12, 22] -> [8, 12] [22]
3.  Adım: [16, 21] -> [16] [21] ve [11] [8, 12] -> [8] [11, 12] ve [22]
4.  Adım: [16] [21] -> [16, 21] ve [8] [11, 12] -> [8, 11, 12] ve [22]
5.  Adım: [16, 21] [8, 11, 12] [22] -> [8, 11, 12, 16, 21, 22]

## Big-O gösterimi: O(n log n)

Merge Sort algoritması, her seferinde diziyi ikiye böler ve her bölüm için n elemanını karşılaştırır, böylece çalışma zamanı n log n düzeyindedir.
