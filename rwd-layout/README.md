# Bài tập - Tạo layout với RWD

## Mục tiêu

Luyện tập sử dụng DIV và CSS để xây dựng bố cục Responsive Web Design.

## Cấu trúc trang

Trang bao gồm:

- Header
- Navigation menu
- Left sidebar
- Main content
- Right sidebar
- Footer

## DIV

Các khối chính sử dụng:

- header
- menu
- layout
- left
- content
- right
- footer

## Desktop

Ở màn hình lớn:

Left Sidebar:

20%

Main Content:

60%

Right Sidebar:

20%

Ba khu vực được đặt cạnh nhau bằng:

display: flex;

## Tablet

Với màn hình nhỏ hơn 900px:

- left sidebar chiếm 25%;
- main content chiếm 75%;
- right sidebar chuyển xuống hàng dưới;
- hai khối ADS hiển thị cạnh nhau.

## Mobile

Với màn hình nhỏ hơn 600px:

- menu chuyển thành dạng dọc;
- left sidebar chiếm 100%;
- main content chiếm 100%;
- right sidebar chiếm 100%;
- các thành phần hiển thị theo một cột.

## Kỹ thuật Responsive

Bài sử dụng:

@media only screen and (max-width: 900px)

và:

@media only screen and (max-width: 600px)

## Thuộc tính CSS

Các thuộc tính chính:

- display: flex
- flex-wrap
- width
- padding
- margin
- background-color
- border
- :hover
- media query

## File bài làm

- index.html
- styles.css
- README.md
