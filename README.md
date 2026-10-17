# Academic Personal Website - Nguyen Xuan Bach

Trang cá nhân học thuật tối giản, thanh lịch chuẩn mực toán học theo phong cách của GS. Vincent Pilloni (Institut de Mathématiques d'Orsay, CNRS & Université Paris-Saclay).

## 1. Cấu trúc thư mục
- `index.html`: Toàn bộ nội dung trang web (thông tin cá nhân, hướng nghiên cứu, bài báo, ghi chép học tập, giảng dạy).
- `style.css`: File định kiểu thẩm mỹ cổ điển (Serif, Latin Modern Roman, tối ưu đọc trên điện thoại/máy tính).
- `robots.txt` & `sitemap.xml`: Tối ưu hóa công cụ tìm kiếm (Google SEO) để mọi người dễ dàng tìm thấy tên bạn.

## 2. Cách đưa trang web lên công khai qua GitHub Pages (Miễn phí 100%)
1. Tạo một tài khoản trên [GitHub](https://github.com) (nếu chưa có). Đặt username ví dụ: `nguyenxuanbach` hoặc `bachnguyen`.
2. Tạo một Repository mới với tên chính xác là:
   `<tên-username>.github.io` (Ví dụ: `nguyenxuanbach.github.io`). Đặt chế độ **Public**.
3. Tải toàn bộ các file trong thư mục này lên repository đó:
   ```bash
   cd nguyenxuanbach.github.io
   git init
   git add .
   git commit -m "Initial academic homepage"
   git branch -M main
   git remote add origin https://github.com/<tên-username>/<tên-username>.github.io.git
   git push -u origin main
   ```
4. Đợi khoảng 1-2 phút, trang web sẽ tự động chạy tại:
   `https://<tên-username>.github.io`
