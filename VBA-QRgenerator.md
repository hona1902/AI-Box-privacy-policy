# Privacy Policy – VietQR Template Generator

Last updated: 2025-11-27

## Dữ liệu thu thập
- **Không thu thập hay gửi dữ liệu cá nhân ra máy chủ bên thứ ba.**
- Thông tin bạn nhập (số tài khoản/nickname, tên chủ TK, tùy chọn hiển thị, template, logo tùy chỉnh) được lưu cục bộ bằng Chrome Storage (`chrome.storage.sync/local`) để tiện ghi nhớ lần dùng sau.
- Khi tải Excel, nội dung file được xử lý hoàn toàn trên trình duyệt, không upload ra bất kỳ máy chủ nào.

## Kết nối mạng
- Tiện ích gọi `https://img.vietqr.io` để tải ảnh QR theo thông tin bạn nhập. Không có kết nối nào khác.
- Thư viện XLSX/JSZip được đóng gói sẵn trong `assets/`. (Có cơ chế fallback CDN nhưng bản phát hành nên dùng bản cục bộ kèm theo.)

## Xử lý file và bộ nhớ cục bộ
- Logo tùy chỉnh và template tùy chỉnh được lưu trong `chrome.storage` và chỉ dùng cho việc hiển thị/generating của tiện ích.
- File ZIP/PDF/PNG được tạo và tải xuống cục bộ; không gửi ra ngoài.

## Phân quyền
- `storage`: lưu cài đặt và dữ liệu tiện ích trên thiết bị.
- `activeTab`/`scripting`: chỉ dùng cho logic nội bộ tiện ích khi cần (không thu thập nội dung trang).

## Bảo mật
- Không có mã theo dõi/analytics.
- Không thu thập cookie, lịch sử duyệt web hoặc dữ liệu đăng nhập.

## Liên hệ
email: nghoainam1902@gmail.com
