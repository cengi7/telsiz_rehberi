---
title: TYT UV-99 Programlama Yazılımı (CPS) Kurulum Rehberi
date: 2026-10-02 12:00:00 +0300
categories: [Telsiz Yazılımları, TYT]
tags: [tyt, uv99, cps, programlama, yazılım, frekans]
---

TYT UV-99 el telsizinizin kanal listesini düzenlemek, frekans yüklemek ve cihazın gelişmiş menü ayarlarını bilgisayarınız üzerinden kolayca yapabilmek için orijinal **Customer Programming Software (CPS)** yazılımını kullanmanız gerekmektedir.

Bu rehberde TYT UV-99 programlama yazılımının kurulum aşamalarını ve dikkat edilmesi gereken noktaları bulabilirsiniz.

---

## Gerekli Gereksinimler

* **TYT UV-99** El Telsizi
* **K-Plug uyumlu USB Programlama Kablosu**
* **Windows İşletim Sistemine Sahip Bilgisayar** (Windows 10/11 desteklenmektedir)

---

## Adım Adım Kurulum Rehberi

### 1. Programlama Kablosunun Bağlanması
Programlama kablonuzu bilgisayarınızın USB portuna takın. Aygıt Yöneticisi üzerinden kablonuza atanan **COM Port** numarasını kontrol edin (Örn: `COM3` veya `COM4`).

> **Not:** Eğer Aygıt Yöneticisi'nde sarı ikaz simgesi görüyorsanız kablonuzun FTDI veya Prolific USB sürücüsünü güncellemeniz gerekebilir.

### 2. Yazılımın Yüklenmesi
1. Sayfa sonundaki resmi indirme bağlantısından kurulum dosyasını (`.exe`) bilgisayarınıza indirin.
2. İndirdiğiniz dosyayı çalıştırın ve ekrandaki kurulum adımlarını takip ederek yüklemeyi tamamlayın.
3. Kurulum bittiğinde masaüstünüzde oluşan **TYT UV-99 CPS** kısayoluna sağ tıklayıp **Yönetici olarak çalıştır** seçeneğiyle programı açın.

### 3. Telsizden Veri Okuma (Read)
1. Telsizinizi kapatın ve programlama kablosunu telsize tam oturduğundan emin olarak takın.
2. Telsizi açın ve ses seviyesini yarıya getirin.
3. CPS yazılımında üst menüden **Communication** veya **Port** seçeneğinden kablonuzun bağlı olduğu `COM Port` numarasını seçin.
4. Menüdeki **Read from Radio** (Telsizden Oku) butonuna basarak mevcut frekans ve kanal verilerini bilgisayara aktarın.

---

## Dosya İndirme Bağlantısı

TYT UV-99 telsizinize ait orijinal üretici yazılımını Cloudflare R2 yüksek hızlı indirme sunucularımız üzerinden güvenle indirebilirsiniz:

> 💾 **İndirme Linki:**  
> [TYT UV-99 Customer Programming Software V1.08 (.exe)](https://indir.cengizkaya.net/UV99_20230909_V108.exe)
> ### Orijinal Firmware (Aygıt Yazılımı)

* ⚙️ **TYT UV-99 Güncelleme Firmware (2025.05.24 - vB91.38):**  
  [TYT UV-99 Firmware vB91.38 İndir (.bin)](https://indir.cengizkaya.net/Eng_UV99_Upadat_20250524_B91.38.bin)
> ### Alternatif Sürümler ve İndirme Bağlantıları

* 📥 **TYT UV-99 CPS v1.04 (2022.10.24 Sürümü):**  
  [TYT UV-99 v1.04 İndir (.exe)](https://indir.cengizkaya.net/UV99_20221024_V104.exe)
