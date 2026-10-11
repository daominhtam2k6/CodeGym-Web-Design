# AI Prompt Log - CreativeChronicle

## Nguyên tắc

AI được sử dụng để tìm hiểu từng kỹ thuật layout riêng lẻ, không đưa toàn bộ Legacy Code cho AI và yêu cầu sửa toàn bộ website.

## Prompt 1 - Float và Flexbox

Prompt:

Tại sao một cụm Author Info gồm avatar, tên tác giả, ngày đăng và nút Share phù hợp với Flexbox hơn float? Hãy tập trung vào vertical alignment và flex-wrap.

Kết luận áp dụng:

Author Info là bố cục một chiều. Flexbox cho phép dùng `align-items: center`, `justify-content: space-between`, `gap` và `flex-wrap` mà không cần clearfix.

## Prompt 2 - Absolute Positioning

Prompt:

Tại sao dùng `position: absolute` cho các ảnh trong gallery có thể khiến parent không có chiều cao tự nhiên và gây đè lấn nội dung trên mobile?

Kết luận áp dụng:

Phần tử absolute không chiếm không gian trong normal flow. Khi toàn bộ gallery phụ thuộc vào các tọa độ cố định, phần tử cha phải dùng chiều cao cứng và rất khó responsive.

## Prompt 3 - CSS Grid Mosaic

Prompt:

Hãy giải thích cách dùng CSS Grid để tạo Mosaic Gallery có một ảnh lớn bên trái chiếm hai hàng và hai ảnh nhỏ bên phải, không sử dụng absolute positioning.

Kết luận áp dụng:

Container dùng `display: grid`, hai cột `2fr 1fr`, `gap: 15px`; ảnh chính dùng `grid-row: span 2`.

## Prompt 4 - Grid tự sinh hàng

Prompt:

Nếu thêm ảnh thứ 4 hoặc thứ 5 vào CSS Grid mà không chỉ định vị trí thủ công, Grid có tự động tạo thêm hàng không?

Kết luận áp dụng:

Có. Grid auto-placement sẽ đặt các item tiếp theo vào ô trống và tạo implicit rows khi cần.

## Prompt 5 - Bootstrap Breakpoints

Prompt:

Trong Bootstrap 5, `col-12 col-md-6 col-lg-3` thay đổi bố cục như thế nào ở mobile, tablet và desktop?

Kết luận áp dụng:

- Mobile: `col-12` -> 1 card mỗi hàng.
- md trở lên: `col-md-6` -> 2 card mỗi hàng.
- lg trở lên: `col-lg-3` -> 4 card mỗi hàng.

## Prompt 6 - Bootstrap Utilities

Prompt:

Các utility class Bootstrap như `d-flex`, `align-items-center`, `gap-3`, `mt-3`, `pb-2` giúp giảm CSS tự viết như thế nào?

Kết luận áp dụng:

Utility class biểu diễn trực tiếp các quy tắc phổ biến trong HTML, phù hợp với spacing và alignment nhỏ, giúp tránh tạo thêm nhiều class CSS chỉ để đặt margin, padding hoặc Flexbox cơ bản.
