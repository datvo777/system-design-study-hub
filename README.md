# System Design Study Hub

Web app tĩnh để học System Design theo lộ trình 15 tuần: roadmap theo tuần, bài học cho từng khái niệm, mock interview 45 phút, thẻ trade-off, cheat sheet và checklist.

- **Bài học trong app:** mỗi khái niệm trong mục "Học" có một bài đầy đủ (giải thích, sơ đồ, trade-off, liên hệ Java/IBM, câu nói mẫu khi phỏng vấn, lỗi hay gặp, câu hỏi tự kiểm tra). Nội dung nằm trong `lessons/w1.md` … `lessons/w15.md`, mỗi khái niệm bắt đầu bằng dòng `@@ <id>` khớp với id checklist trong `index.html`.
- **Giao diện sáng/tối:** nút ở góc phải header; mặc định theo cài đặt của hệ điều hành.
- Chạy 100% phía client (React + Tailwind + marked qua CDN), không cần build.
- Tiến độ và ghi chú lưu trong `localStorage` của trình duyệt (key `sd_senior_15weeks_v1`). Dùng **Export / Import JSON** để backup hoặc chuyển máy.

## Chạy local

Bài học được nạp bằng `fetch`, nên cần mở qua HTTP, không mở trực tiếp file:

```bash
python3 -m http.server 8000
# mở http://localhost:8000
```

## Deploy

Vercel (import repo, framework "Other", không cần build command) hoặc GitHub Pages (`main` / root).
