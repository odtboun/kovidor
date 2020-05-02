# Kovidor Projesi (TRIA AI COVID-19 Datathonu 2.si)

## Amaç
Projenin amacı ülkelerin pandemi süreçlerindeki benzerlikleri toplam ve yeni vaka sayılarının artışını inceleyerek tespit etmek ve temkinli, anlaşılır ve bilgilendirici bir model ortaya koymaktır. Bu model çıktısı herhangi bir ülkenin pandemi sürecinin neresinde olduğunu özetleyecek bir gösterge olacaktır.

## Veri Kaynağı
Hazır olarak tek bir veri seti kullanılmış, bu veri seti üzerinden özgün veri setleri oluşturulmuştur. Hazır olarak alınan ve günlük olarak 
güncellenen ülkelerin vaka sayılarına ulaşmak için: https://covid.ourworldindata.org/data/ecdc/total_cases.csv

## Araçlar
Tüm proje R dili ve kütüphaneleri kullanılarak jupyter notebook'ta geliştirilmiştir. 

**Kullanılan Kütüphanler:**
- _Tidyverse_ (Verinin yüklenmesi / düzenlenmesi)
- _Plotly_ (Görselleştirme)

## Sonuç
Yapılan analizler sonucu tüm ülkelerin özellikle 100 toplam vaka sayısından sonra çok benzer bir süreç tecrübe ettikleri görülmüştür. Bu sürece _Pandemi Koridoru_ ya da kısaca **_Kovidor_** denmektedir. İlgili görselleştirmelere yer verilmiş ve ülkelerin kovidora girip girmediği, kovidordan çıkıp çıkmadıkları ve koridordan çıkmaya ne kadar yaklaştıklarını hesaplayan R fonksiyonları oluşturulmuştur.
