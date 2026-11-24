<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Untuk Bu Vina - Happy Teacher's Day</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(160deg, #080d2b, #171443, #30205a);
    color: white;
    min-height: 100vh;
    overflow-x: hidden;
}

.stars {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 0;
    background-image:
      radial-gradient(2px 2px at 20% 30%, white, transparent),
      radial-gradient(2px 2px at 70% 20%, #c9b6ff, transparent),
      radial-gradient(2px 2px at 40% 80%, white, transparent),
      radial-gradient(2px 2px at 90% 65%, #a9d9ff, transparent);
    background-size: 180px 180px;
    animation: twinkle 4s infinite alternate;
}

@keyframes twinkle {
    from { opacity: 0.4; }
    to { opacity: 1; }
}

.container {
    position: relative;
    z-index: 1;
    max-width: 750px;
    margin: auto;
    padding: 30px 20px;
    text-align: center;
}

.math {
    font-family: Georgia, serif;
    color: #b9a2ff;
    font-size: 25px;
    letter-spacing: 8px;
    margin-top: 30px;
}

h1 {
    font-size: clamp(35px, 8vw, 58px);
    margin: 25px 0;
    color: #e3d7ff;
    text-shadow: 0 0 25px #9878ff;
}

.subtitle {
    color: #c7c2e8;
    font-size: 16px;
    line-height: 1.8;
}

.glow {
    width: 100px;
    height: 3px;
    margin: 25px auto;
    background: linear-gradient(90deg, transparent, #b49aff, transparent);
}

.box {
    margin-top: 40px;
    padding: 30px 25px;
    border: 1px solid rgba(190,165,255,0.35);
    border-radius: 22px;
    background: rgba(255,255,255,0.07);
    backdrop-filter: blur(10px);
    box-shadow: 0 0 35px rgba(128,95,255,0.12);
}

.box h2 {
    color: #d8c7ff;
    font-size: 27px;
    margin-bottom: 20px;
}

.box p {
    line-height: 1.9;
    color: #e1def4;
    font-size: 16px;
}

.formula {
    margin: 30px 0;
    color: #c3adff;
    font-family: Georgia, serif;
    font-size: 24px;
}

button {
    background: linear-gradient(45deg, #7657d8, #a17aff);
    border: 1px solid #c3adff;
    border-radius: 40px;
    padding: 16px 28px;
    color: white;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    margin-top: 30px;
    box-shadow: 0 0 20px rgba(156,122,255,0.4);
    transition: 0.3s;
}

button:hover {
    transform: scale(1.06);
    box-shadow: 0 0 30px #9c7aff;
}

#surprise {
    display: none;
    margin-top: 30px;
    padding: 25px;
    background: rgba(13,12,45,0.8);
    border: 1px solid #a98cff;
    border-radius: 18px;
    text-align: left;
    animation: appear 1.2s ease;
}

#surprise h2 {
    text-align: center;
    color: #d6c2ff;
    line-height: 1.5;
    margin-bottom: 20px;
}

#surprise p {
    color: #e5e0fa;
    line-height: 2;
    font-size: 15px;
    margin-bottom: 17px;
}

.signature {
    text-align: center;
    color: #c6adff;
    margin-top: 30px;
    line-height: 2;
}

.footer {
    margin: 50px 0 25px;
    color: #bdb1e8;
    line-height: 2;
}

.falling {
    position: fixed;
    top: -30px;
    z-index: 5;
    pointer-events: none;
    animation: fall 6s linear forwards;
}

@keyframes fall {
    to {
        transform: translateY(110vh) rotate(360deg);
        opacity: 0;
    }
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(25px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@media(max-width: 480px) {
    .box {
        padding: 24px 17px;
    }
}
</style>
</head>

<body>

<div class="stars"></div>

<div class="container">

    <div class="math">π ∞ √ x² + y²</div>

    <h1>Happy Teacher's Day</h1>

    <div class="glow"></div>

    <p class="subtitle">
        A special appreciation for someone
        who makes numbers meaningful.
        <br>
        Untuk Guru Matematika Tercinta,
    </p>

    <h2 style="color:#d9c9ff; margin-top:20px;">
        Bu Vina 💜
    </h2>

    <div class="box">

        <h2>Dear Bu Vina</h2>

        <p>
            Bu, mungkin matematika dikenal sebagai
            pelajaran yang penuh angka, rumus,
            dan perhitungan.
        </p>

        <p>
            Namun, ada satu hal yang tidak bisa
            dihitung menggunakan rumus matematika,
            yaitu rasa terima kasih seorang murid
            kepada gurunya.
        </p>

        <div class="formula">
            ∞ + ∞ = ∞
        </div>

        <p>
            Terima kasih sudah bersedia membagikan
            ilmu, mengajarkan kami memahami angka,
            dan tetap sabar ketika kami belum
            mengerti suatu materi.
        </p>

        <button onclick="openSurprise()">
            ✨ Buka Kejutan Spesial ✨
        </button>

        <div id="surprise">

            <h2>
                💜 Selamat Hari Guru, Bu Vina 💜
            </h2>

            <p>
                Bu Vina yang saya hormati,
            </p>

            <p>
                Di hari yang istimewa ini, saya ingin
                menyampaikan sesuatu yang mungkin
                tidak selalu bisa saya ungkapkan
                secara langsung.
            </p>

            <p>
                Terima kasih, Bu, karena sudah menjadi
                sosok guru yang memberikan ilmu dan
                membimbing kami. Saya tahu bahwa
                mengajar bukanlah pekerjaan yang
                selalu mudah. Ada banyak hal yang
                harus Ibu hadapi, mulai dari
                mempersiapkan materi, menjelaskan
                pelajaran berulang kali, hingga
                menghadapi berbagai macam karakter
                murid di kelas.
            </p>

            <p>
                Apalagi matematika. Terkadang kami
                membutuhkan waktu lebih lama untuk
                memahami satu rumus, terkadang salah
                menghitung, bahkan mungkin ada saat
                ketika kami belum memperhatikan
                penjelasan Ibu dengan baik.
                Namun, terima kasih karena Ibu tetap
                berusaha mengajarkan kami.
            </p>

            <p>
                Mungkin suatu saat nanti kami akan
                lupa beberapa rumus yang pernah
                dipelajari, lupa cara mengerjakan
                soal-soal tertentu, atau bahkan lupa
                halaman buku yang pernah kami buka.
                Tetapi saya berharap kami tidak akan
                melupakan orang-orang yang pernah
                berusaha memberikan ilmu kepada kami.
            </p>

            <p>
                Bu, bagi saya seorang guru bukan
                hanya seseorang yang berdiri di depan
                kelas dan menjelaskan pelajaran.
                Guru juga merupakan bagian dari
                perjalanan seorang murid untuk
                menjadi pribadi yang lebih baik.
            </p>

            <p>
                Jika dalam perjalanan belajar ini
                saya pernah melakukan kesalahan,
                kurang memperhatikan, atau tanpa
                sengaja membuat Ibu kecewa, saya
                memohon maaf ya, Bu. Saya masih
                seorang murid yang sedang belajar
                dan tentu masih memiliki banyak
                kekurangan.
            </p>

            <p>
                Semoga segala ilmu yang Ibu berikan
                menjadi sesuatu yang bermanfaat,
                bukan hanya untuk nilai di atas
                kertas, tetapi juga untuk masa depan
                kami. Semoga setiap usaha dan
                kesabaran Ibu mendapatkan balasan
                kebaikan yang berlipat ganda.
            </p>

            <p>
                Saya juga berharap Ibu selalu
                diberikan kesehatan, kebahagiaan,
                kekuatan, dan kemudahan dalam
                menjalani setiap hari.
            </p>

            <p>
                Dan jika suatu hari nanti kami sudah
                melangkah jauh, semoga Ibu tahu
                bahwa ada murid-murid yang pernah
                belajar di kelas Ibu dan membawa
                sebagian ilmu serta nasihat Ibu
                dalam perjalanan hidup mereka.
            </p>

            <p>
                Terima kasih sudah menjadi guru
                Matematika yang berarti bagi kami.
                Karena ternyata, tidak semua hal
                berharga dalam hidup bisa dihitung
                dengan angka.
            </p>

            <p>
                Selamat Hari Guru, Bu Vina.
                Terima kasih untuk setiap ilmu,
                waktu, kesabaran, dan pengorbanan
                yang telah Ibu berikan.
            </p>

            <div class="signature">
                <h2>Terima Kasih, Bu Vina 💜</h2>
                <p>
                    Dari murid Ibu,
                    <br>
                    <b>Rizki</b>
                </p>
                <p style="font-size:30px;">
                    🌌 💜 ✨
                </p>
            </div>

        </div>

    </div>

    <div class="footer">
        <p>Mathematics may have endless numbers,</p>
        <p>but gratitude has no limit.</p>
        <br>
        <p>Made with respect and appreciation.</p>
        <b>— Rizki —</b>
    </div>

</div>

<script>
function openSurprise() {

    const surprise = document.getElementById("surprise");

    surprise.style.display = "block";

    document.querySelector("button").innerText =
        "💜 Terima kasih, Bu Vina";

    surprise.scrollIntoView({
        behavior: "smooth",
        block: "start"
    });

    for(let i = 0; i < 45; i++) {

        setTimeout(() => {

            let star = document.createElement("div");

            star.className = "falling";

            star.innerHTML = ["✨","💜","⭐","🌸"][
                Math.floor(Math.random() * 4)
            ];

            star.style.left = Math.random() * 100 + "vw";

            star.style.fontSize =
                (15 + Math.random() * 20) + "px";

            star.style.animationDuration =
                (3 + Math.random() * 4) + "s";

            document.body.appendChild(star);

            setTimeout(() => star.remove(), 7000);

        }, i * 100);

    }
}
</script>

</body>
</html>
