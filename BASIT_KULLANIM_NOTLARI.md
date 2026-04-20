# Basit Kullanım Notları

Bu dosya, notebook içinde veri setini ilk kez incelerken en çok kullanacağın temel komutları özetler.

## En temel komutlar

`X.head()`
İlk 5 satırı gösterir.

`X.shape`
Tablonun kaç satır ve kaç sütundan oluştuğunu verir.

`X.columns`
Kolon isimlerini verir.

`list(X.columns)`
Kolon isimlerini liste halinde daha rahat görmeni sağlar.

`X.info()`
Sütun isimleri, veri tipleri ve eksik veri durumunu toplu gösterir.

`X.dtypes`
Her kolonun veri tipini verir.

`X.describe().T`
Sayısal değişkenlerin özet istatistiklerini daha rahat okunacak şekilde verir.

`y.head()`
Hedef değişkenin ilk 5 satırını gösterir.

`dataset.target_names`
Sınıf isimlerini gösterir.

`df['target'].value_counts()`
Hedef sınıfların kaç adet olduğunu gösterir.

## Başlangıç için önerilen sıralama

1. `X.shape`
2. `X.head()`
3. `list(X.columns)`
4. `X.info()`
5. `X.describe().T`
6. `y.head()`
7. `dataset.target_names`
8. `df['target'].value_counts()`

## Kısa mantık

- `X`: özellikler
- `y`: hedef değişken
- `df`: hepsini tek tabloda görmek için birleştirilmiş hali