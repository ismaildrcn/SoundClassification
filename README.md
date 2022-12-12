# Sound Classification
## Urban Sound 8K Dataset


Bu veri kümesi, 10 sınıftan 8732 etiketli kentsel ses alıntısı (<=4 sn) içerir: `air_conditioner`, `car_horn`, `children_playing`, `dog_bark`, `drill`, `enginge_idling`, `gun_shot`, `jackhammer`, `siren` ve `street_music`. Sınıflar kentsel ses taksonomisinden alınır. Veri seti sınıflar karıştırılmış halde (fold1-fold10 adlı klasörler) önceden sıralanmıştır.  

Listelenen bu klasörler üzerinde gezinerek ve Python'daki Librosa kitaplığını kullanarak, tüm `wav` ses dosyalarının ses spektrogramları çıkarıldı. Spektrogramlar `png` formatında kaydedildi.

Ses Spektrogramlarına ek olarak, her alıntıyla ilgili meta verileri içeren bir CSV dosyası da sağlanır.

> Tüm ses dosyaları `wavToPng.ipynb` notebook ile lokalde ses spektrogramları içeren grayscale görsellere dönüştürüldüler. Görsellerden oluşturulan datasete Kaggle'dan ([Urban Sound 8K Image (.png) Dataset](https://www.kaggle.com/datasets/smaildurcan/urban-sound-8k-image-png-dataset)) ulaşabilirsiniz.
  
  
| Metric | Value |
| ------ | ------ |
| `Accuracy` | %88.5583 |
| `Loss` | 0.4141 |  
  

J. Salamon, C. Jacoby and J. P. Bello, "A Dataset and Taxonomy for Urban Sound Research", 22nd ACM International Conference on Multimedia, Orlando USA, Nov. 2014.
Ses dosyalarını içeren verisetine ([buradan](https://urbansounddataset.weebly.com/urbansound8k.html)) ulaşabilirsiniz.