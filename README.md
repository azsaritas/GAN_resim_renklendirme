# GAN_resim_renklendirme
GAN kullanarak resim renklendirme - Image Colorization using GAN 

#### Generative Adversarial Networks iki temel yapıdan oluşur. Generator (Üretici) ve Discriminator (Ayırıcı). Generator bir veri üretir ve Discriminator üretilen bu verini gerçek mi yoksa sahte mi olduğunu anlamaya çalışır. Bu geri bildirimle Disciriminator her zaman gerçek veriye yaklaşmaya çalışır ve bu sayede Generator zamanla gerçeğe yakın veriler üretmeye başlar.
#### Bu projede önce manzara resimlerinin bulunduğu verisetindeki görsellerin bir kısmı L*a*b formatında siyah beyaz hale dönüşütürlür. Generator bu şekilde yeni görseller üretmeye çalışır. Discirminator elindeki renkli verilerle Generator tarafınfan üretilen yeni resimleri karşılaştırır. Ve renkli resimlere göre hata hesabı yapar. Bu sayede bir süre sonra Generator siyah beyaz resimlerin renklerini tahmin etmeye başlar ve gerçeğe yakın sonuçlar üretir.

# Çıktılar: 
![Çıktı 1](https://github.com/azsaritas/GAN_resim_renklendirme/blob/main/ciktilar/cikti%20(1).png)
![Çıktı 2](https://github.com/azsaritas/GAN_resim_renklendirme/blob/main/ciktilar/cikti%20(2).png)
![Çıktı 3](https://github.com/azsaritas/GAN_resim_renklendirme/blob/main/ciktilar/cikti%20(3).png)
![Çıktı 4](https://github.com/azsaritas/GAN_resim_renklendirme/blob/main/ciktilar/cikti%20(4).png)

