# Teemo Oğuz · 3D Model

**[Modeli tarayıcıda görüntüle →](https://alptekincanatar.github.io/teemo-alp-3d/)**

Kurulum gerektirmeden, telefon veya bilgisayardan 3D modeli döndürüp yakınlaştırabilirsiniz.

## Kontroller

- Sürükle: döndür
- Tekerlek veya iki parmakla çimdik: yakınlaştır
- Sağ tık + sürükle: kaydır
- Düğmeler: otomatik döndürme, ön / yan / arka / yüz görünümü ve açık zemin

## Yerelde çalıştırma

```sh
python3 -m http.server 8000
```

Ardından http://localhost:8000 adresini açın. Dosyayı doğrudan çift tıklamak yerine bir web sunucusu kullanın.

## İçerik

- `index.html`: etkileşimli görüntüleyici
- `models/character.glb`: dokulu 3D model (~4,7 MB)
- `lib/three/`: yerel Three.js r160 bağımlılıkları ve MIT lisansı

Tüm çalışma dosyaları repo içindedir; CDN veya derleme adımı gerekmez.
Model rig veya animasyon içermez. Three.js lisansı `lib/three/LICENSE` içindedir.

## Yayın

GitHub Pages: `main` dalı, `/ (root)` klasörü.
