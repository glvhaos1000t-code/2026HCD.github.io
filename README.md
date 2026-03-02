<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spring Home Coming Day 2025</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&family=Playfair+Display:ital,wght@0,600;1,600&family=Song+Myung&display=swap');
        
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #F9FBFA;
            color: #334D3D;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        h1, h2, h3, .serif {
            font-family: 'Song Myung', serif;
        }

        .fade-in {
            animation: fadeIn 1.2s ease-out forwards;
            opacity: 0;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .tab-active {
            border-bottom: 2px solid #FFB7C5;
            color: #FFB7C5;
            font-weight: 700;
        }

        .spring-deco {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
            opacity: 0.4;
            background-image: radial-gradient(#FFB7C5 1px, transparent 1px);
            background-size: 40px 40px;
        }
        
        .image-frame {
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            border: 8px solid white;
            background-color: #f3f4f6;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <nav class="fixed w-full bg-white/80 backdrop-blur-md z-50 border-b border-pink-100">
        <div class="max-w-5xl mx-auto px-4 py-4 flex justify-between items-center">
            <div class="text-xl font-bold tracking-wider text-[#FFB7C5] serif">Spring HCD</div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="invitation" class="relative pt-40 pb-20 px-4 min-h-screen flex flex-col justify-center items-center text-center">
        <div class="spring-deco"></div>
        <div class="max-w-3xl mx-auto w-full">
            <p class="text-sm md:text-base tracking-widest text-[#FFB7C5] font-semibold mb-4 uppercase fade-in" style="animation-delay: 0.2s;">YOU ARE INVITED</p>
            <h1 class="text-5xl md:text-7xl font-bold mb-8 leading-tight fade-in" style="animation-delay: 0.4s;">Home Coming Day</h1>
            
            <!-- Image Section -->
            <div class="mb-12 w-full max-w-2xl mx-auto px-4 fade-in" style="animation-delay: 0.6s;">
                <div class="image-frame rounded-3xl overflow-hidden transform transition duration-500 hover:scale-[1.01]">
                    <img src="https://images.unsplash.com/photo-1522383225653-ed111181a951?q=80&w=1200&auto=format&fit=crop" 
                         alt="" 
                         class="w-full h-auto object-cover min-h-[400px]"
                         onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                    <div class="image-placeholder w-full h-64 hidden bg-gray-100 flex items-center justify-center text-gray-400 italic">
                        이미지를 불러오는 중입니다...
                    </div>
                </div>
            </div>

            <p class="text-lg md:text-2xl text-gray-600 mb-12 leading-relaxed max-w-2xl mx-auto fade-in" style="animation-delay: 0.8s;">
                긴 겨울이 지나고 따뜻한 바람이 불어오는 3월,<br>
                <strong>홈커밍데이</strong>에 여러분을 초대합니다.
            </p>
        </div>
    </header>

    <!-- Details Section -->
    <section id="details" class="py-32 bg-white px-4">
        <div class="max-w-5xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-10 mb-24">
                <div class="bg-[#F9FBFA] p-12 rounded-3xl border border-green-50 shadow-sm text-center transform transition duration-500 hover:scale-105">
                    <div class="text-6xl mb-6">🌸</div>
                    <h3 class="text-2xl font-bold mb-4">일시</h3>
                    <p class="text-2xl text-[#FFB7C5] font-bold">2025년 3월 7일 (금)</p>
                    <p class="text-gray-500 mt-2 text-lg italic">오후 6시 (18:00)</p>
                </div>
                
                <div class="bg-[#F9FBFA] p-12 rounded-3xl border border-green-50 shadow-sm text-center transform transition duration-500 hover:scale-105">
                    <div class="text-6xl mb-6">🌿</div>
                    <h3 class="text-2xl font-bold mb-4">장소</h3>
                    <p class="text-2xl text-[#2E8B57] font-bold">안양교회 교육관</p>
                    <p class="text-gray-500 mt-2 text-lg">안양시 만안구 삼막로96번길 83</p>
                </div>
            </div>

            <!-- 일정 (Schedule) -->
            <div class="mt-16 bg-[#F9FBFA] p-10 md:p-16 rounded-[3rem] border border-pink-50 relative">
                <h3 class="text-3xl font-bold mb-10 text-center serif text-[#334D3D]">일정</h3>
                <div class="flex justify-center border-b border-pink-100 mb-12 overflow-x-auto pb-2">
                    <button class="tab-btn tab-active px-8 py-4 transition-colors focus:outline-none whitespace-nowrap text-lg" data-target="tab1">식사</button>
                    <button class="tab-btn text-gray-400 px-8 py-4 transition-colors focus:outline-none whitespace-nowrap text-lg" data-target="tab2">섞임&누림</button>
                </div>

                <div id="tab1" class="tab-content text-center fade-in">
                    <h4 class="text-3xl font-bold mb-6 text-[#FFB7C5]">18:00 - 19:00</h4>
                    <p class="text-gray-700 text-xl leading-relaxed">준비된 맛있는 식사와 함께<br>정겨운 인사를 나누는 시간</p>
                </div>
                <div id="tab2" class="tab-content text-center hidden fade-in">
                    <h4 class="text-3xl font-bold mb-6 text-[#FFB7C5]">19:00 - 20:00</h4>
                    <p class="text-gray-700 text-xl leading-relaxed font-medium">찬송을 부르고, 함께 교통하는<br>섞임과 누림의 시간</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#334D3D] py-20 text-center text-gray-300">
        <div class="max-w-5xl mx-auto px-4">
            <p class="serif text-3xl text-[#FFB7C5] mb-6 italic">Spring Home Coming Day</p>
            <div class="w-16 h-px bg-pink-200/30 mx-auto"></div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Tab Logic
            const tabBtns = document.querySelectorAll('.tab-btn');
            const tabContents = document.querySelectorAll('.tab-content');

            tabBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    tabBtns.forEach(b => { 
                        b.classList.remove('tab-active'); 
                        b.classList.add('text-gray-400'); 
                    });
                    btn.classList.add('tab-active'); 
                    btn.classList.remove('text-gray-400');

                    tabContents.forEach(content => content.classList.add('hidden'));
                    const targetId = btn.getAttribute('data-target');
                    const targetContent = document.getElementById(targetId);
                    targetContent.classList.remove('hidden');
                    
                    targetContent.style.animation = 'none';
                    targetContent.offsetHeight;
                    targetContent.style.animation = null;
                });
            });
        });
    </script>
</body>
</html>
