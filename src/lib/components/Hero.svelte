<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-24 pb-32 overflow-hidden border-b-2 border-gray-900">
  <!-- Technical Grid Background -->
  <div class="absolute inset-0 opacity-[0.02]">
    <div class="absolute inset-0" style="background-image: linear-gradient(to right, currentColor 1px, transparent 1px), linear-gradient(to bottom, currentColor 1px, transparent 1px); background-size: 32px 32px;"></div>
  </div>

  <!-- Content -->
  <div class="z-10 mx-auto max-w-5xl px-4 text-center mb-20">
    <!-- Technical Label -->
    <div class="inline-flex items-center gap-2 px-4 py-2 border-2 border-gray-900 mb-8 font-mono text-xs uppercase tracking-widest">
      <div class="h-2 w-2 bg-primary-600 animate-pulse"></div>
      CLINICAL TRIAL PREDICTION PLATFORM
    </div>

    <h1 class="mb-8 text-6xl md:text-7xl lg:text-8xl font-bold font-sans text-gray-900 leading-[0.95] tracking-tight">
      Predict Clinical Trial Success Before You Start
    </h1>
    <p class="mx-auto mb-12 max-w-3xl text-xl md:text-2xl text-gray-700 leading-relaxed font-medium">
      Pheiron uses <span class="font-bold text-gray-900">multimodal AI</span> to design Natural RCTs, generating the <span class="font-bold text-gray-900">causal evidence</span> needed to answer: Which Patient? Which Disease? Which Drug?
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <button class="relative px-10 py-4 text-base font-bold text-white bg-gray-900 border-2 border-gray-900 hover:bg-white hover:text-gray-900 transition-all uppercase tracking-wider">
                Schedule a Demo
            </button>
            <!-- Technical corner brackets -->
            <div class="absolute -top-3 -left-3 h-6 w-6 border-t-4 border-l-4 border-gray-900"></div>
            <div class="absolute -bottom-3 -right-3 h-6 w-6 border-b-4 border-r-4 border-gray-900"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image & Search Interface -->
  <div class="relative w-full max-w-7xl mx-auto px-4">
    <div class="relative aspect-[21/9] w-full overflow-hidden border-4 border-gray-900">
      <img 
        src="https://images.unsplash.com/photo-1582719471384-894fbb16e074?q=80&w=2070&auto=format&fit=crop" 
        alt="Biotech Research Lab" 
        class="h-full w-full object-cover"
      />
      
      <!-- Overlay Search Bar -->
      <div class="absolute inset-0 flex items-center justify-center bg-gradient-to-b from-transparent via-black/5 to-black/20">
        <div class="w-full max-w-2xl border-4 border-gray-900 bg-white p-3 flex items-center gap-4 animate-fade-in-up">
            <div class="pl-2 text-gray-900">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
            </div>
            <div class="flex-1 font-mono text-base font-bold text-gray-900">
                predict Phase II efficacy for PCSK9 inhibitor <span class="animate-pulse">|</span>
            </div>
            <button class="flex h-12 w-12 items-center justify-center bg-gray-900 text-white hover:bg-gray-700 transition-colors border-2 border-gray-900">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
            </button>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
    .animate-fade-in-up {
        animation: fadeInUp 0.8s ease-out forwards;
    }
    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
