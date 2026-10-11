# Thực hành - Sử dụng Box Model

## Mục tiêu

Luyện tập sử dụng CSS Box Model.

Box Model gồm bốn thành phần chính:

- content
- padding
- border
- margin

## Cấu trúc HTML

Trang sử dụng một thẻ div có class:

boxmodel

Bên trong có ba thẻ p với các id:

- boxmodel1
- boxmodel2
- boxmodel3

## CSS cho boxmodel

Các thuộc tính chính:

margin: 0 auto;

width: 800px;

border: 10px;

padding: 10px;

border-color: chartreuse aqua blue blueviolet;

border-style: solid;

## CSS cho các thẻ p

Các đoạn văn bên trong boxmodel sử dụng:

border: 3px dotted darkred;

padding: 10px;

## Margin của từng đoạn

boxmodel1:

margin-bottom: 20px;

boxmodel2:

margin-bottom: 40px;

boxmodel3:

margin-bottom: 60px;

## Ý nghĩa các thuộc tính

### width

Quy định chiều rộng phần content của div.

### padding

Quy định khoảng cách từ nội dung đến border.

### border

Là viền bao quanh content và padding.

### border-color

Quy định màu sắc của các cạnh border.

Bài sử dụng bốn màu:

- chartreuse
- aqua
- blue
- blueviolet

### border-style

Sử dụng solid để tạo đường viền nét liền.

### margin

Là khoảng cách bên ngoài border.

### margin: 0 auto

Giúp phần tử có chiều rộng xác định được căn giữa theo chiều ngang.

### margin-bottom

Tạo khoảng cách phía dưới từng đoạn văn.

Các giá trị lần lượt là:

- 20px
- 40px
- 60px

## File bài làm

- index.html
- README.md
