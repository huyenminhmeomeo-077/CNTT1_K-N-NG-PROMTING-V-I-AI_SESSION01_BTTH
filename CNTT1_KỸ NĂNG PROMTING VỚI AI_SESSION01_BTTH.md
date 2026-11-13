**2\. Yêu cầu thực hiện chi tiết**

Sử dụng kỹ thuật chia nhỏ prompt (Prompt Chaining) để viết cẩm nang theo từng phần:

\- Phần 1: Cách AI đoán từ (LLM hoạt động thế nào).

+ AI đoán chữ theo xác suất dựa vào những dòng code, có bộ nhớ ngắn hạn

\- Phần 2: 3 cách nhận diện ảo giác của AI.

+ AI gợi ý cho hàm những khi chạy thì báo lỗi   
+ code chạy mượt nhưng sai kết quả   
+ AI bịa lí do khi bị hỏi ngược 

\- Phần 3: Cấu trúc prompt mẫu tối ưu bằng khung CREATE.

+ C : Đóng vai trợ giảng   
+ R : Code tính tổng đang bị sai kết quả hãy tìm hiểu nguyên nhân  
+ E : nhập \[2,3,5\] phải in ra 10 nhưng của tôi lại in ra \[9\]  
+ A : Chỉ ra lỗi sai và không được tự tiện sửa   
+ T : Trả lời ngắn gọn bằng gạch đầu dòng  
+ E : Đang dùng ngôn ngữ C 

