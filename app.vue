<template>
  <div>
    <Banner :showBanner="showBanner" @close="showBanner = false" />
    <Header />
    
    <!-- Course section -->
    <div class="relative">
      <!-- Black background section -->
       <Hero />

      <!-- What you'll learn section -->
      <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <h2 class="text-2xl font-bold mb-4">What you'll learn</h2>
            <div class="border border-gray-300 rounded-lg p-6">
              <div class="grid grid-cols-2 gap-4">
                <div class="flex gap-4">
                  <i class="fas fa-check text-gray-400 mt-1"></i>
                  <span>Guadagnare 10$ (circa 8€) di Benvenuto GRATIS</span>
                </div>
                <div class="flex gap-4">
                  <i class="fas fa-check text-gray-400 mt-1"></i>
                  <span>Come Funziona Coinbase Per Comprare BITCOIN</span>
                </div>
                <div class="flex gap-4">
                  <i class="fas fa-check text-gray-400 mt-1"></i>
                  <span>Come Funziona Coinbase Per Comprare Altre Criptovalute</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- After "What you'll learn" section -->
      <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <h2 class="text-[28px] font-bold mb-4 text-[#2d2f31]">Explore related topics</h2>
            <div class="flex flex-wrap gap-3">
              <button class="px-4 py-2 border border-[#2d2f31] rounded-lg text-[#2d2f31] hover:bg-[#2d2f31] hover:text-white transition-colors text-[14px] font-bold">
                Bitcoin
              </button>
              <button class="px-4 py-2 border border-[#2d2f31] rounded-lg text-[#2d2f31] hover:bg-[#2d2f31] hover:text-white transition-colors text-[14px] font-bold">
                Cryptocurrency & Blockchain
              </button>
              <button class="px-4 py-2 border border-[#2d2f31] rounded-lg text-[#2d2f31] hover:bg-[#2d2f31] hover:text-white transition-colors text-[14px] font-bold">
                Finance & Accounting
              </button>
            </div>
          </div>
        </div>
      </div>

      <!-- Course content section -->
      <Course />

      <!-- After the course content section and before the preview section -->
      <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <!-- Requirements section -->
            <h2 class="text-[24px] font-bold mb-4">Requirements</h2>
            <ul class="list-disc pl-5 mb-8 space-y-1">
              <li>Un qualsiasi dispositivo Computer o Smartphone che navighi online</li>
            </ul>

            <!-- Description section -->
            <h2 class="text-[24px] font-bold mb-4">Description</h2>
            <div class="text-[#2d2f31] space-y-4">
              <h3 class="text-[20px] font-bold">Come funziona Coinbase per comprare Bitcoin ed altre criptovalute per guadagnarci?</h3>
              
              <p>Guarda in questa serie di Tutorial come funziona Coinbase per comprare, vendere e trasferire criptovalute.</p>
              
              <p>Guarda anche come guadagnare con Coinbase Criprovalute con Coinbase Earn: te lo spiego in maniera semplice.</p>
              
              <p>Coinbase è un ottimo modo facile per iniziare con le criptovalute quindi se ti va iscriviti a questo corso e segui le semplici lezioni.</p>
              
              <p class="text-gray-400">All'interno del corso troverai anche un invito per guadagnare e ti insegnerò anche come generare il tuo invito personale.</p>

              <button class="text-[#5624d0] font-bold hover:text-[#401b9c]">Show more</button>
            </div>
          </div>
        </div>
      </div>

      <!-- Preview section (fixed) -->
      <div 
        class="fixed right-[275px] w-[380px] bg-white rounded-lg shadow-lg transition-all duration-200" 
        :style="{ top: previewTopPosition + 'px' }"
      >
        <!-- Preview content -->
        <div class="relative aspect-video bg-[#eceb98] rounded-t-lg overflow-hidden">
          <button class="absolute inset-0 flex items-center justify-center group">
            <div class="w-16 h-16 bg-white rounded-full flex items-center justify-center group-hover:scale-110 transition-transform">
              <i class="fas fa-play text-2xl"></i>
            </div>
          </button>
          <div class="absolute bottom-4 left-4 text-white font-bold">
            Preview this course
          </div>
        </div>

        <!-- Course purchase info -->
        <div class="p-6">
          <div class="text-[32px] font-bold mb-4">$19.99</div>
          
          <!-- Buttons -->
          <button class="w-full bg-[#a435f0] text-white font-bold py-3 mb-2 hover:bg-[#8710d8] transition-colors">
            Add to cart
          </button>
          <button class="w-full border border-black font-bold py-3 mb-4 hover:bg-gray-50 transition-colors">
            Buy now
          </button>

          <p class="text-center text-[14px] text-gray-600 mb-6">30-Day Money-Back Guarantee</p>

          <!-- Course includes -->
          <div class="mb-6">
            <h2 class="font-bold mb-3 text-[16px]">This course includes:</h2>
            <ul class="space-y-3 text-[14px]">
              <li class="flex items-center gap-3">
                <i class="fas fa-play-circle text-gray-400"></i>
                <span>2 hours on-demand video</span>
              </li>
              <li class="flex items-center gap-3">
                <i class="fas fa-file-alt text-gray-400"></i>
                <span>1 article</span>
              </li>
              <li class="flex items-center gap-3">
                <i class="fas fa-download text-gray-400"></i>
                <span>2 downloadable resources</span>
              </li>
              <li class="flex items-center gap-3">
                <i class="fas fa-mobile-alt text-gray-400"></i>
                <span>Access on mobile and TV</span>
              </li>
              <li class="flex items-center gap-3">
                <i class="fas fa-infinity text-gray-400"></i>
                <span>Full lifetime access</span>
              </li>
              <li class="flex items-center gap-3">
                <i class="fas fa-certificate text-gray-400"></i>
                <span>Certificate of completion</span>
              </li>
            </ul>
          </div>

          <!-- Share and coupon -->
          <div class="flex items-center justify-between border-t pt-4 mb-4 text-[14px]">
            <button class="text-[#5624d0] hover:text-[#401b9c] font-bold">Share</button>
            <button class="text-[#5624d0] hover:text-[#401b9c] font-bold">Gift this course</button>
            <button class="text-[#5624d0] hover:text-[#401b9c] font-bold" @click="showCouponInput = !showCouponInput">
              Apply Coupon
            </button>
          </div>

          <!-- Coupon section -->
          <template v-if="showCouponInput">
            <!-- Applied coupon message -->
            <div v-if="appliedCoupon" class="border border-dashed border-gray-300 rounded p-3 mb-4 relative">
              <div class="text-gray-500 text-[14px]">
                <span class="font-bold text-gray-700">LETSLEARNNOW</span> is applied
              </div>
              <button 
                @click="removeCoupon" 
                class="absolute right-2 top-1/2 -translate-y-1/2 text-[#5624d0] hover:text-[#401b9c]"
              >
                <i class="fas fa-times"></i>
              </button>
            </div>

            <!-- Coupon input -->
            <div v-else class="flex gap-2 mb-4">
              <input 
                type="text" 
                placeholder="Enter Coupon" 
                class="flex-grow border rounded px-3 py-2 text-[14px] focus:outline-none focus:ring-1 focus:ring-[#5624d0]"
                v-model="couponCode"
              >
              <button 
                class="bg-[#5624d0] text-white px-4 py-2 rounded font-bold hover:bg-[#401b9c] transition-colors"
                @click="applyCoupon"
              >
                Apply
              </button>
            </div>
          </template>

          <!-- Training section -->
          <div class="border-t pt-6">
            <h2 class="text-[20px] font-bold mb-2">Training 5 or more people?</h2>
            <p class="text-[14px] text-gray-600 mb-4">
              Get your team access to 27,000+ top Udemy courses anytime, anywhere.
            </p>
            <button class="w-full border border-[#5624d0] text-[#5624d0] font-bold py-3 hover:bg-gray-50 transition-colors">
              Try Udemy Business
            </button>
          </div>
        </div>
      </div>

      <!-- Students also bought section -->
      <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <h2 class="text-[24px] font-bold text-[#2d2f31] mb-6">Students also bought</h2>
            
            <div class="divide-y divide-[#d1d7dc]">
              <!-- Course cards -->
              <div v-for="(course, index) in courses" :key="index" 
                   class="flex items-start gap-4 py-4 first:pt-0 last:pb-0">
                <img 
                  :src="`/images/${course.image}`" 
                  :alt="course.title"
                  class="w-[64px] h-[64px] object-cover rounded"
                />
                <div class="flex-1">
                  <h3 class="font-bold text-[16px] text-[#2d2f31] leading-snug mb-1">
                    {{ course.title }}
                  </h3>
                  <div class="text-[14px] text-[#6a6f73]">
                    {{ course.duration }} • Updated {{ course.updated }}
                  </div>
                  <div class="flex items-center gap-2 mt-1">
                    <span class="font-bold text-[#b4690e]">{{ course.rating }}</span>
                    <div class="flex text-[#b4690e]">★</div>
                    <span class="text-[14px] text-[#6a6f73]">({{ course.students.toLocaleString() }})</span>
                  </div>
                </div>
                <div class="flex items-center gap-3">
                  <span class="font-bold text-[16px]">${{ course.price }}</span>
                  <button 
                    @click="toggleWishlist(index)"
                    class="p-2 hover:bg-gray-100 rounded-full"
                    :class="{ 'text-[#a435f0]': course.wishlisted }"
                  >
                    <svg class="w-6 h-6" :fill="course.wishlisted ? 'currentColor' : 'none'" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                    </svg>
                  </button>
                </div>
              </div>
            </div>

            <button class="mt-6 text-[#5624d0] font-bold text-[14px] hover:text-[#401b9c]">
              Show more
            </button>
          </div>
        </div>
      </div>

      <!-- Instructor section -->
      <div class="bg-white py-8">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="max-w-[700px]">
            <h2 class="text-[24px] font-bold text-[#2d2f31] mb-6">Instructor</h2>

            <!-- Instructor profile -->
            <a href="#" class="text-[#5624d0] hover:text-[#401b9c] text-[20px] font-bold mb-2 inline-block">
              ACI69 | Trading™
            </a>

            <p class="text-[#6a6f73] mb-4">
              Ingegnere Informatico Best Seller – Impara e Guadagna!
            </p>

            <div class="flex gap-6 mb-6">
              <img 
                src="/images/instractor.jpg" 
                alt="ACI69 Trading instructor" 
                class="w-[112px] h-[112px] rounded-full object-cover hover:opacity-80 transition-opacity"
              />
              
              <div class="space-y-3">
                <div class="flex items-center gap-2 text-[#6a6f73]">
                  <svg class="w-4 h-4" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2 9.19 8.63 2 9.24l5.46 4.73L5.82 21z"/>
                  </svg>
                  <span class="text-[14px]">4.5 Instructor Rating</span>
                </div>
                
                <div class="flex items-center gap-2 text-[#6a6f73]">
                  <svg class="w-4 h-4" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M19 5h-2V3H7v2H5c-1.1 0-2 .9-2 2v1c0 2.55 1.92 4.63 4.39 4.94.63 1.5 1.98 2.63 3.61 2.96V19H7v2h10v-2h-4v-3.1c1.63-.33 2.98-1.46 3.61-2.96C19.08 12.63 21 10.55 21 8V7c0-1.1-.9-2-2-2zM5 8V7h2v3.82C5.84 10.4 5 9.3 5 8zm14 0c0 1.3-.84 2.4-2 2.82V7h2v1z"/>
                  </svg>
                  <span class="text-[14px]">3,023 Reviews</span>
                </div>

                <div class="flex items-center gap-2 text-[#6a6f73]">
                  <svg class="w-4 h-4" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 6.34 5 8s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z"/>
                  </svg>
                  <span class="text-[14px]">14,291 Students</span>
                </div>

                <div class="flex items-center gap-2 text-[#6a6f73]">
                  <svg class="w-4 h-4" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 14.5v-9l6 4.5-6 4.5z"/>
                  </svg>
                  <span class="text-[14px]">53 Courses</span>
                </div>
              </div>
            </div>

            <div class="space-y-4" :class="{ 'line-clamp-3': !showFullDescription }">
              <p class="text-[#2d2f31]">★ Impara, Applica, Guadagna!</p>
              <p class="text-[#2d2f31]">Mi occupo di formazione online da 18 anni</p>
              <p class="text-[#2d2f31]">✓ senza fronzoli</p>
              <p class="text-[#2d2f31]">✓ senza piedistalli del cavolo</p>
              <p class="text-[#2d2f31]">✓ senza perdite di tempo</p>
            </div>

            <button 
              @click="showFullDescription = !showFullDescription"
              class="text-[#5624d0] font-bold hover:text-[#401b9c] mt-4"
            >
              {{ showFullDescription ? 'Show less' : 'Show more' }}
            </button>
          </div>
        </div>
      </div>

      <!-- Ratings section -->
      <Ratings />
      <!-- Top companies banner -->
      <div class="bg-[#1c1d1f] text-white py-4">
        <div class="max-w-[1184px] mx-auto px-6">
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-2 text-[14px]">
              <span>Top companies choose</span>
              <span class="text-[#cec0fc]">Udemy Business</span>
              <span>to build in-demand career skills.</span>
            </div>
            
            <div class="flex items-center gap-8">
              <img src="/images/nas.svg" alt="Nasdaq" class="h-[44px] object-contain" />
              <img src="/images/w.svg" alt="Volkswagen" class="h-[44px] object-contain" />
              <img src="/images/net.svg" alt="NetApp" class="h-[44px] object-contain" />
              <img src="/images/event.svg" alt="Eventbrite" class="h-[44px] object-contain" />
            </div>
          </div>
        </div>
      </div>

      <!-- White divider -->
      <div class="h-px bg-white/[0.2]"></div>

      <!-- Explore top skills section -->
      <div class="bg-[#1c1d1f] text-white py-16">
        <div class="max-w-[1184px] mx-auto px-6">
          <h2 class="text-2xl font-bold mb-12">Explore top skills and certifications</h2>
          
          <div class="grid grid-cols-4 gap-16">
            <!-- Certifications by Issuer -->
            <div>
              <h3 class="font-bold mb-4">Certifications by Issuer</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Amazon Web Services (AWS) Certifications</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Six Sigma Certifications</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Microsoft Certifications</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Cisco Certifications</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Tableau Certifications</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">See all Certifications</a></li>
              </ul>
            </div>

            <!-- Web Development -->
            <div>
              <h3 class="font-bold mb-4">Web Development</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Web Development</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">JavaScript</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">React JS</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Angular</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Java</a></li>
              </ul>
            </div>

            <!-- IT Certifications -->
            <div>
              <h3 class="font-bold mb-4">IT Certifications</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Amazon AWS</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">AWS Certified Cloud Practitioner</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">AZ-900: Microsoft Azure Fundamentals</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">AWS Certified Solutions Architect - Associate</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Kubernetes</a></li>
              </ul>
            </div>

            <!-- Leadership -->
            <div>
              <h3 class="font-bold mb-4">Leadership</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Leadership</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Management Skills</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Project Management</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Personal Productivity</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Emotional Intelligence</a></li>
              </ul>
            </div>
          </div>

          <!-- Second row -->
          <div class="grid grid-cols-4 gap-16 mt-16">
            <!-- Certifications by Skill -->
            <div>
              <h3 class="font-bold mb-4">Certifications by Skill</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Cybersecurity Certification</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Project Management Certification</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Cloud Certification</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Data Analytics Certification</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">HR Management Certification</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">See all Certifications</a></li>
              </ul>
            </div>

            <!-- Data Science -->
            <div>
              <h3 class="font-bold mb-4">Data Science</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Data Science</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Python</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Machine Learning</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">ChatGPT</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Deep Learning</a></li>
              </ul>
            </div>

            <!-- Communication -->
            <div>
              <h3 class="font-bold mb-4">Communication</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Communication Skills</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Presentation Skills</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Public Speaking</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Writing</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">PowerPoint</a></li>
              </ul>
            </div>

            <!-- Business Analytics & Intelligence -->
            <div>
              <h3 class="font-bold mb-4">Business Analytics & Intelligence</h3>
              <ul class="space-y-3">
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Microsoft Excel</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">SQL</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Microsoft Power BI</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Data Analysis</a></li>
                <li><a href="#" class="text-[14px] hover:text-[#cec0fc]">Business Analysis</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Footer -->
    <Footer />
  </div>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const showBanner = ref(true)
