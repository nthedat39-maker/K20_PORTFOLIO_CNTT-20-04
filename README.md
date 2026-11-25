# Portfolio CV - Nguyễn Thế Đạt

Website portfolio cá nhân giới thiệu thông tin, kỹ năng, các dự án học tập và biểu mẫu liên hệ. Dự án được xây dựng bằng HTML, CSS và JavaScript, phù hợp để xem trên máy tính và thiết bị di động.

## Demo

- **Website:** [Portfolio](https://nthedat39-maker.github.io/K20_PORTFOLIO_CNTT-20-04/)
- **Trang kết quả liên hệ:** [Kết quả](https://nthedat39-maker.github.io/K20_PORTFOLIO_CNTT-20-04/ket-qua.html)
- **Mã nguồn:** [GitHub repository](https://github.com/nthedat39-maker/K20_PORTFOLIO_CNTT-20-04)

## Giới thiệu

Trang chính được tổ chức thành các phần Giới thiệu, Kỹ năng, Dự án và Liên hệ. Thanh điều hướng giúp người xem chuyển nhanh đến từng phần. Nội dung tập trung vào hồ sơ cá nhân, các kỹ năng đang học và một số sản phẩm thực hành.

## Tính năng

- **Thông tin cá nhân:** giới thiệu bản thân, quê quán, sở thích và mục tiêu nghề nghiệp.
- **Kỹ năng:** trình bày các nội dung Git/GitHub, HTML/CSS và VPN.
- **Dự án:** giới thiệu portfolio cá nhân, website du lịch Hà Nội và trang tổng hợp game yêu thích kèm hình minh họa SVG.
- **Giao diện thích ứng:** bố cục sử dụng CSS Grid, Flexbox và media queries để điều chỉnh theo kích thước màn hình.
- **Biểu mẫu liên hệ:** thu thập họ tên, email và nội dung liên hệ; số điện thoại là trường không bắt buộc.
- **Trang kết quả:** hiển thị danh sách thông tin đã gửi, số lượng phản hồi và cung cấp thao tác xóa danh sách có xác nhận.

### Cách hoạt động của biểu mẫu

Thông tin biểu mẫu được lưu trong `localStorage` của trình duyệt, không gửi đến máy chủ. Vì vậy, dữ liệu chỉ có trong cùng trình duyệt và hồ sơ người dùng trên thiết bị đã gửi thông tin; mở website trên thiết bị hoặc trình duyệt khác sẽ không tự động thấy dữ liệu đó. Trang `ket-qua.html` đọc dữ liệu này để hiển thị các phản hồi.

## Công nghệ

- **HTML5:** cấu trúc và nội dung trang.
- **CSS3:** màu sắc, bố cục, hiệu ứng và giao diện thích ứng.
- **JavaScript:** xử lý biểu mẫu liên hệ, lưu trữ và hiển thị dữ liệu.
- **Web Storage API (`localStorage`):** lưu dữ liệu liên hệ trên trình duyệt.
- **SVG:** hình minh họa cho các dự án.
- **GitHub Pages:** xuất bản website tĩnh.

## Chạy dự án trên máy

Dự án không cần cài thư viện hay chạy bước build:

1. Tải repository về máy hoặc sao chép mã nguồn.
2. Mở `index.html` bằng trình duyệt web hiện đại.
3. Dùng liên kết **Kết quả** trên thanh điều hướng hoặc mở `ket-qua.html` để xem trang kết quả liên hệ.

Để thử biểu mẫu, nhập họ tên, email và nội dung liên hệ rồi gửi. Sau đó mở trang kết quả trong cùng trình duyệt. Dữ liệu thử nghiệm có thể xóa bằng chức năng xóa trên trang kết quả.

## Cấu trúc repository

```text
.
├── index.html                 # Trang portfolio và biểu mẫu liên hệ
├── ket-qua.html               # Trang hiển thị kết quả liên hệ
├── css/
│   └── styles.css             # Tệp định dạng CSS
├── assets/                    # Hình minh họa SVG cho dự án
├── docs/
│   ├── AI_LOG.md              # Nhật ký kiểm tra và sử dụng AI
│   ├── envidence-index.md     # Danh mục minh chứng
│   └── envidence/             # Ảnh chụp màn hình minh chứng
├── CHANGELOG.md               # Lịch sử thay đổi
└── REALEAS_NOTES.md           # Ghi chú phát hành
```

## Tài liệu và minh chứng

- [Changelog](CHANGELOG.md): lịch sử thay đổi theo phiên bản.
- [Release notes](REALEAS_NOTES.md): ghi chú phát hành V7 và V8.
- [Danh mục minh chứng](docs/envidence-index.md): các trang, tài liệu và ảnh chụp liên quan.
- [Nhật ký kiểm tra và sử dụng AI](docs/AI_LOG.md).
- Ảnh chụp: [Trang Portfolio](docs/envidence/portfolio-home.png) · [Trang kết quả](docs/envidence/contact-results.png).

