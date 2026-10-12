# Grid ile Hizalama Çalışması

## Proje Hakkında

Bu projede CSS Grid kullanılarak üç kutudan oluşan bir yerleşim oluşturuldu. Çalışmada Grid sisteminde elemanların hücre içindeki hizalanması ve ızgaranın kapsayıcı içerisindeki konumlandırılması üzerine uygulama yapıldı.

## Kullanılan Teknolojiler

- HTML5
- CSS3
- CSS Grid

## Uygulanan Özellikler

- `display: grid` ile Grid yerleşimi oluşturuldu.
- `grid-template-columns: 1fr 1fr 1fr` ile üç sütun tanımlandı.
- `gap: 1rem` ile kutular arasına boşluk eklendi.
- `place-content: center` ile ızgaranın kapsayıcı içerisindeki konumlandırılması sağlandı.
- `min-width` ve `min-height` özellikleriyle kutuların minimum genişlik ve yükseklikleri belirlendi.
- Kutulara farklı arka plan renkleri verilerek birbirlerinden ayrılmaları sağlandı.

## Öğrenilen CSS Grid Özellikleri

- `justify-items`: Elemanları hücre içerisinde yatay eksende hizalar.
- `align-items`: Elemanları hücre içerisinde dikey eksende hizalar.
- `justify-content`: Izgarayı kapsayıcı içerisinde yatay eksende konumlandırır.
- `align-content`: Izgarayı kapsayıcı içerisinde dikey eksende konumlandırır.
- `place-items`: `align-items` ve `justify-items` özelliklerini birlikte ayarlar.
- `place-content`: `align-content` ve `justify-content` özelliklerini birlikte ayarlar.

## Proje Yapısı

- `index.html`: Kutuların HTML yapısını içerir.
- `style.css`: Grid yerleşimini, hizalama ayarlarını ve kutuların stillerini içerir.

## Amaç

CSS Grid sisteminin temel hizalama özelliklerini öğrenmek, kutuların hücre içerisindeki hizalanması ile ızgaranın kapsayıcı içerisindeki konumlandırılması arasındaki farkı anlamak ve bu özellikleri uygulamalı olarak pekiştirmek.