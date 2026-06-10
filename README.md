# ZombieChallenge 🧟‍♂️🔫

**Unreal Engine** kullanılarak geliştirilmiş, aksiyon dolu bir Birinci Şahıs Nişancı (FPS) Zombi Hayatta Kalma oyunu. Yoğun arena ve orman ortamlarında zombi sürülerine karşı savaşın.

---

## 🎮 Özellikler

- **Birinci Şahıs Nişancı (FPS) Mekanikleri**: Akıcı hareket, silah kullanımı, ateş etme ve yeniden doldurma (reload).
- **Dinamik Haritalar**: 
  - **Arena Haritası (Arena Shooter)**: Hızlı ve yakın mesafe çatışmalar.
  - **Ladin Ormanı Haritası (Spruce Forest)**: Açık dünyada taktiksel hayatta kalma.
- **Zombi Yapay Zekası**: Akıllı zombi belirme (spawn), hedef takip etme ve kovalama davranışları.
- **Optimize Edilmiş Varlıklar**: Yüksek kaliteli modüler çevre modelleri ve kaplamalar.

---

## 🛠️ Kullanılan Teknolojiler

- **Motor**: Unreal Engine (UE5)
- **Programlama / Kodlama**: Blueprints & C++
- **Sürüm Kontrolü**: Git & Git LFS (Large File Storage)

---

## 🚀 Başlarken

### Gereksinimler

1. Uyumlu bir [Unreal Engine](https://www.unrealengine.com/) sürümü yükleyin.
2. Bilgisayarınızda [Git](https://git-scm.com/) ve [Git LFS](https://git-lfs.github.com/)'in kurulu olduğundan emin olun.

### Kurulum ve Çalıştırma

1. **Depoyu klonlayın**:
   ```bash
   git clone https://github.com/kadirzbk/ZombieChallengeUE.git
   ```
2. **Git LFS'i başlatın** (büyük boyutlu kaplama ve modelleri çekmek için):
   ```bash
   git lfs pull
   ```
3. `ZombieChallenge.uproject` dosyasını Unreal Engine Editor ile açın.
4. Gerekirse Visual Studio proje dosyalarını oluşturun (Generate Visual Studio project files), derleyin ve oyunu başlatın.

---

## 📂 Proje Yapısı

- `Config/`: Proje ve editör yapılandırma ayarları.
- `Content/`: Oyundaki tüm modeller, haritalar, blueprint'ler, materyaller ve ses dosyaları.
- `Source/`: C++ kaynak kodları (varsa).
- `.gitignore`: `Binaries`, `Intermediate`, `Saved` gibi geçici ve ağır boyutlu klasörlerin yüklenmesini engeller.
- `.gitattributes`: Büyük boyutlu binary dosyaların (`.uasset`, `.umap`, `.fbx` vb.) Git LFS ile yönetilmesini sağlar.
