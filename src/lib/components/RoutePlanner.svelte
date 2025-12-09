<script>
	// RoutePlanner Component
</script>

<section class="bg-brand-light py-24 relative overflow-hidden">
    <!-- Map Background Pattern -->
    <div class="absolute inset-0 opacity-30 pointer-events-none" style="background-image: url('https://upload.wikimedia.org/wikipedia/commons/e/ec/World_map_blank_without_borders.svg'); background-size: cover; filter: grayscale(1);"></div>

	<div class="container mx-auto px-4 relative z-10">
		<div class="max-w-3xl mb-16">
            <span class="text-sm font-medium text-gray-500 uppercase tracking-wider mb-4 block">Route Planner</span>
			<h2 class="font-serif text-4xl md:text-5xl text-brand-dark mb-6">
				Capture the EV driver market by <br /> offering a tailored routing experience.
			</h2>
			<p class="text-gray-600 text-lg max-w-2xl mb-8">
				Let drivers find the best place to charge, on your terms. Add a route planner to your app or website to lower charging costs, increase your station visits, and boost customer loyalty.
			</p>
            <button class="bg-brand-dark text-white px-6 py-3 rounded-md font-medium flex items-center gap-2 hover:bg-gray-800 transition-colors group">
                Explore EV routing 
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-4 h-4 group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-transform">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
            </button>
		</div>

        <!-- UI Mockup -->
        <div class="relative w-full h-[600px] bg-blue-50 rounded-xl overflow-hidden shadow-2xl border border-gray-200">
            <!-- Map Background for UI -->
            <div class="absolute inset-0 bg-blue-100/50">
                 <!-- Placeholder for actual map tiles -->
                 <div class="w-full h-full opacity-50" style="background-image: url('https://tile.openstreetmap.org/7/66/41.png'); background-size: cover;"></div>
                 <!-- Route Line (SVG) -->
                 <svg class="absolute inset-0 w-full h-full pointer-events-none">
                     <path d="M300,400 Q400,350 500,300 T800,200" fill="none" stroke="#3b82f6" stroke-width="4" stroke-dasharray="8 4" />
                     <!-- Pins -->
                     <circle cx="300" cy="400" r="6" fill="black" />
                     <circle cx="800" cy="200" r="6" fill="black" />
                 </svg>
            </div>

            <!-- Left Panel: Vehicle Settings -->
            <div class="absolute bottom-4 left-4 bg-white rounded-lg shadow-lg p-4 w-64 text-xs">
                <div class="flex items-center gap-2 mb-3 text-gray-500 font-medium uppercase tracking-wide">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path></svg>
                    Vehicle settings
                </div>
                <div class="space-y-2">
                    <div class="flex justify-between items-center">
                        <span class="text-gray-600">Battery at start</span>
                        <div class="bg-gray-100 px-2 py-1 rounded w-16 text-right">80 <span class="text-gray-400">%</span></div>
                    </div>
                    <div class="flex justify-between items-center">
                        <span class="text-gray-600">Battery at arrival</span>
                        <div class="bg-gray-100 px-2 py-1 rounded w-16 text-right">20 <span class="text-gray-400">%</span></div>
                    </div>
                    <div class="flex justify-between items-center">
                        <span class="text-gray-600">Occupants</span>
                        <div class="bg-gray-100 px-2 py-1 rounded w-16 flex justify-between items-center">
                            <span>3</span>
                            <span class="text-gray-400 text-[10px] flex flex-col leading-none"><span>▲</span><span>▼</span></span>
                        </div>
                    </div>
                     <div class="flex justify-between items-center">
                        <span class="text-gray-600">Driving style</span>
                        <div class="bg-gray-100 px-2 py-1 rounded w-16 text-center">Normal</div>
                    </div>
                     <div class="flex justify-between items-center">
                        <span class="text-gray-600">Climate control</span>
                        <div class="flex bg-gray-100 rounded overflow-hidden w-16">
                            <span class="flex-1 text-center py-1 bg-white shadow-sm text-orange-500">Off</span>
                            <span class="flex-1 text-center py-1 text-gray-400">On</span>
                        </div>
                    </div>
                     <div class="flex justify-between items-center">
                        <span class="text-gray-600">Additional weight</span>
                        <div class="bg-gray-100 px-2 py-1 rounded w-16 text-right">0 <span class="text-gray-400">kg</span></div>
                    </div>
                </div>
            </div>

            <!-- Center Panel: Route Details -->
            <div class="absolute top-4 left-1/2 -translate-x-1/2 bg-white rounded-lg shadow-lg w-80 overflow-hidden">
                <div class="p-4 border-b border-gray-100">
                    <div class="flex justify-between items-start mb-1">
                        <h3 class="font-medium text-brand-dark">Amsterdam to Warsaw</h3>
                        <button class="text-gray-400 hover:text-gray-600">×</button>
                    </div>
                    <p class="text-xs text-gray-500 mb-3">Driving Tesla Model 3 - 80% Battery</p>
                    <div class="flex gap-2">
                        <button class="flex-1 bg-brand-dark text-white text-xs py-2 rounded flex items-center justify-center gap-1">
                            <span>📱</span> Send to phone
                        </button>
                        <button class="flex-1 bg-gray-100 text-gray-600 text-xs py-2 rounded flex items-center justify-center gap-1">
                            <span>Cw</span> Refresh
                        </button>
                         <button class="flex-1 bg-gray-100 text-gray-600 text-xs py-2 rounded flex items-center justify-center gap-1">
                            <span>Top</span> Share
                        </button>
                    </div>
                </div>
                <div class="p-4 bg-gray-50/50">
                    <div class="flex justify-between items-baseline mb-1">
                        <span class="text-xl font-bold text-brand-dark">13 hr 15 min</span>
                        <span class="text-xs text-orange-500 font-medium">Arrive at 05:21</span>
                    </div>
                    <p class="text-xs text-gray-500 mb-4">1273 km · 6 charging stops</p>
                    
                    <div class="space-y-2 text-xs">
                        <div class="flex justify-between">
                            <span class="text-gray-500">Charging time</span>
                            <span class="font-medium">3 hr 10 min</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-gray-500">Est. charge costs</span>
                            <span class="font-medium">€ 240,24</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-gray-500">Est. consumption</span>
                            <span class="font-medium">319 kWh</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-gray-500">CO2e avoided</span>
                            <span class="font-medium">1600 grams</span>
                        </div>
                    </div>
                    
                    <div class="mt-4 space-y-1">
                         <div class="flex items-center gap-2 text-[10px] text-red-500 bg-red-50 p-1 rounded">
                             <span>⚠️</span> Temperatures below 5 °C reduce range
                         </div>
                         <div class="flex items-center gap-2 text-[10px] text-gray-500">
                             <span>⚠️</span> Includes toll roads
                         </div>
                    </div>
                </div>
                <div class="p-3 border-t border-gray-100 text-xs text-gray-400 flex items-center gap-2">
                    <div class="w-4 h-4 rounded-full bg-gray-200"></div>
                    Route breakdown
                </div>
                <div class="p-3 border-t border-gray-100 text-xs text-gray-500 flex items-center gap-2">
                     <div class="w-2 h-2 rounded-full bg-green-500"></div>
                     Amsterdam, North Holland, Netherlands
                </div>
            </div>

            <!-- Right Panel: Station Details -->
            <div class="absolute top-20 right-4 bg-white rounded-lg shadow-lg p-4 w-64">
                <div class="flex items-start gap-3 mb-3">
                    <div class="w-8 h-8 bg-yellow-400 rounded flex items-center justify-center text-white font-bold">F</div>
                    <div>
                        <h4 class="font-medium text-sm text-brand-dark leading-tight">Fastned - Sodetrel Intermarche</h4>
                        <div class="flex gap-2 mt-1 text-[10px] font-medium">
                            <span class="bg-gray-100 px-1 rounded">150 kW</span>
                            <span class="bg-gray-100 px-1 rounded">9 °C</span>
                        </div>
                    </div>
                </div>
                <div class="space-y-2 text-xs border-t border-gray-100 pt-2">
                     <div class="flex justify-between">
                        <span class="text-gray-500">Charging time</span>
                        <span class="font-medium">30 min</span>
                    </div>
                    <div class="flex justify-between">
                        <span class="text-gray-500">Charge from</span>
                        <span class="font-medium">20% → 80%</span>
                    </div>
                    <div class="flex justify-between">
                        <span class="text-gray-500">Estimated pricing</span>
                        <span class="font-medium">€ 31,38</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Bottom Pills -->
        <div class="flex justify-center mt-12">
            <div class="bg-brand-dark text-white p-1 rounded-full flex items-center gap-1 text-sm shadow-xl">
                <span class="px-4 py-1.5 font-medium text-gray-400">Tailored to your industry</span>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">CPO <span class="text-xs">↗</span></button>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">Rental <span class="text-xs">↗</span></button>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">eMSP <span class="text-xs">↗</span></button>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">Leasing <span class="text-xs">↗</span></button>
            </div>
        </div>
	</div>
</section>
