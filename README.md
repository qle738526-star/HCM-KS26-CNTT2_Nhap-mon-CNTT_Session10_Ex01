# HCM-KS26-CNTT2_Nhap-mon-CNTT_Session10_Ex01

## Phần 1: Phân tích các lỗi cú pháp

Đoạn mã của sinh viên mắc 3 lỗi cơ bản sau khiến kết quả render bị lộn xộn:

1.  **Lỗi phân cấp tiêu đề (Heading):** Nhảy bậc từ H1 (`#`) xuống thẳng H3 (`###`). Theo chuẩn, tiêu đề phải giảm dần theo thứ bậc logic (H1 -> H2 -> H3) để tạo cấu trúc rõ ràng. H1 cũng chỉ nên xuất hiện 1 lần đại diện cho tên bài viết.
2.  **Lỗi cú pháp chèn ảnh (Image):** Đoạn `[Logo Dự án] (https://greentech.vn/logo.png)` bị thiếu dấu chấm than `!` ở đầu và bị thừa một khoảng trắng giữa dấu `]` và `(`. Vì vậy, trình biên dịch (như StackEdit) sẽ hiểu nhầm đây là một siêu liên kết (Link) bị viết sai cú pháp thay vì hiển thị hình ảnh.
3.  **Lỗi cú pháp in đậm (Emphasis):** Việc chỉ dùng 1 dấu sao (ví dụ: `*Rất quan trọng*`) sẽ làm chữ bị **in nghiêng (Italic)**. Để in đậm (Bold), bắt buộc phải dùng 2 dấu sao bọc quanh từ khóa.

## Phần 2: Đoạn mã hoàn thiện (Corrected Code)

Dưới đây là đoạn mã chuẩn đã sửa lỗi, đảm bảo hiển thị đúng ảnh logo, cấu trúc tiêu đề hợp lý (H1 -> H2) và chữ in đậm:

![Logo Dự án](https://greentech.vn/logo.png)

# Lợi ích của rau sạch

## Danh sách các loại rau

**Rất quan trọng**
