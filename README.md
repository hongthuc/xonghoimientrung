<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xông Hơi Miền Trung | CÔNG TY TNHH TM DV HOÀNG GIA HIẾU - Sản Xuất & Lắp Đặt Phòng Xông Hơi Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU (xonghoimientrung.com) - Chuyên sản xuất và lắp đặt phòng xông hơi khô, ướt, đá muối, phân phối máy xông hơi Harvia, Sawo, Coast, Amazon tại Đà Nẵng và miền Trung. Địa chỉ: 67 Phi Bình 7, P. Ngũ Hành Sơn, Đà Nẵng. Hotline: 0978.745.785">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Montserrat & Inter (Chuẩn phong cách Flatsome Việt Nam) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@600;700;800;900&display=swap" rel="stylesheet">
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        sauna: {
                            50: '#fdf8f3',
                            100: '#faeee1',
                            200: '#f3dac0',
                            300: '#eac096',
                            400: '#dfa069',
                            500: '#d68545',
                            600: '#b8652c', /* Màu gỗ thông / tuyết tùng chủ đạo */
                            700: '#984e24',
                            800: '#7b3f22',
                            900: '#4a2511', /* Màu gỗ đậm Flatsome */
                            950: '#2b1307',
                        },
                        gold: {
                            400: '#facc15',
                            500: '#eab308',
                            600: '#ca8a04',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Custom Flatsome Theme Styling */
        body {
            font-family: 'Inter', sans-serif;
            color: #333333;
            background-color: #fcfaf7;
            overflow-x: hidden;
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
            margin-bottom: 2rem;
        }
        .section-title-container::before,
        .section-title-container::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e5dcd3;
            max-width: 180px;
        }
        .section-title-main {
            padding: 0 1.25rem;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.04em;
            color: #4a2511;
            position: relative;
        }

        /* Flatsome Product Box Hover Effects */
        .flatsome-product-box {
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .flatsome-product-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px -5px rgba(74, 37, 17, 0.14);
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
            transform: scale(1.07);
        }

        /* Flatsome Date Badge on Blog/Project Cards */
        .flatsome-date-badge {
            width: 52px;
            height: 56px;
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
<body class="antialiased selection:bg-sauna-600 selection:text-white">

    <!-- ==================== FLATSOME TOP BAR ==================== -->
    <div class="bg-sauna-950 text-sauna-100 text-xs border-b border-sauna-800/60">
        <div class="max-w-7xl mx-auto px-4 py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3">
                <span class="inline-flex items-center gap-1.5 font-semibold text-amber-400">
                    <i class="fa-solid fa-crown text-[11px]"></i>
                    CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU
                </span>
                <span class="hidden md:inline text-sauna-400">|</span>
                <span class="hidden md:inline text-gray-300">Giải pháp cho sức khỏe & thư giãn – Tư vấn, sản xuất & lắp đặt phòng xông hơi Miền Trung</span>
            </div>
            <div class="flex flex-wrap items-center gap-4 text-[11px] sm:text-xs">
                <span class="hidden lg:inline-flex items-center gap-1.5 text-gray-300">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    67 Phi Bình 7, P. Ngũ Hành Sơn, TP. Đà Nẵng
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-gray-300">
                    <i class="fa-regular fa-clock text-amber-400"></i>
                    07:30 - 18:30 (T2 - CN)
                </span>
                <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 text-blue-400 hover:text-blue-300 font-medium transition">
                    <i class="fa-brands fa-facebook"></i> Fanpage Hiếu Nghĩa Sauna
                </a>
                <button onclick="triggerLogoUpload()" title="Tải ảnh logo từ máy tính của bạn" class="inline-flex items-center gap-1 bg-sauna-800 hover:bg-sauna-700 text-amber-300 px-2 py-0.5 rounded transition cursor-pointer">
                    <i class="fa-solid fa-camera-rotate text-[10px]"></i> Đổi Logo
                </button>
                <input type="file" id="logoFileInput" accept="image/*" class="hidden" onchange="handleCustomLogo(event)">
            </div>
        </div>
    </div>

    <!-- ==================== FLATSOME MAIN HEADER & STICKY NAV ==================== -->
    <header id="mainHeader" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-md border-b border-sauna-100 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between gap-4">
            
            <!-- Brand Logo (Hoàng Gia Hiếu - Hiếu Nghĩa Sauna & Steam) -->
            <a href="#trang-chu" class="flex items-center gap-3 group shrink-0">
                <div id="logoContainer" class="w-14 h-14 sm:w-16 sm:h-16 rounded-xl bg-gradient-to-br from-sauna-900 via-sauna-800 to-sauna-950 p-1 shadow-md border-2 border-amber-500/80 flex items-center justify-center relative overflow-hidden group-hover:scale-105 transition">
                    <!-- Custom SVG Logo inspired by Fanpage Hiếu Nghĩa Sauna & Steam / Hoàng Gia Hiếu -->
                    <svg id="defaultSvgLogo" viewBox="0 0 120 120" class="w-full h-full">
                        <defs>
                            <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#fde047" />
                                <stop offset="50%" stop-color="#eab308" />
                                <stop offset="100%" stop-color="#ca8a04" />
                            </linearGradient>
                        </defs>
                        <!-- Outer Hexagon / Shield Wood & Gold Frame -->
                        <polygon points="60,6 108,32 108,88 60,114 12,88 12,32" fill="none" stroke="url(#goldGrad)" stroke-width="4"/>
                        <polygon points="60,12 102,35 102,85 60,108 18,85 18,35" fill="#3b1c0c" stroke="#b8652c" stroke-width="1.5"/>
                        <!-- Crown at top -->
                        <path d="M44,32 L51,22 L60,30 L69,22 L76,32 Z" fill="url(#goldGrad)"/>
                        <!-- Sauna Wood Cabin Roof -->
                        <path d="M28,52 L60,33 L92,52" fill="none" stroke="url(#goldGrad)" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Steam Waves -->
                        <path d="M46,74 C43,67 49,62 46,55" fill="none" stroke="#38bdf8" stroke-width="3" stroke-linecap="round"/>
                        <path d="M60,76 C57,68 63,62 60,53" fill="none" stroke="url(#goldGrad)" stroke-width="3.5" stroke-linecap="round"/>
                        <path d="M74,74 C71,67 77,62 74,55" fill="none" stroke="#f97316" stroke-width="3" stroke-linecap="round"/>
                        <!-- Brand Initials -->
                        <text x="60" y="94" text-anchor="middle" fill="url(#goldGrad)" font-family="Montserrat, sans-serif" font-weight="900" font-size="13" letter-spacing="1">HIẾU NGHĨA</text>
                        <text x="60" y="104" text-anchor="middle" fill="#fed7aa" font-family="Inter, sans-serif" font-weight="700" font-size="7.5">SAUNA & STEAM</text>
                    </svg>
                    <img id="customLogoImg" src="" alt="Logo Hoàng Gia Hiếu" class="hidden w-full h-full object-contain rounded-lg">
                </div>
                <div>
                    <div class="flex items-center gap-1.5">
                        <span class="font-heading font-black text-base sm:text-lg md:text-xl text-sauna-900 tracking-tight leading-none">HOÀNG GIA HIẾU</span>
                        <span class="hidden sm:inline-block bg-amber-100 text-sauna-800 text-[10px] font-bold px-2 py-0.5 rounded-full border border-amber-300">HIẾU NGHĨA SAUNA</span>
                    </div>
                    <p class="text-[11px] sm:text-xs font-semibold text-sauna-600 mt-0.5">xonghoimientrung.com • Sản xuất & Lắp đặt Phòng Xông Hơi</p>
                    <p class="text-[10px] text-gray-500 hidden md:block">Đà Nẵng • Huế • Hội An • Quảng Nam • Quảng Ngãi • Quy Nhơn</p>
                </div>
            </a>

            <!-- Desktop Navigation Menu (Flatsome Mega Menu Style) -->
            <nav class="hidden xl:flex items-center gap-1 font-heading text-xs font-bold uppercase tracking-wide text-sauna-900">
                <a href="#trang-chu" class="px-3 py-2.5 rounded-lg text-sauna-600 bg-sauna-50 hover:bg-sauna-100 transition">Trang Chủ</a>
                <a href="#gioi-thieu" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Giới Thiệu</a>
                
                <!-- Dropdown Sản Phẩm -->
                <div class="relative has-dropdown">
                    <a href="#san-pham" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition inline-flex items-center gap-1">
                        Sản Phẩm <i class="fa-solid fa-chevron-down text-[10px] opacity-75"></i>
                    </a>
                    <!-- Mega Menu Dropdown -->
                    <div class="dropdown-menu absolute left-0 top-full pt-2 w-[680px] z-50">
                        <div class="bg-white rounded-2xl shadow-2xl border border-sauna-200 p-5 grid grid-cols-3 gap-5 text-left normal-case font-sans">
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-700 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-house-chimney-window text-amber-600"></i> Phòng Xông Hơi
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Khô (Sauna)</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Đá Muối Himalaya</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Hồng Ngoại</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Ướt Kính Cường Lực</button></li>
                                    <li><button onclick="filterProducts('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Khô Kết Hợp Ướt</button></li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-700 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-fire-burner text-amber-600"></i> Máy Xông Hơi Khô & Ướt
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="filterProducts('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi HARVIA (Phần Lan)</button></li>
                                    <li><button onclick="filterProducts('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi SAWO Chính Hãng</button></li>
                                    <li><button onclick="filterProducts('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi COAST Cao Cấp</button></li>
                                    <li><button onclick="filterProducts('may-xong-uot')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi AMAZON Khô & Ướt</button></li>
                                    <li><button onclick="filterProducts('may-xong-uot')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Hơi OCEANIC / MONACO</button></li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-700 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-tree text-amber-600"></i> Gỗ & Phụ Kiện Xông Hơi
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Gỗ Thông Phần Lan Nhập Khẩu</button></li>
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Gỗ Tuyết Tùng (Cedar) & Hinoki Nhật</button></li>
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Đá Muối Himalaya & Phụ Kiện Sauna</button></li>
                                    <li><button onclick="filterProducts('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5"><i class="fa-solid fa-angle-right text-amber-500"></i> Bồn Sục Jacuzzi & Bồn Ngâm Gỗ</button></li>
                                    <li><button onclick="filterProducts('all')" class="text-sauna-600 font-bold hover:underline flex items-center gap-1.5 pt-1">Xem tất cả 20+ sản phẩm <i class="fa-solid fa-arrow-right"></i></button></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <a href="#cong-trinh" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Công Trình</a>
                <a href="#du-toan" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition flex items-center gap-1">
                    <i class="fa-solid fa-calculator text-amber-600"></i> Báo Giá Nhanh
                </a>
                <a href="#quy-trinh" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Quy Trình</a>
                <a href="#tin-tuc" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Tin Tức</a>
                <a href="#lien-he" class="px-3 py-2.5 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Liên Hệ</a>
            </nav>

            <!-- Right Actions: Search, Wishlist, Cart & Hotline CTA -->
            <div class="flex items-center gap-2 sm:gap-3">
                <!-- Search Button -->
                <button onclick="toggleSearchModal()" class="w-10 h-10 rounded-full bg-sauna-50 hover:bg-sauna-100 text-sauna-800 flex items-center justify-center transition" title="Tìm kiếm sản phẩm">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>

                <!-- Cart / Quote Basket -->
                <button onclick="toggleQuoteDrawer()" class="relative w-10 h-10 rounded-full bg-sauna-50 hover:bg-sauna-100 text-sauna-800 flex items-center justify-center transition" title="Danh sách yêu cầu báo giá">
                    <i class="fa-solid fa-cart-flatbed"></i>
                    <span id="cartCountBadge" class="absolute -top-1 -right-1 w-5 h-5 rounded-full bg-red-600 text-white text-[10px] font-bold flex items-center justify-center">0</span>
                </button>

                <!-- Hotline Button -->
                <a href="tel:0978745785" class="hidden sm:inline-flex items-center gap-2.5 bg-gradient-to-r from-sauna-700 to-sauna-600 hover:from-sauna-800 hover:to-sauna-700 text-white px-4 py-2.5 rounded-full shadow-md hover:shadow-lg transition">
                    <span class="w-7 h-7 rounded-full bg-amber-400 text-sauna-950 flex items-center justify-center animate-phone-ring">
                        <i class="fa-solid fa-phone-volume text-xs"></i>
                    </span>
                    <div class="text-left leading-tight">
                        <span class="block text-[10px] uppercase tracking-wider text-amber-200 font-semibold">Tư vấn 24/7</span>
                        <span class="font-heading font-extrabold text-sm">0978.745.785</span>
                    </div>
                </a>

                <!-- Mobile Menu Button -->
                <button onclick="toggleMobileMenu()" class="xl:hidden w-10 h-10 rounded-xl bg-sauna-900 text-white flex items-center justify-center">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu Drawer -->
        <div id="mobileMenu" class="hidden xl:hidden bg-white border-t border-sauna-100 px-4 pt-3 pb-6 shadow-xl">
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

    <!-- ==================== FLATSOME HERO SLIDER ==================== -->
    <section id="trang-chu" class="relative bg-sauna-950 overflow-hidden">
        <div id="heroSlidesContainer" class="relative min-h-[520px] sm:min-h-[580px] lg:min-h-[630px] flex items-center">
            
            <!-- Slide 1 -->
            <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 flex items-center">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x800/3b1c0c/facc15?text=XONG+HOI+MIEN+TRUNG+-+HOANG+GIA+HIEU'"
                     alt="Thi công phòng xông hơi Đà Nẵng Hoàng Gia Hiếu" 
                     class="
                     absolute inset-0 w-full h-full object-cover object-center scale-105 transition-transform duration-1000">
                <div class="absolute inset-0 bg-gradient-to-r from-sauna-950/95 via-sauna-950/80 to-sauna-950/40"></div>
                
                <div class="relative max-w-7xl mx-auto px-4 py-16 w-full grid lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-7 text-white space-y-5">
                        <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 px-3.5 py-1.5 rounded-full text-xs font-bold uppercase tracking-wider">
                            <i class="fa-solid fa-award text-amber-400"></i> Thương Hiệu Uy Tín Hàng Đầu Đà Nẵng & Miền Trung
                        </div>
                        <h1 class="font-heading font-black text-3xl sm:text-4xl lg:text-5xl leading-tight">
                            CÔNG TY TNHH TM DV <span class="text-amber-400">HOÀNG GIA HIẾU</span>
                            <span class="block text-xl sm:text-2xl lg:text-3xl font-bold text-sauna-200 mt-2">
                                Chuyên Sản Xuất & Lắp Đặt Phòng Xông Hơi Trọn Gói
                            </span>
                        </h1>
                        <p class="text-gray-200 text-sm sm:text-base leading-relaxed max-w-2xl">
                            Đơn vị trực tiếp thiết kế, sản xuất tại xưởng và thi công lắp đặt <strong>Phòng Xông Hơi Khô (Sauna), Phòng Xông Hơi Ướt (Steam), Phòng Xông Đá Muối Himalaya</strong> cho Gia đình, Spa, Biệt thự, Khách sạn & Resort tại Đà Nẵng và các tỉnh miền Trung.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 pt-1 text-xs sm:text-sm">
                            <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm px-3 py-2 rounded-xl border border-white/15">
                                <i class="fa-solid fa-circle-check text-amber-400"></i>
                                <span>Giá gốc trực tiếp tại xưởng</span>
                            </div>
                            <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm px-3 py-2 rounded-xl border border-white/15">
                                <i class="fa-solid fa-circle-check text-amber-400"></i>
                                <span>Gỗ Phần Lan, Hinoki, Tuyết Tùng</span>
                            </div>
                            <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm px-3 py-2 rounded-xl border border-white/15 col-span-2 sm:col-span-1">
                                <i class="fa-solid fa-circle-check text-amber-400"></i>
                                <span>Bảo hành tận nơi 24/7</span>
                            </div>
                        </div>
                        <div class="flex flex-wrap items-center gap-3 pt-3">
                            <a href="tel:0978745785" class="inline-flex items-center gap-2.5 bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-extrabold text-sm px-6 py-3.5 rounded-xl shadow-lg transition transform hover:-translate-y-0.5">
                                <i class="fa-solid fa-phone-volume"></i> GỌI NGAY: 0978.745.785
                            </a>
                            <a href="#du-toan" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 font-heading font-bold text-sm px-6 py-3.5 rounded-xl backdrop-blur-sm transition">
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
            <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none z-0 flex items-center">
                <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x800/4a2511/facc15?text=PHONG+XONG+HOI+DA+MUOI+HIMALAYA'"
                     alt="Phòng xông hơi đá muối Himalaya Đà Nẵng" 
                     class="absolute inset-0 w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-sauna-950/95 via-sauna-950/75 to-transparent"></div>
                <div class="relative max-w-7xl mx-auto px-4 py-16 w-full">
                    <div class="max-w-2xl text-white space-y-5">
                        <span class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 px-3.5 py-1.5 rounded-full text-xs font-bold uppercase">
                            <i class="fa-solid fa-spa"></i> Xu Hướng Chăm Sóc Sức Khỏe Tại Gia 2026
                        </span>
                        <h2 class="font-heading font-black text-3xl sm:text-5xl leading-tight">
                            THI CÔNG PHÒNG XÔNG HƠI <span class="text-amber-400">ĐÁ MUỐI & GỖ HINOKI</span> ĐẲNG CẤP
                        </h2>
                        <p class="text-gray-200 text-sm sm:text-base leading-relaxed">
                            Nhập khẩu trực tiếp Gỗ Thông Phần Lan, Gỗ Tuyết Tùng (Cedar), Gỗ Hinoki Nhật Bản kết hợp Đá Muối Himalaya nguyên khối – Mang không gian Spa 5 sao về ngay ngôi nhà của bạn tại Đà Nẵng, Hội An, Huế.
                        </p>
                        <div class="flex flex-wrap gap-3 pt-2">
                            <a href="#cong-trinh" class="bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-extrabold text-sm px-6 py-3.5 rounded-xl shadow-lg transition">
                                Xem Công Trình Thực Tế
                            </a>
                            <a href="#san-pham" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-heading font-bold text-sm px-6 py-3.5 rounded-xl transition">
                                Xem Báo Giá Sản Phẩm
                            </a>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- Slider Controls -->
        <div class="absolute bottom-5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button onclick="setHeroSlide(0)" id="slideDot0" class="w-8 h-2.5 rounded-full bg-amber-400 transition-all"></button>
            <button onclick="setHeroSlide(1)" id="slideDot1" class="w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
    </section>

    <!-- ==================== QUICK CATEGORY BANNERS (FLATSOME UX BANNER GRID) ==================== -->
    <section class="py-8 bg-white border-b border-sauna-100">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-2 md:grid-cols-5 gap-3 sm:gap-4">
                <button onclick="filterProducts('phong-xong-hoi'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all text-left flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-xl shrink-0 transition">
                        <i class="fa-solid fa-house-fire"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white">Phòng Xông Hơi</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200">Khô, Ướt, Đá Muối</p>
                    </div>
                </button>

                <button onclick="filterProducts('may-xong-kho'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all text-left flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-xl shrink-0 transition">
                        <i class="fa-solid fa-fire-burner"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white">Máy Xông Hơi Khô</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200">Harvia, Sawo, Coast</p>
                    </div>
                </button>

                <button onclick="filterProducts('may-xong-uot'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all text-left flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-xl shrink-0 transition">
                        <i class="fa-solid fa-cloud-showers-water"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white">Máy Xông Hơi Ướt</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200">Amazon, Coast, Harvia</p>
                    </div>
                </button>

                <button onclick="filterProducts('go-phu-kien'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all text-left flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-xl shrink-0 transition">
                        <i class="fa-solid fa-tree"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white">Gỗ & Phụ Kiện</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200">Thông Mỹ, Tuyết Tùng</p>
                    </div>
                </button>

                <button onclick="filterProducts('bon-suc'); document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="col-span-2 md:col-span-1 group relative rounded-2xl overflow-hidden shadow-sm border border-sauna-200 p-4 bg-gradient-to-br from-sauna-50 to-amber-50/50 hover:from-sauna-800 hover:to-sauna-950 transition-all text-left flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-sauna-700 text-amber-300 group-hover:bg-amber-400 group-hover:text-sauna-950 flex items-center justify-center text-xl shrink-0 transition">
                        <i class="fa-solid fa-hot-tub-person"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 group-hover:text-white">Bồn Sục & Bồn Gỗ</h3>
                        <p class="text-[11px] text-gray-500 group-hover:text-sauna-200">Jacuzzi, Bồn Ngâm</p>
                    </div>
                </button>
            </div>
        </div>
    </section>

    <!-- ==================== GIỚI THIỆU & TẠI SAO CHỌN CHÚNG TÔI (STYLE DINHGOSAUNA.VN) ==================== -->
    <section id="gioi-thieu" class="py-14 sm:py-16 bg-[#fcfaf7]">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid lg:grid-cols-12 gap-10 items-center">
                <!-- Left Column: Company Introduction -->
                <div class="lg:col-span-6 space-y-4">
                    <div class="inline-flex items-center gap-2 text-sauna-600 font-heading font-bold text-xs uppercase tracking-widest">
                        <span class="w-8 h-[2px] bg-sauna-600"></span> VỀ CHÚNG TÔI • XONGHOIMIENTRUNG.COM
                    </div>
                    <h2 class="font-heading font-black text-2xl sm:text-3xl text-sauna-900 leading-snug">
                        CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ <span class="text-sauna-600">HOÀNG GIA HIẾU</span>
                    </h2>
                    <p class="text-sm text-amber-800 font-semibold bg-amber-50 border-l-4 border-amber-500 p-3 rounded-r-xl">
                        Chuyên tư vấn – sản xuất – lắp đặt phòng xông hơi tại Đà Nẵng và các tỉnh lân cận. Phân phối gỗ nhập khẩu (Gỗ thông Phần Lan, Tuyết tùng, Hinoki Nhật Bản) & Máy xông hơi chính hãng.
                    </p>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Với nhiều năm kinh nghiệm thực chiến tại thị trường Đà Nẵng và miền Trung dưới thương hiệu <strong>Hiếu Nghĩa Sauna & Steam (Hoàng Gia Hiếu)</strong>, chúng tôi tự hào kiến tạo hàng trăm công trình phòng xông hơi gia đình, Spa, thẩm mỹ viện, khách sạn, biệt thự nghỉ dưỡng và homestay đạt chuẩn kỹ thuật và thẩm mỹ cao nhất.
                    </p>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Mỗi sản phẩm tại <strong>xonghoimientrung.com</strong> đều được tuyển chọn khắt khe theo tiêu chuẩn an toàn điện – nước, khả năng giữ nhiệt tối ưu và phù hợp với khí hậu miền Trung. Phòng xông hơi không đơn thuần là giải pháp chăm sóc sức khỏe, mà còn là biểu tượng của sự thư giãn, phong cách sống và đẳng cấp cho ngôi nhà bạn.
                    </p>

                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="bg-white p-3.5 rounded-xl border border-sauna-200 text-center shadow-sm">
                            <span class="block font-heading font-black text-2xl text-sauna-700">500+</span>
                            <span class="text-xs text-gray-500">Công trình hoàn thiện</span>
                        </div>
                        <div class="bg-white p-3.5 rounded-xl border border-sauna-200 text-center shadow-sm">
                            <span class="block font-heading font-black text-2xl text-sauna-700">100%</span>
                            <span class="text-xs text-gray-500">Thiết bị chính hãng</span>
                        </div>
                        <div class="bg-white p-3.5 rounded-xl border border-sauna-200 text-center shadow-sm">
                            <span class="block font-heading font-black text-2xl text-sauna-700">24/7</span>
                            <span class="text-xs text-gray-500">Bảo hành tận nơi</span>
                        </div>
                    </div>

                    <div class="pt-3 flex flex-wrap items-center gap-4">
                        <a href="tel:0978745785" class="inline-flex items-center gap-2 bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-xs sm:text-sm px-5 py-3 rounded-xl shadow transition">
                            <i class="fa-solid fa-phone"></i> Gọi ngay: 0978.745.785
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-heading font-bold text-xs sm:text-sm px-5 py-3 rounded-xl shadow transition">
                            <i class="fa-brands fa-facebook-f"></i> Xem Fanpage Chính Thức
                        </a>
                    </div>
                </div>

                <!-- Right Column: 04 Lý Do Chọn Chúng Tôi (Chuẩn cấu trúc dinhgosauna.vn) -->
                <div class="lg:col-span-6 grid sm:grid-cols-2 gap-4">
                    <div class="bg-white p-6 rounded-2xl shadow-sm border border-sauna-100 hover:border-sauna-400 transition relative overflow-hidden group">
                        <span class="font-heading font-black text-4xl text-sauna-100 group-hover:text-amber-200 transition absolute top-3 right-4">01</span>
                        <div class="w-11 h-11 rounded-xl bg-sauna-100 text-sauna-700 flex items-center justify-center text-lg mb-3">
                            <i class="fa-solid fa-medal"></i>
                        </div>
                        <h3 class="font-heading font-bold text-base text-sauna-900 mb-2">Chất Lượng Cao Cấp</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Phòng xông hơi được sản xuất từ gỗ thông Phần Lan, gỗ Tuyết Tùng, Hinoki sấy khô tiêu chuẩn chống cong vênh, mối mọt và máy xông hơi nhập khẩu chính hãng.
                        </p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl shadow-sm border border-sauna-100 hover:border-sauna-400 transition relative overflow-hidden group">
                        <span class="font-heading font-black text-4xl text-sauna-100 group-hover:text-amber-200 transition absolute top-3 right-4">02</span>
                        <div class="w-11 h-11 rounded-xl bg-sauna-100 text-sauna-700 flex items-center justify-center text-lg mb-3">
                            <i class="fa-solid fa-screwdriver-wrench"></i>
                        </div>
                        <h3 class="font-heading font-bold text-base text-sauna-900 mb-2">Thi Công Chuyên Nghiệp</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Đội ngũ kỹ thuật viên của Hoàng Gia Hiếu giàu kinh nghiệm, trực tiếp khảo sát – thiết kế – lắp đặt chuẩn an toàn điện nước, thẩm mỹ sắc nét từng chi tiết.
                        </p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl shadow-sm border border-sauna-100 hover:border-sauna-400 transition relative overflow-hidden group">
                        <span class="font-heading font-black text-4xl text-sauna-100 group-hover:text-amber-200 transition absolute top-3 right-4">03</span>
                        <div class="w-11 h-11 rounded-xl bg-sauna-100 text-sauna-700 flex items-center justify-center text-lg mb-3">
                            <i class="fa-solid fa-heart-pulse"></i>
                        </div>
                        <h3 class="font-heading font-bold text-base text-sauna-900 mb-2">Chăm Sóc Sức Khỏe</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Thúc đẩy tuần hoàn máu, đào thải độc tố, giảm đau nhức xương khớp, giải tỏa căng thẳng và cải thiện giấc ngủ ngay tại nhà cho cả gia đình.
                        </p>
                    </div>

                    <div class="bg-white p-6 rounded-2xl shadow-sm border border-sauna-100 hover:border-sauna-400 transition relative overflow-hidden group">
                        <span class="font-heading font-black text-4xl text-sauna-100 group-hover:text-amber-200 transition absolute top-3 right-4">04</span>
                        <div class="w-11 h-11 rounded-xl bg-sauna-100 text-sauna-700 flex items-center justify-center text-lg mb-3">
                            <i class="fa-solid fa-hand-holding-dollar"></i>
                        </div>
                        <h3 class="font-heading font-bold text-base text-sauna-900 mb-2">Giá Gốc Tận Xưởng</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Trực tiếp gia công sản xuất tại xưởng Đà Nẵng không qua trung gian, mang lại mức giá cạnh tranh nhất cùng chế độ bảo hành nhanh chóng trong ngày.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM (FLATSOME TABBED WOOCOMMERCE GRID) ==================== -->
    <section id="san-pham" class="py-14 sm:py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <!-- Flatsome Section Header -->
            <div class="section-title-container">
                <h2 class="section-title-main text-xl sm:text-2xl md:text-3xl text-center">
                    <i class="fa-solid fa-cubes text-sauna-600 mr-2"></i> SẢN PHẨM CHỦ LỰC CỦA HOÀNG GIA HIẾU
                </h2>
            </div>
            <p class="text-center text-gray-500 text-xs sm:text-sm max-w-2xl mx-auto -mt-4 mb-8">
                Cung cấp trọn gói Phòng Xông Hơi thiết kế theo yêu cầu, Máy Xông Hơi Khô & Ướt nhập khẩu chính hãng (Harvia, Sawo, Coast, Amazon), Gỗ Thông Phần Lan, Tuyết Tùng, Hinoki & Bồn Sục.
            </p>

            <!-- Flatsome Category Filter Tabs -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-8" id="productTabs">
                <button onclick="filterProducts('all')" data-tab="all" class="product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-800 text-white shadow">
                    Tất Cả Sản Phẩm
                </button>
                <button onclick="filterProducts('phong-xong-hoi')" data-tab="phong-xong-hoi" class="product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Phòng Xông Hơi
                </button>
                <button onclick="filterProducts('may-xong-kho')" data-tab="may-xong-kho" class="product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Máy Xông Hơi Khô
                </button>
                <button onclick="filterProducts('may-xong-uot')" data-tab="may-xong-uot" class="product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Máy Xông Hơi Ướt
                </button>
                <button onclick="filterProducts('go-phu-kien')" data-tab="go-phu-kien" class="product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Gỗ Nhập Khẩu & Phụ Kiện
                </button>
                <button onclick="filterProducts('bon-suc')" data-tab="bon-suc" class="product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Bồn Sục & Bồn Gỗ
                </button>
            </div>

            <!-- Dynamic Product Grid -->
            <div id="productGrid" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-5">
                <!-- Populated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- ==================== CÔNG TRÌNH TIÊU BIỂU TỪ FANPAGE HIẾU NGHĨA SAUNA ==================== -->
    <section id="cong-trinh" class="py-14 sm:py-16 bg-[#f7f2eb] border-y border-sauna-200/70">
        <div class="max-w-7xl mx-auto px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-xl sm:text-2xl md:text-3xl text-center">
                    <i class="fa-solid fa-helmet-safety text-sauna-600 mr-2"></i> CÔNG TRÌNH TIÊU BIỂU TẠI ĐÀ NẴNG & MIỀN TRUNG
                </h2>
            </div>
            <p class="text-center text-gray-600 text-xs sm:text-sm max-w-2xl mx-auto -mt-4 mb-8">
                Hình ảnh thực tế các dự án sản xuất và lắp đặt phòng xông hơi khô, ướt, đá muối được cập nhật trực tiếp từ Fanpage <strong>Hiếu Nghĩa Sauna & Steam - Công ty TNHH TMDV Hoàng Gia Hiếu</strong>.
            </p>

            <!-- Project Filter Pills -->
            <div class="flex flex-wrap justify-center gap-2 mb-8">
                <button onclick="filterProjects('all')" data-proj="all" class="proj-tab-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-sauna-800 text-white">Tất cả công trình</button>
                <button onclick="filterProjects('Gia đình & Villa')" data-proj="Gia đình & Villa" class="proj-tab-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-white text-sauna-900 border border-sauna-200">Gia đình & Biệt thự</button>
                <button onclick="filterProjects('Spa & Hotel')" data-proj="Spa & Hotel" class="proj-tab-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-white text-sauna-900 border border-sauna-200">Spa, Gym & Khách sạn</button>
                <button onclick="filterProjects('Đá muối & Hinoki')" data-proj="Đá muối & Hinoki" class="proj-tab-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-white text-sauna-900 border border-sauna-200">Phòng Xông Đá Muối & Hinoki</button>
            </div>

            <!-- Projects Grid -->
            <div id="projectsGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Populated by JavaScript -->
            </div>

            <!-- Callout Banner below projects -->
            <div class="mt-10 wood-pattern rounded-2xl p-6 sm:p-8 text-white shadow-xl flex flex-col md:flex-row items-center justify-between gap-6 border border-amber-500/40">
                <div class="space-y-2 text-center md:text-left">
                    <span class="text-xs font-bold uppercase tracking-widest text-amber-400">Trực tiếp khảo sát tại Đà Nẵng - Huế - Quảng Nam - Quảng Ngãi</span>
                    <h3 class="font-heading font-extrabold text-xl sm:text-2xl">Bạn muốn thiết kế phòng xông hơi vừa vặn với diện tích nhà mình?</h3>
                    <p class="text-xs sm:text-sm text-sauna-100">Kỹ thuật viên Hoàng Gia Hiếu sẽ đến đo đạc tận nơi, tư vấn vị trí đặt đường điện - ống hơi và báo giá tiết kiệm nhất!</p>
                </div>
                <div class="flex flex-wrap items-center gap-3 shrink-0">
                    <a href="tel:0978745785" class="bg-amber-400 hover:bg-amber-300 text-sauna-950 font-heading font-extrabold text-sm px-6 py-3.5 rounded-xl shadow-lg transition flex items-center gap-2">
                        <i class="fa-solid fa-phone-volume"></i> 0978.745.785
                    </a>
                    <button onclick="openConsultModal('Đặt lịch khảo sát tận nơi tại Đà Nẵng / Miền Trung')" class="bg-white/15 hover:bg-white/25 border border-white/40 text-white font-heading font-bold text-sm px-5 py-3.5 rounded-xl transition">
                        Đặt Lịch Khảo Sát
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== 04 BƯỚC CHUYÊN NGHIỆP TRONG QUY TRÌNH (CHUẨN DINHGOSAUNA.VN) ==================== -->
    <section id="quy-trinh" class="py-14 sm:py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-xl sm:text-2xl md:text-3xl text-center">
                    04 BƯỚC CHUYÊN NGHIỆP TRONG QUY TRÌNH CỦA HOÀNG GIA HIẾU
                </h2>
            </div>
            <p class="text-center text-gray-500 text-xs sm:text-sm max-w-2xl mx-auto -mt-4 mb-10">
                Quy trình làm việc rõ ràng, minh bạch vật tư, đúng tiến độ cam kết và chế độ bảo hành tận tâm tại <strong>xonghoimientrung.com</strong>.
            </p>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Step 1 -->
                <div class="relative bg-[#fcfaf7] rounded-2xl p-6 border border-sauna-200 shadow-sm hover:shadow-md transition group">
                    <div class="flex items-center justify-between mb-4">
                        <span class="w-12 h-12 rounded-2xl bg-sauna-800 text-amber-400 font-heading font-black text-xl flex items-center justify-center shadow">01</span>
                        <i class="fa-solid fa-comments text-2xl text-sauna-400 group-hover:text-sauna-700 transition"></i>
                    </div>
                    <h3 class="font-heading font-extrabold text-base text-sauna-900 mb-2 uppercase">Gặp Gỡ & Tư Vấn</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Trực tiếp khảo sát hiện trạng, trao đổi về ý tưởng, tư vấn loại gỗ, công suất máy và báo giá chi tiết để định hình phong cách thiết kế phù hợp ngân sách của bạn.
                    </p>
                </div>

                <!-- Step 2 -->
                <div class="relative bg-[#fcfaf7] rounded-2xl p-6 border border-sauna-200 shadow-sm hover:shadow-md transition group">
                    <div class="flex items-center justify-between mb-4">
                        <span class="w-12 h-12 rounded-2xl bg-sauna-800 text-amber-400 font-heading font-black text-xl flex items-center justify-center shadow">02</span>
                        <i class="fa-solid fa-compass-drafting text-2xl text-sauna-400 group-hover:text-sauna-700 transition"></i>
                    </div>
                    <h3 class="font-heading font-extrabold text-base text-sauna-900 mb-2 uppercase">Thiết Kế Chi Tiết</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Sau khi thống nhất phương án và vật liệu, Hoàng Gia Hiếu lên bản vẽ thiết kế chi tiết 2D/3D cho công trình, bố trí ghế ngồi, đèn sauna và đường điện chờ chuẩn xác.
                    </p>
                </div>

                <!-- Step 3 -->
                <div class="relative bg-[#fcfaf7] rounded-2xl p-6 border border-sauna-200 shadow-sm hover:shadow-md transition group">
                    <div class="flex items-center justify-between mb-4">
                        <span class="w-12 h-12 rounded-2xl bg-sauna-800 text-amber-400 font-heading font-black text-xl flex items-center justify-center shadow">03</span>
                        <i class="fa-solid fa-hammer text-2xl text-sauna-400 group-hover:text-sauna-700 transition"></i>
                    </div>
                    <h3 class="font-heading font-extrabold text-base text-sauna-900 mb-2 uppercase">Sản Xuất & Thi Công</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Gia công vách gỗ, khung xương cách nhiệt tại xưởng 67 Phi Bình 7, sau đó vận chuyển lắp đặt nhanh gọn tại công trình dưới sự giám sát kỹ thuật nghiêm ngặt.
                    </p>
                </div>

                <!-- Step 4 -->
                <div class="relative bg-[#fcfaf7] rounded-2xl p-6 border border-sauna-200 shadow-sm hover:shadow-md transition group">
                    <div class="flex items-center justify-between mb-4">
                        <span class="w-12 h-12 rounded-2xl bg-sauna-800 text-amber-400 font-heading font-black text-xl flex items-center justify-center shadow">04</span>
                        <i class="fa-solid fa-file-shield text-2xl text-sauna-400 group-hover:text-sauna-700 transition"></i>
                    </div>
                    <h3 class="font-heading font-extrabold text-base text-sauna-900 mb-2 uppercase">Vận Hành & Bàn Giao</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Vận hành thử nhiệt độ – độ ẩm, hướng dẫn khách hàng sử dụng an toàn, bàn giao công trình kèm phiếu bảo hành chính hãng và bảo trì định kỳ tận nơi.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== CÔNG CỤ TÍNH CÔNG SUẤT MÁY & DỰ TOÁN CHI PHÍ ==================== -->
    <section id="du-toan" class="py-14 sm:py-16 wood-pattern text-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-5 space-y-4">
                    <span class="inline-block bg-amber-400/20 border border-amber-400/50 text-amber-300 text-xs font-bold uppercase px-3 py-1 rounded-full">
                        Tiện Ích Độc Quyền Tại xonghoimientrung.com
                    </span>
                    <h2 class="font-heading font-black text-2xl sm:text-3xl leading-tight">
                        TÍNH CÔNG SUẤT MÁY & <span class="text-amber-400">DỰ TOÁN CHI PHÍ</span> PHÒNG XÔNG HƠI
                    </h2>
                    <p class="text-sauna-100 text-xs sm:text-sm leading-relaxed">
                        Chọn đúng công suất máy xông hơi theo thể tích phòng giúp <strong>làm nóng nhanh (chỉ 5 - 10 phút), tiết kiệm điện năng và tăng tuổi thọ thiết bị</strong>. Nhập kích thước dự kiến của bạn để nhận gợi ý kỹ thuật từ kỹ sư Hoàng Gia Hiếu:
                    </p>
                    <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-4 border border-white/15 space-y-2 text-xs">
                        <div class="flex items-center gap-2 text-amber-300 font-bold">
                            <i class="fa-solid fa-lightbulb"></i> Tiêu chuẩn tham khảo:
                        </div>
                        <p>• Phòng 1 - 2 người: Ngang 1.0m × Sâu 1.2m × Cao 2.0m (Máy 4.5kW - 6kW)</p>
                        <p>• Phòng 2 - 4 người: Ngang 1.5m × Sâu 1.5m × Cao 2.1m (Máy 6kW - 9kW)</p>
                        <p>• Phòng Gia đình lớn / Spa: Ngang 2.0m × Sâu 2.2m × Cao 2.1m (Máy 9kW - 15kW)</p>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <div class="bg-white text-gray-800 rounded-2xl p-6 sm:p-8 shadow-2xl border-2 border-amber-400">
                        <h3 class="font-heading font-extrabold text-lg text-sauna-900 mb-5 flex items-center gap-2">
                            <i class="fa-solid fa-sliders text-sauna-600"></i> Nhập Thông Số Phòng Xông Dự Kiến
                        </h3>

                        <div class="grid sm:grid-cols-2 gap-4 mb-5">
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1.5">Loại phòng xông hơi</label>
                                <select id="calcRoomType" onchange="calculateSaunaEstimate()" class="w-full rounded-xl border border-sauna-200 px-3.5 py-2.5 text-sm font-medium focus:outline-none focus:border-sauna-600">
                                    <option value="dry">Phòng Xông Hơi Khô (Sauna Gỗ)</option>
                                    <option value="salt">Phòng Xông Hơi Đá Muối Himalaya</option>
                                    <option value="wet">Phòng Xông Hơi Ướt (Kính Cường Lực)</option>
                                    <option value="combo">Phòng Xông Hơi Khô Kết Hợp Ướt</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold uppercase text-gray-600 mb-1.5">Chất liệu gỗ / Vật tư & Dòng máy</label>
                                <select id="calcMaterial" onchange="calculateSaunaEstimate()" class="w-full rounded-xl border border-sauna-200 px-3.5 py-2.5 text-sm font-medium focus:outline-none focus:border-sauna-600">
                                    <option value="standard">Gỗ Thông Phần Lan + Máy Amazon / Coast</option>
                                    <option value="premium">Gỗ Tuyết Tùng (Cedar) + Máy Sawo / Coast</option>
                                    <option value="luxury">Gỗ Hinoki Nhật Bản + Máy Harvia Phần Lan</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-3 gap-3 sm:gap-4 mb-6">
                            <div>
                                <label class="block text-xs font-bold text-gray-600 mb-1">Chiều Dài (m)</label>
                                <input type="number" id="calcLength" value="1.5" min="0.8" max="6" step="0.1" oninput="calculateSaunaEstimate()" class="w-full rounded-xl border border-sauna-200 px-3 py-2 text-sm font-bold text-sauna-900">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-600 mb-1">Chiều Rộng (m)</label>
                                <input type="number" id="calcWidth" value="1.4" min="0.8" max="6" step="0.1" oninput="calculateSaunaEstimate()" class="w-full rounded-xl border border-sauna-200 px-3 py-2 text-sm font-bold text-sauna-900">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-600 mb-1">Chiều Cao (m)</label>
                                <input type="number" id="calcHeight" value="2.1" min="1.8" max="3" step="0.05" oninput="calculateSaunaEstimate()" class="w-full rounded-xl border border-sauna-200 px-3 py-2 text-sm font-bold text-sauna-900">
                            </div>
                        </div>

                        <!-- Result Box -->
                        <div class="bg-sauna-50 rounded-2xl p-4 sm:p-5 border border-sauna-200 mb-5">
                            <div class="grid sm:grid-cols-3 gap-4 text-center sm:text-left">
                                <div>
                                    <span class="text-[11px] uppercase font-semibold text-gray-500 block">Thể tích & Sức chứa</span>
                                    <span id="resVolume" class="font-heading font-extrabold text-base sm:text-lg text-sauna-900">4.41 m³ (2-3 người)</span>
                                </div>
                                <div>
                                    <span class="text-[11px] uppercase font-semibold text-gray-500 block">Công suất máy khuyên dùng</span>
                                    <span id="resPower" class="font-heading font-extrabold text-base sm:text-lg text-sauna-700">Máy 6kW - 9kW</span>
                                </div>
                                <div>
                                    <span class="text-[11px] uppercase font-semibold text-gray-500 block">Dự toán trọn gói tham khảo</span>
                                    <span id="resPrice" class="font-heading font-black text-lg sm:text-xl text-red-600">21.5 - 26.8 Triệu</span>
                                </div>
                            </div>
                        </div>

                        <div class="flex flex-col sm:flex-row items-center justify-between gap-3">
                            <p class="text-xs text-gray-500 italic">
                                * Giá đã bao gồm nhân công lắp đặt tại Đà Nẵng và trọn bộ phụ kiện phòng xông.
                            </p>
                            <button onclick="sendEstimateToModal()" class="w-full sm:w-auto bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-xs sm:text-sm px-6 py-3 rounded-xl shadow transition shrink-0">
                                <i class="fa-solid fa-file-invoice-dollar text-amber-400 mr-1.5"></i> Nhận Báo Giá Chi Tiết Cấu Hình Này
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== TIN TỨC & KINH NGHIỆM XÔNG HƠI (FLATSOME BLOG GRID) ==================== -->
    <section id="tin-tuc" class="py-14 sm:py-16 bg-[#fcfaf7]">
        <div class="max-w-7xl mx-auto px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-xl sm:text-2xl md:text-3xl text-center">
                    <i class="fa-regular fa-newspaper text-sauna-600 mr-2"></i> TIN TỨC & CẨM NANG XÔNG HƠI
                </h2>
            </div>

            <div id="blogGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Populated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- ==================== ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI ==================== -->
    <section class="py-10 bg-white border-t border-sauna-100">
        <div class="max-w-7xl mx-auto px-4">
            <p class="text-center font-heading font-bold text-xs uppercase tracking-widest text-gray-400 mb-6">
                ĐỐI TÁC THIẾT BỊ CHÍNH HÃNG & KHÁCH HÀNG TIÊU BIỂU TẠI MIỀN TRUNG
            </p>
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-4 items-center">
                <div class="p-4 rounded-xl bg-sauna-50/70 border border-sauna-100 text-center font-heading font-black text-sauna-800 text-sm tracking-wider">HARVIA FINLAND</div>
                <div class="p-4 rounded-xl bg-sauna-50/70 border border-sauna-100 text-center font-heading font-black text-sauna-800 text-sm tracking-wider">SAWO SAUNA</div>
                <div class="p-4 rounded-xl bg-sauna-50/70 border border-sauna-100 text-center font-heading font-black text-sauna-800 text-sm tracking-wider">COAST STEAM</div>
                <div class="p-4 rounded-xl bg-sauna-50/70 border border-sauna-100 text-center font-heading font-black text-sauna-800 text-sm tracking-wider">AMAZON SAUNA</div>
                <div class="p-4 rounded-xl bg-sauna-50/70 border border-sauna-100 text-center font-heading font-black text-sauna-800 text-sm tracking-wider">ZEN SPA ĐÀ NẴNG</div>
                <div class="p-4 rounded-xl bg-sauna-50/70 border border-sauna-100 text-center font-heading font-black text-sauna-800 text-sm tracking-wider">OCEANIC / MONACO</div>
            </div>
        </div>
    </section>

    <!-- ==================== LIÊN HỆ & BẢN ĐỒ (67 PHI BÌNH 7, NGŨ HÀNH SƠN, ĐÀ NẴNG) ==================== -->
    <section id="lien-he" class="py-14 sm:py-16 bg-sauna-50 border-t border-sauna-200">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid lg:grid-cols-12 gap-8">
                <!-- Contact Form & Info -->
                <div class="lg:col-span-6 bg-white rounded-2xl p-6 sm:p-8 shadow-md border border-sauna-200">
                    <span class="text-xs font-bold uppercase tracking-wider text-sauna-600">LIÊN HỆ CHÚNG TÔI</span>
                    <h2 class="font-heading font-black text-xl sm:text-2xl text-sauna-950 mt-1 mb-4">
                        ĐĂNG KÝ TƯ VẤN & BÁO GIÁ TẠI XƯỞNG
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-600 mb-6">
                        Quý khách cần lắp đặt phòng xông hơi gia đình, Spa hay mua máy xông hơi, gỗ thông nhập khẩu tại Đà Nẵng & miền Trung, vui lòng để lại thông tin hoặc gọi trực tiếp <strong>0978.745.785</strong>.
                    </p>

                    <form id="contactForm" onsubmit="submitContactForm(event)" class="space-y-4">
                        <div class="grid sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Họ và tên của bạn *</label>
                                <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="custPhone" required placeholder="Ví dụ: 0978745785" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-600">
                            </div>
                        </div>
                        <div class="grid sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Khu vực lắp đặt</label>
                                <input type="text" id="custLocation" placeholder="Đà Nẵng, Hội An, Huế, Quảng Nam..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Hạng mục quan tâm</label>
                                <select id="custService" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-600">
                                    <option value="Thi công phòng xông hơi khô trọn gói">Thi công phòng xông hơi khô trọn gói</option>
                                    <option value="Thi công phòng xông hơi ướt kính cường lực">Thi công phòng xông hơi ướt kính cường lực</option>
                                    <option value="Thi công phòng xông hơi đá muối Himalaya">Thi công phòng xông hơi đá muối Himalaya</option>
                                    <option value="Mua máy xông hơi khô / ướt chính hãng">Mua máy xông hơi khô / ướt chính hãng</option>
                                    <option value="Mua gỗ thông nhập khẩu & phụ kiện xông hơi">Mua gỗ thông nhập khẩu & phụ kiện</option>
                                    <option value="Bảo trì / Sửa chữa máy xông hơi tại Đà Nẵng">Bảo trì / Sửa chữa máy xông hơi tại Đà Nẵng</option>
                                </select>
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-gray-700 mb-1">Ghi chú kích thước hoặc yêu cầu thêm</label>
                            <textarea id="custNote" rows="3" placeholder="Ví dụ: Cần khảo sát lắp phòng xông khô cho 2-3 người tại Ngũ Hành Sơn..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-600"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-extrabold text-sm py-3.5 rounded-xl shadow-lg transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane text-amber-400"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>
                </div>

                <!-- Company Card & Interactive Map -->
                <div class="lg:col-span-6 flex flex-col justify-between space-y-6">
                    <div class="bg-sauna-950 text-white rounded-2xl p-6 sm:p-7 shadow-md border border-sauna-800 space-y-4">
                        <div class="flex items-center justify-between border-b border-sauna-800 pb-4">
                            <div>
                                <h3 class="font-heading font-extrabold text-lg text-amber-400">CÔNG TY TNHH TM DV HOÀNG GIA HIẾU</h3>
                                <p class="text-xs text-sauna-200 mt-0.5">Thương hiệu: Hiếu Nghĩa Sauna & Steam • xonghoimientrung.com</p>
                            </div>
                            <span class="px-3 py-1 rounded-full bg-amber-400/20 text-amber-300 text-xs font-bold">MST: 0402088011</span>
                        </div>
                        <div class="space-y-3 text-xs sm:text-sm">
                            <p class="flex items-start gap-3">
                                <i class="fa-solid fa-location-dot text-amber-400 mt-1 w-4"></i>
                                <span><strong>Địa chỉ văn phòng & xưởng:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, Thành phố Đà Nẵng (KĐT Hòa Quý)</span>
                            </p>
                            <p class="flex items-start gap-3">
                                <i class="fa-solid fa-phone-volume text-amber-400 mt-1 w-4"></i>
                                <span><strong>Hotline / Zalo 24/7:</strong> <a href="tel:0978745785" class="text-amber-400 font-bold text-base hover:underline">0978.745.785</a></span>
                            </p>
                            <p class="flex items-start gap-3">
                                <i class="fa-solid fa-envelope text-amber-400 mt-1 w-4"></i>
                                <span><strong>Email:</strong> xonghoihieunghia@gmail.com | info@xonghoimientrung.com</span>
                            </p>
                            <p class="flex items-start gap-3">
                                <i class="fa-solid fa-globe text-amber-400 mt-1 w-4"></i>
                                <span><strong>Website:</strong> <a href="#trang-chu" class="text-amber-300 hover:underline">https://xonghoimientrung.com</a></span>
                            </p>
                            <p class="flex items-start gap-3">
                                <i class="fa-brands fa-facebook text-amber-400 mt-1 w-4"></i>
                                <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="text-blue-300 hover:underline">fb.com/100057133012799 (Hiếu Nghĩa Sauna & Steam)</a></span>
                            </p>
                        </div>
                    </div>

                    <!-- Google Map Embed pointing to 67 Phi Bình 7, Ngũ Hành Sơn, Đà Nẵng -->
                    <div class="rounded-2xl overflow-hidden shadow-md border-2 border-white flex-1 min-h-[260px] relative bg-gray-200">
                        <iframe 
                            title="Bản đồ Công ty TNHH TMDV Hoàng Gia Hiếu - 67 Phi Bình 7, Ngũ Hành Sơn, Đà Nẵng"
                            src="https://www.google.com/maps?q=67+Phi+Binh+7,+Ngu+Hanh+Son,+Da+Nang&output=embed" 
                            class="w-full h-full min-h-[260px] border-0" 
                            allowfullscreen="" 
                            loading="lazy">
                        </iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FLATSOME FOOTER ==================== -->
    <footer class="bg-sauna-950 text-gray-300 pt-14 pb-20 md:pb-8 border-t-4 border-sauna-600">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-10 border-b border-sauna-800">
                
                <!-- Col 1: Company Info -->
                <div class="lg:col-span-4 space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-11 h-11 rounded-xl bg-amber-500 text-sauna-950 font-heading font-black text-lg flex items-center justify-center">
                            HGH
                        </div>
                        <div>
                            <h3 class="font-heading font-black text-base text-white">CÔNG TY TNHH TM DV HOÀNG GIA HIẾU</h3>
                            <p class="text-xs text-amber-400 font-semibold">XONGHOIMIENTRUNG.COM</p>
                        </div>
                    </div>
                    <p class="text-xs text-gray-400 leading-relaxed">
                        Đơn vị hàng đầu chuyên sản xuất và lắp đặt phòng xông hơi khô, phòng xông hơi ướt, phòng xông đá muối Himalaya; phân phối máy xông hơi Harvia, Sawo, Coast, Amazon và gỗ thông nhập khẩu tại Đà Nẵng & các tỉnh miền Trung.
                    </p>
                    <div class="flex items-center gap-3 pt-1">
                        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-lg bg-blue-600 hover:bg-blue-500 text-white flex items-center justify-center transition" title="Fanpage Facebook">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="https://zalo.me/0978745785" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-lg bg-sky-500 hover:bg-sky-400 text-white flex items-center justify-center font-bold text-xs transition" title="Zalo 0978.745.785">
                            Zalo
                        </a>
                        <a href="tel:0978745785" class="w-9 h-9 rounded-lg bg-amber-500 hover:bg-amber-400 text-sauna-950 flex items-center justify-center transition" title="Gọi ngay">
                            <i class="fa-solid fa-phone"></i>
                        </a>
                    </div>
                </div>

                <!-- Col 2: Danh mục sản phẩm -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white tracking-wider border-b border-sauna-800 pb-2">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="space-y-2 text-xs text-gray-400">
                        <li><a href="#san-pham" onclick="filterProducts('phong-xong-hoi')" class="hover:text-amber-400 transition"><i class="fa-solid fa-caret-right text-amber-500 mr-1.5"></i> Phòng Xông Hơi Khô Gia Đình & Spa</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('phong-xong-hoi')" class="hover:text-amber-400 transition"><i class="fa-solid fa-caret-right text-amber-500 mr-1.5"></i> Phòng Xông Hơi Đá Muối Himalaya</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('phong-xong-hoi')" class="hover:text-amber-400 transition"><i class="fa-solid fa-caret-right text-amber-500 mr-1.5"></i> Phòng Xông Hơi Ướt Kính Cường Lực</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('may-xong-kho')" class="hover:text-amber-400 transition"><i class="fa-solid fa-caret-right text-amber-500 mr-1.5"></i> Máy Xông Hơi Khô Harvia, Sawo, Coast</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('may-xong-uot')" class="hover:text-amber-400 transition"><i class="fa-solid fa-caret-right text-amber-500 mr-1.5"></i> Máy Xông Hơi Ướt Amazon, Coast, Harvia</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('go-phu-kien')" class="hover:text-amber-400 transition"><i class="fa-solid fa-caret-right text-amber-500 mr-1.5"></i> Gỗ Thông Nhập Khẩu, Tuyết Tùng, Hinoki</a></li>
                    </ul>
                </div>

                <!-- Col 3: Chính sách & Hỗ trợ -->
                <div class="lg:col-span-2 space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white tracking-wider border-b border-sauna-800 pb-2">
                        Dịch Vụ Khách Hàng
                    </h4>
                    <ul class="space-y-2 text-xs text-gray-400">
                        <li><a href="#quy-trinh" class="hover:text-amber-400 transition">Quy trình khảo sát & thi công</a></li>
                        <li><a href="#du-toan" class="hover:text-amber-400 transition">Tính công suất máy xông hơi</a></li>
                        <li><a href="#cong-trinh" class="hover:text-amber-400 transition">Hồ sơ năng lực & Dự án</a></li>
                        <li><button onclick="openPolicyModal('Chính sách bảo hành & bảo trì tận nơi')" class="hover:text-amber-400 transition text-left">Chính sách bảo hành 24/7</button></li>
                        <li><button onclick="openPolicyModal('Chính sách vận chuyển & lắp đặt miền Trung')" class="hover:text-amber-400 transition text-left">Vận chuyển & Lắp đặt trọn gói</button></li>
                    </ul>
                </div>

                <!-- Col 4: Thông tin liên hệ nhanh -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white tracking-wider border-b border-sauna-800 pb-2">
                        Thông Tin Liên Hệ
                    </h4>
                    <div class="space-y-2.5 text-xs text-gray-300">
                        <p><strong class="text-amber-400">Địa chỉ:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</p>
                        <p><strong class="text-amber-400">Hotline / Zalo:</strong> <a href="tel:0978745785" class="font-bold text-white hover:text-amber-400">0978.745.785</a></p>
                        <p><strong class="text-amber-400">Website:</strong> xonghoimientrung.com</p>
                        <p><strong class="text-amber-400">Khu vực phục vụ:</strong> Đà Nẵng, Hội An, Quảng Nam, Huế, Quảng Ngãi, Bình Định & Tây Nguyên.</p>
                    </div>
                </div>
            </div>

            <div class="pt-6 flex flex-col sm:flex-row items-center justify-between text-xs text-gray-500 gap-4">
                <p>Copyright 2026 © <strong>xonghoimientrung.com</strong> - Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU</strong>.</p>
                <p>Giao diện chuẩn <span class="text-gray-400 font-semibold">Flatsome Sauna UX</span> • Thiết kế tối ưu tốc độ & chuyển đổi.</p>
            </div>
        </div>
    </footer>

    <!-- ==================== FLATSOME STICKY FLOATING CONTACT BUTTONS ==================== -->
    <div class="fixed left-4 bottom-5 z-40 flex flex-col gap-3">
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

    <!-- Right Floating Fanpage & Back to Top -->
    <div class="fixed right-4 bottom-5 z-40 flex flex-col gap-2.5">
        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" title="Fanpage Hiếu Nghĩa Sauna" class="w-11 h-11 rounded-full bg-[#1877F2] hover:bg-blue-700 text-white shadow-lg flex items-center justify-center text-lg transition transform hover:scale-110">
            <i class="fa-brands fa-facebook-messenger"></i>
        </a>
        <button onclick="window.scrollTo({top:0, behavior:'smooth'})" title="Lên đầu trang" class="w-11 h-11 rounded-full bg-sauna-800 hover:bg-sauna-950 text-amber-400 shadow-lg flex items-center justify-center text-sm transition">
            <i class="fa-solid fa-chevron-up"></i>
        </button>
    </div>

    <!-- ==================== MODALS (QUICK VIEW, PROJECT DETAIL, QUOTE DRAWER, TOAST) ==================== -->

    <!-- Quick View Product Modal -->
    <div id="quickViewModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-3xl w-full overflow-hidden shadow-2xl border border-sauna-200 animate-fadeIn">
            <div class="flex items-center justify-between px-6 py-4 bg-sauna-900 text-white">
                <h3 id="qvTitleHeader" class="font-heading font-bold text-sm uppercase tracking-wider text-amber-400">Chi Tiết Sản Phẩm</h3>
                <button onclick="closeQuickView()" class="w-8 h-8 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-6 grid md:grid-cols-2 gap-6 max-h-[82vh] overflow-y-auto">
                <div class="rounded-xl overflow-hidden border border-sauna-100 bg-sauna-50">
                    <img id="qvImage" src="" alt="" class="w-full h-72 object-cover">
                </div>
                <div class="space-y-3">
                    <span id="qvCategory" class="inline-block text-[11px] font-bold uppercase px-2.5 py-1 rounded bg-amber-100 text-sauna-800"></span>
                    <h4 id="qvName" class="font-heading font-extrabold text-xl text-sauna-950"></h4>
                    <div class="flex items-center gap-2 text-amber-500 text-xs">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        <span class="text-gray-500">(Chính hãng • Bảo hành tận nơi)</span>
                    </div>
                    <div id="qvPrice" class="font-heading font-black text-2xl text-red-600"></div>
                    <p id="qvDesc" class="text-xs sm:text-sm text-gray-600 leading-relaxed"></p>
                    <div id="qvSpecs" class="bg-sauna-50 p-3.5 rounded-xl border border-sauna-200 text-xs space-y-1.5 text-gray-700"></div>
                    <div class="pt-3 flex flex-wrap gap-2.5">
                        <button id="qvAddQuoteBtn" class="flex-1 bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-xs uppercase py-3 px-4 rounded-xl transition">
                            <i class="fa-solid fa-cart-plus mr-1"></i> Thêm Vào Báo Giá
                        </button>
                        <a href="tel:0978745785" class="bg-red-600 hover:bg-red-700 text-white font-heading font-bold text-xs uppercase py-3 px-4 rounded-xl transition flex items-center gap-1.5">
                            <i class="fa-solid fa-phone"></i> 0978.745.785
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Project / Article Detail Modal -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-sauna-200">
            <div class="flex items-center justify-between px-6 py-4 bg-sauna-900 text-white">
                <h3 id="detailModalHeader" class="font-heading font-bold text-sm uppercase text-amber-400">Thông Tin Công Trình</h3>
                <button onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-6 max-h-[80vh] overflow-y-auto space-y-4">
                <img id="detailModalImg" src="" alt="" class="w-full h-64 sm:h-80 object-cover rounded-xl">
                <div class="flex flex-wrap items-center gap-2 text-xs text-sauna-700 font-semibold">
                    <span id="detailModalBadge" class="bg-amber-100 px-3 py-1 rounded-full"></span>
                    <span>• Đơn vị thi công: Công ty TNHH TMDV Hoàng Gia Hiếu (0978.745.785)</span>
                </div>
                <h4 id="detailModalTitle" class="font-heading font-extrabold text-xl text-sauna-950"></h4>
                <div id="detailModalContent" class="text-sm text-gray-600 leading-relaxed space-y-2"></div>
                <div class="pt-3 border-t border-gray-100 flex items-center justify-between">
                    <a href="tel:0978745785" class="bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-xs px-5 py-2.5 rounded-xl">
                        <i class="fa-solid fa-phone mr-1.5"></i> Tư vấn mẫu tương tự: 0978.745.785
                    </a>
                    <button onclick="closeDetailModal()" class="text-xs font-bold text-gray-500 hover:text-gray-800">Đóng cửa sổ</button>
                </div>
            </div>
        </div>
    </div>

    <!-- Search Modal -->
    <div id="searchModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-start justify-center pt-20 p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full p-6 shadow-2xl">
            <div class="flex items-center justify-between mb-4">
                <h3 class="font-heading font-bold text-base text-sauna-900">Tìm Kiếm Sản Phẩm & Thiết Bị Xông Hơi</h3>
                <button onclick="toggleSearchModal()" class="w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="relative mb-4">
                <input type="text" id="modalSearchInput" oninput="searchProductsModal(this.value)" placeholder="Nhập tên máy xông hơi Harvia, Sawo, Coast, phòng xông đá muối, gỗ thông..." class="w-full pl-10 pr-4 py-3 rounded-xl border-2 border-sauna-300 focus:outline-none focus:border-sauna-700 text-sm">
                <i class="fa-solid fa-magnifying-glass absolute left-3.5 top-3.5 text-sauna-600"></i>
            </div>
            <div id="modalSearchResults" class="max-h-72 overflow-y-auto divide-y divide-gray-100"></div>
        </div>
    </div>

    <!-- Quote / Cart Drawer -->
    <div id="quoteDrawer" class="fixed inset-0 z-50 hidden bg-black/60 backdrop-blur-sm flex justify-end">
        <div class="bg-white w-full max-w-md h-full flex flex-col justify-between shadow-2xl">
            <div class="p-5 bg-sauna-900 text-white flex items-center justify-between">
                <div>
                    <h3 class="font-heading font-bold text-base text-amber-400">Danh Sách Yêu Cầu Báo Giá</h3>
                    <p class="text-xs text-gray-300">Hoàng Gia Hiếu • Hotline: 0978.745.785</p>
                </div>
                <button onclick="toggleQuoteDrawer()" class="w-8 h-8 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="quoteItemsList" class="p-5 flex-1 overflow-y-auto space-y-3"></div>
            <div class="p-5 bg-sauna-50 border-t border-sauna-200 space-y-3">
                <button onclick="checkoutQuote()" class="w-full bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-sm py-3 rounded-xl shadow">
                    Gửi Yêu Cầu Báo Giá Các Mục Đã Chọn
                </button>
            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toastNotification" class="fixed top-20 right-4 z-50 hidden bg-sauna-950 text-white px-5 py-3.5 rounded-xl shadow-2xl border-l-4 border-amber-400 flex items-center gap-3 max-w-sm">
        <i class="fa-solid fa-circle-check text-amber-400 text-lg"></i>
        <div id="toastMessage" class="text-xs sm:text-sm font-medium"></div>
    </div>

    <!-- ==================== JAVASCRIPT DATA & INTERACTIVE LOGIC ==================== -->
    <script>
        // 1. DANH SÁCH SẢN PHẨM (Tổng hợp từ Fanpage Hiếu Nghĩa Sauna & mẫu dinhgosauna.vn)
        const productsData = [
            {
                id: 'p1',
                code: 'HGH-SA01',
                name: 'Phòng Xông Hơi Khô Gỗ Thông Phần Lan Kết Hợp Vách Kính',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Hơi Khô',
                badge: 'Bán chạy',
                price: '22.500.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=800&q=80',
                desc: 'Mẫu phòng xông hơi khô gia đình sang trọng được sản xuất trực tiếp bởi Công ty TNHH TMDV Hoàng Gia Hiếu. Sử dụng gỗ thông Phần Lan nhập khẩu sấy tiêu chuẩn kết hợp cửa kính cường lực 10mm.',
                specs: ['Kích thước: Thiết kế theo thực tế (1.2x1.2m, 1.5x1.5m...)', 'Vật liệu: Gỗ thông Phần Lan nhập khẩu + Kính cường lực 10mm', 'Thiết bị: Máy xông hơi khô 6kW - 9kW + Trọn bộ phụ kiện']
            },
            {
                id: 'p2',
                code: 'HGH-SM02',
                name: 'Phòng Xông Hơi Đá Muối Himalaya Hồng Ngoại Cao Cấp',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Đá Muối',
                badge: 'Hot 2026',
                price: '28.900.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=800&q=80',
                desc: 'Kết hợp hoàn hảo giữa gỗ thông/tuyết tùng tự nhiên và các viên đá muối Himalaya nguyên khối xuyên sáng, giúp thanh lọc không khí, hỗ trợ xương khớp và làm đẹp da.',
                specs: ['Vật liệu: Gỗ thông Mỹ / Phần Lan + Đá muối Himalaya nhập khẩu', 'Hệ thống nhiệt: Máy sauna kết hợp dây hồng ngoại Hàn Quốc', 'Bảo hành: 36 tháng tận nơi tại Đà Nẵng & miền Trung']
            },
            {
                id: 'p3',
                code: 'HGH-HN03',
                name: 'Phòng Xông Hơi Gỗ Tuyết Tùng (Cedar) & Máy Harvia Phần Lan',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Cao Cấp',
                badge: 'VIP Villa',
                price: '38.500.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=80',
                desc: 'Dòng phòng xông hơi thượng hạng dành cho Biệt thự, Villa & Resort tại Đà Nẵng - Hội An. Gỗ Tuyết Tùng tỏa hương tinh dầu tự nhiên thư giãn sâu, độ bền trên 20 năm.',
                specs: ['Gỗ thi công: Gỗ Tuyết Tùng đỏ (Red Cedar) hoặc Hinoki Nhật Bản', 'Máy đi kèm: Máy xông hơi khô Harvia chính hãng Phần Lan', 'Tặng kèm: Xô gáo gỗ, đá sauna Harvia, ẩm kế, đồng hồ cát']
            },
            {
                id: 'p4',
                code: 'HGH-WS04',
                name: 'Phòng Xông Hơi Ướt Kính Cường Lực Chuẩn Spa Hiện Đại',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Hơi Ướt',
                badge: 'Tiết kiệm',
                price: '16.800.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1620626011761-996317b8d101?auto=format&fit=crop&w=800&q=80',
                desc: 'Tận dụng không gian phòng tắm sẵn có lắp đặt vách kính cường lực kín hơi kết hợp máy xông hơi ướt Coast/Amazon/Harvia giúp xông hơi thảo dược giải cảm hiệu quả.',
                specs: ['Vách kính: Kính cường lực 10ly phụ kiện Inox 304 chống gỉ', 'Máy xông ướt: Công suất 6kW / 9kW bảng điều khiển điện tử', 'Phụ kiện: Ghế ngồi xông ướt + Hộp đựng thảo dược xông']
            },
            {
                id: 'p5',
                code: 'HARVIA-BC60',
                name: 'Máy Xông Hơi Khô HARVIA Vega BC60 / BC90 (Phần Lan)',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                badge: 'Chính hãng',
                price: '12.500.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=800&q=80',
                desc: 'Thương hiệu máy xông hơi khô số 1 thế giới từ Phần Lan. Vỏ thép không gỉ cao cấp, thanh điện trở siêu bền, làm nóng cực nhanh và vận hành êm ái.',
                specs: ['Công suất: 6kW / 8kW / 9kW (Điện 1 pha hoặc 3 pha)', 'Xuất xứ: Nhập khẩu chính hãng Harvia (CO/CQ đầy đủ)', 'Bảo hành: 24 tháng tận nhà bởi Hoàng Gia Hiếu']
            },
            {
                id: 'p6',
                code: 'SAWO-9KW',
                name: 'Máy Xông Hơi Khô SAWO Phần Lan 6kW - 9kW Điều Khiển Điện Tử',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                badge: 'Bền bỉ',
                price: '9.800.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1519823551278-64ac92734fb1?auto=format&fit=crop&w=800&q=80',
                desc: 'Máy xông hơi khô Sawo thiết kế sang trọng, bảng điều khiển điện tử thông minh kiểm soát nhiệt độ và thời gian chính xác, rất được các Spa và gia đình tại Đà Nẵng tin dùng.',
                specs: ['Model: Sawo Scandia / निमbus 6kW - 9kW', 'Bảng điều khiển: Điện tử hiển thị nhiệt độ LED', 'Khoang chứa đá: Lớn, tỏa nhiệt đều khắp phòng']
            },
            {
                id: 'p7',
                code: 'COAST-CA90',
                name: 'Máy Xông Hơi Khô COAST CA-60 / CA-90 / CA-120',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                badge: 'Ưa chuộng',
                price: '7.200.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&w=800&q=80',
                desc: 'Dòng máy xông hơi khô Coast CA-Series nổi tiếng với độ bền cao, linh kiện dễ thay thế, bảng điều khiển điện tử rời tiện lợi lắp ngoài cửa phòng xông.',
                specs: ['Model: CA-60 (6kW), CA-90 (9kW), CA-120 (12kW)', 'Vỏ máy: Sơn tĩnh điện hoặc Inox chống rỉ sét', 'Ứng dụng: Gia đình, Phòng Gym, Spa, Khách sạn']
            },
            {
                id: 'p8',
                code: 'AMAZON-SAMB9',
                name: 'Máy Xông Hơi Khô AMAZON SAM-B6 / SAM-B9 / SAM-B12',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                badge: 'Giá tốt',
                price: '5.500.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1600334089648-b0d9d3028eb2?auto=format&fit=crop&w=800&q=80',
                desc: 'Giải pháp tiết kiệm chi phí nhưng vẫn đảm bảo hiệu suất tạo nhiệt mạnh mẽ và an toàn tuyệt đối. Phân phối và lắp đặt tận nơi bởi Hiếu Nghĩa Sauna.',
                specs: ['Công suất: 6kW, 9kW, 12kW, 15kW', 'Thời gian tạo nhiệt: 5 - 7 phút đạt 50-70°C', 'Bảo hành: 18 - 24 tháng chính hãng']
            },
            {
                id: 'p9',
                code: 'SAWO-STE60',
                name: 'Máy Xông Hơi Ướt SAWO STE-60 / STP-90 Cao Cấp',
                category: 'may-xong-uot',
                categoryLabel: 'Máy Xông Hơi Ướt',
                badge: 'Cao cấp',
                price: '10.900.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1584622781564-1d987f7333c1?auto=format&fit=crop&w=800&q=80',
                desc: 'Máy xông hơi ướt SAWO với hệ thống van xả cặn tự động, bình chứa nước Inox 304 dày dặn, phun hơi mịn và đều, chống bám cặn vôi phù hợp nguồn nước miền Trung.',
                specs: ['Model: STE-60 (6kW), STP-90 (9kW), STP-120 (12kW)', 'Tính năng: Tự động cấp nước, bảo vệ khi cạn nước', 'Bảng điều khiển: Cảm ứng / Điện tử chống nước']
            },
            {
                id: 'p10',
                code: 'COAST-KSA90',
                name: 'Máy Xông Hơi Ướt COAST KSA-60 / KSA-90 / KSA-150 (Xả Cặn Tự Động)',
                category: 'may-xong-uot',
                categoryLabel: 'Máy Xông Hơi Ướt',
                badge: 'Bán chạy #1',
                price: '7.800.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1507652313519-d4e9174996dd?auto=format&fit=crop&w=800&q=80',
                desc: 'Dòng máy xông hơi ướt Coast KSA tích hợp van xả cặn tự động sau khi tắt máy, giúp bảo vệ thanh đốt và kéo dài tuổi thọ gấp đôi so với dòng máy thường.',
                specs: ['Công suất: 6kW - 15kW', 'Ưu điểm: Van xả cặn điện tử tự động chống đóng cặn', 'Lắp đặt: Khảo sát & đi ống hơi chịu nhiệt tận nơi']
            },
            {
                id: 'p11',
                code: 'GO-THONG-PL',
                name: 'Gỗ Thông Phần Lan & Gỗ Tuyết Tùng Nhập Khẩu (Đầy Đủ Quy Cách)',
                category: 'go-phu-kien',
                categoryLabel: 'Gỗ Vật Liệu Thi Công',
                badge: 'Giá sỉ xưởng',
                price: 'Liên hệ 0978.745.785',
                image: 'https://images.unsplash.com/photo-1546484396-fb3fc6f95f98?auto=format&fit=crop&w=800&q=80',
                desc: 'Hoàng Gia Hiếu chuyên phân phối sỉ & lẻ Gỗ thông Phần Lan, Gỗ thông Mỹ (không mắt), Gỗ Tuyết Tùng (Cedar), Gỗ Hinoki Nhật Bản đã bào 4 mặt, chạy hèm âm dương chuẩn thi công sauna.',
                specs: ['Quy cách: Dày 12mm - 15mm, Rộng 90-100mm, Dài 2m - 4.8m', 'Độ ẩm: Sấy tiêu chuẩn 10-12% chống cong vênh', 'Cung cấp: Bán lẻ vật tư hoặc thi công hoàn thiện']
            },
            {
                id: 'p12',
                code: 'BON-SUC-GOC',
                name: 'Bồn Sục Jacuzzi Góc B01 & Bồn Ngâm Gỗ Thông / Pơ Mu',
                category: 'bon-suc',
                categoryLabel: 'Bồn Sục & Bồn Gỗ',
                badge: 'Thư giãn',
                price: '8.260.000 VNĐ',
                image: 'https://images.unsplash.com/photo-1560185007-cde436f6a4d0?auto=format&fit=crop&w=800&q=80',
                desc: 'Cung cấp và lắp đặt bồn sục massage thủy lực Acrylic cao cấp và bồn ngâm thuốc bắc/thảo dược bằng gỗ thông, gỗ pơ mu cho gia đình và Spa.',
                specs: ['Kiểu dáng: Bồn sục góc, bồn oval, bồn gỗ tròn/oval', 'Trang bị: Hệ thống mắt sục massage, sen vòi đồng bộ', 'Bảo hành: 36 tháng chính hãng']
            }
        ];

        // 2. DỮ LIỆU CÔNG TRÌNH THỰC TẾ TRÊN FANPAGE HIẾU NGHĨA SAUNA (100057133012799)
        const projectsData = [
            {
                id: 'proj1',
                day: '18',
                month: 'Th3',
                category: 'Spa & Hotel',
                title: 'Bàn Giao Tổ Hợp Phòng Xông Hơi Khô & Ướt Tại Zen Spa & Beauty – Hải Châu, Đà Nẵng',
                location: 'Quận Hải Châu, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=900&q=80',
                summary: 'Hoàn thiện và bàn giao hệ thống phòng xông hơi khô gỗ thông Phần Lan kết hợp phòng xông ướt cho Zen Spa & Beauty tại trung tâm Hải Châu, Đà Nẵng.',
                details: 'Dự án thực tế được đội ngũ kỹ thuật Hiếu Nghĩa Sauna & Steam (Công ty TNHH TMDV Hoàng Gia Hiếu - 0978.745.785) trực tiếp thiết kế và lắp đặt trọn gói tại Hải Châu, Đà Nẵng. Hệ thống sử dụng gỗ thông Phần Lan tuyển chọn, máy xông hơi công suất lớn đáp ứng tần suất hoạt động liên tục của Spa cùng đèn LED trang trí ấm cúng.'
            },
            {
                id: 'proj2',
                day: '02',
                month: 'Th6',
                category: 'Đá muối & Hinoki',
                title: 'Công Trình Phòng Xông Hơi Gỗ Thông Mỹ Kết Hợp Đá Muối & Vách Kính – KĐT Hòa Quý, Ngũ Hành Sơn',
                location: 'P. Ngũ Hành Sơn, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=900&q=80',
                summary: 'Thiết kế phòng xông hơi gia đình hiện đại với mảng tường đá muối Himalaya phát sáng, vách kính cường lực sang trọng ngay tại Ngũ Hành Sơn.',
                details: 'Công trình lắp đặt tại Khu đô thị Hòa Quý, Phường Ngũ Hành Sơn, Đà Nẵng. Chủ đầu tư lựa chọn gỗ thông Mỹ không mắt kết hợp mảng đá muối Himalaya nguyên khối và máy xông hơi khô Sawo 9kW điều khiển điện tử, mang lại không gian chăm sóc sức khỏe đẳng cấp cho cả gia đình.'
            },
            {
                id: 'proj3',
                day: '15',
                month: 'Th7',
                category: 'Đá muối & Hinoki',
                title: 'Thi Công Phòng Xông Hơi Gỗ Hinoki & Máy Harvia Cho Biệt Thự Sơn Trà, Đà Nẵng',
                location: 'Quận Sơn Trà, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=900&q=80',
                summary: 'Đẳng cấp từ chất liệu gỗ Hinoki Nhật Bản thơm dịu tự nhiên đến thiết bị máy xông hơi Harvia nhập khẩu Phần Lan cho căn Villa ven biển.',
                details: 'Bàn giao công trình phòng xông hơi cao cấp tại Sơn Trà, Đà Nẵng. Toàn bộ vách, trần và sàn ghế 2 tầng được gia công tỉ mỉ từ gỗ Hinoki Nhật Bản có hương thơm tinh dầu đặc trưng, kết hợp máy xông hơi Harvia BC90 và bộ phụ kiện gỗ đồng bộ.'
            },
            {
                id: 'proj4',
                day: '25',
                month: 'Th8',
                category: 'Gia đình & Villa',
                title: 'Công Trình Phòng Xông Hơi Khô Kết Hợp Ướt Cho Gia Đình Tại TP. Huế & Hội An',
                location: 'TP. Hội An & TP. Huế',
                image: 'https://images.unsplash.com/photo-1620626011761-996317b8d101?auto=format&fit=crop&w=900&q=80',
                summary: 'Tối ưu diện tích với tổ hợp 2 trong 1: một bên xông khô gỗ thông truyền thống, một bên xông ướt kính cường lực tiện nghi.',
                details: 'Hoàng Gia Hiếu triển khai lắp đặt nhanh gọn trong 2 ngày cho gia đình khách hàng tại Hội An và Huế. Thiết kế cabin đôi liên hoàn giúp các thành viên có thể tùy chọn xông khô hoặc xông ướt thảo dược tùy sở thích.'
            },
            {
                id: 'proj5',
                day: '01',
                month: 'Th10',
                category: 'Gia đình & Villa',
                title: 'Phòng Xông Hơi Gỗ Tuyết Tùng & Máy Coast – Giải Pháp Wellness Tại Gia Đà Nẵng',
                location: 'Quận Cẩm Lệ, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=900&q=80',
                summary: 'Lắp đặt phòng xông hơi khô gỗ Tuyết Tùng đỏ nhập khẩu tận dụng góc sân thượng có mái che cho nhà phố hiện đại.',
                details: 'Giải pháp tận dụng không gian trống tầng thượng nhà phố tại Cẩm Lệ, Đà Nẵng để bố trí phòng xông hơi kích thước 1.5m x 1.4m x 2.1m. Sử dụng máy xông hơi Coast CA-60 bảng điều khiển điện tử rời cực kỳ tiện dụng.'
            },
            {
                id: 'proj6',
                day: '19',
                month: 'Th10',
                category: 'Spa & Hotel',
                title: 'Dự Án Thi Công Hệ Thống Phòng Xông Hơi Chuẩn Resort Tại Quảng Nam & Quy Nhơn',
                location: 'Quảng Nam - Quảng Ngãi - Quy Nhơn',
                image: 'https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&w=900&q=80',
                summary: 'Nâng tầm dịch vụ lưu trú và chăm sóc sức khỏe với hệ thống phòng Sauna & Steam công suất lớn thi công trọn gói.',
                details: 'Công ty TNHH TMDV Hoàng Gia Hiếu là đối tác tin cậy của nhiều chủ Spa, Khách sạn và Resort dọc miền Trung, đảm bảo tiến độ bàn giao nhanh và hỗ trợ kỹ thuật bảo hành tận nơi.'
            }
        ];

        // 3. DỮ LIỆU TIN TỨC & CẨM NANG (Chuẩn phong cách dinhgosauna.vn)
        const blogPosts = [
            {
                id: 'b1',
                day: '10',
                month: 'Th7',
                title: 'Thi Công Phòng Xông Hơi Spa Trọn Gói – Giải Pháp Thiết Kế, Lắp Đặt Chuyên Nghiệp Tại Đà Nẵng',
                excerpt: 'Bí quyết lựa chọn vật liệu gỗ cách nhiệt, máy xông hơi công suất bền bỉ và bố trí ánh sáng chuẩn phong cách Wellness hiện đại cho Spa.',
                image: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=600&q=80',
                content: 'Khi đầu tư phòng xông hơi cho Spa hoặc khách sạn tại Đà Nẵng, yếu tố quan trọng nhất là độ bền vật liệu và khả năng giữ nhiệt ổn định. Tại Công ty TNHH TMDV Hoàng Gia Hiếu (xonghoimientrung.com), chúng tôi sử dụng khung xương cách nhiệt chuyên dụng, lớp xốp bạc phản xạ nhiệt và gỗ thông Phần Lan / Tuyết tùng dày 15mm giúp tiết kiệm đến 30% điện năng tiêu thụ.'
            },
            {
                id: 'b2',
                day: '12',
                month: 'Th5',
                title: 'Máy Xông Hơi Gia Đình Loại Nào Tốt? Kinh Nghiệm Chọn Máy Sauna Phù Hợp 2026',
                excerpt: 'So sánh chi tiết các dòng máy xông hơi Harvia, Sawo, Coast và Amazon về độ bền, mức tiêu thụ điện và chi phí đầu tư.',
                image: 'https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=600&q=80',
                content: 'Để chọn máy xông hơi gia đình bền bỉ, bạn cần tính đúng thể tích phòng (Dài x Rộng x Cao). Ví dụ phòng từ 3 - 4.5m3 nên chọn máy 6kW; phòng từ 5 - 8m3 nên chọn máy 9kW. Các thương hiệu hàng đầu hiện nay tại Hoàng Gia Hiếu gồm Harvia (Phần Lan), Sawo, Coast và Amazon đều có linh kiện chính hãng và bảo hành dài hạn.'
            },
            {
                id: 'b3',
                day: '09',
                month: 'Th5',
                title: 'So Sánh Phòng Xông Hơi Khô Và Phòng Xông Hơi Ướt – Gia Đình Nên Lắp Loại Nào?',
                excerpt: 'Phân tích ưu nhược điểm và lợi ích sức khỏe của xông hơi khô bằng đá sauna và xông hơi ướt bằng hơi nước thảo dược.',
                image: 'https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=600&q=80',
                content: 'Phòng xông hơi khô (Sauna) sử dụng nhiệt khô 55-75°C với độ ẩm thấp (~10%), rất tốt để đốt cháy mỡ thừa, giảm đau cơ khớp. Trong khi đó phòng xông hơi ướt (Steam) ở 45°C với độ ẩm 100% giúp thông thoáng đường hô hấp, giải cảm và cấp ẩm cho làn da. Nhiều gia đình tại Đà Nẵng hiện nay lựa chọn mẫu phòng xông khô kết hợp ướt để tận hưởng cả hai lợi ích.'
            },
            {
                id: 'b4',
                day: '21',
                month: 'Th10',
                title: 'Top Địa Chỉ Sản Xuất & Lắp Đặt Phòng Xông Hơi Uy Tín Tại Đà Nẵng – Hoàng Gia Hiếu',
                excerpt: 'Vì sao hàng trăm khách hàng tại Ngũ Hành Sơn, Hải Châu, Sơn Trà tin chọn Hiếu Nghĩa Sauna & Steam (0978.745.785)?',
                image: 'https://images.unsplash.com/photo-1620626011761-996317b8d101?auto=format&fit=crop&w=600&q=80',
                content: 'Với xưởng sản xuất và văn phòng tại 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng, Công ty TNHH TMDV Hoàng Gia Hiếu cam kết giá gốc tận xưởng, khảo sát tư vấn miễn phí tận nơi và hỗ trợ kỹ thuật nhanh chóng 24/7.'
            }
        ];

        let quoteCart = [];

        // RENDER PRODUCTS
        function renderProducts(filter = 'all') {
            const grid = document.getElementById('productGrid');
            const filtered = filter === 'all' ? productsData : productsData.filter(p => p.category === filter);

            grid.innerHTML = filtered.map(item => `
                <div class="flatsome-product-box bg-white rounded-2xl border border-sauna-200/80 overflow-hidden flex flex-col justify-between group">
                    <div>
                        <!-- Image Box with Flatsome Quick View Hover -->
                        <div class="relative h-56 overflow-hidden bg-sauna-50">
                            <img src="${item.image}" 
                                 onerror="this.src='https://placehold.co/600x450/4a2511/facc15?text=${encodeURIComponent(item.code)}'"
                                 alt="${item.name}" 
                                 class="product-img w-full h-full object-cover">
                            
                            <!-- Top Left Badge -->
                            <span class="absolute top-3 left-3 bg-sauna-800 text-amber-300 text-[10px] font-heading font-bold uppercase px-2.5 py-1 rounded-md shadow">
                                ${item.badge}
                            </span>

                            <!-- Top Right Wishlist Button -->
                            <button onclick="addToQuote('${item.id}')" title="Thêm vào danh sách báo giá" class="
                                absolute top-3 right-3 w-8 h-8 rounded-full bg-white/90 hover:bg-red-600 text-sauna-800 hover:text-white flex items-center justify-center shadow transition">
                                <i class="fa-regular fa-heart text-xs"></i>
                            </button>

                            <!-- Flatsome Slide-up Quick View Bar -->
                            <button onclick="openQuickView('${item.id}')" class="quick-view-bar absolute bottom-0 inset-x-0 bg-sauna-900/90 hover:bg-sauna-950 text-amber-300 font-heading font-bold text-xs uppercase py-2.5 text-center tracking-wider">
                                <i class="fa-regular fa-eye mr-1"></i> Xem Nhanh Thông Số
                            </button>
                        </div>

                        <!-- Product Info -->
                        <div class="p-4">
                            <span class="text-[10px] font-bold uppercase tracking-wider text-sauna-500 block mb-1">${item.categoryLabel}</span>
                            <h3 onclick="openQuickView('${item.id}')" class="font-heading font-bold text-sm text-sauna-950 hover:text-sauna-600 cursor-pointer line-clamp-2 min-h-[2.5rem]">
                                ${item.name}
                            </h3>
                            <div class="flex items-center gap-1 text-amber-400 text-[11px] my-1.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                                <span class="text-gray-400 text-[10px] ml-1">(${item.code})</span>
                            </div>
                            <div class="font-heading font-extrabold text-base text-red-600 mt-1">
                                ${item.price}
                            </div>
                        </div>
                    </div>

                    <!-- Action Buttons -->
                    <div class="px-4 pb-4 pt-1 flex items-center gap-2">
                        <button onclick="openConsultModal('Báo giá: ${item.name}')" class="flex-1 bg-sauna-800 hover:bg-sauna-900 text-white font-heading font-bold text-xs py-2.5 rounded-xl transition flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-comment-dots text-amber-400"></i> Nhận Báo Giá
                        </button>
                        <button onclick="addToQuote('${item.id}')" title="Lưu vào giỏ báo giá" class="w-9 h-9 rounded-xl bg-sauna-50 hover:bg-sauna-100 text-sauna-800 border border-sauna-200 flex items-center justify-center transition">
                            <i class="fa-solid fa-plus text-xs"></i>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        function filterProducts(category) {
            renderProducts(category);
            document.querySelectorAll('.product-tab-btn').forEach(btn => {
                if (btn.dataset.tab === category) {
                    btn.className = 'product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-800 text-white shadow';
                } else {
                    btn.className = 'product-tab-btn px-4 py-2.5 rounded-full font-heading font-bold text-xs uppercase transition bg-sauna-50 text-sauna-900 hover:bg-sauna-100 border border-sauna-200';
                }
            });
        }

        // RENDER PROJECTS FROM FANPAGE
        function renderProjects(filter = 'all') {
            const grid = document.getElementById('projectsGrid');
            const filtered = filter === 'all' ? projectsData : projectsData.filter(p => p.category === filter);

            grid.innerHTML = filtered.map(proj => `
                <article onclick="openProjectDetail('${proj.id}')" class="group bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-xl border border-sauna-200/80 transition cursor-pointer flex flex-col justify-between">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="${proj.image}" 
                                 onerror="this.src='https://placehold.co/800x500/3b1c0c/facc15?text=CONG+TRINH+HOANG+GIA+HIEU'"
                                 alt="${proj.title}" 
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <!-- Flatsome Signature Date Box -->
                            <div class="flatsome-date-badge absolute top-3 left-3 rounded-xl shadow">
                                <span class="font-black text-base">${proj.day}</span>
                                <span class="text-[10px] font-bold uppercase">${proj.month}</span>
                            </div>
                            <span class="absolute bottom-3 right-3 bg-sauna-950/85 text-amber-300 text-[11px] font-semibold px-3 py-1 rounded-full backdrop-blur-sm">
                                <i class="fa-solid fa-location-dot mr-1"></i> ${proj.location}
                            </span>
                        </div>
                        <div class="p-5">
                            <span class="text-[11px] font-bold uppercase text-sauna-600">${proj.category}</span>
                            <h3 class="font-heading font-extrabold text-base text-sauna-950 group-hover:text-sauna-600 transition mt-1 mb-2 line-clamp-2">
                                ${proj.title}
                            </h3>
                            <p class="text-xs text-gray-600 line-clamp-2 leading-relaxed">
                                ${proj.summary}
                            </p>
                        </div>
                    </div>
                    <div class="px-5 pb-4 pt-2 border-t border-gray-100 flex items-center justify-between text-xs font-heading font-bold text-sauna-700">
                        <span>Xem chi tiết công trình</span>
                        <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition"></i>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(cat) {
            renderProjects(cat);
            document.querySelectorAll('.proj-tab-btn').forEach(btn => {
                if (btn.dataset.proj === cat) {
                    btn.className = 'proj-tab-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-sauna-800 text-white';
                } else {
                    btn.className = 'proj-tab-btn px-4 py-1.5 rounded-lg text-xs font-bold bg-white text-sauna-900 border border-sauna-200';
                }
            });
        }

        // RENDER BLOG POSTS
        function renderBlogs() {
            const grid = document.getElementById('blogGrid');
            grid.innerHTML = blogPosts.map(post => `
                <article onclick="openBlogDetail('${post.id}')" class="group bg-white rounded-2xl overflow-hidden shadow-sm hover:shadow-lg border border-sauna-100 transition cursor-pointer flex flex-col justify-between">
                    <div>
                        <div class="relative h-48 overflow-hidden">
                            <img src="${post.image}" alt="${post.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="flatsome-date-badge absolute top-3 left-3 rounded-xl shadow">
                                <span class="font-black text-base">${post.day}</span>
                                <span class="text-[10px] font-bold uppercase">${post.month}</span>
                            </div>
                        </div>
                        <div class="p-4">
                            <h3 class="font-heading font-bold text-sm text-sauna-950 group-hover:text-sauna-600 transition line-clamp-2 mb-2">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-gray-500 line-clamp-3 leading-relaxed">
                                ${post.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-4 pb-4 pt-1">
                        <span class="text-xs font-heading font-bold text-sauna-700 group-hover:underline">Đọc tiếp <i class="fa-solid fa-angle-right ml-1"></i></span>
                    </div>
                </article>
            `).join('');
        }

        // SAUNA CALCULATOR LOGIC
        function calculateSaunaEstimate() {
            const type = document.getElementById('calcRoomType').value;
            const mat = document.getElementById('calcMaterial').value;
            const l = parseFloat(document.getElementById('calcLength').value) || 1.5;
            const w = parseFloat(document.getElementById('calcWidth').value) || 1.4;
            const h = parseFloat(document.getElementById('calcHeight').value) || 2.1;

            const volume = (l * w * h).toFixed(2);
            let people = '1-2 người';
            if (volume >= 3.5 && volume <= 5.5) people = '2-4 người';
            else if (volume > 5.5 && volume <= 9) people = '4-6 người';
            else if (volume > 9) people = '6-10 người (Spa)';

            let power = 'Máy 4.5kW - 6kW';
            if (volume > 4 && volume <= 6.5) power = 'Máy 6kW - 9kW';
            else if (volume > 6.5 && volume <= 11) power = 'Máy 9kW - 12kW';
            else if (volume > 11) power = 'Máy 12kW - 18kW';

            let baseRate = 14.5; // million VND
            if (type === 'salt') baseRate = 18.5;
            if (type === 'wet') baseRate = 12.0;
            if (type === 'combo') baseRate = 26.0;

            let matMultiplier = 1;
            if (mat === 'premium') matMultiplier = 1.28;
            if (mat === 'luxury') matMultiplier = 1.65;

            const minPrice = ( (baseRate + (volume * 1.6)) * matMultiplier ).toFixed(1);
            const maxPrice = ( parseFloat(minPrice) + 4.8 ).toFixed(1);

            document.getElementById('resVolume').textContent = `${volume} m³ (${people})`;
            document.getElementById('resPower').textContent = power;
            document.getElementById('resPrice').textContent = `${minPrice} - ${maxPrice} Triệu`;
        }

        function sendEstimateToModal() {
            const vol = document.getElementById('resVolume').textContent;
            const pwr = document.getElementById('resPower').textContent;
            const prc = document.getElementById('resPrice').textContent;
            openConsultModal(`Báo giá phòng xông hơi kích thước ${vol}, ${pwr} (Dự toán: ${prc})`);
        }

        // QUICK VIEW & DETAIL MODALS
        function openQuickView(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;
            document.getElementById('qvImage').src = item.image;
            document.getElementById('qvCategory').textContent = item.categoryLabel;
            document.getElementById('qvName').textContent = item.name;
            document.getElementById('qvPrice').textContent = item.price;
            document.getElementById('qvDesc').textContent = item.desc;
            document.getElementById('qvSpecs').innerHTML = item.specs.map(s => `<div><i class="fa-solid fa-check text-sauna-600 mr-1.5"></i>${s}</div>`).join('');
            document.getElementById('qvAddQuoteBtn').onclick = () => {
                addToQuote(item.id);
                closeQuickView();
            };
            document.getElementById('quickViewModal').classList.remove('hidden');
        }

        function closeQuickView() {
            document.getElementById('quickViewModal').classList.add('hidden');
        }

        function openProjectDetail(id) {
            const proj = projectsData.find(p => p.id === id);
            if (!proj) return;
            document.getElementById('detailModalHeader').textContent = 'Công Trình Thực Tế Hoàng Gia Hiếu';
            document.getElementById('detailModalImg').src = proj.image;
            document.getElementById('detailModalBadge').textContent = proj.location;
            document.getElementById('detailModalTitle').textContent = proj.title;
            document.getElementById('detailModalContent').innerHTML = `<p>${proj.details}</p><p class="font-semibold text-sauna-800 mt-2">Quý khách cần tư vấn lắp đặt mẫu tương tự tại Đà Nẵng và miền Trung vui lòng liên hệ trực tiếp Hotline/Zalo: 0978.745.785 (Hiếu Nghĩa Sauna).</p>`;
            document.getElementById('detailModal').classList.remove('hidden');
        }

        function openBlogDetail(id) {
            const post = blogPosts.find(b => b.id === id);
            if (!post) return;
            document.getElementById('detailModalHeader').textContent = 'Cẩm Nang & Kiến Thức Xông Hơi';
            document.getElementById('detailModalImg').src = post.image;
            document.getElementById('detailModalBadge').textContent = `Ngày đăng: ${post.day} ${post.month}, 2026`;
            document.getElementById('detailModalTitle').textContent = post.title;
            document.getElementById('detailModalContent').innerHTML = `<p>${post.content}</p>`;
            document.getElementById('detailModal').classList.remove('hidden');
        }

        function openPolicyModal(title) {
            document.getElementById('detailModalHeader').textContent = 'Chính Sách Công Ty TNHH TMDV Hoàng Gia Hiếu';
            document.getElementById('detailModalImg').src = 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=800&q=80';
            document.getElementById('detailModalBadge').textContent = 'Cam kết chính hãng 100%';
            document.getElementById('detailModalTitle').textContent = title;
            document.getElementById('detailModalContent').innerHTML = `
                <p>• <strong>Bảo hành phần gỗ thi công:</strong> Từ 24 - 36 tháng đối với gỗ thông Phần Lan, gỗ Tuyết Tùng và gỗ Hinoki.</p>
                <p>• <strong>Bảo hành máy xông hơi:</strong> Từ 18 - 24 tháng tận nơi tại Đà Nẵng và các tỉnh lân cận.</p>
                <p>• <strong>Hỗ trợ kỹ thuật:</strong> Xử lý sự cố nhanh chóng trong vòng 2 - 4 giờ tại khu vực TP. Đà Nẵng (67 Phi Bình 7, P. Ngũ Hành Sơn).</p>
            `;
            document.getElementById('detailModal').classList.remove('hidden');
        }

        function closeDetailModal() {
            document.getElementById('detailModal').classList.add('hidden');
        }

        // QUOTE CART FUNCTIONS
        function addToQuote(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;
            if (!quoteCart.find(q => q.id === id)) {
                quoteCart.push(item);
            }
            updateQuoteUI();
            showToast(`Đã thêm "${item.name}" vào danh sách yêu cầu báo giá!`);
        }

        function removeFromQuote(id) {
            quoteCart = quoteCart.filter(q => q.id !== id);
            updateQuoteUI();
        }

        function updateQuoteUI() {
            document.getElementById('cartCountBadge').textContent = quoteCart.length;
            const list = document.getElementById('quoteItemsList');
            if (quoteCart.length === 0) {
                list.innerHTML = `<div class="text-center py-12 text-gray-400 text-xs">Chưa có sản phẩm nào trong danh sách báo giá. Hãy nhấn nút (+) trên sản phẩm bạn quan tâm!</div>`;
                return;
            }
            list.innerHTML = quoteCart.map(item => `
                <div class="flex items-center gap-3 p-3 rounded-xl bg-sauna-50 border border-sauna-200">
                    <img src="${item.image}" class="w-14 h-14 rounded-lg object-cover shrink-0">
                    <div class="flex-1 min-w-0">
                        <h4 class="font-heading font-bold text-xs text-sauna-950 truncate">${item.name}</h4>
                        <span class="text-xs font-bold text-red-600">${item.price}</span>
                    </div>
                    <button onclick="removeFromQuote('${item.id}')" class="text-gray-400 hover:text-red-600 p-1">
                        <i class="fa-solid fa-trash-can"></i>
                    </button>
                </div>
            `).join('');
        }

        function toggleQuoteDrawer() {
            updateQuoteUI();
            document.getElementById('quoteDrawer').classList.toggle('hidden');
        }

        function checkoutQuote() {
            const names = quoteCart.map(q => q.name).join('; ');
            toggleQuoteDrawer();
            openConsultModal(`Báo giá danh sách đã chọn: ${names}`);
        }

        // CONSULT & CONTACT FORM
        function openConsultModal(noteText) {
            document.getElementById('lien-he').scrollIntoView({ behavior: 'smooth' });
            const noteInput = document.getElementById('custNote');
            noteInput.value = noteText;
            noteInput.focus();
            showToast('Vui lòng nhập Số điện thoại để kỹ thuật Hoàng Gia Hiếu gọi lại báo giá ngay!');
        }

        function submitContactForm(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value;
            const phone = document.getElementById('custPhone').value;
            const service = document.getElementById('custService').value;
            showToast(`Cảm ơn ${name} (${phone})! Yêu cầu "${service}" đã được gửi tới Hotline 0978.745.785.`);
            e.target.reset();
        }

        // SEARCH FUNCTIONS
        function toggleSearchModal() {
            const modal = document.getElementById('searchModal');
            modal.classList.toggle('hidden');
            if (!modal.classList.contains('hidden')) {
                document.getElementById('modalSearchInput').focus();
                searchProductsModal('');
            }
        }

        function searchProductsModal(keyword) {
            const q = keyword.trim().toLowerCase();
            const matched = productsData.filter(p => p.name.toLowerCase().includes(q) || p.categoryLabel.toLowerCase().includes(q));
            const container = document.getElementById('modalSearchResults');
            container.innerHTML = matched.map(item => `
                <div onclick="toggleSearchModal(); openQuickView('${item.id}')" class="py-2.5 px-2 hover:bg-sauna-50 rounded-xl flex items-center justify-between cursor-pointer transition">
                    <div class="flex items-center gap-3">
                        <img src="${item.image}" class="w-12 h-12 rounded-lg object-cover">
                        <div>
                            <h4 class="font-heading font-bold text-xs text-sauna-950">${item.name}</h4>
                            <span class="text-[11px] text-gray-500">${item.categoryLabel}</span>
                        </div>
                    </div>
                    <span class="font-heading font-bold text-xs text-red-600 shrink-0">${item.price}</span>
                </div>
            `).join('');
        }

        function searchProductsByKeyword(keyword) {
            const q = keyword.trim().toLowerCase();
            if (!q) {
                renderProducts('all');
                return;
            }
            const grid = document.getElementById('productGrid');
            const filtered = productsData.filter(p => p.name.toLowerCase().includes(q) || p.desc.toLowerCase().includes(q));
            document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
            if (filtered.length > 0) {
                renderProducts('all');
            }
        }

        // CUSTOM LOGO UPLOADER (Allows user to upload exact Fanpage logo file anytime)
        function triggerLogoUpload() {
            document.getElementById('logoFileInput').click();
        }

        function handleCustomLogo(event) {
            const file = event.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(e) {
                const img = document.getElementById('customLogoImg');
                const svg = document.getElementById('defaultSvgLogo');
                img.src = e.target.result;
                img.classList.remove('hidden');
                svg.classList.add('hidden');
                showToast('Đã cập nhật Logo thương hiệu Hoàng Gia Hiếu thành công!');
            };
            reader.readAsDataURL(file);
        }

        // HERO SLIDER LOGIC
        let currentSlide = 0;
        function setHeroSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            slides.forEach((s, i) => {
                if (i === index) {
                    s.classList.remove('opacity-0', 'pointer-events-none', 'z-0');
                    s.classList.add('opacity-100', 'z-10');
                } else {
                    s.classList.remove('opacity-100', 'z-10');
                    s.classList.add('opacity-0', 'pointer-events-none', 'z-0');
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

        // INITIALIZE ON LOAD
        window.onload = function() {
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
