<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kantor Konsultan Pajak Suhardhi</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: #1e40af 100%; }
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1); }
        .fade-in { animation: fadeIn 0.8s ease-in; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="gradient-bg text-white shadow-lg">
        <nav class="container mx-auto px-7 py-5">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <!-- logo kantor -->
                        <img src="favicon-32x32.png">
                    
                    </div>
                    
                            
                    
                    </div>
                    
                        <h1 class="text-xl font-bold">KKP SUHARDHI</h1>
                        
                        <p class="text-blue-100 text-sm">Konsultan Pajak Profesional</p>
                        
                    </div>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#beranda" class="hover:text-blue-200 transition-colors cursor-pointer">Beranda</a>
                    <a href="#tentang" class="hover:text-blue-200 transition-colors cursor-pointer">Tentang Kami</a>
                    <a href="#layanan" class="hover:text-blue-200 transition-colors cursor-pointer">Layanan</a>
                    <a href="#kontak" class="hover:text-blue-200 transition-colors cursor-pointer">Kontak</a>
                </div>
                <button class="md:hidden text-white" onclick="toggleMenu()">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
            <div id="mobile-menu" class="hidden md:hidden mt-4 space-y-2">
                <a href="#beranda" class="block py-2 hover:text-blue-200 transition-colors cursor-pointer">Beranda</a>
                <a href="#tentang" class="block py-2 hover:text-blue-200 transition-colors cursor-pointer">Tentang Kami</a>
                <a href="#layanan" class="block py-2 hover:text-blue-200 transition-colors cursor-pointer">Layanan</a>
                <a href="#kontak" class="block py-2 hover:text-blue-200 transition-colors cursor-pointer">Kontak</a>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="beranda" class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 text-center fade-in">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">
                KANTOR KONSULTAN PAJAK<br>
                <span class=>SUHARDHI & REKAN</span>
            </h1>
            <p class="text-xl md:text-2xl mb-8 text-blue-100 max-w-3xl mx-auto">
                Solusi Perpajakan Terpercaya untuk Bisnis Anda
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <button onclick="scrollToSection('layanan')" class="bg-yellow-400 text-blue-900 px-8 py-3 rounded-lg font-semibold hover:bg-yellow-300 transition-colors">
                    Lihat Layanan Kami
                </button>
                <button onclick="scrollToSection('kontak')" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-blue-600 transition-colors">
                    Hubungi Kami
                </button>
            </div>
        </div>
    </section>

    <!-- Tentang Kami Section -->
    <section id="tentang" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16 fade-in">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Tentang Kami</h2>
                <div class="w-24 h-1 bg-blue-600 mx-auto mb-8"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="fade-in">
                    <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-2xl">
                        <svg class="w-16 h-16 text-blue-600 mb-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/>
                        </svg>
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">Pengalaman & Profesionalisme</h3>
                        <p class="text-gray-600 leading-relaxed">
                            Tim profesional berpengalaman di bidang perpajakan dengan komitmen tinggi untuk memberikan layanan terbaik.
                        </p>
                    </div>
                </div>
                
                <div class="fade-in">
                    <h3 class="text-3xl font-bold text-gray-800 mb-6">Kantor Konsultan Pajak Suhardhi & Rekan</h3>
                    <p class="text-gray-600 text-lg leading-relaxed mb-6">
                        Kantor Konsultan Pajak Suhardhi & Rekan didirikan oleh tim profesional yang berpengalaman di bidang perpajakan. Kami berkomitmen untuk memberikan layanan terbaik kepada klien kami dengan pendekatan yang transparan dan solusi yang tepat.
                    </p>
                    
                    <div class="grid grid-cols-2 gap-6">
                        <div class="text-center p-4 bg-blue-50 rounded-lg">
                            <div class="text-3xl font-bold text-blue-600">10+</div>
                            <div class="text-gray-600">Tahun Pengalaman</div>
                        </div>
                        <div class="text-center p-4 bg-blue-50 rounded-lg">
                            <div class="text-3xl font-bold text-blue-600">500+</div>
                            <div class="text-gray-600">Klien Terpuaskan</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Layanan Section -->
    <section id="layanan" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16 fade-in">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Layanan Kami</h2>
                <div class="w-24 h-1 bg-blue-600 mx-auto mb-8"></div>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Kami menyediakan berbagai layanan perpajakan profesional untuk memenuhi kebutuhan bisnis Anda
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Konsultasi Pajak -->
                <div class="bg-white p-8 rounded-2xl shadow-lg card-hover fade-in">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Konsultasi Pajak</h3>
                    <p class="text-gray-600 leading-relaxed mb-6">
                        Konsultasi komprehensif mengenai peraturan perpajakan terbaru, strategi optimalisasi pajak, dan solusi permasalahan pajak yang Anda hadapi.
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                            </svg>
                            Analisis kewajiban pajak
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                            </svg>
                            Strategi efisiensi pajak
                        </li>
                    </ul>
                </div>

                <!-- Pelaporan Pajak -->
                <div class="bg-white p-8 rounded-2xl shadow-lg card-hover fade-in">
                    <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-green-600" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M14,2H6A2,2 0 0,0 4,4V20A2,2 0 0,0 6,22H18A2,2 0 0,0 20,20V8L14,2M18,20H6V4H13V9H18V20Z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Pelaporan Pajak</h3>
                    <p class="text-gray-600 leading-relaxed mb-6">
                        Layanan pelaporan pajak yang akurat dan tepat waktu untuk memastikan kepatuhan terhadap peraturan perpajakan yang berlaku.
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                            </svg>
                            SPT Tahunan & Bulanan
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                            </svg>
                            Pelaporan e-Filing
                        </li>
                    </ul>
                </div>

                <!-- Perencanaan Pajak -->
                <div class="bg-white p-8 rounded-2xl shadow-lg card-hover fade-in">
                    <div class="bg-purple-100 w-16 h-16 rounded-full flex items-center justify-center mb-6">
                        <svg class="w-8 h-8 text-purple-600" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M17,12H22L18,8V11H4A2,2 0 0,0 2,13V20A2,2 0 0,0 4,22H18A2,2 0 0,0 20,20V13A2,2 0 0,0 18,11H17V12M4,13H18V20H4V13Z"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Perencanaan Pajak</h3>
                    <p class="text-gray-600 leading-relaxed mb-6">
                        Perencanaan pajak strategis untuk mengoptimalkan beban pajak perusahaan dengan tetap mematuhi peraturan yang berlaku.
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                            </svg>
                            Tax planning strategis
                        </li>
                        <li class="flex items-center">
                            <svg class="w-4 h-4 text-green-500 mr-2" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
                            </svg>
                            Optimalisasi pajak legal
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Kontak Section -->
    <section id="kontak" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16 fade-in">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Hubungi Kami</h2>
                <div class="w-24 h-1 bg-blue-600 mx-auto mb-8"></div>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Siap membantu Anda dengan solusi perpajakan terbaik. Hubungi kami untuk konsultasi
                </p>
            </div>

            <div class="grid md:grid-cols-2 gap-12">
                <div class="fade-in">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Informasi Kontak</h3>
                    
                    <div class="space-y-6">
                        <div class="flex items-start space-x-4">
                            <div class="bg-blue-100 p-3 rounded-lg">
                                <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12,11.5A2.5,2.5 0 0,1 9.5,9A2.5,2.5 0 0,1 12,6.5A2.5,2.5 0 0,1 14.5,9A2.5,2.5 0 0,1 12,11.5M12,2A7,7 0 0,0 5,9C5,14.25 12,22 12,22C12,22 19,14.25 19,9A7,7 0 0,0 12,2Z"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">Alamat Kantor</h4>
                                <p class="text-gray-600">📍 Jl. Saputra Gang. 9 Nomer 15 Tuparev, Kedawung-Cirebon<br>📍 Jl. Pejuangan No. 9B Kebon Jeruk, Jakarta Barat</p>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="bg-blue-100 p-3 rounded-lg">
                                <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M6.62,10.79C8.06,13.62 10.38,15.94 13.21,17.38L15.41,15.18C15.69,14.9 16.08,14.82 16.43,14.93C17.55,15.3 18.75,15.5 20,15.5A1,1 0 0,1 21,16.5V20A1,1 0 0,1 20,21A17,17 0 0,1 3,4A1,1 0 0,1 4,3H7.5A1,1 0 0,1 8.5,4C8.5,5.25 8.7,6.45 9.07,7.57C9.18,7.92 9.1,8.31 8.82,8.59L6.62,10.79Z"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">Telepon</h4>
                                <a href="https://wa.me/62811222410000" target="_blank" class="text-blue-600 hover:text-blue-800 transition-colors">+62 811 2224 1000</a>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="bg-blue-100 p-3 rounded-lg">
                                <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M20,8L12,13L4,8V6L12,11L20,6M20,4H4C2.89,4 2,4.89 2,6V18A2,2 0 0,0 4,20H20A2,2 0 0,0 22,18V6C22,4.89 21.1,4 20,4Z"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">Email</h4>
                                <p class="text-gray-600">Kantorkonsultanpajaksuhardhi@gmail.com</p>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="bg-blue-100 p-3 rounded-lg">
                                <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12,20A8,8 0 0,0 20,12A8,8 0 0,0 12,4A8,8 0 0,0 4,12A8,8 0 0,0 12,20M12,2A10,10 0 0,1 22,12A10,10 0 0,1 12,22C6.47,22 2,17.5 2,12A10,10 0 0,1 12,2Z"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">Jam Operasional</h4>
                                <p class="text-gray-600">Senin - Jumat: 08:00 - 17:00</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="fade-in">
                    <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-2xl">
                        <h3 class="text-2xl font-bold text-gray-800 mb-6">Konsultasi Gratis</h3>
                        <p class="text-gray-600 mb-6">Dapatkan konsultasi awal gratis untuk mengetahui bagaimana kami dapat membantu kebutuhan perpajakan Anda.</p>
                        
                        <div class="space-y-4">
                            </button>
                            <a href="https://www.instagram.com/kkp_suhardhi" target="_blank" class="block w-full border-2 border-blue-600 text-blue-600 py-3 px-6 rounded-lg font-semibold hover:bg-blue-600 hover:text-white transition-colors text-center">
                                Edukasi tentang perpajakan
                            </button>
                            <a href="https://wa.link/61s2ru" target="_blank" class="block w-full border-2 border-blue-600 text-blue-600 py-3 px-6 rounded-lg font-semibold hover:bg-blue-600 hover:text-white transition-colors text-center">
                                Chat via WhatsApp
                            </a>
                        </div>

                        <div class="mt-8 p-4 bg-white rounded-lg">
                            <div class="flex items-center space-x-3">
                                <svg class="w-8 h-8 text-green-500" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M11,16.5L6.5,12L7.91,10.59L11,13.67L16.59,8.09L18,9.5L11,16.5Z"/>
                                </svg>
                                <div>
                                    <p class="font-semibold text-gray-800">Respon Cepat</p>
                                    <p class="text-sm text-gray-600">Kami akan merespon dalam 24 jam</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <div class="flex items-center space-x-3 mb-4">
                        <div class="bg-blue-800  p-2 rounded-lg">
                            
                            </svg>
                        </div>
                        <div>
                            <!-- logo kantor -->
                            <img src="favicon-32x32.png">
                            <h3 class="text-lg font-bold">KKP SUHARDHI</h3>
                            <p class="text-blue-200 text-sm">Konsultan Pajak Profesional</p>
                        </div>
                    </div>
                    <p class="text-blue-100 leading-relaxed">
                        Kantor Konsultan Pajak Suhardhi & Rekan - Solusi perpajakan terpercaya dengan pendekatan transparan dan profesional.
                    </p>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Layanan Kami</h4>
                    <ul class="space-y-2 text-blue-100">
                        <li>• Konsultasi Pajak</li>
                        <li>• Pelaporan Pajak</li>
                        <li>• Perencanaan Pajak</li>
                        <li>• Tax Review & Audit</li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Kontak</h4>
                    <div class="space-y-2 text-blue-100">
                        <a href="https://maps.app.goo.gl/RQcD1BApXhTGosnk7" target="_blank" class="text-white hover:text-blue-600 transition-colors">📍Jl. Saputra Gang. 9 No. 15 Tuparev, Kedawung-Cirebon</a>
                        </div>
                        <a href="https://maps.app.goo.gl/gQaK3WPpA9FiTWwu8" target="_blank" class="text-white hover:text-blue-600 transition-colors">📍Jl. Pejuangan No. 9B Kebon Jeruk, Jakarta Barat</a>
                        <p>📞 +62 811 2224 1000</p>
                        <p>✉️ Kantorkonsultanpajaksuhardhi@gmail.com</p>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-blue-400 mt-8 pt-8 text-center text-blue-100">
                <p>&copy; 2025 Kantor Konsultan Pajak Suhardhi & Rekan. Semua hak dilindungi.</p>
            </div>
        </div>
    </footer>

    <script>
        function toggleMenu() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({
                behavior: 'smooth'
            });
        }

        function showAlert(message) {
            alert(message);
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add fade-in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        document.querySelectorAll('.fade-in').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(20px)';
            el.style.transition = 'opacity 0.8s ease, transform 0.8s ease';
            observer.observe(el);
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9727f5e6a04844a9',t:'MTc1NTc1NjU1NS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
