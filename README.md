# learn-devops
  OSI Model
  OSI Model : Mô hình OSI (Open systems interconnection) mô tả cách mà hệ thống mạng hoạt động. Có 7 tầng
-	Tầng 7: Application (Gần gũi với người dung, cùng cấp dịch vụ mạng trức tiếp cho ứng dụng ví dụ http, ftp)
-	Tầng 6: Presentation (Định dạng dữ liệu, mã hóa, giải nén)
-	Tầng 5: Session (Quản lý và duy trì phiên giao tiếp, thiết lập, quản lý và kết thúc kết nối)
-	Tầng 4: Transport (Cung cấp việc truyền dữ liệu từ ứng dụng trên một máy đến ứng dụng trên máy khác, đảm bảo dữ liệu tin cậy . Ví dụ TCP, UPD)
-	Tầng 3: Network (Định tuyến dữ liệu mạng, đảm bảo dữ liệu đến đúng địa chỉ. Ví dụ IP: Internet Protocol)
-	Tầng 2: Data Link (Đảm bảo dữ liệu đc truyền từ node này đến node khác trong cùng 1 mạng. Bao gồm phát hiện và sữa lỗi cơ bản. Ví dụ Ethernet, Wifi)
-	Tâng 1: Physical (Dữ liệu đc mã hóa thành dạng bit, chịu trách nhiệm kết nối vật lý giữa các thiết bị như cáp quang và các giao thức truyền dữ liệu vật lý)
  Chức năng:
-	Tiêu chuẩn hóa cách các thiết bị và hệ thống mạng giao tiếp với nhau
-	Cấu trúc phân tầng giúp phát triển tập trung từng phần riêng
  TCP/IP
  OSI Model: Được dùng để truyền dữ liệu qua internet. Là mô hình phổ biến trên internet và đơn giản hơn OSI
  Có 4 tầng
-	Tầng 1: Network interface
•	Tương ứng với Physical và Data link ở OSI
•	Chịu trách nhiệm truyền tải dữ liệu qua kết nối vật lý (Ethernet, Wifi)
-	Tầng 2: Internet
•	Tương ứng với network OSI
•	Định tuyến dữ liệu trên internet và chịu trách nhiệm cho địa chỉ IP
-	Tầng 3: Transport
•	Tương ứng với tầng Transport của mô hình OSI.
•	Truyền dữ liệu giữa các ứng dụng khác nhau. TCP, UDP
-	Tầng 4:
•	Tương ứng với Session, presentation, Application OSI
•	Cung cấp dịch vụ mạng trực tiếp cho user như HTTP, FTP
  Chức năng:
-	Là mô hình cơ bản cho internet và các mạng dựa trên giao thức IP
-	Phù hợp với internet hiện nay



