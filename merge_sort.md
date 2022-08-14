# Merge Sort Projesi #

- [Patika.dev linkim](https://app.patika.dev/ogulcaanyldz)

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. Dizimizi iki gruba, her grup tek eleman içerene kadar bölüyoruz.
2.                   [16,21,11]   --   [8,12,22]
3.            [16,21]  -- [11] --------- [8,12] -- [22]
4.       [16] -- [21] -- [11]  ---------- [8] -- [12] -- [22]

5. Tek elemanlı olan yeni dizilerimizi ikili ikili sıralayarak birleştiriyoruz.
6.      [16] -- [21] -- [11]  ---------- [8] -- [12] -- [22]
7.           [16,21]  -- [11] --------- [8,12] -- [22]
8.                   [11,16,21]   --   [8,12,22]
9.                           [8,11,12,16,21,22] elde ederiz.




- Big-O gösterimini yazınız.

O(nlogn) olur yani bu dizide O(6log6) olur.