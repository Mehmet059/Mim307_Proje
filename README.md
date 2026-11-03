# Bakım Evi ve Sosyal Proje — 3B Dünya

Gümüşler, Denizli'deki Bakım Evi ve Sosyal Proje arazisinin interaktif 3B modeli. Proje DXF modelinden üretilmiştir: arazi, yol, su yolu ve proje kütleleri modelden gelir; ağaçlar, çimen, kayalar, gökyüzü ve uzak arazi prosedürel olarak eklenmiştir. Tek dosyadır (`index.html`, yaklaşık 4,6 MB), Three.js içine gömülüdür, internet bağlantısı veya kurulum gerekmez.

## Nasıl açılır

- `index.html` dosyasını indirip modern bir tarayıcıda (Chrome, Edge, Firefox, Safari) çift tıklayarak açın.
- GitHub Pages açıksa: https://mehmet059.github.io/Mim307_Proje/

Yükleme ekranı bittikten sonra sahne açılır. WebGL destekleyen bir cihaz yeterlidir; telefon ve tablette de çalışır.

## Gezinme modları

Sol üstteki çubuktan veya 1, 2, 3 tuşlarıyla seçilir.

- Kuş bakışı (1): sol tuş döndürür, sağ tuş kaydırır, tekerlek yakınlaştırır. Çift tıklayınca o noktada zemine inilir.
- Gezinti (2): W A S D yürür, Shift koşar, Boşluk zıplar. Fareyle bakmak için sahneye tıklayın, Esc fareyi bırakır. Duvarlardan geçilemez.
- Serbest uçuş (3): W A S D uçar, Q ve E alçalıp yükselir, Shift hızlandırır.

Telefonda sol alttaki joystick yürür, ekranı sürüklemek bakış yönünü değiştirir.

## Hazır görünümler

Genel, Proje kütleleri, Su yolu ve Plan görünümleri tek tıkla kamerayı yerleştirir. Proje kütlelerine tıklayınca yapının adı ve ölçüleri bilgi panelinde görünür. Sağ alttaki mini harita konumunuzu ve kuzey yönünü gösterir.

## Ayarlar paneli (☰)

- Zaman: saat kaydırıcısı ve Şafak, Öğle, Altın saat, Gün batımı, Gece kısayolları. Güneş konumu Denizli enlemine göre hesaplanır.
- Atmosfer: sis yoğunluğu ve rüzgâr şiddeti.
- Katmanlar: ağaçlar, çimen, su, yol, proje kütleleri vb. tek tek açılıp kapatılır.
- Kalite: Yüksek, Orta, Düşük. Yavaş cihazlarda Düşük seçin.

## Varsayımlar

- DXF dosyasında birim bilgisi yoktur, birim metre kabul edilmiştir.
- Kuzey model +Y yönündedir.
- Su yolu ve yol katmanları, arazi yüzeyine oturacak şekilde kaydırılarak yerleştirilmiştir.

## Teknik

Three.js r158, tek HTML dosyası, harici bağımlılık yok. Arazi 1 m çözünürlüklü ızgaradır, ağaçlar kart tabanlı ve instanced çizilir.
