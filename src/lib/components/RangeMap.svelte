<script>
	// RangeMap Component
</script>

<section class="bg-brand-light py-24 relative overflow-hidden">
    <!-- Map Background -->
    <div class="absolute inset-0 opacity-20 pointer-events-none" style="background-image: url('https://upload.wikimedia.org/wikipedia/commons/e/ec/World_map_blank_without_borders.svg'); background-size: cover; filter: grayscale(1);"></div>

    <div class="container mx-auto px-4 relative z-10">
        <div class="max-w-3xl mb-16">
            <span class="text-sm font-medium text-gray-500 uppercase tracking-wider mb-4 block">Range map</span>
            <h2 class="font-serif text-4xl md:text-5xl text-brand-dark mb-6">
                Satisfy regulators, eliminate range <br /> anxiety and boost EV traction.
            </h2>
            <p class="text-gray-600 text-lg max-w-2xl">
                Display range by using realtime data. Visualize different battery sizes and turn WLTP distances into travel experiences.
            </p>
        </div>

        <!-- Visuals -->
        <div class="relative h-[400px] md:h-[500px] w-full flex justify-center items-end gap-4 md:gap-12 pb-12">
            <!-- Background Polygons (Isochrones) -->
            <div class="absolute inset-0 flex justify-center items-center pointer-events-none -z-10 translate-y-[-10%]">
                 <!-- Orange Polygon -->
                 <svg viewBox="0 0 800 600" class="w-full h-full opacity-30">
                     <path d="M400,300 m-250,0 a250,200 0 1,0 500,0 a250,200 0 1,0 -500,0" fill="#ffccaa" />
                     <path d="M400,300 m-180,0 a180,140 0 1,0 360,0 a180,140 0 1,0 -360,0" fill="#ffaa88" />
                     <path d="M400,300 m-100,0 a100,80 0 1,0 200,0 a100,80 0 1,0 -200,0" fill="#ff8866" />
                 </svg>
            </div>

            <!-- Car 1: Green -->
            <div class="relative group w-1/3 max-w-[300px]">
                <div class="absolute -top-12 left-1/2 -translate-x-1/2 bg-brand-dark text-white px-3 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity">Evolution</div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg/640px-Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg" alt="Green Car" class="w-full h-auto object-contain filter hue-rotate-90 contrast-125" />
            </div>

            <!-- Car 2: Black (Center, larger) -->
            <div class="relative group w-1/3 max-w-[350px] z-10 mb-8">
                <div class="absolute -top-12 left-1/2 -translate-x-1/2 bg-brand-dark text-white px-3 py-1 rounded text-xs">Techno</div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg/640px-Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg" alt="Black Car" class="w-full h-auto object-contain filter grayscale contrast-125 brightness-75" />
            </div>

            <!-- Car 3: Yellow -->
            <div class="relative group w-1/3 max-w-[300px]">
                <div class="absolute -top-12 left-1/2 -translate-x-1/2 bg-brand-dark text-white px-3 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity">Iconiq Cinq</div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg/640px-Renault_5_E-Tech_Electric_Genf_2024_1KY_0304.jpg" alt="Yellow Car" class="w-full h-auto object-contain filter hue-rotate-[-45deg] saturate-200" />
            </div>
        </div>

        <!-- Bottom Pills -->
        <div class="flex justify-center mt-8">
            <div class="bg-brand-dark text-white p-1 rounded-full flex items-center gap-1 text-sm shadow-xl">
                <span class="px-4 py-1.5 font-medium text-gray-400">Tailored to your industry</span>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">OEMs <span class="text-xs">↗</span></button>
                <button class="bg-brand-dark hover:bg-gray-800 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">Consulting <span class="text-xs">↗</span></button>
            </div>
        </div>
    </div>
</section>
