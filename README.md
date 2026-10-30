<!DOCTYPE html>
<html lang="ta" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARTOS DESIGN STUDIO | Architecture & Structural Engineering</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600;700;800&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#1e2022',
                            card: '#292c30',
                            charcoal: '#17191b',
                            gold: '#d8b26e',
                            goldLight: '#f3d399',
                            goldMuted: '#9e8048',
                            accent: '#4ade80'
                        }
                    },
                    fontFamily: {
                        heading: ['Cinzel', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #1a1c1e;
            color: #e5e7eb;
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-image: radial-gradient(circle at 10% 20%, rgba(216, 178, 110, 0.04) 0%, transparent 40%),
                              radial-gradient(circle at 90% 80%, rgba(74, 222, 128, 0.03) 0%, transparent 40%);
        }
        .gold-gradient-text {
            background: linear-gradient(135deg, #f7dfa5 0%, #d8b26e 50%, #b8862f 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gold-border {
            border-color: rgba(216, 178, 110, 0.25);
        }
        .gold-border-glow:hover {
            border-color: rgba(216, 178, 110, 0.65);
            box-shadow: 0 0 25px rgba(216, 178, 110, 0.15);
        }
        .card-bg {
            background: linear-gradient(145deg, #282b2f 0%, #202326 100%);
        }
        .blueprint-pattern {
            background-size: 30px 30px;
            background-image: 
                linear-gradient(to right, rgba(255, 255, 255, 0.02) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(255, 255, 255, 0.02) 1px, transparent 1px);
        }
    </style>
</head>
<body class="blueprint-pattern antialiased selection:bg-brand-gold selection:text-black min-h-screen flex flex-col justify-between">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-brand-dark/85 border-b border-white/10">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 py-3.5 flex items-center justify-between">
            <!-- Brand Logo -->
            <a href="#" class="flex items-center space-x-3 group">
                <div class="w-10 h-10 rounded-lg border border-brand-gold/60 flex items-center justify-center p-1.5 bg-brand-charcoal group-hover:border-brand-gold transition duration-300">
                    <!-- Geometric House / Artos Mark -->
                    <svg class="w-full h-full text-brand-gold" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M24 4L6 18v24h14v-12h8v12h14V18L24 4z"/>
                        <path d="M24 12v6"/>
                    </svg>
                </div>
                <div>
                    <span class="block text-lg font-heading tracking-widest font-bold gold-gradient-text leading-tight">ARTOS</span>
                    <span class="text-[10px] tracking-[0.25em] text-gray-400 uppercase">Design Studio</span>
                </div>
            </a>

            <!-- Quick Action Buttons -->
            <div class="flex items-center space-x-2 sm:space-x-3">
                <a href="tel:+917373135863" class="hidden sm:inline-flex items-center space-x-2 text-xs font-semibold uppercase tracking-wider px-3.5 py-2 rounded-full border border-brand-gold/40 hover:bg-brand-gold/10 text-brand-goldLight transition duration-200">
                    <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                    </svg>
                    <span>அழைக்க</span>
                </a>
                <a href="https://wa.me/917373135863" target="_blank" rel="noopener noreferrer" class="inline-flex items-center space-x-2 text-xs font-semibold px-4 py-2 rounded-full bg-emerald-600 hover:bg-emerald-500 text-white shadow-md shadow-emerald-950/40 transition duration-200">
                    <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24">
                        <path d="M12.031 6.172c-3.181 0-5.767 2.586-5.768 5.766-.001 1.298.38 2.27 1.019 3.287l-.711 2.592 2.654-.696c1 .587 1.78.893 2.806.893 3.182 0 5.767-2.587 5.768-5.766.001-3.182-2.585-5.776-5.768-5.776zm0-1.672c4.103 0 7.438 3.336 7.438 7.438 0 4.105-3.335 7.441-7.438 7.441-1.309 0-2.539-.344-3.609-.949l-4.422 1.158 1.182-4.305c-.688-1.121-1.051-2.434-1.051-3.783 0-4.102 3.335-7.438 7.438-7.438z"/>
                    </svg>
                    <span>WhatsApp</span>
                </a>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-4 sm:px-6 py-8 sm:py-14 space-y-16">
        
        <!-- Hero & Profile Section -->
        <section class="card-bg border gold-border rounded-2xl sm:rounded-3xl p-6 sm:p-10 shadow-2xl relative overflow-hidden">
            <!-- Ambient botanical accent background -->
            <div class="absolute -top-12 -right-12 w-48 h-48 bg-emerald-900/20 rounded-full blur-3xl pointer-events-none"></div>
            <div class="absolute -bottom-12 -left-12 w-48 h-48 bg-brand-gold/10 rounded-full blur-3xl pointer-events-none"></div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center relative z-10">
                <!-- Left Details -->
                <div class="lg:col-span-8 space-y-5">
                    <div class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-brand-gold/10 border border-brand-gold/30 text-brand-goldLight text-xs tracking-wider uppercase font-medium">
                        <span class="w-2 h-2 rounded-full bg-brand-accent animate-pulse"></span>
                        <span>Registered Engineer Grade - II</span>
                    </div>

                    <div>
                        <h1 class="text-3xl sm:text-5xl font-heading font-extrabold gold-gradient-text tracking-wide mb-2">
                            ARTOS DESIGN STUDIO
                        </h1>
                        <p class="text-xl sm:text-2xl font-semibold text-gray-200">
                            Er. S. SELVA PRAVIN <span class="text-brand-gold font-sans text-base">M.E.,</span>
                        </p>
                    </div>

                    <p class="text-gray-400 text-sm sm:text-base leading-relaxed max-w-2xl">
                        கட்டிட வரைபடம் (Planning), அரசு அங்கீகாரம் (Approval), கட்டமைப்பு வடிவமைப்பு (Structural Design) மற்றும் அழகியல் உள்துறை & வெளிப்புற வடிவமைப்பு (Interior & Exterior Design) வரை அனைத்து பணிகளையும் மிக நேர்த்தியாக செய்து தருகிறோம்.
                    </p>

                    <!-- Contact highlight chips -->
                    <div class="pt-3 flex flex-wrap gap-3 text-xs sm:text-sm text-gray-300">
                        <a href="tel:+917373135863" class="inline-flex items-center space-x-2 bg-brand-charcoal/80 hover:bg-brand-charcoal border border-brand-gold/30 hover:border-brand-gold px-4 py-2 rounded-xl transition duration-200">
                            <span class="text-brand-gold font-bold">📞</span>
                            <span>+91 73731 35863</span>
                        </a>
                        <a href="mailto:artosarkstudio@gmail.com" class="inline-flex items-center space-x-2 bg-brand-charcoal/80 hover:bg-brand-charcoal border border-brand-gold/30 hover:border-brand-gold px-4 py-2 rounded-xl transition duration-200">
                            <span class="text-brand-gold font-bold">✉️</span>
                            <span>artosarkstudio@gmail.com</span>
                        </a>
                        <span class="inline-flex items-center space-x-2 bg-brand-charcoal/60 border border-white/5 px-4 py-2 rounded-xl text-gray-400">
                            <span>📍 37/1, Manali, Thuckalay - 629175</span>
                        </span>
                    </div>
                </div>

                <!-- Right Quick Card / QR & Instagram -->
                <div class="lg:col-span-4 flex flex-col items-center justify-center p-6 bg-brand-charcoal/90 rounded-2xl border gold-border text-center space-y-4">
                    <div class="relative p-2 bg-white rounded-xl shadow-lg group">
                        <!-- Direct Instagram QR Visual -->
                        <img 
                            src="https://api.qrserver.com/v1/create-qr-code/?size=160x160&data=https://www.instagram.com/artos_design_studio/&color=1a1c1e" 
                            alt="Instagram QR - ARTOS DESIGN STUDIO"
                            class="w-36 h-36 rounded-lg object-contain mx-auto"
                            onerror="this.src='https://placehold.co/160x160/26292b/d8b26e?text=QR+Code'"
                        />
                    </div>
                    
                    <div class="space-y-1">
                        <p class="text-xs tracking-widest text-gray-400 uppercase font-semibold">Instagram Profile</p>
                        <a href="https://www.instagram.com/artos_design_studio/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center space-x-1.5 text-brand-gold hover:text-brand-goldLight font-semibold text-sm transition">
                            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                            </svg>
                            <span>@artos_design_studio</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Grid Section -->
        <section class="space-y-6">
            <div class="text-center max-w-xl mx-auto space-y-2">
                <span class="text-xs uppercase tracking-[0.3em] text-brand-gold font-semibold">எங்களின் சேவைகள்</span>
                <h2 class="text-2xl sm:text-3xl font-heading font-bold text-white">Our Architectural & Engineering Services</h2>
                <div class="w-16 h-0.5 bg-brand-gold mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5 pt-4">
                
                <!-- 1. Planning -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-brand-gold">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Planning</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        வாஸ்து முறைப்படி, நவீன வசதிகளுடன் கூடிய துல்லியமான பிளான் தயாரித்தல்.
                    </p>
                </div>

                <!-- 2. Approval -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-emerald-400">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Approval</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        பஞ்சாயத்து, நகராட்சி மற்றும் DTCP அப்ரூவல் வரைபடங்கள் பெறுவதற்கான வழிகாட்டல்.
                    </p>
                </div>

                <!-- 3. Architecture -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-brand-gold">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Architecture</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        அழகியல், சூரிய வெளிச்சம் மற்றும் காற்றோட்டம் நிறைந்த தனித்துவமான நவீன வடிவமைப்பு.
                    </p>
                </div>

                <!-- 4. Survey -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-amber-300">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <circle cx="12" cy="12" r="3" stroke-width="2"/>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M12 2v4m0 12v4M2 12h4m12 0h4m-5.636-6.364l2.828-2.828M6.343 17.657l-2.828 2.828m0-14.142l2.828 2.828m11.314 11.314l2.828 2.828"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Survey</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        அதிநவீன கருவிகள் கொண்டு இடத்தின் துல்லியமான எல்லை அளவீடு மற்றும் நில அளவை.
                    </p>
                </div>

                <!-- 5. Structural Design -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-brand-gold">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M4 6h16M4 12h16m-7 6h7M7 6v12m10-12v12"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Structural Design</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        நிலநடுக்கம் தாங்கும் திறன் மற்றும் பாதுகாப்பு விதிமுறைகளுக்குட்பட்ட தூண் & கம்பி கட்டமைப்பு.
                    </p>
                </div>

                <!-- 6. Interior Design -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-brand-gold">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Interior Design</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        வீட்டின் உள் அலங்காரம், மாடுலர் கிச்சன், சீலிங் மற்றும் பிரத்யேக மரவேலைகள் வடிவமைப்பு.
                    </p>
                </div>

                <!-- 7. Exterior Design -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-brand-gold">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Exterior Design</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        கண்ணைக் கவரும் 3D எலிவேஷன் மற்றும் கண்கவர் வெளிப்புற வண்ணத் தேர்வுகள்.
                    </p>
                </div>

                <!-- 8. Landscape -->
                <div class="card-bg border gold-border rounded-xl p-6 hover:-translate-y-1 gold-border-glow transition duration-300">
                    <div class="w-12 h-12 rounded-lg bg-brand-charcoal border border-brand-gold/40 flex items-center justify-center mb-4 text-emerald-400">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M5 3v18m0 0h14m-14 0a5 5 0 015-5h4a5 5 0 015 5m-9-14a4 4 0 100-8 4 4 0 000 8zm0 0v5"/>
                        </svg>
                    </div>
                    <h3 class="font-heading font-bold text-lg text-brand-goldLight mb-1">Landscape</h3>
                    <p class="text-gray-400 text-xs sm:text-sm leading-relaxed">
                        இயற்கையோடு இணைந்த புல்வெளி, நடைபாதை மற்றும் பசுமையான கார்டன் வடிவமைப்பு.
                    </p>
                </div>

            </div>
        </section>

        <!-- Direct Contact Action Bar -->
        <section class="card-bg border gold-border rounded-2xl p-6 sm:p-8">
            <div class="text-center max-w-2xl mx-auto space-y-4">
                <h3 class="text-2xl font-heading font-bold text-brand-goldLight">உங்கள் கனவு இல்லத்தை உருவாக்கத் தயாரா?</h3>
                <p class="text-gray-300 text-sm">
                    இன்றே எங்களைத் தொடர்பு கொண்டு உங்கள் திட்டத்திற்கான இலவச ஆலோசனையைப் பெறுங்கள்.
                </p>
                <div class="pt-2 flex flex-col sm:flex-row items-center justify-center gap-3">
                    <a href="tel:+917373135863" class="w-full sm:w-auto inline-flex items-center justify-center space-x-3 px-6 py-3.5 rounded-xl bg-gradient-to-r from-brand-gold to-brand-goldMuted text-brand-dark font-bold hover:brightness-110 shadow-lg shadow-black/50 transition">
                        <svg class="w-5 h-5 fill-current" viewBox="0 0 20 20">
                            <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 4V3z"/>
                        </svg>
                        <span>+91 73731 35863 ஐ அழைக்கவும்</span>
                    </a>
                    <a href="https://wa.me/917373135863?text=வணக்கம்,%20ARTOS%20Design%20Studio%20பற்றி%20தெரிந்து%20கொள்ள%20விரும்புகிறேன்." target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto inline-flex items-center justify-center space-x-3 px-6 py-3.5 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white font-semibold transition">
                        <span>WhatsApp-ல் பேச</span>
                    </a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-white/10 bg-brand-charcoal py-8 mt-12">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-center justify-between text-xs text-gray-400 gap-4">
            <div>
                <p class="font-heading font-bold text-gray-300">ARTOS DESIGN STUDIO</p>
                <p>37/1, Manali, Thuckalay - 629175</p>
            </div>
            <div class="flex items-center space-x-4">
                <a href="https://www.instagram.com/artos_design_studio/" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition">Instagram</a>
                <span>•</span>
                <a href="mailto:artosarkstudio@gmail.com" class="hover:text-brand-gold transition">Email</a>
                <span>•</span>
                <a href="tel:+917373135863" class="hover:text-brand-gold transition">Phone</a>
            </div>
            <div class="text-gray-500">
                &copy; ARTOS Design Studio. All rights reserved.
            </div>
        </div>
    </footer>

</body>
</html>
