# Electric Cars Dataset Visualization
Bu projede, <a href= "https://www.kaggle.com/datasets/kkhandekar/cheapest-electric-cars">Kaggle</a>'den aldığım "Cheapest Electric Cars Dataset" adlı veri kümesini kullanarak elektrikli araçlar hakkında bilgi elde etmek ve bu verileri görselleştirmek amaçlanmıştır.
Projeyi gerçekleştirirken şu adımları izledim:

## Veri Hazırlığı:

1) İlk adımda, "Cheapestelectriccars-EVDatabase.csv" adlı veri dosyası <a href= "https://www.kaggle.com/datasets/kkhandekar/cheapest-electric-cars">Kaggle</a> adlı siteden indirdim ve projeye entegre ettim.
2) Veri dosyasının yapısını <a href= "https://pandas.pydata.org">pandas</a> kütüphanesi yardımıyla inceleyerek, eksik verilerin sayısını kontrol ettim.
3) Az sayıda olan eksik verileri tamamlamak için değerleri "0" ile doldurdum.
4) Veri içindeki fiyat, hız, verimlilik, menzil gibi sayısal değerleri uygun bir formata dönüştürdüm.

## Veri Görselleştirme:

1) Veriyi görselleştirmek için Python programlama dili ve <a href= "https://matplotlib.org">matplotlib</a> ile <a href= "https://seaborn.pydata.org">seaborn</a> kütüphanelerini kullandım.
2) Elektrikli araçların en yüksek hızlarına göre sıralanmış bir çubuk grafik oluşturarak, en hızlı araçların listesini sundum.
![Top-40-Cheapest-Electric-Cars_s-Top-Speed](https://github.com/KaganMuslu/Electric-Cars-Dataset-Visualization/assets/71410113/2cccf123-2c1e-4e7b-a26c-65b81dd23d89)

3) Verilerin korelasyonunu incelemek için ısı haritası (heatmap) kullandım.
![Data-Correlation](https://github.com/KaganMuslu/Electric-Cars-Dataset-Visualization/assets/71410113/a55f55d0-ad2d-4d6c-9547-2004bb001936)

4) Veriyi daha iyi anlamak için, "Subtitle", "Acceleration", "TopSpeed", "Range", "FastChargeSpeed" ve "PriceinUK" özelliklerini içeren bir çift grafik ve saçılım (scatter) grafikleri oluşturdum.
![output](https://github.com/KaganMuslu/Electric-Cars-Dataset-Visualization/assets/71410113/a8c3f255-95db-40f1-9b5e-29c4ccd0b473)

5) Eksik verileri temizledikten sonra fiyat verilerini karşılaştırmak için bir başka saçılım grafik oluşturdum.
![output5](https://github.com/KaganMuslu/Electric-Cars-Dataset-Visualization/assets/71410113/e205cd94-5d50-4078-98b4-c8a3b6459a00)
