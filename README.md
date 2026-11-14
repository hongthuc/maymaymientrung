<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>MÁY MAY MIỀN TRUNG | CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG</title>
  <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG (maymaymientrung.com) - Chuyên phân phối máy may công nghiệp Jack, Juki, Pegasus, Siruba, Brother, Hashima, Okito, Bruce, máy may cũ, cho thuê và thu mua máy may tại Đà Nẵng & Miền Trung. Hotline: 0877.441.859 - 0966.044.002." />

  <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link maymaymientrung.com -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="MÁY MAY MIỀN TRUNG - maymaymientrung.com" />
  <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG" />
  <meta property="og:description" content="Tổng kho máy may công nghiệp chính hãng tại Đà Nẵng & Miền Trung. SĐT: 0877.441.859 - 0966.044.002. Địa chỉ: Thửa đất số 295, Tờ bản đồ số 10, Tổ 4, Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng." />
  <meta property="og:url" content="https://maymaymientrung.com" />
  <meta property="og:image" content="https://placehold.co/1200x630/0b3b8c/ffffff?text=MAY+MAY+MIEN+TRUNG+%7C+maymaymientrung.com" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://placehold.co/1200x630/0b3b8c/ffffff?text=MAY+MAY+MIEN+TRUNG+%7C+maymaymientrung.com" />

  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800;900&display=swap" rel="stylesheet" />

  <!-- Font Awesome 6 Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brandBlue: '#0b3b8c',
            brandBlueDark: '#072963',
            brandBlueLight: '#e8f0fe',
            brandRed: '#d91e2a',
            brandRedDark: '#b3141f',
            flatsomeBg: '#f5f7fa',
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
    /* Reset chống tràn viền & chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      background-color: #f5f7fa;
      color: #222222;
      font-family: 'Inter', sans-serif;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      padding-left: 10px;
      padding-right: 10px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95vw;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng trong từng mục, không xuống dòng tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 2px;
      list-style: none;
      margin: 0;
      padding: 0;
    }
    .desktop-nav-item {
      position: relative;
    }
    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      white-space: nowrap; /* Tuyệt đối không xuống dòng bên trong tên danh mục */
      font-size: 12px;
      font-weight: 700;
      text-transform: uppercase;
      color: #ffffff;
      padding: 9px 9px;
      border-radius: 4px;
      transition: background-color 0.2s ease, color 0.2s ease;
      letter-spacing: 0.01em;
    }
    .desktop-nav-link:hover, .desktop-nav-link.active {
      background-color: #d91e2a;
      color: #ffffff;
    }

    /* Dropdown Submenu chuẩn Flatsome */
    .desktop-submenu {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 220px;
      background: #ffffff;
      border-top: 3px solid #d91e2a;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      border-radius: 0 0 6px 6px;
      z-index: 100;
      padding: 6px 0;
    }
    .desktop-nav-item:hover .desktop-submenu {
      display: block;
    }
    .desktop-submenu a {
      display: block;
      padding: 8px 14px;
      font-size: 12.5px;
      font-weight: 600;
      color: #1e293b;
      white-space: nowrap;
      border-bottom: 1px solid #f1f5f9;
      transition: all 0.15s ease;
    }
    .desktop-submenu a:last-child {
      border-bottom: none;
    }
    .desktop-submenu a:hover {
      background-color: #f1f5f9;
      color: #0b3b8c;
      padding-left: 18px;
    }

    /* Tiêu đề Section chuẩn Flatsome (Section Title Container) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #0b3b8c;
      margin-bottom: 16px;
      background: #ffffff;
      border-radius: 6px 6px 0 0;
      overflow: hidden;
    }
    .flatsome-section-heading {
      background: linear-gradient(135deg, #0b3b8c 0%, #154db3 100%);
      color: #ffffff;
      font-family: 'Montserrat', sans-serif;
      font-weight: 800;
      font-size: 14px;
      text-transform: uppercase;
      padding: 10px 18px;
      margin: 0;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      position: relative;
      white-space: nowrap;
    }
    @media (min-width: 768px) {
      .flatsome-section-heading {
        font-size: 16px;
        padding: 11px 24px;
      }
    }

    /* Thẻ sản phẩm Flatsome: Tên sản phẩm đầy đủ không bị cắt hay tràn ra ngoài */
    .flatsome-product-card {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 8px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
      position: relative;
      height: 100%;
    }
    .flatsome-product-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 20px rgba(11, 59, 140, 0.12);
      border-color: #0b3b8c;
    }

    /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d91e2a;
      color: #ffffff;
      font-weight: 800;
      font-size: 11.5px;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(217, 30, 42, 0.35);
      line-height: 1;
      pointer-events: none;
    }

    /* Tên sản phẩm tự động xuống dòng gọn gàng, tuyệt đối không tràn viền và không bị cắt mất chữ */
    .flatsome-product-title {
      font-size: 13px;
      font-weight: 600;
      color: #1e293b;
      line-height: 1.4;
      word-wrap: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      margin-bottom: 6px;
      transition: color 0.15s ease;
    }
    @media (min-width: 768px) {
      .flatsome-product-title {
        font-size: 14px;
      }
    }
    .flatsome-product-card:hover .flatsome-product-title {
      color: #0b3b8c;
    }

    /* Banner Slider 2 ảnh bằng nhau tuyệt đối, chữ nằm gọn bên trong cách xa viền */
    .banner-slide-wrapper {
      position: relative;
      width: 100%;
      height: 290px;
      border-radius: 10px;
      overflow: hidden;
    }
    @media (min-width: 640px) {
      .banner-slide-wrapper {
        height: 330px;
      }
    }
    @media (min-width: 1024px) {
      .banner-slide-wrapper {
        height: 390px;
      }
    }
    .banner-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.6s ease-in-out, visibility 0.6s ease-in-out;
    }
    .banner-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 30, 42, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 30, 42, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 30, 42, 0); }
    }
    .pulse-contact {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- =====================================================================
       1. TOP BAR CHUẨN FLATSOME (KHÔNG CÓ THANH UX BUILDER)
       ===================================================================== -->
  <div class="bg-brandBlueDark text-white text-xs py-2 border-b border-blue-900">
    <div class="flatsome-container flex flex-col md:flex-row items-center justify-between gap-1.5">
      <div class="flex items-center gap-2 text-center md:text-left">
        <i class="fa-solid fa-building text-yellow-400 shrink-0"></i>
        <span class="font-semibold tracking-wide">CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG</span>
      </div>
      <div class="flex flex-wrap items-center justify-center md:justify-end gap-x-4 gap-y-1 text-[11.5px] text-blue-100">
        <span>
          <i class="fa-solid fa-location-dot text-red-400 mr-1"></i>
          Thửa đất số 295, Tờ bản đồ số 10, Tổ 4, Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng
        </span>
        <span class="hidden sm:inline">|</span>
        <span class="font-bold text-yellow-300">
          <i class="fa-solid fa-phone-volume mr-1"></i>
          0877.441.859 - 0966.044.002
        </span>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       2. HEADER CHÍNH (LOGO NHỎ GỌN, TÌM KIẾM, CAM KẾT - KHÔNG ĐỂ NÚT GỌI NGAY)
       ===================================================================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40">
    <div class="flatsome-container py-2.5 md:py-3">
      <div class="flex items-center justify-between gap-2 md:gap-5">

        <!-- Nút mở Menu trên Điện thoại -->
        <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-md bg-brandBlue text-white hover:bg-brandRed transition shrink-0">
          <i class="fa-solid fa-bars text-base"></i>
        </button>

        <!-- LOGO CÔNG TY CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
        <a href="#top" class="flex items-center gap-2.5 shrink-0 group">
          <div class="w-10 h-10 md:w-11 md:h-11 rounded-lg bg-gradient-to-br from-brandBlue to-brandBlueDark flex items-center justify-center shadow-sm border border-blue-800 shrink-0">
            <!-- Vector Logo Máy May Miền Trung chuyên nghiệp, nhỏ gọn -->
            <svg class="w-7 h-7 md:w-8 md:h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <!-- Khung thân máy may công nghiệp cách điệu chữ M -->
              <path d="M10 48H54V54H10V48Z" fill="#d91e2a"/>
              <path d="M14 16C14 13.7909 15.7909 12 18 12H46C49.3137 12 52 14.6863 52 18V46H42V24H30V34H22V24H14V16Z" fill="#ffffff"/>
              <!-- Trụ kim & bánh đà -->
              <rect x="24" y="34" width="4" height="10" rx="1" fill="#fbbf24"/>
              <circle cx="46" cy="20" r="3.5" fill="#d91e2a"/>
              <path d="M12 44L36 44" stroke="#93c5fd" stroke-width="2" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="leading-tight">
            <div class="font-heading font-extrabold text-brandBlue text-xs sm:text-sm md:text-[15px] tracking-tight group-hover:text-brandRed transition">
              MÁY MAY MIỀN TRUNG
            </div>
            <div class="text-[10px] md:text-[11px] font-semibold text-brandRed tracking-wider">
              maymaymientrung.com
            </div>
          </div>
        </a>

        <!-- Thanh tìm kiếm sản phẩm ở giữa -->
        <div class="hidden sm:flex flex-1 max-w-md mx-auto">
          <form id="headerSearchForm" class="w-full flex items-center border-2 border-brandBlue rounded-md overflow-hidden bg-slate-50">
            <input
              id="headerSearchInput"
              type="text"
              placeholder="Tìm máy may Jack, Juki, Pegasus, Siruba, Brother, máy cũ..."
              class="w-full px-3 py-1.5 text-xs md:text-sm bg-transparent focus:outline-none text-slate-800"
            />
            <button type="submit" class="bg-brandBlue hover:bg-brandRed text-white px-3.5 py-2 text-xs font-semibold transition shrink-0">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </form>
        </div>

        <!-- 3 Tiện ích chuẩn mẫu maymaydanang.com (Không để nút gọi ngay tránh tràn viền) -->
        <div class="hidden xl:flex items-center gap-5 shrink-0">
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brandBlue flex items-center justify-center text-sm shrink-0 border border-blue-200">
              <i class="fa-solid fa-truck-fast"></i>
            </div>
            <div class="leading-tight">
              <div class="text-[11px] font-bold text-brandBlue uppercase">GIAO HÀNG TẬN NƠI</div>
              <div class="text-[10.5px] text-slate-500">Đà Nẵng & Miền Trung</div>
            </div>
          </div>
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-red-50 text-brandRed flex items-center justify-center text-sm shrink-0 border border-red-200">
              <i class="fa-solid fa-headset"></i>
            </div>
            <div class="leading-tight">
              <div class="text-[11px] font-bold text-brandBlue uppercase">HỖ TRỢ KỸ THUẬT</div>
              <div class="text-[10.5px] text-slate-500">Tư vấn miễn phí 24/7</div>
            </div>
          </div>
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-amber-50 text-amber-600 flex items-center justify-center text-sm shrink-0 border border-amber-200">
              <i class="fa-solid fa-shield-halved"></i>
            </div>
            <div class="leading-tight">
              <div class="text-[11px] font-bold text-brandBlue uppercase">THANH TOÁN TIỆN LỢI</div>
              <div class="text-[10.5px] text-slate-500">Kiểm tra khi nhận máy</div>
            </div>
          </div>
        </div>

        <!-- Nút bật ô tìm kiếm nhanh trên màn hình nhỏ -->
        <button id="mobileSearchToggle" type="button" aria-label="Tìm kiếm" class="sm:hidden inline-flex items-center justify-center w-9 h-9 rounded-md bg-slate-100 text-brandBlue hover:bg-blue-50 shrink-0">
          <i class="fa-solid fa-magnifying-glass text-sm"></i>
        </button>

      </div>

      <!-- Ô tìm kiếm thu gọn trên Mobile -->
      <div id="mobileSearchBox" class="hidden sm:hidden mt-2">
        <form id="mobileSearchForm" class="flex items-center border border-brandBlue rounded-md overflow-hidden bg-white">
          <input
            id="mobileSearchInput"
            type="text"
            placeholder="Nhập tên máy may cần tìm..."
            class="w-full px-3 py-1.5 text-xs focus:outline-none"
          />
          <button type="submit" class="bg-brandBlue text-white px-3 py-1.5 text-xs font-semibold">
            Tìm
          </button>
        </form>
      </div>
    </div>

    <!-- ===================================================================
         3. THANH MENU DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC)
         =================================================================== -->
    <nav class="hidden lg:block bg-brandBlue border-t border-blue-800">
      <div class="flatsome-container">
        <ul class="desktop-nav-list">
          <li class="desktop-nav-item">
            <a href="#top" class="desktop-nav-link active"><i class="fa-solid fa-house text-[11px]"></i> TRANG CHỦ</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#gioi-thieu" class="desktop-nav-link">GIỚI THIỆU</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-bruce" class="desktop-nav-link">BRUCE <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-bruce">Máy 1 kim BRUCE</a>
              <a href="#sec-bruce">Máy vắt sổ BRUCE</a>
              <a href="#sec-bruce">Máy chuyên dùng BRUCE</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-jack" class="desktop-nav-link">JACK <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-jack">Máy May Jack</a>
              <a href="#sec-jack">Máy Vắt Sổ Jack</a>
              <a href="#sec-jack">Máy Trần Đè Jack</a>
              <a href="#sec-jack">Máy Chuyên Dùng Jack</a>
              <a href="#sec-jack">Motor Tiết Kiệm Điện</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-juki" class="desktop-nav-link">JUKI <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-juki">Máy 1 Kim Điện Tử Juki</a>
              <a href="#sec-juki">Máy Vắt Sổ Juki</a>
              <a href="#sec-juki">Máy Thùa Khuy & Đính Bọ Juki</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-pegasus" class="desktop-nav-link">PEGASUS <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-pegasus">Máy chuyên dụng Pegasus</a>
              <a href="#sec-pegasus">Máy trần đè Pegasus</a>
              <a href="#sec-pegasus">Máy tự động Pegasus</a>
              <a href="#sec-pegasus">Máy vắt sổ Pegasus</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-siruba" class="desktop-nav-link">SIRUBA <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-siruba">Máy một kim Siruba</a>
              <a href="#sec-siruba">Máy hai kim Siruba</a>
              <a href="#sec-siruba">Máy khuy, bọ, nút Siruba</a>
              <a href="#sec-siruba">Máy móc xích Siruba</a>
              <a href="#sec-siruba">Máy trần đè Siruba</a>
              <a href="#sec-siruba">Máy tự động Siruba</a>
              <a href="#sec-siruba">Máy vắt sổ Siruba</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-brother" class="desktop-nav-link">BROTHER <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-brother">Máy một kim Brother</a>
              <a href="#sec-brother">Máy hai kim Brother</a>
              <a href="#sec-brother">Máy cuốn sườn Brother</a>
              <a href="#sec-brother">Máy đính bọ & đính nút Brother</a>
              <a href="#sec-brother">Máy lập trình điện tử Brother</a>
              <a href="#sec-brother">Máy thắt nút zig zag & thùa khuy</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-hashima" class="desktop-nav-link">MÁY CÔNG NGHIỆP HÓA <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-hashima">Máy cắt vải Hashima</a>
              <a href="#sec-hashima">Máy cắt vòng Hashima</a>
              <a href="#sec-hashima">Máy dò kim Hashima</a>
              <a href="#sec-hashima">MÁY IN SƠ ĐỒ</a>
              <a href="#sec-hashima">MÁY CẮT RẬP</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-okito" class="desktop-nav-link">OKITO <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-okito">Máy May Okito</a>
              <a href="#sec-okito">Máy Vắt Sổ Okito</a>
              <a href="#sec-okito">Máy Trần Đè Okito</a>
              <a href="#sec-okito">Máy Chuyên Dùng Okito</a>
              <a href="#sec-okito">Ép Mếch & Nồi Hơi</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-may-cu" class="desktop-nav-link">MÁY MAY CŨ <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-may-cu">Máy may cũ Jack</a>
              <a href="#sec-may-cu">Máy may cũ Juki</a>
              <a href="#sec-may-cu">Máy may cũ Siruba</a>
              <a href="#sec-may-cu">Máy may cũ Brother</a>
              <a href="#sec-may-cu">Máy may cũ Okito, Accor, Zusun</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#sec-phu-tung" class="desktop-nav-link">THIẾT BỊ PHỤ TÙNG <i class="fa-solid fa-angle-down text-[10px]"></i></a>
            <div class="desktop-submenu">
              <a href="#sec-phu-tung">Ghế Ngồi May Công Nghiệp</a>
              <a href="#sec-phu-tung">Linh kiện máy 1 kim, vắt sổ</a>
              <a href="#sec-phu-tung">Bàn hút, nồi hơi, bàn ủi</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#form-bao-gia" class="desktop-nav-link">THU MUA - CHO THUÊ</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#tin-tuc" class="desktop-nav-link">TIN TỨC</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#lien-he-ban-do" class="desktop-nav-link">LIÊN HỆ</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- MENU DRAWER CHO ĐIỆN THOẠI (ĐẸP, GỌN, DỄ BẤM) -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/60 z-50 hidden">
    <div class="w-72 max-w-[85vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
      <div>
        <div class="p-3.5 bg-brandBlue text-white flex items-center justify-between">
          <span class="font-heading font-bold text-xs uppercase tracking-wider">DANH MỤC MÁY MAY MIỀN TRUNG</span>
          <button id="closeMobileMenuBtn" type="button" class="w-7 h-7 rounded bg-white/15 flex items-center justify-center text-white">
            <i class="fa-solid fa-xmark"></i>
          </button>
        </div>
        <div class="divide-y divide-slate-100 text-xs font-semibold text-slate-800">
          <a href="#top" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50 text-brandBlue"><i class="fa-solid fa-house mr-2"></i>TRANG CHỦ</a>
          <a href="#gioi-thieu" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-circle-info mr-2 text-brandBlue"></i>GIỚI THIỆU CÔNG TY</a>
          <a href="#sec-jack" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY JACK</a>
          <a href="#sec-juki" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY JUKI</a>
          <a href="#sec-pegasus" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY PEGASUS</a>
          <a href="#sec-siruba" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY SIRUBA</a>
          <a href="#sec-brother" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY BROTHER</a>
          <a href="#sec-hashima" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-scissors mr-2 text-brandBlue"></i>MÁY CÔNG NGHIỆP HÓA HASHIMA</a>
          <a href="#sec-okito" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY OKITO</a>
          <a href="#sec-bruce" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears mr-2 text-brandBlue"></i>MÁY MAY BRUCE</a>
          <a href="#sec-may-cu" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-recycle mr-2 text-brandRed"></i>MÁY MAY CŨ CHÍNH HÃNG</a>
          <a href="#sec-phu-tung" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-screwdriver-wrench mr-2 text-brandBlue"></i>THIẾT BỊ & PHỤ TÙNG</a>
          <a href="#form-bao-gia" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-file-invoice-dollar mr-2 text-brandRed"></i>THU MUA & CHO THUÊ MÁY MAY</a>
          <a href="#tin-tuc" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-newspaper mr-2 text-brandBlue"></i>TIN TỨC</a>
          <a href="#lien-he-ban-do" class="mobile-nav-item block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-map-location-dot mr-2 text-brandBlue"></i>LIÊN HỆ & BẢN ĐỒ</a>
        </div>
      </div>
      <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs">
        <div class="font-bold text-brandBlue mb-1">HOTLINE HỖ TRỢ 24/7:</div>
        <a href="tel:0877441859" class="block font-extrabold text-brandRed text-sm py-0.5">0877.441.859</a>
        <a href="tel:0966044002" class="block font-extrabold text-brandBlue text-sm py-0.5">0966.044.002</a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       4. SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
          (HÌNH ẢNH VÀ CHỮ NẰM TRONG HẾT BANNER, CÁCH XA VIỀN, KHÔNG BỊ THIẾU CHỮ)
       ===================================================================== -->
  <section id="top" class="py-3 md:py-4">
    <div class="flatsome-container">
      <div class="banner-slide-wrapper shadow-md border border-blue-900/20">

        <!-- SLIDE 1: TỔNG KHO PHÂN PHỐI MÁY MAY CHÍNH HÃNG -->
        <div class="banner-slide active bg-gradient-to-r from-[#07255c] via-[#0b3b8c] to-[#134eb0]">
          <!-- Vùng an toàn (Safe-Zone) cách xa viền banner trên cả điện thoại và máy tính -->
          <div class="w-full h-full px-7 py-5 sm:px-12 sm:py-7 md:px-16 lg:px-20 flex flex-col md:flex-row items-center justify-between gap-4">
            <!-- Khối Chữ nằm gọn trong lòng banner -->
            <div class="w-full md:w-[60%] text-white text-center md:text-left flex flex-col justify-center">
              <div class="inline-flex items-center self-center md:self-start gap-1.5 bg-brandRed text-white text-[10px] sm:text-xs font-bold px-3 py-1 rounded-full mb-2 uppercase tracking-wider">
                <i class="fa-solid fa-star text-yellow-300"></i> maymaymientrung.com
              </div>
              <h1 class="font-heading font-extrabold text-sm sm:text-lg md:text-2xl lg:text-[26px] leading-snug text-white mb-1.5">
                CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG
              </h1>
              <p class="text-[11px] sm:text-xs md:text-sm text-blue-100 leading-relaxed mb-3">
                Chuyên nhập khẩu & phân phối Máy May Công Nghiệp <strong class="text-yellow-300">JACK, JUKI, PEGASUS, SIRUBA, BROTHER, HASHIMA, OKITO, BRUCE</strong> mới & cũ chính hãng tại Đà Nẵng và toàn Miền Trung.
              </p>
              <div class="flex flex-wrap items-center justify-center md:justify-start gap-2 text-[11px] sm:text-xs">
                <span class="bg-white text-brandBlue font-extrabold px-3 py-1.5 rounded-md shadow">
                  <i class="fa-solid fa-phone-volume text-brandRed mr-1"></i>0877.441.859 - 0966.044.002
                </span>
                <a href="#form-bao-gia" class="bg-yellow-400 hover:bg-yellow-300 text-slate-900 font-extrabold px-3.5 py-1.5 rounded-md shadow transition">
                  Nhận Báo Giá Ngay
                </a>
              </div>
            </div>

            <!-- Khối Hình Ảnh Sản Phẩm Thực Tế nằm gọn bên trong Banner 1 -->
            <div class="hidden sm:flex w-full md:w-[38%] items-center justify-center">
              <div class="bg-white/95 p-2.5 rounded-xl shadow-lg border-2 border-yellow-400 max-w-[260px] lg:max-w-[300px] w-full flex items-center gap-2.5">
                <img
                  src="https://lh3.googleusercontent.com/d/1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO=w600"
                  data-drive-id="1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO"
                  alt="Máy may công nghiệp thực tế"
                  class="w-24 h-24 lg:w-28 lg:h-28 object-contain rounded-lg bg-white shrink-0 drive-img"
                />
                <div class="text-left leading-snug">
                  <div class="text-[11px] font-extrabold text-brandRed uppercase">HÀNG SẴN TẠI KHO</div>
                  <div class="text-xs font-bold text-brandBlue">Máy 1 Kim, Vắt Sổ, Trần Đè, Lập Trình</div>
                  <div class="text-[10.5px] text-slate-600 mt-1">Bảo hành tận nơi - Giao máy nhanh 24h</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2: DỊCH VỤ CHO THUÊ - THU MUA - THANH LÝ XƯỞNG MAY -->
        <div class="banner-slide bg-gradient-to-r from-[#7f1d1d] via-[#b91c1c] to-[#0b3b8c]">
          <!-- Vùng an toàn (Safe-Zone) cách xa viền banner trên cả điện thoại và máy tính -->
          <div class="w-full h-full px-7 py-5 sm:px-12 sm:py-7 md:px-16 lg:px-20 flex flex-col md:flex-row items-center justify-between gap-4">
            <!-- Khối Chữ nằm gọn trong lòng banner -->
            <div class="w-full md:w-[60%] text-white text-center md:text-left flex flex-col justify-center">
              <div class="inline-flex items-center self-center md:self-start gap-1.5 bg-yellow-400 text-slate-900 text-[10px] sm:text-xs font-extrabold px-3 py-1 rounded-full mb-2 uppercase tracking-wider">
                <i class="fa-solid fa-handshake"></i> GIẢI PHÁP TỐI ƯU CHO XƯỞNG MAY
              </div>
              <h2 class="font-heading font-extrabold text-sm sm:text-lg md:text-2xl lg:text-[26px] leading-snug text-white mb-1.5">
                CHO THUÊ MÁY MAY & THU MUA MÁY MÓC NHÀ XƯỞNG GIÁ CAO
              </h2>
              <p class="text-[11px] sm:text-xs md:text-sm text-red-100 leading-relaxed mb-3">
                Cung cấp trọn gói thiết bị ngành may, nồi hơi, bàn hút, máy cắt vải, ghế ngồi may. Hỗ trợ lắp đặt, sửa chữa và bảo trì tận xưởng tại Xã Thăng Điền, TP Đà Nẵng & Miền Trung.
              </p>
              <div class="flex flex-wrap items-center justify-center md:justify-start gap-2 text-[11px] sm:text-xs">
                <span class="bg-white text-brandRed font-extrabold px-3 py-1.5 rounded-md shadow">
                  <i class="fa-solid fa-location-dot mr-1"></i>Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng
                </span>
                <a href="tel:0877441859" class="bg-brandBlue hover:bg-blue-800 text-white font-extrabold px-3.5 py-1.5 rounded-md border border-white/30 shadow transition">
                  Tư Vấn: 0877.441.859
                </a>
              </div>
            </div>

            <!-- Khối Hình Ảnh Sản Phẩm Thực Tế nằm gọn bên trong Banner 2 -->
            <div class="hidden sm:flex w-full md:w-[38%] items-center justify-center">
              <div class="bg-white/95 p-2.5 rounded-xl shadow-lg border-2 border-blue-300 max-w-[260px] lg:max-w-[300px] w-full flex items-center gap-2.5">
                <img
                  src="https://lh3.googleusercontent.com/d/1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY=w600"
                  data-drive-id="1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY"
                  alt="Máy may công nghiệp thực tế tại xưởng"
                  class="w-24 h-24 lg:w-28 lg:h-28 object-contain rounded-lg bg-white shrink-0 drive-img"
                />
                <div class="text-left leading-snug">
                  <div class="text-[11px] font-extrabold text-brandBlue uppercase">THU MUA & CHO THUÊ</div>
                  <div class="text-xs font-bold text-slate-800">Máy May Cũ & Mới Tiết Kiệm 40% - 60%</div>
                  <div class="text-[10.5px] text-slate-600 mt-1">Kiểm định kỹ thuật 100% trước khi giao</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút chuyển trái/phải nằm gọn trong banner -->
        <button id="prevBannerBtn" type="button" aria-label="Slide trước" class="absolute left-1.5 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-brandRed text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button id="nextBannerBtn" type="button" aria-label="Slide tiếp" class="absolute right-1.5 top-1/2 -translate-y-1/2 z-10 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-brandRed text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>

        <!-- Dấu chấm chỉ mục slide -->
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
          <button type="button" data-slide="0" class="banner-dot w-6 h-2 rounded-full bg-yellow-400 transition"></button>
          <button type="button" data-slide="1" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       5. DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, TỐI ƯU ĐẸP TRÊN PC & MOBILE)
       ===================================================================== -->
  <section class="py-3">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg shadow-sm border border-slate-200 p-3 md:p-4">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3">
          <h2 class="font-heading font-extrabold text-brandBlue text-xs sm:text-sm md:text-base uppercase flex items-center gap-2">
            <i class="fa-solid fa-layer-group text-brandRed"></i> DANH MỤC SẢN PHẨM
          </h2>
          <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn nhanh danh mục thương hiệu máy may</span>
        </div>

        <!-- Chia 5 cột trên Mobile/Tablet, 10 cột trên Desktop chữ nhỏ gọn trên 1 hàng -->
        <div class="grid grid-cols-2 sm:grid-cols-5 lg:grid-cols-10 gap-2">
          <a href="#sec-jack" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO=w300" data-drive-id="1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO" alt="Jack" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">MÁY MAY JACK</span>
          </a>

          <a href="#sec-juki" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY=w300" data-drive-id="1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY" alt="Juki" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">MÁY MAY JUKI</span>
          </a>

          <a href="#sec-pegasus" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ=w300" data-drive-id="1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ" alt="Pegasus" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">PEGASUS</span>
          </a>

          <a href="#sec-siruba" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW=w300" data-drive-id="12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW" alt="Siruba" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">SIRUBA</span>
          </a>

          <a href="#sec-brother" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1ddql_KSs3fC_wu28mFNPMR6lOUM41X_k=w300" data-drive-id="1ddql_KSs3fC_wu28mFNPMR6lOUM41X_k" alt="Brother" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">BROTHER</span>
          </a>

          <a href="#sec-hashima" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1TDWHfvK5GYBGOdCusjqR2O-6qiN0LNna=w300" data-drive-id="1TDWHfvK5GYBGOdCusjqR2O-6qiN0LNna" alt="Hashima" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">HASHIMA</span>
          </a>

          <a href="#sec-okito" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1vmUreyihYBiqwx0H5LLWrMpWjgGmGWCw=w300" data-drive-id="1vmUreyihYBiqwx0H5LLWrMpWjgGmGWCw" alt="Okito" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">OKITO</span>
          </a>

          <a href="#sec-bruce" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1M_FcEsuAbMjQbxQVskjuOkOwO7oQTxCu=w300" data-drive-id="1M_FcEsuAbMjQbxQVskjuOkOwO7oQTxCu" alt="Bruce" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">BRUCE</span>
          </a>

          <a href="#sec-may-cu" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1VLEEdeu3TaN4RNe93S5NoFJnnbYqstrH=w300" data-drive-id="1VLEEdeu3TaN4RNe93S5NoFJnnbYqstrH" alt="Máy may cũ" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">MÁY MAY CŨ</span>
          </a>

          <a href="#sec-phu-tung" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brandBlue hover:bg-blue-50/40 transition text-center">
            <div class="w-12 h-12 rounded-full bg-slate-50 border border-slate-200 flex items-center justify-center overflow-hidden mb-1.5">
              <img src="https://lh3.googleusercontent.com/d/1t93PopaJwLUXH-fgN4KGTKnQKE-eeqjs=w300" data-drive-id="1t93PopaJwLUXH-fgN4KGTKnQKE-eeqjs" alt="Phụ tùng" class="w-full h-full object-contain drive-img" />
            </div>
            <span class="text-[11.5px] font-bold text-slate-800 group-hover:text-brandBlue whitespace-nowrap">PHỤ TÙNG</span>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       6. BỘ SƯU TẬP 11 SẢN PHẨM THỰC TẾ TỪ LINK GOOGLE DRIVE ĐÚNG DANH MỤC
          + CÁC DANH MỤC SẢN PHẨM GIỐNG WEB MẪU MAYMAYDANANG.COM
          (2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH, % GIẢM GIÁ GÓC TRÁI TRÊN)
       ===================================================================== -->
  <main id="productSectionsContainer" class="space-y-6 py-2">
    <!-- Được render tự động bằng dữ liệu chuẩn bên dưới để giữ cấu trúc UX Builder Flatsome sạch sẽ -->
  </main>

  <!-- =====================================================================
       7. GIỚI THIỆU NGẮN VỀ CÔNG TY TNHH TM & DV MÁY MAY MIỀN TRUNG
       ===================================================================== -->
  <section id="gioi-thieu" class="py-4">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg shadow-sm border border-slate-200 p-4 md:p-6">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          <div class="lg:col-span-7">
            <div class="text-xs font-extrabold text-brandRed uppercase tracking-wider mb-1">
              VỀ CHÚNG TÔI - MAYMAYMIENTRUNG.COM
            </div>
            <h2 class="font-heading font-extrabold text-brandBlue text-base sm:text-lg md:text-xl mb-3">
              CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG
            </h2>
            <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
              <strong>CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG</strong> (Mã số thuế: <strong>4001325801</strong>) là đơn vị uy tín chuyên nhập khẩu, phân phối, cho thuê, thu mua và sửa chữa máy may công nghiệp chính hãng tại TP Đà Nẵng và khu vực Miền Trung.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs text-slate-700 mb-4">
              <div class="flex items-start gap-2 bg-slate-50 p-2.5 rounded border border-slate-200">
                <i class="fa-solid fa-circle-check text-brandBlue mt-0.5"></i>
                <span>Phân phối chính hãng <strong>Jack, Juki, Pegasus, Siruba, Brother, Hashima, Okito, Bruce</strong>.</span>
              </div>
              <div class="flex items-start gap-2 bg-slate-50 p-2.5 rounded border border-slate-200">
                <i class="fa-solid fa-circle-check text-brandBlue mt-0.5"></i>
                <span>Kho máy may cũ chất lượng 90-95%, tiết kiệm 40-60% chi phí đầu tư xưởng.</span>
              </div>
              <div class="flex items-start gap-2 bg-slate-50 p-2.5 rounded border border-slate-200">
                <i class="fa-solid fa-circle-check text-brandBlue mt-0.5"></i>
                <span>Dịch vụ <strong>Cho thuê máy may</strong> và <strong>Thu mua thanh lý nhà xưởng</strong> giá tốt.</span>
              </div>
              <div class="flex items-start gap-2 bg-slate-50 p-2.5 rounded border border-slate-200">
                <i class="fa-solid fa-circle-check text-brandBlue mt-0.5"></i>
                <span>Kỹ thuật viên hỗ trợ lắp đặt, bảo hành tận nơi nhanh chóng 24/7.</span>
              </div>
            </div>
            <div class="text-xs sm:text-sm space-y-1 text-slate-800 bg-blue-50/70 p-3 rounded-lg border border-blue-200">
              <div><i class="fa-solid fa-location-dot text-brandRed mr-1.5"></i><strong>Địa chỉ:</strong> Thửa đất số 295, Tờ bản đồ số 10, Tổ 4, Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng</div>
              <div><i class="fa-solid fa-phone-volume text-brandRed mr-1.5"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0877441859" class="font-bold text-brandBlue">0877.441.859</a> - <a href="tel:0966044002" class="font-bold text-brandBlue">0966.044.002</a></div>
              <div><i class="fa-solid fa-globe text-brandRed mr-1.5"></i><strong>Website:</strong> maymaymientrung.com</div>
            </div>
          </div>

          <!-- Khung ảnh thực tế từ Google Drive -->
          <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
            <div class="bg-slate-50 p-2 rounded-lg border border-slate-200">
              <img src="https://lh3.googleusercontent.com/d/1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO=w500" data-drive-id="1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO" alt="Ảnh kho máy thực tế 1" class="w-full h-36 object-contain bg-white rounded drive-img" />
            </div>
            <div class="bg-slate-50 p-2 rounded-lg border border-slate-200">
              <img src="https://lh3.googleusercontent.com/d/1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ=w500" data-drive-id="1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ" alt="Ảnh kho máy thực tế 2" class="w-full h-36 object-contain bg-white rounded drive-img" />
            </div>
            <div class="bg-slate-50 p-2 rounded-lg border border-slate-200">
              <img src="https://lh3.googleusercontent.com/d/12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW=w500" data-drive-id="12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW" alt="Ảnh kho máy thực tế 3" class="w-full h-36 object-contain bg-white rounded drive-img" />
            </div>
            <div class="bg-slate-50 p-2 rounded-lg border border-slate-200">
              <img src="https://lh3.googleusercontent.com/d/1A_QsEgJ3TKkOohuE1M8fWji6-av8tLS9=w500" data-drive-id="1A_QsEgJ3TKkOohuE1M8fWji6-av8tLS9" alt="Ảnh kho máy thực tế 4" class="w-full h-36 object-contain bg-white rounded drive-img" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       8. FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ
       ===================================================================== -->
  <section id="form-bao-gia" class="py-4">
    <div class="flatsome-container">
      <div class="bg-gradient-to-r from-brandBlueDark via-brandBlue to-[#134eb0] rounded-lg shadow-md p-4 md:p-6 text-white">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          <div class="lg:col-span-5">
            <span class="inline-block bg-brandRed text-white text-[11px] font-bold px-3 py-1 rounded uppercase mb-2">
              HỖ TRỢ BÁO GIÁ SỈ & LẺ 24/7
            </span>
            <h2 class="font-heading font-extrabold text-base sm:text-lg md:text-xl uppercase mb-2">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ MÁY MAY
            </h2>
            <p class="text-xs sm:text-sm text-blue-100 leading-relaxed mb-4">
              Quý khách cần báo giá mở xưởng may mới, mua lẻ máy may 1 kim, vắt sổ, trần đè, thuê máy may hoặc thanh lý máy cũ? Vui lòng điền thông tin bên cạnh, bộ phận kỹ thuật của <strong>Máy May Miền Trung</strong> sẽ gọi lại ngay trong 5 phút!
            </p>
            <div class="space-y-2 text-xs sm:text-sm bg-white/10 p-3.5 rounded-lg border border-white/15">
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-phone-volume text-yellow-300"></i>
                <span>Hotline 1: <strong class="text-yellow-300">0877.441.859</strong></span>
              </div>
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-phone-volume text-yellow-300"></i>
                <span>Hotline 2: <strong class="text-yellow-300">0966.044.002</strong></span>
              </div>
              <div class="flex items-start gap-2">
                <i class="fa-solid fa-location-dot text-yellow-300 mt-1"></i>
                <span>Thửa đất số 295, Tờ bản đồ số 10, Tổ 4, Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng</span>
              </div>
            </div>
          </div>

          <div class="lg:col-span-7">
            <form id="quoteRequestForm" class="bg-white text-slate-800 rounded-lg p-4 md:p-5 shadow-lg">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brandBlue" />
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brandBlue" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 mb-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục sản phẩm / dịch vụ</label>
                  <select id="qCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brandBlue bg-white">
                    <option value="Máy may Jack chính hãng">Máy may Jack chính hãng</option>
                    <option value="Máy may Juki chính hãng">Máy may Juki chính hãng</option>
                    <option value="Máy vắt sổ / trần đè Pegasus">Máy vắt sổ / trần đè Pegasus</option>
                    <option value="Máy may Siruba / Brother">Máy may Siruba / Brother</option>
                    <option value="Máy cắt vải / Thiết bị Hashima">Máy cắt vải / Thiết bị Hashima</option>
                    <option value="Máy may Okito / Bruce">Máy may Okito / Bruce</option>
                    <option value="Mua máy may cũ tiết kiệm chi phí">Mua máy may cũ tiết kiệm chi phí</option>
                    <option value="Thuê máy may công nghiệp">Thuê máy may công nghiệp</option>
                    <option value="Cần bán / Thanh lý máy may cũ">Cần bán / Thanh lý máy may cũ</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ nhận máy (Tỉnh/Huyện)</label>
                  <input id="qAddress" type="text" placeholder="Ví dụ: Thăng Điền, Đà Nẵng..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brandBlue" />
                </div>
              </div>

              <div class="mb-3">
                <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu và số lượng cần báo giá</label>
                <textarea id="qNote" rows="2" placeholder="Nhập dòng máy, số lượng hoặc yêu cầu tư vấn kỹ thuật..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brandBlue"></textarea>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-2">
                <button type="submit" class="bg-brandRed hover:bg-brandRedDark text-white font-bold text-xs sm:text-sm px-5 py-2.5 rounded transition flex items-center gap-2">
                  <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ
                </button>
                <a href="https://zalo.me/0877441859" target="_blank" rel="noopener noreferrer" class="bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs sm:text-sm px-4 py-2.5 rounded transition flex items-center gap-1.5">
                  <i class="fa-solid fa-comment-dots"></i> Chat Zalo: 0877.441.859
                </a>
              </div>

              <div id="quoteSuccessMsg" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-semibold"></div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC NỔI BẬT GIỐNG WEB MẪU)
       ===================================================================== -->
  <section id="tin-tuc" class="py-4">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <h2 class="flatsome-section-heading">
          <i class="fa-solid fa-newspaper"></i> TIN TỨC & BÀI VIẾT NỔI BẬT
        </h2>
        <a href="#form-bao-gia" class="text-xs font-bold text-brandBlue hover:text-brandRed pr-3 whitespace-nowrap">
          Xem thêm <i class="fa-solid fa-angle-right"></i>
        </a>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
        <!-- Bài viết 1 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-32 sm:h-40 bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO=w500" data-drive-id="1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO" alt="Cho thuê máy may công nghiệp" class="w-full h-full object-contain bg-white p-2 drive-img" />
            <div class="absolute top-2 left-2 bg-brandBlue text-white text-[10px] font-bold px-2 py-1 rounded text-center leading-tight">
              <div>14</div>
              <div>Th11</div>
            </div>
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue leading-snug mb-1.5">
                Dịch vụ cho thuê máy may công nghiệp tại Đà Nẵng & Miền Trung giá tốt
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                Công ty TNHH Thương Mại Và Dịch Vụ Máy May Miền Trung cung cấp giải pháp cho thuê máy 1 kim, vắt sổ, trần đè, lập trình giúp xưởng may tối ưu chi phí đầu tư.
              </p>
            </div>
            <a href="#form-bao-gia" class="mt-2 inline-block text-[11px] font-bold text-brandRed hover:underline">
              Nhận báo giá thuê máy &rarr;
            </a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-32 sm:h-40 bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY=w500" data-drive-id="1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY" alt="Thu mua máy may cũ Miền Trung" class="w-full h-full object-contain bg-white p-2 drive-img" />
            <div class="absolute top-2 left-2 bg-brandBlue text-white text-[10px] font-bold px-2 py-1 rounded text-center leading-tight">
              <div>10</div>
              <div>Th11</div>
            </div>
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue leading-snug mb-1.5">
                Thu mua máy may cũ Miền Trung – Thanh lý máy móc nhà xưởng giá cao
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                Chuyên thu mua máy may công nghiệp cũ Jack, Juki, Brother, Siruba, Pegasus tận nơi tại Đà Nẵng, Quảng Nam và các tỉnh Miền Trung, thanh toán nhanh gọn 1 lần.
              </p>
            </div>
            <a href="#form-bao-gia" class="mt-2 inline-block text-[11px] font-bold text-brandRed hover:underline">
              Liên hệ thẩm định giá &rarr;
            </a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-32 sm:h-40 bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ=w500" data-drive-id="1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ" alt="Máy may Jack và Juki chính hãng" class="w-full h-full object-contain bg-white p-2 drive-img" />
            <div class="absolute top-2 left-2 bg-brandBlue text-white text-[10px] font-bold px-2 py-1 rounded text-center leading-tight">
              <div>05</div>
              <div>Th11</div>
            </div>
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue leading-snug mb-1.5">
                Máy may Jack & Juki liền trục – Giải pháp tiết kiệm 70% điện năng cho xưởng may
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                Các dòng máy 1 kim điện tử, máy vắt sổ liền trục thế hệ mới vận hành êm ái, cắt chỉ tự động chính xác, nâng cao năng suất cho tổ hợp may mặc xuất khẩu.
              </p>
            </div>
            <a href="#sec-jack" class="mt-2 inline-block text-[11px] font-bold text-brandRed hover:underline">
              Xem danh mục máy &rarr;
            </a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-32 sm:h-40 bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW=w500" data-drive-id="12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW" alt="Máy may cũ Đà Nẵng" class="w-full h-full object-contain bg-white p-2 drive-img" />
            <div class="absolute top-2 left-2 bg-brandBlue text-white text-[10px] font-bold px-2 py-1 rounded text-center leading-tight">
              <div>01</div>
              <div>Th11</div>
            </div>
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue leading-snug mb-1.5">
                Máy may cũ chính hãng – Giải pháp tiết kiệm chi phí tại Đà Nẵng
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-3">
                Tất cả máy may cũ tại Máy May Miền Trung đều được đội ngũ kỹ thuật kiểm định kỹ lưỡng, căn chỉnh đường chỉ chuẩn xác và kèm chế độ bảo hành chu đáo tận nơi.
              </p>
            </div>
            <a href="#sec-may-cu" class="mt-2 inline-block text-[11px] font-bold text-brandRed hover:underline">
              Xem kho máy may cũ &rarr;
            </a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       10. DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI
       ===================================================================== -->
  <section class="py-4">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-4 shadow-sm">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3">
          <h2 class="font-heading font-extrabold text-brandBlue text-xs sm:text-sm md:text-base uppercase flex items-center gap-2">
            <i class="fa-solid fa-handshake-simple text-brandRed"></i> ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG
          </h2>
          <span class="text-[11px] text-slate-500 hidden sm:inline">Cam kết linh kiện & máy móc chính hãng 100%</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
          <a href="#sec-jack" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#005bac] tracking-wider">JACK</span>
            <span class="text-[9.5px] text-slate-500">Sewing Machine</span>
          </a>
          <a href="#sec-juki" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#004098] tracking-wider">JUKI</span>
            <span class="text-[9.5px] text-slate-500">Japan Technology</span>
          </a>
          <a href="#sec-pegasus" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#c8102e] tracking-wider">PEGASUS</span>
            <span class="text-[9.5px] text-slate-500">Overlock Japan</span>
          </a>
          <a href="#sec-siruba" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#007a33] tracking-wider">SIRUBA</span>
            <span class="text-[9.5px] text-slate-500">Taiwan Brand</span>
          </a>
          <a href="#sec-brother" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#0d3880] tracking-wider">BROTHER</span>
            <span class="text-[9.5px] text-slate-500">Industrial Sewing</span>
          </a>
          <a href="#sec-hashima" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#b91c1c] tracking-wider">HASHIMA</span>
            <span class="text-[9.5px] text-slate-500">Cutting & Pressing</span>
          </a>
          <a href="#sec-okito" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#1e3a8a] tracking-wider">OKITO</span>
            <span class="text-[9.5px] text-slate-500">High Speed Sewing</span>
          </a>
          <a href="#sec-bruce" class="h-14 rounded border border-slate-200 bg-slate-50 hover:border-brandBlue flex flex-col items-center justify-center p-2 transition">
            <span class="font-heading font-black text-sm text-[#d91e2a] tracking-wider">BRUCE</span>
            <span class="text-[9.5px] text-slate-500">German Tech</span>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       11. ĐƯA GOOGLE MAP VÀ FACEBOOK RA NGOÀI TRANG CHỦ
       ===================================================================== -->
  <section id="lien-he-ban-do" class="py-4">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">

        <!-- CỘT BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-7 bg-white rounded-lg border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="p-3 bg-brandBlue text-white flex flex-wrap items-center justify-between gap-2">
            <div class="font-heading font-bold text-xs sm:text-sm uppercase flex items-center gap-2">
              <i class="fa-solid fa-map-location-dot text-yellow-300"></i> BẢN ĐỒ VỊ TRÍ CÔNG TY TRÊN GOOGLE MAPS
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&query=Th%C3%B4n+An+Th%C3%A0nh+3,+X%C3%A3+Th%C4%83ng+%C4%90i%E1%BB%81n,+TP+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="bg-yellow-400 hover:bg-yellow-300 text-slate-900 text-[11px] font-extrabold px-2.5 py-1 rounded transition"
            >
              <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Maps lớn
            </a>
          </div>
          <div class="p-3 bg-slate-50 border-b border-slate-200 text-xs text-slate-700">
            <strong>Địa chỉ trụ sở & kho máy:</strong> Thửa đất số 295, Tờ bản đồ số 10, Tổ 4, Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng — <strong>SĐT:</strong> <span class="text-brandRed font-bold">0877.441.859 - 0966.044.002</span>
          </div>
          <div class="w-full h-64 sm:h-72 bg-slate-100 relative">
            <iframe
              title="Bản đồ Google Maps Công ty TNHH Thương Mại Và Dịch Vụ Máy May Miền Trung"
              src="https://maps.google.com/maps?q=Th%C4%83ng%20%C4%90i%E1%BB%81n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=13&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- CỘT KẾT NỐI FACEBOOK NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-5 bg-white rounded-lg border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between">
          <div>
            <div class="p-3 bg-[#1877F2] text-white flex items-center justify-between">
              <div class="font-heading font-bold text-xs sm:text-sm uppercase flex items-center gap-2">
                <i class="fa-brands fa-facebook text-base"></i> KẾT NỐI FACEBOOK CHÍNH THỨC
              </div>
              <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded font-semibold">Fanpage</span>
            </div>

            <div class="p-4">
              <!-- Card hiển thị trang Facebook ngoài trang chủ -->
              <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50 mb-3">
                <div class="bg-gradient-to-r from-[#0b3b8c] to-[#1877F2] p-3.5 text-white flex items-center gap-3">
                  <div class="w-12 h-12 rounded-full bg-white text-brandBlue flex items-center justify-center font-heading font-black text-base shrink-0 shadow">
                    MM
                  </div>
                  <div class="min-w-0">
                    <a
                      href="https://www.facebook.com/profile.php?id=61578846674609"
                      target="_blank"
                      rel="noopener noreferrer"
                      class="font-bold text-sm text-white hover:underline block truncate"
                    >
                      MÁY MAY MIỀN TRUNG
                    </a>
                    <div class="text-[11px] text-blue-100">
                      CÔNG TY TNHH TM & DV MÁY MAY MIỀN TRUNG
                    </div>
                  </div>
                </div>
                <div class="p-3.5 text-xs text-slate-700 space-y-2">
                  <p class="leading-relaxed">
                    Cập nhật hình ảnh xuất kho máy may thực tế mỗi ngày, video test máy 1 kim, máy vắt sổ, máy lập trình và báo giá ưu đãi trực tiếp trên Facebook.
                  </p>
                  <div class="flex flex-wrap gap-2 pt-1">
                    <a
                      href="https://www.facebook.com/profile.php?id=61578846674609"
                      target="_blank"
                      rel="noopener noreferrer"
                      class="inline-flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs px-3.5 py-2 rounded transition"
                    >
                      <i class="fa-brands fa-facebook-f"></i> Truy cập Facebook
                    </a>
                    <a
                      href="https://www.facebook.com/profile.php?id=61578846674609"
                      target="_blank"
                      rel="noopener noreferrer"
                      class="inline-flex items-center gap-1.5 bg-slate-200 hover:bg-slate-300 text-slate-800 font-bold text-xs px-3.5 py-2 rounded transition"
                    >
                      <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i> Nhắn tin Facebook
                    </a>
                  </div>
                </div>
              </div>

              <!-- Nhúng khung Facebook Page Plugin chuẩn -->
              <div class="w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center py-2">
                <iframe
                  title="Facebook Máy May Miền Trung"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61578846674609&tabs&width=340&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  width="340"
                  height="130"
                  style="border:none;overflow:hidden;max-width:100%;"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>
          </div>

          <div class="px-4 py-2.5 bg-slate-50 border-t border-slate-200 text-[11px] text-slate-600 flex items-center justify-between">
            <span>Link Facebook chính thức:</span>
            <a href="https://www.facebook.com/profile.php?id=61578846674609" target="_blank" rel="noopener noreferrer" class="font-bold text-[#1877F2] hover:underline truncate max-w-[200px]">
              facebook.com/profile.php?id=61578846674609
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       12. FOOTER CHUẨN MẪU MAYMAYDANANG.COM (ĐẦY ĐỦ THÔNG TIN CÔNG TY & THỐNG KÊ)
       ===================================================================== -->
  <footer class="bg-brandBlueDark text-white mt-6 border-t-4 border-brandRed">
    <div class="flatsome-container py-8">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6">

        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded bg-white text-brandBlue flex items-center justify-center font-heading font-black text-sm shrink-0">
              MM
            </div>
            <div>
              <h3 class="font-heading font-extrabold text-sm sm:text-base text-yellow-300 uppercase">
                CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG
              </h3>
              <div class="text-xs text-blue-200">Website: maymaymientrung.com | MST: 4001325801</div>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm text-blue-100 pt-1">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brandRed mt-1 shrink-0"></i>
              <span><strong>Địa chỉ:</strong> Thửa đất số 295, Tờ bản đồ số 10, Tổ 4, Thôn An Thành 3, Xã Thăng Điền, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone-volume text-yellow-300 shrink-0"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0877441859" class="text-yellow-300 font-bold hover:underline">0877.441.859</a> - <a href="tel:0966044002" class="text-yellow-300 font-bold hover:underline">0966.044.002</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-blue-300 shrink-0"></i>
              <span><strong>Website:</strong> <a href="https://maymaymientrung.com" class="hover:underline">maymaymientrung.com</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-blue-300 shrink-0"></i>
              <span><strong>Facebook:</strong> <a href="https://www.facebook.com/profile.php?id=61578846674609" target="_blank" rel="noopener noreferrer" class="hover:underline">Máy May Miền Trung</a></span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm chính -->
        <div class="lg:col-span-4">
          <h4 class="font-heading font-bold text-sm uppercase text-white border-b border-blue-800 pb-2 mb-3">
            DANH MỤC SẢN PHẨM
          </h4>
          <div class="grid grid-cols-2 gap-1.5 text-xs text-blue-100">
            <a href="#sec-jack" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Jack</a>
            <a href="#sec-juki" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Juki</a>
            <a href="#sec-pegasus" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Pegasus</a>
            <a href="#sec-siruba" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Siruba</a>
            <a href="#sec-brother" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Brother</a>
            <a href="#sec-hashima" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Thiết bị Hashima</a>
            <a href="#sec-okito" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Okito</a>
            <a href="#sec-bruce" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may Bruce</a>
            <a href="#sec-may-cu" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Máy may cũ</a>
            <a href="#sec-phu-tung" class="hover:text-yellow-300 py-0.5"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Thiết bị phụ tùng</a>
          </div>
        </div>

        <!-- Cột 3: Thống kê truy cập giống mẫu maymaydanang.com -->
        <div class="lg:col-span-3">
          <h4 class="font-heading font-bold text-sm uppercase text-white border-b border-blue-800 pb-2 mb-3">
            THỐNG KÊ TRUY CẬP
          </h4>
          <div class="flex items-center gap-1 mb-3">
            <span class="bg-slate-900 border border-blue-700 text-yellow-300 font-mono font-bold text-sm px-2 py-1 rounded">0</span>
            <span class="bg-slate-900 border border-blue-700 text-yellow-300 font-mono font-bold text-sm px-2 py-1 rounded">5</span>
            <span class="bg-slate-900 border border-blue-700 text-yellow-300 font-mono font-bold text-sm px-2 py-1 rounded">8</span>
            <span class="bg-slate-900 border border-blue-700 text-yellow-300 font-mono font-bold text-sm px-2 py-1 rounded">6</span>
            <span class="bg-slate-900 border border-blue-700 text-yellow-300 font-mono font-bold text-sm px-2 py-1 rounded">2</span>
            <span class="bg-slate-900 border border-blue-700 text-yellow-300 font-mono font-bold text-sm px-2 py-1 rounded">9</span>
          </div>
          <ul class="space-y-1 text-xs text-blue-100">
            <li>Hôm nay: <strong>186</strong></li>
            <li>Tháng này: <strong>5.420</strong></li>
            <li>Tổng truy cập: <strong>58.629</strong></li>
            <li>Đang trực tuyến: <strong class="text-emerald-400">4</strong></li>
          </ul>
        </div>

      </div>
    </div>

    <div class="bg-[#041a42] py-3 text-center text-xs text-blue-200 border-t border-blue-900/60 px-3">
      Copyright 2026 © <strong>CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ MÁY MAY MIỀN TRUNG</strong> | Website: <strong>maymaymientrung.com</strong>
    </div>
  </footer>

  <!-- =====================================================================
       13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH PC & MOBILE
       ===================================================================== -->
  <div class="fixed bottom-3 left-3 z-40 flex flex-col gap-2">
    <!-- Nút Gọi Hotline 1 -->
    <a
      href="tel:0877441859"
      class="pulse-contact inline-flex items-center gap-2 bg-brandRed hover:bg-brandRedDark text-white font-bold text-xs px-3 py-2 rounded-full shadow-lg border border-white/30 transition"
      title="Gọi ngay 0877.441.859"
    >
      <span class="w-6 h-6 rounded-full bg-white text-brandRed flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="pr-1">0877.441.859</span>
    </a>

    <!-- Nút Gọi Hotline 2 -->
    <a
      href="tel:0966044002"
      class="inline-flex items-center gap-2 bg-brandBlue hover:bg-brandBlueDark text-white font-bold text-xs px-3 py-2 rounded-full shadow-lg border border-white/30 transition"
      title="Gọi ngay 0966.044.002"
    >
      <span class="w-6 h-6 rounded-full bg-white text-brandBlue flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="pr-1">0966.044.002</span>
    </a>
  </div>

  <!-- Cụm nút Zalo, Facebook, Chỉ đường bên góc phải -->
  <div class="fixed bottom-3 right-3 z-40 flex flex-col items-end gap-2">
    <a
      href="https://zalo.me/0877441859"
      target="_blank"
      rel="noopener noreferrer"
      class="inline-flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white font-bold text-xs px-3 py-2 rounded-full shadow-lg border border-white/40 transition"
      title="Chat Zalo 0877.441.859"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center shrink-0">
        Zalo
      </span>
      <span class="hidden sm:inline pr-1">Chat Zalo</span>
    </a>

    <a
      href="https://www.facebook.com/profile.php?id=61578846674609"
      target="_blank"
      rel="noopener noreferrer"
      class="inline-flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white font-bold text-xs px-3 py-2 rounded-full shadow-lg border border-white/40 transition"
      title="Facebook Máy May Miền Trung"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="hidden sm:inline pr-1">Facebook</span>
    </a>

    <a
      href="#lien-he-ban-do"
      class="inline-flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-xs px-3 py-2 rounded-full shadow-lg border border-white/40 transition"
      title="Xem bản đồ"
    >
      <span class="w-6 h-6 rounded-full bg-white text-emerald-600 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-location-dot text-xs"></i>
      </span>
      <span class="hidden sm:inline pr-1">Chỉ đường</span>
    </a>
  </div>

  <!-- =====================================================================
       14. MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT MUA NHANH
       ===================================================================== -->
  <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="bg-brandBlue text-white px-4 py-3 flex items-center justify-between">
        <h3 id="modalTitle" class="font-heading font-bold text-xs sm:text-sm uppercase pr-2">Chi tiết sản phẩm</h3>
        <button id="closeModalBtn" type="button" class="w-7 h-7 rounded bg-white/20 hover:bg-brandRed flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4">
        <div class="grid grid-cols-1 sm:grid-cols-12 gap-4 items-center">
          <div class="sm:col-span-5 bg-slate-50 border border-slate-200 rounded-lg p-2 flex items-center justify-center">
            <img id="modalImg" src="" alt="Ảnh sản phẩm" class="w-full h-40 object-contain" />
          </div>
          <div class="sm:col-span-7 space-y-2">
            <div id="modalCat" class="text-[11px] font-bold text-brandBlue uppercase"></div>
            <div id="modalName" class="text-sm font-bold text-slate-900 leading-snug"></div>
            <div class="flex items-center gap-2">
              <del id="modalOldPrice" class="text-xs text-slate-400"></del>
              <span id="modalPrice" class="text-base font-extrabold text-brandRed"></span>
              <span id="modalDiscount" class="bg-brandRed text-white text-[11px] font-bold px-2 py-0.5 rounded"></span>
            </div>
            <p class="text-xs text-slate-600 leading-relaxed">
              Sản phẩm phân phối bởi <strong>Công Ty TNHH Thương Mại Và Dịch Vụ Máy May Miền Trung</strong>. Bảo hành uy tín, hỗ trợ giao lắp tận nơi tại Đà Nẵng & Miền Trung.
            </p>
            <div class="pt-2 flex flex-wrap gap-2">
              <a href="tel:0877441859" class="bg-brandRed hover:bg-brandRedDark text-white font-bold text-xs px-3.5 py-2 rounded">
                <i class="fa-solid fa-phone mr-1"></i> Gọi 0877.441.859
              </a>
              <a href="https://zalo.me/0877441859" target="_blank" rel="noopener noreferrer" class="bg-brandBlue hover:bg-brandBlueDark text-white font-bold text-xs px-3.5 py-2 rounded">
                <i class="fa-solid fa-comment-dots mr-1"></i> Báo giá qua Zalo
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       15. JAVASCRIPT XỬ LÝ DỮ LIỆU 11 ẢNH GOOGLE DRIVE, DANH MỤC & TƯƠNG TÁC
       ===================================================================== -->
  <script>
    // Danh sách 11 ID ảnh sản phẩm thực tế từ Google Drive của khách hàng cung cấp
    const DRIVE_IDS = [
      '1r5Z1yrN-z3_khXkPP8tUu7RcOBcPiCGO', // Ảnh 1
      '1tCMDkpfyiYNSQfkqONWBA2edUaNymCwY', // Ảnh 2
      '1W_tEFy-2aMdThDXdlicqdCcmthF9Q1TJ', // Ảnh 3
      '12yu-AKvMeLhqy9tqsZz7IbvJfGJYyInW', // Ảnh 4
      '1ddql_KSs3fC_wu28mFNPMR6lOUM41X_k', // Ảnh 5
      '1TDWHfvK5GYBGOdCusjqR2O-6qiN0LNna', // Ảnh 6
      '1vmUreyihYBiqwx0H5LLWrMpWjgGmGWCw', // Ảnh 7
      '1M_FcEsuAbMjQbxQVskjuOkOwO7oQTxCu', // Ảnh 8
      '1VLEEdeu3TaN4RNe93S5NoFJnnbYqstrH', // Ảnh 9
      '1t93PopaJwLUXH-fgN4KGTKnQKE-eeqjs', // Ảnh 10
      '1A_QsEgJ3TKkOohuE1M8fWji6-av8tLS9'  // Ảnh 11
    ];

    function getDriveImgUrl(fileId) {
      return `https://lh3.googleusercontent.com/d/${fileId}=w700`;
    }

    // Dữ liệu toàn bộ các danh mục sản phẩm lấy từ web mẫu maymaydanang.com
    // Kết hợp toàn bộ 11 ảnh thực tế từ Google Drive vào đúng danh mục & sản phẩm
    const PRODUCT_SECTIONS = [
      {
        id: 'sec-thuc-te',
        title: 'SẢN PHẨM THỰC TẾ TẠI KHO MÁY MAY MIỀN TRUNG',
        sublinks: ['Máy 1 Kim Điện Tử', 'Máy Vắt Sổ', 'Máy Trần Đè', 'Máy Khuy Bọ', 'Máy May Cũ'],
        products: [
          {
            name: 'Máy may 1 kim điện tử liền trục cắt chỉ tự động Jack A4B / A4F',
            category: 'MÁY MAY JACK',
            driveId: DRIVE_IDS[0],
            oldPrice: '9.500.000 ₫',
            price: '7.800.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy may 1 kim điện tử Juki DDL-9000C / DDL-8000A chính hãng',
            category: 'MÁY MAY JUKI',
            driveId: DRIVE_IDS[1],
            oldPrice: '12.500.000 ₫',
            price: '10.200.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy vắt sổ công nghiệp tốc độ cao Pegasus EX5200 / GX5200 Series',
            category: 'MÁY MAY PEGASUS',
            driveId: DRIVE_IDS[2],
            oldPrice: '14.000.000 ₫',
            price: '11.500.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy một kim tự động cắt chỉ liền trục Siruba DL7200C',
            category: 'MÁY MAY SIRUBA',
            driveId: DRIVE_IDS[3],
            oldPrice: '9.200.000 ₫',
            price: '7.500.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy 1 kim điện tử Brother S-7250A / S-7300A truyền động trực tiếp',
            category: 'MÁY MAY BROTHER',
            driveId: DRIVE_IDS[4],
            oldPrice: '11.000.000 ₫',
            price: '8.900.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy đính cúc, di bọ điện tử tốc độ cao Jack JK-T1900G / 1903G',
            category: 'MÁY MAY JACK',
            driveId: DRIVE_IDS[5],
            oldPrice: '24.000.000 ₫',
            price: '19.800.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy thùa khuy đầu bằng điện tử liền trục Juki / Jack JK-9820',
            category: 'MÁY CHUYÊN DÙNG',
            driveId: DRIVE_IDS[6],
            oldPrice: '25.000.000 ₫',
            price: '21.500.000 ₫',
            discount: '-14%'
          },
          {
            name: 'Máy trần đè / Kansai cuốn sườn 2 kim 3 kim Jack JK-T9280D',
            category: 'MÁY TRẦN ĐÈ',
            driveId: DRIVE_IDS[7],
            oldPrice: '13.500.000 ₫',
            price: '10.800.000 ₫',
            discount: '-20%'
          },
          {
            name: 'Máy cắt vải đứng công nghiệp Hashima KM-SV / Máy ép nhiệt',
            category: 'MÁY CÔNG NGHIỆP HÓA',
            driveId: DRIVE_IDS[8],
            oldPrice: '8.500.000 ₫',
            price: '6.800.000 ₫',
            discount: '-20%'
          },
          {
            name: 'Máy 1 kim điện tử liền trục Okito TK-M5-D4 / TK-8700',
            category: 'MÁY MAY OKITO',
            driveId: DRIVE_IDS[9],
            oldPrice: '7.800.000 ₫',
            price: '6.200.000 ₫',
            discount: '-21%'
          },
          {
            name: 'Máy vắt sổ công nghiệp 4 chỉ 5 chỉ liền trục Bruce X5S / B5000',
            category: 'MÁY MAY BRUCE',
            driveId: DRIVE_IDS[10],
            oldPrice: '10.500.000 ₫',
            price: '8.500.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy may 1 kim Juki chính hãng đã qua sử dụng (Độ mới 95%)',
            category: 'MÁY MAY CŨ',
            driveId: DRIVE_IDS[0],
            oldPrice: '6.000.000 ₫',
            price: '4.000.000 ₫',
            discount: '-33%'
          }
        ]
      },
      {
        id: 'sec-jack',
        title: 'MÁY MAY JACK',
        sublinks: ['Máy May Jack', 'Máy Vắt Sổ Jack', 'Máy Trần Đè Jack', 'Máy Chuyên Dùng Jack', 'Motor Tiết Kiệm Điện'],
        products: [
          {
            name: 'Máy Đính Cúc, Di Bọ Điện Tử Tốc Độ Cao 1900G / 1903G / 1906G',
            category: 'MÁY MAY JACK',
            driveId: DRIVE_IDS[5],
            oldPrice: '24.500.000 ₫',
            price: '20.500.000 ₫',
            discount: '-16%'
          },
          {
            name: 'Máy may 12 kim trần chun Jack JK-8009VC chính hãng',
            category: 'MÁY MAY JACK',
            driveId: DRIVE_IDS[7],
            oldPrice: '18.500.000 ₫',
            price: '15.200.000 ₫',
            discount: '-18%'
          },
          {
            name: 'Máy Thùa Khuy Đầu Tròn Jack JK-9820 điện tử tốc độ cao',
            category: 'MÁY MAY JACK',
            driveId: DRIVE_IDS[6],
            oldPrice: '42.000.000 ₫',
            price: '36.500.000 ₫',
            discount: '-13%'
          },
          {
            name: 'Máy cuốn sườn 2 kim 3 kim Jack JK-T9270D / JK-T9280D',
            category: 'MÁY MAY JACK',
            driveId: DRIVE_IDS[0],
            oldPrice: '21.000.000 ₫',
            price: '17.500.000 ₫',
            discount: '-17%'
          }
        ]
      },
      {
        id: 'sec-juki',
        title: 'MÁY MAY JUKI',
        sublinks: ['DDL-9000C Series', 'DDL-8000A Series', 'DDL-7000A Series', 'Máy Vắt Sổ Juki'],
        products: [
          {
            name: 'Máy 1 kim điện tử Juki DDL-9000CF Series [Premium Digital]',
            category: 'MÁY MAY JUKI',
            driveId: DRIVE_IDS[1],
            oldPrice: '16.500.000 ₫',
            price: '13.800.000 ₫',
            discount: '-16%'
          },
          {
            name: 'Máy 1 kim điện tử Juki DDL-8000A Series liền trục cắt chỉ tự động',
            category: 'MÁY MAY JUKI',
            driveId: DRIVE_IDS[3],
            oldPrice: '11.500.000 ₫',
            price: '9.500.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Máy 1 kim điện tử Juki DDL-7000A-7 truyền động trực tiếp',
            category: 'MÁY MAY JUKI',
            driveId: DRIVE_IDS[4],
            oldPrice: '9.800.000 ₫',
            price: '8.100.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Máy may thùa khuy đầu bằng Juki LBH-1790S chính hãng',
            category: 'MÁY MAY JUKI',
            driveId: DRIVE_IDS[6],
            oldPrice: '50.000.000 ₫',
            price: '40.000.000 ₫',
            discount: '-20%'
          }
        ]
      },
      {
        id: 'sec-pegasus',
        title: 'MÁY MAY PEGASUS',
        sublinks: ['Máy chuyên dụng', 'Máy trần đè Pegasus', 'Máy tự động Pegasus', 'Máy vắt sổ Pegasus'],
        products: [
          {
            name: 'Máy vắt sổ Pegasus EX5200 Series (Overedgers tốc độ cao)',
            category: 'MÁY MAY PEGASUS',
            driveId: DRIVE_IDS[2],
            oldPrice: '15.500.000 ₫',
            price: '12.800.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Máy vắt sổ Pegasus GX5200 Series (Đầu máy khô – tốc độ cao – an toàn)',
            category: 'MÁY MAY PEGASUS',
            driveId: DRIVE_IDS[10],
            oldPrice: '14.200.000 ₫',
            price: '11.900.000 ₫',
            discount: '-16%'
          },
          {
            name: 'Máy vắt sổ Pegasus M900 Series (Trang bị động cơ liền trục)',
            category: 'MÁY MAY PEGASUS',
            driveId: DRIVE_IDS[7],
            oldPrice: '13.000.000 ₫',
            price: '10.500.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy trần đè viền cổ áo Pegasus W500P / W600P chính hãng',
            category: 'MÁY MAY PEGASUS',
            driveId: DRIVE_IDS[8],
            oldPrice: '16.000.000 ₫',
            price: '13.200.000 ₫',
            discount: '-18%'
          }
        ]
      },
      {
        id: 'sec-siruba',
        title: 'MÁY MAY SIRUBA',
        sublinks: ['Máy một kim Siruba', 'Máy hai kim Siruba', 'Máy khuy bọ nút', 'Máy trần đè Siruba', 'Máy vắt sổ Siruba'],
        products: [
          {
            name: 'DL7200C Máy một kim tự động cắt chỉ dạng liền trục SIRUBA',
            category: 'MÁY MAY SIRUBA',
            driveId: DRIVE_IDS[3],
            oldPrice: '9.500.000 ₫',
            price: '7.800.000 ₫',
            discount: '-18%'
          },
          {
            name: 'T8200 / DT8200 Máy may 2 kim cắt chỉ tự động liền trục SIRUBA',
            category: 'MÁY MAY SIRUBA',
            driveId: DRIVE_IDS[4],
            oldPrice: '18.500.000 ₫',
            price: '15.200.000 ₫',
            discount: '-18%'
          },
          {
            name: 'BT430 / BT530 / BT630 Máy đính cúc đính bọ điện tử SIRUBA',
            category: 'MÁY MAY SIRUBA',
            driveId: DRIVE_IDS[5],
            oldPrice: '23.000.000 ₫',
            price: '19.000.000 ₫',
            discount: '-17%'
          },
          {
            name: 'LBHS-1790 Máy thùa khuy đầu bằng điện tử SIRUBA',
            category: 'MÁY MAY SIRUBA',
            driveId: DRIVE_IDS[6],
            oldPrice: '32.000.000 ₫',
            price: '26.500.000 ₫',
            discount: '-17%'
          }
        ]
      },
      {
        id: 'sec-brother',
        title: 'MÁY MAY BROTHER',
        sublinks: ['Máy một kim', 'Máy hai kim', 'Máy cuốn sườn', 'Máy đính bọ', 'Máy lập trình điện tử'],
        products: [
          {
            name: 'Máy 1 kim điện tử Brother S-7250A / S-7300A cắt chỉ tự động',
            category: 'MÁY MAY BROTHER',
            driveId: DRIVE_IDS[4],
            oldPrice: '11.500.000 ₫',
            price: '9.200.000 ₫',
            discount: '-20%'
          },
          {
            name: 'S-7100A Máy 1 kim điện tử Brother truyền động trực tiếp',
            category: 'MÁY MAY BROTHER',
            driveId: DRIVE_IDS[1],
            oldPrice: '10.200.000 ₫',
            price: '8.400.000 ₫',
            discount: '-18%'
          },
          {
            name: 'NEXIO T-8422D Máy may 2 kim cố định truyền động trực tiếp Brother',
            category: 'MÁY MAY BROTHER',
            driveId: DRIVE_IDS[0],
            oldPrice: '24.000.000 ₫',
            price: '19.500.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy cuốn sườn Brother DA-9270 / DA-9280 chuyên may sơ mi, thun',
            category: 'MÁY MAY BROTHER',
            driveId: DRIVE_IDS[7],
            oldPrice: '19.000.000 ₫',
            price: '15.500.000 ₫',
            discount: '-18%'
          }
        ]
      },
      {
        id: 'sec-hashima',
        title: 'MÁY CÔNG NGHIỆP HÓA HASHIMA',
        sublinks: ['Máy cắt vải Hashima', 'Máy cắt vòng Hashima', 'Máy dò kim Hashima', 'Máy in sơ đồ', 'Máy cắt rập'],
        products: [
          {
            name: 'Máy cắt vải đứng Hashima Series KM-SV công suất cao',
            category: 'HASHIMA',
            driveId: DRIVE_IDS[8],
            oldPrice: '8.200.000 ₫',
            price: '6.800.000 ₫',
            discount: '-17%'
          },
          {
            name: 'Máy in sơ đồ & Máy cắt rập ngành may công nghiệp tốc độ cao',
            category: 'HASHIMA',
            driveId: DRIVE_IDS[9],
            oldPrice: '35.000.000 ₫',
            price: '31.850.000 ₫',
            discount: '-9%'
          },
          {
            name: 'Máy dò kim tự động Hashima HN-2880C / HN-2790G (2 cảm biến)',
            category: 'HASHIMA',
            driveId: DRIVE_IDS[10],
            oldPrice: '28.000.000 ₫',
            price: '23.500.000 ₫',
            discount: '-16%'
          },
          {
            name: 'Máy ép nhiệt 2 mâm khổ 40x60 & Máy ép mếch Hashima',
            category: 'HASHIMA',
            driveId: DRIVE_IDS[2],
            oldPrice: '12.000.000 ₫',
            price: '9.600.000 ₫',
            discount: '-20%'
          }
        ]
      },
      {
        id: 'sec-okito',
        title: 'MÁY MAY OKITO & BRUCE',
        sublinks: ['Máy May Okito', 'Máy Vắt Sổ Okito', 'Máy 1 Kim BRUCE', 'Máy Vắt Sổ BRUCE'],
        products: [
          {
            name: 'Máy 1 Kim Điện Tử Liền Trục Okito TK-M5-D4 / TK-8700',
            category: 'MÁY MAY OKITO',
            driveId: DRIVE_IDS[9],
            oldPrice: '7.800.000 ₫',
            price: '6.200.000 ₫',
            discount: '-21%'
          },
          {
            name: 'Máy 1 Kim Xén Điện Tử Okito TK-5200-D3 / TK-9990B-D4',
            category: 'MÁY MAY OKITO',
            driveId: DRIVE_IDS[10],
            oldPrice: '8.900.000 ₫',
            price: '7.200.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy may công nghiệp 1 kim điện tử BRUCE R4000-B-DQ',
            category: 'MÁY MAY BRUCE',
            driveId: DRIVE_IDS[0],
            oldPrice: '8.500.000 ₫',
            price: '6.900.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy vắt sổ công nghiệp liền trục BRUCE X5S-4-M03/333',
            category: 'MÁY MAY BRUCE',
            driveId: DRIVE_IDS[2],
            oldPrice: '10.200.000 ₫',
            price: '8.400.000 ₫',
            discount: '-18%'
          }
        ]
      },
      {
        id: 'sec-may-cu',
        title: 'MÁY MAY CŨ & THIẾT BỊ PHỤ TÙNG',
        sublinks: ['Jack Cũ', 'Juki Cũ', 'Siruba Cũ', 'Brother Cũ', 'Ghế Ngồi May', 'Bàn Hút - Nồi Hơi'],
        products: [
          {
            name: 'Máy may 1 kim Juki chính hãng (Máy lướt đẹp 95%)',
            category: 'MÁY MAY CŨ',
            driveId: DRIVE_IDS[1],
            oldPrice: '8.000.000 ₫',
            price: '6.500.000 ₫',
            discount: '-19%'
          },
          {
            name: 'Máy may thùa khuy đầu bằng Jack liền trục (Đã qua sử dụng)',
            category: 'MÁY MAY CŨ',
            driveId: DRIVE_IDS[6],
            oldPrice: '25.000.000 ₫',
            price: '23.000.000 ₫',
            discount: '-8%'
          },
          {
            name: 'Máy vắt sổ Jin / Pegasus 5 chỉ công nghiệp (Máy đẹp bảo hành 12 tháng)',
            category: 'MÁY MAY CŨ',
            driveId: DRIVE_IDS[3],
            oldPrice: '8.000.000 ₫',
            price: '7.000.000 ₫',
            discount: '-13%'
          },
          {
            name: 'Bàn hút chân không, Nồi hơi công nghiệp & Ghế ngồi may xưởng',
            category: 'THIẾT BỊ PHỤ TÙNG',
            driveId: DRIVE_IDS[8],
            oldPrice: '8.000.000 ₫',
            price: '6.000.000 ₫',
            discount: '-25%'
          }
        ]
      }
    ];

    // Gắn neo #sec-bruce và #sec-phu-tung vào đúng section tương ứng
    function renderProductSections(filterText = '') {
      const container = document.getElementById('productSectionsContainer');
      const keyword = filterText.trim().toLowerCase();
      let html = '';

      PRODUCT_SECTIONS.forEach((sec) => {
        const filteredProducts = sec.products.filter((p) => {
          if (!keyword) return true;
          return (
            p.name.toLowerCase().includes(keyword) ||
            p.category.toLowerCase().includes(keyword) ||
            sec.title.toLowerCase().includes(keyword)
          );
        });

        if (filteredProducts.length === 0) return;

        // Thêm anchor phụ cho sec-bruce và sec-phu-tung để menu nhảy chính xác
        const extraAnchor =
          sec.id === 'sec-okito'
            ? '<div id="sec-bruce"></div>'
            : sec.id === 'sec-may-cu'
            ? '<div id="sec-phu-tung"></div>'
            : '';

        html += `
          <section id="${sec.id}" class="py-2">
            ${extraAnchor}
            <div class="flatsome-container">
              <!-- Tiêu đề danh mục chuẩn Flatsome -->
              <div class="flatsome-section-title">
                <h2 class="flatsome-section-heading">
                  <i class="fa-solid fa-Microchip text-yellow-300 text-xs"></i>
                  <span>${sec.title}</span>
                </h2>
                <div class="hidden md:flex items-center gap-3 pr-3 overflow-x-auto">
                  ${sec.sublinks
                    .map(
                      (sub) =>
                        `<a href="#form-bao-gia" class="text-xs font-semibold text-slate-600 hover:text-brandBlue whitespace-nowrap">${sub}</a>`
                    )
                    .join('<span class="text-slate-300">|</span>')}
                  <a href="#form-bao-gia" class="text-xs font-bold text-brandRed hover:underline whitespace-nowrap ml-2">
                    Xem thêm <i class="fa-solid fa-angle-right"></i>
                  </a>
                </div>
              </div>

              <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
              <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-3.5">
                ${filteredProducts
                  .map(
                    (prod) => `
                  <div class="flatsome-product-card group">
                    <!-- Góc trên bên trái: Nhãn % giảm giá giống Flatsome (Không để các nhãn dán khác) -->
                    <div class="flatsome-sale-badge">${prod.discount}</div>

                    <!-- Ảnh sản phẩm thực tế từ Google Drive -->
                    <div class="relative w-full h-36 sm:h-44 md:h-48 bg-white p-2.5 border-b border-slate-100 flex items-center justify-center overflow-hidden cursor-pointer"
                         onclick='openProductModal(${JSON.stringify(prod)})'>
                      <img
                        src="${getDriveImgUrl(prod.driveId)}"
                        data-drive-id="${prod.driveId}"
                        alt="${prod.name}"
                        loading="lazy"
                        class="w-full h-full object-contain group-hover:scale-105 transition duration-300 drive-img"
                      />
                    </div>

                    <!-- Thông tin sản phẩm: Tên sản phẩm hiển thị đầy đủ, không bị tràn hay thiếu chữ -->
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                      <div>
                        <div class="text-[10px] font-bold text-slate-400 uppercase mb-0.5">${prod.category}</div>
                        <h3 class="flatsome-product-title cursor-pointer" onclick='openProductModal(${JSON.stringify(prod)})'>
                          ${prod.name}
                        </h3>
                      </div>

                      <!-- Giá gốc gạch ngang & Giá giảm chuẩn Flatsome -->
                      <div class="pt-1.5 border-t border-slate-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                          <del class="text-[11px] text-slate-400">${prod.oldPrice}</del>
                          <ins class="text-xs sm:text-sm font-extrabold text-brandRed no-underline">${prod.price}</ins>
                        </div>
                        <div class="mt-2 flex items-center gap-1.5">
                          <button
                            type="button"
                            onclick='openProductModal(${JSON.stringify(prod)})'
                            class="w-full bg-brandBlue hover:bg-brandRed text-white font-bold text-[11px] sm:text-xs py-1.5 px-2 rounded transition text-center"
                          >
                            Đặt mua / Báo giá
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                `
                  )
                  .join('')}
              </div>
            </div>
          </section>
        `;
      });

      container.innerHTML = html;
      attachDriveImageFallbacks();
    }

    // Tự động chuyển đổi sang link dự phòng của Google Drive nếu trình duyệt chặn một định dạng
    function attachDriveImageFallbacks() {
      const imgs = document.querySelectorAll('img.drive-img');
      imgs.forEach((img) => {
        img.onerror = function () {
          const id = this.getAttribute('data-drive-id');
          const step = parseInt(this.getAttribute('data-fallback-step') || '0', 10);
          if (step === 0 && id) {
            this.setAttribute('data-fallback-step', '1');
            this.src = `https://drive.google.com/thumbnail?id=${id}&sz=w800`;
          } else if (step === 1 && id) {
            this.setAttribute('data-fallback-step', '2');
            this.src = `https://drive.google.com/uc?export=view&id=${id}`;
          } else {
            this.onerror = null;
            this.src = 'https://placehold.co/500x500/0b3b8c/ffffff?text=MAY+MAY+MIEN+TRUNG';
          }
        };
      });
    }

    // Modal xem nhanh sản phẩm
    function openProductModal(prod) {
      const modal = document.getElementById('productModal');
      document.getElementById('modalTitle').textContent = prod.category;
      document.getElementById('modalCat').textContent = prod.category;
      document.getElementById('modalName').textContent = prod.name;
      document.getElementById('modalOldPrice').textContent = prod.oldPrice;
      document.getElementById('modalPrice').textContent = prod.price;
      document.getElementById('modalDiscount').textContent = prod.discount;
      const modalImg = document.getElementById('modalImg');
      modalImg.setAttribute('data-drive-id', prod.driveId);
      modalImg.setAttribute('data-fallback-step', '0');
      modalImg.src = getDriveImgUrl(prod.driveId);
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    document.getElementById('closeModalBtn').addEventListener('click', () => {
      const modal = document.getElementById('productModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    });

    document.getElementById('productModal').addEventListener('click', (e) => {
      if (e.target.id === 'productModal') {
        e.currentTarget.classList.add('hidden');
        e.currentTarget.classList.remove('flex');
      }
    });

    // Xử lý Slider 2 Banner tự trượt chuyên nghiệp
    let currentSlide = 0;
    const slides = document.querySelectorAll('.banner-slide');
    const dots = document.querySelectorAll('.banner-dot');

    function showSlide(index) {
      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((sl, i) => {
        sl.classList.toggle('active', i === currentSlide);
      });
      dots.forEach((dot, i) => {
        if (i === currentSlide) {
          dot.className = 'banner-dot w-6 h-2 rounded-full bg-yellow-400 transition';
        } else {
          dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition';
        }
      });
    }

    document.getElementById('prevBannerBtn').addEventListener('click', () => showSlide(currentSlide - 1));
    document.getElementById('nextBannerBtn').addEventListener('click', () => showSlide(currentSlide + 1));
    dots.forEach((dot) => {
      dot.addEventListener('click', () => {
        showSlide(parseInt(dot.getAttribute('data-slide'), 10));
      });
    });

    setInterval(() => {
      showSlide(currentSlide + 1);
    }, 5500);

    // Xử lý đóng/mở Menu Mobile & Tìm kiếm
    const mobileMenuOverlay = document.getElementById('mobileMenuOverlay');
    document.getElementById('mobileMenuBtn').addEventListener('click', () => {
      mobileMenuOverlay.classList.remove('hidden');
    });
    document.getElementById('closeMobileMenuBtn').addEventListener('click', () => {
      mobileMenuOverlay.classList.add('hidden');
    });
    mobileMenuOverlay.addEventListener('click', (e) => {
      if (e.target === mobileMenuOverlay) mobileMenuOverlay.classList.add('hidden');
    });
    document.querySelectorAll('.mobile-nav-item').forEach((link) => {
      link.addEventListener('click', () => mobileMenuOverlay.classList.add('hidden'));
    });

    document.getElementById('mobileSearchToggle').addEventListener('click', () => {
      document.getElementById('mobileSearchBox').classList.toggle('hidden');
    });

    // Tìm kiếm sản phẩm trực tiếp
    document.getElementById('headerSearchForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const val = document.getElementById('headerSearchInput').value;
      renderProductSections(val);
      document.getElementById('productSectionsContainer').scrollIntoView({ behavior: 'smooth' });
    });

    document.getElementById('mobileSearchForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const val = document.getElementById('mobileSearchInput').value;
      renderProductSections(val);
      document.getElementById('productSectionsContainer').scrollIntoView({ behavior: 'smooth' });
    });

    // Xử lý gửi Form Yêu Cầu Báo Giá ở Trang Chủ
    document.getElementById('quoteRequestForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const cat = document.getElementById('qCategory').value;
      const msgBox = document.getElementById('quoteSuccessMsg');
      msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i> Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${cat}</strong> đã được ghi nhận. Bộ phận kinh doanh <strong>Máy May Miền Trung (0877.441.859 - 0966.044.002)</strong> sẽ liên hệ ngay!`;
      msgBox.classList.remove('hidden');
      e.target.reset();
    });

    // Khởi chạy hiển thị danh sách sản phẩm khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderProductSections();
    });
  </script>
</body>
</html>
