<!-- ... existing code ... -->
    <style>
        /* Reset chống lỗi hiển thị khi nhúng trên GitHub Pages hoặc khung hẹp */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
            max-width: 100vw !important;
            overflow-x: hidden !important;
            font-family: 'Inter', sans-serif;
            color: #333333;
            background-color: #fcfaf7;
        }
        /* Tự động bung toàn màn hình nếu chạy trong khung Markdown của GitHub Pages */
        .markdown-body, .container-lg, .px-3.my-5 {
            max-width: 100% !important;
            width: 100% !important;
            margin: 0 !important;
            padding: 0 !important;
        }
        .markdown-body > h1:first-child {
            display: none !important;
        }
        h1, h2, h3, h4, .font-flatsome {
            font-family: 'Montserrat', sans-serif;
        }
        
        /* Flatsome Section Title Divider */
        .section-title-container {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.75rem;
        }
        .section-title-container::before,
        .section-title-container::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e5dcd3;
            max-width: 140px;
        }
        .section-title-main {
            padding: 0 0.75rem;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.03em;
            color: #4a2511;
            position: relative;
        }

        /* Flatsome Product Box Hover Effects */
        .flatsome-product-box {
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .flatsome-product-box:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px -5px rgba(74, 37, 17, 0.14);
        }
        .flatsome-product-box .quick-view-bar {
            transform: translateY(100%);
            transition: transform 0.28s ease-in-out;
        }
        .flatsome-product-box:hover .quick-view-bar {
            transform: translateY(0);
        }
        .flatsome-product-box .product-img {
            transition: transform 0.5s ease;
        }
        .flatsome-product-box:hover .product-img {
            transform: scale(1.06);
        }

        /* Flatsome Date Badge on Blog/Project Cards */
        .flatsome-date-badge {
            width: 48px;
            height: 52px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.95);
            border: 2px solid #b8652c;
            color: #4a2511;
            font-family: 'Montserrat', sans-serif;
            line-height: 1.1;
            transition: all 0.25s ease;
        }
        .group:hover .flatsome-date-badge {
            background: #b8652c;
            color: #ffffff;
        }

        /* Floating Contact Ring Animation */
        @keyframes phoneRing {
            0% { transform: rotate(0) scale(1) skew(1deg); }
            10% { transform: rotate(-25deg) scale(1) skew(1deg); }
            20% { transform: rotate(25deg) scale(1) skew(1deg); }
            30% { transform: rotate(-25deg) scale(1) skew(1deg); }
            40% { transform: rotate(25deg) scale(1) skew(1deg); }
            50% { transform: rotate(0) scale(1) skew(1deg); }
            100% { transform: rotate(0) scale(1) skew(1deg); }
        }
        .animate-phone-ring {
            animation: phoneRing 1.8s infinite ease-in-out;
        }

        @keyframes pulseRing {
            0% { transform: scale(0.95); opacity: 0.8; }
            70% { transform: scale(1.35); opacity: 0; }
            100% { transform: scale(0.95); opacity: 0; }
        }
        .pulse-ring::before {
            content: '';
            position: absolute;
            inset: -6px;
            border-radius: 9999px;
            background: inherit;
            z-index: -1;
            animation: pulseRing 2s infinite;
        }

        /* Wood grain subtle pattern */
        .wood-pattern {
            background-color: #4a2511;
            background-image: radial-gradient(rgba(214, 133, 69, 0.14) 1px, transparent 1px),
                              linear-gradient(135deg, #3b1c0c 0%, #592d16 50%, #3a1b0b 100%);
            background-size: 24px 24px, 100% 100%;
        }

        /* Mega menu hover */
        .has-dropdown:hover .dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(10px);
            transition: all 0.22s ease;
        }
    </style>
