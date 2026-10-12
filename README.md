# Học Lại Để Yêu Hơn - Bảng thi đua

Dashboard thi đua hàng tuần của chương trình "7 Phút - Học Lại Để Yêu Hơn" (Xứ Đoàn Thánh Tâm).

- template.html: giao diện, có chỗ chèn dữ liệu (__DATA__)
- data.json: dữ liệu tuần, cta, game show
- index.html: bản đã ghép (Netlify phát hành file này)
- roster-map.json: Substack user_id -> người trong roster (không chứa email)
- _headers: chặn công cụ tìm kiếm lập chỉ mục

Quy trình mỗi tuần (tối thứ Bảy 20:00): đọc Substack -> cập nhật data.json -> ghép vào template -> index.html -> Netlify đăng.
