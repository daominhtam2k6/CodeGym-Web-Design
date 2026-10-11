# Bài tập - Giao diện giản lược trang chủ Facebook

## Mục tiêu

Luyện tập xây dựng:

- fixed header
- sidebar
- main content
- bố cục nhiều cột

## Fixed Header

Header sử dụng:

position: fixed;

top: 0;

left: 0;

right: 0;

Header luôn nằm ở phía trên màn hình khi cuộn trang.

## Sidebar trái

Sidebar trái sử dụng:

position: fixed;

top: 60px;

left: 0;

bottom: 0;

Sidebar chứa:

- User Name
- Bạn bè
- Nhóm
- Marketplace
- Watch
- Kỷ niệm
- Lối tắt

## Sidebar phải

Sidebar phải sử dụng:

position: fixed;

top: 60px;

right: 0;

bottom: 0;

Sidebar phải chứa:

- Nội dung tài trợ
- Danh sách người liên hệ

## Nội dung chính

Main content nằm ở giữa trang.

Bao gồm:

- stories
- khung tạo bài viết
- bài đăng
- lượt thích
- bình luận
- chia sẻ

## Các kỹ thuật CSS sử dụng

- position: fixed
- position: relative
- position: absolute
- display: flex
- display: grid
- border-radius
- box-shadow
- hover
- media query

## Responsive

Khi màn hình thu nhỏ:

- sidebar phải được ẩn;
- sau đó sidebar trái được ẩn;
- nội dung chính tự căn giữa;
- stories chuyển từ 4 cột xuống 2 cột.

## File bài làm

- index.html
- styles.css
- README.md
