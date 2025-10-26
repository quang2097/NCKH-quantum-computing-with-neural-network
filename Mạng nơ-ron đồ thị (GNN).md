## work in progress
# Mạng nơ-ron đồ thị (GNN).
Mạng Nơ-ron Đồ Thị (Graph Neural Network - GNN) là một loại mô hình học máy chuyên biệt được thiết kế để xử lý dữ liệu có cấu trúc đồ thị (graph-structured data).

Dữ liệu đồ thị bao gồm các nút (nodes/vertices) và các cạnh (edges) thể hiện mối quan hệ giữa các nút đó. Các GNN có khả năng học các biểu diễn (representations) hay embedding giàu thông tin cho mỗi nút bằng cách kết hợp:

Đặc trưng (features) của chính nút đó.

Đặc trưng của các nút lân cận (neighbors).

Cấu trúc của đồ thị (mối quan hệ giữa các nút).

Cơ chế Hoạt động Chính
Cơ chế cốt lõi của GNN là việc truyền tin (message passing) hay tổng hợp (aggregation):

Mỗi nút iteratively (lặp đi lặp lại) thu thập thông tin (tạo ra "tin nhắn") từ các nút lân cận của nó.

Thông tin thu thập được sẽ được tổng hợp (ví dụ: tính trung bình, tổng, hoặc sử dụng cơ chế chú ý) và kết hợp với đặc trưng hiện tại của nút đó để cập nhật biểu diễn mới cho nút.

Quá trình này lặp lại qua nhiều lớp, cho phép thông tin lan truyền và tương tác trên toàn bộ đồ thị, giúp mỗi nút cuối cùng có được biểu diễn mã hóa cả thuộc tính của nó và ngữ cảnh cấu trúc trong mạng.

Ứng dụng của Mạng Nơ-ron Đồ Thị
GNN rất hiệu quả trong các lĩnh vực mà mối quan hệ và sự phụ thuộc giữa các đối tượng là yếu tố then chốt, bao gồm:

Mạng xã hội: Phân loại người dùng, đề xuất bạn bè hoặc nội dung.

Hóa học và Khám phá Thuốc: Mô hình hóa các phân tử (cấu trúc nguyên tử và liên kết), dự đoán tính chất phân tử hoặc tương tác thuốc-mục tiêu.

Hệ thống đề xuất: Đề xuất sản phẩm/dịch vụ dựa trên mối quan hệ giữa người dùng và mặt hàng.

Mạng lưới giao thông: Dự đoán lưu lượng giao thông, tối ưu hóa tuyến đường.

Knowledge Graphs (Đồ thị Tri thức): Liên kết và truy vấn các sự kiện và đối tượng.

Các Loại GNN Phổ biến
Một số kiến trúc GNN tiêu biểu bao gồm:

Graph Convolutional Networks (GCNs): Sử dụng cơ chế tích chập đồ thị (graph convolution) để lan truyền và tổng hợp thông tin.

GraphSAGE: Sử dụng phương pháp lấy mẫu (sampling) và tổng hợp (aggregation) thông tin từ các nút lân cận, giúp xử lý các đồ thị lớn.

Graph Attention Networks (GATs): Áp dụng cơ chế chú ý (attention mechanism) để gán trọng số khác nhau cho các nút lân cận khi tổng hợp thông tin, cho phép mô hình học được mức độ quan trọng khác nhau của các kết nối.