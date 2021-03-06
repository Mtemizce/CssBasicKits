# **Fihrist:**
**1.** [Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#-margin-ve-padding-tan%C4%B1mlamalar%C4%B1-)
   - [Toplam Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#toplam-margin-ve-padding-kullan%C4%B1m%C4%B1)
   - [Dikey Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#dikey-margin-ve-padding-kullan%C4%B1m%C4%B1)
   - [Yatay Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#yatay-margin-ve-padding-kullan%C4%B1m%C4%B1)
   - [Top Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#top-margin-ve-padding-kullan%C4%B1m%C4%B1)
   - [Right Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#right-margin-ve-padding-kullan%C4%B1m%C4%B1)
   - [Bottom Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#bottom-margin-ve-padding-kullan%C4%B1m%C4%B1)
   - [Left Margin ve Padding](https://github.com/Mtemizce/CssColors/blob/master/README.md#left-margin-ve-padding-kullan%C4%B1m%C4%B1)
   
**2.** [CSS Renkler](https://github.com/Mtemizce/CssColors/blob/master/README.md#css-renkler)
   - [Yazı Örnek](https://github.com/Mtemizce/CssColors/blob/master/README.md#yaz%C4%B1-%C3%96rnek)
   - [Arkaplan Örnek](https://github.com/Mtemizce/CssColors/blob/master/README.md#arkaplan-%C3%96rnek)
   - [Koyu ve açık ton renk uygulaması](https://github.com/Mtemizce/CssColors/blob/master/README.md#koyu-ve-a%C3%A7%C4%B1k-ton-renk-uygulamas%C4%B1)
   - [Renk Listesi](https://github.com/Mtemizce/CssColors/blob/master/README.md#renk-listesi-ve-tan%C4%B1mlamalar)
   

# **Margin ve Padding Tanımlamaları**
[Css dosyası için tıkla](mar-pad.css)<br>
Çoğumuz bootstrap gibi css framework kullanma taraftarı olsakta bi yanımız kendi framework hayalini kurar. Bazılarımızda bunun çok zaman alıcı olduğunu düşünerek vazgeçer. Vaktinizi almaması için hazır hali ile css şeklinde paylaştım umarım faydalı olur.

**Verilen sayısal değerler şu şekilde:** 0-5-10-15-20-30-40-50-60<br>
4 tip kullanımı mevcut. **Toplam**, **Yatay**, **Dikey** ve **Top**, **Right**, **Bottom** ve **Left** şeklinde ayrı ayrı uygulamalar.<br>

> ### **Margin ve Padding Sıfırlama:**
 **Margin için sıfırlama şu şekilde:**
 ```
 <div class="mar-0">Margin sıfırlandı</div>
 ```
 **Önemli!**
 Bunu uyguladığınız öğe otomatik olarak sola yapışır. Öğenin ortalanmış halde kalmasını istiyorsanız [mar-pad.css](mar-pad.css) dosyasındaki aşağıdaki kodu bulun:
 ```
 .mar-0 {margin: 0px !important;}
 ```
 **Şununla Değiştirin:**
 ```
 .mar-0 {margin: 0 auto !important;}
 ```
 **Padding için sıfırlama şu şekildedir:**
  ```
   <div class="pad-0">Padding sıfırlandı</div>
 ```
  
> ### **Toplam Margin ve Padding kullanımı:**
 ```
 <div class="mar-5">Toplam 5px Margin Uygulandı</div>
 <div class="pad-5">Toplam 5px Padding Uygulandı</div>
```

> ### **Dikey Margin ve Padding kullanımı:**
 ```
 <div class="mar-y-10">Dikey 10px Margin Uygulandı</div>
 <div class="pad-y-10">Dikey 10px Padding Uygulandı</div>
```

> ### **Yatay Margin ve Padding kullanımı:**
 ```
 <div class="mar-x-15">Yatay 15px Margin Uygulandı</div>
 <div class="pad-x-15">Yatay 15px Padding Uygulandı</div>
```

> ### **Normal Margin ve Padding kullanımı:**
 Margin ve Padding i tek yönde de kullanabilirsiniz. Bunun için aşağıdaki örnekleri inceleyin.
 
> ### **Top Margin ve Padding kullanımı:**
 ```
 <div class="mar-t-20">Margin Top 20px Uygulandı</div>
 <div class="pad-t-20">Padding Top 20px Uygulandı</div>
```
> ### **Right Margin ve Padding kullanımı:**
 ```
 <div class="mar-r-30">Margin Right 30px Uygulandı</div>
 <div class="pad-r-30">Padding Right 30px Uygulandı</div>
```
> ### **Bottom Margin ve Padding kullanımı:**
 ```
 <div class="mar-b-40">Margin Bottom 40px Uygulandı</div>
 <div class="pad-b-40">Padding Bottom 40px Uygulandı</div>
```
> ### **Left Margin ve Padding kullanımı:**
 ```
 <div class="mar-l-50">Margin Left 50px Uygulandı</div>
 <div class="pad-l-60">Padding Left 60px Uygulandı</div>
```

# **Css Renkler:**
[Css dosyası için tıkla](color.css)<br>
Kendi projelerimde kullanmak için less olarak hazırlayıp css compile etmiştim ama fazla bu işe vakit ayrırmak istemeyen arkadaşlarımız için css compile halini paylaşıyorum. Zor değil herkesin yapabileceği şeyler ama olur ya uğraşmak istemeynde çıkabilir.<br>
Renkleri Normal, 20% Koyu ve 10% Açık olarak 3 kısma ayırdım. Yazı ve Arkaplan olarak 2 kısımdır.<br>
Yazı olarak kullanmak için class kısmına txt-(renk ismi)<br>
Arkaplan olarak kullanmak için class içerisine bg-(renk ismi)<br> 

> ### **Yazı Örnek:**
```
<div class="txt-yellow">Sarı Renkli Yazı</div>
```

> ### **Arkaplan Örnek**
```
<div class="bg-yellow">Sarı Arkaplanlı</div>
```

> ### **Koyu ve açık ton renk uygulaması**
```
<div class="txt-dark-yellow">Koyu Sarı Yazı</div>
<div class="txt-light-yellow">Açık Sarı Yazı</div>
<div class="bg-light-yellow">Açık Sarı Arkaplan</div>
<div class="bg-dark-yellow">Koyu Sarı Arkaplan</div>
```

> ### **Renk Listesi ve Tanımlamalar**
 Renkler ve Hex kodları
 - Red:		#FF0000
 - Blue:		#0000FF
 - Orange:	#FFA500
 - Yellow:	#FFFF00
 - Black:	#000000
 - White:	#FFFFFF
 - Gray:		#808080
 - Green:	#008000
 - Purple:	#800080
 - Olive:	#556B2F
 - Begie:	#F5F5DC
 - Pink:		#FFC0CB
 - Indigo:	#6574CD
 - Teal:		#4DC0B5
 - Brown:	#5D4037
 - Bluegray:	#78909c
 
**Kodu parçalara bölerek tanımlayacak olursak:**
 .txt <- Yazı başlangıcı
 .bg <- Arkaplan başlangıcı
 -dark <- Koyu tanımlama
 -light <- açık tanımlama
 -(renkismi) <-Renk tanımlama
 
 **Örnek:**
 .txt-dark-brown <- Koyu Kahverengi Yazı
 .bg-light-pink <- Açık Pembe Arkaplan <br>
 
 **Html Kullanımı:**
 ```
 <div class="txt-white bg-red">Beyaz Yazı ve Kırmızı Arkaplan</div>
 ```
 **Yazıların class isimleri şu şekilde:**
 - -red
 - -blue
 - -orange
 - -yellow
 - -black
 - -white
 - -gray
 - -green
 - -purple
 - -olive
 - -begie
 - -pink
 - -indigo
 - -teal
 - -brown
 - -bluegray
 
 Esasında arkaplana zıt renkler üzerinde çalışıp tek class ile arkaplan ve ona uyumlu text rengini tanımlamak daha az yer kaplar (Örn:.red(background-color: red; color: white;) gibi) ve daha az kod elde ederiz. Fakat bu sonuçta tasarımdaki komple renk uyumu ile alakalı bir durum. Bunun içinde benim vaktim yok. İlerleyen zamanlarda geliştirilebilir. Belki bunun ile alakalı fonksiyon bile yazılabilir. öğeye atadığınız arkaplanı algılayıp zıt txt rengini class olarak ekleyen fonksiyonlar düşünülebilir.
