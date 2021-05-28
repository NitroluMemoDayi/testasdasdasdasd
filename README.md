# Merhabalar! Valoranttaki haritaları güncel ve Türkçe olarak gösteren modüle hoşgeldiniz!

##### Harita verilerini çekme
````js
const valorant = require('valorant-harita')
(async() => {
let veri = await valorant.haritaBul('breeze')
console.log(veri) // harita hakkındaki verileri atar
console.log(veri.fotograflar) // haritanın fotoğraflarını array halinde gönderir
})()
````

##### Breeze haritası için örnek çıktı
````js
{
  id: 'breeze',
  numara: '6',
  isim: 'Breeze',
  fotograflar: [ [ [Object] ] ],
  bilgiler: {
    hakkinda: "Bu tropik cennetteki tarihi yıkıntıları ve deniz kenarındaki mağaraları keşfe çıkın. Ama arkanızı kollayacak ajanlara ihtiyacınız var. Açık alanlarda ve uzun menzilli çatışmalarda buna ihtiyacınız olacak. Dikkati elden bırakmadığınız sürece Breeze'de su akar, yolunu bulur.", 
    kordinatlar: {
    "lokasyon":"25°00'00.0K 71°00'00.0B",
    "bolge": "Atlantik Okyanusu"
    },
    callouts: [ [Array] ]
  }
}
````
# Turkish: Bu modül **https://bit.ly/valorant-fetch** modülünün Türkçe versiyonudur.
# English: This module is the Turkish version of the **https://bit.ly/valorant-fetch** module.

## Log

##### 1.0.0 Modül paylaşıldı.
##### 1.0.1 README kısmı eklendi ve modül güncellendi.
##### 1.0.2 JSON'daki bazı buglar düzeltildi.
##### 1.0.3 README'deki eksik kısımlar düzeltildi.
##### 1.0.4 JSON'da bazı gereksiz kısımlar kaldırıldı.
##### 1.0.5 README'ye modülün İngilizce hali eklendi.
