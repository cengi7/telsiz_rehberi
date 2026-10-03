---
title: Radtel DMR Telsizlerde Tuş Takımı ile Manuel Kurulum Rehberi
date: 2026-10-03 14:00:00 +0300
categories: [Telsiz Kurulum Rehberleri, Radtel]
tags: [dmr, radtel, kurulum, fpp, manuel]
---

Bu belge, Radtel RT-4 ve benzeri DMR telsizlerde, bilgisayara ihtiyaç duymadan cihazın kendi ön paneli ve tuş takımı (FPP - Front Panel Programming) kullanılarak dijital kanal (Talkgroup) ekleme ve kaydetme işlemlerini adım adım anlatmaktadır[cite: 23].

## Adım 1: DMR ID'nizi Cihaza Tanıtın
* Telsiz menüsüne girin ve Dijital Set bölümünü seçin[cite: 23].
* Personel ID kısmına girerek size ait olan 7 haneli DMR numaranızı tuşlayın[cite: 23].
* **Önemli:** Numarayı yazarken başına mutlaka "0" koymayı unutmayın[cite: 23].

## Adım 2: Yeni Bir Talkgroup (Kişi/Grup) Ekleyin
* Dijital Set ayarlarından Contact Set menüsüne ve ardından Contact List seçeneğine girin[cite: 23].
* Buraya yeni bir isim (Örn: "Multi" veya "TR Genel") yazın[cite: 23]. (Hatalı harf/rakamları silmek için imleci en sona götürüp # (diyez) tuşunu kullanın[cite: 23]).
* Edit ID bölümüne girerek grubun numarasını (Örn: 2860) yazıp kaydedin (Save)[cite: 23].
* İşlem bitince ekrandan "Yes" (Evet) seçerek onaylayın[cite: 23].

## Adım 3: Grubu Talkgroup Listesine Dahil Edin
* Sadece kişi eklemek yetmez, bunu bir dinleme listesine atamanız gerekir[cite: 23]. Menüden Talk Group List kısmına girin[cite: 23].
* Mevcut listenizi (Örn: İstanbul) seçip Edit Member (Üye Düzenle) deyin[cite: 23].
* Eklediğiniz grubu (Multi) bulup ilgili yön tuşuyla koyu renge çevirerek seçin ve kaydedin[cite: 23].

## Adım 4: VFO Modunda Frekans Girin
* # (diyez) tuşuna basarak cihazı VFO (Zoom/Frekans) moduna geçirin[cite: 24].
* Ekran üzerinden dinleme yapmak istediğiniz röle veya hotspot frekansını (Örn: 432.100) tuşlayın[cite: 24].

## Adım 5: Kanal Ayarlarını (Channel Set) Yapılandırın
Menüden Channel Set (Kanal Ayarı) kısmına girin ve kanal tipini DMR olarak seçin[cite: 24]. Sırasıyla şu değerleri girin[cite: 24]:
* **Offset:** Yapmayacaksanız "0" seçin[cite: 24]. (Röle shifti varsa ona göre değer girilir[cite: 24]).
* **TX Freq:** Gönderme frekansını (Örn: 432.100) girin[cite: 24].
* **Dual Slot:** "Off" yapın[cite: 24].
* **DMR Slot (Zaman Dilimi):** Rölenize/hotspotunuza göre seçin (Örn: Slot 2)[cite: 24].
* **Color Code (Renk Kodu):** Rölenin renk kodunu girin (Genellikle 1)[cite: 24].
* **Contact:** 2. Adımda oluşturduğunuz grubu (Multi) seçin[cite: 24].
* **TG List:** 3. Adımda güncellediğiniz dinleme listenizi (İstanbul) seçin[cite: 24].

## Adım 6: Promiscuous Modu Açın
* Aynı menüde aşağı inerek Promiscuous Mode (Karışık Dinleme Modu) ayarını mutlaka ON (Açık) konumuna getirin[cite: 24].
* **Not:** Bu ayarı açmazsanız, kanal üzerinden gelen sesleri duyamazsınız[cite: 24].

## Adım 7: Ayarlanan Kanalı Cihaza Kaydedin ve Test Edin
* Yaptığınız ayarları boş bir kanala atamak için menüden Basic Settings'e (Temel Ayarlar) girin[cite: 24].
* Save Channel (Kanalı Kaydet) seçeneğini bularak onaylayın[cite: 24].
* Karşınıza çıkan listeden "Empty" (Boş) yazan bir dijital kanal sırası (Örn: 20. kanal) bulup "Save" diyerek kaydedin[cite: 24].
* **Test:** Cihazı tekrar Channel (Kanal) moduna alın, 20. kanala gidin ve PTT (Mandala) tuşuna basarak doğru gruba bağlanıp bağlanmadığını ekrandan teyit edin[cite: 24].
