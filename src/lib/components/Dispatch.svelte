<script>
	// Dispatch Component
</script>

<section class="bg-brand-light py-24">
    <div class="container mx-auto px-4">
        <div class="mb-16">
            <span class="text-sm font-medium text-gray-500 uppercase tracking-wider mb-4 block">Dispatch</span>
            <h2 class="font-serif text-4xl md:text-5xl text-brand-dark mb-6 max-w-3xl">
                Lower your TCO and optimize your <br /> electric fleet in minutes.
            </h2>
            <p class="text-gray-600 text-lg max-w-3xl">
                Dispatch the right EVs across routes and depots that make sense. Optimize charging across your depots or at home.
            </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 mb-8">
            <!-- Green Card -->
            <div class="bg-brand-green text-white p-8 rounded-2xl h-64 flex flex-col justify-between relative overflow-hidden shadow-lg">
                <div class="relative z-10">
                    <h3 class="font-medium text-lg">Tons of CO2e saved</h3>
                    <p class="text-white/70 text-sm">Compared to an ICE fleet</p>
                </div>
                <div class="relative z-10 text-6xl font-serif">29.3</div>
                
                <!-- Background Graphic -->
                <div class="absolute bottom-0 right-0 w-full h-32 opacity-20">
                    <svg viewBox="0 0 100 40" preserveAspectRatio="none" class="w-full h-full">
                        <path d="M0,40 Q25,10 50,25 T100,0 V40 H0 Z" fill="white" />
                    </svg>
                </div>
            </div>

            <!-- White Card -->
            <div class="bg-white p-8 rounded-2xl h-64 flex flex-col justify-between shadow-sm border border-gray-100">
                <div>
                    <h3 class="font-medium text-lg text-brand-dark">Electrification score</h3>
                    <p class="text-gray-500 text-sm">Median over all depots</p>
                </div>
                <div class="text-6xl font-serif text-brand-orange">93</div>
                <div class="w-full bg-gray-100 h-1 rounded-full mt-4 overflow-hidden">
                    <div class="bg-brand-orange h-full w-[93%]"></div>
                </div>
            </div>
        </div>

        <!-- Table Card -->
        <div class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 mb-12">
            <div class="mb-8">
                <h3 class="font-medium text-lg text-brand-dark">Electrification plan</h3>
                <p class="text-gray-500 text-sm">Acme Inc.</p>
            </div>
            
            <div class="overflow-x-auto">
                <table class="w-full text-sm text-left">
                    <tbody class="divide-y divide-gray-100">
                        <tr class="group hover:bg-gray-50 transition-colors">
                            <td class="py-4 text-gray-500 font-medium">Depot #12914</td>
                            <td class="py-4 text-gray-500">23 Vehicles</td>
                            <td class="py-4 text-gray-500">8 Chargers</td>
                            <td class="py-4 text-right">
                                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-medium">On Track</span>
                            </td>
                        </tr>
                        <tr class="group hover:bg-gray-50 transition-colors">
                            <td class="py-4 text-gray-500 font-medium">Depot #14567</td>
                            <td class="py-4 text-gray-500">15 Vehicles</td>
                            <td class="py-4 text-gray-500">5 Chargers</td>
                            <td class="py-4 text-right">
                                <!-- Empty status -->
                            </td>
                        </tr>
                        <tr class="group hover:bg-gray-50 transition-colors">
                            <td class="py-4 text-gray-500 font-medium">Depot #15892</td>
                            <td class="py-4 text-gray-500">30 Vehicles</td>
                            <td class="py-4 text-gray-500">10 Chargers</td>
                            <td class="py-4 text-right">
                                <span class="bg-orange-100 text-orange-700 px-2 py-1 rounded text-xs font-medium">At Risk</span>
                            </td>
                        </tr>
                        <tr class="group hover:bg-gray-50 transition-colors">
                            <td class="py-4 text-gray-500 font-medium">Depot #15893</td>
                            <td class="py-4 text-gray-500">45 Vehicles</td>
                            <td class="py-4 text-gray-500">15 Chargers</td>
                            <td class="py-4 text-right">
                                <span class="bg-gray-100 text-gray-600 px-2 py-1 rounded text-xs font-medium">On track</span>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- Bottom Pills -->
        <div class="flex justify-center">
            <div class="bg-brand-dark text-white p-1 rounded-full flex items-center gap-1 text-sm shadow-xl">
                <span class="px-4 py-1.5 font-medium text-gray-400">Tailored to your industry</span>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">Consulting <span class="text-xs">↗</span></button>
            </div>
        </div>
    </div>
</section>
