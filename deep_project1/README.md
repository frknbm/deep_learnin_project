# Deep Learning Project
 
---

## Proje Açıklaması

Bu proje, görüntü sınıflandırma üzerine odaklanan bir derin öğrenme çalışmasıdır. Projenin temel amacı, bir görüntü veri kümesinde yer alan nesneleri sınıflandırmak için çeşitli model tasarımları kullanmaktır.
Proje kapsamında şu adımlar izlenmiştir:

Veri Seti Ayrımı: Görüntü veri seti, %80 eğitim, %20 test oranında ayrılmıştır.Ve %70 eğitim ,%30 tes oranında da ayrılmıştır. Ayrıca, seçilen gruplar için %10 validation verisi de kullanılmıştır.

CNN Model Tasarımı: İlk olarak, özel bir Convolutional Neural Network (CNN) tasarlanmıştır. Bu modelin hiperparametreleri dikkatlice seçilmiş ve modelin performansı eğitim, test ve validation aşamalarında değerlendirilmiştir.

Transfer Learning: VGG16 modeli kullanılarak transfer learning yöntemi uygulanmıştır. Bu modelin performansı da eğitim, test ve validation aşamalarında değerlendirilmiştir.

Yapay Sinir Ağı Tasarımı: Ayrıca, kendi özel bir yapay sinir ağı tasarlanmış ve bu modelin performansı da değerlendirilmiştir.

Performans Değerlendirme: Her bir model için test verisinin performansı, Accuracy, Precision, Recall, F1 Score gibi ölçütlerle değerlendirilmiş ve karşılaştırılmıştır. Ayrıca, karmaşıklık matrisi ve sınıflandırma raporu da sunulmuştur.

Bu proje, görüntü sınıflandırma modellerini tasarlama, transfer learning uygulama ve kendi özel modelleri geliştirme konularında derinlemesine bir anlayış geliştirmeyi amaçlamaktadır.

Kullandığımız teknolojiler ise:python ve kütüphaneleri(numpy,pandas,Matplotlib, Seaborn,Scikit-learn) ;derin öğrenme ve kütüphanleri(keras-tensorflow,Scikit-image) projede sonuçların gösterilmesi içinde google colab,jupyter notebook kullandık.

---

## Proje Dosya Yapısı

- `test30.ipynb`
- `test20.ipynb`
- `README.md`
- `LICENSE`  


---

## Kurulum

Bu depoyu yerel bilgisayarınıza klonlayın:

bash
Copy code
git clone https://github.com/kullanici/proje.git
cd proje
Gerekli bağımlılıkları yükleyin:

bash
Copy code
pip install -r requirements.txt
Veri kümesini indirin ve /data dizinine yerleştirin.

Modeli eğitmek için:

bash
Copy code
python src/data_preprocessing.py
python src/model_architecture.py

ve gerekli kütüphaneleri yükleyin numpy,pandas,Matplotlib, Seaborn,Scikit-learn-derin öğrenme ve kütüphanleri(keras-tensorflow,Scikit-image) !pip install #kütüphane ismi  <== windows

---

## Kullanım

Projede kurulumu yapınca ve gerekli kütphaneleri yükledikten sonra kodları çalıştırmanız yeterli olacaktır.Kurulum aşamassını okuyun!

---

## Katkılar

Bu projede derin öğrenme, görüntü sınıflandırma ve transfer öğrenme konularında bilgi edinirken şu kaynaklardan faydalanılmıştır:btk derin öğrenme ders videoları,udemy videoları,
https://www.tensorflow.org/guide/keras?hl=tr
https://keras.io/
yukarıdaki kaynaklardan yararlandık genel olarak.


---

## İletişim

Furkan Bayram ==> furkanbyrm02@gmail.com  (github)==>https://github.com/frknbm  


