# Danh sách thông tin cá nhân được thu thập

**Cập nhật lần cuối: 5 tháng 1 năm 2026**

Theo GDPR Điều 13, CCPA và các luật và quy định liên quan khác, chúng tôi giải thích thông tin cá nhân được thu thập bởi ứng dụng này:

> **QUAN TRỌNG**: Tất cả thông tin dưới đây chỉ được lưu trữ cục bộ trên thiết bị của bạn và sẽ không được tải lên bất kỳ máy chủ nào.

## 1. Thông tin thiết bị (Đọc cục bộ để hiển thị)

### 1.1 Thông tin thiết bị cơ bản
- **Loại thông tin**: Tên thiết bị, model thiết bị, phiên bản hệ thống
- **Mục đích thu thập**: Hiển thị trên trang "Thông tin thiết bị"
- **Cơ sở pháp lý**: Thực hiện hợp đồng (cung cấp dịch vụ bạn yêu cầu)
- **Phương pháp thu thập**: Đọc qua API hệ thống
- **API sử dụng**: UIDevice.current
- **Thời gian lưu giữ**: Thời gian sử dụng ứng dụng

### 1.2 Mã định danh thiết bị
- **Loại thông tin**: Mã định danh model (ví dụ: iPhone17,1)
- **Mục đích thu thập**: Xác định model thiết bị để hiển thị
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Phương pháp thu thập**: Qua cuộc gọi hệ thống utsname
- **Lưu ý**: Không phải mã định danh quảng cáo (IDFA), không phải mã định danh duy nhất thiết bị (IDFV)

### 1.3 Thông tin trạng thái thiết bị
- **Loại thông tin**: Mức pin, trạng thái pin, dung lượng ổ đĩa, sử dụng bộ nhớ
- **Mục đích thu thập**: Hiển thị trên trang "Thông tin thiết bị"
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Phương pháp thu thập**: Đọc qua API hệ thống

## 2. Thông tin mạng (Đọc cục bộ để chẩn đoán)

### 2.1 Địa chỉ IP
- **Loại thông tin**: Địa chỉ IPv4 cục bộ, địa chỉ IPv6 cục bộ
- **Mục đích thu thập**: Chẩn đoán mạng, hiển thị thông tin thiết bị
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Phương pháp thu thập**: Qua cuộc gọi hệ thống getifaddrs

### 2.2 Trạng thái mạng
- **Loại thông tin**: Loại mạng (WiFi/Di động/Không có mạng)
- **Mục đích thu thập**: Xác định môi trường mạng, chẩn đoán mạng
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Phương pháp thu thập**: Qua trình nghe NWPathMonitor

### 2.3 Loại mạng di động
- **Loại thông tin**: 2G/3G/4G/5G
- **Mục đích thu thập**: Hiển thị loại mạng chi tiết
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Phương pháp thu thập**: Qua framework CoreTelephony

## 3. Bản ghi lịch sử (Lưu trữ cục bộ)

### 3.1 Lịch sử mục tiêu thăm dò
- **Loại thông tin**: Địa chỉ mục tiêu Ping/DNS/TCP/UDP/Trace/HTTP
- **Mục đích thu thập**: Thuận tiện cho người dùng chọn nhanh các mục tiêu thường dùng
- **Cơ sở pháp lý**: Lợi ích hợp pháp (cải thiện trải nghiệm người dùng)
- **Phương pháp lưu trữ**: Lưu trữ cục bộ UserDefaults
- **Giới hạn lưu trữ**: Tối đa 10 bản ghi mỗi danh mục
- **Thời gian lưu giữ**: Cho đến khi người dùng xóa hoặc gỡ cài đặt ứng dụng

### 3.2 Lịch sử truy vấn IP
- **Loại thông tin**: Các địa chỉ IP đã truy vấn
- **Mục đích thu thập**: Thuận tiện cho người dùng xem lịch sử truy vấn
- **Cơ sở pháp lý**: Lợi ích hợp pháp
- **Phương pháp lưu trữ**: Lưu trữ cục bộ UserDefaults

### 3.3 Lịch sử kiểm tra kết nối/Chẩn đoán nhanh
- **Loại thông tin**: Địa chỉ mục tiêu kiểm tra
- **Mục đích thu thập**: Thuận tiện cho người dùng lặp lại kiểm tra
- **Cơ sở pháp lý**: Lợi ích hợp pháp
- **Phương pháp lưu trữ**: Lưu trữ cục bộ UserDefaults

## 4. Mã định danh người dùng (Tạo cục bộ)

### 4.1 ID khách
- **Loại thông tin**: Chuỗi được tạo ngẫu nhiên
- **Mục đích thu thập**: Nhận dạng người dùng cục bộ
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Phương pháp lưu trữ**: Lưu trữ cục bộ UserDefaults
- **Lưu ý**: Được tạo hoàn toàn ngẫu nhiên, không liên kết với bất kỳ thông tin danh tính cá nhân nào

## 5. Yêu cầu mạng (Cần thiết cho chức năng) - Chuyển dữ liệu quốc tế

### 5.1 Dịch vụ truy vấn IP NetEase
- **URL dịch vụ**: mail.163.com
- **Nhà cung cấp**: NetEase, Inc. (Trung Quốc)
- **Dữ liệu gửi**: Yêu cầu mạng (tự động gửi IP công cộng)
- **Dữ liệu nhận**: Địa chỉ IP công cộng, quốc gia, tỉnh, thành phố, ISP
- **Mục đích**: Lấy IP công cộng và thông tin vị trí địa lý của thiết bị hiện tại
- **Cơ sở pháp lý**: Thực hiện hợp đồng

### 5.2 Dịch vụ truy vấn IP Bilibili
- **URL dịch vụ**: api.live.bilibili.com
- **Nhà cung cấp**: Bilibili Inc. (Trung Quốc)
- **Dữ liệu gửi**: Địa chỉ IP để truy vấn
- **Dữ liệu nhận**: Quốc gia, tỉnh, thành phố, ISP, tọa độ
- **Mục đích**: Truy vấn vị trí địa lý của IP được chỉ định
- **Cơ sở pháp lý**: Thực hiện hợp đồng

### 5.3 Dịch vụ truy vấn ASN ipinfo.io
- **URL dịch vụ**: api.ipinfo.io
- **Nhà cung cấp**: IPinfo Inc. (Hoa Kỳ)
- **Dữ liệu gửi**: Địa chỉ IP để truy vấn
- **Dữ liệu nhận**: Số AS, tên AS, quốc gia
- **Mục đích**: Truy vấn số AS (Số hệ thống tự trị) của IP
- **Cơ sở pháp lý**: Thực hiện hợp đồng
- **Lưu ý chuyển quốc tế**: Dữ liệu có thể được chuyển đến Hoa Kỳ; dịch vụ tuân thủ GDPR

## 6. Cách xóa thông tin

- **Lịch sử**: Xóa thủ công trên mỗi trang tính năng
- **Tất cả dữ liệu**: Gỡ cài đặt ứng dụng để xóa tất cả dữ liệu cục bộ
- **Thực hiện quyền dữ liệu**: Liên hệ zjccc5889@gmail.com
