# ZoomintoEnglish[index.html](https://github.com/user-attachments/files/25613104/index.html)
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zoom into English - Instituto de Inglés</title>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --verde-claro: #90EE90;
            --celeste: #00BFFF;
            --violeta: #8A2BE2;
        }
        
        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #f8fdff;
            color: #333;
        }

        .font-fredoka { font-family: 'Fredoka One', cursive; }

        .hero-gradient {
            background: linear-gradient(135deg, var(--celeste) 0%, var(--violeta) 100%);
            min-height: 60vh;
            position: relative;
        }

        .btn-3d {
            transition: all 0.2s ease;
            box-shadow: 0 4px 0 rgb(0 0 0 / 0.15);
        }

        .btn-3d:active {
            transform: translateY(4px);
            box-shadow: none;
        }

        .btn-whatsapp-celeste { background-color: var(--celeste); border-bottom: 4px solid #0099cc; }
        .btn-whatsapp-bordo { background-color: #800000; border-bottom: 4px solid #600000; }
        .btn-whatsapp-violeta { background-color: var(--violeta); border-bottom: 4px solid #6a1bb1; }
        .btn-calendar-verde { background-color: #32CD32; border-bottom: 4px solid #28a428; }

        .tag-verde { background-color: #e6ffed; border: 1px solid var(--verde-claro); color: #2d6a4f; }
        
        .floating-study {
            position: absolute;
            opacity: 0.2;
            animation: float 4s ease-in-out infinite;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(5deg); }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero-gradient text-white flex flex-col items-center justify-center px-4 py-16 relative overflow-hidden">
        <!-- Background Study Icons (Floating) -->
        <span class="floating-study text-6xl top-10 left-10">📖</span>
        <span class="floating-study text-6xl top-40 right-10" style="animation-delay: 1s;">🎓</span>
        <span class="floating-study text-6xl bottom-10 left-20" style="animation-delay: 2s;">✍️</span>
        <span class="floating-study text-6xl bottom-20 right-20" style="animation-delay: 1.5s;">💡</span>

        <div class="bg-white p-5 rounded-2xl shadow-2xl mb-8 max-w-[320px]">
             <!-- Reemplazar con URL real de tu logo -->
             <img src="https://i.ibb.co/Xf8zXWd/logo-zoom-into-english.png" alt="Zoom into English Logo" class="w-full" onerror="this.src='https://placehold.co/400x120/ffffff/8A2BE2?text=Zoom+into+English'">
        </div>

        <h1 class="font-fredoka text-4xl md:text-6xl text-center mb-6 drop-shadow-md">
            ¡Inglés para todas las edades y niveles!
        </h1>
        <p class="text-xl md:text-2xl text-center font-semibold bg-white/10 border border-white/30 backdrop-blur-md px-8 py-3 rounded-2xl">
            Clases virtuales personalizadas e individuales 💻📚
        </p>
    </section>

    <!-- Sección Calendario -->
    <section class="max-w-4xl mx-auto -mt-12 mb-16 px-4 relative z-20">
        <div class="bg-white rounded-[2.5rem] shadow-2xl p-8 md:p-12 border-b-8 border-r-8 border-[#00BFFF]">
            <h2 class="font-fredoka text-3xl text-center text-[#800000] mb-8">
                📅 RESERVÁ TU CLASE GRATIS
            </h2>
            
            <div class="flex flex-col items-center">
                <a href="https://calendar.app.google/dD9rm5zqra27Gazp6" target="_blank" class="btn-3d btn-calendar-verde text-white font-fredoka text-2xl px-12 py-6 rounded-2xl text-center w-full max-w-lg hover:scale-105">
                    AGENDAR EN GOOGLE CALENDAR →
                </a>
                
                <div class="mt-8 text-center bg-blue-50 w-full p-6 rounded-2xl">
                    <p class="text-gray-700 font-bold text-xl mb-2">🕒 Horarios Disponibles:</p>
                    <p class="text-[#8A2BE2] font-fredoka text-2xl">
                        Miércoles, Jueves y Viernes
                    </p>
                    <p class="text-gray-600 font-bold text-lg mt-1">
                        8:30 a 11:30hs | 15:00 a 20:00hs
                    </p>
                </div>

                <div class="mt-6 flex items-center gap-2 text-[#2d6a4f] font-bold text-lg bg-[#e6ffed] px-6 py-2 rounded-full border border-[#90EE90]">
                    <span>🎁</span> ¡TODO EL MATERIAL ESTÁ INCLUIDO!
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Niveles y Grupos -->
    <section class="max-w-6xl mx-auto px-4 mb-20">
        <h2 class="font-fredoka text-3xl md:text-4xl text-center text-[#8A2BE2] mb-10">Nuestras Propuestas de Estudio</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            <div class="bg-white border-2 border-[#00BFFF] p-6 rounded-2xl text-center shadow-lg hover:bg-blue-50 transition-colors">
                <span class="text-3xl block mb-2">🏫</span>
                <p class="font-fredoka text-[#00BFFF]">Apoyo Escolar</p>
            </div>
            <div class="bg-white border-2 border-[#8A2BE2] p-6 rounded-2xl text-center shadow-lg hover:bg-purple-50 transition-colors">
                <span class="text-3xl block mb-2">🌱</span>
                <p class="font-fredoka text-[#8A2BE2]">Principiantes</p>
            </div>
            <div class="bg-white border-2 border-[#90EE90] p-6 rounded-2xl text-center shadow-lg hover:bg-green-50 transition-colors">
                <span class="text-3xl block mb-2">📈</span>
                <p class="font-fredoka text-[#2d6a4f]">Intermedio</p>
            </div>
            <div class="bg-white border-2 border-[#800000] p-6 rounded-2xl text-center shadow-lg hover:bg-red-50 transition-colors">
                <span class="text-3xl block mb-2">🏆</span>
                <p class="font-fredoka text-[#800000]">Avanzado</p>
            </div>
            <div class="bg-white border-2 border-[#8A2BE2] p-6 rounded-2xl text-center shadow-lg hover:bg-purple-50 transition-colors">
                <span class="text-3xl block mb-2">🗣️</span>
                <p class="font-fredoka text-[#8A2BE2]">Práctica del Habla</p>
            </div>
            <div class="bg-white border-2 border-[#00BFFF] p-6 rounded-2xl text-center shadow-lg hover:bg-blue-50 transition-colors">
                <span class="text-3xl block mb-2">👥</span>
                <p class="font-fredoka text-[#00BFFF]">Clases Grupales</p>
            </div>
            <div class="bg-white border-2 border-[#90EE90] p-6 rounded-2xl text-center shadow-lg hover:bg-green-50 transition-colors">
                <span class="text-3xl block mb-2">👤</span>
                <p class="font-fredoka text-[#2d6a4f]">Individuales</p>
            </div>
            <div class="bg-white border-2 border-[#8A2BE2] p-6 rounded-2xl text-center shadow-lg hover:bg-purple-50 transition-colors flex items-center justify-center">
                <p class="font-fredoka text-gray-400">¡Y mucho más!</p>
            </div>
        </div>
    </section>

    <!-- Sección WhatsApp -->
    <section class="max-w-6xl mx-auto px-4 mb-20">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <a href="https://wa.me/5491157403841?text=Hola%20Melina,%20quiero%20informacion%20sobre%20las%20clases%20de%20ingles!!" target="_blank" 
               class="btn-3d btn-whatsapp-celeste text-white font-fredoka p-8 rounded-3xl flex flex-col items-center justify-center text-center hover:scale-105">
                <span class="text-5xl mb-3">💬</span>
                <span class="text-xl">Quiero Información de Clases</span>
            </a>

            <a href="https://wa.me/5491157403841?text=Hola%20Melina%20ya%20agende%20mi%20cita%20para%20las%20clases%20de%20ingles!!" target="_blank" 
               class="btn-3d btn-whatsapp-bordo text-white font-fredoka p-8 rounded-3xl flex flex-col items-center justify-center text-center hover:scale-105">
                <span class="text-5xl mb-3">✅</span>
                <span class="text-xl">Confirmar mi Cita</span>
            </a>

            <a href="https://wa.me/5491157403841" target="_blank" 
               class="btn-3d btn-whatsapp-violeta text-white font-fredoka p-8 rounded-3xl flex flex-col items-center justify-center text-center hover:scale-105">
                <span class="text-5xl mb-3">🧠</span>
                <span class="text-xl">Chatear Ahora</span>
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-12 px-4 text-center border-t-4 border-[#00BFFF]">
        <div class="max-w-4xl mx-auto">
            <div class="flex flex-col md:flex-row justify-center gap-8 mb-8 text-lg font-semibold text-gray-700">
                <span>📱 WhatsApp: 1157403841</span>
                <span>📧 Email: zoomintoeng@gmail.com</span>
            </div>
            <div class="w-24 h-1 bg-[#8A2BE2] mx-auto mb-6"></div>
            <p class="text-gray-500 font-fredoka text-xl">📍 Merlo, Buenos Aires 2026</p>
        </div>
    </footer>

</body>
</html>