</head>
<body class="antialiased selection:bg-sauna-600 selection:text-white pb-16 md:pb-0">

    <!-- ==================== FLATSOME TOP BAR (ĐÃ BỎ NÚT ĐỔI LOGO & CĂN ĐỀU) ==================== -->
    <div class="bg-sauna-950 text-sauna-100 text-[11px] sm:text-xs border-b border-sauna-800/60 w-full">
        <div class="max-w-7xl mx-auto px-3 sm:px-4 py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 min-w-0">
                <span class="inline-flex items-center gap-1.5 font-semibold text-amber-400 truncate">
                    <i class="fa-solid fa-crown text-[10px] shrink-0"></i>
                    <span class="truncate">CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU</span>
                </span>
                <span class="hidden xl:inline text-sauna-400">|</span>
                <span class="hidden xl:inline text-gray-300 truncate">Tư vấn, sản xuất & lắp đặt phòng xông hơi Đà Nẵng & Miền Trung</span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 text-[11px] shrink-0">
                <span class="hidden md:inline-flex items-center gap-1.5 text-gray-300">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    67 Phi Bình 7, P. Ngũ Hành Sơn, TP. Đà Nẵng
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-gray-300">
                    <i class="fa-regular fa-clock text-amber-400"></i>
                    07:30 - 18:30
                </span>
                <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 text-blue-400 hover:text-blue-300 font-medium transition">
                    <i class="fa-brands fa-facebook"></i> Fanpage Hiếu Nghĩa Sauna
                </a>
            </div>
        </div>
    </div>

    <!-- ==================== FLATSOME MAIN HEADER & STICKY NAV (CĂN ĐỀU TRÊN MỌI MÀN HÌNH) ==================== -->
    <header id="mainHeader" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-md border-b border-sauna-100 w-full transition-all duration-300">
        <div class="max-w-7xl mx-auto px-3 sm:px-4 py-2.5 sm:py-3 flex items-center justify-between gap-2 sm:gap-3">
            
            <!-- Brand Logo (Hoàng Gia Hiếu - Hiếu Nghĩa Sauna & Steam) -->
            <a href="#trang-chu" class="flex items-center gap-2 sm:gap-3 group min-w-0 flex-1 lg:flex-initial">
                <div id="logoContainer" class="w-11 h-11 sm:w-14 sm:h-14 rounded-xl bg-gradient-to-br from-sauna-900 via-sauna-800 to-sauna-950 p-1 shadow-md border-2 border-amber-500/80 flex items-center justify-center relative overflow-hidden shrink-0 group-hover:scale-105 transition">
                    <svg id="defaultSvgLogo" viewBox="0 0 120 120" class="w-full h-full">
                        <defs>
                            <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#fde047" />
                                <stop offset="50%" stop-color="#eab308" />
                                <stop offset="100%" stop-color="#ca8a04" />
                            </linearGradient>
                        </defs>
                        <polygon points="60,6 108,32 108,88 60,114 12,88 12,32" fill="none" stroke="url(#goldGrad)" stroke-width="4"/>
                        <polygon points="60,12 102,35 102,85 60,108 18,85 18,35" fill="#3b1c0c" stroke="#b8652c" stroke-width="1.5"/>
                        <path d="M44,32 L51,22 L60,30 L69,22 L76,32 Z" fill="url(#goldGrad)"/>
                        <path d="M28,52 L60,33 L92,52" fill="none" stroke="url(#goldGrad)" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M46,74 C43,67 49,62 46,55" fill="none" stroke="#38bdf8" stroke-width="3" stroke-linecap="round"/>
                        <path d="M60,76 C57,68 63,62 60,53" fill="none" stroke="url(#goldGrad)" stroke-width="3.5" stroke-linecap="round"/>
                        <path d="M74,74 C71,67 77,62 74,55" fill="none" stroke="#f97316" stroke-width="3" stroke-linecap="round"/>
                        <text x="60" y="94" text-anchor="middle" fill="url(#goldGrad)" font-family="Montserrat, sans-serif" font-weight="900" font-size="13" letter-spacing="1">HIẾU NGHĨA</text>
                        <text x="60" y="104" text-anchor="middle" fill="#fed7aa" font-family="Inter, sans-serif" font-weight="700" font-size="7.5">SAUNA & STEAM</text>
                    </svg>
                </div>
                <div class="min-w-0">
                    <div class="flex items-center gap-1.5">
                        <span class="font-heading font-black text-sm sm:text-base md:text-lg text-sauna-900 tracking-tight leading-none truncate">HOÀNG GIA HIẾU</span>
                        <span class="hidden sm:inline-block bg-amber-100 text-sauna-800 text-[9px] font-bold px-2 py-0.5 rounded-full border border-amber-300 shrink-0">HIẾU NGHĨA SAUNA</span>
                    </div>
                    <p class="text-[10px] sm:text-xs font-semibold text-sauna-600 mt-0.5 truncate">xonghoimientrung.com • Phòng Xông Hơi</p>
                    <p class="text-[10px] text-gray-500 hidden 2xl:block truncate">Đà Nẵng • Huế • Hội An • Quảng Nam • Quảng Ngãi</p>
                </div>
            </a>

            <!-- Desktop Navigation Menu (Flatsome Mega Menu Style - Căn gọn đều) -->
            <nav class="hidden lg:flex items-center gap-0.5 xl:gap-1 font-heading text-[11px] xl:text-xs font-bold uppercase tracking-wide text-sauna-900 shrink-0">
                <a href="#trang-chu" class="px-2.5 py-2 rounded-lg text-sauna-600 bg-sauna-50 hover:bg-sauna-100 transition whitespace-nowrap">Trang Chủ</a>
                <a href="#gioi-thieu" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition whitespace-nowrap">Giới Thiệu</a>
                
                <!-- Dropdown Sản Phẩm -->
                <div class="relative has-dropdown">
                    <a href="#san-pham" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition inline-flex items-center gap-1 whitespace-nowrap">
                        Sản Phẩm <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                    </a>
                    <!-- Mega Menu Dropdown -->
                    <div class="dropdown-menu absolute left-1/2 -translate-x-1/2 top-full pt-2 w-[640px] z-50">
                        <div class="bg-white rounded-2xl shadow-2xl border border-sauna-200 p-5 grid grid-cols-3 gap-5 text-left normal-case font-sans">
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-700 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-house-chimney-window text-amber-600"></i> Phòng Xông Hơi
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Khô (Sauna)</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Đá Muối Himalaya</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Hồng Ngoại</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Ướt Kính Cường Lực</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Khô Kết Hợp Ướt</button></li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-700 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-fire-burner text-amber-600"></i> Máy Xông Hơi Khô & Ướt
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="filterProducts('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi HARVIA (Phần Lan)</button></li>
                                    <li><button onclick="filterProducts('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi SAWO Chính Hãng</button></li>
                                    <li><button onclick="filterProducts('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi COAST Cao Cấp</button></li>
                                    <li><button onclick="filterProducts('may-xong-uot')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi AMAZON Khô & Ướt</button></li>
                                    <li><button onclick="filterProducts('may-xong-uot')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi OCEANIC / MONACO</button></li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-700 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-tree text-amber-600"></i> Gỗ & Phụ Kiện Xông Hơi
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Gỗ Thông Phần Lan Nhập Khẩu</button></li>
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Gỗ Tuyết Tùng & Hinoki Nhật</button></li>
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Đá Muối Himalaya & Phụ Kiện</button></li>
                                    <li><button onclick="filterProducts('bon-suc')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Bồn Sục Jacuzzi & Bồn Ngâm Gỗ</button></li>
                                    <li><button onclick="filterProducts('all')" class="text-sauna-600 font-bold hover:underline flex items-center gap-1.5 pt-1">Xem tất cả sản phẩm <i class="fa-solid fa-arrow-right"></i></button></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <a href="#cong-trinh" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition whitespace-nowrap">Công Trình</a>
                <a href="#du-toan" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition inline-flex items-center gap-1 whitespace-nowrap">
                    <i class="fa-solid fa-calculator text-amber-600"></i> Báo Giá
                </a>
                <a href="#quy-trinh" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition whitespace-nowrap">Quy Trình</a>
                <a href="#tin-tuc" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition whitespace-nowrap">Tin Tức</a>
                <a href="#lien-he" class="px-2.5 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition whitespace-nowrap">Liên Hệ</a>
            </nav>

            <!-- Right Actions: Search, Quote Basket, Hotline & Mobile Menu (Không bao giờ tràn khung) -->
            <div class="flex items-center gap-1.5 sm:gap-2 shrink-0">
                <!-- Search Button -->
                <button onclick="toggleSearchModal()" class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-sauna-50 hover:bg-sauna-100 text-sauna-800 flex items-center justify-center transition" title="Tìm kiếm sản phẩm">
                    <i class="fa-solid fa-magnifying-glass text-sm"></i>
                </button>

                <!-- Cart / Quote Basket -->
                <button onclick="toggleQuoteDrawer()" class="relative w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-sauna-50 hover:bg-sauna-100 text-sauna-800 flex items-center justify-center transition" title="Danh sách yêu cầu báo giá">
                    <i class="fa-solid fa-cart-flatbed text-sm"></i>
                    <span id="cartCountBadge" class="absolute -top-1 -right-1 w-4 h-4 sm:w-5 sm:h-5 rounded-full bg-red-600 text-white text-[10px] font-bold flex items-center justify-center">0</span>
                </button>

                <!-- Hotline Button -->
                <a href="tel:0978745785" class="hidden sm:inline-flex items-center gap-2 bg-gradient-to-r from-sauna-700 to-sauna-600 hover:from-sauna-800 hover:to-sauna-700 text-white px-3.5 py-2 rounded-full shadow-md hover:shadow-lg transition">
                    <span class="w-6 h-6 rounded-full bg-amber-400 text-sauna-950 flex items-center justify-center animate-phone-ring shrink-0">
                        <i class="fa-solid fa-phone-volume text-[11px]"></i>
                    </span>
                    <div class="text-left leading-tight">
                        <span class="block text-[9px] uppercase tracking-wider text-amber-200 font-semibold">Hotline 24/7</span>
                        <span class="font-heading font-extrabold text-xs xl:text-sm">0978.745.785</span>
                    </div>
                </a>

                <!-- Mobile Menu Button -->
                <button onclick="toggleMobileMenu()" class="lg:hidden w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-sauna-900 text-white flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu Drawer -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-sauna-100 px-4 pt-3 pb-5 shadow-xl">
            <div class="mb-3">
                <div class="relative">
                    <input type="text" id="mobileSearchInput" oninput="searchProductsByKeyword(this.value)" placeholder="Tìm phòng xông hơi, máy Harvia, Coast..." class="w-full pl-9 pr-4 py-2.5 text-sm rounded-xl border border-sauna-200 focus:outline-none focus:border-sauna-600">
                    <i class="fa-solid fa-magnifying-glass absolute left-3 top-3 text-gray-400"></i>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-2 font-heading font-bold text-xs uppercase text-sauna-900">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-sauna-50 text-sauna-700"><i class="fa-solid fa-house mr-1.5"></i> Trang Chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-building mr-1.5"></i> Giới Thiệu</a>
                <a href="#san-pham" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-cubes mr-1.5"></i> Sản Phẩm</a>
                <a href="#cong-trinh" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-helmet-safety mr-1.5"></i> Công Trình</a>
                <a href="#du-toan" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-calculator mr-1.5"></i> Tính Chi Phí</a>
                <a href="#quy-trinh" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-list-check mr-1.5"></i> Quy Trình</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-newspaper mr-1.5"></i> Tin Tức</a>
                <a href="#lien-he" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50"><i class="fa-solid fa-headset mr-1.5"></i> Liên Hệ</a>
            </div>
            <div class="mt-4 pt-3 border-t border-gray-100 flex items-center justify-between text-xs text-gray-600">
                <span><i class="fa-solid fa-location-dot text-sauna-600 mr-1"></i> 67 Phi Bình 7, Ngũ Hành Sơn, Đà Nẵng</span>
                <a href="tel:0978745785" class="font-bold text-sauna-700">0978.745.785</a>
            </div>
        </div>
    </header>

    <!-- ==================== FLATSOME HERO SLIDER (KHÔNG BỊ SÁT MÉP HAY CẮT NÚT TRÊN ĐIỆN THOẠI) ==================== -->
    <section id="trang-chu" class="relative bg-sauna-950 overflow-hidden w-full">
        <div id="heroSlidesContainer" class="relative w-full">
            
            <!-- Slide 1 -->
            <div class="hero-slide relative transition-opacity duration-700 opacity-100 z-10 flex items-center min-h-[460px] sm:min-h-[540px] lg:min-h-[600px]">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x800/3b1c0c/facc15?text=XONG+HOI+MIEN+TRUNG+-+HOANG+GIA+HIEU'"
                     alt="Thi công phòng xông hơi Đà Nẵng Hoàng Gia Hiếu" 
                     class="absolute inset-0 w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-sauna-950/95 via-sauna-950/85 to-sauna-950/50"></div>
                
                <div class="relative max-w-7xl mx-auto px-4 py-10 sm:py-14 lg:py-16 w-full grid lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-7 text-white space-y-4 sm:space-y-5">
                        <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 px-3 py-1.5 rounded-full text-[11px] sm:text-xs font-bold uppercase tracking-wider">
                            <i class="fa-solid fa-award text-amber-400"></i> Thương Hiệu Uy Tín Hàng Đầu Đà Nẵng & Miền Trung
                        </div>
                        <h1 class="font-heading font-black text-2xl sm:text-4xl lg:text-5xl leading-tight">
                            CÔNG TY TNHH TM DV <span class="text-amber-400">HOÀNG GIA HIẾU</span>
                            <span class="block text-lg sm:text-2xl lg:text-3xl font-bold text-sauna-200 mt-2">
                                Chuyên Sản Xuất & Lắp Đặt Phòng Xông Hơi Trọn Gói
                            </span>
                        </h1>
                        <p class="text-gray-200 text-xs sm:text-base leading-relaxed max-w-2xl">
                            Đơn vị trực tiếp thiết kế, sản xuất tại xưởng và thi công lắp đặt <strong>Phòng Xông Hơi Khô (Sauna), Phòng Xông Hơi Ướt (Steam), Phòng Xông Đá Muối Himalaya</strong> cho Gia đình, Spa, Biệt thự, Khách sạn & Resort tại Đà Nẵng và các tỉnh miền Trung.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 pt-1 text-xs">
                            <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm px-3 py-2 rounded-xl border border-white/15">
                                <i class="fa-solid fa-circle-check text-amber-400 shrink-0"></i>
                                <span>Giá gốc tại xưởng</span>
                            </div>
                            <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm px-3 py-2 rounded-xl border border-white/15">
                                <i class="fa-solid fa-circle-check text-amber-400 shrink-0"></i>
                                <span>Gỗ Phần Lan, Tuyết Tùng</span>
                            </div>
                            <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm px-3 py-2 rounded-xl border border-white/15 col-span-2 sm:col-span-1">
                                <i class="fa-solid fa-circle-check text-amber-400 shrink-0"></i>
                                <span>Bảo hành tận nơi 24/7</span>
                            </div>
                        </div>
                        <div class="flex flex-wrap items-center gap-3 pt-2 pb-4 sm:pb-0">
                            <a href="tel:0978745785" class="w-full sm:w-auto justify-center inline-flex items-center gap-2.5 bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-extrabold text-xs sm:text-sm px-6 py-3.5 rounded-xl shadow-lg transition">
                                <i class="fa-solid fa-phone-volume"></i> GỌI NGAY: 0978.745.785
                            </a>
                            <a href="#du-toan" class="w-full sm:w-auto justify-center inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 font-heading font-bold text-xs sm:text-sm px-6 py-3.5 rounded-xl backdrop-blur-sm transition">
                                <i class="fa-solid fa-calculator text-amber-400"></i> Tính Chi Phí Phòng Xông
                            </a>
                        </div>
                    </div>

                    <!-- Right Hero Card: Quick Fanpage Info Card -->
                    <div class="lg:col-span-5 hidden lg:block">
                        <div class="bg-white/95 backdrop-blur-md rounded-2xl p-6 shadow-2xl border-2 border-amber-400/60 text-gray-800">
                            <div class="flex items-center gap-3 pb-4 border-b border-gray-200">
                                <div class="w-12 h-12 rounded-xl bg-sauna-900 text-amber-400 flex items-center justify-center font-heading font-black text-lg shrink-0">
                                    HN
                                </div>
                                <div>
                                    <span class="text-[11px] font-bold uppercase text-sauna-600 tracking-wider">Thông Tin Chính Thức</span>
                                    <h3 class="font-heading font-extrabold text-base text-sauna-950">HIẾU NGHĨA SAUNA & STEAM</h3>
                                    <p class="text-xs text-gray-500">Website: <strong>xonghoimientrung.com</strong></p>
                                </div>
                            </div>
                            <ul class="space-y-3 my-4 text-xs sm:text-sm">
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-building-shield text-sauna-600 mt-1 w-4"></i>
                                    <span><strong>Pháp nhân:</strong> CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU (MST: 0402088011)</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-location-dot text-sauna-600 mt-1 w-4"></i>
                                    <span><strong>Địa chỉ:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-sauna-600 mt-1 w-4"></i>
                                    <span><strong>Hotline / Zalo:</strong> <a href="tel:0978745785" class="text-red-600 font-bold">0978.745.785</a></span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-brands fa-facebook text-blue-600 mt-1 w-4"></i>
                                    <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:underline font-medium">Hiếu Nghĩa Xông Hơi Đà Nẵng</a></span>
                                </li>
                            </ul>
                            <div class="bg-sauna-50 p-3.5 rounded-xl border border-sauna-200 text-xs text-sauna-900 mb-4">
                                <i class="fa-solid fa-gift text-amber-600 mr-1"></i>
                                <strong>Ưu đãi tháng này:</strong> Miễn phí khảo sát tận nơi + Tặng trọn bộ phụ kiện phòng xông (Xô gáo gỗ thông, đá sauna, đồng hồ nhiệt ẩm, đèn chống nổ) khi thi công trọn gói!
                            </div>
                            <button onclick="openConsultModal('Tư vấn thi công phòng xông hơi trọn gói')" class="w-full bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold py-3 rounded-xl shadow transition flex items-center justify-center gap-2 text-sm">
                                <i class="fa-solid fa-paper-plane text-amber-400"></i> Nhận Khảo Sát & Thiết Kế 3D Miễn Phí
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2 -->
            <div class="hero-slide hidden transition-opacity duration-700 opacity-0 z-0 items-center min-h-[460px] sm:min-h-[540px] lg:min-h-[600px]">
                <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x800/4a2511/facc15?text=PHONG+XONG+HOI+DA+MUOI+HIMALAYA'"
                     alt="Phòng xông hơi đá muối Himalaya Đà Nẵng" 
                     class="absolute inset-0 w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-sauna-950/95 via-sauna-950/80 to-sauna-950/40"></div>
                <div class="relative max-w-7xl mx-auto px-4 py-10 sm:py-14 lg:py-16 w-full">
                    <div class="max-w-2xl text-white space-y-4 sm:space-y-5">
                        <span class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 px-3.5 py-1.5 rounded-full text-xs font-bold uppercase">
                            <i class="fa-solid fa-spa"></i> Xu Hướng Chăm Sóc Sức Khỏe Tại Gia 2026
                        </span>
                        <h2 class="font-heading font-black text-2xl sm:text-4xl lg:text-5xl leading-tight">
                            THI CÔNG PHÒNG XÔNG HƠI <span class="text-amber-400">ĐÁ MUỐI & GỖ HINOKI</span> ĐẲNG CẤP
                        </h2>
                        <p class="text-gray-200 text-xs sm:text-base leading-relaxed">
                            Nhập khẩu trực tiếp Gỗ Thông Phần Lan, Gỗ Tuyết Tùng (Cedar), Gỗ Hinoki Nhật Bản kết hợp Đá Muối Himalaya nguyên khối – Mang không gian Spa 5 sao về ngay ngôi nhà của bạn tại Đà Nẵng, Hội An, Huế.
                        </p>
                        <div class="flex flex-wrap gap-3 pt-2 pb-4 sm:pb-0">
                            <a href="#cong-trinh" class="w-full sm:w-auto text-center bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-extrabold text-xs sm:text-sm px-6 py-3.5 rounded-xl shadow-lg transition">
                                Xem Công Trình Thực Tế
                            </a>
                            <a href="#san-pham" class="w-full sm:w-auto text-center bg-white/15 hover:bg-white/25 text-white border border-white/30 font-heading font-bold text-xs sm:text-sm px-6 py-3.5 rounded-xl transition">
                                Xem Báo Giá Sản Phẩm
                            </a>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- Slider Controls -->
        <div class="
        absolute bottom-3 sm:bottom-5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button onclick="setHeroSlide(0)" id="slideDot0" class="w-8 h-2.5 rounded-full bg-amber-400 transition-all"></button>
            <button onclick="setHeroSlide(1)" id="slideDot1" class="w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
    </section>

    <!-- ==================== QUICK CATEGORY BANNERS (CĂN GIỮA TRÊN MOBILE, KHÔNG BỊ ÉP CHỮ DỌC) ==================== -->
    <section class="py-6 sm:py-8 bg-white border-b border-sauna-100">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid grid-cols-2 md:grid-cols-5 gap-2.5 sm:gap-4">
                <button onclick="filterProducts('phong-xong-hoi'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-3 sm:p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all flex flex-col sm:flex-row items-center text-center sm:text-left gap-2 sm:gap-3">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-lg sm:text-xl shrink-0 transition">
                        <i class="fa-solid fa-house-fire"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white leading-snug">Phòng Xông Hơi</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200 mt-0.5">Khô, Ướt, Đá Muối</p>
                    </div>
                </button>

                <button onclick="filterProducts('may-xong-kho'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-3 sm:p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all flex flex-col sm:flex-row items-center text-center sm:text-left gap-2 sm:gap-3">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-lg sm:text-xl shrink-0 transition">
                        <i class="fa-solid fa-fire-burner"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white leading-snug">Máy Xông Hơi Khô</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200 mt-0.5">Harvia, Sawo, Coast</p>
                    </div>
                </button>

                <button onclick="filterProducts('may-xong-uot'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-3 sm:p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all flex flex-col sm:flex-row items-center text-center sm:text-left gap-2 sm:gap-3">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-lg sm:text-xl shrink-0 transition">
                        <i class="fa-solid fa-cloud-showers-water"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white leading-snug">Máy Xông Hơi Ướt</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200 mt-0.5">Amazon, Coast, Harvia</p>
                    </div>
                </button>

                <button onclick="filterProducts('go-phu-kien'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-3 sm:p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all flex flex-col sm:flex-row items-center text-center sm:text-left gap-2 sm:gap-3">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-lg sm:text-xl shrink-0 transition">
                        <i class="fa-solid fa-tree"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white leading-snug">Gỗ & Phụ Kiện</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200 mt-0.5">Thông Mỹ, Tuyết Tùng</p>
                    </div>
                </button>

                <button onclick="filterProducts('bon-suc'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="col-span-2 md:col-span-1 group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-3 sm:p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all flex flex-row items-center justify-center md:justify-start text-left gap-3">
                    <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-lg sm:text-xl shrink-0 transition">
                        <i class="fa-solid fa-hot-tub-person"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white leading-snug">Bồn Sục & Bồn Gỗ</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200 mt-0.5">Jacuzzi, Bồn Ngâm</p>
                    </div>
                </button>
            </div>
        </div>
    </section>

