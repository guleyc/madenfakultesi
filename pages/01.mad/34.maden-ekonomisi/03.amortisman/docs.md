---
title: Amortisman
twitterenable: true
twittercardoptions: summary
articleenabled: false
musiceventenabled: false
orgaenabled: false
orga:
    ratingValue: 2.5
orgaratingenabled: false
eventenabled: false
personenabled: false
musicalbumenabled: false
productenabled: false
product:
    ratingValue: 2.5
restaurantenabled: false
restaurant:
    acceptsReservations: 'yes'
    priceRange: $
---

## Temel Kabuller
1. Amortisman Matrahı (M): Sabit varlığın elde edilmesi için yapılan tüm ödeme ve giderlerdir.
2. Hurda değer (H): Sabit varlığın kullanım süresinin sonunda taşıdığı maddi değer.
3. Amortisman Dönemi (n): Sabit değerin kullanım süresi
4. Amortisman Oranı (r): Amortisman oranının belirlenebilmesi için kullanılan oran.

### Amortisman
Yatırım dönemlerinde alınan sabit varlıkların hesap dönemlerinde hizmet yoğunluklarına ve sürelerine bağlı olarak giderlerinin belirlenmesine amortisman denir.
#### Amortisman Sebepleri
1. Fiziksel: Kullanım kaynaklı eskime ve yıpranmadır.
2. İşlevsel: Teknolojik eskime veya zamanla yetersiz hale gelmeden kaynaklanan amortismandır.
#### Amortisman Yöntemleri
1. Normal (Doğrusal) Amortisman
2. Azalan Bakiyeler Üzerinden Amortisman
3. Tükenme (Madencilik) Amortismanı

### Normal (Doğrusal) Amortisman
Sabit varlığın maliyeti ömrüne eşit olarak yıllara göre dağıtılır. Bu durumda yıllık amortisman tutarı (A);
$$
\begin{array}{l}A=\frac{M-H}n\\r=\frac1n\end{array}
$$

Örneğin 5 yıl sonra 20000 TL'den satılabilecek bir makine 320000 TL'ye alındı ise, yıllara göre amortisman değeri normal amortisman tekniğine göre aşağıdaki şekilde bulunur.

| **Yıllar** | **Amortismana Tabii Miktar** | **Amortisman Oranı** | **Amortisman Tutarı** |
| ------ | ------------------------ | ---------------- | ----------------- |
| 1 | 300000 | 0.2 | 60000 |
| 2 | 300000 | 0.2 | 60000 |
| 3 | 300000 | 0.2 | 60000 |
| 4 | 300000 | 0.2 | 60000 |
| 5 | 300000 | 0.2 | 60000 |
| **Hurda Değeri** | | | 20000 |
| **Toplam** | | | 320000 |

### Azalan Bakiyeler Üzerinden Amortisman
Sabit varlığın maliyeti ilk yıllarda yüksek devam eden yıllarda ise düşük oranlarda dağıtılır.
* Her yıl amortismana esas olan değer bir önceki yıla ait amortisman değerinden çıkartılarak bulunur.
* Amortisman oranı %40'ı geçmemek üzere normal amortisman oranının iki katıdır.
* Amortisman süresi normal amortisman süresi ile aynıdır.
* Sürenin son yılına devreden bakiyeler o yıl tamamen tükenir.

Bir önceki örneği bu yöntem ile tekrar değerlendirirsek, aşağıdaki tablo elde edilir.

| **Yıllar** | **Amortismana Tabii Miktar** | **Amortisman Oranı** | **Amortisman Tutarı** |
| ------ | ------------------------ | ---------------- | ----------------- |
| 1 | 300000 | 0.4 | 120000 |
| 2 | 180000 | 0.4 | 72000 |
| 3 | 108000 | 0.4 | 43200 |
| 4 | 64800 | 0.4 | 25920 |
| 5 | 38880 |  | 38880 |
| **Hurda Değeri** | | | 20000 |
| **Toplam** | | | 320000 |

### Tükenme Amortismanı (Madenlerde Amortisman)
İki farklı yöntem ile sonuca ulaşılır;
1. Maliyet Yönetimi
2. Yüzde Yönetimi

#### Maliyet Yönetimi
$$
yillik\;tukenme\;musadesi\;=\;yil\;boyunca\;uretilen\;cevher\;miktari\;\times\frac{tukenme\;baz\;degeri}{yil\;ba\sin daki\;rezerv}
$$

$$
tukenme\;baz\;degeri\;=\;yatirim\;degeri\;-\;toplam\;tukenme\;musadesi
$$

Maliyet yöntemi bir örnekle açıklanmak istenirse;
* Maden: Bakır
* Rezerv: 4.5 milyon ton
* İlk Yıl Üretim: 600000 ton
* Yatırım tutarı: 2340000 USD

* Cevher İçin Yatırım: 1440000 USD
* Araştırmalar İçin Yatırım: 600000 USD
* Diğer: 300000 USD

Bu verilere göre bakır yatağının yıllara göre tükenme amortismanını bulalım.

İlk Yıl Tükenme Müsadesi;
$$
600000\times\frac{2340000}{4500000}=312000\;USD
$$

İlk Yıl Sonundaki Tükenme Baz Değeri;
$$
2340000-312000=2028000\;USD
$$

İkinci Yıl Tükenme Müsadesi;

$$
ikinciyilda\;tukenme\;musadesi\;=\;ikinciyilda\;uretilen\;cevher\;miktari\;\times\frac{2028000}{3900000}
$$

**Yüzde Yönetimi**
Aşağıda verilen iki değerin hesaplanarak küçük olanın seçilmesi ile gerçekleştirilir.
1. Brüt gelirin belirli bir yüzdesi, üretilen cevherin tipine göre seçilir.
2. Vergi ve amortisman öncesi gelirin %50'si

**Sonuç**
* Bu durumda bakır madeninin 1. yıldaki tkenme amortismanı değer olarak; 1150000 USD (>312000 USD) seçilir.