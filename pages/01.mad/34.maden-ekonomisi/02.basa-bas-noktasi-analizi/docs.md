---
title: 'Başa Baş Noktası Analizi'
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

**Başa Baş Noktası:** İşletmenin gelir v e giderlerinin eşit olduğu diğer bir deyişle karının 0 olduğu noktaya başabaş noktası denir.

Başa baş noktası analiz yönetmleri
* Geleneksel
* Lineer
* Nonlineer

**Kullanım Yerleri**
* Gider-Kar ilişkilerinin tayininde
* Üretim düzeyi-Gider ilişkilerinin tayininde
* Birim satış fiyatı-Kar arası ilişkinin tayininde
* Kar ile üretim hacmi arasındaki ilişkinin tayininde
* Kara geçebilmek için gerekli ürün fiyatının tespitinde
* Birden fazla ürünün üretildiği işlemelerde en karlı ürünün tayininde

**Geleneksel Başa Baş Noktası Analizi**
* Üretim miktarı belirlenmelidir
* Gider ve gelir eğrileri lineerdir
* Maliyetler sabit ve değişken olarak ayrılabilir
* Sabit maliyetler değişmez
* Birim değişken giderler sabittir
* Stoklar hesaba katılmaz ihmal edilebilir niteliktedir
* Hammadde işçilik ve benzeri kalemlerin maliyetleri sabittir
* Üretim verimliliği sabittir

## Matematiksel Yöntem
* SG=Sabit Gider
* DG=Değişken Gider
* d=Birim Değişken Gider
* b=Birim Satış Fiyatı
* Q=Üretim Miktarı
* G=Gelir
* TG=Toplam Gider
* K=Kar

$$
G=Q\times b
$$

$$
TG=Q\times b+SG
$$

$$
K=G-TG=Q\times\left(b-d\right)-SG
$$

**Üretilecek Mal Mitarı Açısından**
$$
Q=\frac{SG}{b-d}
$$

**Satış Geliri Açısından**
$$
R=\frac{SG}{1-{\displaystyle\frac{DG}G}}
$$
(R=Başa baş noktasındaki satış geliri)

**Kapasite Kullanım Oranı Açısından**
$$
Kapasite\;Yüzdesi\;=\frac{SG}{bQ-dQ}
$$

**Amaçlanan Kar Miktarına Göre**
$$
Q_{kar}=\frac{K+SG}{b-d}
$$

**Gelir Vergisinin Hesaba Dahil Edilmesi**
$$
y=\frac z{1-t}
$$
(y=vergiden önceki kar
t=vergi oranı
z=vergiden sonraki kar)

**Örnek 1**
İşletmenin toplam sabit gideri 10.000 TL, birim değişken gideri ise 600 TL/br, satış fiyatı 1000 TL/br'dir.
**a)** Başa baş noktasına ulaşmak için satılması gereken ürün miktarı ne olmalıdır? 
**b)** Başa baş noktasındaki satış geliri ne olmalıdır?

**Çözüm 1**

* SG=10000TL
* d=600TL/br
* b=1000TL/br

**a)**
$$
Q=\frac{SG}{b-d}
$$

$$
Q=\frac{10000}{1000-600}
$$

Q=25 m^3

**b)**
$$
R=\frac{SG}{1-{\displaystyle\frac{DG}G}}
$$

$$
R=\frac{10000}{1-{\displaystyle\frac{600\times25}{1000\times25}}}
$$

R=25000TL

**Örnek 2**
İşletemeye ait aşağıdaki bilgiler verilmiştir.
* Elektrik: 100 TL/m^3
* Mazot ve Yağ: 500 TL/m^3
* Lastik ve Yedek Parça: 400 TL/m^3
* Patlayıcı Madde: 300 TL/m^3
* Diğer Değişken Giderler: 200 TL/m^3
* Amortisman, Faiz ve Sigorta: 1500000 TL/yıl
* Personel: 500000 TL/yıl
* Diğer Sabit Giderler: 125000 TL/yıl

* Gelir: 4000 TL/m^3
* Üretim Kapasitesi: 1500000 m^3/yıl

**a)** Başa baş noktasını üretim miktarı olarak bulunuz.
**b)** Firmanın yıllık karının 500000TL/yıl kara ulaşması için gerekli üretim miktarını bulunuz.

**Çözüm 2**
* d= 100+500+400+300+200 = 1500 TL/m^3
* b= 4000 TL/m^3
* SG= 1500000+500000+125000 = 2250000 TL/yıl
* Üretim Kapasitesi: 1500000 m^3/yıl

**a)**
$$
Q=\frac{SG}{b-d}
$$

$$
Q=\frac{2250000}{4000-1500}
$$
=900 m^3

**b)**
$$
Q_{kar}=\frac{K+SG}{b-d}
$$

$$
Q_{kar}=\frac{500000+2250000}{4000-1500}
$$
=1100 m^3

**Örnek 3**
Aşağıdaki koşullar altında işletme 1000 ton kömür satışından 70000 TL kar elde etmektedir. İşletmenin hedeflenen kar üzerinden %30 gelir vergisini ödedikten sonra hedeflediği kara ulaşması için gerekli üretimi ne olmalıdır?
* b= 150 TL/ton
* d= 50 TL/ton
* SG= 30000 TL

**Çözüm 3**
$$
y=\frac z{1-t}
$$
$$
y=\frac 70000{1-0.3}
$$
=100000TL
K=100000TL ise

$$
Q_{kar}=\frac{K+SG}{b-d}
$$

$$
Q_{kar}=\frac{100000+30000}{150-50}
$$
=1300 ton