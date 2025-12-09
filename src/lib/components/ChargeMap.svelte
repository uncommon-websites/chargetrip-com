<script>
	// ChargeMap Component
</script>

<section class="bg-brand-dark text-white py-24 relative overflow-hidden">
	<div class="container mx-auto px-4 relative z-10">
        <div class="mb-12">
            <span class="text-sm font-medium text-gray-500 uppercase tracking-wider mb-4 block">Charge Map</span>
            <h2 class="font-serif text-4xl md:text-5xl mb-6 max-w-3xl">
                Turn drivers into regulars by making your <br /> charge stations and partnerships stand out.
            </h2>
            <p class="text-gray-400 text-lg max-w-3xl">
                Show drivers what matters: price, availability, speed, amenities. Help them find the right stop, and help yourself reduce idle time and increase traffic.
            </p>
        </div>

        <!-- Map Visual -->
        <div class="relative w-full h-[500px] bg-gray-900 rounded-xl overflow-hidden border border-white/10 shadow-2xl">
             <!-- Dark Map Background -->
             <div class="absolute inset-0 opacity-40" style="background-image: url('https://cartodb-basemaps-a.global.ssl.fastly.net/dark_all/6/32/24.png'); background-size: cover; filter: contrast(1.2) brightness(0.8);"></div>
             
             <!-- Green Pins -->
             <div class="absolute top-1/3 left-1/4 transform -translate-x-1/2 -translate-y-1/2">
                 <div class="w-8 h-8 rounded-full bg-brand-green/20 flex items-center justify-center animate-pulse">
                     <div class="w-3 h-3 rounded-full bg-brand-green shadow-[0_0_10px_rgba(34,197,94,0.8)]"></div>
                 </div>
                 <div class="absolute top-full left-1/2 -translate-x-1/2 mt-2 bg-brand-dark/90 text-xs px-2 py-1 rounded border border-white/10 whitespace-nowrap hidden group-hover:block">Available</div>
             </div>

             <div class="absolute top-1/2 left-1/3 transform -translate-x-1/2 -translate-y-1/2">
                 <div class="w-8 h-8 rounded-full bg-brand-green/20 flex items-center justify-center">
                     <div class="w-3 h-3 rounded-full bg-brand-green shadow-[0_0_10px_rgba(34,197,94,0.8)]"></div>
                 </div>
                 <div class="absolute top-full left-1/2 -translate-x-1/2 mt-2 bg-brand-dark/90 text-xs px-2 py-1 rounded border border-white/10 whitespace-nowrap">
                    <div class="flex items-center gap-1">
                        <span class="w-2 h-2 bg-green-500 rounded-full"></span>
                        <span>€ 0.45/kWh</span>
                    </div>
                 </div>
             </div>

             <div class="absolute bottom-1/3 right-1/3 transform -translate-x-1/2 -translate-y-1/2">
                 <div class="w-8 h-8 rounded-full bg-brand-green/20 flex items-center justify-center">
                     <div class="w-3 h-3 rounded-full bg-brand-green shadow-[0_0_10px_rgba(34,197,94,0.8)]"></div>
                 </div>
             </div>
             
             <!-- More random pins -->
             <div class="absolute top-1/4 right-1/4 w-2 h-2 bg-brand-green rounded-full opacity-50"></div>
             <div class="absolute bottom-1/4 left-1/2 w-2 h-2 bg-brand-green rounded-full opacity-50"></div>
        </div>

        <!-- Bottom Pills -->
        <div class="flex justify-center mt-12">
            <div class="bg-white/10 backdrop-blur-md text-white p-1 rounded-full flex items-center gap-1 text-sm border border-white/10">
                <span class="px-4 py-1.5 font-medium text-gray-400">Tailored to your industry</span>
                <button class="bg-brand-orange hover:bg-orange-600 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">Retailers <span class="text-xs">↗</span></button>
                <button class="hover:bg-white/10 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">CPO <span class="text-xs">↗</span></button>
                <button class="hover:bg-white/10 px-4 py-1.5 rounded-full transition-colors flex items-center gap-1">eMSP <span class="text-xs">↗</span></button>
            </div>
        </div>
    </div>
</section>
