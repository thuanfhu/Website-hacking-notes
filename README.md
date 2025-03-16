# 3.2. The Linux Terminal & Basic Linux Commands

## 1. Giới thiệu về Terminal
Terminal là một giao diện dòng lệnh (CLI - Command Line Interface) trong hệ điều hành Linux, cho phép người dùng nhập các lệnh để thực hiện các tác vụ như quản lý tệp, cài đặt phần mềm, và kiểm soát hệ thống.

## 2. Các lệnh cơ bản trong Linux

### 2.1. `pwd` (Print Working Directory)
Lệnh `pwd` hiển thị thư mục hiện tại mà người dùng đang làm việc.

**Cú pháp:**
```bash
pwd
```
**Ví dụ:**
```bash
/home/user
```

### 2.2. `ls` (List Directory Contents)
Lệnh `ls` liệt kê các tệp và thư mục trong thư mục hiện tại.

**Cú pháp:**
```bash
ls [tùy chọn] [đường dẫn]
```
**Ví dụ:**
```bash
ls -l
```
- `-l`: Hiển thị danh sách tệp theo định dạng chi tiết.
- `-a`: Hiển thị cả các tệp ẩn.

### 2.3. `man` (Manual Pages)
Lệnh `man` hiển thị tài liệu hướng dẫn sử dụng cho một lệnh trong Linux.

**Cú pháp:**
```bash
man [tên_lệnh]
```
**Ví dụ:**
```bash
man ls
```
Lệnh trên sẽ hiển thị hướng dẫn chi tiết về lệnh `ls`.

### 2.4. `apt-get update`
Lệnh `apt-get update` làm mới danh sách các gói phần mềm có sẵn từ các kho lưu trữ.

**Cú pháp:**
```bash
sudo apt-get update
```
Lệnh này không cài đặt hoặc cập nhật phần mềm mà chỉ cập nhật danh sách gói.

### 2.5. `apt-get install`
Lệnh `apt-get install` được sử dụng để cài đặt một gói phần mềm mới từ kho lưu trữ.

**Cú pháp:**
```bash
sudo apt-get install [tên_gói]
```
**Ví dụ:**
```bash
sudo apt-get install vim
```
Lệnh trên sẽ cài đặt trình soạn thảo Vim trên hệ thống.
