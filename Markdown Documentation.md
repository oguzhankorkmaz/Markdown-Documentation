# Markdown
	
Markdown, düz metin belgelerine biçimlendirme öğeleri eklemek için kullanabileceğiniz hafif bir biçimlendirme dilidir. Markdown biçimli bir dosya oluşturduğunuzda, hangi sözcüklerin ve ifadelerin farklı görünmesi gerektiğini belirtmek için metne Markdown sözdizimi eklersiniz.

# Başlık	

Başlık oluşturmak için başına (#) işareti koyulmalıdır. Başlık düzeylerine göre (#) işareti arttırılır. İkinci düzey başlık için (##), Üçüncü düzey başlık için (###) kullanılmaktadır.
 
## Başlıkların HTML karşılığı
Başlık oluşturmak için kullanılan (#) işareti HTML kodlarındaki <h'1'> etiketine karşılık gelmektedir. Kullanılan (#) işaretinin sayısı kadar etiketimiz <h1,2,3,4,5,6> şeklinde değişmektedir. 

>(#) -> h1
>(##) -> h2
>(###) -> h3
>(####) -> h4
>(#####) -> h5
>(######) -> h6

## Alternatif kullanım
Başlık oluşturmak için başlığın altına oluşturmak istenen dereceye göre (=) ya da (-) işareti kullanılabilir.


# Paragraf
Paragraf oluşturmak için, bir veya daha fazla metin satırını ayırmak için boş bir satır kullanın. HTML kodlarında < p > etiketine karşılık gelmektedir.
> Örnek paragraf kullanımı.

# Satır Kesintileri

Satır sonu (< br >) oluşturmak için, bir satırı iki veya daha fazla boşlukla bitirilmektedir.

# Vurgu  
Metni kalın veya italik yaparak vurgu ekleyebilirsiniz.

## Kalın
Metni kalınlaştırmak için, bir sözcük veya tümcecikten önce ve sonra iki yıldız veya alt çizgi ekleyin.  Vurgu yapmak için bir kelimenin ortasını kalınlaştırmak için harflerin etrafına boşluk bırakmadan iki yıldız işareti ekleyin.
> ** Örnek ** -> **Örnek**
> __ Örnek __ -> __Örnek__

## İtalik  
Metni italik hale getirmek için, bir sözcük veya tümcecikten önce ve sonra bir yıldız işareti veya alt çizgi ekleyin.  Vurgu yapmak için bir kelimenin ortasını italik yapmak için harflerin etrafına boşluk bırakmadan bir yıldız işareti ekleyin.
> (* Örnek *) -> *Örnek*
> _ Örnek _ -> _Örnek_

### Kalın ve İtalik Kullanımı
> *** Örnek *** -> ***Örnek***
> ___ Örnek ___ -> ___Örnek___

# Blok alıntılar
 Blok alıntı oluşturmak için paragrafın önüne > ekleyin.
 > Örnek olarak oluşturulmuş blok alıntı

## İç içe geçmiş blok alıntılar
 Blok alıntılar yuvalanabilir.  İç içe yerleştirmek istediğiniz paragrafın önüne bir >> ekleyin.
 
">" Ana Blok
">>"1. Alt Blok
">>>" 1. Alt Alt Blok
">>" 2. Alt Blok
">>>"2. Alt Alt Blok
 > Ana Blok
 > > 1. Alt Blok
 > >> 1. Alt Alt Blok
 > >2. Alt Blok
 > >>2. Alt Alt Blok
 > >>>>>>>>>>> blok

# Listeler
Öğeleri sıralı ve sırasız listeler halinde düzenleyebilirsiniz.

## Sıralı Listeler
Sıralı bir liste oluşturmak için, sayıları ve ardından nokta olan satır öğeleri ekleyin.  Numaraların sayısal sırada olması gerekmez, ancak liste bir numara ile başlamalıdır. HTML'de < ol > < li > </ li> </ ol> elementlerine karşılık gelmektedir.

"1. First item  "  -> 
"2. Second item " 
"3. Third item  "
"4. Fourth item"	
1. First item  
3. Second item  
4. Third item  
5. Fourth item

## Sırasız Listeler  
Sırasız bir liste oluşturmak için satır öğelerinin önüne kısa çizgiler (-), yıldız işaretleri (*) veya artı işaretleri (+) ekleyin.  İç içe bir liste oluşturmak için bir veya daha fazla öğenin girintisini artırın. HTML'de < ul > < li > </ li> </ ul> elementlerine karşılık gelmektedir.

"- First item  "
"--" İtem
" * Second item"
" + Third item "
- First item  
-- İtem
---İtem
* Second item  
* * İtem
*  * * İtem
+ Third item  
+  + İtem
+ + + İtem

# Tablolar
Tablo oluşturmak için ( | , -) şekillerini ayırıcı olarak kullanıyoruz. Kolonları ayırırken ( | ), sütünları ( - ) işareti kullanılır.

Sayı| Renk
----- | -----
1| Sarı
2| Kırmızı
3| Mavi
4| Mor
5| Pembe 
6| Yeşil


# Kod Blokları  
Kod blokları normalde dört boşluk veya bir sekme girintilidir.  Listede olduklarında, onlara sekiz boşluk veya iki sekme girin. yada (`) kullanılmalıdır.
 ```
	<html>
		<head></head>
		<body>
			<p>Araba</p>
		</body>
	</html>
```


# Yatay Kurallar 
Yatay bir kural oluşturmak için, bir satırda kendi başına üç veya daha fazla yıldız işareti (***), kısa çizgi (---) veya alt çizgi (___) kullanın.

>Örnek
"___"
Yatay çizgi

> Örnek
> ___
> Yatay çizgi

# Bağlantılar  
Bir bağlantı oluşturmak için, bağlantı metnini köşeli parantez içine alın (ör. [Duck Duck Go]) ve ardından onu hemen parantez içindeki URL ile takip edin.
> (ör. [Google] (https://google.com))

# URL'ler ve E-posta Adresleri  
Bir URL'yi veya e-posta adresini hızlı bir şekilde bağlantıya dönüştürmek için, (<,>) içine alın.

"<"https://www.markdownguide.org">"
<https://www.markdownguide.org>
<fake@example.com>


# Görev Listesi
Görev listelerini  yapmak için her görevin başına kısa çizgi(-) eklendikten sonra. Onay kutularını köşeli parantez( [] ) ile eklenmektedir. Onay kutusu seçilmiş olan görevlerin köşeli parantez içerisine "x" koyulması gerekmektedir.
 
- [x] Write the press release

- [ ] Update the website

- [ ] Contact the media


# Dipnotlar
Herhangi bir kelime ya da metine dipnot eklenmesi köşeli parantez( [ ] ) içine ^sayi olacak şekilde yapılmaktadır.

> dipnot.[^1]

[^1]: İlk Dipnot
