# 🔥 XUYÊN QUÁN 5.0 - HỆ THỐNG THƯ GIÃN ĐA KHÔNG GIAN 
> *Cafe Sáng Tạo • Gội Đầu Thượng Lưu • Massage & Dịch Vụ Đồng Hành VIP (2026 Edition)*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Mobile Ready](https://img.shields.io/badge/Mobile-Acode%20%2F%20Trebedit-blue?style=for-the-badge)

---

## 🌟 Giới Thiệu Dự Án

**Xuyên Quán 5.0** là mã nguồn website độc đáo tích hợp mô hình dịch vụ giải trí đa tầng, mang phong cách **Futuristic Cyberpunk / Neon Glassmorphism** cực kỳ hợp xu hướng năm **2026**. 

Dự án được thiết kế chuyên biệt để chạy mượt mà ngay trên các trình soạn thảo code di động phổ biến như **Acode** hoặc **Trebedit**, giúp bạn dễ dàng tuỳ biến, xem trước (preview) và triển khai chỉ trong vài nốt nhạc.

---

## 🚀 Tính Năng Nổi Bật (Phiên Bản 5.0)

*   💎 **Giao diện Glassmorphism 5.0:** Hiệu ứng kính mờ kết hợp ánh sáng Neon lung linh, tối ưu hóa cho màn hình điện thoại di động.
*   ☕ **Menu Đa Dạng:** Tích hợp gọi món Cafe, dịch vụ Gội đầu thảo dược thư giãn cổ vai gáy.
*   🔥 **Khu Vực VIP (Trai Đi Khách / Nam Thần):** Hồ sơ profile các nhân viên nam phong độ, hiển thị trạng thái online thời gian thực, đánh giá sao ($4.9 - 5.0$).
*   🛒 **Hệ Thống Giỏ Hàng Động:** Tự động ghi nhận dịch vụ khách hàng lựa chọn và tính toán tương tác nhanh gọn.
*   📱 **Tương Thích Tuyệt Đối:** Hoạt động hoàn hảo trên các app code di động (`Acode`, `Trebedit`) hoặc bất kỳ trình duyệt web hiện đại nào.

---

## 🛠️ Hướng Dẫn Cài Đặt Trên Acode / Trebedit

1. Mở ứng dụng **Acode** hoặc **Trebedit** trên điện thoại của bạn.
2. Tạo một file mới hoàn toàn và đặt tên là: `index.html`.
3. Sao chép toàn bộ mã nguồn bên dưới và dán vào file `index.html`.
4. Nhấn nút **Save** (Lưu) và chọn **Preview** để trải nghiệm ngay lập tức!

---

## 💻 Mã Nguồn Trọn Gói (`index.html`)

```html
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xuyên Quán - Cafe, Gội Đầu & Thư Giãn 5.0</title>
    <!-- Tailwind CSS CDN -->
    <script src="[https://cdn.tailwindcss.com](https://cdn.tailwindcss.com)"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="[https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css)">
    <!-- Google Fonts -->
    <link href="[https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap](https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap)" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0b0f19;
            color: #f3f4f6;
        }
        .glass-card {
            background: rgba(17, 24, 39, 0.7);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .neon-glow {
            box-shadow: 0 0 25px rgba(236, 72, 153, 0.3);
        }
        .neon-border {
            border: 1px solid rgba(236, 72, 153, 0.5);
        }
    </style>
</head>
<body class="bg-[#0b0f19] min-h-screen pb-20">

    <!-- HEADER / NAVBAR -->
    <header class="sticky top-0 z-50 glass-card border-b border-gray-800 px-4 py-3 flex justify-between items-center">
        <div class="flex items-center space-x-2">
            <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-pink-500 to-purple-600 flex items-center justify-center neon-glow">
                <i class="fa-solid fa-mug-hot text-white text-lg"></i>
            </div>
            <div>
                <h1 class="font-extrabold text-lg tracking-wide bg-gradient-to-r from-pink-400 to-purple-400 bg-clip-text text-transparent">XUYÊN QUÁN</h1>
                <p class="text-[10px] text-pink-400 font-medium tracking-widest uppercase">Giao diện 5.0 Ultra</p>
            </div>
        </div>
        <div class="flex items-center space-x-3">
            <span class="relative flex h-3 w-3">
              <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-pink-400 opacity-75"></span>
              <span class="relative inline-flex rounded-full h-3 w-3 bg-pink-500"></span>
            </span>
            <span class="text-xs font-semibold text-gray-300">Online 24/7</span>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="px-4 pt-6 pb-4">
        <div class="relative rounded-3xl overflow-hidden glass-card p-6 neon-border">
            <div class="absolute -right-10 -bottom-10 w-40 h-40 bg-pink-500/20 rounded-full blur-3xl"></div>
            <div class="relative z-10">
                <span class="bg-pink-500/20 text-pink-300 text-xs font-bold px-3 py-1 rounded-full border border-pink-500/30">Hệ Thống Thư Giãn Đa Không Gian</span>
                <h2 class="text-2xl font-black mt-3 leading-tight">Cafe Sáng Tạo, <br><span class="text-pink-400">Gội Đầu Thượng Lưu</span> & Massage.</h2>
                <p class="text-gray-400 text-xs mt-2 leading-relaxed">Trải nghiệm dịch vụ đỉnh cao với đội ngũ chuyên nghiệp, phục vụ tận tâm, mang lại năng lượng tuyệt vời nhất.</p>
                <div class="mt-4 flex gap-2">
                    <a href="#services" class="bg-gradient-to-r from-pink-500 to-purple-600 text-white font-bold text-xs px-4 py-2.5 rounded-xl shadow-lg shadow-pink-500/30 flex items-center gap-2">
                        <i class="fa-solid fa-bolt"></i> Khám Phá Ngay
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- MAIN SERVICES -->
    <main id="services" class="px-4 space-y-6 mt-4">

        <!-- SECTION 1: CAFE & GỘI ĐẦU -->
        <div>
            <div class="flex justify-between items-center mb-3">
                <h3 class="font-bold text-base flex items-center gap-2">
                    <i class="fa-solid fa-mug-saucer text-amber-400"></i> Cafe & Gội Đầu Thư Giãn
                </h3>
                <span class="text-xs text-gray-400">Phổ biến</span>
            </div>
            <div class="grid grid-cols-2 gap-3">
                <!-- Item 1 -->
                <div class="glass-card p-3 rounded-2xl flex flex-col justify-between">
                    <div>
                        <div class="h-28 bg-gray-800 rounded-xl overflow-hidden mb-2 relative">
                            <img src="[https://images.unsplash.com/photo-1541167760496-1628856ab772?auto=format&fit=crop&w=500&q=80](https://images.unsplash.com/photo-1541167760496-1628856ab772?auto=format&fit=crop&w=500&q=80)" alt="Cafe" class="w-full h-full object-cover">
                        </div>
                        <h4 class="font-bold text-sm">Cafe Sữa Đá 5.0</h4>
                        <p class="text-[11px] text-gray-400 mt-0.5">Đậm đà hương vị nguyên bản.</p>
                    </div>
                    <div class="mt-3 flex justify-between items-center">
                        <span class="text-pink-400 font-bold text-xs">35.000đ</span>
                        <button onclick="orderItem('Cafe Sữa Đá 5.0', '35.000đ')" class="bg-gray-800 hover:bg-pink-600 text-white text-xs px-3 py-1.5 rounded-lg transition"><i class="fa-solid fa-plus"></i></button>
                    </div>
                </div>
                <!-- Item 2 -->
                <div class="glass-card p-3 rounded-2xl flex flex-col justify-between">
                    <div>
                        <div class="h-28 bg-gray-800 rounded-xl overflow-hidden mb-2 relative">
                            <img src="[https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&w=500&q=80](https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&w=500&q=80)" alt="Gội đầu" class="w-full h-full object-cover">
                        </div>
                        <h4 class="font-bold text-sm">Gội Đầu Thảo Dược</h4>
                        <p class="text-[11px] text-gray-400 mt-0.5">Massage bấm huyệt cổ vai gáy.</p>
                    </div>
                    <div class="mt-3 flex justify-between items-center">
                        <span class="text-pink-400 font-bold text-xs">120.000đ</span>
                        <button onclick="orderItem('Gội Đầu Thảo Dược', '120.000đ')" class="bg-gray-800 hover:bg-pink-600 text-white text-xs px-3 py-1.5 rounded-lg transition"><i class="fa-solid fa-plus"></i></button>
                    </div>
                </div>
            </div>
        </div>

        <!-- SECTION 2: MASSAGE & TRAI ĐI KHÁCH (VIP SERVICE) -->
        <div>
            <div class="flex justify-between items-center mb-3">
                <h3 class="font-bold text-base flex items-center gap-2">
                    <i class="fa-solid fa-fire text-pink-500"></i> Dịch Vụ VIP & Trai Đi Khách
                </h3>
                <span class="text-xs text-pink-400 font-semibold">Hot 18+</span>
            </div>
            
            <div class="space-y-3">
                <!-- Profile Card 1 -->
                <div class="glass-card p-3.5 rounded-2xl flex items-center gap-4 border border-pink-500/20">
                    <div class="w-16 h-16 rounded-xl overflow-hidden bg-gray-800 flex-shrink-0 relative">
                        <img src="[https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=300&q=80](https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=300&q=80)" alt="Model" class="w-full h-full object-cover">
                        <div class="absolute bottom-0 right-0 w-3 h-3 bg-green-500 rounded-full border-2 border-gray-900"></div>
                    </div>
                    <div class="flex-grow">
                        <div class="flex justify-between items-start">
                            <h4 class="font-bold text-sm">Alex - Nam Thần (22 tuổi)</h4>
                            <span class="bg-pink-500/10 text-pink-400 text-[10px] px-2 py-0.5 rounded font-bold">VIP 01</span>
                        </div>
                        <p class="text-[11px] text-gray-400 mt-1">Chuyên: Massage Body, Đồng hành đi tiệc, Cafe, Đi khách theo giờ.</p>
                        <div class="mt-2 flex justify-between items-center">
                            <span class="text-xs text-amber-400 font-semibold"><i class="fa-solid fa-star"></i> 4.9 (120 lượt)</span>
                            <button onclick="bookingStaff('Alex - Nam Thần')" class="bg-gradient-to-r from-pink-500 to-purple-600 text-white text-xs px-3 py-1 rounded-lg font-bold shadow-md shadow-pink-500/20">Đặt Lịch</button>
                        </div>
                    </div>
                </div>

                <!-- Profile Card 2 -->
                <div class="glass-card p-3.5 rounded-2xl flex items-center gap-4 border border-pink-500/20">
                    <div class="w-16 h-16 rounded-xl overflow-hidden bg-gray-800 flex-shrink-0 relative">
                        <img src="[https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=300&q=80](https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=300&q=80)" alt="Model" class="w-full h-full object-cover">
                        <div class="absolute bottom-0 right-0 w-3 h-3 bg-green-500 rounded-full border-2 border-gray-900"></div>
                    </div>
                    <div class="flex-grow">
                        <div class="flex justify-between items-start">
                            <h4 class="font-bold text-sm">Ken - Phong Độ (25 tuổi)</h4>
                            <span class="bg-pink-500/10 text-pink-400 text-[10px] px-2 py-0.5 rounded font-bold">VIP 02</span>
                        </div>
                        <p class="text-[11px] text-gray-400 mt-1">Chuyên: Trò chuyện tâm sự, Massage thư giãn chuyên sâu, Đi khách cao cấp.</p>
                        <div class="mt-2 flex justify-between items-center">
                            <span class="text-xs text-amber-400 font-semibold"><i class="fa-solid fa-star"></i> 5.0 (98 lượt)</span>
                            <button onclick="bookingStaff('Ken - Phong Độ')" class="bg-gradient-to-r from-pink-500 to-purple-600 text-white text-xs px-3 py-1 rounded-lg font-bold shadow-md shadow-pink-500/20">Đặt Lịch</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </main>

    <!-- FLOATING ACTION BUTTON / CART MODAL TRIGGER -->
    <div class="fixed bottom-4 left-4 right-4 z-40">
        <div class="glass-card p-3 rounded-2xl flex justify-between items-center shadow-2xl border border-pink-500/30">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-pink-500/20 flex items-center justify-center text-pink-400">
                    <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div>
                    <p class="text-xs text-gray-400">Đã chọn dịch vụ:</p>
                    <p id="selected-count" class="text-xs font-bold text-white">0 dịch vụ</p>
                </div>
            </div>
            <button onclick="openCheckout()" class="bg-gradient-to-r from-pink-500 to-purple-600 text-white font-bold text-xs px-5 py-2.5 rounded-xl shadow-lg shadow-pink-500/30">
                Thanh Toán Ngay
            </button>
        </div>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        let cart = [];

        function orderItem(name, price) {
            cart.push({name, price});
            document.getElementById('selected-count').innerText = cart.length + ' dịch vụ';
            alert('Đã thêm "' + name + '" vào danh sách!');
        }

        function bookingStaff(staffName) {
            alert('Hệ thống tiếp nhận yêu cầu đặt lịch với: ' + staffName + '. Nhân viên tổng đài sẽ liên hệ xác nhận bảo mật!');
        }

        function openCheckout() {
            if(cart.length === 0) {
                alert('Vui lòng chọn dịch vụ hoặc nhân viên trước khi thanh toán!');
                return;
            }
            let summary = cart.map(i => i.name + ' (' + i.price + ')').join('\n');
            alert('Xác nhận đơn hàng của bạn:\n\n' + summary + '\n\nCảm ơn bạn đã sử dụng dịch vụ tại Xuyên Quán 5.0!');
            cart = [];
            document.getElementById('selected-count').innerText = '0 dịch vụ';
        }
    </script>

</body>
</html>
