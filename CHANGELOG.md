# Changelog

## v0.1.1 — 2026-11-17

- Số video xử lý song song: chọn Tự động hoặc tự nhập từ 1 đến 16, đổi được ngay cả khi đang render (video đang chạy không bị dừng)
- Khi có phiên bản mới, mục Cài đặt ở thanh bên được highlight kèm nhãn "Mới"; app tự kiểm tra cập nhật mỗi giờ
- Con trỏ chuột đổi thành bàn tay khi rê vào các nút bấm được

## v0.1.0 — 2026-11-17

Phiên bản đầu tiên của 2T Composer, viết lại TV Composer bằng Tauri + Rust.
- Render hàng loạt bằng FFmpeg đi kèm, tự dùng GPU (NVENC / QSV / AMF) nếu có, chạy song song và tự thử lại khi lỗi
- Xem trước khung hình thật, hàng đợi hiển thị tiến độ từng video, huỷ được giữa chừng
- Thư viện 103 bộ lọc màu (sửa 7 bộ lọc lỗi từ TV Composer)
- Giao diện tiếng Việt / tiếng Anh, sáng / tối
- Tự kiểm tra và cài bản cập nhật
