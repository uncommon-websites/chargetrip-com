<script>
	// Hero Component
</script>

<section class="bg-brand-dark text-white pt-24 pb-12 overflow-hidden relative">
	<div class="container mx-auto px-4 text-center relative z-10">
		<h1 class="font-serif text-5xl md:text-7xl leading-tight mb-6 max-w-4xl mx-auto">
			A driver's route plan is your <br class="hidden md:block" /> revenue plan.
		</h1>
		<p class="text-gray-400 text-lg md:text-xl max-w-2xl mx-auto mb-10 font-light">
			Every charge decision has a direct impact on your bottom line. Guide drivers' decisions with EV route planning, station finding, and more, all tailored to your business goals.
		</p>
		
		<div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
			<button class="bg-brand-orange hover:bg-orange-600 text-white px-6 py-3 rounded-md font-medium transition-colors flex items-center gap-2 group">
				Book a demo 
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-4 h-4 group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-transform">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
			</button>
			<button class="bg-white/10 hover:bg-white/20 text-white px-6 py-3 rounded-md font-medium transition-colors flex items-center gap-2 backdrop-blur-sm border border-white/10 group">
				<span class="w-5 h-5 bg-gray-300 rounded-sm overflow-hidden block relative">
                    <!-- Placeholder for map icon -->
                    <svg viewBox="0 0 24 24" fill="currentColor" class="text-black w-full h-full p-0.5">
                        <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
                    </svg>
                </span>
				Plan a route 
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-4 h-4 group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-transform">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 19.5l15-15m0 0H8.25m11.25 0v11.25" />
                </svg>
			</button>
		</div>

		<!-- Central Visual Area -->
		<div class="relative max-w-4xl mx-auto h-[500px] md:h-[600px] mt-10">
            <!-- Hand holding plug placeholder -->
            <div class="absolute inset-0 z-0 flex items-end justify-center">
                <!-- Using a gradient or shape to simulate the hand/plug for now if no image -->
                <img src="https://images.unsplash.com/photo-1667503463633-911c22116263?q=80&w=2574&auto=format&fit=crop" alt="EV Charging Plug" class="h-full object-cover object-center mask-image-b-fade" style="mask-image: linear-gradient(to bottom, black 80%, transparent 100%);" />
            </div>

			<!-- Floating Card: Operation -->
			<div class="absolute top-10 left-0 md:-left-10 bg-white text-black p-4 rounded-xl shadow-2xl w-64 z-20 text-left">
				<div class="flex justify-between items-center mb-4">
					<h3 class="font-medium">Operation</h3>
				</div>
                <div class="flex gap-2 mb-2 text-xs">
                    <span class="bg-orange-100 text-orange-600 px-2 py-0.5 rounded-full">Station utilization</span>
                    <span class="bg-gray-100 text-gray-500 px-2 py-0.5 rounded-full">TCO Redu...</span>
                </div>
				<div class="h-24 w-full relative">
					<!-- Simple SVG Chart -->
					<svg viewBox="0 0 100 50" class="w-full h-full overflow-visible">
                        <!-- Grid lines -->
                        <line x1="0" y1="0" x2="100" y2="0" stroke="#eee" stroke-width="0.5" />
                        <line x1="0" y1="12.5" x2="100" y2="12.5" stroke="#eee" stroke-width="0.5" />
                        <line x1="0" y1="25" x2="100" y2="25" stroke="#eee" stroke-width="0.5" />
                        <line x1="0" y1="37.5" x2="100" y2="37.5" stroke="#eee" stroke-width="0.5" />
                        <line x1="0" y1="50" x2="100" y2="50" stroke="#eee" stroke-width="0.5" />
                        
						<path d="M0,40 Q10,38 20,42 T40,35 T60,20 T80,15 T100,5" fill="none" stroke="#ff5a1f" stroke-width="2" />
                        <path d="M0,40 Q10,38 20,42 T40,35 T60,20 T80,15 T100,5 L100,50 L0,50 Z" fill="url(#gradient)" opacity="0.1" />
                        <defs>
                            <linearGradient id="gradient" x1="0" x2="0" y1="0" y2="1">
                                <stop offset="0%" stop-color="#ff5a1f" />
                                <stop offset="100%" stop-color="white" />
                            </linearGradient>
                        </defs>
					</svg>
                    <!-- Y-axis labels -->
                    <div class="absolute top-0 left-0 h-full flex flex-col justify-between text-[8px] text-gray-400 -ml-4">
                        <span>100</span>
                        <span>75</span>
                        <span>50</span>
                        <span>25</span>
                        <span>0</span>
                    </div>
				</div>
			</div>

			<!-- Floating Card: Renault 5 -->
			<div class="absolute bottom-32 right-0 md:-right-4 bg-white text-black p-3 rounded-xl shadow-2xl w-64 z-20 text-left flex items-center gap-3">
                <div class="w-12 h-8 bg-gray-200 rounded overflow-hidden">
                    <!-- Car Placeholder -->
                     <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg/640px-Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg" class="w-full h-full object-cover" alt="Car" />
                </div>
				<div class="flex-1">
					<h3 class="font-medium text-sm">Renault 5</h3>
					<p class="text-xs text-gray-500">Amsterdam to Porto</p>
                    <div class="flex gap-2 mt-1 text-[10px]">
                        <span class="bg-orange-100 text-orange-700 px-1.5 py-0.5 rounded">€ 238,40</span>
                        <span class="bg-orange-50 text-orange-600 px-1.5 py-0.5 rounded">462 kWh</span>
                    </div>
				</div>
                <div class="flex -space-x-2">
                     <div class="w-6 h-6 rounded-full bg-blue-500 border-2 border-white"></div>
                     <div class="w-6 h-6 rounded-full bg-green-500 border-2 border-white"></div>
                </div>
			</div>
		</div>

        <!-- Logos -->
        <div class="mt-12 border-t border-white/10 pt-8 pb-4">
            <div class="flex flex-wrap justify-center items-center gap-8 md:gap-16 opacity-50 grayscale">
                <!-- Simple text placeholders for logos as I don't have SVGs -->
                <span class="text-xl font-bold italic font-serif">REPSOL</span>
                <span class="text-xl font-bold">PORSCHE</span>
                <span class="text-xl font-bold italic">Hertz</span>
                <span class="text-xl font-bold font-serif">Arval</span>
                <span class="text-xl font-bold">mover</span>
            </div>
        </div>
	</div>
    
    <!-- Background Glow -->
    <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[800px] h-[800px] bg-brand-orange/20 rounded-full blur-[120px] pointer-events-none z-0"></div>
</section>
