Giới thiệu về Posman:
Postman là một công cụ mạnh mẽ và phổ biến được sử dụng rộng rãi trong việc phát triển và kiểm thử API (Application Programming Interface). Được ra đời vào năm 2012, Postman đã nhanh chóng trở thành một trong những lựa chọn hàng đầu của các nhà phát triển, kiểm thử viên và các chuyên gia công nghệ thông tin trên toàn thế giới.


Postman API Testing
API Student được thiết kế để quản lý thông tin sinh viên. Nó cung cấp các chức năng như lấy danh sách sinh viên, tạo mới, cập nhật và xóa sinh viên khỏi hệ thống. API có địa chỉ tại: https://6639dadf1ae792804bed06b5.mockapi.io/api/v1/student.

1. Kiểm thử phương thức GET để lấy danh sách sinh viên
  ![Screenshot 2024-05-19 192449](https://github.com/kuonggaa/btposman/assets/96900121/0b57c37d-6016-4cf2-9922-24c82dd311f4)
 
Mục đích:
Đảm bảo rằng API trả về danh sách sinh viên chính xác.

Kịch bản kiểm thử:
Sử dụng phương thức GET để truy xuất danh sách sinh viên từ API.

Kết quả mong đợi:
API trả về danh sách sinh viên đúng như mong đợi.

2. Kiểm thử phương thức POST để tạo mới một sinh viên
   ![Screenshot 2024-05-19 193311](https://github.com/kuonggaa/btposman/assets/96900121/adf59f7f-a061-4578-ac2c-ee384e16a05e)

Mục đích:
Xác minh khả năng tạo mới sinh viên của API.

Kịch bản kiểm thử:
Gửi một yêu cầu POST với dữ liệu sinh viên mới để tạo một bản ghi sinh viên mới.

Kết quả mong đợi:
API trả về thông tin của sinh viên vừa được thêm mới.

3. Kiểm thử phương thức GET để lấy thông tin của một sinh viên
   ![Screenshot 2024-05-19 193407](https://github.com/kuonggaa/btposman/assets/96900121/e94a2cbe-05a8-4bd2-8fcd-921863eca8ee)
Mục đích:

Đảm bảo API có thể trả về chi tiết của một sinh viên cụ thể dựa trên ID.

Kịch bản kiểm thử:
Sử dụng phương thức GET với một ID cụ thể để truy xuất thông tin của sinh viên đó.

Kết quả mong đợi:
API trả về thông tin chi tiết của sinh viên dựa trên ID cung cấp.

4. Kiểm thử phương thức PUT để cập nhật thông tin sinh viên
   ![Screenshot 2024-05-19 193513](https://github.com/kuonggaa/btposman/assets/96900121/e8dc3563-c301-446a-aac2-30d3ae165c41)

Mục đích:
Xác minh khả năng cập nhật thông tin sinh viên của API.

Kịch bản kiểm thử:
Gửi một yêu cầu PUT với dữ liệu cập nhật để thay đổi thông tin của một sinh viên.

Kết quả mong đợi:
API trả về thông tin mới của sinh viên sau khi cập nhật.

5. Kiểm thử phương thức DELETE để xóa sinh viên
   ![Screenshot 2024-05-19 193550](https://github.com/kuonggaa/btposman/assets/96900121/dfc26e01-2e98-41b8-9fcb-bb64b3d71f43)

Mục đích:
Xác minh khả năng xóa sinh viên của API.
Kịch bản kiểm thử:
Gửi một yêu cầu DELETE để xóa một sinh viên khỏi hệ thống.

Kết quả mong đợi:
API trả về thông tin của sinh viên vừa bị xóa khỏi hệ thống.


các thao tác:

![Screenshot 2024-05-19 193838](https://github.com/kuonggaa/btposman/assets/96900121/8bb0f449-9d19-4557-b316-37dd41548c53)

