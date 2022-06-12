# project-of-insertion-sort
Soru 1 Cevabı

[22,27,16,2,18,6]

İlk Geçiş -İlk sayımız 22 olduğu için 22 ye göre başlarız.

İkinci geçiş -ikinci sayı(27) 22 den küçük bir şey yapmadan devam eder. [22,27,16,2,18,6]

Üçüncü geçiş -Üçüncü sayı(16) ikinci sayıdan küçük yer değiştirir(swap) [22,16,27,2,18,6] -Daha sonra 16 ile 22 yi kıyaslar ve 16 ,22 den küçük tekrar yer değiştirilir [16,22,27,2,18,6]

Dördüncü geçiş -Dördüncü sayımız(2) üçüncü sayıdan küçük olduğu için swap olur [16,22,2,27,18,6] -2 sayısı 22 ve 16 dan küçük olduğu için 2 sayıyla da swap edilir [16,2,22,27,18,6]->[2,16,22,27,18,6]

Beşinci Geçiş -Beşinci sayımız(18) dördüncü sayıdan(27) küçük olduğu için swap edilir [2,16,22,18,27,6] -18 , 22 den de küçük olduğu için tekrar swap edilir [2,16,18,22,27,6]

Altıncı geçiş -Altıncı sayımız(6) beşinci sayımızdan(27) küçük olduğu için swap edilir [2,16,18,22,6,27] [2,16,18,6,22,27]->[2,16,6,18,22,27]->[2,6,16,18,22,27]

Soru 2 Cevabı Tüm elemanları kontrol ettiğimiz için (n.(n-1))/2 = n^2 big o gösterimi O(n2)

Soru 3 Cevabı Best Case= aradığımız sayı dizinin basında ise O(n) Worst Case = aradığımız sayı sonda ise O(n^2) Avarage Case = best case worst case ortalaması O(n^2)

Soru 4 Cevabı Dizi sıralanınca ->[2,6,16,18,22,27] 18 ortada olduğu için avarage case kısmına girer

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

1.Adım [3,7,5,8,2,9,4,15,6] 2.Adım [3,5,7,8,2,9,4,15,6] 3.Adım değişiklik olmaz 3. sayı(7) 4. sayıdan(8) küçük 4.Adım [3,5,7,2,8,9,4,15,6]->[3,5,2,7,8,9,4,15,6]->[3,2,5,7,8,9,4,15,6]->[2,3,5,7,8,9,4,15,6]
