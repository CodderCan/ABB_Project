Ticar@ Yazılımcı Akademisi ABB Projesi


Uygulamamızın amacı: Bir bilimsel çalışmada, kullanılmakta olan 
tüm kısaltmaların açıklamalarıyla birlikte,
"Kısaltmalar Tablosu" oluşturularak eklenmesi ve Microsoft Word 
uygulamasıyla ilişkilendirilmesidir.


Uygulamamızı kullanmak için 2 farklı yolumuz vardır:

1: Windows Uygulaması

	"ABB_Project.exe" adlı uygulamayı çalıştırıp önce yazdığınız metni seçip 
	daha sonra kaydedileceği konumu seçerek işlemi başlatmak. İşlemi başlattıktan sonra
	birden fazla açıklama varsa kısaltmanızda hangi açıklamayı  kullanacağınızı size soracaktır. 
	Seçiminizi yaptıktan sonra kaydedilen dosyanın son sayfasında kısaltmalarınızı bulabilirsiniz.

2: Microsoft Word Makrosu 

	2.1: Microsoft Word Uygulaması ile metninizi açınız.
	2.2: Sol üstteki "Dosya" butonuna tıklayınız.
	2.3: Sol alttan "Seçenekler" butonuna tıklayın.
	2.4: "Şeridi Özelleştir" sekmesini açınız sağ taraftaki tablodan "Geliştirici" seçeneğinin
yanındaki kutuyu işaretleyin ve "Tamam"a tıklayarak kapatın.
	2.5: Üstteki menüden "Geliştirici" sekmesini açınız. Sol taraftaki "Visual Basic" butonuna tıklayın.
	2.6: Zip Dosyası içerisindeki "KisaltmaEslestirme.bas" dosyasını sol taraftaki "normal" yazan yere
sürükleyip bıraklınız, Modules klasörü içerisinde NewMakros Dosyası gelecektir.
	2.7: NewMakros yazan dosyayı çift tıklayarak açınız. "Sabit Excel dosya yolunu belirtin" kısmında
excelPath = "Dosyakonumu/kisaltmalar.xlsx" dosya konumunu giriniz ve yukarıda bulunan yeşil çalıştırma butonuna
veya F5'e tıklayarak makroyu çalıştırabilirsiniz.
	