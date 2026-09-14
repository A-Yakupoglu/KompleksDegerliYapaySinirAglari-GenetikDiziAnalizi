# Kompleks Değerli Yapay Sinir Ağları ve Kompleks Sayılar ile Genetik Dizi Analizi
#### Çalışma Hakkında

Bu çalışma, kompleks değerli yapay sinir ağları (KDYSA) ve kompleks sayıların genetik dizi analizindeki potansiyelini araştırmaktadır. Bu amaçla DNA, kodon ve amino asit dizileri için kompleks sayıların faz ve genlik özelliklerinden yararlanılarak, dizi kodlama (sayısallaştırma) yöntemleri geliştirilmiş; elde edilen temsiller farklı mimarideki tam bağlantılı ve evrişimli kompleks değerli yapay sinir ağlarıyla sınıflandırılmış ve sonuçlar reel değerli yöntemlerle karşılaştırılmıştır.

Çalışmada, insana (Homo sapiens) ait kinaz ve G-proteinine bağlı reseptör (GPCR) protein ailelerine ait DNA, kodon ve amino asit dizileri kullanılmıştır. Diziler, önerilen kompleks değerli yöntemlerin yanı sıra karşılaştırma amacıyla literatürde kullanılan tamsayı tabanlı yöntemlerle de kodlanmış; kompleks ve reel değerli yapay sinir ağları, evrişimli sinir ağları ve geleneksel makine öğrenmesi yöntemleriyle sınıflandırılmıştır.

## Çalışma Aşamaları
### I. Veri Setinin Oluşturulması
Kinaz ve GPCR protein ailelerine ait ilişkili DNA ve amino asit formundaki genetik diziler UniProt ve NCBI GenBank veri tabanlarından FASTA formatında elde edilerek çalışma veri setleri oluşturulmuştur.

### II. Veri Ön İşleme ve Dizi Sayısallaştırma
Elde edilen DNA, kodon ve amino asit dizileri gerekli ön işleme adımlarından geçirilmiştir. Diziler, çalışmada önerilen kompleks tabanlı sayısallaştırma yöntemleri kullanılarak kompleks değerlere dönüştürülmüştür. Karşılaştırmalı analizler için aynı diziler ayrıca literatürde kullanılan tamsayı tabanlı temsil yöntemleriyle kodlanarak ayrı dosyalar hâlinde hazırlanmıştır.

### III. KDYSA ile Dizi Sınıflandırma
Kompleks değerli olarak temsil edilen DNA, kodon ve amino asit dizileri, Kompleks Değerli Yapay Sinir Ağları (KDYSA) kullanılarak sınıflandırılmıştır.

### IV. RDYSA ile Dizi Sınıflandırma
Tamsayı tabanlı yöntemlerle temsil edilen DNA, kodon ve amino asit dizileri, Reel Değerli Yapay Sinir Ağları (RDYSA) kullanılarak sınıflandırılmış ve KDYSA sonuçlarıyla karşılaştırılmıştır.

### V. 1B Kompleks Değerli Evrişimli Yapay Sinir Ağları ile Sınıflandırma
Kompleks değerli DNA, kodon ve amino asit temsilleri, 1 Boyutlu Kompleks Değerli Evrişimli Yapay Sinir Ağları (1B KDEYSA) kullanılarak sınıflandırılmıştır.

### VI. 1B Reel Değerli Evrişimli Yapay Sinir Ağları ile Sınıflandırma
Tamsayı tabanlı DNA, kodon ve amino asit temsilleri, 1 Boyutlu Reel Değerli Evrişimli Yapay Sinir Ağları (1B RDEYSA) kullanılarak sınıflandırılmış ve elde edilen sonuçlar 1B-KDEYSA sonuçlarıyla karşılaştırılmıştır.

### VII. 2B Protein–Amino Asit Temsillerinin Sınıflandırılması
Kompleks tabanlı iki boyutlu protein–amino asit temsilleri, kompleks ve reel değerli 2B evrişimli yapay sinir ağlarının yanı sıra geleneksel makine öğrenmesi yöntemleri kullanılarak sınıflandırılmış ve yöntemlerin performansları karşılaştırılmıştır

### 8. İstatistiksel Karşılaştırmalar
Kompleks ve reel değerli ağlarla gerçekleştirilen dizi sınıflandırma çalışmalarından elde edilen 10 katlı çapraz doğrulama accuracy sonuçları, uygun istatistiksel yöntemler kullanılarak karşılaştırılmış ve modeller arasındaki performans farklılıkları değerlendirilmiştir.

## Kodlar ve Çalışma Ortamı
Bu repository, çalışmada gerçekleştirilen veri ön işleme, dizi sayısallaştırma, sınıflandırma, performans değerlendirme ve istatistiksel karşılaştırmalara ilişkin araştırma kodlarını içermektedir.
Kodlar ağırlıklı olarak Python programlama dili kullanılarak geliştirilmiş ve Jupyter Notebook ortamında çalıştırılmıştır. Çalışmaların yürütülmesinde Anaconda tabanlı Python ortamlarından yararlanılmıştır.

## Veri Kaynakları
Çalışmada kullanılan biyolojik diziler aşağıdaki açık biyolojik veri kaynaklarından elde edilmiştir:
- UniProt: (https://www.uniprot.org/)
- NCBI: (https://www.ncbi.nlm.nih.gov/)

(Veri tabanlarından elde edilen özgün biyolojik verilerin kullanımı ilgili veri sağlayıcılarının kullanım koşullarına tabidir.)

## Atıf
Bu repository'de sunulan kodlardan, çalışmanın kuramsal çerçevesinden veya geliştirilen yöntemlerden akademik çalışmalarda yararlanılması durumunda, bilimsel etik ve akademik kaynak gösterme ilkeleri doğrultusunda ilgili çalışmaya uygun şekilde atıf yapılması beklenmektedir.

(Akademik atıf bilgilerinin standart biçimde sunulabilmesi amacıyla repository'ye ayrıca bir CITATION.cff dosyası eklenecektir.)

## Lisans
Bu repository'de yayımlanan kaynak kodları MIT License kapsamında sunulmaktadır. Ayrıntılı lisans koşulları için repository içerisindeki LICENSE dosyasına bakınız.

### Not:
Bu repository, akademik araştırma kapsamında geliştirilen yöntem ve uygulama kodlarının belgelenmesi; çalışmanın şeffaflık, bilimsel etik ve araştırma dürüstlüğü ilkeleri doğrultusunda incelenebilirliğinin ve tekrarlanabilirliğinin desteklenmesi amacıyla hazırlanmıştır.

Çalışmada kullanılan uygulama kodları, tez çalışması kapsamında Türkçe açıklamalarla organize edilerek yeni bir repository altında paylaşılmıştır.
