# Bài tập - Tạo layout với các thẻ HTML5 và CSS

## Mục tiêu

Luyện tập thiết kế bố cục trang web bằng các thẻ semantic HTML5 và CSS.

## Các thẻ HTML5 sử dụng

### header

Được sử dụng cho phần đầu trang.

Trong bài, header chứa tiêu đề:

Monday Times

### nav

Được sử dụng để tạo thanh điều hướng.

Menu gồm:

- News
- Sports
- Weather

### section

Được sử dụng để nhóm nội dung chính của trang.

### article

Bài có nhiều article nằm bên trong section.

Mỗi article đại diện cho một nội dung độc lập.

### aside

Được sử dụng cho nội dung phụ nằm cạnh nội dung chính.

Trong bài aside chứa các liên kết tin liên quan.

### footer

Được sử dụng cho phần cuối trang.

## CSS Layout

Bài sử dụng Flexbox cho phần nội dung chính:

display: flex;

Trong đó:

section chiếm phần lớn chiều rộng.

aside nằm bên phải section.

## Responsive

Khi màn hình nhỏ hơn 700px:

- menu chuyển sang dạng dọc;
- section và aside chuyển thành bố cục một cột.

## File bài làm

- index.html
- styles.css
- README.md
