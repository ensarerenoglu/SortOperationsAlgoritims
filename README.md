
# Sort İşlemleri - [22,27,16,2,18,6]

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
	* Insertation Sort
		- [22,27,16,2,18,6] 
		- [2,27,16,22,18,6]
		- [2,6,16,22,18,27]
		- [2,6,16,22,18,27]
		- [2,6,16,18,22,27]
	* Merge Sort
		- [22,27,16,2,18,6]
		- [22,27,16]  [2,18,6]
		- [22]  [27,16]  [2,18]  [6]
		- [22]  [27]  [16]  [2]  [18]  [6]
		- [22] [16,27]  [2,18] [6]
		- [16,22,27]  [2,6,18]
		- [2,6,16,18,22,27]
	* Quick Sort
		- [22,27,16,2,18,6] Pivot 18
		- [16,2,6]  [18] [22,27]
		- [2] [6] [16] pivot 6 [18] [22] [27] pivot 22
		- [2,6,16,18,22,27]
	

- Big-O gösterimini = **O(n^2)**

- Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.

- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? **Average Case**
