![Now in Android](https://github.com/hkubratkn/List-JumpToTop/blob/main/images/unnamed%20(1).png "Ira")

<a href="https://play.google.com/store/apps/details?id=com.kapirti.ira"><img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="70"></a>

# LazyColumn

## 💫LazyColumnPosition
<p align="center">
  <img src="images/ss1.jpg" width="300" />
  <img src="images/ss2.jpg" width="300" />
  <img src="images/ss3.jpg" width="300" />
  <img src="images/ss4.jpg" width="300" />
  <img src="images/ss5.jpg" width="300" />
</p>


---------------------------------------------------

## içerik dolgusu
Bazen içeriğin kenarlarına dolgu eklemeniz gerekebilir. PaddingValues Tembel bileşenler, bunu desteklemek için bazılarını contentPaddingparametreye geçirmenize izin verir :

LazyColumn(
    contentPadding = PaddingValues(horizontal = 16.dp, vertical = 8.dp),
) {
    // ...
}

16.dpBu örnekte, yatay kenarlara (sol ve sağ) ve ardından 8.dpiçeriğin üstüne ve altına dolgu ekliyoruz .

Lütfen bu dolgunun içeriğe değil, içeriğe uygulandığınıLazyColumn unutmayın . Yukarıdaki örnekte, ilk öğenin 8.dp üstüne dolgu eklenecek, son öğe 8.dpaltına eklenecek ve tüm öğelerin 16.dpsolunda ve sağında dolgu olacaktır.


## içerik aralığı
Öğeler arasına boşluk eklemek için öğesini kullanabilirsiniz Arrangement.spacedBy(). Aşağıdaki örnek 4.dp, her bir öğenin arasına boşluk ekler:
LazyColumn(
    verticalArrangement = Arrangement.spacedBy(4.dp),
) {
    // ...
}

Benzer şekilde LazyRow:
LazyRow(
    horizontalArrangement = Arrangement.spacedBy(4.dp),
) {
    // ...
}

# List

## List1                                    
<img src="/images/list1.jpg" width="260"> 

## List2                                    
<img src="/images/list2.jpg" width="260">                                   

# GridCell

## GridCellText
<img src="/images/Grid1.jpg" width="260">
