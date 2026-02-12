# Chính sách quyền riêng tư

**Cập nhật lần cuối: 5 tháng 1 năm 2026**
**Ngày có hiệu lực: 5 tháng 1 năm 2026**

## Giới thiệu

Chúng tôi hiểu tầm quan trọng của thông tin cá nhân đối với bạn. Chúng tôi sẽ bảo vệ bảo mật thông tin cá nhân của bạn theo luật pháp và quy định. Chính sách này tuân thủ Quy định bảo vệ dữ liệu chung của EU (GDPR), Đạo luật quyền riêng tư người tiêu dùng California (CCPA) và các luật bảo vệ dữ liệu hiện hành khác.

> **TUYÊN BỐ QUAN TRỌNG**: Đây là ứng dụng thuần túy cục bộ và sẽ không tải bất kỳ dữ liệu nào của bạn lên máy chủ. Tất cả thông tin được lưu trữ cục bộ trên thiết bị của bạn.

## 1. Bên kiểm soát dữ liệu

NetPulse được vận hành bởi một nhà phát triển độc lập.
Email liên hệ: zjccc5889@gmail.com

## 2. Thông tin chúng tôi thu thập và cơ sở pháp lý

**Cơ sở pháp lý (GDPR Điều 6):**
- **Thực hiện hợp đồng**: Cần thiết để cung cấp dịch vụ chẩn đoán mạng bạn yêu cầu
- **Lợi ích hợp pháp**: Để cải thiện trải nghiệm ứng dụng (chúng tôi đã tiến hành đánh giá cân bằng)

### 2.1 Thông tin thiết bị (đọc cục bộ để hiển thị)
- Tên thiết bị, model thiết bị
- Phiên bản hệ điều hành
- Mã định danh thiết bị (mã định danh model, không phải IDFA/IDFV)
- Mức pin, trạng thái pin
- Dung lượng ổ đĩa, sử dụng bộ nhớ

### 2.2 Thông tin mạng (đọc cục bộ để chẩn đoán mạng)
- Địa chỉ IP cục bộ (IPv4/IPv6)
- Loại mạng (WiFi/2G/3G/4G/5G)
- Trạng thái kết nối mạng

### 2.3 Dữ liệu sử dụng (lưu trữ cục bộ)
- Lịch sử mục tiêu Ping
- Lịch sử truy vấn DNS
- Lịch sử phát hiện cổng TCP/UDP
- Lịch sử Traceroute
- Lịch sử yêu cầu HTTP
- Lịch sử kiểm tra kết nối
- Lịch sử chẩn đoán nhanh
- Lịch sử truy vấn IP

### 2.4 Mã định danh người dùng (tạo cục bộ)
- ID khách (tạo ngẫu nhiên, chỉ sử dụng để nhận dạng cục bộ)

## 3. Cách chúng tôi sử dụng thông tin

### 3.1 Cung cấp dịch vụ
- Thực hiện các tác vụ thăm dò mạng (Ping, DNS, TCP, UDP, Traceroute, v.v.)
- Hiển thị kết quả thăm dò
- Cung cấp dịch vụ chẩn đoán nhanh
- Thực hiện kiểm tra tốc độ và độ trễ

### 3.2 Cải thiện trải nghiệm
- Lưu lịch sử để chọn nhanh
- Hiển thị thông tin môi trường mạng thiết bị

## 4. Lưu trữ và bảo mật thông tin

1. **Vị trí lưu trữ**: Cục bộ trên thiết bị của bạn (UserDefaults)
2. **Thời gian lưu trữ**: Cho đến khi bạn xóa lịch sử hoặc gỡ cài đặt ứng dụng
3. Chúng tôi sẽ không tải bất kỳ dữ liệu nào lên máy chủ
4. **Biện pháp bảo mật**: Dữ liệu chỉ được lưu trữ trên thiết bị của bạn, được bảo vệ bởi sandbox hệ thống iOS

## 5. Dịch vụ bên thứ ba và chuyển dữ liệu quốc tế

Ứng dụng này sử dụng các dịch vụ mạng bên thứ ba sau để định vị IP. Khi sử dụng các dịch vụ này, địa chỉ IP của bạn có thể được chuyển ra nước ngoài:

