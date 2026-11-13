# LTH Style — Đoạn 7: Sau giao hàng và kết luận

Video 120 giây, 3840×2160, 16:9, 30fps. Phong cách infographic burgundy–kem, Be Vietnam Pro. Chỉ fade giữa các cảnh; không lời thoại, không âm thanh, không chú thích chân cảnh hay thông báo đã che thông tin.

## Nội dung

- 00:00–00:15: ảnh kiện hiện có và các bước đối chiếu khi nhận.
- 00:15–00:30: infographic kiểm tra SKU, quy cách, số lượng và tình trạng sau mở gói.
- 00:30–00:50: quy trình hoàn trả khi khách có yêu cầu.
- 00:50–01:05: theo dõi chuyển hoàn khi giao không thành công.
- 01:05–01:25: quy trình đổi hàng, kiểm tồn đúng biến thể thay thế.
- 01:25–01:40: nghiệp vụ nhập, xuất; chênh lệch giá và phí vận chuyển.
- 01:40–01:52: bốn khung tổng kết Sản phẩm → Tồn kho → Đơn hàng → Giao nhận.
- 01:52–02:00: LTH Style, Nhóm 11 · Lớp 49K22.4 và lời cảm ơn.

## Nguồn và cách trình bày

Người dùng đã chọn dùng ảnh hiện có và infographic. Chưa có ảnh mở gói hoặc ảnh kiểm tra áo sau nhận. Vì vậy ảnh kiện được dùng đúng vai trò ảnh kiện trong dự án; các bước kiểm tra sau mở gói là hướng dẫn trên infographic, không khẳng định đã có ảnh chứng minh khách mở gói hay đã kiểm đủ sản phẩm thực tế.

Ảnh kiện `parcel-safe.png` được dùng lại từ đoạn 6. Mã GYENL6TA lấy từ phiếu gửi đã cung cấp. Dữ liệu sản phẩm tham chiếu gồm SKU LTH-A2D-REN-001-TR-FS, màu Trắng, Free Size, số lượng trong đơn 1. Thông tin sản phẩm, tồn kho và dòng sản phẩm trong đơn ở phần tổng kết lấy từ nguồn Haravan của các đoạn trước. Ảnh giao nhận lấy từ tracking đã gửi; giữ nguyên trạng thái và thời gian, không thêm mã vào ảnh tracking vốn không có mã hiển thị.

Hoàn trả, giao không thành công và đổi hàng được trình bày dưới dạng quy trình có điều kiện. Không khẳng định đã xảy ra đơn hoàn/đổi thực tế, không tạo mã SKU thay thế, không giả định tiền hoàn hay chính sách riêng của cửa hàng. Dùng các bước kiểm tra, nhận hàng, đánh giá đủ điều kiện trước khi nhập lại tồn và ghi nhận riêng nghiệp vụ xuất hàng thay thế.

## Thông tin cá nhân

Ảnh kiện và tracking giữ bản blur số nhà đã xử lý ở đoạn trước. Ảnh tồn kho chỉ dùng vùng bảng SKU và số lượng, loại phần đầu trang có điện thoại và địa chỉ. Ảnh sản phẩm chỉ dùng vùng biến thể; ảnh đơn chỉ có dòng sản phẩm. Source ZIP chứa đúng các ảnh dùng trong video, không chứa bản chụp màn hình tồn kho đầy đủ thông tin liên hệ.

## Dựng lại

1. Cần Python 3, Node.js, Chromium và FFmpeg.
2. Tại thư mục đã giải nén, chạy `python3 build.py`.
3. Chạy `npm run check` để kiểm tra.
4. Chạy `npm run render -- --output LTH-Style-Doan7.mp4 --fps 30 --quality high --workers 2`.

HyperFrames CLI được ghim tại 0.9.38; GSAP và font nằm cục bộ trong assets. Không cần đăng nhập Haravan hoặc GHN để dựng lại.

## Kiểm tra

Full check đã qua, không có lỗi runtime hoặc tràn bố cục trên các khung mẫu; motion không báo lỗi và 48/48 phép kiểm tra tương phản đạt. Các cảnh được xem tại 13, 28, 48, 63, 83, 98, 110 và 118 giây. Khoảng dừng để đọc và fade mở đầu được giữ có chủ đích; các nhãn nhỏ và hàng nhận diện đồng bộ với các đoạn trước.
