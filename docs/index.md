<div align="center" id="top"> 
</div>

<h1 align="center">DOĞAL DİL İŞLEME TEKNOLOJİLERİ VE GÜNLÜK HAYATTAKİ UYGULAMALARI
</h1>

### Araştırmayı Yapan ve Hazırlayan:
 - **Adı Soyadı**: Mehmet Kekeç
 - **Öğrenci No**: 1030510209
 - **Üniversite**: Erciyes Üniversitesi
 - **Bölüm**: Bilgisayar Mühendisliği
 
&#xa0;

 > **Ödev Github Adresi**: [mehmetkekec58](https://github.com/mehmetkekec58/dogal-dil-isleme-teknolojileri-ve-gunluk-hayattaki-uygulamalari)

&#xa0;

## 1 &#xa0; Doğal Dil İşleme (NPL) Nedir?
Doğal dil işleme (NLP), bilgisayarlara insan dilini yorumlama, işleme ve anlama yeteneği veren bir makine öğrenimi teknolojisidir. Doğal Dil İşleme, verileri dil metni veya sesle sorgulama yeteneğine sahiptir. Bu aynı zamanda *"dil içinde"* olarak adlandırılır. Siri, Cortana, Alexa veya Google asistan gibi sanal asistanların temel teknolojisidir. Bu sanal asistanlara sorular sorduğumuzda, NLP sadece kullanıcının talebini anlamalarına değil, aynı zamanda doğal dilde yanıt vermelerine olanak tanır. NLP tarafından desteklenen diğer araç örnekleri arasında web araması, istenmeyen e-posta filtreleme, metin veya konuşmanın otomatik çevirisi, belge özetleme, duygu analizi ve dil/istem kontrolü bulunmaktadır.

### 1.1 &#xa0; NPL Neden Önemlidir?
Doğal dil işleme, metin ve konuşma verilerini verimli bir şekilde tam olarak analiz etme açısından çok önemlidir. Lehçelerdeki farklılıklar, argo ifadeler ve günlük konuşmalar gibi durumlarda dil bilgisi düzensizliklerini inceleyebilir.

### 1.1.1 &#xa0; NPL'nin Genel Kullanım Alanları:
- **Dil Çeviri (Machine Translation)**:
Bir dilden başka bir dile NLP teknikleri kullanılarak çeviri yapılması işlemidir. Örnek olarak Google Translate, Yandex Çeviri gösterilebilir.

- **Ses Tanıma (Speech Recognition)**:
Yapay sinir ağları veya makine öğrenmesi metotlarından faydalanarak NLP ile ses sinyallerinin anlamlı hale getirilmesi işlemidir. Apple Siri, Google Asistan gibi uygulamalar örnek olarak verilebilir.

- **Yazım Denetimi (Spell Checking)**:
Herhangi bir dilde yazılan bir cümlenin NLP ile dil bilgisi ve kelime bilgisi denetiminin yapılması işlemidir.

- **Metin Özetleme (Text Summarization)**:
Büyük metin verilerinden özet bilgiler çıkarmak için kullanılır.

- **Bilgilerin Çıkarılması (Information Extraction)**:
Genellikle bir metin üzerinden, belirli kriterdeki bilgileri çıkarmak için kullanılır. Amaç büyük veriyi otomatik olarak işleyip, insan müdahalesini minimum seviyeye indirmektir.

- **Adlandırılmış Varlık Tanıma (Named Entity Recognation (NER))**:
Bilgi çıkarımının bir alt dalıdır. Makine çevirilerinden duygu analizine kadar birçok problemde kullanılmaktadır. Kişi, yer, zaman, tarih ve sayı tanımlamalarının yapılmasında kullanılabilir.

- **Soru Cevaplama (Question Answering)**:
Makinenin sorulan sorulardan anlamlar çıkarıp uygun cevaplar verebilmesidir.

- **Metin Sınıflandırma ve Kategorize Etme (Text Classification and Categorization)**:
Bir metin verisinde geçen cümlelerin veya kelimelerin önceden belirlenen etiketlere atanması işlemidir. Önceden etiketlenmiş, olumlu ve olumsuz kategorilerinden oluşturulan veri seti kullanılarak, Twitter’da atılan bir Tweet’in, hangi kategoriye ait olduğunun belirlenmesi işlemi örnek olarak gösterilebilir.

### 1.1.2 &#xa0; Şirketlerin Kullanım Alanları:
- Müşteri geri bildirimlerini veya çağrı merkezi kayıtlarını analiz etmek
- Otomatik müşteri hizmeti sağlamak için chatbot kullanmak
- Kim, ne, ne zaman ve nerede gibi soruları yanıtlamak
- Metinleri sınıflandırıp ayıklamak
- Büyük belgeleri işlemek, analiz etmek ve arşivlemek

### 1.2 &#xa0; Ngram Nedir?
N-gram, belirli bir metin veya konuşma örneğindeki bitişik N öğe dizisidir. N-gramlar genellikle dil kalıplarını analiz etmek için örneğin yaygın ifadelerini veya eşdizimleri belirlemek için kullanılır.

N-gramlar, unigramlardan (N=1) bigramlara (N=2), trigramlara (N=3) kadar farklı uzunluklarda olabilir. Örneğin, bir bigram “doğal dil” gibi iki sözcükten oluşan bir diziyken, bir trigram “doğal dil işleme” gibi üç sözcükten oluşan bir dizidir.

N-gramlar genellikle bir metindeki belirli bir kelime veya karakter dizisinin olasılığını tahmin etme süreci olan dil modellemede kullanılır. N-gramlar, makine çevirisi, konuşma tanıma ve metin sınıflandırma gibi diğer NLP görevlerinde de kullanılabilir.

### 1.3 &#xa0; Doğal dil işleme yaklaşımları nelerdir?
- **Denetimli NLP**: 
Denetimli NLP yöntemleri, yazılımı bir dizi etiketli veya bilinen girdi ve çıktı ile eğitir. Program, ilk önce büyük miktarda bilinen veriyi işler ve bilinmeyen herhangi bir girdiden doğru çıktının nasıl üretileceğini öğrenir. Örneğin şirketler, belgeleri belirli etiketlere göre kategorize etmek için NLP araçlarını eğitir. 

 - **Denetimsiz NLP**: Denetimsiz NLP, etiketlenmemiş bir girdi beslendiğinde oluşan modeli tahmin etmek için istatistiksel bir dil modeli kullanır. Örneğin metin mesajlaşmadaki otomatik tamamlama özelliği, kullanıcının yanıtını izleyerek cümle için anlamlı olan ilgili kelimeleri önerir.  

- **Doğal dil anlama**: Doğal dil anlama (NLU), cümlelerin ardındaki anlamı analiz etmeye odaklanan bir NLP alt kümesidir. NLU, yazılımın farklı cümlelerde benzer anlamlar bulmasına veya farklı anlamlara sahip kelimeleri işlemesine olanak tanır. 

- **Doğal dil üretimi**: Doğal dil üretimi (NLG), insanların belirli anahtar kelimelere veya konulara dayalı olarak yaptığı gibi konuşma metinleri üretmeye odaklanır. Örneğin NLG özelliklerine sahip akıllı bir sohbet robotu, müşterilerle müşteri destek personelininkine benzer şekillerde sohbet edebilir. 

### 1.4 &#xa0; NLP Kütüphaneleri
NLP alanında çalışma yapmak için farklı kütüphaneler bulunmaktadır. Bu kütüphanelerin içerisinde ise önceden hazırlanan modüller ile birçok veri işleme yöntemi uygulanabilir. Bazı açık kaynak kodlu NLP kütüphaneleri ise şunlardır:

- Language Toolkit (NLTK)
- Apache OpenNLP
- Standford NLP

&#xa0;

## 2 &#xa0; Doğal Dil İşlemenin Günlük Hayattaki Uygulamaları

### 2.1 &#xa0; Sesli Asistanlar (Alexa, Siri, Google Asistan) Ve Konuşma Tanıma Teknolojileri

### 2.1.1 &#xa0; Konuşmayı Metne Dönüştürme Nedir?
Konuşma tanıma olarak da bilinen konuşmadan metne, ses akışlarının gerçek zamanlı olarak metne dönüştürülmesini sağlar. Bu aynı zamanda bilgisayarda konuşma tanıma olarak da bilinir. Basitçe söylemek gerekirse, konuşmadan metne, sözlü ses kayıtlarını dinler ve kelimesi kelimesine yazılı bir senaryo oluşturur. Kullanıcılar net bir şekilde konuştuklarında, metin doğruluk oranları yükselir. Yazıya dökülen metin uygulamalar, araçlar ve cihazlar tarafından komut girişi olarak kullanılabilir. Konuşmayı metne dönüştürmenin iki ana türü vardır: konuşmacıya bağlı ve kullanılan konuşmacıdan bağımsız.

### 2.1.2 &#xa0; Siri, Alexa ve Google Assistan Gibi Sesli Asistanların Temel Yetenekleri Nelerdir?
sesli asistanlar, temel görevleri yerine getirme yeteneğine sahiptir. Bunlar arasında hava durumu raporları alma, güncel haberleri okuma, alarm kurma ve takvim etkinlikleri düzenleme gibi günlük işler bulunmakta. Ayrıca, akıllı ev cihazlarına entegre edilerek ışıkları açma, termostatı ayarlama gibi ev otomasyon görevlerini de gerçekleştirebilirler. Bu asistanlar, internetten bilgi çekme ve kullanıcıların sorularını yanıtlama konusunda da oldukça yeteneklidirler.

### 2.1.3 &#xa0; Duygusal İfadeleri Tanıma
Duygusal ifadelerin tanınması, sesli asistanların kullanıcı deneyimini daha da zenginleştirmek için kritik bir unsurdur. Kullanıcıların duygusal durumlarını anlamak, daha kişiselleştirilmiş yanıtlar sunmalarına yardımcı olmakta. Bu noktada, NLP teknolojisinin duygusal analiz için kullanılması büyük önem taşır. Sesli asistanlarda duygusal ifadeleri tanıma yeteneklerini geliştirmek için sürekli olarak çalışmaktadır.

### 2.1.4 &#xa0; Duygusal Analiz Uygulamaları
Sesli asistanlar, duygusal analiz uygulamalarıyla kullanıcıların duygusal durumlarını anlamada büyük bir potansiyele sahiptir. Örneğin, bir kullanıcının ses tonundan veya kelime seçimlerinden mutlu, üzgün veya endişeli olduğunu tespit edebilirler. Bu bilgi, sağlık alanında duygusal destek sağlama veya pazarlama kampanyalarını kişiselleştirme gibi bir dizi uygulamada kullanılmaktadır.

&#xa0;

## 3 &#xa0; Doğal Dil İşlemenin Endüstri Uygulamaları

### 3.1 &#xa0; Sağlık Hizmetlerinde Doğal Dil İşleme

### 3.1.1 &#xa0; NLP'nin Sağlık Alanında Kullanıldığı Yerler

- Klinik notlar veya akademik dergi makaleleri de dahil olmak üzere uzun anlatı metni bloklarını, materyalde bulunan anahtar kavramları veya cümleleri tanımlayarak özetlemek

- Klinik veri bütünlüğünü iyileştirmek için yapılandırılmamış metinde bulunan veri öğelerini elektronik sağlık kaydındaki yapılandırılmış alanlarla eşlemek

- Raporlama ve eğitim amaçlı olarak makine tarafından okunabilir formatlardan diğer yöndeki verileri doğal dile dönüştürmek

- Birden çok veri kaynağının sentezlenmesini gerektiren benzersiz serbest metin sorgularını yanıtlamak

- PDF belgeleri veya bakım özetlerinin ve görüntüleme raporlarının taranması gibi görüntüleri daha sonra ayrıştırılıp analiz edilebilen metin dosyalarına dönüştürmek için optik karakter tanıma özelliğini kullanmak

- Kullanıcıların klinik notları veya daha sonra metne dönüştürülebilecek diğer bilgileri dikte etmelerine izin vermek için konuşma tanıma yapmak

&#xa0;

# 4 &#xa0; Gelişen Trendler ve Gelecekteki Potansiyel
### 4.1 &#xa0; Doğal Dil İşleme Alanındaki Gelecekteki Trendler

**Daha Gelişmiş Dil Modelleri**: GPT-3 gibi büyük dil modelleri, dil anlama ve üretme konusunda önemli ilerlemeler kaydetmiştir. Gelecekte, daha büyük ve daha karmaşık dil modellerinin geliştirilmesi bekleniyor. Bu modeller, daha fazla dil ve kültürü anlama kapasitesine sahip olabilir.

**Özerk Dil Anlama ve Çıkarım**: Gelecekteki NLP sistemleri, metinleri daha derinlemesine anlama yeteneğine sahip olabilir. Daha karmaşık dil yapılarını kavrama, çıkarım yapma ve metinler arasında bağlantı kurma yeteneği geliştirilebilir.

**Duygu Analizi ve Sosyal İnteraksiyon**: NLP, duygu analizi ve sosyal dil anlama konularında daha yetenekli hale gelebilir. Bu, sosyal medya analitiği, müşteri geri bildirimleri, ve insan-makine etkileşimlerinde daha duyarlı ve anlayışlı sistemlerin geliştirilmesine yol açabilir.

**Çok Dillilik ve Kültürel Anlayış**: Gelecekteki NLP sistemleri, daha fazla dilde etkili olabilecek ve çeşitli kültürlere uyum sağlayabilecek şekilde geliştirilebilir. Bu, küresel iletişim ve çeviri alanlarında büyük bir etkiye sahip olabilir.

**Eğitim ve Sağlık Sektörlerinde Kullanım**: NLP, eğitim ve sağlık sektörlerinde daha fazla kullanılabilir hale gelebilir. Öğrenci performansını değerlendirme, öğrencilere özel öğrenme materyalleri oluşturma, ve sağlık kayıtlarını analiz etme gibi alanlarda NLP'nin kullanımı artabilir.

**Özelleştirilmiş ve Kontrol Edilebilir Modeller**: Gelecekteki trendler arasında, kullanıcıların NLP modellerini daha iyi anlamalarına ve yönetmelerine izin veren araçlar ve teknolojiler olabilir. Bu, endüstrilerin ve bireylerin ihtiyaçlarına daha iyi uyan özelleştirilmiş NLP çözümlerinin geliştirilmesini destekleyebilir.

**Bias Azaltma ve Etik Meseleleri**: NLP sistemlerindeki ön yargıları azaltma çabaları artabilir. Bu, daha adil ve etik bir dil işleme ortamı oluşturmak amacıyla gerçekleştirilebilir.

**Çok Modlu Öğrenme**: NLP'nin diğer modalitelerle (görüntü, ses, video) entegre edilerek çok modlu öğrenme konsepti daha fazla önem kazanabilir. Bu, dilin yanı sıra diğer veri türlerini de içeren daha zengin ve kapsamlı anlayışlara olanak tanır.

&#xa0;

# 5 &#xa0; Zorluklar Ve Etik Sorunlar
### 5.1 &#xa0; NPL'nin Karşılaştığı Teknik Sorunlar
Doğal dil işleme konusunda birçok zorluk karşımıza çıkmakta olup bu zorlukların büyük bir kısmı dilin sürekli değişen ve bolca tutarsız ifade içeren bir olgu olmasından kaynaklanmaktadır. Bu zorluklar arasında özellikle göze çarpanlar şu şekildedir:

- **Kesinlik/Doğruluk**: Bilgisayarlar ile olan iletişim net, muğlaklıklardan arındırılmış ve yapılandırılmış bir kodlama dili ile veya net bir şekilde telaffuz edilen ses komutları aracılığıyla gerçekleşmektedir. Bununla beraber insan dili her zaman kesin değildir; genellikle belirsiz ifadeler içerir. Dilbilimsel yapı günlük konuşma dili, bölgesel ağızlar ve toplumsal bağlam gibi birçok karmaşık değişkene bağlı olarak değişmektedir.

- **Ses Tonu ve Vurgu**: Doğal dil işleme sistemleri henüz mükemmel düzeyde değildir. Anlambilimsel (semantik) analizler hala zorluk çıkarabilmekte; dilin içerdiği soyut kullanımlar programlar tarafından anlaşılamayabilmektedir. Bu durum özellikle hiciv gibi söz sanatlarında göze çarpmaktadır. Hiciv ve benzeri kullanımlar, kullanılan sözcüklerin anlamlarının anlaşılmasının yanında konuşma içerisinde bağlamın da anlaşılmasını gerektirmektedir. Bunun yanında bazı tümcelerin anlamı, vurgulanan sözcük veya heceye göre değişebilmektedir. Doğal dil işleme algoritmaları, bu küçük (ancak önemli) ton değişikliklerini kaçırabilmekte; konuşma tonu ve vurgusu aksandan aksana değiştiği için yetersiz kalabilmektedir.

- **Dildeki Değişimler**: Doğal dil işleme alanının karşı karşıya olduğu bir başka zorluk da dilin (ve dil kullanımının) sürekli bir değişim içinde olmasıdır. Dilin kuralları yok değildir; ancak bu kuralların değişmesinin önünde bir engel bulunmamaktadır. Dolayısıyla bu kurallar gözetilerek geliştirilen algoritmalar, kurallar değiştikçe geçerliliklerini ve işlevselliklerini yitirebilmektedir.

&#xa0;

### 5.2 &#xa0; Veri Gizliliği Ve Etik Konular

- **Hassas Bilgilerin İfşası**: NLP sistemleri, kullanıcıların metinlerini analiz ederek dil anlama ve çıkarım yapar. Bu, kullanıcıların özel ve hassas bilgilerini içeren metinlerin işlenmesi anlamına gelir. Eğer bu veriler güvenli bir şekilde işlenmezse, hassas bilgilerin ifşa olma riski ortaya çıkabilir.

- **Topluluk Verisi ve Grup Tanıma**: NLP modelleri genellikle büyük miktarda veri kullanarak eğitilir. Bu veri setleri, topluluklar, demografik gruplar veya belirli konulardaki insanlar hakkında bilgiler içerebilir. Bu durumda, kullanıcıların aidiyetleri ve kimlikleri üzerinde gizlilik endişeleri olabilir.

- **Metin Madenciliği ve İzleme**: NLP uygulamaları, metin madenciliği yaparak büyük veri setlerinden anlamlı bilgiler çıkarabilir. Bu durum, bireylerin online etkileşimlerini izleme ve profil oluşturma anlamına gelebilir. Bu tür izleme, gizlilik endişelerine neden olabilir.

- **Biyometrik Veri Riski**: Kullanıcıların yazılı metinleri, benzersiz dil kullanımları nedeniyle biyometrik bir iz bırakabilir. Bu, NLP uygulamalarının kullanıcılarına dair benzersiz bir profil oluşturmasına ve bu bilgilerin kötü niyetli kullanıma açık hale gelmesine neden olabilir.

- **Kötü Niyetli Saldırılar**: NLP modelleri, kötü niyetli kullanıcılar tarafından manipüle edilebilir. Örneğin, saldırganlar, sistemleri yanıltmak veya zarar vermek amacıyla yanıltıcı metinler girebilir. Bu tür saldırılar, doğru çıkarımların yapılamamasına veya yanlış sonuçlara neden olabilir.

- **Veri Paylaşımı ve İntegrasyonu**: NLP uygulamaları genellikle farklı veri kaynaklarıyla entegre edilir. Bu, kullanıcı verilerinin farklı platformlar arasında paylaşılmasına ve entegre edilmesine yol açabilir. Veri paylaşımında ve entegrasyonunda dikkatsizlik, gizlilik ihlallerine neden olabilir.

&#xa0;

## Kaynakça
1. [https://www.oracle.com/artificial-intelligence/what-is-natural-language-processing](https://www.oracle.com/artificial-intelligence/what-is-natural-language-processing/)
2. [https://aws.amazon.com/tr/what-is/nlp](https://aws.amazon.com/tr/what-is/nlp/)
3. [https://www.hosting.com.tr/blog/nlp](https://www.hosting.com.tr/blog/nlp/)
4. [https://www.saglikteknoloji.com/saglik-hizmetlerinde-dogal-dil-isleme](https://www.saglikteknoloji.com/saglik-hizmetlerinde-dogal-dil-isleme/)
5. [https://tr.shaip.com/blog/how-voice-assistant-understand-what-you-are-saying](https://tr.shaip.com/blog/how-voice-assistant-understand-what-you-are-saying/)
6. [https://evrimagaci.org/dogal-dil-isleme-nlp-hakkinda-bilmeniz-gereken-her-sey-16032](https://evrimagaci.org/dogal-dil-isleme-nlp-hakkinda-bilmeniz-gereken-her-sey-16032)

&#xa0;

<a href="#top">Başa Dönmek İçin Tıkla</a>
