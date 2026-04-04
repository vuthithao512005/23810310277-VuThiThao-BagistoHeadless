**Phần 1:**

<img width="1857" height="1106" alt="Screenshot 2026-04-03 155822" src="https://github.com/user-attachments/assets/8da39fd0-50a2-4701-965f-d0658291ba2f" />
**Phần 2:**

<img width="1902" height="1054" alt="image" src="https://github.com/user-attachments/assets/a277e173-d8ed-4428-9302-7d6629260fe4" />

**#Phần 3:**

<img width="1919" height="1138" alt="Screenshot 2026-04-03 221804" src="https://github.com/user-attachments/assets/fd111678-b5ac-4b41-abad-a744cf65fe2b" />

**Phần IV:**
1. So sánh lưu lượng dữ liệu (Payload):
Khi dùng REST API để lấy danh sách sản phẩm, tất cả dữ liệu của từng sản phẩm (tên, giá, mô tả, hình ảnh, thuộc tính khác…) đều được trả về, dẫn đến payload lớn, tốn băng thông và thời gian tải. Trong khi đó, GraphQL cho phép chỉ chọn những trường cần thiết (ví dụ tên, giá, hình ảnh), nên payload nhỏ hơn, tải nhanh hơn và giảm tài nguyên mạng.

2. Thay đổi giá sản phẩm qua Headless API:
Để thay đổi giá sản phẩm, phải sử dụng Mutation trong GraphQL vì Mutation cho phép thay đổi dữ liệu trên server, như cập nhật giá, tạo, xóa sản phẩm. Query chỉ dùng để truy xuất dữ liệu mà không sửa đổi gì.
