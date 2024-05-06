# sofsuz_proje

Kullandığım dataset:https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data

Öncelikle, 'boston.csv' dosyasından ev fiyatları veri setini yükledik. Bu veri seti, Boston şehrindeki evlerin özelliklerini ve fiyatlarını içeriyor.
Veri setinden bağımsız değişkenler (ev özellikleri) ve bağımlı değişken (fiyatlar) olarak bilinen verileri ayırdık. Bu, makine öğrenimi modelimizi eğitmek için kullanacağımız giriş ve çıkışları belirlememize yardımcı oldu.
Ardından, veri setini eğitim ve test setlerine böldük. Bu, modelimizi eğitirken kullanacağımız verileri ve ardından modelin ne kadar iyi performans gösterdiğini test etmek için kullanacağımız verileri ayırmamızı sağladı.
Eğitim verilerine polinom özellikleri ekledik. Bu, veri setimizdeki özelliklerin (örneğin, evlerin yaşları, odaların sayısı vb.) karmaşık ilişkilerini daha iyi ifade etmek için kullanılan bir tekniktir.
Daha sonra, bir lineer regresyon modeli oluşturduk ve eğitim verilerine uydurduk. Bu model, ev fiyatlarını özelliklerine dayalı olarak tahmin etmek için kullanılacak.
Şimdi, modelimizi test verileri üzerinde kullanarak ev fiyatlarını tahmin ediyoruz. Bu, modelimizin ne kadar iyi çalıştığını değerlendirmemize yardımcı olacak.
Tahmin edilen ve gerçek ev fiyatlarını karşılaştırarak, modelimizin ne kadar doğru tahminler yaptığını kontrol ediyoruz.
Son olarak, modelimizin performansını değerlendirmek için ortalama mutlak hata kullanıyoruz. Bu, tahminlerimizin gerçek değerlerden ne kadar uzak olduğunu ölçmemize yardımcı olur.

