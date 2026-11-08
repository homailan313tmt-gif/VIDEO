# Mẫu chuyển cảnh cho một lẵng hoa

Video minh họa dài 12,58 giây, khổ 9:16. Dùng nhạc tách từ ref bạn gửi và lẵng hoa đỏ–trắng đã clean trước đó. Ba file C5308, C5310, C5314 chưa được sử dụng vì chưa tải được. Đây là video minh họa và công thức dựng lại, không phải file dự án CapCut hay mẫu một chạm trên CapCut.

## Công thức hình ảnh

**Toàn lẵng → tiến gần → hai ô chi tiết → một cận ngang → hai ô mới → toàn lẵng → lời nhắn → tên shop.**

Chỉ cần một lẵng hoa. Các ô khác nhau là các góc hoặc chi tiết của cùng sản phẩm. Giữ nền trắng ngà `#FAFAFA`, chữ tối `#242422`, sắc hoa tự nhiên. Các ô có góc vuông; khe trắng giữa hai ô khoảng 10 px trên khung 1080 × 1920. Không cần viền hoặc bóng cho khung ảnh.

## Chuẩn bị source

- **A — Toàn lẵng:** thấy trọn dáng, chân bình và một ít nền; quay đứng 3–4 giây, máy tiến rất nhẹ.
- **B — Cận hoa chính:** bông đẹp nhất, đặt chủ thể gần giữa khung; quay 3–4 giây.
- **C — Chi tiết phụ:** cánh hoa, nhánh rủ, nơ, tay hoàn thiện hoặc chân bình; quay 3–4 giây.
- Nếu chỉ có một clip 4K: nhân bản rồi crop thành B/C như video minh họa này. Hạn chế crop quá sâu để giữ độ nét.

## Timeline để đặt mốc trong CapCut

| Thời gian | Hình cần đặt | Bố cục trên khung 1080 × 1920 | Chuyển động |
|---|---|---|---|
| 0–1,375 s | A: toàn lẵng | Khung dọc 760 × 1270; tên shop nhỏ phía trên | Zoom nhẹ 100 → 101,8% |
| 1,375–2,917 s | A: crop gần hơn | Khung dọc 880 × 1250, căn giữa | Giữ hướng chuyển động của cảnh trước |
| 2,917–4,958 s | B phía trên, C phía dưới | Khung tổng 960 × 1250; mỗi ô 960 × 620; khe 10 px | Hai chi tiết chuyển động chậm |
| 4,958–7,083 s | B: macro hoa đẹp nhất | Một khung ngang 984 × 670, căn giữa | Zoom 100 → 103,5%; đây là khoảng nghỉ |
| 7,083–8,167 s | Cánh hoa phía trên; nơ/chân bình phía dưới | Hai ô như đoạn trước | Đổi chi tiết, giữ cùng màu hoa |
| 8,167–9,500 s | A: góc toàn đẹp nhất | Khung dọc lớn 948 × 1515 | Zoom nhẹ, thấy được tổng thể |
| 9,500–10,500 s | “Thương gửi.” | Chữ nhỏ giữa nền trắng | Hiện mềm; có thể thay bằng 2–3 từ |
| 10,500–12,582 s | Tên shop | Wordmark giữa khung; một dòng phụ tùy chọn | Giữ đủ lâu để đọc; nền trắng đến hết nhạc |

Ở chế độ 60 fps, mốc sẽ được làm tròn đến khung hình gần nhất. Mốc `1,375 s` là khoảng 1,38 giây, không phải mã thời gian phút:giây:frame.

## Dựng trong CapCut

