✈️ Havayolu Yolcu Memnuniyeti Analizi
Havayolu yolcu memnuniyetini etkileyen temel faktörleri veri temizleme, keşifçi veri analizi (EDA) ve iş odaklı içgörüler aracılığıyla inceleyen uçtan uca bir veri analizi projesi.

Bu projenin temel amacı, ham havayolu anket verilerini karar alma süreçlerini destekleyecek ve müşteri memnuniyetini artıracak anlamlı iş içgörülerine dönüştürmektir.


📌 Projeye Genel Bakış
Müşteri memnuniyeti, havayolu sektöründeki en önemli performans göstergelerinden biridir. Yolcu memnuniyetini hangi faktörlerin etkilediğini anlamak, havayolu şirketlerinin hizmet kalitesini artırmasına, müşteri sadakatini yükseltmesine ve veriye dayalı iş kararları almasına yardımcı olur.

Bu proje, bir havayolu yolcu memnuniyeti veri seti üzerinde uçtan uca keşifçi veri analizi (EDA) gerçekleştirmektedir. Analiz süreci; veriyi anlama, veri temizleme, keşifçi veri analizi ve iş odaklı raporlama adımlarını içermektedir.

Bu projenin temel odak noktası, bir makine öğrenmesi modeli kurmaktan ziyade, veri içindeki anlamlı örüntüleri ortaya çıkarmak ve bunları eyleme geçirilebilir iş içgörülerine (actionable business insights) dönüştürmektir.


🎯 Business Problem
Havayolu şirketleri her uçuştan sonra büyük miktarda müşteri geri bildirimi toplar. Ancak, hangi faktörlerin yolcu memnuniyeti üzerinde en büyük etkiye sahip olduğunu belirlemek zorlayıcı olabilir.

Bu projenin temel amacı, aşağıdaki iş sorularına yanıt bulmaktır:

Yolcu memnuniyeti üzerinde en güçlü etkiye sahip faktörler hangileridir?

Uçuş gecikmeleri müşteri memnuniyetini önemli ölçüde düşürüyor mu?

Business Class yolcuları, Ekonomi sınıfı yolcularına göre daha mı memnun?

Müşteri sadakati memnuniyet seviyelerini etkiliyor mu?

Seyahat amacı müşteri memnuniyetini etkiler mi?



📊 Veri Seti
Veri seti, havayolu yolcularından seyahat deneyimleri ve memnuniyet seviyeleri hakkında toplanan bilgileri içermektedir.

Veri Seti Özeti

Gözlem sayısı: 103.904

Değişken sayısı: 24

Hedef değişken: Memnuniyet (Satisfaction)

Veri seti aşağıdaki konularda bilgiler içermektedir:

Yolcu demografisi

Uçuş bilgileri

Seyahat sınıfı

Müşteri tipi

Uçuş gecikmeleri

Uçak içi hizmet puanları

Genel yolcu memnuniyeti



## 🔍 Methodology

Bu proje, ham verinin iş kararlarını destekleyen anlamlı içgörülere dönüştürülmesi amacıyla uçtan uca (end-to-end) bir veri analizi süreci izlenerek gerçekleştirilmiştir.

Analiz süreci aşağıdaki aşamalardan oluşmaktadır:

### 1. Veri Anlama (Data Understanding)

İlk aşamada veri setinin genel yapısı incelenmiştir. Değişken tipleri, eksik değerler, veri boyutu ve temel istatistiksel özellikler analiz edilerek veri seti tanınmıştır.

---

### 2. Veri Temizleme (Data Cleaning)

Analiz öncesinde veri kalitesini artırmak amacıyla çeşitli veri ön işleme adımları uygulanmıştır.

Bu kapsamda;

- Analiz için anlamlı olmayan sütunlar kaldırılmıştır.
- Sütun isimleri standart bir formata dönüştürülmüştür.
- Veri tipleri optimize edilmiştir.
- Yinelenen kayıtlar kontrol edilmiştir.
- Eksik değerler uygun yöntemlerle giderilmiştir.
- Aykırı değerler tespit edilerek analiz üzerindeki etkileri değerlendirilmiştir.

---

### 3. Keşifsel Veri Analizi (Exploratory Data Analysis)

Veri temizleme sürecinin ardından değişkenlerin dağılımları detaylı olarak incelenmiştir.

Bu aşamada;

- Sayısal değişkenlerin dağılımları analiz edilmiştir.
- Kategorik değişkenlerin frekans dağılımları incelenmiştir.
- Müşteri memnuniyeti ile diğer değişkenler arasındaki ilişkiler görselleştirilmiştir.
- Korelasyon analizi gerçekleştirilmiştir.
- Elde edilen bulgular iş bakış açısıyla yorumlanmıştır.

