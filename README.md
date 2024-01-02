# SelectionSortProjesi

Kodluyoruz FrontEnd 101 Eğitiminde Selection Sort Proje Reposu


22,27,16,2,18,6 – Birinci aşama: İlk elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 2 sayısının en küçük olduğu görülür, 2 ile 22 yer değiştirir.

2,27,16,22,18,6 – İkinci aşama: İkinci elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 6 sayısının en küçük olduğu görülür, 6 ile 27 yer değiştirir.

2,6,16,22,18,27 – Üçüncü aşama: Üçüncü elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 16 sayısının en küçük olduğu görülür, yer değiştirme olmaz.

2,6,16,22,18,27 – Dördüncü aşama: Dördüncü elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 18 sayısının en küçük olduğu görülür, 18 ile 22 yer değiştirir.

2,6,16,18,22,27 – Beşinci aşama: Beşinci elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 22 sayısının en küçük olduğu görülür, yer değiştirme olmaz.

2,6,16,18,22,27 – Altıncı aşama: Altıncı elemandan daha büyük sayı olmadığı için sıralama burada sona erer.


Big-O Gösterimi:
n+(n-1)+(n-2)+........1=n*(n+1)/2=(n²+n)/2=> O(n²)


Dizi sıralandıktan sonra 18 sayısı dizinin ortasında yer alacağından dolayı “average case” kapsamına girer.


7,3,5,8,2,9,4,15,6 – Birinci aşama: İlk elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 2 sayısının en küçük olduğu görülür, 2 ile 7 yer değiştirir.

2,3,5,8,7,9,4,15,6 – İkinci aşama: İkinci elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 3 sayısının en küçük olduğu görülür, yer değiştirme olmaz.

2,3,5,8,7,9,4,15,6 – Üçüncü aşama: Üçüncü elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 4 sayısının en küçük olduğu görülür, 4 ile 5 yer değiştirir.

2,3,4,8,7,9,5,15,6 – Üçüncü aşama: Üçüncü elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 4 sayısının en küçük olduğu görülür, 4 ile 5 yer değiştirir.

2,3,4,8,7,9,5,15,6 – Dördüncü aşama: Dördüncü elemandan başlanarak sona doğru sırayla bütün elemanlara bakılır, 5 sayısının en küçük olduğu görülür, 5 ile 8 yer değiştirir.

2,3,4,5,7,9,8,15,6
