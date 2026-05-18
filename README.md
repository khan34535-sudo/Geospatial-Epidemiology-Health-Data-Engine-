<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asia Khan | BERM v2.0 Global Health Engine</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #0f172a; color: #f8fafc; font-family: 'Inter', sans-serif; }
        .glass-panel { background: rgba(30, 41, 59, 0.7); border: 1px solid rgba(255, 255, 255, 0.1); backdrop-filter: blur(10px); }
        .risk-badge { padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.7rem; }
    </style>
</head>
<body class="p-6 h-screen flex flex-col justify-between overflow-hidden">

    <header class="flex justify-between items-end border-b border-slate-700 pb-4 mb-4">
        <div>
            <h1 class="text-2xl font-bold text-white tracking-tight">Geospatial Epidemiology & Health Data Engine (BERM v2.0)</h1>
            <p class="text-blue-400 font-medium">Asia Khan | Senior UX Researcher & Digital Architect</p>
        </div>
        <div class="text-right text-xs text-slate-400">
            <p>Honours Mohawk/McMaster Pre-Health Science</p>
            <p>Honours BA McMaster University (Anthropology & Social Psychology)</p>
        </div>
    </header>

    <main class="grid grid-cols-12 gap-6 flex-grow overflow-hidden">
        
        <section class="col-span-7 flex flex-col">
            <h2 class="text-sm font-bold uppercase tracking-widest text-slate-500 mb-3"><i class="fas fa-globe-americas mr-2"></i>Global Exposure Strategic Matrix</h2>
            <div class="glass-panel rounded-lg overflow-hidden flex-grow">
                <table class="w-full text-left text-xs">
                    <thead class="bg-slate-800 text-slate-400 uppercase text-[10px]">
                        <tr>
                            <th class="p-3">Region</th>
                            <th class="p-3">Risk Level</th>
                            <th class="p-3">Biocultural & Ecological Hazards</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-700">
                        <tr>
                            <td class="p-3 font-semibold">North America</td>
                            <td class="p-3"><span class="risk-badge bg-orange-600">MODERATE</span></td>
                            <td class="p-3 text-slate-300">Lyme expansion, RMSF, Giant Hogweed, Tick spikes.</td>
                        </tr>
                        <tr>
                            <td class="p-3 font-semibold">Europe</td>
                            <td class="p-3"><span class="risk-badge bg-yellow-600">LOW-MOD</span></td>
                            <td class="p-3 text-slate-300">TBE (Alps), Lyme, CCHF, Mediterranean Spotted Fever.</td>
                        </tr>
                        <tr>
                            <td class="p-3 font-semibold">Asia</td>
                            <td class="p-3"><span class="risk-badge bg-red-600 text-white">HIGH</span></td>
                            <td class="p-3 text-slate-300">SFTS (Tick), Kyasanur Forest, Dengue, Hajj Crowding.</td>
                        </tr>
                        <tr>
                            <td class="p-3 font-semibold">Middle East</td>
                            <td class="p-3"><span class="risk-badge bg-orange-600">MODERATE</span></td>
                            <td class="p-3 text-slate-300">CCHF, Alkhurma, MERS, Religious Pilgrimage hubs.</td>
                        </tr>
                        <tr>
                            <td class="p-3 font-semibold">Africa</td>
                            <td class="p-3"><span class="risk-badge bg-red-600 text-white">HIGH</span></td>
                            <td class="p-3 text-slate-300">African Tick-Bite Fever, Rift Valley Fever, Malaria.</td>
                        </tr>
                        <tr>
                            <td class="p-3 font-semibold">South America</td>
                            <td class="p-3"><span class="risk-badge bg-red-600 text-white">HIGH</span></td>
                            <td class="p-3 text-slate-300">Brazil Spotted Fever, Yellow Fever, Amazon Spillover.</td>
                        </tr>
                        <tr>
                            <td class="p-3 font-semibold">Oceania</td>
                            <td class="p-3"><span class="risk-badge bg-emerald-600">LOW</span></td>
                            <td class="p-3 text-slate-300">Q-Tick Typhus, Ross River Virus, Coastal Topography.</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <section class="col-span-5 flex flex-col gap-4">
            
            <div class="glass-panel p-4 rounded-lg border-l-4 border-blue-500">
                <h2 class="text-xs font-bold uppercase text-blue-400 mb-2">The Interoperable Bridge</h2>
                <p class="text-xs italic text-slate-300 leading-relaxed">
                    "The core innovation is the <strong>Encapsulated Triage QR</strong>. By translating environmental, culinary, and temporal data into anonymized clinical indicators, we bridge the gap between epidemiology and EMR workflows."
                </p>
                <div class="mt-3 flex gap-2">
                    <span class="text-[9px] bg-slate-800 px-2 py-1 rounded">Zero-Knowledge</span>
                    <span class="text-[9px] bg-slate-800 px-2 py-1 rounded">FHIR Standard</span>
                    <span class="text-[9px] bg-slate-800 px-2 py-1 rounded">WCAG 2.1 AA</span>
                </div>
            </div>

            <h2 class="text-sm font-bold uppercase tracking-widest text-slate-500 mt-2"><i class="fas fa-rocket mr-2"></i>Value Propositions</h2>
            <div class="grid grid-cols-1 gap-2 flex-grow overflow-y-auto pr-2">
                <div class="glass-panel p-2 rounded flex items-center gap-3">
                    <i class="fas fa-plane text-blue-400 w-4"></i>
                    <p class="text-[11px]"><strong class="text-white">Travel:</strong> Risk awareness without data collection.</p>
                </div>
                <div class="glass-panel p-2 rounded flex items-center gap-3">
                    <i class="fas fa-user-md text-red-400 w-4"></i>
                    <p class="text-[11px]"><strong class="text-white">Healthcare:</strong> Travel history for clinicians, privacy for patients.</p>
                </div>
                <div class="glass-panel p-2 rounded flex items-center gap-3">
                    <i class="fas fa-shield-alt text-emerald-400 w-4"></i>
                    <p class="text-[11px]"><strong class="text-white">Insurance:</strong> Risk-based pricing without medical records.</p>
                </div>
                <div class="glass-panel p-2 rounded flex items-center gap-3">
                    <i class="fas fa-microscope text-purple-400 w-4"></i>
                    <p class="text-[11px]"><strong class="text-white">Pharma:</strong> Correlating traditional medicine for drug discovery.</p>
                </div>
                <div class="glass-panel p-2 rounded flex items-center gap-3">
                    <i class="fas fa-police-box text-blue-600 w-4"></i>
                    <p class
