<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sithandra Scarface | Command Center</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #0a0a0a; color: #e5e5e5; font-family: 'Courier New', Courier, monospace; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .security-glow { box-shadow: 0 0 15px rgba(16, 185, 129, 0.2); border: 1px solid #10b981; }
    </style>
</head>
<body class="p-4 md:p-10">

    <header class="mb-12 text-center">
        <h1 class="text-3xl font-bold tracking-widest uppercase text-white">Sithandra <span class="text-emerald-500">Scarface</span></h1>
        <p class="text-xs text-gray-500 mt-2">MOBILE DEVELOPER | MARKET ANALYST | AUTHOR</p>
    </header>

    <main class="max-w-4xl mx-auto space-y-8">
        
        <section class="glass p-6 rounded-2xl security-glow">
            <div class="flex flex-col md:flex-row items-center gap-6">
                <div class="flex-1">
                    <span class="bg-emerald-900 text-emerald-300 text-[10px] px-2 py-1 rounded mb-2 inline-block font-bold">ACTIVE PROJECT</span>
                    <h2 class="text-2xl font-bold text-white mb-2">Scar Shield</h2>
                    <p class="text-sm text-gray-400 mb-4">Advanced mobile security vault featuring biometric authentication and encrypted file protection. Built for privacy-conscious users.</p>
                    <button class="bg-emerald-600 hover:bg-emerald-500 text-white text-sm py-2 px-6 rounded-lg transition">View Documentation</button>
                </div>
                <div class="w-32 h-32 bg-gray-800 rounded-xl flex items-center justify-center border border-gray-700">
                    <span class="text-4xl text-emerald-500">🛡️</span>
                </div>
            </div>
        </section>

        <section class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="glass p-6 rounded-2xl">
                <h3 class="text-lg font-bold text-white mb-3">Sithandra Array</h3>
                <p class="text-xs text-gray-500 mb-4">Institutional Core Trading (ICT) and Smart Money Concepts framework applied to XAUUSD and Synthetic Indices.</p>
                <ul class="text-[11px] space-y-2 text-emerald-400">
                    <li>> Price Action Analysis</li>
                    <li>> Liquidity Sweep Monitoring</li>
                    <li>> Fair Value Gap (FVG) Identification</li>
                </ul>
            </div>

            <div class="glass p-6 rounded-2xl border-l-2 border-gray-500">
                <h3 class="text-lg font-bold text-white mb-3">Out of the Shadows</h3>
                <p class="text-xs text-gray-500 mb-4">A journey through development, strategy, and self-mastery. Coming soon to digital platforms.</p>
                <div class="h-1 bg-gray-800 w-full mt-4">
                    <div class="bg-gray-400 h-1 w-1/3"></div>
                </div>
                <p class="text-[10px] text-gray-600 mt-1">35% COMPLETE</p>
            </div>
        </section>

    </main>

    <footer class="mt-20 text-center text-[10px] text-gray-700 uppercase tracking-widest">
        &copy; 2026 Sithandra Scarface | Built with Termux & Logic
    </footer>

</body>
</html>
