# Trang khách đăng ký Bot Zalo AI [?]

Ngày 08/10/2026. Bản nháp chờ Anh Lộc xem; chưa publish.

## Dùng file nào

- index.html: trang giới thiệu và đăng ký trao đổi cho khách.
- huong-dan-cai-bot-zalo.html: trang hướng dẫn cài, là đích của nút hướng dẫn.
- README.md: ghi chú triển khai này.

Chỉ đưa các file của thư mục web này lên repo web, không đưa project bot, bộ cài nâng cao, .env, cấu hình thật hoặc dữ liệu lên theo.
Trang chạy tĩnh, không cần build, package hoặc server xử lý đăng ký.

## Đăng ký hoạt động thế nào

Khách điền tên (tùy chọn), bản quan tâm, máy và nhu cầu.
Bấm chuẩn bị tin đăng ký -> xem tin -> chép -> mở Zalo -> tự dán và gửi.
Đích Zalo: https://zalo.me/0985635358 (Anh Lộc).
Trang không lưu khách vào LocalStorage, không tự gửi, không có bảng đơn đăng ký.
Không có thu tiền hoặc thông báo giả đã gửi thành công.
Đổi trường sẽ ẩn tin cũ để khách tạo lại tin đúng dữ liệu mới.
Nếu trình duyệt chặn Clipboard, trang chọn sẵn nội dung để chép thủ công.

## Trước khi đưa lên GitHub Pages

1. Anh xem nội dung/đích Zalo, chính sách giá và hỗ trợ (hiện chưa niêm yết số tiền/thời hạn).
2. Nếu cần sửa thông tin, sửa nguồn wiki/work/dang-ky-bot-zalo.html và đồng bộ index.html, không để hai bản lệch.
3. Đưa đúng 3 file này vào thư mục web đã chọn. Giữ hai HTML cùng thư mục để liên kết tương đối hoạt động.
4. Trong repo, chọn nguồn GitHub Pages tương ứng theo giao diện GitHub của anh. Không đưa ZIP nâng cao lên web khi chưa quyết định phát hành.
5. Mở URL công khai GitHub cấp và kiểm lại mục lục, nút hướng dẫn, tạo/chép tin và đích Zalo. Kiểm trong máy chưa xác nhận URL công khai.

Các phiên bản đối chiếu: free 0.1.0-preview.5, nâng cao 0.1.0-advanced.preview.18.
Nâng cao đang thử nghiệm; laptop đang kiểm, Mac chưa nghiệm thu và lưu phiên chỉ Windows.
Không tự coi 500.000đ/30 ngày của demo cũ là chính sách hiện hành.
Không publish, commit hoặc push trong lượt chuẩn bị này.