<template>
    <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <div class="flex items-center justify-between mb-4">
              <h2 class="text-2xl font-bold">Course content</h2>
              <button class="text-[#5624d0] font-bold hover:text-[#401b9c]">Expand all sections</button>
            </div>
            <div class="text-sm text-gray-600 mb-4 pb-4 border-b border-[#d1d7dc]">
              13 sections • 23 lectures • 2h 7m total length
            </div>

            <!-- Course content accordion -->
            <div class="border border-gray-300 rounded-lg divide-y">
              <!-- First section (expanded) -->
              <div class="hover:bg-gray-50">
                <!-- Section header -->
                <div class="p-4 cursor-pointer flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-up text-[#5624d0]"></i>
                    <span class="font-bold">INTRODUZIONE A COINBASE Per Comprare BITCOIN</span>
                  </div>
                  <span class="text-sm text-gray-500">4 lectures • 15min</span>
                </div>

                <!-- Expanded content -->
                <div class="border-t">
                  <!-- Lecture 1 -->
                  <div class="p-4 pl-14 flex items-center justify-between hover:bg-gray-50">
                    <div class="flex items-center gap-3">
                      <i class="fas fa-play-circle text-gray-400"></i>
                      <span>Introduzione</span>
                    </div>
                    <div class="flex items-center gap-4">
                      <button class="text-[#5624d0] font-bold hover:text-[#401b9c]">Preview</button>
                      <span class="text-gray-500 w-12 text-right">04:31</span>
                    </div>
                  </div>

                  <!-- Lecture 2 -->
                  <div class="p-4 pl-14 flex items-center justify-between hover:bg-gray-50">
                    <div class="flex items-center gap-3">
                      <i class="fas fa-play-circle text-gray-400"></i>
                      <span>IMPORTANTE Guarda Prima Di Andare Avanti, Grazie...</span>
                    </div>
                    <span class="text-gray-500 w-12 text-right">01:37</span>
                  </div>

                  <!-- Lecture 3 -->
                  <div class="p-4 pl-14 flex items-center justify-between hover:bg-gray-50">
                    <div class="flex items-center gap-3">
                      <i class="fas fa-play-circle text-gray-400"></i>
                      <span>Invito Per Studenti Al Gruppo Telegram ACI69</span>
                    </div>
                    <span class="text-gray-500 w-12 text-right">02:17</span>
                  </div>

                  <!-- Lecture 4 -->
                  <div class="p-4 pl-14 flex items-center justify-between hover:bg-gray-50">
                    <div class="flex items-center gap-3">
                      <i class="fas fa-play-circle text-gray-400"></i>
                      <span>Vantaggi Per Studenti ACI69</span>
                    </div>
                    <span class="text-gray-500 w-12 text-right">06:31</span>
                  </div>
                </div>
              </div>

              <!-- Other sections (collapsed) -->
              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">COME CI SI REGISTRA GRATIS A COINBASE IN ITALIANO?</span>
                  </div>
                  <span class="text-sm text-gray-500">2 lectures • 10min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">COINBASE EARN COME SI GUADAGNA E COME FUNZIONA?</span>
                  </div>
                  <span class="text-sm text-gray-500">1 lecture • 9min</span>
                </div>
              </div>

              <!-- Additional chapters -->
              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">FUNZIONALITA' BASE COINBASE</span>
                  </div>
                  <span class="text-sm text-gray-500">5 lectures • 38min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">COME SI ACQUISTANO BITCOIN E ALTRE CRIPTOVALUTE IN COINBASE?</span>
                  </div>
                  <span class="text-sm text-gray-500">2 lectures • 9min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">COME SI INVIANO BITCOIN (E ALTRE CRIPTO) DA COINBASE AD ALTRI WALLET?</span>
                  </div>
                  <span class="text-sm text-gray-500">1 lecture • 6min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">COME SI RICEVONO BITCOIN (E ALTRE CRIPTO) SUL TUO WALLET COINBASE?</span>
                  </div>
                  <span class="text-sm text-gray-500">1 lecture • 4min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">CASSAFORTE IN COINBASE: QUALI SONO VANTAGGI E SVANTAGGI?</span>
                  </div>
                  <span class="text-sm text-gray-500">1 lecture • 4min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">NOTIFICHE SUI PREZZI IN COINBASE</span>
                  </div>
                  <span class="text-sm text-gray-500">1 lecture • 2min</span>
                </div>
              </div>

              <div class="p-4 hover:bg-gray-50 cursor-pointer">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-3">
                    <i class="fas fa-chevron-down text-gray-400"></i>
                    <span class="font-bold">APP MOBILE COINBASE E COME SI DISATTIVANO LE NOTIFICHE SULL'APP?</span>
                  </div>
                  <span class="text-sm text-gray-500">1 lecture • 4min</span>
                </div>
              </div>
            </div>

            <!-- Show more sections button -->
            <button class="w-full mt-4 py-3 border border-[#5624d0] text-[#5624d0] font-bold rounded-lg hover:bg-gray-50">
              3 more sections
            </button>
          </div>
        </div>
      </div>
</template>