### 5.1 Dịch vụ truy vấn IP NetEase (mail.163.com)
- **Nhà cung cấp**: NetEase, Inc. (Trung Quốc)
- **Chức năng**: Lấy địa chỉ IP công cộng và vị trí địa lý của thiết bị hiện tại
- **Dữ liệu gửi**: Yêu cầu mạng (tự động gửi IP công cộng)
- **Dữ liệu trả về**: Địa chỉ IP công cộng, quốc gia, tỉnh, thành phố, ISP

### 5.2 Dịch vụ truy vấn IP Bilibili (api.live.bilibili.com)
- **Nhà cung cấp**: Bilibili Inc. (Trung Quốc)
- **Chức năng**: Truy vấn vị trí địa lý của IP được chỉ định
- **Dữ liệu gửi**: Địa chỉ IP để truy vấn
- **Dữ liệu trả về**: Quốc gia, tỉnh, thành phố, ISP, tọa độ

### 5.3 Dịch vụ truy vấn ASN ipinfo.io (api.ipinfo.io)
- **Nhà cung cấp**: IPinfo Inc. (Hoa Kỳ)
- **Chức năng**: Truy vấn số AS (Số hệ thống tự trị) của IP
- **Dữ liệu gửi**: Địa chỉ IP để truy vấn
- **Dữ liệu trả về**: Số AS, tên AS, quốc gia
- **Bảo vệ chuyển quốc tế**: Dịch vụ này tuân thủ yêu cầu GDPR

## 6. Chia sẻ thông tin

Ngoài truy vấn vị trí IP, chúng tôi sẽ không chia sẻ thông tin cá nhân của bạn với bất kỳ bên thứ ba nào. Chúng tôi không bán dữ liệu cá nhân của bạn.

## 7. Quyền của bạn

Theo GDPR, CCPA và các luật hiện hành khác, bạn có các quyền sau:

1. **Quyền truy cập**: Bạn có quyền nhận bản sao dữ liệu cá nhân chúng tôi nắm giữ về bạn
2. **Quyền chỉnh sửa**: Bạn có quyền yêu cầu sửa dữ liệu không chính xác
3. **Quyền xóa (Quyền được quên)**: Bạn có thể xóa tất cả lịch sử trong ứng dụng hoặc xóa tất cả dữ liệu bằng cách gỡ cài đặt
4. **Quyền hạn chế xử lý**: Bạn có quyền yêu cầu hạn chế xử lý dữ liệu
5. **Quyền di chuyển dữ liệu**: Bạn có quyền nhận dữ liệu của mình ở định dạng có cấu trúc
6. **Quyền phản đối**: Bạn có quyền phản đối việc xử lý dựa trên lợi ích hợp pháp
7. **Quyền rút lại sự đồng ý**: Bạn có thể rút lại sự đồng ý bất cứ lúc nào
8. **Quyền khiếu nại**: Bạn có quyền nộp đơn khiếu nại lên cơ quan bảo vệ dữ liệu

### Quyền bổ sung cho cư dân California (CCPA)
- **Quyền được biết**: Hiểu các danh mục thông tin cá nhân chúng tôi thu thập
- **Quyền từ chối bán**: Chúng tôi không bán thông tin cá nhân
- **Quyền không phân biệt đối xử**: Bạn sẽ không bị đối xử phân biệt khi thực hiện quyền riêng tư

Để thực hiện quyền của bạn, vui lòng liên hệ: zjccc5889@gmail.com

## 8. Bảo vệ trẻ vị thành niên

Dịch vụ này chủ yếu dành cho người lớn. Chúng tôi không cố ý thu thập thông tin cá nhân từ trẻ em dưới 13 tuổi. Nếu bạn là trẻ vị thành niên, vui lòng sử dụng dưới sự hướng dẫn của người giám hộ.

## 9. Cập nhật chính sách

Chúng tôi có thể cập nhật Chính sách quyền riêng tư này. Đối với các thay đổi quan trọng, chúng tôi sẽ thông báo cho bạn thông qua thông báo trong ứng dụng. Việc tiếp tục sử dụng Dịch vụ có nghĩa là bạn chấp nhận chính sách cập nhật.

## 10. Liên hệ chúng tôi

Nếu bạn có bất kỳ câu hỏi, khiếu nại hoặc muốn thực hiện quyền dữ liệu của mình, vui lòng liên hệ:
**Email**: zjccc5889@gmail.com

Nếu bạn cho rằng chúng tôi chưa giải quyết thỏa đáng các mối quan ngại về dữ liệu của bạn, bạn có quyền nộp đơn khiếu nại lên cơ quan bảo vệ dữ liệu trong khu vực pháp lý của bạn.
