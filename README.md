# Mini Project: Xây dựng trang "Công thức nấu ăn" chuẩn Semantic

Dự án áp dụng các thẻ ngữ nghĩa HTML5 (`<article>`, `<section>`, `<header>`, `<footer>`), bảng biểu `<table>` và biểu mẫu tương tác `<form>` theo chuẩn giáo trình CodeGym.

---

## Các yêu cầu đã hoàn thành
1. **Cấu trúc ngữ nghĩa tổng thể**:
   - Toàn bộ nội dung công thức được bao bọc trong thẻ độc lập `<article>`.
   - `<header>` bên trong `<article>` chứa tiêu đề `<h1>`, mô tả ngắn `<p>` và hình ảnh món ăn `<img>` có thuộc tính `alt` rõ ràng.
   - `<footer>` bên trong `<article>` cung cấp mẹo nhỏ hữu ích từ đầu bếp.
2. **Bảng nguyên liệu (`<table>`)**:
   - Nằm trong `<section>` riêng biệt có tiêu đề `<h2>`.
   - Cấu trúc rõ ràng với `<thead>` chứa các tiêu đề cột (`<th>`) và `<tbody>` chứa các dòng dữ liệu (`<td>`).
3. **Hướng dẫn chế biến (`<ol>`)**:
   - Nằm trong `<section>` riêng có tiêu đề `<h2>`.
   - Trình bày danh sách có thứ tự với các thẻ `<li>` tuần tự từng bước.
4. **Form phản hồi (`<form>`)**:
   - Nằm trong `<section>` phản hồi bên dưới bài viết.
   - Các trường nhập liệu: Tên người gửi (`<input type="text">`), Đánh giá sao (`<input type="radio">` từ 1 đến 5 sao), Bình luận (`<textarea>`).
   - Mỗi trường đều có thẻ `<label>` liên kết chính xác bằng thuộc tính `for` và `id`.
   - Nút bấm gửi `<button type="submit">`.

---

## Cấu trúc thư mục dự án
```
mini-project-cong-thuc-nau-an-semantic/
├── recipe.html      # Trang công thức nấu ăn chuẩn Semantic
├── index.html       # Bản sao hỗ trợ xem trực tiếp
├── README.md        # Tài liệu hướng dẫn & giải thích
└── images/
    └── pho-bo-ha-noi.jpg # Hình ảnh món ăn minh họa
```
