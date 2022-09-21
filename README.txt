Bu dosyanın içerisinde 3 farklı projeye ait kodlar bulunmaktadır.

data_augmentation.ipynb dosyasında, veri çoğaltma yöntemleri bir resim üzerinde denenmiştir. Bunu 
denemek için kod içerisindeki path'e bilgisayarınızda bulunan bir resmin yolu verilebilir.

image_enhancement.ipynb dosyasında, görüntü netleştirme yöntemleri bir resim üzerinde denenmiştir. Bunu 
denemek için kod içerisindeki path'e bilgisayarınızda bulunan bir resmin yolu verilebilir.

Mask_RCNN dosyası, Mask RCNN modeli için gerekli dosyaları barındırır.

demo.ipynb dosyası, "Mask RCNN ile Nesne Tespiti" projemin ana kodudur. 

mask_rcnn_cars.h5 dosyası, modelin eğitimi sonucunda elde ettiğim ağırlıklardır. Ana kod üzerinde
eğitim yapan kod kısımlarının çalıştırılmasına gerek yoktur. Direkt eğitilmiş ağırlıklar kullanılabilir.
Eğitilmiş ağırlıklara bu linkten ulaşabilirsiniz:
https://drive.google.com/file/d/1g8xGAZCjZ8DkNAkScEPi8w391C6Eqhhy/view?usp=sharing

car_detection_dataset dosyası ise test,val ve train olarak üçe bölünmüş bir veri kümesidir. Bu veri 
kümesinin yolunun demo.ipynb'de gerekli path'lere verilmesi gerekmektedir.