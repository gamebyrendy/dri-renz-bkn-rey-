# dri-renz-bkn-rey
<!doctype html>
<html lang="id" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Roasting Teman Mati Topik</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700;800&amp;display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Outfit', sans-serif; }
    
    @keyframes float {
      0%, 100% { transform: translateY(0) rotate(0deg); }
      50% { transform: translateY(-20px) rotate(5deg); }
    }
    
    @keyframes shake {
      0%, 100% { transform: translateX(0); }
      25% { transform: translateX(-5px) rotate(-5deg); }
      75% { transform: translateX(5px) rotate(5deg); }
    }
    
    @keyframes pulse-glow {
      0%, 100% { box-shadow: 0 0 20px rgba(255, 107, 107, 0.3); }
      50% { box-shadow: 0 0 40px rgba(255, 107, 107, 0.6); }
    }
    
    @keyframes slide-up {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    .float-animation { animation: float 3s ease-in-out infinite; }
    .shake-animation { animation: shake 0.5s ease-in-out; }
    .pulse-glow { animation: pulse-glow 2s ease-in-out infinite; }
    .slide-up { animation: slide-up 0.6s ease-out forwards; }
    
    .card-hover:hover {
      transform: translateY(-8px) scale(1.02);
      box-shadow: 0 20px 40px rgba(0,0,0,0.2);
    }
    
    .monkey-emoji {
      display: inline-block;
      animation: float 2s ease-in-out infinite;
    }
    
    .chat-bubble {
      position: relative;
    }
    
    .chat-bubble::before {
      content: '';
      position: absolute;
      bottom: -10px;
      left: 20px;
      border-width: 10px;
      border-style: solid;
      border-color: #25D366 transparent transparent transparent;
    }
    
    .gradient-text {
      background: linear-gradient(135deg, #FF6B6B, #FFE66D);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
  </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full">
  <div id="app-container" class="min-h-full w-full overflow-auto" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);"><!-- Header Section -->
   <header class="text-center py-12 px-4">
    <div class="float-animation text-8xl mb-6">
     🙊
    </div>
    <h1 id="main-title" class="text-4xl md:text-6xl font-extrabold gradient-text mb-4">TEMAN MATI TOPIK</h1>
    <p class="text-xl md:text-2xl text-gray-300">Dedikasi untuk <span id="friend-name" class="text-yellow-400 font-bold">Si Monyet</span> yang selalu bikin chat jadi kuburan 💀</p>
   </header><!-- Main Content -->
   <main class="max-w-6xl mx-auto px-4 pb-16"><!-- Hero Card -->
    <div class="bg-gradient-to-br from-red-500/20 to-orange-500/20 backdrop-blur-sm rounded-3xl p-8 mb-12 border border-red-500/30 pulse-glow">
     <div class="text-center">
      <div class="text-6xl mb-4">
       📱💀
      </div>
      <h2 class="text-2xl md:text-3xl font-bold text-white mb-4">"Oh" "Iya" "Wkwk" "Hmm"</h2>
      <p class="text-gray-300 text-lg">4 kata ajaib yang mampu membunuh semua percakapan di muka bumi</p>
     </div>
    </div><!-- Roasting Cards -->
    <div class="grid md:grid-cols-2 gap-6 mb-12"><!-- Card 1 -->
     <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 card-hover transition-all duration-300 border border-white/20 slide-up" style="animation-delay: 0.1s;">
      <div class="text-5xl mb-4">
       🪦
      </div>
      <h3 class="text-xl font-bold text-white mb-3">Pembunuh Topik Profesional</h3>
      <p class="text-gray-300">Chat bersamanya = menghadiri pemakaman percakapan. RIP topik seru, kamu akan dikenang. 🕯️</p>
     </div><!-- Card 2 -->
     <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 card-hover transition-all duration-300 border border-white/20 slide-up" style="animation-delay: 0.2s;">
      <div class="text-5xl mb-4">
       🏜️
      </div>
      <h3 class="text-xl font-bold text-white mb-3">Padang Pasir WA</h3>
      <p class="text-gray-300">Chat history-nya lebih gersang dari Sahara. Tumbleweed aja males lewat. 🌵</p>
     </div><!-- Card 3 -->
     <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 card-hover transition-all duration-300 border border-white/20 slide-up" style="animation-delay: 0.3s;">
      <div class="text-5xl mb-4">
       🧱
      </div>
      <h3 class="text-xl font-bold text-white mb-3">Tembok Besar China</h3>
      <p class="text-gray-300">Ngobrol sama dia kayak ngomong sama tembok. Bedanya, tembok masih bisa dipantulkan suaranya. 🗣️</p>
     </div><!-- Card 4 -->
     <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 card-hover transition-all duration-300 border border-white/20 slide-up" style="animation-delay: 0.4s;">
      <div class="text-5xl mb-4">
       🎤
      </div>
      <h3 class="text-xl font-bold text-white mb-3">Interviewer Gagal</h3>
      <p class="text-gray-300">Kalau dia jadi host podcast, episode pertama langsung episode terakhir. 🎙️❌</p>
     </div>
    </div><!-- WhatsApp Chat Simulation -->
    <div class="bg-gradient-to-br from-green-900/40 to-green-700/20 rounded-3xl p-6 mb-12 border border-green-500/30">
     <h2 class="text-2xl font-bold text-white mb-6 text-center">📱 Simulasi Chat WA dengan Si Mati Topik</h2>
     <div class="max-w-md mx-auto space-y-4"><!-- Your message -->
      <div class="flex justify-end">
       <div class="bg-green-600 text-white px-4 py-2 rounded-2xl rounded-br-md max-w-xs">
        Bro, kemarin gue nonton film keren banget! Ceritanya tentang...
       </div>
      </div><!-- Their reply -->
      <div class="flex justify-start">
       <div class="bg-gray-700 text-white px-4 py-2 rounded-2xl rounded-bl-md">
        Oh
       </div>
      </div><!-- Your message -->
      <div class="flex justify-end">
       <div class="bg-green-600 text-white px-4 py-2 rounded-2xl rounded-br-md max-w-xs">
        Terus plot twistnya gila! Lo harus nonton deh
       </div>
      </div><!-- Their reply -->
      <div class="flex justify-start">
       <div class="bg-gray-700 text-white px-4 py-2 rounded-2xl rounded-bl-md">
        Iya
       </div>
      </div><!-- Your message -->
      <div class="flex justify-end">
       <div class="bg-green-600 text-white px-4 py-2 rounded-2xl rounded-br-md max-w-xs">
        Lo lagi ngapain sekarang?
       </div>
      </div><!-- Their reply -->
      <div class="flex justify-start">
       <div class="bg-gray-700 text-white px-4 py-2 rounded-2xl rounded-bl-md">
        Gak ngapa-ngapain
       </div>
      </div><!-- Dead chat indicator -->
      <div class="text-center py-4"><span class="bg-red-500/20 text-red-400 px-4 py-2 rounded-full text-sm font-medium"> 💀 TOPIK TELAH MATI 💀 </span>
      </div>
     </div>
    </div><!-- Quotes Section -->
    <div class="bg-gradient-to-r from-yellow-500/20 to-orange-500/20 rounded-3xl p-8 mb-12 border border-yellow-500/30">
     <h2 class="text-2xl md:text-3xl font-bold text-center text-white mb-8">💬 Kata-Kata Mutiara untuk Si Mati Topik</h2>
     <div class="space-y-6">
      <blockquote class="bg-black/30 rounded-2xl p-6 border-l-4 border-yellow-400">
       <p class="text-lg text-gray-200 italic mb-2">"Carilah topik, kawan! Biar chatmu bisa pajang lebar, bukan cuma 'wkwk' doang yang nongol di notifikasi."</p><cite class="text-yellow-400 font-medium">— Korban Mati Topik</cite>
      </blockquote>
      <blockquote class="bg-black/30 rounded-2xl p-6 border-l-4 border-pink-400">
       <p class="text-lg text-gray-200 italic mb-2">"Chat sama kamu kayak main ping pong sendirian. Bolanya gue lempar, lu tangkep terus disimpen. Mana serunyaaa?"</p><cite class="text-pink-400 font-medium">— Teman yang Capek</cite>
      </blockquote>
      <blockquote class="bg-black/30 rounded-2xl p-6 border-l-4 border-cyan-400">
       <p class="text-lg text-gray-200 italic mb-2">"Topik itu kayak tanaman, harus disiram biar tumbuh. Kalau cuma 'hmm' 'oh' 'iya', ya layu dong chatnya!"</p><cite class="text-cyan-400 font-medium">— Guru Ngobrol Sejati</cite>
      </blockquote>
      <blockquote class="bg-black/30 rounded-2xl p-6 border-l-4 border-green-400">
       <p class="text-lg text-gray-200 italic mb-2">"WA-mu sepi bukan karena gak ada yang chat, tapi karena semua sudah trauma sama balasanmu yang kayak robot rusak."</p><cite class="text-green-400 font-medium">— Mantan Teman Chat</cite>
      </blockquote>
      <blockquote class="bg-black/30 rounded-2xl p-6 border-l-4 border-purple-400">
       <p class="text-lg text-gray-200 italic mb-2">"Kalau mau chat history-mu panjang bak novel, belajarlah ngobrol! Jangan cuma jadi batu karang di lautan percakapan."</p><cite class="text-purple-400 font-medium">— Pejuang Anti Mati Topik</cite>
      </blockquote>
     </div>
    </div><!-- Tips Section -->
    <div class="bg-gradient-to-br from-blue-500/20 to-purple-500/20 rounded-3xl p-8 border border-blue-500/30">
     <h2 class="text-2xl md:text-3xl font-bold text-center text-white mb-8">📚 Tips Biar Gak Jadi Pembunuh Topik</h2>
     <div class="grid md:grid-cols-2 gap-4">
      <div class="flex items-start gap-4 bg-black/20 rounded-xl p-4"><span class="text-3xl">1️⃣</span>
       <div>
        <h4 class="font-bold text-white mb-1">Tanya Balik!</h4>
        <p class="text-gray-300 text-sm">Jangan cuma jawab, kasih pertanyaan juga biar nyambung terus.</p>
       </div>
      </div>
      <div class="flex items-start gap-4 bg-black/20 rounded-xl p-4"><span class="text-3xl">2️⃣</span>
       <div>
        <h4 class="font-bold text-white mb-1">Share Cerita!</h4>
        <p class="text-gray-300 text-sm">Bagi pengalaman lo, jangan pelit cerita kayak pelit kuota.</p>
       </div>
      </div>
      <div class="flex items-start gap-4 bg-black/20 rounded-xl p-4"><span class="text-3xl">3️⃣</span>
       <div>
        <h4 class="font-bold text-white mb-1">Ekspresif Dikit!</h4>
        <p class="text-gray-300 text-sm">Pakai emoji, sticker, atau gif. Jangan kering kayak kerupuk.</p>
       </div>
      </div>
      <div class="flex items-start gap-4 bg-black/20 rounded-xl p-4"><span class="text-3xl">4️⃣</span>
       <div>
        <h4 class="font-bold text-white mb-1">Kembangkan Topik!</h4>
        <p class="text-gray-300 text-sm">Dari satu topik bisa ke mana-mana. Jangan stuck di zona aman!</p>
       </div>
      </div>
     </div>
    </div>
   </main><!-- Footer -->
   <footer class="text-center py-8 border-t border-white/10">
    <p class="text-gray-400 mb-2">Dibuat dengan 💔 oleh korban mati topik</p>
    <p class="text-2xl"><span class="monkey-emoji">🙈</span> <span class="monkey-emoji" style="animation-delay: 0.3s;">🙉</span> <span class="monkey-emoji" style="animation-delay: 0.6s;">🙊</span></p>
    <p class="text-gray-500 text-sm mt-4">Semoga yang membaca ini bukan si mati topik... atau mungkin emang dia 👀</p>
   </footer>
  </div>
  <script>
    const defaultConfig = {
      main_title: "TEMAN MATI TOPIK",
      friend_name: "Si Monyet",
      background_color: "#1a1a2e",
      text_color: "#ffffff",
      accent_color: "#FF6B6B",
      secondary_color: "#FFE66D",
      surface_color: "#16213e",
      font_family: "Outfit",
      font_size: 16
    };

    async function onConfigChange(config) {
      const titleEl = document.getElementById('main-title');
      const nameEl = document.getElementById('friend-name');
      const container = document.getElementById('app-container');
      
      if (titleEl) {
        titleEl.textContent = config.main_title || defaultConfig.main_title;
      }
      
      if (nameEl) {
        nameEl.textContent = config.friend_name || defaultConfig.friend_name;
      }
      
      // Apply font
      const fontFamily = config.font_family || defaultConfig.font_family;
      document.body.style.fontFamily = `${fontFamily}, sans-serif`;
      
      // Apply font size scaling
      const baseSize = config.font_size || defaultConfig.font_size;
      document.body.style.fontSize = `${baseSize}px`;
    }

    function mapToCapabilities(config) {
      return {
        recolorables: [
          {
            get: () => config.background_color || defaultConfig.background_color,
            set: (value) => {
              config.background_color = value;
              window.elementSdk.setConfig({ background_color: value });
            }
          },
          {
            get: () => config.surface_color || defaultConfig.surface_color,
            set: (value) => {
              config.surface_color = value;
              window.elementSdk.setConfig({ surface_color: value });
            }
          },
          {
            get: () => config.text_color || defaultConfig.text_color,
            set: (value) => {
              config.text_color = value;
              window.elementSdk.setConfig({ text_color: value });
            }
          },
          {
            get: () => config.accent_color || defaultConfig.accent_color,
            set: (value) => {
              config.accent_color = value;
              window.elementSdk.setConfig({ accent_color: value });
            }
          },
          {
            get: () => config.secondary_color || defaultConfig.secondary_color,
            set: (value) => {
              config.secondary_color = value;
              window.elementSdk.setConfig({ secondary_color: value });
            }
          }
        ],
        borderables: [],
        fontEditable: {
          get: () => config.font_family || defaultConfig.font_family,
          set: (value) => {
            config.font_family = value;
            window.elementSdk.setConfig({ font_family: value });
          }
        },
        fontSizeable: {
          get: () => config.font_size || defaultConfig.font_size,
          set: (value) => {
            config.font_size = value;
            window.elementSdk.setConfig({ font_size: value });
          }
        }
      };
    }

    function mapToEditPanelValues(config) {
      return new Map([
        ["main_title", config.main_title || defaultConfig.main_title],
        ["friend_name", config.friend_name || defaultConfig.friend_name]
      ]);
    }

    // Initialize SDK
    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities,
        mapToEditPanelValues
      });
    }
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9d45726f92126bc9',t:'MTc3MjE3MTg3MC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
