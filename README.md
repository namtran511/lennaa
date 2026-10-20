# lennaa

Trang web tĩnh trong repository này được triển khai bằng GitHub Pages để mở được trên điện thoại.

## Cách bật GitHub Pages

1. Vào **Settings → Pages** của repository `namtran511/lennaa`.
2. Ở mục **Build and deployment**, chọn **Source: GitHub Actions**.
3. Push vào nhánh `main` (workflow `Deploy static site to Pages` sẽ tự chạy).
4. Sau khi workflow chạy xong, mở link Pages tại:
   `https://namtran511.github.io/lennaa/`

## Ghi chú

- `index.html` nằm ở thư mục gốc nên được deploy trực tiếp.
- Có thể mất 1-3 phút để link Pages hoạt động sau lần deploy đầu.