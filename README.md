<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Tech Stack</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&family=JetBrains+Mono&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #020617;
            font-family: 'Plus Jakarta Sans', sans-serif;
            color: #f8fafc;
            background-image: 
                radial-gradient(circle at 0% 0%, rgba(79, 70, 229, 0.15) 0%, transparent 50%),
                radial-gradient(circle at 100% 100%, rgba(168, 85, 247, 0.15) 0%, transparent 50%);
        }

        .typing-animation {
            border-right: 3px solid #6366f1;
            white-space: nowrap;
            overflow: hidden;
            animation: typing 3.5s steps(30, end), blink .75s step-end infinite;
        }

        @keyframes typing { from { width: 0 } to { width: 100% } }
        @keyframes blink { from, to { border-color: transparent } 50% { border-color: #6366f1 } }

        .glass {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }

        .glass:hover {
            border-color: rgba(99, 102, 241, 0.5);
            box-shadow: 0 0 30px rgba(79, 70, 229, 0.1);
        }

        .badge {
            padding: 4px 12px;
            border-radius: 9999px;
            font-size: 0.75rem;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center p-6 md:p-12">

    <header class="w-full max-w-4xl flex flex-col md:flex-row justify-between items-center gap-8 mb-16">
        <div class="flex items-center gap-6">
            <div class="flex flex-col items-center">
                <svg width="60" height="60" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="50" cy="50" r="45" stroke="#6366f1" stroke-width="2" stroke-dasharray="10 5"/>
                    <path d="M30 50L45 35L70 60L55 75L30 50Z" fill="#6366f1" fill-opacity="0.8"/>
                    <rect x="40" y="40" width="20" height="20" rx="4" fill="white"/>
                </svg>
                <span class="text-[10px] font-black mt-2 tracking-[0.3em] text-indigo-400 uppercase">NwareLink</span>
            </div>
            
            <div class="h-10 w-[1px] bg-slate-800"></div>

            <div class="flex flex-col items-center">
                <svg width="60" height="60" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M50 15L85 75H15L50 15Z" stroke="#f43f5e" stroke-width="4" stroke-linejoin="round"/>
                    <path d="M50 35L70 70H30L50 35Z" fill="#f43f5e"/>
                </svg>
                <span class="text-[10px] font-black mt-2 tracking-[0.3em] text-rose-500 uppercase">Delta Project</span>
            </div>
        </div>

        <div class="text-center md:text-right">
            <h1 class="text-4xl md:text-5xl font-black tracking-tighter mb-2">
                <span class="text-white">Software</span><span class="text-indigo-500">Engineer</span>
            </h1>
            <div class="inline-block">
                <p class="typing-animation font-mono text-indigo-300 text-sm md:text-base">
                    > Executing high_performance_code.sh
                </p>
            </div>
        </div>
    </header>

    <section class="w-full max-w-4xl glass rounded-[2.5rem] p-8 mb-8 flex flex-col md:flex-row items-center gap-8">
        <div class="bg-white p-4 rounded-3xl">
            <svg width="80" height="80" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M20 20H80V35H35V45H75V60H35V70H80V85H20V20Z" fill="#e11d48"/>
                <rect x="10" y="10" width="80" height="80" stroke="#e11d48" stroke-width="2" rx="10"/>
            </svg>
        </div>
        <div class="text-center md:text-left">
            <span class="badge bg-rose-500/10 text-rose-500 mb-2 inline-block">Instituição de Ensino</span>
            <h2 class="text-3xl font-black text-white">ETEC</h2>
            <p class="text-slate-400 font-bold text-lg tracking-tight">Desenvolvimento de Sistemas</p>
        </div>
    </section>

    <main class="w-full max-w-4xl grid grid-cols-1 md:grid-cols-2 gap-6">
        
        <div class="glass rounded-[2rem] p-8">
            <div class="flex justify-between items-center mb-6">
                <h3 class="font-black text-sm uppercase tracking-widest text-slate-500">Linguagens</h3>
                <span class="h-2 w-2 rounded-full bg-yellow-400 animate-pulse"></span>
            </div>
            <div class="flex gap-6 items-center">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="JS">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="TS">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Dart">
            </div>
        </div>

        <div class="glass rounded-[2rem] p-8 border-l-4 border-indigo-500">
            <div class="flex justify-between items-center mb-6">
                <h3 class="font-black text-sm uppercase tracking-widest text-slate-500">Frameworks</h3>
                <span class="h-2 w-2 rounded-full bg-indigo-500"></span>
            </div>
            <div class="flex gap-6 items-center">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" class="w-12 h-12 animate-[spin_10s_linear_infinite]" alt="React">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Flutter">
                <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Tailwind">
            </div>
        </div>

        <div class="glass rounded-[2rem] p-8">
            <div class="flex justify-between items-center mb-6">
                <h3 class="font-black text-sm uppercase tracking-widest text-slate-500">Database</h3>
                <span class="h-2 w-2 rounded-full bg-emerald-500"></span>
            </div>
            <div class="flex gap-6 items-center">
                <img src="https://www.vectorlogo.zone/logos/supabase/supabase-icon.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Supabase">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Postgres">
            </div>
        </div>

        <div class="glass rounded-[2rem] p-8 border-r-4 border-purple-500">
            <div class="flex justify-between items-center mb-6">
                <h3 class="font-black text-sm uppercase tracking-widest text-slate-500">Web Infra</h3>
                <span class="h-2 w-2 rounded-full bg-purple-500"></span>
            </div>
            <div class="flex gap-6 items-center">
                <img src="https://www.vectorlogo.zone/logos/vitejs/vitejs-icon.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Vite">
                <svg width="40" height="40" viewBox="0 0 1155 1000" fill="white"><path d="M577.3 0L1154.7 1000H0L577.3 0Z"/></svg>
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" class="w-12 h-12 hover:scale-110 transition-transform" alt="Git">
            </div>
        </div>

    </main>

    <footer class="mt-16 text-slate-600 font-mono text-[10px] uppercase tracking-[0.5em]">
        &copy; 2026 Integrated System Development
    </footer>

</body>
</html>
