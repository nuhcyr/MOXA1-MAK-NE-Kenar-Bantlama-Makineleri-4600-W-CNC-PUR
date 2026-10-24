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

### LAB 1 — Safety Architecture
**Çıktı:** Safety Function Map

- Fiziksel tehlikelerin belirlenmesi
- Emniyet fonksiyonlarının tanımlanması
- Normal PLC ve Safety PLC farkları
- Güvenli durum (Safe State)
- Siber müdahalenin emniyet zincirine etkisi

### LAB 2 — IEC 62443 Mini Workshop
**Çıktı:** Zone / Conduit Diagram

- Makine varlıklarının güvenlik bölgelerine ayrılması
- Bölgeler arası iletişim kanallarının belirlenmesi
- DMZ ve güvenlik duvarı yaklaşımı
- VPN ve erişim kontrolleri

### LAB 3 — Threat & Risk + Risk Matrix
**Çıktı:** Risk Register

- Olası saldırganların ve erişim yollarının belirlenmesi
- Tehdit senaryolarının oluşturulması
- Olasılık, şiddet ve maruziyet puanlaması
- Risklerin önceliklendirilmesi
- Fiziksel emniyet sonuçlarının değerlendirilmesi

### LAB 4 — Secure Remote Access
**Çıktı:** Secure Architecture

- Jump Server ile kontrollü erişim
- VPN ile bağlantı güvenliği
- Çok faktörlü kimlik doğrulama (MFA)
- Kişisel hesaplar ve oturum kayıtları
- Varsayılan kapalı erişim yaklaşımı
- Emniyet fonksiyonlarının bağımsızlığı





