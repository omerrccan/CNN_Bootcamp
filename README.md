# CNN_Bootcamp

Bu repo, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiştir.
Projede Convolutional Neural Networks (CNN) kullanılarak **Intel Image
Classification** veri seti üzerinde çok sınıflı görüntü sınıflandırma
gerçekleştirilmiştir.

## Giriş

Bu projede kullanılan veri seti:\
- **Intel Image Classification Dataset** (6 sınıf: Buildings, Forest,
Glacier, Mountain, Sea, Street).

Çalışmada CNN tabanlı modeller (ResNet18) kullanılmış, transfer learning
ve fine-tuning teknikleri uygulanmıştır.\
Notebook içerisinde Markdown hücreleri ile teknik anlatımlar ve
görseller eklenmiştir.

## Metrikler

Eğitim sürecinde elde edilen sonuçlardan bazıları:\
- Eğitim / Doğrulama **loss-accuracy grafikleri**\
- **Confusion Matrix** ve **Classification Report**\
- **F1-macro \~0.94** seviyelerine ulaşılmıştır.\
- Modelin karar mekanizması **Grad-CAM ve Eigen-CAM** ile
görselleştirilmiştir.

Ayrıca, **Random Search** ile hiperparametre optimizasyonu yapılmış,
dropout, learning rate, optimizer gibi parametrelerde farklı denemeler
gerçekleştirilmiştir.

## Ekler

Proje kapsamında:\
- **Grad-CAM ve Eigen-CAM** görselleştirmeleri ile açıklanabilir yapay
zeka entegrasyonu sağlanmıştır.\
- Eğitim sürecinde overfitting/underfitting durumu grafiklerle
yorumlanmıştır.\

## Sonuç

Bu proje ile CNN tabanlı görüntü sınıflandırma konusunda pratik deneyim
kazanılmıştır


## Linkler

-   📘 Kaggle Notebook: [CNN Bootcamp
    Notebook](https://www.kaggle.com/code/mercan12312325/cnn-project1)\
-   📊 Veri Seti: [Intel Image
    Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
