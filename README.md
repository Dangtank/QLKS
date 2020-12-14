# QLKS


# GOALS
-	Phần mềm dạng ứng dụng cho máy tính cá nhân, chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lí khách sạn được sử dụng
- Hoạt động tốt và ổn định trên mọi loại hệ điều hành
-	Nhân viên bán hàng có thể tìm phòng trống và đặt phòng theo yêu cầu của khách.
-	Nhân viên lễ tân có thể tìm phòng trống theo yêu cầu trực tiếp của khách, checkin cho khách đã đặt phòng hoặc đặt phòng trực tiếp, checkout cho khách và in hóa đơn thanh toán cho khách
-	Quản lí có thể: thêm/sửa/xóa thông tin phòng, xem các báo cáo doanh thu theo thời gian/theo phòng/theo loại phòng, xem báo cáo tỉ lệ phòng trống theo thời gian/theo phòng/theo loại phòng, xem báo cáo khách hàng đặt nhiều theo thời gian/theo nguồn gốc khách hàng.
- Mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...
- Mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau.
- Mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau.
- Tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể.
- Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.
- Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.

# Business Objectives 
- Xây dựng trang web quản lý hệ thống khách sạn, cơ sở dữ liệu có chứa thông tin của khách sạn, nhân viên và chức vụ của họ
- Phân quyền cho nhân viên bán hàng, hoàn thành yêu cầu tìm phòng trống, đặt/hủy phòng
- Phân quyền đối với nhân viến bán hàng; hoàn thành yêu cầu checkin/checkout thanh toán
- Phân quyền đối với quản lý; hoàn thành yêu cầu tạo/xem báo cáo, CRUD thông tin phòng 
- Người quản lý có thể kế thừ toàn bộ các tính năng của nhân viên bán hàng và nhân viên tiếp tân
- Nhân viên tiếp tân được hưởng các tính năng của người bán hàng 
- Đáp ứng đầy đủ các yêu cầu
- Không để chậm tiến độ, hạn trong 2 tháng phải hoàn thành
- Đảm bảo bảo mật và độ chính xác của thông tin
- Liên tục cập nhật cho phù hợp môi trường áp dụng
