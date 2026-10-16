# Bài 3 : Giảm chi phí vận hành Chatbot AI
## I. Phân tích bài toán
## Phần 1. Phân tích bài toán

1. Cơ chế chia nhỏ Token

AI không đọc văn bản giống con người mà chia nội dung thành các đơn vị nhỏ gọi là Token. Mỗi Token có thể là một từ, một phần của từ hoặc ký tự. Số Token ảnh hưởng đến lượng dữ liệu AI cần xử lý.

2. Vì sao Markdown giúp tiết kiệm Token?

Markdown sử dụng cú pháp ngắn gọn để định dạng văn bản, trong khi HTML cần nhiều thẻ mở và thẻ đóng hơn. Vì vậy, khi biểu diễn cùng một nội dung, Markdown thường sử dụng ít ký tự định dạng hơn, giúp giảm số Token đầu vào.

Ví dụ:

-   Markdown: `**Cây lúa**`
    
-   HTML: `<b>Cây lúa</b>`
    

Cả hai đều giúp chữ “Cây lúa” in đậm, nhưng Markdown ngắn gọn hơn.

3. Lợi ích đối với AI 

Khi số Token giảm, AI có ít dữ liệu cần xử lý hơn, từ đó có thể giảm chi phí sử dụng API và thời gian phản hồi. Tuy nhiên, tốc độ còn phụ thuộc vào mô hình AI và hệ thống xử lý.

4. Áp dụng cho GreenTech

GreenTech nên ưu tiên Markdown để tạo câu trả lời hướng dẫn nông dân vì cú pháp gọn, dễ đọc và có thể tiết kiệm Token. HTML chỉ nên sử dụng khi cần định dạng giao diện website phức tạp.
## II. So sánh & Đánh giá
| Tiêu Chí | Markdown | HTML |
|--|--|--|
| Cú Pháp | Ngắn gọn | Dài Hơn |
| Token | Thường ít hơn | Thường nhiều hơn |
| Dễ đọc | Dễ đọc, dễ sửa | Nhiều thẻ nên khó đọc hơn |
| Ứng dụng | Viết tài liệu,trả lời AI | Thiết kế giao diện web |
#### Giải pháp tối ưu cho GreenTech

Nên chọn Markdown làm định dạng nội dung chính.

**Lý do:**

-   Tiết kiệm Token: Cú pháp ngắn gọn, giảm lượng dữ liệu định dạng cần xử lý.
    
-   Dễ hiểu: Có thể trình bày hướng dẫn trồng trọt bằng tiêu đề, danh sách và chữ in đậm để nông dân dễ theo dõi.
    
-   Dễ bảo trì: Nhân viên kỹ thuật dễ cập nhật tài liệu và kiến thức nông nghiệp.
    
-   Kết hợp HTML khi cần: Nếu cần xây dựng giao diện website phức tạp, GreenTech có thể chuyển Markdown sang HTML để hiển thị.
