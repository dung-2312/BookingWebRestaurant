﻿# BookingWebRestaurant
# 📋 Yêu cầu chức năng - Website đặt bàn nhà hàng

## 🧠 1. Brainstorming / Phỏng vấn giả định

| Câu hỏi | Câu trả lời |
|--------|-------------|
| Nhà hàng muốn khách đặt bàn như thế nào? | Qua website, chọn ngày giờ, số khách |
| Quản lý muốn xem thông tin đặt bàn như thế nào? | Theo danh sách ngày, có thể xác nhận/hủy |
| Những thông tin nào cần khi khách đặt bàn? | Họ tên, SĐT, số khách, ngày giờ, ghi chú |
| Có cần quản trị viên không? | Có, để xử lý và xác nhận đơn đặt bàn |
| Có muốn khách xem thực đơn trước không? | Có, để khách dễ quyết định |
| Có tích hợp thanh toán online không? | Có thể thêm sau |

---

## 📝 2. Danh sách User Stories

- Với vai trò **Khách hàng**, tôi muốn **xem lịch trống của bàn** để **chọn được thời gian phù hợp**.
- Với vai trò **Khách hàng**, tôi muốn **đặt bàn qua form** để **khỏi phải gọi điện**.
- Với vai trò **Khách hàng**, tôi muốn **đăng nhập để theo dõi lịch sử đặt bàn**.
- Với vai trò **Quản trị viên**, tôi muốn **xem danh sách đặt bàn theo ngày** để **lên kế hoạch phục vụ**.
- Với vai trò **Quản trị viên**, tôi muốn **xác nhận đơn đặt bàn** để **chốt chỗ trước cho khách**.

---

## 🎯 3. Phân loại tính năng

### ✅ Tính năng bắt buộc (Must-have)
- Form đặt bàn (ngày, giờ, số khách, họ tên, SĐT)
- Đăng nhập người dùng (Firebase Auth)
- Admin dashboard để xác nhận đặt bàn
- Xem lịch sử đặt bàn cho người dùng
- Responsive UI (dùng Tailwind CSS)

### 💡 Tính năng nên có (Nice-to-have)
- Gửi email xác nhận sau khi đặt bàn
- Dropdown chọn khung giờ (thay vì nhập tay)
- Lịch hiển thị tình trạng bàn (màu xanh/đỏ)
- Hiển thị thực đơn món ăn

### 🌱 Ý tưởng tương lai (Future ideas)
- Thanh toán online qua Momo/ZaloPay/Stripe
- Tính điểm thưởng, đặt bàn VIP
- Đặt bàn qua chatbot Facebook Messenger
