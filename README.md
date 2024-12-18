# I. Giới thiệu dự án
- Dự án này nhằm tạo một Operational Dashboard nhằm **phân tích tệp khách hàng hiện có của một công ty ngành tài chính**, việc phân tích hướng đến mục đích hiểu rõ chân dung, nhu cầu, tình trạng, mong muốn của khách hàng nhằm đưa ra quyết định cho các chiến lược Marketing sắp tới để **thu hút thêm khách hàng mới trong việc vay tín dụng**
- Công cụ sử dụng trong dự án này là Excel

# Dataset
Dataset chứa thông tin chi tiết về khách hàng và các khoản vay tín dụng của một công ty tài chính. Dưới đây là mô tả từng cột trong dữ liệu:
![image](https://github.com/user-attachments/assets/db1f894d-d6ab-47ad-8767-78745305c685)


# Dashboard
![image](https://github.com/user-attachments/assets/86958822-89ca-4b7f-878d-605498d470b8)


# Phân tích 
## 1. Phân tích nhân khẩu học

![image](https://github.com/user-attachments/assets/680d4b0e-8f66-4431-a431-5ce6e96e366f)

### Tổng quan: 
- Giới tính: Nam chiếm ưu thế với 67%, trong khi nữ chỉ chiếm 33%. Điều này cho thấy nhu cầu vay chủ yếu đến từ nam giới.
- Nhóm tuổi: Nhóm tuổi trên 25 chiếm phần lớn (70%), trong khi nhóm 22-25 tuổi chỉ chiếm 30%.
- Loại thu nhập: 78% khách hàng có thu nhập không cố định, cho thấy nhu cầu vay chủ yếu từ các đối tượng không ổn định về tài chính. Nhóm thu nhập cố định chỉ chiếm 22%, là nhóm vay ít hơn.
- Vị trí địa lý: Miền Nam chiếm phần lớn với 48% số khách hàng, tiếp theo là Miền Bắc (45%) và Miền Trung (7%). 
- Ngành nghề: 79% không rõ ngành nghề - Đây đều nằm trong nhóm có loại thu nhập không ổn định. Trong số ngành nghề rõ ràng, Manufacturing (10%) là nhóm ngành chiếm tỷ lệ lớn nhất, tiếp theo là Bán buôn/Bán lẻ (3%), Hỗ trợ hành chính (3%), và Ngân hàng, tài chính (3%).

Đi sâu vào nhóm khách hàng có thu nhập không cố định (chiếm tỷ lệ 78%) thì thấy khách hàng cũng chủ yếu đến từ Miền Bắc và Miền Nam
![image](https://github.com/user-attachments/assets/f32e809c-ea12-4706-af56-917e3bf175a4)

## 2. Nguồn khách hàng và thời điểm khách hàng vay
### Thời điểm vay:
![image](https://github.com/user-attachments/assets/738f69ec-13e3-43ba-ae70-05fa409925b5)

- Phần lớn hợp đồng vay rơi vào cuối tháng (81 hợp đồng), cho thấy đây là thời điểm khách hàng cần tài chính nhiều nhất.
- Đầu tháng (19 hợp đồng) và giữa tháng (1 hợp đồng) có số lượng vay thấp hơn rõ rệt.

### Nguồn khách hàng:
![image](https://github.com/user-attachments/assets/8aa82090-07e7-42dd-b60a-51d4a289de93)

- Khách hàng tiếp cận chủ yếu qua các kênh Tiktok (24%) và Google (24%).
- Facebook (20%), Organic (17%), và EDM (16%) cũng đóng góp một phần đáng kể.
- Tiktok và Google là những kênh quảng cáo hiệu quả nhất trong chiến dịch tiếp cận khách hàng.

## 3. Top 5 thành phố vay nhiều nhất và Top 5 mục đích vay
Top 5 thành phố vay nhiều nhất:

![image](https://github.com/user-attachments/assets/9463fcd5-0a65-42bd-a446-5d54555327fc)

- TP. Hồ Chí Minh dẫn đầu với tổng giá trị vay 480.5 triệu đồng, khẳng định đây là thị trường lớn nhất.
- Hà Nội (343 triệu đồng) đứng thứ hai, tiếp theo là Đồng Nai (262 triệu đồng).
- Thái Nguyên (218.5 triệu đồng) và Bình Dương (145 triệu đồng) cũng có nhu cầu vay đáng kể.

Top 5 mục đích vay:

![image](https://github.com/user-attachments/assets/5062ca39-5df3-4b3b-81f0-81f1f8cbecd1)

- 89% khách hàng không rõ mục đích vay, cho thấy việc thu thập thông tin từ khách hàng chưa hiệu quả.
- Mục đích phổ biến khác bao gồm: Mua trang thiết bị gia đình (6%), Sửa chữa nhà ở (4%), và Mua phương tiện đi lại (2%).
- Tỷ lệ khách hàng có mục đích vay cụ thể còn thấp.

# Khuyến nghị 
## 1. Tối ưu hóa kênh tiếp cận
- Tăng ngân sách quảng cáo trên TikTok và Google Ads: Đây là hai kênh hiệu quả nhất, chiếm 48% lượng khách hàng tiếp cận. Tăng cường chiến dịch video ngắn trên TikTok, tập trung vào nội dung liên quan đến nhu cầu tài chính của nam giới và nhóm khách hàng có thu nhập không ổn định. Tuy nhiên, tuỳ vào mục đích MKT, nếu cần tăng lượng traffic, phủ sóng thương hiệu/sản phẩm thì chọn kênh Tiktok. Còn nếu muốn tăng khách hàng lead thì đẩy mạnh quảng cáo Google Ads
- Tuỳ vào vùng miền tiếp cận - nếu là miền Bắc thì quảng cáo Google là một kênh tiếp cận hiệu quả hơn:
  
![image](https://github.com/user-attachments/assets/fdd9c312-c828-476c-b25b-9c75488eaa1a)

- Facebook và EDM (Email Marketing): Duy trì các chiến dịch retargeting và remarketing qua Facebook để tái tiếp cận khách hàng cũ. EDM có thể được cải thiện bằng cách cá nhân hóa nội dung dựa trên dữ liệu khách hàng.
## 2. Tập trung vào thời điểm chiến dịch
- Chạy quảng cáo mạnh vào cuối tháng: Tập trung ngân sách trong tuần cuối tháng, vì đây là thời điểm nhu cầu vay cao nhất (81 hợp đồng). Đảm bảo chiến dịch đạt đến khách hàng ngay trước giai đoạn họ có nhu cầu cấp thiết.
- Triển khai chương trình khuyến mãi để kích thích nhu cầu vay trong thời gian thấp điểm (đầu và giữa tháng), ví dụ như giảm phí dịch vụ hoặc tăng ưu đãi cho khách hàng sớm.
  
![image](https://github.com/user-attachments/assets/7fcb587e-3e19-4602-99c7-39e27cc1a33b)



## 3. Thông điệp quảng cáo
- Tập trung vào nhóm khách hàng nam và nhóm tuổi trên 25: Đưa ra các thông điệp như: "Vay tiêu dùng dễ dàng, giải pháp tài chính linh hoạt cho mọi nhu cầu cuối tháng."
- Nhu cầu tài chính cấp thiết: Đánh mạnh vào thông điệp giải quyết tài chính khẩn cấp với thời gian duyệt vay nhanh vì phần lớn khách hàng không có mục đích vay
  
![image](https://github.com/user-attachments/assets/4069054b-00cf-4520-9801-fcd1d9149847)


