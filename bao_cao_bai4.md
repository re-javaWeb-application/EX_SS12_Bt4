# Báo cáo bài 4

---

Phần 1 - Phân tích: Spring Boot quản lý các cấu hình mặc định (Default Properties) như thế nào? Chúng ta có thể tìm thấy danh sách các cấu hình này ở đâu?

- Spring boot quản lý cấu hình thông qua triết lý (CoC - Convention over Configuration) ưu tiên quy ước hơn cấu hình, cho phéph ứng dụng chạy ngay mà không cần phải thiết lập nhiều
  
  - Spring Boot tự động tìm kiếm và load các file cấu hình (`application.properties` hoặc `application.yml`) (theo thứ tự ưu tiên giảm dần)
  - Nếu như có cả 2 file nói trên thì sẽ ưu tiên `application.properties` hơn

- Có thể tìm thấy các danh sách cấu hình này trên trang chủ của Spring Boot