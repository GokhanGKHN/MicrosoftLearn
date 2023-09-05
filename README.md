Oyun Konsol Uyuglaması:
İlk iki satır hero ve masterın canlarını temsil ediyor. 
4.line'da Random sınıfından dice adında bir ınstance üretiyoruz. 
6.line'da do while döngüsü içerisinde Random class'dan türettiğimiz dice ınstance'nın Next metodu ile 1 ile 11 arasında randım sayıları üretip roll değişkenine atıyoruz. 
9.line'da rolle değişkeni içerisindeki random sayıyı -= operatörü ile monster'ın canından düşmek için - olarak atıyoruz. 
10.line'da string interpolation yöntemiyle roll içerisindeki random sayıyı ve monster içerisideki kalan canı her seferinde console çıktılıyoruz. 
11.Line'da konuşullu ifade ile monster'ın can durumunu kontrol ediyoruz. Eğer can durumu eksi ise continue ifadesi ile atlıyoruz. 
16. ve 18.Line'lar 8 ile 10 Line'lar ile aynıdır. 
21.Line'da do while döngüsünün while koşul parantezinde hero canı sıfırdan büyükse ve monster'ın canı sıfırdan büyükse koşuldan çıkıyoruz. 
23.Line'da ternary operatörü ile hero ile monster'ın canlarını karşılaştırıyoruz. Buyük olan kazanıyor. :D
