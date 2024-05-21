[22,27,16,2,18,6] -> Bize verilen dizi

Sıralama Aşaması; 
	Başlangıç Aşaması : [22,27,16,2,18,6]
	1-"22" Sabit kalır ve yerine geçici olarak 27 alınır.
	2-"16" Yapılan kıyaslama ile en uygun yere yerleştirilir : [16,22,27,2,18,6]
	3-"2"  Yapılan kıyaslama ile en uygun yere yerleştirilir : [2,16,22,27,18,6]
	4-"18" Yapılan kıyaslama ile en uygun yere yerleştirilir : [2,16,18,22,27,6]
	5-"6"  Yapılan kıyaslama ile en uygun yere yerleştirilir : [2,6,16,18,22,27]


Big-O ile gösterimini yaptığımız zaman "O(n^2)" olduğunu görürüz, bu da karesel bir artış ile listenin büyüdüğünü bize ifade eder.

Time Complexity: 18 sayısı dizi tamamen sıralandıktan sonra worst case'e (2.case) girer bu da arama işlemini sondan başlatır.

Özet : 
	-> Average Case : O(n^2)
	-> Worst Case : 2.Case
	-> Best Case : 3.Case
