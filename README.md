# ChestX-ray8 Veri Seti Üzerinde Görüntü İşleme ve Analiz Teknikleri

Bu proje kapsamında, ChestX-ray8 veri seti kullanılmıştır. ChestX-ray8, göğüs hastalıklarının teşhisine yönelik olarak hazırlanmış bir röntgen görüntü veri setidir. Veri setinde göğüs röntgeni görüntüleri ve bu görüntülere ait çeşitli hastalık etiketleri bulunmaktadır (örneğin, atelectasis, effusion, pneumonia). Görseller genellikle düşük çözünürlüklü olup, tıbbi teşhis için hem makine öğrenimi modelleri hem de görüntü işleme tekniklerinin uygulanması için uygundur.

1. Veri İnceleme ve Görselleştirme
Görsellerin ve hastalık etiketlerinin incelenmesi, istatistiksel analizler.
Rastgele Görüntü Seçimi: Veri setinden rastgele 9 görüntü seçilerek görselleştirme.
2. Histogram Analizi
Görsellerin piksel yoğunluk dağılımlarını incelemek için histogramlar oluşturma.
Piksel yoğunluklarının maksimum, minimum, ortalama ve standart sapma değerleri hesaplama.
3. Görüntü Normalizasyonu
Görseller 0-255 piksel aralığından 0-1 aralığına normalize etme.
Kontrast Germe (Stretching) işlemiyle, görüntülerin kontrast seviyeleri arttırma.
4. Histogram Eşitleme
Equalization (Histogram Eşitleme) işlemi ile kontrast artırılarak daha dengeli bir görüntü elde etme.
5. Gürültü Azaltma
Median Blur ve Gaussian Blur teknikleri kullanılarak görüntülerin üzerindeki parazitler temizleme.
6. Frekans Alanında Filtreleme
Fourier Transform kullanılarak düşük frekanslı bileşenlerin korunması sağlama.
Yüksek frekanslı bileşenlerin filtrelenmesiyle gürültüler azaltma.
7. Keskinleştirme ve Enterpolasyon
Unsharp Masking yöntemi ile görüntüleri keskinleştirme.
Keskinleştirilen görüntülere Bicubic Enterpolasyon uygulanarak boyutları büyütme.
8. Ayna Çevirme ve Döndürme
Görseller rastgele açılarda döndürme ve yatay olarak çevrme.

### Colab Notebook

[Notebook](https://colab.research.google.com/drive/1Jb6VxqwyySs4h7g9w5ktWTFCiJVTBl3M?usp=drive_link)
