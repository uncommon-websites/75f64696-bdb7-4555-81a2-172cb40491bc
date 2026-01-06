<script>
  const focusAreas = [
    { 
      title: "Pre-Seed Focus",
      description: "We invest at the earliest stage, backing founders before traditional signals exist."
    },
    { 
      title: "Founder Archetypes",
      description: "Deep pattern recognition for identifying unique founder instincts and capabilities."
    },
    { 
      title: "180 LP Network",
      description: "Access to a curated network of 180 founder-angel LPs who can open doors."
    },
    { 
      title: "EU & US Markets",
      description: "Supporting exceptional founders across European and US markets."
    },
    { 
      title: "Proven Track Record",
      description: "2.2x MOIC on Firedrop I demonstrates our ability to identify winners early."
    },
    { 
      title: "Founder-Referred Deals",
      description: "Proprietary dealflow through our superconnector LP network."
    }
  ];
</script>

<section id="portfolio" class="py-20 px-6 md:px-12 border-t border-gray-300">
  <div class="flex flex-col md:flex-row">
    <!-- Left Column -->
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Approach</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        We back unique founder archetypes before traditional signals exist, connecting them with our network of 180 founder-angels.
      </p>
    </div>

    <!-- Right Column -->
    <div class="w-full md:w-3/4">
      <h3 class="text-xl font-bold mb-8">What We Offer</h3>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        {#each focusAreas as area}
          <div class="border border-gray-300 p-6 hover:border-gray-900 transition-colors">
            <h4 class="font-bold text-lg mb-3">{area.title}</h4>
            <p class="text-sm leading-relaxed text-gray-600">{area.description}</p>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
