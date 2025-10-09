# Giới thiệu IoT.
- IoT hoặc (internet of things) bao quát những thiết bị điện tử vật lí mà có những cảm biến, phần mềm và những công nghệ khác cho phép chúng kết nối qua mạng và trao đổi thông tin với nhau qua mạng đó.

## Tình trạng an ninh của những thiết bị IoT hiện thời.
* An ninh thấp (phổ biến).
* An ninh trung bình (đang cải thiện).
* An ninh cao (phần lớn xuất hiện tại những cơ sở hạ tầng quan trọng như quân sự và y tế).

### Nguyên nhân.
- Khả năng xác thực yếu: Những thiết bị IoT thường được [hardcoded](https://rdsic.edu.vn/blog/blog-4/hardcode-la-gi-vi-cb.html#:~:text=Trong%20l%E1%BA%ADp%20tr%C3%ACnh%2C%20%E2%80%9Chardcode%E2%80%9D%20%28hay%20%E2%80%9Chard%E2%80%91coding%E2%80%9D%29%20l%C3%A0%20vi%E1%BB%87c,bi%E1%BA%BFn%20m%C3%B4i%20tr%C6%B0%E1%BB%9Dng%20ho%E1%BA%B7c%20input%20th%E1%BB%9Di%20gian%20ch%E1%BA%A1y.) và thường sử dụng default username và default password nên dễ bị đoán và xâm nhập.
- Thiếu khả năng mã hóa: Nhiều thiết bị IoT truyền thông tin quan trọng qua mạng không sử dụng mã hóa đầu đuôi (end to end encryption) hoặc sử dụng những phương pháp mã hóa yếu/lỗi thời cho phép thông tin được đọc bởi bên thứ ba.
- Cập nhật phần cứng, phần mềm không bảo mật: Những nhà sản suất thường thất bại trong việc cập nhật kịp thời để vá lỗi về bảo mật. Và chính quá trình cập nhật cũng có thể không bảo mật, cho phép bên thứ ba đẩy những gói hàng không mong muốn vào thiết bị.
- Ràng buộc tài nguyên: Nhiều thiết bị được sản suất cho nhỏ, rẻ và năng lượng thấp. Điều này giới hạn bộ nhớ và khả năng an ninh của những thiết bị đó như là tường lửa và những hệ thống mã hóa phức tạp.
- Vòng đời của thiết bị: Những thiết bị IoT thường được sử dụng lâu sau khi nhà sản suất đã dừng đưa ra cập nhật an ninh. Để lại cho những thiết bị đó những điểm yếu bảo mật mãi mãi.