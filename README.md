<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Xông Hơi Miền Trung | Công Ty TNHH TMDV Hoàng Gia Hiếu - Sản Xuất & Lắp Đặt Phòng Xông Hơi Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU (xonghoimientrung.com) - Chuyên tư vấn, thiết kế, sản xuất và lắp đặt phòng xông hơi khô, ướt, đá muối Himalaya tại Đà Nẵng và miền Trung. Địa chỉ: 67 Phi Bình 7, P. Ngũ Hành Sơn, TP Đà Nẵng. Hotline: 0978.745.785">
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Montserrat & Inter (Chuẩn Flatsome Việt Hóa) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@600;700;800;900&display=swap" rel="stylesheet">
    
    <!-- Font Awesome 6 Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        sauna: {
                            50: '#fdf9f3',
                            100: '#f9efe0',
                            200: '#f2dcb8',
                            300: '#e8c188',
                            400: '#dc9f56',
                            500: '#d18332',
                            600: '#b86524',
                            700: '#964c1f',
                            800: '#6e3718',
                            900: '#4a2410',
                            950: '#2d1407',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn khung và ẩn mọi ký tự rác nếu nhúng trên GitHub Pages */
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
            color: #2d2d2d;
            background-color: #fcfaf7;
            -webkit-tap-highlight-color: transparent;
        }
        /* Phá khung hẹp mặc định của GitHub Pages Markdown nếu có */
        .markdown-body, .container-lg, .px-3.my-5 {
            max-width: 100% !important;
            width: 100% !important;
            margin: 0 !important;
            padding: 0 !important;
        }
        .markdown-body > h1:first-child,
        .markdown-body > p:first-child {
            display: none !important;
        }

        h1, h2, h3, h4, .font-flatsome {
            font-family: 'Montserrat', sans-serif;
        }

        /* Flatsome Section Title Divider (Chuẩn mẫu Đỉnh Gỗ Sauna) */
        .section-title-container {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
        }
        .section-title-container::before,
        .section-title-container::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e6dacb;
            max-width: 160px;
        }
        .section-title-main {
            padding: 0 0.85rem;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.02em;
            color: #4a2410;
            text-align: center;
        }

        /* Flatsome Product Card Hover */
        .flatsome-product-box {
            transition: all 0.28s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .flatsome-product-box:hover {
            transform: translateY(-4px);
            box-shadow: 0 14px 28px -6px rgba(74, 36, 16, 0.15);
        }
        .flatsome-product-box .quick-view-bar {
            transform: translateY(100%);
            transition: transform 0.25s ease-in-out;
        }
        .flatsome-product-box:hover .quick-view-bar {
            transform: translateY(0);
        }
        .flatsome-product-box .product-img {
            transition: transform 0.45s ease;
        }
        .flatsome-product-box:hover .product-img {
            transform: scale(1.06);
        }

        /* Flatsome Date Badge */
        .flatsome-date-badge {
            width: 46px;
            height: 50px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.96);
            border: 2px solid #b86524;
            color: #4a2410;
            font-family: 'Montserrat', sans-serif;
            line-height: 1.05;
            transition: all 0.25s ease;
        }
        .group:hover .flatsome-date-badge {
            background: #b86524;
            color: #ffffff;
        }

        /* Hiệu ứng rung chuông điện thoại */
        @keyframes phoneRing {
            0%, 50%, 100% { transform: rotate(0) scale(1); }
            10%, 30% { transform: rotate(-22deg) scale(1.05); }
            20%, 40% { transform: rotate(22deg) scale(1.05); }
        }
        .animate-phone-ring {
            animation: phoneRing 1.8s infinite ease-in-out;
        }

        /* Mega menu hover trên máy tính */
        .has-dropdown:hover .dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }

        /* Ẩn thanh cuộn ngang trên các tab danh mục mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased selection:bg-sauna-700 selection:text-white pb-16 md:pb-0">

    <!-- Script xử lý tức thời: Xóa mọi dòng chữ thừa "<!doctype html>" trên giao diện điện thoại nếu có -->
    <script>
        (function removeStrayDoctypeImmediately() {
            function cleanDOM() {
                const walker = document.createTreeWalker(document.body, NodeFilter.SHOW_TEXT, null, false);
                const toRemove = [];
                while (walker.nextNode()) {
                    const node = walker.currentNode;
                    if (node.nodeValue && node.nodeValue.toLowerCase().includes('<!doctype')) {
                        toRemove.push(node);
                    }
                }
                toRemove.forEach(n => n.parentNode && n.parentNode.removeChild(n));
                document.querySelectorAll('p, div, span, h1').forEach(el => {
                    if (el.children.length === 0) {
                        const txt = (el.textContent || '').trim().toLowerCase();
                        if (txt.includes('<!doctype html>') || txt === '<!doctype html>' || txt === 'xonghoimientrung') {
                            el.remove();
                        }
                    }
                });
            }
            cleanDOM();
            document.addEventListener('DOMContentLoaded', cleanDOM);
            window.addEventListener('load', cleanDOM);
        })();
    </script>

    <!-- ==================== 1. FLATSOME TOP BAR ==================== -->
    <div class="bg-sauna-950 text-sauna-100 text-[11px] sm:text-xs border-b border-sauna-800 w-full">
        <div class="max-w-7xl mx-auto px-3 sm:px-4 py-1.5 sm:py-2 flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 min-w-0">
                <span class="inline-flex items-center gap-1.5 font-bold text-amber-400 truncate">
                    <i class="fa-solid fa-medal text-[11px] shrink-0"></i>
                    <span class="truncate">CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU</span>
                </span>
                <span class="hidden xl:inline text-sauna-500">|</span>
                <span class="hidden xl:inline text-gray-300 truncate">Chuyên sản xuất & lắp đặt phòng xông hơi tại Đà Nẵng và lân cận</span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 text-[11px] shrink-0">
                <span class="hidden md:inline-flex items-center gap-1.5 text-gray-200">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    67 Phi Bình 7, P. Ngũ Hành Sơn, TP. Đà Nẵng
                </span>
                <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-amber-300 hover:text-white font-semibold transition">
                    <i class="fa-brands fa-facebook text-blue-400"></i>
                    <span>Fanpage Xông Hơi</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==================== 2. FLATSOME MAIN HEADER & STICKY MENU ==================== -->
    <header id="mainHeader" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-md border-b border-sauna-100 w-full">
        <div class="max-w-7xl mx-auto px-3 sm:px-4 py-2 sm:py-3 flex items-center justify-between gap-2 sm:gap-4">
            
            <!-- Brand Logo (Lấy trực tiếp ảnh đại diện Fanpage ID 100057133012799 + Fallback SVG sắc nét) -->
            <a href="#trang-chu" class="flex items-center gap-2.5 sm:gap-3 group min-w-0 flex-1 lg:flex-initial">
                <div class="w-11 h-11 sm:w-14 sm:h-14 rounded-xl bg-sauna-950 p-0.5 shadow-md border-2 border-amber-500 flex items-center justify-center relative overflow-hidden shrink-0 group-hover:scale-105 transition">
                    <img src="https://graph.facebook.com/100057133012799/picture?type=large&width=300&height=300" 
                         alt="Logo Công Ty TNHH TMDV Hoàng Gia Hiếu - Xông Hơi Miền Trung"
                         class="w-full h-full object-cover rounded-[10px]"
                         onerror="this.style.display='none'; document.getElementById('fallbackFanpageLogo').classList.remove('hidden');">
                    <svg id="fallbackFanpageLogo" viewBox="0 0 120 120" class="hidden w-full h-full">
                        <defs>
                            <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#fde047" />
                                <stop offset="50%" stop-color="#eab308" />
                                <stop offset="100%" stop-color="#ca8a04" />
                            </linearGradient>
                        </defs>
                        <rect width="120" height="120" rx="18" fill="#2d1407"/>
                        <polygon points="60,8 106,33 106,87 60,112 14,87 14,33" fill="#4a2410" stroke="url(#goldGrad)" stroke-width="3.5"/>
                        <path d="M30,52 L60,31 L90,52" fill="none" stroke="url(#goldGrad)" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M46,74 C43,66 49,61 46,53" fill="none" stroke="#38bdf8" stroke-width="3.2" stroke-linecap="round"/>
                        <path d="M60,76 C57,67 63,61 60,51" fill="none" stroke="url(#goldGrad)" stroke-width="3.8" stroke-linecap="round"/>
                        <path d="M74,74 C71,66 77,61 74,53" fill="none" stroke="#f97316" stroke-width="3.2" stroke-linecap="round"/>
                        <text x="60" y="93" text-anchor="middle" fill="url(#goldGrad)" font-family="Montserrat, sans-serif" font-weight="900" font-size="11.5">HOÀNG GIA HIẾU</text>
                        <text x="60" y="103" text-anchor="middle" fill="#fed7aa" font-family="Inter, sans-serif" font-weight="700" font-size="7">SAUNA & STEAM</text>
                    </svg>
                </div>
                <div class="min-w-0">
                    <div class="flex items-center gap-1.5">
                        <span class="font-heading font-black text-xs sm:text-base md:text-lg text-sauna-900 tracking-tight leading-tight truncate">HOÀNG GIA HIẾU</span>
                        <span class="hidden sm:inline-block bg-amber-100 text-sauna-800 text-[9px] font-extrabold px-2 py-0.5 rounded-full border border-amber-300 shrink-0">SAUNA & STEAM</span>
                    </div>
                    <p class="text-[10px] sm:text-xs font-bold text-sauna-600 truncate">xonghoimientrung.com</p>
                    <p class="text-[10px] text-gray-500 hidden xl:block truncate">Sản xuất & lắp đặt phòng xông hơi Đà Nẵng - Miền Trung</p>
                </div>
            </a>

            <!-- Desktop Navigation Menu (Chuẩn Flatsome Đỉnh Gỗ Sauna - Không có mục tính toán) -->
            <nav class="hidden lg:flex items-center gap-1 xl:gap-1.5 font-heading text-xs font-bold uppercase tracking-wide text-sauna-900 shrink-0">
                <a href="#trang-chu" class="px-3 py-2 rounded-lg text-sauna-700 bg-sauna-50 hover:bg-sauna-100 transition">Trang Chủ</a>
                <a href="#gioi-thieu" class="px-3 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Giới Thiệu</a>
                
                <!-- Dropdown Sản Phẩm -->
                <div class="relative has-dropdown">
                    <a href="#san-pham" class="px-3 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition inline-flex items-center gap-1">
                        Sản Phẩm <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                    </a>
                    <div class="dropdown-menu absolute left-1/2 -translate-x-1/2 top-full pt-2 w-[620px] z-50">
                        <div class="bg-white rounded-2xl shadow-2xl border border-sauna-200 p-5 grid grid-cols-3 gap-5 text-left normal-case font-sans">
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-800 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-house-fire text-amber-600"></i> Phòng Xông Hơi
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="selectCategoryAndScroll('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Khô (Sauna)</button></li>
                                    <li><button onclick="selectCategoryAndScroll('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Đá Muối Himalaya</button></li>
                                    <li><button onclick="selectCategoryAndScroll('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hơi Ướt (Steam)</button></li>
                                    <li><button onclick="selectCategoryAndScroll('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Khô Kết Hợp Ướt</button></li>
                                    <li><button onclick="selectCategoryAndScroll('phong-xong-hoi')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Phòng Xông Hồng Ngoại</button></li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-800 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-fire-burner text-amber-600"></i> Máy Xông Hơi
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="selectCategoryAndScroll('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Khô HARVIA Phần Lan</button></li>
                                    <li><button onclick="selectCategoryAndScroll('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Khô SAWO / COAST</button></li>
                                    <li><button onclick="selectCategoryAndScroll('may-xong-kho')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Khô AMAZON</button></li>
                                    <li><button onclick="selectCategoryAndScroll('may-xong-uot')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Ướt COAST Cao Cấp</button></li>
                                    <li><button onclick="selectCategoryAndScroll('may-xong-uot')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Máy Xông Ướt AMAZON / HARVIA</button></li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-heading font-bold text-xs uppercase text-sauna-800 border-b border-sauna-100 pb-2 mb-2.5 flex items-center gap-1.5">
                                    <i class="fa-solid fa-tree text-amber-600"></i> Gỗ & Phụ Kiện
                                </h4>
                                <ul class="space-y-2 text-xs text-gray-700 font-medium">
                                    <li><button onclick="selectCategoryAndScroll('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Gỗ Thông Phần Lan Nhập Khẩu</button></li>
                                    <li><button onclick="selectCategoryAndScroll('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Gỗ Tuyết Tùng & Hinoki Nhật</button></li>
                                    <li><button onclick="selectCategoryAndScroll('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Đá Muối Himalaya & Đá Sauna</button></li>
                                    <li><button onclick="selectCategoryAndScroll('go-phu-kien')" class="hover:text-sauna-600 flex items-center gap-1.5 text-left"><i class="fa-solid fa-angle-right text-amber-500"></i> Xô Gáo Gỗ, Đèn, Đồng Hồ Nhiệt</button></li>
                                    <li><button onclick="selectCategoryAndScroll('all')" class="text-sauna-700 font-bold hover:underline flex items-center gap-1.5 pt-1">Xem tất cả sản phẩm <i class="fa-solid fa-arrow-right"></i></button></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <a href="#cong-trinh" class="px-3 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Dự Án Thực Tế</a>
                <a href="#quy-trinh" class="px-3 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Quy Trình</a>
                <a href="#tin-tuc" class="px-3 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Tin Tức</a>
                <a href="#lien-he" class="px-3 py-2 rounded-lg hover:text-sauna-600 hover:bg-sauna-50 transition">Liên Hệ</a>
            </nav>

            <!-- Right Header Actions -->
            <div class="flex items-center gap-1.5 sm:gap-2 shrink-0">
                <!-- Search Button -->
                <button onclick="toggleSearchModal()" class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-sauna-50 hover:bg-sauna-100 text-sauna-800 flex items-center justify-center transition" title="Tìm kiếm sản phẩm">
                    <i class="fa-solid fa-magnifying-glass text-sm"></i>
                </button>

                <!-- Hotline Button -->
                <a href="tel:0978745785" class="hidden sm:inline-flex items-center gap-2 bg-gradient-to-r from-sauna-800 to-sauna-700 hover:from-sauna-900 hover:to-sauna-800 text-white px-3.5 py-2 rounded-full shadow-md hover:shadow-lg transition">
                    <span class="w-6 h-6 rounded-full bg-amber-400 text-sauna-950 flex items-center justify-center animate-phone-ring shrink-0">
                        <i class="fa-solid fa-phone-volume text-[11px]"></i>
                    </span>
                    <div class="text-left leading-tight">
                        <span class="block text-[9px] uppercase tracking-wider text-amber-200 font-semibold">Hotline / Zalo</span>
                        <span class="font-heading font-extrabold text-xs xl:text-sm">0978.745.785</span>
                    </div>
                </a>

                <!-- Mobile Hamburger Button -->
                <button onclick="toggleMobileMenu()" class="lg:hidden w-9 h-9 sm:w-10 sm:h-10 rounded-xl bg-sauna-900 text-white flex items-center justify-center shrink-0" aria-label="Menu">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu Drawer -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-sauna-100 px-4 pt-3 pb-5 shadow-2xl">
            <div class="mb-3">
                <div class="relative">
                    <input type="text" oninput="searchProductsInline(this.value)" placeholder="Tìm phòng xông hơi, máy Harvia, Coast..." class="w-full pl-9 pr-4 py-2.5 text-sm rounded-xl border border-sauna-200 focus:outline-none focus:border-sauna-600">
                    <i class="fa-solid fa-magnifying-glass absolute left-3 top-3 text-gray-400"></i>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-2 font-heading font-bold text-xs uppercase text-sauna-900">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg bg-sauna-50 text-sauna-700 flex items-center gap-2"><i class="fa-solid fa-house"></i> Trang Chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50 flex items-center gap-2"><i class="fa-solid fa-building"></i> Giới Thiệu</a>
                <a href="#san-pham" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50 flex items-center gap-2"><i class="fa-solid fa-cubes"></i> Sản Phẩm</a>
                <a href="#cong-trinh" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50 flex items-center gap-2"><i class="fa-solid fa-helmet-safety"></i> Dự Án Fanpage</a>
                <a href="#quy-trinh" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50 flex items-center gap-2"><i class="fa-solid fa-list-check"></i> Quy Trình</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2.5 rounded-lg hover:bg-sauna-50 flex items-center gap-2"><i class="fa-solid fa-newspaper"></i> Tin Tức</a>
                <a href="#lien-he" onclick="toggleMobileMenu()" class="col-span-2 p-2.5 rounded-lg bg-amber-50 text-sauna-900 border border-amber-200 flex items-center justify-center gap-2"><i class="fa-solid fa-headset text-sauna-700"></i> Liên Hệ & Bản Đồ Chỉ Đường</a>
            </div>
            <div class="mt-3 pt-3 border-t border-gray-100 flex flex-col gap-1 text-xs text-gray-600">
                <span><i class="fa-solid fa-location-dot text-sauna-600 mr-1.5"></i> 67 Phi Bình 7, P. Ngũ Hành Sơn, TP. Đà Nẵng</span>
                <div class="flex items-center justify-between pt-1">
                    <a href="tel:0978745785" class="font-bold text-red-600"><i class="fa-solid fa-phone mr-1"></i> 0978.745.785</a>
                    <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="font-bold text-blue-600"><i class="fa-brands fa-facebook mr-1"></i> Fanpage Hoàng Gia Hiếu</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==================== 3. FLATSOME HERO BANNER SLIDER ==================== -->
    <section id="trang-chu" class="relative bg-sauna-950 overflow-hidden w-full">
        <div id="heroSlidesContainer" class="relative w-full">
            
            <!-- Slide 1 -->
            <div class="hero-slide relative flex items-center min-h-[430px] sm:min-h-[520px] lg:min-h-[580px]">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x800/3b1c0c/facc15?text=XONG+HOI+MIEN+TRUNG+-+HOANG+GIA+HIEU'"
                     alt="Xưởng sản xuất và thi công phòng xông hơi Đà Nẵng Hoàng Gia Hiếu" 
                     class="absolute inset-0 w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-sauna-950/95 via-sauna-950/85 to-sauna-950/45"></div>
                
                <div class="relative max-w-7xl mx-auto px-4 py-8 sm:py-14 lg:py-16 w-full grid lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-7 text-white space-y-3.5 sm:space-y-5">
                        <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 px-3 py-1 rounded-full text-[11px] sm:text-xs font-bold uppercase tracking-wider">
                            <i class="fa-solid fa-crown text-amber-400"></i> Xưởng Sản Xuất & Thi Công Trực Tiếp Giá Gốc
                        </div>
                        <h1 class="font-heading font-black text-xl sm:text-4xl lg:text-5xl leading-tight">
                            CÔNG TY TNHH TM DV <span class="text-amber-400">HOÀNG GIA HIẾU</span>
                            <span class="block text-base sm:text-2xl lg:text-3xl font-bold text-sauna-200 mt-1.5 sm:mt-2">
                                Chuyên Sản Xuất & Lắp Đặt Phòng Xông Hơi Tại Đà Nẵng & Lân Cận
                            </span>
                        </h1>
                        <p class="text-gray-200 text-xs sm:text-base leading-relaxed max-w-2xl">
                            Trực tiếp nhập khẩu thiết bị & gia công đóng mới <strong>Phòng Xông Hơi Khô Gỗ Thông Phần Lan, Phòng Xông Hơi Đá Muối Himalaya, Phòng Xông Hơi Ướt Kính Cường Lực</strong> cho Gia đình, Spa, Khách sạn, Resort tại Đà Nẵng, Quảng Nam, Hội An, Huế, Quảng Ngãi.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-2 pt-1 text-[11px] sm:text-xs">
                            <div class="flex items-center gap-1.5 bg-white/10 backdrop-blur-sm px-2.5 py-2 rounded-xl border border-white/15">
                                <i class="fa-solid fa-circle-check text-amber-400 shrink-0"></i>
                                <span>Sản xuất tại xưởng Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-1.5 bg-white/10 backdrop-blur-sm px-2.5 py-2 rounded-xl border border-white/15">
                                <i class="fa-solid fa-circle-check text-amber-400 shrink-0"></i>
                                <span>Gỗ Thông Phần Lan loại 1</span>
                            </div>
                            <div class="flex items-center gap-1.5 bg-white/10 backdrop-blur-sm px-2.5 py-2 rounded-xl border border-white/15 col-span-2 sm:col-span-1">
                                <i class="fa-solid fa-circle-check text-amber-400 shrink-0"></i>
                                <span>Khảo sát & Lắp đặt tận nơi</span>
                            </div>
                        </div>
                        <div class="flex flex-wrap items-center gap-2.5 sm:gap-3 pt-2 pb-4 sm:pb-0">
                            <a href="tel:0978745785" class="w-full sm:w-auto justify-center inline-flex items-center gap-2 bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-extrabold text-xs sm:text-sm px-5 py-3 sm:py-3.5 rounded-xl shadow-lg transition">
                                <i class="fa-solid fa-phone-volume"></i> GỌI BÁO GIÁ: 0978.745.785
                            </a>
                            <a href="#san-pham" class="w-full sm:w-auto justify-center inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/30 font-heading font-bold text-xs sm:text-sm px-5 py-3 sm:py-3.5 rounded-xl backdrop-blur-sm transition">
                                <i class="fa-solid fa-cubes text-amber-400"></i> Xem Kệ Sản Phẩm
                            </a>
                        </div>
                    </div>

                    <!-- Card thông tin Fanpage trên Desktop -->
                    <div class="lg:col-span-5 hidden lg:block">
                        <div class="bg-white/95 backdrop-blur-md rounded-2xl p-6 shadow-2xl border-2 border-amber-400/70 text-gray-800">
                            <div class="flex items-center gap-3.5 pb-4 border-b border-gray-200">
                                <img src="https://graph.facebook.com/100057133012799/picture?type=large&width=200&height=200" 
                                     alt="Fanpage Hoàng Gia Hiếu" 
                                     class="w-14 h-14 rounded-xl object-cover border-2 border-sauna-700 shrink-0"
                                     onerror="this.src='https://placehold.co/120x120/4a2410/facc15?text=HGH'">
                                <div>
                                    <span class="text-[11px] font-bold uppercase text-sauna-600 tracking-wider">Thông Tin Doanh Nghiệp</span>
                                    <h3 class="font-heading font-extrabold text-base text-sauna-950">CÔNG TY TNHH TMDV HOÀNG GIA HIẾU</h3>
                                    <p class="text-xs text-gray-500">Website: <strong class="text-sauna-700">xonghoimientrung.com</strong></p>
                                </div>
                            </div>
                            <ul class="space-y-2.5 my-4 text-xs sm:text-sm">
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-screwdriver-wrench text-sauna-600 mt-1 w-4"></i>
                                    <span><strong>Lĩnh vực:</strong> Sản xuất & lắp đặt phòng xông hơi khô, ướt, đá muối tại Đà Nẵng và lân cận</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-location-dot text-sauna-600 mt-1 w-4"></i>
                                    <span><strong>Địa chỉ:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-sauna-600 mt-1 w-4"></i>
                                    <span><strong>Hotline / Zalo 24/7:</strong> <a href="tel:0978745785" class="text-red-600 font-extrabold">0978.745.785</a></span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-brands fa-facebook text-blue-600 mt-1 w-4"></i>
                                    <span><strong>Fanpage chính thức:</strong> <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:underline font-semibold">Xem hình ảnh thực tế trên Facebook</a></span>
                                </li>
                            </ul>
                            <div class="bg-amber-50 p-3 rounded-xl border border-amber-200 text-xs text-sauna-900 mb-4">
                                <i class="fa-solid fa-gift text-amber-600 mr-1"></i>
                                <strong>Quà tặng trọn gói:</strong> Tặng bộ phụ kiện xông hơi cao cấp (Xô gáo gỗ thông, đá sauna, đồng hồ đo nhiệt ẩm, đèn chống nổ, khung bao máy) khi lắp đặt phòng xông!
                            </div>
                            <button onclick="openConsultModal('Tư vấn & khảo sát lắp đặt phòng xông hơi tận nơi')" class="w-full bg-sauna-800 hover:bg-sauna-950 text-white font-heading font-bold py-3 rounded-xl shadow transition flex items-center justify-center gap-2 text-sm">
                                <i class="fa-solid fa-paper-plane text-amber-400"></i> Đăng Ký Khảo Sát & Báo Giá Tận Nơi
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2 -->
            <div class="hero-slide hidden items-center min-h-[430px] sm:min-h-[520px] lg:min-h-[580px]">
                <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x800/4a2410/facc15?text=PHONG+XONG+HOI+DA+MUOI+DA+NANG'"
                     alt="Thi công phòng xông hơi đá muối Himalaya tại Đà Nẵng" 
                     class="absolute inset-0 w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-sauna-950/95 via-sauna-950/80 to-sauna-950/40"></div>
                <div class="relative max-w-7xl mx-auto px-4 py-8 sm:py-14 lg:py-16 w-full">
                    <div class="max-w-2xl text-white space-y-4">
                        <span class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/50 text-amber-300 px-3 py-1 rounded-full text-xs font-bold uppercase">
                            <i class="fa-solid fa-spa"></i> Chuẩn Thiết Kế Flatsome - Đỉnh Gỗ Sauna
                        </span>
                        <h2 class="font-heading font-black text-xl sm:text-4xl lg:text-5xl leading-tight">
                            PHÒNG XÔNG HƠI <span class="text-amber-400">GỖ THÔNG PHẦN LAN & ĐÁ MUỐI</span> BỀN ĐẸP TRỌN ĐỜI
                        </h2>
                        <p class="text-gray-200 text-xs sm:text-base leading-relaxed">
                            Đo đạc đóng mới theo mọi kích thước thực tế của ngôi nhà bạn (gầm cầu thang, phòng tắm master, sân thượng, phòng tập gym, spa thẩm mỹ).
                        </p>
                        <div class="flex flex-wrap gap-3 pt-2 pb-4 sm:pb-0">
                            <a href="#cong-trinh" class="w-full sm:w-auto text-center bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-extrabold text-xs sm:text-sm px-6 py-3.5 rounded-xl shadow-lg transition">
                                Xem Công Trình Đã Lắp Đặt
                            </a>
                            <a href="tel:0978745785" class="w-full sm:w-auto text-center bg-white/15 hover:bg-white/25 text-white border border-white/30 font-heading font-bold text-xs sm:text-sm px-6 py-3.5 rounded-xl transition">
                                Hotline: 0978.745.785
                            </a>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- Nút chuyển Slide -->
        <div class="absolute bottom-2.5 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button onclick="setHeroSlide(0)" id="slideDot0" class="w-8 h-2 rounded-full bg-amber-400 transition-all" aria-label="Slide 1"></button>
            <button onclick="setHeroSlide(1)" id="slideDot1" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Slide 2"></button>
        </div>
    </section>

    <!-- ==================== 4. FLATSOME 4 CAM KẾT VÀNG (MẪU ĐỈNH GỖ SAUNA) ==================== -->
    <section class="py-5 sm:py-7 bg-white border-b border-sauna-100">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <div class="flex flex-col sm:flex-row items-center text-center sm:text-left gap-2.5 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-sauna-50/70 border border-sauna-100">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-sauna-800 text-amber-400 flex items-center justify-center text-base sm:text-xl shrink-0">
                        <i class="fa-solid fa-industry"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950">Xưởng Sản Xuất Trực Tiếp</h3>
                        <p class="text-[11px] text-gray-600 mt-0.5">Giá gốc tại xưởng Đà Nẵng, không qua trung gian</p>
                    </div>
                </div>

                <div class="flex flex-col sm:flex-row items-center text-center sm:text-left gap-2.5 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-sauna-50/70 border border-sauna-100">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-sauna-800 text-amber-400 flex items-center justify-center text-base sm:text-xl shrink-0">
                        <i class="fa-solid fa-certificate"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950">Gỗ & Máy Nhập Khẩu</h3>
                        <p class="text-[11px] text-gray-600 mt-0.5">Thông Phần Lan, Harvia, Coast, Amazon chính hãng</p>
                    </div>
                </div>

                <div class="flex flex-col sm:flex-row items-center text-center sm:text-left gap-2.5 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-sauna-50/70 border border-sauna-100">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-sauna-800 text-amber-400 flex items-center justify-center text-base sm:text-xl shrink-0">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950">Lắp Đặt Nhanh Trong Ngày</h3>
                        <p class="text-[11px] text-gray-600 mt-0.5">Thi công trọn gói tại Đà Nẵng & các tỉnh lân cận</p>
                    </div>
                </div>

                <div class="flex flex-col sm:flex-row items-center text-center sm:text-left gap-2.5 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-sauna-50/70 border border-sauna-100">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-sauna-800 text-amber-400 flex items-center justify-center text-base sm:text-xl shrink-0">
                        <i class="fa-solid fa-shield-heart"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950">Bảo Hành Tận Nơi 24/7</h3>
                        <p class="text-[11px] text-gray-600 mt-0.5">Bảo hành phần gỗ tới 5 năm, máy xông 24-36 tháng</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== 5. DANH MỤC SẢN PHẨM & BÁO GIÁ (2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH) ==================== -->
    <section id="san-pham" class="py-10 sm:py-14 bg-[#fcfaf7]">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            
            <!-- Flatsome Section Header -->
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl md:text-3xl">
                    SẢN PHẨM PHÒNG XÔNG HƠI & THIẾT BỊ CHÍNH HÃNG
                </h2>
            </div>
            <p class="text-center text-gray-600 text-xs sm:text-sm max-w-2xl mx-auto -mt-3 mb-6">
                Tổng hợp các mẫu <strong>Phòng Xông Hơi Khô, Phòng Xông Hơi Ướt, Phòng Xông Đá Muối, Máy Xông Hơi & Phụ Kiện</strong> được Công Ty TNHH TMDV Hoàng Gia Hiếu trực tiếp sản xuất và lắp đặt.
            </p>

            <!-- Bộ lọc Danh Mục chuẩn Flatsome -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2.5 mb-6 sm:mb-8" id="productTabs">
                <button onclick="filterProducts('all')" data-tab="all" class="product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-800 text-white shadow">
                    Tất Cả (12)
                </button>
                <button onclick="filterProducts('phong-xong-hoi')" data-tab="phong-xong-hoi" class="product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-white text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Phòng Xông Hơi
                </button>
                <button onclick="filterProducts('may-xong-kho')" data-tab="may-xong-kho" class="product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-white text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Máy Xông Hơi Khô
                </button>
                <button onclick="filterProducts('may-xong-uot')" data-tab="may-xong-uot" class="product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-white text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Máy Xông Hơi Ướt
                </button>
                <button onclick="filterProducts('go-phu-kien')" data-tab="go-phu-kien" class="product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-white text-sauna-900 hover:bg-sauna-100 border border-sauna-200">
                    Gỗ & Phụ Kiện
                </button>
            </div>

            <!-- LƯỚI SẢN PHẨM: 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2), 3 CỘT TABLET (md:grid-cols-3), 4 CỘT MÁY TÍNH (lg:grid-cols-4) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-5">
                <!-- Được render tự động bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- ==================== 6. KỆ PHÂN LOẠI THEO MẪU DINHGOSAUNA.VN (BANNER + SẢN PHẨM) ==================== -->
    <section class="py-8 sm:py-12 bg-white border-t border-b border-sauna-100">
        <div class="max-w-7xl mx-auto px-3 sm:px-4 space-y-10">
            
            <!-- Khối 1: Chuyên Đề Phòng Xông Hơi Đóng Theo Kích Thước -->
            <div class="grid lg:grid-cols-12 gap-5 items-stretch">
                <div class="lg:col-span-4 rounded-2xl overflow-hidden relative min-h-[260px] flex flex-col justify-end p-5 sm:p-6 text-white shadow-lg">
                    <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=900&q=80" alt="Đóng phòng xông hơi theo yêu cầu Đà Nẵng" class="absolute inset-0 w-full h-full object-cover">
                    <div class="absolute inset-0 bg-gradient-to-t from-sauna-950 via-sauna-950/70 to-transparent"></div>
                    <div class="relative z-10 space-y-2.5">
                        <span class="bg-amber-400 text-sauna-950 text-[10px] font-heading font-extrabold px-2.5 py-1 rounded uppercase">Thế Mạnh Chủ Lực</span>
                        <h3 class="font-heading font-black text-lg sm:text-xl leading-snug">THIẾT KẾ & SẢN XUẤT PHÒNG XÔNG HƠI THEO KÍCH THƯỚC</h3>
                        <p class="text-xs text-gray-200 leading-relaxed">
                            Đo đạc tận nhà tại Đà Nẵng, Hội An, Quảng Nam, Huế. Tận dụng tối đa góc phòng tắm, gầm cầu thang, sân thượng với độ thẩm mỹ cao nhất.
                        </p>
                        <a href="tel:0978745785" class="inline-flex items-center gap-2 bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-bold text-xs px-4 py-2.5 rounded-xl transition">
                            <i class="fa-solid fa-phone-volume"></i> Gọi Kỹ Thuật: 0978.745.785
                        </a>
                    </div>
                </div>

                <!-- 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div id="customSaunaShowcase" class="lg:col-span-8 grid grid-cols-2 sm:grid-cols-3 gap-2.5 sm:gap-4">
                    <!-- Populated by JS -->
                </div>
            </div>

        </div>
    </section>

    <!-- ==================== 7. DỰ ÁN & CÔNG TRÌNH THỰC TẾ TRÊN FANPAGE ==================== -->
    <section id="cong-trinh" class="py-10 sm:py-14 bg-[#fcfaf7]">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl md:text-3xl">
                    DỰ ÁN & CÔNG TRÌNH THỰC TẾ TRÊN FANPAGE
                </h2>
            </div>
            <p class="text-center text-gray-600 text-xs sm:text-sm max-w-2xl mx-auto -mt-3 mb-6">
                Hình ảnh bàn giao thực tế các công trình <strong>Phòng Xông Hơi Khô, Ướt, Đá Muối Himalaya</strong> do đội ngũ kỹ thuật <strong>Công Ty TNHH TMDV Hoàng Gia Hiếu</strong> trực tiếp thi công tại Đà Nẵng và miền Trung.
            </p>

            <!-- Bộ lọc Công Trình -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
                <button onclick="filterProjects('all')" data-proj="all" class="proj-tab-btn px-3.5 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase bg-sauna-800 text-white shadow transition">
                    Tất Cả Công Trình
                </button>
                <button onclick="filterProjects('gia-dinh')" data-proj="gia-dinh" class="proj-tab-btn px-3.5 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase bg-white text-sauna-900 border border-sauna-200 hover:bg-sauna-100 transition">
                    Phòng Xông Gia Đình & Biệt Thự
                </button>
                <button onclick="filterProjects('spa-hotel')" data-proj="spa-hotel" class="proj-tab-btn px-3.5 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase bg-white text-sauna-900 border border-sauna-200 hover:bg-sauna-100 transition">
                    Spa, Gym, Khách Sạn & Resort
                </button>
            </div>

            <!-- Lưới Công Trình: 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div id="projectGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-2.5 sm:gap-6">
                <!-- Populated by JS -->
            </div>

            <div class="mt-8 text-center">
                <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white font-heading font-bold text-xs sm:text-sm px-6 py-3.5 rounded-xl shadow-md transition">
                    <i class="fa-brands fa-facebook text-base"></i> Xem Thêm Hàng Trăm Công Trình Trên Fanpage Facebook
                </a>
            </div>
        </div>
    </section>

    <!-- ==================== 8. GIỚI THIỆU CÔNG TY TNHH TMDV HOÀNG GIA HIẾU ==================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-sauna-950 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-3 sm:px-4 relative z-10">
            <div class="grid lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-6 space-y-4">
                    <span class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 text-amber-300 px-3 py-1 rounded-full text-xs font-bold uppercase">
                        <i class="fa-solid fa-building-circle-check"></i> Về Chúng Tôi - xonghoimientrung.com
                    </span>
                    <h2 class="font-heading font-black text-xl sm:text-3xl lg:text-4xl leading-tight">
                        CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ <span class="text-amber-400">HOÀNG GIA HIẾU</span>
                    </h2>
                    <p class="text-gray-200 text-xs sm:text-sm leading-relaxed">
                        Tọa lạc tại <strong>67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</strong>, <strong>Công Ty TNHH Thương Mại Dịch Vụ Hoàng Gia Hiếu</strong> (Thương hiệu <em>Hiếu Nghĩa Sauna & Steam - Xông Hơi Miền Trung</em>) là đơn vị uy tín chuyên sản xuất, phân phối vật tư và thi công lắp đặt trọn gói các hạng mục phòng xông hơi tại Đà Nẵng và khu vực miền Trung.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-3 pt-2 text-xs">
                        <div class="bg-white/10 p-3.5 rounded-xl border border-white/15">
                            <h3 class="font-heading font-bold text-amber-400 text-sm mb-1"><i class="fa-solid fa-check-double mr-1.5"></i> Xưởng Mộc Chuyên Dụng</h3>
                            <p class="text-gray-300 leading-relaxed">Gia công vách, trần, sàn và ghế ngồi bằng Gỗ Thông Phần Lan, Thông Mỹ, Tuyết Tùng đã qua xử lý chống cong vênh, mối mọt.</p>
                        </div>
                        <div class="bg-white/10 p-3.5 rounded-xl border border-white/15">
                            <h3 class="font-heading font-bold text-amber-400 text-sm mb-1"><i class="fa-solid fa-bolt mr-1.5"></i> An Toàn Điện Tuyệt Đối</h3>
                            <p class="text-gray-300 leading-relaxed">Lắp đặt tủ điện автомати (CB chống giật), dây cáp chịu nhiệt chuyên dụng và bảng điều khiển điện tử thông minh bên ngoài phòng.</p>
                        </div>
                    </div>

                    <!-- Thống kê năng lực -->
                    <div class="grid grid-cols-3 gap-2.5 pt-2 text-center">
                        <div class="bg-sauna-900/90 border border-amber-500/30 rounded-xl p-3">
                            <span class="block font-heading font-black text-xl sm:text-2xl text-amber-400">500+</span>
                            <span class="text-[11px] text-gray-300">Phòng Xông Đã Lắp</span>
                        </div>
                        <div class="bg-sauna-900/90 border border-amber-500/30 rounded-xl p-3">
                            <span class="block font-heading font-black text-xl sm:text-2xl text-amber-400">100%</span>
                            <span class="text-[11px] text-gray-300">Gỗ & Máy Nhập Khẩu</span>
                        </div>
                        <div class="bg-sauna-900/90 border border-amber-500/30 rounded-xl p-3">
                            <span class="block font-heading font-black text-xl sm:text-2xl text-amber-400">24/7</span>
                            <span class="text-[11px] text-gray-300">Bảo Hành Tận Nhà</span>
                        </div>
                    </div>
                </div>

                <!-- Khung Hình Ảnh & Thông Tin Pháp Nhân -->
                <div class="lg:col-span-6">
                    <div class="bg-white rounded-2xl p-4 sm:p-6 text-gray-800 shadow-2xl border-2 border-amber-400">
                        <div class="grid grid-cols-2 gap-3 mb-4">
                            <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=600&q=80" alt="Thi công phòng xông hơi gỗ thông Đà Nẵng" class="rounded-xl h-36 sm:h-44 w-full object-cover">
                            <img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=600&q=80" alt="Phòng xông hơi đá muối Himalaya Hoàng Gia Hiếu" class="rounded-xl h-36 sm:h-44 w-full object-cover">
                        </div>
                        <div class="bg-sauna-50 rounded-xl p-4 border border-sauna-200 space-y-2 text-xs sm:text-sm">
                            <div class="font-heading font-extrabold text-sauna-900 text-sm sm:text-base uppercase">
                                HỒ SƠ LIÊN HỆ CHÍNH THỨC:
                            </div>
                            <p><strong>• Tên công ty:</strong> CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU</p>
                            <p><strong>• Website:</strong> <a href="https://xonghoimientrung.com" class="text-sauna-700 font-bold">xonghoimientrung.com</a></p>
                            <p><strong>• Địa chỉ:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</p>
                            <p><strong>• Điện thoại / Zalo:</strong> <a href="tel:0978745785" class="text-red-600 font-extrabold">0978.745.785</a></p>
                            <p><strong>• Khu vực phục vụ:</strong> TP. Đà Nẵng, Hội An, Quảng Nam, Thừa Thiên Huế, Quảng Ngãi, Quảng Trị & toàn miền Trung.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== 9. QUY TRÌNH 5 BƯỚC THI CÔNG TRỌN GÓI ==================== -->
    <section id="quy-trinh" class="py-10 sm:py-14 bg-white border-b border-sauna-100">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl md:text-3xl">
                    QUY TRÌNH SẢN XUẤT & LẮP ĐẶT PHÒNG XÔNG HƠI
                </h2>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4 mt-6">
                <div class="bg-sauna-50/80 rounded-2xl p-4 border border-sauna-200 text-center relative">
                    <span class="w-9 h-9 rounded-full bg-sauna-800 text-amber-400 font-heading font-black text-sm flex items-center justify-center mx-auto mb-2.5">01</span>
                    <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 mb-1">Khảo Sát Tận Nơi</h3>
                    <p class="text-[11px] text-gray-600 leading-relaxed">Kỹ thuật đến đo đạc mặt bằng thực tế và tư vấn vị trí chờ nguồn điện, cấp thoát nước miễn phí.</p>
                </div>

                <div class="bg-sauna-50/80 rounded-2xl p-4 border border-sauna-200 text-center relative">
                    <span class="w-9 h-9 rounded-full bg-sauna-800 text-amber-400 font-heading font-black text-sm flex items-center justify-center mx-auto mb-2.5">02</span>
                    <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 mb-1">Thiết Kế & Báo Giá</h3>
                    <p class="text-[11px] text-gray-600 leading-relaxed">Lên phương án bố trí băng ghế, chọn loại gỗ, công suất máy xông phù hợp và báo giá trọn gói không phát sinh.</p>
                </div>

                <div class="bg-sauna-50/80 rounded-2xl p-4 border border-sauna-200 text-center relative">
                    <span class="w-9 h-9 rounded-full bg-sauna-800 text-amber-400 font-heading font-black text-sm flex items-center justify-center mx-auto mb-2.5">03</span>
                    <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 mb-1">Gia Công Tại Xưởng</h3>
                    <p class="text-[11px] text-gray-600 leading-relaxed">Cắt ghép khung xương, vách gỗ thông Phần Lan, vách đá muối tại xưởng 67 Phi Bình 7, Đà Nẵng.</p>
                </div>

                <div class="bg-sauna-50/80 rounded-2xl p-4 border border-sauna-200 text-center relative">
                    <span class="w-9 h-9 rounded-full bg-sauna-800 text-amber-400 font-heading font-black text-sm flex items-center justify-center mx-auto mb-2.5">04</span>
                    <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 mb-1">Lắp Đặt Hoàn Thiện</h3>
                    <p class="text-[11px] text-gray-600 leading-relaxed">Lắp dựng hoàn chỉnh chỉ trong 1 ngày, đấu nối máy xông hơi, kính cường lực và kiểm tra nhiệt độ chuẩn.</p>
                </div>

                <div class="col-span-2 sm:col-span-1 bg-sauna-50/80 rounded-2xl p-4 border border-sauna-200 text-center relative">
                    <span class="w-9 h-9 rounded-full bg-sauna-800 text-amber-400 font-heading font-black text-sm flex items-center justify-center mx-auto mb-2.5">05</span>
                    <h3 class="font-heading font-bold text-xs sm:text-sm text-sauna-950 mb-1">Bàn Giao & Bảo Hành</h3>
                    <p class="text-[11px] text-gray-600 leading-relaxed">Hướng dẫn vận hành an toàn, nghiệm thu bàn giao và kích hoạt chế độ bảo hành tận nhà dài hạn.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== 10. TIN TỨC & CẨM NANG XÔNG HƠI (CHUẨN FLATSOME BLOG) ==================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-[#fcfaf7]">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="section-title-container">
                <h2 class="section-title-main text-lg sm:text-2xl md:text-3xl">
                    KINH NGHIỆM & CẨM NANG LẮP PHÒNG XÔNG HƠI
                </h2>
            </div>

            <div id="blogGrid" class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6 mt-6">
                <!-- Populated by JS -->
            </div>
        </div>
    </section>

    <!-- ==================== 11. LIÊN HỆ & BẢN ĐỒ ĐỊA CHỈ ==================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white border-t border-sauna-200">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid lg:grid-cols-12 gap-6 sm:gap-8 items-start">
                
                <!-- Cột Trái: Form Gửi Yêu Cầu Báo Giá -->
                <div class="lg:col-span-6 bg-sauna-50 rounded-2xl p-5 sm:p-7 border border-sauna-200 shadow-sm">
                    <span class="text-xs font-bold uppercase text-sauna-600 tracking-wider">Liên Hệ Trực Tiếp Xưởng Hoàng Gia Hiếu</span>
                    <h2 class="font-heading font-black text-xl sm:text-2xl text-sauna-950 mt-1 mb-2">
                        NHẬN TƯ VẤN & BÁO GIÁ LẮP ĐẶT TẬN NƠI
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-600 mb-5">
                        Quý khách để lại thông tin hoặc gọi trực tiếp Hotline/Zalo <strong>0978.745.785</strong>, kỹ thuật viên của Hoàng Gia Hiếu sẽ tư vấn kích thước và báo giá chi tiết ngay lập tức.
                    </p>

                    <form onsubmit="submitContactForm(event)" class="space-y-3.5">
                        <div class="grid sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-sauna-900 mb-1">Họ và tên quý khách *</label>
                                <input type="text" id="contactName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 rounded-xl border border-sauna-200 text-sm focus:outline-none focus:border-sauna-700 bg-white">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-sauna-900 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="contactPhone" required placeholder="Ví dụ: 0978745785" class="w-full px-3.5 py-2.5 rounded-xl border border-sauna-200 text-sm focus:outline-none focus:border-sauna-700 bg-white">
                            </div>
                        </div>
                        <div class="grid sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-sauna-900 mb-1">Hạng mục quan tâm</label>
                                <select id="contactService" class="w-full px-3.5 py-2.5 rounded-xl border border-sauna-200 text-sm focus:outline-none focus:border-sauna-700 bg-white">
                                    <option value="Phòng Xông Hơi Khô (Sauna)">Phòng Xông Hơi Khô (Sauna)</option>
                                    <option value="Phòng Xông Đá Muối Himalaya">Phòng Xông Đá Muối Himalaya</option>
                                    <option value="Phòng Xông Hơi Ướt (Steam)">Phòng Xông Hơi Ướt (Steam)</option>
                                    <option value="Phòng Xông Hơi Khô Kết Hợp Ướt">Phòng Xông Hơi Khô Kết Hợp Ướt</option>
                                    <option value="Mua Máy Xông Hơi / Gỗ / Phụ Kiện">Mua Máy Xông Hơi / Gỗ / Phụ Kiện</option>
                                    <option value="Sửa chữa & Bảo trì phòng xông hơi">Sửa chữa & Bảo trì phòng xông hơi</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-sauna-900 mb-1">Khu vực lắp đặt</label>
                                <input type="text" id="contactAddress" placeholder="Quận/Huyện tại Đà Nẵng, Quảng Nam, Huế..." class="w-full px-3.5 py-2.5 rounded-xl border border-sauna-200 text-sm focus:outline-none focus:border-sauna-700 bg-white">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-sauna-900 mb-1">Yêu cầu kích thước hoặc ghi chú thêm</label>
                            <textarea id="contactNote" rows="3" placeholder="Ví dụ: Cần làm phòng xông khô gia đình 2-3 người ngồi, kích thước khoảng 1.4m x 1.2m..." class="w-full px-3.5 py-2.5 rounded-xl border border-sauna-200 text-sm focus:outline-none focus:border-sauna-700 bg-white"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-sauna-800 hover:bg-sauna-950 text-white font-heading font-extrabold text-xs sm:text-sm py-3.5 rounded-xl shadow-lg transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane text-amber-400"></i> GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY
                        </button>
                    </form>
                </div>

                <!-- Cột Phải: Địa chỉ 67 Phi Bình 7 & Bản đồ Google Maps -->
                <div class="lg:col-span-6 space-y-4">
                    <div class="bg-sauna-900 text-white rounded-2xl p-5 sm:p-6 shadow-md">
                        <h3 class="font-heading font-extrabold text-base sm:text-lg text-amber-400 mb-3">
                            CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU
                        </h3>
                        <div class="space-y-2.5 text-xs sm:text-sm text-gray-200">
                            <p class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-amber-400 mt-1 w-4 shrink-0"></i>
                                <span><strong>Địa chỉ văn phòng & xưởng:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                            </p>
                            <p class="flex items-center gap-2.5">
                                <i class="fa-solid fa-phone-volume text-amber-400 w-4 shrink-0"></i>
                                <span><strong>Hotline / Zalo:</strong> <a href="tel:0978745785" class="text-amber-300 font-extrabold text-base">0978.745.785</a></span>
                            </p>
                            <p class="flex items-center gap-2.5">
                                <i class="fa-solid fa-globe text-amber-400 w-4 shrink-0"></i>
                                <span><strong>Website:</strong> xonghoimientrung.com</span>
                            </p>
                            <p class="flex items-center gap-2.5">
                                <i class="fa-brands fa-facebook text-amber-400 w-4 shrink-0"></i>
                                <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="text-amber-300 underline hover:text-white">Hiếu Nghĩa Sauna - Xông Hơi Đà Nẵng</a></span>
                            </p>
                        </div>
                    </div>

                    <!-- Google Map Embed: 67 Phi Bình 7, Ngũ Hành Sơn, Đà Nẵng -->
                    <div class="rounded-2xl overflow-hidden border-2 border-sauna-200 shadow-sm h-64 sm:h-72 bg-gray-100">
                        <iframe 
                            title="Bản đồ Công Ty TNHH TMDV Hoàng Gia Hiếu - 67 Phi Bình 7, Ngũ Hành Sơn, Đà Nẵng"
                            src="https://www.google.com/maps?q=67+Phi+Binh+7,+Ngu+Hanh+Son,+Da+Nang&output=embed" 
                            width="100%" 
                            height="100%" 
                            style="border:0;" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== 12. FLATSOME FOOTER ==================== -->
    <footer class="bg-sauna-950 text-gray-300 pt-10 pb-6 border-t-4 border-amber-500">
        <div class="max-w-7xl mx-auto px-3 sm:px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-sauna-800">
                
                <!-- Col 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <img src="https://graph.facebook.com/100057133012799/picture?type=large&width=200&height=200" 
                             alt="Logo Hoàng Gia Hiếu" 
                             class="w-12 h-12 rounded-xl object-cover border-2 border-amber-400 shrink-0"
                             onerror="this.style.display='none'">
                        <div>
                            <h3 class="font-heading font-black text-sm sm:text-base text-amber-400">CÔNG TY TNHH TMDV HOÀNG GIA HIẾU</h3>
                            <p class="text-xs text-sauna-200 font-semibold">xonghoimientrung.com • Chuyên Phòng Xông Hơi</p>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed">
                        Đơn vị chuyên tư vấn, thiết kế, sản xuất tại xưởng và lắp đặt trọn gói Phòng Xông Hơi Khô (Sauna), Phòng Xông Hơi Ướt (Steam), Phòng Xông Hơi Đá Muối Himalaya, phân phối Máy Xông Hơi chính hãng tại Đà Nẵng và các tỉnh lân cận.
                    </p>
                    <ul class="space-y-1.5 text-xs text-gray-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> 67 Phi Bình 7, Phường Ngũ Hành Sơn, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0978745785" class="text-amber-300 font-bold">0978.745.785</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> xonghoimientrung.com</li>
                    </ul>
                </div>

                <!-- Col 2: Danh mục sản phẩm -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="font-heading font-bold text-sm uppercase text-white border-b border-sauna-800 pb-2">Hạng Mục Sản Xuất & Lắp Đặt</h4>
                    <ul class="space-y-2 text-xs text-gray-300">
                        <li><a href="#san-pham" onclick="filterProducts('phong-xong-hoi')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thi công Phòng Xông Hơi Khô Gỗ Thông Phần Lan</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('phong-xong-hoi')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Thi công Phòng Xông Hơi Đá Muối Himalaya</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('phong-xong-hoi')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Lắp đặt Phòng Xông Hơi Ướt Kính Cường Lực</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('may-xong-kho')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Phân phối Máy Xông Hơi Harvia, Coast, Amazon, Sawo</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('go-phu-kien')" class="hover:text-amber-400 transition"><i class="fa-solid fa-angle-right text-amber-500 mr-1.5"></i> Cung cấp Gỗ Thông Nhập Khẩu & Phụ Kiện Xông Hơi</a></li>
                    </ul>
                </div>

                <!-- Col 3: Kết nối Fanpage -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white border-b border-sauna-800 pb-2">Kết Nối Fanpage</h4>
                    <div class="bg-sauna-900 p-3.5 rounded-xl border border-sauna-800 space-y-2.5">
                        <div class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-2xl text-blue-400"></i>
                            <div>
                                <div class="font-heading font-bold text-xs text-white">Hiếu Nghĩa Sauna & Steam</div>
                                <div class="text-[11px] text-gray-400">Cập nhật công trình mới mỗi ngày</div>
                            </div>
                        </div>
                        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="block w-full text-center bg-[#1877F2] hover:bg-blue-600 text-white font-heading font-bold text-xs py-2.5 rounded-lg transition">
                            Theo Dõi Trang Fanpage
                        </a>
                        <a href="https://zalo.me/0978745785" target="_blank" rel="noopener noreferrer" class="block w-full text-center bg-amber-500 hover:bg-amber-400 text-sauna-950 font-heading font-bold text-xs py-2.5 rounded-lg transition">
                            Nhắn Tin Zalo: 0978.745.785
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-[11px] text-gray-400 gap-2 text-center sm:text-left">
                <p>© 2026 Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ HOÀNG GIA HIẾU</strong> (xonghoimientrung.com).</p>
                <p>Địa chỉ: 67 Phi Bình 7, P. Ngũ Hành Sơn, TP. Đà Nẵng • Hotline: 0978.745.785</p>
            </div>
        </div>
    </footer>

    <!-- ==================== 13. NÚT LIÊN HỆ NỔI (DESKTOP & MOBILE CHUẨN FLATSOME) ==================== -->
    <!-- Trên Máy Tính -->
    <div class="hidden md:flex fixed left-4 bottom-5 z-40 flex-col gap-2.5">
        <a href="https://zalo.me/0978745785" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2.5 bg-blue-600 hover:bg-blue-700 text-white p-1.5 pr-4 rounded-full shadow-xl transition transform hover:scale-105">
            <span class="w-10 h-10 rounded-full bg-white text-blue-600 font-heading font-black text-xs flex items-center justify-center shrink-0">Zalo</span>
            <div class="leading-tight">
                <span class="block text-[10px] text-blue-100">Chat Zalo báo giá</span>
                <span class="font-heading font-extrabold text-xs">0978.745.785</span>
            </div>
        </a>
        <a href="tel:0978745785" class="flex items-center gap-2.5 bg-red-600 hover:bg-red-700 text-white p-1.5 pr-4 rounded-full shadow-xl transition transform hover:scale-105">
            <span class="w-10 h-10 rounded-full bg-amber-400 text-sauna-950 flex items-center justify-center shrink-0 animate-phone-ring">
                <i class="fa-solid fa-phone-volume text-base"></i>
            </span>
            <div class="leading-tight">
                <span class="block text-[10px] text-red-100">Hotline kỹ thuật 24/7</span>
                <span class="font-heading font-extrabold text-xs sm:text-sm">0978.745.785</span>
            </div>
        </a>
    </div>

    <div class="hidden md:flex fixed right-4 bottom-5 z-40 flex-col gap-2.5">
        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" title="Fanpage Hoàng Gia Hiếu" class="w-11 h-11 rounded-full bg-[#1877F2] hover:bg-blue-700 text-white shadow-lg flex items-center justify-center text-lg transition transform hover:scale-110">
            <i class="fa-brands fa-facebook-messenger"></i>
        </a>
        <button onclick="window.scrollTo({top:0, behavior:'smooth'})" title="Lên đầu trang" class="w-11 h-11 rounded-full bg-sauna-800 hover:bg-sauna-950 text-amber-400 shadow-lg flex items-center justify-center text-sm transition">
            <i class="fa-solid fa-chevron-up"></i>
        </button>
    </div>

    <!-- Trên Điện Thoại: Thanh Bottom Bar cố định gọn đẹp (Đã thay mục tính toán bằng Tư Vấn Báo Giá) -->
    <div class="md:hidden fixed bottom-0 inset-x-0 z-40 bg-white border-t border-sauna-200 shadow-[0_-4px_20px_rgba(0,0,0,0.12)] grid grid-cols-4 h-14">
        <a href="tel:0978745785" class="flex flex-col items-center justify-center text-red-600 active:bg-red-50">
            <i class="fa-solid fa-phone-volume text-base animate-phone-ring"></i>
            <span class="text-[10px] font-heading font-extrabold mt-0.5">0978.745.785</span>
        </a>
        <a href="https://zalo.me/0978745785" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-blue-600 active:bg-blue-50 border-l border-gray-100">
            <span class="font-heading font-black text-[10px] leading-none bg-blue-600 text-white px-1.5 py-0.5 rounded">Zalo</span>
            <span class="text-[10px] font-heading font-bold mt-0.5">Nhắn Zalo</span>
        </a>
        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-[#1877F2] active:bg-blue-50 border-l border-gray-100">
            <i class="fa-brands fa-facebook text-base"></i>
            <span class="text-[10px] font-heading font-bold mt-0.5">Fanpage</span>
        </a>
        <button onclick="openConsultModal('Yêu cầu tư vấn & báo giá lắp đặt phòng xông hơi')" class="flex flex-col items-center justify-center bg-sauna-800 text-amber-300 active:bg-sauna-950">
            <i class="fa-solid fa-comment-dots text-sm"></i>
            <span class="text-[10px] font-heading font-bold mt-0.5 text-white">Nhận Báo Giá</span>
        </button>
    </div>

    <!-- ==================== 14. MODALS (XEM NHANH SẢN PHẨM, TÌM KIẾM, ĐĂNG KÝ TƯ VẤN) ==================== -->
    <!-- Quick View Modal -->
    <div id="quickViewModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-sauna-200 max-h-[90vh] flex flex-col">
            <div class="flex items-center justify-between px-4 sm:px-6 py-3.5 bg-sauna-900 text-white">
                <h3 id="qvTitle" class="font-heading font-bold text-sm sm:text-base truncate pr-3">Chi tiết sản phẩm</h3>
                <button onclick="closeQuickView()" class="w-8 h-8 rounded-full bg-white/15 hover:bg-white/25 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="qvContent" class="p-4 sm:p-6 overflow-y-auto"></div>
        </div>
    </div>

    <!-- Consult Modal -->
    <div id="consultModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-md w-full overflow-hidden shadow-2xl border border-sauna-200">
            <div class="bg-sauna-900 text-white px-5 py-4 flex items-center justify-between">
                <div>
                    <span class="text-[10px] uppercase tracking-wider text-amber-300 font-bold">Hoàng Gia Hiếu Sauna & Steam</span>
                    <h3 class="font-heading font-extrabold text-base">YÊU CẦU BÁO GIÁ NHANH</h3>
                </div>
                <button onclick="closeConsultModal()" class="w-8 h-8 rounded-full bg-white/15 hover:bg-white/25 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <form onsubmit="submitModalForm(event)" class="p-5 space-y-3.5">
                <div class="bg-amber-50 border border-amber-200 rounded-xl p-3 text-xs text-sauna-900">
                    <strong>Sản phẩm / Dịch vụ:</strong> <span id="consultProductName" class="text-sauna-700 font-semibold">Tư vấn phòng xông hơi</span>
                </div>
                <div>
                    <label class="block text-xs font-bold text-gray-700 mb-1">Họ tên quý khách *</label>
                    <input type="text" id="modalCustName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-700">
                </div>
                <div>
                    <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
                    <input type="tel" id="modalCustPhone" required placeholder="Nhập số điện thoại..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-700">
                </div>
                <div>
                    <label class="block text-xs font-bold text-gray-700 mb-1">Địa chỉ lắp đặt (Đà Nẵng / Quảng Nam / Huế...)</label>
                    <input type="text" id="modalCustAddress" placeholder="Ví dụ: Ngũ Hành Sơn, Đà Nẵng" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 text-sm focus:outline-none focus:border-sauna-700">
                </div>
                <div class="pt-1 flex flex-col sm:flex-row gap-2">
                    <button type="submit" class="flex-1 bg-sauna-800 hover:bg-sauna-950 text-white font-heading font-bold text-xs sm:text-sm py-3 rounded-xl shadow transition">
                        <i class="fa-solid fa-paper-plane text-amber-400 mr-1"></i> Gửi Yêu Cầu
                    </button>
                    <a href="tel:0978745785" class="bg-red-600 hover:bg-red-700 text-white font-heading font-bold text-xs sm:text-sm py-3 px-4 rounded-xl shadow text-center transition">
                        <i class="fa-solid fa-phone mr-1"></i> Gọi 0978.745.785
                    </a>
                </div>
            </form>
        </div>
    </div>

    <!-- Search Modal -->
    <div id="searchModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-start justify-center pt-16 p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-xl w-full overflow-hidden shadow-2xl border border-sauna-200">
            <div class="p-4 border-b border-gray-100 flex items-center gap-2">
                <i class="fa-solid fa-magnifying-glass text-sauna-700"></i>
                <input type="text" id="modalSearchInput" oninput="searchProductsModal(this.value)" placeholder="Tìm phòng xông hơi, máy xông Harvia, Coast, đá muối..." class="w-full text-sm focus:outline-none">
                <button onclick="toggleSearchModal()" class="text-gray-400 hover:text-gray-700 px-2"><i class="fa-solid fa-xmark text-lg"></i></button>
            </div>
            <div id="modalSearchResults" class="max-h-80 overflow-y-auto p-3 divide-y divide-gray-100 text-xs">
                <p class="text-gray-500 text-center py-4">Nhập từ khóa để tìm nhanh sản phẩm...</p>
            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toastNotification" class="fixed top-20 right-4 z-50 hidden bg-sauna-950 text-white px-4 py-3 rounded-xl shadow-2xl border-l-4 border-amber-400 flex items-center gap-2.5 text-xs sm:text-sm max-w-sm">
        <i class="fa-solid fa-circle-check text-amber-400 text-base"></i>
        <span id="toastMessage">Đã gửi yêu cầu thành công!</span>
    </div>

    <!-- ==================== 15. JAVASCRIPT DỮ LIỆU SẢN PHẨM & DỰ ÁN FANPAGE ==================== -->
    <script>
        // Danh sách 12 Sản phẩm chủ lực lấy từ nội dung Fanpage Hoàng Gia Hiếu & mẫu Đỉnh Gỗ Sauna
        const productsData = [
            {
                id: 'sp-01',
                code: 'HGH-SAUNA-01',
                name: 'Phòng Xông Hơi Khô Gỗ Thông Phần Lan Đóng Theo Kích Thước',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Hơi Khô',
                price: 'Giá xưởng: 0978.745.785',
                badge: 'Bán Chạy #1',
                image: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Chất liệu: Gỗ Thông Phần Lan nhập khẩu tiêu chuẩn AA chống cong vênh',
                    'Máy xông hơi khô: Tùy chọn Amazon / Coast / Sawo / Harvia (4.5kW - 9kW)',
                    'Cửa kính cường lực 10mm chịu nhiệt, bản lề Inox 304 cao cấp',
                    'Tặng kèm trọn bộ phụ kiện: Xô gáo gỗ, đá sauna, đồng hồ nhiệt ẩm, đèn chống nổ'
                ]
            },
            {
                id: 'sp-02',
                code: 'HGH-DAMUOI-02',
                name: 'Phòng Xông Hơi Đá Muối Himalaya Kết Hợp Hồng Ngoại Cao Cấp',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Đá Muối',
                price: 'Báo giá: 0978.745.785',
                badge: 'Xu Hướng Spa',
                image: 'https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Vách đá muối Himalaya nguyên khối xuyên sáng 100% nhập khẩu Pakistan',
                    'Gỗ Thông Phần Lan hoặc Gỗ Tuyết Tùng (Cedar) thơm dịu tự nhiên',
                    'Hỗ trợ đào thải độc tố, giảm đau nhức xương khớp, giúp ngủ sâu giấc',
                    'Thi công trọn gói tại Đà Nẵng, Hội An, Quảng Nam, Huế, Quảng Ngãi'
                ]
            },
            {
                id: 'sp-03',
                code: 'HGH-STEAM-03',
                name: 'Phòng Xông Hơi Ướt Kính Cường Lực 10mm Gia Đình & Spa',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Hơi Ướt',
                price: 'Giá trọn gói: 0978.745.785',
                badge: 'Tiết Kiệm Diện Tích',
                image: 'https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Vách và trần kính cường lực 10mm kín hơi tuyệt đối, phụ kiện Inox 304',
                    'Trang bị máy xông hơi ướt Coast / Amazon / Harvia tạo hơi nhanh sau 3 phút',
                    'Tích hợp ghế ngồixếp gọn hoặc bệ ngồi ốp gạch mosaic sang trọng',
                    'Tặng hộp đựng thảo dược xông sả, gừng, tinh dầu thiên nhiên'
                ]
            },
            {
                id: 'sp-04',
                code: 'HGH-COMBO-04',
                name: 'Phòng Xông Hơi Khô Kết Hợp Ướt 2 Trong 1 Sang Trọng',
                category: 'phong-xong-hoi',
                categoryLabel: 'Phòng Xông Khô & Ướt',
                price: 'Liên hệ: 0978.745.785',
                badge: 'Đẳng Cấp Biệt Thự',
                image: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Thiết kế 2 buồng độc lập: 1 bên xông khô gỗ thông + 1 bên xông ướt kính cường lực',
                    'Phù hợp cho Biệt thự, Villa, Penthouse, Khách sạn tại Đà Nẵng & Hội An',
                    'Tủ điện điều khiển tự động chống rò điện an toàn tuyệt đối',
                    'Bảo hành tận nhà 24/7 bởi đội ngũ kỹ thuật Hoàng Gia Hiếu'
                ]
            },
            {
                id: 'sp-05',
                code: 'HARVIA-BC60',
                name: 'Máy Xông Hơi Khô HARVIA Phần Lan Chính Hãng (6kW - 9kW)',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                price: 'Giá ưu đãi: 0978.745.785',
                badge: 'Nhập Khẩu Phần Lan',
                image: 'https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Thương hiệu máy xông hơi số 1 thế giới HARVIA (Finland)',
                    'Vỏ thép không gỉ siêu bền, thanh điện trở đốt nóng cực nhanh và tiết kiệm điện',
                    'Đầy đủ công suất 4.5kW, 6kW, 8kW, 9kW, 12kW cho phòng gia đình đến Spa lớn',
                    'Lắp đặt tận nơi và bảo hành chính hãng 24 - 36 tháng'
                ]
            },
            {
                id: 'sp-06',
                code: 'COAST-CA60',
                name: 'Máy Xông Hơi Khô COAST Vỏ Inox Bảng Điều Khiển Điện Tử',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                price: 'Giá xưởng: 0978.745.785',
                badge: 'Siêu Bền Bỉ',
                image: 'https://images.unsplash.com/photo-1507652313519-d4e9174996dd?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Bảng điều khiển điện tử thông minh cài đặt nhiệt độ và thời gian tự ngắt',
                    'Thân vỏ Inox chống gỉ sét trong môi trường độ ẩm cao vùng biển Đà Nẵng',
                    'Khoang chứa đá sauna rộng giúp tỏa nhiệt đều khắp phòng xông',
                    'Tặng kèm đá sauna núi lửa chuyên dụng khi lắp máy'
                ]
            },
            {
                id: 'sp-07',
                code: 'AMAZON-AM60',
                name: 'Máy Xông Hơi Khô AMAZON Chính Hãng (4.5kW / 6kW / 9kW)',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                price: 'Giá tốt nhất: 0978.745.785',
                badge: 'Giá Tốt Nhất',
                image: 'https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Dòng máy xông hơi khô quốc dân được ưa chuộng nhất cho gia đình & phòng Gym',
                    'Hoạt động ổn định, linh kiện sẵn có, chi phí đầu tư hợp lý',
                    'Có bảng điều khiển rời lắp ngoài cửa phòng xông tiện lợi',
                    'Miễn phí giao hàng và khảo sát lắp đặt tại nội thành Đà Nẵng'
                ]
            },
            {
                id: 'sp-08',
                code: 'SAWO-SCA',
                name: 'Máy Xông Hơi Khô SAWO Vỏ Inox Gương Cao Cấp (6kW - 9kW)',
                category: 'may-xong-kho',
                categoryLabel: 'Máy Xông Hơi Khô',
                price: 'Liên hệ: 0978.745.785',
                badge: 'Chuẩn Châu Âu',
                image: 'https://images.unsplash.com/photo-1596178065887-1198b6148b2b?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Công nghệ Phần Lan, thiết kế vỏ Inox bóng gương sang trọng',
                    'Vận hành êm ái, giữ nhiệt lâu, độ bền lên đến hơn 10 năm sử dụng',
                    'Phù hợp cho phòng xông hơi gia đình cao cấp, Resort, Khách sạn 4-5 sao'
                ]
            },
            {
                id: 'sp-09',
                code: 'COAST-KSB60',
                name: 'Máy Xông Hơi Ướt COAST KSB Có Van Xả Cặn Tự Động',
                category: 'may-xong-uot',
                categoryLabel: 'Máy Xông Hơi Ướt',
                price: 'Báo giá: 0978.745.785',
                badge: 'Xả Cặn Tự Động',
                image: 'https://images.unsplash.com/photo-1584622781564-1d987f7333c1?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Tích hợp van xả cặn tự động thông minh sau mỗi lần xông, chống đóng cặn bình đun',
                    'Vỏ Inox 304 chống rỉ, bảng điều khiển điện tử hiển thị nhiệt độ chính xác',
                    'Đầy đủ công suất 6kW, 9kW, 12kW cho phòng tắm kính gia đình & Spa'
                ]
            },
            {
                id: 'sp-10',
                code: 'AMAZON-STEAM',
                name: 'Máy Xông Hơi Ướt AMAZON Chính Hãng Gia Đình & Spa',
                category: 'may-xong-uot',
                categoryLabel: 'Máy Xông Hơi Ướt',
                price: 'Giá xưởng: 0978.745.785',
                badge: 'Bán Chạy',
                image: 'https://images.unsplash.com/photo-1552321554-5fefe8c9ef14?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Tạo hơi nước mạnh mẽ chỉ sau 3-5 phút khởi động',
                    'Kết hợp hoàn hảo với hộp đựng thảo dược sả, chanh, ngải cứu, tinh dầu',
                    'Bảo hành tận nơi nhanh chóng tại Đà Nẵng & khu vực lân cận'
                ]
            },
            {
                id: 'sp-11',
                code: 'GO-THONG-PL',
                name: 'Gỗ Thông Phần Lan & Gỗ Tuyết Tùng Nhập Khẩu Đóng Phòng Xông',
                category: 'go-phu-kien',
                categoryLabel: 'Gỗ & Đá Muối',
                price: 'Giá sỉ tại xưởng: 0978.745.785',
                badge: 'Nhập Khẩu Chuẩn AA',
                image: 'https://images.unsplash.com/photo-1546484396-fb3fc6f95f98?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Gỗ Thông Phần Lan, Thông Mỹ không mắt, Gỗ Tuyết Tùng (Cedar) sấy khô tiêu chuẩn',
                    'Hương thơm tinh dầu thông tự nhiên dễ chịu khi gặp nhiệt độ cao',
                    'Cung cấp sỉ & lẻ vật tư gỗ xông hơi và đá muối Himalaya tại miền Trung'
                ]
            },
            {
                id: 'sp-12',
                code: 'COMBO-PK-06',
                name: 'Trọn Bộ Phụ Kiện Phòng Xông Hơi (Xô Gáo Gỗ, Đá Sauna, Đồng Hồ, Đèn)',
                category: 'go-phu-kien',
                categoryLabel: 'Phụ Kiện Xông Hơi',
                price: 'Trọn bộ ưu đãi: 0978.745.785',
                badge: 'Combo Đầy Đủ',
                image: 'https://images.unsplash.com/photo-1519823551278-64ac92734fb1?auto=format&fit=crop&w=700&q=80',
                specs: [
                    'Bao gồm: Xô gáo gỗ thông Phần Lan, Đá Sauna núi lửa, Đồng hồ nhiệt ẩm, Đồng hồ cát',
                    'Đèn chống nổ chịu nhiệt + khung gỗ che đèn + khung bao máy xông hơi',
                    'Hộp tạo hương thảo dược Inox và tinh dầu xông hơi thiên nhiên'
                ]
            }
        ];

        // Danh sách Dự Án & Công Trình thực tế từ Fanpage Hoàng Gia Hiếu
        const projectsData = [
            {
                id: 'du-an-1',
                category: 'gia-dinh',
                dateDay: '18',
                dateMonth: 'Th10',
                title: 'Lắp Đặt Phòng Xông Hơi Khô Đá Muối Gia Đình Tại Phường Ngũ Hành Sơn, Đà Nẵng',
                location: 'Ngũ Hành Sơn, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=800&q=80',
                summary: 'Hoàn thiện bàn giao phòng xông hơi khô gỗ thông Phần Lan kết hợp mảng tường đá muối Himalaya và máy xông hơi 6kW cho biệtự gia đình.'
            },
            {
                id: 'du-an-2',
                category: 'spa-hotel',
                dateDay: '12',
                dateMonth: 'Th10',
                title: 'Thi Công Hệ Thống Phòng Xông Khô & Ướt Cho Spa Thẩm Mỹ Tại Quận Sơn Trà, Đà Nẵng',
                location: 'Sơn Trà, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=800&q=80',
                summary: 'Thiết kế và thi công trọn gói cặp phòng xông hơi khô Sauna & phòng xông ướt Steam công suất 9kW phục vụ khách hàng Spa & Massage.'
            },
            {
                id: 'du-an-3',
                category: 'gia-dinh',
                dateDay: '05',
                dateMonth: 'Th10',
                title: 'Bàn Giao Phòng Xông Hơi Khô Kết Hợp Ướt 2 Trong 1 Tại Khu Đô Thị Hòa Xuân, Đà Nẵng',
                location: 'Cẩm Lệ, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80',
                summary: 'Mẫu phòng xông hơi đôi sang trọng đặt ngay trong phòng tắm Master, sử dụng gỗ thông Phần Lan không mắt và kính cường lực 10mm.'
            },
            {
                id: 'du-an-4',
                category: 'spa-hotel',
                dateDay: '26',
                dateMonth: 'Th09',
                title: 'Lắp Đặt Phòng Xông Hơi Gỗ Thông & Máy Harvia Cho Villa Nghỉ Dưỡng Tại Hội An',
                location: 'TP. Hội An, Quảng Nam',
                image: 'https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=800&q=80',
                summary: 'Thi công nhanh gọn trong ngày, đạt tiêu chuẩn thẩm mỹ và an toàn điện cho khu Villa du lịch nghỉ dưỡng cao cấp tại Hội An.'
            },
            {
                id: 'du-an-5',
                category: 'gia-dinh',
                dateDay: '19',
                dateMonth: 'Th09',
                title: 'Đóng Mới Phòng Xông Hơi Khô Tận Dụng Góc Phòng Tắm Tại Quận Hải Châu, Đà Nẵng',
                location: 'Hải Châu, TP. Đà Nẵng',
                image: 'https://images.unsplash.com/photo-1507652313519-d4e9174996dd?auto=format&fit=crop&w=800&q=80',
                summary: 'Giải pháp đóng phòng xông hơi theo kích thước thực tế 1.3m x 1.1m vừa vặn cho nhà phố hiện đại, đầy đủ phụ kiện xông hơi.'
            },
            {
                id: 'du-an-6',
                category: 'spa-hotel',
                dateDay: '10',
                dateMonth: 'Th09',
                title: 'Thi Công Tổ Hợp Phòng Xông Hơi Đá Muối Cho Phòng Tập Gym & Yoga Tại Huế',
                location: 'TP. Huế',
                image: 'https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&w=800&q=80',
                summary: 'Lắp đặt phòng xông hơi sức chứa 8-10 người sử dụng máy xông hơi công suất lớn 12kW kèm tủ điện tự động công nghiệp.'
            }
        ];

        // Dữ liệu bài viết Cẩm Nang
        const blogsData = [
            {
                title: 'Kinh Nghiệm Chọn Lắp Phòng Xông Hơi Gia Đình Tại Đà Nẵng Bền Đẹp, Tiết Kiệm Điện',
                date: '20/10/2026',
                excerpt: 'Hướng dẫn cách chọn kích thước phòng xông hơi khô và ướt phù hợp với số lượng thành viên gia đình từ 1-4 người, cách chờ dây nguồn và chọn công suất máy...',
                image: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=600&q=80'
            },
            {
                title: 'So Sánh Phòng Xông Hơi Khô (Sauna) Và Phòng Xông Hơi Ướt (Steam): Nên Lắp Loại Nào?',
                date: '14/10/2026',
                excerpt: 'Phân tích chi tiết ưu điểm của xông hơi khô bằng gỗ thông đá muối và xông hơi ướt bằng kính cường lực để gia chủ dễ dàng lựa chọn giải pháp tối ưu...',
                image: 'https://images.unsplash.com/photo-1515377905703-c4788e51af15?auto=format&fit=crop&w=600&q=80'
            },
            {
                title: 'Tại Sao Nên Chọn Đơn Vị Có Xưởng Sản Xuất Phòng Xông Hơi Trực Tiếp Tại Đà Nẵng?',
                date: '05/10/2026',
                excerpt: 'Đặt đóng phòng xông hơi trực tiếp tại xưởng Công Ty TNHH TMDV Hoàng Gia Hiếu (67 Phi Bình 7, Đà Nẵng) giúp tiết kiệm 20-30% chi phí và bảo hành tức thì...',
                image: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80'
            }
        ];

        // Render Lưới Sản Phẩm Chính (2 cột trên điện thoại, 3 cột tablet, 4 cột máy tính)
        function renderProducts(filter = 'all') {
            const grid = document.getElementById('productGrid');
            const list = filter === 'all' ? productsData : productsData.filter(p => p.category === filter);

            grid.innerHTML = list.map(item => `
                <div class="flatsome-product-box bg-white rounded-xl sm:rounded-2xl border border-sauna-200/90 overflow-hidden flex flex-col justify-between group h-full">
                    <div>
                        <div class="relative h-36 sm:h-52 overflow-hidden bg-sauna-50">
                            <img src="${item.image}" 
                                 onerror="this.src='https://placehold.co/600x450/4a2410/facc15?text=${encodeURIComponent(item.code)}'"
                                 alt="${item.name}" 
                                 class="product-img w-full h-full object-cover">
                            <span class="absolute top-2 left-2 sm:top-3 sm:left-3 bg-sauna-800/95 text-amber-300 text-[9px] sm:text-[10px] font-heading font-bold uppercase px-2 py-0.5 sm:px-2.5 sm:py-1 rounded shadow">
                                ${item.badge}
                            </span>
                            <button onclick="openQuickView('${item.id}')" class="quick-view-bar hidden sm:block absolute bottom-0 inset-x-0 bg-sauna-900/95 hover:bg-sauna-950 text-amber-300 font-heading font-bold text-xs uppercase py-2 text-center tracking-wider">
                                <i class="fa-regular fa-eye mr-1"></i> Xem Thông Số Kỹ Thuật
                            </button>
                        </div>

                        <div class="p-2.5 sm:p-4">
                            <span class="text-[9px] sm:text-[10px] font-bold uppercase tracking-wider text-sauna-600 block mb-0.5 truncate">${item.categoryLabel}</span>
                            <h3 onclick="openQuickView('${item.id}')" class="font-heading font-bold text-xs sm:text-sm text-sauna-950 hover:text-sauna-600 cursor-pointer line-clamp-2 h-8 sm:h-10 leading-4 sm:leading-5">
                                ${item.name}
                            </h3>
                            <div class="flex items-center gap-0.5 text-amber-400 text-[9px] sm:text-[11px] my-1">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                                <span class="text-gray-400 text-[9px] sm:text-[10px] ml-1 truncate">(${item.code})</span>
                            </div>
                            <div class="font-heading font-extrabold text-[11px] sm:text-sm text-red-600 mt-1 truncate">
                                ${item.price}
                            </div>
                        </div>
                    </div>

                    <div class="px-2.5 pb-2.5 sm:px-4 sm:pb-4 pt-1 flex items-center gap-1.5 sm:gap-2">
                        <button onclick="openConsultModal('${item.name}')" class="flex-1 bg-sauna-800 hover:bg-sauna-950 text-white font-heading font-bold text-[11px] sm:text-xs py-2 sm:py-2.5 px-2 rounded-lg sm:rounded-xl transition flex items-center justify-center gap-1">
                            <i class="fa-solid fa-phone-volume text-amber-400 text-[10px]"></i> <span>Báo Giá</span>
                        </button>
                        <button onclick="openQuickView('${item.id}')" title="Xem chi tiết" class="w-8 h-8 sm:w-9 sm:h-9 rounded-lg sm:rounded-xl bg-sauna-50 hover:bg-sauna-100 text-sauna-800 border border-sauna-200 flex items-center justify-center shrink-0 transition">
                            <i class="fa-regular fa-eye text-xs"></i>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        // Render Kệ Chuyên Đề Phòng Xông (3 mẫu nổi bật)
        function renderCustomSaunaShowcase() {
            const container = document.getElementById('customSaunaShowcase');
            const featured = productsData.slice(0, 3);
            container.innerHTML = featured.map((item, idx) => `
                <div class="${idx === 2 ? 'col-span-2 sm:col-span-1' : ''} flatsome-product-box bg-[#fcfaf7] rounded-xl sm:rounded-2xl border border-sauna-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="h-32 sm:h-40 overflow-hidden relative">
                            <img src="${item.image}" alt="${item.name}" class="product-img w-full h-full object-cover">
                            <span class="absolute top-2 left-2 bg-amber-400 text-sauna-950 text-[9px] font-heading font-extrabold px-2 py-0.5 rounded uppercase">${item.badge}</span>
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h4 onclick="openQuickView('${item.id}')" class="font-heading font-bold text-xs sm:text-sm text-sauna-950 hover:text-sauna-600 cursor-pointer line-clamp-2">${item.name}</h4>
                            <p class="text-[11px] sm:text-xs font-extrabold text-red-600 mt-1.5">${item.price}</p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5">
                        <button onclick="openConsultModal('${item.name}')" class="w-full bg-white hover:bg-sauna-800 text-sauna-900 hover:text-white border border-sauna-300 font-heading font-bold text-[11px] py-2 rounded-lg transition">
                            Nhận Báo Giá Xưởng
                        </button>
                    </div>
                </div>
            `).join('');
        }

        // Bộ lọc tab sản phẩm
        function filterProducts(category) {
            renderProducts(category);
            document.querySelectorAll('.product-tab-btn').forEach(btn => {
                if (btn.dataset.tab === category) {
                    btn.className = 'product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-sauna-800 text-white shadow';
                } else {
                    btn.className = 'product-tab-btn px-3 sm:px-4 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase transition bg-white text-sauna-900 hover:bg-sauna-100 border border-sauna-200';
                }
            });
        }

        function selectCategoryAndScroll(category) {
            filterProducts(category);
            document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        // Render Dự Án Thực Tế trên Fanpage
        function renderProjects(filter = 'all') {
            const grid = document.getElementById('projectGrid');
            const list = filter === 'all' ? projectsData : projectsData.filter(p => p.category === filter);

            grid.innerHTML = list.map(proj => `
                <div class="group bg-white rounded-xl sm:rounded-2xl border border-sauna-200 overflow-hidden shadow-sm hover:shadow-xl transition flex flex-col justify-between">
                    <div>
                        <div class="relative h-36 sm:h-52 overflow-hidden">
                            <img src="${proj.image}" alt="${proj.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="flatsome-date-badge absolute top-2.5 left-2.5 rounded-lg shadow">
                                <span class="font-extrabold text-xs sm:text-sm">${proj.dateDay}</span>
                                <span class="text-[9px] uppercase font-bold">${proj.dateMonth}</span>
                            </div>
                            <span class="absolute bottom-2 left-2 bg-sauna-950/85 text-amber-300 text-[9px] sm:text-[10px] font-semibold px-2 py-0.5 rounded">
                                <i class="fa-solid fa-location-dot mr-1"></i>${proj.location}
                            </span>
                        </div>
                        <div class="p-3 sm:p-4">
                            <h3 class="font-heading font-bold text-xs sm:text-base text-sauna-950 group-hover:text-sauna-600 line-clamp-2 leading-snug">
                                ${proj.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-gray-600 mt-1.5 line-clamp-2 hidden sm:block">
                                ${proj.summary}
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-gray-100 mt-1">
                        <button onclick="openConsultModal('Báo giá mẫu tương tự: ${proj.title}')" class="text-[11px] sm:text-xs font-heading font-bold text-sauna-700 hover:text-red-600 flex items-center gap-1">
                            <span>Báo giá mẫu này</span> <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                        <a href="https://www.facebook.com/profile.php?id=100057133012799" target="_blank" rel="noopener noreferrer" class="text-[11px] text-blue-600 hover:underline font-medium hidden sm:inline-flex items-center gap-1">
                            <i class="fa-brands fa-facebook"></i> Fanpage
                        </a>
                    </div>
                </div>
            `).join('');
        }

        function filterProjects(category) {
            renderProjects(category);
            document.querySelectorAll('.proj-tab-btn').forEach(btn => {
                if (btn.dataset.proj === category) {
                    btn.className = 'proj-tab-btn px-3.5 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase bg-sauna-800 text-white shadow transition';
                } else {
                    btn.className = 'proj-tab-btn px-3.5 py-2 rounded-full font-heading font-bold text-[11px] sm:text-xs uppercase bg-white text-sauna-900 border border-sauna-200 hover:bg-sauna-100 transition';
                }
            });
        }

        // Render Tin Tức
        function renderBlogs() {
            const grid = document.getElementById('blogGrid');
            grid.innerHTML = blogsData.map(b => `
                <article class="bg-white rounded-2xl border border-sauna-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="h-44 overflow-hidden">
                            <img src="${b.image}" alt="${b.title}" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-4">
                            <span class="text-[11px] text-sauna-600 font-semibold"><i class="fa-regular fa-calendar mr-1"></i>${b.date} • Cẩm Nang Xông Hơi</span>
                            <h3 class="font-heading font-bold text-sm sm:text-base text-sauna-950 mt-1 mb-2 leading-snug">${b.title}</h3>
                            <p class="text-xs text-gray-600 leading-relaxed line-clamp-3">${b.excerpt}</p>
                        </div>
                    </div>
                    <div class="px-4 pb-4">
                        <button onclick="openConsultModal('Tư vấn chi tiết: ${b.title}')" class="text-xs font-heading font-bold text-sauna-800 hover:text-sauna-600 inline-flex items-center gap-1.5">
                            Nhận tư vấn kỹ thuật <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        // Xem nhanh sản phẩm
        function openQuickView(productId) {
            const item = productsData.find(p => p.id === productId);
            if (!item) return;
            document.getElementById('qvTitle').textContent = item.name;
            document.getElementById('qvContent').innerHTML = `
                <div class="grid sm:grid-cols-12 gap-5 items-start">
                    <div class="sm:col-span-5">
                        <img src="${item.image}" alt="${item.name}" class="w-full h-52 sm:h-60 object-cover rounded-xl border border-sauna-200">
                    </div>
                    <div class="sm:col-span-7 space-y-3">
                        <span class="inline-block bg-amber-100 text-sauna-800 text-[10px] font-bold px-2.5 py-1 rounded-full uppercase">${item.categoryLabel} • Mã: ${item.code}</span>
                        <h4 class="font-heading font-extrabold text-base sm:text-lg text-sauna-950">${item.name}</h4>
                        <div class="text-base sm:text-lg font-heading font-black text-red-600">${item.price}</div>
                        <ul class="space-y-1.5 text-xs text-gray-700 bg-sauna-50 p-3.5 rounded-xl border border-sauna-200">
                            ${item.specs.map(s => `<li class="flex items-start gap-2"><i class="fa-solid fa-check text-sauna-700 mt-0.5"></i><span>${s}</span></li>`).join('')}
                        </ul>
                        <div class="text-xs text-gray-600">
                            <i class="fa-solid fa-location-dot text-sauna-700 mr-1"></i> Sản xuất & bảo hành bởi: <strong>CÔNG TY TNHH TMDV HOÀNG GIA HIẾU</strong> (67 Phi Bình 7, P. Ngũ Hành Sơn, TP Đà Nẵng)
                        </div>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <a href="tel:0978745785" class="flex-1 text-center bg-red-600 hover:bg-red-700 text-white font-heading font-bold text-xs py-3 px-4 rounded-xl shadow transition">
                                <i class="fa-solid fa-phone-volume mr-1"></i> Gọi Ngay: 0978.745.785
                            </a>
                            <button onclick="closeQuickView(); openConsultModal('${item.name}')" class="flex-1 bg-sauna-800 hover:bg-sauna-950 text-white font-heading font-bold text-xs py-3 px-4 rounded-xl shadow transition">
                                <i class="fa-solid fa-paper-plane text-amber-400 mr-1"></i> Yêu Cầu Báo Giá
                            </button>
                        </div>
                    </div>
                </div>
            `;
            document.getElementById('quickViewModal').classList.remove('hidden');
        }

        function closeQuickView() {
            document.getElementById('quickViewModal').classList.add('hidden');
        }

        // Modal Tư Vấn Báo Giá
        function openConsultModal(productTitle) {
            document.getElementById('consultProductName').textContent = productTitle || 'Tư vấn lắp đặt phòng xông hơi trọn gói';
            document.getElementById('consultModal').classList.remove('hidden');
        }

        function closeConsultModal() {
            document.getElementById('consultModal').classList.add('hidden');
        }

        function submitModalForm(e) {
            e.preventDefault();
            const name = document.getElementById('modalCustName').value;
            const phone = document.getElementById('modalCustPhone').value;
            closeConsultModal();
            showToast(`Cảm ơn anh/chị ${name}! Hoàng Gia Hiếu sẽ gọi lại số ${phone} ngay.`);
            e.target.reset();
        }

        function submitContactForm(e) {
            e.preventDefault();
            const name = document.getElementById('contactName').value;
            const phone = document.getElementById('contactPhone').value;
            showToast(`Đã nhận yêu cầu của ${name} (${phone}). Kỹ thuật Hoàng Gia Hiếu sẽ liên hệ ngay!`);
            e.target.reset();
        }

        // Tìm kiếm sản phẩm
        function toggleSearchModal() {
            const modal = document.getElementById('searchModal');
            modal.classList.toggle('hidden');
            if (!modal.classList.contains('hidden')) {
                setTimeout(() => document.getElementById('modalSearchInput').focus(), 100);
            }
        }

        function searchProductsModal(keyword) {
            const container = document.getElementById('modalSearchResults');
            const q = (keyword || '').trim().toLowerCase();
            if (!q) {
                container.innerHTML = '<p class="text-gray-500 text-center py-4">Nhập từ khóa để tìm nhanh sản phẩm...</p>';
                return;
            }
            const matched = productsData.filter(p => p.name.toLowerCase().includes(q) || p.categoryLabel.toLowerCase().includes(q) || p.code.toLowerCase().includes(q));
            if (matched.length === 0) {
                container.innerHTML = '<p class="text-gray-500 text-center py-4">Không tìm thấy sản phẩm khớp từ khóa. Gọi ngay 0978.745.785 để được tư vấn!</p>';
                return;
            }
            container.innerHTML = matched.map(item => `
                <div onclick="toggleSearchModal(); openQuickView('${item.id}')" class="flex items-center gap-3 p-2.5 hover:bg-sauna-50 rounded-xl cursor-pointer transition">
                    <img src="${item.image}" alt="${item.name}" class="w-12 h-12 rounded-lg object-cover shrink-0">
                    <div class="min-w-0 flex-1">
                        <div class="font-heading font-bold text-xs text-sauna-950 truncate">${item.name}</div>
                        <div class="text-[11px] text-red-600 font-bold">${item.price}</div>
                    </div>
                </div>
            `).join('');
        }

        function searchProductsInline(keyword) {
            const q = (keyword || '').trim().toLowerCase();
            const grid = document.getElementById('productGrid');
            const matched = !q ? productsData : productsData.filter(p => p.name.toLowerCase().includes(q) || p.categoryLabel.toLowerCase().includes(q));
            if (q && matched.length > 0) {
                document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
            }
            renderProducts('all');
        }

        // Hero Slider
        let currentSlide = 0;
        function setHeroSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            slides.forEach((s, i) => {
                if (i === index) {
                    s.classList.remove('hidden');
                    s.classList.add('flex');
                } else {
                    s.classList.remove('flex');
                    s.classList.add('hidden');
                }
            });
            document.getElementById('slideDot0').className = index === 0 ? 'w-8 h-2 rounded-full bg-amber-400 transition-all' : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
            document.getElementById('slideDot1').className = index === 1 ? 'w-8 h-2 rounded-full bg-amber-400 transition-all' : 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
            currentSlide = index;
        }

        function toggleMobileMenu() {
            document.getElementById('mobileMenu').classList.toggle('hidden');
        }

        function showToast(msg) {
            const toast = document.getElementById('toastNotification');
            document.getElementById('toastMessage').textContent = msg;
            toast.classList.remove('hidden');
            setTimeout(() => toast.classList.add('hidden'), 4200);
        }

        window.addEventListener('DOMContentLoaded', function() {
            renderProducts('all');
            renderCustomSaunaShowcase();
            renderProjects('all');
            renderBlogs();
            setInterval(() => {
                setHeroSlide((currentSlide + 1) % 2);
            }, 6500);
        });
    </script>
</body>
</html>
