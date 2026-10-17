# System Design Study Hub

Web app tĩnh để theo dõi lộ trình học System Design trong 15 tuần: roadmap theo tuần, mock interview 45 phút, thẻ trade-off, cheat sheet và checklist.

- Chạy 100% phía client (React + Tailwind qua CDN), không cần build.
- Tiến độ lưu trong `localStorage` của trình duyệt (key `sd_senior_15weeks_v1`). Dùng **Export / Import JSON** để backup hoặc chuyển máy.

## Chạy local

Mở `index.html` trực tiếp bằng trình duyệt, hoặc `python3 -m http.server`.

## Deploy

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `(root)`.
