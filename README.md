# MOXA1-MAK-NE-Kenar-Bantlama-Makineleri-4600-W-CNC-PUR
Yazılım mühendisliği güncel konular dersi kapsamında CRA — Siber Dayanıklılık Yasası altında seçilen makinanın incelenmesi

Kenar Bantlama Makinesi, endüstriyel bir kenar bantlama makinesini örnek alarak operasyonel teknoloji (OT) güvenliği, fonksiyonel emniyet ve siber risklerin fiziksel sonuçlarını inceleyen uygulamalı bir laboratuvar çalışmasıdır.
Çalışmada; sıcak yapıştırma çenesi, film kesme bıçağı, ışık perdesi, kapak kilidi, Safety PLC ve güvenli tork kapatma (STO) gibi makine bileşenleri ele alınır. Özellikle internete açık uzak bakım modülünün, makine kontrol sistemleri ve operatör güvenliği açısından oluşturabileceği riskler değerlendirilir.

Amaç yalnızca bir siber güvenlik açığını belirlemek değil; bu açığın makinenin çalışmasına ve makinenin başındaki insana nasıl etki edebileceğini anlamak ve güvenli tasarım kararlarını gerekçelendirmektir.
Temel yaklaşım: Siber güvenlik ve makine emniyeti birlikte düşünülmelidir. Bir dijital olay, fiziksel yaralanma veya tehlikeli makine davranışıyla sonuçlanabilir.

Çalışmanın Amaçları
- Makinedeki tehlikeleri ve emniyet fonksiyonlarını belirlemek.
- Normal kontrol sistemi ile emniyet kontrol zincirini ayırt etmek.
- IEC 62443 yaklaşımıyla varlıkları güvenlik bölgelerine ayırmak ve bölgeler arasındaki iletişimi kontrol etmek.
- Tehdit senaryoları oluşturmak, riskleri puanlamak ve önceliklendirmek.
- Güvenli uzaktan erişim için katmanlı önlemler tasarlamak.
- Yazılım bileşenleri, CVE kayıtları ve yamalar hakkında değerlendirme yapmak.
- Siber olaylara müdahale akışını ve kanıtların korunmasını ele almak.
- Yapay zekâ tabanlı kontrol sistemlerinde hata durumlarında güvenli davranışı tanımlamak.

Safety Architecture
-Makinedeki fiziksel tehlikeler, emniyet fonksiyonları, normal PLC ile Safety PLC arasındaki fark, güvenli durum (safe state) ve siber müdahalenin emniyet          zincirine etkisi incelenir.
IEC 62443 Mini Workshop
-Makine varlıkları güvenlik bölgelerine ayrılır. Bölgeler arası iletişim noktaları belirlenir ve uzak erişimin DMZ, güvenlik duvarı, VPN ve erişim kontrolleriyle nasıl sınırlandırılabileceği değerlendirilir.
Threat & Risk + Risk Matrix
-Olası saldırganlar, erişim yolları ve saldırı zincirleri üzerinden tehdit senaryoları oluşturulur. Olasılık, şiddet ve maruziyet puanları kullanılarak riskler değerlendirilir; insan güvenliğine yönelik fiziksel sonuçlar ayrıca görünür tutulur.
Secure Remote Access
-Mevcut uzak erişim yaklaşımı ile hedeflenen daha güvenli mimari karşılaştırılır. Jump server, VPN, çok faktörlü kimlik doğrulama (MFA), kişisel hesaplar, oturum kayıtları ve varsayılan kapalı erişim gibi ilkeler ele alınır.





