# 3V2T
## Github công nghệ phần mềm cờ caro
***
### Yêu cầu phần mềm
#### Yêu cầu chức năng
- Kết nạp người chơi mới
  + Người chơi có thể đăng ký tài khoản mới bằng cách cung cấp thông tin cơ bản như tên, email và mật khẩu.
  + Email xác nhận sẽ được gửi đến người chơi sau khi đăng ký thành công.
- Tạo ván đấu
  + Người chơi có thể tạo ván đấu mới với các chế độ chơi như:
   * Chơi 2 người
   * Chơi với máy
- Lưu ván đấu đang chơi
  + Người chơi có thể lưu ván đấu đang chơi để tiếp tục sau.
  + Ván đấu được lưu lại sẽ bao gồm thông tin về các nước đi của cả hai người chơi.
- Tiếp tục ván đấu
  + Người chơi có thể tiếp tục ván đấu đã lưu.
- Xem thông tin người chơi
  + Người chơi có thể xem thông tin của bản thân như điểm số, số trận thắng, thua, hòa, và thứ hạng.
  + Người chơi có thể đổi tên của mình.
- Xem thứ hạng
  + Người chơi có thể xem thứ hạng của bản thân trên tổng số người chơi.
- Quản lý người chơi
  + Admin có thể thêm, xóa, sửa, cập nhật thông tin người chơi và thống kê người chơi
#### Yêu cầu phi chức năng
- Yêu cầu về hiệu năng
  + Hệ thống phải đáp ứng được nhu cầu chơi game của nhiều người cùng lúc.
  + Thời gian phản hồi của hệ thống phải nhanh chóng.
- Yêu cầu về khả năng mở rộng
  + Hệ thống phải có khả năng mở rộng để đáp ứng nhu cầu phát triển trong tương lai.
#### Kiến trúc hệ thống
- Mô hình kiến trúc
  + Hệ thống được thiết kế theo mô hình client-server.
  + Client là trình duyệt web của người dùng.
  + Server là máy chủ web cung cấp dịch vụ cho client.
- Các thành phần chính
  + Thành phần front-end
   * Trình duyệt web của người dùng
   * Các trang web cung cấp giao diện cho người dùng
  + Thành phần back-end
   * Máy chủ web
   * Các dịch vụ cung cấp cho người dùng
   * Cơ sở dữ liệu lưu trữ dữ liệu người dùng
***