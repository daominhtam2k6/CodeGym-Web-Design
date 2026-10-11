# Layout Refactoring

Legacy Author Info dùng `float`, khiến phần tử con thoát khỏi luồng bố cục thông thường theo cách khó kiểm soát và thường phải dùng clearfix hoặc `overflow: hidden` để phần tử cha ôm được nội dung. Flexbox phù hợp hơn vì Author Info là bố cục một chiều; `align-items: center`, `justify-content: space-between`, `gap` và `flex-wrap` giúp avatar, thông tin và nút chia sẻ căn chỉnh linh hoạt.

Mosaic Gallery cũ dùng `position: absolute` và chiều cao cố định. Các ảnh không còn đóng góp chiều cao tự nhiên cho phần tử cha, nên trên màn hình nhỏ chúng dễ chồng lên nội dung phía dưới.

CSS Grid giữ các ảnh trong normal flow, đồng thời quản lý hàng và cột trực tiếp. Ảnh chính dùng `grid-row: span 2`, còn mobile chuyển thành một cột. Recommended Articles dùng Bootstrap `col-12 col-md-6 col-lg-3` để responsive mà không cần tự tính phần trăm.
