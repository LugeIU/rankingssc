# TFT Bootcamp Việt Nam – Set 19

Trang web tĩnh cho sự kiện leo rank TFT theo format BoxBox Bootcamp (server Việt Nam).

- `index.html`: toàn bộ trang (HTML + CSS + JS, không cần build).

## Deploy lên Vercel

1. Đẩy repo này lên GitHub.
2. Vào vercel.com, chọn Add New > Project, rồi Import repo.
3. Framework Preset: **Other**. Để trống Build Command và Output Directory.
4. Bấm Deploy. Mỗi lần push lên nhánh `main`, Vercel tự deploy lại.

## Chỉnh nhanh (đầu phần `<script>` trong index.html)

- `START`: ngày bắt đầu (hiện là 2/12/2026, giờ GMT+7)
- `SAFE`: số ngày an toàn (10)
- `LAST`: ngày chung cuộc (17, tức 18/12)
- `CAP`, `PER_DIV`: số người tối đa và số người mỗi division
- `REGION`: mã vùng lolchess (`vn`)
