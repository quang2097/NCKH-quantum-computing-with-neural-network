# Thông tin cần biết.
* [giới thiệu IDS](./giới%20thiệu%20IDS.md)
* [AI là gì](./giới%20thiệu%20về%20AI.md) (cơ bản)

# AI trong hệ thống IDS (Intrusion detection system).
* Sử dụng trí tuệ nhân tạo (AI) và mô hình học sâu (deep learning) trong những hệ thống IDS đã thay đổi cốt lõi của những hệ thống IDS từ việc tìm kiếm những nguy cơ đã được biết đến tới việc xác nhận những cuộc tấn công phức tạp chưa được biết đến.

## Vai trò của AI trong IDS.
- AI được sử dụng cho việc đo lường thông tin, lượng giao thông truy cập và hành vi người dùng để xác nhận một trạng thái "bình thường" để từ đó tìm kiếm những sự thay đổi lạ thường trong hệ thống.
- Tìm chữ ký và sử dụng sai lệch.
- Phân tích hành vi.

## Ưu điểm của áp dụng AI so với phương pháp truyền thống.
- Phát hiện không-ngày: Khả năng tìm lạ thường của AI cho phép sự xác nhận của những cuộc tấn công chưa từng được thấy bao giờ.
- Ít thông báo dương tính sai lệch hơn so với những hệ thống IDS truyền thống.
- Phân tích thời gian thực: AI có thể phân tích và xử lý thông tin nhanh hơn nhiều lần so với con người, cho phép sự phát hiện và xử lý gần như tức thời.
- Khả năng tiến hóa: Những mô hình AI có thể liên tục học hỏi và phát triển khi mối đe dọa phát triển, giữ vững độ hiệu quả mà không cần đến sự duy trì liên tục bởi con người.
- Khả năng tự động thực thi: Những hệ thống IDS sử dụng AI có thể tự động thi hành những quá trình được lập sẵn để xử lý cuộc tấn công đã được phát hiện bằng cách chặn địa chỉ IP độc hại hoặc cách ly một host đã bị xâm lược. Tối thiểu hóa thiệt hại được gây ra.

## Nhược điểm của áp dụng AI so với phương pháp truyền thống.
- Sự cần thiết của một lượng lớn dữ liệu chất lượng tốt cho việc huấn luyện mô hình AI: Dữ liệu sai lệch hoặc chất lượng kém có thể dẫn đến mô hình AI có độ hiệu quả, độ chính xác thấp hoặc không thể dự đoán những cuộc tấn công nhất định.
- Những người tấn công có thể đưa vào AI dữ liệu độc hại khi trong quá trình huấn luyện. Hoặc đưa ra những hướng dẫn được tạo ra để tránh sự phát hiện của AI.
- Phức tạp và khó giải thích: AI có thể được coi là hộp đen chứa thông tin trong dạng con người không thể hiểu được khiến cho độ phức tạp trong việc xác nhận và sửa lỗi do AI gây ra khó khăn và phức tạp.
- Sự đòi hỏi tài nguyên máy tính: Sự huấn luyện của những mô hình AI đòi hỏi một lượng lớn tài nguyên máy tính (GPU hoặc graphics processing unit) làm tăng chi phí một cách đáng kể.

## Phương pháp đề ra để áp dụng AI để tối ưu ưu điểm và tối thiểu nhược điểm.