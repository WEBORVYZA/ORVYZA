<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ORVYZA Web Studio | İşletmenize Özel Web Sitesi</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0b1020;
    color:white;
}

/* MENÜ */

nav{
    width:100%;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:fixed;
    top:0;
    z-index:1000;
    background:rgba(11,16,32,.95);
    border-bottom:1px solid #252d45;
}

.logo{
    font-size:24px;
    font-weight:bold;
    color:#00d4ff;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-size:15px;
}

/* ANA SAYFA */

.hero{
    min-height:100vh;
    padding:150px 10% 80px;
    display:flex;
    align-items:center;
    text-align:center;
    justify-content:center;
    background:
    radial-gradient(circle at top right,#163d69,transparent 35%),
    radial-gradient(circle at bottom left,#172e57,transparent 35%);
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-size:55px;
    margin-bottom:20px;
}

.hero h1 span{
    color:#00d4ff;
}

.hero p{
    font-size:20px;
    line-height:1.7;
    color:#c9d2e3;
    margin-bottom:35px;
}

.btn{
    display:inline-block;
    padding:16px 28px;
    background:#00d4ff;
    color:#07101f;
    text-decoration:none;
    font-weight:bold;
    border-radius:10px;
    margin:8px;
}

/* GENEL BÖLÜM */

section{
    padding:90px 10%;
}

.title{
    text-align:center;
    margin-bottom:50px;
}

.title h2{
    font-size:36px;
    color:#00d4ff;
}

.title p{
    color:#aeb9cc;
    margin-top:12px;
}

/* HİZMETLER */

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
    gap:25px;
}

.card{
    background:#121a2e;
    padding:30px;
    border-radius:15px;
    border:1px solid #26314b;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
    border-color:#00d4ff;
}

.card h3{
    margin-bottom:15px;
    color:#00d4ff;
}

.card p{
    color:#c3cbd9;
    line-height:1.6;
}

/* QR */

.qr-section{
    text-align:center;
    background:#10182b;
}

.qr-box{
    max-width:650px;
    margin:auto;
    background:#151f36;
    padding:40px;
    border-radius:20px;
}

.qr-icon{
    font-size:90px;
    margin:20px;
}

.qr-box p{
    color:#c6cfdd;
    line-height:1.8;
}

/* NASIL ÇALIŞIYOR */

.steps{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.step{
    text-align:center;
    padding:25px;
    background:#121a2e;
    border-radius:15px;
}

.number{
    width:50px;
    height:50px;
    margin:auto auto 15px;
    border-radius:50%;
    background:#00d4ff;
    color:#07101f;
    display:flex;
    align-items:center;
    justify-content:center;
    font-weight:bold;
    font-size:20px;
}

/* HAKKIMIZDA */

.about{
    background:#10182b;
}

.about-box{
    max-width:800px;
    margin:auto;
    text-align:center;
    line-height:1.8;
    color:#c5cedd;
}

.names{
    margin-top:30px;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
}

.person{
    background:#17233d;
    padding:20px 35px;
    border-radius:12px;
}

.person h3{
    color:#00d4ff;
}

/* İLETİŞİM */

.contact{
    text-align:center;
}

.phone{
    display:inline-block;
    margin:12px;
    padding:18px 25px;
    border-radius:12px;
    background:#151f36;
    color:white;
    text-decoration:none;
    font-size:20px;
    border:1px solid #26314b;
}

.phone:hover{
    border-color:#00d4ff;
}

.whatsapp{
    background:#00d4ff;
    color:#07101f;
    font-weight:bold;
}

/* FOOTER */

footer{
    text-align:center;
    padding:30px;
    background:#070b15;
    color:#8f9bb0;
}

/* MOBİL */

@media(max-width:700px){

nav{
    padding:18px 5%;
}

nav ul{
    display:none;
}

.hero h1{
    font-size:38px;
}

.hero p{
    font-size:17px;
}

section{
    padding:70px 6%;
}

}
</style>
</head>

<body>

<!-- MENÜ -->

<nav>

<div class="logo">SG WEB STUDIO</div>

<ul>
<li><a href="#anasayfa">Ana Sayfa</a></li>
<li><a href="#hizmetler">Hizmetler</a></li>
<li><a href="#qr">QR Kod</a></li>
<li><a href="#hakkimizda">Hakkımızda</a></li>
<li><a href="#iletisim">İletişim</a></li>
</ul>

</nav>


<!-- ANA SAYFA -->

<section class="hero" id="anasayfa">

<div class="hero-content">

<h1>İşletmenizi <span>Dijitale Taşıyoruz</span></h1>

<p>
İşletmenize özel modern web siteleri, mobil uyumlu tasarımlar
ve QR kod çözümleri hazırlıyoruz.
Müşterileriniz kameralarını QR koda okuttuğunda
sizin web sitenize veya istediğiniz dijital sayfaya
kolayca ulaşabilir.
</p>

<a class="btn" href="#iletisim">Hemen İletişime Geç</a>

<a class="btn" href="#hizmetler">Hizmetlerimizi Gör</a>

</div>

</section>


<!-- HİZMETLER -->

<section id="hizmetler">

<div class="title">

<h2>Hizmetlerimiz</h2>

<p>İşletmeniz için ihtiyacınız olan dijital çözümler</p>

</div>


<div class="cards">

<div class="card">

<h3>🌐 Web Sitesi Tasarımı</h3>

<p>
İşletmenize özel modern, şık ve profesyonel web siteleri hazırlıyoruz.
</p>

</div>


<div class="card">

<h3>📱 Mobil Uyumlu Tasarım</h3>

<p>
Web siteniz telefon, tablet ve bilgisayarlarda düzgün ve hızlı çalışır.
</p>

</div>


<div class="card">

<h3>🔲 QR Kod Sistemleri</h3>

<p>
İşletmenize özel QR kod hazırlıyoruz.
Müşterileriniz kamerayla okutarak web sitenize ulaşabilir.
</p>

</div>


<div class="card">

<h3>☕ QR Menü</h3>

<p>
Kafe, restoran ve benzeri işletmeler için dijital QR menüler hazırlıyoruz.
</p>

</div>


<div class="card">

<h3>🎨 Özel Tasarım</h3>

<p>
Hazır ve sıradan tasarımlar yerine işletmenizin tarzına uygun özel tasarımlar yapıyoruz.
</p>

</div>


<div class="card">

<h3>🚀 Yayına Alma Desteği</h3>

<p>
Hazırladığımız web sitesinin internette yayınlanması konusunda destek sağlıyoruz.
</p>

</div>

</div>

</section>


<!-- QR KOD -->

<section class="qr-section" id="qr">

<div class="title">

<h2>QR Kod Çözümlerimiz</h2>

<p>Kamerayı okutun ve işletmenizin dijital dünyasına girin</p>

</div>


<div class="qr-box">

<div class="qr-icon">▣</div>

<h2>İşletmenize Özel QR Kod</h2>

<br>

<p>
İşletmeniz için özel QR kod oluşturuyoruz.
Müşterileriniz telefonlarının kamerasıyla QR kodu okuttuğunda
doğrudan web sitenize, dijital menünüze, kampanyanıza
veya istediğiniz özel sayfaya yönlendirilir.
</p>

<br>

<p>
Kafe ve restoranlar için QR menü,
mağazalar için ürün tanıtımı,
işletmeler için kurumsal web sitesi bağlantıları
ve daha birçok dijital çözüm hazırlıyoruz.
</p>

</div>

</section>


<!-- NASIL ÇALIŞIYOR -->

<section>

<div class="title">

<h2>Nasıl Çalışıyoruz?</h2>

<p>Web siteniz birkaç basit adımda hazırlanır</p>

</div>


<div class="steps">

<div class="step">

<div class="number">1</div>

<h3>Bize Ulaşın</h3>

<p>İşletmeniz ve istediğiniz web sitesi hakkında konuşalım.</p>

</div>


<div class="step">

<div class="number">2</div>

<h3>Tasarımı Hazırlayalım</h3>

<p>İşletmenize uygun modern ve özel bir tasarım oluşturalım.</p>

</div>


<div class="step">

<div class="number">3</div>

<h3>Web Sitenizi Oluşturalım</h3>

<p>Telefon ve bilgisayarlara uyumlu web sitenizi hazırlayalım.</p>

</div>


<div class="step">

<div class="number">4</div>

<h3>QR Kodunuzu Verelim</h3>

<p>Hazırladığımız QR kod ile müşterileriniz sitenize kolayca ulaşsın.</p>

</div>


<div class="step">

<div class="number">5</div>

<h3>Yayına Alalım</h3>

<p>Web sitenizi internette herkesin görebileceği şekilde yayınlayalım.</p>

</div>

</div>

</section>


<!-- HAKKIMIZDA -->

<section class="about" id="hakkimizda">

<div class="title">

<h2>Biz Kimiz?</h2>

</div>


<div class="about-box">

<p>
Biz işletmelerin dijital dünyada daha güçlü görünmesi için
modern web siteleri ve QR kod çözümleri hazırlıyoruz.
Her işletmenin kendine özel bir tarzı olduğuna inanıyor
ve tasarımlarımızı buna göre hazırlıyoruz.
</p>

<p style="margin-top:20px;">
Amacımız işletmelerin müşterilerine daha kolay ulaşmasını
ve profesyonel bir şekilde internette yer almasını sağlamaktır.
</p>


<div class="names">

<div class="person">

<h3>Serkan Gültekin</h3>

<p>Web Site ve Dijital Çözümler</p>

</div>


<div class="person">

<h3>Ömer Dayam</h3>

<p>Web Site ve Dijital Çözümler</p>

</div>

</div>

</div>

</section>


<!-- İLETİŞİM -->

<section class="contact" id="iletisim">

<div class="title">

<h2>Bizimle İletişime Geçin</h2>

<p>İşletmeniz için web sitesi veya QR kod çözümü mü istiyorsunuz?</p>

</div>


<a class="phone whatsapp"
href="https://wa.me/905314008897"
target="_blank">

💬 Serkan Gültekin ile WhatsApp'tan İletişime Geç

</a>

<br>


<a class="phone"
href="tel:05314008897">

📞 Serkan Gültekin
<br>
0531 400 88 97

</a>


<a class="phone"
href="tel:05453682967">

📞 Ömer Dayam
<br>
0545 368 29 67

</a>


<p style="margin-top:30px;color:#aeb9cc;">

İşletmenizi anlatın, size özel web sitesi ve dijital çözümü birlikte oluşturalım.

</p>

</section>


<footer>

<p>© 2026 SG Web Studio</p>

<p style="margin-top:8px;">
Serkan Gültekin & Ömer Dayam | Web Sitesi ve QR Kod Çözümleri
</p>

</footer>


</body>
</html>
