# Automatic-Modulation-Classification-with-Deep-Learning
Using the multi-class modulation dataset Tensorflow library with different SNR levels, different CNN models were trained with the GPU and the modulation types were classified for each SNR level.

## Modülasyon Nedir ? 
Modülasyon, düşük frekanslı bilgi sinyalini, yüksek frekanslı taşıyıcı sinyal ile uzak mesafelere taşıyabilen bir yöntemdir. Analog ve sayısal olarak iki temel yöntemin altında farklı modülasyon türleri bulunmaktadır. Modülasyon işlemini gerçekleştirmek için iki sinyale ihtiyaç bulunmaktadır. Bu sinyaller; Bilgi Sinyali ile Taşıyıcı Sinyali'dir. Alçak frekanslı bilgi sinyaline, modüle edici, modüle eden, modülasyon sinyali, gönderilecek sinyal ya da alçak frekanslı (AF) sinyal ismi verilmektedir. Yüksek frekanslı taşıyıcı sinyaline, modüle eden, RF (Radyo Frekans) sinyali ya da hamal sinyali adını almaktadır. Modülasyon işleminde modüle eden sinyal, bilgi sinyali; modülasyona uğrayan ya da modüle edilen sinyal ise taşıyıcı sinyal olmaktadır.
Modülasyon Çeşitleri ve Özellikleri
Modülasyon işlemi sonunda taşıyıcı sinyalin frekansı, genliği ile fazı değişikliğe uğramaktadır. Genel olarak üç çeşit modülasyon bulunmaktadır.
a) Genlik Modülasyonu (Amplitude Modulation, A-M, G-M): Taşıyıcı sinyalin genliğinin, bilgi sinyalinin genliğine ve frekansına bağlı olarak değiştirilmesi olarak tanımlanır.
b) Frekans Modülasyonu (Frequency Modulation, F-M): Taşıyıcı sinyal frekansının, bilgi sinyalinin frekans ile genliğine bağlı olarak değiştirilmesidir.
c) Faz Modülasyonu (Phase Modulation, P-M): Taşıyıcı sinyal fazının, bilgi sinyalinin frekans ve genliğine bağlı olarak değiştirilmesi olarak ifade edilmektedir. Endirekt F-M olarak da bilinmektedir.
Otomatik modülasyon sınıflandırma (OMS) işlemi ise alınan sinyalden modülasyon türlerini sınıflandırmak için kullanılan bir yöntemdir. Otomatik modülasyon sınıflandırma, elektronik harp, yazılım tabanlı radyo ve spektrum farkındalığı gibi çeşitli askeri ve sivil iletişim sistemlerinin önemli bir kısmında kullanılmaktadır.
Bu çalışmada ise derin öğrenme modelleri kullanarak, Derin Öğrenme tabanlı Otomatik Modülasyon Sistemlerinin yöntemi ile modülasyonların farklı SNR değerleri için sınıflandırılması yapılarak, kullanılan modellerin modülasyon sınıflandırma problemindeki performansları karşılaştırılmaktadır.