<!-- ... existing code ... -->
            <!-- Flatsome Category Filter Tabs -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8" id="productTabs">
                <button onclick="filterProducts('all')" data-tab="all" class="product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-800 text-white shadow">
                    Tất Cả Sản Phẩm
                </button>
                <button onclick="filterProducts('phong-xong-hoi')" data-tab="phong-xong-hoi" class="product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Phòng Xông Hơi
                </button>
                <button onclick="filterProducts('may-xong-kho')" data-tab="may-xong-kho" class="product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Máy Xông Hơi Khô
                </button>
                <button onclick="filterProducts('may-xong-uot')" data-tab="may-xong-uot" class="product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Máy Xông Hơi Ướt
                </button>
                <button onclick="filterProducts('go-phu-kien')" data-tab="go-phu-kien" class="product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Gỗ & Phụ Kiện
                </button>
                <button onclick="filterProducts('bon-suc')" data-tab="bon-suc" class="product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Bồn Sục & Bồn Gỗ
                </button>
            </div>

            <!-- Dynamic Product Grid (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 3 CỘT TABLET, 4 CỘT MÁY TÍNH) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-5">
                <!-- Populated by JavaScript -->
            </div>
        </div>
    </section>

<!-- ... existing code ... -->
    <!-- ==================== FLATSOME STICKY FLOATING CONTACT BUTTONS ==================== -->
    <!-- Trên Máy Tính: Hiển thị nút nổi góc trái và phải -->
    <div class="hidden md:flex fixed left-4 bottom-5 z-40 flex-col gap-3">
        <!-- Zalo Button -->
        <a href="https://zalo.me/0978745785" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2.5 bg-blue-600 hover:bg-blue-700 text-white p-1.5 pr-4 rounded-full shadow-xl transition transform hover:scale-105">
            <span class="w-10 h-10 rounded-full bg-white text-blue-600 font-heading font-black text-xs flex items-center justify-center shrink-0 pulse-ring">
                Zalo
            </span>
            <div class="leading-tight">
                <span class="block text-[10px] text-blue-100">Chat Zalo báo giá</span>
                <span class="font-heading font-extrabold text-xs">0978.745.785</span>
            </div>
        </a>

        <!-- Phone Hotline Button -->
        <a href="tel:0978745785" class="group flex items-center gap-2.5 bg-red-600 hover:bg-red-700 text-white p-1.5 pr-4 rounded-full shadow-xl transition transform hover:scale-105">
            <span class="w-10 h-10 rounded-full bg-amber-400 text-sauna-950 flex items-center justify-center shrink-0 animate-phone-ring pulse-ring">
                <i class="fa-solid fa-phone-volume text-base"></i>
            </span>
            <div class="leading-tight">
                <span class="block text-[10px] text-red-100">Gọi kỹ thuật 24/7</span>
                <span class="font-heading font-extrabold text-xs sm:text-sm">0978.745.785</span>
            </div>
        </a>
    </div>

    <!-- Right Floating Fanpage & Back to Top (Desktop) -->
    <div class="hidden md:flex fixed right-4 bottom-5 z-40 flex-col gap-2.5">
        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" title="Fanpage Hiếu Nghĩa Sauna" class="w-11 h-11 rounded-full bg-[#1877F2] hover:bg-blue-700 text-white shadow-lg flex items-center justify-center text-lg transition transform hover:scale-110">
            <i class="fa-brands fa-facebook-messenger"></i>
        </a>
        <button onclick="window.scrollTo({top:0, behavior:'smooth'})" title="Lên đầu trang" class="w-11 h-11 rounded-full bg-sauna-800 hover:bg-sauna-950 text-amber-400 shadow-lg flex items-center justify-center text-sm transition">
            <i class="fa-solid fa-chevron-up"></i>
        </button>
    </div>

    <!-- Trên Điện Thoại: Thanh liên hệ cố định dưới đáy chuẩn Flatsome (Không che nội dung web) -->
    <div class="md:hidden fixed bottom-0 inset-x-0 z-40 bg-white border-t border-sauna-200 shadow-[0_-4px_20px_rgba(0,0,0,0.1)] grid grid-cols-4 h-14">
        <a href="tel:0978745785" class="flex flex-col items-center justify-center text-red-600 hover:bg-red-50 transition">
            <i class="fa-solid fa-phone-volume text-base animate-phone-ring"></i>
            <span class="text-[10px] font-heading font-extrabold mt-0.5">0978.745.785</span>
        </a>
        <a href="https://zalo.me/0978745785" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-blue-600 hover:bg-blue-50 transition border-l border-gray-100">
            <span class="font-heading font-black text-xs leading-none bg-blue-600 text-white px-1.5 py-0.5 rounded">Zalo</span>
            <span class="text-[10px] font-heading font-bold mt-0.5">Chat Báo Giá</span>
        </a>
        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-[#1877F2] hover:bg-blue-50 transition border-l border-gray-100">
            <i class="fa-brands fa-facebook-messenger text-base"></i>
            <span class="text-[10px] font-heading font-bold mt-0.5">Fanpage</span>
        </a>
        <a href="#du-toan" class="flex flex-col items-center justify-center bg-sauna-800 text-amber-300 hover:bg-sauna-900 transition">
            <i class="fa-solid fa-calculator text-sm"></i>
            <span class="text-[10px] font-heading font-bold mt-0.5 text-white">Tính Chi Phí</span>
        </a>
    </div>

<!-- ... existing code ... -->
        // RENDER PRODUCTS (TỐI ƯU 2 CỘT ĐỒNG ĐỀU TRÊN ĐIỆN THOẠI & 4 CỘT TRÊN MÁY TÍNH)
        function renderProducts(filter = 'all') {
            const grid = document.getElementById('productGrid');
            const filtered = filter === 'all' ? productsData : productsData.filter(p => p.category === filter);

            grid.innerHTML = filtered.map(item => `
                <div class="flatsome-product-box bg-white rounded-xl sm:rounded-2xl border border-sauna-200/80 overflow-hidden flex flex-col justify-between group h-full">
                    <div>
                        <!-- Image Box with Flatsome Quick View Hover -->
                        <div class="relative h-36 sm:h-52 overflow-hidden bg-sauna-50">
                            <img src="${item.image}" 
                                 onerror="this.src='https://placehold.co/600x450/4a2511/facc15?text=${encodeURIComponent(item.code)}'"
                                 alt="${item.name}" 
                                 class="product-img w-full h-full object-cover">
                            
                            <!-- Top Left Badge -->
                            <span class="absolute top-2 left-2 sm:top-3 sm:left-3 bg-sauna-800 text-amber-300 text-[9px] sm:text-[10px] font-heading font-bold uppercase px-2 py-0.5 sm:px-2.5 sm:py-1 rounded shadow">
                                ${item.badge}
                            </span>

                            <!-- Top Right Wishlist Button -->
                            <button onclick="addToQuote('${item.id}')" title="Thêm vào danh sách báo giá" class="absolute top-2 right-2 sm:top-3 sm:right-3 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-white/90 hover:bg-red-600 text-sauna-800 hover:text-white flex items-center justify-center shadow transition">
                                <i class="fa-regular fa-heart text-[11px] sm:text-xs"></i>
                            </button>

                            <!-- Flatsome Slide-up Quick View Bar -->
                            <button onclick="openQuickView('${item.id}')" class="quick-view-bar hidden sm:block absolute bottom-0 inset-x-0 bg-sauna-900/90 hover:bg-sauna-950 text-amber-300 font-heading font-bold text-xs uppercase py-2.5 text-center tracking-wider">
                                <i class="fa-regular fa-eye mr-1"></i> Xem Nhanh Thông Số
                            </button>
                        </div>

                        <!-- Product Info -->
                        <div class="p-2.5 sm:p-4">
                            <span class="text-[9px] sm:text-[10px] font-bold uppercase tracking-wider text-sauna-500 block mb-0.5 truncate">${item.categoryLabel}</span>
                            <h3 onclick="openQuickView('${item.id}')" class="font-heading font-bold text-xs sm:text-sm text-sauna-950 hover:text-sauna-600 cursor-pointer line-clamp-2 h-8 sm:h-10 leading-4 sm:leading-5">
                                ${item.name}
                            </h3>
                            <div class="flex items-center gap-0.5 sm:gap-1 text-amber-400 text-[9px] sm:text-[11px] my-1 sm:my-1.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                                <span class="text-gray-400 text-[9px] sm:text-[10px] ml-1 truncate">(${item.code})</span>
                            </div>
                            <div class="font-heading font-extrabold text-xs sm:text-base text-red-600 mt-0.5 truncate">
                                ${item.price}
                            </div>
                        </div>
                    </div>

                    <!-- Action Buttons -->
                    <div class="px-2.5 pb-2.5 sm:px-4 sm:pb-4 pt-1 flex items-center gap-1.5 sm:gap-2">
                        <button onclick="openConsultModal('Báo giá: ${item.name}')" class="flex-1 bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-[11px] sm:text-xs py-2 sm:py-2.5 px-2 rounded-lg sm:rounded-xl transition flex items-center justify-center gap-1">
                            <i class="fa-solid fa-comment-dots text-amber-400"></i> <span>Báo Giá</span>
                        </button>
                        <button onclick="openQuickView('${item.id}')" title="Xem chi tiết" class="w-8 h-8 sm:w-9 sm:h-9 rounded-lg sm:rounded-xl bg-sauna-50 hover:bg-sauna-100 text-sauna-800 border border-sauna-200 flex items-center justify-center shrink-0 transition">
                            <i class="fa-regular fa-eye text-xs"></i>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        function filterProducts(category) {
            renderProducts(category);
            document.querySelectorAll('.product-tab-btn').forEach(btn => {
                if (btn.dataset.tab === category) {
                    btn.className = 'product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-800 text-white shadow';
                } else {
                    btn.className = 'product-tab-btn px-3 sm:px-4 py-2 sm:py-2.5 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200';
                }
            });
        }

<!-- ... existing code ... -->
        // HERO SLIDER LOGIC (DÙNG RELATIVE/HIDDEN ĐỂ CHIỀU CAO TỰ ĐỘNG CHUẨN TRÊN MOBILE)
        let currentSlide = 0;
        function setHeroSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            slides.forEach((s, i) => {
                if (i === index) {
                    s.classList.remove('hidden', 'opacity-0', 'z-0');
                    s.classList.add('flex', 'opacity-100', 'z-10');
                } else {
                    s.classList.remove('flex', 'opacity-100', 'z-10');
                    s.classList.add('hidden', 'opacity-0', 'z-0');
                }
            });
            document.getElementById('slideDot0').className = index === 0 ? 'w-8 h-2.5 rounded-full bg-amber-400 transition-all' : 'w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all';
            document.getElementById('slideDot1').className = index === 1 ? 'w-8 h-2.5 rounded-full bg-amber-400 transition-all' : 'w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all';
            currentSlide = index;
        }

        function toggleMobileMenu() {
            document.getElementById('mobileMenu').classList.toggle('hidden');
        }

        function showToast(msg) {
            const toast = document.getElementById('toastNotification');
            document.getElementById('toastMessage').textContent = msg;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 4000);
        }

        // Tự động làm sạch dòng chữ thừa "<!DOCTYPE html>" hoặc tiêu đề GitHub Pages nếu dán vào README.md
        function cleanStrayDoctypeAndWrapper() {
            const walker = document.createTreeWalker(document.body, NodeFilter.SHOW_TEXT, null, false);
            const nodesToRemove = [];
            while (walker.nextNode()) {
                const node = walker.currentNode;
                if (node.nodeValue && node.nodeValue.trim().toLowerCase().includes('<!doctype html>')) {
                    nodesToRemove.push(node);
                }
            }
            nodesToRemove.forEach(n => n.parentNode && n.parentNode.removeChild(n));

            document.querySelectorAll('p, div, h1').forEach(el => {
                const txt = (el.textContent || '').trim().toLowerCase();
                if (txt === '<!doctype html>' || txt === 'xonghoimientrung') {
                    el.style.display = 'none';
                }
            });
        }

        // INITIALIZE ON LOAD
        window.onload = function() {
            cleanStrayDoctypeAndWrapper();
            renderProducts('all');
            renderProjects('all');
            renderBlogs();
            calculateSaunaEstimate();
            setInterval(() => {
                setHeroSlide((currentSlide + 1) % 2);
            }, 6500);
        };
    </script>
</body>
</html>