1. Tạo dự án **1080 × 1920**. Thêm một nền trắng ngà dài **12,58 giây** làm nền. Thêm nhạc của ref bằng chức năng trích xuất âm thanh từ video; đặt bắt đầu ở 0. Tắt tiếng các source hoa.
2. Đặt marker ở các mốc trong bảng. Đưa source hoa vào các lớp phủ/overlay trên nền trắng, cắt mỗi lớp theo các mốc này. Làm trên overlay để thay bố cục mà không kéo lệch toàn bộ nhịp nhạc.
3. Với cảnh đơn: crop source, dùng mặt nạ hình chữ nhật hoặc khung crop rồi thu nhỏ cả khung vào giữa nền. Căn theo kích thước tương đối trong bảng. Giữ phần bông đẹp nằm trong vùng an toàn của khung.
4. Với cảnh hai ô: tạo hai overlay độc lập có cùng thời điểm bắt đầu/kết thúc. Crop mỗi overlay thành hình ngang; đặt một ô trên, một ô dưới. Khe trắng chỉ khoảng 1% chiều ngang video.
5. Đặt keyframe zoom đầu–cuối như bảng. Dùng chuyển động đều hoặc ease rất nhẹ. Source quay 50/60 fps có thể để tốc độ **0,65–0,8×**; source 25/30 fps nên giữ 1× hoặc thử 0,85×. Nếu bật nội suy mà cánh hoa bị méo, tắt nội suy.
6. Dùng cùng một kiểu chuyển cảnh ở các mốc đầu: **mờ nét ngắn rồi rõ lại**, tổng khoảng **0,22 giây**. Trong các phiên bản có chuyển cảnh Blur/Defocus, chọn bản đơn giản nhất và giảm cường độ. Tên nút có thể khác theo phiên bản CapCut.
7. Nếu không có hiệu ứng phù hợp: chồng hai cảnh khoảng **0,2 giây**, giảm opacity cảnh cũ 100 → 0%, tăng cảnh mới 0 → 100%; cảnh mới zoom 99 → 100% trong khoảng 0,22 giây. Nếu chỉnh được Blur bằng keyframe, chỉ thêm một nhịp mờ nhẹ quanh điểm cắt, không làm mờ cả cảnh.
8. Giữ marker làm chuẩn: một số chuyển cảnh tự rút ngắn timeline. Sau khi thêm hiệu ứng, kiểm tra lại độ dài **12,58 giây** và vị trí nhạc. Chữ cuối dùng Lora hoặc một serif thanh, khoảng 70 px; lời nhắn khoảng 30 px. Dòng chữ nhỏ dưới ảnh là trang trí, có thể bỏ.
9. Xuất **1080 × 1920**, H.264, 60 fps nếu source quay 50/60 fps; khoảng 12–20 Mbps. Với source 25/30 fps, xuất 30 fps là đủ. Xem lại trên điện thoại: hoa phải rõ, khe giữa hai ô đều, không có khung trống lúc chuyển.

## Nhịp chuyển chính

| Thời điểm quanh điểm cắt T | Thao tác |
|---|---|
| T − 0,11 s | Cảnh cũ bắt đầu mất nét nhẹ |
| T − 0,04 s | Cảnh mới xuất hiện; cảnh cũ bắt đầu hòa tan |
| T + 0,10 s | Cảnh cũ biến mất hoàn toàn |
| T + 0,18 s | Cảnh mới rõ nét và ổn định |

Nếu muốn làm nhanh: dùng dissolve 0,2 giây cho toàn bộ các điểm cắt; đầu tư vào **đổi kích thước khung + hai ô trên/dưới + crop đúng bông hoa**. Đó là phần tạo nên phong cách của mẫu.

## Tệp trong bộ mẫu

- `Floral-Transition-Template.mp4`: video minh họa có nhạc ref.
- `Floral-Transition-Storyboard.jpg`: bảng tám cảnh để xem khi dựng.
- `Huong-dan-CapCut.md`: công thức này.
- `film/`: dự án HyperFrames có source mẫu, khung hình và animation; mở bằng HyperFrames để chỉnh tiếp. Không nhập trực tiếp thư mục này vào CapCut.

