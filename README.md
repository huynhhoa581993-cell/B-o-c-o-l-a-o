# BÁO CÁO ĐƯỜNG DÂY NÓNG LỪA ĐẢO – XÃ TRÀ LIÊN

Ứng dụng web/mobile chuyên biệt hỗ trợ người dân xã Trà Liên báo cáo nhanh các vụ việc nghi ngờ lừa đảo qua mạng, qua điện thoại, chuyển khoản ngân hàng đến **Công an xã Trà Liên**.

---

## 🌟 TÍNH NĂNG NỔI BẬT

### 1. Dành cho Người dân
* **Giao diện thân thiện:** Tối ưu hóa cho màn hình điện thoại (mobile-first), phông chữ lớn, nút bấm to rõ, màu sắc trang nghiêm (xanh dương - đỏ cảnh báo - trắng).
* **Nút lớn trung tâm:** `🔴 BÁO CÁO NGAY` mở ngay biểu mẫu gửi tin báo.
* **Báo cáo ẩn danh:** Lựa chọn `Tôi muốn báo cáo ẩn danh` không bắt buộc cung cấp họ tên và số điện thoại.
* **10 loại hình lừa đảo chi tiết:** Lừa đảo điện thoại, Facebook/Zalo, SMS, chuyển khoản, giả danh Công an, lừa đảo việc làm, mua sắm online, lừa đảo đầu tư, chiếm đoạt nick...
* **Đính kèm bằng chứng:** Cho phép tải lên ảnh chụp màn hình tin nhắn, giao dịch chuyển khoản, file bằng chứng.
* **Mã định danh báo cáo:** Cấp mã theo chuẩn `TL-XXXXXXXX` để người dân tiện theo dõi và tra cứu tiến độ tiếp nhận.
* **Nút gọi khẩn cấp cố định:** Nút `☎️ GỌI CÔNG AN` luôn nổi ở góc màn hình, tự động kết nối đến số Hotline của trực ban Công an xã.
* **Đọc hướng dẫn bằng giọng nói:** Tích hợp công nghệ giọng đọc tiếng Việt (Web Speech API) hỗ trợ người cao tuổi hoặc người khó đọc chữ.
* **Cẩm nang nhận diện lừa đảo & Chia sẻ:** 7 kịch bản lừa đảo kèm ví dụ thực tế; hỗ trợ chia sẻ nhanh lên Facebook, Zalo hoặc sao chép nội dung cảnh báo.

### 2. Dành cho Cán bộ Công an xã
* **Bảng điều khiển quản trị:** Bấm vào nút `Cán bộ` ở góc trên bên phải màn hình (Mật khẩu mặc định: `police123`).
* **Tiếp nhận & Xử lý:** Xem danh sách, lọc theo trạng thái (`Đã tiếp nhận`, `Đang xác minh`, `Đã xử lý`, `Chuyển cấp có thẩm quyền`), lọc theo thôn xóm, tìm kiếm theo từ khóa / số điện thoại nghi vấn.
* **Xem chi tiết & Bằng chứng:** Xem toàn bộ nội dung vụ việc, phóng to ảnh chụp màn hình chứng cứ, cập nhật trạng thái và ghi chú xử lý nghiệp vụ.
* **Thống kê Dashboard:** Biểu đồ trực quan số vụ theo từng loại lừa đảo và số vụ theo từng thôn trong xã.
* **Xuất báo cáo:** Xuất dữ liệu ra file Excel / CSV (hỗ trợ tiếng Việt UTF-8 có BOM) để lưu trữ hoặc nộp báo cáo cấp trên.
* **Cấu hình hệ thống:** Cho phép thay đổi tên đơn vị, số hotline, email tiếp nhận, địa chỉ, cán bộ phụ trách, và địa chỉ API Endpoint máy chủ cấp trên.

---

## 🚀 CÁCH SỬ DỤNG

1. Bấm đúp chuột vào file **`Chay_Ung_Dung.bat`** hoặc mở trực tiếp file **`index.html`** bằng trình duyệt bất kỳ (Google Chrome, Microsoft Edge, Cốc Cốc, Safari...).
2. Không cần cài đặt bất kỳ phần mềm hay môi trường lập trình nào.
3. Ứng dụng tự động lưu trữ dữ liệu vào máy tính (Local Storage / Cache) và sẵn sàng kết nối API thật khi cán bộ cấu hình.
