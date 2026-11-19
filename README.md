# Umbra 3D — 3B → 2B Gölge ve İzdüşüm Simülatörü

Python ile geliştirilen, 3 boyutlu geometrik cisimlerin bir ışık kaynağı (fener) yardımıyla 2 boyutlu bir düzleme düşen gerçek zamanlı gölgelerini incelemeye yarayan etkileşimli izdüşüm laboratuvarı.

## Amaç
İzdüşümsel geometrinin temel mantığını (3B nesnelerin 2B gölgelere dönüşümünü) sıfırdan inşa ederek kavramak ve yüksek boyutlu izdüşümler (4B → 3B) için görsel sezgi geliştirmek.

## Planlanan Özellikler
- **Geniş 3B Oda Ortamı:** Ayarlanabilir ortam aydınlatmasına (ambient light) sahip, ferah 3 boyutlu sahne.
- **Geometrik Cisimler:** Küp, piramit, tetrahedron, oktahedron, küre ve diğer temel 3B şekiller.
- **Tel Kafes & Katı Mod:** Her cismin hem içi boş tel kafes (wireframe) hem de katı (solid) olarak görüntülenmesi.
- **Etkileşimli Fener Kontrolü:** Fare ile sürükleme/döndürme veya doğrudan sayısal koordinat/açı girişi.
- **Gelişmiş Işık Ayarları:** Işık gücü, hüzme açısı (boyut), ortam parlaklığı ve odak ayarları için kaydırıcı + sayısal kutu (0–100) senkronizasyonu.
- **Görselleştirme Yardımcıları:** İsteğe bağlı ışın izleri (ray guides) ve "2B Gözlemci" duvar önizleme penceresi.

## Kurulum

```bash
# Repoyu klonlayın
git clone [https://github.com/](https://github.com/)yunusemreshahbaz/umbra-3d.git
cd umbra-3d

# Sanal ortamı oluşturun ve aktifleştirin (Windows)
python -m venv .venv
.venv\Scripts\activate

# Bağımlılıkları yükleyin
pip install -r requirements.txt

# Uygulamayı başlatın
python src/main.py