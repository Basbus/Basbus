[22,27,16,2,18,6] -> Insertion Sort
 
	1.Aşamaları
1.[2,22,27,16,18,6]
2.[2,6,22,27,16,18]
3.[2,6,16,22,27,18]
4.[2,6,16,18,22,27]

	2.Big O Notation
O(n^2)

	3.Time Complexity
Worst Case = n.(n+1)/2 = n^2 dominant terimdir 
Avarage Case = bununda yukarıdaki gibi bir formülle çözüldüğünü varsayarsak yine dominant terim n^2 dir yani O(n^2)
Best Case= n dolayısıyla 0(n)

	4. 18 Sayısını Arama
Dizinin ortasında yer aldığından dolayı Avarage Case'dir

	[7,3,5,8,2,9,4,15,6] ilk 4 adım

[2,7,3,5,8,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
[2,3,4,5,7,8,9,15,6]
