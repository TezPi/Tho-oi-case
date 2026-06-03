THỢ ƠI — UI/UX CASE STUDY
On-Demand Home Services App · 2025
Thiết kế: Ông Chủ TezPi · Biên Hòa, Đồng Nai

============================================================
NỘI DUNG GÓI
============================================================

tho-oi-case-study.html
   Case study board hoàn chỉnh. Mở bằng trình duyệt (Chrome / Safari).
   Toàn bộ hình ảnh nhúng sẵn dạng base64 — không cần file ngoài.
   Deploy: upload riêng file này lên bất kỳ host tĩnh nào
   (Netlify, Vercel, GitHub Pages, Cloudflare Pages...).

facebook-post.md
   Bài giới thiệu dự án để đăng Facebook (plain text, FB-safe).
   Kèm 3 hook thay thế ở cuối file để đổi góc tiếp cận.

/slides   (9 ảnh PNG, retina 2x — chiều ngang 2640px)
   slide-00-full-board ........ toàn board 1 ảnh dọc (Behance hero)
   slide-01-hero .............. màn mở đầu
   slide-02-tong-quan ......... tổng quan dự án
   slide-03-thach-thuc-tiep-can  thách thức & hướng tiếp cận
   slide-04-he-thong-thiet-ke .. design system (màu/chữ/component)
   slide-05-trai-nghiem ....... gallery 8 màn hình
   slide-06-luong-dat-tho ..... luồng đặt thợ 6 bước
   slide-07-nguyen-tac-thiet-ke  nguyên tắc thiết kế
   slide-08-ket-qua ........... kết quả & CTA
   → full-board cho Behance; slide rời cho carousel mạng xã hội.

/assets
   logo.png ... logo Thợ Ơi đã cắt tròn, nền trong suốt (136×136).

============================================================
GHI CHÚ KỸ THUẬT
============================================================
- Font: Be Vietnam Pro + JetBrains Mono, nạp qua Google Fonts khi mở
  online. Mở offline vẫn chạy, tự rớt về font hệ thống.
- Bảng màu, typography, component được dựng native bằng HTML/CSS
  (không phụ thuộc framework).
- Hiệu ứng: scroll-reveal, sticky-nav blur, hover micro-interactions;
  tôn trọng prefers-reduced-motion.
- Responsive: breakpoint 1024px / 680px.