---

### 4. İş Raporu (Business Report)

Analizlerden elde edilen bulgular yalnızca istatistiksel olarak değerlendirilmemiş, aynı zamanda iş dünyası açısından yorumlanmıştır.

Elde edilen sonuçlar doğrultusunda müşteri memnuniyetini artırmaya yönelik uygulanabilir öneriler geliştirilmiş ve proje genel bir değerlendirme ile tamamlanmıştır.

## 📈 Key Findings

Analiz sonucunda müşteri memnuniyetini etkileyen temel faktörler aşağıda özetlenmiştir.

### 1. Uçuş Sınıfı (Class)

Business Class yolcularının memnuniyet oranı, Economy ve Economy Plus sınıfında seyahat eden yolculara göre belirgin şekilde daha yüksektir. Bu durum, sunulan hizmet kalitesinin müşteri deneyimi üzerinde önemli bir etkisi olduğunu göstermektedir.

---

### 2. Seyahat Amacı (Type of Travel)

İş amaçlı seyahat eden yolcuların memnuniyet oranı, kişisel amaçlı seyahat eden yolculara kıyasla oldukça yüksektir. Bu bulgu, farklı yolcu segmentlerinin beklentilerinin birbirinden farklı olduğunu göstermektedir.

---

### 3. Müşteri Tipi (Customer Type)

Sadık müşteriler (Loyal Customer), sadık olmayan müşterilere göre daha yüksek memnuniyet oranına sahiptir. Bununla birlikte sadık müşteriler arasında da memnun olmayan önemli bir yolcu kitlesi bulunmaktadır.

---

### 4. Uçuş Gecikmeleri

Kalkış ve varış gecikmeleri arttıkça müşteri memnuniyetinin azalma eğiliminde olduğu gözlemlenmiştir. Özellikle yüksek gecikme süreleri memnun olmayan yolcu grubunda daha yaygın görülmektedir.

---

### 5. Uçuş Mesafesi

Memnun olan yolcuların ortalama uçuş mesafesi, memnun olmayan yolculara göre daha yüksektir. Bu durum, uzun mesafeli uçuşlarda sunulan hizmetlerin müşteri deneyimine olumlu katkı sağlayabileceğini düşündürmektedir.

---

### 6. Yaş

Memnun olan yolcuların yaş ortalaması, memnun olmayan yolculara göre bir miktar daha yüksektir. Ancak bu farkın diğer değişkenlere kıyasla daha sınırlı olduğu görülmektedir.


Bu bulgular doğrultusunda müşteri memnuniyetini artırmaya yönelik iş önerileri geliştirilmiş ve bir sonraki bölümde sunulmuştur.

## 💼 Business Recommendations

Analiz sonucunda elde edilen bulgular doğrultusunda aşağıdaki iş önerileri geliştirilmiştir.

### 1. Economy Class Yolcu Deneyimi İyileştirilmelidir

Analizler, Economy sınıfında seyahat eden yolcuların memnuniyet oranının Business Class yolcularına kıyasla belirgin şekilde daha düşük olduğunu göstermektedir. Koltuk konforu, uçuş içi hizmetler ve eğlence sistemleri gibi alanlarda yapılacak iyileştirmeler müşteri memnuniyetini artırabilir.

---

### 2. Operasyonel Gecikmeler Azaltılmalıdır

Kalkış ve varış gecikmeleri arttıkça müşteri memnuniyetinin azaldığı gözlemlenmiştir. Operasyonel süreçlerin iyileştirilmesi ve gecikme durumlarında yolcuların zamanında bilgilendirilmesi müşteri deneyimini olumlu yönde etkileyebilir.

---

### 3. Sadakat Programları Güçlendirilmelidir

Sadık müşteriler genel olarak daha yüksek memnuniyet düzeyine sahip olsa da bu grupta hâlâ memnun olmayan önemli bir yolcu kitlesi bulunmaktadır. Mevcut sadakat programlarının kişiselleştirilmiş avantajlar ve ek hizmetlerle desteklenmesi müşteri bağlılığını artırabilir.

---

### 4. Farklı Yolcu Segmentlerine Özel Hizmetler Sunulmalıdır

İş amaçlı ve kişisel amaçlı seyahat eden yolcuların beklentileri farklılık göstermektedir. Yolcu segmentlerine göre özelleştirilen hizmet ve kampanyalar müşteri memnuniyetini artırmada etkili olabilir.

Bu öneriler, veri analizi sonucunda elde edilen bulgulara dayanmaktadır ve havayolu şirketlerinin müşteri deneyimini geliştirmeye yönelik stratejik kararlarına destek sağlamayı amaçlamaktadır.