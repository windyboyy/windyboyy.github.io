# Danh sách SDK bên thứ ba

**Cập nhật lần cuối: 5 tháng 1 năm 2026**

Ứng dụng này tích hợp các SDK sau:

## 1. SDK hệ thống Apple

### 1.1 Foundation
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Hỗ trợ framework cơ bản, cung cấp các kiểu dữ liệu và bộ sưu tập cơ bản
- **Thông tin thu thập**: Không có

### 1.2 SwiftUI
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Framework giao diện người dùng, xây dựng giao diện ứng dụng
- **Thông tin thu thập**: Không có

### 1.3 UIKit
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Hỗ trợ thành phần UI, lấy thông tin thiết bị
- **Thông tin thu thập**: Tên thiết bị, phiên bản hệ thống, trạng thái pin

### 1.4 Network
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Hỗ trợ giao tiếp mạng, kết nối TCP/UDP, giám sát trạng thái mạng
- **Thông tin thu thập**: Trạng thái kết nối mạng

### 1.5 CoreTelephony
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Lấy thông tin mạng di động
- **Thông tin thu thập**: Loại mạng di động (2G/3G/4G/5G)

### 1.6 NetworkExtension
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Hỗ trợ mở rộng mạng (dành cho tính năng bắt gói)
- **Thông tin thu thập**: Không có

### 1.7 Security
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Hỗ trợ framework bảo mật
- **Thông tin thu thập**: Không có

### 1.8 Darwin
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Cuộc gọi hệ thống cấp thấp, sử dụng cho Ping, Traceroute, v.v.
- **Thông tin thu thập**: Không có

### 1.9 dnssd
- **Nhà cung cấp**: Apple Inc.
- **Chức năng**: Khám phá dịch vụ DNS, sử dụng cho tính năng truy vấn DNS
- **Thông tin thu thập**: Không có

## 2. SDK thương mại bên thứ ba

Ứng dụng này hiện không tích hợp bất kỳ SDK thương mại bên thứ ba nào, bao gồm nhưng không giới hạn:
- Không có SDK quảng cáo
- Không có SDK phân tích
- Không có SDK chia sẻ xã hội
- Không có SDK thông báo đẩy
- Không có SDK thanh toán

## 3. Dịch vụ mạng bên thứ ba

### 3.1 Dịch vụ truy vấn IP NetEase
- **URL dịch vụ**: mail.163.com
- **Nhà cung cấp**: NetEase, Inc.
- **Chức năng**: Lấy địa chỉ IP công cộng và vị trí địa lý của thiết bị hiện tại
- **Dữ liệu gửi**: Yêu cầu mạng (tự động gửi IP công cộng)
- **Dữ liệu trả về**: Địa chỉ IP công cộng, quốc gia, tỉnh, thành phố, ISP

### 3.2 Dịch vụ truy vấn IP Bilibili
- **URL dịch vụ**: api.live.bilibili.com
- **Nhà cung cấp**: Bilibili Inc.
- **Chức năng**: Truy vấn vị trí địa lý của IP được chỉ định
- **Dữ liệu gửi**: Địa chỉ IP để truy vấn
- **Dữ liệu trả về**: Quốc gia, tỉnh, thành phố, ISP, tọa độ

### 3.3 Dịch vụ truy vấn ASN ipinfo.io
- **URL dịch vụ**: api.ipinfo.io
- **Nhà cung cấp**: IPinfo Inc. (Hoa Kỳ)
- **Chức năng**: Truy vấn số AS (Số hệ thống tự trị) của IP
- **Dữ liệu gửi**: Địa chỉ IP để truy vấn
- **Dữ liệu trả về**: Số AS, tên AS, quốc gia

## 4. Lưu ý

1. Ứng dụng này chỉ sử dụng SDK hệ thống chính thức của Apple để đảm bảo an toàn và đáng tin cậy.
2. Nếu SDK bên thứ ba mới được tích hợp trong tương lai, chúng tôi sẽ cập nhật danh sách này và thông báo cho bạn kịp thời.
3. Tất cả việc sử dụng SDK tuân theo nguyên tắc tối thiểu cần thiết.
