# 4.2. How To Hack a Website?

## 1. Giới thiệu
Một trang web là một ứng dụng chạy trên máy tính (máy chủ). Việc tấn công một trang web có thể được phân loại theo ba cấp độ chính: tấn công ứng dụng web, tấn công phía máy chủ và tấn công phía khách hàng.

## 2. Các phương pháp tấn công website

### 2.1. Web Application Pentesting (Kiểm thử thâm nhập ứng dụng web)
- **Mô tả:** Một trang web thực chất là một ứng dụng chạy trên máy chủ web. Nếu ứng dụng này có lỗ hổng bảo mật, tin tặc có thể khai thác để tấn công.
- **Các kỹ thuật phổ biến:**
  - **SQL Injection:** Chèn mã SQL độc hại để truy xuất hoặc thao túng cơ sở dữ liệu.
  - **Cross-Site Scripting (XSS):** Chèn mã JavaScript độc hại để tấn công người dùng.
  - **Insecure Direct Object References (IDOR):** Truy cập trái phép vào dữ liệu nhạy cảm.

### 2.2. Server Side Attacks (Tấn công phía máy chủ)
- **Mô tả:** Máy chủ chạy hệ điều hành và các phần mềm hỗ trợ như web server, database server, và firewall. Nếu tin tặc khai thác lỗ hổng trong các thành phần này, họ có thể kiểm soát toàn bộ máy chủ.
- **Các kỹ thuật phổ biến:**
  - **Remote Code Execution (RCE):** Thực thi mã độc từ xa để kiểm soát máy chủ.
  - **Privilege Escalation:** Leo thang đặc quyền để chiếm quyền điều khiển.
  - **Denial of Service (DoS/DDoS):** Làm tê liệt máy chủ bằng cách gửi lượng lớn yêu cầu.

### 2.3. Client Side Attacks (Tấn công phía người dùng)
- **Mô tả:** Người dùng tương tác với website thông qua trình duyệt web. Nếu website có lỗ hổng, tin tặc có thể khai thác để tấn công người dùng.
- **Các kỹ thuật phổ biến:**
  - **Phishing:** Tạo trang web giả mạo để đánh cắp thông tin người dùng.
  - **Session Hijacking:** Chiếm quyền điều khiển phiên đăng nhập của người dùng.
  - **Man-in-the-Middle (MitM):** Chặn và thay đổi dữ liệu truyền giữa người dùng và máy chủ.

## 3. Kết luận
Bảo mật web là một lĩnh vực quan trọng trong an ninh mạng. Việc hiểu rõ các phương pháp tấn công giúp lập trình viên và quản trị viên hệ thống bảo vệ website tốt hơn. Nếu bạn muốn kiểm thử bảo mật web, hãy sử dụng các công cụ và kỹ thuật hợp pháp trong môi trường kiểm thử có sự cho phép.