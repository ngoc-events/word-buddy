# Bridge-Lexi

Tra từ **Nga ⇄ Anh** kiểu nhắn tin. Không cần đăng nhập, không cần API key, không cần server.

- Gõ từ **tiếng Nga** → các nghĩa cơ bản bằng tiếng Anh.
- Gõ từ **tiếng Anh** → các từ tiếng Nga tương ứng.
- Gõ dạng đã chia/biến cách (vd. `книгу`) → tự tìm về từ gốc (`книга`).

## Cách hoạt động

Toàn bộ app là một file `index.html`. Trình duyệt của người dùng gọi thẳng API công khai của
[Wiktionary](https://en.wiktionary.org) (cho phép gọi từ mọi trang web, không cần khoá),
nên GitHub Pages chỉ cần phục vụ file tĩnh.

## Đăng lên GitHub Pages

1. Tạo repo mới tên `Bridge-Lexi` (Public).
2. **Add file → Upload files** → tải lên `index.html` và `README.md` → **Commit**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → **Save**.
4. Sau 1–2 phút, app chạy tại `https://<tên-github>.github.io/Bridge-Lexi/`.

Ai có link đều dùng được ngay, không cần tài khoản.

## Giới hạn

- Nghĩa hiển thị bằng tiếng Anh theo cách Wiktionary viết, đôi khi dài hơn mức “cơ bản”.

## Giấy phép dữ liệu

Nội dung từ điển © các tác giả Wiktionary, theo giấy phép
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
