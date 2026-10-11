# Bài tập - Phát triển trang web xem hoạt hình trực tuyến

## Mục tiêu

Luyện tập:

- tạo layout bằng div và CSS;
- sử dụng thẻ video;
- nhúng YouTube bằng iframe;
- fixed header;
- responsive web design.

## Bố cục

Trang được chia thành:

- header
- head-link
- left content
- right content
- footer

## Header

Header chứa:

- Logo CartoonHD
- Ô tìm kiếm phim

Header sử dụng:

position: fixed;

top: 0;

left: 0;

right: 0;

z-index: 1000;

Do đó header vẫn được giữ ở đầu màn hình khi người dùng cuộn trang.

## Head-link

Bao gồm các liên kết:

- Phim hoạt hình
- Phim yêu thích
- Nhân vật hoạt hình
- Góp ý

Liên kết bỏ gạch chân.

Khi hover:

- chữ đổi màu;
- chữ được in đậm.

## Left Content

Left content chứa danh sách các video.

Mỗi phim có:

- thumbnail;
- tên phim;
- số lượt xem;
- liên kết đến video.

Các liên kết sử dụng target cartoon-player.

Khi click, video YouTube được tải vào iframe ở phần nội dung bên phải.

## Right Content

Right content chứa video đang được chọn.

Video mặc định là video đầu tiên.

YouTube được nhúng bằng thẻ iframe.

## HTML5 Video

Trang cũng có một ví dụ sử dụng:

video

source

controls

để đáp ứng yêu cầu luyện tập thẻ video HTML5.

## Footer

Footer hiển thị:

- thông tin bản quyền;
- thông tin mục đích học tập.

## Responsive

Bài sử dụng các breakpoint:

- 950px
- 700px
- 450px

Desktop:

left content và right content nằm cạnh nhau.

Mobile:

left content và right content chuyển thành một cột.

## File bài làm

- index.html
- styles.css
- README.md
