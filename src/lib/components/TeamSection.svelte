<script>
  const team = [
    {
      name: "Pietro Invernizzi",
      role: "Founder & GP",
      bio: "Pietro spent 7.5 years helping hundreds of founders launch companies, giving him deep pattern recognition for identifying strong founder instincts. His personal experience building Firedrop I to 2.2x MOIC proves he can execute his thesis of backing unique founder archetypes before traditional signals exist.",
      image: "/generated/image-professional-portrait-of-a-confident-ven-1767713998419-0.webp"
    }
  ];
</script>

<section id="team" class="py-20 px-6 md:px-12 border-t border-gray-300">
  <div class="flex flex-col md:flex-row">
    <!-- Left Column -->
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Team</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        Deep pattern recognition for identifying exceptional founders before traditional signals exist.
      </p>
    </div>

    <!-- Right Column -->
    <div class="w-full md:w-3/4">
      <div class="max-w-md">
        {#each team as member}
          <div class="group">
            <div class="aspect-[4/5] bg-gray-200 mb-6 overflow-hidden">
              <img src={member.image} alt={member.name} class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" />
            </div>
            <h3 class="font-bold text-2xl mb-2">{member.name}</h3>
            <p class="text-gray-500 text-lg mb-4">{member.role}</p>
            <p class="text-base leading-relaxed">{member.bio}</p>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
