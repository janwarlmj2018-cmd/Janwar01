<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan Janwar & Suci</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&family=Great+Vibes&family=Playfair+Display:wght@400;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gold: '#D4AF37',
                        cream: '#FFF8E7',
                    },
                    fontFamily: {
                        'cinzel': ['Cinzel', 'serif'],
                        'script': ['Great Vibes', 'cursive'],
                        'serif': ['Playfair Display', 'serif'],
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .bg-cover { background-size: cover; }
            .bg-center { background-position: center; }
            .text-shadow { text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        }
    </style>
</head>
<body class="bg-cream text-neutral-800 antialiased">

    <!-- HERO SECTION -->
    <header class="relative h-screen flex items-center justify-center text-center text-white px-4">
        <div class="absolute inset-0 bg-black/50 z-10"></div>
        <div class="absolute inset-0 bg-cover bg-center" style="background-image: url('DSC_2231.jpg');"></div>
        <div class="relative z-20 space-y-4 max-w-2xl mx-auto">
            <p class="font-cinzel tracking-widest text-gold uppercase text-sm">Undangan Pernikahan</p>
            <h1 class="font-script text-6xl md:text-7xl text-gold">Janwar & Suci</h1>
            <div class="w-24 h-0.5 bg-gold mx-auto"></div>
            <p class="mt-6 text-lg font-serif">Kepada Yth.<br>Bapak/Ibu/Saudara/i</p>
            <h2 id="guest-name" class="font-cinzel font-bold text-2xl mt-2">Tamu Undangan</h2>
            <p class="mt-4 text-sm opacity-80">Dengan memohon rahmat dan ridho Allah SWT, kami bermaksud menyelenggarakan Resepsi Pernikahan putra-putri kami:</p>
            <a href="#couple" class="inline-block mt-8 px-8 py-3 bg-gold text-white rounded-full font-cinzel hover:bg-gold/90 transition">
                <i class="fa fa-heart mr-2"></i>Buka Undangan
            </a>
        </div>
    </header>

    <!-- COUPLE SECTION -->
    <section id="couple" class="py-20 px-4 max-w-4xl mx-auto text-center">
        <p class="font-serif text-lg text-neutral-600 italic">"Dan segala sesuatu Kami ciptakan berpasang-pasangan agar kamu mengingat kebesaran Allah." (QS. Adz-Dzariyat: 49)</p>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mt-12">
            <!-- Pria -->
            <div class="space-y-4 flex flex-col items-center">
                <div class="w-64 h-80 rounded-2xl overflow-hidden shadow-xl border-4 border-gold">
                    <img src="IMG-20260805-WA0024.jpg" alt="Janwar Febriyanto" class="w-full h-full object-cover">
                </div>
                <h3 class="font-cinzel text-2xl font-bold text-neutral-900">Janwar Febriyanto</h3>
                <p class="text-sm text-neutral-600">Putra dari Bapak Suwari & Ibu Ponitri</p>
            </div>

            <!-- Wanita -->
            <div class="space-y-4 flex flex-col items-center">
                <div class="w-64 h-80 rounded-2xl overflow-hidden shadow-xl border-4 border-gold">
                    <img src="IMG-20260805-WA0025.jpg" alt="Suci Rahmawati" class="w-full h-full object-cover">
                </div>
                <h3 class="font-cinzel text-2xl font-bold text-neutral-900">Suci Rahmawati</h3>
                <p class="text-sm text-neutral-600">Putri dari Bapak [Nama Ayah] & Ibu [Nama Ibu]</p>
            </div>
        </div>
    </section>

    <!-- DATE SECTION -->
    <section class="py-20 px-4 bg-neutral-100">
        <div class="max-w-2xl mx-auto text-center">
            <h2 class="font-script text-4xl text-gold mb-8">Waktu & Tempat</h2>
            <div class="space-y-6 font-cinzel">
                <div>
                    <p class="text-lg font-bold">Akad Nikah</p>
                    <p class="text-neutral-600">Jum'at, 18 September 2026 | Pukul 08:00 WIB</p>
                </div>
                <div>
                    <p class="text-lg font-bold">Resepsi</p>
                    <p class="text-neutral-600">Jum'at 18 September 2026 | Pukul 13:00 s.d. Selesai WIB</p>
                </div>
                <div class="mt-8">
                    <p class="font-bold">Tempat</p>
                    <p class="text-neutral-600">[Nama Tempat / Alamat Lengkap]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="py-12 text-center text-neutral-500 text-sm">
        <p>Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir untuk memberikan doa restu kepada kedua mempelai.</p>
        <p class="mt-4">— Janwar & Suci —</p>
    </footer>

</body>
</html>
                    },
                    fontFamily: {
                        cinzel: ['Cinzel', 'serif'],
                        script: ['Pinyon Script', 'cursive'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .glass-card { background: rgba(255,255,255,0.85); backdrop-filter: blur(10px); }
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-softcream text-neutral-800 font-sans antialiased overflow-x-hidden">

    <!-- 🎵 MUSIK -->
    <iframe id="yt-music" src="https://www.youtube.com/embed/5iMztimFbu0?autoplay=1&loop=1&playlist=5iMztimFbu0" style="display:none;" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

    <!-- COVER / HALAMAN DEPAN -->
    <div id="cover-section" class="fixed inset-0 z-50 flex flex-col items-center justify-center bg-javaneseGreen text-white p-6 transition-all duration-700">
        <div class="absolute inset-0 opacity-25 bg-cover bg-center" style="background-image: url('https://janwarimj2018-cmd.github.io/undangan/DSC_2231.jpg');"></div>
        <div class="relative z-10 text-center max-w-md mx-auto space-y-6">
            <p class="font-cinzel tracking-widest text-gold text-sm uppercase">Undangan Pernikahan</p>
            <h1 class="font-script text-6xl text-gold">Janwar & Suci</h1>
            <div class="w-24 h-0.5 bg-gold mx-auto"></div>
            <div class="py-4">
                <p class="text-sm text-neutral-300">Kepada Yth. Bapak/Ibu/Saudara/i</p>
                <h2 id="guest-name" class="font-semibold text-xl text-white mt-1">Tamu Undangan</h2>
                <p class="text-xs text-neutral-400 mt-1">Tanpa mengurangi rasa hormat, kami mengundang Anda</p>
            </div>
            <button onclick="openInvitation()" class="bg-gold hover:bg-darkgold text-neutral-900 font-medium px-8 py-3 rounded-full shadow-lg transition duration-300 flex items-center justify-center mx-auto space-x-2">
                <i class="fa-solid fa-envelope-open-text"></i>
                <span>Buka Undangan</span>
            </button>
        </div>
    </div>

    <!-- MAIN CONTENT -->
    <div id="main-content" class="opacity-0 transition-opacity duration-1000 hidden">

        <!-- HERO SECTION -->
        <header class="relative h-screen flex items-center justify-center text-center text-white px-4">
            <div class="absolute inset-0 bg-black/50 z-10"></div>
            <div class="absolute inset-0 bg-cover bg-center" style="background-image: url('https://janwarimj2018-cmd.github.io/undangan/DSC_2231.jpg');"></div>
            <div class="relative z-20 space-y-4 max-w-2xl mx-auto">
                <p class="font-cinzel tracking-widest text-gold uppercase text-sm">The Wedding Of</p>
                <h1 class="font-script text-6xl md:text-8xl text-gold">Janwar & Suci</h1>
                <p class="font-cinzel text-lg tracking-wider">Jumat, 18 September 2026</p>
                <div class="pt-6"><a href="#countdown" class="animate-bounce inline-block text-gold"><i class="fa-solid fa-chevron-down text-xl"></i></a></div>
            </div>
        </header>

        <!-- COUPLE SECTION -->
        <section class="py-20 px-6 max-w-5xl mx-auto text-center">
            <div class="space-y-4 mb-16">
                <p class="font-cinzel text-gold text-sm tracking-widest uppercase">Sang Mempelai</p>
                <h2 class="font-script text-5xl text-neutral-900">Pasangan Bahagia</h2>
                <p class="text-neutral-600 max-w-lg mx-auto text-sm">"Dan di antara tanda-tanda kebesaran-Nya ialah Dia menciptakan pasangan-pasangan untukmu dari jenismu sendiri, agar kamu cenderung dan merasa tenteram kepadanya..." (QS. Ar-Rum: 21)</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <!-- Pria -->
                <div class="space-y-4 flex flex-col items-center">
                    <div class="w-64 h-80 rounded-2xl overflow-hidden shadow-xl border-4 border-gold">
                        <img src="https://janwarimj2018-cmd.github.io/undangan/IMG-20260805-WA0024.jpg" alt="Janwar Febriyanto" class="w-full h-full object-cover">
                    </div>
                    <h3 class="font-cinzel text-2xl font-bold text-neutral-900">Janwar Febriyanto</h3>
                    <p class="text-sm text-neutral-600">Putra dari Bapak Suwari & Ibu Ponitri</p>
                </div>
                <!-- Wanita -->
                <div class="space-y-4 flex flex-col items-center">
                    <div class="w-64 h-80 rounded-2xl overflow-hidden shadow-xl border-4 border-gold">
                        <img src="https://janwarimj2018-cmd.github.io/undangan/IMG-20260805-WA0025.jpg" alt="Suci Rahmawati" class="w-full h-full object-cover">
                    </div>
                    <h3 class="font-cinzel text-2xl font-bold text-neutral-900">Suci Rahmawati</h3>
                    <p class="text-sm text-neutral-600">Putri dari Bapak Heri Nursio & Ibu Dewi Musyarofah</p>
                </div>
            </div>
        </section>

        <!-- COUNTDOWN -->
        <section id="countdown" class="py-16 bg-javaneseGreen text-white px-6 text-center">
            <div class="max-w-2xl mx-auto space-y-6">
                <h2 class="font-cinzel text-2xl text-gold tracking-widest">Menuju Hari Bahagia</h2>
                <div class="grid grid-cols-4 gap-4 max-w-md mx-auto">
                    <div class="bg-white/10 p-3 rounded-lg backdrop-blur"><span id="days" class="font-cinzel text-3xl font-bold text-gold">00</span><p class="text-xs uppercase text-neutral-300">Hari</p></div>
                    <div class="bg-white/10 p-3 rounded-lg backdrop-blur"><span id="hours" class="font-cinzel text-3xl font-bold text-gold">00</span><p class="text-xs uppercase text-neutral-300">Jam</p></div>
                    <div class="bg-white/10 p-3 rounded-lg backdrop-blur"><span id="minutes" class="font-cinzel text-3xl font-bold text-gold">00</span><p class="text-xs uppercase text-neutral-300">Menit</p></div>
                    <div class="bg-white/10 p-3 rounded-lg backdrop-blur"><span id="seconds" class="font-cinzel text-3xl font-bold text-gold">00</span><p class="text-xs uppercase text-neutral-300">Detik</p></div>
                </div>
            </div>
        </section>

        <!-- ACARA -->
        <section class="py-20 px-6 max-w-4xl mx-auto">
            <div class="text-center space-y-4 mb-12">
                <p class="font-cinzel text-gold text-sm tracking-widest uppercase">Rangkaian Acara</p>
                <h2 class="font-script text-5xl text-neutral-900">Waktu & Tempat</h2>
                <p class="text-sm text-neutral-600 font-medium max-w-md mx-auto">
                    <i class="fa-solid fa-location-dot text-gold mr-2"></i> Rumah Kediaman Mempelai Wanita<br>Dsn. Siluman Ds. Bades Kec. Pasirian
                </p>
                <a href="https://maps.app.goo.gl/bzDdork2EipFquSn8" target="_blank" class="inline-block mt-2 text-gold hover:text-darkgold font-medium">
                    <i class="fa-solid fa-map-location-dot mr-1"></i> Buka di Google Maps
                </a>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-8 rounded-2xl shadow-md border-t-4 border-gold text-center space-y-4">
                    <h3 class="font-cinzel text-2xl font-bold text-neutral-900">🕌 Akad Nikah</h3>
                    <p class="text-sm text-neutral-600"><i class="fa-regular fa-calendar-days text-gold mr-2"></i> Jumat, 18 September 2026</p>
                    <p class="text-sm text-neutral-600"><i class="fa-regular fa-clock text-gold mr-2"></i> Pukul 08.00 WIB - Selesai</p>
                </div>
                <div class="bg-white p-8 rounded-2xl shadow-md border-t-4 border-gold text-center space-y-4">
                    <h3 class="font-cinzel text-2xl font-bold text-neutral-900">🎉 Resepsi</h3>
                    <p class="text-sm text-neutral-600"><i class="fa-regular fa-calendar-days text-gold mr-2"></i> Jumat, 18 September 2026</p>
                    <p class="text-sm text-neutral-600"><i class="fa-regular fa-clock text-gold mr-2"></i> Pukul 13.00 WIB - Selesai</p>
                </div>
            </div>
        </section>

        <!-- RSVP -->
        <section class="py-20 px-6 max-w-3xl mx-auto">
            <div class="text-center space-y-4 mb-12">
                <p class="font-cinzel text-gold text-sm tracking-widest uppercase">Konfirmasi Kehadiran</p>
                <h2 class="font-script text-5xl text-neutral-900">RSVP & Ucapan</h2>
            </div>
            <form id="rsvp-form" class="bg-white p-8 rounded-2xl shadow-md space-y-6">
                <div><label class="block text-sm font-medium text-neutral-700 mb-2">Nama</label><input type="text" id="name" required class="w-full px-4 py-3 border rounded-lg focus:ring-2 focus:ring-gold outline-none"></div>
                <div><label class="block text-sm font-medium text-neutral-700 mb-2">Konfirmasi Kehadiran</label>
                    <select id="status" class="w-full px-4 py-3 border rounded-lg focus:ring-2 focus:ring-gold outline-none">
                        <option value="Hadir">✅ Hadir</option>
                        <option value="Tidak Hadir">🙏 Berhalangan Hadir</option>
                    </select>
                </div>
                <div><label class="block text-sm font-medium text-neutral-700 mb-2">Ucapan & Doa</label>
                    <textarea id="message" rows="4" required class="w-full px-4 py-3 border rounded-lg focus:ring-2 focus:ring-gold outline-none" placeholder="Tulis doa & ucapan..."></textarea>
                </div>
                <button type="submit" class="w-full bg-gold hover:bg-darkgold text-neutral-900 font-medium py-3 rounded-lg transition duration-300">Kirim Ucapan 🤲</button>
            </form>
            <div id="wishes-container" class="mt-10 space-y-4"></div>
        </section>

        <!-- PENUTUP -->
        <section class="py-16 px-6 text-center max-w-2xl mx-auto">
            <p class="text-lg text-neutral-700 leading-relaxed">
                Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu.<br><br>
                <em class="text-gold italic">"Dan di antara tanda-tanda kebesaran-Nya ialah Dia menciptakan pasangan-pasangan untukmu..."</em><br><br>
                Wassalamu'alaikum Warahmatullahi Wabarakatuh ❤️
            </p>
        </section>

        <!-- FOOTER -->
        <footer class="bg-javaneseGreen text-white py-8 text-center text-sm">
            <p class="font-cinzel tracking-wider text-gold">Terima Kasih</p>
            <p class="text-neutral-400 mt-1">&copy; 2026 Undangan Pernikahan — Janwar & Suci</p>
        </footer>
    </div>

    <!-- TOMBOL MUSIK -->
    <button id="audio-btn" onclick="toggleAudio()" class="fixed bottom-6 right-6 z-40 bg-gold text-neutral-900 w-12 h-12 rounded-full shadow-lg flex items-center justify-center hidden">
        <i id="audio-icon" class="fa-solid fa-music"></i>
    </button>

    <script>
        // Nama tamu
        const urlParams = new URLSearchParams(window.location.search);
        const guest = urlParams.get('to');
        if (guest) document.getElementById('guest-name').innerText = decodeURIComponent(guest);

        // Buka undangan
        function openInvitation() {
            const cover = document.getElementById('cover-section');
            const main = document.getElementById('main-content');
            const audioBtn = document.getElementById('audio-btn');
            const ytMusic = document.getElementById('yt-music');
            cover.style.transform = 'translateY(-100%)';
            setTimeout(() => {
                cover.classList.add('hidden');
                main.classList.remove('hidden','opacity-0');
                audioBtn.classList.remove('hidden');
                ytMusic.src = ytMusic.src;
            }, 700);
        }

        // Musik
        let isMuted = false;
        function toggleAudio() {
            isMuted = !isMuted;
            document.getElementById('audio-icon').className = isMuted ? 'fa-solid fa-volume-xmark' : 'fa-solid fa-music';
            alert('Musik ' + (isMuted ? 'dimatikan 🔇' : 'dinyalakan 🔊'));
        }

        // Hitung mundur
        const weddingDate = new Date("September 18, 2026 08:00:00").getTime();
        setInterval(() => {
            const now = new Date().getTime();
            const distance = weddingDate - now;
            const pad = n => String(Math.max(0, n)).padStart(2, '0');
            if (distance > 0) {
                document.getElementById('days').innerText = pad(Math.floor(distance / (1000 * 60 * 60 * 24)));
                document.getElementById('hours').innerText = pad(Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60)));
                document.getElementById('minutes').innerText = pad(Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60)));
                document.getElementById('seconds').innerText = pad(Math.floor((distance % (1000 * 60)) / 1000));
            } else {
                ['days','hours','minutes','seconds'].forEach(id => document.getElementById(id).innerText = '00');
            }
        }, 1000);

        // Form RSVP
        document.addEventListener('DOMContentLoaded', () => {
            const form = document.getElementById('rsvp-form');
            const container = document.getElementById('wishes-container');
            form?.addEventListener('submit', e => {
                e.preventDefault();
                const name = document.getElementById('name').value;
                const status = document.getElementById('status').value;
                const msg = document.getElementById('message').value;
                const card = document.createElement('div');
                card.className = 'bg-white p-4 rounded-xl shadow-sm border border-neutral-200';
                card.innerHTML = `
                    <div class="flex justify-between items-center mb-2">
                        <h4 class="font-semibold text-neutral-900">${name}</h4>
                        <span class="text-xs px-2 py-1 rounded-full ${status === 'Hadir' ? 'bg-green-100 text-green-700' : 'bg-red-100 text-red-700'}">${status}</span>
                    </div>
                    <p class="text-sm text-neutral-600">${msg}</p>`;
                container?.prepend(card);
                form.reset();
                alert('✅ Terima kasih! Ucapan terkirim!');
            });
        });
    </script>
</body>
</html>
