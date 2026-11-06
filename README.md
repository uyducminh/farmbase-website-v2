# FarmBase website, bản mới (thử nghiệm)

Bản dựng lại trang giới thiệu FarmBase để so sánh với website hiện tại.
Hoàn toàn độc lập: repo riêng, dự án Cloudflare Pages riêng, không dùng chung mã hay dữ liệu với site đang chạy.

## Cách dựng
- Hệ thống thiết kế tạo bằng skill **UI/UX Pro Max** (phong cách Organic Biophilic, xanh lá và vàng mùa vụ).
- Bố cục và chữ theo skill **Frontend Design** của Anthropic: hình ảnh chủ đạo là bản đồ thửa đất, font Be Vietnam Pro.
- Một file `index.html` tĩnh, không cần build.

## Triển khai lên Cloudflare Pages
1. Cloudflare Dashboard > Workers & Pages > Create > Pages > Connect to Git.
2. Chọn repo này. Framework preset: None. Build command: để trống. Build output directory: `/`.
3. Deploy. Địa chỉ sẽ có dạng `<tên-repo>.pages.dev`.

## Việc còn lại
- Form tư vấn chưa nối máy chủ (bản cũ dùng Resend để gửi email).
- Chỉ có tiếng Việt, chưa có EN và 中文.
- Chưa có ảnh thật và video giới thiệu.
