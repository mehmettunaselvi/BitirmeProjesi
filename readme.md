# Proje Adı

Bu proje, [Proje Adı]'nın detaylarını ve kullanımını içermektedir. Bitirme tezi kapsamında geliştirilmiştir.

## İçindekiler

- [Özet](#özet)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Efektiflik Skoru](#efektiflik-skoru)
- [Katkıda Bulunanlar](#katkıda-bulunanlar)
- [Lisans](#lisans)

## Özet

Mevcut projemiz olarak Katarakt Teşhisi için pre-
trained edilmiş eğitim ağırlıklarıyla çalışıldı. Bu ağırlıklardan popülaritesi, kompleks ve çok sayıda
farklı türde görseller üzerine çalışan ImageNet kullanıldı. Egitim için faydalandığımız bir diğer yapı
ise VGG19 oldu. State-of-Art modellerinden biri olan,başarımı ve efektif çalışması çoğunluk
tarafından onaylanmış VGG19 modeli, 19 katmanlı bir evrişimli sinir ağı modelidir. Görsel
segmentasyon işlemlerinde yüksek başarımı ile bilinmektedir. Uygulamamızın temel amacı teşhis
cümlelerinde Kataraktlı ve Normal olarak etiketlenmiş görselleri ikili şekilde sınıflandırabilecek
yüksek başarımlı bir eğitim modeli oluşturmaktır.

## Kurulum

Bu projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. **Gereksinimleri Yükleyin:**

   Proje için gerekli olan modüllerin tamamı ve kurulum aşamaları tezde verilmiştir. Proje üzerinde çalışmadan önce kesinlikle bakmanızı tavsiye ederim.

2. **Projeyi Klonlayın:**

   GitHub reposunu yerel makinenize klonlayın:

   ```bash
   git clone https://github.com/mehmettunaselvi/BitirmeProjesi
   cd BitirmeProjesi
   ```

## Kullanım

Projeyi kullanmak için aşağıdaki adımları izleyin:

1. **Veri Setini Yükleyin:**

   Veri setini proje dosyaları ile birlikte verilmiştir. Aynı modeli farklı veri setlerinde denemek isterseni
   ( `kaggle/input/ocular-disease-recognition-odir5k/full_df.csv`) dosya yolunda `full_df.csv` yi kendi özelleştirdiğiniz veri seti ile değiştirin.

2. **Scripti Çalıştırın:**

   Ana script dosyasını çalıştırarak modeli eğitin ve test edin:

   .ipynb uzantılı dosya üzerinden hücre hücre çalıştırıp çıktıları gözlemleyebilirsiniz.

## Efektiflik Skoru

Projenin efektiflik skorunu aşağıdaki şekilde değerlendirebilirsiniz:

- Doğruluk: %97
- Overfitting: %3
- F1 Skoru: %96

Bu skorlar, projenin performansını değerlendirirken dikkate alınması gereken önemli metriklerdir.

## Katkıda Bulunanlar

- [Mehmet Tuna Selvi](https://github.com/mehmettunaselvi)
- [Esra Gülmez](https://github.com/EsraGulmez)

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır.
