# LTH Style — Đoạn 6: Tracking, giao hàng và COD

Video 120 giây, 3840×2160, 16:9, 30 fps. Infographic burgundy–kem, Be Vietnam Pro. Không lời thoại, không âm thanh; chỉ fade giữa các cảnh.

## Nội dung

- 00:00–00:16: kiện đã đóng gói, dán phiếu gửi và các điểm cần đối chiếu.
- 00:16–00:30: phiếu gửi GYENL6TA, SKU, quy cách, số lượng và thời điểm tạo đơn.
- 00:30–01:15: năm mốc trên tracking GHN, giữ nguyên tên trạng thái và thời gian.
- 01:15–01:40: trạng thái giao thành công lúc 15:59 ngày 13/11.
- 01:40–02:00: phân biệt COD 0đ với cước 16.500đ, người nhận thanh toán.

## Nguồn và xử lý

Ảnh kiện và phiếu gửi lấy từ ZIP người dùng bổ sung. Phiếu có mã GYENL6TA, tham chiếu #10029, thu người nhận 0, tạo đơn 11/11/2026 lúc 17:38. Ảnh kiện không được dùng để khẳng định đã chụp khoảnh khắc bàn giao cho nhân viên GHN hay khách mở gói.

Ảnh tracking lấy từ nguồn người dùng đã gửi trước đó. Ảnh không có mã vận đơn hiển thị, vì vậy không thêm mã vào ảnh và không khẳng định đã xác minh được mã chỉ từ ảnh này. Các mốc được giữ nguyên: Tạo đơn — 11/11 17:38; Đang lấy hàng — 12/11 16:29; Đang vận chuyển — 13/11 08:04; Đang giao hàng — 13/11 08:04; Giao hàng thành công — 13/11 15:59.

Ảnh cước là ảnh dự án đã chỉnh theo yêu cầu trước đó: đổi GYENQLUW thành GYENL6TA và COD 84.000đ thành 0đ. Đây không phải bản gốc chưa chỉnh sửa. Video chỉ sử dụng phần các cột thông tin kiện, COD và cước; không hiển thị trạng thái chờ lấy hàng của ảnh cũ. Cước giữ ở 16.500đ. Không có kết luận cửa hàng đã nhận tiền đối soát.

Nguồn Haravan #10030 của đoạn 5 và tham chiếu #10029 trên phiếu gửi mới khác nhau; đoạn 6 không sửa tham chiếu hay đưa ảnh Haravan vào để khẳng định hai số đó là cùng một đơn.

Số nhà được blur trên phiếu, ảnh kiện và tracking; tên đường và khu vực vẫn được giữ. Các số điện thoại đã ẩn sẵn trên phiếu được giữ nguyên. Ảnh cước đã có blur một phần điện thoại trước khi cắt khung. Source ZIP chỉ chứa các ảnh đã xử lý dùng trong video; không chứa ảnh đầu vào chưa blur.

## Dựng lại

1. Giải nén, mở terminal tại thư mục dự án. Cần Node.js, Chromium và FFmpeg.
2. `python3 build.py` để tạo lại HTML từ bố cục hiện tại.
3. `npm run check` để kiểm tra.
4. `npm run render -- --output LTH-Style-Doan6.mp4 --fps 30 --quality high --workers 2`.

CLI được ghim ở HyperFrames 0.9.38. Thư mục `assets` có GSAP và font cục bộ. Không cần truy cập website hay tài khoản Haravan/GHN để dựng lại.

## Kiểm tra

Full check đã qua: không có lỗi runtime, không có tràn bố cục trên các khung mẫu; 64/64 phép kiểm tra tương phản đạt. Các cảnh được xem tại 13, 28, 70, 95 và 118 giây. Khoảng dừng được chủ động giữ để người xem đọc ảnh và đối chiếu mốc; chữ nhỏ trong hàng nhận diện và nhãn phụ giữ cùng hệ thống với các đoạn trước. Fade mở đầu và video im lặng là lựa chọn theo yêu cầu.
