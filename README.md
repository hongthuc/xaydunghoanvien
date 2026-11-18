<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN - Thiết Kế & Thi Công Xây Dựng Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN (xaydunghoanvien.com) chuyên Thiết kế - Thi công phần thô - Thi công hoàn thiện - Nội thất Khách sạn, Biệt thự, Nhà phố, Căn hộ, Văn phòng tại Hội An, Đà Nẵng. Hotline: 0769 444 556.">
    <meta name="keywords" content="Xây dựng Hoàn Viên, xaydunghoanvien.com, công ty xây dựng Đà Nẵng, xây nhà trọn gói Hội An Đà Nẵng, thi công phần thô Đà Nẵng, thiết kế kiến trúc nội thất">
    <link rel="canonical" href="https://xaydunghoanvien.com/">

    <!-- Thumbnail là ảnh Logo trang web khi gửi link chia sẻ (Open Graph & Zalo/Facebook/Twitter) -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="xaydunghoanvien.com">
    <meta property="og:url" content="https://xaydunghoanvien.com/">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN - xaydunghoanvien.com">
    <meta property="og:description" content="Chuyên Thiết Kế Kiến Trúc - Thi Công Xây Dựng Trọn Gói Khách Sạn, Biệt Thự, Nhà Phố, Căn Hộ, Văn Phòng tại Đà Nẵng. ĐC: 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng. ĐT: 0769 444 556">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN - xaydunghoanvien.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs">
    <link rel="image_src" href="https://lh3.googleusercontent.com/d/1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#0f3b68', // Xanh kiến trúc đậm theo tông chuẩn logo xây dựng
                            dark: '#092646',
                            light: '#195491',
                            accent: '#d97706',  // Vàng đồng / Cam xây dựng điểm nhấn
                            accentHover: '#b45309'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên cả điện thoại và máy tính */
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #f8fafc;
            color: #1e293b;
            box-sizing: border-box;
        }
        *, *::before, *::after {
            box-sizing: border-box;
        }

        /* Chuẩn khung giao diện 95% chiều ngang trên máy tính theo yêu cầu */
        .flatsome-container {
            width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu danh mục trên máy tính: từng tên danh mục viết liền trên 1 hàng, không xuống dòng giữa chừng */
        .desktop-nav-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
        }

        /* Tiêu đề section kiểu Flatsome UX Builder (Title Divided / Center) */
        .section-title-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin-bottom: 8px;
        }
        .section-title-line {
            height: 2px;
            flex: 1;
            max-width: 80px;
            background-color: #cbd5e1;
        }

        /* Hiệu ứng mượt cho ảnh sản phẩm / dự án Flatsome box */
        .ux-box-image {
            overflow: hidden;
            background-color: #e2e8f0;
        }
        .ux-box-image img {
            transition: transform 0.45s ease;
        }
        .ux-box:hover .ux-box-image img {
            transform: scale(1.05);
        }

        /* Nút liên hệ nổi có hiệu ứng sóng nhẹ không gây tràn màn hình */
        @keyframes pulse-ring {
            0% { box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.55); }
            70% { box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==========================================
         TOP BAR (Cấu trúc Flatsome Top Bar đơn giản)
         ========================================== -->
    <div id="top-bar" class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-building text-amber-400"></i>
                    <strong class="tracking-wide">CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN</strong>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-4 ml-auto">
                <a href="tel:0769444556" class="inline-flex items-center gap-1.5 hover:text-amber-300 transition">
                    <i class="fa-solid fa-phone-volume text-amber-400"></i>
                    <span>0769 444 556</span>
                </a>
                <span class="text-white/30">|</span>
                <a href="https://xaydunghoanvien.com" class="hidden sm:inline-flex items-center gap-1 hover:text-amber-300 transition">
                    <i class="fa-solid fa-globe text-amber-400"></i>
                    <span>xaydunghoanvien.com</span>
                </a>
                <a href="https://www.facebook.com/hoanvien.do" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 hover:text-amber-300 transition" title="Facebook Đỗ Hoàn Viên">
                    <i class="fa-brands fa-facebook text-amber-400"></i>
                    <span>Facebook</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Chuẩn Flatsome Header - Không để nút Gọi ngay để tránh tràn viền)
         ========================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200">
        <div class="flatsome-container py-2.5">
            <div class="flex items-center justify-between gap-3">
                <!-- Logo chỉnh gọn nhỏ lại theo đúng yêu cầu -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs&sz=w400';"
                            alt="Logo Công Ty TNHH Xây Dựng Hoàn Viên" 
                            class="max-h-full max-w-full object-contain"
                        >
                    </div>
                    <div class="leading-tight">
                        <span class="block text-xs sm:text-sm font-extrabold text-brand tracking-tight group-hover:text-brand-accent transition">
                            XÂY DỰNG HOÀN VIÊN
                        </span>
                        <span class="block text-[10px] sm:text-[11px] text-slate-500 font-medium">
                            xaydunghoanvien.com
                        </span>
                    </div>
                </a>

                <!-- MENU DANH MỤC TRÊN MÁY TÍNH:
                     Chữ nhỏ gọn, viết liền trên 1 hàng (hoặc tự xuống hàng 2 nếu màn hình hẹp),
                     tuyệt đối không xuống dòng giữa chừng tên danh mục -->
                <nav class="hidden lg:flex flex-wrap items-center justify-end gap-x-1 xl:gap-x-1.5 gap-y-1 flex-1" aria-label="Menu chính">
                    <a href="#trang-chu" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-brand hover:text-brand-accent rounded transition">
                        Trang chủ
                    </a>
                    <a href="#gioi-thieu" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 hover:text-brand-accent rounded transition">
                        Giới thiệu
                    </a>

                    <!-- Dropdown Công trình thực tế (giống mẫu tintruongthinh.com) -->
                    <div class="relative group">
                        <a href="#cong-trinh-thuc-te" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 group-hover:text-brand-accent rounded transition gap-1">
                            <span>Công trình thực tế</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="absolute left-0 top-full pt-1 hidden group-hover:block z-50">
                            <div class="bg-white shadow-lg rounded border border-slate-200 py-1.5 min-w-[230px]">
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Văn phòng</a>
                            </div>
                        </div>
                    </div>

                    <a href="#du-an-da-nang" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 hover:text-brand-accent rounded transition">
                        Dự án tại Đà Nẵng
                    </a>

                    <!-- Dropdown Lĩnh vực hoạt động -->
                    <div class="relative group">
                        <a href="#linh-vuc-hoat-dong" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 group-hover:text-brand-accent rounded transition gap-1">
                            <span>Lĩnh vực hoạt động</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="absolute left-0 top-full pt-1 hidden group-hover:block z-50">
                            <div class="bg-white shadow-lg rounded border border-slate-200 py-1.5 min-w-[220px]">
                                <a href="#linh-vuc-hoat-dong" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc-hoat-dong" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Thi công phần thô</a>
                                <a href="#linh-vuc-hoat-dong" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Thi công hoàn thiện</a>
                                <a href="#linh-vuc-hoat-dong" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Thi công nội thất</a>
                            </div>
                        </div>
                    </div>

                    <!-- Dropdown Mẫu thiết kế -->
                    <div class="relative group">
                        <a href="#cong-trinh-thuc-te" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 group-hover:text-brand-accent rounded transition gap-1">
                            <span>Mẫu thiết kế</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="absolute left-0 top-full pt-1 hidden group-hover:block z-50">
                            <div class="bg-white shadow-lg rounded border border-slate-200 py-1.5 min-w-[200px]">
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Mẫu thiết kế nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('noi-that')" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Mẫu thiết kế nội thất</a>
                            </div>
                        </div>
                    </div>

                    <!-- Dropdown Báo giá -->
                    <div class="relative group">
                        <a href="#bao-gia" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 group-hover:text-brand-accent rounded transition gap-1">
                            <span>Báo giá</span>
                            <i class="fa-solid fa-chevron-down text-[9px]"></i>
                        </a>
                        <div class="absolute right-0 top-full pt-1 hidden group-hover:block z-50">
                            <div class="bg-white shadow-lg rounded border border-slate-200 py-1.5 min-w-[215px]">
                                <a href="#bao-gia" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Báo giá thi công phần thô</a>
                                <a href="#bao-gia" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia" class="block px-3.5 py-1.5 text-xs font-medium text-slate-700 hover:bg-slate-100 hover:text-brand whitespace-nowrap">Báo giá thi công trọn gói</a>
                            </div>
                        </div>
                    </div>

                    <a href="#doi-tac" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 hover:text-brand-accent rounded transition">
                        Đối tác
                    </a>
                    <a href="#tin-tuc" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 hover:text-brand-accent rounded transition">
                        Tin tức
                    </a>
                    <a href="#lien-he" class="desktop-nav-item px-2 py-1.5 text-[11.5px] xl:text-xs font-bold uppercase text-slate-700 hover:text-brand-accent rounded transition">
                        Liên hệ
                    </a>
                </nav>

                <!-- Nút mở Menu trên Điện thoại -->
                <button 
                    id="mobile-menu-btn" 
                    type="button" 
                    onclick="toggleMobileMenu()"
                    class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded border border-slate-300 text-slate-700 hover:bg-slate-100 text-xs font-bold uppercase"
                    aria-label="Mở danh mục"
                >
                    <i class="fa-solid fa-bars text-sm text-brand"></i>
                    <span>Danh mục</span>
                </button>
            </div>

            <!-- MENU DANH MỤC TRÊN ĐIỆN THOẠI (Thiết kế gọn đẹp, rõ ràng) -->
            <div id="mobile-menu" class="hidden lg:hidden mt-2.5 pt-2.5 border-t border-slate-200">
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-1.5">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-100 text-brand font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-house text-[11px]"></i> Trang chủ
                    </a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-circle-info text-[11px] text-brand"></i> Giới thiệu
                    </a>
                    <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-helmet-safety text-[11px] text-brand"></i> Công trình thực tế
                    </a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-city text-[11px] text-brand"></i> Dự án Đà Nẵng
                    </a>
                    <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-layer-group text-[11px] text-brand"></i> Lĩnh vực hoạt động
                    </a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-file-invoice-dollar text-[11px] text-brand"></i> Báo giá xây dựng
                    </a>
                    <a href="#doi-tac" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-handshake text-[11px] text-brand"></i> Đối tác
                    </a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 hover:bg-slate-100 text-slate-700 font-semibold text-xs flex items-center gap-1.5">
                        <i class="fa-solid fa-newspaper text-[11px] text-brand"></i> Tin tức
                    </a>
                    <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="col-span-2 sm:col-span-1 px-3 py-2 rounded bg-brand text-white font-semibold text-xs flex items-center justify-center gap-1.5">
                        <i class="fa-solid fa-paper-plane text-[11px]"></i> Yêu cầu báo giá
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Hình ảnh và chữ nằm gọn hoàn toàn bên trong banner
         - Chữ cách xa viền ảnh banner (padding an toàn lớn)
         - Điện thoại & máy tính không bao giờ bị thiếu hay cắt chữ
         ========================================== -->
    <section id="trang-chu" class="py-3 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="relative w-full h-[270px] sm:h-[350px] md:h-[430px] rounded-lg overflow-hidden shadow-md bg-brand-dark select-none">
                
                <!-- SLIDE 1 -->
                <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10" data-index="0">
                    <img 
                        src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT" 
                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600';"
                        alt="Banner 1 Công Ty TNHH Xây Dựng Hoàn Viên" 
                        class="w-full h-full object-cover object-center"
                    >
                    <!-- Lớp phủ gradient giúp chữ nổi bật tuyệt đối -->
                    <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/90 via-brand-dark/75 to-brand-dark/50"></div>
                    
                    <!-- Khung chữ cách xa viền ảnh banner (px-10 sm:px-16 md:px-24 py-6) -->
                    <div class="absolute inset-0 flex items-center justify-center px-10 sm:px-16 md:px-24 py-6">
                        <div class="w-full max-w-3xl text-center text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm uppercase tracking-widest text-amber-400 font-bold mb-1.5">
                                XAYDUNGHOANVIEN.COM • UY TÍN TẠO NÊN THƯƠNG HIỆU
                            </p>
                            <h1 class="text-base sm:text-2xl md:text-4xl font-extrabold leading-snug mb-2">
                                CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-3 max-w-2xl mx-auto">
                                Chuyên Thiết kế Kiến trúc – Thi công Phần thô – Thi công Hoàn thiện – Nội thất Khách sạn, Biệt thự, Nhà phố, Căn hộ tại Hội An & TP Đà Nẵng.
                            </p>
                            <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3 text-[11px] sm:text-xs font-semibold">
                                <span class="bg-amber-500 text-white px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-phone mr-1"></i> Hotline: 0769 444 556
                                </span>
                                <span class="bg-white/15 border border-white/30 text-white px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-location-dot mr-1 text-amber-400"></i> 25/18 Đường 18/8, P. Hội An, TP Đà Nẵng
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
                <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0" data-index="1">
                    <img 
                        src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz" 
                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600';"
                        alt="Banner 2 Thi Công Xây Dựng Trọn Gói Hoàn Viên" 
                        class="w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-slate-900/90 via-brand-dark/80 to-brand-dark/55"></div>
                    
                    <!-- Khung chữ cách xa viền ảnh banner (px-10 sm:px-16 md:px-24 py-6) -->
                    <div class="absolute inset-0 flex items-center justify-center px-10 sm:px-16 md:px-24 py-6">
                        <div class="w-full max-w-3xl text-center text-white">
                            <p class="text-[11px] sm:text-xs md:text-sm uppercase tracking-widest text-amber-400 font-bold mb-1.5">
                                NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH
                            </p>
                            <h2 class="text-base sm:text-2xl md:text-4xl font-extrabold leading-snug mb-2">
                                AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-3 max-w-2xl mx-auto">
                                Giải pháp xây dựng tối ưu chi phí, giám sát kỹ thuật chặt chẽ, vật tư chính hãng và chế độ bảo hành công trình dài hạn tận tâm.
                            </p>
                            <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3 text-[11px] sm:text-xs font-semibold">
                                <a href="#form-bao-gia" class="bg-amber-500 hover:bg-amber-600 text-white px-3.5 py-1.5 rounded transition">
                                    Nhận Báo Giá Miễn Phí
                                </a>
                                <a href="#du-an-da-nang" class="bg-white/15 hover:bg-white/25 border border-white/30 text-white px-3.5 py-1.5 rounded transition">
                                    Xem Dự Án Đà Nẵng
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút chuyển trái/phải nằm gọn ở mép, không đè vào vùng chữ -->
                <button 
                    type="button" 
                    onclick="changeBannerSlide(-1)" 
                    class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition"
                    aria-label="Banner trước"
                >
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button 
                    type="button" 
                    onclick="changeBannerSlide(1)" 
                    class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition"
                    aria-label="Banner tiếp theo"
                >
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToBannerSlide(1)" class="banner-dot w-2 h-2 rounded-full bg-white/60 transition-all" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         THANH DANH MỤC NHỎ GỌN Ở TRANG CHỦ (Tối ưu cho cả máy tính & điện thoại)
         ========================================== -->
    <section class="py-3 bg-slate-100 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2">
                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-hotel text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Khách sạn - Căn hộ</span>
                </a>
                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-house-chimney-window text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Biệt thự nghỉ dưỡng</span>
                </a>
                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-building-user text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Thi công Nhà phố</span>
                </a>
                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-briefcase text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Tòa nhà Văn phòng</span>
                </a>
                <a href="#linh-vuc-hoat-dong" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-compass-drafting text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Thiết kế Kiến trúc</span>
                </a>
                <a href="#linh-vuc-hoat-dong" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-trowel-bricks text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Thi công Phần thô</span>
                </a>
                <a href="#linh-vuc-hoat-dong" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-paint-roller text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Thi công Hoàn thiện</span>
                </a>
                <a href="#du-an-da-nang" class="bg-white hover:bg-brand hover:text-white border border-slate-200 rounded px-2.5 py-2 text-center transition group">
                    <i class="fa-solid fa-bridge-water text-brand group-hover:text-amber-300 text-sm mb-1 block"></i>
                    <span class="text-[11px] font-semibold block leading-tight">Dự án tại Đà Nẵng</span>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DỊCH VỤ TIÊU BIỂU & GIỚI THIỆU CÔNG TY (Giống bố cục web mẫu tintruongthinh.com)
         ========================================== -->
    <section id="gioi-thieu" class="py-8 bg-white">
        <div class="flatsome-container">
            <!-- 3 Khối Dịch vụ tiêu biểu: THIẾT KẾ - THI CÔNG - NỘI THẤT -->
            <div class="text-center mb-6">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand tracking-wide">Dịch Vụ Tiêu Biểu</h2>
                    <span class="section-title-line"></span>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-10">
                <div class="border border-slate-200 rounded-lg p-5 bg-slate-50 hover:shadow-md transition text-center">
                    <div class="w-12 h-12 rounded-full bg-brand text-white flex items-center justify-center mx-auto mb-3 text-lg">
                        <i class="fa-solid fa-pen-ruler"></i>
                    </div>
                    <h3 class="text-sm sm:text-base font-extrabold uppercase text-brand mb-2">THIẾT KẾ KIẾN TRÚC</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Tư vấn quy hoạch công năng tối ưu, thiết kế bản vẽ kiến trúc, kết cấu, điện nước 2D & phối cảnh 3D hiện đại cho Biệt thự, Nhà phố, Khách sạn, Căn hộ.
                    </p>
                </div>

                <div class="border border-slate-200 rounded-lg p-5 bg-slate-50 hover:shadow-md transition text-center">
                    <div class="w-12 h-12 rounded-full bg-brand-accent text-white flex items-center justify-center mx-auto mb-3 text-lg">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h3 class="text-sm sm:text-base font-extrabold uppercase text-brand mb-2">THI CÔNG XÂY DỰNG</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Nhận thầu thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay đúng tiến độ, cam kết sử dụng vật tư chính hãng 100%.
                    </p>
                </div>

                <div class="border border-slate-200 rounded-lg p-5 bg-slate-50 hover:shadow-md transition text-center">
                    <div class="w-12 h-12 rounded-full bg-brand text-white flex items-center justify-center mx-auto mb-3 text-lg">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="text-sm sm:text-base font-extrabold uppercase text-brand mb-2">THI CÔNG NỘI THẤT</h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Sản xuất và lắp đặt đồ gỗ xây dựng, giường, tủ, bàn ghế nội thất gia đình, khách sạn, văn phòng với độ hoàn thiện sắc nét và bền bỉ.
                    </p>
                </div>
            </div>

            <!-- Giới thiệu CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN & 6 Thế mạnh -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-6">
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase text-brand-accent mb-1">Về chúng tôi • MST: 4001194676</p>
                    <h2 class="text-lg sm:text-xl font-extrabold text-brand uppercase mb-3 leading-snug">
                        CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN</strong> chuyên Thiết kế – Xây dựng – Nội thất các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại khu vực Hội An – Đà Nẵng và miền Trung.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
                        Với tiêu chí <strong>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi luôn đặt chữ <strong>“TÂM”</strong> trong nghề lên hàng đầu để mỗi công trình luôn đạt kết quả: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>.
                    </p>
                    <div class="bg-white border border-slate-200 rounded p-3 text-xs space-y-1.5 text-slate-700">
                        <div><i class="fa-solid fa-user-tie text-brand w-5"></i> <strong>Đại diện pháp luật:</strong> Ông Đỗ Hoàn Viên</div>
                        <div><i class="fa-solid fa-location-dot text-brand w-5"></i> <strong>Địa chỉ:</strong> 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone text-brand w-5"></i> <strong>Điện thoại:</strong> <a href="tel:0769444556" class="font-bold text-brand-accent">0769 444 556</a></div>
                        <div><i class="fa-solid fa-globe text-brand w-5"></i> <strong>Website:</strong> xaydunghoanvien.com</div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của chúng tôi (Giống mẫu tintruongthinh.com) -->
                <div class="lg:col-span-7">
                    <h3 class="text-sm sm:text-base font-extrabold uppercase text-brand mb-3 text-center lg:text-left">
                        Thế Mạnh Của Chúng Tôi
                    </h3>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                        <div class="bg-white p-3.5 rounded border border-slate-200 flex gap-3">
                            <i class="fa-solid fa-users-gear text-brand-accent text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Đội ngũ KTS, kỹ sư chuyên nghiệp</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giàu kinh nghiệm và thợ lành nghề lâu năm.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 rounded border border-slate-200 flex gap-3">
                            <i class="fa-solid fa-lightbulb text-brand-accent text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Cập nhật xu hướng hiện đại</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Ứng dụng xu thế thiết kế mới, vật liệu bền vững và biện pháp thi công tiên tiến.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 rounded border border-slate-200 flex gap-3">
                            <i class="fa-solid fa-clipboard-check text-brand-accent text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Giám sát tiến độ chuẩn xác</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Hoàn thành đúng tiến độ cam kết, báo cáo nhật ký công trình thường xuyên minh bạch.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 rounded border border-slate-200 flex gap-3">
                            <i class="fa-solid fa-shield-halved text-brand-accent text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Bảo hành công trình lâu dài</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi tận tâm, bảo hành kết cấu và chống thấm dài hạn cho mọi công trình.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 rounded border border-slate-200 flex gap-3">
                            <i class="fa-solid fa-scale-balanced text-brand-accent text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Giá cả hợp lý phải chăng</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 rounded border border-slate-200 flex gap-3">
                            <i class="fa-solid fa-headset text-brand-accent text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <h4 class="text-xs sm:text-sm font-bold text-slate-800 mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                                <p class="text-xs text-slate-600 leading-relaxed">Khảo sát mặt bằng thực tế, tư vấn xin phép xây dựng và dự toán hoàn toàn miễn phí.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         CÔNG TRÌNH THỰC TẾ & SẢN PHẨM DỊCH VỤ THI CÔNG (9 ẢNH THỰC TẾ)
         - Lấy danh mục từ web mẫu tintruongthinh.com
         - Chia thành 2 cột trên điện thoại (grid-cols-2)
         - KHÔNG để các nhãn dán ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hay thiếu chữ
         ========================================== -->
    <section id="cong-trinh-thuc-te" class="py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-4">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand tracking-wide">
                        Công Trình Thực Tế & Hạng Mục Thi Công
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs text-slate-600">
                    Hình ảnh thực tế thi công xây dựng của Công Ty TNHH Xây Dựng Hoàn Viên
                </p>
            </div>

            <!-- Thanh lọc danh mục nhỏ gọn chuẩn web mẫu -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
                <button type="button" onclick="filterConstruction('all')" class="filter-btn active-filter px-3 py-1.5 rounded border border-brand bg-brand text-white text-xs font-semibold transition" data-filter="all">
                    Tất cả
                </button>
                <button type="button" onclick="filterConstruction('khach-san')" class="filter-btn px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-brand text-xs font-semibold transition" data-filter="khach-san">
                    Khách sạn – Căn hộ – Phòng trọ
                </button>
                <button type="button" onclick="filterConstruction('biet-thu')" class="filter-btn px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-brand text-xs font-semibold transition" data-filter="biet-thu">
                    Biệt thự
                </button>
                <button type="button" onclick="filterConstruction('nha-pho')" class="filter-btn px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-brand text-xs font-semibold transition" data-filter="nha-pho">
                    Nhà phố
                </button>
                <button type="button" onclick="filterConstruction('van-phong')" class="filter-btn px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-brand text-xs font-semibold transition" data-filter="van-phong">
                    Văn phòng
                </button>
                <button type="button" onclick="filterConstruction('noi-that')" class="filter-btn px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-brand text-xs font-semibold transition" data-filter="noi-that">
                    Thi công Phần thô & Nội thất
                </button>
            </div>

            <!-- Lưới sản phẩm / công trình: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính -->
            <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                
                <!-- 1. File ID: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="nha-pho noi-that">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800';"
                            alt="Thi Công Phần Thô & Kết Cấu Nhà Phố Hiện Đại" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Thi công phần thô • Nhà phố</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thi Công Phần Thô & Kết Cấu Khung Bê Tông Cốt Thép Nhà Phố
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 2. File ID: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="khach-san">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800';"
                            alt="Thi Công Khách Sạn Căn Hộ Cho Thuê" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Khách sạn – Căn hộ – Phòng trọ</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thiết Kế & Thi Công Khách Sạn – Căn Hộ Dịch Vụ Cho Thuê
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 3. File ID: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="biet-thu">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800';"
                            alt="Thi Công Biệt Thự Hiện Đại" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Biệt thự • Thi công trọn gói</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thi Công Xây Dựng Hoàn Thiện Biệt Thự Gia Đình Cao Cấp
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 4. File ID: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="nha-pho">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800';"
                            alt="Thi Công Nhà Phố Trọn Gói" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Nhà phố • Mẫu thiết kế nhà phố</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Xây Dựng Nhà Phố Hiện Đại Trọn Gói Chìa Khóa Trao Tay
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 5. File ID: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="noi-that nha-pho">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800';"
                            alt="Thi Công Cốt Thép & Đổ Bê Tông Sàn" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Thi công phần thô • Kết cấu</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thi Công Lắp Đặt Cốtpha, Cốt Thép & Đổ Bê Tông Sàn Móng
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 6. File ID: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="nha-pho biet-thu">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800';"
                            alt="Thi Công Xây Tô Hoàn Thiện Công Trình" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Thi công hoàn thiện • Dân dụng</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thi Công Xây Tường, Tô Trát & Chống Thấm Hoàn Thiện
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 7. File ID: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="noi-that">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w800';"
                            alt="Thiết Kế & Thi Công Nội Thất Hoàn Thiện" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Thi công nội thất • Đồ gỗ xây dựng</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thiết Kế & Thi Công Nội Thất Phòng Khách – Phòng Ngủ – Bếp
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 8. File ID: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="van-phong khach-san">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w800';"
                            alt="Thi Công Văn Phòng & Công Trình Thương Mại" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Văn phòng • Công trình thương mại</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Thiết Kế & Thi Công Trọn Gói Tòa Nhà Văn Phòng Công Ty
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- 9. File ID: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                <div class="ux-box construction-item bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col" data-category="biet-thu khach-san">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800';"
                            alt="Thi Công Hoàn Thiện Điện Nước & Sơn Bả" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-500 mb-1">Thi công hoàn thiện • Hệ thống M&E</p>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug break-words">
                                Lắp Đặt Hệ Thống Điện Nước, Sơn Nước & Cải Tạo Công Trình
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px]">
                            <span class="text-brand font-semibold">Xây dựng Hoàn Viên</span>
                            <a href="#form-bao-gia" class="text-brand-accent font-semibold hover:underline">Báo giá</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN ĐÀ NẴNG TRÊN TRANG CHỦ)
         - Chia thành 2 cột trên điện thoại (grid-cols-2), 5 cột trên màn hình lớn
         - Không gắn nhãn dán đè lên ảnh
         - Tên dự án đầy đủ, không tràn viền
         ========================================== -->
    <section id="du-an-da-nang" class="py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand tracking-wide">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs text-slate-600">
                    Tổng hợp các dự án Khách sạn, Căn hộ, Biệt thự, Nhà phố do Xây Dựng Hoàn Viên triển khai tại TP Đà Nẵng
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 5 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                
                <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800';"
                            alt="Dự Án Khách Sạn & Căn Hộ Cao Cấp Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Khách sạn – Căn hộ • Đà Nẵng</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Khách Sạn & Căn Hộ Cao Cấp View Sông Hàn – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800';"
                            alt="Dự Án Biệt Thự Khu Đô Thị Hòa Xuân Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Biệt thự • Hòa Xuân, Đà Nẵng</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Biệt Thự Hiện Đại Khu Đô Thị Hòa Xuân – TP Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800';"
                            alt="Dự Án Nhà Phố Khu Nam Việt Á Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Nhà phố • Khu Nam Việt Á</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Nhà Phố 3 Tầng Khu Đô Thị Nam Việt Á – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800';"
                            alt="Dự Án Căn Hộ Cho Thuê Sơn Trà Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Căn hộ cho thuê • Sơn Trà</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Tòa Căn Hộ Dịch Vụ Cho Thuê Quận Sơn Trà – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800';"
                            alt="Dự Án Nhà Phố Khu Phước Lý Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Nhà phố • Khu Phước Lý</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Thi Công Nhà Phố Khu Đô Thị Phước Lý – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800';"
                            alt="Dự Án Biệt Thự 2 Mặt Tiền Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Biệt thự • Ngũ Hành Sơn</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Biệt Thự Nghỉ Dưỡng 2 Mặt Tiền Ven Biển Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800';"
                            alt="Dự Án Văn Phòng Hải Châu Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Văn phòng • Hải Châu</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Thiết Kế & Thi Công Văn Phòng Quận Hải Châu – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800';"
                            alt="Dự Án Nhà Phố Tiểu La Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Nhà phố • Đường Tiểu La</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Thi Công Nhà Phố Gia Đình Đường Tiểu La – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800';"
                            alt="Dự Án Villa Homestay Hội An Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Khách sạn – Homestay • Hội An</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Khu Lưu Trú Homestay & Villa Nghỉ Dưỡng Hội An – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                <div class="ux-box bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800';"
                            alt="Dự Án Căn Hộ Hồ Biểu Chánh Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10.5px] text-slate-500 mb-0.5">Căn hộ • Hồ Biểu Chánh</p>
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                                Dự Án Thi Công Hoàn Thiện Căn Hộ Hồ Biểu Chánh – Đà Nẵng
                            </h3>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         LĨNH VỰC HOẠT ĐỘNG & BẢNG BÁO GIÁ THAM KHẢO (Chuẩn danh mục tintruongthinh.com)
         ========================================== -->
    <section id="linh-vuc-hoat-dong" class="py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div id="bao-gia" class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand tracking-wide">
                        Lĩnh Vực Hoạt Động & Bảng Báo Giá Xây Dựng
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs text-slate-600">
                    Đơn giá minh bạch, vật tư chính hãng, tối ưu chi phí theo từng quy mô công trình tại Đà Nẵng
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="bg-white rounded-lg border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand mb-1.5">
                            Báo Giá Thiết Kế Kiến Trúc
                        </h3>
                        <p class="text-sm sm:text-base font-extrabold text-brand-accent mb-2">
                            120.000đ - 180.000đ/m²
                        </p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                            <li>• Hồ sơ bản vẽ kiến trúc 2D & 3D</li>
                            <li>• Bản vẽ kết cấu & điện nước M&E</li>
                            <li>• Hỗ trợ hồ sơ xin phép xây dựng</li>
                            <li>• Miễn phí thiết kế khi nhận thi công</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block text-center py-2 rounded bg-brand text-white text-xs font-semibold hover:bg-brand-light transition">
                        Nhận tư vấn
                    </a>
                </div>

                <div class="bg-white rounded-lg border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand mb-1.5">
                            Báo Giá Thi Công Phần Thô
                        </h3>
                        <p class="text-sm sm:text-base font-extrabold text-brand-accent mb-2">
                            3.500.000đ - 3.900.000đ/m²
                        </p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                            <li>• Vật tư sắt thép, xi măng, gạch chuẩn</li>
                            <li>• Nhân công phần thô & hoàn thiện</li>
                            <li>• Thi công hệ thống điện nước âm tường</li>
                            <li>• Bảo hành kết cấu công trình dài hạn</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block text-center py-2 rounded bg-brand text-white text-xs font-semibold hover:bg-brand-light transition">
                        Nhận tư vấn
                    </a>
                </div>

                <div class="bg-white rounded-lg border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand mb-1.5">
                            Báo Giá Thi Công Hoàn Thiện
                        </h3>
                        <p class="text-sm sm:text-base font-extrabold text-brand-accent mb-2">
                            2.200.000đ - 3.200.000đ/m²
                        </p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                            <li>• Ốp lát gạch nền, gạch tường, đá cầu thang</li>
                            <li>• Sơn bả nội ngoại thất, chống thấm Sika</li>
                            <li>• Lắp đặt cửa, trần thạch cao, thiết bị vệ sinh</li>
                            <li>• Nghiệm thu bàn giao sạch đẹp</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block text-center py-2 rounded bg-brand text-white text-xs font-semibold hover:bg-brand-light transition">
                        Nhận tư vấn
                    </a>
                </div>

                <div class="bg-white rounded-lg border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand mb-1.5">
                            Báo Giá Xây Nhà Trọn Gói
                        </h3>
                        <p class="text-sm sm:text-base font-extrabold text-brand-accent mb-2">
                            5.600.000đ - 7.200.000đ/m²
                        </p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                            <li>• Trọn gói từ thiết kế đến hoàn thiện</li>
                            <li>• Tặng 100% chi phí xin phép & thiết kế</li>
                            <li>• Cam kết không phát sinh chi phí</li>
                            <li>• Giám sát kỹ sư trực tiếp tại công trình</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block text-center py-2 rounded bg-brand-accent text-white text-xs font-semibold hover:bg-brand-accentHover transition">
                        Đăng ký báo giá
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ + KẾT NỐI FACEBOOK & GOOGLE MAP
         - Form thiết kế giống mẫu tintruongthinh.com
         - Đưa Facebook https://www.facebook.com/hoanvien.do ra ngoài trang chủ
         - Đưa Google Map 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng ra ngoài trang chủ
         ========================================== -->
    <section id="form-bao-gia" class="py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                
                <!-- Cột Trái: Form Yêu Cầu Tư Vấn & Báo Giá (Giống mẫu tintruongthinh.com) -->
                <div class="lg:col-span-6 bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-6">
                    <div class="mb-4">
                        <span class="text-xs font-bold uppercase text-brand-accent">Hỗ trợ nhanh 24/7</span>
                        <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand mt-0.5">
                            MIỄN PHÍ TƯ VẤN & BÁO GIÁ XÂY DỰNG
                        </h2>
                        <p class="text-xs text-slate-600 mt-1">
                            Quý khách vui lòng điền thông tin công trình, Kỹ sư Xây Dựng Hoàn Viên sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết.
                        </p>
                    </div>

                    <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ tên Quý khách *</label>
                                <input type="text" id="q-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                                <input type="tel" id="q-phone" required placeholder="Nhập số điện thoại..." class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                                <select id="q-type" class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                    <option value="Nhà phố hiện đại">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa & Nội thất">Cải tạo sửa chữa & Nội thất</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                <select id="q-budget" class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                    <option value="1 - 2 tỷ">1 - 2 tỷ</option>
                                    <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Email (nếu có)</label>
                                <input type="email" id="q-email" placeholder="Nhập địa chỉ email..." class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Khu vực & Diện tích đất</label>
                                <input type="text" id="q-area" placeholder="VD: Hội An, Đà Nẵng - 5x20m..." class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết</label>
                            <textarea id="q-note" rows="3" placeholder="Nhập nhu cầu số tầng, số phòng hoặc hạng mục cần tư vấn báo giá..." class="w-full px-3 py-2 text-xs sm:text-sm rounded border border-slate-300 focus:outline-none focus:border-brand bg-white"></textarea>
                        </div>

                        <button type="submit" class="w-full py-2.5 px-4 rounded bg-brand hover:bg-brand-light text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Nhận Báo Giá Ngay
                        </button>

                        <!-- Hộp thông báo trạng thái gửi form (Không dùng alert) -->
                        <div id="quote-success-msg" class="hidden p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs leading-relaxed"></div>
                    </form>
                </div>

                <!-- Cột Phải: Đưa Facebook & Bản đồ Google Maps ra ngoài trang chủ -->
                <div id="lien-he" class="lg:col-span-6 flex flex-col justify-between space-y-4">
                    
                    <!-- Khối Kết nối Facebook chính thức ngoài trang chủ -->
                    <div class="bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-5">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                            <div class="flex items-center gap-3">
                                <div class="w-12 h-12 rounded-lg bg-[#1877F2] text-white flex items-center justify-center text-2xl shrink-0">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </div>
                                <div>
                                    <span class="text-[11px] font-bold uppercase text-[#1877F2] block">Kết nối Facebook chính thức</span>
                                    <h3 class="text-sm sm:text-base font-extrabold text-slate-800">
                                        Đỗ Hoàn Viên - Xây Dựng Hoàn Viên
                                    </h3>
                                    <p class="text-xs text-slate-600 break-all">
                                        https://www.facebook.com/hoanvien.do
                                    </p>
                                </div>
                            </div>
                            <a 
                                href="https://www.facebook.com/hoanvien.do" 
                                target="_blank" 
                                rel="noopener noreferrer" 
                                class="inline-flex items-center justify-center gap-1.5 px-4 py-2 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold shrink-0 transition"
                            >
                                <i class="fa-brands fa-facebook"></i>
                                <span>Xem Trang Facebook</span>
                            </a>
                        </div>
                    </div>

                    <!-- Khối Bản đồ Google Maps ngoài trang chủ -->
                    <div class="bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-5 flex-1 flex flex-col">
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                            <div>
                                <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand">
                                    <i class="fa-solid fa-map-location-dot text-brand-accent mr-1"></i>
                                    Bản Đồ Google Maps Trụ Sở Công Ty
                                </h3>
                                <p class="text-xs text-slate-600 mt-0.5">
                                    Địa chỉ: 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng
                                </p>
                            </div>
                            <a 
                                href="https://www.google.com/maps/search/?api=1&query=25%2F18+%C4%90%C6%B0%E1%BB%9Dng+18+th%C3%A1ng+8%2C+H%E1%BB%99i+An%2C+%C4%90%C3%A0+N%E1%BA%B5ng" 
                                target="_blank" 
                                rel="noopener noreferrer"
                                class="text-xs font-semibold text-brand hover:text-brand-accent underline"
                            >
                                Mở chỉ đường lớn
                            </a>
                        </div>
                        <div class="w-full h-[230px] sm:h-[260px] rounded overflow-hidden border border-slate-300 bg-slate-200">
                            <iframe 
                                title="Bản đồ Công Ty TNHH Xây Dựng Hoàn Viên - 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng"
                                src="https://maps.google.com/maps?q=25/18%20%C4%90%C6%B0%E1%BB%9Dng%2018%20th%C3%A1ng%208,%20H%E1%BB%99i%20An,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade"
                            ></iframe>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG)
         - Chia 2 cột trên điện thoại, 4 cột trên máy tính
         ========================================== -->
    <section id="tin-tuc" class="py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand tracking-wide">
                        Tin Tức & Cẩm Nang Xây Dựng
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs text-slate-600">
                    Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm xây nhà trọn gói và thiết kế nội thất
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                
                <article class="ux-box bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w600';"
                            alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5 break-words">
                                Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Kỹ Thuật Xây Dựng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Quy trình giữ ẩm và bảo dưỡng bê tông móng giúp công trình đạt cường độ chịu lực tối đa, hạn chế nứt sàn.
                            </p>
                        </div>
                        <span class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand inline-block">
                            Kỹ thuật thi công
                        </span>
                    </div>
                </article>

                <article class="ux-box bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w600';"
                            alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư thường gặp" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5 break-words">
                                03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Thường Gặp Phải
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Giải pháp kiểm soát ngân sách không phát sinh, lựa chọn vật tư chuẩn và đảm bảo tiến độ bàn giao nhà.
                            </p>
                        </div>
                        <span class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand inline-block">
                            Kinh nghiệm xây nhà
                        </span>
                    </div>
                </article>

                <article class="ux-box bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w600';"
                            alt="Thiết kế nội thất là gì? Khái niệm và tầm quan trọng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5 break-words">
                                Thiết Kế Thi Công Nội Thất Đồng Bộ Giúp Tối Ưu Không Gian Sống
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Sự kết hợp hài hòa giữa ánh sáng tự nhiên, vật liệu gỗ và bố cục công năng cho nhà phố, biệt thự.
                            </p>
                        </div>
                        <span class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand inline-block">
                            Kiến trúc & Nội thất
                        </span>
                    </div>
                </article>

                <article class="ux-box bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w600';"
                            alt="Quy trình chống thấm tường và sàn mái bền vững tại Đà Nẵng" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5 break-words">
                                Quy Trình Chống Thấm Sàn Mái, Nhà Vệ Sinh & Tường Ngoài Trời
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Biện pháp xử lý chống thấm chuyên sâu thích ứng với khí hậu mưa nắng miền Trung tại Hội An – Đà Nẵng.
                            </p>
                        </div>
                        <span class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-brand inline-block">
                            Chống thấm & Hoàn thiện
                        </span>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC VẬT TƯ & ĐỒNG HÀNH)
         ========================================== -->
    <section id="doi-tac" class="py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase text-brand tracking-wide">
                        Đối Tác Cung Cấp Vật Tư Chính Hãng
                    </h2>
                    <span class="section-title-line"></span>
                </div>
                <p class="text-xs text-slate-600">
                    Hợp tác cùng các thương hiệu vật liệu xây dựng và trang thiết bị uy tín hàng đầu
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">THÉP HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">XI MĂNG KIM ĐỈNH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Xi măng bê tông</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">SIKA VIỆT NAM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Hóa chất chống thấm</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">SƠN JOTUN</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">SƠN DULUX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn cao cấp</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">GẠCH ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch ốp lát</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">THIẾT BỊ INAX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
                </div>
                <div class="border border-slate-200 rounded p-3 text-center bg-slate-50 flex flex-col items-center justify-center">
                    <span class="text-xs sm:text-sm font-extrabold text-brand">ĐIỆN PANASONIC</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị điện M&E</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER (Chân trang chuẩn Flatsome)
         ========================================== -->
    <footer class="bg-brand-dark text-slate-200 pt-8 pb-6 border-t-4 border-brand-accent">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10">
                
                <!-- Thông tin Công ty -->
                <div>
                    <div class="flex items-center gap-2.5 mb-3">
                        <div class="w-9 h-9 rounded bg-white p-0.5 flex items-center justify-center shrink-0">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs" 
                                onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Oo1kdgOIOBjfcwqu2p4pqXB3Lu0cElfs&sz=w400';"
                                alt="Logo Công Ty TNHH Xây Dựng Hoàn Viên" 
                                class="max-h-full max-w-full object-contain"
                            >
                        </div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-white uppercase">
                                CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN
                            </h3>
                            <p class="text-[11px] text-amber-400">xaydunghoanvien.com</p>
                        </div>
                    </div>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-4"></i> <strong>Trụ sở:</strong> 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 w-4"></i> <strong>Hotline:</strong> <a href="tel:0769444556" class="text-white font-bold hover:text-amber-300">0769 444 556</a></li>
                        <li><i class="fa-solid fa-id-card text-amber-400 w-4"></i> <strong>Mã số thuế:</strong> 4001194676</li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-4"></i> <strong>Facebook:</strong> <a href="https://www.facebook.com/hoanvien.do" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 underline">facebook.com/hoanvien.do</a></li>
                    </ul>
                </div>

                <!-- Lĩnh vực hoạt động -->
                <div>
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white mb-3 border-b border-white/15 pb-1.5">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thi công xây dựng phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thi công xây dựng hoàn thiện</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Sản xuất & Thi công đồ gỗ nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Lắp đặt điện nước & Chống thấm</a></li>
                    </ul>
                </div>

                <!-- Danh mục công trình -->
                <div>
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white mb-3 border-b border-white/15 pb-1.5">
                        Công Trình Thực Tế
                    </h4>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="hover:text-amber-400 transition">• Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-amber-400 transition">• Thi công Biệt thự nghỉ dưỡng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-amber-400 transition">• Xây dựng Nhà phố trọn gói</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="hover:text-amber-400 transition">• Thiết kế & Thi công Văn phòng</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-400 transition">• Các dự án tiêu biểu tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cam kết chất lượng -->
                <div>
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white mb-3 border-b border-white/15 pb-1.5">
                        Phương Châm Hoạt Động
                    </h4>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        “Nhà ở Gia đình – Tiêu chuẩn Công trình”. Đặt chữ TÂM lên hàng đầu, cam kết An toàn – Chất lượng – Đúng tiến độ – Chi phí hợp lý.
                    </p>
                    <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded bg-brand-accent hover:bg-brand-accentHover text-white text-xs font-bold transition">
                        <i class="fa-solid fa-calculator"></i> Đăng ký nhận báo giá
                    </a>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright © CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN (xaydunghoanvien.com). All rights reserved.</p>
                <p>ĐC: 25/18 Đường 18 tháng 8, Phường Hội An, TP Đà Nẵng | ĐT: 0769 444 556</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Tương thích trên máy tính và điện thoại
         - Nằm gọn bên góc phải dưới, không gây tràn viền
         ========================================== -->
    <div class="fixed bottom-4 right-3 sm:right-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a 
            href="https://www.facebook.com/hoanvien.do" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition"
            title="Chat Facebook Xây Dựng Hoàn Viên"
        >
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a 
            href="https://zalo.me/0769444556" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition"
            title="Liên hệ Zalo: 0769 444 556"
        >
            <span class="font-extrabold text-[11px] bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a 
            href="tel:0769444556" 
            class="pulse-btn flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white px-3.5 py-2.5 rounded-full shadow-lg transition"
            title="Gọi ngay: 0769 444 556"
        >
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold tracking-wide">0769 444 556</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, BỘ LỌC DANH MỤC & FORM BÁO GIÁ
         ========================================== -->
    <script>
        // 1. Bật/tắt Menu trên điện thoại
        function toggleMobileMenu() {
            var menu = document.getElementById('mobile-menu');
            if (menu) {
                menu.classList.toggle('hidden');
            }
        }

        // 2. Xử lý 2 Banner tự trượt chuyên nghiệp
        var currentBannerIndex = 0;
        var bannerSlides = [];
        var bannerDots = [];
        var bannerInterval = null;

        function updateBannerDisplay() {
            bannerSlides = document.querySelectorAll('.banner-slide');
            bannerDots = document.querySelectorAll('.banner-dot');
            for (var i = 0; i < bannerSlides.length; i++) {
                if (i === currentBannerIndex) {
                    bannerSlides[i].classList.remove('opacity-0', 'z-0');
                    bannerSlides[i].classList.add('opacity-100', 'z-10');
                } else {
                    bannerSlides[i].classList.remove('opacity-100', 'z-10');
                    bannerSlides[i].classList.add('opacity-0', 'z-0');
                }
            }
            for (var j = 0; j < bannerDots.length; j++) {
                if (j === currentBannerIndex) {
                    bannerDots[j].classList.remove('w-2', 'bg-white/60');
                    bannerDots[j].classList.add('w-6', 'bg-amber-400');
                } else {
                    bannerDots[j].classList.remove('w-6', 'bg-amber-400');
                    bannerDots[j].classList.add('w-2', 'bg-white/60');
                }
            }
        }

        function changeBannerSlide(step) {
            bannerSlides = document.querySelectorAll('.banner-slide');
            if (!bannerSlides.length) return;
            currentBannerIndex = (currentBannerIndex + step + bannerSlides.length) % bannerSlides.length;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            currentBannerIndex = index;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(function() {
                changeBannerSlide(1);
            }, 5000);
        }

        // 3. Bộ lọc Danh mục Công trình thực tế
        function filterConstruction(category) {
            var items = document.querySelectorAll('.construction-item');
            var buttons = document.querySelectorAll('.filter-btn');

            for (var b = 0; b < buttons.length; b++) {
                var btnCat = buttons[b].getAttribute('data-filter');
                if (btnCat === category) {
                    buttons[b].classList.add('bg-brand', 'text-white', 'border-brand');
                    buttons[b].classList.remove('bg-white', 'text-slate-700', 'border-slate-300');
                } else {
                    buttons[b].classList.remove('bg-brand', 'text-white', 'border-brand');
                    buttons[b].classList.add('bg-white', 'text-slate-700', 'border-slate-300');
                }
            }

            for (var i = 0; i < items.length; i++) {
                var itemCats = items[i].getAttribute('data-category') || '';
                if (category === 'all' || itemCats.indexOf(category) !== -1) {
                    items[i].classList.remove('hidden');
                } else {
                    items[i].classList.add('hidden');
                }
            }
        }

        // 4. Xử lý gửi Form Yêu cầu tư vấn & Báo giá (Không dùng alert)
        function handleQuoteSubmit(event) {
            event.preventDefault();
            var name = document.getElementById('q-name').value.trim();
            var phone = document.getElementById('q-phone').value.trim();
            var type = document.getElementById('q-type').value;
            var budget = document.getElementById('q-budget').value;
            var msgBox = document.getElementById('quote-success-msg');

            if (msgBox) {
                msgBox.innerHTML = '<strong>Đã gửi yêu cầu thành công!</strong> Cảm ơn Quý khách <strong>' + name + '</strong> (' + phone + '). Bộ phận Kỹ thuật & Báo giá của <strong>CÔNG TY TNHH XÂY DỰNG HOÀN VIÊN</strong> đã ghi nhận nhu cầu <em>' + type + ' (' + budget + ')</em> và sẽ liên hệ tư vấn sớm nhất qua số <strong>0769 444 556</strong>.';
                msgBox.classList.remove('hidden');
                document.getElementById('quote-form').reset();
            }
        }

        window.onload = function() {
            resetBannerTimer();
        };
    </script>
</body>
</html>
