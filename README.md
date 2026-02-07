# 🎮 VR Fobi Tedavi Simülasyonu

<div align="center">

![Unity](https://img.shields.io/badge/Unity-2022.3+-black?style=for-the-badge&logo=unity)
![VR](https://img.shields.io/badge/VR-Meta%20Quest-blue?style=for-the-badge&logo=oculus)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Sanal Gerçeklik ile Fobi Tedavisi - Exposure Therapy Uygulaması**

[🎯 Özellikler](#-özellikler) • [🚀 Kurulum](#-kurulum) • [🎮 Kullanım](#-kullanım) • [📁 Proje Yapısı](#-proje-yapısı)

</div>

---

## 📖 Proje Hakkında

Bu proje, **Sanal Gerçeklik (VR)** teknolojisi kullanarak çeşitli fobilerin tedavisine yardımcı olmak amacıyla geliştirilmiş bir **Exposure Therapy (Maruz Bırakma Terapisi)** simülasyonudur.

Kullanıcılar güvenli bir sanal ortamda korkularıyla yüzleşerek, kontrollü bir şekilde fobilerini aşmayı öğrenebilirler.

---

## 🎯 Özellikler

### 🏔️ Yükseklik Fobisi (Acrophobia)

**🌲 Doğal Ortam - Vadi Köprüsü:**
- **Seviye 1:** Güvenli köprü geçişi - Başlangıç seviyesi
- **Seviye 2:** Yüksek platform deneyimi - İleri seviye
- Kocaman bir vadi üzerinde asma köprü deneyimi
- Doğal manzara ve derin uçurum

**🏙️ Şehir Ortamı - Gökdelen:**
- Yüksek gökdelen çatısında deneyim
- Modern şehir manzarası
- Cam zeminli platform

**⚙️ Ortak Özellikler:**
- **Güvenlik Rayları:** Açılıp kapanabilen korkuluklar
- **Düşme Respawn:** Düşme durumunda güvenli geri dönüş
- **Vignette Efekti:** Kenar kararması ile korku göstergesi

### 🕷️ Örümcek Fobisi (Arachnophobia)
- Kontrollü örümcek maruziyeti
- Kademeli zorluk seviyeleri

### 🚪 Klastrofobi (Claustrophobia)
- Daralan oda deneyimi
- Kapalı alan simülasyonu

### 🎛️ Genel Özellikler
- ✅ Modern VR arayüzü
- ✅ Kolay navigasyon sistemi
- ✅ Işınlanma (Teleportation) desteği
- ✅ VR controller desteği
- ✅ Dinamik sahne geçişleri

---

## 🚀 Kurulum

### Gereksinimler
- **Unity 2022.3** veya üzeri
- **XR Interaction Toolkit** paketi
- **TextMeshPro** paketi
- **VR Gözlük** (Meta Quest, HTC Vive, vb.)

### Adımlar

1. **Projeyi klonlayın:**
```bash
git clone https://github.com/squichip/vr-proje-son.git
```

2. **Unity ile açın:**
   - Unity Hub'ı açın
   - "Add" butonuna tıklayın
   - Proje klasörünü seçin

3. **Gerekli paketleri yükleyin:**
   - Window → Package Manager
   - XR Interaction Toolkit'i yükleyin
   - XR Plugin Management'ı yapılandırın

4. **VR cihazınızı bağlayın ve oynatın!**

---

## 🎮 Kullanım

### Ana Menü
- **Yükseklik Fobisi:** Köprü ve platform seviyeleri
- **Örümcek & Klastrofobi:** Bekleme odasına geçiş

### Kontroller
| Eylem | Kontrol |
|-------|---------|
| Hareket | Sol Joystick |
| Teleport | Sağ Joystick |
| Etkileşim | Trigger |
| Güvenlik Rayı | A Butonu |
| Menü | Menu Butonu |

### Seviye Geçişleri
- Bitiş çizgisine ulaşınca panel açılır
- "Sonraki Seviye" veya "Ana Menü" seçenekleri

---

## 📁 Proje Yapısı

```
Assets/
├── ali_assetler/
│   ├── Art/
│   │   ├── Materials/     # Materyaller
│   │   ├── Texture/       # Görseller ve ikonlar
│   │   └── UI/            # Arayüz görselleri
│   ├── LevelManager.cs         # Seviye yönetimi
│   ├── FallRespawnManager.cs   # Düşme/respawn sistemi
│   ├── SafetyRailManager.cs    # Güvenlik rayları
│   ├── RoomTeleportButton.cs   # Oda geçiş butonu
│   ├── ExitDoorTrigger.cs      # Çıkış kapısı
│   ├── MainMenuButton.cs       # Ana menü butonu
│   └── ForceCameraHeight.cs    # VR kamera yüksekliği
├── Scenes/
│   ├── MainMenu.unity     # Ana menü sahnesi
│   ├── ozcan2.unity       # Fobi odaları sahnesi
│   └── ...
└── XR/                    # VR ayarları
```

---

## 🛠️ Teknik Detaylar

### Kullanılan Teknolojiler
- **Unity Engine** - Oyun motoru
- **XR Interaction Toolkit** - VR etkileşimleri
- **TextMeshPro** - UI metinleri
- **C#** - Scripting

### Ana Scriptler

| Script | Açıklama |
|--------|----------|
| `LevelManager.cs` | Seviye geçişleri, panel yönetimi |
| `FallRespawnManager.cs` | Düşme algılama, respawn, vignette |
| `SafetyRailManager.cs` | Güvenlik raylarını açma/kapama |
| `RoomTeleportButton.cs` | Oda geçişleri için ışınlanma |
| `ForceCameraHeight.cs` | VR kamera yükseklik düzeltmesi |

---

## 👥 Proje Ekibi

- **Ali Turhan** - Geliştirme ve Tasarım
- **Şinasi Onuralp Akkurt** - Geliştirme ve Tasarım
- **Özcan Yıldıral** - Geliştirme ve Tasarım

---

## 📄 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır.

---

<div align="center">



</div>
