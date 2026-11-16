# Kai Jewelry · Hub nội bộ

Trang tĩnh GitHub Pages. `index.html` chỉ chứa bản Hub **đã mã hóa** (AES-256-GCM, khóa từ mật khẩu qua PBKDF2-SHA256 600.000 vòng). Mở trang, nhập mật khẩu để xem; chọn "Nhớ trên máy này" thì lần sau tự mở.

Cập nhật: sửa Hub trong dự án, chạy `node file/build/ma-hoa-hub.js`, rồi commit và push thư mục này. Mật khẩu không lưu trong repo.

## Số liệu

Tab Tổng quan · Việc cần làm · Sản phẩm · Lô hàng · Tồn kho · Đơn hàng · KOC · Kết nối Sheet đọc và ghi Google Sheet "[Kai Jewelry] Working File" qua API Apps Script. Mã khóa API nhập một lần trên mỗi máy, lưu trong trình duyệt, không nằm trong repo. Đăng xuất (thanh trái, hoặc nút ⋯ trên điện thoại) xóa mật khẩu Hub và mã khóa đã nhớ. `dash/` chỉ còn chuyển hướng về Hub. Cài như app: manifest.webmanifest.
