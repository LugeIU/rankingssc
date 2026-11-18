# SSC Bootcamp Set 19

Trang web sự kiện leo rank TFT (server Việt Nam), format theo BoxBox Bootcamp Set 18.

- `index.html`: giao diện (HTML + CSS + JS, không cần build)
- `api/players.js`: hàm máy chủ Vercel (đăng ký, danh sách, rank từ Riot API)

## Cài đặt trên Vercel

1. Import repo vào Vercel, Framework Preset: **Other**.
2. Tab Storage (hoặc Marketplace): thêm **Upstash Redis** và nối vào project (tự tạo biến môi trường KV_REST_API_URL, KV_REST_API_TOKEN).
3. Settings > Environment Variables, thêm:
   - `RIOT_API_KEY`: key từ developer.riotgames.com (key dev hết hạn sau 24 giờ, nên đăng ký Personal/Production key cho sự kiện)
   - `ADMIN_KEY`: mã bí mật do bạn tự đặt, dùng để xóa người chơi
4. Redeploy.

Xóa người chơi: mở `https://<ten-mien>/?admin`, nhập `ADMIN_KEY`, nút × sẽ hiện trong tab Danh sách.

## Chỉnh nhanh (đầu phần `<script>`)

`START`, `SAFE`, `LAST`, `CAP`, `DEF`, `PRIZES`.
