# Chính sách Quyền riêng tư - AI Box Chrome Extension

**Cập nhật lần cuối:** 2025-11-01

## Giới thiệu

AI Box là một extension trình duyệt Chrome giúp người dùng tương tác với các dịch vụ AI trực tiếp từ trình duyệt. Chúng tôi cam kết bảo vệ quyền riêng tư của bạn.

## Thu thập và Sử dụng Dữ liệu

### Dữ liệu KHÔNG được thu thập

AI Box **KHÔNG** thu thập, lưu trữ, hoặc truyền tải bất kỳ dữ liệu nào về máy chủ của chúng tôi, bao gồm:

- ❌ Lịch sử duyệt web
- ❌ Nội dung trang web bạn truy cập
- ❌ Nội dung chat với AI
- ❌ Thông tin cá nhân
- ❌ API keys
- ❌ Cấu hình người dùng

### Dữ liệu được lưu trữ cục bộ

Tất cả dữ liệu sau được lưu trữ **cục bộ trên máy tính của bạn** thông qua Chrome Storage API và IndexedDB:

- ✅ Lịch sử cuộc trò chuyện với AI
- ✅ Cấu hình cá nhân (API keys, mô hình AI ưa thích)
- ✅ Danh sách webhook
- ✅ Custom prompts

Dữ liệu này:
- Chỉ tồn tại trên máy của bạn
- Không được đồng bộ lên cloud
- Có thể xóa bất kỳ lúc nào thông qua Settings → Xóa dữ liệu

## Quyền truy cập (Permissions)

### 1. Truy cập tất cả các trang web (`<all_urls>`)

**Mục đích:**
- Hiển thị Quick Actions (menu Tóm tắt, Dịch, Giải thích) khi bạn chọn văn bản
- Đọc nội dung trang web khi bạn sử dụng tính năng "Chat với trang web"
- Trích xuất phụ đề video YouTube

**Không sử dụng để:**
- ❌ Theo dõi hoạt động duyệt web của bạn
- ❌ Thu thập dữ liệu cá nhân
- ❌ Gửi dữ liệu về server của chúng tôi

### 2. Storage (`storage`)

**Mục đích:** Lưu trữ cấu hình và lịch sử chat cục bộ trên máy bạn.

### 3. Side Panel (`sidePanel`)

**Mục đích:** Hiển thị giao diện chat trong thanh bên Chrome.

### 4. Active Tab (`activeTab`)

**Mục đích:** Đọc nội dung trang hiện tại khi bạn chủ động sử dụng tính năng "Chat với trang web".

### 5. Scripting (`scripting`)

**Mục đích:** Inject giao diện Quick Actions khi bạn chọn văn bản.

## Dịch vụ Bên thứ ba

### Nhà cung cấp AI

Khi bạn sử dụng tính năng AI, dữ liệu sẽ được gửi **trực tiếp** từ máy của bạn tới nhà cung cấp AI mà bạn đã cấu hình (ví dụ: OpenAI, Anthropic, Google, v.v.).

**Quan trọng:**
- Bạn sử dụng **API key riêng** của mình
- Chúng tôi **KHÔNG** là trung gian
- Chúng tôi **KHÔNG** lưu trữ hoặc truy cập API key của bạn
- Dữ liệu tuân theo chính sách quyền riêng tư của nhà cung cấp AI bạn chọn

### Webhook

Khi bạn sử dụng tính năng webhook, dữ liệu được gửi **trực tiếp** tới endpoint mà bạn tự cấu hình. Chúng tôi không kiểm soát hoặc lưu trữ dữ liệu này.

## Bảo mật

- Tất cả API keys được lưu trữ an toàn trong Chrome Storage (chỉ extension có thể truy cập)
- Không có server backend, không có điểm yếu bảo mật từ xa
- Mã nguồn có thể được review để đảm bảo tính minh bạch

## Quyền của Người dùng

Bạn có quyền:

1. **Xem dữ liệu:** Tất cả dữ liệu lưu cục bộ có thể xem qua Chrome DevTools
2. **Xóa dữ liệu:** Vào Settings → Xóa tất cả dữ liệu
3. **Xuất dữ liệu:** Backup cuộc trò chuyện qua tính năng Export
4. **Gỡ cài đặt:** Xóa extension sẽ xóa toàn bộ dữ liệu cục bộ

## Thay đổi Chính sách

Chúng tôi có thể cập nhật chính sách này. Mọi thay đổi quan trọng sẽ được thông báo qua:
- Cập nhật version extension
- Thông báo trong extension
- GitHub repository

## Tuân thủ

Extension này tuân thủ:
- Chrome Web Store Developer Program Policies
- Google API Services User Data Policy
- GDPR (General Data Protection Regulation)

## Liên hệ

Nếu bạn có câu hỏi về chính sách quyền riêng tư này:

- **Email:** [your-email@example.com]
- **GitHub Issues:** [https://github.com/[username]/ai-box/issues]
- **Chrome Web Store:** [Link tới extension]

## Tuyên bố Minh bạch

**Chúng tôi cam kết:**
- ✅ Không thu thập dữ liệu cá nhân
- ✅ Không bán dữ liệu cho bên thứ ba
- ✅ Không theo dõi hoạt động người dùng
- ✅ Không có server backend để lưu trữ dữ liệu
- ✅ Mã nguồn minh bạch, có thể kiểm tra
- ✅ Người dùng kiểm soát hoàn toàn dữ liệu của mình

---

**Ngày có hiệu lực:** 2025-11-01

**Version:** 1.0.0
