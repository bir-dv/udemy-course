<template>
    <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <div class="flex items-center gap-2 mb-6">
              <span class="text-[#b4690e] text-[22px] font-bold">★</span>
              <h2 class="text-[24px] font-bold text-[#2d2f31]">
                4.7 course rating
              </h2>
              <span class="text-[24px] font-bold text-[#2d2f31]">•</span>
              <span class="text-[24px] font-bold text-[#2d2f31]">50 ratings</span>
            </div>

            <!-- Reviews -->
            <div class="grid grid-cols-2 gap-x-6 gap-y-8">
              <!-- Review 1 (Fabrizio G.) -->
              <div class="pb-6 border-b border-[#d1d7dc]">
                <div class="flex justify-between mb-4">
                  <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-[#1c1d1f] rounded-full flex items-center justify-center text-white font-bold">
                      FG
                    </div>
                    <div>
                      <h3 class="font-bold">Fabrizio G.</h3>
                      <div class="flex items-center gap-2 text-[#6a6f73] text-sm">
                        <div class="flex">
                          <span class="text-[#b4690e]">★★★</span>
                          <span class="text-[#b4690e]">☆☆</span>
                        </div>
                        <span>2 years ago</span>
                      </div>
                    </div>
                  </div>
                  <button class="text-[#1c1d1f] hover:text-[#401b9c]">
                    <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                      <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"/>
                    </svg>
                  </button>
                </div>
                <p class="text-[#2d2f31] text-base">
                  Spiegazione elementare dell'uso di Coinbase.Probabilmente la cosa più fastidiosa è che tutte le risorse "scaricabili" fanno riferimento a pseudo bonus o referral cosa alquanto antipatica ritengo.
                </p>
                <div class="mt-4">
                  <p class="text-[#6a6f73] text-sm">Helpful?</p>
                  <div class="flex gap-2 mt-2">
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5"/>
                      </svg>
                    </button>
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 14H5.236a2 2 0 01-1.789-2.894l3.5-7A2 2 0 018.736 3h4.018c.163 0 .326.02.485.06L17 4m-7 10v2a2 2 0 002 2h.095c.5 0 .905-.405.905-.905 0-.714.211-1.412.608-2.006L17 13V4m-7 10h2"/>
                      </svg>
                    </button>
                  </div>
                </div>
              </div>

              <!-- Review 2 (Paolo S.) -->
              <div class="pb-6 border-b border-[#d1d7dc]">
                <div class="flex justify-between mb-4">
                  <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-[#1c1d1f] rounded-full flex items-center justify-center text-white font-bold">
                      PS
                    </div>
                    <div>
                      <h3 class="font-bold">Paolo S.</h3>
                      <div class="flex items-center gap-2 text-[#6a6f73] text-sm">
                        <div class="flex text-[#b4690e]">★★★★★</div>
                        <span>2 years ago</span>
                      </div>
                    </div>
                  </div>
                  <button class="text-[#1c1d1f] hover:text-[#401b9c]">
                    <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                      <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"/>
                    </svg>
                  </button>
                </div>
                <p class="text-[#2d2f31] text-base">
                  Bene! ottima spiegazione, avevo giù una buona conoscenza, così è stata approfondita e, sempre a portata di mano la rinfrescata.
                </p>
                <div class="mt-4">
                  <p class="text-[#6a6f73] text-sm">Helpful?</p>
                  <div class="flex gap-2 mt-2">
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5"/>
                      </svg>
                    </button>
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 14H5.236a2 2 0 01-1.789-2.894l3.5-7A2 2 0 018.736 3h4.018c.163 0 .326.02.485.06L17 4m-7 10v2a2 2 0 002 2h.095c.5 0 .905-.405.905-.905 0-.714.211-1.412.608-2.006L17 13V4m-7 10h2"/>
                      </svg>
                    </button>
                  </div>
                </div>
              </div>

              <!-- Review 3 (Andrea R.) -->
              <div class="pb-6 border-b border-[#d1d7dc]">
                <div class="flex justify-between mb-4">
                  <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-[#1c1d1f] rounded-full flex items-center justify-center text-white font-bold">
                      AR
                    </div>
                    <div>
                      <h3 class="font-bold">Andrea R.</h3>
                      <div class="flex items-center gap-2 text-[#6a6f73] text-sm">
                        <div class="flex text-[#b4690e]">★★★★★</div>
                        <span>3 years ago</span>
                      </div>
                    </div>
                  </div>
                  <button class="text-[#1c1d1f] hover:text-[#401b9c]">
                    <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                      <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"/>
                    </svg>
                  </button>
                </div>
                <p class="text-[#2d2f31] text-base">
                  ero gia a conoscenza dell'uso di coinbase ma una rinfrescata fa sempre bene
                </p>
                <div class="mt-4">
                  <p class="text-[#6a6f73] text-sm">Helpful?</p>
                  <div class="flex gap-2 mt-2">
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5"/>
                      </svg>
                    </button>
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 14H5.236a2 2 0 01-1.789-2.894l3.5-7A2 2 0 018.736 3h4.018c.163 0 .326.02.485.06L17 4m-7 10v2a2 2 0 002 2h.095c.5 0 .905-.405.905-.905 0-.714.211-1.412.608-2.006L17 13V4m-7 10h2"/>
                      </svg>
                    </button>
                  </div>
                </div>
              </div>

              <!-- Review 4 (Ivan G.) -->
              <div class="pb-6 border-b border-[#d1d7dc]">
                <div class="flex justify-between mb-4">
                  <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-[#1c1d1f] rounded-full flex items-center justify-center text-white font-bold">
                      IG
                    </div>
                    <div>
                      <h3 class="font-bold">Ivan G.</h3>
                      <div class="flex items-center gap-2 text-[#6a6f73] text-sm">
                        <div class="flex text-[#b4690e]">★★★★★</div>
                        <span>3 years ago</span>
                      </div>
                    </div>
                  </div>
                  <button class="text-[#1c1d1f] hover:text-[#401b9c]">
                    <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor">
                      <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"/>
                    </svg>
                  </button>
                </div>
                <p class="text-[#2d2f31] text-base line-clamp-3">
                  Molto positiva, avendo anche COINBASE come exchange, mi ha fatto capire che effettivamente ncome fee non è molto conveniente, interessante anche il discorso della cassaforte, penso che il discorso di...
                </p>
                <button class="text-[#5624d0] text-sm font-bold hover:text-[#401b9c] mt-1">Show more</button>
                <div class="mt-4">
                  <p class="text-[#6a6f73] text-sm">Helpful?</p>
                  <div class="flex gap-2 mt-2">
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5"/>
                      </svg>
                    </button>
                    <button class="p-2 border rounded-full hover:bg-gray-50">
                      <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 14H5.236a2 2 0 01-1.789-2.894l3.5-7A2 2 0 018.736 3h4.018c.163 0 .326.02.485.06L17 4m-7 10v2a2 2 0 002 2h.095c.5 0 .905-.405.905-.905 0-.714.211-1.412.608-2.006L17 13V4m-7 10h2"/>
                      </svg>
                    </button>
                  </div>
                </div>
              </div>
            </div>

            <button class="mt-6 text-[#5624d0] font-bold hover:text-[#401b9c]">
              Show more reviews
            </button>
          </div>
        </div>
      </div>
</template>