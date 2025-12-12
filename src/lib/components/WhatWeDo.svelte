<script lang="ts">
</script>

<section class="py-32 bg-white border-b-2 border-gray-900">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Problem Statement -->
        <div class="mb-24 border-l-4 border-gray-900 pl-8">
            <h2 class="text-5xl md:text-6xl font-bold font-sans text-gray-900 leading-[1.1] max-w-5xl">
                Over 90% of clinical trials fail. <span class="text-primary-600">We predict success using human genetic evidence before you invest billions.</span>
            </h2>
        </div>

        <!-- Core Capabilities -->
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
            <!-- Natural RCTs -->
            <div class="border-2 border-gray-900 p-8 hover:bg-gray-50 transition-colors">
                <div class="h-16 w-16 border-2 border-gray-900 flex items-center justify-center text-gray-900 font-bold text-3xl mb-6">
                    Φ
                </div>
                <h3 class="text-2xl font-bold font-sans text-gray-900 mb-4 uppercase tracking-tight">
                    Natural RCTs
                </h3>
                <p class="text-base text-gray-700 leading-relaxed font-medium">
                    Design Natural Randomized Controlled Trials from population data. Identify people born with genetic variants that mimic drug effects and measure lifelong outcomes.
                </p>
            </div>

            <!-- Multimodal AI -->
            <div class="border-2 border-gray-900 p-8 hover:bg-gray-50 transition-colors">
                <div class="h-16 w-16 border-2 border-gray-900 flex items-center justify-center mb-6">
                    <div class="grid grid-cols-2 gap-1.5">
                        {#each [1, 2, 3, 4] as i}
                            <div class="h-3 w-3 bg-gray-900"></div>
                        {/each}
                    </div>
                </div>
                <h3 class="text-2xl font-bold font-sans text-gray-900 mb-4 uppercase tracking-tight">
                    Multimodal AI
                </h3>
                <p class="text-base text-gray-700 leading-relaxed font-medium">
                    Integrate genomic, clinical, imaging, and molecular data across billions of data points from complex biomedical datasets to generate disease signatures.
                </p>
            </div>

            <!-- Causal Evidence -->
            <div class="border-2 border-gray-900 p-8 hover:bg-gray-50 transition-colors">
                <div class="h-16 w-16 border-2 border-gray-900 flex items-center justify-center mb-6">
                    <div class="relative">
                        <div class="flex gap-1.5 mb-1">
                            <div class="h-3 w-3 border-2 border-gray-900 bg-white"></div>
                            <div class="h-3 w-3 border-2 border-gray-900 bg-white"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-4 w-1 bg-gray-900"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-4 w-4 bg-gray-900"></div>
                        </div>
                    </div>
                </div>
                <h3 class="text-2xl font-bold font-sans text-gray-900 mb-4 uppercase tracking-tight">
                    Causal Evidence
                </h3>
                <p class="text-base text-gray-700 leading-relaxed font-medium">
                    Advanced causal inference distinguishes correlation from causation. Answer which patient, which disease, which drug with human genetic validation.
                </p>
            </div>
        </div>

        <!-- Key Stats -->
        <div class="mt-24 pt-24 border-t-4 border-gray-900">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-16">
                <div class="text-center">
                    <div class="text-7xl font-bold font-sans text-gray-900 mb-4 tracking-tighter">2x</div>
                    <p class="text-base font-bold text-gray-700 uppercase tracking-wide">Higher approval rate with genetic evidence</p>
                </div>
                <div class="text-center">
                    <div class="text-7xl font-bold font-sans text-gray-900 mb-4 tracking-tighter">$450M</div>
                    <p class="text-base font-bold text-gray-700 uppercase tracking-wide">Average savings per program from reduced Phase II failures</p>
                </div>
                <div class="text-center">
                    <div class="text-7xl font-bold font-sans text-gray-900 mb-4 tracking-tighter">90%</div>
                    <p class="text-base font-bold text-gray-700 uppercase tracking-wide">Clinical trial failure rate we help you avoid</p>
                </div>
            </div>
        </div>
    </div>
</section>
