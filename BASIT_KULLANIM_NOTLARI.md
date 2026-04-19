# Basit Kullanim Notlari

Bu dosya, notebook icinde veri setini ilk kez incelerken en cok kullanacagin temel komutlari ozetler.

## En temel komutlar

`X.head()`
Ilk 5 satiri gosterir.

`X.shape`
Tablonun kac satir ve kac sutundan olustugunu verir.

`X.columns`
Kolon isimlerini verir.

`list(X.columns)`
Kolon isimlerini liste halinde daha rahat gormeni saglar.

`X.info()`
Sutun isimleri, veri tipleri ve eksik veri durumunu toplu gosterir.

`X.dtypes`
Her kolonun veri tipini verir.

`X.describe().T`
Sayisal degiskenlerin ozet istatistiklerini daha rahat okunacak sekilde verir.

`y.head()`
Hedef degiskenin ilk 5 satirini gosterir.

`dataset.target_names`
Sinif isimlerini gosterir.

`df['target'].value_counts()`
Hedef siniflarin kac adet oldugunu gosterir.

## Baslangic icin onerilen siralama

1. `X.shape`
2. `X.head()`
3. `list(X.columns)`
4. `X.info()`
5. `X.describe().T`
6. `y.head()`
7. `dataset.target_names`
8. `df['target'].value_counts()`

## Kisa mantik

- `X`: ozellikler
- `y`: hedef degisken
- `df`: hepsini tek tabloda gormek icin birlestirilmis hali