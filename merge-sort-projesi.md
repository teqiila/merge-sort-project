[16,21,11,8,12,22] -> Merge Sort

Divide and conquer prensibiyle dizi sürekli olarak parçalanır.

1. Aşama --> [16,21,11|8,12,22]

2. Aşama --> [|16|,|21,11|,|8|,|12,22|] --> 2'li grupları kendi aralarında sıralıyoruz.

3. Aşama --> [|16|,|11,21|,|8|,|12,22|] --> grupları birleştirme aşaması --> Birleştirme aşamasında sıralamayı düzenliyoruz.

4. Aşama --> [|11,16,21|,|8,12,22|] --> 3'lü grupları birleştiriyoruz. -->Birleştirme aşamasında sıralamayı düzenliyoruz.

5. Aşama --> [8,11,12,16,21,22]

Big-O(nlogn) 