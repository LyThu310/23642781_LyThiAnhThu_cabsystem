PHẦN 1: TEST SCENARIO CAB SYSTEM
TS01 – Quản lý tài khoản người dùng
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS01.01	FR01	-	Người dùng đăng ký tài khoản với thông tin hợp lệ
TS01.02	FR01	-	Người dùng đăng ký tài khoản với thông tin đã tồn tại
TS01.03	FR02	-	Người dùng đăng nhập với thông tin hợp lệ
TS01.04	FR02	-	Người dùng đăng nhập với thông tin không hợp lệ
TS01.05	FR03	-	Người dùng cập nhật thông tin cá nhân thành công
TS02 – Quản lý tài xế
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS02.01	FR04	AC14	Nhân viên vận hành xem và quản lý thông tin tài xế
TS02.02	FR05	AC05	Tài xế cập nhật trạng thái hoạt động để nhận chuyến
TS02.03	FR06	AC05	Tài xế nhận chuyến khi đang ở trạng thái Available
TS02.04	FR06	AC07	Tài xế từ chối chuyến và hệ thống tiếp tục xử lý
TS03 – Quản lý phương tiện
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS03.01	FR07	AC14	Nhân viên vận hành quản lý thông tin phương tiện
TS04 – Đặt chuyến xe
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS04.01	FR08, FR09, FR10, FR11	AC01	Khách hàng tạo chuyến xe với đầy đủ thông tin hợp lệ
TS04.02	FR08, FR09, FR10, FR11	AC02	Khách hàng tạo chuyến xe với thông tin thiếu hoặc sai
TS04.03	FR11	AC03	Khách hàng hủy chuyến khi chuyến đang ở trạng thái cho phép
TS05 – Tìm kiếm và phân công tài xế
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS05.01	FR12, FR13	AC04	Hệ thống tìm tài xế Available phù hợp với yêu cầu chuyến
TS05.02	FR12, FR13	AC06	Hệ thống phân công tài xế thành công và thông báo cho khách hàng
TS05.03	FR14, FR15	AC07	Hệ thống xử lý trường hợp không tìm được tài xế
TS06 – Theo dõi chuyến đi
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS06.01	FR16, FR17, FR18	AC08	Khách hàng theo dõi trạng thái chuyến và thông tin tài xế
TS06.02	FR23	AC08	Hệ thống cập nhật vị trí hiện tại của tài xế
TS07 – Thực hiện chuyến
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS07.01	FR19, FR20, FR21, FR22	AC09	Tài xế cập nhật trạng thái chuyến theo đúng quy trình
TS07.02	FR19-FR22	AC09	Hệ thống từ chối cập nhật trạng thái sai thứ tự
TS08 – Tính cước và thanh toán
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS08.01	FR24	AC10	Hệ thống tự động tính cước khi chuyến hoàn thành
TS08.02	FR25	AC11	Khách hàng thanh toán bằng tiền mặt
TS08.03	FR26	AC11	Khách hàng thanh toán điện tử
TS08.04	FR27, FR28	AC12	Hệ thống xử lý thanh toán điện tử thất bại
TS09 – Thông báo
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS09.01	FR29-FR33	AC16	Hệ thống gửi thông báo khi trạng thái chuyến thay đổi
TS10 – Lịch sử và đánh giá
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS10.01	FR34, FR35	AC18	Khách hàng xem lịch sử chuyến và chi phí
TS10.02	FR36	AC17	Khách hàng đánh giá tài xế sau chuyến hoàn thành
TS11 – Quản lý vận hành
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS11.01	FR37-FR43	AC13	Nhân viên vận hành quản lý thông tin khách hàng
TS11.02	FR37-FR43	AC14	Nhân viên vận hành quản lý tài xế và phương tiện
TS11.03	FR40-FR43	AC15	Nhân viên vận hành giám sát và xử lý chuyến lỗi
TS12 – Phân quyền và báo cáo
Scenario ID	FR	AC	Ngữ cảnh kiểm thử
TS12.01	FR44, FR45	AC19	Người dùng truy cập chức năng theo quyền được cấp
TS12.02	FR46-FR50	-	Quản lý xem báo cáo hoạt động hệ thống
TS12.03	-	AC20	Hệ thống hỗ trợ mở rộng thêm dịch vụ mới
