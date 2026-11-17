# Changelog

## v0.1.0 — 2026-11-17

Phiên bản đầu tiên của 2T Composer, viết lại TV Composer bằng Tauri + Rust.
- Render hàng loạt bằng FFmpeg đi kèm, tự dùng GPU (NVENC / QSV / AMF) nếu có, chạy song song và tự thử lại khi lỗi
- Xem trước khung hình thật, hàng đợi hiển thị tiến độ từng video, huỷ được giữa chừng
- Thư viện 103 bộ lọc màu (sửa 7 bộ lọc lỗi từ TV Composer)
- Giao diện tiếng Việt / tiếng Anh, sáng / tối
- Tự kiểm tra và cài bản cập nhật
