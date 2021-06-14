# Harum Manis Tree

buatlah class yang memiliki property yang sama dengan MangoTree.   
perlu diperhatikan bahwa HarumManisTree menghasilkan buah MangoHarumManis pada produceFruits

# Mango Tree Grove

buatlah class yang bernama MangoTreeGrove denga properti mangoTrees berupa array yang akan di isi oleh instance. 


Terdapat Method : 
- inputTree(name, age, height, matureAge, healthStatus)  
  akan mengisi trees pada MangoTreeGrove sehingga isi dari properti mangoTreess adalah array of instance MangoTree atau HarumManisTree.  
- nextYear()  
  akan menambahkan umur dari pohon-pohon pada properti mangoTrees dengan menggunakan method yang telah tersedia pada HarumManisTree/MangoTree.  
- showAboveAverageHeight()  
  Menampilkan `nama pohon, umur dan tinggi` yang memiliki tinggi diatas rata-rata.  

```js
let grove = new MangoTreeGrove()
// input your trees data !
// parameter ke-1: nama pohon
// parameter ke-2: umur pohon ketika ditanam di taman tersebut
// parameter ke-3: tinggi pohon pertama kali ketika ditanam di taman tersebut
// parameter ke-4: umur mature pohon tersebut
// parameter ke-5: healthyStatus dari pohon tersebut ketika ditanam
grove.inputTree("HarumManisTree", 5, 2.4, 12, false)
grove.inputTree("MangoTree", 4, 1.2, 5, true)
grove.inputTree("MangoTree", 3, 1.8, 7, false)
grove.inputTree("HarumManisTree", 7, 2, 15, true)


grove.showAboveAverageHeight()  


grove.nextYear()
```
