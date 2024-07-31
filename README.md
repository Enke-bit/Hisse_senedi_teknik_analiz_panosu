# Hisse Senedi Analiz Panosu

Bu proje, hisse senedi analizleri için bir grafik uygulamasıdır. Kullanıcılar, seçtikleri hisse senedinin geçmiş verilerini görüntüleyebilir ve çeşitli finansal göstergeleri analiz edebilirler. Uygulama, `yfinance` kütüphanesi ile verileri çeker ve `matplotlib` ile görselleştirir.

## Özellikler

- **Fiyat ve Zaman Grafiği**: Hisse senedinin kapanış fiyatları ve hacim grafikleri.
- **Hareketli Ortalamalar (MA20 ve MA50)**: Kapanış fiyatlarına göre 20 ve 50 günlük hareketli ortalamalar.
- **Aylık Ortalama Fiyat**: Her ay için ortalama kapanış fiyatı.
- **Hacim Grafiği**: Hisse senedinin işlem hacmi grafiği.
- **RSI (Relative Strength Index)**: 14 günlük RSI göstergesi.
- **Bollinger Bantları**: 20 günlük hareketli ortalama ve üst/alt Bollinger bantları.
- **MACD (Moving Average Convergence Divergence)**: MACD ve sinyal çizgileri.
- **OBV (On-Balance Volume)**: Hacimle birlikte fiyat değişimini gösteren OBV göstergesi.
- **Stokastik Osilatör**: 14 günlük stokastik osilatör göstergesi.

## Kullanım
Uygulama açıldığında, "Hisse Senedi Kodu" alanına analiz etmek istediğiniz hisse senedinin kodunu girin.
"Göster" butonuna tıklayarak verileri çekin ve grafikleri görüntüleyin.

Ekran Görüntüleri
- Fiyat ve Zaman Grafiği
- Hareketli Ortalamalar
- Aylık Ortalama Fiyat
- Hacim Grafiği
- RSI
- Bollinger Bantları
- MACD
- OBV
- Stokastik Osilatör


## Katkıda Bulunanlar
İbrahim Püsküllü - Proje sahibi ve geliştirici
## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

## İletişim
Herhangi bir sorunuz varsa, ibrahimpuskullu44@gmail.com adresi üzerinden bana ulaşabilirsiniz.

## Gereksinimler

Projenin çalışması için aşağıdaki Python kütüphanelerine ihtiyacınız olacak:

- `yfinance`
- `pandas`
- `matplotlib`
- `ta`
- `tkinter`

Bu kütüphaneleri yüklemek için aşağıdaki pip komutunu kullanabilirsiniz:

```bash
pip install yfinance pandas matplotlib ta

