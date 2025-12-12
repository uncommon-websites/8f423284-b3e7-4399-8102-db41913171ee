<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-20 pb-32 overflow-hidden">
  <!-- Content -->
  <div class="z-10 mx-auto max-w-4xl px-4 text-center mb-16">
    <h1 class="mb-6 text-5xl md:text-6xl lg:text-7xl font-serif text-gray-900 leading-tight">
      Predict Clinical Trial Success Before You Start
    </h1>
    <p class="mx-auto mb-10 max-w-2xl text-lg text-gray-600 leading-relaxed">
      Pheiron uses multimodal AI to design Natural RCTs, generating the causal evidence needed to answer: Which Patient? Which Disease? Which Drug?
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <!-- Decorative brackets/corners could be added here if needed, but simple button for now -->
            <button class="relative rounded-full bg-black px-8 py-3 text-base font-medium text-white hover:bg-gray-800 transition-all">
                Schedule a Demo
            </button>
            <!-- Decorative corners -->
            <div class="absolute -top-2 -left-2 h-4 w-4 border-t-2 border-l-2 border-black"></div>
            <div class="absolute -bottom-2 -right-2 h-4 w-4 border-b-2 border-r-2 border-black"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image & Search Interface -->
  <div class="relative w-full max-w-7xl mx-auto px-4">
    <div class="relative aspect-[21/9] w-full overflow-hidden rounded-lg shadow-2xl">
      <img 
        src="https://images.unsplash.com/photo-1582719471384-894fbb16e074?q=80&w=2070&auto=format&fit=crop" 
        alt="Biotech Research Lab" 
        class="h-full w-full object-cover"
      />
      
      <!-- Overlay Search Bar -->
      <div class="absolute inset-0 flex items-center justify-center bg-black/10">
        <div class="w-full max-w-xl rounded-xl bg-white p-2 shadow-xl flex items-center gap-3 animate-fade-in-up">
            <div class="pl-3 text-gray-400">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
            </div>
            <div class="flex-1 font-mono text-sm text-gray-800">
                predict Phase II efficacy for PCSK9 inhibitor <span class="animate-pulse">|</span>
            </div>
            <button class="flex h-8 w-8 items-center justify-center rounded-lg bg-primary-700 text-white hover:bg-primary-800 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
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
