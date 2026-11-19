<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG | quangandanang.com</title>
  <meta name="description" content="CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện, nội thất và các công trình xây dựng dân dụng tại Đà Nẵng. Hotline: 0395.398.653." />
  <link rel="canonical" href="https://quangandanang.com/" />

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ link trang web -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="QUẢNG AN ĐÀ NẴNG" />
  <meta property="og:title" content="CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG" />
  <meta property="og:description" content="Thiết kế Kiến trúc – Thi công Phần thô – Thi công Hoàn thiện & Nội thất trọn gói tại Đà Nẵng. Hotline: 0395.398.653." />
  <meta property="og:url" content="https://quangandanang.com/" />
  <meta property="og:image" content="https://quangandanang.com/wp-content/uploads/logo-quang-an-da-nang.png" />
  <meta property="og:image:alt" content="Logo Công ty TNHH Đầu tư Xây dựng Quảng An Đà Nẵng" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG" />
  <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng." />
  <meta name="twitter:image" content="https://quangandanang.com/wp-content/uploads/logo-quang-an-da-nang.png" />

  <!-- Favicon Logo thương hiệu Quảng An Đà Nẵng -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230E3A5D'/%3E%3Cpath d='M12 44L32 16L52 44H44L32 27L20 44H12Z' fill='%23D98218'/%3E%3Crect x='26' y='36' width='12' height='12' rx='1.5' fill='%23FFFFFF'/%3E%3C/svg%3E" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome 6 -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    // Cấu hình bảng màu thương hiệu đồng bộ theo Logo Quảng An Đà Nẵng
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              navy: '#0E3A5D',
              navyDark: '#092740',
              navyLight: '#175280',
              gold: '#D98218',
              goldDark: '#B86A0F',
              goldLight: '#F4A236',
              bgSoft: '#F6F8FA',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Đảm bảo bố cục không bao giờ tràn viền, không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      max-width: 100%;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình, căn giữa chuẩn xác */
    .qa-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .qa-container {
        padding-left: 16px;
        padding-right: 16px;
      }
    }

    @media (min-width: 1024px) {
      .qa-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Flatsome Section Heading Underline */
    .section-title-bar {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .section-title-bar::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 56px;
      height: 3px;
      background-color: #D98218;
      border-radius: 999px;
    }
    .section-title-bar-left::after {
      left: 0;
      transform: none;
    }

    /* Hero Slider: Dùng CSS Grid xếp chồng giúp 2 banner luôn bằng nhau 100% và chữ không bao giờ bị cắt */
    .hero-slider-grid {
      display: grid;
      grid-template-columns: 1fr;
      grid-template-rows: 1fr;
      position: relative;
      width: 100%;
      overflow: hidden;
    }
    .hero-slide-item {
      grid-area: 1 / 1 / 2 / 2;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.65s ease, visibility 0.65s ease;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      width: 100%;
    }
    .hero-slide-item.active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 2;
    }

    /* Menu ngang 1 hàng chuẩn trên máy tính, tên danh mục không xuống dòng */
    .desktop-nav-link {
      white-space: nowrap;
      transition: color 0.2s ease, background-color 0.2s ease;
    }

    /* Tab danh mục nhỏ gọn, tên danh mục luôn nằm trên 1 dòng */
    .cat-pill {
      white-space: nowrap;
      transition: all 0.2s ease;
    }
    .cat-pill.active {
      background-color: #0E3A5D;
      color: #FFFFFF;
      border-color: #0E3A5D;
    }

    /* Hiệu ứng card nhẹ nhàng kiểu Flatsome (dễ dựng lại trên UX Builder) */
    .flatsome-card {
      transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
    }
    .flatsome-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 12px 24px -8px rgba(14, 58, 93, 0.14);
      border-color: #CBD5E1;
    }
    .flatsome-card img {
      transition: transform 0.45s ease;
    }
    .flatsome-card:hover img {
      transform: scale(1.04);
    }

    /* Nút liên hệ nổi bật Zalo / Facebook / Hotline */
    @keyframes qaPulseRing {
      0% {
        transform: scale(0.95);
        box-shadow: 0 0 0 0 rgba(217, 130, 24, 0.6);
      }
      70% {
        transform: scale(1);
        box-shadow: 0 0 0 12px rgba(217, 130, 24, 0);
      }
      100% {
        transform: scale(0.95);
        box-shadow: 0 0 0 0 rgba(217, 130, 24, 0);
      }
    }
    .hotline-pulse {
      animation: qaPulseRing 2.1s infinite;
    }

    /* Ngăn tràn chiều ngang đối với iframe */
    iframe {
      max-width: 100%;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- FLATSOME TOP BAR (Thông tin liên hệ gọn sạch - Không hiển thị UX Builder) -->
  <!-- ===================================================================== -->
  <div class="bg-brand-navyDark text-slate-200 text-xs border-b border-white/10">
    <div class="qa-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:0395398653" class="inline-flex items-center gap-1.5 hover:text-brand-goldLight transition-colors whitespace-nowrap">
          <i class="fa-solid fa-phone text-brand-goldLight text-[11px]"></i>
          <span class="font-medium">0395.398.653</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <a href="mailto:info@quangandanang.com" class="hidden sm:inline-flex items-center gap-1.5 hover:text-brand-goldLight transition-colors whitespace-nowrap">
          <i class="fa-solid fa-envelope text-brand-goldLight text-[11px]"></i>
          <span>info@quangandanang.com</span>
        </a>
      </div>
      <div class="hidden md:flex items-center gap-4">
        <span class="inline-flex items-center gap-1.5 text-slate-300 whitespace-nowrap">
          <i class="fa-solid fa-location-dot text-brand-goldLight text-[11px]"></i>
          <span>145 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP Đà Nẵng</span>
        </span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- FLATSOME HEADER (Logo gọn nhỏ + Menu 1 hàng + Không nút Gọi Ngay)     -->
  <!-- ===================================================================== -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="qa-container h-16 lg:h-[70px] flex items-center justify-between gap-3">

      <!-- LOGO CÔNG TY CHUYÊN NGHIỆP (CHỈNH GỌN NHỎ LẠI) -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none" aria-label="Công ty TNHH Đầu tư Xây dựng Quảng An Đà Nẵng">
        <!-- Biểu tượng SVG Logo gọn đẹp -->
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Quảng An Đà Nẵng">
          <rect width="64" height="64" rx="11" fill="#0E3A5D"/>
          <!-- Khung mái kiến trúc & kết cấu chữ A cách điệu -->
          <path d="M12 46L32 15L52 46H43.5L32 27.5L20.5 46H12Z" fill="#D98218"/>
          <!-- Khối tòa nhà vững chắc ở tâm -->
          <path d="M26 46V35.5L32 31L38 35.5V46H34.2V39.5H29.8V46H26Z" fill="#FFFFFF"/>
          <!-- Đường nền vững chãi -->
          <rect x="12" y="49" width="40" height="3.2" rx="1.6" fill="#FFFFFF" fill-opacity="0.9"/>
        </svg>
        <div class="flex flex-col leading-tight">
          <span class="text-brand-navy font-extrabold text-[15px] sm:text-[17px] tracking-tight whitespace-nowrap group-hover:text-brand-gold transition-colors">
            QUẢNG AN <span class="text-brand-gold">ĐÀ NẴNG</span>
          </span>
          <span class="text-[9.5px] sm:text-[10.5px] font-semibold tracking-wider text-slate-500 uppercase whitespace-nowrap">
            Đầu Tư &amp; Xây Dựng
          </span>
        </div>
      </a>

      <!-- MENU ĐIỀU HƯỚNG TRÊN MÁY TÍNH (Viết liền 1 hàng, chữ nhỏ gọn, không xuống dòng) -->
      <nav class="hidden lg:flex items-center justify-end gap-1 xl:gap-2 flex-nowrap" aria-label="Menu chính">
        <a href="#trang-chu" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold rounded-md">Trang chủ</a>
        <a href="#gioi-thieu" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Giới thiệu</a>
        <a href="#linh-vuc" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Lĩnh vực</a>
        <a href="#san-pham-thi-cong" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Thi công thực tế</a>
        <a href="#du-an-da-nang" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Dự án Đà Nẵng</a>
        <a href="#doi-tac" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Đối tác</a>
        <a href="#bao-gia" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Báo giá</a>
        <a href="#tin-tuc" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Bài viết</a>
        <a href="#lien-he" class="desktop-nav-link px-2 xl:px-3 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold rounded-md">Liên hệ</a>
      </nav>

      <!-- NÚT MENU MOBILE (Không đặt nút Gọi Ngay trên header để tránh tràn viền) -->
      <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-100 focus:outline-none shrink-0" aria-label="Mở menu điều hướng" aria-expanded="false">
        <i class="fa-solid fa-bars text-lg" id="mobileMenuIcon"></i>
      </button>
    </div>

    <!-- MENU XỔ XUỐNG TRÊN ĐIỆN THOẠI -->
    <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="qa-container py-3 flex flex-col divide-y divide-slate-100">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-brand-navy hover:text-brand-gold">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Giới thiệu công ty</a>
        <a href="#linh-vuc" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Lĩnh vực hoạt động</a>
        <a href="#san-pham-thi-cong" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Danh mục &amp; Thi công thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Dự án tại Đà Nẵng</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Đối tác chiến lược</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Yêu cầu &amp; Báo giá</a>
        <a href="#tin-tuc" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Bài viết &amp; Kinh nghiệm</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 px-2 text-sm font-semibold text-slate-700 hover:text-brand-gold">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 1: 2 BANNER TỰ TRƯỢT BẰNG NHAU, CHỮ CÁCH XA VIỀN     -->
    <!-- ===================================================================== -->
    <section class="w-full bg-brand-navyDark">
      <div id="heroSlider" class="hero-slider-grid" aria-roledescription="carousel" aria-label="Banner giới thiệu Quảng An Đà Nẵng">

        <!-- BANNER 1 -->
        <div class="hero-slide-item active" data-slide="0">
          <!-- Ảnh nền công trình thực tế -->
          <img
            src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
            data-gdrive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
            onerror="handleDriveFallback(this)"
            alt="Thi công xây dựng công trình thực tế Quảng An Đà Nẵng"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <!-- Lớp phủ gradient đảm bảo chữ nổi bật rõ nét -->
          <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/80 to-brand-navyDark/70"></div>

          <!-- Nội dung nằm trọn bên trong banner, cách xa viền cả trên điện thoại và máy tính -->
          <div class="relative z-10 w-full">
            <div class="qa-container">
              <div class="px-5 py-10 sm:px-12 sm:py-14 md:px-16 md:py-20 lg:px-20 lg:py-24 max-w-4xl mx-auto text-center">
                <p class="text-brand-goldLight text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.16em] mb-3">
                  CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG
                </p>
                <h1 class="text-white text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug sm:leading-tight mb-4">
                  THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP TẠI ĐÀ NẴNG
                </h1>
                <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed max-w-2xl mx-auto mb-6 sm:mb-8">
                  Kiến tạo không gian sống và công trình bền vững với tiêu chuẩn kỹ thuật chuẩn xác, đội ngũ kỹ sư giàu kinh nghiệm và quy trình giám sát chặt chẽ từ phần thô đến hoàn thiện.
                </p>
                <div class="flex flex-wrap items-center justify-center gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white font-semibold text-xs sm:text-sm px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg shadow-md transition-colors">
                    <i class="fa-solid fa-file-signature"></i>
                    <span>Nhận báo giá miễn phí</span>
                  </a>
                  <a href="#du-an-da-nang" class="inline-flex items-center justify-center gap-2 bg-white/10 hover:bg-white/20 text-white border border-white/40 font-semibold text-xs sm:text-sm px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg transition-colors">
                    <i class="fa-solid fa-building"></i>
                    <span>Xem dự án Đà Nẵng</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER 2 -->
        <div class="hero-slide-item" data-slide="1">
          <!-- Ảnh nền dự án Đà Nẵng thực tế -->
          <img
            src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
            data-gdrive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
            onerror="handleDriveFallback(this)"
            alt="Dự án xây dựng tiêu biểu tại Đà Nẵng - Quảng An Đà Nẵng"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/80 to-brand-navyDark/70"></div>

          <!-- Nội dung nằm trọn bên trong banner, khoảng cách lề rộng giống hệt Banner 1 -->
          <div class="relative z-10 w-full">
            <div class="qa-container">
              <div class="px-5 py-10 sm:px-12 sm:py-14 md:px-16 md:py-20 lg:px-20 lg:py-24 max-w-4xl mx-auto text-center">
                <p class="text-brand-goldLight text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.16em] mb-3">
                  AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ
                </p>
                <h2 class="text-white text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug sm:leading-tight mb-4">
                  NHÀ PHỐ – BIỆT THỰ – KHÁCH SẠN – VĂN PHÒNG ĐẠT CHUẨN KỸ THUẬT
                </h2>
                <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed max-w-2xl mx-auto mb-6 sm:mb-8">
                  Cam kết vật tư chính hãng, báo giá minh bạch không phát sinh và chính sách bảo hành công trình lâu dài tại khu vực Đà Nẵng và miền Trung.
                </p>
                <div class="flex flex-wrap items-center justify-center gap-3">
                  <a href="#san-pham-thi-cong" class="inline-flex items-center justify-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white font-semibold text-xs sm:text-sm px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg shadow-md transition-colors">
                    <i class="fa-solid fa-helmet-safety"></i>
                    <span>Xem thi công thực tế</span>
                  </a>
                  <a href="tel:0395398653" class="inline-flex items-center justify-center gap-2 bg-white/10 hover:bg-white/20 text-white border border-white/40 font-semibold text-xs sm:text-sm px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg transition-colors">
                    <i class="fa-solid fa-phone-volume"></i>
                    <span>Hotline: 0395.398.653</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút chuyển slide trái/phải (chỉ hiện trên màn hình rộng để không che chữ trên điện thoại) -->
        <button id="prevSlideBtn" type="button" class="hidden md:flex absolute left-4 lg:left-6 top-1/2 -translate-y-1/2 z-20 w-10 h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white items-center justify-center transition-colors focus:outline-none" aria-label="Banner trước">
          <i class="fa-solid fa-chevron-left text-sm"></i>
        </button>
        <button id="nextSlideBtn" type="button" class="hidden md:flex absolute right-4 lg:right-6 top-1/2 -translate-y-1/2 z-20 w-10 h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white items-center justify-center transition-colors focus:outline-none" aria-label="Banner tiếp theo">
          <i class="fa-solid fa-chevron-right text-sm"></i>
        </button>

        <!-- Dấu chấm chỉ báo slide đặt gọn sát đáy banner -->
        <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
          <button type="button" class="hero-dot w-7 h-2 rounded-full bg-brand-gold transition-all" data-slide-to="0" aria-label="Chuyển tới banner 1"></button>
          <button type="button" class="hero-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white/80 transition-all" data-slide-to="1" aria-label="Chuyển tới banner 2"></button>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 2: DỊCH VỤ TIÊU BIỂU (Theo web mẫu Tín Trường Thịnh) -->
    <!-- ===================================================================== -->
    <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
      <div class="qa-container">
        <div class="text-center mb-8 sm:mb-10">
          <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Lĩnh vực hoạt động</p>
          <h2 class="section-title-bar text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
            Dịch Vụ Tiêu Biểu
          </h2>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Dịch vụ 1 -->
          <div class="flatsome-card bg-brand-bgSoft border border-slate-200 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-goldLight flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
              <i class="fa-solid fa-compass-drafting"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thiết Kế Kiến Trúc</h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              Thiết kế nhà phố, biệt thự, khách sạn, căn hộ và văn phòng tối ưu công năng, thẩm mỹ hiện đại.
            </p>
          </div>

          <!-- Dịch vụ 2 -->
          <div class="flatsome-card bg-brand-bgSoft border border-slate-200 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-goldLight flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
              <i class="fa-solid fa-trowel-bricks"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thi Công Phần Thô</h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              Thi công móng, kết cấu bê tông cốt thép, xây tô đúng tiêu chuẩn kỹ thuật, đảm bảo độ bền vững.
            </p>
          </div>

          <!-- Dịch vụ 3 -->
          <div class="flatsome-card bg-brand-bgSoft border border-slate-200 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-goldLight flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
              <i class="fa-solid fa-paint-roller"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thi Công Hoàn Thiện</h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              Ốp lát, sơn nước, lắp đặt hệ thống điện nước M&amp;E, cửa nhôm kính sắc nét từng chi tiết.
            </p>
          </div>

          <!-- Dịch vụ 4 -->
          <div class="flatsome-card bg-brand-bgSoft border border-slate-200 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-goldLight flex items-center justify-center text-xl sm:text-2xl mb-3 sm:mb-4">
              <i class="fa-solid fa-couch"></i>
            </div>
            <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-2">Thi Công Nội Thất</h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              Hoàn thiện nội thất đồng bộ chìa khóa trao tay cho nhà ở, căn hộ cho thuê, khách sạn và văn phòng.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 3: GIỚI THIỆU CÔNG TY & THẾ MẠNH                     -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-bgSoft border-y border-slate-200">
      <div class="qa-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <!-- Cột ảnh giới thiệu -->
          <div class="lg:col-span-5">
            <div class="rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm">
              <img
                src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                data-gdrive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                onerror="handleDriveFallback(this)"
                alt="Thi công công trình Công ty TNHH Đầu tư Xây dựng Quảng An Đà Nẵng"
                class="w-full aspect-[4/3] object-cover"
              />
            </div>
          </div>

          <!-- Cột nội dung giới thiệu -->
          <div class="lg:col-span-7">
            <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Về chúng tôi</p>
            <h2 class="section-title-bar section-title-bar-left text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy mb-5">
              CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG
            </h2>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-4">
              <strong>QUẢNG AN ĐÀ NẴNG</strong> (MST: 0402207205) là đơn vị chuyên sâu trong lĩnh vực Thiết kế kiến trúc, Thi công xây dựng công trình dân dụng, công nghiệp, hạ tầng kỹ thuật và hoàn thiện nội ngoại thất tại khu vực Thành phố Đà Nẵng và miền Trung.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-6">
              Với phương châm <strong>“An toàn – Chất lượng – Tiến độ – Sự hài lòng của Khách hàng”</strong>, chúng tôi đặt chữ <strong>TÂM</strong> lên hàng đầu trong từng hạng mục thi công, cam kết sử dụng vật liệu chuẩn nguồn gốc, quy trình giám sát kỹ thuật nghiêm ngặt và chi phí đầu tư tối ưu nhất.
            </p>

            <!-- 6 Thế mạnh cốt lõi (Theo cấu trúc web mẫu Tín Trường Thịnh) -->
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-user-tie text-brand-gold text-lg mt-0.5 shrink-0"></i>
                <div>
                  <h4 class="text-sm font-bold text-brand-navy">Đội ngũ kỹ sư chuyên nghiệp</h4>
                  <p class="text-xs text-slate-600 mt-0.5">Kiến trúc sư sáng tạo cùng kỹ sư giám sát và tổ đội thợ lành nghề.</p>
                </div>
              </div>
              <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-layer-group text-brand-gold text-lg mt-0.5 shrink-0"></i>
                <div>
                  <h4 class="text-sm font-bold text-brand-navy">Cập nhật giải pháp hiện đại</h4>
                  <p class="text-xs text-slate-600 mt-0.5">Ứng dụng vật liệu mới và biện pháp thi công tiên tiến, bền vững.</p>
                </div>
              </div>
              <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-clipboard-check text-brand-gold text-lg mt-0.5 shrink-0"></i>
                <div>
                  <h4 class="text-sm font-bold text-brand-navy">Giám sát tiến độ chuẩn xác</h4>
                  <p class="text-xs text-slate-600 mt-0.5">Báo cáo tiến độ thường xuyên, bàn giao công trình đúng cam kết.</p>
                </div>
              </div>
              <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-shield-halved text-brand-gold text-lg mt-0.5 shrink-0"></i>
                <div>
                  <h4 class="text-sm font-bold text-brand-navy">Bảo hành công trình lâu dài</h4>
                  <p class="text-xs text-slate-600 mt-0.5">Chính sách hậu mãi rõ ràng, hỗ trợ kỹ thuật nhanh chóng khi cần.</p>
                </div>
              </div>
              <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-hand-holding-dollar text-brand-gold text-lg mt-0.5 shrink-0"></i>
                <div>
                  <h4 class="text-sm font-bold text-brand-navy">Chi phí hợp lý, minh bạch</h4>
                  <p class="text-xs text-slate-600 mt-0.5">Dự toán chi tiết từng hạng mục, tối ưu ngân sách cho chủ đầu tư.</p>
                </div>
              </div>
              <div class="flex items-start gap-3 bg-white p-3.5 rounded-lg border border-slate-200">
                <i class="fa-solid fa-headset text-brand-gold text-lg mt-0.5 shrink-0"></i>
                <div>
                  <h4 class="text-sm font-bold text-brand-navy">Tư vấn miễn phí 24/7</h4>
                  <p class="text-xs text-slate-600 mt-0.5">Hỗ trợ khảo sát thực tế và tư vấn phương án thi công tận nơi.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 4: DANH MỤC SẢN PHẨM & THI CÔNG THỰC TẾ (9 ẢNH THẬT) -->
    <!-- Chia 2 cột trên điện thoại, tên đầy đủ không tràn/thiếu chữ, không nhãn dán -->
    <!-- ===================================================================== -->
    <section id="san-pham-thi-cong" class="py-10 sm:py-14 bg-white">
      <div class="qa-container">
        <div class="text-center mb-6 sm:mb-8">
          <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Hình ảnh thực tế tại công trường</p>
          <h2 class="section-title-bar text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
            Danh Mục Thi Công &amp; Sản Phẩm Xây Dựng
          </h2>
        </div>

        <!-- Thanh lọc danh mục: chữ nhỏ gọn, tên danh mục không xuống dòng, sắp xếp đẹp trên PC & Mobile -->
        <div id="productFilterBar" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
          <button type="button" class="cat-pill active px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="all">Tất cả</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="phan-tho">Thi công phần thô</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="hoan-thien">Thi công hoàn thiện</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="kien-truc">Thiết kế kiến trúc</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="noi-that">Thi công nội thất</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="nha-pho">Nhà phố – Biệt thự</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="khach-san">Khách sạn – Căn hộ</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-filter="van-phong">Văn phòng – Hạ tầng</button>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 4 cột desktop -->
        <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render động từ mảng dữ liệu 9 ảnh thực tế Google Drive -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 5: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH THẬT)     -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-bgSoft border-y border-slate-200">
      <div class="qa-container">
        <div class="text-center mb-6 sm:mb-8">
          <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Công trình tiêu biểu</p>
          <h2 class="section-title-bar text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
            Các Dự Án Tại Đà Nẵng
          </h2>
        </div>

        <!-- Bộ lọc danh mục dự án Đà Nẵng (chữ nhỏ gọn, không xuống dòng tên danh mục) -->
        <div id="projectFilterBar" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
          <button type="button" class="cat-pill active px-3 py-1.5 rounded-lg border border-slate-300 bg-white text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-project-filter="all">Tất cả dự án</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 bg-white text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-project-filter="nha-pho">Nhà phố Đà Nẵng</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 bg-white text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-project-filter="biet-thu">Biệt thự</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 bg-white text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-project-filter="khach-san">Khách sạn – Căn hộ</button>
          <button type="button" class="cat-pill px-3 py-1.5 rounded-lg border border-slate-300 bg-white text-[11px] sm:text-xs font-semibold text-slate-700 hover:border-brand-navy" data-project-filter="van-phong">Văn phòng – Dân dụng</button>
        </div>

        <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 3 cột tablet, 5 cột trên màn hình lớn -->
        <div id="projectGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render động từ mảng dữ liệu 10 ảnh dự án Đà Nẵng Google Drive -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 6: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ                  -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
      <div class="qa-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <!-- Thông tin cam kết tư vấn bên trái -->
          <div class="lg:col-span-5">
            <p class="text-brand-goldLight text-xs font-bold uppercase tracking-widest mb-2">Miễn phí tư vấn &amp; dự toán</p>
            <h2 class="text-2xl sm:text-3xl font-extrabold leading-tight mb-4">
              ĐĂNG KÝ YÊU CẦU &amp; NHẬN BÁO GIÁ XÂY DỰNG
            </h2>
            <p class="text-sm sm:text-[15px] text-slate-200 leading-relaxed mb-6">
              Quý khách vui lòng để lại thông tin loại công trình và nhu cầu xây dựng. Kỹ sư của <strong>Quảng An Đà Nẵng</strong> sẽ liên hệ khảo sát thực tế và gửi bảng dự toán chi tiết trong thời gian sớm nhất.
            </p>
            <div class="space-y-3 text-sm text-slate-100">
              <div class="flex items-center gap-3">
                <span class="w-9 h-9 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-phone"></i>
                </span>
                <div>
                  <div class="text-xs text-slate-300">Hotline tư vấn trực tiếp</div>
                  <a href="tel:0395398653" class="font-bold text-base hover:text-brand-goldLight">0395.398.653</a>
                </div>
              </div>
              <div class="flex items-center gap-3">
                <span class="w-9 h-9 rounded-lg bg-white/10 text-brand-goldLight flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-location-dot"></i>
                </span>
                <div>
                  <div class="text-xs text-slate-300">Văn phòng giao dịch</div>
                  <div class="font-medium">145 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP Đà Nẵng</div>
                </div>
              </div>
            </div>
          </div>

          <!-- Form đăng ký bên phải (Theo chuẩn form web mẫu Tín Trường Thịnh) -->
          <div class="lg:col-span-7">
            <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                  <input id="qName" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 outline-none" />
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại *</label>
                  <input id="qPhone" name="phone" type="tel" required placeholder="VD: 0395.398.653" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 outline-none" />
                </div>
                <div>
                  <label for="qEmail" class="block text-xs font-semibold text-slate-700 mb-1.5">Email</label>
                  <input id="qEmail" name="email" type="email" placeholder="Nhập địa chỉ email" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 outline-none" />
                </div>
                <div>
                  <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                  <select id="qType" name="type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 outline-none">
                    <option value="Nhà phố">Nhà phố</option>
                    <option value="Biệt thự">Biệt thự</option>
                    <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                    <option value="Văn phòng - Nhà xưởng">Văn phòng – Nhà xưởng</option>
                    <option value="Thi công phần thô">Thi công phần thô</option>
                    <option value="Thi công hoàn thiện & Nội thất">Thi công hoàn thiện &amp; Nội thất</option>
                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                  </select>
                </div>
                <div class="sm:col-span-2">
                  <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                  <select id="qBudget" name="budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 outline-none">
                    <option value="Chưa xác định">Chưa xác định (Cần tư vấn)</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
                <div class="sm:col-span-2">
                  <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết (diện tích, số tầng, vị trí xây dựng...)</label>
                  <textarea id="qNote" name="note" rows="3" placeholder="Mô tả sơ bộ nhu cầu xây dựng của quý khách..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-navy focus:ring-2 focus:ring-brand-navy/15 outline-none resize-none"></textarea>
                </div>
              </div>

              <div class="mt-5 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                <button type="submit" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-sm px-7 py-3 rounded-lg shadow transition-colors">
                  <i class="fa-solid fa-paper-plane"></i>
                  <span>Gửi yêu cầu báo giá</span>
                </button>
                <span class="text-xs text-slate-500">Thông tin của quý khách được bảo mật tuyệt đối.</span>
              </div>

              <!-- Thông báo phản hồi trực tiếp (không dùng alert) -->
              <div id="quoteFeedback" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-sm font-medium"></div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 7: DANH MỤC CÁC ĐỐI TÁC                              -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-14 bg-white border-b border-slate-200">
      <div class="qa-container">
        <div class="text-center mb-8">
          <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Hợp tác cung ứng vật tư chính hãng</p>
          <h2 class="section-title-bar text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
            Đối Tác Chiến Lược
          </h2>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
          <div class="bg-brand-bgSoft border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-gold transition-colors">
            <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">HÒA PHÁT</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thép Xây Dựng</span>
          </div>
          <div class="bg-brand-bgSoft border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-gold transition-colors">
            <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">VIỆT NHẬT</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thép Vina Kyoei</span>
          </div>
          <div class="bg-brand-bgSoft border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-gold transition-colors">
            <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">SÔNG GIANH</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Xi Măng Chất Lượng</span>
          </div>
          <div class="bg-brand-bgSoft border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-gold transition-colors">
            <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">JOTUN</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn Nội Ngoại Thất</span>
          </div>
          <div class="bg-brand-bgSoft border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-gold transition-colors">
            <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">CADIVI</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Dây Cáp Điện</span>
          </div>
          <div class="bg-brand-bgSoft border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center min-h-[88px] hover:border-brand-gold transition-colors">
            <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">VIGLACERA</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Vật Liệu Hoàn Thiện</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ                   -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-brand-bgSoft border-b border-slate-200">
      <div class="qa-container">
        <div class="text-center mb-8">
          <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Kiến thức &amp; Cẩm nang xây dựng</p>
          <h2 class="section-title-bar text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
            Bài Viết &amp; Tin Tức Mới Nhất
          </h2>
        </div>

        <div id="articleGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <!-- Render động danh sách bài viết trang chủ -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 9: GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ     -->
    <!-- ===================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white">
      <div class="qa-container">
        <div class="text-center mb-8">
          <p class="text-brand-gold text-xs font-bold uppercase tracking-widest mb-1.5">Kết nối trực tiếp cùng Quảng An Đà Nẵng</p>
          <h2 class="section-title-bar text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
            Bản Đồ Chỉ Đường &amp; Fanpage Chính Thức
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
          <!-- Cột trái: Google Map 145 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP Đà Nẵng -->
          <div class="lg:col-span-7 flex flex-col bg-brand-bgSoft border border-slate-200 rounded-xl overflow-hidden shadow-sm">
            <div class="px-4 py-3 bg-brand-navy text-white flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2 text-sm font-bold">
                <i class="fa-solid fa-map-location-dot text-brand-goldLight"></i>
                <span>Bản đồ: 145 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP Đà Nẵng</span>
              </div>
              <a
                href="https://www.google.com/maps/search/?api=1&query=145+X%C3%B4+Vi%E1%BA%BFt+Ngh%E1%BB%87+T%C4%A9nh,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-brand-goldLight hover:underline whitespace-nowrap"
              >
                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
              </a>
            </div>
            <div class="w-full flex-1 min-h-[300px] sm:min-h-[340px]">
              <iframe
                title="Bản đồ Công ty TNHH Đầu tư Xây dựng Quảng An Đà Nẵng - 145 Xô Viết Nghệ Tĩnh, Cẩm Lệ, Đà Nẵng"
                src="https://maps.google.com/maps?q=145%20X%C3%B4%20Vi%E1%BA%BFt%20Ngh%E1%BB%87%20T%C4%A9nh,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full min-h-[300px] sm:min-h-[340px] border-0 block"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Cột phải: Fanpage Facebook ngoài trang chủ -->
          <div class="lg:col-span-5 flex flex-col bg-brand-bgSoft border border-slate-200 rounded-xl overflow-hidden shadow-sm">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
              <div class="flex items-center gap-2 text-sm font-bold">
                <i class="fa-brands fa-facebook text-base"></i>
                <span>Fanpage Facebook Chính Thức</span>
              </div>
              <span class="text-xs text-white/90">quangandanang.com</span>
            </div>

            <!-- Hộp giao diện Fanpage đồng bộ chuẩn Facebook Page Plugin -->
            <div class="p-4 flex-1 flex flex-col justify-between bg-white">
              <div>
                <!-- Ảnh bìa Fanpage -->
                <div class="relative rounded-lg overflow-hidden border border-slate-200 h-36 sm:h-40 bg-brand-navy">
                  <img
                    src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                    data-gdrive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                    onerror="handleDriveFallback(this)"
                    alt="Fanpage Công ty TNHH Đầu tư Xây dựng Quảng An Đà Nẵng"
                    class="w-full h-full object-cover"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                  <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                    <!-- Avatar Logo -->
                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                      <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect width="64" height="64" rx="10" fill="#0E3A5D"/>
                        <path d="M12 46L32 15L52 46H43.5L32 27.5L20.5 46H12Z" fill="#D98218"/>
                        <path d="M26 46V35.5L32 31L38 35.5V46H34.2V39.5H29.8V46H26Z" fill="#FFFFFF"/>
                      </svg>
                    </div>
                    <div class="min-w-0">
                      <h3 class="text-white font-bold text-sm leading-snug">
                        Xây Dựng Quảng An Đà Nẵng
                      </h3>
                      <p class="text-slate-200 text-xs mt-0.5">Công ty Xây dựng &amp; Thiết kế tại Đà Nẵng</p>
                    </div>
                  </div>
                </div>

                <!-- Bài đăng nổi bật trên Fanpage -->
                <div class="mt-4 space-y-2.5 text-xs text-slate-600">
                  <div class="p-3 rounded-lg bg-brand-bgSoft border border-slate-200">
                    <p class="font-semibold text-brand-navy mb-1">Cập nhật tiến độ thi công công trình tại Đà Nẵng</p>
                    <p class="leading-relaxed">Theo dõi hình ảnh nghiệm thu phần thô, hoàn thiện nhà phố, biệt thự và bảng giá xây dựng trọn gói mới nhất từ Quảng An Đà Nẵng.</p>
                  </div>
                  <div class="flex flex-wrap items-center gap-x-4 gap-y-1 text-slate-600 px-1">
                    <span><i class="fa-solid fa-phone text-[#1877F2] mr-1"></i>0395.398.653</span>
                    <span><i class="fa-solid fa-globe text-[#1877F2] mr-1"></i>quangandanang.com</span>
                  </div>
                </div>
              </div>

              <!-- Nút tương tác Fanpage -->
              <div class="mt-4 pt-3 border-t border-slate-200 grid grid-cols-2 gap-2.5">
                <a
                  href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20%C4%90%E1%BA%A7u%20t%C6%B0%20X%C3%A2y%20d%E1%BB%B1ng%20Qu%E1%BA%A3ng%20An%20%C4%90%C3%A0%20N%E1%BA%B5ng"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="inline-flex items-center justify-center gap-1.5 bg-[#1877F2] hover:bg-[#1464CC] text-white font-semibold text-xs py-2.5 px-3 rounded-lg transition-colors"
                >
                  <i class="fa-brands fa-facebook-f"></i>
                  <span>Theo dõi Fanpage</span>
                </a>
                <a
                  href="https://zalo.me/0395398653"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="inline-flex items-center justify-center gap-1.5 bg-brand-navy hover:bg-brand-navyDark text-white font-semibold text-xs py-2.5 px-3 rounded-lg transition-colors"
                >
                  <i class="fa-solid fa-comments"></i>
                  <span>Nhắn tin tư vấn</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ===================================================================== -->
  <!-- FLATSOME FOOTER                                                       -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-navyDark text-slate-300 pt-10 sm:pt-12 pb-6 border-t-4 border-brand-gold">
    <div class="qa-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-2.5 mb-4">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect width="64" height="64" rx="11" fill="#0E3A5D"/>
              <path d="M12 46L32 15L52 46H43.5L32 27.5L20.5 46H12Z" fill="#D98218"/>
              <path d="M26 46V35.5L32 31L38 35.5V46H34.2V39.5H29.8V46H26Z" fill="#FFFFFF"/>
              <rect x="12" y="49" width="40" height="3.2" rx="1.6" fill="#FFFFFF" fill-opacity="0.9"/>
            </svg>
            <div>
              <div class="text-white font-extrabold text-base tracking-tight">QUẢNG AN <span class="text-brand-goldLight">ĐÀ NẴNG</span></div>
              <div class="text-[11px] text-slate-400">quangandanang.com</div>
            </div>
          </div>
          <p class="text-sm font-bold text-white mb-2">CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG</p>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-brand-goldLight mt-1 shrink-0"></i>
              <span>Địa chỉ: 145 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-brand-goldLight shrink-0"></i>
              <span>Hotline: <a href="tel:0395398653" class="text-white font-semibold hover:text-brand-goldLight">0395.398.653</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-brand-goldLight shrink-0"></i>
              <span>Website: <a href="https://quangandanang.com" class="hover:text-brand-goldLight">quangandanang.com</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-id-card text-brand-goldLight shrink-0"></i>
              <span>Mã số thuế: 0402207205</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h3 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Lĩnh vực hoạt động</h3>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham-thi-cong" class="hover:text-brand-goldLight transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#san-pham-thi-cong" class="hover:text-brand-goldLight transition-colors">Thi công phần thô trọn gói</a></li>
            <li><a href="#san-pham-thi-cong" class="hover:text-brand-goldLight transition-colors">Thi công hoàn thiện công trình</a></li>
            <li><a href="#san-pham-thi-cong" class="hover:text-brand-goldLight transition-colors">Thi công nội thất chìa khóa trao tay</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition-colors">Xây dựng nhà phố, biệt thự Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Liên kết nhanh -->
        <div class="lg:col-span-4">
          <h3 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Liên kết nhanh</h3>
          <div class="grid grid-cols-2 gap-2 text-xs sm:text-sm mb-4">
            <a href="#trang-chu" class="hover:text-brand-goldLight transition-colors">Trang chủ</a>
            <a href="#gioi-thieu" class="hover:text-brand-goldLight transition-colors">Giới thiệu</a>
            <a href="#san-pham-thi-cong" class="hover:text-brand-goldLight transition-colors">Thi công thực tế</a>
            <a href="#du-an-da-nang" class="hover:text-brand-goldLight transition-colors">Dự án Đà Nẵng</a>
            <a href="#doi-tac" class="hover:text-brand-goldLight transition-colors">Đối tác</a>
            <a href="#bao-gia" class="hover:text-brand-goldLight transition-colors">Yêu cầu báo giá</a>
            <a href="#tin-tuc" class="hover:text-brand-goldLight transition-colors">Bài viết</a>
            <a href="#lien-he" class="hover:text-brand-goldLight transition-colors">Liên hệ &amp; Bản đồ</a>
          </div>
          <p class="text-xs text-slate-400">
            Thời gian làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30). Hỗ trợ tư vấn kỹ thuật 24/7 qua Hotline &amp; Zalo.
          </p>
        </div>
      </div>

      <div class="pt-5 text-center text-xs text-slate-400">
        Copyright &copy; 2026 CÔNG TY TNHH ĐẦU TƯ XÂY DỰNG QUẢNG AN ĐÀ NẴNG (quangandanang.com). All rights reserved.
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (PC & MOBILE)       -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-4 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0395398653"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Liên hệ Zalo Quảng An Đà Nẵng"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054CC] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20%C4%90%E1%BA%A7u%20t%C6%B0%20X%C3%A2y%20d%E1%BB%B1ng%20Qu%E1%BA%A3ng%20An%20%C4%90%C3%A0%20N%E1%BA%B5ng"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Fanpage Facebook Quảng An Đà Nẵng"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464CC] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0395398653"
      aria-label="Gọi Hotline 0395.398.653"
      class="hotline-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition-all"
    >
      <span class="w-6 h-6 rounded-full bg-white text-brand-gold flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="text-xs font-extrabold pr-1 whitespace-nowrap">0395.398.653</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM ẢNH CHI TIẾT CÔNG TRÌNH / BÀI VIẾT                          -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="hidden fixed inset-0 z-50 bg-black/75 backdrop-blur-xs flex items-center justify-center p-4" role="dialog" aria-modal="true">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-navy pr-4">Chi tiết</h3>
        <button id="closeModalBtn" type="button" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0" aria-label="Đóng cửa sổ">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6">
        <div class="rounded-lg overflow-hidden bg-slate-100 mb-4 border border-slate-200">
          <img id="modalImage" src="" alt="" class="w-full max-h-[55vh] object-contain mx-auto bg-slate-900" />
        </div>
        <p id="modalCategory" class="text-xs font-semibold text-brand-gold uppercase tracking-wider mb-1.5"></p>
        <p id="modalDesc" class="text-sm text-slate-700 leading-relaxed mb-5"></p>
        <div class="flex flex-wrap items-center gap-2.5">
          <a href="#bao-gia" id="modalQuoteBtn" class="inline-flex items-center gap-2 bg-brand-navy hover:bg-brand-navyDark text-white text-xs sm:text-sm font-semibold px-4 py-2.5 rounded-lg transition-colors">
            <i class="fa-solid fa-file-invoice"></i>
            <span>Yêu cầu báo giá hạng mục này</span>
          </a>
          <a href="tel:0395398653" class="inline-flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold px-4 py-2.5 rounded-lg transition-colors">
            <i class="fa-solid fa-phone"></i>
            <span>Gọi 0395.398.653</span>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: TẢI ẢNH GOOGLE DRIVE, SLIDER, LỌC DANH MỤC, FORM & MODAL  -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Hàm dự phòng khi ảnh Google Drive cần chuyển đổi định dạng đường dẫn trực tiếp
     * Ưu tiên: drive.google.com/thumbnail -> lh3.googleusercontent.com -> ảnh placeholder
     */
    function handleDriveFallback(img) {
      const id = img.getAttribute('data-gdrive-id');
      const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);

      if (step === 0 && id) {
        img.setAttribute('data-fallback-step', '1');
        img.src = 'https://lh3.googleusercontent.com/d/' + id + '=w1200';
      } else if (step === 1 && id) {
        img.setAttribute('data-fallback-step', '2');
        img.src = 'https://drive.google.com/uc?export=view&id=' + id;
      } else {
        img.onerror = null;
        img.src = 'https://placehold.co/800x600/0E3A5D/FFFFFF?text=Quang+An+Da+Nang';
      }
    }

    /**
     * Dữ liệu 9 ảnh thực tế thi công xây dựng từ Google Drive khách hàng cung cấp
     * Phân loại khớp danh mục web mẫu Tín Trường Thịnh
     */
    const constructionProducts = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công phần thô kết cấu bê tông cốt thép',
        category: 'phan-tho',
        categoryName: 'Thi công phần thô',
        desc: 'Thi công lắp dựng cốt thép, cốp pha và đổ bê tông đúng quy trình kỹ thuật, kiểm soát nghiêm ngặt độ sụt và chất lượng kết cấu công trình.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi công móng, dầm sàn và hệ khung chịu lực',
        category: 'phan-tho',
        categoryName: 'Thi công phần thô',
        desc: 'Thi công hệ thống móng băng, móng cọc và sàn bê tông cốt thép vững chắc, đảm bảo an toàn chịu lực lâu dài cho công trình dân dụng.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi công hoàn thiện mặt tiền kiến trúc hiện đại',
        category: 'hoan-thien',
        categoryName: 'Thi công hoàn thiện',
        desc: 'Hoàn thiện trát phẳng, sơn chống thấm ngoài trời và lắp đặt hệ mặt dựng kiến trúc bền đẹp theo điều kiện khí hậu miền Trung.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi công xây tô tường, ốp lát gạch và sơn nước',
        category: 'hoan-thien',
        categoryName: 'Thi công hoàn thiện',
        desc: 'Đội ngũ thợ tay nghề cao thực hiện xây tô chuẩn mạch, ốp lát thẩm mỹ và sơn hoàn thiện sắc nét từng góc cạnh không gian.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thiết kế kiến trúc & thi công nhà phố trọn gói',
        category: 'kien-truc',
        categoryName: 'Thiết kế kiến trúc',
        desc: 'Giải pháp thiết kế kiến trúc tối ưu ánh sáng tự nhiên, thông gió và thi công trọn gói chìa khóa trao tay tiết kiệm chi phí.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi công biệt thự & nhà ở gia đình cao cấp',
        category: 'nha-pho',
        categoryName: 'Nhà phố – Biệt thự',
        desc: 'Thi công các hạng mục biệt thự hiện đại, tân cổ điển với yêu cầu kỹ thuật và độ hoàn thiện thẩm mỹ cao nhất.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi công hoàn thiện nội thất gỗ & trang trí',
        category: 'noi-that',
        categoryName: 'Thi công nội thất',
        desc: 'Lắp đặt hoàn thiện trần thạch cao, hệ thống chiếu sáng và đồ nội thất đồng bộ theo bản vẽ thiết kế 3D đã phê duyệt.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi công hạ tầng kỹ thuật & hệ thống cơ điện M&E',
        category: 'van-phong',
        categoryName: 'Văn phòng – Hạ tầng',
        desc: 'Triển khai hệ thống cấp thoát nước, điện dân dụng, chiếu sáng và hạ tầng kỹ thuật đồng bộ đạt chuẩn nghiệm thu.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi công xây dựng khách sạn & căn hộ cho thuê',
        category: 'khach-san',
        categoryName: 'Khách sạn – Căn hộ',
        desc: 'Tổng thầu thi công khách sạn, tòa nhà căn hộ dịch vụ tại Đà Nẵng đảm bảo công năng vận hành và tiến độ bàn giao khai thác.'
      }
    ];

    /**
     * Dữ liệu 10 ảnh Các Dự Án Tại Đà Nẵng từ Google Drive khách hàng cung cấp
     */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự án Nhà phố hiện đại Quận Cẩm Lệ – Đà Nẵng',
        category: 'nha-pho',
        categoryName: 'Nhà phố Đà Nẵng',
        desc: 'Công trình nhà phố thi công trọn gói từ phần thô đến hoàn thiện tại khu vực Cẩm Lệ, TP Đà Nẵng.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự án Biệt thự Khu đô thị Hòa Xuân – Đà Nẵng',
        category: 'biet-thu',
        categoryName: 'Biệt thự',
        desc: 'Thiết kế và thi công biệt thự hiện đại tại KĐT Hòa Xuân với không gian thoáng mát, kết cấu bền vững.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự án Khách sạn & Căn hộ Sơn Trà – Đà Nẵng',
        category: 'khach-san',
        categoryName: 'Khách sạn – Căn hộ',
        desc: 'Hạng mục thi công xây dựng tòa nhà căn hộ lưu trú ven biển Sơn Trà đạt chuẩn chống thấm và an toàn kỹ thuật.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự án Nhà phố trọn gói Hải Châu – Đà Nẵng',
        category: 'nha-pho',
        categoryName: 'Nhà phố Đà Nẵng',
        desc: 'Thi công xây dựng nhà phố trung tâm Hải Châu, tổ chức mặt bằng gọn gàng và đảm bảo tiến độ cam kết.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự án Văn phòng kết hợp Showroom Thanh Khê',
        category: 'van-phong',
        categoryName: 'Văn phòng – Dân dụng',
        desc: 'Thi công cải tạo và xây mới không gian văn phòng làm việc hiện đại tại quận Thanh Khê, Đà Nẵng.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự án Căn hộ cho thuê Ngũ Hành Sơn – Đà Nẵng',
        category: 'khach-san',
        categoryName: 'Khách sạn – Căn hộ',
        desc: 'Thi công trọn gói hệ thống căn hộ dịch vụ cao cấp tại Ngũ Hành Sơn tối ưu diện tích và chi phí vận hành.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự án Biệt thự 2 mặt tiền Nam Việt Á – Đà Nẵng',
        category: 'biet-thu',
        categoryName: 'Biệt thự',
        desc: 'Công trình biệt thự góc 2 mặt tiền sang trọng được Quảng An Đà Nẵng thi công và giám sát chặt chẽ.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự án Nhà phố kinh doanh Liên Chiểu – Đà Nẵng',
        category: 'nha-pho',
        categoryName: 'Nhà phố Đà Nẵng',
        desc: 'Thi công nhà phố kết hợp mặt bằng kinh doanh tại khu vực Liên Chiểu với kết cấu chịu lực vượt nhịp tối ưu.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự án Hoàn thiện công trình Khuê Trung – Cẩm Lệ',
        category: 'van-phong',
        categoryName: 'Văn phòng – Dân dụng',
        desc: 'Hạng mục hoàn thiện xây dựng và lắp đặt hệ thống nội ngoại thất trọn gói tại phường Khuê Trung, Cẩm Lệ.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự án Công trình Dân dụng Hòa Vang – Đà Nẵng',
        category: 'van-phong',
        categoryName: 'Văn phòng – Dân dụng',
        desc: 'Thi công xây dựng công trình dân dụng và hạ tầng kỹ thuật đồng bộ tại khu vực Hòa Vang, TP Đà Nẵng.'
      }
    ];

    /**
     * Dữ liệu 4 bài viết trang chủ (đồng bộ chủ đề web mẫu Tín Trường Thịnh)
     */
    const homeArticles = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '15/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng đúng chuẩn kỹ thuật xây dựng',
        excerpt: 'Bảo dưỡng bê tông móng sau khi đổ là bước quan trọng quyết định cường độ chịu lực và tuổi thọ bền vững của công trình.',
        fullContent: 'Trong quá trình thi công phần thô, bê tông móng sau khi đổ cần được giữ ẩm liên tục trong 7 ngày đầu để quá trình thủy hóa xi măng diễn ra hoàn toàn, tránh hiện tượng nứt co ngót bề mặt. Kỹ sư Quảng An Đà Nẵng luôn kiểm tra độ ẩm, che phủ bảo vệ và kiểm định cường độ bê tông trước khi chuyển giai đoạn thi công tiếp theo.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        date: '10/11/2026',
        title: '03 Lưu ý quan trọng giúp chủ đầu tư tối ưu chi phí khi xây nhà tại Đà Nẵng',
        excerpt: 'Lập hồ sơ thiết kế chi tiết, lựa chọn gói vật tư minh bạch và chọn nhà thầu uy tín giúp tránh phát sinh ngân sách.',
        fullContent: 'Để quá trình xây dựng tổ ấm diễn ra suôn sẻ, chủ đầu tư nên chuẩn bị bản vẽ thiết kế kiến trúc – kết cấu – điện nước đầy đủ trước khi khởi công. Đồng thời cần thống nhất chủng loại vật tư ngay trong hợp đồng và lựa chọn đơn vị thi công có quy trình giám sát minh bạch như Quảng An Đà Nẵng.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        date: '04/11/2026',
        title: 'Giải pháp chống thấm hiệu quả cho nhà phố ven biển miền Trung',
        excerpt: 'Khí hậu mưa bão và độ ẩm cao tại Đà Nẵng đòi hỏi quy trình xử lý chống thấm tường ngoài, sân thượng và nhà vệ sinh bài bản.',
        fullContent: 'Tại khu vực Đà Nẵng, hiện tượng thấm dột thường xảy ra ở tường tiếp giáp, sàn mái và khu vực vệ sinh nếu không xử lý kỹ từ giai đoạn phần thô. Sử dụng phụ gia chống thấm chuyên dụng kết hợp màng quét 2 thành phần và thử nước nghiệm thu 48 giờ là tiêu chuẩn bắt buộc tại mọi công trình của Quảng An Đà Nẵng.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        date: '28/10/2026',
        title: 'Kinh nghiệm thiết kế & thi công nội thất tối ưu không gian sống',
        excerpt: 'Bố trí ánh sáng, vật liệu hài hòa và đồng bộ thi công ngay từ phần thô mang lại không gian tiện nghi, sang trọng.',
        fullContent: 'Thiết kế nội thất không chỉ dừng lại ở việc lựa chọn đồ gỗ đẹp mắt mà còn là sự kết hợp khoa học giữa công năng di chuyển, hệ thống chiếu sáng và thông gió tự nhiên. Thi công đồng bộ cùng một đơn vị giúp đường điện, ổ cắm và hệ trần khớp chính xác 100% với bản vẽ nội thất.'
      }
    ];

    /**
     * Render danh mục Sản phẩm & Thi công thực tế (KHÔNG có nhãn dán đè lên ảnh)
     */
    function renderProducts(filterKey) {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      const list = filterKey === 'all'
        ? constructionProducts
        : constructionProducts.filter(item => item.category === filterKey);

      grid.innerHTML = list.map((item, idx) => `
        <article class="flatsome-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col cursor-pointer" onclick="openItemModal('product', ${constructionProducts.indexOf(item)})">
          <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
            <img
              src="https://drive.google.com/thumbnail?id=${item.id}&sz=w800"
              data-gdrive-id="${item.id}"
              onerror="handleDriveFallback(this)"
              alt="${item.title}"
              loading="lazy"
              class="w-full h-full object-cover block"
            />
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <p class="text-[11px] font-semibold text-brand-gold mb-1">${item.categoryName}</p>
              <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy leading-snug break-words">
                ${item.title}
              </h3>
            </div>
            <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-slate-500">
              <span class="font-medium text-brand-navy">Liên hệ báo giá</span>
              <span class="text-brand-gold font-semibold">Chi tiết <i class="fa-solid fa-angle-right ml-0.5"></i></span>
            </div>
          </div>
        </article>
      `).join('');
    }

    /**
     * Render danh mục Các Dự Án Tại Đà Nẵng (KHÔNG có nhãn dán đè lên ảnh)
     */
    function renderProjects(filterKey) {
      const grid = document.getElementById('projectGrid');
      if (!grid) return;

      const list = filterKey === 'all'
        ? danangProjects
        : danangProjects.filter(item => item.category === filterKey);

      grid.innerHTML = list.map(item => `
        <article class="flatsome-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col cursor-pointer" onclick="openItemModal('project', ${danangProjects.indexOf(item)})">
          <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
            <img
              src="https://drive.google.com/thumbnail?id=${item.id}&sz=w800"
              data-gdrive-id="${item.id}"
              onerror="handleDriveFallback(this)"
              alt="${item.title}"
              loading="lazy"
              class="w-full h-full object-cover block"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <p class="text-[11px] font-semibold text-brand-gold mb-1">${item.categoryName}</p>
              <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-navy leading-snug break-words">
                ${item.title}
              </h3>
            </div>
            <div class="mt-2 text-[11px] text-slate-500 flex items-center gap-1">
              <i class="fa-solid fa-location-dot text-brand-gold text-[10px]"></i>
              <span>TP. Đà Nẵng</span>
            </div>
          </div>
        </article>
      `).join('');
    }

    /**
     * Render danh mục Bài viết trang chủ
     */
    function renderArticles() {
      const grid = document.getElementById('articleGrid');
      if (!grid) return;

      grid.innerHTML = homeArticles.map((art, index) => `
        <article class="flatsome-card bg-white border border-slate-200 rounded-xl overflow-hidden flex flex-col cursor-pointer" onclick="openArticleModal(${index})">
          <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
            <img
              src="https://drive.google.com/thumbnail?id=${art.id}&sz=w800"
              data-gdrive-id="${art.id}"
              onerror="handleDriveFallback(this)"
              alt="${art.title}"
              loading="lazy"
              class="w-full h-full object-cover block"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <p class="text-[11px] text-slate-500 mb-1.5"><i class="fa-regular fa-calendar mr-1 text-brand-gold"></i>${art.date}</p>
              <h3 class="text-sm font-bold text-brand-navy leading-snug mb-2 break-words">${art.title}</h3>
              <p class="text-xs text-slate-600 leading-relaxed">${art.excerpt}</p>
            </div>
            <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-semibold text-brand-gold">
              Đọc tiếp <i class="fa-solid fa-arrow-right ml-1"></i>
            </div>
          </div>
        </article>
      `).join('');
    }

    /**
     * Mở modal chi tiết sản phẩm / dự án
     */
    function openItemModal(type, index) {
      const data = type === 'product' ? constructionProducts[index] : danangProjects[index];
      if (!data) return;

      const modal = document.getElementById('detailModal');
      const img = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = data.title;
      document.getElementById('modalCategory').textContent = data.categoryName;
      document.getElementById('modalDesc').textContent = data.desc;

      img.removeAttribute('data-fallback-step');
      img.setAttribute('data-gdrive-id', data.id);
      img.onerror = function() { handleDriveFallback(this); };
      img.src = 'https://drive.google.com/thumbnail?id=' + data.id + '&sz=w1400';
      img.alt = data.title;

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    /**
     * Mở modal đọc chi tiết bài viết
     */
    function openArticleModal(index) {
      const art = homeArticles[index];
      if (!art) return;

      const modal = document.getElementById('detailModal');
      const img = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = art.title;
      document.getElementById('modalCategory').textContent = 'Cẩm nang xây dựng • ' + art.date;
      document.getElementById('modalDesc').textContent = art.fullContent;

      img.removeAttribute('data-fallback-step');
      img.setAttribute('data-gdrive-id', art.id);
      img.onerror = function() { handleDriveFallback(this); };
      img.src = 'https://drive.google.com/thumbnail?id=' + art.id + '&sz=w1400';
      img.alt = art.title;

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    /**
     * Khởi tạo toàn bộ tương tác sau khi tải DOM
     */
    document.addEventListener('DOMContentLoaded', function() {
      // 1. Render dữ liệu ban đầu
      renderProducts('all');
      renderProjects('all');
      renderArticles();

      // 2. Xử lý menu Mobile
      const mobileMenuBtn = document.getElementById('mobileMenuBtn');
      const mobileMenuPanel = document.getElementById('mobileMenuPanel');
      const mobileMenuIcon = document.getElementById('mobileMenuIcon');

      if (mobileMenuBtn && mobileMenuPanel) {
        mobileMenuBtn.addEventListener('click', function() {
          const isOpen = !mobileMenuPanel.classList.contains('hidden');
          mobileMenuPanel.classList.toggle('hidden');
          mobileMenuBtn.setAttribute('aria-expanded', String(!isOpen));
          mobileMenuIcon.className = isOpen ? 'fa-solid fa-bars text-lg' : 'fa-solid fa-xmark text-lg';
        });

        document.querySelectorAll('.mobile-nav-link').forEach(link => {
          link.addEventListener('click', function() {
            mobileMenuPanel.classList.add('hidden');
            mobileMenuBtn.setAttribute('aria-expanded', 'false');
            mobileMenuIcon.className = 'fa-solid fa-bars text-lg';
          });
        });
      }

      // 3. Slider 2 Banner tự trượt chuyên nghiệp (hỗ trợ vuốt cảm ứng trên điện thoại)
      const slides = document.querySelectorAll('.hero-slide-item');
      const dots = document.querySelectorAll('.hero-dot');
      let currentSlide = 0;
      let sliderTimer = null;

      function showSlide(index) {
        currentSlide = (index + slides.length) % slides.length;
        slides.forEach((slide, i) => {
          slide.classList.toggle('active', i === currentSlide);
        });
        dots.forEach((dot, i) => {
          if (i === currentSlide) {
            dot.classList.add('w-7', 'bg-brand-gold');
            dot.classList.remove('w-2.5', 'bg-white/50');
          } else {
            dot.classList.remove('w-7', 'bg-brand-gold');
            dot.classList.add('w-2.5', 'bg-white/50');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        sliderTimer = setInterval(() => showSlide(currentSlide + 1), 5000);
      }

      function stopAutoSlide() {
        if (sliderTimer) clearInterval(sliderTimer);
      }

      const prevBtn = document.getElementById('prevSlideBtn');
      const nextBtn = document.getElementById('nextSlideBtn');
      if (prevBtn) prevBtn.addEventListener('click', () => { showSlide(currentSlide - 1); startAutoSlide(); });
      if (nextBtn) nextBtn.addEventListener('click', () => { showSlide(currentSlide + 1); startAutoSlide(); });

      dots.forEach(dot => {
        dot.addEventListener('click', function() {
          const target = parseInt(this.getAttribute('data-slide-to'), 10);
          showSlide(target);
          startAutoSlide();
        });
      });

      const heroSlider = document.getElementById('heroSlider');
      let touchStartX = 0;
      if (heroSlider) {
        heroSlider.addEventListener('mouseenter', stopAutoSlide);
        heroSlider.addEventListener('mouseleave', startAutoSlide);
        heroSlider.addEventListener('touchstart', (e) => {
          touchStartX = e.changedTouches[0].screenX;
          stopAutoSlide();
        }, { passive: true });
        heroSlider.addEventListener('touchend', (e) => {
          const touchEndX = e.changedTouches[0].screenX;
          if (touchStartX - touchEndX > 45) showSlide(currentSlide + 1);
          if (touchEndX - touchStartX > 45) showSlide(currentSlide - 1);
          startAutoSlide();
        }, { passive: true });
      }
      startAutoSlide();

      // 4. Lọc danh mục Sản phẩm & Thi công thực tế
      document.querySelectorAll('#productFilterBar .cat-pill').forEach(btn => {
        btn.addEventListener('click', function() {
          document.querySelectorAll('#productFilterBar .cat-pill').forEach(b => b.classList.remove('active'));
          this.classList.add('active');
          renderProducts(this.getAttribute('data-filter'));
        });
      });

      // 5. Lọc danh mục Dự án Đà Nẵng
      document.querySelectorAll('#projectFilterBar .cat-pill').forEach(btn => {
        btn.addEventListener('click', function() {
          document.querySelectorAll('#projectFilterBar .cat-pill').forEach(b => b.classList.remove('active'));
          this.classList.add('active');
          renderProjects(this.getAttribute('data-project-filter'));
        });
      });

      // 6. Xử lý Form yêu cầu báo giá trang chủ (thông báo inline, không dùng alert)
      const quoteForm = document.getElementById('quoteForm');
      const quoteFeedback = document.getElementById('quoteFeedback');
      if (quoteForm && quoteFeedback) {
        quoteForm.addEventListener('submit', function(e) {
          e.preventDefault();
          const name = document.getElementById('qName').value.trim();
          const phone = document.getElementById('qPhone').value.trim();
          const type = document.getElementById('qType').value;

          quoteFeedback.innerHTML =
            '<i class="fa-solid fa-circle-check mr-2 text-emerald-600"></i>' +
            'Cảm ơn <strong>' + name + '</strong>! Yêu cầu tư vấn hạng mục <strong>' + type + '</strong> đã được ghi nhận. Kỹ sư Quảng An Đà Nẵng sẽ gọi lại qua số <strong>' + phone + '</strong> trong thời gian sớm nhất.';
          quoteFeedback.classList.remove('hidden');
          quoteForm.reset();
        });
      }

      // 7. Đóng Modal
      const closeModalBtn = document.getElementById('closeModalBtn');
      const detailModal = document.getElementById('detailModal');
      const modalQuoteBtn = document.getElementById('modalQuoteBtn');
      if (closeModalBtn) closeModalBtn.addEventListener('click', closeDetailModal);
      if (modalQuoteBtn) modalQuoteBtn.addEventListener('click', closeDetailModal);
      if (detailModal) {
        detailModal.addEventListener('click', function(e) {
          if (e.target === detailModal) closeDetailModal();
        });
      }
      document.addEventListener('keydown', function(e) {
        if (e.key === 'Escape') closeDetailModal();
      });
    });
  </script>
</body>
</html>
