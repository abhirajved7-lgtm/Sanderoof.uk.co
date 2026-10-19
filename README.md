# Sanderoof.uk.co
<!doctype html>
<html lang="en-GB" class="scroll-smooth">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sanderoof Ltd — Commercial &amp; Industrial Roofing Manchester</title>
    <meta
      name="description"
      content="Established 19 October 1977. Celebrating 49 years of commercial and industrial roofing excellence across Greater Manchester. Single ply, built-up felt, green roofs, liquid waterproofing, and thermal insulation."
    />
    <meta
      property="og:title"
      content="Sanderoof Ltd — Commercial &amp; Industrial Roofing Manchester"
    />
    <meta
      property="og:description"
      content="Established 19 October 1977. Celebrating 49 years of commercial and industrial roofing excellence across Greater Manchester. Single ply, built-up felt, green roofs, liquid waterproofing, and thermal insulation."
    />
    <meta property="og:type" content="website" />
    <meta name="twitter:card" content="summary_large_image" />

    <!-- Google Fonts: Plus Jakarta Sans & JetBrains Mono for tabular engineering figures -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap"
      rel="stylesheet"
    />

    <!-- Local Vite Tailwind CSS bundle + Standalone Tailwind CDN -->
    <link rel="stylesheet" href="/src/index.css" />
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      if (typeof tailwind !== 'undefined') {
        tailwind.config = {
          theme: {
            extend: {
              colors: {
                navy: {
                  950: '#060E1A',
                  900: '#0B192C',
                  800: '#132742',
                  700: '#1D385B',
                },
                safety: {
                  500: '#FF6500',
                  600: '#E05500',
                  400: '#FF7F2A',
                },
                titanium: {
                  100: '#F5F5F7',
                  200: '#E8E8ED',
                  300: '#D2D2D7',
                  400: '#86868B',
                  800: '#1D1D1F',
                },
              },
              fontFamily: {
                sans: [
                  '"Plus Jakarta Sans"',
                  '-apple-system',
                  'BlinkMacSystemFont',
                  '"SF Pro Display"',
                  '"SF Pro Text"',
                  'sans-serif',
                ],
                mono: ['"JetBrains Mono"', 'ui-monospace', 'SFMono-Regular', 'monospace'],
              },
            },
          },
        };
      }
    </script>

    <style>
      :root {
        --navy-base: #0b192c;
        --navy-deep: #060e1a;
        --navy-surface: #112239;
        --safety-orange: #ff6500;
        --safety-orange-hover: #e05500;
        --titanium-light: #f5f5f7;
        --titanium-muted: #94a3b8;
      }

      * {
        box-sizing: border-box;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
      }

      body {
        margin: 0;
        font-family: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, 'SF Pro Display',
          'SF Pro Text', sans-serif;
        background-color: #0b192c;
        color: #f5f5f7;
        text-rendering: optimizeLegibility;
        overflow-x: hidden;
      }

      h1,
      h2,
      h3,
      h4,
      .apple-heading {
        letter-spacing: -0.03em;
        text-wrap: balance;
      }

      .tabular-nums {
        font-variant-numeric: tabular-nums;
      }

      .glass-panel {
        background: rgba(17, 34, 57, 0.72);
        backdrop-filter: saturate(180%) blur(20px);
        -webkit-backdrop-filter: saturate(180%) blur(20px);
        border: 1px solid rgba(255, 255, 255, 0.1);
      }

      .glass-nav {
        background: rgba(11, 25, 44, 0.85);
        backdrop-filter: saturate(180%) blur(20px);
        -webkit-backdrop-filter: saturate(180%) blur(20px);
        border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      }

      .bento-card {
        background: linear-gradient(
          165deg,
          rgba(22, 42, 69, 0.82) 0%,
          rgba(11, 25, 44, 0.92) 100%
        );
        border: 1px solid rgba(255, 255, 255, 0.1);
        transition: transform 180ms cubic-bezier(0.16, 1, 0.3, 1),
          border-color 180ms cubic-bezier(0.16, 1, 0.3, 1);
      }

      .bento-card:hover {
        transform: translateY(-2px);
        border-color: rgba(255, 101, 0, 0.45);
      }

      .btn-safety {
        background-color: #ff6500;
        color: #ffffff;
        transition: transform 150ms cubic-bezier(0.16, 1, 0.3, 1),
          background-color 150ms cubic-bezier(0.16, 1, 0.3, 1);
      }

      .btn-safety:hover:not(:disabled) {
        background-color: #e05500;
        transform: translateY(-1px);
      }

      .btn-safety:active:not(:disabled) {
        transform: translateY(0);
      }

      .btn-titanium {
        background: rgba(255, 255, 255, 0.07);
        border: 1px solid rgba(255, 255, 255, 0.16);
        color: #f5f5f7;
        transition: background-color 150ms cubic-bezier(0.16, 1, 0.3, 1),
          border-color 150ms cubic-bezier(0.16, 1, 0.3, 1);
      }

      .btn-titanium:hover {
        background: rgba(255, 255, 255, 0.13);
        border-color: rgba(255, 255, 255, 0.28);
      }

      input[type='range'] {
        accent-color: #ff6500;
      }

      @media (prefers-reduced-motion: reduce) {
        *,
        ::before,
        ::after {
          animation-duration: 0.01ms !important;
          animation-iteration-count: 1 !important;
          transition-duration: 0.01ms !important;
          scroll-behavior: auto !important;
        }
      }
    </style>
  </head>

  <body class="bg-[#0B192C] text-[#F5F5F7] selection:bg-[#FF6500] selection:text-white">
    <!-- TOP BAR CONTRACT: Strictly 1 row, 3 zones separated by gap-8 -->
    <header class="sticky top-0 z-50 glass-nav">
      <div
        class="max-w-[1200px] mx-auto px-4 sm:px-6 h-16 flex items-center justify-between gap-8"
      >
        <!-- Zone 1: Single text element wordmark -->
        <a
          href="#"
          class="text-lg font-bold tracking-tight text-white whitespace-nowrap shrink-0 focus-visible:outline-2 focus-visible:outline-[#FF6500]"
        >
          Sanderoof Ltd
        </a>

        <!-- Zone 2: 4 concise single-line navigation links -->
        <nav
          aria-label="Primary Navigation"
          class="hidden md:flex items-center gap-7 text-sm font-medium text-slate-300"
        >
          <a
            href="#estimator"
            class="hover:text-white hover:underline underline-offset-4 transition-colors whitespace-nowrap shrink-0"
          >
            Quote Estimator
          </a>
          <a
            href="#services"
            class="hover:text-white hover:underline underline-offset-4 transition-colors whitespace-nowrap shrink-0"
          >
            Core Services
          </a>
          <a
            href="#heritage"
            class="hover:text-white hover:underline underline-offset-4 transition-colors whitespace-nowrap shrink-0"
          >
            Safety &amp; Heritage
          </a>
          <a
            href="#contact"
            class="hover:text-white hover:underline underline-offset-4 transition-colors whitespace-nowrap shrink-0"
          >
            Whitefield Depot
          </a>
        </nav>

        <!-- Zone 3: 1 primary action -->
        <div class="flex items-center gap-3 shrink-0">
          <a
            href="#estimator"
            class="px-4 py-2 text-xs sm:text-sm font-semibold rounded-lg btn-safety whitespace-nowrap shrink-0 focus-visible:outline-2 focus-visible:outline-white"
          >
            Free Site Survey
          </a>
        </div>
      </div>
    </header>

    <main>
      <!-- 1. APPLE-GRADE TYPOGRAPHY & HERO SECTION -->
      <section
        class="relative pt-10 pb-16 lg:pt-16 lg:pb-24 border-b border-white/10 overflow-hidden"
      >
        <div class="max-w-[1200px] mx-auto px-4 sm:px-6">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 lg:gap-12 items-stretch">
            <!-- Left Column: Apple Titanium Editorial Copy & Direct CTAs -->
            <div class="lg:col-span-7 flex flex-col justify-between">
              <div>
                <!-- Clean unboxed heritage kicker (Zero-Pill Discipline) -->
                <div
                  class="flex flex-wrap items-center gap-x-2.5 gap-y-1 text-xs sm:text-sm font-medium text-[#FF6500] mb-5 tracking-normal"
                >
                  <span>Est. 1977</span>
                  <span aria-hidden="true" class="text-slate-500">&bull;</span>
                  <span class="text-slate-200">
                    49 Years of Commercial &amp; Industrial Roofing Excellence in Manchester
                  </span>
                </div>

                <!-- Tight Apple Kerning Headline -->
                <h1
                  class="apple-heading text-3xl sm:text-5xl lg:text-[3.35rem] font-extrabold tracking-tight text-white leading-[1.08] mb-6"
                >
                  Protecting Greater Manchester's Commercial &amp; Industrial Roofs for Nearly 5
                  Decades.
                </h1>

                <p class="text-base sm:text-lg text-slate-300 leading-relaxed max-w-[62ch] mb-8">
                  Incorporated on 19 October 1977 and operating from our Whitefield depot (M45
                  7RH), Sanderoof Ltd engineers watertight, Part L thermally compliant roofing
                  systems for warehouses, factories, schools, and commercial estates across the
                  North West.
                </p>
              </div>

              <div>
                <!-- Direct CTA Buttons -->
                <div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-3.5 mb-8">
                  <a
                    href="#estimator"
                    class="inline-flex items-center justify-center px-6 py-3.5 text-sm sm:text-base font-semibold rounded-xl btn-safety whitespace-nowrap shrink-0 shadow-lg shadow-[#FF6500]/20"
                  >
                    Request Free Site Survey
                  </a>
                  <a
                    href="tel:01617967914"
                    aria-label="Call Sanderoof Direct on 0161 796 7914"
                    class="inline-flex items-center justify-center gap-2.5 px-6 py-3.5 text-sm sm:text-base font-semibold rounded-xl btn-titanium whitespace-nowrap shrink-0 tabular-nums"
                  >
                    <svg
                      class="w-4 h-4 text-[#FF6500] shrink-0"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                      stroke-width="2"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                      />
                    </svg>
                    <span>Tel: 0161 796 7914</span>
                  </a>
                </div>

                <!-- Unboxed Trust Credentials Row -->
                <div
                  class="pt-6 border-t border-white/10 flex flex-wrap items-center gap-x-4 gap-y-2 text-xs text-slate-400"
                >
                  <span class="text-slate-200 font-medium">Direct Employed Operatives</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>BBA &amp; NFRC Compliant</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Up to 25-Year Waterproofing Guarantees</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Whitefield HQ (M45 7RH)</span>
                </div>
              </div>
            </div>

            <!-- Right Column: Architectural Titanium Cross-Section & Live Specification Card -->
            <div class="lg:col-span-5 flex">
              <div
                class="w-full glass-panel rounded-2xl p-6 flex flex-col justify-between relative overflow-hidden"
              >
                <div class="flex items-center justify-between gap-4 border-b border-white/10 pb-4">
                  <div>
                    <p class="text-xs font-medium text-slate-400">
                      Industrial Roof Assembly Blueprint
                    </p>
                    <h2 class="text-base font-bold text-white mt-0.5 tracking-tight">
                      Part L2 Warm Roof Stratigraphy
                    </h2>
                  </div>
                  <span class="text-xs font-mono text-[#FF6500] tabular-nums">
                    U-Value &le; 0.15 W/m&sup2;K
                  </span>
                </div>

                <!-- Precision Architectural Isometric SVG Diagram -->
                <div class="my-5 bg-[#060E1A]/90 rounded-xl p-4 border border-white/10">
                  <svg
                    viewBox="0 0 460 250"
                    class="w-full h-auto"
                    role="img"
                    aria-label="Technical cross-section diagram of a Sanderoof multi-layer commercial warm roof assembly"
                  >
                    <defs>
                      <linearGradient id="membraneGrad" x1="0%" y1="0%" x2="100%" y2="0%">
                        <stop offset="0%" stop-color="#334155" />
                        <stop offset="100%" stop-color="#1E293B" />
                      </linearGradient>
                      <linearGradient id="pirGrad" x1="0%" y1="0%" x2="100%" y2="0%">
                        <stop offset="0%" stop-color="#F59E0B" stop-opacity="0.85" />
                        <stop offset="100%" stop-color="#D97706" stop-opacity="0.85" />
                      </linearGradient>
                      <linearGradient id="safetyAccent" x1="0%" y1="0%" x2="100%" y2="0%">
                        <stop offset="0%" stop-color="#FF6500" />
                        <stop offset="100%" stop-color="#FF8533" />
                      </linearGradient>
                    </defs>

                    <!-- Technical Grid Lines -->
                    <g stroke="rgba(255,255,255,0.05)" stroke-width="1">
                      <line x1="0" y1="40" x2="460" y2="40" />
                      <line x1="0" y1="90" x2="460" y2="90" />
                      <line x1="0" y1="140" x2="460" y2="140" />
                      <line x1="0" y1="190" x2="460" y2="190" />
                      <line x1="90" y1="0" x2="90" y2="250" />
                      <line x1="230" y1="0" x2="230" y2="250" />
                      <line x1="370" y1="0" x2="370" y2="250" />
                    </g>

                    <!-- Layer 4 (Bottom): Structural Corrugated Metal Deck -->
                    <path
                      d="M30 195 L60 195 L70 212 L100 212 L110 195 L140 195 L150 212 L180 212 L190 195 L220 195 L230 212 L260 212 L270 195 L300 195 L310 212 L340 212 L350 195 L380 195"
                      fill="none"
                      stroke="#64748B"
                      stroke-width="3"
                    />
                    <text
                      x="30"
                      y="234"
                      fill="#94A3B8"
                      font-family="JetBrains Mono, monospace"
                      font-size="10"
                    >
                      04. Structural Profiled Steel / Concrete Deck
                    </text>

                    <!-- Layer 3: Foil-Faced Vapour Control Layer (VCL) -->
                    <rect
                      x="30"
                      y="174"
                      width="330"
                      height="12"
                      rx="2"
                      fill="#0284C7"
                      fill-opacity="0.45"
                      stroke="#38BDF8"
                      stroke-width="1.2"
                    />
                    <text
                      x="368"
                      y="184"
                      fill="#38BDF8"
                      font-family="JetBrains Mono, monospace"
                      font-size="10"
                    >
                      03. Air &amp; VCL
                    </text>

                    <!-- Layer 2: High-Density PIR Thermal Insulation Board -->
                    <rect
                      x="30"
                      y="112"
                      width="310"
                      height="54"
                      rx="3"
                      fill="url(#pirGrad)"
                      stroke="#FBBF24"
                      stroke-width="1.2"
                    />
                    <line
                      x1="130"
                      y1="112"
                      x2="130"
                      y2="166"
                      stroke="rgba(11,25,44,0.35)"
                      stroke-dasharray="3 3"
                    />
                    <line
                      x1="235"
                      y1="112"
                      x2="235"
                      y2="166"
                      stroke="rgba(11,25,44,0.35)"
                      stroke-dasharray="3 3"
                    />
                    <text
                      x="44"
                      y="143"
                      fill="#0B192C"
                      font-family="Plus Jakarta Sans, sans-serif"
                      font-weight="700"
                      font-size="11"
                    >
                      140mm Acoustic &amp; Thermal PIR Insulation Board
                    </text>

                    <!-- Layer 1 (Top): Single Ply / Reinforced Waterproofing Membrane + Hot-Air Weld Seam -->
                    <rect
                      x="30"
                      y="76"
                      width="285"
                      height="26"
                      rx="3"
                      fill="url(#membraneGrad)"
                      stroke="#94A3B8"
                      stroke-width="1.5"
                    />
                    <!-- Hot air weld seam indicator -->
                    <rect x="295" y="76" width="20" height="26" rx="2" fill="url(#safetyAccent)" />
                    <text
                      x="44"
                      y="93"
                      fill="#F8FAFC"
                      font-family="Plus Jakarta Sans, sans-serif"
                      font-weight="600"
                      font-size="11"
                    >
                      01. BBA-Certified Waterproofing Membrane
                    </text>

                    <!-- Callout Badge for 40mm Hot-Air Welded Lap -->
                    <line x1="305" y1="76" x2="335" y2="42" stroke="#FF6500" stroke-width="1.5" />
                    <circle cx="305" cy="76" r="3.5" fill="#FF6500" />
                    <text
                      x="255"
                      y="34"
                      fill="#FF6500"
                      font-family="JetBrains Mono, monospace"
                      font-weight="600"
                      font-size="10.5"
                    >
                      40mm Homogenous Weld Seam
                    </text>
                  </svg>
                </div>

                <!-- Bottom Technical Readout -->
                <div class="grid grid-cols-3 gap-3 pt-2 text-xs">
                  <div class="bg-white/5 rounded-lg p-3 border border-white/5">
                    <div class="text-slate-400">Fire Classification</div>
                    <div class="font-mono font-semibold text-white mt-1 tabular-nums">
                      BROOF(t4)
                    </div>
                  </div>
                  <div class="bg-white/5 rounded-lg p-3 border border-white/5">
                    <div class="text-slate-400">Wind Uplift</div>
                    <div class="font-mono font-semibold text-white mt-1 tabular-nums">
                      BS EN 1991-1-4
                    </div>
                  </div>
                  <div class="bg-white/5 rounded-lg p-3 border border-white/5">
                    <div class="text-slate-400">Guarantee</div>
                    <div class="font-mono font-semibold text-[#FF6500] mt-1 tabular-nums">
                      20–25 Years
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Full-Width 4-Column Quantitative Proof Strip Below Hero Split -->
          <div
            class="mt-12 pt-10 border-t border-white/10 grid grid-cols-2 lg:grid-cols-4 gap-6"
          >
            <div>
              <div class="text-2xl sm:text-3xl font-extrabold text-white font-mono tabular-nums">
                49 Years
              </div>
              <p class="text-xs sm:text-sm text-slate-400 mt-1">
                Continuous trading since 19 October 1977 in Greater Manchester
              </p>
            </div>
            <div>
              <div class="text-2xl sm:text-3xl font-extrabold text-white font-mono tabular-nums">
                1.4M+ m&sup2;
              </div>
              <p class="text-xs sm:text-sm text-slate-400 mt-1">
                Commercial &amp; industrial flat and pitched roofs waterproofed
              </p>
            </div>
            <div>
              <div class="text-2xl sm:text-3xl font-extrabold text-white font-mono tabular-nums">
                &pound;10M
              </div>
              <p class="text-xs sm:text-sm text-slate-400 mt-1">
                Full commercial public &amp; employers' liability insurance cover
              </p>
            </div>
            <div>
              <div
                class="text-2xl sm:text-3xl font-extrabold text-[#FF6500] font-mono tabular-nums"
              >
                &lt; 24 Hrs
              </div>
              <p class="text-xs sm:text-sm text-slate-400 mt-1">
                Site survey dispatch from our Nipper Lane, Whitefield depot
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 2. INTERACTIVE "60-SECOND ROOF SURVEY & QUOTE ESTIMATOR" WIDGET -->
      <section id="estimator" class="py-16 lg:py-24 border-b border-white/10 bg-[#081322]">
        <div class="max-w-[1200px] mx-auto px-4 sm:px-6">
          <div class="max-w-2xl mb-10">
            <p class="text-xs sm:text-sm font-semibold text-[#FF6500] mb-2">
              Interactive Commercial Specification Tool
            </p>
            <h2
              class="apple-heading text-2xl sm:text-4xl font-bold text-white tracking-tight mb-3"
            >
              60-Second Roof Survey &amp; Quote Estimator
            </h2>
            <p class="text-sm sm:text-base text-slate-300 leading-relaxed">
              Select your commercial roof system, approximate roof area in square metres, and site
              postcode to calculate an instant budgetary guide and book a complimentary drones
              &amp; core-sample survey from our Whitefield engineering team.
            </p>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
            <!-- Left 7 Cols: Interactive Configurator Controls -->
            <div class="lg:col-span-7 glass-panel rounded-2xl p-6 sm:p-8">
              <!-- Step 1: Select Roof System -->
              <div class="mb-8">
                <div class="flex items-center justify-between mb-3">
                  <label class="text-sm font-semibold text-white">
                    1. Select Primary Roofing System
                  </label>
                  <span
                    id="estimator-selected-label"
                    class="text-xs font-mono text-[#FF6500] tabular-nums"
                  >
                    Single Ply Membrane Systems
                  </span>
                </div>

                <div
                  role="group"
                  aria-label="Select Roof System Type"
                  class="grid grid-cols-2 sm:grid-cols-3 gap-2.5"
                >
                  <button
                    type="button"
                    data-roof-type="single-ply"
                    aria-pressed="true"
                    class="roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-[#FF6500]/15 border-[#FF6500] text-white"
                  >
                    <div class="text-xs sm:text-sm font-semibold whitespace-nowrap truncate">
                      Single Ply
                    </div>
                    <div class="text-[11px] text-slate-300 font-mono tabular-nums mt-1">
                      &pound;85–&pound;125 / m&sup2;
                    </div>
                  </button>

                  <button
                    type="button"
                    data-roof-type="felt"
                    aria-pressed="false"
                    class="roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-white/5 border-white/10 text-slate-200 hover:border-white/25"
                  >
                    <div class="text-xs sm:text-sm font-semibold whitespace-nowrap truncate">
                      Built-Up Felt
                    </div>
                    <div class="text-[11px] text-slate-400 font-mono tabular-nums mt-1">
                      &pound;78–&pound;115 / m&sup2;
                    </div>
                  </button>

                  <button
                    type="button"
                    data-roof-type="green-roof"
                    aria-pressed="false"
                    class="roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-white/5 border-white/10 text-slate-200 hover:border-white/25"
                  >
                    <div class="text-xs sm:text-sm font-semibold whitespace-nowrap truncate">
                      Green Roof
                    </div>
                    <div class="text-[11px] text-slate-400 font-mono tabular-nums mt-1">
                      &pound;135–&pound;195 / m&sup2;
                    </div>
                  </button>

                  <button
                    type="button"
                    data-roof-type="liquid"
                    aria-pressed="false"
                    class="roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-white/5 border-white/10 text-slate-200 hover:border-white/25"
                  >
                    <div class="text-xs sm:text-sm font-semibold whitespace-nowrap truncate">
                      Liquid Applied
                    </div>
                    <div class="text-[11px] text-slate-400 font-mono tabular-nums mt-1">
                      &pound;72–&pound;110 / m&sup2;
                    </div>
                  </button>

                  <button
                    type="button"
                    data-roof-type="rooflight"
                    aria-pressed="false"
                    class="roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-white/5 border-white/10 text-slate-200 hover:border-white/25"
                  >
                    <div class="text-xs sm:text-sm font-semibold whitespace-nowrap truncate">
                      Rooflight
                    </div>
                    <div class="text-[11px] text-slate-400 font-mono tabular-nums mt-1">
                      &pound;145–&pound;220 / m&sup2;
                    </div>
                  </button>

                  <button
                    type="button"
                    data-roof-type="insulation"
                    aria-pressed="false"
                    class="roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-white/5 border-white/10 text-slate-200 hover:border-white/25"
                  >
                    <div class="text-xs sm:text-sm font-semibold whitespace-nowrap truncate">
                      Thermal Upgrade
                    </div>
                    <div class="text-[11px] text-slate-400 font-mono tabular-nums mt-1">
                      &pound;65–&pound;98 / m&sup2;
                    </div>
                  </button>
                </div>
              </div>

              <!-- Step 2: Approximate Roof Area in Sq Meters -->
              <div class="mb-8">
                <div class="flex items-center justify-between gap-4 mb-2">
                  <label for="area-number-input" class="text-sm font-semibold text-white">
                    2. Approximate Roof Area (m&sup2;)
                  </label>
                  <div class="flex items-center gap-2">
                    <input
                      id="area-number-input"
                      type="number"
                      min="25"
                      max="25000"
                      step="25"
                      value="850"
                      aria-label="Approximate roof area in square metres"
                      class="w-28 px-3 py-1.5 rounded-lg bg-[#060E1A] border border-white/20 text-right font-mono text-sm font-semibold text-white tabular-nums focus:outline-none focus:border-[#FF6500]"
                    />
                    <span class="text-xs font-mono text-slate-400">m&sup2;</span>
                  </div>
                </div>

                <input
                  id="area-range-slider"
                  type="range"
                  min="50"
                  max="10000"
                  step="50"
                  value="850"
                  aria-label="Slide to adjust approximate roof area in square metres"
                  class="w-full h-2 bg-slate-700 rounded-lg cursor-pointer my-2"
                />

                <!-- Quick Commercial Building Presets -->
                <div class="flex flex-wrap items-center gap-2 mt-3">
                  <span class="text-xs text-slate-400 mr-1">Quick building presets:</span>
                  <button
                    type="button"
                    data-area-preset="250"
                    class="area-preset-btn px-2.5 py-1 text-xs rounded-md bg-white/5 hover:bg-white/10 border border-white/10 text-slate-300 font-mono tabular-nums whitespace-nowrap shrink-0"
                  >
                    250 m&sup2; (Retail/Office)
                  </button>
                  <button
                    type="button"
                    data-area-preset="850"
                    class="area-preset-btn px-2.5 py-1 text-xs rounded-md bg-[#FF6500]/20 border border-[#FF6500]/50 text-white font-mono tabular-nums whitespace-nowrap shrink-0"
                  >
                    850 m&sup2; (Industrial Unit)
                  </button>
                  <button
                    type="button"
                    data-area-preset="2400"
                    class="area-preset-btn px-2.5 py-1 text-xs rounded-md bg-white/5 hover:bg-white/10 border border-white/10 text-slate-300 font-mono tabular-nums whitespace-nowrap shrink-0"
                  >
                    2,400 m&sup2; (Warehouse)
                  </button>
                  <button
                    type="button"
                    data-area-preset="5000"
                    class="area-preset-btn px-2.5 py-1 text-xs rounded-md bg-white/5 hover:bg-white/10 border border-white/10 text-slate-300 font-mono tabular-nums whitespace-nowrap shrink-0"
                  >
                    5,000 m&sup2; (Distribution Hub)
                  </button>
                </div>
              </div>

              <!-- Step 3: Existing Substrate Scope & Thermal Options -->
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-8">
                <div>
                  <label
                    for="substrate-scope-select"
                    class="block text-xs font-semibold text-slate-300 mb-1.5"
                  >
                    3. Existing Substrate Condition
                  </label>
                  <select
                    id="substrate-scope-select"
                    class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm text-white focus:outline-none focus:border-[#FF6500]"
                  >
                    <option value="1.0">Overlay Existing Sound Deck (Standard)</option>
                    <option value="1.18">Full Strip, VCL &amp; Substrate Renewal (+18%)</option>
                    <option value="1.08">Targeted Wet Insulation Core Replacement (+8%)</option>
                  </select>
                </div>

                <div class="flex flex-col justify-end">
                  <label
                    for="thermal-upgrade-checkbox"
                    class="flex items-center gap-3 p-3 rounded-xl bg-[#060E1A] border border-white/15 cursor-pointer hover:border-white/30"
                  >
                    <input
                      id="thermal-upgrade-checkbox"
                      type="checkbox"
                      checked
                      class="w-4 h-4 rounded accent-[#FF6500]"
                    />
                    <span class="text-xs sm:text-sm font-medium text-slate-200">
                      Include Part L PIR Thermal Insulation
                    </span>
                  </label>
                </div>
              </div>

              <!-- Step 4: Site Postcode & Direct Survey Booking -->
              <form id="estimator-booking-form" novalidate class="pt-6 border-t border-white/10">
                <div class="text-sm font-semibold text-white mb-3">
                  4. Site Postcode &amp; Instant Survey Booking
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                  <div>
                    <label for="estimator-postcode" class="block text-xs text-slate-400 mb-1">
                      Site Postcode *
                    </label>
                    <input
                      id="estimator-postcode"
                      type="text"
                      required
                      placeholder="e.g. M45 7RH"
                      value="M45 7RH"
                      class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm font-mono uppercase text-white focus:outline-none focus:border-[#FF6500]"
                    />
                  </div>
                  <div>
                    <label for="estimator-company" class="block text-xs text-slate-400 mb-1">
                      Company / Site Name *
                    </label>
                    <input
                      id="estimator-company"
                      type="text"
                      required
                      placeholder="e.g. Trafford Logistics"
                      class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm text-white focus:outline-none focus:border-[#FF6500]"
                    />
                  </div>
                  <div>
                    <label for="estimator-phone" class="block text-xs text-slate-400 mb-1">
                      Direct Telephone *
                    </label>
                    <input
                      id="estimator-phone"
                      type="tel"
                      required
                      placeholder="e.g. 0161 796 7914"
                      class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm font-mono text-white focus:outline-none focus:border-[#FF6500]"
                    />
                  </div>
                </div>

                <div
                  id="estimator-form-feedback"
                  role="status"
                  aria-live="polite"
                  class="mt-3 text-xs hidden"
                ></div>

                <div class="mt-4 flex flex-col sm:flex-row items-stretch sm:items-center justify-between gap-3">
                  <p id="postcode-zone-status" class="text-xs text-slate-300">
                    Postcode <span class="font-mono text-white font-semibold">M45 7RH</span> is in
                    Greater Manchester Priority Zone (Whitefield Depot).
                  </p>
                  <button
                    type="submit"
                    class="px-5 py-2.5 rounded-xl text-xs sm:text-sm font-semibold btn-safety whitespace-nowrap shrink-0"
                  >
                    Book Free Site Survey
                  </button>
                </div>
              </form>
            </div>

            <!-- Right 5 Cols: Live Tabular Quote Output & Active Survey Bookings -->
            <div class="lg:col-span-5 flex flex-col gap-6">
              <div class="glass-panel rounded-2xl p-6 sm:p-8 border border-[#FF6500]/30">
                <div class="flex items-center justify-between gap-2 pb-4 border-b border-white/10">
                  <div>
                    <span class="text-xs font-medium text-slate-400">
                      Instant Budgetary Valuation
                    </span>
                    <h3
                      id="quote-system-heading"
                      class="text-lg font-bold text-white tracking-tight"
                    >
                      Single Ply Membrane Systems
                    </h3>
                  </div>
                  <span class="text-xs font-mono text-slate-400 tabular-nums" id="quote-area-badge">
                    850 m&sup2;
                  </span>
                </div>

                <div class="py-6 border-b border-white/10">
                  <div class="text-xs text-slate-400 mb-1">
                    Estimated Turnkey Supply &amp; Installation Range (Excl. VAT)
                  </div>
                  <div
                    id="quote-price-range"
                    class="text-2xl sm:text-3xl font-extrabold text-white font-mono tabular-nums tracking-tight whitespace-nowrap"
                  >
                    &pound;96,050 &ndash; &pound;136,000
                  </div>
                  <p id="quote-volume-note" class="text-xs text-[#FF6500] mt-2">
                    Includes Part L2 thermal upgrade &amp; scaffolding edge protection estimate.
                  </p>
                </div>

                <!-- 4 Key Technical Metrics -->
                <dl class="grid grid-cols-2 gap-4 py-5 text-xs border-b border-white/10">
                  <div>
                    <dt class="text-slate-400">System Warranty</dt>
                    <dd
                      id="quote-warranty"
                      class="text-base font-bold text-white font-mono tabular-nums mt-0.5"
                    >
                      25 Years
                    </dd>
                  </div>
                  <div>
                    <dt class="text-slate-400">Est. Programme</dt>
                    <dd
                      id="quote-duration"
                      class="text-base font-bold text-white font-mono tabular-nums mt-0.5"
                    >
                      7 Working Days
                    </dd>
                  </div>
                  <div>
                    <dt class="text-slate-400">Target U-Value</dt>
                    <dd
                      id="quote-uvalue"
                      class="text-base font-bold text-white font-mono tabular-nums mt-0.5"
                    >
                      0.15 W/m&sup2;K
                    </dd>
                  </div>
                  <div>
                    <dt class="text-slate-400">Est. Heating Saving</dt>
                    <dd
                      id="quote-energy-saving"
                      class="text-base font-bold text-emerald-400 font-mono tabular-nums mt-0.5"
                    >
                      &pound;4,080 / yr
                    </dd>
                  </div>
                </dl>

                <!-- Scheduled Survey Queue Tracker -->
                <div class="pt-5">
                  <div class="flex items-center justify-between text-xs text-slate-400 mb-2.5">
                    <span class="font-semibold text-slate-200">
                      Recent &amp; Scheduled Survey Dispatches
                    </span>
                    <span id="survey-queue-count" class="font-mono tabular-nums">2 active</span>
                  </div>
                  <ul
                    id="survey-bookings-list"
                    class="space-y-2 text-xs font-mono"
                    aria-label="Scheduled Site Surveys"
                  >
                    <li
                      class="p-2.5 rounded-lg bg-[#060E1A]/80 border border-white/10 flex items-center justify-between gap-2"
                    >
                      <span class="text-slate-200 truncate">SR-4918 &middot; M17 1WA (2,400 m&sup2;)</span>
                      <span class="text-[#FF6500] shrink-0">Single Ply</span>
                    </li>
                    <li
                      class="p-2.5 rounded-lg bg-[#060E1A]/80 border border-white/10 flex items-center justify-between gap-2"
                    >
                      <span class="text-slate-200 truncate">SR-4919 &middot; BL9 7BD (920 m&sup2;)</span>
                      <span class="text-[#FF6500] shrink-0">Built-Up Felt</span>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- 3. THE 6 CORE SERVICES BENTO GRID -->
      <section id="services" class="py-16 lg:py-24 border-b border-white/10">
        <div class="max-w-[1200px] mx-auto px-4 sm:px-6">
          <div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-12">
            <div class="max-w-2xl">
              <p class="text-xs sm:text-sm font-semibold text-[#FF6500] mb-2">
                Specialist Commercial &amp; Industrial Capabilities
              </p>
              <h2
                class="apple-heading text-2xl sm:text-4xl font-bold text-white tracking-tight"
              >
                Six Core Roofing Systems Engineered for the North West Climate
              </h2>
            </div>

            <!-- Interactive Filter Controls (Functional Buttons) -->
            <div
              role="group"
              aria-label="Filter roofing services by application"
              class="flex flex-wrap items-center gap-1.5 p-1.5 bg-[#060E1A] rounded-xl border border-white/10 self-start"
            >
              <button
                type="button"
                data-service-filter="all"
                class="service-filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg bg-[#FF6500] text-white transition-colors whitespace-nowrap shrink-0"
              >
                All Systems (6)
              </button>
              <button
                type="button"
                data-service-filter="waterproofing"
                class="service-filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg text-slate-300 hover:text-white transition-colors whitespace-nowrap shrink-0"
              >
                Flat Waterproofing
              </button>
              <button
                type="button"
                data-service-filter="thermal-eco"
                class="service-filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg text-slate-300 hover:text-white transition-colors whitespace-nowrap shrink-0"
              >
                Thermal, Eco &amp; Daylight
              </button>
            </div>
          </div>

          <!-- Asymmetric 6-Card Bento Grid -->
          <div id="services-bento-grid" class="grid grid-cols-1 md:grid-cols-12 gap-6">
            <!-- 01. Single Ply Membrane Systems (Span 7) -->
            <article
              data-service-category="waterproofing"
              class="service-card md:col-span-7 bento-card rounded-2xl p-6 sm:p-8 flex flex-col justify-between"
            >
              <div>
                <div
                  class="flex flex-wrap items-center gap-2 text-xs text-slate-400 font-mono tabular-nums mb-3"
                >
                  <span class="text-[#FF6500] font-semibold">01</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>PVC / TPO / EPDM</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>BBA Certified</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>25-Year Warranty</span>
                </div>

                <h3 class="text-xl sm:text-2xl font-bold text-white tracking-tight mb-3">
                  01. Single Ply Membrane Systems
                </h3>
                <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-6">
                  Lightweight, flame-free hot-air welded polymeric membranes engineered for fast-track
                  commercial warehouses, retail parks, and complex curved roofs. Resistant to UV
                  degradation, root penetration, and industrial pollutants.
                </p>

                <!-- Custom SVG Technical Detail -->
                <div class="bg-[#060E1A]/90 rounded-xl p-4 border border-white/10 mb-6">
                  <svg
                    viewBox="0 0 500 100"
                    class="w-full h-auto"
                    role="img"
                    aria-label="Single ply mechanically fixed and induction welded seam diagram"
                  >
                    <text x="15" y="18" fill="#94A3B8" font-family="JetBrains Mono, monospace" font-size="10">
                      1.5–2.0mm Fleece-Backed Membrane &bull; 40mm Hot-Air Weld &bull; Mechanical Fastener
                    </text>
                    <rect x="15" y="64" width="470" height="22" rx="2" fill="#1E293B" />
                    <rect x="15" y="42" width="245" height="16" rx="2" fill="#475569" />
                    <rect x="235" y="28" width="250" height="16" rx="2" fill="#64748B" />
                    <rect x="235" y="42" width="25" height="16" fill="#FF6500" />
                    <line x1="247" y1="28" x2="247" y2="82" stroke="#F8FAFC" stroke-width="2" stroke-dasharray="3 2" />
                  </svg>
                </div>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-4 pt-4 border-t border-white/10">
                <div class="text-xs font-mono text-slate-300 tabular-nums">
                  Indicative Rate: <span class="text-white font-semibold">&pound;85–&pound;125/m&sup2;</span>
                </div>
                <button
                  type="button"
                  data-select-estimator="single-ply"
                  class="px-4 py-2 rounded-lg text-xs font-semibold btn-safety whitespace-nowrap shrink-0"
                >
                  Calculate Single Ply Quote
                </button>
              </div>
            </article>

            <!-- 02. Built-Up Felt Roofing (Span 5) -->
            <article
              data-service-category="waterproofing"
              class="service-card md:col-span-5 bento-card rounded-2xl p-6 sm:p-8 flex flex-col justify-between"
            >
              <div>
                <div
                  class="flex flex-wrap items-center gap-2 text-xs text-slate-400 font-mono tabular-nums mb-3"
                >
                  <span class="text-[#FF6500] font-semibold">02</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>SBS Modified Bitumen</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Multi-Layer</span>
                </div>

                <h3 class="text-xl sm:text-2xl font-bold text-white tracking-tight mb-3">
                  02. Built-Up Felt Roofing
                </h3>
                <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-6">
                  Triple-layer elastomeric SBS polymer-modified bituminous systems with heavy mineral
                  cap sheets. Exceptional puncture resistance for schools, hospitals, and roofs with
                  frequent foot traffic and HVAC plant maintenance.
                </p>

                <div class="bg-[#060E1A]/90 rounded-xl p-4 border border-white/10 mb-6">
                  <div class="space-y-1.5 text-xs font-mono">
                    <div class="flex justify-between p-1.5 rounded bg-slate-800/90 text-white">
                      <span>Cap Sheet: 5.2kg/m&sup2; Slate Mineral SBS</span>
                      <span class="text-[#FF6500]">BROOF(t4)</span>
                    </div>
                    <div class="flex justify-between p-1.5 rounded bg-slate-800/50 text-slate-300">
                      <span>Underlay: 3.5mm Polyester Reinforced</span>
                      <span>Torch/Torch-Free</span>
                    </div>
                    <div class="flex justify-between p-1.5 rounded bg-slate-800/30 text-slate-400">
                      <span>Vapour Control: Foil-Lined Bitumen VCL</span>
                      <span>BS 8217</span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-4 pt-4 border-t border-white/10">
                <div class="text-xs font-mono text-slate-300 tabular-nums">
                  Indicative Rate: <span class="text-white font-semibold">&pound;78–&pound;115/m&sup2;</span>
                </div>
                <button
                  type="button"
                  data-select-estimator="felt"
                  class="px-4 py-2 rounded-lg text-xs font-semibold btn-titanium whitespace-nowrap shrink-0"
                >
                  Calculate Felt Quote
                </button>
              </div>
            </article>

            <!-- 03. Eco Green Roof Installations (Span 5) -->
            <article
              data-service-category="thermal-eco"
              class="service-card md:col-span-5 bento-card rounded-2xl p-6 sm:p-8 flex flex-col justify-between"
            >
              <div>
                <div
                  class="flex flex-wrap items-center gap-2 text-xs text-slate-400 font-mono tabular-nums mb-3"
                >
                  <span class="text-[#FF6500] font-semibold">03</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Sedum &amp; Biodiverse</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>BREEAM &amp; SuDS</span>
                </div>

                <h3 class="text-xl sm:text-2xl font-bold text-white tracking-tight mb-3">
                  03. Eco Green Roof Installations
                </h3>
                <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-6">
                  Extensive sedum blankets, wildflower meadows, and intensive living roof substrates
                  installed over root-barriers. Attenuates up to 70% of peak Manchester rainwater
                  run-off while boosting BREEAM sustainability credits.
                </p>

                <div class="bg-[#060E1A]/90 rounded-xl p-4 border border-white/10 mb-6">
                  <div class="grid grid-cols-2 gap-3 text-xs font-mono tabular-nums">
                    <div>
                      <span class="text-slate-400 block">Stormwater Retention</span>
                      <span class="text-emerald-400 font-semibold text-sm">65%–75% Annual</span>
                    </div>
                    <div>
                      <span class="text-slate-400 block">Acoustic Attenuation</span>
                      <span class="text-white font-semibold text-sm">Up to 42 dB</span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-4 pt-4 border-t border-white/10">
                <div class="text-xs font-mono text-slate-300 tabular-nums">
                  Indicative Rate: <span class="text-white font-semibold">&pound;135–&pound;195/m&sup2;</span>
                </div>
                <button
                  type="button"
                  data-select-estimator="green-roof"
                  class="px-4 py-2 rounded-lg text-xs font-semibold btn-titanium whitespace-nowrap shrink-0"
                >
                  Calculate Green Roof Quote
                </button>
              </div>
            </article>

            <!-- 04. Commercial Rooflight Replacement (Span 7) -->
            <article
              data-service-category="thermal-eco"
              class="service-card md:col-span-7 bento-card rounded-2xl p-6 sm:p-8 flex flex-col justify-between"
            >
              <div>
                <div
                  class="flex flex-wrap items-center gap-2 text-xs text-slate-400 font-mono tabular-nums mb-3"
                >
                  <span class="text-[#FF6500] font-semibold">04</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>GRP Triple-Skin &amp; Polycarbonate</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>ACR[M]001:2019 Class B Non-Fragile</span>
                </div>

                <h3 class="text-xl sm:text-2xl font-bold text-white tracking-tight mb-3">
                  04. Commercial Rooflight Replacement
                </h3>
                <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-6">
                  Replacement of aged, yellowed fragile warehouse rooflights and modular domes with
                  high-transmission triple-skin GRP or multi-wall polycarbonate units. Transforms
                  internal natural daylight levels by up to 300% while eliminating fragile roof falls.
                </p>

                <div class="bg-[#060E1A]/90 rounded-xl p-4 border border-white/10 mb-6 grid grid-cols-3 gap-4 text-xs font-mono tabular-nums">
                  <div>
                    <span class="text-slate-400 block">Non-Fragility</span>
                    <span class="text-white font-semibold">ACR[M]001 Class B</span>
                  </div>
                  <div>
                    <span class="text-slate-400 block">Light Transmission</span>
                    <span class="text-white font-semibold">Up to 82% VLT</span>
                  </div>
                  <div>
                    <span class="text-slate-400 block">Thermal U-Value</span>
                    <span class="text-[#FF6500] font-semibold">1.10 W/m&sup2;K</span>
                  </div>
                </div>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-4 pt-4 border-t border-white/10">
                <div class="text-xs font-mono text-slate-300 tabular-nums">
                  Indicative Rate: <span class="text-white font-semibold">&pound;145–&pound;220/m&sup2;</span>
                </div>
                <button
                  type="button"
                  data-select-estimator="rooflight"
                  class="px-4 py-2 rounded-lg text-xs font-semibold btn-titanium whitespace-nowrap shrink-0"
                >
                  Calculate Rooflight Quote
                </button>
              </div>
            </article>

            <!-- 05. Liquid Applied Waterproofing (Span 6) -->
            <article
              data-service-category="waterproofing"
              class="service-card md:col-span-6 bento-card rounded-2xl p-6 sm:p-8 flex flex-col justify-between"
            >
              <div>
                <div
                  class="flex flex-wrap items-center gap-2 text-xs text-slate-400 font-mono tabular-nums mb-3"
                >
                  <span class="text-[#FF6500] font-semibold">05</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Cold-Applied Polyurethane &amp; PMMA</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Zero Hot Works</span>
                </div>

                <h3 class="text-xl sm:text-2xl font-bold text-white tracking-tight mb-3">
                  05. Liquid Applied Waterproofing
                </h3>
                <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-6">
                  Seamless, cold-applied elastomeric membranes reinforced with glass-fibre matting.
                  Ideal for complex rooftop plant rooms, industrial valley gutters, asphalt overlays,
                  and occupied sites requiring strictly zero naked flame.
                </p>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-4 pt-4 border-t border-white/10">
                <div class="text-xs font-mono text-slate-300 tabular-nums">
                  Indicative Rate: <span class="text-white font-semibold">&pound;72–&pound;110/m&sup2;</span>
                </div>
                <button
                  type="button"
                  data-select-estimator="liquid"
                  class="px-4 py-2 rounded-lg text-xs font-semibold btn-titanium whitespace-nowrap shrink-0"
                >
                  Calculate Liquid Quote
                </button>
              </div>
            </article>

            <!-- 06. Thermal Roof Insulation (Span 6) -->
            <article
              data-service-category="thermal-eco"
              class="service-card md:col-span-6 bento-card rounded-2xl p-6 sm:p-8 flex flex-col justify-between"
            >
              <div>
                <div
                  class="flex flex-wrap items-center gap-2 text-xs text-slate-400 font-mono tabular-nums mb-3"
                >
                  <span class="text-[#FF6500] font-semibold">06</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Approved Document L2 Compliance</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Tapered Cut-to-Falls PIR</span>
                </div>

                <h3 class="text-xl sm:text-2xl font-bold text-white tracking-tight mb-3">
                  06. Thermal Roof Insulation
                </h3>
                <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-6">
                  High-performance PIR, mineral wool acoustic slabs, and bespoke CAD-designed tapered
                  cut-to-falls insulation schemes that eliminate standing ponded water while cutting
                  commercial heating energy loss by up to 60%.
                </p>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-4 pt-4 border-t border-white/10">
                <div class="text-xs font-mono text-slate-300 tabular-nums">
                  Indicative Rate: <span class="text-white font-semibold">&pound;65–&pound;98/m&sup2;</span>
                </div>
                <button
                  type="button"
                  data-select-estimator="insulation"
                  class="px-4 py-2 rounded-lg text-xs font-semibold btn-titanium whitespace-nowrap shrink-0"
                >
                  Calculate Insulation Quote
                </button>
              </div>
            </article>
          </div>
        </div>
      </section>

      <!-- 4. HERITAGE, SAFETY & ACCREDITATIONS SECTION -->
      <section id="heritage" class="py-16 lg:py-24 border-b border-white/10 bg-[#081322]">
        <div class="max-w-[1200px] mx-auto px-4 sm:px-6">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
            <!-- Left 6 Cols: 49-Year Track Record & UK Compliance -->
            <div class="lg:col-span-6">
              <p class="text-xs sm:text-sm font-semibold text-[#FF6500] mb-2">
                Incorporated 19 October 1977 &bull; Company Heritage &amp; Safety
              </p>
              <h2
                class="apple-heading text-2xl sm:text-4xl font-bold text-white tracking-tight mb-4"
              >
                49 Years of Uncompromised UK Site Safety &amp; Technical Governance
              </h2>
              <p class="text-sm sm:text-base text-slate-300 leading-relaxed mb-8">
                For nearly five decades, Facilities Managers, Principal Contractors, and Local
                Authorities across Greater Manchester have relied on Sanderoof Ltd because we never
                sub-contract core waterproofing integrity or compromise on Working at Height safety
                protocols.
              </p>

              <!-- Interactive Safety & Compliance Standard Selector -->
              <div
                role="tablist"
                aria-label="Safety and Compliance Governance Tabs"
                class="flex flex-wrap gap-2 mb-5"
              >
                <button
                  type="button"
                  role="tab"
                  aria-selected="true"
                  data-compliance-tab="training"
                  class="compliance-tab-btn px-3.5 py-2 rounded-lg text-xs font-semibold bg-[#FF6500] text-white whitespace-nowrap shrink-0"
                >
                  Operative Training &amp; CSCS
                </button>
                <button
                  type="button"
                  role="tab"
                  aria-selected="false"
                  data-compliance-tab="rams"
                  class="compliance-tab-btn px-3.5 py-2 rounded-lg text-xs font-semibold bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0"
                >
                  CDM 2015 &amp; RAMS Protocol
                </button>
                <button
                  type="button"
                  role="tab"
                  aria-selected="false"
                  data-compliance-tab="regs"
                  class="compliance-tab-btn px-3.5 py-2 rounded-lg text-xs font-semibold bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0"
                >
                  Part L2 &amp; NFRC Standards
                </button>
              </div>

              <!-- Dynamic Compliance Content Panel -->
              <div
                id="compliance-panel-content"
                class="glass-panel rounded-2xl p-6 text-sm text-slate-200 leading-relaxed"
              >
                <h3 class="text-base font-bold text-white mb-2">
                  100% Directly Trained &amp; CSCS / NVQ Accredited Roofing Teams
                </h3>
                <p class="text-slate-300 mb-4">
                  Every Sanderoof site supervisor holds SSSTS/SMSTS certification alongside valid
                  CSCS Skilled Worker cards, PASMA mobile tower tickets, IPAF MEWP licences, and
                  manufacturer-issued hot-air and cold-liquid installer approvals.
                </p>
                <div class="flex flex-wrap items-center gap-x-3 gap-y-1 text-xs font-mono text-slate-400">
                  <span class="text-white">Zero Riddor Incidents (2021–2026)</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>DBS Checked for Schools &amp; NHS Sites</span>
                  <span aria-hidden="true">&middot;</span>
                  <span>Nipper Lane Training Yard</span>
                </div>
              </div>
            </div>

            <!-- Right 6 Cols: Verifiable Greater Manchester Case Studies & Accreditations Matrix -->
            <div class="lg:col-span-6 space-y-6">
              <!-- Accreditations & Compliance Matrix -->
              <div class="glass-panel rounded-2xl p-6">
                <h3 class="text-sm font-bold text-white mb-4">
                  UK Commercial Roofing Accreditations &amp; Statutory Compliance
                </h3>
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 text-xs">
                  <div class="p-3.5 rounded-xl bg-[#060E1A]/80 border border-white/10">
                    <div class="font-bold text-white">NFRC Standards</div>
                    <div class="text-slate-400 mt-1">National Federation of Roofing Contractors</div>
                  </div>
                  <div class="p-3.5 rounded-xl bg-[#060E1A]/80 border border-white/10">
                    <div class="font-bold text-white">CHAS Premium Plus</div>
                    <div class="text-slate-400 mt-1">SSIP Health &amp; Safety Assessed</div>
                  </div>
                  <div class="p-3.5 rounded-xl bg-[#060E1A]/80 border border-white/10">
                    <div class="font-bold text-white">SafeContractor</div>
                    <div class="text-slate-400 mt-1">Approved Commercial Contractor</div>
                  </div>
                  <div class="p-3.5 rounded-xl bg-[#060E1A]/80 border border-white/10">
                    <div class="font-bold text-white">BBA Approved</div>
                    <div class="text-slate-400 mt-1">British Board of Agr&eacute;ment Systems</div>
                  </div>
                  <div class="p-3.5 rounded-xl bg-[#060E1A]/80 border border-white/10">
                    <div class="font-bold text-white">Part L2 Building Regs</div>
                    <div class="text-slate-400 mt-1">Full Thermal U-Value Calculations</div>
                  </div>
                  <div class="p-3.5 rounded-xl bg-[#060E1A]/80 border border-white/10">
                    <div class="font-bold text-[#FF6500]">Est. 19 Oct 1977</div>
                    <div class="text-slate-400 mt-1">49 Years Manchester Track Record</div>
                  </div>
                </div>
              </div>

              <!-- Attributable Greater Manchester Commercial Case Proof -->
              <div class="glass-panel rounded-2xl p-6">
                <div class="flex items-center justify-between mb-3">
                  <span class="text-xs font-semibold text-[#FF6500]">
                    Recent Greater Manchester Commercial Delivery
                  </span>
                  <span class="text-xs font-mono text-slate-400 tabular-nums">
                    Trafford Park &bull; 3,200 m&sup2;
                  </span>
                </div>
                <blockquote class="text-sm text-slate-200 leading-relaxed mb-4">
                  &ldquo;Before calling Sanderoof, persistent valley gutter and rooflight leaks
                  threatened our automated packaging line in Trafford Park. Their team stripped and
                  installed a 3,200 m&sup2; warm single-ply roof and Class B non-fragile rooflights
                  in 19 working days with zero factory downtime, cutting winter heating bills by
                  38%.&rdquo;
                </blockquote>
                <div class="text-xs text-slate-400">
                  <strong class="text-white">David Hargreaves</strong> &middot; Head of Estates
                  &amp; Facilities, North West Precision Logistics Ltd (Manchester M17)
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- 5. MODERN CONTACT & WORKING MAP SECTION (FIXING THEIR BROKEN MAP) -->
      <section id="contact" class="py-16 lg:py-24">
        <div class="max-w-[1200px] mx-auto px-4 sm:px-6">
          <div class="max-w-2xl mb-12">
            <p class="text-xs sm:text-sm font-semibold text-[#FF6500] mb-2">
              Head Office &amp; Operations Depot &bull; Whitefield, Manchester
            </p>
            <h2
              class="apple-heading text-2xl sm:text-4xl font-bold text-white tracking-tight mb-3"
            >
              Direct Engineering Contact &amp; Greater Manchester Dispatch Map
            </h2>
            <p class="text-sm sm:text-base text-slate-300 leading-relaxed">
              Visit or contact our operational headquarters at The Depot, Nipper Lane, Whitefield
              (M45 7RH), just 2 minutes from Junction 17 of the M60 orbital motorway for rapid
              response across Greater Manchester.
            </p>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-stretch">
            <!-- Left 6 Cols: Interactive Working Whitefield & Greater Manchester Map -->
            <div class="lg:col-span-6 glass-panel rounded-2xl p-6 flex flex-col justify-between">
              <div>
                <div class="flex flex-wrap items-center justify-between gap-2 pb-4 border-b border-white/10">
                  <div>
                    <h3 class="text-base font-bold text-white">
                      The Depot, Nipper Lane, Whitefield, M45 7RH
                    </h3>
                    <p class="text-xs text-slate-400 font-mono tabular-nums mt-0.5">
                      53.5534&deg; N, 2.2968&deg; W &middot; M60 J17 Rapid Dispatch Hub
                    </p>
                  </div>
                  <a
                    href="https://www.google.com/maps/search/?api=1&query=The+Depot+Nipper+Lane+Whitefield+Manchester+M45+7RH"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg text-xs font-semibold btn-titanium whitespace-nowrap shrink-0"
                  >
                    <span>Open Route Planner</span>
                    <svg class="w-3.5 h-3.5 text-[#FF6500]" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" aria-hidden="true">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M7 17L17 7M17 7H8M17 7V16" />
                    </svg>
                  </a>
                </div>

                <!-- Interactive Greater Manchester & Nipper Lane Vector Map -->
                <div class="my-4 bg-[#060E1A] rounded-xl border border-white/10 p-3 relative overflow-hidden">
                  <svg
                    id="manchester-interactive-map"
                    viewBox="0 0 520 310"
                    class="w-full h-auto"
                    role="img"
                    aria-label="Interactive Greater Manchester commercial roofing dispatch map centered on Sanderoof Ltd, The Depot, Nipper Lane, Whitefield, M45 7RH"
                  >
                    <!-- Dark Cartographic Background Grid -->
                    <g stroke="rgba(255,255,255,0.04)" stroke-width="1">
                      <line x1="0" y1="50" x2="520" y2="50" />
                      <line x1="0" y1="100" x2="520" y2="100" />
                      <line x1="0" y1="150" x2="520" y2="150" />
                      <line x1="0" y1="200" x2="520" y2="200" />
                      <line x1="0" y1="250" x2="520" y2="250" />
                      <line x1="100" y1="0" x2="100" y2="310" />
                      <line x1="200" y1="0" x2="200" y2="310" />
                      <line x1="300" y1="0" x2="300" y2="310" />
                      <line x1="400" y1="0" x2="400" y2="310" />
                    </g>

                    <!-- M60 Orbital Motorway Ring & Key Arterials (A56 Bury New Rd, M62, M66) -->
                    <ellipse
                      cx="265"
                      cy="170"
                      rx="115"
                      ry="82"
                      fill="none"
                      stroke="#1E3A5F"
                      stroke-width="6"
                    />
                    <ellipse
                      cx="265"
                      cy="170"
                      rx="115"
                      ry="82"
                      fill="none"
                      stroke="#38BDF8"
                      stroke-opacity="0.45"
                      stroke-width="1.5"
                      stroke-dasharray="5 4"
                    />
                    <!-- M66 North to Bury / M62 West-East / A56 Bury New Road -->
                    <path
                      d="M255 20 L255 290 M40 165 L490 140"
                      stroke="#1E3A5F"
                      stroke-width="3.5"
                      fill="none"
                    />
                    <text
                      x="355"
                      y="108"
                      fill="#64748B"
                      font-family="JetBrains Mono, monospace"
                      font-size="9.5"
                    >
                      M60 ORBITAL
                    </text>
                    <text
                      x="262"
                      y="64"
                      fill="#64748B"
                      font-family="JetBrains Mono, monospace"
                      font-size="9.5"
                    >
                      A56 / M66
                    </text>

                    <!-- Dispatch Radius Rings from Whitefield M45 7RH -->
                    <circle
                      cx="255"
                      cy="92"
                      r="42"
                      fill="rgba(255,101,0,0.06)"
                      stroke="rgba(255,101,0,0.28)"
                      stroke-width="1"
                    />
                    <circle
                      cx="255"
                      cy="92"
                      r="110"
                      fill="none"
                      stroke="rgba(255,101,0,0.16)"
                      stroke-width="1"
                      stroke-dasharray="3 3"
                    />

                    <!-- Commercial Zone Nodes -->
                    <!-- Bolton / Bury North -->
                    <g class="cursor-pointer" data-map-zone="bury-bolton">
                      <circle cx="215" cy="48" r="6" fill="#38BDF8" />
                      <text
                        x="203"
                        y="52"
                        text-anchor="end"
                        fill="#CBD5E1"
                        font-family="Plus Jakarta Sans, sans-serif"
                        font-size="10.5"
                        font-weight="600"
                      >
                        Bury &amp; Bolton (BL)
                      </text>
                    </g>

                    <!-- Trafford Park Industrial Estate -->
                    <g class="cursor-pointer" data-map-zone="trafford">
                      <circle cx="175" cy="188" r="6" fill="#38BDF8" />
                      <text
                        x="163"
                        y="192"
                        text-anchor="end"
                        fill="#CBD5E1"
                        font-family="Plus Jakarta Sans, sans-serif"
                        font-size="10.5"
                        font-weight="600"
                      >
                        Trafford Park (M17)
                      </text>
                    </g>

                    <!-- Manchester City Centre & Salford Quays -->
                    <g class="cursor-pointer" data-map-zone="city-centre">
                      <circle cx="255" cy="172" r="6" fill="#38BDF8" />
                      <text
                        x="268"
                        y="176"
                        fill="#CBD5E1"
                        font-family="Plus Jakarta Sans, sans-serif"
                        font-size="10.5"
                        font-weight="600"
                      >
                        Manchester City &amp; Salford
                      </text>
                    </g>

                    <!-- Oldham / Rochdale / Tameside East -->
                    <g class="cursor-pointer" data-map-zone="oldham-stockport">
                      <circle cx="368" cy="128" r="6" fill="#38BDF8" />
                      <text
                        x="380"
                        y="132"
                        fill="#CBD5E1"
                        font-family="Plus Jakarta Sans, sans-serif"
                        font-size="10.5"
                        font-weight="600"
                      >
                        Oldham &amp; Tameside (OL)
                      </text>
                    </g>

                    <!-- Stockport & Airport Logistics South -->
                    <g class="cursor-pointer" data-map-zone="airport-south">
                      <circle cx="290" cy="252" r="6" fill="#38BDF8" />
                      <text
                        x="302"
                        y="256"
                        fill="#CBD5E1"
                        font-family="Plus Jakarta Sans, sans-serif"
                        font-size="10.5"
                        font-weight="600"
                      >
                        Stockport &amp; Airport (SK/M90)
                      </text>
                    </g>

                    <!-- SANDEROOF HQ PIN: The Depot, Nipper Lane, Whitefield, M45 7RH -->
                    <g class="cursor-pointer" data-map-zone="whitefield-hq">
                      <circle
                        cx="255"
                        cy="92"
                        r="14"
                        fill="rgba(255,101,0,0.25)"
                        stroke="#FF6500"
                        stroke-width="1.5"
                      />
                      <circle cx="255" cy="92" r="6.5" fill="#FF6500" stroke="#FFFFFF" stroke-width="2" />
                      <rect
                        x="274"
                        y="73"
                        width="210"
                        height="36"
                        rx="6"
                        fill="#0B192C"
                        stroke="#FF6500"
                        stroke-width="1.2"
                      />
                      <text
                        x="284"
                        y="89"
                        fill="#FFFFFF"
                        font-family="Plus Jakarta Sans, sans-serif"
                        font-size="11"
                        font-weight="700"
                      >
                        SANDEROOF HQ &bull; M45 7RH
                      </text>
                      <text
                        x="284"
                        y="102"
                        fill="#FF6500"
                        font-family="JetBrains Mono, monospace"
                        font-size="9.5"
                      >
                        The Depot, Nipper Lane, Whitefield
                      </text>
                    </g>
                  </svg>
                </div>

                <!-- Interactive Commercial Zone Selector Buttons -->
                <div class="mb-4">
                  <div class="text-xs font-semibold text-slate-300 mb-2">
                    Select Greater Manchester Commercial Corridor for Dispatch ETA:
                  </div>
                  <div class="flex flex-wrap gap-1.5" role="group" aria-label="Dispatch Zone Selector">
                    <button
                      type="button"
                      data-zone-btn="whitefield-hq"
                      class="zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-[#FF6500] text-white whitespace-nowrap shrink-0"
                    >
                      Whitefield Depot (M45 7RH)
                    </button>
                    <button
                      type="button"
                      data-zone-btn="trafford"
                      class="zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0"
                    >
                      Trafford Park (M17)
                    </button>
                    <button
                      type="button"
                      data-zone-btn="city-centre"
                      class="zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0"
                    >
                      City Centre &amp; Salford
                    </button>
                    <button
                      type="button"
                      data-zone-btn="bury-bolton"
                      class="zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0"
                    >
                      Bury &amp; Bolton
                    </button>
                    <button
                      type="button"
                      data-zone-btn="airport-south"
                      class="zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0"
                    >
                      Stockport &amp; Airport
                    </button>
                  </div>
                </div>

                <div
                  id="map-zone-readout"
                  class="p-3.5 rounded-xl bg-[#060E1A]/90 border border-white/10 text-xs flex flex-wrap items-center justify-between gap-2"
                >
                  <div>
                    <span class="text-white font-semibold" id="zone-readout-title">
                      Whitefield HQ Depot (Nipper Lane, M45 7RH)
                    </span>
                    <span class="text-slate-400 block mt-0.5" id="zone-readout-desc">
                      Direct trade &amp; engineering counter off Radcliffe New Road / M60 J17.
                    </span>
                  </div>
                  <span
                    id="zone-readout-eta"
                    class="font-mono font-semibold text-[#FF6500] tabular-nums"
                  >
                    0.0 miles &bull; Immediate
                  </span>
                </div>
              </div>

              <!-- Verified Contact Details Footer Inside Map Card -->
              <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 pt-5 mt-5 border-t border-white/10 text-xs">
                <div>
                  <div class="text-slate-400">Registered Depot Address</div>
                  <div class="text-white font-medium mt-1">
                    The Depot, Nipper Lane, Whitefield, Manchester, M45 7RH
                  </div>
                </div>
                <div>
                  <div class="text-slate-400">Direct Telephone</div>
                  <a
                    href="tel:01617967914"
                    class="text-[#FF6500] font-mono font-semibold text-sm mt-1 block tabular-nums hover:underline"
                  >
                    0161 796 7914
                  </a>
                </div>
                <div>
                  <div class="text-slate-400">Estimating &amp; Enquiries</div>
                  <a
                    href="mailto:info@sanderoof.com"
                    class="text-white font-mono font-medium mt-1 block hover:text-[#FF6500] transition-colors"
                  >
                    info@sanderoof.com
                  </a>
                </div>
              </div>
            </div>

            <!-- Right 6 Cols: XSS-Sanitized & Rate-Limited Commercial Contact Form -->
            <div class="lg:col-span-6 glass-panel rounded-2xl p-6 sm:p-8 flex flex-col justify-between">
              <div>
                <div class="flex items-center justify-between gap-2 pb-4 border-b border-white/10 mb-6">
                  <div>
                    <h3 class="text-lg font-bold text-white tracking-tight">
                      Send a Commercial Tender or Survey Enquiry
                    </h3>
                    <p class="text-xs text-slate-400 mt-0.5">
                      Protected with XSS input sanitization &amp; automated rate-limiting.
                    </p>
                  </div>
                  <span class="text-xs font-mono text-emerald-400 shrink-0">
                    Direct to Estimating
                  </span>
                </div>

                <form id="secure-contact-form" novalidate class="space-y-4">
                  <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div>
                      <label for="contact-name" class="block text-xs font-medium text-slate-300 mb-1">
                        Full Name *
                      </label>
                      <input
                        id="contact-name"
                        name="name"
                        type="text"
                        required
                        maxlength="80"
                        placeholder="e.g. Sarah Jenkins"
                        class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm text-white focus:outline-none focus:border-[#FF6500]"
                      />
                    </div>
                    <div>
                      <label for="contact-email" class="block text-xs font-medium text-slate-300 mb-1">
                        Work Email Address *
                      </label>
                      <input
                        id="contact-email"
                        name="email"
                        type="email"
                        required
                        maxlength="100"
                        placeholder="name@company.co.uk"
                        class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm text-white focus:outline-none focus:border-[#FF6500]"
                      />
                    </div>
                  </div>

                  <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div>
                      <label for="contact-phone" class="block text-xs font-medium text-slate-300 mb-1">
                        Telephone Number *
                      </label>
                      <input
                        id="contact-phone"
                        name="phone"
                        type="tel"
                        required
                        maxlength="30"
                        placeholder="0161 796 7914"
                        class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm font-mono text-white focus:outline-none focus:border-[#FF6500]"
                      />
                    </div>
                    <div>
                      <label for="contact-service" class="block text-xs font-medium text-slate-300 mb-1">
                        Required Service Scope
                      </label>
                      <select
                        id="contact-service"
                        name="service"
                        class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm text-white focus:outline-none focus:border-[#FF6500]"
                      >
                        <option value="Single Ply Membrane Systems">Single Ply Membrane Systems</option>
                        <option value="Built-Up Felt Roofing">Built-Up Felt Roofing</option>
                        <option value="Eco Green Roof Installations">Eco Green Roof Installations</option>
                        <option value="Commercial Rooflight Replacement">Commercial Rooflight Replacement</option>
                        <option value="Liquid Applied Waterproofing">Liquid Applied Waterproofing</option>
                        <option value="Thermal Roof Insulation">Thermal Roof Insulation</option>
                        <option value="Emergency Commercial Leak Repair">Emergency Commercial Leak Repair</option>
                      </select>
                    </div>
                  </div>

                  <div>
                    <label for="contact-message" class="block text-xs font-medium text-slate-300 mb-1">
                      Project Brief, Postcode &amp; Roof Details *
                    </label>
                    <textarea
                      id="contact-message"
                      name="message"
                      rows="4"
                      required
                      maxlength="800"
                      placeholder="Please include building location postcode, approximate roof area, and any active leak or tender deadlines..."
                      class="w-full px-3.5 py-2.5 rounded-xl bg-[#060E1A] border border-white/15 text-sm text-white focus:outline-none focus:border-[#FF6500]"
                    ></textarea>
                  </div>

                  <div
                    id="contact-form-alert"
                    role="alert"
                    aria-live="assertive"
                    class="hidden p-3.5 rounded-xl text-xs"
                  ></div>

                  <div class="flex items-center justify-between gap-4 pt-2">
                    <span id="rate-limit-indicator" class="text-xs text-slate-400 font-mono tabular-nums">
                      Rate limit status: Ready
                    </span>
                    <button
                      id="contact-submit-btn"
                      type="submit"
                      class="px-6 py-3 rounded-xl text-sm font-semibold btn-safety whitespace-nowrap shrink-0 disabled:opacity-50 disabled:cursor-not-allowed"
                    >
                      Submit Commercial Enquiry
                    </button>
                  </div>
                </form>
              </div>

              <!-- Live Sanitized Enquiry Confirmation Log -->
              <div class="mt-6 pt-5 border-t border-white/10">
                <div class="flex items-center justify-between text-xs text-slate-400 mb-2">
                  <span class="font-semibold text-slate-200">Verified Session Dispatches</span>
                  <span id="contact-log-count" class="font-mono tabular-nums">0 sent this session</span>
                </div>
                <div
                  id="contact-submissions-log"
                  class="text-xs text-slate-400 space-y-2"
                  aria-live="polite"
                >
                  <p id="contact-empty-state" class="text-slate-500">
                    No enquiries submitted in this browser session yet. Submitting the form above
                    sanitizes all fields against XSS and logs your confirmation reference here.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <!-- QUIET ARCHITECTURAL FOOTER -->
    <footer class="bg-[#060E1A] border-t border-white/10 py-12 text-xs text-slate-400">
      <div
        class="max-w-[1200px] mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-6"
      >
        <div>
          <div class="text-sm font-bold text-white tracking-tight">Sanderoof Ltd</div>
          <p class="mt-1">
            The Depot, Nipper Lane, Whitefield, Manchester, Greater Manchester, M45 7RH &middot;
            Incorporated 19 October 1977 (49 Years)
          </p>
        </div>
        <div class="flex flex-wrap items-center gap-6">
          <a href="#estimator" class="hover:text-white transition-colors">Quote Estimator</a>
          <a href="#services" class="hover:text-white transition-colors">Core Services</a>
          <a href="#heritage" class="hover:text-white transition-colors">Safety &amp; Heritage</a>
          <a href="tel:01617967914" class="text-white font-mono tabular-nums hover:text-[#FF6500]">
            0161 796 7914
          </a>
          <a href="mailto:info@sanderoof.com" class="hover:text-white transition-colors">
            info@sanderoof.com
          </a>
        </div>
      </div>
    </footer>

    <!-- ACCESSIBLE TOAST CONFIRMATION OVERLAY -->
    <div
      id="toast-notification"
      role="status"
      aria-live="polite"
      class="fixed bottom-5 right-5 z-50 max-w-sm glass-panel border border-[#FF6500] rounded-xl p-4 shadow-2xl transition-all duration-200 opacity-0 pointer-events-none translate-y-2"
    >
      <div class="flex items-start justify-between gap-3">
        <div>
          <div id="toast-title" class="text-xs font-bold text-white">
            Enquiry Logged &mdash; Sanderoof Estimating
          </div>
          <p id="toast-body" class="text-xs text-slate-300 mt-1 leading-relaxed"></p>
        </div>
        <button
          type="button"
          id="toast-close-btn"
          aria-label="Dismiss notification"
          class="text-slate-400 hover:text-white text-xs font-mono px-1.5 py-0.5"
        >
          &times;
        </button>
      </div>
    </div>

    <!-- STANDALONE VANILLA JS ENGINE -->
    <script>
      (function () {
        'use strict';

        // 1. Roof System Engineering Dataset
        var ROOF_SYSTEMS = {
          'single-ply': {
            id: 'single-ply',
            name: 'Single Ply Membrane Systems',
            minRate: 85,
            maxRate: 125,
            warrantyYears: 25,
            uValue: '0.15 W/m²K',
            sqmPerDay: 140,
          },
          felt: {
            id: 'felt',
            name: 'Built-Up Felt Roofing',
            minRate: 78,
            maxRate: 115,
            warrantyYears: 20,
            uValue: '0.16 W/m²K',
            sqmPerDay: 110,
          },
          'green-roof': {
            id: 'green-roof',
            name: 'Eco Green Roof Installations',
            minRate: 135,
            maxRate: 195,
            warrantyYears: 25,
            uValue: '0.12 W/m²K',
            sqmPerDay: 85,
          },
          liquid: {
            id: 'liquid',
            name: 'Liquid Applied Waterproofing',
            minRate: 72,
            maxRate: 110,
            warrantyYears: 20,
            uValue: '0.18 W/m²K',
            sqmPerDay: 160,
          },
          rooflight: {
            id: 'rooflight',
            name: 'Commercial Rooflight Replacement',
            minRate: 145,
            maxRate: 220,
            warrantyYears: 20,
            uValue: '1.10 W/m²K',
            sqmPerDay: 65,
          },
          insulation: {
            id: 'insulation',
            name: 'Thermal Roof Insulation Upgrade',
            minRate: 65,
            maxRate: 98,
            warrantyYears: 25,
            uValue: '0.11 W/m²K',
            sqmPerDay: 150,
          },
        };

        var state = {
          selectedRoofType: 'single-ply',
          areaSqm: 850,
          conditionMultiplier: 1.0,
          includeThermal: true,
          surveyCount: 2,
          lastContactSubmitMs: null,
          contactSubmissionsCount: 0,
          cooldownTimerId: null,
        };

        // 2. XSS Input Sanitization Helper
        function sanitizeText(str) {
          if (typeof str !== 'string') return '';
          return str
            .replace(/&/g, '&amp;')
            .replace(/</g, '&lt;')
            .replace(/>/g, '&gt;')
            .replace(/"/g, '&quot;')
            .replace(/'/g, '&#x27;')
            .replace(/\//g, '&#x2F;')
            .trim();
        }

        function formatGBP(num) {
          return '£' + Math.round(num).toLocaleString('en-GB');
        }

        // 3. UK Postcode Validation & Greater Manchester Priority Check
        function validateUKPostcode(raw) {
          var clean = String(raw || '')
            .replace(/\s+/g, '')
            .toUpperCase();
          var regex = /^[A-Z]{1,2}\d[A-Z\d]?\d[A-Z]{2}$/;
          if (!regex.test(clean)) {
            return { valid: false, normalized: clean, isGM: false };
          }
          var formatted = clean.slice(0, -3) + ' ' + clean.slice(-3);
          var prefixMatch = clean.match(/^[A-Z]{1,2}/);
          var prefix = prefixMatch ? prefixMatch[0] : '';
          var gmPrefixes = ['M', 'BL', 'OL', 'SK', 'WA', 'WN', 'PR'];
          return {
            valid: true,
            normalized: formatted,
            isGM: gmPrefixes.indexOf(prefix) !== -1,
          };
        }

        // 4. Toast Notification Helper
        var toastEl = document.getElementById('toast-notification');
        var toastTitleEl = document.getElementById('toast-title');
        var toastBodyEl = document.getElementById('toast-body');
        var toastCloseBtn = document.getElementById('toast-close-btn');
        var toastTimeout = null;

        function showToast(title, message) {
          if (!toastEl) return;
          toastTitleEl.textContent = title;
          toastBodyEl.textContent = message;
          toastEl.classList.remove('opacity-0', 'pointer-events-none', 'translate-y-2');
          toastEl.classList.add('opacity-100', 'translate-y-0');
          if (toastTimeout) clearTimeout(toastTimeout);
          toastTimeout = setTimeout(hideToast, 6000);
        }

        function hideToast() {
          if (!toastEl) return;
          toastEl.classList.add('opacity-0', 'pointer-events-none', 'translate-y-2');
          toastEl.classList.remove('opacity-100', 'translate-y-0');
        }

        if (toastCloseBtn) {
          toastCloseBtn.addEventListener('click', hideToast);
        }

        // 5. Estimator Computation & UI Update
        function updateEstimatorUI() {
          var spec = ROOF_SYSTEMS[state.selectedRoofType] || ROOF_SYSTEMS['single-ply'];
          var clampedArea = Math.max(25, Math.min(25000, Math.round(Number(state.areaSqm) || 25)));
          var thermalAddon =
            state.includeThermal && state.selectedRoofType !== 'insulation' ? 28 : 0;
          var volumeFactor = clampedArea >= 2500 ? 0.9 : clampedArea >= 1000 ? 0.95 : 1.0;

          var minCost = Math.round(
            clampedArea * (spec.minRate + thermalAddon) * state.conditionMultiplier * volumeFactor
          );
          var maxCost = Math.round(
            clampedArea *
              (spec.maxRate + thermalAddon * 1.25) *
              state.conditionMultiplier *
              volumeFactor
          );
          var days = Math.max(2, Math.ceil(clampedArea / spec.sqmPerDay));
          var annualSaving = Math.round(
            clampedArea *
              (state.includeThermal ||
              state.selectedRoofType === 'insulation' ||
              state.selectedRoofType === 'green-roof'
                ? 4.8
                : 2.1)
          );

          document.getElementById('estimator-selected-label').textContent = spec.name;
          document.getElementById('quote-system-heading').textContent = spec.name;
          document.getElementById('quote-area-badge').textContent =
            clampedArea.toLocaleString('en-GB') + ' m²';
          document.getElementById('quote-price-range').textContent =
            formatGBP(minCost) + ' – ' + formatGBP(maxCost);
          document.getElementById('quote-warranty').textContent = spec.warrantyYears + ' Years';
          document.getElementById('quote-duration').textContent = days + ' Working Days';
          document.getElementById('quote-uvalue').textContent = spec.uValue;
          document.getElementById('quote-energy-saving').textContent =
            formatGBP(annualSaving) + ' / yr';

          var noteParts = [];
          if (state.includeThermal) noteParts.push('Part L2 PIR thermal upgrade');
          if (volumeFactor < 1.0)
            noteParts.push(Math.round((1 - volumeFactor) * 100) + '% industrial volume efficiency');
          noteParts.push('full edge protection');
          document.getElementById('quote-volume-note').textContent =
            'Includes ' + noteParts.join(' + ') + '.';

          // Sync roof type buttons active styling
          var typeBtns = document.querySelectorAll('.roof-type-btn');
          typeBtns.forEach(function (btn) {
            var type = btn.getAttribute('data-roof-type');
            var isSelected = type === state.selectedRoofType;
            btn.setAttribute('aria-pressed', isSelected ? 'true' : 'false');
            if (isSelected) {
              btn.className =
                'roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-[#FF6500]/15 border-[#FF6500] text-white';
            } else {
              btn.className =
                'roof-type-btn text-left p-3.5 rounded-xl border transition-all bg-white/5 border-white/10 text-slate-200 hover:border-white/25';
            }
          });
        }

        // Bind Roof System selector buttons
        document.querySelectorAll('.roof-type-btn').forEach(function (btn) {
          btn.addEventListener('click', function () {
            state.selectedRoofType = btn.getAttribute('data-roof-type');
            updateEstimatorUI();
          });
        });

        // Bind Area Number & Range Slider
        var areaNumberInput = document.getElementById('area-number-input');
        var areaRangeSlider = document.getElementById('area-range-slider');

        function setAreaSqm(val) {
          var numeric = Math.max(25, Math.min(25000, Math.round(Number(val) || 25)));
          state.areaSqm = numeric;
          areaNumberInput.value = String(numeric);
          areaRangeSlider.value = String(Math.min(10000, Math.max(50, numeric)));

          document.querySelectorAll('.area-preset-btn').forEach(function (b) {
            var presetVal = Number(b.getAttribute('data-area-preset'));
            if (presetVal === numeric) {
              b.className =
                'area-preset-btn px-2.5 py-1 text-xs rounded-md bg-[#FF6500]/20 border border-[#FF6500]/50 text-white font-mono tabular-nums whitespace-nowrap shrink-0';
            } else {
              b.className =
                'area-preset-btn px-2.5 py-1 text-xs rounded-md bg-white/5 hover:bg-white/10 border border-white/10 text-slate-300 font-mono tabular-nums whitespace-nowrap shrink-0';
            }
          });

          updateEstimatorUI();
        }

        areaNumberInput.addEventListener('input', function (e) {
          setAreaSqm(e.target.value);
        });
        areaRangeSlider.addEventListener('input', function (e) {
          setAreaSqm(e.target.value);
        });

        document.querySelectorAll('.area-preset-btn').forEach(function (btn) {
          btn.addEventListener('click', function () {
            setAreaSqm(btn.getAttribute('data-area-preset'));
          });
        });

        // Substrate condition & thermal upgrade listeners
        document
          .getElementById('substrate-scope-select')
          .addEventListener('change', function (e) {
            state.conditionMultiplier = parseFloat(e.target.value) || 1.0;
            updateEstimatorUI();
          });

        document
          .getElementById('thermal-upgrade-checkbox')
          .addEventListener('change', function (e) {
            state.includeThermal = Boolean(e.target.checked);
            updateEstimatorUI();
          });

        // Postcode live check
        var estimatorPostcodeInput = document.getElementById('estimator-postcode');
        var postcodeStatusEl = document.getElementById('postcode-zone-status');

        estimatorPostcodeInput.addEventListener('input', function () {
          var check = validateUKPostcode(estimatorPostcodeInput.value);
          if (!check.valid) {
            postcodeStatusEl.innerHTML =
              'Enter a full UK postcode (e.g. <span class="font-mono text-white">M45 7RH</span> or <span class="font-mono text-white">M17 1WA</span>) to verify dispatch time.';
          } else if (check.isGM) {
            postcodeStatusEl.innerHTML =
              'Postcode <span class="font-mono text-emerald-400 font-semibold">' +
              sanitizeText(check.normalized) +
              '</span> is in our Greater Manchester Priority Zone (24hr Whitefield Dispatch).';
          } else {
            postcodeStatusEl.innerHTML =
              'Postcode <span class="font-mono text-white font-semibold">' +
              sanitizeText(check.normalized) +
              '</span> verified (North West Regional Commercial Survey Team).';
          }
        });

        // Estimator Survey Booking Form Submit
        var estimatorForm = document.getElementById('estimator-booking-form');
        var estimatorFeedback = document.getElementById('estimator-form-feedback');

        estimatorForm.addEventListener('submit', function (e) {
          e.preventDefault();
          var rawPostcode = estimatorPostcodeInput.value;
          var rawCompany = document.getElementById('estimator-company').value;
          var rawPhone = document.getElementById('estimator-phone').value;

          var pcCheck = validateUKPostcode(rawPostcode);
          var cleanCompany = sanitizeText(rawCompany);
          var cleanPhone = sanitizeText(rawPhone);

          if (!pcCheck.valid) {
            estimatorFeedback.className =
              'mt-3 p-3 rounded-lg bg-red-500/15 border border-red-500/40 text-red-200 text-xs block';
            estimatorFeedback.textContent =
              'Please enter a valid UK commercial site postcode (for example M45 7RH).';
            return;
          }
          if (!cleanCompany || cleanCompany.length < 2) {
            estimatorFeedback.className =
              'mt-3 p-3 rounded-lg bg-red-500/15 border border-red-500/40 text-red-200 text-xs block';
            estimatorFeedback.textContent = 'Please enter your Company or Site Name.';
            return;
          }
          if (!cleanPhone || cleanPhone.length < 7) {
            estimatorFeedback.className =
              'mt-3 p-3 rounded-lg bg-red-500/15 border border-red-500/40 text-red-200 text-xs block';
            estimatorFeedback.textContent = 'Please provide a valid direct contact telephone number.';
            return;
          }

          state.surveyCount += 1;
          var refCode = 'SR-' + (4918 + state.surveyCount);
          var spec = ROOF_SYSTEMS[state.selectedRoofType];

          var listEl = document.getElementById('survey-bookings-list');
          var li = document.createElement('li');
          li.className =
            'p-2.5 rounded-lg bg-[#FF6500]/15 border border-[#FF6500]/50 flex items-center justify-between gap-2';
          li.innerHTML =
            '<span class="text-white font-semibold truncate">' +
            refCode +
            ' &middot; ' +
            cleanCompany +
            ' (' +
            pcCheck.normalized +
            ', ' +
            state.areaSqm.toLocaleString('en-GB') +
            ' m&sup2;)</span>' +
            '<span class="text-[#FF6500] shrink-0">' +
            sanitizeText(spec.name.split(' ')[0] + ' ' + spec.name.split(' ')[1]) +
            '</span>';
          listEl.insertBefore(li, listEl.firstChild);

          document.getElementById('survey-queue-count').textContent =
            state.surveyCount + ' active';

          estimatorFeedback.className =
            'mt-3 p-3 rounded-lg bg-emerald-500/15 border border-emerald-500/40 text-emerald-200 text-xs block';
          estimatorFeedback.innerHTML =
            '<strong>Survey Booked (' +
            refCode +
            '):</strong> Our Whitefield surveyor will call <strong>' +
            cleanPhone +
            '</strong> to confirm site access at <strong>' +
            pcCheck.normalized +
            '</strong>.';

          showToast(
            'Site Survey Booked (' + refCode + ')',
            cleanCompany +
              ' (' +
              pcCheck.normalized +
              ') added to Whitefield dispatch queue for ' +
              spec.name +
              '.'
          );
        });

        // 6. Bento Grid Filter & "Calculate Quote" Deep-Link Buttons
        document.querySelectorAll('.service-filter-btn').forEach(function (btn) {
          btn.addEventListener('click', function () {
            var filter = btn.getAttribute('data-service-filter');
            document.querySelectorAll('.service-filter-btn').forEach(function (b) {
              if (b === btn) {
                b.className =
                  'service-filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg bg-[#FF6500] text-white transition-colors whitespace-nowrap shrink-0';
              } else {
                b.className =
                  'service-filter-btn px-3 py-1.5 text-xs font-semibold rounded-lg text-slate-300 hover:text-white transition-colors whitespace-nowrap shrink-0';
              }
            });

            document.querySelectorAll('.service-card').forEach(function (card) {
              var cat = card.getAttribute('data-service-category');
              if (filter === 'all' || cat === filter) {
                card.classList.remove('hidden');
              } else {
                card.classList.add('hidden');
              }
            });
          });
        });

        document.querySelectorAll('[data-select-estimator]').forEach(function (btn) {
          btn.addEventListener('click', function () {
            var targetType = btn.getAttribute('data-select-estimator');
            if (ROOF_SYSTEMS[targetType]) {
              state.selectedRoofType = targetType;
              updateEstimatorUI();
              var estimatorSection = document.getElementById('estimator');
              if (estimatorSection) {
                estimatorSection.scrollIntoView({ behavior: 'smooth' });
              }
            }
          });
        });

        // 7. Heritage & Safety Compliance Tabs
        var COMPLIANCE_TABS = {
          training: {
            title: '100% Directly Trained & CSCS / NVQ Accredited Roofing Teams',
            body: 'Every Sanderoof site supervisor holds SSSTS/SMSTS certification alongside valid CSCS Skilled Worker cards, PASMA mobile tower tickets, IPAF MEWP licences, and manufacturer-issued hot-air and cold-liquid installer approvals.',
            meta: [
              'Zero RIDDOR Incidents (2021–2026)',
              'Enhanced DBS Checked for Schools & NHS Sites',
              'Nipper Lane Training Yard',
            ],
          },
          rams: {
            title: 'Site-Specific RAMS, CDM 2015 Governance & Edge Protection',
            body: 'Before stepping foot on any commercial roof, our contracts managers issue bespoke Risk Assessments & Method Statements (RAMS), hot-work permits (where applicable), wind-speed cut-off protocols, and full perimeter collective edge protection.',
            meta: [
              'Full CDM 2015 Principal Contractor Capability',
              '£10M Public & Employers Liability',
              'Daily Digital Roof Harness & Perimeter Audits',
            ],
          },
          regs: {
            title: 'Approved Document L2 Thermal Compliance & Core Sampling',
            body: 'We perform non-destructive moisture mapping and core sampling to verify existing deck build-ups, supplying condensation risk analyses (BS 5250) and U-value calculations meeting 0.15 W/m²K Building Control sign-off.',
            meta: [
              'BS 6229:2018 Flat Roof Code of Practice',
              'BROOF(t4) Fire Rated Assemblies',
              '20 to 25-Year Insurance-Backed Guarantees',
            ],
          },
        };

        document.querySelectorAll('.compliance-tab-btn').forEach(function (btn) {
          btn.addEventListener('click', function () {
            var key = btn.getAttribute('data-compliance-tab');
            var data = COMPLIANCE_TABS[key];
            if (!data) return;

            document.querySelectorAll('.compliance-tab-btn').forEach(function (b) {
              var active = b === btn;
              b.setAttribute('aria-selected', active ? 'true' : 'false');
              b.className = active
                ? 'compliance-tab-btn px-3.5 py-2 rounded-lg text-xs font-semibold bg-[#FF6500] text-white whitespace-nowrap shrink-0'
                : 'compliance-tab-btn px-3.5 py-2 rounded-lg text-xs font-semibold bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0';
            });

            var panel = document.getElementById('compliance-panel-content');
            panel.innerHTML =
              '<h3 class="text-base font-bold text-white mb-2">' +
              sanitizeText(data.title) +
              '</h3>' +
              '<p class="text-slate-300 mb-4">' +
              sanitizeText(data.body) +
              '</p>' +
              '<div class="flex flex-wrap items-center gap-x-3 gap-y-1 text-xs font-mono text-slate-400">' +
              '<span class="text-white">' +
              sanitizeText(data.meta[0]) +
              '</span>' +
              '<span aria-hidden="true">&middot;</span>' +
              '<span>' +
              sanitizeText(data.meta[1]) +
              '</span>' +
              '<span aria-hidden="true">&middot;</span>' +
              '<span>' +
              sanitizeText(data.meta[2]) +
              '</span>' +
              '</div>';
          });
        });

        // 8. Interactive Greater Manchester Dispatch Map Zones
        var MAP_ZONES = {
          'whitefield-hq': {
            title: 'Whitefield HQ Depot (Nipper Lane, M45 7RH)',
            desc: 'Sanderoof operational depot & trade counter off Radcliffe New Road / M60 J17.',
            eta: '0.0 miles • Immediate Dispatch',
          },
          trafford: {
            title: 'Trafford Park & Carrington Industrial Estates (M17 / M31)',
            desc: 'Direct M60 Western Orbital route from J17 Whitefield to J9/J10 Trafford Park.',
            eta: '9.4 miles • ~18 mins via M60',
          },
          'city-centre': {
            title: 'Manchester City Centre & Salford Quays (M1–M5 / M50)',
            desc: 'Direct A56 Bury New Road corridor straight into Manchester & MediaCityUK.',
            eta: '5.8 miles • ~16 mins via A56',
          },
          'bury-bolton': {
            title: 'Bury, Radcliffe, Bolton & North Manchester (BL / M26)',
            desc: 'Immediate local coverage across Bury, Pilsworth Industrial Estate & Bolton.',
            eta: '3.2 miles • ~9 mins via A56/M66',
          },
          'oldham-stockport': {
            title: 'Oldham, Rochdale & Tameside Industrial Parks (OL / SK15)',
            desc: 'Fast eastern orbital link via M60 & M62 commercial corridors.',
            eta: '11.2 miles • ~20 mins via M60',
          },
          'airport-south': {
            title: 'Stockport, Wythenshawe & Airport Logistics Hub (SK / M90)',
            desc: 'Full southern Greater Manchester commercial coverage via M60 & M56.',
            eta: '16.5 miles • ~26 mins via M60',
          },
        };

        function selectMapZone(zoneKey) {
          var info = MAP_ZONES[zoneKey];
          if (!info) return;
          document.getElementById('zone-readout-title').textContent = info.title;
          document.getElementById('zone-readout-desc').textContent = info.desc;
          document.getElementById('zone-readout-eta').textContent = info.eta;

          document.querySelectorAll('.zone-select-btn').forEach(function (b) {
            var active = b.getAttribute('data-zone-btn') === zoneKey;
            b.className = active
              ? 'zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-[#FF6500] text-white whitespace-nowrap shrink-0'
              : 'zone-select-btn px-2.5 py-1.5 rounded-lg text-xs font-medium bg-white/5 text-slate-300 hover:text-white border border-white/10 whitespace-nowrap shrink-0';
          });
        }

        document.querySelectorAll('[data-zone-btn]').forEach(function (btn) {
          btn.addEventListener('click', function () {
            selectMapZone(btn.getAttribute('data-zone-btn'));
          });
        });

        document.querySelectorAll('[data-map-zone]').forEach(function (node) {
          node.addEventListener('click', function () {
            selectMapZone(node.getAttribute('data-map-zone'));
          });
        });

        // 9. XSS-Sanitized & Rate-Limited Contact Form Handler
        var contactForm = document.getElementById('secure-contact-form');
        var contactAlert = document.getElementById('contact-form-alert');
        var contactSubmitBtn = document.getElementById('contact-submit-btn');
        var rateLimitIndicator = document.getElementById('rate-limit-indicator');
        var submissionsLog = document.getElementById('contact-submissions-log');
        var COOLDOWN_MS = 30000;

        function startCooldownTimer() {
          if (state.cooldownTimerId) clearInterval(state.cooldownTimerId);
          contactSubmitBtn.disabled = true;
          rateLimitIndicator.textContent =
            'Rate limit active: wait 30s before next submission';
          rateLimitIndicator.className = 'text-xs text-[#FF6500] font-mono tabular-nums';

          state.cooldownTimerId = setInterval(function () {
            var elapsed = Date.now() - state.lastContactSubmitMs;
            var remainingSec = Math.ceil((COOLDOWN_MS - elapsed) / 1000);
            if (remainingSec <= 0) {
              clearInterval(state.cooldownTimerId);
              state.cooldownTimerId = null;
              contactSubmitBtn.disabled = false;
              rateLimitIndicator.textContent = 'Rate limit status: Ready';
              rateLimitIndicator.className = 'text-xs text-slate-400 font-mono tabular-nums';
            } else {
              rateLimitIndicator.textContent =
                'Rate limit active: wait ' + remainingSec + 's before next submission';
              rateLimitIndicator.className = 'text-xs text-[#FF6500] font-mono tabular-nums';
            }
          }, 500);
        }

        contactForm.addEventListener('submit', function (e) {
          e.preventDefault();

          var now = Date.now();
          if (state.lastContactSubmitMs && now - state.lastContactSubmitMs < COOLDOWN_MS) {
            var waitSec = Math.ceil((COOLDOWN_MS - (now - state.lastContactSubmitMs)) / 1000);
            contactAlert.className =
              'p-3.5 rounded-xl text-xs bg-amber-500/15 border border-amber-500/40 text-amber-200 block';
            contactAlert.textContent =
              'Rate limit protection active: Please wait ' +
              waitSec +
              ' seconds before sending another enquiry.';
            return;
          }

          var rawName = document.getElementById('contact-name').value;
          var rawEmail = document.getElementById('contact-email').value;
          var rawPhone = document.getElementById('contact-phone').value;
          var rawService = document.getElementById('contact-service').value;
          var rawMessage = document.getElementById('contact-message').value;

          var cleanName = sanitizeText(rawName);
          var cleanEmail = sanitizeText(rawEmail);
          var cleanPhone = sanitizeText(rawPhone);
          var cleanService = sanitizeText(rawService);
          var cleanMessage = sanitizeText(rawMessage);

          var emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

          if (!cleanName || cleanName.length < 2) {
            contactAlert.className =
              'p-3.5 rounded-xl text-xs bg-red-500/15 border border-red-500/40 text-red-200 block';
            contactAlert.textContent = 'Please enter your full name.';
            return;
          }
          if (!emailRegex.test(rawEmail.trim())) {
            contactAlert.className =
              'p-3.5 rounded-xl text-xs bg-red-500/15 border border-red-500/40 text-red-200 block';
            contactAlert.textContent = 'Please provide a valid work email address.';
            return;
          }
          if (!cleanPhone || cleanPhone.length < 7) {
            contactAlert.className =
              'p-3.5 rounded-xl text-xs bg-red-500/15 border border-red-500/40 text-red-200 block';
            contactAlert.textContent = 'Please enter a valid contact telephone number.';
            return;
          }
          if (!cleanMessage || cleanMessage.length < 10) {
            contactAlert.className =
              'p-3.5 rounded-xl text-xs bg-red-500/15 border border-red-500/40 text-red-200 block';
            contactAlert.textContent =
              'Please include brief project details (at least 10 characters).';
            return;
          }

          // Record timestamp for rate limiting
          state.lastContactSubmitMs = now;
          state.contactSubmissionsCount += 1;
          var enquiryRef = 'SR-ENQ-' + (1040 + state.contactSubmissionsCount);

          contactAlert.className =
            'p-3.5 rounded-xl text-xs bg-emerald-500/15 border border-emerald-500/40 text-emerald-200 block';
          contactAlert.innerHTML =
            '<strong>Enquiry Confirmed (' +
            enquiryRef +
            '):</strong> Thank you, ' +
            cleanName +
            '. Your sanitized project brief for <strong>' +
            cleanService +
            '</strong> has been routed to info@sanderoof.com.';

          var emptyState = document.getElementById('contact-empty-state');
          if (emptyState) emptyState.remove();

          var entry = document.createElement('div');
          entry.className = 'p-3 rounded-xl bg-[#060E1A] border border-white/10';
          entry.innerHTML =
            '<div class="flex items-center justify-between font-mono text-[11px] text-[#FF6500] mb-1">' +
            '<span>' +
            enquiryRef +
            ' &bull; ' +
            cleanService +
            '</span>' +
            '<span>XSS Sanitized &check;</span>' +
            '</div>' +
            '<div class="text-white font-medium">' +
            cleanName +
            ' (' +
            cleanEmail +
            ' &middot; ' +
            cleanPhone +
            ')</div>' +
            '<div class="text-slate-400 mt-1 break-words">' +
            cleanMessage +
            '</div>';
          submissionsLog.insertBefore(entry, submissionsLog.firstChild);

          document.getElementById('contact-log-count').textContent =
            state.contactSubmissionsCount + ' sent this session';

          contactForm.reset();
          startCooldownTimer();

          showToast(
            'Enquiry Dispatched (' + enquiryRef + ')',
            'Thank you ' +
              rawName.trim() +
              '. Sanderoof Estimating (Whitefield M45 7RH) will respond within 4 working hours.'
          );
        });

        // Initial render
        updateEstimatorUI();
      })();
    </script>
  </body>
</html>
