# Thiết lập HoneyPot sử dụng Azure Sentinel 
Trong bối cảnh an toàn thông tin ngày càng được đặt lên hàng đầu khi mà môi trường mạng toàn cầu liên tục phát sinh các mối đe dọa mới, việc áp dụng các giải pháp phòng thủ chủ động là điều cần thiết đối với các tổ chức và cá nhân. Một trong những công cụ hiệu quả được nghiên cứu và ứng dụng rộng rãi hiện nay là honeypot.
Honeypot, hay hệ thống mồi nhử, là một giải pháp an ninh mạng đặc biệt giúp cho các nhà nghiên cứu và chuyên gia an ninh hiểu rõ hơn về cách thức tấn công của tin tặc. Thông qua việc “bẫy” các cuộc tấn công, honeypot không chỉ cung cấp thông tin giá trị về hành vi của kẻ xâm nhập mà còn giúp triển khai các biện pháp bảo vệ hệ thống thật một cách hiệu quả.
## HoneyPot
"Mật ngọt thì chết ruồi"
### HoneyPot là gì?
Honeypot là một hệ thống máy tính hoặc một tài nguyên thông tin được thiết lập với mục đích làm mồi nhử cho các kẻ hacker xâm nhập bất hợp pháp. Khi hacker tấn công vào hệ thống này, họ sẽ không nhận ra rằng mình đang hack vào môi trường giả lập, không thu được thông tin giá trị nào. Thay vào đó, các kỹ sư an ninh mạng sẽ ghi nhận hành vi, địa chỉ, động cơ tấn công của chúng để phân tích và nâng cấp, cải thiện hệ thống chính, giúp tăng cường bảo mật.
### Nguyên lý hoạt động
Honeypot hoạt động dựa trên cơ chế “lừa đập” tin tặc vào một hệ thống được thiết kế có sẵn các lỗ hổng bảo mật hoặc cấu hình kém để dễ bị tấn công. Mục tiêu của hệ thống này là thu hút sự xâm nhập từ tin tặc, cho phép thu thập các dữ liệu như:

  - Phương thức tấn công: Các công cụ, script và thủ thuật mà tin tặc sử dụng.
    + Hành vi xâm nhập: Thời gian, tần suất và các bước triển khai cuộc tấn công.
    + Thông tin thu thập: Tên người dùng, mật khẩu, mã độc và các lỗ hổng được khai thác.
      
  - Khi honeypot ghi nhận được thông tin này, các chuyên gia an ninh có thể:
    + Phân tích và nghiên cứu các phương thức tấn công để cải thiện hệ thống phòng thủ của tổ chức.
    + Phát hiện sớm các mối đe dọa và ngăn chặn kịp thời các cuộc tấn công vào hệ thống thực.
### Phân loại HoneyPot
    
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