const showCouponInput = ref(false)
const couponCode = ref('')
const appliedCoupon = ref(false)
const previewTopPosition = ref(200)
const showFullDescription = ref(false)

const courses = ref([
  {
    image: 'course1.jpg',
    title: 'Crypto Condensed: The Complete Guide To Bitcoin',
    duration: '7 total hours',
    updated: '2/2024',
    rating: 4.3,
    students: 31373,
    price: '54.99',
    wishlisted: false
  },
  {
    image: 'course2.jpg',
    title: 'Blockchain and Bitcoin Fundamentals',
    duration: '3 total hours',
    updated: '3/2025',
    rating: 4.6,
    students: 132398,
    price: '74.99',
    wishlisted: false,
    bestseller: true
  },
  {
    image: 'course3.webp',
    title: 'Bitcoin Advanced Level: Transactions',
    duration: '1.5 total hours',
    updated: '3/2025',
    rating: 4.7,
    students: 5900,
    price: '59.99',
    wishlisted: false
  },
  {
    image: 'course4.webp',
    title: 'Bitcoin and Cryptocurrency Bootcamp',
    duration: '8.5 total hours',
    updated: '6/2018',
    rating: 4.4,
    students: 10663,
    price: '69.99',
    wishlisted: false
  },
  {
    image: 'course5.webp',
    title: 'Introduction to Bitcoin & Crypto Assets',
    duration: '1.5 total hours',
    updated: '12/2021',
    rating: 4.5,
    students: 3881,
    price: '34.99',
    wishlisted: false
  },
  {
    image: 'course6.webp',
    title: 'Crypto Masterclass: Bitcoin, Altcoins, NFTs, DeFi, Metaverse',
    duration: '4.5 total hours',
    updated: '1/2024',
    rating: 4.4,
    students: 87151,
    price: '39.99',
    wishlisted: false
  }
])

const applyCoupon = () => {
  if (couponCode.value) {
    appliedCoupon.value = true
    showCouponInput.value = true
  }
}

const removeCoupon = () => {
  appliedCoupon.value = false
  couponCode.value = ''
}

const handleScroll = () => {
  const scrollPosition = window.scrollY
  const headerHeight = 72 // header height

  if (scrollPosition > headerHeight) {
    previewTopPosition.value = 0
  } else {
    previewTopPosition.value = 200 - scrollPosition
  }
}

const toggleWishlist = (index) => {
  courses.value[index].wishlisted = !courses.value[index].wishlisted
}

onMounted(() => {
  window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>

<style>
/* Add custom font family */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}
</style>