<script>
    const partners = [
        { name: "UK Biobank", icon: "🧬", color: "bg-primary-600" },
        { name: "ClinicalTrials.gov", icon: "C", color: "bg-primary-700" },
        { name: "Genomic Databases", icon: "G", color: "bg-primary-800" },
        { name: "Electronic Health Records", icon: "E", color: "bg-primary-600" },
        { name: "Population Cohorts", icon: "👥" },
        { name: "Genetic Consortia", icon: "🔬" },
        { name: "Biobank Networks", icon: "B", color: "bg-primary-700" },
        { name: "Real-World Evidence", icon: "📊" },
        { name: "Disease Registries", icon: "📋" },
        { name: "Pharmacovigilance Data", icon: "💊" },
        { name: "Omics Platforms", icon: "O", color: "bg-primary-800" },
        { name: "Clinical Data Warehouses", icon: "🏥" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Population-Scale Data</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                We integrate the world's largest biomedical databases and population cohorts to generate Natural RCTs. Pheiron's multimodal AI transforms real-world data into causal evidence for clinical trial success.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
