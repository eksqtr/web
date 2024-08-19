---
title: "Client Commands"
description: Danh sách tất cả các lệnh của Client.
---

## Commands

| Lệnh           | Mô tả                                                                                                                                                                                                                                                                                                                                                                  |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /quit (/q)     | Lệnh dùng để thoát khỏi trò chơi, bạn cũng có thể /q để thoát game tựa như /quit.                                                                                                                                                                                                                                                                                      |
| /save          | /save là lệnh được sử dụng rất nhiều và có lẽ nó là lệnh hữu ích nhất. Khi bạn /save ngay lập tức vị trí hiện tại của bạn sẽ được lưu vào savedpositions.txt trong thư mục Document của bạn, bạn có thể dụng nó với rất nhiều mục đích.                                                                                                                                |
| /rs            | /rs (Raw Save) giống như /save, nhưng nó chỉ lưu vị trí và góc độ xoay hiện tại của bạn vào rawpositions.txt trong thư mục Document của bạn. Lệnh này không lấy thông tin bổ sung như class, vũ khí của bạn.                                                                                                                                                           |
| /interior      | Cũng quan trọng như lệnh /save, nhưng lệnh này sẽ lấy interior hiện tại của bạn và hiện lên chatlog.                                                                                                                                                                                                                                                                   |
| /vw            | Cũng quan trọng như lệnh /save, nhưng lệnh này sẽ lấy virtual world hiện tại của bạn và hiện lên chatlog.                                                                                                                                                                                                                                                              |
| /fpslimit      | Lệnh này đặt giới hạn FPS (Khung hình trên giây) cho trò chơi của bạn. Giới hạn càng cao thì những chuyển động trong trò chơi của bạn càng mượt mà. Nó sẽ không có tác dụng khi 'frame limiter' bị tắt trong cài đặt 'display setting'. Có thể giới hạn từ 20-90 và mặc định là 50. Nó sẽ điều chỉnh 'fpslimit' trong sa-mp.cfg.                                       |
| /pagesize      | /pagesize được sử dụng để chọn số lượng dòng chat được phép hiển thị. Có thể đặt từ 10 đến 20 dòng. Pagesize mặc định là 10. Nó sẽ điều chỉnh 'pagesize' trong sa-mp.cfg.                                                                                                                                                                                              |
| /headmove      | Lệnh này điều khiển việc đầu của người chơi có di chuyển theo hướng họ nhìn hay không, tuy nhiên nó được xử lý cục bộ nên những người chơi khác vẫn sẽ thấy đầu bạn di chuyển. Nó sẽ điều chỉnh 'disableheadmove' trong sa-mp.cfg.                                                                                                                                     |
| /timestamp     | This command will show/hide a time next to all messages in the chatbox. The time that is displayed is your computer's time, not the server time. This sets the sa-mp.cfg 'timestamp' option.                                                                                                                                                                           |
| /dl            | DL là viết tắt của debug labels. Lệnh này bật/tắt debug labels trên các phương tiện, hiển thị ID phương tiện, model, health, xem phương tiện có được tải trước không, khoảng cách từ người chơi, trailer, số ghế có sẵn, vị trí hiện tại và vị trí spawn.                                                                                                              |
| /nametagstatus | Khi được bật (mặc định là bật), người chơi sẽ thấy một biểu tượng đồng hồ nhỏ bên cạnh nametag của những người chơi AFK. Điều này bao gồm việc thu nhỏ (alt-tab), menu tạm dừng (ESC), mất kết nối (crash/timeout) và khi chụp màn hình làm đông game trên 3 giây. Nó sẽ điều chỉnh 'nonametagstatus' trong sa-mp.cfg.                                                 |
| /mem           | Hiển thị số lượng bộ nhớ hiện tại đang sử dụng. (Mặc dù thường chỉ in ra 128 MB.)                                                                                                                                                                                                                                                                                      |
| /audiomsg      | Bật/tắt thông báo in ra khi một URL được phát trực tiếp đến client. Nó sẽ điều chỉnh 'audiomsgoff' trong sa-mp.cfg.                                                                                                                                                                                                                                                    |
| /fontsize      | Thay đổi kích thước phông chữ của UI (chat, hộp thoại, v.v.). Kích thước phông chữ hợp lệ là từ -3 đến 5.                                                                                                                                                                                                                                                              |
| /ctd           | Lệnh này được thêm vào trong SA-MP 0.3.7 RC2. Nó bật chế độ gỡ lỗi client của mục tiêu camera của người chơi.                                                                                                                                                                                                                                                          |
| /rcon          | Liên quan nhiều hơn đến máy chủ hơn là client. Lệnh này được sử dụng để thực thi các lệnh RCON. RCON là hệ thống quản trị tích hợp. RCON là viết tắt của [Remote Control](../server/ControllingServer#using-rcon).                                                                                                                                                     |
| /hudscalefix   | Lệnh này được thêm vào trong SA-MP 0.3.7 R3. Bật/tắt sửa lỗi tỷ lệ radar, để radar của trò chơi có tỷ lệ tốt hơn trong các độ phân giải màn hình rộng (tức là không còn 'egg of finding'). Lệnh này thiết lập tùy chọn 'nohudscale' trong sa-mp.cfg.                                                                                                                   |

## File sa-mp.cfg

| Option          | Mô tả                                                                                                                                                                                        |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| pagesize        | Đọc /pagesize.                                                                                                                                                                               |
| fpslimit        | Đọc /fpslimit.                                                                                                                                                                               |
| disableheadmove | Đọc /headmove.                                                                                                                                                                               |
| timestamp       | Đọc /timestamp.                                                                                                                                                                              |
| ime             | Điều này kiểm soát việc cửa sổ chat có hỗ trợ chỉnh sửa văn bản và chuyển đổi ngôn ngữ hay không. 1 là bật IME, 0 là tắt.                                                                    |
| audiomsgoff     | Đọc /audiomsg.                                                                                                                                                                               |
| multicore       | Bật/tắt việc client SA-MP sử dụng nhiều lõi CPU khi chạy. Mặc định là 1 (SỬ DỤNG nhiều lõi CPU). Đặt thành 0 nếu bạn gặp vấn đề với chuột.                                                   |
| directmode      | Điều này cho phép người chơi có vấn đề về việc vẽ văn bản chat sử dụng chế độ kết xuất văn bản trực tiếp lên màn hình. 0 để tắt, 1 để bật.                                                   |
| audioproxyoff   | Nếu tùy chọn này được đặt thành 1 và có một máy chủ proxy được đặt trong Tùy chọn Internet của Windows, proxy sẽ không được sử dụng khi phát âm thanh trong SA-MP.                           |
| nonametagstatus | Đọc /nametagstatus.                                                                                                                                                                          |
| fontface        | Cho phép bạn thay đổi phông chữ của chat, hộp thoại và bảng điểm. Ví dụ: fontface="Comic Sans MS". Không được hỗ trợ chính thức và có thể gây ra lỗi xung đột.                               |
| fontweight      | Tùy chọn này bật/tắt việc phông chữ chat của bạn có đậm hay không. 0 = ĐẬM (mặc định) và 1 = BÌNH THƯỜNG.                                                                                    |
| nohudscale      | Tùy chọn này được thêm vào trong 0.3.7 R3. Xem /hudscalefix.                                                                                                                                 |