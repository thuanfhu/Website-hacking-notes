# 5.1. Gathering Information Using Whois Lookup

## 1. Giới thiệu
Quá trình thu thập thông tin (Information Gathering) là bước đầu tiên trong việc phân tích bảo mật một website. Bằng cách thu thập thông tin có sẵn về mục tiêu, ta có thể xác định điểm yếu tiềm ẩn và chuẩn bị cho các bước kiểm thử tiếp theo.

## 2. Các thông tin có thể thu thập
- **Địa chỉ IP** của website.
- **Thông tin tên miền** (chủ sở hữu, ngày đăng ký, ngày hết hạn,...).
- **Công nghệ được sử dụng** trên trang web (server, CMS, framework, v.v.).
- **Các website khác trên cùng một máy chủ**.
- **Bản ghi DNS** (MX, NS, TXT,...).
- **Các tệp tin chưa được liệt kê**, **các sub-domain** và **thư mục ẩn**.

## 3. Công cụ thu thập thông tin
### 3.1. Whois Lookup
- **Mô tả**: Whois là một giao thức giúp tìm kiếm thông tin về chủ sở hữu của một tên miền.
- **Công cụ:** [Whois Lookup](<http://whois.domaintools.com/>)
- **Thông tin thu thập được:**
  - Tên chủ sở hữu tên miền.
  - Ngày đăng ký và ngày hết hạn tên miền.
  - Nhà cung cấp dịch vụ đăng ký tên miền.
  - Địa chỉ IP của máy chủ.

### 3.2. Netcraft Site Report
- **Mô tả**: Công cụ Netcraft giúp xác định công nghệ được sử dụng trên một trang web.
- **Công cụ:** [Netcraft Site Report](<http://toolbar.netcraft.com/site_report?url=>)
- **Thông tin thu thập được:**
  - Máy chủ web (Apache, Nginx, IIS,...).
  - Frameworks và CMS sử dụng (WordPress, Joomla, Drupal,...).
  - Chứng chỉ SSL và thông tin bảo mật.

### 3.3. Robtex DNS Lookup
- **Mô tả**: Robtex giúp thu thập thông tin DNS chi tiết về mục tiêu.
- **Công cụ:** [Robtex DNS Lookup](<https://www.robtex.com/>)
- **Thông tin thu thập được:**
  - Các bản ghi DNS (A, MX, NS, TXT,...).
  - Mối quan hệ giữa các tên miền và máy chủ.
  - Thông tin về hạ tầng mạng của website.

## 4. Kết luận
Việc thu thập thông tin là bước quan trọng trong bảo mật mạng. Bằng cách sử dụng các công cụ như Whois, Netcraft và Robtex, ta có thể thu thập thông tin chi tiết về mục tiêu, từ đó đánh giá các điểm yếu có thể bị khai thác.