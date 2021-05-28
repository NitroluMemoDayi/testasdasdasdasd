# Merhabalar! Valoranttaki haritaları güncel ve Türkçe olarak gösteren modüle hoşgeldiniz!

##### Harita verilerini çekme
````js
const valorant = require('valorant-harita')
(async() => {
let veri = await valorant.haritaBul('breeze')
console.log(data) // harita hakkındaki verileri atar
console.log(data.fotograflar) // haritanın fotoğraflarını array halinde gönderir
})()
````

##### Breeze haritası için örnek çıktı
````js
{
  id: 'split',
  numara: '4',
  isim: 'Split',
  fotograflar: [ [ [Object] ] ],
  bilgiler: {
    hakkinda: 'Uzağa kaçmak istiyorsan yukarı gitmen lazım. Birkaç farklı bölgenin tam ortasında 
yükselen merkez noktası, iki tane yükseltici halat yardımıyla hızlı bir şekilde hareket etme imkânı tanıyor. Her bir bölgede kontrolü sağlayabilmek için hayati öneme sahip iki dev kule bulunuyor. Gözün göklerden gelebilecek tehlikelerde olsun.',
    kordinatlar: [ "35°41'K139°41'D", 'Japonya' ],
    callouts: [ [Array] ]
  }
}
````
