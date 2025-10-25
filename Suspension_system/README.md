## Süspansiyon Sistemi Kontrolü / Suspension System Control
# Türkçe

Bu proje, bir araç süspansiyon sisteminin Simulink modeli üzerinde PID ve Skyhook kontrolcülerinin karşılaştırmalı simülasyonunu içerir.

Yapılanlar

Sinyal Girişi: Sine Wave bloğu kullanıldı.

Kontrolcüler:

1)PID kontrolcü başarıyla kuruldu.

2)Skyhook kontrolcüsü eklenerek pasif ve aktif kontrol karşılaştırması yapılabilecek hale getirildi.

3)Switch bloğu ile PID ve Skyhook kontrolü seçilebiliyor.


Gain ve Amplitüd Ayarları: Gain değerleri ve giriş sinyal genlikleri değiştirilerek PID, Skyhook ve pasif sistem arasındaki farklar daha net gözlemlenebilir.

Kullanım Notları

Simülasyonu çalıştırarak PID, Skyhook ve pasif kontrolün performansını gözlemleyebilirsiniz.

İstenirse Scope üzerinde manuel Y ve X limitleri ayarlanabilir.

z_s – z_u fark sinyali eklenerek Skyhook etkisi daha net görülebilir.

Gain değerlerini ve sinyal genliğini değiştirerek sistem tepkisi üzerindeki etkileri test edebilirsiniz.

# English

This project contains a comparative simulation of PID and Skyhook controllers on a vehicle suspension system modeled in Simulink.

Implemented Features

Input Signal: A Sine Wave block was chosen.

Controllers:

1)PID controller has been successfully implemented.

2)Skyhook controller added for comparison between passive and active control.

3)A Switch block allows selecting between PID and Skyhook control.


Gain and Amplitude Settings: Adjusting gain values and input signal amplitude allows observing the differences between PID, Skyhook, and passive system more clearly.

Usage Notes

Run the simulation to observe PID, Skyhook, and passive control performance.

Y and X axis limits can be manually adjusted if needed.

Adding the z_s – z_u difference signal helps visualize the effect of Skyhook control more clearly.

You can test the effect of gain values and input signal amplitude on system response.