Semantic Segmentation Project

Bu proje, derin öğrenme tabanlı görüntü segmentasyonu yöntemlerini incelemek amacıyla hazırlanmıştır. Farklı derin öğrenme mimarileri kullanılarak semantik segmentasyon problemleri üzerinde deneyler yapılmış ve elde edilen sonuçlar karşılaştırılmıştır.

📌 Kullanılan Modeller

Projede aşağıdaki derin öğrenme tabanlı segmentasyon mimarileri uygulanmıştır:

- FCN (Fully Convolutional Network)

- UNet

- PSPNet (Pyramid Scene Parsing Network)

- DeepLabv3

Her bir model için eğitim, doğrulama ve test süreçleri yürütülmüş, sonuçlar kaydedilmiştir.

⚙️ Teknolojiler

Python 3.x

PyTorch – Derin öğrenme modellerinin tanımlanması ve eğitimi

Torchvision – Hazır modeller ve veri dönüşümleri

Matplotlib & Seaborn – Görselleştirme

NumPy & Pandas – Veri işleme

📊 Eğitim Süreci

Veri seti eğitim (%80) ve doğrulama (%20) olarak ikiye ayrılmıştır.

DataLoader ile veriler modele uygun şekilde hazırlanmıştır.

Early Stopping mekanizması uygulanarak aşırı öğrenme (overfitting) engellenmiştir.

Eğitim sonunda her model için Precision, Recall, F1-Score, Accuracy, IoU metrikleri hesaplanmıştır.

🖼️ Sonuçların Görselleştirilmesi

Model çıktıları, gerçek maskeler ve tahmin maskeleri yan yana gösterilmiştir. Aşağıda örnek bir çıktı yer almaktadır:

📈 Değerlendirme

FCN: Basit yapısı ile hızlı ancak doğruluk oranı diğer modellere göre daha düşüktür.

UNet: Özellikle medikal görüntülerde başarılı sonuçlar vermiştir.

PSPNet: Çok ölçekli özellik çıkarımı sayesinde daha iyi segmentasyon sağlamıştır.

DeepLabv3: En yüksek başarıyı elde eden model olmuştur.
