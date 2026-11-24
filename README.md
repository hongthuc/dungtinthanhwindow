<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>Dũng Tín Thành Window | Công Ty TNHH SX & TM D.T.T 46 - Cửa Nhôm Xingfa Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI D.T.T 46 (Dũng Tín Thành Window) chuyên sản xuất, thi công Cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp uy tín tại Đà Nẵng. Hotline: 0905.959.991." />

  <!-- Ảnh thumbnail chia sẻ link website (sử dụng logo công ty) -->
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w500" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://dungtinthanhwindow.com/" />
  <meta property="og:title" content="Dũng Tín Thành Window - Công Ty TNHH SX & TM D.T.T 46 | Nhôm Kính Đà Nẵng" />
  <meta property="og:description" content="Chuyên thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng. Địa chỉ: 14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng. Hotline: 0905.959.991." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w1000" />
  <meta property="og:image:alt" content="Logo Công Ty TNHH SX & TM D.T.T 46 - Dũng Tín Thành Window" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Dũng Tín Thành Window - Cửa Nhôm Xingfa Đà Nẵng" />
  <meta name="twitter:description" content="Sản xuất và thi công nhôm kính trọn gói tại Đà Nẵng. Hotline: 0905.959.991." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w1000" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#eef6fc',
              100: '#d7eaf8',
              200: '#b3d7f2',
              500: '#1668b3',
              600: '#0d4f8c',
              700: '#0a3d6e',
              800: '#072d52',
              900: '#041f3a',
            },
            accent: {
              500: '#e02424',
              600: '#c81e1e',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* ==========================================================================
       FLATSOME-STYLE LAYOUT & ANTI-OVERFLOW RULES
       Cấu trúc gọn gàng dễ dàng dựng lại trên UX Builder (Flatsome)
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      scroll-behavior: smooth;
      font-family: 'Inter', sans-serif;
      color: #1e293b;
      background-color: #ffffff;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
    .ux-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .ux-container {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    @media (min-width: 1024px) {
      .ux-container {
        width: 95%;
        max-width: 95vw;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Header Navigation: Tên danh mục máy tính viết liền 1 hàng, không xuống dòng */
    .desktop-nav-list {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      flex-wrap: nowrap;
      gap: 2px;
    }

    .desktop-nav-link {
      white-space: nowrap;
      flex-shrink: 0;
      font-size: clamp(11px, 0.9vw, 13.5px);
      font-weight: 600;
      letter-spacing: -0.01em;
      padding: 8px clamp(5px, 0.65vw, 11px);
      color: #0a3d6e;
      border-radius: 6px;
      transition: all 0.2s ease;
      display: inline-flex;
      align-items: center;
      gap: 4px;
    }

    .desktop-nav-link:hover,
    .desktop-nav-link.active {
      color: #ffffff;
      background-color: #0d4f8c;
    }

    /* Dropdown Menu Flatsome Style */
    .nav-dropdown-wrap {
      position: relative;
    }

    .nav-dropdown-menu {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-top: 3px solid #0d4f8c;
      border-radius: 0 0 10px 10px;
      box-shadow: 0 12px 28px rgba(10, 61, 110, 0.14);
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 60;
      padding: 6px 0;
    }

    .nav-dropdown-wrap:hover .nav-dropdown-menu,
    .nav-dropdown-wrap:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Hero Banner Slider: 2 banner có kích thước 100% bằng nhau trên mọi thiết bị */
    .hero-slider-grid {
      display: grid;
      grid-template-areas: "slide";
      position: relative;
      width: 100%;
      overflow: hidden;
    }

    .hero-slide-item {
      grid-area: slide;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.65s ease, visibility 0.65s ease;
      z-index: 1;
      display: flex;
      align-items: center;
    }

    .hero-slide-item.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Section Title Flatsome Style */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }

    .flatsome-heading::after {
      content: "";
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 68px;
      height: 3px;
      background: linear-gradient(90deg, #0d4f8c, #1668b3);
      border-radius: 99px;
    }

    .flatsome-heading-left::after {
      left: 0;
      transform: none;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.92); opacity: 0.7; }
      70% { transform: scale(1.25); opacity: 0; }
      100% { transform: scale(1.25); opacity: 0; }
    }

    .hotline-pulse::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background-color: #e02424;
      animation: pulseRing 1.9s cubic-bezier(0.215, 0.61, 0.355, 1) infinite;
      z-index: -1;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ========================================================================
       1. TOP BAR (Thông tin nhanh - không hiển thị công cụ UX Builder)
       ======================================================================== -->
  <div class="bg-brand-700 text-white text-xs py-2 border-b border-brand-800">
    <div class="ux-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-200"></i>
          <span>14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-flex items-center gap-1.5">
          <i class="fa-regular fa-clock text-brand-200"></i>
          <span>T2 - CN: 07:30 - 17:00</span>
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4">
        <a href="mailto:dungtinthanhdn@gmail.com" class="inline-flex items-center gap-1.5 hover:text-brand-200 transition">
          <i class="fa-regular fa-envelope"></i>
          <span>dungtinthanhdn@gmail.com</span>
        </a>
        <span class="text-brand-200">|</span>
        <span class="font-medium">dungtinthanhwindow.com</span>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       2. MAIN HEADER (Logo gọn nhỏ + Menu 1 hàng không xuống dòng, không nút Gọi ngay)
       ======================================================================== -->
  <header id="site-header" class="sticky top-0 z-50 bg-white/98 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="ux-container h-16 lg:h-[72px] flex items-center justify-between gap-2">
      <!-- Logo gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 py-1" aria-label="Trang chủ Dũng Tín Thành Window">
        <img
          src="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w500"
          data-drive-id="1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr"
          data-fallback-label="D.T.T+46"
          onerror="handleDriveImageError(this)"
          alt="Logo Công Ty TNHH SX & TM D.T.T 46"
          class="h-10 sm:h-11 lg:h-12 w-auto max-w-[130px] sm:max-w-[155px] object-contain rounded-md"
        />
        <div class="flex flex-col leading-tight sm:hidden xl:flex">
          <span class="text-[12px] xl:text-[13px] font-extrabold text-brand-700 tracking-tight uppercase whitespace-nowrap">Dũng Tín Thành</span>
          <span class="text-[10px] font-medium text-slate-500 whitespace-nowrap">D.T.T 46 Window</span>
        </div>
      </a>

      <!-- Desktop Menu: Viết liền trên 1 hàng, không xuống dòng, không tràn viền -->
      <nav class="hidden lg:block flex-1 min-w-0" aria-label="Menu chính">
        <ul class="desktop-nav-list list-none m-0 p-0">
          <li>
            <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
          </li>
          <li>
            <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
          </li>
          <!-- Dropdown: Cửa nhôm xingfa -->
          <li class="nav-dropdown-wrap">
            <a href="#san-pham-xingfa" class="desktop-nav-link">
              <span>Cửa nhôm xingfa</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
            </a>
            <ul class="nav-dropdown-menu list-none m-0">
              <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('1-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('2-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('3-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('4-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('5-canh')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>
          <li>
            <a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cửa kính cường lực')" class="desktop-nav-link">Cửa kính cường lực</a>
          </li>
          <!-- Dropdown: Sản phẩm -->
          <li class="nav-dropdown-wrap">
            <a href="#danh-muc-san-pham" class="desktop-nav-link">
              <span>Sản phẩm</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
            </a>
            <ul class="nav-dropdown-menu list-none m-0">
              <li><a href="#san-pham-xingfa" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cửa nhựa lõi thép')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cửa kính tự động')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cầu thang kính')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Kính ốp bếp')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Phòng tắm kính')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-50 hover:text-brand-700 font-medium transition">Phòng tắm kính</a></li>
            </ul>
          </li>
          <li>
            <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
          </li>
          <li>
            <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
          </li>
          <li>
            <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
          </li>
          <li>
            <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
          </li>
        </ul>
      </nav>

      <!-- Nút mở menu trên điện thoại & máy tính bảng -->
      <button
        id="mobile-menu-open"
        type="button"
        class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-700 hover:bg-brand-50 transition"
        aria-label="Mở danh mục trang web"
      >
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>
  </header>

  <!-- Mobile Off-Canvas Drawer Menu -->
  <div id="mobile-drawer-overlay" class="fixed inset-0 bg-slate-900/50 z-[70] hidden transition-opacity"></div>
  <aside
    id="mobile-drawer"
    class="fixed top-0 left-0 bottom-0 w-[84%] max-w-[320px] bg-white z-[80] transform -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col overflow-y-auto"
    aria-label="Menu di động"
  >
    <div class="flex items-center justify-between p-4 border-b border-slate-200 bg-brand-700 text-white">
      <div class="flex items-center gap-2.5">
        <img
          src="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w300"
          data-drive-id="1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr"
          data-fallback-label="D.T.T+46"
          onerror="handleDriveImageError(this)"
          alt="Logo D.T.T 46"
          class="h-8 w-auto bg-white p-0.5 rounded"
        />
        <span class="font-bold text-sm tracking-tight">DANH MỤC</span>
      </div>
      <button id="mobile-menu-close" type="button" class="w-9 h-9 rounded-lg bg-white/15 hover:bg-white/25 flex items-center justify-center" aria-label="Đóng menu">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>
    </div>

    <nav class="p-3 flex-1">
      <ul class="space-y-1 list-none m-0 p-0 text-sm font-semibold text-slate-700">
        <li><a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Trang chủ</a></li>
        <li><a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Giới thiệu</a></li>

        <!-- Accordion: Cửa nhôm xingfa -->
        <li>
          <div class="flex items-center justify-between rounded-lg hover:bg-brand-50">
            <a href="#san-pham-xingfa" class="mobile-nav-link flex-1 px-3 py-2.5 hover:text-brand-700">Cửa nhôm xingfa</a>
            <button type="button" class="mobile-accordion-btn w-10 h-10 flex items-center justify-center text-slate-500" data-target="sub-xingfa" aria-label="Mở danh mục con Cửa nhôm xingfa">
              <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
            </button>
          </div>
          <ul id="sub-xingfa" class="hidden pl-5 pr-2 py-1 space-y-1 text-[13px] font-medium text-slate-600 border-l-2 border-brand-200 ml-3 mt-1">
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('1-canh')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('2-canh')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('3-canh')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('4-canh')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('5-canh')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </li>

        <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cửa kính cường lực')" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Cửa kính cường lực</a></li>

        <!-- Accordion: Sản phẩm -->
        <li>
          <div class="flex items-center justify-between rounded-lg hover:bg-brand-50">
            <a href="#danh-muc-san-pham" class="mobile-nav-link flex-1 px-3 py-2.5 hover:text-brand-700">Sản phẩm</a>
            <button type="button" class="mobile-accordion-btn w-10 h-10 flex items-center justify-center text-slate-500" data-target="sub-sanpham" aria-label="Mở danh mục con Sản phẩm">
              <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
            </button>
          </div>
          <ul id="sub-sanpham" class="hidden pl-5 pr-2 py-1 space-y-1 text-[13px] font-medium text-slate-600 border-l-2 border-brand-200 ml-3 mt-1">
            <li><a href="#san-pham-xingfa" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cửa nhựa lõi thép')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cửa kính tự động')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Cầu thang kính')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Kính ốp bếp')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Kính ốp bếp</a></li>
            <li><a href="#danh-muc-san-pham" onclick="selectCategoryToast('Phòng tắm kính')" class="mobile-nav-link block py-1.5 hover:text-brand-700">+ Phòng tắm kính</a></li>
          </ul>
        </li>

        <li><a href="#cong-trinh" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Công trình</a></li>
        <li><a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Báo giá</a></li>
        <li><a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Tin tức</a></li>
        <li><a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-brand-50 hover:text-brand-700">Liên hệ</a></li>
      </ul>
    </nav>

    <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1.5">
      <p class="font-bold text-brand-700">CÔNG TY TNHH SX & TM D.T.T 46</p>
      <p><i class="fa-solid fa-location-dot text-brand-600 mr-1.5"></i>14 Chơn Tâm 12, P. Hòa Khánh, TP Đà Nẵng</p>
      <p><i class="fa-solid fa-phone text-brand-600 mr-1.5"></i>Hotline: <a href="tel:0905959991" class="font-bold text-brand-700">0905.959.991</a></p>
    </div>
  </aside>

  <main id="trang-chu">
    <!-- ======================================================================
         3. HERO BANNER SLIDER (2 banner tự trượt kích thước bằng nhau, chữ nằm trọn bên trong và cách xa viền ảnh)
         ====================================================================== -->
    <section class="w-full bg-brand-900 py-3 sm:py-4 lg:py-5">
      <div class="ux-container">
        <div class="relative rounded-2xl overflow-hidden shadow-xl border border-brand-800 bg-brand-900" id="hero-slider">
          <div class="hero-slider-grid">

            <!-- BANNER 1 -->
            <div class="hero-slide-item active relative w-full bg-brand-900">
              <!-- Ảnh nền toàn banner -->
              <img
                src="https://lh3.googleusercontent.com/d/1dNHCXvt477-46T21JZ3RqvdrUUhA6pY8=w1400"
                data-drive-id="1dNHCXvt477-46T21JZ3RqvdrUUhA6pY8"
                data-fallback-label="Dung+Tin+Thanh+Window"
                onerror="handleDriveImageError(this)"
                alt="Xưởng sản xuất và thi công cửa nhôm kính Dũng Tín Thành Window"
                class="absolute inset-0 w-full h-full object-cover opacity-30"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-brand-900/95 via-brand-800/88 to-brand-700/75"></div>

              <!-- Nội dung đặt lùi sâu cách xa viền ảnh trên cả Mobile và Desktop -->
              <div class="relative z-10 w-full px-10 py-9 sm:px-16 sm:py-12 lg:px-24 lg:py-16">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                    <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-brand-200">
                      CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI D.T.T 46
                    </p>
                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight">
                      DŨNG TÍN THÀNH WINDOW<br />
                      <span class="text-brand-200">CỬA NHÔM XINGFA ĐÀ NẴNG</span>
                    </h1>
                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                      Chuyên thiết kế, sản xuất và thi công trọn gói Cửa nhôm Xingfa nhập khẩu tem đỏ, Cửa kính cường lực, Lan can cầu thang kính, Phòng tắm kính. Giá tận xưởng chỉ từ 1.650.000đ/m².
                    </p>
                    <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5 sm:gap-3">
                      <a href="#bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-semibold text-xs sm:text-sm shadow-md transition">
                        <span>Nhận báo giá ngay</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                      </a>
                      <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                        <span>Xem mẫu cửa</span>
                      </a>
                    </div>
                  </div>
                  <div class="hidden lg:block lg:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl aspect-[16/10] bg-brand-800">
                      <img
                        src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w1000"
                        data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                        data-fallback-label="Cua+Nhom+Xingfa"
                        onerror="handleDriveImageError(this)"
                        alt="Mẫu cửa nhôm Xingfa cao cấp Dũng Tín Thành"
                        class="w-full h-full object-cover"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 (Cấu trúc tương đồng để đảm bảo chiều cao 2 banner bằng nhau tuyệt đối) -->
            <div class="hero-slide-item relative w-full bg-brand-900">
              <img
                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1400"
                data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                data-fallback-label="Cong+Trinh+Da+Nang"
                onerror="handleDriveImageError(this)"
                alt="Thi công dự án khách sạn resort nhôm kính tại Đà Nẵng"
                class="absolute inset-0 w-full h-full object-cover opacity-30"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-brand-900/95 via-brand-800/88 to-brand-700/75"></div>

              <div class="relative z-10 w-full px-10 py-9 sm:px-16 sm:py-12 lg:px-24 lg:py-16">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                    <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-brand-200">
                      BẢO HÀNH 3 NĂM — BẢO TRÌ TRỌN ĐỜI
                    </p>
                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight">
                      THI CÔNG NHÔM KÍNH TRỌN GÓI<br />
                      <span class="text-brand-200">KHÁCH SẠN - BIỆT THỰ - NHÀ PHỐ</span>
                    </h2>
                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                      Gia công bằng dây chuyền máy cắt 2 đầu & ép góc CNC độ chính xác tuyệt đối. Khảo sát, đo đạc và lên phương án hoàn toàn miễn phí tận công trình tại Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5 sm:gap-3">
                      <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-semibold text-xs sm:text-sm shadow-md transition">
                        <span>Xem công trình thực tế</span>
                        <i class="fa-solid fa-arrow-right text-xs"></i>
                      </a>
                      <a href="tel:0905959991" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                        <i class="fa-solid fa-phone text-xs"></i>
                        <span>0905.959.991</span>
                      </a>
                    </div>
                  </div>
                  <div class="hidden lg:block lg:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl aspect-[16/10] bg-brand-800">
                      <img
                        src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w1000"
                        data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                        data-fallback-label="Du+An+Khach+San"
                        onerror="handleDriveImageError(this)"
                        alt="Công trình tiêu biểu Dũng Tín Thành Window tại Đà Nẵng"
                        class="w-full h-full object-cover"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển slide đặt sát viền, không che chữ -->
          <button
            id="hero-prev"
            type="button"
            class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-600 text-white flex items-center justify-center transition"
            aria-label="Banner trước"
          >
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button
            id="hero-next"
            type="button"
            class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-600 text-white flex items-center justify-center transition"
            aria-label="Banner kế tiếp"
          >
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chấm chỉ báo slide -->
          <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" class="hero-dot w-6 h-2 rounded-full bg-white transition-all" data-slide="0" aria-label="Chuyển tới banner 1"></button>
            <button type="button" class="hero-dot w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/80 transition-all" data-slide="1" aria-label="Chuyển tới banner 2"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         4. GIỚI THIỆU CÔNG TY (Flatsome 2-Column Section)
         ====================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-white">
      <div class="ux-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center">
          <div class="lg:col-span-6 space-y-4">
            <h2 class="text-lg sm:text-2xl lg:text-[26px] font-extrabold text-brand-700 uppercase flatsome-heading flatsome-heading-left">
              CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI D.T.T 46
            </h2>
            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
              <strong class="text-brand-700">Dũng Tín Thành Window</strong> là đơn vị chuyên sâu trong lĩnh vực thiết kế, gia công sản xuất và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Lan can cầu thang kính, Kính ốp bếp và Cabin phòng tắm kính</strong>.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed">
              Với xưởng sản xuất trực tiếp tại <strong>14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng</strong> cùng hệ thống máy móc gia công CNC hiện đại, chúng tôi cam kết mang đến những bộ cửa kín khít tuyệt đối, cách âm cách nhiệt vượt trội, giá tận gốc không phát sinh chi phí.
            </p>

            <!-- 4 Cam kết cốt lõi từ Fanpage -->
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-1">
              <div class="flex items-start gap-2.5 p-3 rounded-xl bg-brand-50/70 border border-brand-100">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5"></i>
                <span class="text-xs sm:text-sm font-medium text-slate-700">Giá cả tận gốc xưởng, báo giá trọn gói minh bạch</span>
              </div>
              <div class="flex items-start gap-2.5 p-3 rounded-xl bg-brand-50/70 border border-brand-100">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5"></i>
                <span class="text-xs sm:text-sm font-medium text-slate-700">Gia công ép góc CNC chính xác, kính & phụ kiện chính hãng</span>
              </div>
              <div class="flex items-start gap-2.5 p-3 rounded-xl bg-brand-50/70 border border-brand-100">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5"></i>
                <span class="text-xs sm:text-sm font-medium text-slate-700">Bàn giao đúng tiến độ, đội ngũ kỹ thuật nhiều năm kinh nghiệm</span>
              </div>
              <div class="flex items-start gap-2.5 p-3 rounded-xl bg-brand-50/70 border border-brand-100">
                <i class="fa-solid fa-circle-check text-brand-600 mt-0.5"></i>
                <span class="text-xs sm:text-sm font-medium text-slate-700">Chính sách bảo hành 3 năm — bảo trì kỹ thuật trọn đời</span>
              </div>
            </div>
          </div>

          <!-- Ảnh công ty & số liệu nổi bật -->
          <div class="lg:col-span-6 space-y-4">
            <div class="rounded-2xl overflow-hidden shadow-lg border border-slate-200 aspect-[16/10] bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1dNHCXvt477-46T21JZ3RqvdrUUhA6pY8=w1200"
                data-drive-id="1dNHCXvt477-46T21JZ3RqvdrUUhA6pY8"
                data-fallback-label="Cong+Ty+DTT+46"
                onerror="handleDriveImageError(this)"
                alt="Hình ảnh Công ty TNHH SX & TM D.T.T 46 - Dũng Tín Thành Window"
                class="w-full h-full object-cover"
              />
            </div>

            <!-- Thanh thống kê chuẩn Flatsome -->
            <div class="grid grid-cols-4 gap-2 sm:gap-3 text-center">
              <div class="p-2.5 sm:p-3.5 rounded-xl bg-brand-700 text-white">
                <div class="text-base sm:text-xl font-extrabold">150+</div>
                <div class="text-[10px] sm:text-xs text-brand-100 mt-0.5">Công trình</div>
              </div>
              <div class="p-2.5 sm:p-3.5 rounded-xl bg-brand-600 text-white">
                <div class="text-base sm:text-xl font-extrabold">50+</div>
                <div class="text-[10px] sm:text-xs text-brand-100 mt-0.5">Kỹ thuật viên</div>
              </div>
              <div class="p-2.5 sm:p-3.5 rounded-xl bg-brand-700 text-white">
                <div class="text-base sm:text-xl font-extrabold">3 Năm</div>
                <div class="text-[10px] sm:text-xs text-brand-100 mt-0.5">Bảo hành</div>
              </div>
              <div class="p-2.5 sm:p-3.5 rounded-xl bg-brand-600 text-white">
                <div class="text-base sm:text-xl font-extrabold">100%</div>
                <div class="text-[10px] sm:text-xs text-brand-100 mt-0.5">Hài lòng</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         5. DANH MỤC SẢN PHẨM NỔI BẬT (6 danh mục chuẩn web mẫu, chữ nhỏ gọn đẹp mắt)
         ====================================================================== -->
    <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200">
      <div class="ux-container">
        <div class="text-center mb-7">
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-700 uppercase flatsome-heading">
            DANH MỤC SẢN PHẨM NỔI BẬT
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Giải pháp cửa và kính kiến trúc đồng bộ cho nhà phố, biệt thự, văn phòng & khách sạn
          </p>
        </div>

        <!-- 2 cột trên điện thoại, 3 cột tablet, 6 cột gọn gàng trên máy tính -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4" id="category-grid">
          <!-- Render bằng JS để gọn nhẹ & dễ bảo trì -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         6. SẢN PHẨM CỬA NHÔM XINGFA (2 cột điện thoại, giá & giảm giá % góc trên trái)
         ====================================================================== -->
    <section id="san-pham-xingfa" class="py-10 sm:py-14 bg-white">
      <div class="ux-container">
        <div class="flex flex-col sm:flex-row sm:items-end justify-between gap-3 mb-7">
          <div class="text-center sm:text-left w-full sm:w-auto">
            <h2 class="text-lg sm:text-2xl font-extrabold text-brand-700 uppercase flatsome-heading sm:flatsome-heading-left">
              SẢN PHẨM CỬA NHÔM XINGFA
            </h2>
            <p class="text-xs sm:text-sm text-slate-500 mt-2">
              Nhôm Xingfa nhập khẩu Quảng Đông chính hãng — Phụ kiện đồng bộ — Giá ưu đãi tại xưởng
            </p>
          </div>

          <!-- Bộ lọc nhanh gọn nhẹ -->
          <div class="flex flex-wrap items-center justify-center sm:justify-end gap-1.5" id="product-filter-bar">
            <button type="button" onclick="filterXingfaProduct('all')" data-filter="all" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-700 text-white transition">Tất cả</button>
            <button type="button" onclick="filterXingfaProduct('1-canh')" data-filter="1-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">1 cánh</button>
            <button type="button" onclick="filterXingfaProduct('2-canh')" data-filter="2-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">2 cánh</button>
            <button type="button" onclick="filterXingfaProduct('3-canh')" data-filter="3-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">3 cánh</button>
            <button type="button" onclick="filterXingfaProduct('4-canh')" data-filter="4-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">4 cánh</button>
            <button type="button" onclick="filterXingfaProduct('xep-truot')" data-filter="xep-truot" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">Xếp trượt</button>
          </div>
        </div>

        <!-- Lưới sản phẩm: BẮT BUỘC 2 cột trên điện thoại, tên đầy đủ không cắt chữ -->
        <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-5 lg:gap-6">
          <!-- Render bằng JavaScript -->
        </div>

        <!-- Bảng báo giá tham khảo nhanh (chuẩn bố cục ngochanwindow.com) -->
        <div class="mt-10 rounded-2xl border border-slate-200 overflow-hidden bg-slate-50/60">
          <div class="bg-brand-700 text-white px-4 sm:px-6 py-3.5 flex flex-wrap items-center justify-between gap-2">
            <h3 class="text-sm sm:text-base font-bold uppercase tracking-wide">
              <i class="fa-solid fa-table-list mr-2"></i>Bảng Báo Giá Thi Công Cửa Nhôm Xingfa Đà Nẵng
            </h3>
            <span class="text-xs text-brand-100">Đơn vị tính: VNĐ / m² (Đã gồm lắp đặt)</span>
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-50 text-brand-800 border-b border-slate-200">
                  <th class="py-3 px-4 font-bold">Hạng mục cửa nhôm Xingfa</th>
                  <th class="py-3 px-4 font-bold">Hệ nhôm & Độ dày</th>
                  <th class="py-3 px-4 font-bold">Đơn giá ưu đãi</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-200 bg-white">
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-medium text-slate-800">Cửa sổ mở quay / mở hất nhôm Xingfa</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 55 — Dày 1.4mm</td>
                  <td class="py-3 px-4 font-bold text-accent-600">1.650.000 ₫/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-medium text-slate-800">Cửa đi mở quay 1 cánh, 2 cánh nhôm Xingfa</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 55 — Dày 2.0mm</td>
                  <td class="py-3 px-4 font-bold text-accent-600">1.790.000 ₫/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-medium text-slate-800">Cửa đi mở quay 3 cánh, 4 cánh nhôm Xingfa</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 55 — Dày 2.0mm</td>
                  <td class="py-3 px-4 font-bold text-accent-600">1.850.000 ₫/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-medium text-slate-800">Cửa đi xếp trượt gấp 4 - 6 cánh nhôm Xingfa</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 63 — Dày 2.0mm</td>
                  <td class="py-3 px-4 font-bold text-accent-600">1.950.000 ₫/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-3 px-4 font-medium text-slate-800">Cửa đi mở trượt lùa 2 cánh, 4 cánh</td>
                  <td class="py-3 px-4 text-slate-600">Hệ 93 — Dày 2.0mm</td>
                  <td class="py-3 px-4 font-bold text-accent-600">1.750.000 ₫/m²</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         7. CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
         ====================================================================== -->
    <section id="cong-trinh" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200">
      <div class="ux-container">
        <div class="text-center mb-8">
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-700 uppercase flatsome-heading">
            CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Hàng trăm công trình khách sạn, resort, biệt thự và nhà phố được D.T.T 46 thi công hoàn thiện
          </p>
        </div>

        <div id="projects-grid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
          <!-- Render bằng JavaScript -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         8. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
         ====================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-700 text-white">
      <div class="ux-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center">
          <div class="lg:col-span-5 space-y-4">
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase leading-snug">
              ĐĂNG KÝ YÊU CẦU & NHẬN BÁO GIÁ MIỄN PHÍ
            </h2>
            <p class="text-xs sm:text-sm text-brand-100 leading-relaxed">
              Quý khách đang xây nhà mới hoặc cần cải tạo hạng mục cửa nhôm kính, cầu thang kính, phòng tắm kính tại Đà Nẵng? Hãy để lại thông tin để đội ngũ kỹ thuật của <strong>CÔNG TY TNHH SX & TM D.T.T 46</strong> khảo sát đo đạc và gửi bảng dự toán chi tiết trong 15 phút.
            </p>
            <ul class="space-y-2.5 text-xs sm:text-sm text-brand-50 pt-1">
              <li class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-white/15 flex items-center justify-center shrink-0"><i class="fa-solid fa-check text-xs"></i></span>
                <span>Khảo sát thực tế và tư vấn mẫu tại công trình miễn phí</span>
              </li>
              <li class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-white/15 flex items-center justify-center shrink-0"><i class="fa-solid fa-check text-xs"></i></span>
                <span>Báo giá trực tiếp từ xưởng, chiết khấu tốt cho công trình lớn</span>
              </li>
              <li class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-white/15 flex items-center justify-center shrink-0"><i class="fa-solid fa-check text-xs"></i></span>
                <span>Hotline hỗ trợ nhanh 24/7: <a href="tel:0905959991" class="font-bold underline text-white">0905.959.991</a></span>
              </li>
            </ul>
          </div>

          <div class="lg:col-span-7">
            <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                  <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none transition" />
                </div>
                <div>
                  <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                  <input id="q-phone" type="tel" required placeholder="VD: 0905.959.991" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none transition" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="q-category" class="block text-xs font-semibold text-slate-700 mb-1.5">Hạng mục cần báo giá</label>
                  <select id="q-category" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none bg-white transition">
                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa nhập khẩu</option>
                    <option value="Cửa kính cường lực">Cửa kính cường lực / Thủy lực</option>
                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                    <option value="Cầu thang kính">Cầu thang & Lan can kính</option>
                    <option value="Kính ốp bếp">Kính màu ốp bếp</option>
                    <option value="Phòng tắm kính">Cabin phòng tắm kính</option>
                  </select>
                </div>
                <div>
                  <label for="q-address" class="block text-xs font-semibold text-slate-700 mb-1.5">Khu vực công trình</label>
                  <input id="q-address" type="text" placeholder="VD: Hòa Khánh, Liên Chiểu, Đà Nẵng" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none transition" />
                </div>
              </div>

              <div>
                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết (kích thước, số lượng bộ cửa...)</label>
                <textarea id="q-note" rows="3" placeholder="Mô tả sơ bộ số lượng cửa hoặc yêu cầu tư vấn..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-100 outline-none transition"></textarea>
              </div>

              <div id="quote-feedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-700 border border-emerald-200"></div>

              <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-bold text-sm shadow-md transition inline-flex items-center justify-center gap-2">
                <i class="fa-solid fa-paper-plane"></i>
                <span>GỬI YÊU CẦU BÁO GIÁ</span>
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         9. DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
         ====================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
      <div class="ux-container">
        <div class="text-center mb-8">
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-700 uppercase flatsome-heading">
            TIN TỨC & KINH NGHIỆM NHÔM KÍNH
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Chia sẻ kiến thức lựa chọn cửa nhôm Xingfa, phụ kiện chính hãng và cập nhật công trình mới nhất
          </p>
        </div>

        <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <!-- Render bằng JavaScript -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         10. ĐỐI TÁC CỦA CHÚNG TÔI (6 đối tác từ Google Drive)
         ====================================================================== -->
    <section class="py-9 sm:py-12 bg-slate-50 border-y border-slate-200">
      <div class="ux-container">
        <div class="text-center mb-6">
          <h2 class="text-base sm:text-xl font-extrabold text-brand-700 uppercase flatsome-heading">
            ĐỐI TÁC CỦA CHÚNG TÔI
          </h2>
        </div>

        <div id="partners-grid" class="grid grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
          <!-- Render bằng JavaScript -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         11. GOOGLE MAP & FANPAGE FACEBOOK TRỰC TIẾP TRÊN TRANG CHỦ
         ====================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white">
      <div class="ux-container">
        <div class="text-center mb-8">
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-700 uppercase flatsome-heading">
            BẢN ĐỒ CHỈ ĐƯỜNG & FANPAGE FACEBOOK
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Ghé thăm xưởng sản xuất tại 14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng hoặc theo dõi Fanpage chính thức
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
          <!-- Bản đồ Google Map -->
          <div class="lg:col-span-7 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-slate-50">
            <div class="px-4 py-3 bg-brand-700 text-white flex flex-wrap items-center justify-between gap-2">
              <span class="text-xs sm:text-sm font-bold inline-flex items-center gap-2">
                <i class="fa-solid fa-map-location-dot"></i>
                <span>14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng</span>
              </span>
              <a
                href="https://www.google.com/maps/search/?api=1&query=14+Ch%C6%A1n+T%C3%A2m+12,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold bg-white/15 hover:bg-white/25 px-3 py-1 rounded-md transition"
              >
                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-[10px]"></i>
              </a>
            </div>
            <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-200">
              <iframe
                title="Bản đồ Công ty TNHH SX & TM D.T.T 46 - 14 Chơn Tâm 12, Hòa Khánh, Đà Nẵng"
                src="https://maps.google.com/maps?q=14%20Ch%C6%A1n%20T%C3%A2m%2012%2C%20H%C3%B2a%20Kh%C3%A1nh%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
                allowfullscreen
              ></iframe>
            </div>
          </div>

          <!-- Fanpage Facebook Dũng Tín Thành Window -->
          <div class="lg:col-span-5 flex flex-col rounded-2xl overflow-hidden border border-slate-200 shadow-sm bg-white">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
              <span class="text-xs sm:text-sm font-bold inline-flex items-center gap-2">
                <i class="fa-brands fa-facebook text-base"></i>
                <span>Fanpage Dũng Tín Thành Window</span>
              </span>
              <a
                href="https://www.facebook.com/nhomkinhdanang43/"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold bg-white/20 hover:bg-white/30 px-3 py-1 rounded-md transition"
              >
                Theo dõi trang
              </a>
            </div>

            <!-- Thẻ giới thiệu nhanh Fanpage + Nhúng Facebook Page Plugin -->
            <div class="p-4 flex flex-col justify-between flex-1 gap-3 bg-slate-50/70">
              <div class="flex items-center gap-3 bg-white p-3 rounded-xl border border-slate-200">
                <img
                  src="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w300"
                  data-drive-id="1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr"
                  data-fallback-label="DTT+46"
                  onerror="handleDriveImageError(this)"
                  alt="Avatar Fanpage Dũng Tín Thành Window"
                  class="w-12 h-12 rounded-full object-contain border border-slate-200 bg-white p-1 shrink-0"
                />
                <div class="min-w-0 flex-1">
                  <h3 class="text-sm font-bold text-slate-900 leading-tight">Dũng Tín Thành Window</h3>
                  <p class="text-xs text-slate-500 mt-0.5">facebook.com/nhomkinhdanang43</p>
                </div>
                <a
                  href="https://www.facebook.com/nhomkinhdanang43/"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="shrink-0 px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold transition"
                >
                  <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn tin
                </a>
              </div>

              <!-- Facebook Page Plugin Iframe -->
              <div class="w-full rounded-xl overflow-hidden border border-slate-200 bg-white min-h-[210px] flex items-center justify-center">
                <iframe
                  title="Fanpage Facebook Dũng Tín Thành Window"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fnhomkinhdanang43%2F&tabs=timeline&width=440&height=230&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  class="w-full h-[230px] border-0"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- ========================================================================
       12. FOOTER (Flatsome 4-Column Corporate Footer)
       ======================================================================== -->
  <footer class="bg-brand-900 text-slate-200 pt-12 pb-6 border-t-4 border-brand-500">
    <div class="ux-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-9 border-b border-brand-800">
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="inline-flex items-center gap-2.5 bg-white px-3 py-1.5 rounded-lg">
            <img
              src="https://lh3.googleusercontent.com/d/1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr=w400"
              data-drive-id="1ndsWVdBbYBmjOvlg5Z1la4powU8ibhVr"
              data-fallback-label="D.T.T+46"
              onerror="handleDriveImageError(this)"
              alt="Logo Công ty D.T.T 46"
              class="h-9 w-auto object-contain"
            />
            <span class="text-xs font-extrabold text-brand-700 uppercase">D.T.T 46 Window</span>
          </div>
          <h3 class="text-sm font-bold text-white uppercase leading-snug pt-1">
            CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI D.T.T 46
          </h3>
          <ul class="space-y-2 text-xs text-slate-300 leading-relaxed list-none m-0 p-0">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brand-200 mt-0.5"></i>
              <span>Địa chỉ: 14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-brand-200"></i>
              <span>Hotline: <a href="tel:0905959991" class="text-white font-bold hover:underline">0905.959.991</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-regular fa-envelope text-brand-200"></i>
              <span>Email: dungtinthanhdn@gmail.com</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-brand-200"></i>
              <span>Website: dungtinthanhwindow.com</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-file-invoice text-brand-200"></i>
              <span>MST: 0402089544</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase mb-4 pb-2 border-b border-brand-700">Cửa nhôm Xingfa</h3>
          <ul class="space-y-2 text-xs text-slate-300 list-none m-0 p-0">
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('1-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('2-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('3-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('4-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('5-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 5 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterXingfaProduct('xep-truot')" class="hover:text-white transition">› Cửa đi xếp trượt nhôm Xingfa</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase mb-4 pb-2 border-b border-brand-700">Danh mục sản phẩm</h3>
          <ul class="space-y-2 text-xs text-slate-300 list-none m-0 p-0">
            <li><a href="#san-pham-xingfa" class="hover:text-white transition">› Cửa nhôm Xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-white transition">› Cửa kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-white transition">› Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-white transition">› Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-white transition">› Cầu thang & Lan can kính</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-white transition">› Kính ốp bếp & Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết & Hỗ trợ -->
        <div>
          <h3 class="text-sm font-bold text-white uppercase mb-4 pb-2 border-b border-brand-700">Hỗ trợ khách hàng</h3>
          <ul class="space-y-2 text-xs text-slate-300 list-none m-0 p-0 mb-4">
            <li><a href="#gioi-thieu" class="hover:text-white transition">› Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-white transition">› Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-white transition">› Nhận báo giá nhanh</a></li>
            <li><a href="#tin-tuc" class="hover:text-white transition">› Tin tức & Tư vấn chọn cửa</a></li>
          </ul>
          <div class="flex items-center gap-2.5">
            <a href="https://www.facebook.com/nhomkinhdanang43/" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-lg bg-[#1877F2] hover:opacity-90 flex items-center justify-center text-white transition" aria-label="Facebook Dũng Tín Thành">
              <i class="fa-brands fa-facebook-f"></i>
            </a>
            <a href="https://zalo.me/0905959991" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-lg bg-[#0068FF] hover:opacity-90 flex items-center justify-center text-white font-extrabold text-[11px] transition" aria-label="Zalo Dũng Tín Thành">
              Zalo
            </a>
            <a href="tel:0905959991" class="w-9 h-9 rounded-lg bg-accent-500 hover:opacity-90 flex items-center justify-center text-white transition" aria-label="Gọi Hotline">
              <i class="fa-solid fa-phone"></i>
            </a>
          </div>
        </div>
      </div>

      <div class="pt-5 text-center text-xs text-slate-400">
        Copyright 2026 © <strong class="text-slate-200">CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI D.T.T 46</strong> — dungtinthanhwindow.com. All rights reserved.
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       13. CÁC NÚT LIÊN HỆ NỔI BẬT (Zalo, Facebook, Hotline) TƯƠNG THÍCH MOBILE & PC
       ======================================================================== -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-[65] flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0905959991"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white rounded-full shadow-lg pl-3 pr-3 sm:pr-4 py-2.5 transition-all"
      aria-label="Chat Zalo 0905.959.991"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/nhomkinhdanang43/"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full shadow-lg pl-3 pr-3 sm:pr-4 py-2.5 transition-all"
      aria-label="Fanpage Facebook Dũng Tín Thành Window"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0905959991"
      class="relative hotline-pulse flex items-center gap-2 bg-accent-500 hover:bg-accent-600 text-white rounded-full shadow-xl pl-3 pr-3.5 sm:pr-4 py-2.5 transition-all"
      aria-label="Gọi Hotline 0905.959.991"
    >
      <span class="w-6 h-6 rounded-full bg-white text-accent-600 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0905.959.991</span>
    </a>
  </div>

  <!-- ========================================================================
       MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT (Không dùng alert)
       ======================================================================== -->
  <div id="detail-modal" class="fixed inset-0 z-[90] hidden items-center justify-center p-3 sm:p-5 bg-slate-900/65 backdrop-blur-xs">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-white border-b border-slate-200 px-5 py-3.5 flex items-center justify-between z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand-700 pr-4">Chi tiết</h3>
        <button id="modal-close" type="button" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0" aria-label="Đóng cửa sổ">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="modal-body" class="p-5"></div>
    </div>
  </div>

  <!-- Thông báo Toast gọn nhẹ -->
  <div id="toast-box" class="fixed bottom-20 left-1/2 -translate-x-1/2 z-[95] hidden bg-brand-800 text-white text-xs sm:text-sm font-medium px-4 py-2.5 rounded-xl shadow-xl"></div>

  <!-- ========================================================================
       JAVASCRIPT: DỮ LIỆU THỰC TẾ, SLIDER, LỌC SẢN PHẨM & TƯƠNG TÁC
       ======================================================================== -->
  <script>
    /**
     * Xử lý fallback tự động cho ảnh Google Drive:
     * Bước 1: lh3.googleusercontent.com/d/{id}=w1000
     * Bước 2: drive.google.com/thumbnail?id={id}&sz=w1000
     * Bước 3: placehold.co nếu file bị giới hạn quyền truy cập
     */
    function handleDriveImageError(img) {
      const stage = parseInt(img.getAttribute('data-err-stage') || '0', 10);
      const id = img.getAttribute('data-drive-id');
      const label = img.getAttribute('data-fallback-label') || 'Dung+Tin+Thanh';

      if (stage === 0 && id) {
        img.setAttribute('data-err-stage', '1');
        img.src = `https://drive.google.com/thumbnail?id=${id}&sz=w1000`;
      } else if (stage === 1) {
        img.setAttribute('data-err-stage', '2');
        img.src = `https://placehold.co/600x450/0d4f8c/ffffff?text=${label}`;
      }
    }

    function driveImgUrl(id, size = 1000) {
      return `https://lh3.googleusercontent.com/d/${id}=w${size}`;
    }

    // 1. DỮ LIỆU DANH MỤC SẢN PHẨM NỔI BẬT (Chuẩn web mẫu ngochanwindow.com)
    const CATEGORIES = [
      {
        name: 'Cửa nhôm Xingfa',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        target: '#san-pham-xingfa',
        desc: 'Thanh profile Xingfa tem đỏ Quảng Đông hệ 55, 63, 93'
      },
      {
        name: 'Cửa nhựa lõi thép',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        target: '#bao-gia',
        desc: 'Cách âm cách nhiệt tối ưu, thanh uPVC gia cường lõi thép'
      },
      {
        name: 'Cửa tự động',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        target: '#bao-gia',
        desc: 'Cửa kính cảm biến đóng mở tự động cho văn phòng, khách sạn'
      },
      {
        name: 'Cầu thang kính',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        target: '#bao-gia',
        desc: 'Kính cường lực 10mm - 12mm, tay vịn gỗ hoặc inox 304'
      },
      {
        name: 'Kính ốp bếp',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        target: '#bao-gia',
        desc: 'Kính cường lực sơn màu chịu nhiệt, dễ lau chùi, bền màu'
      },
      {
        name: 'Phòng tắm kính',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        target: '#bao-gia',
        desc: 'Cabin vách tắm kính cường lực phụ kiện inox 304 chống gỉ'
      }
    ];

    // 2. DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA (Giá & Giảm giá % góc trên bên trái)
    const PRODUCTS = [
      {
        id: 'p1',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        categoryTags: ['all', '1-canh'],
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        originalPrice: 2150000,
        salePrice: 1790000,
        discount: 17,
        spec: {
          nhom: 'Thanh nhôm Xingfa nhập khẩu tem đỏ hệ 55',
          doDay: '2.0 mm (±5%)',
          mauSac: 'Ghi xám, Đen tuyền, Trắng sứ, Nâu cà phê, Vân gỗ',
          kinh: 'Kính cường lực 8mm / Kính dán an toàn 6.38mm',
          phuKien: 'Kinlong / Janus đồng bộ chính hãng, gioăng kép EPDM',
          baoHanh: '3 năm — Bảo trì trọn đời'
        }
      },
      {
        id: 'p2',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        categoryTags: ['all', '2-canh'],
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        originalPrice: 2200000,
        salePrice: 1850000,
        discount: 16,
        spec: {
          nhom: 'Thanh nhôm Xingfa nhập khẩu tem đỏ hệ 55',
          doDay: '2.0 mm (±5%)',
          mauSac: 'Ghi xám, Đen tuyền, Trắng sứ, Nâu sần, Vân gỗ',
          kinh: 'Kính cường lực 8mm - 10mm hoặc kính hộp cách âm',
          phuKien: 'Bản lề 3D, khóa đa điểm Kinlong chính hãng',
          baoHanh: '3 năm — Bảo trì trọn đời'
        }
      },
      {
        id: 'p3',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        categoryTags: ['all', '3-canh'],
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        originalPrice: 2250000,
        salePrice: 1890000,
        discount: 16,
        spec: {
          nhom: 'Thanh nhôm Xingfa nhập khẩu tem đỏ hệ 55',
          doDay: '2.0 mm (±5%)',
          mauSac: 'Ghi xám, Đen, Trắng sứ, Nâu cà phê, Vân gỗ',
          kinh: 'Kính dán an toàn 8.38mm / Kính cường lực 8mm',
          phuKien: 'Phụ kiện đồng bộ cao cấp, vít Inox 304 chống han gỉ',
          baoHanh: '3 năm — Bảo trì trọn đời'
        }
      },
      {
        id: 'p4',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        categoryTags: ['all', '4-canh'],
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        originalPrice: 2300000,
        salePrice: 1920000,
        discount: 17,
        spec: {
          nhom: 'Thanh nhôm Xingfa nhập khẩu tem đỏ hệ 55',
          doDay: '2.0 mm (±5%)',
          mauSac: 'Nâu sần, Ghi xám, Đen, Trắng sứ, Vân gỗ',
          kinh: 'Kính cường lực 8mm - 10mm chịu lực gió bão',
          phuKien: 'Bản lề 4D chịu tải lớn, khóa đa điểm chống trộm',
          baoHanh: '3 năm — Bảo trì trọn đời'
        }
      },
      {
        id: 'p5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        categoryTags: ['all', 'xep-truot', '5-canh'],
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        originalPrice: 2450000,
        salePrice: 1990000,
        discount: 19,
        spec: {
          nhom: 'Thanh nhôm Xingfa nhập khẩu tem đỏ hệ 63 (4-5-6 cánh)',
          doDay: '2.0 mm - 3.0 mm',
          mauSac: 'Ghi xám, Đen tuyền, Trắng sứ, Vân gỗ',
          kinh: 'Kính cường lực 8mm - 10mm / Kính hộp nan trang trí',
          phuKien: 'Ray trượt treo trên & bánh xe dẫn hướng êm ái',
          baoHanh: '3 năm — Bảo trì trọn đời'
        }
      },
      {
        id: 'p6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        categoryTags: ['all', '2-canh'],
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        originalPrice: 1980000,
        salePrice: 1650000,
        discount: 17,
        spec: {
          nhom: 'Thanh nhôm Xingfa nhập khẩu tem đỏ hệ 55',
          doDay: '1.4 mm (±5%)',
          mauSac: 'Ghi xám, Đen, Trắng sứ, Nâu cà phê',
          kinh: 'Kính an toàn 6.38mm / Kính cường lực 8mm',
          phuKien: 'Bản lề chữ A chống gió dập, thanh chống sao Inox',
          baoHanh: '3 năm — Bảo trì trọn đời'
        }
      }
    ];

    // 3. DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
    const PROJECTS = [
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        location: 'TP. Đà Nẵng',
        scope: 'Thi công toàn bộ hệ thống cửa nhôm Xingfa cách âm, vách kính mặt dựng và phòng tắm kính cường lực cho hệ thống phòng lưu trú.'
      },
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        location: 'Quảng Nam - Đà Nẵng',
        scope: 'Cung cấp & lắp đặt hạng mục cửa đi xếp trượt nhôm Xingfa cao cấp, vách kính cường lực chịu áp lực gió cho khu nghỉ dưỡng 4 sao.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        location: 'TP. Đà Nẵng',
        scope: 'Gia công lắp đặt trọn gói cửa đi ban công, cửa sổ mở hất chống bão và lan can kính cường lực ngoài trời.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        location: 'TP. Đà Nẵng',
        scope: 'Hoàn thiện hạng mục cửa nhôm kính hệ Xingfa, cửa kính tự động sảnh lễ tân và vách ngăn cabin tắm kính sang trọng.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        location: 'TP. Đà Nẵng',
        scope: 'Thi công mặt dựng nhôm kính, cửa nhôm kính cách âm chống ồn tiêu chuẩn khách sạn ven biển.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        location: 'Biển Mỹ Khê, Đà Nẵng',
        scope: 'Lắp đặt đồng bộ cửa nhôm kính chống ăn mòn muối biển, phụ kiện Inox 304 và hệ thống vách kính cường lực.'
      }
    ];

    // 4. DỮ LIỆU BÀI VIẾT TRANG CHỦ
    const ARTICLES = [
      {
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu gió biển Đà Nẵng không?',
        date: '18/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Phân tích khả năng chống gió bão lên tới 1600 Pascal, lớp sơn tĩnh điện ngoài trời và gioăng kép EPDM kín nước của nhôm Xingfa.',
        content: 'Đà Nẵng là thành phố ven biển có mùa mưa bão khắc nghiệt và hơi muối dễ gây oxy hóa. Cửa nhôm Xingfa nhập khẩu Quảng Đông với kết cấu khoang rỗng tăng cứng, bề mặt sơn tĩnh điện cao cấp kết hợp ốc vít Inox 304 và gioăng kép EPDM đảm bảo kín nước, chống rung lắc và bền đẹp trên 20 năm.'
      },
      {
        title: 'Cách phân biệt cửa nhôm Xingfa nhập khẩu tem đỏ chính hãng',
        date: '10/11/2026',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        excerpt: 'Hướng dẫn kiểm tra mã QR tem đỏ Quảng Đông, ánh kim mạ crom bên trong khoang nhôm và độ dày chuẩn 1.4mm - 2.0mm.',
        content: 'Để chọn đúng nhôm Xingfa nhập khẩu chính hãng, khách hàng cần kiểm tra 4 yếu tố: (1) Tem chữ đỏ sắc nét có mã QR quét ra nhà máy Guangdong Xingfa, (2) Lõi nhôm bên trong có ánh đồng mạ crom chống ăn mòn, (3) Đường cắt góc 45 độ ép thủy lực kín khít bằng keo chuyên dụng, (4) Phụ kiện Kinlong hoặc Janus đồng bộ có bảo hành rõ ràng.'
      },
      {
        title: 'Báo giá thi công cầu thang kính và phòng tắm kính tại Đà Nẵng',
        date: '02/11/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        excerpt: 'Cập nhật mẫu lan can cầu thang kính cường lực và cabin phòng tắm kính 90 độ, 135 độ, cửa lùa tối ưu diện tích nhà phố.',
        content: 'Sử dụng kính cường lực 10mm - 12mm kết hợp trụ và kẹp inox 304 chuẩn giúp không gian nhà phố Đà Nẵng thêm rộng rãi, sáng sủa và dễ vệ sinh. Dũng Tín Thành Window khảo sát đo đạc miễn phí, thi công nhanh trong 3-5 ngày.'
      },
      {
        title: 'Nên chọn cửa đi xếp trượt hay cửa mở quay 4 cánh cho mặt tiền?',
        date: '25/10/2026',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        excerpt: 'So sánh độ mở thông thủy, độ bền bản lề và chi phí đầu tư giữa cửa đi mở quay 4 cánh hệ 55 và cửa xếp trượt hệ 63.',
        content: 'Nếu mặt tiền rộng từ 3.2m trở lên và muốn mở tối đa không gian kết nối sân vườn hoặc gara ô tô, cửa đi xếp trượt hệ 63 (4-6 cánh) là lựa chọn đẳng cấp. Trong khi đó, cửa đi mở quay 4 cánh hệ 55 mang lại sự chắc chắn, dễ đóng mở hàng ngày với chi phí rất hợp lý.'
      }
    ];

    // 5. DỮ LIỆU 6 ĐỐI TÁC
    const PARTNERS = [
      { name: 'Đối tác 1', driveId: '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk' },
      { name: 'Đối tác 2', driveId: '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq' },
      { name: 'Đối tác 3', driveId: '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn' },
      { name: 'Đối tác 4', driveId: '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT' },
      { name: 'Đối tác 5', driveId: '1SDcarhnX0yypmqdbawICjYBRtFnKngn-' },
      { name: 'Đối tác 6', driveId: '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg' }
    ];

    function formatVND(price) {
      return price.toLocaleString('vi-VN') + ' ₫';
    }

    // Render Danh mục sản phẩm nổi bật (Chữ gọn đẹp trên PC & Mobile)
    function renderCategories() {
      const container = document.getElementById('category-grid');
      container.innerHTML = CATEGORIES.map((cat) => `
        <a
          href="${cat.target}"
          onclick="selectCategoryToast('${cat.name}')"
          class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-500 shadow-xs hover:shadow-md transition-all flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(cat.driveId, 600)}"
              data-drive-id="${cat.driveId}"
              data-fallback-label="${encodeURIComponent(cat.name)}"
              onerror="handleDriveImageError(this)"
              alt="${cat.name}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex flex-col justify-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-800 group-hover:text-brand-600 uppercase leading-snug">
              ${cat.name}
            </h3>
          </div>
        </a>
      `).join('');
    }

    // Render Lưới sản phẩm (2 cột trên mobile, tên đầy đủ, giảm giá % góc trên bên trái)
    function renderProducts(filterTag = 'all') {
      const grid = document.getElementById('product-grid');
      const filtered = filterTag === 'all'
        ? PRODUCTS
        : PRODUCTS.filter((p) => p.categoryTags.includes(filterTag));

      const listToShow = filtered.length > 0 ? filtered : PRODUCTS;

      grid.innerHTML = listToShow.map((p) => `
        <article class="group bg-white rounded-xl border border-slate-200 hover:border-brand-500 hover:shadow-lg transition-all flex flex-col overflow-hidden">
          <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal('${p.id}')">
            <!-- Badge giảm giá % góc trên bên trái sản phẩm -->
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded-md bg-accent-500 text-white text-[11px] sm:text-xs font-extrabold shadow">
              -${p.discount}%
            </span>
            <img
              src="${driveImgUrl(p.driveId, 800)}"
              data-drive-id="${p.driveId}"
              data-fallback-label="${encodeURIComponent(p.name)}"
              onerror="handleDriveImageError(this)"
              alt="${p.name}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>

          <div class="p-2.5 sm:p-4 flex flex-col flex-1 justify-between gap-2.5">
            <!-- Tên sản phẩm đầy đủ, không cắt chữ, không tràn viền -->
            <h3
              onclick="openProductModal('${p.id}')"
              class="cursor-pointer text-[12.5px] sm:text-sm lg:text-[15px] font-bold text-slate-800 group-hover:text-brand-700 leading-snug break-words"
            >
              ${p.name}
            </h3>

            <div class="space-y-2.5">
              <!-- Giá gốc & Giá khuyến mãi -->
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-[13px] sm:text-base font-extrabold text-accent-600">${formatVND(p.salePrice)}/m²</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${formatVND(p.originalPrice)}</span>
              </div>

              <!-- Nút thao tác gọn gàng vừa khít 2 cột mobile -->
              <div class="grid grid-cols-2 gap-1.5 sm:gap-2">
                <button
                  type="button"
                  onclick="openProductModal('${p.id}')"
                  class="py-1.5 sm:py-2 px-1.5 sm:px-3 rounded-lg border border-brand-600 text-brand-700 hover:bg-brand-50 text-[11px] sm:text-xs font-semibold transition text-center"
                >
                  Chi tiết
                </button>
                <button
                  type="button"
                  onclick="requestProductQuote('${p.name}')"
                  class="py-1.5 sm:py-2 px-1.5 sm:px-3 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-[11px] sm:text-xs font-semibold transition text-center"
                >
                  Báo giá
                </button>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterXingfaProduct(tag) {
      renderProducts(tag);
      document.querySelectorAll('.filter-btn').forEach((btn) => {
        const isActive = btn.getAttribute('data-filter') === tag;
        btn.className = isActive
          ? 'filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-700 text-white transition'
          : 'filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition';
      });
    }

    // Render 6 Dự án tại Đà Nẵng
    function renderProjects() {
      const grid = document.getElementById('projects-grid');
      grid.innerHTML = PROJECTS.map((proj, idx) => `
        <article
          onclick="openProjectModal(${idx})"
          class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-500 shadow-xs hover:shadow-lg transition-all flex flex-col"
        >
          <div class="aspect-[16/11] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(proj.driveId, 900)}"
              data-drive-id="${proj.driveId}"
              data-fallback-label="${encodeURIComponent(proj.title)}"
              onerror="handleDriveImageError(this)"
              alt="${proj.title}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-2">
            <h3 class="text-[12px] sm:text-sm font-bold text-brand-800 group-hover:text-brand-600 leading-snug break-words">
              ${proj.title}
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 flex items-center gap-1.5">
              <i class="fa-solid fa-location-dot text-brand-600"></i>
              <span>${proj.location}</span>
            </p>
          </div>
        </article>
      `).join('');
    }

    // Render Danh mục bài viết trang chủ
    function renderArticles() {
      const grid = document.getElementById('articles-grid');
      grid.innerHTML = ARTICLES.map((art, idx) => `
        <article
          onclick="openArticleModal(${idx})"
          class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-500 hover:shadow-md transition-all flex flex-col"
        >
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(art.driveId, 700)}"
              data-drive-id="${art.driveId}"
              data-fallback-label="Tin+Tuc+Nhom+Kinh"
              onerror="handleDriveImageError(this)"
              alt="${art.title}"
              loading="lazy"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
            />
          </div>
          <div class="p-4 flex flex-col flex-1 justify-between gap-2.5">
            <div>
              <div class="text-[11px] text-slate-400 mb-1.5">
                <i class="fa-regular fa-calendar mr-1"></i>${art.date}
              </div>
              <h3 class="text-sm font-bold text-slate-800 group-hover:text-brand-700 leading-snug mb-2">
                ${art.title}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                ${art.excerpt}
              </p>
            </div>
            <span class="text-xs font-bold text-brand-600 group-hover:underline inline-flex items-center gap-1 pt-1">
              Đọc chi tiết <i class="fa-solid fa-angle-right"></i>
            </span>
          </div>
        </article>
      `).join('');
    }

    // Render 6 Đối tác
    function renderPartners() {
      const grid = document.getElementById('partners-grid');
      grid.innerHTML = PARTNERS.map((pt) => `
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-md transition">
          <img
            src="${driveImgUrl(pt.driveId, 400)}"
            data-drive-id="${pt.driveId}"
            data-fallback-label="${encodeURIComponent(pt.name)}"
            onerror="handleDriveImageError(this)"
            alt="${pt.name} - Dũng Tín Thành Window"
            loading="lazy"
            class="max-h-full max-w-full object-contain"
          />
        </div>
      `).join('');
    }

    // Modal Helpers
    const modal = document.getElementById('detail-modal');
    const modalTitle = document.getElementById('modal-title');
    const modalBody = document.getElementById('modal-body');

    function showModal(title, htmlContent) {
      modalTitle.textContent = title;
      modalBody.innerHTML = htmlContent;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    document.getElementById('modal-close').addEventListener('click', closeModal);
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });

    function openProductModal(productId) {
      const p = PRODUCTS.find((item) => item.id === productId);
      if (!p) return;
      showModal(p.name, `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
            <span class="absolute top-2.5 left-2.5 px-2.5 py-0.5 rounded-md bg-accent-500 text-white text-xs font-extrabold">-${p.discount}%</span>
            <img src="${driveImgUrl(p.driveId, 900)}" data-drive-id="${p.driveId}" onerror="handleDriveImageError(this)" alt="${p.name}" class="w-full aspect-[4/3] object-cover" />
          </div>
          <div class="space-y-3 text-xs sm:text-sm">
            <div class="flex items-baseline gap-2.5">
              <span class="text-lg sm:text-xl font-extrabold text-accent-600">${formatVND(p.salePrice)}/m²</span>
              <span class="text-xs text-slate-400 line-through">${formatVND(p.originalPrice)}</span>
            </div>
            <ul class="space-y-1.5 text-slate-700 list-none m-0 p-0">
              <li><strong>Nhôm:</strong> ${p.spec.nhom}</li>
              <li><strong>Độ dày:</strong> ${p.spec.doDay}</li>
              <li><strong>Màu sắc:</strong> ${p.spec.mauSac}</li>
              <li><strong>Kính:</strong> ${p.spec.kinh}</li>
              <li><strong>Phụ kiện:</strong> ${p.spec.phuKien}</li>
              <li><strong>Bảo hành:</strong> ${p.spec.baoHanh}</li>
            </ul>
            <div class="pt-2 flex flex-wrap gap-2">
              <button type="button" onclick="closeModal(); requestProductQuote('${p.name}')" class="flex-1 py-2.5 px-4 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-bold text-xs sm:text-sm transition">
                Nhận báo giá ngay
              </button>
              <a href="tel:0905959991" class="py-2.5 px-4 rounded-lg bg-brand-700 hover:bg-brand-800 text-white font-bold text-xs sm:text-sm transition">
                Gọi 0905.959.991
              </a>
            </div>
          </div>
        </div>
      `);
    }

    function openProjectModal(index) {
      const proj = PROJECTS[index];
      if (!proj) return;
      showModal(proj.title, `
        <div class="space-y-4">
          <img src="${driveImgUrl(proj.driveId, 1100)}" data-drive-id="${proj.driveId}" onerror="handleDriveImageError(this)" alt="${proj.title}" class="w-full rounded-xl aspect-[16/10] object-cover border border-slate-200" />
          <div class="space-y-2 text-sm text-slate-700">
            <p><strong>Địa điểm:</strong> ${proj.location}</p>
            <p><strong>Đơn vị thi công:</strong> CÔNG TY TNHH SẢN XUẤT VÀ THƯƠNG MẠI D.T.T 46 (Dũng Tín Thành Window)</p>
            <p><strong>Hạng mục thực hiện:</strong> ${proj.scope}</p>
          </div>
          <div class="pt-1">
            <a href="#bao-gia" onclick="closeModal()" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-brand-700 hover:bg-brand-800 text-white text-xs sm:text-sm font-bold transition">
              Liên hệ tư vấn dự án tương tự
            </a>
          </div>
        </div>
      `);
    }

    function openArticleModal(index) {
      const art = ARTICLES[index];
      if (!art) return;
      showModal(art.title, `
        <div class="space-y-4">
          <img src="${driveImgUrl(art.driveId, 1000)}" data-drive-id="${art.driveId}" onerror="handleDriveImageError(this)" alt="${art.title}" class="w-full rounded-xl aspect-[16/9] object-cover border border-slate-200" />
          <div class="text-xs text-slate-500"><i class="fa-regular fa-calendar mr-1"></i>Ngày đăng: ${art.date} — Dũng Tín Thành Window</div>
          <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
          <div class="p-3.5 rounded-xl bg-brand-50 border border-brand-100 text-xs sm:text-sm text-brand-800">
            Cần tư vấn chi tiết hơn? Gọi ngay Hotline <strong>0905.959.991</strong> hoặc đến trực tiếp <strong>14 Chơn Tâm 12, Phường Hòa Khánh, TP Đà Nẵng</strong>.
          </div>
        </div>
      `);
    }

    function requestProductQuote(productName) {
      const noteEl = document.getElementById('q-note');
      const catEl = document.getElementById('q-category');
      if (catEl) catEl.value = 'Cửa nhôm Xingfa';
      if (noteEl) noteEl.value = `Tôi muốn nhận báo giá chi tiết cho sản phẩm: ${productName}`;
      document.getElementById('bao-gia').scrollIntoView({ behavior: 'smooth' });
      setTimeout(() => document.getElementById('q-name').focus(), 450);
    }

    // Toast notification nhẹ nhàng
    let toastTimer = null;
    function selectCategoryToast(categoryName) {
      const catEl = document.getElementById('q-category');
      if (catEl) {
        for (let opt of catEl.options) {
          if (opt.value.toLowerCase().includes(categoryName.toLowerCase().replace('cửa tự động', 'cửa kính tự động'))) {
            catEl.value = opt.value;
            break;
          }
        }
      }
      const box = document.getElementById('toast-box');
      box.textContent = `Đã chọn hạng mục: ${categoryName}`;
      box.classList.remove('hidden');
      clearTimeout(toastTimer);
      toastTimer = setTimeout(() => box.classList.add('hidden'), 2600);
    }

    // Hero Banner Slider (2 ảnh tự trượt kích thước bằng nhau)
    function initHeroSlider() {
      const slides = document.querySelectorAll('.hero-slide-item');
      const dots = document.querySelectorAll('.hero-dot');
      let current = 0;
      let timer = null;

      function goToSlide(index) {
        current = (index + slides.length) % slides.length;
        slides.forEach((s, i) => s.classList.toggle('active', i === current));
        dots.forEach((d, i) => {
          d.className = i === current
            ? 'hero-dot w-6 h-2 rounded-full bg-white transition-all'
            : 'hero-dot w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/80 transition-all';
        });
      }

      function startAuto() {
        stopAuto();
        timer = setInterval(() => goToSlide(current + 1), 5500);
      }

      function stopAuto() {
        if (timer) clearInterval(timer);
      }

      document.getElementById('hero-prev').addEventListener('click', () => {
        goToSlide(current - 1);
        startAuto();
      });

      document.getElementById('hero-next').addEventListener('click', () => {
        goToSlide(current + 1);
        startAuto();
      });

      dots.forEach((dot) => {
        dot.addEventListener('click', () => {
          goToSlide(parseInt(dot.getAttribute('data-slide'), 10));
          startAuto();
        });
      });

      // Hỗ trợ vuốt cảm ứng trên điện thoại
      const sliderEl = document.getElementById('hero-slider');
      let touchStartX = 0;
      sliderEl.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      sliderEl.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 40) {
          goToSlide(diff < 0 ? current + 1 : current - 1);
          startAuto();
        }
      }, { passive: true });

      startAuto();
    }

    // Mobile Menu Drawer & Accordions
    function initMobileMenu() {
      const openBtn = document.getElementById('mobile-menu-open');
      const closeBtn = document.getElementById('mobile-menu-close');
      const drawer = document.getElementById('mobile-drawer');
      const overlay = document.getElementById('mobile-drawer-overlay');

      function openDrawer() {
        drawer.classList.remove('-translate-x-full');
        overlay.classList.remove('hidden');
        document.body.style.overflow = 'hidden';
      }

      function closeDrawer() {
        drawer.classList.add('-translate-x-full');
        overlay.classList.add('hidden');
        document.body.style.overflow = '';
      }

      openBtn.addEventListener('click', openDrawer);
      closeBtn.addEventListener('click', closeDrawer);
      overlay.addEventListener('click', closeDrawer);

      document.querySelectorAll('.mobile-nav-link').forEach((link) => {
        link.addEventListener('click', closeDrawer);
      });

      document.querySelectorAll('.mobile-accordion-btn').forEach((btn) => {
        btn.addEventListener('click', () => {
          const targetId = btn.getAttribute('data-target');
          const sub = document.getElementById(targetId);
          const icon = btn.querySelector('i');
          if (sub) {
            sub.classList.toggle('hidden');
            icon.classList.toggle('rotate-180');
          }
        });
      });
    }

    // Form yêu cầu báo giá trang chủ
    function initQuoteForm() {
      const form = document.getElementById('quote-form');
      const feedback = document.getElementById('quote-feedback');

      form.addEventListener('submit', (e) => {
        e.preventDefault();
        const name = document.getElementById('q-name').value.trim();
        const phone = document.getElementById('q-phone').value.trim();
        const cat = document.getElementById('q-category').value;

        feedback.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá <strong>${cat}</strong> đã được tiếp nhận. Kỹ thuật viên Dũng Tín Thành sẽ liên hệ SĐT <strong>${phone}</strong> trong ít phút.`;
        feedback.classList.remove('hidden');
        form.reset();
      });
    }

    // Khởi chạy toàn bộ chức năng
    window.addEventListener('DOMContentLoaded', () => {
      renderCategories();
      renderProducts('all');
      renderProjects();
      renderArticles();
      renderPartners();
      initHeroSlider();
      initMobileMenu();
      initQuoteForm();
    });
  </script>
</body>
</html>
