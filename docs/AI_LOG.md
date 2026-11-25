# Nhật ký kiểm tra và sử dụng AI

## 1. Kiểm tra website

**Ngày rà soát mã nguồn:** 25/11/2026

**Phạm vi:** tải stylesheet, giao diện ở màn hình 375 px và ảnh dự án.

| Mã | Trường hợp kiểm tra | Kết quả |
| --- | --- | --- |
| TC01 | Tải stylesheet trên `index.html` | ĐẠT - trình duyệt tải `css/styles.css` thành công |
| TC02 | Tải stylesheet trên `ket-qua.html` | ĐẠT - trình duyệt tải cùng `css/styles.css` thành công |
| TC03 | Kiểm tra tràn ngang ở viewport 375 px | ĐẠT - cả hai trang không tràn ngang |
| TC04 | Kiểm tra ảnh minh họa dự án | ĐẠT - cả ba ảnh SVG tải thành công |

### Ghi chú về kết quả kiểm tra trước đây

Nhật ký ngày 05/11/2026 từng ghi đường dẫn CSS là `css/style.css`. Tên file thực tế là `css/styles.css`; hai trang hiện sử dụng stylesheet dùng chung này. Các kết quả HTTP 200 và 304 được ghi ngày 05/11/2026 là kết quả lịch sử, chưa được kiểm tra lại trong lần rà soát này.

## 2. Nhật ký sử dụng AI trong Lab 8

| Ngày | Dùng AI làm gì | Em sửa lại gì |
| --- | --- | --- |
| 09/11/2026 | Hỗ trợ đọc hướng dẫn Lab 8, kiểm tra cấu trúc repository và chuẩn bị nội dung README, CHANGELOG, bảng minh chứng | Đối chiếu nội dung với mã nguồn và cấu trúc thực tế của Portfolio; kiểm tra lại các thông tin trước khi đưa vào repository |

### Cam kết

AI được sử dụng như công cụ hỗ trợ đọc tài liệu, rà soát cấu trúc và chuẩn bị nội dung. Người thực hiện có trách nhiệm kiểm tra, chỉnh sửa và xác nhận tính chính xác của các thông tin trước khi nộp bài.
