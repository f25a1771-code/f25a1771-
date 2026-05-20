<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Derivatives in Agro-Product Technology: Oil Palm Fruit Ripening</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        .custom-shadow {
            box-shadow: 0 10px 30px -5px rgba(0, 0, 0, 0.1), 0 4px 12px -5px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased min-h-screen">

    <header class="bg-gradient-to-r from-emerald-700 to-teal-600 text-white py-8 px-4 shadow-md">
        <div class="max-w-5xl mx-auto">
            <span class="bg-emerald-500 text-xs font-bold uppercase tracking-widest px-3 py-1 rounded-full bg-opacity-30 border border-emerald-300">
                Agro-Product Technology Bioscience App
            </span>
            <h1 class="text-3xl md:text-4xl font-extrabold mt-3 tracking-tight">
                Visualizing Derivatives: Oil Palm Fruit Bunch Lipid Accumulation Rates
            </h1>
            <p class="text-emerald-100 mt-2 text-sm md:text-base max-w-3xl">
                An interactive simulation demonstrating how calculus determines peak harvest timing for Malaysian Oil Palm (*Elaeis guineensis*) fresh fruit bunches (FFB).
            </p>
        </div>
    </header>

    <main class="max-w-5xl mx-auto px-4 py-8 space-y-8">
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            
            <div class="bg-white p-6 rounded-2xl custom-shadow border border-slate-100 md:col-span-2">
                <h2 class="text-xl font-bold text-emerald-800 mb-3 flex items-center gap-2">
                    🌾 The Bioscience Scenario: Optimizing FFB Harvest
                </h2>
                <div class="space-y-3 text-sm md:text-base leading-relaxed text-slate-600">
                    <p>
                        In Malaysia's agro-product sector, maximizing crude palm oil (CPO) extraction rates is vital. During the final weeks of oil palm fruit development (weeks 12 to 22 post-anthesis), the fruit bunch undergoes a rapid physiological synthesis of lipids. 
                    </p>
                    <p>
                        Harvesting too early results in low oil yield, while harvesting too late leads to fruit drop and high Free Fatty Acid (FFA) rancidity. By tracking the **lipid percentage $f(x)$** over time, we can use the **first derivative $f'(x)$** to
