---
title: Radtel DMR Telsizlerde Tuş Takımı ile Manuel Kurulum Rehberi
date: 2026-10-03 13:00:00 +0300
categories: [Telsiz Kurulum Rehberleri, Radtel]
tags: [dmr, radtel, kurulum, fpp, manuel]
---

Bu belge, Radtel RT-4 ve benzeri DMR telsizlerde, bilgisayara ihtiyaç duymadan cihazın kendi ön paneli ve tuş takımı (FPP - Front Panel Programming) kullanılarak dijital kanal (Talkgroup) ekleme ve kaydetme işlemlerini adım adım anlatmaktadır.

## Adım 1: DMR ID'nizi Cihaza Tanıtın
* Telsiz menüsüne girin ve Dijital Set bölümünü seçin.
* Personel ID kısmına girerek size ait olan 7 haneli DMR numaranızı tuşlayın.
* **Önemli:** Numarayı yazarken başına mutlaka "0" koymayı unutmayın.

## Adım 2: Yeni Bir Talkgroup (Kişi/Grup) Ekleyin
* Dijital Set ayarlarından Contact Set menüsüne ve ardından Contact List seçeneğine girin.
* Buraya yeni bir isim (Örn: "Multi" veya "TR Genel") yazın. (Hatalı harf/rakamları silmek için imleci en sona götürüp # (diyez) tuşunu kullanın).
* Edit ID bölümüne girerek grubun numarasını (Örn: 2860) yazıp kaydedin (Save).
* İşlem bitince ekrandan "Yes" (Evet) seçerek onaylayın.

## Adım 3: Grubu Talkgroup Listesine Dahil Edin
* Sadece kişi eklemek yetmez, bunu bir dinleme listesine atamanız gerekir. Menüden Talk Group List kısmına girin.
* Mevcut listenizi (Örn: İstanbul) seçip Edit Member (Üye Düzenle) deyin.
* Eklediğiniz grubu (Multi) bulup ilgili yön tuşuyla koyu renge çevirerek seçin ve kaydedin.

## Adım 4: VFO Modunda Frekans Girin
* # (diyez) tuşuna basarak cihazı VFO (Zoom/Frekans) moduna geçirin.
* Ekran üzerinden dinleme yapmak istediğiniz röle veya hotspot frekansını (Örn: 432.100) tuşlayın.

## Adım 5: Kanal Ayarlarını (Channel Set) Yapılandırın
Menüden Channel Set (Kanal Ayarı) kısmına girin ve kanal tipini DMR olarak seçin. Sırasıyla şu değerleri girin:
* **Offset:** Yapmayacaksanız "0" seçin. (Röle shifti varsa ona göre değer girilir).
* **TX Freq:** Gönderme frekansını (Örn: 432.100) girin.
* **Dual Slot:** "Off" yapın.
* **DMR Slot (Zaman Dilimi):** Rölenize/hotspotunuza göre seçin (Örn: Slot 2).
* **Color Code (Renk Kodu):** Rölenin renk kodunu girin (Genellikle 1).
* **Contact:** 2. Adımda oluşturduğunuz grubu (Multi) seçin.
* **TG List:** 3. Adımda güncellediğiniz dinleme listenizi (İstanbul) seçin.

## Adım 6: Promiscuous Modu Açın
* Aynı menüde aşağı inerek Promiscuous Mode (Karışık Dinleme Modu) ayarını mutlaka ON (Açık) konumuna getirin.
* **Not:** Bu ayarı açmazsanız, kanal üzerinden gelen sesleri duyamazsınız.

## Adım 7: Ayarlanan Kanalı Cihaza Kaydedin ve Test Edin
* Yaptığınız ayarları boş bir kanala atamak için menüden Basic Settings'e (Temel Ayarlar) girin.
* Save Channel (Kanalı Kaydet) seçeneğini bularak onaylayın.
* Karşınıza çıkan listeden "Empty" (Boş) yazan bir dijital kanal sırası (Örn: 20. kanal) bulup "Save" diyerek kaydedin.
* **Test:** Cihazı tekrar Channel (Kanal) moduna alın, 20. kanala gidin ve PTT (Mandala) tuşuna basarak doğru gruba bağlanıp bağlanmadığını ekrandan teyit edin.
