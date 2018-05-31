---
title: 'Faiz Hesapları'
media_order: 'nakitakisornek.png,esdegerlilikornek.png'
twitterenable: false
twittercardoptions: summary
articleenabled: false
orgaenabled: false
orga:
    ratingValue: 2.5
orgaratingenabled: false
facebookenable: false
---

### Faiz
Bir zaman dilimi sonunda para miktarında meydana gelen artışa faiz denir. Faiz = Günümüzde Geri Ödenen Miktar - İlk Borç

#### Faiz Oranı
Faiz Oranı (%) = Birim Zamanda Gerçekleşen Faiz*100 / İlk Miktar

#### Örnek
Bir yıl önce bugün 10000 TL olarak bankaya yatırılan miktar, bugün 11750 TL olarak geri alınmıştır. Faiz miktarını ve oranını yıllık bazda bulunuz.

Faiz = 11750 - 10000 = 1750 TL

FO= 1750*100/10000 = 17,5%

### Eşdeğerlilik
Paranın farklı zamanlardaki miktarlarının faiz ve/veya enflasyon değerlerinde hareket ederek eşitlenmesidir.

![](esdegerlilikornek.png)

### Basit Faiz Hesapları
Daha önce gerçekleşen faiz değerlerini dikkate almadan, sadece ana para üzerinden gerçekleştirilen faiz hesaplarına basit faiz denir.

Basit Faiz = Ana Para * Peryod Sayısı * Faiz Oranı

#### Örnek
5 yıllığına yılda %12 faiz oranı ile alınan 25000 TL borcun beş yıl sonraki ödemesi ne kadar olur?

Ödeme = 25000*5*0,12+25000 = 40000 TL

| Yıl Sonu | Alınan Borç | Faiz Miktarı | Borç Miktarı | Ödeme |
| ----- | ----- | ----- | ---- | ---- |
| 0 | 25000 | - | - | - |
| 1 | - | 3000 | 28000 | - |
| 2 | - | 3000 | 31000 | - |
| 3 | - | 3000 | 34000 | - |
| 4 | - | 3000 | 37000 | - |
| 5 | - | 3000 | 40000 | 40000 |

### Bileşik Faiz
Paranın zaman değeri dikkate alınarak gerçekleştirilen faiz hesaplarına denir. Her yıl için faiz hesaplanırken, bir önceki yıl için ana para + faiz miktarından elde edilen değer dikkate alınır.

#### Örnek
5 yıllığına yılda %12 bileşik faiz oranı ile alınan 25000 TL borcun beş yıl sonraki ödemesi ne kadar olur?

| Yıl Sonu | Alınan Borç | Faiz Miktarı | Borç Miktarı | Ödeme |
| ----- | ----- | ----- | ---- | ---- |
| 0 | 25000 | - | - | - |
| 1 | - | 3000 | 28000 | - |
| 2 | - | 3360 | 31360 | - |
| 3 | - | 3763 | 35123 | - |
| 4 | - | 4215 | 39338 | - |
| 5 | - | 4721 | 44059 | 44059 |

#### Bileşik Faiz Hesaplamaları

Kullanılan notasyonlar;
i: dönemlik faiz oranı, n: dönem sayısı, P: paranın bugünkü değeri, F: paranın gelecek zamandaki değeri, A: dönem sonu ödemeler

##### Örnek
Günümüzde 75000 TL olarak yılda %20 faizle alınan bir paranın 5 yıl sonraki ödemesi ne kadar olur?

P = 75000 TL
i = 20% - YIL
n = 5 YIL
A = 0 ise F=?

F= 75000*0,2*5*75000 = 150000 TL

### Nakit Akış Diyagramları
Net Nakit Akışı = Gelirler - Giderler

#### Örnek
Günümüzde 75000 TL olarak yılda %20 faizle alınan bir paranın 5 yıl sonraki ödemesi ne kadar olur sorusuna ait diagramı çizin.

![](nakitakisornek.png)

## Bileşik Faiz Faktörleri ve Kullanımları

1) Tek Ödeme Bileşik Değer Formülleri

Aşağıda verilen formül bugünkü değeri P olan ve n sene boyunca i oranından faize yatırılan paranın n sene sonraki F değerini bulmada kullanılır.

$ F=P\ast(1+i)^n $