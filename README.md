# Trương Gia Phúc — Portfolio / GitHub Pages

## Đưa website lên GitHub

1. Đăng nhập GitHub và tạo repository Public tên portfolio.
2. Giải nén gói này. Trong repository, chọn Add file > Upload files.
3. Tải lên toàn bộ nội dung vừa giải nén: index.html, styles.css, app.js, video-library.js, thư mục assets, .nojekyll và README.md. File index.html phải nằm ngay ở gốc repository. Không tải nguyên file ZIP lên và không đặt website trong một thư mục con.
4. Commit changes vào nhánh main.
5. Vào Settings > Pages > Build and deployment. Chọn Source: Deploy from a branch, Branch: main, Folder: / (root), rồi Save.
6. Chờ GitHub triển khai. Mục Settings > Pages sẽ hiển thị URL thật khi website đã sẵn sàng. Với repo tên portfolio, URL thường có dạng https://TEN-TAI-KHOAN.github.io/portfolio/.

Gói này là website HTML/CSS/JS tĩnh hoàn chỉnh, không cần Node, WordPress hay Elementor để chạy trên GitHub Pages. Các đường dẫn tài nguyên tương đối phù hợp với repository project site.

Video vẫn phát từ Google Drive; cần Internet và quyền xem phù hợp. Ảnh bìa một số video và font cũng được tải qua Internet. Gói này không thay đổi quyền chia sẻ Drive.

Mã nguồn nằm trong repository public. Khi website đã lên GitHub Pages, không cần giữ máy cá nhân bật.

## Chỉnh sửa

- index.html: nội dung và thông tin liên hệ.
- styles.css: giao diện.
- app.js: tương tác gallery, website và video.
- video-library.js: 16 video đại diện, không có 3b.
- assets/: hình ảnh, preview ngắn và danh bạ.

Khi muốn cập nhật, thay các file đã chỉnh sửa trên nhánh main và commit. GitHub Pages sẽ triển khai lại.

## Tài liệu chính thức

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
