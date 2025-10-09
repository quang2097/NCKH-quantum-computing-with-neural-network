# Lời nói đầu: những nội dung ghi sau đây là sự tổng hợp tổng quát về cách ứng dụng và hoạt động của LLM. Để tìm hiểu sau hơn thì mỗi phần sẽ được chia ra làm các file .md khác nhau. Để viết chuyên sâu hơn về phương pháp thực hiện, kiến thức cần tìm hiểu và kết quả của việc thử nghiệm áp dụng.

## Tổng hợp nội dung nghiên cứu khoa học.
-	Sử dụng mạng nơ-ron để dự đoán tính chất phân tử vật liệu qua dự đoán và xu hướng. [link](https://arxiv.org/abs/2405.05205)
//Bình luận: một cách sử dụng đã được áp dụng ở bên mỹ để dự đoán tính chất của những chuỗi protein khác nhau trong lĩnh vực sinh học/y dược.
//Bình luận 2: chưa hiểu đủ về mạng nơ ron để áp dụng trong công dụng này. (cụ thể là về vật liệu do không biết cần cung cấp dữ liệu gì để huấn luyện LLM cho chức năng này. Do nếu cung cấp thông tin không liên quan đến kết quả cần tìm thì đáp án LLM suy luận được sẽ luôn sai)
-	Áp dụng hệ thống kết hợp mạng nơ-ron truyền thống và lượng tử cho việc phân loại những khối u trong lĩnh vực y học. [link](https://arxiv.org/abs/2310.11353)
//Bình luận: có lẽ dễ hơn so với việc sử dụng LLM để dự đoán vật liệu. Do mình biết rõ đặc điểm của những khối u qua dữ liệu scan, và chức năng là để phân loại và không phải dự đoán.

->  KHÔNG LIÊN QUAN ĐẾN NỘI DUNG CHÍNH ĐÓ CHÍNH LÀ TẠO RA MỘT HỆ THỐNG SỬ DỤNG MẠNG NƠ RON TRUYỀN THỐNG VỚI QUANTUM MACHINE LEARNING ĐỂ PHÁT HIỆN KHẢ NĂNG TẤN CÔNG TRONG MẠNG (LỖ HỔNG TRONG PHẦN MỀM TẠO NÊN MỐI NGUY AN NINH.)

//Theo [Quang] nghĩ thì có thể chia ra thành 2 phương pháp để dự đoán: 
*  	Cho chương trình đọc qua những code bases khác nhau và cho biết trước những lỗ hổng để cho chương trình học qua pattern recognition và dự đoán qua xác suất (ví dụ là nếu những chương trình có mô típ giống nhau (trong chương trình có lỗ hổng luôn có dòng mã nhất định)).
-	Nhược điểm: Có nhiều ngoại lệ, định nghĩa của con người về lỗ hổng có lẽ quá phức tạp đồng thời còn chứa khiếm khuyết nên khó để có thể áp dụng hiệu quả.
*	Cho chương trình thực hiện tấn công hệ thống để nhận biết qua xác suất thành công.
//Nhận xét: có lẽ là hơi giống chương trình truyền thống và không phải cách áp dụng machine learning.
