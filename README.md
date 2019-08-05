# tezlatex
## Tekirdağ Namık Kemal Üniversitesi Fen Bilimleri Enstitüsü için Latex tez yazım şablonu..

### İndirilecek programlar

- Miktex dağıtımı https://miktex.org/download (ilk kurulacak) (veya başka dağıtım, ama testler Miktex ile yapıldı) 
- Texstudio editörü https://www.texstudio.org/ (ikinci kurulacak) (veya başka sevdiğiniz bir editör) 

### Ayarlar
- Texstudio'da "Bibliography" "biber" olarak ayarlanmalıdır.
- Texstudio --> Configure Texstudio -->  Options --> Build --> Default Bibliography Tool --> biber

### Bu sitedeki dosyaları indirme
 - Sağ üstte "Clone or download" dan "Download ZIP" seçilir. (ya da tıklayınız --> https://github.com/tgurel/tezlatex/archive/master.zip)
 - tezlatex-master.zip dosyası indirilir ve "tezim" klasörü sıkıştırılmış dosyadan bilgisayarınıza çıkarılır.

### Tez yazımı

Texstudio ile ilgili .tex dosyaları düzenlenerek tez yazılır.


### İlgili .tex dosyaları

* **tezim.tex : Burada**
   * Adınız Soyadınız, mesleğiniz
   * tez danışmanınız, varsa ikinci danışmanınız
   * tez savunma tarihi
   * jüri ad soyad **bilgileri girilecektir.**
   * Ayrıca "apa" ya da "IEEE" referans stili seçilecektir.
   * Tezin içeriğini bu dosyaya yazılır. (ya da "\input bolumx.tex" kullanarak bolumleri ayrı dosyalara da yazabilirsiniz.)
* **ozet.tex**
   * özetinizi bu dosyaya yazmalısınız.
* **summary.tex**
   * ingilizce özetinizi bu dosyaya yazmalısınız.
* **simge_ve_kisaltmalar.tex**
   * simge ve kısaltmalarınızı bu dosyada tablo halinde vermelisiniz.
* **tesekkur.tex**
* **ozgecmis.tex**
