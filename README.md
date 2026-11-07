# FarmBase website, bản mới (thử nghiệm, v3)

Bản dựng lại trang giới thiệu FarmBase để so sánh với website hiện tại.
Hoàn toàn độc lập: repo riêng, dự án Cloudflare Pages riêng, không dùng chung mã hay dữ liệu với site đang chạy.

## Cách dựng
- Hệ thống thiết kế tạo bằng skill **UI/UX Pro Max** (phong cách Organic Biophilic, xanh lá và vàng mùa vụ).
- Bố cục và chữ theo skill **Frontend Design** của Anthropic: hình ảnh chủ đạo là bản đồ thửa đất, font Be Vietnam Pro.
- Chuyển động theo bộ skill của **Emil Kowalski**: một màn mở đầu duy nhất, đường cong ease-out, hover chỉ trên thiết bị có chuột.
- Ảnh, ảnh chụp app, logo và video lấy từ repo website cũ (chỉ sao chép, đã nén lại) trong thư mục `assets/`.
- Trang tĩnh: `index.html` + `assets/`, không cần build.

## Motion graphic trong v3
- Hero: ranh thửa đất tự vẽ lên ảnh vườn thật, tia quét như flycam, ghim GPS rơi xuống, điện thoại tự đổi màn hình app.
- Số liệu đếm lên khi cuộn tới. Thanh tiến độ cuộn ở đầu trang.
- Công tắc Sổ giấy và FarmBase để so sánh.
- Phần cuộn kể chuyện: điện thoại đứng yên, màn hình đổi theo nông hộ, HTX, người mua.
- Sơ đồ dữ liệu có gói tin chạy từ vườn qua FarmBase tới hệ thống quốc gia, kiểm tra, người mua, xuất khẩu.
- Đường tiến độ 6 bước chạy theo cuộn, ảnh thực địa và logo chạy ngang.
- Tất cả tắt khi người dùng bật giảm chuyển động. Không dùng thư viện ngoài.

## Triển khai lên Cloudflare Pages
1. Cloudflare Dashboard > Workers & Pages > Create > Pages > Connect to Git.
2. Chọn repo này. Framework preset: None. Build command: để trống. Build output directory: `/`.
3. Deploy. Địa chỉ sẽ có dạng `<tên-repo>.pages.dev`.

## Việc còn lại
- Form tư vấn chưa nối máy chủ (bản cũ dùng Resend để gửi email).
- Chỉ có tiếng Việt, chưa có EN và 中文.
