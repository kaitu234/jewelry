# Kai Jewelry · Hub nội bộ

Trang tĩnh GitHub Pages. `index.html` chỉ chứa bản Hub **đã mã hóa** (AES-256-GCM, khóa từ mật khẩu qua PBKDF2-SHA256 600.000 vòng). Mở trang, nhập mật khẩu để xem; chọn "Nhớ trên máy này" thì lần sau tự mở.

Cập nhật: sửa Hub trong dự án, chạy `node file/build/ma-hoa-hub.js`, rồi commit và push thư mục này. Mật khẩu không lưu trong repo.


## Dashboard (dash/)

`dash/index.html`: dashboard nội bộ cùng khung với dashboard Kai Café (Tổng quan · Việc · Sản phẩm · Lô hàng · Tồn kho · Đơn hàng · KOC · Kết nối). Đọc và ghi Google Sheet "[Kai Jewelry] Working File" qua API Apps Script. File không chứa số liệu, link API hay mã khóa: mỗi máy nhập link + mã khóa một lần (lưu trong trình duyệt).
