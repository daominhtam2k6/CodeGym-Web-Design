# Thực hành - Tạo menu ngang

## Mục tiêu

Luyện tập sử dụng CSS để xây dựng menu ngang có menu con dạng dropdown.

## Cấu trúc menu

Menu chính gồm:

- Sem 1
- Sem 2
- Sem 3
- Sem 4

Sem 1 và Sem 2 có các menu con.

## HTML

Menu được xây dựng bằng:

- div có id menu
- ul
- li
- a
- ul lồng nhau để tạo submenu

## CSS

### Menu chính

Menu sử dụng:

height: 30px;

background-color: #000000;

border: 1px solid #CDCDCD;

### Menu theo chiều ngang

Các li sử dụng:

position: relative;

float: left;

list-style: none;

Thuộc tính float: left giúp các mục menu được đặt cạnh nhau theo chiều ngang.

### Liên kết

Mỗi liên kết có:

width: 100px;

height: 30px;

display: block;

text-decoration: none;

text-align: center;

line-height: 30px;

background-color: black;

color: white;

### Menu con

Các liên kết trong menu con có:

width: 200px;

text-align: left;

padding-left: 10px;

### Hover

Khi đưa chuột vào liên kết:

background-color: red;

### Vị trí menu con

Menu con sử dụng:

position: absolute;

top: 30px;

left: 15px;

visibility: hidden;

### Hiện submenu

Khi hover vào li của menu cha:

visibility: visible;

## File bài làm

- index.html
- styles.css
- README.md
