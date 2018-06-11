1.3 Ví dụ mẫu về đặc tả các smart contracts bằng linear logic
1.3.1 Mô tả một ngữ cảnh đấu giá online cho smart contract (Bài toán 2.1 )
Mỗi một lần giao dịch đấu giá cần có sự xuất hiện của cả hai bên: bên cung cấp sản phẩm
hàng hóa và bên tham gia đấu giá. 
Có nhiều bất lợi xảy ra ở đây. 
Ví dụ: có nhiều người muốn tham gia phiên đấu giá nhưng vì lý do cá nhân, hoặc địa điểm đấu giá quá xa nên không thể
đến tham gia đấu giá hoặc người đấu giá tung giá ảo. Điều này sẽ được giải quyết dễ dàng khi giữa hai bên có sự thiết
lập thông qua một hợp đồng thông minh. Tình huống cụ thể như sau:
“Vào 15:15 Ngày 31/12/2018 sẽ mở 1 phiên đấu giá tại Mỹ, nhưng có nhiều người ở các nước khác. Khi đó, những người này
không thể di chuyển đến tận nơi để tham dự phiên đấu giá. Ban tổ chức sẽ mở phiên đấu giá online. Mỗi món hàng được đem
đi đấu giá sẽ có một giá sàn. Mọi người muốn tham gia phiên đấu giá online này phải đăng ký trước thời hạn xảy ra một ngày
(để xác thực thông tin) đấu giá và được xác nhận đủ điều kiện (Có tiền từ giá sàn trở lên). Nếu một người muốn nâng giá,
hệ thống sẽ kiểm gia số tiền thực người đó đang sở hữu (để tránh tình trạng hô giá ảo) nếu hợp lệ thì hệ thống sẽ nâng giá
cho món hàng. Kết thúc phiên đấu giá, hệ thống sẽ vận chuyển món hàng đến địa chỉ của người đấu giá thành công. Khi đó đồng
thời sẽ tiến hành trừ tiền trong tài khoản của người đấu giá và chuyển số tiền đó vào tài khoản của
bên đã đưa ra đấu giá.”

1.3.2 Mô tả một ngữ cảnh đấu giá online dưới dạng các điều khoản (articles) (Bài toán 2.2 )
Gọi bên cung cấp sản phẩm đấu giá là bên A, bên tham gia đấu giá là bên B
Article 1. Bên A gửi tiền thuê nhà 3 tháng đến smart contract trước 8h00 AM ngày
28/04/3018. Số tiền sẽ bị smart contract giữ lại.
• Article 2. Bên B gửi mã code cho smart contract trước 8h00 ngày 28/04/2018 và bị giữ lại.
• Article 3. Đến 8h00 ngày 28/04/2018 smart contract chuyển mã khóa cho người thuê nhà
và tiền đến chủ căn hộ.
• Article 4. 8h00 AM ngày 28/04/3018, Bên A gửi tiền rồi nhưng bên B vẫn không gửi mã
khóa thì Bên A sẽ nhận lại được toàn bộ tiền.
• Article 5. 8h00 AM ngày 28/04/3018, Bên A chưa gửi tiền trong khi bên B đã gửi mã khóa
thì thì mã khóa sẽ bị hủy và không gửi mã khóa về bên A.
……………………….
Bài toán 3. 
1.3.3 Đặc tả ngữ cảnh đấu giá online bằng linear logic
………………………………….
Bài toán 4. 
1.3.4 Dùng mã giả để xây dựng một smart contract cho ngữ cảnh đấu giá online
