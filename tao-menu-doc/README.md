# Thực hành - Tạo menu dọc

## Mục tiêu

Luyện tập sử dụng CSS để tạo menu dọc có menu con dạng dropdown.

## Cấu trúc menu

Menu chính gồm:

- Sem 1
- Sem 2
- Sem 3
- Sem 4

Sem 1 và Sem 2 có menu con.

## HTML

Menu sử dụng:

- div có id menu
- ul
- li
- a
- các ul lồng nhau

## CSS chính

### Xóa ký hiệu danh sách

Sử dụng:

list-style: none;

### Định vị phần tử

Sử dụng:

position: relative;

cho các li.

### Kích thước

Menu có:

width: 100px;

height: 30px;

padding: 0 20px;

### Màu nền

Menu chính sử dụng:

background-color: black;

### Link

Các thẻ a sử dụng:

text-decoration: none;

color: white;

### Hover

Khi đưa chuột vào mục menu:

background-color: red;

### Menu con

Menu con sử dụng:

position: absolute;

top: 0;

left: 140px;

visibility: hidden;

### Hiện menu con

Khi hover vào mục menu cha:

visibility: visible;

## File bài làm

- index.html
- styles.css
- README.md
