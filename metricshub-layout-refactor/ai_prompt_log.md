# AI Prompt Log - MetricsHub

## Quy tắc sử dụng

AI được dùng để phản biện từng vấn đề nhỏ về layout, không nhận toàn bộ Legacy Code với yêu cầu viết lại toàn bộ trang.

## Prompt 1 - Grid hay Flexbox cho Bento

Prompt:

Khi tôi cần một bố cục mà một phần tử con phải chiếm chính xác 2 hàng và 2 cột, đan xen với các phần tử nhỏ khác, tôi nên chọn CSS Grid hay Flexbox? Tại sao Flexbox lại chật vật với yêu cầu này?

Kết luận áp dụng:

CSS Grid phù hợp vì kiểm soát đồng thời hàng và cột. `grid-column` và `grid-row` mô tả span trực tiếp. Flexbox chủ yếu xử lý một trục mỗi lần, nên Bento phức tạp thường phải thêm wrapper.

## Prompt 2 - Bootstrap breakpoint

Prompt:

Trong Bootstrap 5, sự khác biệt giữa `col-sm-4` và `col-md-4` là gì? Tại sao dùng Bootstrap phù hợp với Pricing ba cột đơn giản?

Kết luận áp dụng:

Bootstrap theo mobile-first. `col-md-4` khiến mỗi card rộng 4/12 cột từ breakpoint md trở lên. Kết hợp `col-12 col-md-4` cho phép card chiếm 12/12 trên mobile và 4/12 trên desktop.

## Prompt 3 - Bento Box

Prompt:

Hãy cho tôi cú pháp CSS Grid tối giản để tạo Bento Box có một widget lớn chiếm 2 cột và 2 hàng, xen kẽ các widget nhỏ. Chỉ giải thích cấu trúc Grid và span.

Kết luận áp dụng:

Dashboard dùng `grid-template-columns: repeat(3, minmax(0, 1fr))`, sau đó widget lớn dùng `grid-column: span 2` và `grid-row: span 2`.

## Prompt 4 - Navbar Mobile

Prompt:

Làm thế nào sử dụng `flex-wrap: wrap` để Navbar trên màn hình khoảng 375px tự xuống dòng mà không che Logo?

Kết luận áp dụng:

Navbar dùng Flexbox với `flex-wrap: wrap`. Menu được cho `flex-basis: 100%` trên mobile để chuyển xuống một hàng mới.

## Prompt 5 - Thuộc tính gap

Prompt:

Thuộc tính CSS `gap` hiện dùng được với Flexbox và Grid như thế nào, và vì sao nó tốt hơn việc gắn margin vào từng child?

Kết luận áp dụng:

`gap` mô tả khoảng cách tại container, dùng được cho cả Grid và Flexbox. Nó làm CSS rõ hơn, tránh xử lý margin ở phần tử đầu/cuối và giảm các quy tắc khoảng cách rời rạc.
