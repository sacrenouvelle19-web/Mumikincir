<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>MUDA-MUDI KINCIR</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
/* RESET */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

/* BODY */
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #f2f4f7;
    color: #333;
    line-height: 1.6;
}

/* HEADER */
header {
    background: linear-gradient(135deg, #2c3e50, #3498db);
    color: white;
    padding: 30px 15px;
    text-align: center;
}

header h1 {
    font-size: 1.8em;
}

header p {
    font-size: 1em;
    opacity: 0.9;
}

/* NAV */
nav {
    position: sticky;
    top: 0;
    background: #fff;
    display: flex;
    justify-content: space-around;
    padding: 10px 5px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    z-index: 100;
}

nav a {
    text-decoration: none;
    color: #3498db;
    font-weight: 600;
    font-size: 0.9em;
}

/* SECTION */
section {
    margin: 15px;
    padding: 20px;
    background: white;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

section h2 {
    margin-bottom: 10px;
    color: #2c3e50;
    font-size: 1.3em;
}

/* KEGIATAN CARD */
.kegiatan {
    background: #f8f9fb;
    padding: 15px;
    border-radius: 10px;
    margin-bottom: 12px;
    border-left: 4px solid #3498db;
}

.kegiatan h4 {
    margin-bottom: 5px;
}

/* GALERI */
.galeri {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 10px;
}

.galeri img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 10px;
}

/* KONTAK */
.kontak p {
    margin: 6px 0;
    font-size: 0.95em;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 15px;
    font-size: 0.85em;
    color: #666;
}

/* DESKTOP */
@media (min-width: 768px) {
    nav {
        justify-content: center;
        gap: 30px;
    }

    section {
        max-width: 900px;
        margin: 20px auto;
    }

    .galeri {
        grid-template-columns: repeat(3, 1fr);
    }
}
</style>
</head>

<body>

<header>
    <h1>MUMI KINCIR</h1>
    <p>Website Resmi muda/i kincir</p>
</header>

<nav>
    <a href="#beranda">Beranda</a>
    <a href="#tentang">Tentang</a>
    <a href="#kegiatan">Kegiatan</a>
    <a href="#galeri">Galeri</a>
    <a href="#kontak">Kontak</a>
</nav>

<section id="beranda">
    <h2>Beranda</h2>
    <p>
        Selamat datang di website resmi mumi kincir.
        Kami aktif dalam kegiatan pengajian dan keakraban dikelompok kincir.
    </p>
</section>

<section id="tentang">
    <h2>Tentang Kami</h2>
    <p>
        Muda/i kincir adalah anak-anak generasi penerus yang akan meneruskan kelestarian Al-Qur'an dan hadits.
    </p>
</section>

<section id="kegiatan">
    <h2>Kegiatan</h2>

    <div class="kegiatan">
        <h4>Mengaji</h4>
        <p>Mengaji Alquran dan Al hadist secara mangqul musnad muttasil.</p>
    </div>

    <div class="kegiatan">
        <h4>Musyawarah</h4>
        <p>Evaluasi dan perencanaan program kegiatan.</p>
    </div>

    <div class="kegiatan">
        <h4>Keakraban</h4>
        <p>Kegiatan kebersamaan untuk meningkatkan kebersamaan.</p>
    </div>
</section>

<section id="galeri">
    <h2>Galeri</h2>
    <div class="galeri">

    <figure>
        <img src="https://uploads.onecompiler.io/44aahqfdy/44aahpqcq/foto2.jpg">
        <figcaption>makan-makan</figcaption>
    </figure>

    <figure>
        <img src="https://uploads.onecompiler.io/44aahqfdy/44aahpqcq/foto3.jpg">
        <figcaption>liwetan</figcaption>
    </figure>

    <figure>
        <img src="https://uploads.onecompiler.io/44aahqfdy/44aahpqcq/foto4.jpg">
        <figcaption>musyawarah perencanaan kegiatan</figcaption>
    </figure>

    <figure>
        <img src="https://uploads.onecompiler.io/44aahqfdy/44aahpqcq/foto5.jpg">
        <figcaption>pengajian dirumah pengurus</figcaption>
    </figure>

</div>


    </div>
</section>

<section id="kontak" class="kontak">
    <h2>Kontak</h2>
    <p>📍 Jl. swadaya 2 kp.pondok manggis</p>
    <p>📧 mumikincir354@email.com</p>
    <p>📞 08xxxxxxxx</p>
</section>

<footer>
    © 2026 Mumi kincir 
</footer>

</body>
</html>
