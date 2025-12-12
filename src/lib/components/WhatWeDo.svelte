<script lang="ts">
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Problem Statement -->
        <div class="mb-20">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight max-w-4xl">
                Over 90% of clinical trials fail. <span class="font-semibold">We predict success using human genetic evidence before you invest billions.</span>
            </h2>
        </div>

        <!-- Core Capabilities -->
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12">
            <!-- Natural RCTs -->
            <div class="space-y-4">
                <div class="h-12 w-12 bg-primary-100 rounded-lg flex items-center justify-center text-primary-700 font-serif text-xl">
                    Φ
                </div>
                <h3 class="text-xl font-serif text-gray-900">
                    Natural RCTs
                </h3>
                <p class="text-sm text-gray-600 leading-relaxed">
                    Design Natural Randomized Controlled Trials from population data. Identify people born with genetic variants that mimic drug effects and measure lifelong outcomes.
                </p>
            </div>

            <!-- Multimodal AI -->
            <div class="space-y-4">
                <div class="h-12 w-12 bg-primary-100 rounded-lg flex items-center justify-center">
                    <div class="grid grid-cols-2 gap-1">
                        {#each [1, 2, 3, 4] as i}
                            <div class="h-2 w-2 bg-primary-600 rounded-sm"></div>
                        {/each}
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900">
                    Multimodal AI
                </h3>
                <p class="text-sm text-gray-600 leading-relaxed">
                    Integrate genomic, clinical, imaging, and molecular data across billions of data points from complex biomedical datasets to generate disease signatures.
                </p>
            </div>

            <!-- Causal Evidence -->
            <div class="space-y-4">
                <div class="h-12 w-12 bg-primary-100 rounded-lg flex items-center justify-center">
                    <div class="relative">
                        <div class="flex gap-1 mb-1">
                            <div class="h-2 w-2 border border-primary-600 bg-white rounded-sm"></div>
                            <div class="h-2 w-2 border border-primary-600 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-3 w-px bg-primary-600"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-3 w-3 bg-primary-600 rounded-sm"></div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900">
                    Causal Evidence
                </h3>
                <p class="text-sm text-gray-600 leading-relaxed">
                    Advanced causal inference distinguishes correlation from causation. Answer which patient, which disease, which drug with human genetic validation.
                </p>
            </div>
        </div>

        <!-- Key Stats -->
        <div class="mt-20 pt-20 border-t border-gray-100">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
                <div>
                    <div class="text-4xl font-serif text-gray-900 mb-2">2x</div>
                    <p class="text-sm text-gray-600">Higher approval rate with genetic evidence</p>
                </div>
                <div>
                    <div class="text-4xl font-serif text-gray-900 mb-2">$450M</div>
                    <p class="text-sm text-gray-600">Average savings per program from reduced Phase II failures</p>
                </div>
                <div>
                    <div class="text-4xl font-serif text-gray-900 mb-2">90%</div>
                    <p class="text-sm text-gray-600">Clinical trial failure rate we help you avoid</p>
                </div>
            </div>
        </div>
    </div>
</section>
