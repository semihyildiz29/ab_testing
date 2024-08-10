AB Testi ile Bidding Yöntemlerinin Dönüşümünün Karşılaştırılması

Bu proje, Facebook'un yeni teklif verme türü olan "average bidding" ile mevcut "maximum bidding" teklif verme türünü karşılaştırmak amacıyla yapılmış bir A/B testinin sonuçlarını analiz eder. bombabomba.com, average bidding'in maximum bidding'den daha fazla dönüşüm sağladığını belirlemek için bu testi gerçekleştirmiştir. Nihai başarı ölçütü olarak "Purchase" metriğine odaklanılmıştır.

İş Problemi

Facebook, mevcut "maximum bidding" teklif verme türüne alternatif olarak yeni bir teklif türü olan "average bidding"i tanıttı. bombabomba.com, bu yeni özelliği test etmeye karar verdi ve average bidding'in maximum bidding'den daha fazla dönüşüm getirip getirmediğini anlamak için bir A/B testi yapma kararı aldı. Test 1 aydır devam etmektedir ve bombabomba.com şimdi sizden bu A/B testinin sonuçlarını analiz etmenizi bekliyor. Test sonuçlarını değerlendirirken nihai başarı ölçütü olarak "Purchase" metriğine odaklanmalısınız. Bu, testin en önemli göstergesidir ve istatistiksel analizlerde temel odak noktanız olmalıdır.

Veri Seti Hikayesi

Veri seti, bir firmanın web sitesinde kullanıcıların gördükleri ve tıkladıkları reklamlara ilişkin bilgileri içermektedir. Ayrıca, bu reklamlar sonucu elde edilen kazanç bilgileri de yer almaktadır. Veri seti iki ana gruba ayrılmıştır: Kontrol grubu ve Test grubu. Kontrol grubunda "Maximum Bidding", test grubunda ise "Average Bidding" uygulanmıştır. Bu veri setini inceleyerek her iki teklif türünün dönüşüm oranlarını karşılaştıracağız.

Veri Seti Bilgileri

- **Veri Seti:** `ab_testing.xlsx`
- **Sayfalar:** İki ayrı sayfa bulunur: Kontrol Grubu ve Test Grubu.
- **Kontrol Grubu:** Maximum Bidding uygulanan kullanıcılar.
- **Test Grubu:** Average Bidding uygulanan kullanıcılar.

Değişkenler

- **impression:** Reklam görüntüleme sayısı. Kullanıcıların reklama maruz kaldığı toplam sayıyı belirtir.
- **Click:** Görüntülenen reklama tıklama sayısı. Kullanıcıların reklama tıkladığı toplam sayıyı belirtir.
- **Purchase:** Tıklanan reklamlar sonrası satın alınan ürün sayısı. Reklam tıklamaları sonrası gerçekleştirilen satın alımların toplam sayısını gösterir.
- **Earning:** Satın alınan ürünler sonrası elde edilen kazanç. Satışlardan elde edilen toplam kazancı ifade eder.

Analiz Adımları

1. **Veri Setinin Yüklenmesi ve İncelenmesi**
   - `ab_testing.xlsx` dosyasının yüklenmesi.
   - Kontrol ve test gruplarının ayrı sayfalarından verilerin alınması.
   - Verilerin genel yapısının incelenmesi ve eksik değerlerin kontrol edilmesi.

2. **Temel İstatistiklerin Hesaplanması**
   - Her iki grubun `impression`, `click`, `purchase`, ve `earning` bilgileri için temel istatistiklerin hesaplanması.
   - Ortalama, medyan, standart sapma gibi istatistiklerin hesaplanması.

3. **Dönüşüm Oranı Hesaplamaları**
   - Dönüşüm oranlarının hesaplanması: `Conversion Rate = Purchase / Click`.
   - Her iki grup için dönüşüm oranlarının karşılaştırılması.

4. **İstatistiksel Testler**
   - Purchase metriği için uygun istatistiksel testlerin uygulanması.
   - T-Testi veya Mann-Whitney U testi gibi yöntemlerle iki grubun dönüşüm oranlarının karşılaştırılması.
   - Sonuçların istatistiksel anlamlılığının test edilmesi.

5. **Sonuçların Yorumlanması**
   - Average bidding ve maximum bidding'in dönüşüm oranlarının karşılaştırılması.
   - İstatistiksel test sonuçlarının değerlendirilmesi ve sonuçların yorumlanması.
   - Test sonuçlarına dayalı olarak önerilerin sunulması.

6. **Raporlama ve Öneriler**
   - Test sonuçlarının özetlenmesi ve görselleştirilmesi.
   - İlgili grafiklerin ve tabloların oluşturulması.
   - Test sonuçlarına dayalı olarak stratejik önerilerin sunulması.

Katkıda Bulunma

Bu proje üzerinde geliştirme yapmak istiyorsanız, lütfen projeyi fork'layın ve pull request gönderin. Her türlü katkı kabul edilir ve projeye katkıda bulunanlara teşekkür edilir.

Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Lisans hakkında daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.
