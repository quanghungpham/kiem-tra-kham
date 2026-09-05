# Tool kiểm tra danh sách khám

Web app HTML chạy trực tiếp trên GitHub Pages.

## Cấu trúc

- `index.html` — ứng dụng chính
- `files/TongHop2.xlsx` — file mẫu Danh sách tổng
- `files/DaKham111.xlsx` — file mẫu Danh sách đã khám

## Chạy GitHub Pages

1. Tạo một repository GitHub mới.
2. Upload toàn bộ nội dung thư mục này vào repository.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**.
5. Chọn branch `main` và thư mục `/ (root)`.
6. Lưu lại và mở URL GitHub Pages được cấp.

Sau khi deploy, các nút tải file mẫu sẽ lấy file từ `files/` trên chính website, không cần đặt Excel cạnh file HTML trên máy người dùng.

## Cập nhật

Chỉ cần sửa `index.html` và commit/push lên GitHub. GitHub Pages sẽ cập nhật phiên bản mới sau khi deploy.

> Ứng dụng sử dụng SheetJS từ CDN `jsdelivr`, nên trình duyệt cần Internet để tải thư viện đọc/ghi Excel.
