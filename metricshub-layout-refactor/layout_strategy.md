# MetricsHub Layout Strategy

Legacy Navbar dùng Grid với cột pixel cố định nên nội dung dài, đặc biệt khi đổi ngôn ngữ, dễ tràn và va chạm. Navbar là bài toán 1 chiều nên chuyển sang Flexbox, kết hợp `justify-content`, `align-items`, `gap` và `flex-wrap` để ưu tiên kích thước nội dung.

Legacy Dashboard dùng nhiều Flexbox lồng nhau tạo Div Soup và khó biểu diễn widget chiếm nhiều hàng/cột. Dashboard là bài toán 2 chiều nên CSS Grid phù hợp hơn; các widget là siblings trực tiếp và dùng `grid-column: span 2` hoặc `grid-row: span 2`.

Pricing chỉ cần ba cột chuẩn nên dùng Bootstrap 12-column grid: `col-12 col-md-4`. Mobile tự xếp dọc mà không cần media query riêng.

Grid quản lý layout tổng thể 2D; Flexbox phù hợp căn chỉnh component 1D. `gap` thay thế nhiều margin thủ công.
