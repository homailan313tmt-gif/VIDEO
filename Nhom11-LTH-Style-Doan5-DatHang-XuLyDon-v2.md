# LTH Style — Đoạn 5 v2: Đặt hàng và xử lý đơn

240 giây, 3840×2160, 16:9, 30fps. Burgundy–kem, Be Vietnam Pro, chỉ fade. Không lời thoại, không âm thanh, không ghi chú chân cảnh hoặc chữ báo đã che.

## Thay đổi so với bản trước

- Bỏ việc kéo khoảng11 giây thao tác chọn sản phẩm thành40 giây; clip chọn hàng dùng tốc độ gốc.
- Thêm nguồn mới: vào giỏ, điền tên và liên hệ, nhập địa chỉ, chọn khu vực, kiểm tra thanh toán và bấm đặt hàng.
- Theo chỉ định của người dùng, dùng ảnh đơn Haravan cũ cho phần đặt hàng thành công/ghi nhận đơn. Không dựng trang cảm ơn website giả.
- Đồng bộ phần hiển thị mã Haravan #10029, vận đơn GHN GYENL6TA và thời gian tạo11/11/2026 17:38 với thông tin ở đoạn6.
- Giữ blur một phần số điện thoại và số nhà; giữ tên đường, phường, thành phố. Không hiển thị nhãn đã che.

## Nội dung và thời gian

- 00:00–00:12: chọn biến thể ở tốc độ gốc; áo2 dây màu Trắng, SKU LTH-A2D-REN-001-TR-FS, giá69.000đ, số lượng1.
- 00:12–00:20: giỏ hàng và chuyển đến checkout.
- 00:20–00:40: điền thông tin nhận hàng bằng clip mới.
- 00:40–00:43: kiểm tra thanh toán và bấm đặt hàng.
- 00:43–00:58: ảnh đơn cũ cho kết quả ghi nhận trên Haravan.
- 00:58–01:20: đối chiếu sản phẩm, người nhận và giá trị đơn.
- 01:20–02:00: tiếp nhận, xác thực thông tin đơn trên Haravan.
- 02:00–02:40: kiểm tồn và quy trình soạn hàng.
- 02:40–03:15: đóng gói và kiểm tra kiện.
- 03:15–03:45: vận đơn GHN.
- 03:45–04:00: phân biệt SKU, mã đơn và mã vận đơn; dẫn sang đoạn6.

## Số liệu sử dụng

Mã đơn hiển thị: #10029. Mã vận đơn: GYENL6TA. Ngày tạo hiển thị:11/11/2026 17:38. Sản phẩm màu Trắng, số lượng1, SKU LTH-A2D-REN-001-TR-FS, giá69.000đ.

Website hiển thị phí giao15.000đ, tổng84.000đ. Đây là phí giao trong checkout. Ảnh GHN giữ trường cước16.500đ, người nhận thanh toán, COD0đ, kiện200g và1 sản phẩm. Hai khoản phí được giữ theo tên trường trên từng nguồn; không đổi tổng đơn thành85.500đ hay khẳng định đã đối soát. Trạng thái Haravan giữ Đã thanh toán/Chưa giao hàng. Chỉ tiêu Còn tồn2 trong dòng sản phẩm giữ nguyên.

## Nguồn và chỉnh sửa theo yêu cầu

Video website cũ dài31.2149 giây; chỉ dùng các nhịp chọn sản phẩm rõ ở tốc độ gốc. Video mới do người dùng gửi ngày14/11/2026 dài51.463733 giây; dùng đoạn14–44.8 giây để thấy giỏ, điền thông tin và bấm đặt hàng. Cắt cuộn ngoài luồng và phần lặp sau đó.

Nguồn mới không có trang xác nhận thành công. Người dùng yêu cầu lấy ảnh cũ cho đoạn này, nên video chuyển sang ảnh đơn đã ghi nhận trên Haravan. Ảnh nguồn vốn là #10030; phần mã được phủ chữ thành #10029 theo yêu cầu đồng bộ. Thời gian tương đối trong ảnh được thay bằng11/11/2026 17:38 theo yêu cầu trước đó. Đây là chỉnh sửa trong bản dựng, không phải thao tác đổi dữ liệu trong tài khoản Haravan.

Ảnh GHN dùng bản dự án đã chỉnh từ GYENQLUW thành GYENL6TA và COD84.000đ thành0đ theo yêu cầu trước. Chỉnh sửa đó không xác minh mã của ảnh tracking vốn không có mã hiển thị. Ảnh đóng gói và quy trình soạn/kiểm hàng giữ đúng phạm vi tư liệu hiện có; không tạo thêm ảnh kiểm áo ngoài đời.

## Thông tin riêng tư

Clip checkout đã xử lý theo vị trí các ô khi cuộn. Phần điện thoại hiển thị dùng lại ảnh số đã blur giữa từ đơn cũ, giữ3 số đầu và3 số cuối, để thống nhất phần liên hệ trong bản dựng. Số nhà trên ô địa chỉ được blur, giữ Hoàng Diệu, Hải Châu và Đà Nẵng. Thanh địa chỉ trình duyệt và URL phiên checkout được cắt khỏi clip. Gói source không chứa clip đầu vào có dữ liệu chưa xử lý hoặc ảnh đơn gốc chưa blur.

## Dựng lại

Python3, Node.js, Chromium, FFmpeg. CLI ghim HyperFrames0.9.38. Chạy `python3 build.py`, sau đó `npm run check` và `npm run render -- --output doan5-v2.mp4 --fps 30 --quality high --workers 2`.

`style.css`, `later-scenes.json` và `build.py` là nguồn bố cục. Thư mục assets chứa đúng clip đã xử lý, ảnh, GSAP và font cục bộ. Không cần đăng nhập Haravan/GHN để dựng lại.

## Kiểm tra

Full check đã qua: không có lỗi runtime, không tràn bố cục trong các khung mẫu, motion không báo lỗi;56/56 phép kiểm tra tương phản đạt. Đã xem các khung8,17,28,37,42,52,75,100,217 và235 giây. Cảnh checkout được kiểm tra riêng tại các mốc nhập điện thoại, cuộn địa chỉ và chọn thanh toán.
