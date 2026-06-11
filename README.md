# 🚀 Hoang Tuanz - Creative Product Architect Portfolio

Trang web Portfolio cá nhân cực kỳ hiện đại và chuyên nghiệp sử dụng **React (Vite) + Tailwind CSS v4**. Trang web được thiết kế theo phong cách tối giản cao cấp, có hiệu ứng hạt lưới tương tác (Canvas Grid), hỗ trợ đa ngôn ngữ (VI/EN) và case study chi tiết cho từng dự án.

## ✨ Tính năng nổi bật
- **React 19 & Vite 8**: Tốc độ phản hồi cực nhanh và tối ưu dung lượng tải trang.
- **Tailwind CSS v4**: Biên dịch CSS hiệu năng cao với các tính năng hiện đại.
- **Canvas Interaction**: Hiệu ứng mạng lưới điểm tương tác động theo con trỏ chuột.
- **Đa Ngôn Ngữ**: Dễ dàng chuyển đổi giữa tiếng Việt (VI) và tiếng Anh (EN).
- **Case Study Chi Tiết**: Giao diện đọc case study dự án được thiết kế chuẩn editorial sang trọng.
- **Biểu mẫu Liên hệ**: Xác thực trực tiếp trên Client-side kèm phản hồi trực quan.

---

## 💻 Cách chạy dự án ở máy cục bộ (Local Development)

Để chạy trang web trên máy tính của bạn, hãy làm theo các bước sau:

1. **Cài đặt thư viện phụ thuộc**:
   Đảm bảo bạn đã cài đặt Node.js trên máy. Sau đó mở Terminal trong thư mục dự án và chạy:
   ```bash
   npm install
   ```
2. **Chạy máy chủ phát triển (Development Server)**:
   ```bash
   npm run dev
   ```
   *Sau khi chạy, Terminal sẽ hiển thị một đường dẫn dạng `http://localhost:5173`. Hãy mở link này trên trình duyệt.*
3. **Build dự án cho sản xuất (Production Build)**:
   ```bash
   npm run build
   ```
   *Code sau khi biên dịch tối ưu sẽ nằm trong thư mục `dist`.*

---

## ☁️ Hướng dẫn đưa trang web lên Vercel (Miễn phí)

Vercel tự động hỗ trợ rất tốt các dự án React + Vite. Dưới đây là cách triển khai:

### Cách 1: Triển khai qua GitHub (Khuyên dùng - Cập nhật tự động)
Mỗi khi bạn đẩy code mới lên GitHub, Vercel sẽ tự động build và cập nhật trang web của bạn.

1. **Đẩy code lên GitHub**:
   - Truy cập [GitHub](https://github.com) tạo một repository mới tên là `my-portfolio` (chọn Public).
   - Mở Terminal trong thư mục dự án và chạy các lệnh:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin <ĐƯỜNG_DẪN_GIT_REPO_CỦA_BẠN>
     git push -u origin main
     ```
2. **Liên kết với Vercel**:
   - Đăng nhập vào [Vercel](https://vercel.com) bằng tài khoản GitHub của bạn.
   - Nhấp **Add New...** -> **Project**.
   - Tìm Repository `my-portfolio` của bạn và chọn **Import**.
   - **Vercel sẽ tự động nhận diện dự án là Vite!**
     - Framework Preset: **Vite**
     - Build Command: `npm run build`
     - Output Directory: `dist`
   - Nhấp vào nút **Deploy**.
   - Sau vài giây, trang web của bạn sẽ hoạt động chính thức với một đường dẫn miễn phí dạng `my-portfolio.vercel.app`.

### Cách 2: Triển khai nhanh bằng Vercel CLI (Không cần GitHub)
1. Cài đặt Vercel CLI toàn cục:
   ```bash
   npm install -g vercel
   ```
2. Đăng nhập và triển khai dự án:
   ```bash
   vercel
   ```
   - Nhấn **Enter** để đồng ý với các tùy chọn mặc định.
   - Khi Vercel hỏi cấu hình build, nó sẽ tự động phát hiện Vite. Bạn chỉ cần nhấn **Enter** để đồng ý.
3. Khi quá trình hoàn tất, chạy lệnh sau để đưa lên Production chính thức:
   ```bash
   vercel --prod
   ```

Chúc bạn triển khai dự án thành công và có một trang Portfolio thật ấn tượng!
