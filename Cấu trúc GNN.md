# Cấu trúc GNN.
## Node
Vai trò của Node trong Đồ thịTrong một đồ thị:Đại diện Thực thể: Node đại diện cho một đối tượng, một sự vật, hoặc một thực thể cụ thể trong hệ thống đang được mô hình hóa (ví dụ: một người dùng trong mạng xã hội, một nguyên tử trong phân tử, một trang web).Điểm Tương tác: Node là trung tâm của quá trình Truyền tin (Message Passing), nơi dữ liệu được tổng hợp từ các lân cận để cập nhật thông tin của chính nó.
## Edge
Vai trò Cấu trúc Edge xác định cách các nút được kết nối, điều này ảnh hưởng trực tiếp đến việc học của mô hình:Xác định Lân cận: Đối với mỗi nút, các cạnh xác định tập hợp các nút lân cận, nơi $v$ sẽ thu thập thông tin.Định hướng và Trọng số:Đồ thị vô hướng: Nếu cạnh giữa A và B là vô hướng, thông tin có thể truyền theo cả hai chiều (A -> B và B -> A).Đồ thị có hướng: Nếu cạnh là có hướng (A -> B), thông tin chỉ truyền từ A đến B.Trọng số: Cạnh có thể có trọng số để thể hiện độ mạnh hay tần suất của mối quan hệ (ví dụ: số lần tương tác giữa hai người dùng).
## Message passing.
Message Passing (Truyền tin) là cơ chế hoạt động cốt lõi của Mạng Nơ-ron Đồ Thị (GNN), cho phép các nút (nodes) học các biểu diễn (embeddings) giàu ngữ cảnh bằng cách trao đổi và tổng hợp thông tin từ các nút lân cận.
Cơ chế này lặp lại qua nhiều lớp GNN, giúp thông tin từ các nút xa hơn lan truyền đến nút mục tiêu.
## Embedding.
Định nghĩa: Embedding là một vector dày đặc (dense vector) có chiều thấp, được học để ánh xạ (map) một nút (hoặc đồ thị) từ không gian đặc trưng ban đầu (thường là thưa thớt) sang một không gian mới, nơi khoảng cách giữa các vector phản ánh sự tương đồng về ngữ cảnh cấu trúc và thuộc tính của chúng.
Mã hóa Ngữ cảnh: Khác với embedding truyền thống, embedding của GNN không chỉ mã hóa thuộc tính của nút mà còn mã hóa thông tin cấu trúc do quá trình Message Passing mang lại (tức là thông tin từ các nút lân cận).