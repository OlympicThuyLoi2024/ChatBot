# ChatBot
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)

Nạp dữ liệu, phân tích, trainning cho chat bot AI của hệ thống SafeZone bằng nền tảng công nghệ LCDP n8n.

## Changelogs

### v1.0
- Nạp dữ liệu.
- Chuyển hóa dữ liệu.
- Trainning dữ liệu.
- Nhận và gửi trả câu trả lời cho chat bot AI. 

## Hướng dẫn cài đặt
### 1. Yêu cầu hệ thống  
- **Tài khoản OpenAI**: Để sử dụng mô hình tạo embedding.  
- **Tài khoản Pinecone**: Để lưu trữ và truy vấn vector.
- [**N8N**](https://n8n.io/): Phiên bản >=1.66.0

### 2. Cài đặt dữ án
#### Bước 1: Tải mã nguồn từ bản phát hành
1. Truy cập trang phát hành chính thức tại: [Releases](https://github.com/trungthanhcva2206/Service-ChatBot/releases).
2. Chọn phiên bản phù hợp với nhu cầu của bạn.
3. Trong phần **Assets**, tải tệp:
   - `Source code (zip)` hoặc
   - `Source code (tar.gz)`.

#### Bước 2: Giải nén và truy cập thư mục
```bash
# Giải nén file đã tải
unzip Service-ChatBot.zip
cd Service-ChatBot
```
#### Bước 3: Import vô N8N 
1. Tạo 1 workflow trong N8N
2. Import file Agent.json, file này lấy được ở trong thư mục Service-ChatBot

#### Bước 4: Chỉnh sửa các tài khoản dịch vụ
Ở trong các node OpenAI, Pinecone sẽ có phần **Credential to connect with**, có thể chỉnh sửa các tài khoản dịch vụ của mình ở đây. 

## Đóng góp cho dự án

<a href="https://github.com/OlympicThuyLoi2024/GiaoDienUser/issues/new?assignees=&labels=&projects=&template=bug_report.md&title=BUG">Bug Report ⚠️
</a>

<a href="https://github.com/OlympicThuyLoi2024/GiaoDienUser/issues/new?assignees=&labels=&projects=&template=feature_template.md&title=Feature">Request Feature 👩‍💻</a>

Nếu bạn muốn đóng góp cho dự án, hãy đọc [CONTRIBUTING.md](.github/CONTRIBUTING.md) để tìm hiểu thêm chi tiết.

Chúng tôi rất trân trọng mọi đóng góp từ các bạn. Đừng ngần ngại tạo pull request và gửi đến dự án.

## Tác giả
- Nguyễn Lê Trung Thành
- Trần Tuấn Anh
- Lê Văn Quang

# License
Phần mềm sử dụng License  [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
