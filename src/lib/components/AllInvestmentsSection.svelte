<script>
  const lpBenefits = [
    "Access to 180 founder-angel LPs",
    "Curated network introductions",
    "Founder-referred dealflow",
    "Pattern recognition expertise",
    "7.5 years pre-seed experience",
    "Proven 2.2x MOIC track record",
    "EU & US market coverage",
    "Pre-seed stage specialists",
    "Unique founder archetypes",
    "Early-stage conviction",
    "Superconnector network",
    "Proprietary deal access"
  ];
</script>

<section class="py-20 px-6 md:px-12">
  <div class="flex flex-col md:flex-row">
    <!-- Left Spacer -->
    <div class="w-full md:w-1/4 pr-8 hidden md:block">
      <!-- Empty to align with right column of previous sections -->
    </div>

    <!-- Right Column Content -->
    <div class="w-full md:w-3/4">
      <div class="mb-12">
        <h3 class="text-2xl font-bold mb-6">Why Firedrop</h3>
        <div class="text-lg leading-relaxed max-w-2xl space-y-4">
          <p>
            Firedrop reaches exited founders through LP referrals, overcoming trust concerns with our proven 2.2x MOIC track record. Our £10M pre-seed fund is backed by 180 founder-angel LPs who serve as superconnectors, driving proprietary dealflow.
          </p>
          <p class="text-gray-600">
            Pietro spent 7.5 years in pre-seed venture, uniquely positioned to solve founder-market fit. This deep experience enables us to identify exceptional founders before traditional signals exist.
          </p>
        </div>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-3 gap-4 text-base font-medium">
        {#each lpBenefits as benefit}
          <div class="py-3 px-4 bg-gray-50 hover:bg-gray-100 transition-colors border border-gray-200">
            {benefit}
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
