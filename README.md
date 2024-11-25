# Maaş ve Tecrübe Arasındaki İlişkiyi Modelleme

Bu proje, çalışanların maaşlarını tahmin etmek için tecrübe (yıl olarak) ile maaş arasındaki ilişkiyi modellemeyi amaçlamaktadır. Veri seti, çalışanın tecrübe düzeyine göre maaşını tahmin etmek için kullanılan örnek verilerden oluşmaktadır. Bu tür bir analiz, iş dünyasında maaş tahminlerini daha doğru yapmayı ve çalışanları daha iyi değerlendirmeyi sağlayabilir.

https://www.kaggle.com/datasets/hussainnasirkhan/multiple-linear-regression-dataset kullanılan dataset.Bir bağımlı ve bir bağımsız değişken olacak şekilde indirgendi.

## Veri Seti Açıklaması

Veri seti, her çalışanın maaşı ve yıllık tecrübesi ile ilgili bilgileri içerir. Bu veri seti ile lineer regresyon modeli eğitilmiş olup, maaşın tecrübe ile nasıl bir ilişki içerisinde olduğu incelenmiştir. 

### Veri Seti Özellikleri

- **Tecrübe (Yıl)**: Çalışanın toplam iş tecrübesini yıl olarak gösterir. Bu, bağımsız değişken (X) olarak kullanılmaktadır. Yani, modelin tahmin yapabilmesi için kullanılan ana veridir.
  
- **Maaş (TL)**: Çalışanın maaşını Türk Lirası (TL) cinsinden belirtir. Bu, bağımlı değişken (Y) olarak kullanılmaktadır. Modelin tahmin etmek amacıyla çalışacağı veridir.

## Modelin Amacı

Modelin temel amacı, çalışanların maaşlarını tahmin edebilmek için yalnızca tecrübe (yıl) verisini kullanmaktır. Bu, özellikle iş dünyasında yeni işe alım süreçlerinde maaş önerileri yapmak ve mevcut çalışanların maaşlarını belirlemek için faydalı olabilir.

## Modelleme Yöntemi

Bu proje, **lineer regresyon** kullanarak maaş ve tecrübe arasındaki doğrusal ilişkiyi incelemektedir. Bu model, belirli bir tecrübe düzeyine sahip bir çalışanın maaşını tahmin etmek için eğitilmiştir. **Sklearn** kütüphanesi kullanılarak lineer regresyon modeli oluşturulmuş ve eğitilmiştir.

## Sonuçlar

Elde edilen model, tecrübe ile maaş arasındaki ilişkiyi doğrusal bir şekilde gösterir. Tecrübe arttıkça maaş da artmaktadır, ancak bu artışın hızının sabit olup olmadığı, modelin tahminleriyle doğrulandıktan sonra daha iyi anlaşılacaktır.

### Görselleştirme

Veri setindeki her bir çalışanın maaşı ve tecrübesi, görsel olarak da sunulmuştur. Tecrübe (yıl) eksende, maaş ise dikey eksende yer almaktadır. Bu görselleştirme, ilişkiyi daha net bir şekilde gözler önüne sermektedir.

## Katkılar

Bu projeye katkıda bulunmak isterseniz, katkılarınızı pull request olarak gönderebilirsiniz.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.
