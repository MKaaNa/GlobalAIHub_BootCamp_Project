# IMDB 50K Movie Reviews: Algoritma Karşılaştırması

Bu projede, IMDB 50K Movie Reviews veri seti üzerinde iki farklı öğrenme algoritması kullanılmıştır: **Lojistik Regresyon** ve **KMeans Kümeleme**. Her iki algoritma da veri seti üzerinde test edilmiştir ve performansları değerlendirilmiştir.

## Lojistik Regresyon

Lojistik Regresyon, gözetimli öğrenme algoritmasıdır ve iki sınıflı sınıflandırma problemleri için oldukça etkilidir. Bu projede, incelemelerin olumlu veya olumsuz olduğunu tahmin etmek için kullanılmıştır.

- **Doğruluk (Accuracy):** 89.68%
- **Karışıklık Matrisi:** Model, olumlu ve olumsuz incelemeleri yüksek doğrulukla sınıflandırmıştır. Detaylar için Kaggle defterinde bulunan karışıklık matrisine bakılabilir.


## KMeans Kümeleme

KMeans, gözetimsiz öğrenme algoritmasıdır ve veriyi kümelere ayırmak için kullanılır. Bu algoritma, etiketlenmemiş veriler üzerinde çalışır ve veri içindeki doğal yapıları keşfetmeyi amaçlar. Ancak, KMeans genellikle etiketli veri setleriyle sınıflandırma problemlerinde sınırlı performans gösterir.

- **Silhouette Skoru:** 0.0045

## Sonuç ve Uygunluk

Veri setimiz, metin verilerini içermekte olup, **Lojistik Regresyon** gibi gözetimli öğrenme algoritmaları için daha uygun bir yapıya sahiptir. Lojistik Regresyon, etiketlenmiş verilerle yüksek doğruluk elde ederken, KMeans gibi gözetimsiz algoritmalar, etiketlenmemiş veri üzerinde kümeleri ayırma konusunda sınırlı performans sergileyebilir.

Bu nedenle, **Lojistik Regresyon**, bu veri seti için daha uygun bir algoritma olarak değerlendirilmiştir. KMeans, veri kümesinin doğal yapısını anlamak için kullanılabilir, ancak sınıflandırma performansını değerlendirmek için yeterli verimlilik sağlamamıştır.

## Kaynaklar

- [IMDB 50K Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- [Projenin Kaggle Linki](https://www.kaggle.com/code/musakaanaltin/imdb-film-ncelemeleri-g-zetimli-ve-g-zetimsiz/notebook)

